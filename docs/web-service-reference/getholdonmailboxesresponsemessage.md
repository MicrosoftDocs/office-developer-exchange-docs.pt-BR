---
title: GetHoldOnMailboxesResponseMessage
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: 0f7d0d90-d418-4ce9-8cea-afe8f14728c3
description: O elemento GetHoldOnMailboxesResponseMessage especifica a mensagem de resposta para uma solicitação GetHoldOnMailboxes.
ms.openlocfilehash: 31832c11181bdca482e88419dd46ff1eacf77ea6
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44462947"
---
# <a name="getholdonmailboxesresponsemessage"></a><span data-ttu-id="4111b-103">GetHoldOnMailboxesResponseMessage</span><span class="sxs-lookup"><span data-stu-id="4111b-103">GetHoldOnMailboxesResponseMessage</span></span>

<span data-ttu-id="4111b-104">O elemento **GetHoldOnMailboxesResponseMessage** especifica a mensagem de resposta para uma solicitação **GetHoldOnMailboxes** .</span><span class="sxs-lookup"><span data-stu-id="4111b-104">The **GetHoldOnMailboxesResponseMessage** element specifies the response message for a **GetHoldOnMailboxes** request.</span></span> 
  
```XML
<GetHoldOnMailboxesResponseMessage ResponseClass=" Success | Warning | Error ">
    <MailboxHoldResult/>
    <MessageText/>
    <ResponseCode/>
    <DescriptiveLinkKey/>
    <MessageXml/>
</GetHoldOnMailboxesResponseMessage>
```

 <span data-ttu-id="4111b-105">**GetHoldOnMailboxesResponseMessageType**</span><span class="sxs-lookup"><span data-stu-id="4111b-105">**GetHoldOnMailboxesResponseMessageType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="4111b-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="4111b-106">Attributes and elements</span></span>

<span data-ttu-id="4111b-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="4111b-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="4111b-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="4111b-108">Attributes</span></span>

|<span data-ttu-id="4111b-109">**Atributo**</span><span class="sxs-lookup"><span data-stu-id="4111b-109">**Attribute**</span></span>|<span data-ttu-id="4111b-110">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="4111b-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="4111b-111">ResponseClass</span><span class="sxs-lookup"><span data-stu-id="4111b-111">ResponseClass</span></span>  <br/> |<span data-ttu-id="4111b-112">Indica a classe da resposta.</span><span class="sxs-lookup"><span data-stu-id="4111b-112">Indicates the class of the response.</span></span>  <br/> |
   
#### <a name="responseclass"></a><span data-ttu-id="4111b-113">ResponseClass</span><span class="sxs-lookup"><span data-stu-id="4111b-113">ResponseClass</span></span>

|<span data-ttu-id="4111b-114">**Valor**</span><span class="sxs-lookup"><span data-stu-id="4111b-114">**Value**</span></span>|<span data-ttu-id="4111b-115">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="4111b-115">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="4111b-116">Êxito</span><span class="sxs-lookup"><span data-stu-id="4111b-116">Success</span></span>  <br/> |<span data-ttu-id="4111b-117">Indica êxito.</span><span class="sxs-lookup"><span data-stu-id="4111b-117">Indicates success.</span></span>  <br/> |
|<span data-ttu-id="4111b-118">Aviso</span><span class="sxs-lookup"><span data-stu-id="4111b-118">Warning</span></span>  <br/> |<span data-ttu-id="4111b-119">Indica um aviso.</span><span class="sxs-lookup"><span data-stu-id="4111b-119">Indicates a warning.</span></span>  <br/> |
|<span data-ttu-id="4111b-120">Erro</span><span class="sxs-lookup"><span data-stu-id="4111b-120">Error</span></span>  <br/> |<span data-ttu-id="4111b-121">Indica um erro.</span><span class="sxs-lookup"><span data-stu-id="4111b-121">Indicates an error.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="4111b-122">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="4111b-122">Child elements</span></span>

|<span data-ttu-id="4111b-123">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="4111b-123">**Element**</span></span>|<span data-ttu-id="4111b-124">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="4111b-124">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="4111b-125">MailboxHoldResult</span><span class="sxs-lookup"><span data-stu-id="4111b-125">MailboxHoldResult</span></span>](mailboxholdresult.md) <br/> |<span data-ttu-id="4111b-126">Contém o resultado da solicitação **GetHoldOnMailboxes** .</span><span class="sxs-lookup"><span data-stu-id="4111b-126">Contains the result of the **GetHoldOnMailboxes** request.</span></span>  <br/> |
|[<span data-ttu-id="4111b-127">DescriptiveLinkKey</span><span class="sxs-lookup"><span data-stu-id="4111b-127">DescriptiveLinkKey</span></span>](descriptivelinkkey.md) <br/> |<span data-ttu-id="4111b-128">Atualmente não usado e reservado para uso futuro.</span><span class="sxs-lookup"><span data-stu-id="4111b-128">Currently unused and reserved for future use.</span></span>  <br/> |
|[<span data-ttu-id="4111b-129">MessageText</span><span class="sxs-lookup"><span data-stu-id="4111b-129">MessageText</span></span>](messagetext.md) <br/> |<span data-ttu-id="4111b-130">Fornece uma descrição de texto do status da resposta.</span><span class="sxs-lookup"><span data-stu-id="4111b-130">Provides a text description of the status of the response.</span></span>  <br/> |
|[<span data-ttu-id="4111b-131">MessageXml</span><span class="sxs-lookup"><span data-stu-id="4111b-131">MessageXml</span></span>](messagexml.md) <br/> |<span data-ttu-id="4111b-132">Fornece informações adicionais de resposta de erro.</span><span class="sxs-lookup"><span data-stu-id="4111b-132">Provides additional error response information.</span></span>  <br/> |
|[<span data-ttu-id="4111b-133">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="4111b-133">ResponseCode</span></span>](responsecode.md) <br/> |<span data-ttu-id="4111b-134">Fornece informações de status sobre a solicitação.</span><span class="sxs-lookup"><span data-stu-id="4111b-134">Provides status information about the request.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="4111b-135">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="4111b-135">Parent elements</span></span>

|<span data-ttu-id="4111b-136">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="4111b-136">**Element**</span></span>|<span data-ttu-id="4111b-137">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="4111b-137">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="4111b-138">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="4111b-138">ResponseMessages</span></span>](responsemessages.md) <br/> |<span data-ttu-id="4111b-139">Contém as mensagens de resposta para uma solicitação de serviços Web do Exchange (EWS).</span><span class="sxs-lookup"><span data-stu-id="4111b-139">Contains the response messages for an Exchange Web Services (EWS) request.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="4111b-140">Comentários</span><span class="sxs-lookup"><span data-stu-id="4111b-140">Remarks</span></span>

<span data-ttu-id="4111b-141">Este elemento foi introduzido no Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="4111b-141">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="4111b-142">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="4111b-142">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="4111b-143">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="4111b-143">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="4111b-144">Namespace</span><span class="sxs-lookup"><span data-stu-id="4111b-144">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="4111b-145">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="4111b-145">Schema Name</span></span>  <br/> |<span data-ttu-id="4111b-146">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="4111b-146">Message schema</span></span>  <br/> |
|<span data-ttu-id="4111b-147">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="4111b-147">Validation File</span></span>  <br/> |<span data-ttu-id="4111b-148">messages. xsd</span><span class="sxs-lookup"><span data-stu-id="4111b-148">messages.xsd</span></span>  <br/> |
|<span data-ttu-id="4111b-149">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="4111b-149">Can Be Empty</span></span>  <br/> ||
   
## <a name="see-also"></a><span data-ttu-id="4111b-150">Também consulte</span><span class="sxs-lookup"><span data-stu-id="4111b-150">See also</span></span>



- [<span data-ttu-id="4111b-151">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="4111b-151">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

