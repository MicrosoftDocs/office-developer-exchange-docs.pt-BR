---
title: Adicionar anexos usando o EWS no Exchange
manager: sethgros
ms.date: 03/9/2015
ms.audience: Developer
localization_priority: Normal
ms.assetid: 0cbce436-2ae6-4fcc-bd8b-f517a0724e55
description: Aprenda a criar novos itens com anexos ou adicionar anexos aos itens existentes usando a API gerenciada de EWS ou EWS no Exchange.
ms.openlocfilehash: dbfff879c92dafeec588d79cddd92e294b763c06
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/25/2018
ms.locfileid: "19750715"
---
# <a name="add-attachments-by-using-ews-in-exchange"></a><span data-ttu-id="cdee3-103">Adicionar anexos usando o EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="cdee3-103">Add attachments by using EWS in Exchange</span></span>

<span data-ttu-id="cdee3-104">Aprenda a criar novos itens com anexos ou adicionar anexos aos itens existentes usando a API gerenciada de EWS ou EWS no Exchange.</span><span class="sxs-lookup"><span data-stu-id="cdee3-104">Learn how to create new items with attachments, or add attachments to existing items by using the EWS Managed API or EWS in Exchange.</span></span>
  
<span data-ttu-id="cdee3-105">Você pode adicionar anexos de arquivo ou item anexos aos itens novos ou existentes usando o EWS Managed API ou o EWS.</span><span class="sxs-lookup"><span data-stu-id="cdee3-105">You can add file attachments or item attachments to new or existing items by using the EWS Managed API or EWS.</span></span> <span data-ttu-id="cdee3-106">Se você estiver usando o EWS Managed API, use o mesmo método para adicionar anexos aos itens novos ou existentes; No entanto, o método altera se você estiver usando um anexo de arquivo ou item.</span><span class="sxs-lookup"><span data-stu-id="cdee3-106">If you are using the EWS Managed API, you use the same method to add attachments to new or existing items; however, the method changes if you're using a file or item attachment.</span></span> <span data-ttu-id="cdee3-107">De modo oposto, se você estiver usando o EWS, você usa a mesma operação para adicionar um arquivo ou um item anexo a um item, mas a operação será alterada se você estiver adicionando o anexo a um item novo ou existente.</span><span class="sxs-lookup"><span data-stu-id="cdee3-107">Conversely, if you are using EWS, you use the same operation to add either a file or item attachment to an item, but the operation changes if you're adding the attachment to a new or existing item.</span></span>
  
<span data-ttu-id="cdee3-108">**Tabela 1. Métodos de API gerenciada de EWS e operações de EWS para adição de anexos**</span><span class="sxs-lookup"><span data-stu-id="cdee3-108">**Table 1. EWS Managed API methods and EWS operations for adding attachments**</span></span>

|<span data-ttu-id="cdee3-109">**Task**</span><span class="sxs-lookup"><span data-stu-id="cdee3-109">**Task**</span></span>|<span data-ttu-id="cdee3-110">**Método API gerenciada de EWS**</span><span class="sxs-lookup"><span data-stu-id="cdee3-110">**EWS Managed API method**</span></span>|<span data-ttu-id="cdee3-111">**Operação do EWS**</span><span class="sxs-lookup"><span data-stu-id="cdee3-111">**EWS operation**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="cdee3-112">Adicionar um anexo de arquivo a um email novo ou existente</span><span class="sxs-lookup"><span data-stu-id="cdee3-112">Add a file attachment to a new or existing email</span></span>  <br/> |[<span data-ttu-id="cdee3-113">AttachmentCollection.AddFileAttachment</span><span class="sxs-lookup"><span data-stu-id="cdee3-113">AttachmentCollection.AddFileAttachment</span></span>](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.attachmentcollection.addfileattachment%28v=exchg.80%29.aspx) <br/> |<span data-ttu-id="cdee3-114">[CreateItem](http://msdn.microsoft.com/library/fe6bb7fc-8918-4e6e-b0a1-b7e0ef44c3d1%28Office.15%29.aspx) para um novo email</span><span class="sxs-lookup"><span data-stu-id="cdee3-114">[CreateItem](http://msdn.microsoft.com/library/fe6bb7fc-8918-4e6e-b0a1-b7e0ef44c3d1%28Office.15%29.aspx) for a new email</span></span>  <br/> <span data-ttu-id="cdee3-115">[CreateAttachment](http://msdn.microsoft.com/library/e066db95-6963-4507-a8d0-8efad287f550%28Office.15%29.aspx) para adicionar um email existente</span><span class="sxs-lookup"><span data-stu-id="cdee3-115">[CreateAttachment](http://msdn.microsoft.com/library/e066db95-6963-4507-a8d0-8efad287f550%28Office.15%29.aspx) to add to an existing email</span></span>  <br/> |
|<span data-ttu-id="cdee3-116">Adicionar um anexo do item a um email novo ou existente</span><span class="sxs-lookup"><span data-stu-id="cdee3-116">Add an item attachment to a new or existing email</span></span>  <br/> |[<span data-ttu-id="cdee3-117">AttachmentCollection.AddItemAttachment</span><span class="sxs-lookup"><span data-stu-id="cdee3-117">AttachmentCollection.AddItemAttachment</span></span>](http://msdn.microsoft.com/pt-br/library/dd634986%28v=exchg.80%29.aspx) <br/> |<span data-ttu-id="cdee3-118">[CreateItem](http://msdn.microsoft.com/library/fe6bb7fc-8918-4e6e-b0a1-b7e0ef44c3d1%28Office.15%29.aspx) para um novo email</span><span class="sxs-lookup"><span data-stu-id="cdee3-118">[CreateItem](http://msdn.microsoft.com/library/fe6bb7fc-8918-4e6e-b0a1-b7e0ef44c3d1%28Office.15%29.aspx) for a new email</span></span>  <br/> <span data-ttu-id="cdee3-119">[CreateAttachment](http://msdn.microsoft.com/library/e066db95-6963-4507-a8d0-8efad287f550%28Office.15%29.aspx) para adicionar um email existente</span><span class="sxs-lookup"><span data-stu-id="cdee3-119">[CreateAttachment](http://msdn.microsoft.com/library/e066db95-6963-4507-a8d0-8efad287f550%28Office.15%29.aspx) to add to an existing email</span></span>  <br/> |
   
## <a name="create-an-email-with-file-and-item-attachments-by-using-the-ews-managed-api"></a><span data-ttu-id="cdee3-120">Criar um email com anexos de arquivo e um item usando a API gerenciada de EWS</span><span class="sxs-lookup"><span data-stu-id="cdee3-120">Create an email with file and item attachments by using the EWS Managed API</span></span>
<span data-ttu-id="cdee3-121"><a name="bk_createattachewsma"> </a></span><span class="sxs-lookup"><span data-stu-id="cdee3-121"></span></span>

<span data-ttu-id="cdee3-122">O exemplo de código a seguir mostra como criar um email com vários anexos de arquivo e um anexo do item por:</span><span class="sxs-lookup"><span data-stu-id="cdee3-122">The following code example shows how to create an email with multiple file attachments and an item attachment by:</span></span> 
  
1. <span data-ttu-id="cdee3-123">Usando o objeto [EmailMessage](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.emailmessage%28v=exchg.80%29.aspx) para criar uma mensagem de email.</span><span class="sxs-lookup"><span data-stu-id="cdee3-123">Using the [EmailMessage](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.emailmessage%28v=exchg.80%29.aspx) object to create an email message.</span></span> 
    
2. <span data-ttu-id="cdee3-124">Usando os métodos [AttachmentCollection.AddFileAttachment](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.attachmentcollection.addfileattachment%28v=exchg.80%29.aspx) e [AttachmentCollection.AddItemAttachment](http://msdn.microsoft.com/pt-br/library/dd634986%28v=exchg.80%29.aspx) para adicionar anexos à mensagem.</span><span class="sxs-lookup"><span data-stu-id="cdee3-124">Using the [AttachmentCollection.AddFileAttachment](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.attachmentcollection.addfileattachment%28v=exchg.80%29.aspx) and [AttachmentCollection.AddItemAttachment](http://msdn.microsoft.com/pt-br/library/dd634986%28v=exchg.80%29.aspx) methods to add attachments to the message.</span></span> 
    
3. <span data-ttu-id="cdee3-125">Usando o método [EmailMessage.SendAndSaveCopy](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.emailmessage.sendandsavecopy%28v=exchg.80%29.aspx) para enviar a mensagem para os destinatários e salve a mensagem na pasta Itens enviados.</span><span class="sxs-lookup"><span data-stu-id="cdee3-125">Using the [EmailMessage.SendAndSaveCopy](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.emailmessage.sendandsavecopy%28v=exchg.80%29.aspx) method to send the message to the recipients and save the message in the Sent Items folder.</span></span> 
    
<span data-ttu-id="cdee3-126">Este exemplo de código mostra as quatro maneiras em que um anexo de arquivo pode ser adicionado a um item usando a API gerenciada de EWS:</span><span class="sxs-lookup"><span data-stu-id="cdee3-126">This code example shows the four ways in which a file attachment can be added to an item by using the EWS Managed API:</span></span>
  
- <span data-ttu-id="cdee3-127">Usando um local de arquivo totalmente qualificado.</span><span class="sxs-lookup"><span data-stu-id="cdee3-127">By using a fully qualified file location.</span></span>
    
- <span data-ttu-id="cdee3-128">Usando um local de arquivo totalmente qualificado e um novo nome de anexo.</span><span class="sxs-lookup"><span data-stu-id="cdee3-128">By using a fully qualified file location and a new attachment name.</span></span>
    
- <span data-ttu-id="cdee3-129">Usando uma matriz de bytes.</span><span class="sxs-lookup"><span data-stu-id="cdee3-129">By using a byte array.</span></span>
    
- <span data-ttu-id="cdee3-130">Usando um fluxo.</span><span class="sxs-lookup"><span data-stu-id="cdee3-130">By using a stream.</span></span>
    
<span data-ttu-id="cdee3-131">Observe que o item de anexo neste exemplo é criado ao mesmo tempo que a mensagem de email.</span><span class="sxs-lookup"><span data-stu-id="cdee3-131">Note that the item attachment in this example is created at the same time as the email message.</span></span> <span data-ttu-id="cdee3-132">Para adicionar uma mensagem de email existente como um anexo de item, consulte [Adicionar um item existente para um novo email usando o MimeContent e a API gerenciada de EWS](#bk_addexistingemailewsma).</span><span class="sxs-lookup"><span data-stu-id="cdee3-132">To add an existing email message as an item attachment, see [Add an existing item to a new email by using the MimeContent and the EWS Managed API](#bk_addexistingemailewsma).</span></span>
  
<span data-ttu-id="cdee3-133">Este exemplo supõe que esse **serviço** é um objeto válido do [ExchangeService](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.exchangeservice%28v=exchg.80%29.aspx) e que o usuário foi autenticado com um servidor Exchange.</span><span class="sxs-lookup"><span data-stu-id="cdee3-133">This example assumes that **service** is a valid [ExchangeService](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.exchangeservice%28v=exchg.80%29.aspx) object and that the user has been authenticated to an Exchange server.</span></span> 
  
```cs
public static void CreateEmailWithAttachments(ExchangeService service)
{
    // Create an email message and set properties on the message.
    EmailMessage message = new EmailMessage(service);
    // Set properties on the email message.
    message.Subject = "Message with Attachments";
    message.Body = "This message contains four file attachments 
        and one message item attachment.";
    message.ToRecipients.Add("sadie@contoso.com");
    message.ToRecipients.Add("ronnie@contoso.com");
    // Add a file attachment by using the fully qualified location of the file. 
    message.Attachments.AddFileAttachment("C:\\temp\\FileAttachment.txt");
    // Add a file attachment by using the fully qualified string name, 
    // and specify the name of the attachment as it will appear in the email.
    // The new name of the file attachment is SecondAttachment.txt.
    message.Attachments.AddFileAttachment("SecondAttachment.txt", "C:\\temp\\FileAttachment2.txt");
    // Add a file attachment by using a byte array.
    // In this example, theBytes is the byte array that represents the content of the image file to attach.
    byte[] theBytes = File.ReadAllBytes("C:\\Temp\\Tulips.jpg");
    // The byte array file attachment is named ThirdAttachment.jpg.
    message.Attachments.AddFileAttachment("ThirdAttachment.jpg", theBytes);
    // Add a file attachment by using a stream.
    FileStream theStream = new FileStream("C:\\temp\\FileAttachment4.txt", FileMode.OpenOrCreate);
    // The streamed file attachment is named FourthAttachment.txt.
    message.Attachments.AddFileAttachment("FourthAttachment.txt", theStream);
    // Add an email message as an item attachment and set properties on the item.
    ItemAttachment<EmailMessage> itemAttachment = message.Attachments.AddItemAttachment<EmailMessage>();
    itemAttachment.Name = "Attached Message Item";
    itemAttachment.Item.Subject = "Message Item Subject";
    itemAttachment.Item.Body = "Message Item Body";
    itemAttachment.Item.ToRecipients.Add("sadie@contoso.com");
    itemAttachment.Item.ToRecipients.Add("ronnie@contoso.com");
    // Send the mail and save a copy in the Sent Items folder.
    // This method results in a CreateItem and SendItem call to EWS.
    message.SendAndSaveCopy();
}
```

## <a name="create-an-email-with-file-and-item-attachments-by-using-ews"></a><span data-ttu-id="cdee3-134">Criar um email com anexos de arquivo e um item usando o EWS</span><span class="sxs-lookup"><span data-stu-id="cdee3-134">Create an email with file and item attachments by using EWS</span></span>
<span data-ttu-id="cdee3-135"><a name="bk_createattachews"> </a></span><span class="sxs-lookup"><span data-stu-id="cdee3-135"></span></span>

<span data-ttu-id="cdee3-136">O exemplo de código a seguir mostra como usar a operação [CreateItem](http://msdn.microsoft.com/library/fe6bb7fc-8918-4e6e-b0a1-b7e0ef44c3d1%28Office.15%29.aspx) para criar uma mensagem de email com quatro anexos de arquivo e um anexo do item.</span><span class="sxs-lookup"><span data-stu-id="cdee3-136">The following code example shows how to use the [CreateItem](http://msdn.microsoft.com/library/fe6bb7fc-8918-4e6e-b0a1-b7e0ef44c3d1%28Office.15%29.aspx) operation to create an email message with four file attachments and one item attachment.</span></span> <span data-ttu-id="cdee3-137">Isso também é uma das solicitações de XML que o EWS Managed API envia quando você [criar um email com anexos de arquivo e o item](#bk_createattachewsma).</span><span class="sxs-lookup"><span data-stu-id="cdee3-137">This is also one of the XML requests that the EWS Managed API sends when you [create an email with file and item attachments](#bk_createattachewsma).</span></span>
  
<span data-ttu-id="cdee3-138">Observe que o item de anexo neste exemplo é criado ao mesmo tempo que a mensagem de email.</span><span class="sxs-lookup"><span data-stu-id="cdee3-138">Note that the item attachment in this example is created at the same time as the email message.</span></span> <span data-ttu-id="cdee3-139">Para adicionar uma mensagem de email existente como um anexo de item, consulte [Adicionar um item existente para um novo email usando o MimeContent e a API gerenciada de EWS](#bk_addexistingemailewsma).</span><span class="sxs-lookup"><span data-stu-id="cdee3-139">To add an existing email message as an item attachment, see [Add an existing item to a new email by using the MimeContent and the EWS Managed API](#bk_addexistingemailewsma).</span></span>
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
               xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages"
               xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types"
               xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2007_SP1" />
  </soap:Header>
  <soap:Body>
    <m:CreateItem MessageDisposition="SaveOnly">
      <m:Items>
        <t:Message>
          <t:Subject>Message with Attachments</t:Subject>
          <t:Body BodyType="HTML">This message contains four file attachments 
              and one message item attachment.</t:Body>
          <t:Attachments>
            <t:FileAttachment>
              <t:Name>FileAttachment.txt</t:Name>
              <t:IsInline>false</t:IsInline>
              <t:IsContactPhoto>false</t:IsContactPhoto>
              <t:Content>VGhpcyBpcyBhIGZpbGUgYXR0YWNobWVudC4=</t:Content>
            </t:FileAttachment>
            <t:FileAttachment>
              <t:Name>SecondAttachment.txt</t:Name>
              <t:IsInline>false</t:IsInline>
              <t:IsContactPhoto>false</t:IsContactPhoto>
              <t:Content>VGhpcyBpcyB0aGUgc2Vjb25kIGZpbGUgYXR0YWNobWVudC4=</t:Content>
            </t:FileAttachment>
            <t:FileAttachment>
              <t:Name>ThirdAttachment.jpg</t:Name>
              <t:IsInline>false</t:IsInline>
              <t:IsContactPhoto>false</t:IsContactPhoto>
              <t:Content>nAoAXNIZMVEZs5GKhdzRcLH/9k=</t:Content>
            </t:FileAttachment>
            <t:FileAttachment>
              <t:Name>FourthAttachment.txt</t:Name>
              <t:IsInline>false</t:IsInline>
              <t:IsContactPhoto>false</t:IsContactPhoto>
              <t:Content>obWVudC4=…</t:Content>
            </t:FileAttachment>
            <t:ItemAttachment>
              <t:Name>Attached Message Item</t:Name>
              <t:IsInline>false</t:IsInline>
              <t:Message>
                <t:Subject>Message Item Subject</t:Subject>
                <t:Body BodyType="HTML">Message Item Body</t:Body>
                <t:ToRecipients>
                  <t:Mailbox>
                    <t:EmailAddress>sadie@contoso.com</t:EmailAddress>
                  </t:Mailbox>
                  <t:Mailbox>
                    <t:EmailAddress>mack@contoso.com</t:EmailAddress>
                  </t:Mailbox>
                </t:ToRecipients>
              </t:Message>
            </t:ItemAttachment>
          </t:Attachments>
          <t:ToRecipients>
            <t:Mailbox>
              <t:EmailAddress>sadie@contoso.com</t:EmailAddress>
            </t:Mailbox>
            <t:Mailbox>
              <t:EmailAddress>ronnie@contoso.com</t:EmailAddress>
            </t:Mailbox>
          </t:ToRecipients>
        </t:Message>
      </m:Items>
    </m:CreateItem>
  </soap:Body>
</soap:Envelope>
```

<span data-ttu-id="cdee3-140">O servidor responde à solicitação **CreateItem** com uma mensagem de [CreateItemResponse](http://msdn.microsoft.com/library/742a46a0-2475-45a0-b44f-90639a3f5a43%28Office.15%29.aspx) que inclui um valor de [ResponseCode](http://msdn.microsoft.com/pt-br/library/aa580757%28v=exchg.150%29.aspx) de **NoError**, que indica que o email e os anexos foram criados com êxito.</span><span class="sxs-lookup"><span data-stu-id="cdee3-140">The server responds to the **CreateItem** request with a [CreateItemResponse](http://msdn.microsoft.com/library/742a46a0-2475-45a0-b44f-90639a3f5a43%28Office.15%29.aspx) message that includes a [ResponseCode](http://msdn.microsoft.com/pt-br/library/aa580757%28v=exchg.150%29.aspx) value of **NoError**, which indicates that the email and the attachments were created successfully.</span></span> <span data-ttu-id="cdee3-141">O [ItemId](http://msdn.microsoft.com/library/3350b597-57a0-4961-8f44-8624946719b4%28Office.15%29.aspx) da mensagem recém-criado e os valores de [AttachmentId](http://msdn.microsoft.com/library/55a5fd77-60d1-40fa-8144-770600cedc6a%28Office.15%29.aspx) para cada um dos anexos também pode ser incluído na resposta.</span><span class="sxs-lookup"><span data-stu-id="cdee3-141">The [ItemId](http://msdn.microsoft.com/library/3350b597-57a0-4961-8f44-8624946719b4%28Office.15%29.aspx) of the newly created message and the [AttachmentId](http://msdn.microsoft.com/library/55a5fd77-60d1-40fa-8144-770600cedc6a%28Office.15%29.aspx) values for each of the attachments is also included in the response.</span></span> <span data-ttu-id="cdee3-142">Os valores de alguns atributos foram diminuídos para melhorar a legibilidade.</span><span class="sxs-lookup"><span data-stu-id="cdee3-142">The values of some attributes have been shortened for readability.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<s:Envelope xmlns:s="http://schemas.xmlsoap.org/soap/envelope/">
  <s:Header>
    <h:ServerVersionInfo MajorVersion="15"
                         MinorVersion="0"
                         MajorBuildNumber="939"
                         MinorBuildNumber="12"
                         Version="V2_11"
                         xmlns:h="http://schemas.microsoft.com/exchange/services/2006/types"
                         xmlns="http://schemas.microsoft.com/exchange/services/2006/types"
                         xmlns:xsd="http://www.w3.org/2001/XMLSchema"
                         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" />
  </s:Header>
  <s:Body xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
          xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <m:CreateItemResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages"
                          xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
      <m:ResponseMessages>
        <m:CreateItemResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:Items>
            <t:Message>
              <t:ItemId Id="upV4AAA="
                        ChangeKey="CQAAABYAAAAFI5DJmZv+TLtyLOLIF1S5AAAXuktU" />
              <t:Attachments>
                <t:FileAttachment>
                  <t:AttachmentId Id="6ts3NuI=" />
                </t:FileAttachment>
                <t:FileAttachment>
                  <t:AttachmentId Id="gOIZx1I=" />
                </t:FileAttachment>
                <t:FileAttachment>
                  <t:AttachmentId Id="esRan5I=" />
                </t:FileAttachment>
                <t:FileAttachment>
                  <t:AttachmentId Id="t7sU6s=" />
                </t:FileAttachment>
                <t:ItemAttachment>
                  <t:AttachmentId Id="XgDCggM=" />
                </t:ItemAttachment>
              </t:Attachments>
            </t:Message>
          </m:Items>
        </m:CreateItemResponseMessage>
      </m:ResponseMessages>
    </m:CreateItemResponse>
  </s:Body>
</s:Envelope>
```

<span data-ttu-id="cdee3-143">Para [Enviar a mensagem de dados criado recentemente](how-to-send-email-messages-by-using-ews-in-exchange.md), chame a operação [SendItem](http://msdn.microsoft.com/library/337b89ef-e1b7-45ed-92f3-8abe4200e4c7%28Office.15%29.aspx) .</span><span class="sxs-lookup"><span data-stu-id="cdee3-143">To [send this newly created message](how-to-send-email-messages-by-using-ews-in-exchange.md), call the [SendItem](http://msdn.microsoft.com/library/337b89ef-e1b7-45ed-92f3-8abe4200e4c7%28Office.15%29.aspx) operation.</span></span> 
  
## <a name="add-an-existing-item-to-a-new-email-by-using-the-mimecontent-and-the-ews-managed-api"></a><span data-ttu-id="cdee3-144">Adicionar um item existente para um novo email usando o MimeContent e a API gerenciada de EWS</span><span class="sxs-lookup"><span data-stu-id="cdee3-144">Add an existing item to a new email by using the MimeContent and the EWS Managed API</span></span>
<span data-ttu-id="cdee3-145"><a name="bk_addexistingemailewsma"> </a></span><span class="sxs-lookup"><span data-stu-id="cdee3-145"></span></span>

<span data-ttu-id="cdee3-146">Para adicionar um item existente como um anexo do item a outro item, você precisará criar um novo item de anexo e copiar o conteúdo do item existente para o novo item.</span><span class="sxs-lookup"><span data-stu-id="cdee3-146">To add an existing item as an item attachment to another item, you need to create a new item attachment and copy the content of the existing item to the new item.</span></span> <span data-ttu-id="cdee3-147">Há duas maneiras de fazer isso:</span><span class="sxs-lookup"><span data-stu-id="cdee3-147">There are two ways to do this:</span></span> 
  
1. <span data-ttu-id="cdee3-148">Se você estiver trabalhando com mensagens de email especificamente, você pode copiar o valor da propriedade [MimeContent](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.item.mimecontent%28v=exchg.80%29.aspx) de email para o item recém-criado de anexo.</span><span class="sxs-lookup"><span data-stu-id="cdee3-148">If you're working with email messages specifically, you can copy the value of the [MimeContent](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.item.mimecontent%28v=exchg.80%29.aspx) property from the email into the newly created item attachment.</span></span> <span data-ttu-id="cdee3-149">Você perderá algumas propriedades durante esse processo, como categorias e os sinalizadores de acompanhamento, mas ele é muito útil para mensagens de email padrão.</span><span class="sxs-lookup"><span data-stu-id="cdee3-149">You will lose some properties during this process, such as follow up flags and categories, but it works great for standard email messages.</span></span> 
    
2. <span data-ttu-id="cdee3-150">Se você precisar com fidelidade total para todos os tipos de item, você pode vincular a um item existente e copiar todas as propriedades e propriedades estendidas para o novo anexo.</span><span class="sxs-lookup"><span data-stu-id="cdee3-150">If you need full fidelity for all item types, you can bind to an existing item and copy all the properties and extended properties into the new attachment.</span></span>
    
<span data-ttu-id="cdee3-151">O exemplo de código a seguir mostra a primeira abordagem, copiando o **MimeContent** para o novo item de anexo.</span><span class="sxs-lookup"><span data-stu-id="cdee3-151">The following code example shows the first approach, copying the **MimeContent** into the new item attachment.</span></span> <span data-ttu-id="cdee3-152">Este exemplo a seguir é um procedimento que mostra como você pode modificar o código para usar a segunda abordagem.</span><span class="sxs-lookup"><span data-stu-id="cdee3-152">Following this example is a procedure that shows how you can modify the code to use the second approach.</span></span> 
  
<span data-ttu-id="cdee3-153">Este exemplo supõe que esse **serviço** é um objeto válido do [ExchangeService](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.exchangeservice%28v=exchg.80%29.aspx) que o usuário foi autenticado com um servidor Exchange e que o **itemId** é o [ItemId](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.itemid%28v=exchg.80%29.aspx) do item para anexar.</span><span class="sxs-lookup"><span data-stu-id="cdee3-153">This example assumes that **service** is a valid [ExchangeService](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.exchangeservice%28v=exchg.80%29.aspx) object and that the user has been authenticated to an Exchange server, and that the **itemId** is the [ItemId](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.itemid%28v=exchg.80%29.aspx) of the item to attach.</span></span> 
  
```cs
public static void CreateEmailExistingItem(ExchangeService service, ItemId itemId)
{        
    // This method results in a GetItem call to EWS.
    EmailMessage msgToAttach = EmailMessage.Bind(service,itemId, 
        new PropertySet(ItemSchema.MimeContent, ItemSchema.Subject));
    // Create an email message and set properties on the message.
    EmailMessage message = new EmailMessage(service);
    message.Subject = "Message with Item Attachment (MimeContent)";
    message.Body = "The attachment to this message was created by copying
        the MimeContent from the original message and adding it to a new item attachment.";
    message.ToRecipients.Add("sadie@contoso.com");
    // Add an email message item attachment and set properties on the item.
    ItemAttachment<EmailMessage> itemAttachment = message.Attachments.AddItemAttachment<EmailMessage>();
    itemAttachment.Item.MimeContent = msgToAttach.MimeContent;
    itemAttachment.Name = msgToAttach.Subject;
    // Send the mail and save a copy in the Sent Items folder.
    // This method results in a CreateItem and SendItem call to EWS.
    message.SendAndSaveCopy();
}
```

<span data-ttu-id="cdee3-154">Para modificar este exemplo para copiar cada uma das propriedades no item existente para o novo item de anexo, faça o seguinte:</span><span class="sxs-lookup"><span data-stu-id="cdee3-154">To modify this example to copy each of the properties on the existing item into the new item attachment, do the following:</span></span> 
  
1. <span data-ttu-id="cdee3-155">Altere a propriedade definida para incluir **PropertySet.FirstClassProperties** e qualquer propriedades adicionais ou propriedades estendidas, que você precisa.</span><span class="sxs-lookup"><span data-stu-id="cdee3-155">Change the property set to include **PropertySet.FirstClassProperties** and any additional properties or extended properties you need.</span></span> 
    
  ```cs
  // Add additional properties to the PropertySet.
  EmailMessage msgToAttach = EmailMessage.Bind(service, itemId, new PropertySet(PropertySet.FirstClassProperties));
  ```

2. <span data-ttu-id="cdee3-156">Remova a linha seguinte, porque a propriedade **MimeContent** não é necessário.</span><span class="sxs-lookup"><span data-stu-id="cdee3-156">Remove the following line, because you do not need the **MimeContent** property.</span></span> 
    
  ```cs
  itemAttachment.Item.MimeContent = msgToAttach.MimeContent;
  ```

3. <span data-ttu-id="cdee3-157">Repita essa linha para cada propriedade copiar do item existente para o novo anexo.</span><span class="sxs-lookup"><span data-stu-id="cdee3-157">Repeat this line for each property to copy from the existing item to the new attachment.</span></span> <span data-ttu-id="cdee3-158">Não copie o **ItemId** para o novo item de anexo porque que é uma propriedade de somente leitura.</span><span class="sxs-lookup"><span data-stu-id="cdee3-158">Do not copy the **ItemId** into the new item attachment because that's a read-only property.</span></span> 
    
  ```cs
  itemAttachment.Item.Subject = msgToAttach.Subject;
  ```

4. <span data-ttu-id="cdee3-159">Defina a propriedade [PidTagMessageFlags](http://msdn.microsoft.com/pt-br/library/cc839733.aspx) (0x0E070003) no anexo para **enviado**.</span><span class="sxs-lookup"><span data-stu-id="cdee3-159">Set the [PidTagMessageFlags](http://msdn.microsoft.com/pt-br/library/cc839733.aspx) (0x0E070003) property on the attachment to **Sent**.</span></span>
    
  ```cs
  ExtendedPropertyDefinition sent = new ExtendedPropertyDefinition(3591, MapiPropertyType.Integer);
  msgToAttach.Item.SetExtendedProperty(sent, "1");
  ```

## <a name="add-an-existing-item-to-a-new-email-by-using-the-mimecontent-and-ews"></a><span data-ttu-id="cdee3-160">Adicionar um item existente para um novo email usando o EWS e MimeContent</span><span class="sxs-lookup"><span data-stu-id="cdee3-160">Add an existing item to a new email by using the MimeContent and EWS</span></span>
<span data-ttu-id="cdee3-161"><a name="bk_addexistingemailews"> </a></span><span class="sxs-lookup"><span data-stu-id="cdee3-161"></span></span>

<span data-ttu-id="cdee3-162">Há duas maneiras de adicionar um item existente para um novo item:</span><span class="sxs-lookup"><span data-stu-id="cdee3-162">There are two ways to add an existing item to a new item:</span></span> 
  
1. <span data-ttu-id="cdee3-163">Se você estiver trabalhando com mensagens de email especificamente, você pode copiar o valor do elemento [MimeContent](http://msdn.microsoft.com/library/4f472a08-5653-4c54-ba65-831dfe32f20f%28Office.15%29.aspx) de email para o item recém-criado de anexo.</span><span class="sxs-lookup"><span data-stu-id="cdee3-163">If you're working with email messages specifically, you can copy the value of the [MimeContent](http://msdn.microsoft.com/library/4f472a08-5653-4c54-ba65-831dfe32f20f%28Office.15%29.aspx) element from the email into the newly created item attachment.</span></span> <span data-ttu-id="cdee3-164">Você perderá algumas propriedades durante esse processo, como categorias e os sinalizadores de acompanhamento, mas ele é muito útil para mensagens de email padrão.</span><span class="sxs-lookup"><span data-stu-id="cdee3-164">You will lose some properties during this process, such as follow up flags and categories, but it works great for standard email messages.</span></span> 
    
2. <span data-ttu-id="cdee3-165">Se você precisar com fidelidade total para todos os tipos de item, você pode vincular a um item existente e copiar todas as propriedades e propriedades estendidas para o novo anexo.</span><span class="sxs-lookup"><span data-stu-id="cdee3-165">If you need full fidelity for all item types, you can bind to an existing item and copy all the properties and extended properties into the new attachment.</span></span>
    
<span data-ttu-id="cdee3-166">O exemplo de código a seguir mostra como usar o elemento **MimeContent** para copiar o conteúdo do item original para o valor de **MimeContent** do anexo novo item.</span><span class="sxs-lookup"><span data-stu-id="cdee3-166">The following code example shows how to use the **MimeContent** element to copy the content of the original item into the **MimeContent** value of the new item attachment.</span></span> <span data-ttu-id="cdee3-167">O exemplo utiliza as seguintes operações:</span><span class="sxs-lookup"><span data-stu-id="cdee3-167">The example uses the following operations:</span></span> 
  
1. <span data-ttu-id="cdee3-168">[GetItem](http://msdn.microsoft.com/library/e3590b8b-c2a7-4dad-a014-6360197b68e4%28Office.15%29.aspx) — para obter o **MimeContent** e o [assunto](http://msdn.microsoft.com/library/c140d6c2-deb1-4f67-a908-9397197c4ae7%28Office.15%29.aspx) da mensagem que se tornará o anexo do item na nova mensagem.</span><span class="sxs-lookup"><span data-stu-id="cdee3-168">[GetItem](http://msdn.microsoft.com/library/e3590b8b-c2a7-4dad-a014-6360197b68e4%28Office.15%29.aspx) — To get the **MimeContent** and [Subject](http://msdn.microsoft.com/library/c140d6c2-deb1-4f67-a908-9397197c4ae7%28Office.15%29.aspx) of the message that will become the item attachment on the new message.</span></span> 
    
2. <span data-ttu-id="cdee3-169">[CreateItem](http://msdn.microsoft.com/library/fe6bb7fc-8918-4e6e-b0a1-b7e0ef44c3d1%28Office.15%29.aspx) — para criar a nova mensagem de email.</span><span class="sxs-lookup"><span data-stu-id="cdee3-169">[CreateItem](http://msdn.microsoft.com/library/fe6bb7fc-8918-4e6e-b0a1-b7e0ef44c3d1%28Office.15%29.aspx) — To create the new email message.</span></span> 
    
3. <span data-ttu-id="cdee3-170">[CreateAttachment](http://msdn.microsoft.com/library/e066db95-6963-4507-a8d0-8efad287f550%28Office.15%29.aspx)— para criar o novo anexo, usando o **assunto** e **MimeContent** recuperados pela operação de **GetItem** .</span><span class="sxs-lookup"><span data-stu-id="cdee3-170">[CreateAttachment](http://msdn.microsoft.com/library/e066db95-6963-4507-a8d0-8efad287f550%28Office.15%29.aspx)— To create the new attachment, using the **MimeContent** and **Subject** retrieved by the **GetItem** operation.</span></span> 
    
4. <span data-ttu-id="cdee3-171">[SendItem](http://msdn.microsoft.com/library/337b89ef-e1b7-45ed-92f3-8abe4200e4c7%28Office.15%29.aspx) — para enviar e salvar a mensagem.</span><span class="sxs-lookup"><span data-stu-id="cdee3-171">[SendItem](http://msdn.microsoft.com/library/337b89ef-e1b7-45ed-92f3-8abe4200e4c7%28Office.15%29.aspx) — To send and save the message.</span></span> 
    
<span data-ttu-id="cdee3-172">O exemplo começa recuperando o **MimeContent** e o **assunto** do item existente.</span><span class="sxs-lookup"><span data-stu-id="cdee3-172">The example starts by retrieving the **MimeContent** and the **Subject** of the existing item.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
               xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages"
               xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types"
               xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Body>
    <m:GetItem>
      <m:ItemShape>
        <t:BaseShape>IdOnly</t:BaseShape>
        <t:AdditionalProperties>
          <t:FieldURI FieldURI="item:MimeContent" />
          <t:FieldURI FieldURI="item:Subject" />
        </t:AdditionalProperties>
      </m:ItemShape>
      <m:ItemIds>
        <t:ItemId Id="jCrTAAA=" />
      </m:ItemIds>
    </m:GetItem>
  </soap:Body>
</soap:Envelope>
```

<span data-ttu-id="cdee3-173">O servidor responde à solicitação **GetItem** com uma mensagem de [GetItemResponse](http://msdn.microsoft.com/library/8b66de1b-26a6-476c-9585-a96059125716%28Office.15%29.aspx) que inclui um valor de [ResponseCode](http://msdn.microsoft.com/pt-br/library/aa580757%28v=exchg.150%29.aspx) do **NoError**, que indica que o email foi recuperado com êxito, a **MimeContent** e ** Assunto** do email.</span><span class="sxs-lookup"><span data-stu-id="cdee3-173">The server responds to the **GetItem** request with a [GetItemResponse](http://msdn.microsoft.com/library/8b66de1b-26a6-476c-9585-a96059125716%28Office.15%29.aspx) message that includes a [ResponseCode](http://msdn.microsoft.com/pt-br/library/aa580757%28v=exchg.150%29.aspx) value of **NoError**, which indicates that the email was retrieved successfully, and the **MimeContent** and **Subject** of the email.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<s:Envelope xmlns:s="http://schemas.xmlsoap.org/soap/envelope/">
  <s:Header>
    <h:ServerVersionInfo MajorVersion="15"
                         MinorVersion="0"
                         MajorBuildNumber="944"
                         MinorBuildNumber="11"
                         Version="V2_12"
                         xmlns:h="http://schemas.microsoft.com/exchange/services/2006/types"
                         xmlns="http://schemas.microsoft.com/exchange/services/2006/types"
                         xmlns:xsd="http://www.w3.org/2001/XMLSchema"
                         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" />
  </s:Header>
  <s:Body xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
          xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <m:GetItemResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages"
                       xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
      <m:ResponseMessages>
        <m:GetItemResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:Items>
            <t:Message>
              <t:MimeContent CharacterSet="UTF-8">tDQe/Eo=…</t:MimeContent>
              <t:ItemId Id="jCrTAAA="
                        ChangeKey="CQAAABYAAAAFI5DJmZv+TLtyLOLIF1S5AAAZi+7u" />
              <t:Subject>Play tennis?</t:Subject>
            </t:Message>
          </m:Items>
        </m:GetItemResponseMessage>
      </m:ResponseMessages>
    </m:GetItemResponse>
  </s:Body>
</s:Envelope>
```

<span data-ttu-id="cdee3-174">Em seguida, chame a operação **CreateItem** para criar o novo email.</span><span class="sxs-lookup"><span data-stu-id="cdee3-174">Next, call the **CreateItem** operation to create the new email.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
               xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages"
               xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types"
               xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2010" />
  </soap:Header>
  <soap:Body>
    <m:CreateItem MessageDisposition="SaveOnly">
      <m:Items>
        <t:Message>
          <t:Subject>Message with Item Attachment (MimeContent)</t:Subject>
          <t:Body BodyType="HTML">The attachment to this message was created by copying the MimeContent from the original message and adding it to a new item attachment.</t:Body>
          <t:ToRecipients>
            <t:Mailbox>
              <t:EmailAddress>primary@contoso1000.onmicrosoft.com</t:EmailAddress>
            </t:Mailbox>
          </t:ToRecipients>
        </t:Message>
      </m:Items>
    </m:CreateItem>
  </soap:Body>
</soap:Envelope>
```

<span data-ttu-id="cdee3-175">O servidor responde à solicitação **CreateItem** com uma mensagem de [CreateItemResponse](http://msdn.microsoft.com/library/742a46a0-2475-45a0-b44f-90639a3f5a43%28Office.15%29.aspx) que inclui um valor de [ResponseCode](http://msdn.microsoft.com/pt-br/library/aa580757%28v=exchg.150%29.aspx) de **NoError**, que indica se o email foi criado com êxito.</span><span class="sxs-lookup"><span data-stu-id="cdee3-175">The server responds to the **CreateItem** request with a [CreateItemResponse](http://msdn.microsoft.com/library/742a46a0-2475-45a0-b44f-90639a3f5a43%28Office.15%29.aspx) message that includes a [ResponseCode](http://msdn.microsoft.com/pt-br/library/aa580757%28v=exchg.150%29.aspx) value of **NoError**, which indicates that the email was created successfully.</span></span>
  
<span data-ttu-id="cdee3-176">Em seguida, crie o novo anexo de item usando o **MimeContent** e o **assunto** recuperados pela operação de **GetItem** .</span><span class="sxs-lookup"><span data-stu-id="cdee3-176">Next, create the new item attachment by using the **MimeContent** and **Subject** retrieved by the **GetItem** operation.</span></span> <span data-ttu-id="cdee3-177">O valor do elemento [ParentItemId](http://msdn.microsoft.com/library/72dc4391-72db-44d2-85d9-4718d59886a7%28Office.15%29.aspx) é preenchido com o valor de **ItemId** retornado na resposta **CreateItem** .</span><span class="sxs-lookup"><span data-stu-id="cdee3-177">The value of the [ParentItemId](http://msdn.microsoft.com/library/72dc4391-72db-44d2-85d9-4718d59886a7%28Office.15%29.aspx) element is populated by using the **ItemId** value returned in the **CreateItem** response.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
               xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages"
               xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types"
               xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2010" />
  </soap:Header>
  <soap:Body>
    <m:CreateAttachment>
      <m:ParentItemId Id="jDKsAAA=" />
      <m:Attachments>
        <t:ItemAttachment>
          <t:Name>Play tennis?</t:Name>
          <t:IsInline>false</t:IsInline>
          <t:Message>
            <t:MimeContent CharacterSet="UTF-8">tDQe/Eo=…</t:MimeContent>
          </t:Message>
        </t:ItemAttachment>
      </m:Attachments>
    </m:CreateAttachment>
  </soap:Body>
</soap:Envelope>
```

<span data-ttu-id="cdee3-178">O servidor responde à solicitação **CreateAttachment** com uma mensagem de [CreateAttachmentResponse](http://msdn.microsoft.com/library/cf6bd8bb-5317-4a03-bd75-297dd359b5da%28Office.15%29.aspx) que inclui um valor de [ResponseCode](http://msdn.microsoft.com/pt-br/library/aa580757%28v=exchg.150%29.aspx) de **NoError**, que indica que o anexo foi criado com êxito e o [ AttachmentId](http://msdn.microsoft.com/library/55a5fd77-60d1-40fa-8144-770600cedc6a%28Office.15%29.aspx) do anexo recém-criado.</span><span class="sxs-lookup"><span data-stu-id="cdee3-178">The server responds to the **CreateAttachment** request with a [CreateAttachmentResponse](http://msdn.microsoft.com/library/cf6bd8bb-5317-4a03-bd75-297dd359b5da%28Office.15%29.aspx) message that includes a [ResponseCode](http://msdn.microsoft.com/pt-br/library/aa580757%28v=exchg.150%29.aspx) value of **NoError**, which indicates that the attachment was created successfully, and the [AttachmentId](http://msdn.microsoft.com/library/55a5fd77-60d1-40fa-8144-770600cedc6a%28Office.15%29.aspx) of the newly created attachment.</span></span> 
  
<span data-ttu-id="cdee3-179">Agora que a nova mensagem tiver sido criada, e o item foi anexado, você poderá [Enviar a mensagem de dados criado recentemente](how-to-send-email-messages-by-using-ews-in-exchange.md) chamando-se a operação [SendItem](http://msdn.microsoft.com/library/337b89ef-e1b7-45ed-92f3-8abe4200e4c7%28Office.15%29.aspx) .</span><span class="sxs-lookup"><span data-stu-id="cdee3-179">Now that the new message has been created, and the item was attached, you can [send this newly created message](how-to-send-email-messages-by-using-ews-in-exchange.md) by calling the [SendItem](http://msdn.microsoft.com/library/337b89ef-e1b7-45ed-92f3-8abe4200e4c7%28Office.15%29.aspx) operation.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
               xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages"
               xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types"
               xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2010" />
  </soap:Header>
  <soap:Body>
    <m:SendItem SaveItemToFolder="true">
      <m:ItemIds>
        <t:ItemId Id="jDKsAAA="
                  ChangeKey="CQAAABYAAAAFI5DJmZv+TLtyLOLIF1S5AAAZi/q/" />
      </m:ItemIds>
      <m:SavedItemFolderId>
        <t:DistinguishedFolderId Id="sentitems" />
      </m:SavedItemFolderId>
    </m:SendItem>
  </soap:Body>
</soap:Envelope>
```

<span data-ttu-id="cdee3-180">O servidor responde à solicitação **SendItem** com uma mensagem de [SendItemResponse](http://msdn.microsoft.com/library/26ac41c7-57d9-473e-ab7a-bae93e1d2aba%28Office.15%29.aspx) que inclui um valor de [ResponseCode](http://msdn.microsoft.com/library/4b84d670-74c9-4d6d-84e7-f0a9f76f0d93%28Office.15%29.aspx) de **NoError**, que indica que o email foi enviado com êxito.</span><span class="sxs-lookup"><span data-stu-id="cdee3-180">The server responds to the **SendItem** request with a [SendItemResponse](http://msdn.microsoft.com/library/26ac41c7-57d9-473e-ab7a-bae93e1d2aba%28Office.15%29.aspx) message that includes a [ResponseCode](http://msdn.microsoft.com/library/4b84d670-74c9-4d6d-84e7-f0a9f76f0d93%28Office.15%29.aspx) value of **NoError**, which indicates that the email was sent successfully.</span></span>
  
## <a name="create-an-email-with-an-inline-attachment-by-using-the-ews-managed-api"></a><span data-ttu-id="cdee3-181">Criar um email com um anexo em linha, usando a API gerenciada de EWS</span><span class="sxs-lookup"><span data-stu-id="cdee3-181">Create an email with an inline attachment by using the EWS Managed API</span></span>
<span data-ttu-id="cdee3-182"><a name="bk_createinlineattachewsma"> </a></span><span class="sxs-lookup"><span data-stu-id="cdee3-182"></span></span>

<span data-ttu-id="cdee3-183">O exemplo de código a seguir mostra como criar um email com um anexo em linha por:</span><span class="sxs-lookup"><span data-stu-id="cdee3-183">The following code example shows how to create an email with an inline attachment by:</span></span>
  
1. <span data-ttu-id="cdee3-184">Usando o objeto [EmailMessage](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.emailmessage%28v=exchg.80%29.aspx) para criar uma mensagem de email.</span><span class="sxs-lookup"><span data-stu-id="cdee3-184">Using the [EmailMessage](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.emailmessage%28v=exchg.80%29.aspx) object to create an email message.</span></span> 
    
2. <span data-ttu-id="cdee3-185">Definindo a propriedade [EmailMessage.Body](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.item.body%28v=exchg.80%29.aspx) para um corpo HTML que inclui um anexo em linha.</span><span class="sxs-lookup"><span data-stu-id="cdee3-185">Setting the [EmailMessage.Body](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.item.body%28v=exchg.80%29.aspx) property to an HTML body that includes an inline attachment.</span></span> 
    
3. <span data-ttu-id="cdee3-186">Usando o método [AttachmentCollection.AddFileAttachment](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.attachmentcollection.addfileattachment%28v=exchg.80%29.aspx) para adicionar o anexo à mensagem.</span><span class="sxs-lookup"><span data-stu-id="cdee3-186">Using the [AttachmentCollection.AddFileAttachment](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.attachmentcollection.addfileattachment%28v=exchg.80%29.aspx) method to add the attachment to the message.</span></span> 
    
4. <span data-ttu-id="cdee3-187">Usando o método [EmailMessage.SendAndSaveCopy](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.emailmessage.sendandsavecopy%28v=exchg.80%29.aspx) para enviar a mensagem ao destinatário e salve a mensagem na pasta Itens enviados.</span><span class="sxs-lookup"><span data-stu-id="cdee3-187">Using the [EmailMessage.SendAndSaveCopy](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.emailmessage.sendandsavecopy%28v=exchg.80%29.aspx) method to send the message to the recipient and save the message in the Sent Items folder.</span></span> 
    
<span data-ttu-id="cdee3-188">Este exemplo supõe que esse **serviço** é um objeto válido do [ExchangeService](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.exchangeservice%28v=exchg.80%29.aspx) e que o usuário foi autenticado com um servidor Exchange.</span><span class="sxs-lookup"><span data-stu-id="cdee3-188">This example assumes that **service** is a valid [ExchangeService](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.exchangeservice%28v=exchg.80%29.aspx) object and that the user has been authenticated to an Exchange server.</span></span> 
  
```cs
public static void CreateEmailWithInlineAttachment(ExchangeService service)
{
    // Create the HTML body with the content identifier of the attachment.
    string html = @"<html>
                        <head>
                        </head>
                        <body>
                        <img width=100 height=100 id=""1"" src=""cid:Party.jpg"">
                        </body>
                        </html>";
         
    // Create the email message.
    EmailMessage message = new EmailMessage(service);
    message.Subject = "Inline Attachment";
    message.Body = new MessageBody(BodyType.HTML, html);
    message.ToRecipients.Add("sadie@contoso.com");
    // Add the attachment to the local copy of the email message.
    string file = @"C:\Temp\Party.jpg";
    message.Attachments.AddFileAttachment("Party.jpg", file);
    message.Attachments[0].IsInline = true;
    message.Attachments[0].ContentId = "Party.jpg";
         
    // Send the mail and save a copy in the Sent Items folder.
    // This method results in a CreateItem and SendItem call to EWS.
    message.SendAndSaveCopy();
}
```

## <a name="create-an-email-with-an-inline-attachment-by-using-ews"></a><span data-ttu-id="cdee3-189">Criar um email com um anexo em linha usando o EWS</span><span class="sxs-lookup"><span data-stu-id="cdee3-189">Create an email with an inline attachment by using EWS</span></span>
<span data-ttu-id="cdee3-190"><a name="bk_createinlineattachewsma"> </a></span><span class="sxs-lookup"><span data-stu-id="cdee3-190"></span></span>

<span data-ttu-id="cdee3-191">O exemplo de código a seguir mostra como usar a operação [CreateItem](http://msdn.microsoft.com/library/fe6bb7fc-8918-4e6e-b0a1-b7e0ef44c3d1%28Office.15%29.aspx) para criar uma mensagem de email com um anexo de arquivo embutida.</span><span class="sxs-lookup"><span data-stu-id="cdee3-191">The following code example shows how to use the [CreateItem](http://msdn.microsoft.com/library/fe6bb7fc-8918-4e6e-b0a1-b7e0ef44c3d1%28Office.15%29.aspx) operation to create an email message with an inline file attachment.</span></span> <span data-ttu-id="cdee3-192">O atributo **BodyType** do elemento [Body](http://msdn.microsoft.com/library/7851ea9b-9f87-4adc-a26f-7a27df4a9bca%28Office.15%29.aspx) indica que o conteúdo está no formato HTML e inclui a origem da imagem.</span><span class="sxs-lookup"><span data-stu-id="cdee3-192">The **BodyType** attribute of the [Body](http://msdn.microsoft.com/library/7851ea9b-9f87-4adc-a26f-7a27df4a9bca%28Office.15%29.aspx) element indicates that the content is in HTML format and includes the image source.</span></span> <span data-ttu-id="cdee3-193">Isso também é uma das solicitações de XML que o EWS Managed API envia quando você usar a API gerenciada de EWS para [criar um email com um anexo em linha](#bk_createinlineattachewsma).</span><span class="sxs-lookup"><span data-stu-id="cdee3-193">This is also one of the XML requests that the EWS Managed API sends when you use the EWS Managed API to [create an email with an inline attachment](#bk_createinlineattachewsma).</span></span>
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
               xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages"
               xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types"
               xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2010" />
  </soap:Header>
  <soap:Body>
    <m:CreateItem MessageDisposition="SaveOnly">
      <m:Items>
        <t:Message>
          <t:Subject>Inline Attachment</t:Subject>
          <t:Body BodyType="HTML">
            &amp;lt;html&amp;gt;
            &amp;lt;head&amp;gt;
            &amp;lt;/head&amp;gt;
            &amp;lt;body&amp;gt;
            &amp;lt;img width=100 height=100 id="1" src="cid:Party.jpg"&amp;gt;
            &amp;lt;/body&amp;gt;
            &amp;lt;/html&amp;gt;
          </t:Body>
          <t:ToRecipients>
            <t:Mailbox>
              <t:EmailAddress>sadie@contoso.com</t:EmailAddress>
            </t:Mailbox>
          </t:ToRecipients>
        </t:Message>
      </m:Items>
    </m:CreateItem>
  </soap:Body>
</soap:Envelope>
```

<span data-ttu-id="cdee3-194">O servidor responde à solicitação **CreateItem** com uma mensagem de [CreateItemResponse](http://msdn.microsoft.com/library/742a46a0-2475-45a0-b44f-90639a3f5a43%28Office.15%29.aspx) que inclui um valor de [ResponseCode](http://msdn.microsoft.com/pt-br/library/aa580757%28v=exchg.150%29.aspx) de **NoError**, que indica se o email foi criado com êxito e o [ItemId](http://msdn.microsoft.com/library/3350b597-57a0-4961-8f44-8624946719b4%28Office.15%29.aspx) do recentemente mensagem criada.</span><span class="sxs-lookup"><span data-stu-id="cdee3-194">The server responds to the **CreateItem** request with a [CreateItemResponse](http://msdn.microsoft.com/library/742a46a0-2475-45a0-b44f-90639a3f5a43%28Office.15%29.aspx) message that includes a [ResponseCode](http://msdn.microsoft.com/pt-br/library/aa580757%28v=exchg.150%29.aspx) value of **NoError**, which indicates that the email was created successfully, and the [ItemId](http://msdn.microsoft.com/library/3350b597-57a0-4961-8f44-8624946719b4%28Office.15%29.aspx) of the newly created message.</span></span> 
  
<span data-ttu-id="cdee3-195">Para [Enviar a mensagem de dados criado recentemente](how-to-send-email-messages-by-using-ews-in-exchange.md), chame a operação [SendItem](http://msdn.microsoft.com/library/337b89ef-e1b7-45ed-92f3-8abe4200e4c7%28Office.15%29.aspx) .</span><span class="sxs-lookup"><span data-stu-id="cdee3-195">To [send this newly created message](how-to-send-email-messages-by-using-ews-in-exchange.md), call the [SendItem](http://msdn.microsoft.com/library/337b89ef-e1b7-45ed-92f3-8abe4200e4c7%28Office.15%29.aspx) operation.</span></span> 
  
## <a name="add-an-attachment-to-an-existing-email-by-using-the-ews-managed-api"></a><span data-ttu-id="cdee3-196">Adicionar um anexo a um email existente usando a API gerenciada de EWS</span><span class="sxs-lookup"><span data-stu-id="cdee3-196">Add an attachment to an existing email by using the EWS Managed API</span></span>
<span data-ttu-id="cdee3-197"><a name="bk_createinlineattachewsma"> </a></span><span class="sxs-lookup"><span data-stu-id="cdee3-197"></span></span>

<span data-ttu-id="cdee3-198">O exemplo de código a seguir mostra como adicionar um anexo a um email existente por:</span><span class="sxs-lookup"><span data-stu-id="cdee3-198">The following code example shows how to add an attachment to an existing email by:</span></span> 
  
1. <span data-ttu-id="cdee3-199">Usando o método [EmailMessage.Bind](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.emailmessage.bind%28v=exchg.80%29.aspx) para associar a uma mensagem de email existente.</span><span class="sxs-lookup"><span data-stu-id="cdee3-199">Using the [EmailMessage.Bind](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.emailmessage.bind%28v=exchg.80%29.aspx) method to bind to an existing email message.</span></span> 
    
2. <span data-ttu-id="cdee3-200">Adicionando um anexo de arquivo à mensagem usando o método **AddFileAttachment** .</span><span class="sxs-lookup"><span data-stu-id="cdee3-200">Adding a file attachment to the message by using the **AddFileAttachment** method.</span></span> 
    
3. <span data-ttu-id="cdee3-201">Salvando as atualizações ao chamar o método [EmailMessage.Update](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.emailmessage.update%28v=exchg.80%29.aspx) .</span><span class="sxs-lookup"><span data-stu-id="cdee3-201">Saving the updates by calling the [EmailMessage.Update](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.emailmessage.update%28v=exchg.80%29.aspx) method.</span></span> 
    
<span data-ttu-id="cdee3-202">Este exemplo supõe que esse **serviço** é um objeto válido do [ExchangeService](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.exchangeservice%28v=exchg.80%29.aspx) e que o usuário foi autenticado com um servidor Exchange.</span><span class="sxs-lookup"><span data-stu-id="cdee3-202">This example assumes that **service** is a valid [ExchangeService](http://msdn.microsoft.com/pt-br/library/microsoft.exchange.webservices.data.exchangeservice%28v=exchg.80%29.aspx) object and that the user has been authenticated to an Exchange server.</span></span> 
  
```XML
public static void AddAttachmentToExisting(ExchangeService service, ItemId itemId)
{
    // This method results in a GetItem call to EWS.
    EmailMessage message = EmailMessage.Bind(service, itemId);
    message.Attachments.AddFileAttachment("C:\\temp\\FileAttachment.txt");
    // This method results in a CreateAttachment call to EWS.
    message.Update(ConflictResolutionMode.AlwaysOverwrite);
}
```

## <a name="add-an-attachment-to-an-existing-email-by-using-ews"></a><span data-ttu-id="cdee3-203">Adicionar um anexo a um email existente usando o EWS</span><span class="sxs-lookup"><span data-stu-id="cdee3-203">Add an attachment to an existing email by using EWS</span></span>
<span data-ttu-id="cdee3-204"><a name="bk_createinlineattachewsma"> </a></span><span class="sxs-lookup"><span data-stu-id="cdee3-204"></span></span>

<span data-ttu-id="cdee3-205">O exemplo de código a seguir mostra como usar a operação [CreateAttachment](http://msdn.microsoft.com/library/e066db95-6963-4507-a8d0-8efad287f550%28Office.15%29.aspx) para adicionar um anexo de arquivo a uma mensagem de email existente.</span><span class="sxs-lookup"><span data-stu-id="cdee3-205">The following code example shows how to use the [CreateAttachment](http://msdn.microsoft.com/library/e066db95-6963-4507-a8d0-8efad287f550%28Office.15%29.aspx) operation to add a file attachment to an existing email message.</span></span> <span data-ttu-id="cdee3-206">Isso também é uma das solicitações de XML que o EWS Managed API envia quando você usar a API gerenciada de EWS para [Adicionar um anexo a um email existente](#bk_createinlineattachewsma).</span><span class="sxs-lookup"><span data-stu-id="cdee3-206">This is also one of the XML requests that the EWS Managed API sends when you use the EWS Managed API to [add an attachment to an existing email](#bk_createinlineattachewsma).</span></span>
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
               xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages"
               xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types"
               xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2007_SP1" />
    <t:TimeZoneContext>
      <t:TimeZoneDefinition Id="Central Standard Time" />
    </t:TimeZoneContext>
  </soap:Header>
  <soap:Body>
    <m:CreateAttachment>
      <m:ParentItemId Id="uqE2AAA=" />
      <m:Attachments>
        <t:FileAttachment>
          <t:Name>FileAttachment.txt</t:Name>
          <t:Content>VGhpcyBpcyBhIGZpbGUgYXR0YWNobWVudC4=</t:Content>
        </t:FileAttachment>
      </m:Attachments>
    </m:CreateAttachment>
  </soap:Body>
</soap:Envelope>
```

<span data-ttu-id="cdee3-207">O servidor responde à solicitação **CreateAttachment** com uma mensagem de [CreateAttachmentResponse](http://msdn.microsoft.com/library/cf6bd8bb-5317-4a03-bd75-297dd359b5da%28Office.15%29.aspx) que inclui um valor de [ResponseCode](http://msdn.microsoft.com/pt-br/library/aa580757%28v=exchg.150%29.aspx) de **NoError**, que indica que o anexo foi criado com êxito e o [ AttachmentId](http://msdn.microsoft.com/library/55a5fd77-60d1-40fa-8144-770600cedc6a%28Office.15%29.aspx) do anexo recém-criado.</span><span class="sxs-lookup"><span data-stu-id="cdee3-207">The server responds to the **CreateAttachment** request with a [CreateAttachmentResponse](http://msdn.microsoft.com/library/cf6bd8bb-5317-4a03-bd75-297dd359b5da%28Office.15%29.aspx) message that includes a [ResponseCode](http://msdn.microsoft.com/pt-br/library/aa580757%28v=exchg.150%29.aspx) value of **NoError**, which indicates that the attachment was created successfully, and the [AttachmentId](http://msdn.microsoft.com/library/55a5fd77-60d1-40fa-8144-770600cedc6a%28Office.15%29.aspx) of the newly created attachment.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<s:Envelope xmlns:s="http://schemas.xmlsoap.org/soap/envelope/">
  <s:Header>
    <h:ServerVersionInfo MajorVersion="15"
                         MinorVersion="0"
                         MajorBuildNumber="939"
                         MinorBuildNumber="12"
                         Version="V2_11"
                         xmlns:h="http://schemas.microsoft.com/exchange/services/2006/types"
                         xmlns="http://schemas.microsoft.com/exchange/services/2006/types"
                         xmlns:xsd="http://www.w3.org/2001/XMLSchema"
                         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" />
  </s:Header>
  <s:Body xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
          xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <m:CreateAttachmentResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages"
                                xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
      <m:ResponseMessages>
        <m:CreateAttachmentResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:Attachments>
            <t:FileAttachment>
              <t:AttachmentId Id="yRLhCh8="
                              RootItemId="uqE2AAA="
                              RootItemChangeKey="CQAAABYAAAAFI5DJmZv+TLtyLOLIF1S5AAAXulcf" />
            </t:FileAttachment>
          </m:Attachments>
        </m:CreateAttachmentResponseMessage>
      </m:ResponseMessages>
    </m:CreateAttachmentResponse>
  </s:Body>
</s:Envelope>
```

## <a name="see-also"></a><span data-ttu-id="cdee3-208">Confira também</span><span class="sxs-lookup"><span data-stu-id="cdee3-208">See also</span></span>


- [<span data-ttu-id="cdee3-209">EWS no Exchange e anexos</span><span class="sxs-lookup"><span data-stu-id="cdee3-209">Attachments and EWS in Exchange</span></span>](attachments-and-ews-in-exchange.md)
    
- [<span data-ttu-id="cdee3-210">Adicionar anexos usando o EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="cdee3-210">Add attachments by using EWS in Exchange</span></span>](how-to-add-attachments-by-using-ews-in-exchange.md)
    
- [<span data-ttu-id="cdee3-211">Excluir anexos usando o EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="cdee3-211">Delete attachments by using EWS in Exchange</span></span>](how-to-delete-attachments-by-using-ews-in-exchange.md)
    
- [<span data-ttu-id="cdee3-212">Obter anexos usando o EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="cdee3-212">Get attachments by using EWS in Exchange</span></span>](how-to-get-attachments-by-using-ews-in-exchange.md)
    
- [<span data-ttu-id="cdee3-213">Enviar mensagens de email usando o EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="cdee3-213">Send email messages by using EWS in Exchange</span></span>](how-to-send-email-messages-by-using-ews-in-exchange.md)
    

