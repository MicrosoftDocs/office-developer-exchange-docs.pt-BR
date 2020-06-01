---
title: ContainsRecipientStrings
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- ContainsRecipientStrings
api_type:
- schema
ms.assetid: a7fd13ac-0f13-4610-ac9b-98e27ac3940b
description: O elemento ContainsRecipientStrings indica as cadeias de caracteres que devem aparecer nas propriedades ToRecipients ou CcRecipients de mensagens de entrada para que a condição ou exceção seja aplicada.
ms.openlocfilehash: ba717de6b3c53b37d12c4c0be8301083b2080c8b
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44458982"
---
# <a name="containsrecipientstrings"></a><span data-ttu-id="34202-103">ContainsRecipientStrings</span><span class="sxs-lookup"><span data-stu-id="34202-103">ContainsRecipientStrings</span></span>

<span data-ttu-id="34202-104">O elemento **ContainsRecipientStrings** indica as cadeias de caracteres que devem aparecer nas propriedades **ToRecipients** ou **CcRecipients** de mensagens de entrada para que a condição ou exceção seja aplicada.</span><span class="sxs-lookup"><span data-stu-id="34202-104">The **ContainsRecipientStrings** element indicates the strings that must appear in either the **ToRecipients** or **CcRecipients** properties of incoming messages in order for the condition or exception to apply.</span></span> 
  
```XML
<ContainsRecipientStrings>
    <String/>
</ContainsRecipientStrings>
```

 <span data-ttu-id="34202-105">**ArrayOfStringsType**</span><span class="sxs-lookup"><span data-stu-id="34202-105">**ArrayOfStringsType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="34202-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="34202-106">Attributes and elements</span></span>

<span data-ttu-id="34202-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="34202-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="34202-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="34202-108">Attributes</span></span>

<span data-ttu-id="34202-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="34202-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="34202-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="34202-110">Child elements</span></span>

|<span data-ttu-id="34202-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="34202-111">**Element**</span></span>|<span data-ttu-id="34202-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="34202-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="34202-113">String</span><span class="sxs-lookup"><span data-stu-id="34202-113">String</span></span>](string.md) <br/> |<span data-ttu-id="34202-114">Representa uma cadeia de caracteres que deve aparecer nas propriedades **ToRecipients** ou **CcRecipients** de mensagens de entrada para que a condição ou exceção seja aplicada.</span><span class="sxs-lookup"><span data-stu-id="34202-114">Represents a string that must appear in either the **ToRecipients** or **CcRecipients** properties of incoming messages in order for the condition or exception to apply.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="34202-115">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="34202-115">Parent elements</span></span>

|<span data-ttu-id="34202-116">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="34202-116">**Element**</span></span>|<span data-ttu-id="34202-117">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="34202-117">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="34202-118">Condições</span><span class="sxs-lookup"><span data-stu-id="34202-118">Conditions</span></span>](conditions.md) <br/> |<span data-ttu-id="34202-119">Representa as condições que, ao serem atendidas, acionarão as ações de regra para uma regra.</span><span class="sxs-lookup"><span data-stu-id="34202-119">Represents the conditions that, when fulfilled, will trigger the rule actions for a rule.</span></span>  <br/> |
|[<span data-ttu-id="34202-120">Exceções</span><span class="sxs-lookup"><span data-stu-id="34202-120">Exceptions</span></span>](exceptions.md) <br/> |<span data-ttu-id="34202-121">Representa as exceções que representam todas as condições de exceção de regra disponíveis para uma regra de caixa de entrada.</span><span class="sxs-lookup"><span data-stu-id="34202-121">Represents the exceptions that represent all the available rule exception conditions for an Inbox rule.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="34202-122">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="34202-122">Text value</span></span>

<span data-ttu-id="34202-123">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="34202-123">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="34202-124">Comentários</span><span class="sxs-lookup"><span data-stu-id="34202-124">Remarks</span></span>

<span data-ttu-id="34202-125">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="34202-125">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="34202-126">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="34202-126">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="34202-127">Namespace</span><span class="sxs-lookup"><span data-stu-id="34202-127">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="34202-128">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="34202-128">Schema Name</span></span>  <br/> |<span data-ttu-id="34202-129">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="34202-129">Messages schema</span></span>  <br/> |
|<span data-ttu-id="34202-130">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="34202-130">Validation File</span></span>  <br/> |<span data-ttu-id="34202-131">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="34202-131">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="34202-132">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="34202-132">Can be Empty</span></span>  <br/> |<span data-ttu-id="34202-133">Verdadeiro</span><span class="sxs-lookup"><span data-stu-id="34202-133">True</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="34202-134">Também consulte</span><span class="sxs-lookup"><span data-stu-id="34202-134">See also</span></span>



- [<span data-ttu-id="34202-135">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="34202-135">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

