---
title: Domínio
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- Domain
api_type:
- schema
ms.assetid: 7e45a061-856f-4b44-b053-a7c4d5ad569e
description: O elemento Domain identifica um único domínio SMTP.
ms.openlocfilehash: 3bf8e132b5fa588171ac4f3c095692bc68394663
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44461328"
---
# <a name="domain"></a><span data-ttu-id="f1c51-103">Domínio</span><span class="sxs-lookup"><span data-stu-id="f1c51-103">Domain</span></span>

<span data-ttu-id="f1c51-104">O elemento **Domain** identifica um único domínio SMTP.</span><span class="sxs-lookup"><span data-stu-id="f1c51-104">The **Domain** element identifies a single SMTP domain.</span></span> 
  
```xml
<Domain Name="" IncludeSubdomains="" />
```

 <span data-ttu-id="f1c51-105">**StmpDomain**</span><span class="sxs-lookup"><span data-stu-id="f1c51-105">**StmpDomain**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="f1c51-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="f1c51-106">Attributes and elements</span></span>

<span data-ttu-id="f1c51-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="f1c51-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="f1c51-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="f1c51-108">Attributes</span></span>

|<span data-ttu-id="f1c51-109">**Atributo**</span><span class="sxs-lookup"><span data-stu-id="f1c51-109">**Attribute**</span></span>|<span data-ttu-id="f1c51-110">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="f1c51-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="f1c51-111">Nome</span><span class="sxs-lookup"><span data-stu-id="f1c51-111">Name</span></span>  <br/> |<span data-ttu-id="f1c51-112">Identifica o nome de um domínio.</span><span class="sxs-lookup"><span data-stu-id="f1c51-112">Identifies the name of a domain.</span></span> <span data-ttu-id="f1c51-113">Esse atributo é necessário.</span><span class="sxs-lookup"><span data-stu-id="f1c51-113">This attribute is required.</span></span>  <br/> |
|<span data-ttu-id="f1c51-114">IncludeSubdomains</span><span class="sxs-lookup"><span data-stu-id="f1c51-114">IncludeSubdomains</span></span>  <br/> |<span data-ttu-id="f1c51-115">Indica se os subdomínios do domínio identificado pelo atributo **Name** são considerados internos.</span><span class="sxs-lookup"><span data-stu-id="f1c51-115">Indicates whether subdomains of the domain identified by the **Name** attribute are considered internal.</span></span> <span data-ttu-id="f1c51-116">Esse atributo é opcional.</span><span class="sxs-lookup"><span data-stu-id="f1c51-116">This attribute is optional.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="f1c51-117">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="f1c51-117">Child elements</span></span>

<span data-ttu-id="f1c51-118">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="f1c51-118">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="f1c51-119">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="f1c51-119">Parent elements</span></span>

|<span data-ttu-id="f1c51-120">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="f1c51-120">**Element**</span></span>|<span data-ttu-id="f1c51-121">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="f1c51-121">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="f1c51-122">InternalDomains (SmtpDomainList)</span><span class="sxs-lookup"><span data-stu-id="f1c51-122">InternalDomains (SmtpDomainList)</span></span>](internaldomains-smtpdomainlist.md) <br/> |<span data-ttu-id="f1c51-123">Identifica a lista de domínios SMTP internos da organização.</span><span class="sxs-lookup"><span data-stu-id="f1c51-123">Identifies the list of internal SMTP domains of the organization.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="f1c51-124">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="f1c51-124">Text value</span></span>

<span data-ttu-id="f1c51-125">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="f1c51-125">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="f1c51-126">Comentários</span><span class="sxs-lookup"><span data-stu-id="f1c51-126">Remarks</span></span>

<span data-ttu-id="f1c51-127">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="f1c51-127">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="f1c51-128">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="f1c51-128">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="f1c51-129">Namespace</span><span class="sxs-lookup"><span data-stu-id="f1c51-129">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="f1c51-130">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="f1c51-130">Schema Name</span></span>  <br/> |<span data-ttu-id="f1c51-131">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="f1c51-131">Types schema</span></span>  <br/> |
|<span data-ttu-id="f1c51-132">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="f1c51-132">Validation File</span></span>  <br/> |<span data-ttu-id="f1c51-133">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="f1c51-133">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="f1c51-134">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="f1c51-134">Can be Empty</span></span>  <br/> |<span data-ttu-id="f1c51-135">False</span><span class="sxs-lookup"><span data-stu-id="f1c51-135">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="f1c51-136">Confira também</span><span class="sxs-lookup"><span data-stu-id="f1c51-136">See also</span></span>

- [<span data-ttu-id="f1c51-137">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="f1c51-137">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

