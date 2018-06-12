---
title: Categories
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- Categories
api_type:
- schema
ms.assetid: d84d4927-b524-4e62-bf3d-1f12fec8c21a
description: O elemento de categorias contém uma coleção de cadeias de caracteres que identificam as categorias para o qual um item na caixa de correio pertence.
ms.openlocfilehash: 8f112a9a736ff4f242b9dfb084b3ad7541cc493d
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19751383"
---
# <a name="categories"></a><span data-ttu-id="c8fa8-103">Categories</span><span class="sxs-lookup"><span data-stu-id="c8fa8-103">Categories</span></span>

<span data-ttu-id="c8fa8-104">O elemento de **categorias** contém uma coleção de cadeias de caracteres que identificam as categorias para o qual um item na caixa de correio pertence.</span><span class="sxs-lookup"><span data-stu-id="c8fa8-104">The **Categories** element contains a collection of strings that identify the categories to which an item in the mailbox belongs.</span></span> 
  
```XML
<Categories>
   <String/>
</Categories>
```

 <span data-ttu-id="c8fa8-105">**ArrayOfStringsType**</span><span class="sxs-lookup"><span data-stu-id="c8fa8-105">**ArrayOfStringsType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="c8fa8-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="c8fa8-106">Attributes and elements</span></span>

<span data-ttu-id="c8fa8-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="c8fa8-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="c8fa8-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="c8fa8-108">Attributes</span></span>

<span data-ttu-id="c8fa8-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="c8fa8-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="c8fa8-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="c8fa8-110">Child elements</span></span>

|<span data-ttu-id="c8fa8-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="c8fa8-111">**Element**</span></span>|<span data-ttu-id="c8fa8-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="c8fa8-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="c8fa8-113">String</span><span class="sxs-lookup"><span data-stu-id="c8fa8-113">String</span></span>](string.md) <br/> |<span data-ttu-id="c8fa8-114">Contém uma cadeia de caracteres que identifica uma única categoria.</span><span class="sxs-lookup"><span data-stu-id="c8fa8-114">Contains a string that identifies a single category.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="c8fa8-115">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="c8fa8-115">Parent elements</span></span>

|<span data-ttu-id="c8fa8-116">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="c8fa8-116">**Element**</span></span>|<span data-ttu-id="c8fa8-117">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="c8fa8-117">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="c8fa8-118">Item</span><span class="sxs-lookup"><span data-stu-id="c8fa8-118">Item</span></span>](item.md) <br/> |<span data-ttu-id="c8fa8-119">Representa um item no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="c8fa8-119">Represents an item in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="c8fa8-120">RemoveItem</span><span class="sxs-lookup"><span data-stu-id="c8fa8-120">RemoveItem</span></span>](removeitem.md) <br/> |<span data-ttu-id="c8fa8-121">Remove um item de armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="c8fa8-121">Removes an item from the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="c8fa8-122">Mensagem</span><span class="sxs-lookup"><span data-stu-id="c8fa8-122">Message</span></span>](message-ex15websvcsotherref.md) <br/> |<span data-ttu-id="c8fa8-123">Representa uma mensagem de email do Exchange.</span><span class="sxs-lookup"><span data-stu-id="c8fa8-123">Represents an Exchange e-mail message.</span></span>  <br/> |
|[<span data-ttu-id="c8fa8-124">Task</span><span class="sxs-lookup"><span data-stu-id="c8fa8-124">Task</span></span>](task.md) <br/> |<span data-ttu-id="c8fa8-125">Representa uma tarefa no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="c8fa8-125">Represents a task in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="c8fa8-126">CalendarItem</span><span class="sxs-lookup"><span data-stu-id="c8fa8-126">CalendarItem</span></span>](calendaritem.md) <br/> |<span data-ttu-id="c8fa8-127">Representa um item de calendário do Exchange.</span><span class="sxs-lookup"><span data-stu-id="c8fa8-127">Represents an Exchange calendar item.</span></span>  <br/> |
|[<span data-ttu-id="c8fa8-128">Conversa (ConversationType)</span><span class="sxs-lookup"><span data-stu-id="c8fa8-128">Conversation (ConversationType)</span></span>](conversation-conversationtype.md) <br/> |<span data-ttu-id="c8fa8-129">Representa uma única conversa.</span><span class="sxs-lookup"><span data-stu-id="c8fa8-129">Represents a single conversation.</span></span>  <br/> |
|[<span data-ttu-id="c8fa8-130">MeetingMessage</span><span class="sxs-lookup"><span data-stu-id="c8fa8-130">MeetingMessage</span></span>](meetingmessage.md) <br/> |<span data-ttu-id="c8fa8-131">Representa uma reunião no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="c8fa8-131">Represents a meeting in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="c8fa8-132">MeetingRequest</span><span class="sxs-lookup"><span data-stu-id="c8fa8-132">MeetingRequest</span></span>](meetingrequest.md) <br/> |<span data-ttu-id="c8fa8-133">Representa uma solicitação de reunião no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="c8fa8-133">Represents a meeting request in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="c8fa8-134">MeetingResponse</span><span class="sxs-lookup"><span data-stu-id="c8fa8-134">MeetingResponse</span></span>](meetingresponse.md) <br/> |<span data-ttu-id="c8fa8-135">Representa uma resposta de reunião no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="c8fa8-135">Represents a meeting response in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="c8fa8-136">MeetingCancellation</span><span class="sxs-lookup"><span data-stu-id="c8fa8-136">MeetingCancellation</span></span>](meetingcancellation.md) <br/> |<span data-ttu-id="c8fa8-137">Representa o cancelamento da reunião no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="c8fa8-137">Represents a meeting cancellation in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="c8fa8-138">Contato</span><span class="sxs-lookup"><span data-stu-id="c8fa8-138">Contact</span></span>](contact.md) <br/> |<span data-ttu-id="c8fa8-139">Representa um item de contato do Exchange.</span><span class="sxs-lookup"><span data-stu-id="c8fa8-139">Represents an Exchange contact item.</span></span>  <br/> |
|[<span data-ttu-id="c8fa8-140">DistributionList</span><span class="sxs-lookup"><span data-stu-id="c8fa8-140">DistributionList</span></span>](distributionlist.md) <br/> |<span data-ttu-id="c8fa8-141">Representa uma lista de distribuição.</span><span class="sxs-lookup"><span data-stu-id="c8fa8-141">Represents a distribution list.</span></span>  <br/> |
|[<span data-ttu-id="c8fa8-142">Condições</span><span class="sxs-lookup"><span data-stu-id="c8fa8-142">Conditions</span></span>](conditions.md) <br/> |<span data-ttu-id="c8fa8-143">Representa as condições que, quando atendida, irá disparar as ações de regra para uma regra.</span><span class="sxs-lookup"><span data-stu-id="c8fa8-143">Represents the conditions that, when fulfilled, will trigger the rule actions for a rule.</span></span>  <br/> |
|[<span data-ttu-id="c8fa8-144">Exceções</span><span class="sxs-lookup"><span data-stu-id="c8fa8-144">Exceptions</span></span>](exceptions.md) <br/> |<span data-ttu-id="c8fa8-145">Representa todas as condições de exceção de regra disponíveis para uma regra de caixa de entrada.</span><span class="sxs-lookup"><span data-stu-id="c8fa8-145">Represents all the available rule exception conditions for an Inbox rule.</span></span>  <br/> |
|[<span data-ttu-id="c8fa8-146">ConversationAction</span><span class="sxs-lookup"><span data-stu-id="c8fa8-146">ConversationAction</span></span>](conversationaction.md) <br/> |<span data-ttu-id="c8fa8-147">Contém uma única ação a ser aplicado a uma única conversa.</span><span class="sxs-lookup"><span data-stu-id="c8fa8-147">Contains a single action to be applied to a single conversation.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="c8fa8-148">Text value</span><span class="sxs-lookup"><span data-stu-id="c8fa8-148">Text value</span></span>

<span data-ttu-id="c8fa8-149">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="c8fa8-149">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="c8fa8-150">Comentários</span><span class="sxs-lookup"><span data-stu-id="c8fa8-150">Remarks</span></span>

<span data-ttu-id="c8fa8-151">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="c8fa8-151">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="c8fa8-152">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="c8fa8-152">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c8fa8-153">Namespace</span><span class="sxs-lookup"><span data-stu-id="c8fa8-153">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="c8fa8-154">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="c8fa8-154">Schema Name</span></span>  <br/> |<span data-ttu-id="c8fa8-155">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="c8fa8-155">Types schema</span></span>  <br/> |
|<span data-ttu-id="c8fa8-156">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="c8fa8-156">Validation File</span></span>  <br/> |<span data-ttu-id="c8fa8-157">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="c8fa8-157">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="c8fa8-158">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="c8fa8-158">Can be Empty</span></span>  <br/> |<span data-ttu-id="c8fa8-159">False</span><span class="sxs-lookup"><span data-stu-id="c8fa8-159">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="c8fa8-160">Ver também</span><span class="sxs-lookup"><span data-stu-id="c8fa8-160">See also</span></span>



- [<span data-ttu-id="c8fa8-161">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="c8fa8-161">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

