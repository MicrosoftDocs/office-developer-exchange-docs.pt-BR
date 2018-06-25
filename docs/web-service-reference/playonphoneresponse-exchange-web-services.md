---
title: PlayOnPhoneResponse (serviços Web do Exchange)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- PlayOnPhoneResponse
api_type:
- schema
ms.assetid: 578b70d1-dc9d-4bce-b859-0109b2d2bcec
description: O elemento PlayOnPhoneResponse Especifica a resposta a uma solicitação para reproduzir uma caixa postal por telefone.
ms.openlocfilehash: 203309bdd6d17b1c78054e673f8a340c2f069b38
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/25/2018
ms.locfileid: "19824831"
---
# <a name="playonphoneresponse-exchange-web-services"></a><span data-ttu-id="2f350-103">PlayOnPhoneResponse (serviços Web do Exchange)</span><span class="sxs-lookup"><span data-stu-id="2f350-103">PlayOnPhoneResponse (Exchange Web Services)</span></span>

<span data-ttu-id="2f350-104">O elemento **PlayOnPhoneResponse** Especifica a resposta a uma solicitação para reproduzir uma caixa postal por telefone.</span><span class="sxs-lookup"><span data-stu-id="2f350-104">The **PlayOnPhoneResponse** element specifies the response to a request to play a voice mail over the telephone.</span></span> 
  
```xml
<PlayOnPhoneResponse ResponseClass="">
   <MessageText/>
   <ResponseCode/>
   <DescriptiveLinkKey/>
   <MessageXml/>
   <PhoneCallId/>
</PlayOnPhoneResponse>
```

 <span data-ttu-id="2f350-105">**PlayOnPhoneResponseMessageType**</span><span class="sxs-lookup"><span data-stu-id="2f350-105">**PlayOnPhoneResponseMessageType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="2f350-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="2f350-106">Attributes and elements</span></span>

<span data-ttu-id="2f350-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="2f350-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="2f350-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="2f350-108">Attributes</span></span>

|<span data-ttu-id="2f350-109">**Attribute**</span><span class="sxs-lookup"><span data-stu-id="2f350-109">**Attribute**</span></span>|<span data-ttu-id="2f350-110">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="2f350-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="2f350-111">**ResponseClass**</span><span class="sxs-lookup"><span data-stu-id="2f350-111">**ResponseClass**</span></span> <br/> | <span data-ttu-id="2f350-112">Descreve o status da resposta.</span><span class="sxs-lookup"><span data-stu-id="2f350-112">Describes the status of the response.</span></span> <br/><br/><span data-ttu-id="2f350-113">Os seguintes valores são válidos para este atributo:</span><span class="sxs-lookup"><span data-stu-id="2f350-113">The following values are valid for this attribute:</span></span>  <br/><br/><span data-ttu-id="2f350-114">-Êxito</span><span class="sxs-lookup"><span data-stu-id="2f350-114">-  Success</span></span>  <br/><span data-ttu-id="2f350-115">-Aviso</span><span class="sxs-lookup"><span data-stu-id="2f350-115">-  Warning</span></span>  <br/><span data-ttu-id="2f350-116">-Erro</span><span class="sxs-lookup"><span data-stu-id="2f350-116">-  Error</span></span>  <br/> |
   
#### <a name="responseclass-attribute-values"></a><span data-ttu-id="2f350-117">Valores de atributo ResponseClass</span><span class="sxs-lookup"><span data-stu-id="2f350-117">ResponseClass attribute values</span></span>

|<span data-ttu-id="2f350-118">**Valor**</span><span class="sxs-lookup"><span data-stu-id="2f350-118">**Value**</span></span>|<span data-ttu-id="2f350-119">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="2f350-119">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="2f350-120">**Sucesso**</span><span class="sxs-lookup"><span data-stu-id="2f350-120">**Success**</span></span> <br/> |<span data-ttu-id="2f350-121">Descreve uma solicitação que seja cumprida.</span><span class="sxs-lookup"><span data-stu-id="2f350-121">Describes a request that is fulfilled.</span></span>  <br/> |
|<span data-ttu-id="2f350-122">**Warning**</span><span class="sxs-lookup"><span data-stu-id="2f350-122">**Warning**</span></span> <br/> | <span data-ttu-id="2f350-123">Descreve uma solicitação que não foi processada.</span><span class="sxs-lookup"><span data-stu-id="2f350-123">Describes a request that was not processed.</span></span> <span data-ttu-id="2f350-124">Um aviso pode ser retornado se ocorreu um erro quando um item na solicitação estava processando e itens subsequentes não pôde ser processados.</span><span class="sxs-lookup"><span data-stu-id="2f350-124">A warning may be returned if an error occurred while an item in the request was processing and subsequent items could not be processed.</span></span><br/><br/> <span data-ttu-id="2f350-125">Estes são exemplos de fontes de avisos de:</span><span class="sxs-lookup"><span data-stu-id="2f350-125">The following are examples of sources of warnings:</span></span> <br/><br/><span data-ttu-id="2f350-126">-O armazenamento do Exchange está offline durante o lote.</span><span class="sxs-lookup"><span data-stu-id="2f350-126">-  The Exchange store is offline during the batch.</span></span>  <br/><span data-ttu-id="2f350-127">-Active Directory Domain Services (AD DS) está offline.</span><span class="sxs-lookup"><span data-stu-id="2f350-127">-  Active Directory Domain Services (AD DS) is offline.</span></span>  <br/><span data-ttu-id="2f350-128">-Caixas de correio foram movidos.</span><span class="sxs-lookup"><span data-stu-id="2f350-128">-  Mailboxes were moved.</span></span>  <br/><span data-ttu-id="2f350-129">-O banco de dados de mensagens (MDB) está offline.</span><span class="sxs-lookup"><span data-stu-id="2f350-129">-  The message database (MDB) is offline.</span></span>  <br/><span data-ttu-id="2f350-130">-Uma senha expirou.</span><span class="sxs-lookup"><span data-stu-id="2f350-130">-  A password is expired.</span></span>  <br/><span data-ttu-id="2f350-131">-Uma cota foi excedida.</span><span class="sxs-lookup"><span data-stu-id="2f350-131">-  A quota has been exceeded.</span></span>  <br/> |
|<span data-ttu-id="2f350-132">**Erro**</span><span class="sxs-lookup"><span data-stu-id="2f350-132">**Error**</span></span> <br/> | <span data-ttu-id="2f350-133">Descreve uma solicitação que não puder ser atendida.</span><span class="sxs-lookup"><span data-stu-id="2f350-133">Describes a request that cannot be fulfilled.</span></span> <br/><br/><span data-ttu-id="2f350-134">Estes são exemplos de fontes de erros:</span><span class="sxs-lookup"><span data-stu-id="2f350-134">The following are examples of sources of errors:</span></span>  <br/><br/><span data-ttu-id="2f350-135">-Inválido atributos e elementos.</span><span class="sxs-lookup"><span data-stu-id="2f350-135">-  Invalid attributes or elements.</span></span>  <br/><span data-ttu-id="2f350-136">-Atributos ou elementos que estão fora do intervalo</span><span class="sxs-lookup"><span data-stu-id="2f350-136">-  Attributes or elements that are out of range</span></span>  <br/><span data-ttu-id="2f350-137">-Uma marca desconhecida.</span><span class="sxs-lookup"><span data-stu-id="2f350-137">-  An unknown tag.</span></span>  <br/><span data-ttu-id="2f350-138">-Um atributo ou elemento que não é válido no contexto.</span><span class="sxs-lookup"><span data-stu-id="2f350-138">-  An attribute or element that is not valid in the context.</span></span>  <br/><span data-ttu-id="2f350-139">-Uma tentativa de acesso não autorizado por qualquer cliente.</span><span class="sxs-lookup"><span data-stu-id="2f350-139">-  An unauthorized access attempt by any client.</span></span>  <br/><span data-ttu-id="2f350-140">-Uma falha no servidor em resposta a uma chamada de cliente válida.</span><span class="sxs-lookup"><span data-stu-id="2f350-140">-  A server-side failure in response to a valid client-side call.</span></span>  <br/><br/>  <span data-ttu-id="2f350-141">Informações sobre o erro podem ser encontradas no [ResponseCode](responsecode.md) e tópicos de elemento [MessageText](messagetext.md) .</span><span class="sxs-lookup"><span data-stu-id="2f350-141">Information about the error can be found in the [ResponseCode](responsecode.md) and [MessageText](messagetext.md) element topics.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="2f350-142">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="2f350-142">Child elements</span></span>

|<span data-ttu-id="2f350-143">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="2f350-143">**Element**</span></span>|<span data-ttu-id="2f350-144">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="2f350-144">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="2f350-145">MessageText</span><span class="sxs-lookup"><span data-stu-id="2f350-145">MessageText</span></span>](messagetext.md) <br/> |<span data-ttu-id="2f350-146">Fornece uma descrição de texto do status da resposta.</span><span class="sxs-lookup"><span data-stu-id="2f350-146">Provides a text description of the status of the response.</span></span>  <br/> |
|[<span data-ttu-id="2f350-147">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="2f350-147">ResponseCode</span></span>](responsecode.md) <br/> |<span data-ttu-id="2f350-148">Fornece um código de erro que identifica o erro específico que enfrentaram a solicitação.</span><span class="sxs-lookup"><span data-stu-id="2f350-148">Provides an error code that identifies the specific error that the request encountered.</span></span>  <br/> |
|[<span data-ttu-id="2f350-149">DescriptiveLinkKey</span><span class="sxs-lookup"><span data-stu-id="2f350-149">DescriptiveLinkKey</span></span>](descriptivelinkkey.md) <br/> |<span data-ttu-id="2f350-150">No momento não utilizados e reservada para uso futuro.</span><span class="sxs-lookup"><span data-stu-id="2f350-150">Currently unused and reserved for future use.</span></span> <span data-ttu-id="2f350-151">Esse elemento contém um valor de 0.</span><span class="sxs-lookup"><span data-stu-id="2f350-151">This element contains a value of 0.</span></span>  <br/> |
|[<span data-ttu-id="2f350-152">MessageXml</span><span class="sxs-lookup"><span data-stu-id="2f350-152">MessageXml</span></span>](messagexml.md) <br/> |<span data-ttu-id="2f350-153">Fornece informações de resposta de erro adicionais.</span><span class="sxs-lookup"><span data-stu-id="2f350-153">Provides additional error response information.</span></span>  <br/> |
|[<span data-ttu-id="2f350-154">PhoneCallId</span><span class="sxs-lookup"><span data-stu-id="2f350-154">PhoneCallId</span></span>](phonecallid.md) <br/> |<span data-ttu-id="2f350-155">Especifica o identificador de chamada telefônica.</span><span class="sxs-lookup"><span data-stu-id="2f350-155">Specifies the telephone call identifier.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="2f350-156">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="2f350-156">Parent elements</span></span>

<span data-ttu-id="2f350-157">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="2f350-157">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="2f350-158">Comentários</span><span class="sxs-lookup"><span data-stu-id="2f350-158">Remarks</span></span>

<span data-ttu-id="2f350-159">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="2f350-159">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="2f350-160">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="2f350-160">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="2f350-161">Namespace</span><span class="sxs-lookup"><span data-stu-id="2f350-161">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="2f350-162">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="2f350-162">Schema Name</span></span>  <br/> |<span data-ttu-id="2f350-163">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="2f350-163">Messages schema</span></span>  <br/> |
|<span data-ttu-id="2f350-164">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="2f350-164">Validation File</span></span>  <br/> |<span data-ttu-id="2f350-165">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="2f350-165">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="2f350-166">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="2f350-166">Can be Empty</span></span>  <br/> |<span data-ttu-id="2f350-167">False</span><span class="sxs-lookup"><span data-stu-id="2f350-167">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="2f350-168">Ver também</span><span class="sxs-lookup"><span data-stu-id="2f350-168">See also</span></span>

- [<span data-ttu-id="2f350-169">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="2f350-169">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

