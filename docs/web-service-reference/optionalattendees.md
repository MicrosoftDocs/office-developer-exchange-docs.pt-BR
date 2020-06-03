---
title: OptionalAttendees
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- OptionalAttendees
api_type:
- schema
ms.assetid: e7c80c4d-3794-45e9-986f-6a8a687df0a4
description: O elemento OptionalAttendees representa os participantes que não precisam participar de uma reunião.
ms.openlocfilehash: 9eeff7151042f26fe5b00b43ec16a27946680a9f
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44468170"
---
# <a name="optionalattendees"></a><span data-ttu-id="c4616-103">OptionalAttendees</span><span class="sxs-lookup"><span data-stu-id="c4616-103">OptionalAttendees</span></span>

<span data-ttu-id="c4616-104">O elemento **OptionalAttendees** representa os participantes que não precisam participar de uma reunião.</span><span class="sxs-lookup"><span data-stu-id="c4616-104">The **OptionalAttendees** element represents attendees who are not required to attend a meeting.</span></span> 
  
```xml
<OptionalAttendees>
   <Attendee/>
</OptionalAttendees>
```

 <span data-ttu-id="c4616-105">**NonEmptyArrayOfAttendeesType**</span><span class="sxs-lookup"><span data-stu-id="c4616-105">**NonEmptyArrayOfAttendeesType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="c4616-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="c4616-106">Attributes and elements</span></span>

<span data-ttu-id="c4616-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="c4616-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="c4616-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="c4616-108">Attributes</span></span>

<span data-ttu-id="c4616-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="c4616-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="c4616-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="c4616-110">Child elements</span></span>

|<span data-ttu-id="c4616-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="c4616-111">**Element**</span></span>|<span data-ttu-id="c4616-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="c4616-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="c4616-113">Participante</span><span class="sxs-lookup"><span data-stu-id="c4616-113">Attendee</span></span>](attendee.md) <br/> |<span data-ttu-id="c4616-114">Representa participantes e recursos de uma reunião.</span><span class="sxs-lookup"><span data-stu-id="c4616-114">Represents attendees and resources for a meeting.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="c4616-115">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="c4616-115">Parent elements</span></span>

|<span data-ttu-id="c4616-116">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="c4616-116">**Element**</span></span>|<span data-ttu-id="c4616-117">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="c4616-117">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="c4616-118">CalendarItem</span><span class="sxs-lookup"><span data-stu-id="c4616-118">CalendarItem</span></span>](calendaritem.md) <br/> |<span data-ttu-id="c4616-119">Representa um item de calendário do Exchange.</span><span class="sxs-lookup"><span data-stu-id="c4616-119">Represents an Exchange calendar item.</span></span>  <br/> |
|[<span data-ttu-id="c4616-120">MeetingRequest</span><span class="sxs-lookup"><span data-stu-id="c4616-120">MeetingRequest</span></span>](meetingrequest.md) <br/> |<span data-ttu-id="c4616-121">Representa uma solicitação de reunião no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="c4616-121">Represents a meeting request in the Exchange store.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="c4616-122">Comentários</span><span class="sxs-lookup"><span data-stu-id="c4616-122">Remarks</span></span>

<span data-ttu-id="c4616-123">O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o MicrosoftExchange Server 2007 que tem instalada a função de servidor de Acesso para Cliente.</span><span class="sxs-lookup"><span data-stu-id="c4616-123">The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="c4616-124">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="c4616-124">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c4616-125">Namespace</span><span class="sxs-lookup"><span data-stu-id="c4616-125">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="c4616-126">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="c4616-126">Schema name</span></span>  <br/> |<span data-ttu-id="c4616-127">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="c4616-127">Types schema</span></span>  <br/> |
|<span data-ttu-id="c4616-128">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="c4616-128">Validation file</span></span>  <br/> |<span data-ttu-id="c4616-129">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="c4616-129">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="c4616-130">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="c4616-130">Can be empty</span></span>  <br/> |<span data-ttu-id="c4616-131">False</span><span class="sxs-lookup"><span data-stu-id="c4616-131">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="c4616-132">Confira também</span><span class="sxs-lookup"><span data-stu-id="c4616-132">See also</span></span>



- [<span data-ttu-id="c4616-133">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="c4616-133">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

