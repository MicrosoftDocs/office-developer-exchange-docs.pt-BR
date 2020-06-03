---
title: ResponseType
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- ResponseType
api_type:
- schema
ms.assetid: cdc09dda-ce20-4504-880d-9da6025ca812
description: O elemento ResponseType representa o tipo de resposta de destinatário que é recebido para uma reunião.
ms.openlocfilehash: ef8183b71e267a20427873ca44b269b828686cbe
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44465391"
---
# <a name="responsetype"></a><span data-ttu-id="ea722-103">ResponseType</span><span class="sxs-lookup"><span data-stu-id="ea722-103">ResponseType</span></span>

<span data-ttu-id="ea722-104">O elemento **ResponseType** representa o tipo de resposta de destinatário que é recebido para uma reunião.</span><span class="sxs-lookup"><span data-stu-id="ea722-104">The **ResponseType** element represents the type of recipient response that is received for a meeting.</span></span> 
  
```xml
<ResponseType/>
```

 <span data-ttu-id="ea722-105">**ResponseTypeType**</span><span class="sxs-lookup"><span data-stu-id="ea722-105">**ResponseTypeType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="ea722-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="ea722-106">Attributes and elements</span></span>

<span data-ttu-id="ea722-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="ea722-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="ea722-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="ea722-108">Attributes</span></span>

<span data-ttu-id="ea722-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="ea722-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="ea722-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="ea722-110">Child elements</span></span>

<span data-ttu-id="ea722-111">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="ea722-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="ea722-112">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="ea722-112">Parent elements</span></span>

|<span data-ttu-id="ea722-113">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="ea722-113">**Element**</span></span>|<span data-ttu-id="ea722-114">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="ea722-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="ea722-115">Participante</span><span class="sxs-lookup"><span data-stu-id="ea722-115">Attendee</span></span>](attendee.md) <br/> |<span data-ttu-id="ea722-116">Representa participantes e recursos de uma reunião.</span><span class="sxs-lookup"><span data-stu-id="ea722-116">Represents attendees and resources for a meeting.</span></span>  <br/> |
|[<span data-ttu-id="ea722-117">MeetingCancellation</span><span class="sxs-lookup"><span data-stu-id="ea722-117">MeetingCancellation</span></span>](meetingcancellation.md) <br/> |<span data-ttu-id="ea722-118">Representa um cancelamento de reunião no repositório do Exchange</span><span class="sxs-lookup"><span data-stu-id="ea722-118">Represents a meeting cancellation in the Exchange store</span></span>  <br/> |
|[<span data-ttu-id="ea722-119">MeetingMessage</span><span class="sxs-lookup"><span data-stu-id="ea722-119">MeetingMessage</span></span>](meetingmessage.md) <br/> |<span data-ttu-id="ea722-120">Representa uma mensagem de reunião no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="ea722-120">Represents a meeting message in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="ea722-121">MeetingRequest</span><span class="sxs-lookup"><span data-stu-id="ea722-121">MeetingRequest</span></span>](meetingrequest.md) <br/> |<span data-ttu-id="ea722-122">Representa uma solicitação de reunião no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="ea722-122">Represents a meeting request in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="ea722-123">MeetingResponse</span><span class="sxs-lookup"><span data-stu-id="ea722-123">MeetingResponse</span></span>](meetingresponse.md) <br/> |<span data-ttu-id="ea722-124">Representa uma resposta de reunião no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="ea722-124">Represents a meeting response in the Exchange store.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="ea722-125">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="ea722-125">Text value</span></span>

<span data-ttu-id="ea722-126">Um valor de texto é obrigatório.</span><span class="sxs-lookup"><span data-stu-id="ea722-126">A text value is required.</span></span> <span data-ttu-id="ea722-127">Estes são os valores de texto possíveis para este elemento:</span><span class="sxs-lookup"><span data-stu-id="ea722-127">The following are the possible text values for this element:</span></span>
  
- <span data-ttu-id="ea722-128">Desconhecido</span><span class="sxs-lookup"><span data-stu-id="ea722-128">Unknown</span></span>
    
- <span data-ttu-id="ea722-129">Organizador</span><span class="sxs-lookup"><span data-stu-id="ea722-129">Organizer</span></span>
    
- <span data-ttu-id="ea722-130">Provisória</span><span class="sxs-lookup"><span data-stu-id="ea722-130">Tentative</span></span>
    
- <span data-ttu-id="ea722-131">Aceitar</span><span class="sxs-lookup"><span data-stu-id="ea722-131">Accept</span></span>
    
- <span data-ttu-id="ea722-132">Aceito</span><span class="sxs-lookup"><span data-stu-id="ea722-132">Decline</span></span>
    
- <span data-ttu-id="ea722-133">NoResponseReceived</span><span class="sxs-lookup"><span data-stu-id="ea722-133">NoResponseReceived</span></span>
    
## <a name="remarks"></a><span data-ttu-id="ea722-134">Comentários</span><span class="sxs-lookup"><span data-stu-id="ea722-134">Remarks</span></span>

<span data-ttu-id="ea722-135">O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o Microsoft Exchange Server 2007 que tem a função de servidor de acesso para Cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="ea722-135">The schema that describes this element is located in the EWS virtual directory of the computer that is running Microsoft Exchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="ea722-136">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="ea722-136">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="ea722-137">Namespace</span><span class="sxs-lookup"><span data-stu-id="ea722-137">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="ea722-138">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="ea722-138">Schema Name</span></span>  <br/> |<span data-ttu-id="ea722-139">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="ea722-139">Types schema</span></span>  <br/> |
|<span data-ttu-id="ea722-140">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="ea722-140">Validation File</span></span>  <br/> |<span data-ttu-id="ea722-141">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="ea722-141">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="ea722-142">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="ea722-142">Can be Empty</span></span>  <br/> |<span data-ttu-id="ea722-143">False</span><span class="sxs-lookup"><span data-stu-id="ea722-143">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="ea722-144">Confira também</span><span class="sxs-lookup"><span data-stu-id="ea722-144">See also</span></span>



- [<span data-ttu-id="ea722-145">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="ea722-145">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

