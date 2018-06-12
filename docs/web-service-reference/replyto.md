---
title: ReplyTo
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- ReplyTo
api_type:
- schema
ms.assetid: 6b6ae792-e2c4-4aa0-95cb-b49b446f1e08
description: O elemento ReplyTo identifica uma matriz de endereços para o qual as respostas devem ser enviadas.
ms.openlocfilehash: 0ceb4f5edb75bbfe52a7a7156da3c2a328bea346
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19825115"
---
# <a name="replyto"></a><span data-ttu-id="2bdf5-103">ReplyTo</span><span class="sxs-lookup"><span data-stu-id="2bdf5-103">ReplyTo</span></span>

<span data-ttu-id="2bdf5-104">O elemento **ReplyTo** identifica uma matriz de endereços para o qual as respostas devem ser enviadas.</span><span class="sxs-lookup"><span data-stu-id="2bdf5-104">The **ReplyTo** element identifies an array of addresses to which replies should be sent.</span></span> 
  
```xml
<ReplyTo>
   <Mailbox/>
</ReplyTo>
```

 <span data-ttu-id="2bdf5-105">**ArrayOfRecipientsType**</span><span class="sxs-lookup"><span data-stu-id="2bdf5-105">**ArrayOfRecipientsType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="2bdf5-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="2bdf5-106">Attributes and elements</span></span>

<span data-ttu-id="2bdf5-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="2bdf5-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="2bdf5-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="2bdf5-108">Attributes</span></span>

<span data-ttu-id="2bdf5-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="2bdf5-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="2bdf5-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="2bdf5-110">Child elements</span></span>

|<span data-ttu-id="2bdf5-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="2bdf5-111">**Element**</span></span>|<span data-ttu-id="2bdf5-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="2bdf5-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="2bdf5-113">Caixa de correio</span><span class="sxs-lookup"><span data-stu-id="2bdf5-113">Mailbox</span></span>](mailbox.md) <br/> |<span data-ttu-id="2bdf5-114">Identifica um habilitados para email do Active Directory directory service objeto ao qual uma resposta é enviada.</span><span class="sxs-lookup"><span data-stu-id="2bdf5-114">Identifies a mail-enabled Active Directory directory service object to which a reply is sent.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="2bdf5-115">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="2bdf5-115">Parent elements</span></span>

|<span data-ttu-id="2bdf5-116">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="2bdf5-116">**Element**</span></span>|<span data-ttu-id="2bdf5-117">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="2bdf5-117">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="2bdf5-118">RemoveItem</span><span class="sxs-lookup"><span data-stu-id="2bdf5-118">RemoveItem</span></span>](removeitem.md) <br/> |<span data-ttu-id="2bdf5-119">Remove um item de armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="2bdf5-119">Removes an item from the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="2bdf5-120">Mensagem</span><span class="sxs-lookup"><span data-stu-id="2bdf5-120">Message</span></span>](message-ex15websvcsotherref.md) <br/> |<span data-ttu-id="2bdf5-121">Representa uma mensagem de email do Exchange.</span><span class="sxs-lookup"><span data-stu-id="2bdf5-121">Represents an Exchange e-mail message.</span></span>  <br/> |
|[<span data-ttu-id="2bdf5-122">MeetingMessage</span><span class="sxs-lookup"><span data-stu-id="2bdf5-122">MeetingMessage</span></span>](meetingmessage.md) <br/> |<span data-ttu-id="2bdf5-123">Representa uma reunião no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="2bdf5-123">Represents a meeting in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="2bdf5-124">MeetingRequest</span><span class="sxs-lookup"><span data-stu-id="2bdf5-124">MeetingRequest</span></span>](meetingrequest.md) <br/> |<span data-ttu-id="2bdf5-125">Representa uma solicitação de reunião no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="2bdf5-125">Represents a meeting request in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="2bdf5-126">MeetingResponse</span><span class="sxs-lookup"><span data-stu-id="2bdf5-126">MeetingResponse</span></span>](meetingresponse.md) <br/> |<span data-ttu-id="2bdf5-127">Representa uma resposta de reunião no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="2bdf5-127">Represents a meeting response in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="2bdf5-128">MeetingCancellation</span><span class="sxs-lookup"><span data-stu-id="2bdf5-128">MeetingCancellation</span></span>](meetingcancellation.md) <br/> |<span data-ttu-id="2bdf5-129">Representa o cancelamento da reunião no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="2bdf5-129">Represents a meeting cancellation in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="2bdf5-130">AcceptItem</span><span class="sxs-lookup"><span data-stu-id="2bdf5-130">AcceptItem</span></span>](acceptitem.md) <br/> |<span data-ttu-id="2bdf5-131">Representa uma resposta de aceitar a uma solicitação de reunião.</span><span class="sxs-lookup"><span data-stu-id="2bdf5-131">Represents an Accept reply to a meeting request.</span></span>  <br/> |
|[<span data-ttu-id="2bdf5-132">TentativelyAcceptItem</span><span class="sxs-lookup"><span data-stu-id="2bdf5-132">TentativelyAcceptItem</span></span>](tentativelyacceptitem.md) <br/> |<span data-ttu-id="2bdf5-133">Representa um provisório responde a uma solicitação de reunião.</span><span class="sxs-lookup"><span data-stu-id="2bdf5-133">Represents a Tentative reply to a meeting request.</span></span>  <br/> |
|[<span data-ttu-id="2bdf5-134">DeclineItem</span><span class="sxs-lookup"><span data-stu-id="2bdf5-134">DeclineItem</span></span>](declineitem.md) <br/> |<span data-ttu-id="2bdf5-135">Representa uma resposta recusar a uma solicitação de reunião.</span><span class="sxs-lookup"><span data-stu-id="2bdf5-135">Represents a Decline reply to a meeting request.</span></span>  <br/> |
|[<span data-ttu-id="2bdf5-136">ReplyToItem</span><span class="sxs-lookup"><span data-stu-id="2bdf5-136">ReplyToItem</span></span>](replytoitem.md) <br/> |<span data-ttu-id="2bdf5-137">Contém uma resposta para o criador de um item no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="2bdf5-137">Contains a reply to the creator of an item in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="2bdf5-138">ReplyAllToItem</span><span class="sxs-lookup"><span data-stu-id="2bdf5-138">ReplyAllToItem</span></span>](replyalltoitem.md) <br/> |<span data-ttu-id="2bdf5-139">Contém uma resposta a todos os destinatários identificados de um item no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="2bdf5-139">Contains a reply to all identified recipients of an item in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="2bdf5-140">ForwardItem</span><span class="sxs-lookup"><span data-stu-id="2bdf5-140">ForwardItem</span></span>](forwarditem.md) <br/> |<span data-ttu-id="2bdf5-141">Contém um item de armazenamento do Exchange para encaminhar para destinatários.</span><span class="sxs-lookup"><span data-stu-id="2bdf5-141">Contains an Exchange store item to forward to recipients.</span></span>  <br/> |
|[<span data-ttu-id="2bdf5-142">CancelCalendarItem</span><span class="sxs-lookup"><span data-stu-id="2bdf5-142">CancelCalendarItem</span></span>](cancelcalendaritem.md) <br/> |<span data-ttu-id="2bdf5-143">Representa o objeto de resposta é usado para cancelar uma reunião.</span><span class="sxs-lookup"><span data-stu-id="2bdf5-143">Represents the response object that is used to cancel a meeting.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="2bdf5-144">Coment�rios</span><span class="sxs-lookup"><span data-stu-id="2bdf5-144">Remarks</span></span>

<span data-ttu-id="2bdf5-145">O esquema que descreve este elemento está localizado no diretório virtual EWS do computador que está executando o Microsoft Exchange Server 2007 que possui a função de servidor acesso para cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="2bdf5-145">The schema that describes this element is located in the EWS virtual directory of the computer that is running Microsoft Exchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="2bdf5-146">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="2bdf5-146">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="2bdf5-147">Namespace</span><span class="sxs-lookup"><span data-stu-id="2bdf5-147">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="2bdf5-148">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="2bdf5-148">Schema Name</span></span>  <br/> |<span data-ttu-id="2bdf5-149">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="2bdf5-149">Types schema</span></span>  <br/> |
|<span data-ttu-id="2bdf5-150">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="2bdf5-150">Validation File</span></span>  <br/> |<span data-ttu-id="2bdf5-151">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="2bdf5-151">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="2bdf5-152">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="2bdf5-152">Can be Empty</span></span>  <br/> |<span data-ttu-id="2bdf5-153">False</span><span class="sxs-lookup"><span data-stu-id="2bdf5-153">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="2bdf5-154">Ver também</span><span class="sxs-lookup"><span data-stu-id="2bdf5-154">See also</span></span>



- [<span data-ttu-id="2bdf5-155">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="2bdf5-155">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

