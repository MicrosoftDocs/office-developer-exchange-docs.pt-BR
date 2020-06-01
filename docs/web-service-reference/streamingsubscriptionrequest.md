---
title: StreamingSubscriptionRequest
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- StreamingSubscriptionRequest
api_type:
- schema
ms.assetid: d18f3b60-ebb6-4133-b895-a6ec8942d039
description: O elemento StreamingSubscriptionRequest representa uma assinatura para uma assinatura de notificação de eventos de streaming.
ms.openlocfilehash: b469ba7598420189c1db0e2fe676a279390eb6bf
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44468226"
---
# <a name="streamingsubscriptionrequest"></a><span data-ttu-id="fbdc8-103">StreamingSubscriptionRequest</span><span class="sxs-lookup"><span data-stu-id="fbdc8-103">StreamingSubscriptionRequest</span></span>

<span data-ttu-id="fbdc8-104">O elemento **StreamingSubscriptionRequest** representa uma assinatura para uma assinatura de notificação de eventos de streaming.</span><span class="sxs-lookup"><span data-stu-id="fbdc8-104">The **StreamingSubscriptionRequest** element represents a subscription to a streaming event notification subscription.</span></span> 
  
[<span data-ttu-id="fbdc8-105">Assinar</span><span class="sxs-lookup"><span data-stu-id="fbdc8-105">Subscribe</span></span>](subscribe.md)
  
[<span data-ttu-id="fbdc8-106">StreamingSubscriptionRequest</span><span class="sxs-lookup"><span data-stu-id="fbdc8-106">StreamingSubscriptionRequest</span></span>](streamingsubscriptionrequest.md)
  
```xml
<StreamingSubscriptionRequest SubscribeToAllFolders="">
   <FolderIds/>
   <EventTypes/>
</StreamingSubscriptionRequest>
```

 <span data-ttu-id="fbdc8-107">**StreamingSubscriptionRequest**</span><span class="sxs-lookup"><span data-stu-id="fbdc8-107">**StreamingSubscriptionRequest**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="fbdc8-108">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="fbdc8-108">Attributes and elements</span></span>

<span data-ttu-id="fbdc8-109">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="fbdc8-109">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="fbdc8-110">Atributos</span><span class="sxs-lookup"><span data-stu-id="fbdc8-110">Attributes</span></span>

|<span data-ttu-id="fbdc8-111">**Atributo**</span><span class="sxs-lookup"><span data-stu-id="fbdc8-111">**Attribute**</span></span>|<span data-ttu-id="fbdc8-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="fbdc8-112">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="fbdc8-113">**SubscribeToAllFolders**</span><span class="sxs-lookup"><span data-stu-id="fbdc8-113">**SubscribeToAllFolders**</span></span> <br/> |<span data-ttu-id="fbdc8-114">Indica se o servidor se inscreverá em todas as pastas da caixa de correio do usuário.</span><span class="sxs-lookup"><span data-stu-id="fbdc8-114">Indicates whether the server will subscribe to all folders in the user's mailbox.</span></span> <span data-ttu-id="fbdc8-115">Um valor **true** indica que o servidor irá se inscrever.</span><span class="sxs-lookup"><span data-stu-id="fbdc8-115">A value of **true** indicates that the server will subscribe.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="fbdc8-116">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="fbdc8-116">Child elements</span></span>

|<span data-ttu-id="fbdc8-117">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="fbdc8-117">**Element**</span></span>|<span data-ttu-id="fbdc8-118">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="fbdc8-118">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="fbdc8-119">FolderIds</span><span class="sxs-lookup"><span data-stu-id="fbdc8-119">FolderIds</span></span>](folderids.md) <br/> |<span data-ttu-id="fbdc8-120">Contém uma matriz de identificadores de pasta que são usados para identificar as pastas a serem monitoradas para notificações de eventos.</span><span class="sxs-lookup"><span data-stu-id="fbdc8-120">Contains an array of folder identifiers that are used to identify folders to monitor for event notifications.</span></span>  <br/> |
|[<span data-ttu-id="fbdc8-121">EventType</span><span class="sxs-lookup"><span data-stu-id="fbdc8-121">EventTypes</span></span>](eventtypes.md) <br/> |<span data-ttu-id="fbdc8-122">Contém uma coleção de notificações de eventos que são usadas para criar uma assinatura.</span><span class="sxs-lookup"><span data-stu-id="fbdc8-122">Contains a collection of event notifications that are used to create a subscription.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="fbdc8-123">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="fbdc8-123">Parent elements</span></span>

|<span data-ttu-id="fbdc8-124">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="fbdc8-124">**Element**</span></span>|<span data-ttu-id="fbdc8-125">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="fbdc8-125">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="fbdc8-126">Assinar</span><span class="sxs-lookup"><span data-stu-id="fbdc8-126">Subscribe</span></span>](subscribe.md) <br/> |<span data-ttu-id="fbdc8-127">Contém as propriedades que são usadas para criar assinaturas.</span><span class="sxs-lookup"><span data-stu-id="fbdc8-127">Contains the properties that are used to create subscriptions.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="fbdc8-128">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="fbdc8-128">Text value</span></span>

<span data-ttu-id="fbdc8-129">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="fbdc8-129">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="fbdc8-130">Comentários</span><span class="sxs-lookup"><span data-stu-id="fbdc8-130">Remarks</span></span>

<span data-ttu-id="fbdc8-131">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os serviços Web do Exchange. este elemento foi introduzido no Exchange Server 2010 Service Pack 1 (SP1).</span><span class="sxs-lookup"><span data-stu-id="fbdc8-131">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.This element was introduced in Exchange Server 2010 Service Pack 1 (SP1).</span></span>
  
## <a name="element-information"></a><span data-ttu-id="fbdc8-132">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="fbdc8-132">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="fbdc8-133">Namespace</span><span class="sxs-lookup"><span data-stu-id="fbdc8-133">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="fbdc8-134">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="fbdc8-134">Schema name</span></span>  <br/> |<span data-ttu-id="fbdc8-135">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="fbdc8-135">Messages schema</span></span>  <br/> |
|<span data-ttu-id="fbdc8-136">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="fbdc8-136">Validation file</span></span>  <br/> |<span data-ttu-id="fbdc8-137">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="fbdc8-137">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="fbdc8-138">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="fbdc8-138">Can be empty</span></span>  <br/> |<span data-ttu-id="fbdc8-139">False</span><span class="sxs-lookup"><span data-stu-id="fbdc8-139">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="fbdc8-140">Confira também</span><span class="sxs-lookup"><span data-stu-id="fbdc8-140">See also</span></span>



[<span data-ttu-id="fbdc8-141">Operação Subscribe</span><span class="sxs-lookup"><span data-stu-id="fbdc8-141">Subscribe operation</span></span>](subscribe-operation.md)
  
[<span data-ttu-id="fbdc8-142">Operação GetEvents</span><span class="sxs-lookup"><span data-stu-id="fbdc8-142">GetEvents operation</span></span>](getevents-operation.md)
  
[<span data-ttu-id="fbdc8-143">Operação GetStreamingEvents</span><span class="sxs-lookup"><span data-stu-id="fbdc8-143">GetStreamingEvents operation</span></span>](getstreamingevents-operation.md)
  
[<span data-ttu-id="fbdc8-144">Cancelar a operação</span><span class="sxs-lookup"><span data-stu-id="fbdc8-144">Unsubscribe operation</span></span>](unsubscribe-operation.md)

