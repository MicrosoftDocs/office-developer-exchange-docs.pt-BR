---
title: ErrorCode (SOAP)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
localization_priority: Normal
api_type:
- schema
ms.assetid: 5e5ec861-0191-4ecb-a906-47ce8ed96381
description: O elemento ErrorCode representa um código de erro retornado pelo serviço de descoberta automática.
ms.openlocfilehash: 2dd91cec4645325c02bc8588af0ee0547909b945
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19752088"
---
# <a name="errorcode-soap"></a><span data-ttu-id="fcb10-103">ErrorCode (SOAP)</span><span class="sxs-lookup"><span data-stu-id="fcb10-103">ErrorCode (SOAP)</span></span>

<span data-ttu-id="fcb10-104">O elemento **ErrorCode** representa um código de erro retornado pelo serviço de descoberta automática.</span><span class="sxs-lookup"><span data-stu-id="fcb10-104">The **ErrorCode** element represents an error code that is returned by the Autodiscover service.</span></span> 
  
```XML
<ErrorCode/>
```

 <span data-ttu-id="fcb10-105">**cadeia de caracteres**</span><span class="sxs-lookup"><span data-stu-id="fcb10-105">**string**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="fcb10-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="fcb10-106">Attributes and elements</span></span>

<span data-ttu-id="fcb10-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="fcb10-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="fcb10-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="fcb10-108">Attributes</span></span>

<span data-ttu-id="fcb10-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="fcb10-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="fcb10-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="fcb10-110">Child elements</span></span>

<span data-ttu-id="fcb10-111">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="fcb10-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="fcb10-112">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="fcb10-112">Parent elements</span></span>

|<span data-ttu-id="fcb10-113">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="fcb10-113">**Element**</span></span>|<span data-ttu-id="fcb10-114">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="fcb10-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="fcb10-115">AutodiscoverResponse (SOAP)</span><span class="sxs-lookup"><span data-stu-id="fcb10-115">AutodiscoverResponse (SOAP)</span></span>](autodiscoverresponse-soap.md) <br/> |<span data-ttu-id="fcb10-116">Representa o tipo de base para todas as respostas que são retornados pelo serviço de descoberta automática.</span><span class="sxs-lookup"><span data-stu-id="fcb10-116">Represents the base type for all responses that are returned by the Autodiscover service.</span></span>  <br/> |
|[<span data-ttu-id="fcb10-117">DomainResponse (SOAP)</span><span class="sxs-lookup"><span data-stu-id="fcb10-117">DomainResponse (SOAP)</span></span>](domainresponse-soap.md) <br/> |<span data-ttu-id="fcb10-118">Contém as configurações solicitadas para o domínio especificado.</span><span class="sxs-lookup"><span data-stu-id="fcb10-118">Contains the requested settings for the specified domain.</span></span>  <br/> |
|[<span data-ttu-id="fcb10-119">GetDomainSettingsResponse (SOAP)</span><span class="sxs-lookup"><span data-stu-id="fcb10-119">GetDomainSettingsResponse (SOAP)</span></span>](getdomainsettingsresponse-soap.md) <br/> |<span data-ttu-id="fcb10-120">Contém a resposta a uma chamada de [operação GetDomainSettings (SOAP)](getdomainsettings-operation-soap.md) para um domínio individual.</span><span class="sxs-lookup"><span data-stu-id="fcb10-120">Contains the response to a [GetDomainSettings operation (SOAP)](getdomainsettings-operation-soap.md) call for an individual domain.</span></span>  <br/> |
|[<span data-ttu-id="fcb10-121">GetFederationInformationResponse (SOAP)</span><span class="sxs-lookup"><span data-stu-id="fcb10-121">GetFederationInformationResponse (SOAP)</span></span>](getfederationinformationresponse-soap.md) <br/> |<span data-ttu-id="fcb10-122">Contém a resposta a uma solicitação de [operação GetFederationInformation (SOAP)](getfederationinformation-operation-soap.md) .</span><span class="sxs-lookup"><span data-stu-id="fcb10-122">Contains the response to a [GetFederationInformation operation (SOAP)](getfederationinformation-operation-soap.md) request.</span></span>  <br/> |
|[<span data-ttu-id="fcb10-123">Resposta SOAP)</span><span class="sxs-lookup"><span data-stu-id="fcb10-123">Response (SOAP)</span></span>](response-soap.md) <br/> |<span data-ttu-id="fcb10-124">Contém a resposta a uma solicitação de [operação GetUserSettings (SOAP)](getusersettings-operation-soap.md).</span><span class="sxs-lookup"><span data-stu-id="fcb10-124">Contains the response to a [GetUserSettings operation (SOAP)](getusersettings-operation-soap.md)request.</span></span>  <br/> |
|[<span data-ttu-id="fcb10-125">UserSettingError (SOAP)</span><span class="sxs-lookup"><span data-stu-id="fcb10-125">UserSettingError (SOAP)</span></span>](usersettingerror-soap.md) <br/> |<span data-ttu-id="fcb10-126">Representa um erro retornado ao recuperar uma configuração de usuário.</span><span class="sxs-lookup"><span data-stu-id="fcb10-126">Represents an error that is returned while retrieving a user setting.</span></span>  <br/> |
|[<span data-ttu-id="fcb10-127">Resposta SOAP)</span><span class="sxs-lookup"><span data-stu-id="fcb10-127">UserResponse (SOAP)</span></span>](userresponse-soap.md) <br/> |<span data-ttu-id="fcb10-128">Representa uma resposta a uma solicitação de [operação GetUserSettings (SOAP)](getusersettings-operation-soap.md) para um usuário individual.</span><span class="sxs-lookup"><span data-stu-id="fcb10-128">Represents a response to a [GetUserSettings operation (SOAP)](getusersettings-operation-soap.md) request for an individual user.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="fcb10-129">Text value</span><span class="sxs-lookup"><span data-stu-id="fcb10-129">Text value</span></span>

<span data-ttu-id="fcb10-130">O valor de texto representa o código de erro para uma resposta de erro de descoberta automática.</span><span class="sxs-lookup"><span data-stu-id="fcb10-130">The text value represents the error code for an Autodiscover error response.</span></span> <span data-ttu-id="fcb10-131">A tabela a seguir lista os valores de texto possíveis para o elemento **ErrorCode** .</span><span class="sxs-lookup"><span data-stu-id="fcb10-131">The following table lists the possible text values for the **ErrorCode** element.</span></span> 
  
|<span data-ttu-id="fcb10-132">**Valor de texto de código de erro**</span><span class="sxs-lookup"><span data-stu-id="fcb10-132">**Error code text value**</span></span>|<span data-ttu-id="fcb10-133">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="fcb10-133">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="fcb10-134">NoError</span><span class="sxs-lookup"><span data-stu-id="fcb10-134">NoError</span></span>  <br/> |<span data-ttu-id="fcb10-135">Não houve nenhum erro.</span><span class="sxs-lookup"><span data-stu-id="fcb10-135">There was no error.</span></span>  <br/> |
|<span data-ttu-id="fcb10-136">RedirectAddress</span><span class="sxs-lookup"><span data-stu-id="fcb10-136">RedirectAddress</span></span>  <br/> |<span data-ttu-id="fcb10-137">O chamador deve seguir o redirecionamento de endereço de email que foi retornado por descoberta automática.</span><span class="sxs-lookup"><span data-stu-id="fcb10-137">The caller must follow the e-mail address redirection that was returned by Autodiscover.</span></span>  <br/> |
|<span data-ttu-id="fcb10-138">RedirectUrl</span><span class="sxs-lookup"><span data-stu-id="fcb10-138">RedirectUrl</span></span>  <br/> |<span data-ttu-id="fcb10-139">O chamador deve seguir o redirecionamento de URL que foi retornado por descoberta automática.</span><span class="sxs-lookup"><span data-stu-id="fcb10-139">The caller must follow the URL redirection that was returned by Autodiscover.</span></span>  <br/> |
|<span data-ttu-id="fcb10-140">InvalidUser</span><span class="sxs-lookup"><span data-stu-id="fcb10-140">InvalidUser</span></span>  <br/> |<span data-ttu-id="fcb10-141">O usuário que foi passado na solicitação é inválido.</span><span class="sxs-lookup"><span data-stu-id="fcb10-141">The user that was passed in the request is invalid.</span></span>  <br/> |
|<span data-ttu-id="fcb10-142">InvalidRequest</span><span class="sxs-lookup"><span data-stu-id="fcb10-142">InvalidRequest</span></span>  <br/> |<span data-ttu-id="fcb10-143">A solicitação é inválida.</span><span class="sxs-lookup"><span data-stu-id="fcb10-143">The request is invalid.</span></span>  <br/> |
|<span data-ttu-id="fcb10-144">InvalidSetting</span><span class="sxs-lookup"><span data-stu-id="fcb10-144">InvalidSetting</span></span>  <br/> |<span data-ttu-id="fcb10-145">Uma configuração especificada é inválida.</span><span class="sxs-lookup"><span data-stu-id="fcb10-145">A specified setting is invalid.</span></span>  <br/> |
|<span data-ttu-id="fcb10-146">SettingIsNotAvailable</span><span class="sxs-lookup"><span data-stu-id="fcb10-146">SettingIsNotAvailable</span></span>  <br/> |<span data-ttu-id="fcb10-147">Uma configuração especificada não está disponível.</span><span class="sxs-lookup"><span data-stu-id="fcb10-147">A specified setting is not available.</span></span>  <br/> |
|<span data-ttu-id="fcb10-148">ServerBusy</span><span class="sxs-lookup"><span data-stu-id="fcb10-148">ServerBusy</span></span>  <br/> |<span data-ttu-id="fcb10-149">O servidor está muito ocupado para processar a solicitação.</span><span class="sxs-lookup"><span data-stu-id="fcb10-149">The server is too busy to process the request.</span></span>  <br/> |
|<span data-ttu-id="fcb10-150">InvalidDomain</span><span class="sxs-lookup"><span data-stu-id="fcb10-150">InvalidDomain</span></span>  <br/> |<span data-ttu-id="fcb10-151">O domínio solicitado não é válido.</span><span class="sxs-lookup"><span data-stu-id="fcb10-151">The requested domain is not valid.</span></span>  <br/> |
|<span data-ttu-id="fcb10-152">NotFederated</span><span class="sxs-lookup"><span data-stu-id="fcb10-152">NotFederated</span></span>  <br/> |<span data-ttu-id="fcb10-153">A organização não é federada.</span><span class="sxs-lookup"><span data-stu-id="fcb10-153">The organization is not federated.</span></span>  <br/> |
|<span data-ttu-id="fcb10-154">InternalServerError</span><span class="sxs-lookup"><span data-stu-id="fcb10-154">InternalServerError</span></span>  <br/> |<span data-ttu-id="fcb10-155">Não há um erro interno do servidor.</span><span class="sxs-lookup"><span data-stu-id="fcb10-155">There is an internal server error.</span></span>  <br/> |
   
## <a name="element-information"></a><span data-ttu-id="fcb10-156">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="fcb10-156">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="fcb10-157">Namespace</span><span class="sxs-lookup"><span data-stu-id="fcb10-157">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/2010/Autodiscover  <br/> |
|<span data-ttu-id="fcb10-158">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="fcb10-158">Schema Name</span></span>  <br/> |<span data-ttu-id="fcb10-159">Esquema de descoberta automática</span><span class="sxs-lookup"><span data-stu-id="fcb10-159">Autodiscover schema</span></span>  <br/> |
|<span data-ttu-id="fcb10-160">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="fcb10-160">Validation File</span></span>  <br/> |<span data-ttu-id="fcb10-161">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="fcb10-161">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="fcb10-162">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="fcb10-162">Can be Empty</span></span>  <br/> |<span data-ttu-id="fcb10-163">Verdadeiro</span><span class="sxs-lookup"><span data-stu-id="fcb10-163">True</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="fcb10-164">Ver também</span><span class="sxs-lookup"><span data-stu-id="fcb10-164">See also</span></span>



[<span data-ttu-id="fcb10-165">Operação de GetUserSettings (SOAP)</span><span class="sxs-lookup"><span data-stu-id="fcb10-165">GetUserSettings operation (SOAP)</span></span>](getusersettings-operation-soap.md)
  
[<span data-ttu-id="fcb10-166">Operação de GetDomainSettings (SOAP)</span><span class="sxs-lookup"><span data-stu-id="fcb10-166">GetDomainSettings operation (SOAP)</span></span>](getdomainsettings-operation-soap.md)
  
[<span data-ttu-id="fcb10-167">Operação de GetFederationInformation (SOAP)</span><span class="sxs-lookup"><span data-stu-id="fcb10-167">GetFederationInformation operation (SOAP)</span></span>](getfederationinformation-operation-soap.md)

