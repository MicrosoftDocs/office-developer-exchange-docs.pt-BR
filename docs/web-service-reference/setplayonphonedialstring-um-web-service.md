---
title: SetPlayOnPhoneDialString (serviço web de Unificação de mensagens)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
localization_priority: Normal
api_name:
- SetPlayOnPhoneDialString
api_type:
- schema
ms.assetid: 513a5072-c3ac-405f-98c2-0ab982d0a360
description: O elemento SetPlayOnPhoneDialString define uma solicitação para definir a sequência de discagem padrão para a operação de PlayOnPhone (serviço web de Unificação de mensagens) e PlayOnPhoneGreeting solicitações de operação (serviço web de Unificação de mensagens).
ms.openlocfilehash: fd82dc6ef0dd90a2318da93191f657005b7a5c87
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/25/2018
ms.locfileid: "19825450"
---
# <a name="setplayonphonedialstring-um-web-service"></a><span data-ttu-id="b0815-103">SetPlayOnPhoneDialString (serviço web de Unificação de mensagens)</span><span class="sxs-lookup"><span data-stu-id="b0815-103">SetPlayOnPhoneDialString (UM web service)</span></span>

<span data-ttu-id="b0815-104">O elemento de **SetPlayOnPhoneDialString** define uma solicitação para definir a sequência de discagem padrão para solicitações de [operação de PlayOnPhone (serviço web de Unificação de mensagens)](playonphone-operation-um-web-service.md) e [a operação de PlayOnPhoneGreeting (serviço web de Unificação de mensagens)](playonphonegreeting-operation-um-web-service.md) .</span><span class="sxs-lookup"><span data-stu-id="b0815-104">The **SetPlayOnPhoneDialString** element defines a request to set the default dial string for [PlayOnPhone operation (UM web service)](playonphone-operation-um-web-service.md) and [PlayOnPhoneGreeting operation (UM web service)](playonphonegreeting-operation-um-web-service.md) requests.</span></span> 
  
[<span data-ttu-id="b0815-105">SetPlayOnPhoneDialString (serviço web de Unificação de mensagens)</span><span class="sxs-lookup"><span data-stu-id="b0815-105">SetPlayOnPhoneDialString (UM web service)</span></span>](setplayonphonedialstring-um-web-service.md)
  
```xml
<SetPlayOnPhoneDialString>
  <dialString>   </dialString>
</SetPlayOnPhoneDialString>
```

 <span data-ttu-id="b0815-106">**complexType**</span><span class="sxs-lookup"><span data-stu-id="b0815-106">**complexType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="b0815-107">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="b0815-107">Attributes and elements</span></span>

<span data-ttu-id="b0815-108">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="b0815-108">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="b0815-109">Atributos</span><span class="sxs-lookup"><span data-stu-id="b0815-109">Attributes</span></span>

<span data-ttu-id="b0815-110">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="b0815-110">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="b0815-111">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="b0815-111">Child elements</span></span>

|<span data-ttu-id="b0815-112">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="b0815-112">**Element**</span></span>|<span data-ttu-id="b0815-113">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="b0815-113">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="b0815-114">dialString (serviço web de Unificação de mensagens)</span><span class="sxs-lookup"><span data-stu-id="b0815-114">dialString (UM web service)</span></span>](dialstring-um-web-service.md) <br/> |<span data-ttu-id="b0815-115">O número de telefone para definir como a cadeia de caracteres de discagem padrão.</span><span class="sxs-lookup"><span data-stu-id="b0815-115">The telephone number to set as the default dial string.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="b0815-116">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="b0815-116">Parent elements</span></span>

<span data-ttu-id="b0815-117">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="b0815-117">None.</span></span>
  
## <a name="text-value"></a><span data-ttu-id="b0815-118">Text value</span><span class="sxs-lookup"><span data-stu-id="b0815-118">Text value</span></span>

<span data-ttu-id="b0815-119">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="b0815-119">None.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="b0815-120">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="b0815-120">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="b0815-121">Namespace</span><span class="sxs-lookup"><span data-stu-id="b0815-121">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="b0815-122">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="b0815-122">Schema Name</span></span>  <br/> |<span data-ttu-id="b0815-123">Mensagens</span><span class="sxs-lookup"><span data-stu-id="b0815-123">Messages</span></span>  <br/> |
|<span data-ttu-id="b0815-124">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="b0815-124">Validation File</span></span>  <br/> |<span data-ttu-id="b0815-125">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="b0815-125">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="b0815-126">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="b0815-126">Can be Empty</span></span>  <br/> |<span data-ttu-id="b0815-127">False</span><span class="sxs-lookup"><span data-stu-id="b0815-127">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="b0815-128">Ver também</span><span class="sxs-lookup"><span data-stu-id="b0815-128">See also</span></span>



[<span data-ttu-id="b0815-129">Operação de SetPlayOnPhoneDialString (serviço web de Unificação de mensagens)</span><span class="sxs-lookup"><span data-stu-id="b0815-129">SetPlayOnPhoneDialString operation (UM web service)</span></span>](setplayonphonedialstring-operation-um-web-service.md)

