---
title: ServiceConfigurationResponseMessageType
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- ServiceConfigurationResponseMessageType
api_type:
- schema
ms.assetid: ccfb0578-c648-44c2-ac4d-7620d881363e
description: O elemento ServiceConfigurationResponseMessageType contém definições de configuração do serviço.
ms.openlocfilehash: fb7841f346083017319cece4479fea8bbfb6de17
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19825393"
---
# <a name="serviceconfigurationresponsemessagetype"></a><span data-ttu-id="31a5d-103">ServiceConfigurationResponseMessageType</span><span class="sxs-lookup"><span data-stu-id="31a5d-103">ServiceConfigurationResponseMessageType</span></span>

<span data-ttu-id="31a5d-104">O elemento **ServiceConfigurationResponseMessageType** contém definições de configuração do serviço.</span><span class="sxs-lookup"><span data-stu-id="31a5d-104">The **ServiceConfigurationResponseMessageType** element contains service configuration settings.</span></span> 
  
```XML
<ServiceConfigurationResponseMessageType ResponseClass="">
   <MessageText/>
   <ResponseCode/>
   <DescriptiveLinkKey/>
   <MessageXml/>
   <MailTipsConfiguration/>
   <UnifiedMessagingConfiguration/>
   <ProtectionRulesConfiguration/>
</ServiceConfigurationResponseMessageType>
```

 <span data-ttu-id="31a5d-105">**ServiceConfigurationResponseMessageType**</span><span class="sxs-lookup"><span data-stu-id="31a5d-105">**ServiceConfigurationResponseMessageType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="31a5d-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="31a5d-106">Attributes and elements</span></span>

<span data-ttu-id="31a5d-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="31a5d-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="31a5d-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="31a5d-108">Attributes</span></span>

|<span data-ttu-id="31a5d-109">**Attribute**</span><span class="sxs-lookup"><span data-stu-id="31a5d-109">**Attribute**</span></span>|<span data-ttu-id="31a5d-110">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="31a5d-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="31a5d-111">**ResponseClass**</span><span class="sxs-lookup"><span data-stu-id="31a5d-111">**ResponseClass**</span></span> <br/> | <span data-ttu-id="31a5d-112">Descreve o status da resposta.</span><span class="sxs-lookup"><span data-stu-id="31a5d-112">Describes the status of the response.</span></span><br/><br/> <span data-ttu-id="31a5d-113">Os seguintes valores são válidos para este atributo:</span><span class="sxs-lookup"><span data-stu-id="31a5d-113">The following values are valid for this attribute:</span></span>  <br/><br/><span data-ttu-id="31a5d-114">-Êxito</span><span class="sxs-lookup"><span data-stu-id="31a5d-114">-  Success</span></span>  <br/><span data-ttu-id="31a5d-115">-Aviso</span><span class="sxs-lookup"><span data-stu-id="31a5d-115">-  Warning</span></span>  <br/><span data-ttu-id="31a5d-116">-Erro</span><span class="sxs-lookup"><span data-stu-id="31a5d-116">-  Error</span></span>  <br/> |
   
#### <a name="responseclass-attribute-values"></a><span data-ttu-id="31a5d-117">Valores de atributo ResponseClass</span><span class="sxs-lookup"><span data-stu-id="31a5d-117">ResponseClass attribute values</span></span>

|<span data-ttu-id="31a5d-118">**Valor**</span><span class="sxs-lookup"><span data-stu-id="31a5d-118">**Value**</span></span>|<span data-ttu-id="31a5d-119">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="31a5d-119">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="31a5d-120">**Sucesso**</span><span class="sxs-lookup"><span data-stu-id="31a5d-120">**Success**</span></span> <br/> |<span data-ttu-id="31a5d-121">Descreve uma solicitação que seja cumprida.</span><span class="sxs-lookup"><span data-stu-id="31a5d-121">Describes a request that is fulfilled.</span></span>  <br/> |
|<span data-ttu-id="31a5d-122">**Warning**</span><span class="sxs-lookup"><span data-stu-id="31a5d-122">**Warning**</span></span> <br/> | <span data-ttu-id="31a5d-123">Descreve uma solicitação que não foi processada.</span><span class="sxs-lookup"><span data-stu-id="31a5d-123">Describes a request that was not processed.</span></span> <span data-ttu-id="31a5d-124">Um aviso pode ser retornado se ocorreu um erro quando um item na solicitação estava processando e itens subsequentes não pôde ser processados.</span><span class="sxs-lookup"><span data-stu-id="31a5d-124">A warning may be returned if an error occurred while an item in the request was processing and subsequent items could not be processed.</span></span> <br/><br/><span data-ttu-id="31a5d-125">Estes são exemplos de fontes de avisos de:</span><span class="sxs-lookup"><span data-stu-id="31a5d-125">The following are examples of sources of warnings:</span></span>  <br/><br/><span data-ttu-id="31a5d-126">-O armazenamento do Exchange está offline durante o lote.</span><span class="sxs-lookup"><span data-stu-id="31a5d-126">-  The Exchange store is offline during the batch.</span></span>  <br/><span data-ttu-id="31a5d-127">-Active Directory Domain Services (AD DS) está offline.</span><span class="sxs-lookup"><span data-stu-id="31a5d-127">-  Active Directory Domain Services (AD DS) is offline.</span></span>  <br/><span data-ttu-id="31a5d-128">-Caixas de correio foram movidos.</span><span class="sxs-lookup"><span data-stu-id="31a5d-128">-  Mailboxes were moved.</span></span>  <br/><span data-ttu-id="31a5d-129">-O banco de dados de mensagens (MDB) está offline.</span><span class="sxs-lookup"><span data-stu-id="31a5d-129">-  The message database (MDB) is offline.</span></span>  <br/><span data-ttu-id="31a5d-130">-Uma senha expirou.</span><span class="sxs-lookup"><span data-stu-id="31a5d-130">-  A password is expired.</span></span>  <br/><span data-ttu-id="31a5d-131">-Uma cota foi excedida.</span><span class="sxs-lookup"><span data-stu-id="31a5d-131">-  A quota has been exceeded.</span></span>  <br/> |
|<span data-ttu-id="31a5d-132">**Erro**</span><span class="sxs-lookup"><span data-stu-id="31a5d-132">**Error**</span></span> <br/> | <span data-ttu-id="31a5d-133">Descreve uma solicitação que não puder ser atendida.</span><span class="sxs-lookup"><span data-stu-id="31a5d-133">Describes a request that cannot be fulfilled.</span></span> <br/><br/><span data-ttu-id="31a5d-134">Estes são exemplos de fontes de erros:</span><span class="sxs-lookup"><span data-stu-id="31a5d-134">The following are examples of sources of errors:</span></span>  <br/><br/><span data-ttu-id="31a5d-135">-Inválido atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="31a5d-135">-  Invalid attributes or elements</span></span>  <br/><span data-ttu-id="31a5d-136">-Atributos ou elementos que estão fora do intervalo</span><span class="sxs-lookup"><span data-stu-id="31a5d-136">-  Attributes or elements that are out of range</span></span>  <br/><span data-ttu-id="31a5d-137">-Uma marca desconhecida</span><span class="sxs-lookup"><span data-stu-id="31a5d-137">-  An unknown tag</span></span>  <br/><span data-ttu-id="31a5d-138">-Um atributo ou elemento não é válido no contexto</span><span class="sxs-lookup"><span data-stu-id="31a5d-138">-  An attribute or element is not valid in the context</span></span>  <br/><span data-ttu-id="31a5d-139">-Uma tentativa de acesso não autorizado por qualquer cliente</span><span class="sxs-lookup"><span data-stu-id="31a5d-139">-  An unauthorized access attempt by any client</span></span>  <br/><span data-ttu-id="31a5d-140">-Uma falha no servidor em resposta a uma chamada de cliente válida</span><span class="sxs-lookup"><span data-stu-id="31a5d-140">-  A server-side failure in response to a valid client-side call</span></span>  <br/><br/>  <span data-ttu-id="31a5d-141">Informações sobre o erro podem ser encontradas nos elementos [ResponseCode](responsecode.md) e [MessageText](messagetext.md) .</span><span class="sxs-lookup"><span data-stu-id="31a5d-141">Information about the error can be found in the [ResponseCode](responsecode.md) and [MessageText](messagetext.md) elements.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="31a5d-142">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="31a5d-142">Child elements</span></span>

|<span data-ttu-id="31a5d-143">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="31a5d-143">**Element**</span></span>|<span data-ttu-id="31a5d-144">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="31a5d-144">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="31a5d-145">MessageText</span><span class="sxs-lookup"><span data-stu-id="31a5d-145">MessageText</span></span>](messagetext.md) <br/> |<span data-ttu-id="31a5d-146">Fornece uma descrição de texto do status da resposta.</span><span class="sxs-lookup"><span data-stu-id="31a5d-146">Provides a text description of the status of the response.</span></span>  <br/> |
|[<span data-ttu-id="31a5d-147">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="31a5d-147">ResponseCode</span></span>](responsecode.md) <br/> |<span data-ttu-id="31a5d-148">Fornece um código de erro que identifica o erro específico que enfrentaram a solicitação.</span><span class="sxs-lookup"><span data-stu-id="31a5d-148">Provides an error code that identifies the specific error that the request encountered.</span></span>  <br/> |
|[<span data-ttu-id="31a5d-149">DescriptiveLinkKey</span><span class="sxs-lookup"><span data-stu-id="31a5d-149">DescriptiveLinkKey</span></span>](descriptivelinkkey.md) <br/> |<span data-ttu-id="31a5d-150">No momento não utilizados e reservada para uso futuro.</span><span class="sxs-lookup"><span data-stu-id="31a5d-150">Currently unused and reserved for future use.</span></span> <span data-ttu-id="31a5d-151">Esse elemento contém um valor de 0.</span><span class="sxs-lookup"><span data-stu-id="31a5d-151">This element contains a value of 0.</span></span>  <br/> |
|[<span data-ttu-id="31a5d-152">MessageXml</span><span class="sxs-lookup"><span data-stu-id="31a5d-152">MessageXml</span></span>](messagexml.md) <br/> |<span data-ttu-id="31a5d-153">Fornece informações de resposta de erro adicionais.</span><span class="sxs-lookup"><span data-stu-id="31a5d-153">Provides additional error response information.</span></span>  <br/> |
|[<span data-ttu-id="31a5d-154">MailTipsConfiguration (MailTipsServiceConfiguration)</span><span class="sxs-lookup"><span data-stu-id="31a5d-154">MailTipsConfiguration (MailTipsServiceConfiguration)</span></span>](mailtipsconfiguration-mailtipsserviceconfiguration.md) <br/> |<span data-ttu-id="31a5d-155">Contém informações de configuração de serviço para o serviço de dicas de email.</span><span class="sxs-lookup"><span data-stu-id="31a5d-155">Contains service configuration information for the mail tips service.</span></span>  <br/> |
|[<span data-ttu-id="31a5d-156">UnifiedMessagingConfiguration</span><span class="sxs-lookup"><span data-stu-id="31a5d-156">UnifiedMessagingConfiguration</span></span>](unifiedmessagingconfiguration.md) <br/> |<span data-ttu-id="31a5d-157">Contém informações de configuração de serviço para o serviço de Unificação de mensagens.</span><span class="sxs-lookup"><span data-stu-id="31a5d-157">Contains service configuration information for the Unified Messaging service.</span></span>  <br/> |
|[<span data-ttu-id="31a5d-158">ProtectionRulesConfiguration</span><span class="sxs-lookup"><span data-stu-id="31a5d-158">ProtectionRulesConfiguration</span></span>](protectionrulesconfiguration.md) <br/> |<span data-ttu-id="31a5d-159">Contém informações de configuração de serviço para o serviço de regras de proteção.</span><span class="sxs-lookup"><span data-stu-id="31a5d-159">Contains service configuration information for the protection rules service.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="31a5d-160">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="31a5d-160">Parent elements</span></span>

|<span data-ttu-id="31a5d-161">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="31a5d-161">**Element**</span></span>|<span data-ttu-id="31a5d-162">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="31a5d-162">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="31a5d-163">ResponseMessages (ArrayOfServiceConfigurationResponseMessageType)</span><span class="sxs-lookup"><span data-stu-id="31a5d-163">ResponseMessages (ArrayOfServiceConfigurationResponseMessageType)</span></span>](responsemessages-arrayofserviceconfigurationresponsemessagetype.md) <br/> |<span data-ttu-id="31a5d-164">Contém uma matriz das mensagens de resposta de configuração do serviço.</span><span class="sxs-lookup"><span data-stu-id="31a5d-164">Contains an array of service configuration response messages.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="31a5d-165">Text value</span><span class="sxs-lookup"><span data-stu-id="31a5d-165">Text value</span></span>

<span data-ttu-id="31a5d-166">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="31a5d-166">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="31a5d-167">Comentários</span><span class="sxs-lookup"><span data-stu-id="31a5d-167">Remarks</span></span>

<span data-ttu-id="31a5d-168">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="31a5d-168">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="31a5d-169">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="31a5d-169">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="31a5d-170">Namespace</span><span class="sxs-lookup"><span data-stu-id="31a5d-170">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="31a5d-171">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="31a5d-171">Schema Name</span></span>  <br/> |<span data-ttu-id="31a5d-172">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="31a5d-172">Messages schema</span></span>  <br/> |
|<span data-ttu-id="31a5d-173">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="31a5d-173">Validation File</span></span>  <br/> |<span data-ttu-id="31a5d-174">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="31a5d-174">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="31a5d-175">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="31a5d-175">Can be Empty</span></span>  <br/> |<span data-ttu-id="31a5d-176">False</span><span class="sxs-lookup"><span data-stu-id="31a5d-176">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="31a5d-177">Ver também</span><span class="sxs-lookup"><span data-stu-id="31a5d-177">See also</span></span>

- [<span data-ttu-id="31a5d-178">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="31a5d-178">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

