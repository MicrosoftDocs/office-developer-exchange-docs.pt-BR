---
title: GetPhoneCallInformationResponse
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- GetPhoneCallInformationResponse
api_type:
- schema
ms.assetid: 17f79875-46ec-4289-b974-b3c35af429cd
description: O elemento GetPhoneCallInformationResponse define uma resposta a uma única solicitação de GetPhoneCallInformation.
ms.openlocfilehash: 5bc060504ea734ec2d7e01707ef6bbdb0aa665d3
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44457883"
---
# <a name="getphonecallinformationresponse"></a><span data-ttu-id="da947-103">GetPhoneCallInformationResponse</span><span class="sxs-lookup"><span data-stu-id="da947-103">GetPhoneCallInformationResponse</span></span>

<span data-ttu-id="da947-104">O elemento **GetPhoneCallInformationResponse** define uma resposta a uma única solicitação de GetPhoneCallInformation.</span><span class="sxs-lookup"><span data-stu-id="da947-104">The **GetPhoneCallInformationResponse** element defines a response to a single GetPhoneCallInformation request.</span></span> 
  
```xml
<GetPhoneCallInformationResponse ResponseClass="">
   <MessageText/>
   <ResponseCode/>
   <DescriptiveLinkKey/>
   <MessageXml/>   <PhoneCallInformation/>
</GetPhoneCallInformationResponse>
```

 <span data-ttu-id="da947-105">**GetPhoneCallInformationResponseMessageType**</span><span class="sxs-lookup"><span data-stu-id="da947-105">**GetPhoneCallInformationResponseMessageType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="da947-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="da947-106">Attributes and elements</span></span>

<span data-ttu-id="da947-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="da947-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="da947-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="da947-108">Attributes</span></span>

|<span data-ttu-id="da947-109">**Atributo**</span><span class="sxs-lookup"><span data-stu-id="da947-109">**Attribute**</span></span>|<span data-ttu-id="da947-110">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="da947-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="da947-111">**ResponseClass**</span><span class="sxs-lookup"><span data-stu-id="da947-111">**ResponseClass**</span></span> <br/> | <span data-ttu-id="da947-112">Descreve o status da resposta.</span><span class="sxs-lookup"><span data-stu-id="da947-112">Describes the status of the response.</span></span> <br/><br/><span data-ttu-id="da947-113">Os seguintes valores são válidos para este atributo:</span><span class="sxs-lookup"><span data-stu-id="da947-113">The following values are valid for this attribute:</span></span> <br/> <br/><span data-ttu-id="da947-114">-Êxito</span><span class="sxs-lookup"><span data-stu-id="da947-114">-  Success</span></span>  <br/><span data-ttu-id="da947-115">-Aviso</span><span class="sxs-lookup"><span data-stu-id="da947-115">-  Warning</span></span>  <br/><span data-ttu-id="da947-116">-Erro</span><span class="sxs-lookup"><span data-stu-id="da947-116">-  Error</span></span>  <br/> |
   
#### <a name="responseclass-attribute-values"></a><span data-ttu-id="da947-117">Valores de atributo ResponseClass</span><span class="sxs-lookup"><span data-stu-id="da947-117">ResponseClass attribute values</span></span>

|<span data-ttu-id="da947-118">**Valor**</span><span class="sxs-lookup"><span data-stu-id="da947-118">**Value**</span></span>|<span data-ttu-id="da947-119">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="da947-119">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="da947-120">**Success**</span><span class="sxs-lookup"><span data-stu-id="da947-120">**Success**</span></span> <br/> |<span data-ttu-id="da947-121">Descreve uma solicitação que é atendida.</span><span class="sxs-lookup"><span data-stu-id="da947-121">Describes a request that is fulfilled.</span></span>  <br/> |
|<span data-ttu-id="da947-122">**Aviso**</span><span class="sxs-lookup"><span data-stu-id="da947-122">**Warning**</span></span> <br/> | <span data-ttu-id="da947-123">Descreve uma solicitação que não foi processada.</span><span class="sxs-lookup"><span data-stu-id="da947-123">Describes a request that was not processed.</span></span> <span data-ttu-id="da947-124">Um aviso pode ser retornado se um erro ocorreu enquanto um item na solicitação estava sendo processado e não foi possível processar os itens subsequentes.</span><span class="sxs-lookup"><span data-stu-id="da947-124">A warning may be returned if an error occurred while an item in the request was processing and subsequent items could not be processed.</span></span><br/><br/> <span data-ttu-id="da947-125">A seguir estão exemplos de fontes de avisos:</span><span class="sxs-lookup"><span data-stu-id="da947-125">The following are examples of sources of warnings:</span></span> <br/> <br/><span data-ttu-id="da947-126">– O repositório do Exchange está offline durante o lote.</span><span class="sxs-lookup"><span data-stu-id="da947-126">-  The Exchange store is offline during the batch.</span></span>  <br/><span data-ttu-id="da947-127">– O serviço de diretório do Active Directory está offline.</span><span class="sxs-lookup"><span data-stu-id="da947-127">-  The Active Directory directory service is offline.</span></span>  <br/><span data-ttu-id="da947-128">-As caixas de correio foram movidas.</span><span class="sxs-lookup"><span data-stu-id="da947-128">-  Mailboxes were moved.</span></span>  <br/><span data-ttu-id="da947-129">– O banco de dados de mensagens (MDB) está offline.</span><span class="sxs-lookup"><span data-stu-id="da947-129">-  The message database (MDB) is offline.</span></span>  <br/><span data-ttu-id="da947-130">-Uma senha expirou.</span><span class="sxs-lookup"><span data-stu-id="da947-130">-  A password is expired.</span></span>  <br/><span data-ttu-id="da947-131">-Uma cota foi excedida.</span><span class="sxs-lookup"><span data-stu-id="da947-131">-  A quota has been exceeded.</span></span>  <br/> |
|<span data-ttu-id="da947-132">**Error**</span><span class="sxs-lookup"><span data-stu-id="da947-132">**Error**</span></span> <br/> | <span data-ttu-id="da947-133">Descreve uma solicitação que não pode ser atendida.</span><span class="sxs-lookup"><span data-stu-id="da947-133">Describes a request that cannot be fulfilled.</span></span> <br/><br/><span data-ttu-id="da947-134">A seguir estão exemplos de fontes de erros:</span><span class="sxs-lookup"><span data-stu-id="da947-134">The following are examples of sources of errors:</span></span>  <br/><br/><span data-ttu-id="da947-135">-Atributos ou elementos inválidos</span><span class="sxs-lookup"><span data-stu-id="da947-135">-  Invalid attributes or elements</span></span>  <br/><span data-ttu-id="da947-136">-Atributos ou elementos fora do intervalo</span><span class="sxs-lookup"><span data-stu-id="da947-136">-  Attributes or elements out of range</span></span>  <br/><span data-ttu-id="da947-137">– Marca desconhecida</span><span class="sxs-lookup"><span data-stu-id="da947-137">-  Unknown tag</span></span>  <br/><span data-ttu-id="da947-138">-Atributo ou elemento não válido no contexto</span><span class="sxs-lookup"><span data-stu-id="da947-138">-  Attribute or element not valid in the context</span></span>  <br/><span data-ttu-id="da947-139">– Tentativa de acesso não autorizado por qualquer cliente</span><span class="sxs-lookup"><span data-stu-id="da947-139">-  Unauthorized access attempt by any client</span></span>  <br/><span data-ttu-id="da947-140">-Falha do servidor em resposta a uma chamada válida do lado do cliente</span><span class="sxs-lookup"><span data-stu-id="da947-140">-  Server-side failure in response to a valid client-side call</span></span>  <br/><br/>  <span data-ttu-id="da947-141">As informações sobre o erro podem ser encontradas nos elementos [ResponseCode](responsecode.md) e [MessageText](messagetext.md) .</span><span class="sxs-lookup"><span data-stu-id="da947-141">Information about the error can be found in the [ResponseCode](responsecode.md) and [MessageText](messagetext.md) elements.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="da947-142">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="da947-142">Child elements</span></span>

|<span data-ttu-id="da947-143">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="da947-143">**Element**</span></span>|<span data-ttu-id="da947-144">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="da947-144">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="da947-145">MessageText</span><span class="sxs-lookup"><span data-stu-id="da947-145">MessageText</span></span>](messagetext.md) <br/> |<span data-ttu-id="da947-146">Fornece uma descrição de texto do status da resposta.</span><span class="sxs-lookup"><span data-stu-id="da947-146">Provides a text description of the status of the response.</span></span>  <br/> |
|[<span data-ttu-id="da947-147">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="da947-147">ResponseCode</span></span>](responsecode.md) <br/> |<span data-ttu-id="da947-148">Fornece um código de erro que identifica o erro específico que a solicitação encontrou.</span><span class="sxs-lookup"><span data-stu-id="da947-148">Provides an error code that identifies the specific error that the request encountered.</span></span>  <br/> |
|[<span data-ttu-id="da947-149">DescriptiveLinkKey</span><span class="sxs-lookup"><span data-stu-id="da947-149">DescriptiveLinkKey</span></span>](descriptivelinkkey.md) <br/> |<span data-ttu-id="da947-150">Atualmente não usado e reservado para uso futuro.</span><span class="sxs-lookup"><span data-stu-id="da947-150">Currently unused and reserved for future use.</span></span> <span data-ttu-id="da947-151">Este elemento contém um valor de 0.</span><span class="sxs-lookup"><span data-stu-id="da947-151">This element contains a value of 0.</span></span>  <br/> |
|[<span data-ttu-id="da947-152">MessageXml</span><span class="sxs-lookup"><span data-stu-id="da947-152">MessageXml</span></span>](messagexml.md) <br/> |<span data-ttu-id="da947-153">Fornece informações adicionais de resposta de erro.</span><span class="sxs-lookup"><span data-stu-id="da947-153">Provides additional error response information.</span></span>  <br/> |
|[<span data-ttu-id="da947-154">PhoneCallInformation</span><span class="sxs-lookup"><span data-stu-id="da947-154">PhoneCallInformation</span></span>](phonecallinformation.md) <br/> |<span data-ttu-id="da947-155">Especifica as informações de estado de uma chamada telefônica.</span><span class="sxs-lookup"><span data-stu-id="da947-155">Specifies the state information for a phone call.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="da947-156">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="da947-156">Parent elements</span></span>

<span data-ttu-id="da947-157">Nenhum</span><span class="sxs-lookup"><span data-stu-id="da947-157">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="da947-158">Comentários</span><span class="sxs-lookup"><span data-stu-id="da947-158">Remarks</span></span>

<span data-ttu-id="da947-159">O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o Exchange Server com a função de servidor de acesso para Cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="da947-159">The schema that describes this element is located in the EWS virtual directory of the computer that is running Exchange Server with the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="da947-160">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="da947-160">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="da947-161">Namespace</span><span class="sxs-lookup"><span data-stu-id="da947-161">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="da947-162">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="da947-162">Schema Name</span></span>  <br/> |<span data-ttu-id="da947-163">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="da947-163">Messages schema</span></span>  <br/> |
|<span data-ttu-id="da947-164">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="da947-164">Validation File</span></span>  <br/> |<span data-ttu-id="da947-165">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="da947-165">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="da947-166">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="da947-166">Can be Empty</span></span>  <br/> |<span data-ttu-id="da947-167">False</span><span class="sxs-lookup"><span data-stu-id="da947-167">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="da947-168">Confira também</span><span class="sxs-lookup"><span data-stu-id="da947-168">See also</span></span>

- [<span data-ttu-id="da947-169">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="da947-169">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

