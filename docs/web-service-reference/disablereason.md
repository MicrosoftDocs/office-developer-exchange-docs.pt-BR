---
title: DisableReason
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: f41b5be6-9b79-4e83-8cdb-aa779e13cb3f
description: O elemento DisableReason especifica a razão para desabilitar um aplicativo.
ms.openlocfilehash: 1406d69647bde5389dc9bb61adf7537a57d5adfc
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44463668"
---
# <a name="disablereason"></a><span data-ttu-id="5ef5e-103">DisableReason</span><span class="sxs-lookup"><span data-stu-id="5ef5e-103">DisableReason</span></span>

<span data-ttu-id="5ef5e-104">O elemento **DisableReason** especifica a razão para desabilitar um aplicativo.</span><span class="sxs-lookup"><span data-stu-id="5ef5e-104">The **DisableReason** element specifies the reason for disabling an app.</span></span> 
  
```XML
<DisableReason> NoReason | OutlookClientPerformance | OWAClientPerformance | MobileClientPerformance </DisableReason>
```

 <span data-ttu-id="5ef5e-105">**DisableReasonType**</span><span class="sxs-lookup"><span data-stu-id="5ef5e-105">**DisableReasonType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="5ef5e-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="5ef5e-106">Attributes and elements</span></span>

<span data-ttu-id="5ef5e-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="5ef5e-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="5ef5e-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="5ef5e-108">Attributes</span></span>

<span data-ttu-id="5ef5e-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="5ef5e-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="5ef5e-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="5ef5e-110">Child elements</span></span>

<span data-ttu-id="5ef5e-111">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="5ef5e-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="5ef5e-112">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="5ef5e-112">Parent elements</span></span>

|<span data-ttu-id="5ef5e-113">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="5ef5e-113">**Element**</span></span>|<span data-ttu-id="5ef5e-114">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="5ef5e-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="5ef5e-115">DisableApp</span><span class="sxs-lookup"><span data-stu-id="5ef5e-115">DisableApp</span></span>](disableapp.md) <br/> |<span data-ttu-id="5ef5e-116">Especifica uma solicitação para desabilitar um aplicativo.</span><span class="sxs-lookup"><span data-stu-id="5ef5e-116">Specifies a request to disable an app.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="5ef5e-117">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="5ef5e-117">Text value</span></span>

<span data-ttu-id="5ef5e-118">**Valor de texto do elemento DisableReason**</span><span class="sxs-lookup"><span data-stu-id="5ef5e-118">**DisableReason element text value**</span></span>

|<span data-ttu-id="5ef5e-119">**Valor**</span><span class="sxs-lookup"><span data-stu-id="5ef5e-119">**Value**</span></span>|<span data-ttu-id="5ef5e-120">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="5ef5e-120">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="5ef5e-121">Noreason</span><span class="sxs-lookup"><span data-stu-id="5ef5e-121">NoReason</span></span>  <br/> |<span data-ttu-id="5ef5e-122">Nenhum motivo fornecido</span><span class="sxs-lookup"><span data-stu-id="5ef5e-122">No reason given</span></span>  <br/> |
|<span data-ttu-id="5ef5e-123">OutlookClientPerformance</span><span class="sxs-lookup"><span data-stu-id="5ef5e-123">OutlookClientPerformance</span></span>  <br/> |<span data-ttu-id="5ef5e-124">Para melhorar o desempenho do cliente de email.</span><span class="sxs-lookup"><span data-stu-id="5ef5e-124">To improve email client performance.</span></span>  <br/> |
|<span data-ttu-id="5ef5e-125">OWAClientPerformance</span><span class="sxs-lookup"><span data-stu-id="5ef5e-125">OWAClientPerformance</span></span>  <br/> |<span data-ttu-id="5ef5e-126">Para melhorar o desempenho do cliente do aplicativo Web.</span><span class="sxs-lookup"><span data-stu-id="5ef5e-126">To improve Web app client performance.</span></span>  <br/> |
|<span data-ttu-id="5ef5e-127">MobileClientPerformance</span><span class="sxs-lookup"><span data-stu-id="5ef5e-127">MobileClientPerformance</span></span>  <br/> |<span data-ttu-id="5ef5e-128">Para melhorar o desempenho do cliente móvel.</span><span class="sxs-lookup"><span data-stu-id="5ef5e-128">To improve mobile client performance.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="5ef5e-129">Comentários</span><span class="sxs-lookup"><span data-stu-id="5ef5e-129">Remarks</span></span>

<span data-ttu-id="5ef5e-130">Este elemento foi introduzido no Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="5ef5e-130">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="5ef5e-131">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="5ef5e-131">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="5ef5e-132">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="5ef5e-132">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="5ef5e-133">Namespace</span><span class="sxs-lookup"><span data-stu-id="5ef5e-133">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="5ef5e-134">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="5ef5e-134">Schema Name</span></span>  <br/> |<span data-ttu-id="5ef5e-135">Esquema de tipo</span><span class="sxs-lookup"><span data-stu-id="5ef5e-135">Type schema</span></span>  <br/> |
|<span data-ttu-id="5ef5e-136">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="5ef5e-136">Validation File</span></span>  <br/> |<span data-ttu-id="5ef5e-137">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="5ef5e-137">types.xsd</span></span>  <br/> |
|<span data-ttu-id="5ef5e-138">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="5ef5e-138">Can Be Empty</span></span>  <br/> ||
   
## <a name="see-also"></a><span data-ttu-id="5ef5e-139">Confira também</span><span class="sxs-lookup"><span data-stu-id="5ef5e-139">See also</span></span>

- [<span data-ttu-id="5ef5e-140">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="5ef5e-140">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

