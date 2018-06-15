---
title: OrganizationRelationshipSettings (SOAP)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
localization_priority: Normal
ms.assetid: 917481bb-46fc-4b88-8683-4cf812dcb0ab
description: O elemento OrganizationRelationshipSettings representa uma lista de relacionamentos de organização para uma única organização. O elemento OrganizationRelationshipSettings é apenas para uso interno. Este elemento não é usado pelos clientes.
ms.openlocfilehash: ed6cc0ef1891cd92c02a8e088e913886048623ee
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19824660"
---
# <a name="organizationrelationshipsettings-soap"></a><span data-ttu-id="c65b6-105">OrganizationRelationshipSettings (SOAP)</span><span class="sxs-lookup"><span data-stu-id="c65b6-105">OrganizationRelationshipSettings (SOAP)</span></span>

<span data-ttu-id="c65b6-106">O elemento **OrganizationRelationshipSettings** representa uma lista de relacionamentos de organização para uma única organização.</span><span class="sxs-lookup"><span data-stu-id="c65b6-106">The **OrganizationRelationshipSettings** element represents a list of organization relationships for a single organization.</span></span> <span data-ttu-id="c65b6-107">O elemento **OrganizationRelationshipSettings** é apenas para uso interno.</span><span class="sxs-lookup"><span data-stu-id="c65b6-107">The **OrganizationRelationshipSettings** element is for internal use only.</span></span> <span data-ttu-id="c65b6-108">Este elemento não é usado pelos clientes.</span><span class="sxs-lookup"><span data-stu-id="c65b6-108">This element is not used by clients.</span></span> 
  
```XML
<OrganizationRelationshipSettings>
    <DeliveryReportEnabled/>
    <DomainNames/>
    <FreeBusyAccessEnabled/>
    <FreeBusyAccessLevel/>
    <MailTipsAccessEnabled/>
    <MailTipsAccessLevel/>
    <MailboxMoveEnabled/>
    <Name/>
    <TargetApplicationUri/>
    <TargetAudodiscoverEpr/>
    <TargetSharingEpr/>
</OrganizationRelationshipSettings>
```

 <span data-ttu-id="c65b6-109">**OrganizationRelationshipSettings**</span><span class="sxs-lookup"><span data-stu-id="c65b6-109">**OrganizationRelationshipSettings**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="c65b6-110">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="c65b6-110">Attributes and elements</span></span>

<span data-ttu-id="c65b6-111">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="c65b6-111">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="c65b6-112">Atributos</span><span class="sxs-lookup"><span data-stu-id="c65b6-112">Attributes</span></span>

<span data-ttu-id="c65b6-113">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="c65b6-113">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="c65b6-114">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="c65b6-114">Child elements</span></span>

|<span data-ttu-id="c65b6-115">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="c65b6-115">**Element**</span></span>|<span data-ttu-id="c65b6-116">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="c65b6-116">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="c65b6-117">DeliveryReportEnabled (SOAP)</span><span class="sxs-lookup"><span data-stu-id="c65b6-117">DeliveryReportEnabled (SOAP)</span></span>](deliveryreportenabled-soap.md) <br/> |<span data-ttu-id="c65b6-118">Representa o sinalizador [DeliveryReportEnabled()](https://msdn.microsoft.com/library/Microsoft.Exchange.SoapWebClient.AutoDiscover.OrganizationRelationshipSettings.DeliveryReportEnabled.aspx) .</span><span class="sxs-lookup"><span data-stu-id="c65b6-118">Represents the [DeliveryReportEnabled()](https://msdn.microsoft.com/library/Microsoft.Exchange.SoapWebClient.AutoDiscover.OrganizationRelationshipSettings.DeliveryReportEnabled.aspx) flag.</span></span>  <br/> |
|[<span data-ttu-id="c65b6-119">DomainNames (SOAP)</span><span class="sxs-lookup"><span data-stu-id="c65b6-119">DomainNames (SOAP)</span></span>](domainnames-soap.md) <br/> |<span data-ttu-id="c65b6-120">Representa a coleção de nomes de domínio.</span><span class="sxs-lookup"><span data-stu-id="c65b6-120">Represents the domain names collection.</span></span>  <br/> |
|[<span data-ttu-id="c65b6-121">FreeBusyAccessEnabled (SOAP)</span><span class="sxs-lookup"><span data-stu-id="c65b6-121">FreeBusyAccessEnabled (SOAP)</span></span>](freebusyaccessenabled-soap.md) <br/> |<span data-ttu-id="c65b6-122">Representa o sinalizador [FreeBusyAccessEnabled()](https://msdn.microsoft.com/library/Microsoft.Exchange.SoapWebClient.AutoDiscover.OrganizationRelationshipSettings.FreeBusyAccessEnabled.aspx) .</span><span class="sxs-lookup"><span data-stu-id="c65b6-122">Represents the [FreeBusyAccessEnabled()](https://msdn.microsoft.com/library/Microsoft.Exchange.SoapWebClient.AutoDiscover.OrganizationRelationshipSettings.FreeBusyAccessEnabled.aspx) flag.</span></span>  <br/> |
|[<span data-ttu-id="c65b6-123">FreeBusyAccessLevel (SOAP)</span><span class="sxs-lookup"><span data-stu-id="c65b6-123">FreeBusyAccessLevel (SOAP)</span></span>](freebusyaccesslevel-soap.md) <br/> |<span data-ttu-id="c65b6-124">Representa a propriedade [FreeBusyAccessLevel](https://msdn.microsoft.com/library/Microsoft.Exchange.Data.Directory.SystemConfiguration.OrganizationRelationship.FreeBusyAccessLevel.aspx) .</span><span class="sxs-lookup"><span data-stu-id="c65b6-124">Represents the [FreeBusyAccessLevel](https://msdn.microsoft.com/library/Microsoft.Exchange.Data.Directory.SystemConfiguration.OrganizationRelationship.FreeBusyAccessLevel.aspx) property.</span></span>  <br/> |
|[<span data-ttu-id="c65b6-125">MailTipsAccessEnabled (SOAP)</span><span class="sxs-lookup"><span data-stu-id="c65b6-125">MailTipsAccessEnabled (SOAP)</span></span>](mailtipsaccessenabled-soap.md) <br/> |<span data-ttu-id="c65b6-126">Representa o sinalizador [MailTipsAccessEnabled()](https://msdn.microsoft.com/library/Microsoft.Exchange.SoapWebClient.AutoDiscover.OrganizationRelationshipSettings.MailTipsAccessEnabled.aspx) .</span><span class="sxs-lookup"><span data-stu-id="c65b6-126">Represents the [MailTipsAccessEnabled()](https://msdn.microsoft.com/library/Microsoft.Exchange.SoapWebClient.AutoDiscover.OrganizationRelationshipSettings.MailTipsAccessEnabled.aspx) flag.</span></span>  <br/> |
|[<span data-ttu-id="c65b6-127">MailTipsAccessLevel (SOAP)</span><span class="sxs-lookup"><span data-stu-id="c65b6-127">MailTipsAccessLevel (SOAP)</span></span>](mailtipsaccesslevel-soap.md) <br/> |<span data-ttu-id="c65b6-128">Representa a propriedade [MailTipsAccessLevel](https://msdn.microsoft.com/library/Microsoft.Exchange.Data.Directory.SystemConfiguration.OrganizationRelationship.MailTipsAccessLevel.aspx) .</span><span class="sxs-lookup"><span data-stu-id="c65b6-128">Represents the [MailTipsAccessLevel](https://msdn.microsoft.com/library/Microsoft.Exchange.Data.Directory.SystemConfiguration.OrganizationRelationship.MailTipsAccessLevel.aspx) property.</span></span>  <br/> |
|[<span data-ttu-id="c65b6-129">MailboxMoveEnabled (SOAP)</span><span class="sxs-lookup"><span data-stu-id="c65b6-129">MailboxMoveEnabled (SOAP)</span></span>](mailboxmoveenabled-soap.md) <br/> |<span data-ttu-id="c65b6-130">Representa o sinalizador [MailboxMoveEnabled()](https://msdn.microsoft.com/library/Microsoft.Exchange.SoapWebClient.AutoDiscover.OrganizationRelationshipSettings.MailboxMoveEnabled.aspx) .</span><span class="sxs-lookup"><span data-stu-id="c65b6-130">Represents the [MailboxMoveEnabled()](https://msdn.microsoft.com/library/Microsoft.Exchange.SoapWebClient.AutoDiscover.OrganizationRelationshipSettings.MailboxMoveEnabled.aspx) flag.</span></span>  <br/> |
|[<span data-ttu-id="c65b6-131">Nome (SOAP)</span><span class="sxs-lookup"><span data-stu-id="c65b6-131">Name (SOAP)</span></span>](name-soap.md) <br/> |<span data-ttu-id="c65b6-132">Representa o nome do relacionamento da organização.</span><span class="sxs-lookup"><span data-stu-id="c65b6-132">Represents the name of the organization relationship.</span></span>  <br/> |
|[<span data-ttu-id="c65b6-133">TargetApplicationUri (SOAP)</span><span class="sxs-lookup"><span data-stu-id="c65b6-133">TargetApplicationUri (SOAP)</span></span>](targetapplicationuri-soap.md) <br/> |<span data-ttu-id="c65b6-134">Define o URI do aplicativo de destino.</span><span class="sxs-lookup"><span data-stu-id="c65b6-134">Defines the target application URI.</span></span>  <br/> |
|[<span data-ttu-id="c65b6-135">TargetAutodiscoverEpr (SOAP)</span><span class="sxs-lookup"><span data-stu-id="c65b6-135">TargetAutodiscoverEpr (SOAP)</span></span>](targetautodiscoverepr-soap.md) <br/> |<span data-ttu-id="c65b6-136">Representa a propriedade [TargetAutodiscoverEpr](https://msdn.microsoft.com/library/Microsoft.Exchange.Data.Directory.SystemConfiguration.OrganizationRelationship.TargetAutodiscoverEpr.aspx) .</span><span class="sxs-lookup"><span data-stu-id="c65b6-136">Represents the [TargetAutodiscoverEpr](https://msdn.microsoft.com/library/Microsoft.Exchange.Data.Directory.SystemConfiguration.OrganizationRelationship.TargetAutodiscoverEpr.aspx) property.</span></span>  <br/> |
|[<span data-ttu-id="c65b6-137">TargetSharingEpr (SOAP)</span><span class="sxs-lookup"><span data-stu-id="c65b6-137">TargetSharingEpr (SOAP)</span></span>](targetsharingepr-soap.md) <br/> |<span data-ttu-id="c65b6-138">Representa a propriedade [TargetSharingEpr](https://msdn.microsoft.com/library/Microsoft.Exchange.Data.Directory.SystemConfiguration.OrganizationRelationship.TargetSharingEpr.aspx) .</span><span class="sxs-lookup"><span data-stu-id="c65b6-138">Represents the [TargetSharingEpr](https://msdn.microsoft.com/library/Microsoft.Exchange.Data.Directory.SystemConfiguration.OrganizationRelationship.TargetSharingEpr.aspx) property.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="c65b6-139">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="c65b6-139">Parent elements</span></span>

|<span data-ttu-id="c65b6-140">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="c65b6-140">**Element**</span></span>|<span data-ttu-id="c65b6-141">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="c65b6-141">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="c65b6-142">OrganizationRelationshipSettingsCollection (SOAP)</span><span class="sxs-lookup"><span data-stu-id="c65b6-142">OrganizationRelationshipSettingsCollection (SOAP)</span></span>](organizationrelationshipsettingscollection-soap.md) <br/> |<span data-ttu-id="c65b6-143">Representa uma lista de relacionamentos da organização que correspondem à consulta.</span><span class="sxs-lookup"><span data-stu-id="c65b6-143">Represents a list of organization relationships that match the query.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="c65b6-144">Text value</span><span class="sxs-lookup"><span data-stu-id="c65b6-144">Text value</span></span>

<span data-ttu-id="c65b6-145">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="c65b6-145">None.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="c65b6-146">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="c65b6-146">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c65b6-147">Namespace</span><span class="sxs-lookup"><span data-stu-id="c65b6-147">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/2010/Autodiscover  <br/> |
|<span data-ttu-id="c65b6-148">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="c65b6-148">Schema Name</span></span>  <br/> |<span data-ttu-id="c65b6-149">Esquema de descoberta automática</span><span class="sxs-lookup"><span data-stu-id="c65b6-149">Autodiscover schema</span></span>  <br/> |
|<span data-ttu-id="c65b6-150">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="c65b6-150">Validation File</span></span>  <br/> |<span data-ttu-id="c65b6-151">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="c65b6-151">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="c65b6-152">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="c65b6-152">Can be Empty</span></span>  <br/> |<span data-ttu-id="c65b6-153">Verdadeiro</span><span class="sxs-lookup"><span data-stu-id="c65b6-153">True</span></span>  <br/> |
   
