---
title: EndDateRecurrence
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- EndDateRecurrence
api_type:
- schema
ms.assetid: a5ee2504-db84-49ee-870c-cca9269f2e26
description: O elemento EndDateRecurrence descreve a data de início e a data final do padrão de recorrência de um item.
ms.openlocfilehash: 73450bf69c6b122e806d85011975159e348ad740
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19752060"
---
# <a name="enddaterecurrence"></a><span data-ttu-id="beef5-103">EndDateRecurrence</span><span class="sxs-lookup"><span data-stu-id="beef5-103">EndDateRecurrence</span></span>

<span data-ttu-id="beef5-104">O elemento **EndDateRecurrence** descreve a data de início e a data final do padrão de recorrência de um item.</span><span class="sxs-lookup"><span data-stu-id="beef5-104">The **EndDateRecurrence** element describes the start date and the end date of an item recurrence pattern.</span></span> 
  
```xml
<EndDateRecurrence>
   <StartDate/>
   <EndDate/>
</EndDateRecurrence>
```

 <span data-ttu-id="beef5-105">**EndDateRecurrenceRangeType**</span><span class="sxs-lookup"><span data-stu-id="beef5-105">**EndDateRecurrenceRangeType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="beef5-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="beef5-106">Attributes and elements</span></span>

<span data-ttu-id="beef5-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="beef5-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="beef5-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="beef5-108">Attributes</span></span>

<span data-ttu-id="beef5-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="beef5-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="beef5-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="beef5-110">Child elements</span></span>

|<span data-ttu-id="beef5-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="beef5-111">**Element**</span></span>|<span data-ttu-id="beef5-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="beef5-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="beef5-113">StartDate (recorrência)</span><span class="sxs-lookup"><span data-stu-id="beef5-113">StartDate (Recurrence)</span></span>](startdate-recurrence.md) <br/> |<span data-ttu-id="beef5-114">Representa a data de início de uma tarefa recorrente ou item de calendário.</span><span class="sxs-lookup"><span data-stu-id="beef5-114">Represents the start date of a recurring task or calendar item.</span></span>  <br/> |
|[<span data-ttu-id="beef5-115">EndDate (recorrência)</span><span class="sxs-lookup"><span data-stu-id="beef5-115">EndDate (Recurrence)</span></span>](enddate-recurrence.md) <br/> |<span data-ttu-id="beef5-116">Representa a data de término de uma tarefa recorrente ou item de calendário.</span><span class="sxs-lookup"><span data-stu-id="beef5-116">Represents the end date of a recurring task or calendar item.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="beef5-117">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="beef5-117">Parent elements</span></span>

|<span data-ttu-id="beef5-118">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="beef5-118">**Element**</span></span>|<span data-ttu-id="beef5-119">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="beef5-119">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="beef5-120">Recorrência (RecurrenceType)</span><span class="sxs-lookup"><span data-stu-id="beef5-120">Recurrence (RecurrenceType)</span></span>](recurrence-recurrencetype.md) <br/> |<span data-ttu-id="beef5-121">Contém o padrão de recorrência para itens de calendário e solicitações de reunião.</span><span class="sxs-lookup"><span data-stu-id="beef5-121">Contains the recurrence pattern for calendar items and meeting requests.</span></span>  <br/> |
|[<span data-ttu-id="beef5-122">Recorrência (TaskRecurrenceType)</span><span class="sxs-lookup"><span data-stu-id="beef5-122">Recurrence (TaskRecurrenceType)</span></span>](recurrence-taskrecurrencetype.md) <br/> |<span data-ttu-id="beef5-123">Contém o padrão de recorrência para as tarefas recorrentes.</span><span class="sxs-lookup"><span data-stu-id="beef5-123">Contains the recurrence pattern for recurring tasks.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="beef5-124">Comentários</span><span class="sxs-lookup"><span data-stu-id="beef5-124">Remarks</span></span>

<span data-ttu-id="beef5-125">O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o MicrosoftExchange Server 2007 que tem instalada a função de servidor de Acesso para Cliente.</span><span class="sxs-lookup"><span data-stu-id="beef5-125">The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="beef5-126">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="beef5-126">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="beef5-127">Namespace</span><span class="sxs-lookup"><span data-stu-id="beef5-127">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="beef5-128">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="beef5-128">Schema name</span></span>  <br/> |<span data-ttu-id="beef5-129">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="beef5-129">Types schema</span></span>  <br/> |
|<span data-ttu-id="beef5-130">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="beef5-130">Validation file</span></span>  <br/> |<span data-ttu-id="beef5-131">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="beef5-131">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="beef5-132">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="beef5-132">Can be empty</span></span>  <br/> |<span data-ttu-id="beef5-133">False</span><span class="sxs-lookup"><span data-stu-id="beef5-133">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="beef5-134">Ver também</span><span class="sxs-lookup"><span data-stu-id="beef5-134">See also</span></span>



- [<span data-ttu-id="beef5-135">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="beef5-135">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

