---
title: Notificação
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- Notification
api_type:
- schema
ms.assetid: c9070936-0930-438e-839c-91127256a6c8
description: O elemento Notification contém informações sobre a assinatura e os eventos que ocorreram desde a última notificação.
ms.openlocfilehash: c4a5206c14985ec46cf40162a9ce4eaec68242ff
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44530384"
---
# <a name="notification"></a><span data-ttu-id="de13d-103">Notificação</span><span class="sxs-lookup"><span data-stu-id="de13d-103">Notification</span></span>

<span data-ttu-id="de13d-104">O elemento **Notification** contém informações sobre a assinatura e os eventos que ocorreram desde a última notificação.</span><span class="sxs-lookup"><span data-stu-id="de13d-104">The **Notification** element contains information about the subscription and the events that have occurred since the last notification.</span></span> 
  
```xml
<Notification>
   <SubscriptionId/>
   <PreviousWatermark/>
   <MoreEvents/>
   <CopiedEvent/>
</Notification>
```

```xml
<Notification>
   <SubscriptionId/>
   <PreviousWatermark/>
   <MoreEvents/>
   <CreatedEvent/>
</Notification>
```

```xml
<Notification>
   <SubscriptionId/>
   <PreviousWatermark/>
   <MoreEvents/>
   <DeletedEvent/>
</Notification>
```

```xml
<Notification>
   <SubscriptionId/>
   <PreviousWatermark/>
   <MoreEvents/>
   <ModifiedEvent/>
</Notification>
```

```xml
<Notification>
   <SubscriptionId/>
   <PreviousWatermark/>
   <MoreEvents/>
   <MovedEvent/>
</Notification>
```

```xml
<Notification>
   <SubscriptionId/>
   <PreviousWatermark/>
   <MoreEvents/>
   <NewMailEvent/>
</Notification>
```

```xml
<Notification>
   <SubscriptionId/>
   <PreviousWatermark/>
   <MoreEvents/>
   <StatusEvent/>
</Notification>
```

```xml
<Notification>
   <SubscriptionId/>
   <PreviousWatermark/>
   <MoreEvents/>
   <FreeBusyChangedEvent/>
</Notification>
```

<span data-ttu-id="de13d-105">**NotificationType**</span><span class="sxs-lookup"><span data-stu-id="de13d-105">**NotificationType**</span></span>

## <a name="attributes-and-elements"></a><span data-ttu-id="de13d-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="de13d-106">Attributes and elements</span></span>

<span data-ttu-id="de13d-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="de13d-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="de13d-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="de13d-108">Attributes</span></span>

<span data-ttu-id="de13d-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="de13d-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="de13d-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="de13d-110">Child elements</span></span>

|<span data-ttu-id="de13d-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="de13d-111">**Element**</span></span>|<span data-ttu-id="de13d-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="de13d-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="de13d-113">SubscriptionId (GetEvents)</span><span class="sxs-lookup"><span data-stu-id="de13d-113">SubscriptionId (GetEvents)</span></span>](subscriptionid-getevents.md) <br/> |<span data-ttu-id="de13d-114">Representa o identificador de uma assinatura.</span><span class="sxs-lookup"><span data-stu-id="de13d-114">Represents the identifier for a subscription.</span></span>  <br/> |
|[<span data-ttu-id="de13d-115">PreviousWatermark</span><span class="sxs-lookup"><span data-stu-id="de13d-115">PreviousWatermark</span></span>](previouswatermark.md) <br/> |<span data-ttu-id="de13d-116">Representa a marca d' água do último evento que foi comunicado com êxito ao cliente para a assinatura.</span><span class="sxs-lookup"><span data-stu-id="de13d-116">Represents the watermark of the latest event that was successfully communicated to the client for the subscription.</span></span>  <br/> |
|[<span data-ttu-id="de13d-117">MoreEvents</span><span class="sxs-lookup"><span data-stu-id="de13d-117">MoreEvents</span></span>](moreevents.md) <br/> |<span data-ttu-id="de13d-118">Indica se há mais eventos na fila a serem entregues ao cliente.</span><span class="sxs-lookup"><span data-stu-id="de13d-118">Indicates whether there are more events in the queue to be delivered to the client.</span></span>  <br/> |
|[<span data-ttu-id="de13d-119">CopiedEvent</span><span class="sxs-lookup"><span data-stu-id="de13d-119">CopiedEvent</span></span>](copiedevent.md) <br/> |<span data-ttu-id="de13d-120">Representa um evento no qual um item ou pasta é copiado.</span><span class="sxs-lookup"><span data-stu-id="de13d-120">Represents an event in which an item or folder is copied.</span></span>  <br/> |
|[<span data-ttu-id="de13d-121">CreatedEvent</span><span class="sxs-lookup"><span data-stu-id="de13d-121">CreatedEvent</span></span>](createdevent.md) <br/> |<span data-ttu-id="de13d-122">Representa um evento no qual um item ou pasta é criado.</span><span class="sxs-lookup"><span data-stu-id="de13d-122">Represents an event in which an item or folder is created.</span></span>  <br/> |
|[<span data-ttu-id="de13d-123">DeletedEvent</span><span class="sxs-lookup"><span data-stu-id="de13d-123">DeletedEvent</span></span>](deletedevent.md) <br/> |<span data-ttu-id="de13d-124">Representa um evento no qual um item ou pasta é excluído.</span><span class="sxs-lookup"><span data-stu-id="de13d-124">Represents an event in which an item or folder is deleted.</span></span>  <br/> |
|[<span data-ttu-id="de13d-125">ModifiedEvent</span><span class="sxs-lookup"><span data-stu-id="de13d-125">ModifiedEvent</span></span>](modifiedevent.md) <br/> |<span data-ttu-id="de13d-126">Representa um evento no qual um item ou pasta é modificado.</span><span class="sxs-lookup"><span data-stu-id="de13d-126">Represents an event in which an item or folder is modified.</span></span>  <br/> |
|[<span data-ttu-id="de13d-127">MovedEvent</span><span class="sxs-lookup"><span data-stu-id="de13d-127">MovedEvent</span></span>](movedevent.md) <br/> |<span data-ttu-id="de13d-128">Representa um evento no qual um item ou pasta é movido de uma pasta pai para outra pasta pai.</span><span class="sxs-lookup"><span data-stu-id="de13d-128">Represents an event in which an item or folder is moved from one parent folder to another parent folder.</span></span>  <br/> |
|[<span data-ttu-id="de13d-129">NewMailEvent</span><span class="sxs-lookup"><span data-stu-id="de13d-129">NewMailEvent</span></span>](newmailevent.md) <br/> |<span data-ttu-id="de13d-130">Representa um evento que é disparado por um novo item de email em uma caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="de13d-130">Represents an event that is triggered by a new mail item in a mailbox.</span></span>  <br/> |
|[<span data-ttu-id="de13d-131">StatusEvent</span><span class="sxs-lookup"><span data-stu-id="de13d-131">StatusEvent</span></span>](statusevent.md) <br/> |<span data-ttu-id="de13d-132">Representa uma notificação de que nenhuma atividade nova ocorreu na caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="de13d-132">Represents a notification that no new activity has occurred in the mailbox.</span></span>  <br/> |
|[<span data-ttu-id="de13d-133">FreeBusyChangedEvent</span><span class="sxs-lookup"><span data-stu-id="de13d-133">FreeBusyChangedEvent</span></span>](freebusychangedevent.md) <br/> |<span data-ttu-id="de13d-134">Representa um evento no qual o horário de disponibilidade de um item foi alterado.</span><span class="sxs-lookup"><span data-stu-id="de13d-134">Represents an event in which an item's free/busy time has changed.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="de13d-135">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="de13d-135">Parent elements</span></span>

|<span data-ttu-id="de13d-136">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="de13d-136">**Element**</span></span>|<span data-ttu-id="de13d-137">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="de13d-137">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="de13d-138">GetEventsResponseMessage</span><span class="sxs-lookup"><span data-stu-id="de13d-138">GetEventsResponseMessage</span></span>](geteventsresponsemessage.md) <br/> |<span data-ttu-id="de13d-139">Contém o status e o resultado de uma única solicitação GetEvents.</span><span class="sxs-lookup"><span data-stu-id="de13d-139">Contains the status and result of a single GetEvents request.</span></span>  <br/> |
|[<span data-ttu-id="de13d-140">SendNotificationResponseMessage</span><span class="sxs-lookup"><span data-stu-id="de13d-140">SendNotificationResponseMessage</span></span>](sendnotificationresponsemessage.md) <br/> |<span data-ttu-id="de13d-141">Contém o status e o resultado de uma única solicitação de SendNotification.</span><span class="sxs-lookup"><span data-stu-id="de13d-141">Contains the status and result of a single SendNotification request.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="de13d-142">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="de13d-142">Text value</span></span>

<span data-ttu-id="de13d-143">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="de13d-143">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="de13d-144">Comentários</span><span class="sxs-lookup"><span data-stu-id="de13d-144">Remarks</span></span>

<span data-ttu-id="de13d-145">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="de13d-145">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="de13d-146">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="de13d-146">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="de13d-147">Namespace</span><span class="sxs-lookup"><span data-stu-id="de13d-147">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="de13d-148">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="de13d-148">Schema Name</span></span>  <br/> |<span data-ttu-id="de13d-149">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="de13d-149">Types schema</span></span>  <br/> |
|<span data-ttu-id="de13d-150">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="de13d-150">Validation File</span></span>  <br/> |<span data-ttu-id="de13d-151">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="de13d-151">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="de13d-152">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="de13d-152">Can be Empty</span></span>  <br/> |<span data-ttu-id="de13d-153">False</span><span class="sxs-lookup"><span data-stu-id="de13d-153">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="de13d-154">Confira também</span><span class="sxs-lookup"><span data-stu-id="de13d-154">See also</span></span>

- [<span data-ttu-id="de13d-155">Operação Subscribe</span><span class="sxs-lookup"><span data-stu-id="de13d-155">Subscribe operation</span></span>](subscribe-operation.md) 
- [<span data-ttu-id="de13d-156">Operação GetEvents</span><span class="sxs-lookup"><span data-stu-id="de13d-156">GetEvents operation</span></span>](getevents-operation.md) 
- [<span data-ttu-id="de13d-157">Operação GetStreamingEvents</span><span class="sxs-lookup"><span data-stu-id="de13d-157">GetStreamingEvents operation</span></span>](getstreamingevents-operation.md) 
- [<span data-ttu-id="de13d-158">Cancelar a operação</span><span class="sxs-lookup"><span data-stu-id="de13d-158">Unsubscribe operation</span></span>](unsubscribe-operation.md)

