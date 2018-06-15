---
title: SetRuleOperation
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- SetRuleOperation
api_type:
- schema
ms.assetid: 2106a85b-58fe-49be-b71d-4ca6aa66e060
description: O elemento SetRuleOperation representa uma operação de atualização de uma regra existente.
ms.openlocfilehash: 9c956394d14c510e8dcc95110ef1874ea7010be0
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19825451"
---
# <a name="setruleoperation"></a><span data-ttu-id="0d31f-103">SetRuleOperation</span><span class="sxs-lookup"><span data-stu-id="0d31f-103">SetRuleOperation</span></span>

<span data-ttu-id="0d31f-104">O elemento **SetRuleOperation** representa uma operação de atualização de uma regra existente.</span><span class="sxs-lookup"><span data-stu-id="0d31f-104">The **SetRuleOperation** element represents an operation to update an existing rule.</span></span> 
  
[<span data-ttu-id="0d31f-105">UpdateInboxRules</span><span class="sxs-lookup"><span data-stu-id="0d31f-105">UpdateInboxRules</span></span>](updateinboxrules.md)
  
[<span data-ttu-id="0d31f-106">Operations</span><span class="sxs-lookup"><span data-stu-id="0d31f-106">Operations</span></span>](operations.md)
  
```XML
<SetRuleOperation>
    <Rule/>
</SetRuleOperation>
```

 <span data-ttu-id="0d31f-107">**SetRuleOperationType**</span><span class="sxs-lookup"><span data-stu-id="0d31f-107">**SetRuleOperationType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="0d31f-108">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="0d31f-108">Attributes and elements</span></span>

<span data-ttu-id="0d31f-109">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="0d31f-109">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="0d31f-110">Atributos</span><span class="sxs-lookup"><span data-stu-id="0d31f-110">Attributes</span></span>

<span data-ttu-id="0d31f-111">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="0d31f-111">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="0d31f-112">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="0d31f-112">Child elements</span></span>

|<span data-ttu-id="0d31f-113">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="0d31f-113">**Element**</span></span>|<span data-ttu-id="0d31f-114">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="0d31f-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="0d31f-115">Regra (RuleType)</span><span class="sxs-lookup"><span data-stu-id="0d31f-115">Rule (RuleType)</span></span>](rule-ruletype.md) <br/> |<span data-ttu-id="0d31f-116">Representa uma regra de caixa de correio do usuário.</span><span class="sxs-lookup"><span data-stu-id="0d31f-116">Represents a rule in a user's mailbox.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="0d31f-117">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="0d31f-117">Parent elements</span></span>

|<span data-ttu-id="0d31f-118">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="0d31f-118">**Element**</span></span>|<span data-ttu-id="0d31f-119">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="0d31f-119">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="0d31f-120">Operations</span><span class="sxs-lookup"><span data-stu-id="0d31f-120">Operations</span></span>](operations.md) <br/> |<span data-ttu-id="0d31f-121">Contém uma matriz das operações de regra que podem ser executadas em uma caixa de entrada.</span><span class="sxs-lookup"><span data-stu-id="0d31f-121">Contains an array of rule operations that can be performed on an Inbox.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="0d31f-122">Text value</span><span class="sxs-lookup"><span data-stu-id="0d31f-122">Text value</span></span>

<span data-ttu-id="0d31f-123">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="0d31f-123">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="0d31f-124">Comentários</span><span class="sxs-lookup"><span data-stu-id="0d31f-124">Remarks</span></span>

<span data-ttu-id="0d31f-125">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="0d31f-125">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="0d31f-126">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="0d31f-126">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="0d31f-127">Namespace</span><span class="sxs-lookup"><span data-stu-id="0d31f-127">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="0d31f-128">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="0d31f-128">Schema Name</span></span>  <br/> |<span data-ttu-id="0d31f-129">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="0d31f-129">Types schema</span></span>  <br/> |
|<span data-ttu-id="0d31f-130">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="0d31f-130">Validation File</span></span>  <br/> |<span data-ttu-id="0d31f-131">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="0d31f-131">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="0d31f-132">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="0d31f-132">Can be Empty</span></span>  <br/> |<span data-ttu-id="0d31f-133">False</span><span class="sxs-lookup"><span data-stu-id="0d31f-133">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="0d31f-134">Ver também</span><span class="sxs-lookup"><span data-stu-id="0d31f-134">See also</span></span>



[<span data-ttu-id="0d31f-135">UpdateInboxRules</span><span class="sxs-lookup"><span data-stu-id="0d31f-135">UpdateInboxRules</span></span>](updateinboxrules.md)
  
[<span data-ttu-id="0d31f-136">DeleteRuleOperation</span><span class="sxs-lookup"><span data-stu-id="0d31f-136">DeleteRuleOperation</span></span>](deleteruleoperation.md)
  
[<span data-ttu-id="0d31f-137">CreateRuleOperation</span><span class="sxs-lookup"><span data-stu-id="0d31f-137">CreateRuleOperation</span></span>](createruleoperation.md)


- [<span data-ttu-id="0d31f-138">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="0d31f-138">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
