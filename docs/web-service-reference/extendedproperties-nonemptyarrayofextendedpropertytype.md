---
title: ExtendedProperties (NonEmptyArrayOfExtendedPropertyType)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: a7034730-210d-4916-b992-dda342f890f8
description: O elemento ExtendedProperties especifica uma matriz de propriedades adicionais.
ms.openlocfilehash: 36011e0252ed391daefab190d4da679fb3a3f856
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44463094"
---
# <a name="extendedproperties-nonemptyarrayofextendedpropertytype"></a><span data-ttu-id="992a0-103">ExtendedProperties (NonEmptyArrayOfExtendedPropertyType)</span><span class="sxs-lookup"><span data-stu-id="992a0-103">ExtendedProperties (NonEmptyArrayOfExtendedPropertyType)</span></span>

<span data-ttu-id="992a0-104">O elemento **ExtendedProperties** especifica uma matriz de propriedades adicionais.</span><span class="sxs-lookup"><span data-stu-id="992a0-104">The **ExtendedProperties** element specifies an array of additional properties.</span></span> 
  
```XML
<ExtendedProperties>
    <ExtendedProperty/>
</ExtendedProperties>
```

 <span data-ttu-id="992a0-105">**NonEmptyArrayOfExtendedPropertyType**</span><span class="sxs-lookup"><span data-stu-id="992a0-105">**NonEmptyArrayOfExtendedPropertyType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="992a0-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="992a0-106">Attributes and elements</span></span>

<span data-ttu-id="992a0-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="992a0-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="992a0-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="992a0-108">Attributes</span></span>

<span data-ttu-id="992a0-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="992a0-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="992a0-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="992a0-110">Child elements</span></span>

|<span data-ttu-id="992a0-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="992a0-111">**Element**</span></span>|<span data-ttu-id="992a0-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="992a0-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="992a0-113">ExtendedProperty</span><span class="sxs-lookup"><span data-stu-id="992a0-113">ExtendedProperty</span></span>](extendedproperty.md) <br/> |<span data-ttu-id="992a0-114">Identifica as propriedades de MAPI estendidas em pastas e itens.</span><span class="sxs-lookup"><span data-stu-id="992a0-114">Identifies extended MAPI properties on folders and items.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="992a0-115">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="992a0-115">Parent elements</span></span>

|<span data-ttu-id="992a0-116">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="992a0-116">**Element**</span></span>|<span data-ttu-id="992a0-117">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="992a0-117">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="992a0-118">Imgroup</span><span class="sxs-lookup"><span data-stu-id="992a0-118">ImGroup</span></span>](imgroup.md) <br/> |<span data-ttu-id="992a0-119">Representa um grupo de mensagens instantâneas.</span><span class="sxs-lookup"><span data-stu-id="992a0-119">Represents an instant messaging group.</span></span>  <br/> |
|[<span data-ttu-id="992a0-120">SearchPreviewItem</span><span class="sxs-lookup"><span data-stu-id="992a0-120">SearchPreviewItem</span></span>](searchpreviewitem.md) <br/> |<span data-ttu-id="992a0-121">Especifica os primeiros 256 caracteres de um item de caixa de correio para visualização sem abrir o item.</span><span class="sxs-lookup"><span data-stu-id="992a0-121">Specifies the first 256 characters of a mailbox item for preview without opening the item.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="992a0-122">Comentários</span><span class="sxs-lookup"><span data-stu-id="992a0-122">Remarks</span></span>

<span data-ttu-id="992a0-123">Este elemento foi introduzido no Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="992a0-123">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="992a0-124">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="992a0-124">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="992a0-125">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="992a0-125">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="992a0-126">Namespace</span><span class="sxs-lookup"><span data-stu-id="992a0-126">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="992a0-127">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="992a0-127">Schema Name</span></span>  <br/> |<span data-ttu-id="992a0-128">Esquema de tipo</span><span class="sxs-lookup"><span data-stu-id="992a0-128">Type schema</span></span>  <br/> |
|<span data-ttu-id="992a0-129">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="992a0-129">Validation File</span></span>  <br/> |<span data-ttu-id="992a0-130">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="992a0-130">types.xsd</span></span>  <br/> |
|<span data-ttu-id="992a0-131">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="992a0-131">Can Be Empty</span></span>  <br/> ||
   
## <a name="see-also"></a><span data-ttu-id="992a0-132">Confira também</span><span class="sxs-lookup"><span data-stu-id="992a0-132">See also</span></span>



- [<span data-ttu-id="992a0-133">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="992a0-133">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

