---
title: GetSearchableMailboxesResponseMessage
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: f45865fd-4626-4d80-84f6-7989339fdd85
description: O elemento GetSearchableMailboxesResponseMessage especifica a mensagem de resposta para uma solicitação GetSearchableMailboxes.
ms.openlocfilehash: 69f45d87cfbd398013d021cdd39b55497d78ae04
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44458254"
---
# <a name="getsearchablemailboxesresponsemessage"></a><span data-ttu-id="e0a9e-103">GetSearchableMailboxesResponseMessage</span><span class="sxs-lookup"><span data-stu-id="e0a9e-103">GetSearchableMailboxesResponseMessage</span></span>

<span data-ttu-id="e0a9e-104">O elemento **GetSearchableMailboxesResponseMessage** especifica a mensagem de resposta para uma solicitação **GetSearchableMailboxes** .</span><span class="sxs-lookup"><span data-stu-id="e0a9e-104">The **GetSearchableMailboxesResponseMessage** element specifies the response message for a **GetSearchableMailboxes** request.</span></span> 
  
```XML
<GetSearchableMailboxesResponseMessage ResponseClass=" Success | Warning | Error ">
    <SearchableMailboxes/>
    <MessageText/>
    <ResponseCode/>
    <DescriptiveLinkKey/>
    <MessageXml/>
</GetSearchablemailboxesResponseMessage>
```

 <span data-ttu-id="e0a9e-105">**GetSearchableMailboxesResponseMessageType**</span><span class="sxs-lookup"><span data-stu-id="e0a9e-105">**GetSearchableMailboxesResponseMessageType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="e0a9e-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="e0a9e-106">Attributes and elements</span></span>

<span data-ttu-id="e0a9e-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="e0a9e-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="e0a9e-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="e0a9e-108">Attributes</span></span>

|<span data-ttu-id="e0a9e-109">**Atributo**</span><span class="sxs-lookup"><span data-stu-id="e0a9e-109">**Attribute**</span></span>|<span data-ttu-id="e0a9e-110">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="e0a9e-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="e0a9e-111">ResponseClass</span><span class="sxs-lookup"><span data-stu-id="e0a9e-111">ResponseClass</span></span>  <br/> |<span data-ttu-id="e0a9e-112">Indica a classe da resposta.</span><span class="sxs-lookup"><span data-stu-id="e0a9e-112">Indicates the class of the response.</span></span>  <br/> |
   
#### <a name="responseclass"></a><span data-ttu-id="e0a9e-113">ResponseClass</span><span class="sxs-lookup"><span data-stu-id="e0a9e-113">ResponseClass</span></span>

|<span data-ttu-id="e0a9e-114">**Valor**</span><span class="sxs-lookup"><span data-stu-id="e0a9e-114">**Value**</span></span>|<span data-ttu-id="e0a9e-115">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="e0a9e-115">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="e0a9e-116">Êxito</span><span class="sxs-lookup"><span data-stu-id="e0a9e-116">Success</span></span>  <br/> |<span data-ttu-id="e0a9e-117">Indica êxito.</span><span class="sxs-lookup"><span data-stu-id="e0a9e-117">Indicates success.</span></span>  <br/> |
|<span data-ttu-id="e0a9e-118">Aviso</span><span class="sxs-lookup"><span data-stu-id="e0a9e-118">Warning</span></span>  <br/> |<span data-ttu-id="e0a9e-119">Indica um aviso.</span><span class="sxs-lookup"><span data-stu-id="e0a9e-119">Indicates a warning.</span></span>  <br/> |
|<span data-ttu-id="e0a9e-120">Erro</span><span class="sxs-lookup"><span data-stu-id="e0a9e-120">Error</span></span>  <br/> |<span data-ttu-id="e0a9e-121">Indica um erro.</span><span class="sxs-lookup"><span data-stu-id="e0a9e-121">Indicates an error.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="e0a9e-122">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="e0a9e-122">Child elements</span></span>

|<span data-ttu-id="e0a9e-123">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="e0a9e-123">**Element**</span></span>|<span data-ttu-id="e0a9e-124">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="e0a9e-124">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="e0a9e-125">SearchableMailboxes</span><span class="sxs-lookup"><span data-stu-id="e0a9e-125">SearchableMailboxes</span></span>](searchablemailboxes.md) <br/> |<span data-ttu-id="e0a9e-126">Contém uma matriz das caixas de correio retornadas de uma solicitação **GetSearchableMailboxes** .</span><span class="sxs-lookup"><span data-stu-id="e0a9e-126">Contains an array of the mailboxes returned from a **GetSearchableMailboxes** request.</span></span>  <br/> |
|[<span data-ttu-id="e0a9e-127">DescriptiveLinkKey</span><span class="sxs-lookup"><span data-stu-id="e0a9e-127">DescriptiveLinkKey</span></span>](descriptivelinkkey.md) <br/> |<span data-ttu-id="e0a9e-128">Atualmente não usado e reservado para uso futuro.</span><span class="sxs-lookup"><span data-stu-id="e0a9e-128">Currently unused and reserved for future use.</span></span>  <br/> |
|[<span data-ttu-id="e0a9e-129">MessageText</span><span class="sxs-lookup"><span data-stu-id="e0a9e-129">MessageText</span></span>](messagetext.md) <br/> |<span data-ttu-id="e0a9e-130">Fornece uma descrição de texto do status da resposta.</span><span class="sxs-lookup"><span data-stu-id="e0a9e-130">Provides a text description of the status of the response.</span></span>  <br/> |
|[<span data-ttu-id="e0a9e-131">MessageXml</span><span class="sxs-lookup"><span data-stu-id="e0a9e-131">MessageXml</span></span>](messagexml.md) <br/> |<span data-ttu-id="e0a9e-132">Fornece informações adicionais de resposta de erro.</span><span class="sxs-lookup"><span data-stu-id="e0a9e-132">Provides additional error response information.</span></span>  <br/> |
|[<span data-ttu-id="e0a9e-133">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="e0a9e-133">ResponseCode</span></span>](responsecode.md) <br/> |<span data-ttu-id="e0a9e-134">Fornece informações de status sobre a solicitação.</span><span class="sxs-lookup"><span data-stu-id="e0a9e-134">Provides status information about the request.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="e0a9e-135">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="e0a9e-135">Parent elements</span></span>

|<span data-ttu-id="e0a9e-136">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="e0a9e-136">**Element**</span></span>|<span data-ttu-id="e0a9e-137">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="e0a9e-137">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="e0a9e-138">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="e0a9e-138">ResponseMessages</span></span>](responsemessages.md) <br/> |<span data-ttu-id="e0a9e-139">Contém as mensagens de resposta para uma solicitação de serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="e0a9e-139">Contains the response messages for an Exchange Web Services request.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="e0a9e-140">Comentários</span><span class="sxs-lookup"><span data-stu-id="e0a9e-140">Remarks</span></span>

<span data-ttu-id="e0a9e-141">Este elemento foi introduzido no Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="e0a9e-141">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="e0a9e-142">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="e0a9e-142">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="e0a9e-143">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="e0a9e-143">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="e0a9e-144">Namespace</span><span class="sxs-lookup"><span data-stu-id="e0a9e-144">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="e0a9e-145">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="e0a9e-145">Schema Name</span></span>  <br/> |<span data-ttu-id="e0a9e-146">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="e0a9e-146">Message schema</span></span>  <br/> |
|<span data-ttu-id="e0a9e-147">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="e0a9e-147">Validation File</span></span>  <br/> |<span data-ttu-id="e0a9e-148">messages. xsd</span><span class="sxs-lookup"><span data-stu-id="e0a9e-148">messages.xsd</span></span>  <br/> |
|<span data-ttu-id="e0a9e-149">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="e0a9e-149">Can Be Empty</span></span>  <br/> ||
   
## <a name="see-also"></a><span data-ttu-id="e0a9e-150">Também consulte</span><span class="sxs-lookup"><span data-stu-id="e0a9e-150">See also</span></span>



- [<span data-ttu-id="e0a9e-151">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="e0a9e-151">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

