---
title: DeletedEvent
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- DeletedEvent
api_type:
- schema
ms.assetid: c4565eb4-b537-466c-b1ff-11602533812b
description: O elemento DeletedEvent representa um evento no qual uma pasta ou um item é excluída.
ms.openlocfilehash: 5ddc909ffc9c74ea6b423610e915d5b9ff9bff43
ms.sourcegitcommit: 9061fcf40c218ebe88911783f357b7df278846db
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/28/2018
ms.locfileid: "21354404"
---
# <a name="deletedevent"></a><span data-ttu-id="86381-103">DeletedEvent</span><span class="sxs-lookup"><span data-stu-id="86381-103">DeletedEvent</span></span>

<span data-ttu-id="86381-104">O elemento **DeletedEvent** representa um evento no qual uma pasta ou um item é excluída.</span><span class="sxs-lookup"><span data-stu-id="86381-104">The **DeletedEvent** element represents an event in which an item or folder is deleted.</span></span> 
  
```xml
<DeletedEvent>
   <Watermark/>
   <TimeStamp/>
   <ItemId/>
   <ParentFolderId/>
</DeletedEvent>
```

```xml
<DeletedEvent>
   <Watermark/>
   <TimeStamp/>
   <FolderId/>
   <ParentFolderId/>
</DeletedEvent>
```

<span data-ttu-id="86381-105">**BaseObjectChangedEventType**</span><span class="sxs-lookup"><span data-stu-id="86381-105">**BaseObjectChangedEventType**</span></span>

## <a name="attributes-and-elements"></a><span data-ttu-id="86381-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="86381-106">Attributes and elements</span></span>

<span data-ttu-id="86381-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="86381-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="86381-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="86381-108">Attributes</span></span>

<span data-ttu-id="86381-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="86381-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="86381-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="86381-110">Child elements</span></span>

|<span data-ttu-id="86381-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="86381-111">**Element**</span></span>|<span data-ttu-id="86381-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="86381-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="86381-113">Watermark</span><span class="sxs-lookup"><span data-stu-id="86381-113">Watermark</span></span>](watermark.md) <br/> |<span data-ttu-id="86381-114">Representa um indicador de evento na tabela de eventos de caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="86381-114">Represents an event bookmark in the mailbox events table.</span></span>  <br/> |
|[<span data-ttu-id="86381-115">TimeStamp</span><span class="sxs-lookup"><span data-stu-id="86381-115">TimeStamp</span></span>](timestamp.md) <br/> |<span data-ttu-id="86381-116">Representa o carimbo de hora de um evento de caixa de correio excluído item ou uma pasta.</span><span class="sxs-lookup"><span data-stu-id="86381-116">Represents the timestamp of a deleted item or folder mailbox event.</span></span>  <br/> |
|[<span data-ttu-id="86381-117">FolderId</span><span class="sxs-lookup"><span data-stu-id="86381-117">FolderId</span></span>](folderid.md) <br/> |<span data-ttu-id="86381-118">Representa o identificador da pasta excluído.</span><span class="sxs-lookup"><span data-stu-id="86381-118">Represents the identifier of the deleted folder.</span></span>  <br/> |
|[<span data-ttu-id="86381-119">ItemId</span><span class="sxs-lookup"><span data-stu-id="86381-119">ItemId</span></span>](itemid.md) <br/> |<span data-ttu-id="86381-120">Representa o identificador do item excluído.</span><span class="sxs-lookup"><span data-stu-id="86381-120">Represents the identifier of the deleted item.</span></span>  <br/> |
|[<span data-ttu-id="86381-121">ParentFolderId</span><span class="sxs-lookup"><span data-stu-id="86381-121">ParentFolderId</span></span>](parentfolderid.md) <br/> |<span data-ttu-id="86381-122">Representa o identificador da pasta antes da exclusão ou a pasta pai do item excluído.</span><span class="sxs-lookup"><span data-stu-id="86381-122">Represents the identifier of the parent folder of the deleted item or folder before deletion.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="86381-123">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="86381-123">Parent elements</span></span>

|<span data-ttu-id="86381-124">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="86381-124">**Element**</span></span>|<span data-ttu-id="86381-125">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="86381-125">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="86381-126">Notificação</span><span class="sxs-lookup"><span data-stu-id="86381-126">Notification</span></span>](notification-ex15websvcsotherref.md) <br/> |<span data-ttu-id="86381-127">Contém informações sobre a inscrição e os eventos que ocorreram desde a última notificação.</span><span class="sxs-lookup"><span data-stu-id="86381-127">Contains information about the subscription and the events that have occurred since the last notification.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="86381-128">Comentários</span><span class="sxs-lookup"><span data-stu-id="86381-128">Remarks</span></span>

<span data-ttu-id="86381-129">O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o MicrosoftExchange Server 2007 que tem instalada a função de servidor de Acesso para Cliente.</span><span class="sxs-lookup"><span data-stu-id="86381-129">The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="86381-130">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="86381-130">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="86381-131">Namespace</span><span class="sxs-lookup"><span data-stu-id="86381-131">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="86381-132">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="86381-132">Schema name</span></span>  <br/> |<span data-ttu-id="86381-133">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="86381-133">Types schema</span></span>  <br/> |
|<span data-ttu-id="86381-134">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="86381-134">Validation file</span></span>  <br/> |<span data-ttu-id="86381-135">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="86381-135">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="86381-136">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="86381-136">Can be empty</span></span>  <br/> |<span data-ttu-id="86381-137">False</span><span class="sxs-lookup"><span data-stu-id="86381-137">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="86381-138">Ver também</span><span class="sxs-lookup"><span data-stu-id="86381-138">See also</span></span>

- [<span data-ttu-id="86381-139">Inscrever-se a operação</span><span class="sxs-lookup"><span data-stu-id="86381-139">Subscribe operation</span></span>](subscribe-operation.md)  
- [<span data-ttu-id="86381-140">Operação GetEvents</span><span class="sxs-lookup"><span data-stu-id="86381-140">GetEvents operation</span></span>](getevents-operation.md)  
- [<span data-ttu-id="86381-141">Cancelar a operação</span><span class="sxs-lookup"><span data-stu-id="86381-141">Unsubscribe operation</span></span>](unsubscribe-operation.md)

