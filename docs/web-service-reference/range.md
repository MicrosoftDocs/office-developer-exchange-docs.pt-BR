---
title: Intervalo
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: ee2891e4-3aa6-4258-9727-1f2ee9622508
description: O elemento Range Especifica um intervalo de ocorrências do item de calendário para um item de calendário de repetição.
ms.openlocfilehash: 0264c541604808b46a50e292b8ff75f205796295
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19824946"
---
# <a name="range"></a><span data-ttu-id="24aa4-103">Intervalo</span><span class="sxs-lookup"><span data-stu-id="24aa4-103">Range</span></span>

<span data-ttu-id="24aa4-104">O elemento **Range** Especifica um intervalo de ocorrências do item de calendário para um item de calendário de repetição.</span><span class="sxs-lookup"><span data-stu-id="24aa4-104">The **Range** element specifies a range of calendar item occurrences for a repeating calendar item.</span></span> 
  
```XML
<Range Start="" End="" Count="" CompareOriginalStartTime=""/>
```

 <span data-ttu-id="24aa4-105">**OccurrencesRangeType**</span><span class="sxs-lookup"><span data-stu-id="24aa4-105">**OccurrencesRangeType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="24aa4-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="24aa4-106">Attributes and elements</span></span>

<span data-ttu-id="24aa4-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="24aa4-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="24aa4-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="24aa4-108">Attributes</span></span>

|<span data-ttu-id="24aa4-109">**Attribute**</span><span class="sxs-lookup"><span data-stu-id="24aa4-109">**Attribute**</span></span>|<span data-ttu-id="24aa4-110">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="24aa4-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="24aa4-111">**Start**</span><span class="sxs-lookup"><span data-stu-id="24aa4-111">**Start**</span></span> <br/> |<span data-ttu-id="24aa4-112">O valor de texto do atributo **Iniciar** é a data de início do intervalo de item recorrente.</span><span class="sxs-lookup"><span data-stu-id="24aa4-112">The text value of the **Start** attribute is the start date of the recurring item range.</span></span> <span data-ttu-id="24aa4-113">Este é um valor de **data/hora** .</span><span class="sxs-lookup"><span data-stu-id="24aa4-113">This is a **dateTime** value.</span></span>  <br/> |
|<span data-ttu-id="24aa4-114">**End**</span><span class="sxs-lookup"><span data-stu-id="24aa4-114">**End**</span></span> <br/> |<span data-ttu-id="24aa4-115">O valor de texto do atributo **final** é a data de término do intervalo de item recorrente.</span><span class="sxs-lookup"><span data-stu-id="24aa4-115">The text value of the **End** attribute is the end date of the recurring item range.</span></span> <span data-ttu-id="24aa4-116">Este é um valor de **data/hora** .</span><span class="sxs-lookup"><span data-stu-id="24aa4-116">This is a **dateTime** value.</span></span>  <br/> |
|<span data-ttu-id="24aa4-117">**Count**</span><span class="sxs-lookup"><span data-stu-id="24aa4-117">**Count**</span></span> <br/> |<span data-ttu-id="24aa4-118">O valor de texto do atributo **Count** é o número de ocorrências do item recorrente.</span><span class="sxs-lookup"><span data-stu-id="24aa4-118">The text value of the **Count** attribute is the number of occurrences of the recurring item.</span></span> <span data-ttu-id="24aa4-119">Este é um valor **inteiro** .</span><span class="sxs-lookup"><span data-stu-id="24aa4-119">This is an **integer** value.</span></span>  <br/> |
|<span data-ttu-id="24aa4-120">**CompareOriginalStartTime**</span><span class="sxs-lookup"><span data-stu-id="24aa4-120">**CompareOriginalStartTime**</span></span> <br/> |<span data-ttu-id="24aa4-121">O valor de texto de **true** para o atributo **CompareOriginalStartTime** indica que o cliente compare a hora de início original com a nova hora de início.</span><span class="sxs-lookup"><span data-stu-id="24aa4-121">The text value of **true** for the **CompareOriginalStartTime** attribute indicates that the client should compare the original start time with the new start time.</span></span> <span data-ttu-id="24aa4-122">Um valor **false** indica que o cliente não precisa comparar a hora de início original com a nova hora de início.</span><span class="sxs-lookup"><span data-stu-id="24aa4-122">A value of **false** indicates that the client does not need to compare the original start time with the new start time.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="24aa4-123">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="24aa4-123">Child elements</span></span>

<span data-ttu-id="24aa4-124">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="24aa4-124">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="24aa4-125">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="24aa4-125">Parent elements</span></span>

[<span data-ttu-id="24aa4-126">Ranges</span><span class="sxs-lookup"><span data-stu-id="24aa4-126">Ranges</span></span>](ranges.md)
  
## <a name="remarks"></a><span data-ttu-id="24aa4-127">Coment�rios</span><span class="sxs-lookup"><span data-stu-id="24aa4-127">Remarks</span></span>

<span data-ttu-id="24aa4-128">Este elemento foi introduzido no Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="24aa4-128">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="24aa4-129">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="24aa4-129">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="24aa4-130">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="24aa4-130">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="24aa4-131">Namespace</span><span class="sxs-lookup"><span data-stu-id="24aa4-131">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="24aa4-132">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="24aa4-132">Schema name</span></span>  <br/> |<span data-ttu-id="24aa4-133">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="24aa4-133">Types schema</span></span>  <br/> |
|<span data-ttu-id="24aa4-134">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="24aa4-134">Validation file</span></span>  <br/> |<span data-ttu-id="24aa4-135">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="24aa4-135">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="24aa4-136">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="24aa4-136">Can be empty</span></span>  <br/> ||
   
