---
title: GroupBy
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- GroupBy
api_type:
- schema
ms.assetid: 9728619b-4674-4b9d-9f6c-e75c6165966c
description: O elemento GroupBy Especifica um agrupamento arbitrário para consultas FindItem.
ms.openlocfilehash: cdf9b9906025bc91768bb4a14acb2573801c4e12
ms.sourcegitcommit: 9061fcf40c218ebe88911783f357b7df278846db
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/28/2018
ms.locfileid: "21353214"
---
# <a name="groupby"></a><span data-ttu-id="cb768-103">GroupBy</span><span class="sxs-lookup"><span data-stu-id="cb768-103">GroupBy</span></span>

<span data-ttu-id="cb768-104">O elemento **GroupBy** Especifica um agrupamento arbitrário para consultas FindItem.</span><span class="sxs-lookup"><span data-stu-id="cb768-104">The **GroupBy** element specifies an arbitrary grouping for FindItem queries.</span></span> 
  
- [<span data-ttu-id="cb768-105">FindItem</span><span class="sxs-lookup"><span data-stu-id="cb768-105">FindItem</span></span>](finditem.md)
- [<span data-ttu-id="cb768-106">GroupBy</span><span class="sxs-lookup"><span data-stu-id="cb768-106">GroupBy</span></span>](groupby.md)
  
```xml
<GroupBy Order="">
   <FieldURI/>
   <AggregateOn/>
</GroupBy>
```

```xml
<GroupBy Order="">
   <ExtendededFieldURI/>
   <AggregateOn/>
</GroupBy>
```

```xml
<GroupBy Order="">
   <IndexedFieldURI/>
   <AggregateOn/>
</GroupBy>
```

<span data-ttu-id="cb768-107">**GroupByType**</span><span class="sxs-lookup"><span data-stu-id="cb768-107">**GroupByType**</span></span>

## <a name="attributes-and-elements"></a><span data-ttu-id="cb768-108">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="cb768-108">Attributes and elements</span></span>

<span data-ttu-id="cb768-109">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="cb768-109">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="cb768-110">Atributos</span><span class="sxs-lookup"><span data-stu-id="cb768-110">Attributes</span></span>

|<span data-ttu-id="cb768-111">**Attribute**</span><span class="sxs-lookup"><span data-stu-id="cb768-111">**Attribute**</span></span>|<span data-ttu-id="cb768-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="cb768-112">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="cb768-113">**Order**</span><span class="sxs-lookup"><span data-stu-id="cb768-113">**Order**</span></span> <br/> | <span data-ttu-id="cb768-114">Determina a ordem dos grupos da matriz de item agrupado que é retornado em tempo de resposta.</span><span class="sxs-lookup"><span data-stu-id="cb768-114">Determines the order of the groups in the grouped item array that is returned in the response.</span></span> <span data-ttu-id="cb768-115">Este atributo é do tipo SortDirectionType.</span><span class="sxs-lookup"><span data-stu-id="cb768-115">This attribute is of type SortDirectionType.</span></span>  <br/> |
   
#### <a name="order-attribute-values"></a><span data-ttu-id="cb768-116">Valores de atributos de ordem</span><span class="sxs-lookup"><span data-stu-id="cb768-116">Order attribute values</span></span>

|<span data-ttu-id="cb768-117">**Valor**</span><span class="sxs-lookup"><span data-stu-id="cb768-117">**Value**</span></span>|<span data-ttu-id="cb768-118">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="cb768-118">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="cb768-119">Crescente</span><span class="sxs-lookup"><span data-stu-id="cb768-119">Ascending</span></span>  <br/> |<span data-ttu-id="cb768-120">Os grupos são classificados em ordem crescente.</span><span class="sxs-lookup"><span data-stu-id="cb768-120">The groups are ordered in ascending order.</span></span>  <br/> |
|<span data-ttu-id="cb768-121">Decrescente</span><span class="sxs-lookup"><span data-stu-id="cb768-121">Descending</span></span>  <br/> |<span data-ttu-id="cb768-122">Os grupos são classificados em ordem decrescente.</span><span class="sxs-lookup"><span data-stu-id="cb768-122">The groups are ordered in descending order.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="cb768-123">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="cb768-123">Child elements</span></span>

|<span data-ttu-id="cb768-124">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="cb768-124">**Element**</span></span>|<span data-ttu-id="cb768-125">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="cb768-125">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="cb768-126">FieldURI</span><span class="sxs-lookup"><span data-stu-id="cb768-126">FieldURI</span></span>](fielduri.md) <br/> |<span data-ttu-id="cb768-127">Identifica as propriedades frequentemente referenciadas pelo URI.</span><span class="sxs-lookup"><span data-stu-id="cb768-127">Identifies frequently referenced properties by URI.</span></span>  <br/> |
|[<span data-ttu-id="cb768-128">IndexedFieldURI</span><span class="sxs-lookup"><span data-stu-id="cb768-128">IndexedFieldURI</span></span>](indexedfielduri.md) <br/> |<span data-ttu-id="cb768-129">Identifica a membros individuais de um dicionário.</span><span class="sxs-lookup"><span data-stu-id="cb768-129">Identifies individual members of a dictionary.</span></span>  <br/> |
|[<span data-ttu-id="cb768-130">ExtendedFieldURI</span><span class="sxs-lookup"><span data-stu-id="cb768-130">ExtendedFieldURI</span></span>](extendedfielduri.md) <br/> |<span data-ttu-id="cb768-131">Identifica as propriedades estendidas de MAPI para obter, definir ou criar.</span><span class="sxs-lookup"><span data-stu-id="cb768-131">Identifies extended MAPI properties to get, set, or create.</span></span>  <br/> |
|[<span data-ttu-id="cb768-132">AggregateOn</span><span class="sxs-lookup"><span data-stu-id="cb768-132">AggregateOn</span></span>](aggregateon.md) <br/> |<span data-ttu-id="cb768-133">Representa o campo que é usado para determinar a ordem dos grupos em uma resposta.</span><span class="sxs-lookup"><span data-stu-id="cb768-133">Represents the field that is used to determine the order of groups in a response.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="cb768-134">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="cb768-134">Parent elements</span></span>

|<span data-ttu-id="cb768-135">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="cb768-135">**Element**</span></span>|<span data-ttu-id="cb768-136">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="cb768-136">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="cb768-137">FindItem</span><span class="sxs-lookup"><span data-stu-id="cb768-137">FindItem</span></span>](finditem.md) <br/> |<span data-ttu-id="cb768-138">Define uma solicitação para localizar itens em uma caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="cb768-138">Defines a request to find items in a mailbox.</span></span>  <br/><br/> <span data-ttu-id="cb768-139">Este é a expressão XPath para esse elemento:`/FindItem`</span><span class="sxs-lookup"><span data-stu-id="cb768-139">The following is the XPath expression to this element:  `/FindItem`</span></span> <br/> |
   
## <a name="remarks"></a><span data-ttu-id="cb768-140">Comentários</span><span class="sxs-lookup"><span data-stu-id="cb768-140">Remarks</span></span>

<span data-ttu-id="cb768-141">A resposta FindItem conterá uma coleção dos grupos.</span><span class="sxs-lookup"><span data-stu-id="cb768-141">The FindItem response will contain a collection of groups.</span></span> <span data-ttu-id="cb768-142">Cada grupo conterá todos os itens que tiveram valores da propriedade **GroupBy** correspondentes.</span><span class="sxs-lookup"><span data-stu-id="cb768-142">Each group will contain all items that had matching values for the **GroupBy** property.</span></span> <span data-ttu-id="cb768-143">A propriedade que determina o agrupamento é identificada no elemento [FieldURI](fielduri.md), [IndexedFieldURI](indexedfielduri.md)ou [ExtendedFieldURI](extendedfielduri.md) .</span><span class="sxs-lookup"><span data-stu-id="cb768-143">The property that determines the grouping is identified in the [FieldURI](fielduri.md), [IndexedFieldURI](indexedfielduri.md), or [ExtendedFieldURI](extendedfielduri.md) element.</span></span> 
  
<span data-ttu-id="cb768-144">O esquema que descreve este elemento está localizado no diretório virtual EWS do computador que está executando o Microsoft Exchange Server 2007 que possui a função de servidor acesso para cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="cb768-144">The schema that describes this element is located in the EWS virtual directory of the computer that is running Microsoft Exchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="cb768-145">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="cb768-145">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="cb768-146">Namespace</span><span class="sxs-lookup"><span data-stu-id="cb768-146">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="cb768-147">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="cb768-147">Schema Name</span></span>  <br/> |<span data-ttu-id="cb768-148">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="cb768-148">Messages schema</span></span>  <br/> |
|<span data-ttu-id="cb768-149">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="cb768-149">Validation File</span></span>  <br/> |<span data-ttu-id="cb768-150">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="cb768-150">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="cb768-151">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="cb768-151">Can be Empty</span></span>  <br/> |<span data-ttu-id="cb768-152">False</span><span class="sxs-lookup"><span data-stu-id="cb768-152">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="cb768-153">Ver também</span><span class="sxs-lookup"><span data-stu-id="cb768-153">See also</span></span>

- [<span data-ttu-id="cb768-154">Operação FindItem</span><span class="sxs-lookup"><span data-stu-id="cb768-154">FindItem operation</span></span>](finditem-operation.md)
- [<span data-ttu-id="cb768-155">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="cb768-155">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
- [<span data-ttu-id="cb768-156">Localizando itens</span><span class="sxs-lookup"><span data-stu-id="cb768-156">Finding Items</span></span>](http://msdn.microsoft.com/library/63af1f9c-464b-4fca-9ae3-3d60f24ca93c%28Office.15%29.aspx)

