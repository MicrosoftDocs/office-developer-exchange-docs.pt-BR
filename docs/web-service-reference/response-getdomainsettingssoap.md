---
title: Resposta (GetDomainSettings) (SOAP)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
localization_priority: Normal
api_type:
- schema
ms.assetid: a5b052df-93bd-4fe1-ac30-83de9a3dfcd7
description: O elemento de resposta representa a resposta a uma chamada de GetDomainSettings para um domínio individual.
ms.openlocfilehash: 316d77104894cf5ed9121e7dab1c38646765c948
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19825169"
---
# <a name="response-getdomainsettings-soap"></a><span data-ttu-id="2d21c-103">Resposta (GetDomainSettings) (SOAP)</span><span class="sxs-lookup"><span data-stu-id="2d21c-103">Response (GetDomainSettings) (SOAP)</span></span>

<span data-ttu-id="2d21c-104">O elemento de **resposta** representa a resposta a uma chamada de **GetDomainSettings** para um domínio individual.</span><span class="sxs-lookup"><span data-stu-id="2d21c-104">The **Response** element represents the response to a **GetDomainSettings** call for an individual domain.</span></span> 
  
```XML
<Response>
   <DomainResponses/>
   <ErrorCode/>
   <ErrorMessage/>
</Response>
```

 <span data-ttu-id="2d21c-105">**GetDomainSettingsResponse**</span><span class="sxs-lookup"><span data-stu-id="2d21c-105">**GetDomainSettingsResponse**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="2d21c-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="2d21c-106">Attributes and elements</span></span>

<span data-ttu-id="2d21c-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="2d21c-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="2d21c-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="2d21c-108">Attributes</span></span>

<span data-ttu-id="2d21c-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="2d21c-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="2d21c-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="2d21c-110">Child elements</span></span>

|<span data-ttu-id="2d21c-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="2d21c-111">**Element**</span></span>|<span data-ttu-id="2d21c-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="2d21c-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="2d21c-113">DomainResponses (SOAP)</span><span class="sxs-lookup"><span data-stu-id="2d21c-113">DomainResponses (SOAP)</span></span>](domainresponses-soap.md) <br/> |<span data-ttu-id="2d21c-114">Contém a resposta para cada domínio solicitado em uma solicitação de **GetDomainSettings** .</span><span class="sxs-lookup"><span data-stu-id="2d21c-114">Contains the response for each domain requested in a **GetDomainSettings** request.</span></span>  <br/> |
|[<span data-ttu-id="2d21c-115">ErrorCode (SOAP)</span><span class="sxs-lookup"><span data-stu-id="2d21c-115">ErrorCode (SOAP)</span></span>](errorcode-soap.md) <br/> |<span data-ttu-id="2d21c-116">Contém o código de erro que está associado com a resposta, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="2d21c-116">Contains the error code that is associated with the response, if applicable.</span></span>  <br/> |
|[<span data-ttu-id="2d21c-117">ErrorMessage (SOAP)</span><span class="sxs-lookup"><span data-stu-id="2d21c-117">ErrorMessage (SOAP)</span></span>](errormessage-soap.md) <br/> |<span data-ttu-id="2d21c-118">Contém a mensagem de erro que está associada com a resposta, se aplicável.</span><span class="sxs-lookup"><span data-stu-id="2d21c-118">Contains the error message that is associated with the response, if applicable.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="2d21c-119">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="2d21c-119">Parent elements</span></span>

|<span data-ttu-id="2d21c-120">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="2d21c-120">**Element**</span></span>|<span data-ttu-id="2d21c-121">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="2d21c-121">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="2d21c-122">GetDomainSettingsResponseMessage (SOAP)</span><span class="sxs-lookup"><span data-stu-id="2d21c-122">GetDomainSettingsResponseMessage (SOAP)</span></span>](getdomainsettingsresponsemessage-soap.md) <br/> |<span data-ttu-id="2d21c-123">Retorna ao chamador domínio definições de configuração.</span><span class="sxs-lookup"><span data-stu-id="2d21c-123">Returns to the caller the domain configuration settings.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="2d21c-124">Text value</span><span class="sxs-lookup"><span data-stu-id="2d21c-124">Text value</span></span>

<span data-ttu-id="2d21c-125">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="2d21c-125">None.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="2d21c-126">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="2d21c-126">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="2d21c-127">Namespace</span><span class="sxs-lookup"><span data-stu-id="2d21c-127">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/2010/Autodiscover  <br/> |
|<span data-ttu-id="2d21c-128">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="2d21c-128">Schema Name</span></span>  <br/> |<span data-ttu-id="2d21c-129">Esquema de descoberta automática</span><span class="sxs-lookup"><span data-stu-id="2d21c-129">Autodiscover schema</span></span>  <br/> |
|<span data-ttu-id="2d21c-130">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="2d21c-130">Validation File</span></span>  <br/> |<span data-ttu-id="2d21c-131">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="2d21c-131">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="2d21c-132">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="2d21c-132">Can be Empty</span></span>  <br/> |<span data-ttu-id="2d21c-133">Verdadeiro</span><span class="sxs-lookup"><span data-stu-id="2d21c-133">True</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="2d21c-134">Ver também</span><span class="sxs-lookup"><span data-stu-id="2d21c-134">See also</span></span>



[<span data-ttu-id="2d21c-135">Operação de GetDomainSettings (SOAP)</span><span class="sxs-lookup"><span data-stu-id="2d21c-135">GetDomainSettings operation (SOAP)</span></span>](getdomainsettings-operation-soap.md)

