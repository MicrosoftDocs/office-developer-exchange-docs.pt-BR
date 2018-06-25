---
title: Atualização (ItemSync)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- Update
api_type:
- schema
ms.assetid: 4e204446-1c80-44f9-b93b-77ce630a01a5
description: O elemento de atualização identifica um único item a ser atualizado no repositório de cliente local.
ms.openlocfilehash: ef1bd46906152affbe54372472766afc2a6ae8c1
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/25/2018
ms.locfileid: "19837875"
---
# <a name="update-itemsync"></a><span data-ttu-id="56d9a-103">Atualização (ItemSync)</span><span class="sxs-lookup"><span data-stu-id="56d9a-103">Update (ItemSync)</span></span>

<span data-ttu-id="56d9a-104">O elemento **Atualizar** identifica um único item a ser atualizado no repositório de cliente local.</span><span class="sxs-lookup"><span data-stu-id="56d9a-104">The **Update** element identifies a single item to update in the local client store.</span></span> 
  
[<span data-ttu-id="56d9a-105">SyncFolderItemsResponse</span><span class="sxs-lookup"><span data-stu-id="56d9a-105">SyncFolderItemsResponse</span></span>](syncfolderitemsresponse.md)
  
[<span data-ttu-id="56d9a-106">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="56d9a-106">ResponseMessages</span></span>](responsemessages.md)
  
[<span data-ttu-id="56d9a-107">SyncFolderItemsResponseMessage</span><span class="sxs-lookup"><span data-stu-id="56d9a-107">SyncFolderItemsResponseMessage</span></span>](syncfolderitemsresponsemessage.md)
  
[<span data-ttu-id="56d9a-108">Alterações (itens)</span><span class="sxs-lookup"><span data-stu-id="56d9a-108">Changes (Items)</span></span>](changes-items.md)
  
[<span data-ttu-id="56d9a-109">Atualização (ItemSync)</span><span class="sxs-lookup"><span data-stu-id="56d9a-109">Update (ItemSync)</span></span>](update-itemsync.md)
  
```xml
<Update>
   <Item/>
</Update>
```

 <span data-ttu-id="56d9a-110">**SyncFolderItemsCreateOrUpdateType**</span><span class="sxs-lookup"><span data-stu-id="56d9a-110">**SyncFolderItemsCreateOrUpdateType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="56d9a-111">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="56d9a-111">Attributes and elements</span></span>

<span data-ttu-id="56d9a-112">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="56d9a-112">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="56d9a-113">Atributos</span><span class="sxs-lookup"><span data-stu-id="56d9a-113">Attributes</span></span>

<span data-ttu-id="56d9a-114">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="56d9a-114">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="56d9a-115">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="56d9a-115">Child elements</span></span>

|<span data-ttu-id="56d9a-116">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="56d9a-116">**Element**</span></span>|<span data-ttu-id="56d9a-117">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="56d9a-117">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="56d9a-118">Item</span><span class="sxs-lookup"><span data-stu-id="56d9a-118">Item</span></span>](item.md) <br/> |<span data-ttu-id="56d9a-119">Representa um item genérico do Exchange para atualizar.</span><span class="sxs-lookup"><span data-stu-id="56d9a-119">Represents a generic Exchange item to update.</span></span>  <br/> |
|[<span data-ttu-id="56d9a-120">Mensagem</span><span class="sxs-lookup"><span data-stu-id="56d9a-120">Message</span></span>](message-ex15websvcsotherref.md) <br/> |<span data-ttu-id="56d9a-121">Representa uma mensagem de email do Exchange para atualizar.</span><span class="sxs-lookup"><span data-stu-id="56d9a-121">Represents an Exchange e-mail message to update.</span></span>  <br/> |
|[<span data-ttu-id="56d9a-122">CalendarItem</span><span class="sxs-lookup"><span data-stu-id="56d9a-122">CalendarItem</span></span>](calendaritem.md) <br/> |<span data-ttu-id="56d9a-123">Representa um item de calendário do Exchange para atualizar.</span><span class="sxs-lookup"><span data-stu-id="56d9a-123">Represents an Exchange calendar item to update.</span></span>  <br/> |
|[<span data-ttu-id="56d9a-124">Contato</span><span class="sxs-lookup"><span data-stu-id="56d9a-124">Contact</span></span>](contact.md) <br/> |<span data-ttu-id="56d9a-125">Representa um item de contato do Exchange para atualizar.</span><span class="sxs-lookup"><span data-stu-id="56d9a-125">Represents an Exchange contact item to update.</span></span>  <br/> |
|[<span data-ttu-id="56d9a-126">DistributionList</span><span class="sxs-lookup"><span data-stu-id="56d9a-126">DistributionList</span></span>](distributionlist.md) <br/> |<span data-ttu-id="56d9a-127">Representa uma lista de distribuição a ser atualizado.</span><span class="sxs-lookup"><span data-stu-id="56d9a-127">Represents a distribution list to update.</span></span>  <br/> |
|[<span data-ttu-id="56d9a-128">MeetingMessage</span><span class="sxs-lookup"><span data-stu-id="56d9a-128">MeetingMessage</span></span>](meetingmessage.md) <br/> |<span data-ttu-id="56d9a-129">Representa uma mensagem de reunião a atualização.</span><span class="sxs-lookup"><span data-stu-id="56d9a-129">Represents a meeting message to update.</span></span>  <br/> |
|[<span data-ttu-id="56d9a-130">MeetingRequest</span><span class="sxs-lookup"><span data-stu-id="56d9a-130">MeetingRequest</span></span>](meetingrequest.md) <br/> |<span data-ttu-id="56d9a-131">Representa uma solicitação de reunião para atualizar.</span><span class="sxs-lookup"><span data-stu-id="56d9a-131">Represents a meeting request to update.</span></span>  <br/> |
|[<span data-ttu-id="56d9a-132">MeetingResponse</span><span class="sxs-lookup"><span data-stu-id="56d9a-132">MeetingResponse</span></span>](meetingresponse.md) <br/> |<span data-ttu-id="56d9a-133">Representa uma resposta de reunião para atualizar.</span><span class="sxs-lookup"><span data-stu-id="56d9a-133">Represents a meeting response to update.</span></span>  <br/> |
|[<span data-ttu-id="56d9a-134">MeetingCancellation</span><span class="sxs-lookup"><span data-stu-id="56d9a-134">MeetingCancellation</span></span>](meetingcancellation.md) <br/> |<span data-ttu-id="56d9a-135">Representa o cancelamento da reunião para atualizar.</span><span class="sxs-lookup"><span data-stu-id="56d9a-135">Represents a meeting cancellation to update.</span></span>  <br/> |
|[<span data-ttu-id="56d9a-136">Task</span><span class="sxs-lookup"><span data-stu-id="56d9a-136">Task</span></span>](task.md) <br/> |<span data-ttu-id="56d9a-137">Representa uma tarefa a ser atualizado.</span><span class="sxs-lookup"><span data-stu-id="56d9a-137">Represents a task to update.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="56d9a-138">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="56d9a-138">Parent elements</span></span>

|<span data-ttu-id="56d9a-139">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="56d9a-139">**Element**</span></span>|<span data-ttu-id="56d9a-140">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="56d9a-140">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="56d9a-141">Alterações (itens)</span><span class="sxs-lookup"><span data-stu-id="56d9a-141">Changes (Items)</span></span>](changes-items.md) <br/> |<span data-ttu-id="56d9a-142">Contém uma matriz de sequência de tipos de alteração que representam o tipo das diferenças entre os itens no cliente e os itens no servidor Exchange.</span><span class="sxs-lookup"><span data-stu-id="56d9a-142">Contains a sequence array of change types that represent the type of differences between the items on the client and the items on the Exchange server.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="56d9a-143">Comentários</span><span class="sxs-lookup"><span data-stu-id="56d9a-143">Remarks</span></span>

<span data-ttu-id="56d9a-144">O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o MicrosoftExchange Server 2007 que tem instalada a função de servidor de Acesso para Cliente.</span><span class="sxs-lookup"><span data-stu-id="56d9a-144">The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="56d9a-145">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="56d9a-145">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="56d9a-146">Namespace</span><span class="sxs-lookup"><span data-stu-id="56d9a-146">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="56d9a-147">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="56d9a-147">Schema name</span></span>  <br/> |<span data-ttu-id="56d9a-148">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="56d9a-148">Types schema</span></span>  <br/> |
|<span data-ttu-id="56d9a-149">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="56d9a-149">Validation file</span></span>  <br/> |<span data-ttu-id="56d9a-150">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="56d9a-150">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="56d9a-151">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="56d9a-151">Can be empty</span></span>  <br/> |<span data-ttu-id="56d9a-152">False</span><span class="sxs-lookup"><span data-stu-id="56d9a-152">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="56d9a-153">Ver também</span><span class="sxs-lookup"><span data-stu-id="56d9a-153">See also</span></span>



[<span data-ttu-id="56d9a-154">Operação SyncFolderItems</span><span class="sxs-lookup"><span data-stu-id="56d9a-154">SyncFolderItems operation</span></span>](syncfolderitems-operation.md)


- [<span data-ttu-id="56d9a-155">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="56d9a-155">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

