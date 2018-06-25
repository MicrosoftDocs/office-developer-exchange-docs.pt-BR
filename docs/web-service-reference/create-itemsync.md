---
title: Criar (ItemSync)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- Create
api_type:
- schema
ms.assetid: cb5e64a2-66a5-4447-921e-7c13efb8f6bf
description: O elemento de criar identifica um único item para criar no repositório de cliente local.
ms.openlocfilehash: 39056bcaab3577b1b729421118a45571910922fc
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/25/2018
ms.locfileid: "19751563"
---
# <a name="create-itemsync"></a><span data-ttu-id="1e213-103">Criar (ItemSync)</span><span class="sxs-lookup"><span data-stu-id="1e213-103">Create (ItemSync)</span></span>

<span data-ttu-id="1e213-104">O elemento de **criar** identifica um único item para criar no repositório de cliente local.</span><span class="sxs-lookup"><span data-stu-id="1e213-104">The **Create** element identifies a single item to create in the local client store.</span></span> 
  
[<span data-ttu-id="1e213-105">SyncFolderItemsResponse</span><span class="sxs-lookup"><span data-stu-id="1e213-105">SyncFolderItemsResponse</span></span>](syncfolderitemsresponse.md)
  
[<span data-ttu-id="1e213-106">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="1e213-106">ResponseMessages</span></span>](responsemessages.md)
  
[<span data-ttu-id="1e213-107">SyncFolderItemsResponseMessage</span><span class="sxs-lookup"><span data-stu-id="1e213-107">SyncFolderItemsResponseMessage</span></span>](syncfolderitemsresponsemessage.md)
  
[<span data-ttu-id="1e213-108">Alterações (itens)</span><span class="sxs-lookup"><span data-stu-id="1e213-108">Changes (Items)</span></span>](changes-items.md)
  
[<span data-ttu-id="1e213-109">Criar (ItemSync)</span><span class="sxs-lookup"><span data-stu-id="1e213-109">Create (ItemSync)</span></span>](create-itemsync.md)
  
```xml
<Create>
   <Item/>
</Create>
```

 <span data-ttu-id="1e213-110">**SyncFolderItemsCreateOrUpdateType**</span><span class="sxs-lookup"><span data-stu-id="1e213-110">**SyncFolderItemsCreateOrUpdateType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="1e213-111">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="1e213-111">Attributes and elements</span></span>

<span data-ttu-id="1e213-112">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="1e213-112">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="1e213-113">Atributos</span><span class="sxs-lookup"><span data-stu-id="1e213-113">Attributes</span></span>

<span data-ttu-id="1e213-114">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="1e213-114">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="1e213-115">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="1e213-115">Child elements</span></span>

|<span data-ttu-id="1e213-116">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="1e213-116">**Element**</span></span>|<span data-ttu-id="1e213-117">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="1e213-117">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="1e213-118">Item</span><span class="sxs-lookup"><span data-stu-id="1e213-118">Item</span></span>](item.md) <br/> |<span data-ttu-id="1e213-119">Representa um item genérico do Exchange para criar.</span><span class="sxs-lookup"><span data-stu-id="1e213-119">Represents a generic Exchange item to create.</span></span>  <br/> |
|[<span data-ttu-id="1e213-120">Mensagem</span><span class="sxs-lookup"><span data-stu-id="1e213-120">Message</span></span>](message-ex15websvcsotherref.md) <br/> |<span data-ttu-id="1e213-121">Representa uma mensagem de email do Exchange para criar.</span><span class="sxs-lookup"><span data-stu-id="1e213-121">Represents an Exchange e-mail message to create.</span></span>  <br/> |
|[<span data-ttu-id="1e213-122">CalendarItem</span><span class="sxs-lookup"><span data-stu-id="1e213-122">CalendarItem</span></span>](calendaritem.md) <br/> |<span data-ttu-id="1e213-123">Representa um item de calendário do Exchange para criar.</span><span class="sxs-lookup"><span data-stu-id="1e213-123">Represents an Exchange calendar item to create.</span></span>  <br/> |
|[<span data-ttu-id="1e213-124">Contato</span><span class="sxs-lookup"><span data-stu-id="1e213-124">Contact</span></span>](contact.md) <br/> |<span data-ttu-id="1e213-125">Representa um item de contato do Exchange para criar.</span><span class="sxs-lookup"><span data-stu-id="1e213-125">Represents an Exchange contact item to create.</span></span>  <br/> |
|[<span data-ttu-id="1e213-126">DistributionList</span><span class="sxs-lookup"><span data-stu-id="1e213-126">DistributionList</span></span>](distributionlist.md) <br/> |<span data-ttu-id="1e213-127">Representa uma lista de distribuição para criar.</span><span class="sxs-lookup"><span data-stu-id="1e213-127">Represents a distribution list to create.</span></span>  <br/> |
|[<span data-ttu-id="1e213-128">MeetingMessage</span><span class="sxs-lookup"><span data-stu-id="1e213-128">MeetingMessage</span></span>](meetingmessage.md) <br/> |<span data-ttu-id="1e213-129">Representa uma mensagem de reunião para criar.</span><span class="sxs-lookup"><span data-stu-id="1e213-129">Represents a meeting message to create.</span></span>  <br/> |
|[<span data-ttu-id="1e213-130">MeetingRequest</span><span class="sxs-lookup"><span data-stu-id="1e213-130">MeetingRequest</span></span>](meetingrequest.md) <br/> |<span data-ttu-id="1e213-131">Representa uma solicitação de reunião para criar.</span><span class="sxs-lookup"><span data-stu-id="1e213-131">Represents a meeting request to create.</span></span>  <br/> |
|[<span data-ttu-id="1e213-132">MeetingResponse</span><span class="sxs-lookup"><span data-stu-id="1e213-132">MeetingResponse</span></span>](meetingresponse.md) <br/> |<span data-ttu-id="1e213-133">Representa uma resposta de reunião para criar.</span><span class="sxs-lookup"><span data-stu-id="1e213-133">Represents a meeting response to create.</span></span>  <br/> |
|[<span data-ttu-id="1e213-134">MeetingCancellation</span><span class="sxs-lookup"><span data-stu-id="1e213-134">MeetingCancellation</span></span>](meetingcancellation.md) <br/> |<span data-ttu-id="1e213-135">Representa o cancelamento da reunião para criar.</span><span class="sxs-lookup"><span data-stu-id="1e213-135">Represents a meeting cancellation to create.</span></span>  <br/> |
|[<span data-ttu-id="1e213-136">Task</span><span class="sxs-lookup"><span data-stu-id="1e213-136">Task</span></span>](task.md) <br/> |<span data-ttu-id="1e213-137">Representa uma tarefa para criar.</span><span class="sxs-lookup"><span data-stu-id="1e213-137">Represents a task to create.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="1e213-138">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="1e213-138">Parent elements</span></span>

|<span data-ttu-id="1e213-139">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="1e213-139">**Element**</span></span>|<span data-ttu-id="1e213-140">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="1e213-140">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="1e213-141">Alterações (itens)</span><span class="sxs-lookup"><span data-stu-id="1e213-141">Changes (Items)</span></span>](changes-items.md) <br/> |<span data-ttu-id="1e213-142">Contém uma matriz de sequência de tipos de alteração que representam os tipos de diferenças entre os itens no cliente e os itens no servidor Exchange.</span><span class="sxs-lookup"><span data-stu-id="1e213-142">Contains a sequence array of change types that represent the types of differences between the items on the client and the items on the Exchange server.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="1e213-143">Comentários</span><span class="sxs-lookup"><span data-stu-id="1e213-143">Remarks</span></span>

<span data-ttu-id="1e213-144">O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o MicrosoftExchange Server 2007 que tem instalada a função de servidor de Acesso para Cliente.</span><span class="sxs-lookup"><span data-stu-id="1e213-144">The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="1e213-145">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="1e213-145">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="1e213-146">Namespace</span><span class="sxs-lookup"><span data-stu-id="1e213-146">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="1e213-147">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="1e213-147">Schema name</span></span>  <br/> |<span data-ttu-id="1e213-148">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="1e213-148">Types schema</span></span>  <br/> |
|<span data-ttu-id="1e213-149">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="1e213-149">Validation file</span></span>  <br/> |<span data-ttu-id="1e213-150">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="1e213-150">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="1e213-151">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="1e213-151">Can be empty</span></span>  <br/> |<span data-ttu-id="1e213-152">False</span><span class="sxs-lookup"><span data-stu-id="1e213-152">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="1e213-153">Ver também</span><span class="sxs-lookup"><span data-stu-id="1e213-153">See also</span></span>



[<span data-ttu-id="1e213-154">Operação SyncFolderItems</span><span class="sxs-lookup"><span data-stu-id="1e213-154">SyncFolderItems operation</span></span>](syncfolderitems-operation.md)


- [<span data-ttu-id="1e213-155">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="1e213-155">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

