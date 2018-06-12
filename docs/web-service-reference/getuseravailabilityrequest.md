---
title: GetUserAvailabilityRequest
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- GetUserAvailabilityRequest
api_type:
- schema
ms.assetid: 7906711b-80a1-42ae-8b33-26eeac036a5a
description: O elemento GetUserAvailabilityRequest contém os argumentos usados para obter informações de disponibilidade do usuário. Este é um elemento raiz.
ms.openlocfilehash: 5440f739b09bfbe27ad97cba99c08756686594f7
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19823683"
---
# <a name="getuseravailabilityrequest"></a><span data-ttu-id="1a27b-104">GetUserAvailabilityRequest</span><span class="sxs-lookup"><span data-stu-id="1a27b-104">GetUserAvailabilityRequest</span></span>

<span data-ttu-id="1a27b-105">O elemento **GetUserAvailabilityRequest** contém os argumentos usados para obter informações de disponibilidade do usuário.</span><span class="sxs-lookup"><span data-stu-id="1a27b-105">The **GetUserAvailabilityRequest** element contains the arguments used to obtain user availability information.</span></span> <span data-ttu-id="1a27b-106">Este é um elemento raiz.</span><span class="sxs-lookup"><span data-stu-id="1a27b-106">This is a root element.</span></span> 
  
```xml
<GetUserAvailabilityRequest>
   <TimeZone>...</TimeZone>
   <MailboxDataArray>...</MailboxDataArray>
   <FreeBusyViewOptions>...</FreeBusyViewOptions>
   <SuggestionsViewOptions>...</SuggestionsViewOptions>
</GetUserAvailabilityRequest>
```

 <span data-ttu-id="1a27b-107">**GetUserAvailabilityRequestType**</span><span class="sxs-lookup"><span data-stu-id="1a27b-107">**GetUserAvailabilityRequestType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="1a27b-108">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="1a27b-108">Attributes and elements</span></span>

<span data-ttu-id="1a27b-109">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="1a27b-109">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="1a27b-110">Atributos</span><span class="sxs-lookup"><span data-stu-id="1a27b-110">Attributes</span></span>

<span data-ttu-id="1a27b-111">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="1a27b-111">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="1a27b-112">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="1a27b-112">Child elements</span></span>

|<span data-ttu-id="1a27b-113">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="1a27b-113">**Element**</span></span>|<span data-ttu-id="1a27b-114">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="1a27b-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="1a27b-115">Fuso horário (disponibilidade)</span><span class="sxs-lookup"><span data-stu-id="1a27b-115">TimeZone (Availability)</span></span>](timezone-availability.md) <br/> |<span data-ttu-id="1a27b-116">Contém os elementos que identificam as informações de fuso horário.</span><span class="sxs-lookup"><span data-stu-id="1a27b-116">Contains elements that identify time zone information.</span></span> <span data-ttu-id="1a27b-117">Esse elemento também contém informações sobre a transição entre o período padrão e o horário de verão.</span><span class="sxs-lookup"><span data-stu-id="1a27b-117">This element also contains information about the transition between standard time and daylight saving time.</span></span>  <br/> |
|[<span data-ttu-id="1a27b-118">MailboxDataArray</span><span class="sxs-lookup"><span data-stu-id="1a27b-118">MailboxDataArray</span></span>](mailboxdataarray.md) <br/> |<span data-ttu-id="1a27b-119">Contém uma lista de caixas de correio para consultar informações sobre a disponibilidade.</span><span class="sxs-lookup"><span data-stu-id="1a27b-119">Contains a list of mailboxes to query for availability information.</span></span>  <br/> |
|[<span data-ttu-id="1a27b-120">FreeBusyViewOptions</span><span class="sxs-lookup"><span data-stu-id="1a27b-120">FreeBusyViewOptions</span></span>](freebusyviewoptions.md) <br/> |<span data-ttu-id="1a27b-121">Especifica o tipo de informações de disponibilidade retornadas na resposta.</span><span class="sxs-lookup"><span data-stu-id="1a27b-121">Specifies the type of free/busy information returned in the response.</span></span>  <br/> |
|[<span data-ttu-id="1a27b-122">SuggestionsViewOptions</span><span class="sxs-lookup"><span data-stu-id="1a27b-122">SuggestionsViewOptions</span></span>](suggestionsviewoptions.md) <br/> |<span data-ttu-id="1a27b-123">Contém as opções para a obtenção de informações de sugestão de reunião.</span><span class="sxs-lookup"><span data-stu-id="1a27b-123">Contains the options for obtaining meeting suggestion information.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="1a27b-124">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="1a27b-124">Parent elements</span></span>

<span data-ttu-id="1a27b-125">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="1a27b-125">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="1a27b-126">Comentários</span><span class="sxs-lookup"><span data-stu-id="1a27b-126">Remarks</span></span>

<span data-ttu-id="1a27b-127">O esquema que descreve este elemento está localizado no diretório /EWS/ do computador que está executando o Microsoft Exchange Server 2007 que possui a função de servidor acesso para cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="1a27b-127">The schema that describes this element is located in the /EWS/ directory of the computer that is running Microsoft Exchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="example"></a><span data-ttu-id="1a27b-128">Example</span><span class="sxs-lookup"><span data-stu-id="1a27b-128">Example</span></span>

<span data-ttu-id="1a27b-129">O exemplo a seguir mostra uma solicitação de informações de livre/ocupado.</span><span class="sxs-lookup"><span data-stu-id="1a27b-129">The following example shows a request for free/busy information.</span></span>
  
```
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
               xmlns:xsd="http://www.w3.org/2001/XMLSchema" 
               xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Body>
    <GetUserAvailabilityRequest xmlns="http://schemas.microsoft.com/exchange/services/2006/messages">
      <TimeZone xmlns="http://schemas.microsoft.com/exchange/services/2006/types">
        <Bias>480</Bias>
        <StandardTime>
          <Bias>0</Bias>
          <Time>02:00:00</Time>
          <DayOrder>5</DayOrder>
          <Month>10</Month>
          <DayOfWeek>Sunday</DayOfWeek>
        </StandardTime>
        <DaylightTime>
          <Bias>-60</Bias>
          <Time>02:00:00</Time>
          <DayOrder>1</DayOrder>
          <Month>4</Month>
          <DayOfWeek>Sunday</DayOfWeek>
        </DaylightTime>
      </TimeZone>
      <MailboxDataArray>
        <MailboxData xmlns="http://schemas.microsoft.com/exchange/services/2006/types">
          <Email>
            <Name></Name>
            <Address>someone@exchangeserver.example.com</Address>
            <RoutingType>SMTP</RoutingType>
          </Email>
          <AttendeeType>Organizer</AttendeeType>
          <ExcludeConflicts>false</ExcludeConflicts>
          <ExcludeNonWorkingHours>false</ExcludeNonWorkingHours>
        </MailboxData>
      </MailboxDataArray>
      <FreeBusyViewOptions xmlns="http://schemas.microsoft.com/exchange/services/2006/types">
        <TimeWindow>
          <StartTime>2006-02-06T00:00:00</StartTime>
          <EndTime>2006-02-30T23:59:59</EndTime>
        </TimeWindow>
        <MergedFreeBusyIntervalInMinutes>60</MergedFreeBusyIntervalInMinutes>
        <RequestedView>FreeBusyMerged</RequestedView>
      </FreeBusyViewOptions>
    </GetUserAvailabilityRequest>
  </soap:Body>
</soap:Envelope>
```

## <a name="element-information"></a><span data-ttu-id="1a27b-130">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="1a27b-130">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="1a27b-131">Namespace</span><span class="sxs-lookup"><span data-stu-id="1a27b-131">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="1a27b-132">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="1a27b-132">Schema Name</span></span>  <br/> |<span data-ttu-id="1a27b-133">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="1a27b-133">Messages schema</span></span>  <br/> |
|<span data-ttu-id="1a27b-134">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="1a27b-134">Validation File</span></span>  <br/> |<span data-ttu-id="1a27b-135">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="1a27b-135">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="1a27b-136">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="1a27b-136">Can be Empty</span></span>  <br/> |<span data-ttu-id="1a27b-137">False</span><span class="sxs-lookup"><span data-stu-id="1a27b-137">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="1a27b-138">Ver também</span><span class="sxs-lookup"><span data-stu-id="1a27b-138">See also</span></span>



[<span data-ttu-id="1a27b-139">Operação GetUserAvailability</span><span class="sxs-lookup"><span data-stu-id="1a27b-139">GetUserAvailability operation</span></span>](getuseravailability-operation.md)
  
[<span data-ttu-id="1a27b-140">GetUserAvailabilityResponse</span><span class="sxs-lookup"><span data-stu-id="1a27b-140">GetUserAvailabilityResponse</span></span>](getuseravailabilityresponse.md)


[<span data-ttu-id="1a27b-141">Obtenção de disponibilidade do usuário</span><span class="sxs-lookup"><span data-stu-id="1a27b-141">Getting User Availability</span></span>](http://msdn.microsoft.com/library/d4133fcb-9b0f-4e6b-aadf-a389da83516a%28Office.15%29.aspx)

