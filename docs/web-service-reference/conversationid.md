---
title: ConversationId
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- ConversationId
api_type:
- schema
ms.assetid: d5f1ddb3-9af3-4677-a6ba-111b304a951e
description: O elemento Conversation contém o identificador de um item ou uma conversa.
ms.openlocfilehash: 4f12d70ae6b72773760a731f5778cf6743ce699f
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44461468"
---
# <a name="conversationid"></a><span data-ttu-id="518e6-103">ConversationId</span><span class="sxs-lookup"><span data-stu-id="518e6-103">ConversationId</span></span>

<span data-ttu-id="518e6-104">O elemento **Conversation** contém o identificador de um item ou uma conversa.</span><span class="sxs-lookup"><span data-stu-id="518e6-104">The **ConversationId** element contains the identifier of an item or conversation.</span></span> 
  
```XML
<ConversationId Id="" ChangeKey="" />
```

 <span data-ttu-id="518e6-105">**ItemIdtype**</span><span class="sxs-lookup"><span data-stu-id="518e6-105">**ItemIdType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="518e6-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="518e6-106">Attributes and elements</span></span>

<span data-ttu-id="518e6-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="518e6-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="518e6-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="518e6-108">Attributes</span></span>

|<span data-ttu-id="518e6-109">**Atributo**</span><span class="sxs-lookup"><span data-stu-id="518e6-109">**Attribute**</span></span>|<span data-ttu-id="518e6-110">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="518e6-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="518e6-111">**Id**</span><span class="sxs-lookup"><span data-stu-id="518e6-111">**Id**</span></span> <br/> |<span data-ttu-id="518e6-112">Identifica um item específico no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="518e6-112">Identifies a specific item in the Exchange store.</span></span>  <br/> |
|<span data-ttu-id="518e6-113">**ChangeKey**</span><span class="sxs-lookup"><span data-stu-id="518e6-113">**ChangeKey**</span></span> <br/> | <span data-ttu-id="518e6-114">Identifica uma versão específica de um item.</span><span class="sxs-lookup"><span data-stu-id="518e6-114">Identifies a specific version of an item.</span></span> <span data-ttu-id="518e6-115">Um **ChangeKey** é necessário para os seguintes cenários:</span><span class="sxs-lookup"><span data-stu-id="518e6-115">A **ChangeKey** is required for the following scenarios:</span></span>  <br/><br/><span data-ttu-id="518e6-116">– O elemento [UpdateItem](updateitem.md) requer um **ChangeKey** se o atributo **ConflictResolution** estiver definido como autoresolver.</span><span class="sxs-lookup"><span data-stu-id="518e6-116">- The [UpdateItem](updateitem.md) element requires a **ChangeKey** if the **ConflictResolution** attribute is set to AutoResolve.</span></span> <span data-ttu-id="518e6-117">Autoresolver é um valor padrão.</span><span class="sxs-lookup"><span data-stu-id="518e6-117">AutoResolve is a default value.</span></span> <span data-ttu-id="518e6-118">Se o atributo **ChangeKey** não for incluído, a resposta retornará um valor [ResponseCode](responsecode.md) igual a **ErrorChangeKeyRequired**.</span><span class="sxs-lookup"><span data-stu-id="518e6-118">If the **ChangeKey** attribute is not included, the response will return a [ResponseCode](responsecode.md) value equal to **ErrorChangeKeyRequired**.</span></span><br/><br/><span data-ttu-id="518e6-119">- Os elementos [SendItem](senditem.md), [DeleteItem](deleteitem.md)e [DeleteFolder](deletefolder.md) exigem um **ChangeKey** para testar se a operação tentada funcionará na versão mais recente de um item.</span><span class="sxs-lookup"><span data-stu-id="518e6-119">- [SendItem](senditem.md), [DeleteItem](deleteitem.md), and [DeleteFolder](deletefolder.md) elements require a **ChangeKey** to test whether the attempted operation will act upon the most recent version of an item.</span></span> <span data-ttu-id="518e6-120">Se o atributo **ChangeKey** não estiver incluído no **ItemId** ou se o **ChangeKey** estiver vazio, a resposta retornará um valor de [ResponseCode](responsecode.md) igual a **ErrorStaleObject**.</span><span class="sxs-lookup"><span data-stu-id="518e6-120">If the **ChangeKey** attribute is not included in the **ItemId** or if the **ChangeKey** is empty, the response will return a [ResponseCode](responsecode.md) value equal to **ErrorStaleObject**.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="518e6-121">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="518e6-121">Child elements</span></span>

<span data-ttu-id="518e6-122">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="518e6-122">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="518e6-123">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="518e6-123">Parent elements</span></span>

|<span data-ttu-id="518e6-124">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="518e6-124">**Element**</span></span>|<span data-ttu-id="518e6-125">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="518e6-125">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="518e6-126">CalendarItem</span><span class="sxs-lookup"><span data-stu-id="518e6-126">CalendarItem</span></span>](calendaritem.md) <br/> |<span data-ttu-id="518e6-127">Representa um item de calendário do Exchange.</span><span class="sxs-lookup"><span data-stu-id="518e6-127">Represents an Exchange calendar item.</span></span>  <br/> |
|[<span data-ttu-id="518e6-128">Contato</span><span class="sxs-lookup"><span data-stu-id="518e6-128">Contact</span></span>](contact.md) <br/> |<span data-ttu-id="518e6-129">Representa um item de contato do Exchange.</span><span class="sxs-lookup"><span data-stu-id="518e6-129">Represents an Exchange contact item.</span></span>  <br/> |
|[<span data-ttu-id="518e6-130">Conversation</span><span class="sxs-lookup"><span data-stu-id="518e6-130">ConversationAction</span></span>](conversationaction.md) <br/> |<span data-ttu-id="518e6-131">Representa uma única ação a ser aplicada a uma única conversa.</span><span class="sxs-lookup"><span data-stu-id="518e6-131">Represents a single action to be applied to a single conversation.</span></span>  <br/> |
|[<span data-ttu-id="518e6-132">DistributionList</span><span class="sxs-lookup"><span data-stu-id="518e6-132">DistributionList</span></span>](distributionlist.md) <br/> |<span data-ttu-id="518e6-133">Representa uma lista de distribuição.</span><span class="sxs-lookup"><span data-stu-id="518e6-133">Represents a distribution list.</span></span>  <br/> |
|[<span data-ttu-id="518e6-134">Item</span><span class="sxs-lookup"><span data-stu-id="518e6-134">Item</span></span>](item.md) <br/> |<span data-ttu-id="518e6-135">Representa um item no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="518e6-135">Represents an item in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="518e6-136">MeetingCancellation</span><span class="sxs-lookup"><span data-stu-id="518e6-136">MeetingCancellation</span></span>](meetingcancellation.md) <br/> |<span data-ttu-id="518e6-137">Representa um cancelamento de reunião no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="518e6-137">Represents a meeting cancellation in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="518e6-138">MeetingMessage</span><span class="sxs-lookup"><span data-stu-id="518e6-138">MeetingMessage</span></span>](meetingmessage.md) <br/> |<span data-ttu-id="518e6-139">Representa uma reunião no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="518e6-139">Represents a meeting in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="518e6-140">MeetingRequest</span><span class="sxs-lookup"><span data-stu-id="518e6-140">MeetingRequest</span></span>](meetingrequest.md) <br/> |<span data-ttu-id="518e6-141">Representa uma solicitação de reunião no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="518e6-141">Represents a meeting request in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="518e6-142">MeetingResponse</span><span class="sxs-lookup"><span data-stu-id="518e6-142">MeetingResponse</span></span>](meetingresponse.md) <br/> |<span data-ttu-id="518e6-143">Representa uma resposta de reunião no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="518e6-143">Represents a meeting response in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="518e6-144">Mensagem</span><span class="sxs-lookup"><span data-stu-id="518e6-144">Message</span></span>](message-ex15websvcsotherref.md) <br/> |<span data-ttu-id="518e6-145">Representa uma mensagem de email do Exchange.</span><span class="sxs-lookup"><span data-stu-id="518e6-145">Represents an Exchange e-mail message.</span></span>  <br/> |
|[<span data-ttu-id="518e6-146">Item de postagem</span><span class="sxs-lookup"><span data-stu-id="518e6-146">PostItem</span></span>](postitem.md) <br/> |<span data-ttu-id="518e6-147">Representa um item de postagem no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="518e6-147">Represents a post item in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="518e6-148">RemoveItem</span><span class="sxs-lookup"><span data-stu-id="518e6-148">RemoveItem</span></span>](removeitem.md) <br/> |<span data-ttu-id="518e6-149">Remove um item do repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="518e6-149">Removes an item from the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="518e6-150">Tarefa</span><span class="sxs-lookup"><span data-stu-id="518e6-150">Task</span></span>](task.md) <br/> |<span data-ttu-id="518e6-151">Representa uma tarefa no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="518e6-151">Represents a task in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="518e6-152">Conversa (Conversatype)</span><span class="sxs-lookup"><span data-stu-id="518e6-152">Conversation (ConversationType)</span></span>](conversation-conversationtype.md) <br/> |<span data-ttu-id="518e6-153">Representa uma única conversa.</span><span class="sxs-lookup"><span data-stu-id="518e6-153">Represents a single conversation.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="518e6-154">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="518e6-154">Text value</span></span>

<span data-ttu-id="518e6-155">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="518e6-155">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="518e6-156">Comentários</span><span class="sxs-lookup"><span data-stu-id="518e6-156">Remarks</span></span>

<span data-ttu-id="518e6-157">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="518e6-157">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="518e6-158">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="518e6-158">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="518e6-159">Namespace</span><span class="sxs-lookup"><span data-stu-id="518e6-159">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="518e6-160">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="518e6-160">Schema Name</span></span>  <br/> |<span data-ttu-id="518e6-161">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="518e6-161">Types schema</span></span>  <br/> |
|<span data-ttu-id="518e6-162">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="518e6-162">Validation File</span></span>  <br/> |<span data-ttu-id="518e6-163">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="518e6-163">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="518e6-164">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="518e6-164">Can be Empty</span></span>  <br/> |<span data-ttu-id="518e6-165">False</span><span class="sxs-lookup"><span data-stu-id="518e6-165">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="518e6-166">Confira também</span><span class="sxs-lookup"><span data-stu-id="518e6-166">See also</span></span>

- [<span data-ttu-id="518e6-167">Operação FindConversation</span><span class="sxs-lookup"><span data-stu-id="518e6-167">FindConversation operation</span></span>](findconversation-operation.md)
- [<span data-ttu-id="518e6-168">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="518e6-168">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

