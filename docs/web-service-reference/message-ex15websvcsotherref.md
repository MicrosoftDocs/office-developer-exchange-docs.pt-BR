---
title: Mensagem
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- Message
api_type:
- schema
ms.assetid: 2400b33c-43b2-4fc2-b6fb-275a99e0e810
description: O elemento Message representa uma mensagem de email do Microsoft Exchange.
ms.openlocfilehash: 510e97572e54f0ea0cb65fc7c75910e69cc0651f
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44467778"
---
# <a name="message"></a>Mensagem

O elemento **Message** representa uma mensagem de email do Microsoft Exchange. 
  
```xml
<Message>
   <MimeContent/>
   <ItemId/>
   <ParentFolderId/>
   <ItemClass/>
   <Subject/>
   <Sensitivity/>
   <Body/>
   <Attachments/>
   <DateTimeReceived/>
   <Size/>
   <Categories/>
   <Importance/>
   <InReplyTo/>
   <IsSubmitted/>
   <IsDraft/>
   <IsFromMe/>
   <IsResend/>
   <IsUnmodified/>
   <InternetMessageHeaders/>
   <DateTimeSent/>
   <DateTimeCreated/>
   <ResponseObjects/>
   <ReminderDueBy/>
   <ReminderIsSet/>
   <ReminderMinutesBeforeStart/>
   <DisplayCc/>
   <DisplayTo/>
   <HasAttachments/>
   <ExtendedProperty/>
   <Culture/>
   <Sender/>
   <ToRecipients/>
   <CcRecipients/>
   <BccRecipients/>
   <IsReadReceiptRequested/>
   <IsDeliveryReceiptRequested/>
   <ConversationIndex/>
   <ConversationTopic/>
   <From/>
   <InternetMessageId/>
   <IsRead/>
   <IsResponseRequested/>
   <References/>
   <ReplyTo/>
   <EffectiveRights/>
   <ReceivedBy/>
   <ReceivedRepresenting/>
   <LastModifiedName/>
   <LastModifiedTime/>
   <IsAssociated/>
   <WebClientReadFormQueryString/>
   <WebClientEditFormQueryString/>
   <ConversationId/>
   <UniqueBody/>
   <ReminderMessageData/>
</Message>
```

 **MessageType**
## <a name="attributes-and-elements"></a>Atributos e elementos

As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.
  
### <a name="attributes"></a>Atributos

Nenhum
  
### <a name="child-elements"></a>Elementos filho

|**Elemento**|**Descrição**|
|:-----|:-----|
|[MimeContent](mimecontent.md) <br/> |Contém o fluxo MIME (Multipurpose Internet Mail Extensions) nativo de um objeto representado no formato base64Binary.  <br/> |
|[ItemId](itemid.md) <br/> |Contém o identificador exclusivo e a chave de alteração de um item no repositório do Exchange. Essa propriedade é somente leitura.  <br/> |
|[ParentFolderId](parentfolderid.md) <br/> |Representa o identificador da pasta pai que contém o item ou a pasta. Essa propriedade é somente leitura.  <br/> |
|[ItemClass](itemclass.md) <br/> |Representa a classe de mensagem de um item.  <br/> |
|[Assunto](subject.md) <br/> |Representa o assunto de itens do repositório do Exchange e objetos de resposta. O assunto está limitado a 255 caracteres.  <br/> |
|[Sensitivity](sensitivity.md) <br/> |Indica o nível de sensibilidade de um item.  <br/> |
|[Body](body.md) <br/> |Representa o conteúdo real do corpo de uma mensagem.  <br/> |
|[Anexos](attachments-ex15websvcsotherref.md) <br/> |Contém os itens ou arquivos anexados a um item no repositório do Exchange.  <br/> |
|[DateTimeReceived](datetimereceived.md) <br/> |Representa a data e a hora em que um item foi recebido em uma caixa de correio.  <br/> |
|[Tamanho](size.md) <br/> |Representa o tamanho em bytes de um item. Essa propriedade é somente leitura.  <br/> |
|[Categorias](categories-ex15websvcsotherref.md) <br/> |Representa uma coleção de cadeias de caracteres que identificam a quais categorias um item da caixa de correio pertence.  <br/> |
|[Importance](importance.md) <br/> |Descreve a importância de um item.  <br/> |
|[Inresponderto](inreplyto.md) <br/> |Representa o identificador do item para o qual este item é uma resposta.  <br/> |
|[Isenviado](issubmitted.md) <br/> |Indica se um item foi enviado para a pasta padrão da pasta de saída.  <br/> |
|[IsDraft](isdraft.md) <br/> |Indica se um item ainda não foi enviado.  <br/> |
|[IsFromMe](isfromme.md) <br/> |Indica se um usuário enviou um item para ele.  <br/> |
|[IsResend](isresend.md) <br/> |Indica se o item foi enviado anteriormente.  <br/> |
|[IsUnmodified](isunmodified.md) <br/> |Indica se o item foi modificado.  <br/> |
|[Propriedadeinternetmessageheaders](internetmessageheaders.md) <br/> |Representa a coleção de todos os cabeçalhos de mensagens da Internet que estão contidos em um item em uma caixa de correio.  <br/> |
|[DateTimeSent](datetimesent.md) <br/> |Representa a data e a hora em que um item em uma caixa de correio foi enviado.  <br/> |
|[DateTimeCreated](datetimecreated.md) <br/> |Representa a data e a hora em que um determinado item da caixa de correio foi criado.  <br/> |
|[ResponseObjects](responseobjects.md) <br/> |Contém uma coleção de todos os objetos Response associados a um item no repositório do Exchange.  <br/> |
|[ReminderDueBy](reminderdueby.md) <br/> |Representa a data e a hora em que o evento ocorre. Isso é usado pelo elemento [ReminderMinutesBeforeStart](reminderminutesbeforestart.md) para determinar quando o lembrete é exibido.  <br/> |
|[ReminderIsSet](reminderisset.md) <br/> |Indica se um lembrete foi definido para um item no repositório do Exchange.  <br/> |
|[ReminderMinutesBeforeStart](reminderminutesbeforestart.md) <br/> |Representa o número de minutos antes de um evento quando um lembrete é exibido.  <br/> |
|[DisplayCc](displaycc.md) <br/> |Representa a cadeia de caracteres de exibição usada para o conteúdo da linha CC. Esta é a cadeia de caracteres concatenada de todos os nomes de exibição de destinatários CC.  <br/> |
|[DisplayTo](displayto.md) <br/> |Representa a cadeia de caracteres de exibição usada para o conteúdo da caixa para. Esta é a cadeia de caracteres concatenada de todos os nomes de exibição de destinatários.  <br/> |
|[HasAttachments](hasattachments.md) <br/> |Representa uma propriedade que é definida como **true** se um item tem pelo menos um anexo visível. Essa propriedade é somente leitura.  <br/> |
|[ExtendedProperty](extendedproperty.md) <br/> |Identifica as propriedades estendidas em pastas e itens.  <br/> |
|[Cultura](culture.md) <br/> |Representa a cultura de um determinado item em uma caixa de correio.  <br/> |
|[Sender](sender.md) <br/> |Identifica o remetente de um item.  <br/> |
|[ToRecipients](torecipients.md) <br/> |Contém um conjunto de destinatários de uma mensagem.  <br/> |
|[CcRecipients](ccrecipients.md) <br/> |Representa uma coleção de destinatários que receberão uma cópia da mensagem.  <br/> |
|[BccRecipients](bccrecipients.md) <br/> |Representa uma coleção de destinatários para receber uma cópia oculta (Cco) de uma mensagem de email.  <br/> |
|[IsReadReceiptRequested](isreadreceiptrequested.md) <br/> |Indica se o remetente de um item solicita uma confirmação de leitura.  <br/> |
|[IsDeliveryReceiptRequested](isdeliveryreceiptrequested.md) <br/> |Indica se o remetente de um item solicita uma confirmação de entrega.  <br/> |
|[ConversationIndex](conversationindex.md) <br/> |Contém uma ID binária que representa o thread ao qual esta mensagem pertence.  <br/> |
|[ConversationTopic](conversationtopic.md) <br/> |Representa o identificador de conversa.  <br/> |
|[De](from.md) <br/> |Representa o destinatário de quem a mensagem foi enviada.  <br/> |
|[InternetMessageId](internetmessageid.md) <br/> |Representa o identificador de mensagem da Internet de um item.  <br/> |
|[IsRead](isread.md) <br/> |Indica se uma mensagem foi lida.  <br/> |
|[IsResponseRequested](isresponserequested.md) <br/> |Indica se uma resposta a uma mensagem de email é solicitada.  <br/> |
|[References](references.md) <br/> |Representa o cabeçalho da Usenet que é usado para correlacionar respostas com suas mensagens originais.  <br/> |
|[ReplyTo](replyto.md) <br/> |Identifica um conjunto de endereços para os quais as respostas devem ser enviadas.  <br/> |
|[EffectiveRights](effectiverights.md) <br/> |Contém os direitos do cliente com base nas configurações de permissão para o item ou pasta. Este elemento é somente leitura.  <br/> |
|[ReceivedBy](receivedby.md) <br/> |Identifica o representante em um cenário de acesso de representante.  <br/> |
|[ReceivedRepresenting](receivedrepresenting.md) <br/> |Identifica o principal em um cenário de acesso de representante.  <br/> |
|[LastModified](lastmodifiedname.md) <br/> |Contém o nome de exibição do último usuário a modificar um item.  <br/> |
|[LastModifiedTime](lastmodifiedtime.md) <br/> |Indica quando um item foi modificado pela última vez.  <br/> |
|[Isassociated](isassociated.md) <br/> |Indica se o item está associado a uma pasta.  <br/> |
|[WebClientReadFormQueryString](webclientreadformquerystring.md) <br/> |Representa uma URL para concatenar ao ponto de extremidade do Microsoft Office Outlook Web App para ler um item no Outlook Web App.  <br/> |
|[WebClientEditFormQueryString](webclienteditformquerystring.md) <br/> |Representa uma URL para concatenar ao ponto de extremidade do Outlook Web App para editar um item no Outlook Web App.  <br/> |
|[ConversationId](conversationid.md) <br/> |Contém o identificador de um item ou uma conversa.  <br/> |
|[UniqueBody](uniquebody.md) <br/> |Representa um fragmento HTML ou texto sem formatação que representa o corpo exclusivo desta conversa.  <br/> |
|[ReminderMessageData](remindermessagedata.md) <br/> |Contém os dados de uma mensagem de lembrete.  <br/> |
   
### <a name="parent-elements"></a>Elementos pai

|**Elemento**|**Descrição**|
|:-----|:-----|
|[AdjacentMeetings](adjacentmeetings.md) <br/> |Descreve todos os itens de calendário adjacentes a um horário de reunião.  <br/> |
|[AppendToItemField](appendtoitemfield.md) <br/> |Identifica os dados a serem acrescentados a uma única propriedade de um item durante uma [operação UpdateItem](updateitem-operation.md).  <br/> |
|[ConflictingMeetings](conflictingmeetings.md) <br/> |Identifica todos os itens que entram em conflito com um horário de reunião.  <br/> |
|[Create (issync)](create-itemsync.md) <br/> |Identifica um único item a ser criado no armazenamento do cliente local.  <br/> |
|[ItemAttachment](itemattachment.md) <br/> |Representa um item do Exchange anexado a outro item do Exchange.  <br/> |
|[Itens](items.md) <br/> |Contém uma matriz de itens.  <br/> |
|[Itens (NonEmptyArrayOfAllItemsType)](items-nonemptyarrayofallitemstype.md) <br/> |Contém uma matriz de itens a serem criados na pasta que é identificada pelo elemento [ParentFolderId (TargetFolderIdType)](parentfolderid-targetfolderidtype.md) .  <br/> |
|[Setitemfield](setitemfield.md) <br/> |Representa uma atualização de uma única propriedade de um item em uma [operação UpdateItem](updateitem-operation.md).  <br/> |
|[Atualização (issync)](update-itemsync.md) <br/> |Identifica um único item a ser atualizado no repositório do cliente local.  <br/> |
   
## <a name="text-value"></a>Valor de texto

Nenhum.
  
## <a name="remarks"></a>Comentários

Outro elemento de **mensagem** , [Message (disponibilidade)](message-availability.md) é usado pelas operações de disponibilidade para retornar mensagens de ausência temporária. 
  
Os elementos da [mensagem](message-ex15websvcsotherref.md) representam mensagens de email e todos os outros itens que não são digitados com rigidez pelo esquema dos serviços Web do Exchange (EWS). Itens como IPM. O compartilhamento e o IPM. InfoPath são retornados como elementos de **mensagem** . O Exchange 2010 não retorna o elemento de **Item** base nas respostas. 
  
O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.
  
## <a name="element-information"></a>Elemento de informações

|||
|:-----|:-----|
|Namespace  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|Nome do esquema  <br/> |Esquema de tipos  <br/> |
|Arquivo de validação  <br/> |Types. xsd  <br/> |
|Pode ser vazio  <br/> |False  <br/> |
   
## <a name="see-also"></a>Confira também



- [Elementos XML do EWS no Exchange](ews-xml-elements-in-exchange.md)

