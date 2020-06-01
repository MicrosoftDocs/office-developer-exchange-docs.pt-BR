---
title: Ocorrência (transição de fuso horário)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- Occurrence
api_type:
- schema
ms.assetid: 5c1142b1-c51f-42e1-bbb2-57e00cad0fdb
description: O elemento ocorrência representa a ocorrência do dia da semana no mês em que ocorre a transição de fuso horário.
ms.openlocfilehash: 846f6b22f43bcda07b9408d768d0845a5acfe668
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44467974"
---
# <a name="occurrence-time-zone-transition"></a><span data-ttu-id="78ebe-103">Ocorrência (transição de fuso horário)</span><span class="sxs-lookup"><span data-stu-id="78ebe-103">Occurrence (Time Zone Transition)</span></span>

<span data-ttu-id="78ebe-104">O elemento **ocorrência** representa a ocorrência do dia da semana no mês em que ocorre a transição de fuso horário.</span><span class="sxs-lookup"><span data-stu-id="78ebe-104">The **Occurrence** element represents the occurrence of the day of the week in the month that the time zone transition occurs.</span></span> 
  
```xml
<Occurrence/>
```

<span data-ttu-id="78ebe-105">**int**</span><span class="sxs-lookup"><span data-stu-id="78ebe-105">**int**</span></span>

## <a name="attributes-and-elements"></a><span data-ttu-id="78ebe-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="78ebe-106">Attributes and elements</span></span>

<span data-ttu-id="78ebe-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="78ebe-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="78ebe-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="78ebe-108">Attributes</span></span>

<span data-ttu-id="78ebe-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="78ebe-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="78ebe-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="78ebe-110">Child elements</span></span>

<span data-ttu-id="78ebe-111">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="78ebe-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="78ebe-112">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="78ebe-112">Parent elements</span></span>

|<span data-ttu-id="78ebe-113">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="78ebe-113">**Element**</span></span>|<span data-ttu-id="78ebe-114">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="78ebe-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="78ebe-115">RecurringDayTransition</span><span class="sxs-lookup"><span data-stu-id="78ebe-115">RecurringDayTransition</span></span>](recurringdaytransition.md) <br/> |<span data-ttu-id="78ebe-116">Representa uma transição de fuso horário que ocorre no mesmo dia a cada ano.</span><span class="sxs-lookup"><span data-stu-id="78ebe-116">Represents a time zone transition that occurs on the same day each year.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="78ebe-117">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="78ebe-117">Text value</span></span>

<span data-ttu-id="78ebe-118">O valor de texto é um inteiro que representa a ocorrência do dia da semana no mês em que ocorre a transição de fuso horário.</span><span class="sxs-lookup"><span data-stu-id="78ebe-118">The text value is an integer that represents the occurrence of the day of the week in the month that the time zone transition occurs.</span></span> <span data-ttu-id="78ebe-119">A tabela a seguir lista os valores possíveis.</span><span class="sxs-lookup"><span data-stu-id="78ebe-119">The following table lists the possible values.</span></span>
  
|<span data-ttu-id="78ebe-120">**Valor**</span><span class="sxs-lookup"><span data-stu-id="78ebe-120">**Value**</span></span>|<span data-ttu-id="78ebe-121">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="78ebe-121">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="78ebe-122">1</span><span class="sxs-lookup"><span data-stu-id="78ebe-122">1</span></span>  <br/> |<span data-ttu-id="78ebe-123">A primeira ocorrência do dia da semana especificado desde o início do mês.</span><span class="sxs-lookup"><span data-stu-id="78ebe-123">The first occurrence of the specified day of the week from the beginning of the month.</span></span>  <br/> |
|<span data-ttu-id="78ebe-124">duas</span><span class="sxs-lookup"><span data-stu-id="78ebe-124">2</span></span>  <br/> |<span data-ttu-id="78ebe-125">A segunda ocorrência do dia da semana especificado desde o início do mês.</span><span class="sxs-lookup"><span data-stu-id="78ebe-125">The second occurrence of the specified day of the week from the beginning of the month.</span></span>  <br/> |
|<span data-ttu-id="78ebe-126">3D</span><span class="sxs-lookup"><span data-stu-id="78ebe-126">3</span></span>  <br/> |<span data-ttu-id="78ebe-127">A terceira ocorrência do dia da semana especificado desde o início do mês.</span><span class="sxs-lookup"><span data-stu-id="78ebe-127">The third occurrence of the specified day of the week from the beginning of the month.</span></span>  <br/> |
|<span data-ttu-id="78ebe-128">4 </span><span class="sxs-lookup"><span data-stu-id="78ebe-128">4</span></span>  <br/> |<span data-ttu-id="78ebe-129">A quarta ocorrência do dia da semana especificado desde o início do mês.</span><span class="sxs-lookup"><span data-stu-id="78ebe-129">The fourth occurrence of the specified day of the week from the beginning of the month.</span></span>  <br/> |
|<span data-ttu-id="78ebe-130">-1</span><span class="sxs-lookup"><span data-stu-id="78ebe-130">-1</span></span>  <br/> |<span data-ttu-id="78ebe-131">A primeira ocorrência do dia da semana especificado do final do mês.</span><span class="sxs-lookup"><span data-stu-id="78ebe-131">The first occurrence of the specified day of the week from the end of the month.</span></span>  <br/> |
|<span data-ttu-id="78ebe-132">-2</span><span class="sxs-lookup"><span data-stu-id="78ebe-132">-2</span></span>  <br/> |<span data-ttu-id="78ebe-133">A segunda ocorrência do dia da semana especificado do final do mês.</span><span class="sxs-lookup"><span data-stu-id="78ebe-133">The second occurrence of the specified day of the week from the end of the month.</span></span>  <br/> |
|<span data-ttu-id="78ebe-134">-3</span><span class="sxs-lookup"><span data-stu-id="78ebe-134">-3</span></span>  <br/> |<span data-ttu-id="78ebe-135">A terceira ocorrência do dia da semana especificado do final do mês.</span><span class="sxs-lookup"><span data-stu-id="78ebe-135">The third occurrence of the specified day of the week from the end of the month.</span></span>  <br/> |
|<span data-ttu-id="78ebe-136">-4</span><span class="sxs-lookup"><span data-stu-id="78ebe-136">-4</span></span>  <br/> |<span data-ttu-id="78ebe-137">A quarta ocorrência do dia da semana especificado do final do mês.</span><span class="sxs-lookup"><span data-stu-id="78ebe-137">The fourth occurrence of the specified day of the week from the end of the month.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="78ebe-138">Comentários</span><span class="sxs-lookup"><span data-stu-id="78ebe-138">Remarks</span></span>

<span data-ttu-id="78ebe-139">O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o Microsoft Exchange Server que tem a função de servidor de acesso para Cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="78ebe-139">The schema that describes this element is located in the EWS virtual directory of the computer that is running Microsoft Exchange Server that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="78ebe-140">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="78ebe-140">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="78ebe-141">Namespace</span><span class="sxs-lookup"><span data-stu-id="78ebe-141">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="78ebe-142">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="78ebe-142">Schema Name</span></span>  <br/> |<span data-ttu-id="78ebe-143">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="78ebe-143">Types schema</span></span>  <br/> |
|<span data-ttu-id="78ebe-144">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="78ebe-144">Validation File</span></span>  <br/> |<span data-ttu-id="78ebe-145">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="78ebe-145">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="78ebe-146">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="78ebe-146">Can be Empty</span></span>  <br/> |<span data-ttu-id="78ebe-147">False</span><span class="sxs-lookup"><span data-stu-id="78ebe-147">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="78ebe-148">Confira também</span><span class="sxs-lookup"><span data-stu-id="78ebe-148">See also</span></span>

- [<span data-ttu-id="78ebe-149">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="78ebe-149">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

