---
title: Solicitação (POX)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
localization_priority: Normal
api_type:
- schema
ms.assetid: da54eb32-7ce5-4384-9893-255a2243a959
description: O elemento de solicitação contém a solicitação para o serviço Descoberta automática.
ms.openlocfilehash: ed6b0a80e83e160287f382a881dc5405bfb47a37
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/25/2018
ms.locfileid: "19825124"
---
# <a name="request-pox"></a><span data-ttu-id="7a89e-103">Solicitação (POX)</span><span class="sxs-lookup"><span data-stu-id="7a89e-103">Request (POX)</span></span>

<span data-ttu-id="7a89e-104">O elemento de **solicitação** contém a solicitação para o serviço Descoberta automática.</span><span class="sxs-lookup"><span data-stu-id="7a89e-104">The **Request** element contains the request to the Autodiscover service.</span></span> 
  
[<span data-ttu-id="7a89e-105">Descoberta automática (POX)</span><span class="sxs-lookup"><span data-stu-id="7a89e-105">AutoDiscover (POX)</span></span>](autodiscover-pox.md)
  
[<span data-ttu-id="7a89e-106">Solicitação (POX)</span><span class="sxs-lookup"><span data-stu-id="7a89e-106">Request (POX)</span></span>](request-pox.md)
  
```xml
<Request>
   <AcceptableResponseSchema/>
   <EMailAddress/>
</Request>
```

## <a name="attributes-and-elements"></a><span data-ttu-id="7a89e-107">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="7a89e-107">Attributes and elements</span></span>

<span data-ttu-id="7a89e-108">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="7a89e-108">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="7a89e-109">Atributos</span><span class="sxs-lookup"><span data-stu-id="7a89e-109">Attributes</span></span>

<span data-ttu-id="7a89e-110">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="7a89e-110">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="7a89e-111">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="7a89e-111">Child elements</span></span>

|<span data-ttu-id="7a89e-112">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="7a89e-112">**Element**</span></span>|<span data-ttu-id="7a89e-113">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="7a89e-113">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="7a89e-114">AcceptableResponseSchema (POX)</span><span class="sxs-lookup"><span data-stu-id="7a89e-114">AcceptableResponseSchema (POX)</span></span>](acceptableresponseschema-pox.md) <br/> |<span data-ttu-id="7a89e-115">Identifica o esquema de uma resposta de descoberta automática.</span><span class="sxs-lookup"><span data-stu-id="7a89e-115">Identifies the schema for an Autodiscover response.</span></span>  <br/> |
|[<span data-ttu-id="7a89e-116">EmailAddress (NonEmptyStringType)</span><span class="sxs-lookup"><span data-stu-id="7a89e-116">EmailAddress (NonEmptyStringType)</span></span>](emailaddress-nonemptystringtype.md) <br/> |<span data-ttu-id="7a89e-117">Identifica o endereço de email do usuário.</span><span class="sxs-lookup"><span data-stu-id="7a89e-117">Identifies the user's e-mail address.</span></span>  <br/> |
|[<span data-ttu-id="7a89e-118">LegacyDN (POX)</span><span class="sxs-lookup"><span data-stu-id="7a89e-118">LegacyDN (POX)</span></span>](legacydn-pox.md) <br/> |<span data-ttu-id="7a89e-119">Identifica a caixa de correio de um usuário por nome distinto herdado.</span><span class="sxs-lookup"><span data-stu-id="7a89e-119">Identifies a user's mailbox by legacy distinguished name.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="7a89e-120">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="7a89e-120">Parent elements</span></span>

|<span data-ttu-id="7a89e-121">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="7a89e-121">**Element**</span></span>|<span data-ttu-id="7a89e-122">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="7a89e-122">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="7a89e-123">Descoberta automática (POX)</span><span class="sxs-lookup"><span data-stu-id="7a89e-123">AutoDiscover (POX)</span></span>](autodiscover-pox.md) <br/> |<span data-ttu-id="7a89e-124">O elemento raiz em uma solicitação de descoberta automática.</span><span class="sxs-lookup"><span data-stu-id="7a89e-124">The root element in an Autodiscover request.</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="7a89e-125">Confira também</span><span class="sxs-lookup"><span data-stu-id="7a89e-125">See also</span></span>



[<span data-ttu-id="7a89e-126">Elementos de Autodiscover XML POX para Exchange</span><span class="sxs-lookup"><span data-stu-id="7a89e-126">POX Autodiscover XML elements for Exchange</span></span>](pox-autodiscover-xml-elements-for-exchange.md)

