---
title: From
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- From
api_type:
- schema
ms.assetid: 5a52d644-3677-4049-874c-12bd5c3080dc
description: O elemento from representa o endereço a partir do qual a mensagem foi enviada.
ms.openlocfilehash: c0d655731677e56cc02c7c029264ffc96f0a18c2
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44459550"
---
# <a name="from"></a><span data-ttu-id="d0a9f-103">From</span><span class="sxs-lookup"><span data-stu-id="d0a9f-103">From</span></span>

<span data-ttu-id="d0a9f-104">O elemento **from** representa o endereço a partir do qual a mensagem foi enviada.</span><span class="sxs-lookup"><span data-stu-id="d0a9f-104">The **From** element represents the address from which the message was sent.</span></span> 
  
```xml
<From>
   <Mailbox/>
</From>
```

 <span data-ttu-id="d0a9f-105">**SingleRecipientType**</span><span class="sxs-lookup"><span data-stu-id="d0a9f-105">**SingleRecipientType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="d0a9f-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="d0a9f-106">Attributes and elements</span></span>

<span data-ttu-id="d0a9f-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="d0a9f-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="d0a9f-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="d0a9f-108">Attributes</span></span>

<span data-ttu-id="d0a9f-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="d0a9f-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="d0a9f-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="d0a9f-110">Child elements</span></span>

|<span data-ttu-id="d0a9f-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="d0a9f-111">**Element**</span></span>|<span data-ttu-id="d0a9f-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="d0a9f-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="d0a9f-113">Caixa de Correio</span><span class="sxs-lookup"><span data-stu-id="d0a9f-113">Mailbox</span></span>](mailbox.md) <br/> |<span data-ttu-id="d0a9f-114">Identifica um objeto de serviço de diretório do Active Directory habilitado para email.</span><span class="sxs-lookup"><span data-stu-id="d0a9f-114">Identifies a mail-enabled Active Directory directory service object.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="d0a9f-115">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="d0a9f-115">Parent elements</span></span>

|<span data-ttu-id="d0a9f-116">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="d0a9f-116">**Element**</span></span>|<span data-ttu-id="d0a9f-117">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="d0a9f-117">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="d0a9f-118">RemoveItem</span><span class="sxs-lookup"><span data-stu-id="d0a9f-118">RemoveItem</span></span>](removeitem.md) <br/> |<span data-ttu-id="d0a9f-119">Remove um item do repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="d0a9f-119">Removes an item from the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="d0a9f-120">Message</span><span class="sxs-lookup"><span data-stu-id="d0a9f-120">Message</span></span>](message-ex15websvcsotherref.md) <br/> |<span data-ttu-id="d0a9f-121">Representa uma mensagem de email do Exchange.</span><span class="sxs-lookup"><span data-stu-id="d0a9f-121">Represents an Exchange e-mail message.</span></span>  <br/> |
|[<span data-ttu-id="d0a9f-122">MeetingMessage</span><span class="sxs-lookup"><span data-stu-id="d0a9f-122">MeetingMessage</span></span>](meetingmessage.md) <br/> |<span data-ttu-id="d0a9f-123">Representa uma reunião no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="d0a9f-123">Represents a meeting in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="d0a9f-124">MeetingRequest</span><span class="sxs-lookup"><span data-stu-id="d0a9f-124">MeetingRequest</span></span>](meetingrequest.md) <br/> |<span data-ttu-id="d0a9f-125">Representa uma solicitação de reunião no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="d0a9f-125">Represents a meeting request in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="d0a9f-126">MeetingResponse</span><span class="sxs-lookup"><span data-stu-id="d0a9f-126">MeetingResponse</span></span>](meetingresponse.md) <br/> |<span data-ttu-id="d0a9f-127">Representa uma resposta de reunião no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="d0a9f-127">Represents a meeting response in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="d0a9f-128">MeetingCancellation</span><span class="sxs-lookup"><span data-stu-id="d0a9f-128">MeetingCancellation</span></span>](meetingcancellation.md) <br/> |<span data-ttu-id="d0a9f-129">Representa um cancelamento de reunião no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="d0a9f-129">Represents a meeting cancellation in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="d0a9f-130">AcceptItem</span><span class="sxs-lookup"><span data-stu-id="d0a9f-130">AcceptItem</span></span>](acceptitem.md) <br/> |<span data-ttu-id="d0a9f-131">Representa uma resposta de aceitação para uma solicitação de reunião.</span><span class="sxs-lookup"><span data-stu-id="d0a9f-131">Represents an Accept reply to a meeting request.</span></span>  <br/> |
|[<span data-ttu-id="d0a9f-132">TentativelyAcceptItem</span><span class="sxs-lookup"><span data-stu-id="d0a9f-132">TentativelyAcceptItem</span></span>](tentativelyacceptitem.md) <br/> |<span data-ttu-id="d0a9f-133">Representa uma resposta provisória a uma solicitação de reunião.</span><span class="sxs-lookup"><span data-stu-id="d0a9f-133">Represents a Tentative reply to a meeting request.</span></span>  <br/> |
|[<span data-ttu-id="d0a9f-134">DeclineItem</span><span class="sxs-lookup"><span data-stu-id="d0a9f-134">DeclineItem</span></span>](declineitem.md) <br/> |<span data-ttu-id="d0a9f-135">Representa uma resposta de recusa a uma solicitação de reunião.</span><span class="sxs-lookup"><span data-stu-id="d0a9f-135">Represents a Decline reply to a meeting request.</span></span>  <br/> |
|[<span data-ttu-id="d0a9f-136">ReplyToItem</span><span class="sxs-lookup"><span data-stu-id="d0a9f-136">ReplyToItem</span></span>](replytoitem.md) <br/> |<span data-ttu-id="d0a9f-137">Contém uma resposta para o criador de um item no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="d0a9f-137">Contains a reply to the creator of an item in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="d0a9f-138">ReplyAllToItem</span><span class="sxs-lookup"><span data-stu-id="d0a9f-138">ReplyAllToItem</span></span>](replyalltoitem.md) <br/> |<span data-ttu-id="d0a9f-139">Contém uma resposta a todos os destinatários identificados de um item no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="d0a9f-139">Contains a reply to all identified recipients of an item in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="d0a9f-140">ForwardItem</span><span class="sxs-lookup"><span data-stu-id="d0a9f-140">ForwardItem</span></span>](forwarditem.md) <br/> |<span data-ttu-id="d0a9f-141">Contém um item de repositório do Exchange para encaminhar aos destinatários.</span><span class="sxs-lookup"><span data-stu-id="d0a9f-141">Contains an Exchange store item to forward to recipients.</span></span>  <br/> |
|[<span data-ttu-id="d0a9f-142">CancelCalendarItem</span><span class="sxs-lookup"><span data-stu-id="d0a9f-142">CancelCalendarItem</span></span>](cancelcalendaritem.md) <br/> |<span data-ttu-id="d0a9f-143">Representa o objeto Response que é usado para cancelar uma reunião.</span><span class="sxs-lookup"><span data-stu-id="d0a9f-143">Represents the response object that is used to cancel a meeting.</span></span>  <br/> |
|[<span data-ttu-id="d0a9f-144">Item de postagem</span><span class="sxs-lookup"><span data-stu-id="d0a9f-144">PostItem</span></span>](postitem.md) <br/> |<span data-ttu-id="d0a9f-145">Representa um item de postagem no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="d0a9f-145">Represents a post item in the Exchange store.</span></span> <span data-ttu-id="d0a9f-146">Este elemento foi introduzido no Microsoft Exchange Server 2007 Service Pack 1 (SP1).</span><span class="sxs-lookup"><span data-stu-id="d0a9f-146">This element was introduced in Microsoft Exchange Server 2007 Service Pack 1 (SP1).</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="d0a9f-147">Comentários</span><span class="sxs-lookup"><span data-stu-id="d0a9f-147">Remarks</span></span>

<span data-ttu-id="d0a9f-148">Este elemento é usado para emails "enviar em nome de".</span><span class="sxs-lookup"><span data-stu-id="d0a9f-148">This element is used for "send on behalf of" e-mails.</span></span>
  
<span data-ttu-id="d0a9f-149">O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o Microsoft Exchange Server 2007 que tem a função de servidor de acesso para Cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="d0a9f-149">The schema that describes this element is located in the EWS virtual directory of the computer that is running Microsoft Exchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="d0a9f-150">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="d0a9f-150">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="d0a9f-151">Namespace</span><span class="sxs-lookup"><span data-stu-id="d0a9f-151">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="d0a9f-152">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="d0a9f-152">Schema Name</span></span>  <br/> |<span data-ttu-id="d0a9f-153">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="d0a9f-153">Types schema</span></span>  <br/> |
|<span data-ttu-id="d0a9f-154">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="d0a9f-154">Validation File</span></span>  <br/> |<span data-ttu-id="d0a9f-155">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="d0a9f-155">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="d0a9f-156">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="d0a9f-156">Can be Empty</span></span>  <br/> |<span data-ttu-id="d0a9f-157">False</span><span class="sxs-lookup"><span data-stu-id="d0a9f-157">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="d0a9f-158">Confira também</span><span class="sxs-lookup"><span data-stu-id="d0a9f-158">See also</span></span>



- [<span data-ttu-id="d0a9f-159">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="d0a9f-159">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

