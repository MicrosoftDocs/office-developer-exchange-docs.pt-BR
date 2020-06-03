---
title: GetClientAccessTokenResponseMessage
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: 45ca2500-ceab-4c98-9576-cb9e158e5896
description: O elemento GetClientAccessTokenResponseMessage especifica a mensagem de resposta para uma solicitação GetClientAccessToken.
ms.openlocfilehash: e842353dfe91fa7df410203b53e22d5ec53e1e39
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44526680"
---
# <a name="getclientaccesstokenresponsemessage"></a><span data-ttu-id="1bfca-103">GetClientAccessTokenResponseMessage</span><span class="sxs-lookup"><span data-stu-id="1bfca-103">GetClientAccessTokenResponseMessage</span></span>

<span data-ttu-id="1bfca-104">O elemento **GetClientAccessTokenResponseMessage** especifica a mensagem de resposta para uma solicitação **GetClientAccessToken** .</span><span class="sxs-lookup"><span data-stu-id="1bfca-104">The **GetClientAccessTokenResponseMessage** element specifies the response message for a **GetClientAccessToken** request.</span></span> 
  
```XML
<GetClientAccessTokenResponseMessage ResponseClass=" Success | Warning | Error ">
    <Token/>
    <MessageText/>
    <ResponseCode/>
    <DescriptiveLinkKey/>
    <MessageXml/>
</GetClientAccessTokenResponseMessage>
```

 <span data-ttu-id="1bfca-105">**GetClientAccessTokenResponseMessageType**</span><span class="sxs-lookup"><span data-stu-id="1bfca-105">**GetClientAccessTokenResponseMessageType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="1bfca-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="1bfca-106">Attributes and elements</span></span>

<span data-ttu-id="1bfca-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="1bfca-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="1bfca-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="1bfca-108">Attributes</span></span>

|<span data-ttu-id="1bfca-109">**Atributo**</span><span class="sxs-lookup"><span data-stu-id="1bfca-109">**Attribute**</span></span>|<span data-ttu-id="1bfca-110">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="1bfca-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="1bfca-111">ResponseClass</span><span class="sxs-lookup"><span data-stu-id="1bfca-111">ResponseClass</span></span>  <br/> |<span data-ttu-id="1bfca-112">Indica a classe da resposta.</span><span class="sxs-lookup"><span data-stu-id="1bfca-112">Indicates the class of the response.</span></span>  <br/> |
   
#### <a name="responseclass"></a><span data-ttu-id="1bfca-113">ResponseClass</span><span class="sxs-lookup"><span data-stu-id="1bfca-113">ResponseClass</span></span>

|<span data-ttu-id="1bfca-114">**Valor**</span><span class="sxs-lookup"><span data-stu-id="1bfca-114">**Value**</span></span>|<span data-ttu-id="1bfca-115">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="1bfca-115">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="1bfca-116">Êxito</span><span class="sxs-lookup"><span data-stu-id="1bfca-116">Success</span></span>  <br/> |<span data-ttu-id="1bfca-117">Indica êxito.</span><span class="sxs-lookup"><span data-stu-id="1bfca-117">Indicates success.</span></span>  <br/> |
|<span data-ttu-id="1bfca-118">Aviso</span><span class="sxs-lookup"><span data-stu-id="1bfca-118">Warning</span></span>  <br/> |<span data-ttu-id="1bfca-119">Indica um aviso.</span><span class="sxs-lookup"><span data-stu-id="1bfca-119">Indicates a warning.</span></span>  <br/> |
|<span data-ttu-id="1bfca-120">Erro</span><span class="sxs-lookup"><span data-stu-id="1bfca-120">Error</span></span>  <br/> |<span data-ttu-id="1bfca-121">Indica um erro.</span><span class="sxs-lookup"><span data-stu-id="1bfca-121">Indicates an error.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="1bfca-122">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="1bfca-122">Child elements</span></span>

|<span data-ttu-id="1bfca-123">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="1bfca-123">**Element**</span></span>|<span data-ttu-id="1bfca-124">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="1bfca-124">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="1bfca-125">Token (ClientAccessTokenType)</span><span class="sxs-lookup"><span data-stu-id="1bfca-125">Token (ClientAccessTokenType)</span></span>](token-clientaccesstokentype.md) <br/> |<span data-ttu-id="1bfca-126">Especifica um token de acesso para cliente.</span><span class="sxs-lookup"><span data-stu-id="1bfca-126">Specifies a client access token.</span></span>  <br/> |
|[<span data-ttu-id="1bfca-127">DescriptiveLinkKey</span><span class="sxs-lookup"><span data-stu-id="1bfca-127">DescriptiveLinkKey</span></span>](descriptivelinkkey.md) <br/> |<span data-ttu-id="1bfca-128">Atualmente não usado e reservado para uso futuro.</span><span class="sxs-lookup"><span data-stu-id="1bfca-128">Currently unused and reserved for future use.</span></span>  <br/> |
|[<span data-ttu-id="1bfca-129">MessageText</span><span class="sxs-lookup"><span data-stu-id="1bfca-129">MessageText</span></span>](messagetext.md) <br/> |<span data-ttu-id="1bfca-130">Fornece uma descrição de texto do status da resposta.</span><span class="sxs-lookup"><span data-stu-id="1bfca-130">Provides a text description of the status of the response.</span></span>  <br/> |
|[<span data-ttu-id="1bfca-131">MessageXml</span><span class="sxs-lookup"><span data-stu-id="1bfca-131">MessageXml</span></span>](messagexml.md) <br/> |<span data-ttu-id="1bfca-132">Fornece informações adicionais de resposta de erro.</span><span class="sxs-lookup"><span data-stu-id="1bfca-132">Provides additional error response information.</span></span>  <br/> |
|[<span data-ttu-id="1bfca-133">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="1bfca-133">ResponseCode</span></span>](responsecode.md) <br/> |<span data-ttu-id="1bfca-134">Fornece informações de status sobre a solicitação.</span><span class="sxs-lookup"><span data-stu-id="1bfca-134">Provides status information about the request.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="1bfca-135">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="1bfca-135">Parent elements</span></span>

|<span data-ttu-id="1bfca-136">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="1bfca-136">**Element**</span></span>|<span data-ttu-id="1bfca-137">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="1bfca-137">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="1bfca-138">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="1bfca-138">ResponseMessages</span></span>](responsemessages.md) <br/> |<span data-ttu-id="1bfca-139">Contém as mensagens de resposta para uma solicitação de serviços Web do Exchange (EWS).</span><span class="sxs-lookup"><span data-stu-id="1bfca-139">Contains the response messages for an Exchange Web Services (EWS) request.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="1bfca-140">Comentários</span><span class="sxs-lookup"><span data-stu-id="1bfca-140">Remarks</span></span>

<span data-ttu-id="1bfca-141">Este elemento foi introduzido no Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="1bfca-141">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="1bfca-142">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="1bfca-142">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="1bfca-143">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="1bfca-143">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="1bfca-144">Namespace</span><span class="sxs-lookup"><span data-stu-id="1bfca-144">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="1bfca-145">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="1bfca-145">Schema Name</span></span>  <br/> |<span data-ttu-id="1bfca-146">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="1bfca-146">Message schema</span></span>  <br/> |
|<span data-ttu-id="1bfca-147">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="1bfca-147">Validation File</span></span>  <br/> |<span data-ttu-id="1bfca-148">messages. xsd</span><span class="sxs-lookup"><span data-stu-id="1bfca-148">messages.xsd</span></span>  <br/> |
|<span data-ttu-id="1bfca-149">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="1bfca-149">Can Be Empty</span></span>  <br/> ||
   
## <a name="see-also"></a><span data-ttu-id="1bfca-150">Confira também</span><span class="sxs-lookup"><span data-stu-id="1bfca-150">See also</span></span>



- [<span data-ttu-id="1bfca-151">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="1bfca-151">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

