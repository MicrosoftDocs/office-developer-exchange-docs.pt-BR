---
title: GetServerTimeZonesResponseMessage
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- GetServerTimeZonesResponseMessage
api_type:
- schema
ms.assetid: eb2592b2-144f-4c33-8df7-8e70dce7ab55
description: O elemento GetServerTimeZonesResponseMessage contém o status e o resultado de uma única solicitação de operação GetServerTimeZones.
ms.openlocfilehash: 594b194f7c73e8880b83db6e20bb447e682a525c
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/25/2018
ms.locfileid: "19823665"
---
# <a name="getservertimezonesresponsemessage"></a><span data-ttu-id="77cf3-103">GetServerTimeZonesResponseMessage</span><span class="sxs-lookup"><span data-stu-id="77cf3-103">GetServerTimeZonesResponseMessage</span></span>

<span data-ttu-id="77cf3-104">O elemento **GetServerTimeZonesResponseMessage** contém o status e o resultado de uma única solicitação de [operação GetServerTimeZones](getservertimezones-operation.md) .</span><span class="sxs-lookup"><span data-stu-id="77cf3-104">The **GetServerTimeZonesResponseMessage** element contains the status and result of a single [GetServerTimeZones operation](getservertimezones-operation.md) request.</span></span> 
  
```XML
<GetServerTimeZonesResponseMessage ResponseClass="">
   <MessageText/>
   <ResponseCode/>
   <DescriptiveLinkKey/>
   <MessageXml/>
   <TimeZoneDefinitions/>
</GetServerTimeZonesResponseMessage>
```

 <span data-ttu-id="77cf3-105">**GetServerTimeZonesResponseMessageType**</span><span class="sxs-lookup"><span data-stu-id="77cf3-105">**GetServerTimeZonesResponseMessageType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="77cf3-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="77cf3-106">Attributes and elements</span></span>

<span data-ttu-id="77cf3-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="77cf3-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="77cf3-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="77cf3-108">Attributes</span></span>

|<span data-ttu-id="77cf3-109">**Attribute**</span><span class="sxs-lookup"><span data-stu-id="77cf3-109">**Attribute**</span></span>|<span data-ttu-id="77cf3-110">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="77cf3-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="77cf3-111">**ResponseClass**</span><span class="sxs-lookup"><span data-stu-id="77cf3-111">**ResponseClass**</span></span> <br/> | <span data-ttu-id="77cf3-112">Descreve o status da resposta.</span><span class="sxs-lookup"><span data-stu-id="77cf3-112">Describes the status of the response.</span></span> <br/><br/><span data-ttu-id="77cf3-113">Os seguintes valores são válidos para este atributo:</span><span class="sxs-lookup"><span data-stu-id="77cf3-113">The following values are valid for this attribute:</span></span>  <br/><br/><span data-ttu-id="77cf3-114">-Êxito</span><span class="sxs-lookup"><span data-stu-id="77cf3-114">-  Success</span></span>  <br/><span data-ttu-id="77cf3-115">-Aviso</span><span class="sxs-lookup"><span data-stu-id="77cf3-115">-  Warning</span></span>  <br/><span data-ttu-id="77cf3-116">-Erro</span><span class="sxs-lookup"><span data-stu-id="77cf3-116">-  Error</span></span>  <br/> |
   
#### <a name="responseclass-attribute-values"></a><span data-ttu-id="77cf3-117">Valores de atributo ResponseClass</span><span class="sxs-lookup"><span data-stu-id="77cf3-117">ResponseClass attribute values</span></span>

|<span data-ttu-id="77cf3-118">**Valor**</span><span class="sxs-lookup"><span data-stu-id="77cf3-118">**Value**</span></span>|<span data-ttu-id="77cf3-119">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="77cf3-119">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="77cf3-120">**Sucesso**</span><span class="sxs-lookup"><span data-stu-id="77cf3-120">**Success**</span></span> <br/> |<span data-ttu-id="77cf3-121">Descreve uma solicitação que seja cumprida.</span><span class="sxs-lookup"><span data-stu-id="77cf3-121">Describes a request that is fulfilled.</span></span>  <br/> |
|<span data-ttu-id="77cf3-122">**Warning**</span><span class="sxs-lookup"><span data-stu-id="77cf3-122">**Warning**</span></span> <br/> | <span data-ttu-id="77cf3-123">Descreve uma solicitação que não foi processada.</span><span class="sxs-lookup"><span data-stu-id="77cf3-123">Describes a request that was not processed.</span></span> <span data-ttu-id="77cf3-124">Um aviso pode ser retornado se ocorreu um erro quando um item na solicitação estava processando e itens subsequentes não pôde ser processados.</span><span class="sxs-lookup"><span data-stu-id="77cf3-124">A warning may be returned if an error occurred while an item in the request was processing and subsequent items could not be processed.</span></span><br/><br/> <span data-ttu-id="77cf3-125">Estes são exemplos de fontes de avisos de:</span><span class="sxs-lookup"><span data-stu-id="77cf3-125">The following are examples of sources of warnings:</span></span> <br/> <br/><span data-ttu-id="77cf3-126">-O armazenamento do Exchange está offline durante o lote.</span><span class="sxs-lookup"><span data-stu-id="77cf3-126">-  The Exchange store is offline during the batch.</span></span>  <br/><span data-ttu-id="77cf3-127">-Active Directory Domain Services (AD DS) está offline.</span><span class="sxs-lookup"><span data-stu-id="77cf3-127">-  Active Directory Domain Services (AD DS) is offline.</span></span>  <br/><span data-ttu-id="77cf3-128">-Caixas de correio foram movidos.</span><span class="sxs-lookup"><span data-stu-id="77cf3-128">-  Mailboxes were moved.</span></span>  <br/><span data-ttu-id="77cf3-129">-O banco de dados de mensagens (MDB) está offline.</span><span class="sxs-lookup"><span data-stu-id="77cf3-129">-  The message database (MDB) is offline.</span></span>  <br/><span data-ttu-id="77cf3-130">-Uma senha expirou.</span><span class="sxs-lookup"><span data-stu-id="77cf3-130">-  A password is expired.</span></span>  <br/><span data-ttu-id="77cf3-131">-Uma cota foi excedida.</span><span class="sxs-lookup"><span data-stu-id="77cf3-131">-  A quota has been exceeded.</span></span>  <br/> |
|<span data-ttu-id="77cf3-132">**Erro**</span><span class="sxs-lookup"><span data-stu-id="77cf3-132">**Error**</span></span> <br/> | <span data-ttu-id="77cf3-133">Descreve uma solicitação que não puder ser atendida.</span><span class="sxs-lookup"><span data-stu-id="77cf3-133">Describes a request that cannot be fulfilled.</span></span> <br/><br/><span data-ttu-id="77cf3-134">Estes são exemplos de fontes de erros:</span><span class="sxs-lookup"><span data-stu-id="77cf3-134">The following are examples of sources of errors:</span></span>  <br/><br/><span data-ttu-id="77cf3-135">-Inválido atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="77cf3-135">-  Invalid attributes or elements</span></span>  <br/><span data-ttu-id="77cf3-136">-Atributos ou elementos fora do intervalo</span><span class="sxs-lookup"><span data-stu-id="77cf3-136">-  Attributes or elements out of range</span></span>  <br/><span data-ttu-id="77cf3-137">-Uma marca desconhecida</span><span class="sxs-lookup"><span data-stu-id="77cf3-137">-  An unknown tag</span></span>  <br/><span data-ttu-id="77cf3-138">-Um atributo ou elemento que não é válido no contexto</span><span class="sxs-lookup"><span data-stu-id="77cf3-138">-  An attribute or element that is not valid in the context</span></span>  <br/><span data-ttu-id="77cf3-139">-Uma tentativa de acesso não autorizado por qualquer cliente</span><span class="sxs-lookup"><span data-stu-id="77cf3-139">-  An unauthorized access attempt by any client</span></span>  <br/><span data-ttu-id="77cf3-140">-Uma falha no servidor em resposta a uma chamada de cliente válida</span><span class="sxs-lookup"><span data-stu-id="77cf3-140">-  A server-side failure in response to a valid client-side call</span></span>  <br/><br/>  <span data-ttu-id="77cf3-141">Informações sobre o erro podem ser encontradas nos elementos [ResponseCode](responsecode.md) e [MessageText](messagetext.md) .</span><span class="sxs-lookup"><span data-stu-id="77cf3-141">Information about the error can be found in the [ResponseCode](responsecode.md) and [MessageText](messagetext.md) elements.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="77cf3-142">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="77cf3-142">Child elements</span></span>

|<span data-ttu-id="77cf3-143">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="77cf3-143">**Element**</span></span>|<span data-ttu-id="77cf3-144">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="77cf3-144">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="77cf3-145">MessageText</span><span class="sxs-lookup"><span data-stu-id="77cf3-145">MessageText</span></span>](messagetext.md) <br/> |<span data-ttu-id="77cf3-146">Fornece uma descrição de texto do status da resposta.</span><span class="sxs-lookup"><span data-stu-id="77cf3-146">Provides a text description of the status of the response.</span></span>  <br/> |
|[<span data-ttu-id="77cf3-147">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="77cf3-147">ResponseCode</span></span>](responsecode.md) <br/> |<span data-ttu-id="77cf3-148">Fornece um código de erro que identifica o erro específico que enfrentaram a solicitação.</span><span class="sxs-lookup"><span data-stu-id="77cf3-148">Provides an error code that identifies the specific error that the request encountered.</span></span>  <br/> |
|[<span data-ttu-id="77cf3-149">DescriptiveLinkKey</span><span class="sxs-lookup"><span data-stu-id="77cf3-149">DescriptiveLinkKey</span></span>](descriptivelinkkey.md) <br/> |<span data-ttu-id="77cf3-150">No momento não utilizados e reservada para uso futuro.</span><span class="sxs-lookup"><span data-stu-id="77cf3-150">Currently unused and reserved for future use.</span></span> <span data-ttu-id="77cf3-151">Esse elemento contém um valor de 0.</span><span class="sxs-lookup"><span data-stu-id="77cf3-151">This element contains a value of 0.</span></span>  <br/> |
|[<span data-ttu-id="77cf3-152">MessageXml</span><span class="sxs-lookup"><span data-stu-id="77cf3-152">MessageXml</span></span>](messagexml.md) <br/> |<span data-ttu-id="77cf3-153">Fornece informações de resposta de erro adicionais.</span><span class="sxs-lookup"><span data-stu-id="77cf3-153">Provides additional error response information.</span></span>  <br/> |
|[<span data-ttu-id="77cf3-154">TimeZoneDefinitions</span><span class="sxs-lookup"><span data-stu-id="77cf3-154">TimeZoneDefinitions</span></span>](timezonedefinitions.md) <br/> |<span data-ttu-id="77cf3-155">Contém uma matriz de definições de fuso horário.</span><span class="sxs-lookup"><span data-stu-id="77cf3-155">Contains an array of time zone definitions.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="77cf3-156">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="77cf3-156">Parent elements</span></span>

|<span data-ttu-id="77cf3-157">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="77cf3-157">**Element**</span></span>|<span data-ttu-id="77cf3-158">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="77cf3-158">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="77cf3-159">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="77cf3-159">ResponseMessages</span></span>](responsemessages.md) <br/> |<span data-ttu-id="77cf3-160">Contém as mensagens de resposta para uma solicitação de serviços Web do Exchange (EWS).</span><span class="sxs-lookup"><span data-stu-id="77cf3-160">Contains the response messages for an Exchange Web Services (EWS) request.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="77cf3-161">Comentários</span><span class="sxs-lookup"><span data-stu-id="77cf3-161">Remarks</span></span>

<span data-ttu-id="77cf3-162">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="77cf3-162">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="77cf3-163">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="77cf3-163">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="77cf3-164">Namespace</span><span class="sxs-lookup"><span data-stu-id="77cf3-164">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="77cf3-165">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="77cf3-165">Schema Name</span></span>  <br/> |<span data-ttu-id="77cf3-166">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="77cf3-166">Messages schema</span></span>  <br/> |
|<span data-ttu-id="77cf3-167">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="77cf3-167">Validation File</span></span>  <br/> |<span data-ttu-id="77cf3-168">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="77cf3-168">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="77cf3-169">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="77cf3-169">Can be Empty</span></span>  <br/> |<span data-ttu-id="77cf3-170">False</span><span class="sxs-lookup"><span data-stu-id="77cf3-170">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="77cf3-171">Ver também</span><span class="sxs-lookup"><span data-stu-id="77cf3-171">See also</span></span>

- [<span data-ttu-id="77cf3-172">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="77cf3-172">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

