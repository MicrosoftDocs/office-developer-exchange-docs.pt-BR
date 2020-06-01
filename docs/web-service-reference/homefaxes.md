---
title: HomeFaxes
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: 459ddb1c-8cff-4125-b6fa-dc93c183dee8
description: O elemento HomeFaxes especifica uma matriz de números de fax residenciais e os identificadores de suas atribuições de origem para o persona associado.
ms.openlocfilehash: d49eb9e12547e4011e4ba403cb898c0fe6e9bf02
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44460845"
---
# <a name="homefaxes"></a><span data-ttu-id="2d628-103">HomeFaxes</span><span class="sxs-lookup"><span data-stu-id="2d628-103">HomeFaxes</span></span>

<span data-ttu-id="2d628-104">O elemento **HomeFaxes** especifica uma matriz de números de fax residenciais e os identificadores de suas atribuições de origem para o persona associado.</span><span class="sxs-lookup"><span data-stu-id="2d628-104">The **HomeFaxes** element specifies an array of home fax numbers and the identifiers of their source attributions for the associated persona.</span></span> 
  
```XML
<HomeFaxes>
    <PhoneNumberAttributedValue/>
</HomeFaxes>
```

 <span data-ttu-id="2d628-105">**ArrayOfPhoneNumberAttributedValuesType**</span><span class="sxs-lookup"><span data-stu-id="2d628-105">**ArrayOfPhoneNumberAttributedValuesType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="2d628-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="2d628-106">Attributes and elements</span></span>

<span data-ttu-id="2d628-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="2d628-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="2d628-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="2d628-108">Attributes</span></span>

<span data-ttu-id="2d628-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="2d628-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="2d628-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="2d628-110">Child elements</span></span>

|<span data-ttu-id="2d628-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="2d628-111">**Element**</span></span>|<span data-ttu-id="2d628-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="2d628-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="2d628-113">PhoneNumberAttributedValue</span><span class="sxs-lookup"><span data-stu-id="2d628-113">PhoneNumberAttributedValue</span></span>](phonenumberattributedvalue.md) <br/> |<span data-ttu-id="2d628-114">Contém um único número de telefone atribuído para uma pessoa.</span><span class="sxs-lookup"><span data-stu-id="2d628-114">Contains a single attributed phone number for a persona.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="2d628-115">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="2d628-115">Parent elements</span></span>

|<span data-ttu-id="2d628-116">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="2d628-116">**Element**</span></span>|<span data-ttu-id="2d628-117">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="2d628-117">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="2d628-118">Pessoal</span><span class="sxs-lookup"><span data-stu-id="2d628-118">Persona</span></span>](persona.md) <br/> |<span data-ttu-id="2d628-119">Especifica um conjunto de dados persona retornados por uma solicitação **Getpersona** .</span><span class="sxs-lookup"><span data-stu-id="2d628-119">Specifies a set of persona data returned by a **GetPersona** request.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="2d628-120">Comentários</span><span class="sxs-lookup"><span data-stu-id="2d628-120">Remarks</span></span>

<span data-ttu-id="2d628-121">Este elemento foi introduzido no Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="2d628-121">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="2d628-122">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="2d628-122">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="2d628-123">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="2d628-123">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="2d628-124">Namespace</span><span class="sxs-lookup"><span data-stu-id="2d628-124">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="2d628-125">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="2d628-125">Schema Name</span></span>  <br/> |<span data-ttu-id="2d628-126">Esquema de tipo</span><span class="sxs-lookup"><span data-stu-id="2d628-126">Type schema</span></span>  <br/> |
|<span data-ttu-id="2d628-127">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="2d628-127">Validation File</span></span>  <br/> |<span data-ttu-id="2d628-128">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="2d628-128">types.xsd</span></span>  <br/> |
|<span data-ttu-id="2d628-129">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="2d628-129">Can Be Empty</span></span>  <br/> ||
   
## <a name="see-also"></a><span data-ttu-id="2d628-130">Também consulte</span><span class="sxs-lookup"><span data-stu-id="2d628-130">See also</span></span>



- [<span data-ttu-id="2d628-131">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="2d628-131">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

