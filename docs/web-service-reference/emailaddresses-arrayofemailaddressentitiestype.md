---
title: EmailAddresses (ArrayOfEmailAddressEntitiesType)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: 2fc4a8e8-5377-4059-8fb4-3fdabfd30fe3
description: O elemento EmailAddresses Especifica uma matriz de entidades de endereço de email.
ms.openlocfilehash: 8d96d49ef2420f269197e47577efb956daa64e53
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19751999"
---
# <a name="emailaddresses-arrayofemailaddressentitiestype"></a><span data-ttu-id="0125d-103">EmailAddresses (ArrayOfEmailAddressEntitiesType)</span><span class="sxs-lookup"><span data-stu-id="0125d-103">EmailAddresses (ArrayOfEmailAddressEntitiesType)</span></span>

<span data-ttu-id="0125d-104">O elemento **EmailAddresses** Especifica uma matriz de entidades de endereço de email.</span><span class="sxs-lookup"><span data-stu-id="0125d-104">The **EmailAddresses** element specifies an array of email address entities.</span></span> 
  
```XML
<EmailAddresses>
    <EmailAddressEntity></EmailAddressEntity>
</EmailAddresses>
```

 <span data-ttu-id="0125d-105">**ArrayOfEmailAddressEntitiesType**</span><span class="sxs-lookup"><span data-stu-id="0125d-105">**ArrayOfEmailAddressEntitiesType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="0125d-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="0125d-106">Attributes and elements</span></span>

<span data-ttu-id="0125d-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="0125d-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="0125d-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="0125d-108">Attributes</span></span>

<span data-ttu-id="0125d-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="0125d-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="0125d-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="0125d-110">Child elements</span></span>

|<span data-ttu-id="0125d-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="0125d-111">**Element**</span></span>|<span data-ttu-id="0125d-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="0125d-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="0125d-113">EmailAddressEntity</span><span class="sxs-lookup"><span data-stu-id="0125d-113">EmailAddressEntity</span></span>](emailaddressentity.md) <br/> |<span data-ttu-id="0125d-114">Especifica uma entidade de endereço de email único.</span><span class="sxs-lookup"><span data-stu-id="0125d-114">Specifies a single email address entity.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="0125d-115">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="0125d-115">Parent elements</span></span>

|<span data-ttu-id="0125d-116">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="0125d-116">**Element**</span></span>|<span data-ttu-id="0125d-117">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="0125d-117">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="0125d-118">EntityExtractionResult</span><span class="sxs-lookup"><span data-stu-id="0125d-118">EntityExtractionResult</span></span>](entityextractionresult.md) <br/> |<span data-ttu-id="0125d-119">Especifica a propriedade **EntityExtractionResult** de um item.</span><span class="sxs-lookup"><span data-stu-id="0125d-119">Specifies the **EntityExtractionResult** property of an item.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="0125d-120">Coment�rios</span><span class="sxs-lookup"><span data-stu-id="0125d-120">Remarks</span></span>

<span data-ttu-id="0125d-121">Este elemento foi introduzido no Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="0125d-121">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="0125d-122">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="0125d-122">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="0125d-123">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="0125d-123">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="0125d-124">Namespace</span><span class="sxs-lookup"><span data-stu-id="0125d-124">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="0125d-125">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="0125d-125">Schema Name</span></span>  <br/> |<span data-ttu-id="0125d-126">Esquema de tipo</span><span class="sxs-lookup"><span data-stu-id="0125d-126">Type schema</span></span>  <br/> |
|<span data-ttu-id="0125d-127">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="0125d-127">Validation File</span></span>  <br/> |<span data-ttu-id="0125d-128">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="0125d-128">types.xsd</span></span>  <br/> |
|<span data-ttu-id="0125d-129">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="0125d-129">Can Be Empty</span></span>  <br/> ||
   
## <a name="see-also"></a><span data-ttu-id="0125d-130">Confira também</span><span class="sxs-lookup"><span data-stu-id="0125d-130">See also</span></span>



- [<span data-ttu-id="0125d-131">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="0125d-131">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

