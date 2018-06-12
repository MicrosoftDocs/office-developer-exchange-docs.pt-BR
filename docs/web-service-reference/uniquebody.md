---
title: UniqueBody
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- UniqueBody
api_type:
- schema
ms.assetid: 06bc95d7-121c-433b-bd27-c2b0eb8c011f
description: O elemento UniqueBody representa um fragmento HTML ou texto sem formatação que representa um único corpo da conversa.
ms.openlocfilehash: 49d3607926e0b985074d79cde76cad084f537f01
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19837837"
---
# <a name="uniquebody"></a><span data-ttu-id="1f772-103">UniqueBody</span><span class="sxs-lookup"><span data-stu-id="1f772-103">UniqueBody</span></span>

<span data-ttu-id="1f772-104">O elemento **UniqueBody** representa um fragmento HTML ou texto sem formatação que representa um único corpo da conversa.</span><span class="sxs-lookup"><span data-stu-id="1f772-104">The **UniqueBody** element represents an HTML fragment or plain text which represents the unique body of this conversation.</span></span> 
  
```XML
<UniqueBody BodyType=""/>
```

 <span data-ttu-id="1f772-105">**BodyType**</span><span class="sxs-lookup"><span data-stu-id="1f772-105">**BodyType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="1f772-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="1f772-106">Attributes and elements</span></span>

<span data-ttu-id="1f772-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="1f772-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="1f772-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="1f772-108">Attributes</span></span>

|<span data-ttu-id="1f772-109">**Attribute**</span><span class="sxs-lookup"><span data-stu-id="1f772-109">**Attribute**</span></span>|<span data-ttu-id="1f772-110">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="1f772-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="1f772-111">**BodyType**</span><span class="sxs-lookup"><span data-stu-id="1f772-111">**BodyType**</span></span> <br/> |<span data-ttu-id="1f772-112">Descreve como o corpo do item é armazenado no item.</span><span class="sxs-lookup"><span data-stu-id="1f772-112">Describes how the item body is stored in the item.</span></span>  <br/> |
   
#### <a name="bodytype-attribute"></a><span data-ttu-id="1f772-113">Atributo BodyType</span><span class="sxs-lookup"><span data-stu-id="1f772-113">BodyType Attribute</span></span>

|<span data-ttu-id="1f772-114">**Valor**</span><span class="sxs-lookup"><span data-stu-id="1f772-114">**Value**</span></span>|<span data-ttu-id="1f772-115">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="1f772-115">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="1f772-116">**HTML**</span><span class="sxs-lookup"><span data-stu-id="1f772-116">**HTML**</span></span> <br/> |<span data-ttu-id="1f772-117">Converte todos os corpos em HTML.</span><span class="sxs-lookup"><span data-stu-id="1f772-117">Converts all bodies to HTML.</span></span>  <br/> |
|<span data-ttu-id="1f772-118">**Text**</span><span class="sxs-lookup"><span data-stu-id="1f772-118">**Text**</span></span> <br/> |<span data-ttu-id="1f772-119">Converte todos os corpos de texto sem formatação.</span><span class="sxs-lookup"><span data-stu-id="1f772-119">Converts all bodies to plain text.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="1f772-120">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="1f772-120">Child elements</span></span>

<span data-ttu-id="1f772-121">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="1f772-121">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="1f772-122">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="1f772-122">Parent elements</span></span>

|<span data-ttu-id="1f772-123">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="1f772-123">**Element**</span></span>|<span data-ttu-id="1f772-124">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="1f772-124">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="1f772-125">CalendarItem</span><span class="sxs-lookup"><span data-stu-id="1f772-125">CalendarItem</span></span>](calendaritem.md) <br/> |<span data-ttu-id="1f772-126">Representa um item de calendário do Exchange.</span><span class="sxs-lookup"><span data-stu-id="1f772-126">Represents an Exchange calendar item.</span></span>  <br/> |
|[<span data-ttu-id="1f772-127">Contato</span><span class="sxs-lookup"><span data-stu-id="1f772-127">Contact</span></span>](contact.md) <br/> |<span data-ttu-id="1f772-128">Representa um item de contato do Exchange.</span><span class="sxs-lookup"><span data-stu-id="1f772-128">Represents an Exchange contact item.</span></span>  <br/> |
|[<span data-ttu-id="1f772-129">DistributionList</span><span class="sxs-lookup"><span data-stu-id="1f772-129">DistributionList</span></span>](distributionlist.md) <br/> |<span data-ttu-id="1f772-130">Representa uma lista de distribuição.</span><span class="sxs-lookup"><span data-stu-id="1f772-130">Represents a distribution list.</span></span>  <br/> |
|[<span data-ttu-id="1f772-131">1.1</span><span class="sxs-lookup"><span data-stu-id="1f772-131">Item</span></span>](item.md) <br/> |<span data-ttu-id="1f772-132">Representa um item no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="1f772-132">Represents an item in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="1f772-133">MeetingCancellation</span><span class="sxs-lookup"><span data-stu-id="1f772-133">MeetingCancellation</span></span>](meetingcancellation.md) <br/> |<span data-ttu-id="1f772-134">Representa o cancelamento da reunião no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="1f772-134">Represents a meeting cancellation in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="1f772-135">MeetingMessage</span><span class="sxs-lookup"><span data-stu-id="1f772-135">MeetingMessage</span></span>](meetingmessage.md) <br/> |<span data-ttu-id="1f772-136">Representa uma reunião no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="1f772-136">Represents a meeting in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="1f772-137">MeetingRequest</span><span class="sxs-lookup"><span data-stu-id="1f772-137">MeetingRequest</span></span>](meetingrequest.md) <br/> |<span data-ttu-id="1f772-138">Representa uma solicitação de reunião no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="1f772-138">Represents a meeting request in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="1f772-139">MeetingResponse</span><span class="sxs-lookup"><span data-stu-id="1f772-139">MeetingResponse</span></span>](meetingresponse.md) <br/> |<span data-ttu-id="1f772-140">Representa uma resposta de reunião no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="1f772-140">Represents a meeting response in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="1f772-141">Mensagem</span><span class="sxs-lookup"><span data-stu-id="1f772-141">Message</span></span>](message-ex15websvcsotherref.md) <br/> |<span data-ttu-id="1f772-142">Representa uma mensagem de email do Exchange.</span><span class="sxs-lookup"><span data-stu-id="1f772-142">Represents an Exchange e-mail message.</span></span>  <br/> |
|[<span data-ttu-id="1f772-143">PostItem</span><span class="sxs-lookup"><span data-stu-id="1f772-143">PostItem</span></span>](postitem.md) <br/> |<span data-ttu-id="1f772-144">Representa um item de postagem no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="1f772-144">Represents a post item in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="1f772-145">RemoveItem</span><span class="sxs-lookup"><span data-stu-id="1f772-145">RemoveItem</span></span>](removeitem.md) <br/> |<span data-ttu-id="1f772-146">Remove um item de armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="1f772-146">Removes an item from the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="1f772-147">Task</span><span class="sxs-lookup"><span data-stu-id="1f772-147">Task</span></span>](task.md) <br/> |<span data-ttu-id="1f772-148">Representa uma tarefa no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="1f772-148">Represents a task in the Exchange store.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="1f772-149">Text value</span><span class="sxs-lookup"><span data-stu-id="1f772-149">Text value</span></span>

<span data-ttu-id="1f772-150">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="1f772-150">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="1f772-151">Comentários</span><span class="sxs-lookup"><span data-stu-id="1f772-151">Remarks</span></span>

<span data-ttu-id="1f772-152">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="1f772-152">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="1f772-153">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="1f772-153">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="1f772-154">Namespace</span><span class="sxs-lookup"><span data-stu-id="1f772-154">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="1f772-155">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="1f772-155">Schema Name</span></span>  <br/> |<span data-ttu-id="1f772-156">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="1f772-156">Types schema</span></span>  <br/> |
|<span data-ttu-id="1f772-157">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="1f772-157">Validation File</span></span>  <br/> |<span data-ttu-id="1f772-158">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="1f772-158">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="1f772-159">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="1f772-159">Can be Empty</span></span>  <br/> |<span data-ttu-id="1f772-160">False</span><span class="sxs-lookup"><span data-stu-id="1f772-160">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="1f772-161">Ver também</span><span class="sxs-lookup"><span data-stu-id="1f772-161">See also</span></span>



- [<span data-ttu-id="1f772-162">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="1f772-162">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

