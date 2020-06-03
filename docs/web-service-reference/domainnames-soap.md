---
title: Usermainnames (SOAP)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
localization_priority: Normal
ms.assetid: 79ffc3f9-25c4-40b5-84ce-09a3c5f892fa
description: O elemento DomainNames representa a coleção de nomes de domínio. O elemento DomainNames é somente para uso interno. Esse elemento não é usado por clientes.
ms.openlocfilehash: 0b425b3cd4c0e7cb2427920d61feb04010a3b123
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44458415"
---
# <a name="domainnames-soap"></a><span data-ttu-id="6cc3d-105">Usermainnames (SOAP)</span><span class="sxs-lookup"><span data-stu-id="6cc3d-105">DomainNames (SOAP)</span></span>

<span data-ttu-id="6cc3d-106">O elemento **DomainNames** representa a coleção de nomes de domínio.</span><span class="sxs-lookup"><span data-stu-id="6cc3d-106">The **DomainNames** element represents the domain names collection.</span></span> <span data-ttu-id="6cc3d-107">O elemento **DomainNames** é somente para uso interno.</span><span class="sxs-lookup"><span data-stu-id="6cc3d-107">The **DomainNames** element is for internal use only.</span></span> <span data-ttu-id="6cc3d-108">Esse elemento não é usado por clientes.</span><span class="sxs-lookup"><span data-stu-id="6cc3d-108">This element is not used by clients.</span></span> 
  
```XML
<DomainNames>
    <Domains/>
</DomainNames>
```

 <span data-ttu-id="6cc3d-109">**DomainNames**</span><span class="sxs-lookup"><span data-stu-id="6cc3d-109">**DomainNames**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="6cc3d-110">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="6cc3d-110">Attributes and elements</span></span>

<span data-ttu-id="6cc3d-111">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="6cc3d-111">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="6cc3d-112">Atributos</span><span class="sxs-lookup"><span data-stu-id="6cc3d-112">Attributes</span></span>

<span data-ttu-id="6cc3d-113">Nenhum</span><span class="sxs-lookup"><span data-stu-id="6cc3d-113">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="6cc3d-114">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="6cc3d-114">Child elements</span></span>

|<span data-ttu-id="6cc3d-115">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="6cc3d-115">**Element**</span></span>|<span data-ttu-id="6cc3d-116">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="6cc3d-116">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="6cc3d-117">Domínios (SOAP)</span><span class="sxs-lookup"><span data-stu-id="6cc3d-117">Domains (SOAP)</span></span>](domains-soap.md) <br/> |<span data-ttu-id="6cc3d-118">Representa uma coleção de domínios retornados da [operação GetDomainSettings (SOAP)](getdomainsettings-operation-soap.md), [GETFEDERATIONINFORMATION Operation (SOAP)](getfederationinformation-operation-soap.md)ou a [operação GetOrganizationRelationshipSettings (SOAP)](getorganizationrelationshipsettings-operation-soap.md).</span><span class="sxs-lookup"><span data-stu-id="6cc3d-118">Represents a collection of domains that are returned from the [GetDomainSettings operation (SOAP)](getdomainsettings-operation-soap.md), [GetFederationInformation operation (SOAP)](getfederationinformation-operation-soap.md), or the [GetOrganizationRelationshipSettings operation (SOAP)](getorganizationrelationshipsettings-operation-soap.md).</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="6cc3d-119">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="6cc3d-119">Parent elements</span></span>

|<span data-ttu-id="6cc3d-120">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="6cc3d-120">**Element**</span></span>|<span data-ttu-id="6cc3d-121">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="6cc3d-121">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="6cc3d-122">OrganizationRelationshipSettings (SOAP)</span><span class="sxs-lookup"><span data-stu-id="6cc3d-122">OrganizationRelationshipSettings (SOAP)</span></span>](organizationrelationshipsettings-soap.md) <br/> |<span data-ttu-id="6cc3d-123">Representa uma lista de relações de organização para uma única organização.</span><span class="sxs-lookup"><span data-stu-id="6cc3d-123">Represents a list of organization relationships for a single organization.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="6cc3d-124">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="6cc3d-124">Text value</span></span>

<span data-ttu-id="6cc3d-125">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="6cc3d-125">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="6cc3d-126">Comentários</span><span class="sxs-lookup"><span data-stu-id="6cc3d-126">Remarks</span></span>

<span data-ttu-id="6cc3d-127">Este elemento representa os domínios SMTP das organizações externas.</span><span class="sxs-lookup"><span data-stu-id="6cc3d-127">This element represents the SMTP domains of the external organizations.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="6cc3d-128">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="6cc3d-128">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="6cc3d-129">Namespace</span><span class="sxs-lookup"><span data-stu-id="6cc3d-129">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/2010/Autodiscover  <br/> |
|<span data-ttu-id="6cc3d-130">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="6cc3d-130">Schema Name</span></span>  <br/> |<span data-ttu-id="6cc3d-131">Esquema de descoberta automática</span><span class="sxs-lookup"><span data-stu-id="6cc3d-131">Autodiscover schema</span></span>  <br/> |
|<span data-ttu-id="6cc3d-132">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="6cc3d-132">Validation File</span></span>  <br/> |<span data-ttu-id="6cc3d-133">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="6cc3d-133">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="6cc3d-134">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="6cc3d-134">Can be Empty</span></span>  <br/> |<span data-ttu-id="6cc3d-135">Verdadeiro</span><span class="sxs-lookup"><span data-stu-id="6cc3d-135">True</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="6cc3d-136">Confira também</span><span class="sxs-lookup"><span data-stu-id="6cc3d-136">See also</span></span>

- [<span data-ttu-id="6cc3d-137">Operação GetOrganizationRelationshipSettings (SOAP)</span><span class="sxs-lookup"><span data-stu-id="6cc3d-137">GetOrganizationRelationshipSettings operation (SOAP)</span></span>](getorganizationrelationshipsettings-operation-soap.md)

