---
title: ItemHoldPeriod
manager: sethgros
ms.date: 03/9/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: 30369db5-4d45-40e8-bc83-3236667fc404
description: O elemento ItemHoldPeriod especifica a quantidade de tempo para armazenar o conteúdo que corresponde à consulta de caixa de correio.
ms.openlocfilehash: 185666b72cc96dd88605b7baa6433d070e7ebc91
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44452283"
---
# <a name="itemholdperiod"></a><span data-ttu-id="06e18-103">ItemHoldPeriod</span><span class="sxs-lookup"><span data-stu-id="06e18-103">ItemHoldPeriod</span></span>

<span data-ttu-id="06e18-104">O elemento **ItemHoldPeriod** especifica a quantidade de tempo para armazenar o conteúdo que corresponde à consulta de caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="06e18-104">The **ItemHoldPeriod** element specifies the amount of time to hold content that matches the mailbox query.</span></span> 
  
```XML
<ItemHoldPeriod/>
```

 <span data-ttu-id="06e18-105">**cadeia de caracteres**</span><span class="sxs-lookup"><span data-stu-id="06e18-105">**string**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="06e18-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="06e18-106">Attributes and elements</span></span>

<span data-ttu-id="06e18-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="06e18-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="06e18-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="06e18-108">Attributes</span></span>

<span data-ttu-id="06e18-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="06e18-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="06e18-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="06e18-110">Child elements</span></span>

<span data-ttu-id="06e18-111">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="06e18-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="06e18-112">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="06e18-112">Parent elements</span></span>

[<span data-ttu-id="06e18-113">SetHoldOnMailboxes</span><span class="sxs-lookup"><span data-stu-id="06e18-113">SetHoldOnMailboxes</span></span>](setholdonmailboxes.md)
  
## <a name="text-value"></a><span data-ttu-id="06e18-114">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="06e18-114">Text value</span></span>

<span data-ttu-id="06e18-115">O valor de texto pode ser "Unlimited" ou o valor da cadeia de caracteres de qualquer valor [TimeSpan](https://msdn.microsoft.com/library/1ecy8h51%28v=vs.110%29.aspx) .</span><span class="sxs-lookup"><span data-stu-id="06e18-115">The text value can be "Unlimited" or the string value of any [Timespan](https://msdn.microsoft.com/library/1ecy8h51%28v=vs.110%29.aspx) value.</span></span> 
  
## <a name="remarks"></a><span data-ttu-id="06e18-116">Comentários</span><span class="sxs-lookup"><span data-stu-id="06e18-116">Remarks</span></span>

<span data-ttu-id="06e18-117">Este elemento foi introduzido no Exchange Server 2013 Service Pack 1 (SP1).</span><span class="sxs-lookup"><span data-stu-id="06e18-117">This element was introduced in Exchange Server 2013 Service Pack 1 (SP1).</span></span>
  
<span data-ttu-id="06e18-118">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="06e18-118">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="06e18-119">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="06e18-119">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="06e18-120">Namespace</span><span class="sxs-lookup"><span data-stu-id="06e18-120">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="06e18-121">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="06e18-121">Schema Name</span></span>  <br/> |<span data-ttu-id="06e18-122">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="06e18-122">Messages schema</span></span>  <br/> |
|<span data-ttu-id="06e18-123">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="06e18-123">Validation File</span></span>  <br/> |<span data-ttu-id="06e18-124">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="06e18-124">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="06e18-125">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="06e18-125">Can be Empty</span></span>  <br/> |<span data-ttu-id="06e18-126">Verdadeiro</span><span class="sxs-lookup"><span data-stu-id="06e18-126">True</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="06e18-127">Confira também</span><span class="sxs-lookup"><span data-stu-id="06e18-127">See also</span></span>



[<span data-ttu-id="06e18-128">SetHoldOnMailboxes</span><span class="sxs-lookup"><span data-stu-id="06e18-128">SetHoldOnMailboxes</span></span>](setholdonmailboxes.md)


- [<span data-ttu-id="06e18-129">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="06e18-129">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

