---
title: ReferenceItemId
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- ReferenceItemId
api_type:
- schema
ms.assetid: 8fd4bb12-a94b-43f5-be3b-f435684e311d
description: O elemento ReferenceItemId identifica o item para o qual o objeto Response se refere.
ms.openlocfilehash: 3b77d75de91af8ec8fb7ae2d507377d1d976febf
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44457225"
---
# <a name="referenceitemid"></a><span data-ttu-id="d63e3-103">ReferenceItemId</span><span class="sxs-lookup"><span data-stu-id="d63e3-103">ReferenceItemId</span></span>

<span data-ttu-id="d63e3-104">O elemento **ReferenceItemId** identifica o item para o qual o objeto Response se refere.</span><span class="sxs-lookup"><span data-stu-id="d63e3-104">The **ReferenceItemId** element identifies the item to which the response object refers.</span></span> 
  
```xml
<ReferenceItemId Id="" ChangeKey="" />
```

 <span data-ttu-id="d63e3-105">**ItemIdtype**</span><span class="sxs-lookup"><span data-stu-id="d63e3-105">**ItemIdType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="d63e3-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="d63e3-106">Attributes and elements</span></span>

<span data-ttu-id="d63e3-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="d63e3-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="d63e3-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="d63e3-108">Attributes</span></span>

|<span data-ttu-id="d63e3-109">**Atributo**</span><span class="sxs-lookup"><span data-stu-id="d63e3-109">**Attribute**</span></span>|<span data-ttu-id="d63e3-110">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="d63e3-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="d63e3-111">**Id**</span><span class="sxs-lookup"><span data-stu-id="d63e3-111">**Id**</span></span> <br/> |<span data-ttu-id="d63e3-112">Identifica um item específico no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="d63e3-112">Identifies a specific item in the Exchange store.</span></span>  <br/> |
|<span data-ttu-id="d63e3-113">**ChangeKey**</span><span class="sxs-lookup"><span data-stu-id="d63e3-113">**ChangeKey**</span></span> <br/> |<span data-ttu-id="d63e3-114">Identifica uma versão específica de um item.</span><span class="sxs-lookup"><span data-stu-id="d63e3-114">Identifies a specific version of an item.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="d63e3-115">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="d63e3-115">Child elements</span></span>

<span data-ttu-id="d63e3-116">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="d63e3-116">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="d63e3-117">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="d63e3-117">Parent elements</span></span>

|<span data-ttu-id="d63e3-118">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="d63e3-118">**Element**</span></span>|<span data-ttu-id="d63e3-119">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="d63e3-119">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="d63e3-120">AcceptItem</span><span class="sxs-lookup"><span data-stu-id="d63e3-120">AcceptItem</span></span>](acceptitem.md) <br/> |<span data-ttu-id="d63e3-121">Representa uma resposta de aceitação para uma solicitação de reunião.</span><span class="sxs-lookup"><span data-stu-id="d63e3-121">Represents an Accept reply to a meeting request.</span></span>  <br/> |
|[<span data-ttu-id="d63e3-122">AcceptSharingInvitation</span><span class="sxs-lookup"><span data-stu-id="d63e3-122">AcceptSharingInvitation</span></span>](acceptsharinginvitation.md) <br/> |<span data-ttu-id="d63e3-123">Representa uma resposta de aceitação para um convite de compartilhamento.</span><span class="sxs-lookup"><span data-stu-id="d63e3-123">Represents an Accept reply to a sharing invitation.</span></span>  <br/> |
|[<span data-ttu-id="d63e3-124">CancelCalendarItem</span><span class="sxs-lookup"><span data-stu-id="d63e3-124">CancelCalendarItem</span></span>](cancelcalendaritem.md) <br/> |<span data-ttu-id="d63e3-125">Representa o objeto Response que é usado para cancelar uma reunião.</span><span class="sxs-lookup"><span data-stu-id="d63e3-125">Represents the response object that is used to cancel a meeting.</span></span>  <br/> |
|[<span data-ttu-id="d63e3-126">DeclineItem</span><span class="sxs-lookup"><span data-stu-id="d63e3-126">DeclineItem</span></span>](declineitem.md) <br/> |<span data-ttu-id="d63e3-127">Representa uma resposta de recusa a uma solicitação de reunião.</span><span class="sxs-lookup"><span data-stu-id="d63e3-127">Represents a Decline reply to a meeting request.</span></span>  <br/> |
|[<span data-ttu-id="d63e3-128">ForwardItem</span><span class="sxs-lookup"><span data-stu-id="d63e3-128">ForwardItem</span></span>](forwarditem.md) <br/> |<span data-ttu-id="d63e3-129">Contém um item de repositório do Exchange para encaminhar aos destinatários.</span><span class="sxs-lookup"><span data-stu-id="d63e3-129">Contains an Exchange store item to forward to recipients.</span></span>  <br/> |
|[<span data-ttu-id="d63e3-130">RemoveItem</span><span class="sxs-lookup"><span data-stu-id="d63e3-130">RemoveItem</span></span>](removeitem.md) <br/> |<span data-ttu-id="d63e3-131">Remove um item do repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="d63e3-131">Removes an item from the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="d63e3-132">ReplyAllToItem</span><span class="sxs-lookup"><span data-stu-id="d63e3-132">ReplyAllToItem</span></span>](replyalltoitem.md) <br/> |<span data-ttu-id="d63e3-133">Contém uma resposta a todos os destinatários identificados de um item no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="d63e3-133">Contains a reply to all identified recipients of an item in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="d63e3-134">ReplyToItem</span><span class="sxs-lookup"><span data-stu-id="d63e3-134">ReplyToItem</span></span>](replytoitem.md) <br/> |<span data-ttu-id="d63e3-135">Contém uma resposta para o criador de um item no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="d63e3-135">Contains a reply to the creator of an item in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="d63e3-136">SuppressReadReceipt</span><span class="sxs-lookup"><span data-stu-id="d63e3-136">SuppressReadReceipt</span></span>](suppressreadreceipt.md) <br/> |<span data-ttu-id="d63e3-137">Usado para responder às solicitações de confirmação de leitura.</span><span class="sxs-lookup"><span data-stu-id="d63e3-137">Used to respond to read receipt requests.</span></span>  <br/> |
|[<span data-ttu-id="d63e3-138">TentativelyAcceptItem</span><span class="sxs-lookup"><span data-stu-id="d63e3-138">TentativelyAcceptItem</span></span>](tentativelyacceptitem.md) <br/> |<span data-ttu-id="d63e3-139">Representa uma resposta provisória a uma solicitação de reunião.</span><span class="sxs-lookup"><span data-stu-id="d63e3-139">Represents a Tentative reply to a meeting request.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="d63e3-140">Comentários</span><span class="sxs-lookup"><span data-stu-id="d63e3-140">Remarks</span></span>

<span data-ttu-id="d63e3-141">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os serviços Web do Exchange do computador que está executando o Microsoft Exchange Server que tem a função de servidor de acesso para Cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="d63e3-141">The schema that describes this element is located in the IIS Virtual directory that hosts Exchange Web Services of the computer that is running Microsoft Exchange Server that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="d63e3-142">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="d63e3-142">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="d63e3-143">Namespace</span><span class="sxs-lookup"><span data-stu-id="d63e3-143">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="d63e3-144">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="d63e3-144">Schema Name</span></span>  <br/> |<span data-ttu-id="d63e3-145">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="d63e3-145">Types schema</span></span>  <br/> |
|<span data-ttu-id="d63e3-146">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="d63e3-146">Validation File</span></span>  <br/> |<span data-ttu-id="d63e3-147">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="d63e3-147">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="d63e3-148">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="d63e3-148">Can be Empty</span></span>  <br/> |<span data-ttu-id="d63e3-149">False</span><span class="sxs-lookup"><span data-stu-id="d63e3-149">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="d63e3-150">Confira também</span><span class="sxs-lookup"><span data-stu-id="d63e3-150">See also</span></span>



- [<span data-ttu-id="d63e3-151">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="d63e3-151">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

