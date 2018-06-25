---
title: MeetingRequest
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- MeetingRequest
api_type:
- schema
ms.assetid: c44f8804-a355-473d-a837-48cc91617251
description: O elemento MeetingRequest representa uma solicitação de reunião no armazenamento do Exchange.
ms.openlocfilehash: 3e290613293cb6ad1563912e5015742ffc503d08
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/25/2018
ms.locfileid: "19824450"
---
# <a name="meetingrequest"></a>MeetingRequest

O elemento **MeetingRequest** representa uma solicitação de reunião no armazenamento do Exchange. 
  
```xml
<MeetingRequest>
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
   <AssociatedCalendarItemId/>
   <IsDelegated/>
   <IsOutOfDate/>
   <HasBeenProcessed/>
   <ResponseType/>
   <MeetingRequestType/>
   <IntendedFreeBusyStatus/>
   <Start/>
   <End/>
   <OriginalStart/>
   <IsAllDayEvent/>
   <LegacyFreeBusyStatus/>
   <Location/>
   <When/>
   <IsMeeting/>
   <IsCancelled/>
   <IsRecurring/>
   <MeetingRequestWasSent/>
   <CalendarItemType/>
   <MyResponseType/>
   <Organizer/>
   <RequiredAttendees/>
   <OptionalAttendees/>
   <Resources/>
   <ConflictingMeetingCount/>
   <AdjacentMeetingCount/>
   <ConflictingMeetings/>
   <AdjacentMeetings/>
   <Duration/>
   <TimeZone/>
   <AppointmentReplyTime/>
   <AppointmentSequenceNumber/>
   <AppointmentState/>
   <Recurrence/>
   <FirstOccurrence/>
   <LastOccurrence/>
   <ModifiedOccurrences/>
   <DeletedOccurrences/>
   <MeetingTimeZone/>
   <StartTimeZone/>
   <EndTimeZone/>
   <ConferenceType/>
   <AllowNewTimeProposal/>
   <IsOnlineMeeting/>
   <MeetingWorkspaceUrl/>
   <NetShowUrl/>
   <EffectiveRights/>
   <LastModifiedName/>
   <LastModifiedTime/>
   <IsAssociated/>
   <WebClientReadFormQueryString/>
   <WebClientEditFormQueryString/>
   <ConversationId/>
   <UniqueBody/>
</MeetingRequest>
```

 **MeetingRequestMessageType**
## <a name="attributes-and-elements"></a>Attributes and elements

As seções a seguir descrevem os atributos e elementos filho elementos pai.
  
### <a name="attributes"></a>Atributos

Nenhum.
  
### <a name="child-elements"></a>Elementos filho

|**Elemento**|**Descrição**|
|:-----|:-----|
|[MimeContent](mimecontent.md) <br/> |Contém o fluxo de email extensões MIME (Multipurpose Internet) nativo de um objeto representado no formato base64Binary.  <br/> |
|[ItemId](itemid.md) <br/> |Contém o identificador e alterar a chave exclusiva de um item no armazenamento do Exchange. Esta propriedade é somente leitura.  <br/> |
|[ParentFolderId](parentfolderid.md) <br/> |Representa o identificador da pasta pai que contém o item ou a pasta. Esta propriedade é somente leitura.  <br/> |
|[ItemClass](itemclass.md) <br/> |Representa a classe de mensagem de um item.  <br/> |
|[Assunto](subject.md) <br/> |Representa o assunto para armazenar itens do Exchange e objetos de resposta. O assunto é limitado a 255 caracteres.  <br/> |
|[Sensitivity](sensitivity.md) <br/> |Indica o nível de sensibilidade de um item.  <br/> |
|[Corpo](body.md) <br/> |Representa o conteúdo real do corpo de uma mensagem.  <br/> |
|[Anexos](attachments-ex15websvcsotherref.md) <br/> |Contém os itens ou arquivos que estejam anexados a um item no armazenamento do Exchange.  <br/> |
|[DateTimeReceived](datetimereceived.md) <br/> |Representa a data e hora em que um item em uma caixa de correio foi recebido.  <br/> |
|[Size](size.md) <br/> |Representa o tamanho em bytes de um item. Esta propriedade é somente leitura.  <br/> |
|[Categorias](categories-ex15websvcsotherref.md) <br/> |Representa uma coleção de cadeias de caracteres que identificam a quais categorias de um item na caixa de correio pertence.  <br/> |
|[Importância](importance.md) <br/> |Descreve a importância de um item.  <br/> |
|[InReplyTo](inreplyto.md) <br/> |Representa o identificador do item ao qual este item é uma resposta.  <br/> |
|[IsSubmitted](issubmitted.md) <br/> |Indica se um item foi enviado à pasta padrão caixa de saída.  <br/> |
|[IsDraft](isdraft.md) <br/> |Indica se um item ainda não foi enviado.  <br/> |
|[IsFromMe](isfromme.md) <br/> |Indica se um usuário enviada a um item para si mesma.  <br/> |
|[IsResend](isresend.md) <br/> |Indica se o item anteriormente foi enviado.  <br/> |
|[IsUnmodified](isunmodified.md) <br/> |Indica se o item foi modificado.  <br/> |
|[InternetMessageHeaders](internetmessageheaders.md) <br/> |Representa a coleção de todos os cabeçalhos de mensagem de Internet contida em um item em uma caixa de correio.  <br/> |
|[DateTimeSent](datetimesent.md) <br/> |Representa a data e hora em que um item em uma caixa de correio foi enviado.  <br/> |
|[DateTimeCreated](datetimecreated.md) <br/> |Representa a data e hora em que um determinado item na caixa de correio foi criado.  <br/> |
|[ResponseObjects](responseobjects.md) <br/> |Contém uma coleção de todos os objetos de resposta que estão associados um item no armazenamento do Exchange.  <br/> |
|[ReminderDueBy](reminderdueby.md) <br/> |Representa a data e hora quando o evento ocorre. Isso é usado pelo elemento [ReminderMinutesBeforeStart](reminderminutesbeforestart.md) para determinar quando o lembrete é exibido.  <br/> |
|[ReminderIsSet](reminderisset.md) <br/> |Indica se um lembrete tiver sido definido para um item no armazenamento do Exchange.  <br/> |
|[ReminderMinutesBeforeStart](reminderminutesbeforestart.md) <br/> |Representa o número de minutos antes de um evento, quando um lembrete é exibido.  <br/> |
|[DisplayCc](displaycc.md) <br/> |Representa a cadeia de caracteres de exibição que é usada para o conteúdo da linha CC. Esta é a cadeia de caracteres concatenada de todos os nomes de exibição destinatários CC.  <br/> |
|[DisplayTo](displayto.md) <br/> |Representa a cadeia de caracteres de exibição que é usada para o conteúdo da linha para. Esta é a cadeia de caracteres concatenada de todos os aos nomes de exibição do destinatário.  <br/> |
|[HasAttachments](hasattachments.md) <br/> |Representa uma propriedade que é definida como **true** se um item tem pelo menos um anexo visível. Essa propriedade é somente leitura.  <br/> |
|[ExtendedProperty](extendedproperty.md) <br/> |Identifica as propriedades estendidas em pastas e itens.  <br/> |
|[Cultura](culture.md) <br/> |Representa a cultura de um determinado item em uma caixa de correio.  <br/> |
|[Sender](sender.md) <br/> |Identifica o remetente de um item.  <br/> |
|[ToRecipients](torecipients.md) <br/> |Contém um conjunto de destinatários de uma mensagem.  <br/> |
|[CcRecipients](ccrecipients.md) <br/> |Representa uma coleção dos destinatários que receberão uma cópia da mensagem.  <br/> |
|[BccRecipients](bccrecipients.md) <br/> |Representa uma coleção de destinatários para receber uma cópia oculta (Cco) de um email.  <br/> |
|[IsReadReceiptRequested](isreadreceiptrequested.md) <br/> |Indica se o remetente de um item solicita uma confirmação de leitura.  <br/> |
|[IsDeliveryReceiptRequested](isdeliveryreceiptrequested.md) <br/> |Indica se o remetente de um item solicita uma confirmação de entrega.  <br/> |
|[ConversationIndex](conversationindex.md) <br/> |Contém uma ID binária que representa o segmento ao qual esta mensagem pertence.  <br/> |
|[ConversationTopic](conversationtopic.md) <br/> |Representa o identificador de conversa.  <br/> |
|[From](from.md) <br/> |Representa o destinatário de quem a mensagem foi enviada.  <br/> |
|[InternetMessageId](internetmessageid.md) <br/> |Representa o identificador de mensagem da Internet de um item.  <br/> |
|[Foi lido](isread.md) <br/> |Indica se uma mensagem foi lido.  <br/> |
|[IsResponseRequested](isresponserequested.md) <br/> |Indica se uma resposta a uma mensagem de email é solicitada.  <br/> |
|[Referências](references.md) <br/> |Representa o cabeçalho de Usenet é usado para correlacionar respostas com suas mensagens originais.  <br/> |
|[ReplyTo](replyto.md) <br/> |Identifica um conjunto de endereços para o qual as respostas devem ser enviadas.  <br/> |
|[AssociatedCalendarItemId](associatedcalendaritemid.md) <br/> |Representa o item de calendário que está associado um [MeetingMessage](meetingmessage.md).  <br/> |
|[IsDelegated](isdelegated.md) <br/> |Indica se uma reunião foi tratada por uma conta com acesso de representante.  <br/> |
|[IsOutOfDate](isoutofdate.md) <br/> |Indica se uma mensagem de reunião está desatualizada.  <br/> |
|[HasBeenProcessed](hasbeenprocessed.md) <br/> |Indica se uma mensagem de reunião item foi processada.  <br/> |
|[ResponseType](responsetype.md) <br/> |Representa o tipo de destinatário resposta recebida para uma reunião.  <br/> |
|[MeetingRequestType](meetingrequesttype.md) <br/> |Descreve o tipo de solicitação de reunião.  <br/> |
|[IntendedFreeBusyStatus](intendedfreebusystatus.md) <br/> |Representa o status desejado para o item de calendário que está associado à solicitação de reunião.  <br/> |
|[Start](start.md) <br/> |Representa o início de um item de calendário. Esse elemento só se aplica a uma única ocorrência de um item do calendário.  <br/> |
|[End](end-ex15websvcsotherref.md) <br/> |Representa o fim de uma duração. Esse elemento só se aplica a uma única ocorrência de um item do calendário.  <br/> |
|[OriginalStart](originalstart.md) <br/> |Representa a hora de início original de um item de calendário.  <br/> |
|[IsAllDayEvent](isalldayevent.md) <br/> |Indica se uma solicitação de reunião ou item de calendário representa um evento de dia inteiro.  <br/> |
|[LegacyFreeBusyStatus](legacyfreebusystatus.md) <br/> |Representa o status livre/ocupado do item de calendário.  <br/> |
|[Location](location.md) <br/> |Representa o local de uma reunião ou compromisso.  <br/> |
|[When](when.md) <br/> |Fornece uma descrição de quando ocorre a uma reunião.  <br/> |
|[IsMeeting](ismeeting.md) <br/> |Indica se o item do calendário é uma reunião ou um compromisso.  <br/> |
|[IsCancelled](iscancelled.md) <br/> |Indica se um compromisso ou reunião foi cancelada.  <br/> |
|[IsRecurring](isrecurring.md) <br/> |Indica se um item de calendário é parte de um item recorrente. Este elemento é somente leitura.  <br/> |
|[MeetingRequestWasSent](meetingrequestwassent.md) <br/> |Indica se foi enviada uma solicitação de reunião a participantes solicitados.  <br/> |
|[CalendarItemType](calendaritemtype.md) <br/> |Representa o tipo de ocorrência de um item de calendário.  <br/> |
|[MyResponseType](myresponsetype.md) <br/> |Contém o status da ou uma resposta a um item de calendário.  <br/> |
|[Organizer](organizer.md) <br/> |Representa o organizador de uma reunião.  <br/> |
|[RequiredAttendees](requiredattendees.md) <br/> |Representa os participantes necessários para participar de uma reunião.  <br/> |
|[OptionalAttendees](optionalattendees.md) <br/> |Representa a participantes que não são necessárias para participar de uma reunião.  <br/> |
|[Recursos](resources.md) <br/> |Representa um recurso agendado para uma reunião.  <br/> |
|[ConflictingMeetingCount](conflictingmeetingcount.md) <br/> |Representa o número de reuniões que estão em conflito com a solicitação de reunião.  <br/> |
|[AdjacentMeetingCount](adjacentmeetingcount.md) <br/> |Representa o número total de itens de calendário que sejam adjacentes um horário de reunião.  <br/> |
|[ConflictingMeetings](conflictingmeetings.md) <br/> |Identifica todos os itens que estão em conflito com um tempo de reunião.  <br/> |
|[AdjacentMeetings](adjacentmeetings.md) <br/> |Descreve todos os itens de calendário que são adjacentes para um horário de reunião.  <br/> |
|[Duração (itens)](duration-items.md) <br/> |Representa a duração de um item de calendário.  <br/> |
|[Fuso horário (Item)](timezone-item.md) <br/> |Fornece uma descrição de texto de um fuso horário.  <br/> |
|[AppointmentReplyTime](appointmentreplytime.md) <br/> |Representa a data e hora quando um participante respondeu a uma solicitação de reunião.  <br/> |
|[AppointmentSequenceNumber](appointmentsequencenumber.md) <br/> |Especifica o número de sequência de uma versão de um compromisso.  <br/> |
|[AppointmentState](appointmentstate.md) <br/> |Especifica o status do compromisso.  <br/> |
|[Recorrência (RecurrenceType)](recurrence-recurrencetype.md) <br/> |Contém o padrão de recorrência para itens de calendário e solicitações de reunião.  <br/> |
|[FirstOccurrence](firstoccurrence.md) <br/> |Representa a primeira ocorrência de um item de calendário recorrente.  <br/> Esse elemento é válido se [CalendarItemType](calendaritemtype.md) tem o valor de RecurringMaster.  <br/> |
|[LastOccurrence](lastoccurrence.md) <br/> |Representa a última ocorrência de um item de calendário recorrente.  <br/> Esse elemento é válido se [CalendarItemType](calendaritemtype.md) tem o valor de RecurringMaster.  <br/> |
|[ModifiedOccurrences](modifiedoccurrences.md) <br/> |Contém uma matriz de recorrente ocorrências de item de calendário que foram modificados para que sejam diferentes do que o item de recorrência mestre.  <br/> Esse elemento é válido se [CalendarItemType](calendaritemtype.md) tem o valor de RecurringMaster.  <br/> |
|[DeletedOccurrences](deletedoccurrences.md) <br/> |Contém uma matriz de ocorrências excluídas de um item de calendário recorrente.  <br/> Esse elemento é válido se [CalendarItemType](calendaritemtype.md) tem o valor de RecurringMaster.  <br/> |
|[MeetingTimeZone](meetingtimezone.md) <br/> |Representa o fuso horário do local onde a reunião está hospedada.  <br/> |
|[StartTimeZone](starttimezone.md) <br/> |Representa o fuso horário de início do item de calendário.  <br/> |
|[EndTimeZone](endtimezone.md) <br/> |Representa o fuso horário de término do item de calendário.  <br/> |
|[ConferenceType](conferencetype.md) <br/> |Descreve o tipo de conferência que for executado com um item de calendário.  <br/> |
|[AllowNewTimeProposal](allownewtimeproposal.md) <br/> |Indica se um novo tempo de reunião pode ser proposto para uma reunião.  <br/> |
|[IsOnlineMeeting](isonlinemeeting.md) <br/> |Indica se a reunião está online.  <br/> |
|[MeetingWorkspaceUrl](meetingworkspaceurl.md) <br/> |Contém a URL para o espaço de trabalho de reunião que está vinculada pelo item do calendário.  <br/> |
|[NetShowUrl](netshowurl.md) <br/> |Especifica a URL de uma reunião online do Microsoft Netshow.  <br/> |
|[EffectiveRights](effectiverights.md) <br/> |Contém os direitos do cliente com base nas configurações de permissão para o item ou a pasta. Este elemento é somente leitura.  <br/> |
|[LastModifiedName](lastmodifiedname.md) <br/> |Contém o nome de exibição do último usuário para modificar um item.  <br/> |
|[LastModifiedTime](lastmodifiedtime.md) <br/> |Indica quando um item da última modificação.  <br/> |
|[IsAssociated](isassociated.md) <br/> |Indica se o item está associado a uma pasta.  <br/> |
|[WebClientReadFormQueryString](webclientreadformquerystring.md) <br/> |Representa uma URL para concatenar no ponto de extremidade do Microsoft Office Outlook Web App para ler um item no Outlook Web App.  <br/> |
|[WebClientEditFormQueryString](webclienteditformquerystring.md) <br/> |Representa uma URL para concatenar no ponto de extremidade do Outlook Web App para editar um item no Outlook Web App.  <br/> |
|[ConversationId](conversationid.md) <br/> |Contém o identificador de um item ou conversa.  <br/> |
|[UniqueBody](uniquebody.md) <br/> |Representa um fragmento HTML ou texto sem formatação que representa um único corpo da conversa.  <br/> |
|[UID](uid.md) <br/> |Identifica um item de calendário.  <br/> |
|[RecurrenceId](recurrenceid.md) <br/> |Usado para identificar uma instância específica de um item de calendário recorrente.  <br/> |
|[DateTimeStamp](datetimestamp.md) <br/> |Indica a data e hora em que uma instância de um objeto iCalendar foi criada.  <br/> |
   
### <a name="parent-elements"></a>Elementos pai

|**Elemento**|**Descrição**|
|:-----|:-----|
|[AdjacentMeetings](adjacentmeetings.md) <br/> |Identifica todos os itens de calendário que são adjacentes para um horário de reunião.  <br/> |
|[AppendToItemField](appendtoitemfield.md) <br/> |Identifica os dados a serem acrescentados a uma única propriedade de um item durante uma [operação UpdateItem](updateitem-operation.md).  <br/> |
|[ConflictingMeetings](conflictingmeetings.md) <br/> |Identifica todos os itens que estão em conflito com um tempo de reunião.  <br/> |
|[Criar (ItemSync)](create-itemsync.md) <br/> |Identifica um único item para criar no repositório de cliente local.  <br/> |
|[Items](items.md) <br/> |Contém uma matriz de itens.  <br/> |
|[Itens (NonEmptyArrayOfAllItemsType)](items-nonemptyarrayofallitemstype.md) <br/> |Contém uma matriz de itens para criar.  <br/> |
|[ItemAttachment](itemattachment.md) <br/> |Representa um item do Exchange que está anexado a outro item do Exchange.  <br/> |
|[SetItemField](setitemfield.md) <br/> |Representa uma atualização para uma única propriedade de um item em uma [operação UpdateItem](updateitem-operation.md).  <br/> |
|[Atualização (ItemSync)](update-itemsync.md) <br/> |Identifica um único item a ser atualizado no repositório de cliente local.  <br/> |
   
## <a name="text-value"></a>Text value

Nenhum.
  
## <a name="remarks"></a>Comentários

O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.
  
## <a name="element-information"></a>Informações de elemento

|||
|:-----|:-----|
|Namespace  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|Nome do esquema  <br/> |Esquema de tipos  <br/> |
|Arquivo de validação  <br/> |Types.xsd  <br/> |
|Pode ser vazio  <br/> |False  <br/> |
   
## <a name="see-also"></a>Ver também



- [Elementos XML do EWS no Exchange](ews-xml-elements-in-exchange.md)

