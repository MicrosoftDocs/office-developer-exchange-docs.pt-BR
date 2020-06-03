---
title: CreateUserConfigurationResponseMessage
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- CreateUserConfigurationResponseMessage
api_type:
- schema
ms.assetid: 9c11427c-74c9-4c6a-a0e7-7d5556670c1e
description: O elemento CreateUserConfigurationResponseMessage contém o status e o resultado de uma única solicitação de CreateUserConfiguration.
ms.openlocfilehash: 3217734f7451ad397c531cd9ff9ce7d44b13f6ba
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44463731"
---
# <a name="createuserconfigurationresponsemessage"></a><span data-ttu-id="d99ef-103">CreateUserConfigurationResponseMessage</span><span class="sxs-lookup"><span data-stu-id="d99ef-103">CreateUserConfigurationResponseMessage</span></span>

<span data-ttu-id="d99ef-104">O elemento **CreateUserConfigurationResponseMessage** contém o status e o resultado de uma única solicitação de **CreateUserConfiguration** .</span><span class="sxs-lookup"><span data-stu-id="d99ef-104">The **CreateUserConfigurationResponseMessage** element contains the status and result of a single **CreateUserConfiguration** request.</span></span> 
  
```xml
<CreateUserConfigurationResponseMessage ResponseClass="">
   <MessageText/>
   <ResponseCode/>
   <DescriptiveLinkKey/>
   <MessageXml/>
</CreateUserConfigurationResponseMessage>
```

<span data-ttu-id="d99ef-105">**ResponseMessageType**</span><span class="sxs-lookup"><span data-stu-id="d99ef-105">**ResponseMessageType**</span></span>

## <a name="attributes-and-elements"></a><span data-ttu-id="d99ef-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="d99ef-106">Attributes and elements</span></span>

<span data-ttu-id="d99ef-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="d99ef-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="d99ef-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="d99ef-108">Attributes</span></span>

|<span data-ttu-id="d99ef-109">**Atributo**</span><span class="sxs-lookup"><span data-stu-id="d99ef-109">**Attribute**</span></span>|<span data-ttu-id="d99ef-110">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="d99ef-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="d99ef-111">**ResponseClass**</span><span class="sxs-lookup"><span data-stu-id="d99ef-111">**ResponseClass**</span></span> <br/> | <span data-ttu-id="d99ef-112">Descreve o status da resposta.</span><span class="sxs-lookup"><span data-stu-id="d99ef-112">Describes the status of the response.</span></span><br/><br/><span data-ttu-id="d99ef-113">Os seguintes valores são válidos para este atributo:</span><span class="sxs-lookup"><span data-stu-id="d99ef-113">The following values are valid for this attribute:</span></span>  <br/><br/><span data-ttu-id="d99ef-114">-Êxito</span><span class="sxs-lookup"><span data-stu-id="d99ef-114">-  Success</span></span>  <br/><span data-ttu-id="d99ef-115">-Aviso</span><span class="sxs-lookup"><span data-stu-id="d99ef-115">-  Warning</span></span>  <br/><span data-ttu-id="d99ef-116">-Erro</span><span class="sxs-lookup"><span data-stu-id="d99ef-116">-  Error</span></span>  <br/> |
   
#### <a name="responseclass-attribute-values"></a><span data-ttu-id="d99ef-117">Valores de atributo ResponseClass</span><span class="sxs-lookup"><span data-stu-id="d99ef-117">ResponseClass attribute values</span></span>

|<span data-ttu-id="d99ef-118">**Valor**</span><span class="sxs-lookup"><span data-stu-id="d99ef-118">**Value**</span></span>|<span data-ttu-id="d99ef-119">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="d99ef-119">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="d99ef-120">**Success**</span><span class="sxs-lookup"><span data-stu-id="d99ef-120">**Success**</span></span> <br/> |<span data-ttu-id="d99ef-121">Descreve uma solicitação que é atendida.</span><span class="sxs-lookup"><span data-stu-id="d99ef-121">Describes a request that is fulfilled.</span></span>  <br/> |
|<span data-ttu-id="d99ef-122">**Aviso**</span><span class="sxs-lookup"><span data-stu-id="d99ef-122">**Warning**</span></span> <br/> | <span data-ttu-id="d99ef-123">Descreve uma solicitação que não foi processada.</span><span class="sxs-lookup"><span data-stu-id="d99ef-123">Describes a request that was not processed.</span></span> <span data-ttu-id="d99ef-124">Um aviso pode ser retornado se um erro ocorreu enquanto um item na solicitação estava sendo processado e não foi possível processar os itens subsequentes.</span><span class="sxs-lookup"><span data-stu-id="d99ef-124">A warning may be returned if an error occurred while an item in the request was processing and subsequent items could not be processed.</span></span><br/><br/> <span data-ttu-id="d99ef-125">A seguir estão exemplos de fontes de avisos:</span><span class="sxs-lookup"><span data-stu-id="d99ef-125">The following are examples of sources of warnings:</span></span>  <br/><br/><span data-ttu-id="d99ef-126">– O repositório do Exchange está offline durante o lote.</span><span class="sxs-lookup"><span data-stu-id="d99ef-126">-  The Exchange store is offline during the batch.</span></span>  <br/><span data-ttu-id="d99ef-127">– Os serviços de domínio do Active Directory (AD DS) estão offline.</span><span class="sxs-lookup"><span data-stu-id="d99ef-127">-  Active Directory Domain Services (AD DS) is offline.</span></span>  <br/><span data-ttu-id="d99ef-128">-As caixas de correio foram movidas.</span><span class="sxs-lookup"><span data-stu-id="d99ef-128">-  Mailboxes were moved.</span></span>  <br/><span data-ttu-id="d99ef-129">– O banco de dados de mensagens (MDB) está offline.</span><span class="sxs-lookup"><span data-stu-id="d99ef-129">-  The message database (MDB) is offline.</span></span>  <br/><span data-ttu-id="d99ef-130">-Uma senha expirou.</span><span class="sxs-lookup"><span data-stu-id="d99ef-130">-  A password is expired.</span></span>  <br/><span data-ttu-id="d99ef-131">-Uma cota foi excedida.</span><span class="sxs-lookup"><span data-stu-id="d99ef-131">-  A quota has been exceeded.</span></span>  <br/> |
|<span data-ttu-id="d99ef-132">**Error**</span><span class="sxs-lookup"><span data-stu-id="d99ef-132">**Error**</span></span> <br/> | <span data-ttu-id="d99ef-133">Descreve uma solicitação que não pode ser atendida.</span><span class="sxs-lookup"><span data-stu-id="d99ef-133">Describes a request that cannot be fulfilled.</span></span><br/><br/> <span data-ttu-id="d99ef-134">A seguir estão exemplos de fontes de erros:</span><span class="sxs-lookup"><span data-stu-id="d99ef-134">The following are examples of sources of errors:</span></span>  <br/><br/><span data-ttu-id="d99ef-135">-Atributos ou elementos inválidos.</span><span class="sxs-lookup"><span data-stu-id="d99ef-135">-  Invalid attributes or elements.</span></span>  <br/><span data-ttu-id="d99ef-136">-Atributos ou elementos que estão fora do intervalo.</span><span class="sxs-lookup"><span data-stu-id="d99ef-136">-  Attributes or elements that are out of range.</span></span>  <br/><span data-ttu-id="d99ef-137">-Uma marca desconhecida.</span><span class="sxs-lookup"><span data-stu-id="d99ef-137">-  An unknown tag.</span></span>  <br/><span data-ttu-id="d99ef-138">-O atributo ou elemento não é válido no contexto.</span><span class="sxs-lookup"><span data-stu-id="d99ef-138">-  The attribute or element is not valid in the context.</span></span>  <br/><span data-ttu-id="d99ef-139">– Uma tentativa de acesso não autorizado por qualquer cliente.</span><span class="sxs-lookup"><span data-stu-id="d99ef-139">-  An unauthorized access attempt by any client.</span></span>  <br/><span data-ttu-id="d99ef-140">-Uma falha do servidor em resposta a uma chamada válida do lado do cliente.</span><span class="sxs-lookup"><span data-stu-id="d99ef-140">-  A server-side failure in response to a valid client-side call.</span></span><br/><br/>  <span data-ttu-id="d99ef-141">As informações sobre o erro podem ser encontradas nos elementos [ResponseCode](responsecode.md) e [MessageText](messagetext.md) .</span><span class="sxs-lookup"><span data-stu-id="d99ef-141">Information about the error can be found in the [ResponseCode](responsecode.md) and [MessageText](messagetext.md) elements.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="d99ef-142">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="d99ef-142">Child elements</span></span>

|<span data-ttu-id="d99ef-143">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="d99ef-143">**Element**</span></span>|<span data-ttu-id="d99ef-144">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="d99ef-144">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="d99ef-145">MessageText</span><span class="sxs-lookup"><span data-stu-id="d99ef-145">MessageText</span></span>](messagetext.md) <br/> |<span data-ttu-id="d99ef-146">Fornece uma descrição de texto do status da resposta.</span><span class="sxs-lookup"><span data-stu-id="d99ef-146">Provides a text description of the status of the response.</span></span>  <br/> |
|[<span data-ttu-id="d99ef-147">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="d99ef-147">ResponseCode</span></span>](responsecode.md) <br/> |<span data-ttu-id="d99ef-148">Fornece um código de erro que identifica o erro específico que a solicitação encontrou.</span><span class="sxs-lookup"><span data-stu-id="d99ef-148">Provides an error code that identifies the specific error that the request encountered.</span></span>  <br/> |
|[<span data-ttu-id="d99ef-149">DescriptiveLinkKey</span><span class="sxs-lookup"><span data-stu-id="d99ef-149">DescriptiveLinkKey</span></span>](descriptivelinkkey.md) <br/> |<span data-ttu-id="d99ef-150">Atualmente não usado e reservado para uso futuro.</span><span class="sxs-lookup"><span data-stu-id="d99ef-150">Currently unused and reserved for future use.</span></span> <span data-ttu-id="d99ef-151">Este elemento contém um valor de 0.</span><span class="sxs-lookup"><span data-stu-id="d99ef-151">This element contains a value of 0.</span></span>  <br/> |
|[<span data-ttu-id="d99ef-152">MessageXml</span><span class="sxs-lookup"><span data-stu-id="d99ef-152">MessageXml</span></span>](messagexml.md) <br/> |<span data-ttu-id="d99ef-153">Fornece informações adicionais de resposta de erro.</span><span class="sxs-lookup"><span data-stu-id="d99ef-153">Provides additional error response information.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="d99ef-154">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="d99ef-154">Parent elements</span></span>

|<span data-ttu-id="d99ef-155">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="d99ef-155">**Element**</span></span>|<span data-ttu-id="d99ef-156">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="d99ef-156">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="d99ef-157">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="d99ef-157">ResponseMessages</span></span>](responsemessages.md) <br/> |<span data-ttu-id="d99ef-158">Contém as mensagens de resposta para uma solicitação de serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="d99ef-158">Contains the response messages for an Exchange Web Services request.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="d99ef-159">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="d99ef-159">Text value</span></span>

<span data-ttu-id="d99ef-160">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="d99ef-160">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="d99ef-161">Comentários</span><span class="sxs-lookup"><span data-stu-id="d99ef-161">Remarks</span></span>

<span data-ttu-id="d99ef-162">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="d99ef-162">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="d99ef-163">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="d99ef-163">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="d99ef-164">Namespace</span><span class="sxs-lookup"><span data-stu-id="d99ef-164">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="d99ef-165">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="d99ef-165">Schema Name</span></span>  <br/> |<span data-ttu-id="d99ef-166">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="d99ef-166">Messages schema</span></span>  <br/> |
|<span data-ttu-id="d99ef-167">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="d99ef-167">Validation File</span></span>  <br/> |<span data-ttu-id="d99ef-168">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="d99ef-168">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="d99ef-169">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="d99ef-169">Can be Empty</span></span>  <br/> |<span data-ttu-id="d99ef-170">False</span><span class="sxs-lookup"><span data-stu-id="d99ef-170">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="d99ef-171">Confira também</span><span class="sxs-lookup"><span data-stu-id="d99ef-171">See also</span></span>

- [<span data-ttu-id="d99ef-172">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="d99ef-172">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

