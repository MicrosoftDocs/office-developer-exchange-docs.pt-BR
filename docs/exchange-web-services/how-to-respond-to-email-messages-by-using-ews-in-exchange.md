---
title: Responder a mensagens de email usando o EWS no Exchange
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
localization_priority: Normal
ms.assetid: 9d584991-4d67-4d36-ae2f-99970af8488f
description: Saiba como responder a mensagens de email usando a API gerenciada do EWS ou o EWS no Exchange.
ms.openlocfilehash: 81599051f603654cdf8a50b789b37d7e76664a53
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44455706"
---
# <a name="respond-to-email-messages-by-using-ews-in-exchange"></a>Responder a mensagens de email usando o EWS no Exchange

Saiba como responder a mensagens de email usando a API gerenciada do EWS ou o EWS no Exchange.
  
Você pode usar a API gerenciada do EWS ou o EWS para responder às mensagens respondendo a elas ou encaminhá-las aos destinatários.
  
**Tabela 1. Métodos da API gerenciada do EWS e operações do EWS para responder a mensagens de email**

|**Tarefa**|**Método de API gerenciada do EWS**|**Operação do EWS**|
|:-----|:-----|:-----|
|Responder a uma mensagem de email  <br/> |[EmailMessage. Reply](https://msdn.microsoft.com/library/microsoft.exchange.webservices.data.emailmessage.reply%28v=exchg.80%29.aspx) <br/> [EmailMessage. createreply](https://msdn.microsoft.com/library/microsoft.exchange.webservices.data.emailmessage.createreply%28v=exchg.80%29.aspx) <br/> |[CreateItem](https://msdn.microsoft.com/library/fe6bb7fc-8918-4e6e-b0a1-b7e0ef44c3d1%28Office.15%29.aspx), onde o elemento [Items](https://msdn.microsoft.com/library/d61ef1cc-ddfc-480a-9625-7b436cb33ae0%28Office.15%29.aspx) tem um elemento filho de [ReplyToItem](https://msdn.microsoft.com/library/35ee751a-41c0-4216-ad8b-78f7ada43a2f%28Office.15%29.aspx) ou [ReplyAllToItem](https://msdn.microsoft.com/library/8ca970ca-ca73-40db-9233-7b271cc5f44f%28Office.15%29.aspx).  <br/> |
|Encaminhar uma mensagem de email  <br/> |[EmailMessage. Forward](https://msdn.microsoft.com/library/microsoft.exchange.webservices.data.emailmessage.forward%28v=exchg.80%29.aspx) <br/> [EmailMessage. createforward](https://msdn.microsoft.com/library/microsoft.exchange.webservices.data.emailmessage.createforward%28v=exchg.80%29.aspx) <br/> |[CreateItem](https://msdn.microsoft.com/library/fe6bb7fc-8918-4e6e-b0a1-b7e0ef44c3d1%28Office.15%29.aspx), onde o elemento [Items](https://msdn.microsoft.com/library/d61ef1cc-ddfc-480a-9625-7b436cb33ae0%28Office.15%29.aspx) tem um elemento filho de [ForwardItem](https://msdn.microsoft.com/library/97786086-8b91-4471-8af8-d21e8d66de87%28Office.15%29.aspx).  <br/> |
   
## <a name="reply-to-an-email-message-by-using-the-ews-managed-api"></a>Responder a uma mensagem de email usando a API gerenciada do EWS
<a name="bk_replyewsma"> </a>

A API gerenciada do EWS fornece dois métodos que você pode usar para responder às mensagens: [Reply](https://msdn.microsoft.com/library/microsoft.exchange.webservices.data.emailmessage.reply%28v=exchg.80%29.aspx) e [createreply](https://msdn.microsoft.com/library/microsoft.exchange.webservices.data.emailmessage.createreply%28v=exchg.80%29.aspx). O método **Reply** só aceita dois parâmetros: a mensagem de resposta para preceder o corpo existente e um valor **Boolean** que indica se a resposta deve ir para todos os destinatários (true) ou apenas para o remetente (false). Se você precisar adicionar destinatários adicionais a uma mensagem, definir propriedades adicionais em uma resposta ou adicionar um anexo, use o método **createreply** , que permite que você defina todas as propriedades de [primeira classe](email-properties-and-elements-in-ews-in-exchange.md) que estão disponíveis em um objeto [EmailMessage](https://msdn.microsoft.com/library/microsoft.exchange.webservices.data.emailmessage%28v=exchg.80%29.aspx) . 
  
O exemplo de código a seguir mostra como usar o método **Reply** para responder a uma mensagem de email. 
  
Este exemplo pressupõe que o **serviço** é um objeto [ExchangeService](https://msdn.microsoft.com/library/microsoft.exchange.webservices.data.exchangeservice%28v=exchg.80%29.aspx) válido e que o usuário foi autenticado em um servidor Exchange. A variável local *ItemId* é a [ID](https://msdn.microsoft.com/library/microsoft.exchange.webservices.data.item.id%28v=exchg.80%29.aspx) do item a ser respondido. O exemplo chama o [método FindRecentlySent](#bk_findlast) para verificar se a mensagem foi marcada como respondida. 
  
```cs
// As a best practice, limit the properties returned by the Bind method to only those that are required.
PropertySet propSet = new PropertySet(BasePropertySet.IdOnly, ItemSchema.LastModifiedTime);
// Bind to the email message to reply to by using the ItemId.
// This method call results in a GetItem call to EWS.
EmailMessage message = EmailMessage.Bind(service, ItemId, propSet);
string myReply = "This is the message body of the email reply.";
bool replyToAll = false;
// Send the response message.
// This method call results in a CreateItem call to EWS.
message.Reply(myReply, replyToAll);
// Verify that the response was sent by calling FindRecentlySent.
FindRecentlySent(message);
```

O exemplo de código a seguir mostra como usar o método **createreply** para responder a uma mensagem de email. 
  
```cs
// Bind to the email message to reply to by using the ItemId.
// This method call results in a GetItem call to EWS.
EmailMessage message = EmailMessage.Bind(service, ItemId, BasePropertySet.IdOnly);
// Create the reply response message from the original email message.
// Indicate whether the message is a reply or reply all type of reply.
bool replyToAll = true;
ResponseMessage responseMessage = message.CreateReply(replyToAll);
// Prepend the reply to the message body. 
string myReply = "This is the message body of the email reply.";
responseMessage.BodyPrefix = myReply;
// Send the response message.
// This method call results in a CreateItem call to EWS.
responseMessage.SendAndSaveCopy();
// Check that the response was sent by calling FindRecentlySent.
FindRecentlySent(message);
```

Se você precisar adicionar um anexo à mensagem de resposta, substitua a chamada para o método **SendAndSaveCopy** pelo código a seguir. 
  
```cs
EmailMessage reply = responseMessage.Save();
reply.Attachments.AddFileAttachment("attachmentname.txt");
reply.Update(ConflictResolutionMode.AutoResolve);
reply.SendAndSaveCopy();
```

## <a name="reply-to-an-email-message-by-using-ews"></a>Responder a uma mensagem de email usando EWS
<a name="bk_replyews"> </a>

O exemplo de código a seguir mostra como responder a uma mensagem usando o EWS. Use a operação [CreateItem](https://msdn.microsoft.com/library/fe6bb7fc-8918-4e6e-b0a1-b7e0ef44c3d1%28Office.15%29.aspx) com o atributo **MessageDisposition** definido como **SendAndSaveCopy** para enviar a mensagem e salvar a resposta na pasta Itens enviados. Inclua o elemento [ReplyAllToItem](https://msdn.microsoft.com/library/8ca970ca-ca73-40db-9233-7b271cc5f44f%28Office.15%29.aspx) como um filho do elemento [Items](https://msdn.microsoft.com/library/d61ef1cc-ddfc-480a-9625-7b436cb33ae0%28Office.15%29.aspx) para responder a todos no thread de mensagens ou inclua o elemento [ReplyToItem](https://msdn.microsoft.com/library/35ee751a-41c0-4216-ad8b-78f7ada43a2f%28Office.15%29.aspx) para responder apenas ao remetente. 
  
Essa é também a solicitação XML que a API gerenciada do EWS envia ao chamar o método [Reply](https://msdn.microsoft.com/library/microsoft.exchange.webservices.data.emailmessage.reply%28v=exchg.80%29.aspx) ou [createreply](https://msdn.microsoft.com/library/microsoft.exchange.webservices.data.emailmessage.createreply%28v=exchg.80%29.aspx) . 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
               xmlns:m="https://schemas.microsoft.com/exchange/services/2006/messages"
               xmlns:t="https://schemas.microsoft.com/exchange/services/2006/types"
               xmlns:soap="https://schemas.xmlsoap.org/soap/envelope/">
  <soap:Header>
    <t:RequestServerVersion Version=" Exchange2007_SP1" />
  </soap:Header>
  <soap:Body>
    <m:CreateItem MessageDisposition="SendAndSaveCopy">
      <m:Items>
        <t:ReplyAllToItem>
          <t:ReferenceItemId Id="AAMkADE4="
                             ChangeKey="CQAAABYA" />
          <t:NewBodyContent BodyType="HTML">This is the message body of the email reply.</t:NewBodyContent>
        </t:ReplyAllToItem>
      </m:Items>
    </m:CreateItem>
  </soap:Body>
</soap:Envelope>
```

O servidor responde à solicitação **CreateItem** com uma mensagem [CreateItemResponse](https://msdn.microsoft.com/library/742a46a0-2475-45a0-b44f-90639a3f5a43%28Office.15%29.aspx) que inclui um valor de elemento [ResponseCode](https://msdn.microsoft.com/library/4b84d670-74c9-4d6d-84e7-f0a9f76f0d93%28Office.15%29.aspx) de **NOERROR**, que indica que a resposta foi criada e enviada com êxito.
  
Se você precisar adicionar um anexo à mensagem de resposta, chame a operação **CreateItem** conforme especificado acima, mas altere o **MessageDisposition** para **SaveOnly**. Em seguida, chame a operação [CreateAttachment](https://msdn.microsoft.com/library/e066db95-6963-4507-a8d0-8efad287f550%28Office.15%29.aspx) , seguida pela operação [SendItem](https://msdn.microsoft.com/library/337b89ef-e1b7-45ed-92f3-8abe4200e4c7%28Office.15%29.aspx) . 
  
## <a name="forward-an-email-message-by-using-the-ews-managed-api"></a>Encaminhar uma mensagem de email usando a API gerenciada do EWS
<a name="bk_forwardewsma"> </a>

A API gerenciada do EWS fornece dois métodos que você pode usar para encaminhar mensagens: para [frente](https://msdn.microsoft.com/library/microsoft.exchange.webservices.data.emailmessage.forward%28v=exchg.80%29.aspx) e [createforward](https://msdn.microsoft.com/library/microsoft.exchange.webservices.data.emailmessage.createforward%28v=exchg.80%29.aspx). O método **Forward** só aceita dois parâmetros: a mensagem para preceder o corpo existente e uma matriz ou coleção de destinatários, dependendo da sobrecarga que você escolher usar. Se você precisar adicionar um anexo à mensagem que você está encaminhando ou definir propriedades adicionais na nova mensagem, use o método **createforward** , que permite que você defina todas as propriedades que estão disponíveis em um objeto [EmailMessage](https://msdn.microsoft.com/library/microsoft.exchange.webservices.data.emailmessage%28v=exchg.80%29.aspx) . 
  
O exemplo de código a seguir mostra como usar o método **Forward** para encaminhar uma mensagem de email para um destinatário. 
  
Este exemplo pressupõe que o **serviço** é um objeto [ExchangeService](https://msdn.microsoft.com/library/microsoft.exchange.webservices.data.exchangeservice%28v=exchg.80%29.aspx) válido e que o usuário foi autenticado em um servidor Exchange. A variável local *ItemId* é a [ID](https://msdn.microsoft.com/library/microsoft.exchange.webservices.data.item.id%28v=exchg.80%29.aspx) do item a ser encaminhada. O exemplo chama o [método FindRecentlySent](#bk_findlast) para verificar se a mensagem foi marcada como encaminhada. 
  
```cs
// Bind to the email message to reply to by using the ItemId.
// This method call results in a GetItem call to EWS.
EmailMessage message = EmailMessage.Bind(service, ItemId, BasePropertySet.IdOnly);
string myForward = "This is the message body of the forwarded email.";
// Send the response message.
// This method call results in a CreateItem call to EWS.
message.Forward(myForward, "sadie@contoso.com");
// Verify that the forwarded response was sent by calling FindRecentlySent.
FindRecentlySent(message);
```

O exemplo de código a seguir mostra como usar o método **createforward** para encaminhar uma mensagem de email para um destinatário. 
  
```cs
// Bind to the email message to reply to by using the ItemId.
// This method call results in a GetItem call to EWS.
EmailMessage message = EmailMessage.Bind(service, ItemId, BasePropertySet.IdOnly);
// Create the reply response message from the original email message.
// Indicate whether the message is a reply or reply all type of reply.
ResponseMessage forwardMessage = message.CreateForward();
// Set properties on the email message.
forwardMessage.ToRecipients.Add("sadie@contoso.com");
forwardMessage.Body = "Sadie,<br><br>I thought you'd be interested in this thread.<br><br>-Mack";
// Send and save a copy of the replied email message in the default Sent Items folder. 
forwardMessage.SendAndSaveCopy();
// Verify that the forwarded message was sent by calling FindRecentlySent.
FindRecentlySent(message);
```

Se você precisar adicionar um anexo à mensagem encaminhada, substitua a chamada para o método **SendAndSaveCopy** pelo código a seguir. 
  
```cs
EmailMessage forward = forwardMessage.Save();
forward.Attachments.AddFileAttachment("attachmentname.txt");
forward.Update(ConflictResolutionMode.AutoResolve);
forward.SendAndSaveCopy();
```

## <a name="forward-an-email-message-by-using-ews"></a>Encaminhar uma mensagem de email usando EWS
<a name="bk_forwardews"> </a>

O exemplo de código a seguir mostra como encaminhar uma mensagem usando o EWS. Use a operação [CreateItem](https://msdn.microsoft.com/library/fe6bb7fc-8918-4e6e-b0a1-b7e0ef44c3d1%28Office.15%29.aspx) com o atributo **MessageDisposition** definido como **SendAndSaveCopy** para enviar a mensagem e salvar a resposta na pasta Itens enviados. O elemento [ForwardItem](https://msdn.microsoft.com/library/97786086-8b91-4471-8af8-d21e8d66de87%28Office.15%29.aspx) indica que o item é uma mensagem encaminhada. 
  
Essa é também a solicitação XML que a API gerenciada do EWS envia ao chamar o método [Forward](https://msdn.microsoft.com/library/microsoft.exchange.webservices.data.emailmessage.forward%28v=exchg.80%29.aspx) ou [createforward](https://msdn.microsoft.com/library/microsoft.exchange.webservices.data.emailmessage.createforward%28v=exchg.80%29.aspx) . 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
               xmlns:m="https://schemas.microsoft.com/exchange/services/2006/messages"
               xmlns:t="https://schemas.microsoft.com/exchange/services/2006/types"
               xmlns:soap="https://schemas.xmlsoap.org/soap/envelope/">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2007_SP1" />
  </soap:Header>
  <soap:Body>
    <m:CreateItem MessageDisposition="SendAndSaveCopy">
      <m:Items>
        <t:ForwardItem>
          <t:ToRecipients>
            <t:Mailbox>
              <t:EmailAddress>sadie@contoso.com</t:EmailAddress>
            </t:Mailbox>
          </t:ToRecipients>
          <t:ReferenceItemId Id="AAAMkADE="
                             ChangeKey="CQAAABYA" />
          <t:NewBodyContent BodyType="HTML">This is the message body of the forwarded email.</t:NewBodyContent>
        </t:ForwardItem>
      </m:Items>
    </m:CreateItem>
  </soap:Body>
</soap:Envelope>
```

O servidor responde à solicitação **CreateItem** com uma mensagem [CreateItemResponse](https://msdn.microsoft.com/library/742a46a0-2475-45a0-b44f-90639a3f5a43%28Office.15%29.aspx) que inclui um valor de elemento [ResponseCode](https://msdn.microsoft.com/library/4b84d670-74c9-4d6d-84e7-f0a9f76f0d93%28Office.15%29.aspx) de **NOERROR**, que indica que a mensagem encaminhada foi criada e enviada com êxito.
  
Se você precisar adicionar um anexo à mensagem de resposta, chame a operação **CreateItem** , mas altere o **MessageDisposition** para **SaveOnly**. Em seguida, chame a operação [CreateAttachment](https://msdn.microsoft.com/library/e066db95-6963-4507-a8d0-8efad287f550%28Office.15%29.aspx) , seguida pela operação [SendItem](https://msdn.microsoft.com/library/337b89ef-e1b7-45ed-92f3-8abe4200e4c7%28Office.15%29.aspx) . 
  
## <a name="find-the-message-last-replied-to-or-forwarded-by-using-the-ews-managed-api"></a>Localizar a mensagem respondida pela última vez ou encaminhada usando a API gerenciada do EWS
<a name="bk_findlast"> </a>

O exemplo de código a seguir mostra como localizar o último verbo executado e a hora em que o último verbo foi executado no item especificado. Este método é chamado a partir de outros exemplos de código da API gerenciada do EWS neste tópico para verificar se os itens que você respondeu ou encaminhadas foram marcados como respondidos ou encaminhados na sua caixa de entrada. 
  
O exemplo usa a propriedade estendida [PidTagLastVerbExecuted](https://msdn.microsoft.com/library/cc841968.aspx) (0x10820003) para determinar se a mensagem foi uma resposta, uma resposta a todos, ou uma para frente, e a [PidTagLastVerbExecutionTime](https://msdn.microsoft.com/library/cc839918.aspx) (0x10820040) estendida para determinar quando responder ou encaminhar foi enviado. 
  
```cs
public static void FindRecentlySent(EmailMessage messageToCheck)
{
    // Create extended property definitions for PidTagLastVerbExecuted and PidTagLastVerbExecutionTime.
    ExtendedPropertyDefinition PidTagLastVerbExecuted = new ExtendedPropertyDefinition(0x1081, MapiPropertyType.Integer);
    ExtendedPropertyDefinition PidTagLastVerbExecutionTime = new ExtendedPropertyDefinition(0x1082, MapiPropertyType.SystemTime);
    PropertySet propSet = new PropertySet(BasePropertySet.IdOnly, EmailMessageSchema.Subject, PidTagLastVerbExecutionTime, PidTagLastVerbExecuted);
    messageToCheck = EmailMessage.Bind(service, messageToCheck.Id, propSet);
    // Determine the last verb executed on the message and display output.
    object responseType;
    if (messageToCheck.TryGetProperty(PidTagLastVerbExecuted, out responseType))
    {
        object ReplyTime = null;
        switch (((Int32)responseType))
        {
            case 102: Console.WriteLine("A reply was sent to the '" + messageToCheck.Subject.ToString() + "' email message at");
                break;
            case 103: Console.WriteLine("A reply all was sent to the '" + messageToCheck.Subject.ToString() + "' email message at");
                break;
            case 104: Console.WriteLine("The '" + messageToCheck.Subject.ToString() + "' email message was forwarded at");
                break;
        }
        if (messageToCheck.TryGetProperty(PidTagLastVerbExecutionTime, out ReplyTime))
        {
            Console.WriteLine(((DateTime)ReplyTime).ToString() + ".");
        }
    }
    else
    {
        Console.WriteLine("No changes were made to  '" + messageToCheck.Subject.ToString() + "'.");
    }
}
```

## <a name="see-also"></a>Confira também


- [Email e EWS no Exchange](email-and-ews-in-exchange.md)
    
- [Enviar mensagens de email usando o EWS no Exchange](how-to-send-email-messages-by-using-ews-in-exchange.md)
    

