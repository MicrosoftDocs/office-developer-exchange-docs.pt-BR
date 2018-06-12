---
title: EntityExtractionResult
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: 643b99ab-ff90-4411-864c-1077623028d6
description: O elemento EntityExtractionResult Especifica a propriedade EntityExtractionResult de um item.
ms.openlocfilehash: ef99629beb95f1e1123569fa99e3f495c1b56e95
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19752081"
---
# <a name="entityextractionresult"></a><span data-ttu-id="e8fb2-103">EntityExtractionResult</span><span class="sxs-lookup"><span data-stu-id="e8fb2-103">EntityExtractionResult</span></span>

<span data-ttu-id="e8fb2-104">O elemento **EntityExtractionResult** Especifica a propriedade **EntityExtractionResult** de um item.</span><span class="sxs-lookup"><span data-stu-id="e8fb2-104">The **EntityExtractionResult** element specifies the **EntityExtractionResult** property of an item.</span></span> 
  
```XML
<EntityExtractionResult>
    <Addresses/>
    <MeetingSuggestions/>
    <TaskSuggestions/>
    <EmailAddresses/>
    <Contacts/>
    <Urls/>
    <PhoneNumbers/>
</EntityExtractionResult>
```

 <span data-ttu-id="e8fb2-105">**EntityExtractionResultType**</span><span class="sxs-lookup"><span data-stu-id="e8fb2-105">**EntityExtractionResultType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="e8fb2-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="e8fb2-106">Attributes and elements</span></span>

<span data-ttu-id="e8fb2-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="e8fb2-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="e8fb2-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="e8fb2-108">Attributes</span></span>

<span data-ttu-id="e8fb2-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="e8fb2-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="e8fb2-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="e8fb2-110">Child elements</span></span>

|<span data-ttu-id="e8fb2-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="e8fb2-111">**Element**</span></span>|<span data-ttu-id="e8fb2-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="e8fb2-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="e8fb2-113">Endereços (ArrayOfAddressEntitiesType)</span><span class="sxs-lookup"><span data-stu-id="e8fb2-113">Addresses (ArrayOfAddressEntitiesType)</span></span>](addresses-arrayofaddressentitiestype.md) <br/> |<span data-ttu-id="e8fb2-114">Especifica uma matriz de elementos de **AddressEntity** .</span><span class="sxs-lookup"><span data-stu-id="e8fb2-114">Specifies an array of **AddressEntity** elements.</span></span>  <br/> |
|[<span data-ttu-id="e8fb2-115">MeetingSuggestions</span><span class="sxs-lookup"><span data-stu-id="e8fb2-115">MeetingSuggestions</span></span>](meetingsuggestions.md) <br/> |<span data-ttu-id="e8fb2-116">Especifica uma matriz de elementos de **MeetingSuggestion** .</span><span class="sxs-lookup"><span data-stu-id="e8fb2-116">Specifies an array of **MeetingSuggestion** elements.</span></span>  <br/> |
|[<span data-ttu-id="e8fb2-117">TaskSuggestions</span><span class="sxs-lookup"><span data-stu-id="e8fb2-117">TaskSuggestions</span></span>](tasksuggestions.md) <br/> |<span data-ttu-id="e8fb2-118">Especifica uma matriz de elementos de **TaskSuggestion** .</span><span class="sxs-lookup"><span data-stu-id="e8fb2-118">Specifies an array of **TaskSuggestion** elements.</span></span>  <br/> |
|[<span data-ttu-id="e8fb2-119">EmailAddresses (ArrayOfEmailAddressEntitiesType)</span><span class="sxs-lookup"><span data-stu-id="e8fb2-119">EmailAddresses (ArrayOfEmailAddressEntitiesType)</span></span>](emailaddresses-arrayofemailaddressentitiestype.md) <br/> |<span data-ttu-id="e8fb2-120">Especifica uma matriz de entidades de endereço de email.</span><span class="sxs-lookup"><span data-stu-id="e8fb2-120">Specifies an array of email address entities.</span></span>  <br/> |
|[<span data-ttu-id="e8fb2-121">Contatos (ArrayOfContactsType)</span><span class="sxs-lookup"><span data-stu-id="e8fb2-121">Contacts (ArrayOfContactsType)</span></span>](contacts-arrayofcontactstype.md) <br/> |<span data-ttu-id="e8fb2-122">Especifica uma matriz de contatos.</span><span class="sxs-lookup"><span data-stu-id="e8fb2-122">Specifies an array of contacts.</span></span>  <br/> |
|[<span data-ttu-id="e8fb2-123">URLs (ArrayOfUrlEntitiesType)</span><span class="sxs-lookup"><span data-stu-id="e8fb2-123">Urls (ArrayOfUrlEntitiesType)</span></span>](urls-arrayofurlentitiestype.md) <br/> |<span data-ttu-id="e8fb2-124">Especifica uma matriz de URLs.</span><span class="sxs-lookup"><span data-stu-id="e8fb2-124">Specifies an array of URLs.</span></span>  <br/> |
|[<span data-ttu-id="e8fb2-125">PhoneNumbers (ArrayOfPhoneEntitiesType)</span><span class="sxs-lookup"><span data-stu-id="e8fb2-125">PhoneNumbers (ArrayOfPhoneEntitiesType)</span></span>](phonenumbers-arrayofphoneentitiestype.md) <br/> |<span data-ttu-id="e8fb2-126">Especifica uma matriz de números de telefone.</span><span class="sxs-lookup"><span data-stu-id="e8fb2-126">Specifies an array of phone numbers.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="e8fb2-127">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="e8fb2-127">Parent elements</span></span>

|<span data-ttu-id="e8fb2-128">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="e8fb2-128">**Element**</span></span>|<span data-ttu-id="e8fb2-129">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="e8fb2-129">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="e8fb2-130">Item</span><span class="sxs-lookup"><span data-stu-id="e8fb2-130">Item</span></span>](item.md) <br/> |<span data-ttu-id="e8fb2-131">Representa um item genérico no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="e8fb2-131">Represents a generic item in the Exchange store.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="e8fb2-132">Coment�rios</span><span class="sxs-lookup"><span data-stu-id="e8fb2-132">Remarks</span></span>

<span data-ttu-id="e8fb2-133">Este elemento foi introduzido no Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="e8fb2-133">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="e8fb2-134">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="e8fb2-134">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="e8fb2-135">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="e8fb2-135">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="e8fb2-136">Namespace</span><span class="sxs-lookup"><span data-stu-id="e8fb2-136">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="e8fb2-137">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="e8fb2-137">Schema Name</span></span>  <br/> |<span data-ttu-id="e8fb2-138">Esquema de tipo</span><span class="sxs-lookup"><span data-stu-id="e8fb2-138">Type schema</span></span>  <br/> |
|<span data-ttu-id="e8fb2-139">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="e8fb2-139">Validation File</span></span>  <br/> |<span data-ttu-id="e8fb2-140">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="e8fb2-140">types.xsd</span></span>  <br/> |
|<span data-ttu-id="e8fb2-141">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="e8fb2-141">Can Be Empty</span></span>  <br/> ||
   
## <a name="see-also"></a><span data-ttu-id="e8fb2-142">Confira também</span><span class="sxs-lookup"><span data-stu-id="e8fb2-142">See also</span></span>



- [<span data-ttu-id="e8fb2-143">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="e8fb2-143">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

