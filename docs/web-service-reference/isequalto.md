---
title: IsEqualTo
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- IsEqualTo
api_type:
- schema
ms.assetid: 48e7e067-049c-4184-8026-071e6f558e8a
description: O elemento IsEqualTo representa uma expressão de pesquisa que compara uma propriedade com a um valor de constante ou outra propriedade e retornará true se eles forem iguais.
ms.openlocfilehash: a7a7deed79c271be74bb2ff16dd86605d468721b
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19824013"
---
# <a name="isequalto"></a><span data-ttu-id="34b77-103">IsEqualTo</span><span class="sxs-lookup"><span data-stu-id="34b77-103">IsEqualTo</span></span>

<span data-ttu-id="34b77-104">O elemento **IsEqualTo** representa uma expressão de pesquisa que compara uma propriedade com a um valor de constante ou outra propriedade e retornará true se eles forem iguais.</span><span class="sxs-lookup"><span data-stu-id="34b77-104">The **IsEqualTo** element represents a search expression that compares a property with either a constant value or another property and evaluates to true if they are equal.</span></span> 
  
```xml
<IsEqualTo>
   <FieldURI/>
   <FieldURIOrConstant/>
</IsEqualTo>
```

 <span data-ttu-id="34b77-105">**IsEqualToType**</span><span class="sxs-lookup"><span data-stu-id="34b77-105">**IsEqualToType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="34b77-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="34b77-106">Attributes and elements</span></span>

<span data-ttu-id="34b77-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="34b77-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="34b77-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="34b77-108">Attributes</span></span>

<span data-ttu-id="34b77-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="34b77-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="34b77-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="34b77-110">Child elements</span></span>

|<span data-ttu-id="34b77-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="34b77-111">**Element**</span></span>|<span data-ttu-id="34b77-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="34b77-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="34b77-113">FieldURI</span><span class="sxs-lookup"><span data-stu-id="34b77-113">FieldURI</span></span>](fielduri.md) <br/> |<span data-ttu-id="34b77-114">Identifica as propriedades frequentemente referenciadas pelo URI.</span><span class="sxs-lookup"><span data-stu-id="34b77-114">Identifies frequently referenced properties by URI.</span></span>  <br/> |
|[<span data-ttu-id="34b77-115">IndexedFieldURI</span><span class="sxs-lookup"><span data-stu-id="34b77-115">IndexedFieldURI</span></span>](indexedfielduri.md) <br/> |<span data-ttu-id="34b77-116">Identifica a membros individuais de um dicionário.</span><span class="sxs-lookup"><span data-stu-id="34b77-116">Identifies individual members of a dictionary.</span></span>  <br/> |
|[<span data-ttu-id="34b77-117">ExtendedFieldURI</span><span class="sxs-lookup"><span data-stu-id="34b77-117">ExtendedFieldURI</span></span>](extendedfielduri.md) <br/> |<span data-ttu-id="34b77-118">Identifica as propriedades MAPI.</span><span class="sxs-lookup"><span data-stu-id="34b77-118">Identifies MAPI properties.</span></span>  <br/> |
|[<span data-ttu-id="34b77-119">FieldURIOrConstant</span><span class="sxs-lookup"><span data-stu-id="34b77-119">FieldURIOrConstant</span></span>](fielduriorconstant.md) <br/> |<span data-ttu-id="34b77-120">Representa uma propriedade ou um valor de constante a ser usado ao comparar com outra propriedade.</span><span class="sxs-lookup"><span data-stu-id="34b77-120">Represents either a property or a constant value to be used when comparing with another property.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="34b77-121">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="34b77-121">Parent elements</span></span>

|<span data-ttu-id="34b77-122">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="34b77-122">**Element**</span></span>|<span data-ttu-id="34b77-123">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="34b77-123">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="34b77-124">Restriction</span><span class="sxs-lookup"><span data-stu-id="34b77-124">Restriction</span></span>](restriction.md) <br/> |<span data-ttu-id="34b77-125">Representa a restrição ou a consulta que é usada para filtrar itens ou pastas nas operações da pasta FindItem/FindFolder e pesquisa.</span><span class="sxs-lookup"><span data-stu-id="34b77-125">Represents the restriction or query that is used to filter items or folders in FindItem/FindFolder and search folder operations.</span></span>  <br/> |
|[<span data-ttu-id="34b77-126">Não</span><span class="sxs-lookup"><span data-stu-id="34b77-126">Not</span></span>](not.md) <br/> |<span data-ttu-id="34b77-127">Representa uma expressão de pesquisa que dispensa o valor booliano da expressão de pesquisa que ele contém.</span><span class="sxs-lookup"><span data-stu-id="34b77-127">Represents a search expression that negates the Boolean value of the search expression that it contains.</span></span>  <br/> |
|[<span data-ttu-id="34b77-128">E</span><span class="sxs-lookup"><span data-stu-id="34b77-128">And</span></span>](and.md) <br/> |<span data-ttu-id="34b77-129">Representa uma expressão de pesquisa que permite realizar uma operação Boolean e entre dois ou mais expressões de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="34b77-129">Represents a search expression that allows you to perform a Boolean And operation between two or more search expressions.</span></span> <span data-ttu-id="34b77-130">O resultado da operação e será **true** se todas as expressões de pesquisa contidas And forem **verdadeiras**.</span><span class="sxs-lookup"><span data-stu-id="34b77-130">The result of the And operation is **true** if all of the search expressions contained within the And are **true**.</span></span>  <br/> |
|[<span data-ttu-id="34b77-131">Ou</span><span class="sxs-lookup"><span data-stu-id="34b77-131">Or</span></span>](or.md) <br/> |<span data-ttu-id="34b77-132">Representa uma expressão de pesquisa que realiza um OR lógico a expressão de pesquisa que ele contém.</span><span class="sxs-lookup"><span data-stu-id="34b77-132">Represents a search expression that performs a logical OR on the search expression that it contains.</span></span> <span data-ttu-id="34b77-133">[Ou](or.md) retornará true se qualquer um dos seus filhos retornam true.</span><span class="sxs-lookup"><span data-stu-id="34b77-133">[Or](or.md) will return true if any of its children return true.</span></span> <span data-ttu-id="34b77-134">**Ou** deve ter dois ou mais filhos.</span><span class="sxs-lookup"><span data-stu-id="34b77-134">**Or** must have two or more children.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="34b77-135">Coment�rios</span><span class="sxs-lookup"><span data-stu-id="34b77-135">Remarks</span></span>

<span data-ttu-id="34b77-136">Para executar comparações de sequência de caracteres, considere o uso do elemento [contém](contains.md) , como ele fornece opções para os parâmetros correspondentes, como caso e espaços em branco.</span><span class="sxs-lookup"><span data-stu-id="34b77-136">To perform string comparisons, consider using the [Contains](contains.md) element, as it provides options for matching parameters, such as case and white space.</span></span> <span data-ttu-id="34b77-137">Use o elemento [não](not.md) em conjunto com o elemento [contém](contains.md) para negar o resultado.</span><span class="sxs-lookup"><span data-stu-id="34b77-137">Use the [Not](not.md) element in conjunction with the [Contains](contains.md) element to negate the result.</span></span> 
  
<span data-ttu-id="34b77-138">O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o MicrosoftExchange Server 2007 que tem instalada a função de servidor de Acesso para Cliente.</span><span class="sxs-lookup"><span data-stu-id="34b77-138">The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="34b77-139">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="34b77-139">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="34b77-140">Namespace</span><span class="sxs-lookup"><span data-stu-id="34b77-140">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="34b77-141">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="34b77-141">Schema Name</span></span>  <br/> |<span data-ttu-id="34b77-142">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="34b77-142">Types schema</span></span>  <br/> |
|<span data-ttu-id="34b77-143">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="34b77-143">Validation File</span></span>  <br/> |<span data-ttu-id="34b77-144">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="34b77-144">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="34b77-145">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="34b77-145">Can be Empty</span></span>  <br/> |<span data-ttu-id="34b77-146">False</span><span class="sxs-lookup"><span data-stu-id="34b77-146">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="34b77-147">Ver também</span><span class="sxs-lookup"><span data-stu-id="34b77-147">See also</span></span>



- [<span data-ttu-id="34b77-148">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="34b77-148">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
