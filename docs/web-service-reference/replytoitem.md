---
title: ReplyToItem
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- ReplyToItem
api_type:
- schema
ms.assetid: 35ee751a-41c0-4216-ad8b-78f7ada43a2f
description: O elemento ReplyToItem contém uma resposta para o remetente de um item no repositório do Exchange.
ms.openlocfilehash: fc40335dc73327820c0b39cafa07168d1f27851d
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44529851"
---
# <a name="replytoitem"></a><span data-ttu-id="e5bfc-103">ReplyToItem</span><span class="sxs-lookup"><span data-stu-id="e5bfc-103">ReplyToItem</span></span>

<span data-ttu-id="e5bfc-104">O elemento **ReplyToItem** contém uma resposta para o remetente de um item no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-104">The **ReplyToItem** element contains a reply to the sender of an item in the Exchange store.</span></span> 
  
```xml
<ReplyToItem>
   <Subject/>
   <Body/>
   <ToRecipients/>
   <CcRecipients/>
   <BccRecipients/>
   <IsReadReceiptRequested/>
   <IsDeliveryReceiptRequested/>
   <From/>
   <ReferenceItemId/>
   <NewBodyContent/>
   <ReceivedBy/>
   <ReceivedRepresenting/>
</ReplyToItem>
```

<span data-ttu-id="e5bfc-105">**ReplyToItemType**</span><span class="sxs-lookup"><span data-stu-id="e5bfc-105">**ReplyToItemType**</span></span>

## <a name="attributes-and-elements"></a><span data-ttu-id="e5bfc-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="e5bfc-106">Attributes and elements</span></span>

<span data-ttu-id="e5bfc-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="e5bfc-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="e5bfc-108">Attributes</span></span>

<span data-ttu-id="e5bfc-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="e5bfc-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="e5bfc-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="e5bfc-110">Child elements</span></span>

|<span data-ttu-id="e5bfc-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="e5bfc-111">**Element**</span></span>|<span data-ttu-id="e5bfc-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="e5bfc-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="e5bfc-113">Assunto</span><span class="sxs-lookup"><span data-stu-id="e5bfc-113">Subject</span></span>](subject.md) <br/> |<span data-ttu-id="e5bfc-114">Representa a propriedade Subject dos itens do repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-114">Represents the subject property of Exchange store items.</span></span>  <br/> |
|[<span data-ttu-id="e5bfc-115">Body</span><span class="sxs-lookup"><span data-stu-id="e5bfc-115">Body</span></span>](body.md) <br/> |<span data-ttu-id="e5bfc-116">Representa o conteúdo real do corpo de uma mensagem.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-116">Represents the actual body content of a message.</span></span>  <br/> |
|[<span data-ttu-id="e5bfc-117">ToRecipients</span><span class="sxs-lookup"><span data-stu-id="e5bfc-117">ToRecipients</span></span>](torecipients.md) <br/> |<span data-ttu-id="e5bfc-118">Contém uma matriz de destinatários de um item.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-118">Contains an array of recipients of an item.</span></span> <span data-ttu-id="e5bfc-119">Estes são os principais destinatários de um item.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-119">These are the primary recipients of an item.</span></span>  <br/> |
|[<span data-ttu-id="e5bfc-120">CcRecipients</span><span class="sxs-lookup"><span data-stu-id="e5bfc-120">CcRecipients</span></span>](ccrecipients.md) <br/> |<span data-ttu-id="e5bfc-121">Representa uma coleção de destinatários que receberão uma cópia da mensagem.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-121">Represents a collection of recipients that will receive a copy of the message.</span></span>  <br/> |
|[<span data-ttu-id="e5bfc-122">BccRecipients</span><span class="sxs-lookup"><span data-stu-id="e5bfc-122">BccRecipients</span></span>](bccrecipients.md) <br/> |<span data-ttu-id="e5bfc-123">Representa uma coleção de destinatários para receber uma cópia oculta (Cco) de uma mensagem de email.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-123">Represents a collection of recipients to receive a blind carbon copy (Bcc) of an e-mail message.</span></span>  <br/> |
|[<span data-ttu-id="e5bfc-124">IsReadReceiptRequested</span><span class="sxs-lookup"><span data-stu-id="e5bfc-124">IsReadReceiptRequested</span></span>](isreadreceiptrequested.md) <br/> |<span data-ttu-id="e5bfc-125">Indica se o remetente de um item solicita uma confirmação de leitura.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-125">Indicates whether the sender of an item requests a read receipt.</span></span>  <br/> |
|[<span data-ttu-id="e5bfc-126">IsDeliveryReceiptRequested</span><span class="sxs-lookup"><span data-stu-id="e5bfc-126">IsDeliveryReceiptRequested</span></span>](isdeliveryreceiptrequested.md) <br/> |<span data-ttu-id="e5bfc-127">Indica se o remetente de um item solicita uma confirmação de entrega.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-127">Indicates whether the sender of an item requests a delivery receipt.</span></span>  <br/> |
|[<span data-ttu-id="e5bfc-128">De</span><span class="sxs-lookup"><span data-stu-id="e5bfc-128">From</span></span>](from.md) <br/> |<span data-ttu-id="e5bfc-129">Representa o endereço a partir do qual a mensagem foi enviada.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-129">Represents the address from which the message was sent.</span></span>  <br/> |
|[<span data-ttu-id="e5bfc-130">ReferenceItemId</span><span class="sxs-lookup"><span data-stu-id="e5bfc-130">ReferenceItemId</span></span>](referenceitemid.md) <br/> |<span data-ttu-id="e5bfc-131">Identifica o item ao qual o objeto Response se refere.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-131">Identifies the item to which the response object refers.</span></span>  <br/> |
|[<span data-ttu-id="e5bfc-132">NewBodyContent</span><span class="sxs-lookup"><span data-stu-id="e5bfc-132">NewBodyContent</span></span>](newbodycontent.md) <br/> |<span data-ttu-id="e5bfc-133">Representa o novo conteúdo do corpo de uma mensagem.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-133">Represents the new body content of a message.</span></span>  <br/> |
|[<span data-ttu-id="e5bfc-134">ReceivedBy</span><span class="sxs-lookup"><span data-stu-id="e5bfc-134">ReceivedBy</span></span>](receivedby.md) <br/> |<span data-ttu-id="e5bfc-135">Identifica o representante em um cenário de acesso de representante.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-135">Identifies the delegate in a delegate access scenario.</span></span> <span data-ttu-id="e5bfc-136">Este elemento foi introduzido no Microsoft Exchange Server 2007 Service Pack 1 (SP1).</span><span class="sxs-lookup"><span data-stu-id="e5bfc-136">This element was introduced in Microsoft Exchange Server 2007 Service Pack 1 (SP1).</span></span>  <br/> |
|[<span data-ttu-id="e5bfc-137">ReceivedRepresenting</span><span class="sxs-lookup"><span data-stu-id="e5bfc-137">ReceivedRepresenting</span></span>](receivedrepresenting.md) <br/> |<span data-ttu-id="e5bfc-138">Identifica o principal em um cenário de acesso de representante.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-138">Identifies the principal in a delegate access scenario.</span></span> <span data-ttu-id="e5bfc-139">Este elemento foi introduzido no Exchange 2007 SP1.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-139">This element was introduced in Exchange 2007 SP1.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="e5bfc-140">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="e5bfc-140">Parent elements</span></span>

|<span data-ttu-id="e5bfc-141">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="e5bfc-141">**Element**</span></span>|<span data-ttu-id="e5bfc-142">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="e5bfc-142">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="e5bfc-143">AdjacentMeetings</span><span class="sxs-lookup"><span data-stu-id="e5bfc-143">AdjacentMeetings</span></span>](adjacentmeetings.md) <br/> | <span data-ttu-id="e5bfc-144">Descreve todos os itens que estão adjacentes a um horário de reunião.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-144">Describes all items that are adjacent to a meeting time.</span></span> <br/> <br/>  <span data-ttu-id="e5bfc-145">A seguir estão algumas das expressões XPath para este elemento:</span><span class="sxs-lookup"><span data-stu-id="e5bfc-145">The following are some of the XPath expressions to this element:</span></span> <br/> <br/>  `/CalendarItem/AdjacentMeetings` <br/>  `/MeetingRequest/AdjacentMeetings` <br/>  `/SetItemField/CalendarItem/AdjacentMeetings` <br/>  `/AppendToItemField/CalendarItem/AdjacentMeetings` <br/>  `/AcceptItem/Attachments/ItemAttachment/CalendarItem/AdjacentMeetings` <br/>  `/DeclineItem/Attachments/ItemAttachment/CalendarItem/AdjacentMeetings` <br/>  `/TentativelyAcceptItem/Attachments/ItemAttachment/CalendarItem/AdjacentMeetings` <br/>  `/UpdateItem/ItemChanges/ItemChange/Updates/SetItemField/CalendarItem/AdjacentMeetings` <br/>  `/UpdateItem/ItemChanges/ItemChange/Updates/AppendToItemField/CalendarItem/AdjacentMeetings` <br/>  `/CreateAttachmentResponseMessage/Attachments/ItemAttachment/CalendarItem/AdjacentMeetings` <br/>  `/GetAttachmentResponseMessage/Attachments/ItemAttachment/CalendarItem/AdjacentMeetings` <br/> |
|[<span data-ttu-id="e5bfc-146">ConflictingMeetings</span><span class="sxs-lookup"><span data-stu-id="e5bfc-146">ConflictingMeetings</span></span>](conflictingmeetings.md) <br/> | <span data-ttu-id="e5bfc-147">Descreve todos os itens que entram em conflito com um horário de reunião.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-147">Describes all items that conflict with a meeting time.</span></span> <br/> <br/>  <span data-ttu-id="e5bfc-148">A seguir estão algumas das expressões XPath para este elemento:</span><span class="sxs-lookup"><span data-stu-id="e5bfc-148">The following are some of the XPath expressions to this element:</span></span> <br/> <br/>  `/CalendarItem/ConflictingMeetings` <br/>  `/MeetingRequest/ConflictingMeetings` <br/>  `/SetItemField/CalendarItem/ConflictingMeetings` <br/>  `/AppendToItemField/CalendarItem/ConflictingMeetings` <br/>  `/AcceptItem/Attachments/ItemAttachment/CalendarItem/ConflictingMeetings` <br/>  `/DeclineItem/Attachments/ItemAttachment/CalendarItem/ConflictingMeetings` <br/>  `/TentativelyAcceptItem/Attachments/ItemAttachment/CalendarItem/ConflictingMeetings` <br/>  `/UpdateItem/ItemChanges/ItemChange/Updates/SetItemField/CalendarItem/ConflictingMeetings` <br/>  `/UpdateItem/ItemChanges/ItemChange/Updates/AppendToItemField/CalendarItem/ConflictingMeetings` <br/>  `/CreateAttachmentResponseMessage/Attachments/ItemAttachment/CalendarItem/ConflictingMeetings` <br/>  `/GetAttachmentResponseMessage/Attachments/ItemAttachment/CalendarItem/ConflictingMeetings` <br/> |
|[<span data-ttu-id="e5bfc-149">ResponseObjects</span><span class="sxs-lookup"><span data-stu-id="e5bfc-149">ResponseObjects</span></span>](responseobjects.md) <br/> |<span data-ttu-id="e5bfc-150">Contém uma coleção de todos os objetos Response associados a um item no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-150">Contains a collection of all the response objects that are associated with an item in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="e5bfc-151">Itens (NonEmptyArrayOfAllItemsType)</span><span class="sxs-lookup"><span data-stu-id="e5bfc-151">Items (NonEmptyArrayOfAllItemsType)</span></span>](items-nonemptyarrayofallitemstype.md) <br/> |<span data-ttu-id="e5bfc-152">Contém uma matriz de itens a serem criados na pasta que é identificada pelo elemento [ParentFolderId (TargetFolderIdType)](parentfolderid-targetfolderidtype.md) .</span><span class="sxs-lookup"><span data-stu-id="e5bfc-152">Contains an array of items to create in the folder that is identified by the [ParentFolderId (TargetFolderIdType)](parentfolderid-targetfolderidtype.md) element.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="e5bfc-153">Comentários</span><span class="sxs-lookup"><span data-stu-id="e5bfc-153">Remarks</span></span>

<span data-ttu-id="e5bfc-154">O elemento [from](from.md) deve ser definido como o endereço de email da entidade de segurança se um item for uma resposta por um representante.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-154">The [From](from.md) element should be set to the e-mail address of the principal if an item is a reply by a delegate.</span></span> <span data-ttu-id="e5bfc-155">Se o representante não definir a propriedade [from](from.md) , o item parecerá ter sido enviado diretamente a partir da caixa de correio do representante.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-155">If the delegate does not set the [From](from.md) property, the item will appear to have been sent directly from the delegate's mailbox.</span></span> 
  
<span data-ttu-id="e5bfc-156">O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o Microsoft Exchange Server 2007 que tem a função de servidor de acesso para Cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="e5bfc-156">The schema that describes this element is located in the EWS virtual directory of the computer that is running Microsoft Exchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="e5bfc-157">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="e5bfc-157">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="e5bfc-158">Namespace</span><span class="sxs-lookup"><span data-stu-id="e5bfc-158">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="e5bfc-159">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="e5bfc-159">Schema Name</span></span>  <br/> |<span data-ttu-id="e5bfc-160">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="e5bfc-160">Types schema</span></span>  <br/> |
|<span data-ttu-id="e5bfc-161">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="e5bfc-161">Validation File</span></span>  <br/> |<span data-ttu-id="e5bfc-162">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="e5bfc-162">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="e5bfc-163">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="e5bfc-163">Can be Empty</span></span>  <br/> |<span data-ttu-id="e5bfc-164">False</span><span class="sxs-lookup"><span data-stu-id="e5bfc-164">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="e5bfc-165">Confira também</span><span class="sxs-lookup"><span data-stu-id="e5bfc-165">See also</span></span>

- [<span data-ttu-id="e5bfc-166">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="e5bfc-166">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

