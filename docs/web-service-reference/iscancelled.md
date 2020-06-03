---
title: IsCanceled
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- IsCancelled
api_type:
- schema
ms.assetid: 50c1e97f-2913-47a1-8457-60428a3c5b92
description: O elemento IsCanceled indica se um compromisso ou uma reunião foi cancelado.
ms.openlocfilehash: 946c9d956da9cf31e9fa08d4ab6f4950b11214b9
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44455566"
---
# <a name="iscancelled"></a><span data-ttu-id="e5012-103">IsCanceled</span><span class="sxs-lookup"><span data-stu-id="e5012-103">IsCancelled</span></span>

<span data-ttu-id="e5012-104">O elemento **IsCanceled** indica se um compromisso ou uma reunião foi cancelado.</span><span class="sxs-lookup"><span data-stu-id="e5012-104">The **IsCancelled** element indicates whether an appointment or meeting has been canceled.</span></span> 
  
```xml
<IsCancelled/>
```

 <span data-ttu-id="e5012-105">**Boolean**</span><span class="sxs-lookup"><span data-stu-id="e5012-105">**Boolean**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="e5012-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="e5012-106">Attributes and elements</span></span>

<span data-ttu-id="e5012-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="e5012-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="e5012-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="e5012-108">Attributes</span></span>

<span data-ttu-id="e5012-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="e5012-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="e5012-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="e5012-110">Child elements</span></span>

<span data-ttu-id="e5012-111">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="e5012-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="e5012-112">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="e5012-112">Parent elements</span></span>

|<span data-ttu-id="e5012-113">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="e5012-113">**Element**</span></span>|<span data-ttu-id="e5012-114">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="e5012-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="e5012-115">CalendarItem</span><span class="sxs-lookup"><span data-stu-id="e5012-115">CalendarItem</span></span>](calendaritem.md) <br/> |<span data-ttu-id="e5012-116">Representa um item de calendário do Exchange.</span><span class="sxs-lookup"><span data-stu-id="e5012-116">Represents an Exchange calendar item.</span></span>  <br/> |
|[<span data-ttu-id="e5012-117">MeetingRequest</span><span class="sxs-lookup"><span data-stu-id="e5012-117">MeetingRequest</span></span>](meetingrequest.md) <br/> |<span data-ttu-id="e5012-118">Representa uma solicitação de reunião no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="e5012-118">Represents a meeting request in the Exchange store.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="e5012-119">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="e5012-119">Text value</span></span>

<span data-ttu-id="e5012-120">Um valor de texto que representa um valor booliano é necessário se esse elemento for incluído.</span><span class="sxs-lookup"><span data-stu-id="e5012-120">A text value that represents a Boolean value is required if this element is included.</span></span> <span data-ttu-id="e5012-121">Um valor **true** indica que o item de calendário foi cancelado.</span><span class="sxs-lookup"><span data-stu-id="e5012-121">A value of **true** indicates that the calendar item has been canceled.</span></span> <span data-ttu-id="e5012-122">Um valor **false** indica que um item de calendário não foi cancelado.</span><span class="sxs-lookup"><span data-stu-id="e5012-122">A value of **false** indicates that a calendar item has not been canceled.</span></span> 
  
## <a name="remarks"></a><span data-ttu-id="e5012-123">Comentários</span><span class="sxs-lookup"><span data-stu-id="e5012-123">Remarks</span></span>

<span data-ttu-id="e5012-124">O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o MicrosoftExchange Server 2007 que tem instalada a função de servidor de Acesso para Cliente.</span><span class="sxs-lookup"><span data-stu-id="e5012-124">The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="e5012-125">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="e5012-125">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="e5012-126">Namespace</span><span class="sxs-lookup"><span data-stu-id="e5012-126">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="e5012-127">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="e5012-127">Schema name</span></span>  <br/> |<span data-ttu-id="e5012-128">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="e5012-128">Types schema</span></span>  <br/> |
|<span data-ttu-id="e5012-129">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="e5012-129">Validation file</span></span>  <br/> |<span data-ttu-id="e5012-130">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="e5012-130">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="e5012-131">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="e5012-131">Can be empty</span></span>  <br/> |<span data-ttu-id="e5012-132">False</span><span class="sxs-lookup"><span data-stu-id="e5012-132">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="e5012-133">Confira também</span><span class="sxs-lookup"><span data-stu-id="e5012-133">See also</span></span>



- [<span data-ttu-id="e5012-134">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="e5012-134">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

