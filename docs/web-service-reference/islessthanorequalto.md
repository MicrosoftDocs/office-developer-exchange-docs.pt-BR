---
title: IsLessThanOrEqualTo
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- IsLessThanOrEqualTo
api_type:
- schema
ms.assetid: b5d85eb2-5e15-4d01-ad49-6289e735ad8a
description: O elemento IsLessThanOrEqualTo representa uma expressão de pesquisa que compara uma propriedade com a um valor de constante ou outra propriedade e retorna true se a primeira propriedade for menor ou igual à segunda.
ms.openlocfilehash: 9aeb688ec68e13635ac3083119899bcd55045f7a
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19824043"
---
# <a name="islessthanorequalto"></a><span data-ttu-id="84c42-103">IsLessThanOrEqualTo</span><span class="sxs-lookup"><span data-stu-id="84c42-103">IsLessThanOrEqualTo</span></span>

<span data-ttu-id="84c42-104">O elemento **IsLessThanOrEqualTo** representa uma expressão de pesquisa que compara uma propriedade com um valor de constante ou outra propriedade e retorna **true** se a primeira propriedade for menor ou igual à segunda.</span><span class="sxs-lookup"><span data-stu-id="84c42-104">The **IsLessThanOrEqualTo** element represents a search expression that compares a property with either a constant value or another property and returns **true** if the first property is less than or equal to the second.</span></span> 
  
```xml
<IsLessThanOrEqualTo>
   <FieldURI/>
   <FieldURIOrConstant/>
</IsLessThanOrEqualTo>
```

 <span data-ttu-id="84c42-105">**IsLessThanOrEqualToType**</span><span class="sxs-lookup"><span data-stu-id="84c42-105">**IsLessThanOrEqualToType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="84c42-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="84c42-106">Attributes and elements</span></span>

<span data-ttu-id="84c42-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="84c42-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="84c42-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="84c42-108">Attributes</span></span>

<span data-ttu-id="84c42-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="84c42-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="84c42-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="84c42-110">Child elements</span></span>

|<span data-ttu-id="84c42-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="84c42-111">**Element**</span></span>|<span data-ttu-id="84c42-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="84c42-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="84c42-113">FieldURI</span><span class="sxs-lookup"><span data-stu-id="84c42-113">FieldURI</span></span>](fielduri.md) <br/> |<span data-ttu-id="84c42-114">Identifica as propriedades frequentemente referenciadas pelo URI.</span><span class="sxs-lookup"><span data-stu-id="84c42-114">Identifies frequently referenced properties by URI.</span></span>  <br/> |
|[<span data-ttu-id="84c42-115">IndexedFieldURI</span><span class="sxs-lookup"><span data-stu-id="84c42-115">IndexedFieldURI</span></span>](indexedfielduri.md) <br/> |<span data-ttu-id="84c42-116">Identifica a membros individuais de um dicionário.</span><span class="sxs-lookup"><span data-stu-id="84c42-116">Identifies individual members of a dictionary.</span></span>  <br/> |
|[<span data-ttu-id="84c42-117">ExtendedFieldURI</span><span class="sxs-lookup"><span data-stu-id="84c42-117">ExtendedFieldURI</span></span>](extendedfielduri.md) <br/> |<span data-ttu-id="84c42-118">Identifica as propriedades MAPI.</span><span class="sxs-lookup"><span data-stu-id="84c42-118">Identifies MAPI properties.</span></span>  <br/> |
|[<span data-ttu-id="84c42-119">FieldURIOrConstant</span><span class="sxs-lookup"><span data-stu-id="84c42-119">FieldURIOrConstant</span></span>](fielduriorconstant.md) <br/> |<span data-ttu-id="84c42-120">Representa uma propriedade ou um valor de constante a ser usado ao comparar com outra propriedade.</span><span class="sxs-lookup"><span data-stu-id="84c42-120">Represents either a property or a constant value to be used when comparing with another property.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="84c42-121">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="84c42-121">Parent elements</span></span>

|<span data-ttu-id="84c42-122">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="84c42-122">**Element**</span></span>|<span data-ttu-id="84c42-123">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="84c42-123">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="84c42-124">Restriction</span><span class="sxs-lookup"><span data-stu-id="84c42-124">Restriction</span></span>](restriction.md) <br/> |<span data-ttu-id="84c42-125">Representa a restrição ou a consulta que é usada para filtrar itens ou pastas nas operações da pasta FindItem/FindFolder e pesquisa.</span><span class="sxs-lookup"><span data-stu-id="84c42-125">Represents the restriction or query that is used to filter items or folders in FindItem/FindFolder and search folder operations.</span></span>  <br/> |
|[<span data-ttu-id="84c42-126">Não</span><span class="sxs-lookup"><span data-stu-id="84c42-126">Not</span></span>](not.md) <br/> |<span data-ttu-id="84c42-127">Representa uma expressão de pesquisa que dispensa o valor booliano da expressão de pesquisa que ele contém.</span><span class="sxs-lookup"><span data-stu-id="84c42-127">Represents a search expression that negates the Boolean value of the search expression it contains.</span></span>  <br/> |
|[<span data-ttu-id="84c42-128">E</span><span class="sxs-lookup"><span data-stu-id="84c42-128">And</span></span>](and.md) <br/> |<span data-ttu-id="84c42-129">Representa uma expressão de pesquisa que permite realizar uma operação Boolean e entre dois ou mais expressões de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="84c42-129">Represents a search expression that enables you to perform a Boolean And operation between two or more search expressions.</span></span> <span data-ttu-id="84c42-130">O resultado da operação e será **true** se todas as expressões de pesquisa contidas And forem **verdadeiras**.</span><span class="sxs-lookup"><span data-stu-id="84c42-130">The result of the And operation is **true** if all of the search expressions contained within the And are **true**.</span></span>  <br/> |
|[<span data-ttu-id="84c42-131">Ou</span><span class="sxs-lookup"><span data-stu-id="84c42-131">Or</span></span>](or.md) <br/> |<span data-ttu-id="84c42-132">Representa uma expressão de pesquisa que realiza um OR lógico a expressão de pesquisa que ele contém.</span><span class="sxs-lookup"><span data-stu-id="84c42-132">Represents a search expression that performs a logical OR on the search expression it contains.</span></span> <span data-ttu-id="84c42-133">[Ou](or.md) retornará **true** se qualquer um dos seus filhos retornam true.</span><span class="sxs-lookup"><span data-stu-id="84c42-133">[Or](or.md) will return **true** if any of its children return true.</span></span> <span data-ttu-id="84c42-134">[Ou](or.md) deve ter dois ou mais filhos.</span><span class="sxs-lookup"><span data-stu-id="84c42-134">[Or](or.md) must have two or more children.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="84c42-135">Comentários</span><span class="sxs-lookup"><span data-stu-id="84c42-135">Remarks</span></span>

<span data-ttu-id="84c42-136">O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o MicrosoftExchange Server 2007 que tem instalada a função de servidor de Acesso para Cliente.</span><span class="sxs-lookup"><span data-stu-id="84c42-136">The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="84c42-137">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="84c42-137">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="84c42-138">Namespace</span><span class="sxs-lookup"><span data-stu-id="84c42-138">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="84c42-139">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="84c42-139">Schema Name</span></span>  <br/> |<span data-ttu-id="84c42-140">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="84c42-140">Types schema</span></span>  <br/> |
|<span data-ttu-id="84c42-141">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="84c42-141">Validation File</span></span>  <br/> |<span data-ttu-id="84c42-142">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="84c42-142">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="84c42-143">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="84c42-143">Can be Empty</span></span>  <br/> |<span data-ttu-id="84c42-144">False</span><span class="sxs-lookup"><span data-stu-id="84c42-144">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="84c42-145">Ver também</span><span class="sxs-lookup"><span data-stu-id="84c42-145">See also</span></span>



- [<span data-ttu-id="84c42-146">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="84c42-146">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

