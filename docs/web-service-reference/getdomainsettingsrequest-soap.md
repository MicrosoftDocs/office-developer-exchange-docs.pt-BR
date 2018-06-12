---
title: GetDomainSettingsRequest (SOAP)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
localization_priority: Normal
api_type:
- schema
ms.assetid: 5ac0ff6d-9e02-4e4c-973d-cd9e076661d5
description: O elemento GetDomainSettingsRequest representa uma solicitação de operação GetDomainSettings operação (SOAP).
ms.openlocfilehash: 4de525a9ba47a0d9afb0d6db9200fe32845f31d0
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19752465"
---
# <a name="getdomainsettingsrequest-soap"></a><span data-ttu-id="c47c9-103">GetDomainSettingsRequest (SOAP)</span><span class="sxs-lookup"><span data-stu-id="c47c9-103">GetDomainSettingsRequest (SOAP)</span></span>

<span data-ttu-id="c47c9-104">O elemento **GetDomainSettingsRequest** representa uma solicitação de operação de [operação GetDomainSettings (SOAP)](getdomainsettings-operation-soap.md) .</span><span class="sxs-lookup"><span data-stu-id="c47c9-104">The **GetDomainSettingsRequest** element represents a [GetDomainSettings operation (SOAP)](getdomainsettings-operation-soap.md) operation request.</span></span> 
  
```XML
<GetDomainSettingsRequest>
   <Domains/>
   <RequestedSettings/>
   <RequestedVersion/>
</GetDomainSettingsRequest>
```

 <span data-ttu-id="c47c9-105">**GetDomainSettingsRequest**</span><span class="sxs-lookup"><span data-stu-id="c47c9-105">**GetDomainSettingsRequest**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="c47c9-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="c47c9-106">Attributes and elements</span></span>

<span data-ttu-id="c47c9-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="c47c9-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="c47c9-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="c47c9-108">Attributes</span></span>

<span data-ttu-id="c47c9-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="c47c9-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="c47c9-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="c47c9-110">Child elements</span></span>

|<span data-ttu-id="c47c9-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="c47c9-111">**Element**</span></span>|<span data-ttu-id="c47c9-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="c47c9-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="c47c9-113">Domínios (SOAP)</span><span class="sxs-lookup"><span data-stu-id="c47c9-113">Domains (SOAP)</span></span>](domains-soap.md) <br/> |<span data-ttu-id="c47c9-114">Representa uma coleção dos identificadores de domínio.</span><span class="sxs-lookup"><span data-stu-id="c47c9-114">Represents a collection of domain identifiers.</span></span>  <br/> |
|[<span data-ttu-id="c47c9-115">RequestedSettings (SOAP)</span><span class="sxs-lookup"><span data-stu-id="c47c9-115">RequestedSettings (SOAP)</span></span>](requestedsettings-soap.md) <br/> |<span data-ttu-id="c47c9-116">Contém os nomes das definições de configuração de domínio solicitado.</span><span class="sxs-lookup"><span data-stu-id="c47c9-116">Contains the names of the requested domain configuration settings.</span></span>  <br/> |
|[<span data-ttu-id="c47c9-117">RequestedVersion (SOAP)</span><span class="sxs-lookup"><span data-stu-id="c47c9-117">RequestedVersion (SOAP)</span></span>](requestedversion-soap.md) <br/> |<span data-ttu-id="c47c9-118">Especifica a versão do servidor que usará o provedor.</span><span class="sxs-lookup"><span data-stu-id="c47c9-118">Specifies the server version that the provider will use.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="c47c9-119">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="c47c9-119">Parent elements</span></span>

<span data-ttu-id="c47c9-120">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="c47c9-120">None.</span></span>
  
## <a name="text-value"></a><span data-ttu-id="c47c9-121">Text value</span><span class="sxs-lookup"><span data-stu-id="c47c9-121">Text value</span></span>

<span data-ttu-id="c47c9-122">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="c47c9-122">None.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="c47c9-123">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="c47c9-123">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c47c9-124">Namespace</span><span class="sxs-lookup"><span data-stu-id="c47c9-124">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/2010/Autodiscover  <br/> |
|<span data-ttu-id="c47c9-125">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="c47c9-125">Schema Name</span></span>  <br/> |<span data-ttu-id="c47c9-126">Esquema de descoberta automática</span><span class="sxs-lookup"><span data-stu-id="c47c9-126">Autodiscover schema</span></span>  <br/> |
|<span data-ttu-id="c47c9-127">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="c47c9-127">Validation File</span></span>  <br/> |<span data-ttu-id="c47c9-128">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="c47c9-128">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="c47c9-129">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="c47c9-129">Can be Empty</span></span>  <br/> |<span data-ttu-id="c47c9-130">Verdadeiro</span><span class="sxs-lookup"><span data-stu-id="c47c9-130">True</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="c47c9-131">Ver também</span><span class="sxs-lookup"><span data-stu-id="c47c9-131">See also</span></span>



[<span data-ttu-id="c47c9-132">Operação de GetDomainSettings (SOAP)</span><span class="sxs-lookup"><span data-stu-id="c47c9-132">GetDomainSettings operation (SOAP)</span></span>](getdomainsettings-operation-soap.md)

