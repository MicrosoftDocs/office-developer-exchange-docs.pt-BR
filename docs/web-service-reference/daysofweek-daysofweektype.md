---
title: DaysOfWeek (DaysOfWeekType)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- DaysOfWeek
api_type:
- schema
ms.assetid: c56f997d-28f3-4590-97b0-cb71f016dbe4
description: O elemento DaysOfWeek descreve os dias da semana que são usados em padrões de recorrência do item.
ms.openlocfilehash: 0b730ff5a7bc9aa6b324fc080022d056c5342296
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/25/2018
ms.locfileid: "19751713"
---
# <a name="daysofweek-daysofweektype"></a><span data-ttu-id="ef785-103">DaysOfWeek (DaysOfWeekType)</span><span class="sxs-lookup"><span data-stu-id="ef785-103">DaysOfWeek (DaysOfWeekType)</span></span>

<span data-ttu-id="ef785-104">O elemento **DaysOfWeek** descreve os dias da semana que são usados em padrões de recorrência do item.</span><span class="sxs-lookup"><span data-stu-id="ef785-104">The **DaysOfWeek** element describes days of the week that are used in item recurrence patterns.</span></span> 
  
```XML
<DaysOfWeek/>
```

<span data-ttu-id="ef785-105">**DaysOfWeekType**</span><span class="sxs-lookup"><span data-stu-id="ef785-105">**DaysOfWeekType**</span></span>

## <a name="attributes-and-elements"></a><span data-ttu-id="ef785-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="ef785-106">Attributes and elements</span></span>

<span data-ttu-id="ef785-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="ef785-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="ef785-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="ef785-108">Attributes</span></span>

<span data-ttu-id="ef785-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="ef785-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="ef785-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="ef785-110">Child elements</span></span>

<span data-ttu-id="ef785-111">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="ef785-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="ef785-112">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="ef785-112">Parent elements</span></span>

|<span data-ttu-id="ef785-113">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="ef785-113">**Element**</span></span>|<span data-ttu-id="ef785-114">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="ef785-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="ef785-115">WeeklyRecurrence</span><span class="sxs-lookup"><span data-stu-id="ef785-115">WeeklyRecurrence</span></span>](weeklyrecurrence.md) <br/> |<span data-ttu-id="ef785-116">Descreve um padrão de recorrência semanal.</span><span class="sxs-lookup"><span data-stu-id="ef785-116">Describes a weekly recurrence pattern.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="ef785-117">Text value</span><span class="sxs-lookup"><span data-stu-id="ef785-117">Text value</span></span>

<span data-ttu-id="ef785-118">É necessário um valor de texto.</span><span class="sxs-lookup"><span data-stu-id="ef785-118">A text value is required.</span></span> <span data-ttu-id="ef785-119">Veja a seguir os valores possíveis:</span><span class="sxs-lookup"><span data-stu-id="ef785-119">The following are the possible values:</span></span>
  
- <span data-ttu-id="ef785-120">Domingo</span><span class="sxs-lookup"><span data-stu-id="ef785-120">Sunday</span></span>    
- <span data-ttu-id="ef785-121">Segunda-feira</span><span class="sxs-lookup"><span data-stu-id="ef785-121">Monday</span></span>    
- <span data-ttu-id="ef785-122">Terça-feira</span><span class="sxs-lookup"><span data-stu-id="ef785-122">Tuesday</span></span>    
- <span data-ttu-id="ef785-123">Quarta-feira</span><span class="sxs-lookup"><span data-stu-id="ef785-123">Wednesday</span></span>    
- <span data-ttu-id="ef785-124">Quinta-feira</span><span class="sxs-lookup"><span data-stu-id="ef785-124">Thursday</span></span>    
- <span data-ttu-id="ef785-125">Sexta-feira</span><span class="sxs-lookup"><span data-stu-id="ef785-125">Friday</span></span>    
- <span data-ttu-id="ef785-126">Sábado</span><span class="sxs-lookup"><span data-stu-id="ef785-126">Saturday</span></span>    
- <span data-ttu-id="ef785-127">Dia (esse valor não é válido para um padrão de recorrência semanal)</span><span class="sxs-lookup"><span data-stu-id="ef785-127">Day (this value is not valid for a weekly recurrence pattern)</span></span>    
- <span data-ttu-id="ef785-128">Weekday (esse valor não é válido para um padrão de recorrência semanal)</span><span class="sxs-lookup"><span data-stu-id="ef785-128">Weekday (this value is not valid for a weekly recurrence pattern)</span></span>    
- <span data-ttu-id="ef785-129">WeekendDay (esse valor não é válido para um padrão de recorrência semanal)</span><span class="sxs-lookup"><span data-stu-id="ef785-129">WeekendDay (this value is not valid for a weekly recurrence pattern)</span></span>
    
<span data-ttu-id="ef785-130">Um padrão de recorrência semanal pode conter vários valores.</span><span class="sxs-lookup"><span data-stu-id="ef785-130">A weekly recurrence pattern can contain multiple values.</span></span> <span data-ttu-id="ef785-131">Valores são separados por um caractere de espaço.</span><span class="sxs-lookup"><span data-stu-id="ef785-131">Values are separated by a space character.</span></span> <span data-ttu-id="ef785-132">Por exemplo, para uma recorrência semanal às terças e quintas-feiras, o valor de texto será "Terça-feira quinta-feira".</span><span class="sxs-lookup"><span data-stu-id="ef785-132">For example, for a weekly recurrence on Tuesdays and Thursdays, the text value will be "Tuesday Thursday".</span></span>
  
## <a name="remarks"></a><span data-ttu-id="ef785-133">Comentários</span><span class="sxs-lookup"><span data-stu-id="ef785-133">Remarks</span></span>

<span data-ttu-id="ef785-134">O esquema que descreve este elemento está localizado no diretório virtual EWS do computador que está executando o Microsoft Exchange Server 2010 que tem a função de servidor acesso para cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="ef785-134">The schema that describes this element is located in the EWS virtual directory of the computer that is running Microsoft Exchange Server 2010 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="ef785-135">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="ef785-135">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="ef785-136">Namespace</span><span class="sxs-lookup"><span data-stu-id="ef785-136">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="ef785-137">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="ef785-137">Schema Name</span></span>  <br/> |<span data-ttu-id="ef785-138">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="ef785-138">Types schema</span></span>  <br/> |
|<span data-ttu-id="ef785-139">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="ef785-139">Validation File</span></span>  <br/> |<span data-ttu-id="ef785-140">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="ef785-140">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="ef785-141">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="ef785-141">Can be Empty</span></span>  <br/> |<span data-ttu-id="ef785-142">False</span><span class="sxs-lookup"><span data-stu-id="ef785-142">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="ef785-143">Ver também</span><span class="sxs-lookup"><span data-stu-id="ef785-143">See also</span></span>

- [<span data-ttu-id="ef785-144">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="ef785-144">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

