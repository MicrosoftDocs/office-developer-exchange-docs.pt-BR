---
title: Erro (POX)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
localization_priority: Normal
api_type:
- schema
ms.assetid: 91c63b62-ab68-4c32-a2f7-5a87c188335b
description: O elemento de erro contém uma resposta de erro de descoberta automática.
ms.openlocfilehash: 3135a352365fe3000ce2d202ad78452d5c8ccc7f
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19752086"
---
# <a name="error-pox"></a><span data-ttu-id="11016-103">Erro (POX)</span><span class="sxs-lookup"><span data-stu-id="11016-103">Error (POX)</span></span>

<span data-ttu-id="11016-104">O elemento de **erro** contém uma resposta de erro de descoberta automática.</span><span class="sxs-lookup"><span data-stu-id="11016-104">The **Error** element contains an Autodiscover error response.</span></span> 
  
[<span data-ttu-id="11016-105">Descoberta automática (POX)</span><span class="sxs-lookup"><span data-stu-id="11016-105">AutoDiscover (POX)</span></span>](autodiscover-pox.md)
  
[<span data-ttu-id="11016-106">Resposta POX)</span><span class="sxs-lookup"><span data-stu-id="11016-106">Response (POX)</span></span>](response-pox.md)
  
[<span data-ttu-id="11016-107">Conta (POX)</span><span class="sxs-lookup"><span data-stu-id="11016-107">Account (POX)</span></span>](account-pox.md)
  
[<span data-ttu-id="11016-108">Erro (POX)</span><span class="sxs-lookup"><span data-stu-id="11016-108">Error (POX)</span></span>](error-pox.md)
  
```xml
<Error Time="" Id="">
   <ErrorCode/>
   <Message/>
   <DebugData/>
</Error>
```

## <a name="attributes-and-elements"></a><span data-ttu-id="11016-109">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="11016-109">Attributes and elements</span></span>

<span data-ttu-id="11016-110">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="11016-110">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="11016-111">Atributos</span><span class="sxs-lookup"><span data-stu-id="11016-111">Attributes</span></span>

|<span data-ttu-id="11016-112">**Attribute**</span><span class="sxs-lookup"><span data-stu-id="11016-112">**Attribute**</span></span>|<span data-ttu-id="11016-113">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="11016-113">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="11016-114">Hora</span><span class="sxs-lookup"><span data-stu-id="11016-114">Time</span></span>  <br/> |<span data-ttu-id="11016-115">Representa a hora em que a resposta de erro foi retornada.</span><span class="sxs-lookup"><span data-stu-id="11016-115">Represents the time when the error response was returned.</span></span>  <br/> |
|<span data-ttu-id="11016-116">Id</span><span class="sxs-lookup"><span data-stu-id="11016-116">Id</span></span>  <br/> |<span data-ttu-id="11016-117">Representa um hash do nome do computador que está executando o Microsoft Exchange Server 2007 que possui a função de servidor acesso para cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="11016-117">Represents a hash of the name of the computer that is running Microsoft Exchange Server 2007 that has the Client Access server role installed.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="11016-118">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="11016-118">Child elements</span></span>

|<span data-ttu-id="11016-119">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="11016-119">**Element**</span></span>|<span data-ttu-id="11016-120">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="11016-120">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="11016-121">ErrorCode POX)</span><span class="sxs-lookup"><span data-stu-id="11016-121">ErrorCode (POX)</span></span>](errorcode-pox.md) <br/> |<span data-ttu-id="11016-122">Contém o código de erro para um erro de resposta de descoberta automática.</span><span class="sxs-lookup"><span data-stu-id="11016-122">Contains the error code for an error Autodiscover response.</span></span>  <br/> |
|[<span data-ttu-id="11016-123">Mensagem (POX)</span><span class="sxs-lookup"><span data-stu-id="11016-123">Message (POX)</span></span>](message-pox.md) <br/> |<span data-ttu-id="11016-124">Contém a mensagem de erro para um erro de resposta de descoberta automática.</span><span class="sxs-lookup"><span data-stu-id="11016-124">Contains the error message for an error Autodiscover response.</span></span>  <br/> |
|[<span data-ttu-id="11016-125">DebugData (POX)</span><span class="sxs-lookup"><span data-stu-id="11016-125">DebugData (POX)</span></span>](debugdata-pox.md) <br/> |<span data-ttu-id="11016-126">Contém os dados de depuração para um erro de resposta de descoberta automática.</span><span class="sxs-lookup"><span data-stu-id="11016-126">Contains the debug data for an error Autodiscover response.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="11016-127">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="11016-127">Parent elements</span></span>

|<span data-ttu-id="11016-128">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="11016-128">**Element**</span></span>|<span data-ttu-id="11016-129">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="11016-129">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="11016-130">Conta (POX)</span><span class="sxs-lookup"><span data-stu-id="11016-130">Account (POX)</span></span>](account-pox.md) <br/> |<span data-ttu-id="11016-131">Contém uma resposta de erro de descoberta automática.</span><span class="sxs-lookup"><span data-stu-id="11016-131">Contains an Autodiscover error response.</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="11016-132">Confira também</span><span class="sxs-lookup"><span data-stu-id="11016-132">See also</span></span>



[<span data-ttu-id="11016-133">Elementos de Autodiscover XML POX para Exchange</span><span class="sxs-lookup"><span data-stu-id="11016-133">POX Autodiscover XML elements for Exchange</span></span>](pox-autodiscover-xml-elements-for-exchange.md)

