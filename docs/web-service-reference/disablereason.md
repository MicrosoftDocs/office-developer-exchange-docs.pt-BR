---
title: DisableReason
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: f41b5be6-9b79-4e83-8cdb-aa779e13cb3f
description: O elemento DisableReason Especifica a razão para desabilitar um aplicativo.
ms.openlocfilehash: f900bd1b98b294900f767c778b9c5f87f74042ca
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19751837"
---
# <a name="disablereason"></a><span data-ttu-id="eb96b-103">DisableReason</span><span class="sxs-lookup"><span data-stu-id="eb96b-103">DisableReason</span></span>

<span data-ttu-id="eb96b-104">O elemento **DisableReason** Especifica a razão para desabilitar um aplicativo.</span><span class="sxs-lookup"><span data-stu-id="eb96b-104">The **DisableReason** element specifies the reason for disabling an app.</span></span> 
  
```XML
<DisableReason> NoReason | OutlookClientPerformance | OWAClientPerformance | MobileClientPerformance </DisableReason>
```

 <span data-ttu-id="eb96b-105">**DisableReasonType**</span><span class="sxs-lookup"><span data-stu-id="eb96b-105">**DisableReasonType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="eb96b-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="eb96b-106">Attributes and elements</span></span>

<span data-ttu-id="eb96b-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="eb96b-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="eb96b-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="eb96b-108">Attributes</span></span>

<span data-ttu-id="eb96b-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="eb96b-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="eb96b-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="eb96b-110">Child elements</span></span>

<span data-ttu-id="eb96b-111">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="eb96b-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="eb96b-112">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="eb96b-112">Parent elements</span></span>

|<span data-ttu-id="eb96b-113">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="eb96b-113">**Element**</span></span>|<span data-ttu-id="eb96b-114">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="eb96b-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="eb96b-115">DisableApp</span><span class="sxs-lookup"><span data-stu-id="eb96b-115">DisableApp</span></span>](disableapp.md) <br/> |<span data-ttu-id="eb96b-116">Especifica uma solicitação para desabilitar um aplicativo.</span><span class="sxs-lookup"><span data-stu-id="eb96b-116">Specifies a request to disable an app.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="eb96b-117">Text value</span><span class="sxs-lookup"><span data-stu-id="eb96b-117">Text value</span></span>

<span data-ttu-id="eb96b-118">**Valor de texto do elemento DisableReason**</span><span class="sxs-lookup"><span data-stu-id="eb96b-118">**DisableReason element text value**</span></span>

|<span data-ttu-id="eb96b-119">**Valor**</span><span class="sxs-lookup"><span data-stu-id="eb96b-119">**Value**</span></span>|<span data-ttu-id="eb96b-120">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="eb96b-120">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="eb96b-121">NoReason</span><span class="sxs-lookup"><span data-stu-id="eb96b-121">NoReason</span></span>  <br/> |<span data-ttu-id="eb96b-122">Não há motivo dado</span><span class="sxs-lookup"><span data-stu-id="eb96b-122">No reason given</span></span>  <br/> |
|<span data-ttu-id="eb96b-123">OutlookClientPerformance</span><span class="sxs-lookup"><span data-stu-id="eb96b-123">OutlookClientPerformance</span></span>  <br/> |<span data-ttu-id="eb96b-124">Para melhorar o desempenho do cliente de email.</span><span class="sxs-lookup"><span data-stu-id="eb96b-124">To improve email client performance.</span></span>  <br/> |
|<span data-ttu-id="eb96b-125">OWAClientPerformance</span><span class="sxs-lookup"><span data-stu-id="eb96b-125">OWAClientPerformance</span></span>  <br/> |<span data-ttu-id="eb96b-126">Para melhorar o desempenho de cliente de aplicativo Web.</span><span class="sxs-lookup"><span data-stu-id="eb96b-126">To improve Web app client performance.</span></span>  <br/> |
|<span data-ttu-id="eb96b-127">MobileClientPerformance</span><span class="sxs-lookup"><span data-stu-id="eb96b-127">MobileClientPerformance</span></span>  <br/> |<span data-ttu-id="eb96b-128">Para melhorar o desempenho do cliente móvel.</span><span class="sxs-lookup"><span data-stu-id="eb96b-128">To improve mobile client performance.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="eb96b-129">Coment�rios</span><span class="sxs-lookup"><span data-stu-id="eb96b-129">Remarks</span></span>

<span data-ttu-id="eb96b-130">Este elemento foi introduzido no Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="eb96b-130">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="eb96b-131">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="eb96b-131">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="eb96b-132">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="eb96b-132">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="eb96b-133">Namespace</span><span class="sxs-lookup"><span data-stu-id="eb96b-133">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="eb96b-134">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="eb96b-134">Schema Name</span></span>  <br/> |<span data-ttu-id="eb96b-135">Esquema de tipo</span><span class="sxs-lookup"><span data-stu-id="eb96b-135">Type schema</span></span>  <br/> |
|<span data-ttu-id="eb96b-136">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="eb96b-136">Validation File</span></span>  <br/> |<span data-ttu-id="eb96b-137">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="eb96b-137">types.xsd</span></span>  <br/> |
|<span data-ttu-id="eb96b-138">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="eb96b-138">Can Be Empty</span></span>  <br/> ||
   
## <a name="see-also"></a><span data-ttu-id="eb96b-139">Confira também</span><span class="sxs-lookup"><span data-stu-id="eb96b-139">See also</span></span>

- [<span data-ttu-id="eb96b-140">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="eb96b-140">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

