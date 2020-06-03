---
title: Userconfigurationproperties
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- UserConfigurationProperties
api_type:
- schema
ms.assetid: c143a6ec-62ad-4d48-b844-b1ad88054bc1
description: O elemento userconfigurationproperties especifica os tipos de propriedade a serem obtidos em uma operação GetUserConfiguration.
ms.openlocfilehash: af6bee64516a7410d96ecc7581e8e819f550ddc1
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44466490"
---
# <a name="userconfigurationproperties"></a><span data-ttu-id="954b5-103">Userconfigurationproperties</span><span class="sxs-lookup"><span data-stu-id="954b5-103">UserConfigurationProperties</span></span>

<span data-ttu-id="954b5-104">O elemento **Userconfigurationproperties** especifica os tipos de propriedade a serem obtidos em uma operação GetUserConfiguration.</span><span class="sxs-lookup"><span data-stu-id="954b5-104">The **UserConfigurationProperties** element specifies the property types to get in a GetUserConfiguration operation.</span></span> 
  
```xml
<UserConfigurationProperties>Id | Dictionary | XmlData | BinaryData | All</UserConfigurationProperties>
```

 <span data-ttu-id="954b5-105">**UserConfigurationPropertyType**</span><span class="sxs-lookup"><span data-stu-id="954b5-105">**UserConfigurationPropertyType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="954b5-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="954b5-106">Attributes and elements</span></span>

<span data-ttu-id="954b5-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="954b5-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="954b5-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="954b5-108">Attributes</span></span>

<span data-ttu-id="954b5-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="954b5-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="954b5-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="954b5-110">Child elements</span></span>

<span data-ttu-id="954b5-111">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="954b5-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="954b5-112">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="954b5-112">Parent elements</span></span>

|<span data-ttu-id="954b5-113">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="954b5-113">**Element**</span></span>|<span data-ttu-id="954b5-114">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="954b5-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="954b5-115">GetUserConfiguration</span><span class="sxs-lookup"><span data-stu-id="954b5-115">GetUserConfiguration</span></span>](getuserconfiguration.md) <br/> |<span data-ttu-id="954b5-116">Especifica uma solicitação para obter um objeto de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="954b5-116">Specifies a request to get a user configuration object.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="954b5-117">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="954b5-117">Text value</span></span>

<span data-ttu-id="954b5-118">A tabela a seguir lista os valores possíveis para o elemento **Userconfigurationproperties** .</span><span class="sxs-lookup"><span data-stu-id="954b5-118">The following table lists the possible values for the **UserConfigurationProperties** element.</span></span> 
  
|<span data-ttu-id="954b5-119">**Valor**</span><span class="sxs-lookup"><span data-stu-id="954b5-119">**Value**</span></span>|<span data-ttu-id="954b5-120">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="954b5-120">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="954b5-121">Id</span><span class="sxs-lookup"><span data-stu-id="954b5-121">Id</span></span>  <br/> |<span data-ttu-id="954b5-122">Especifica a propriedade Identifier.</span><span class="sxs-lookup"><span data-stu-id="954b5-122">Specifies the identifier property.</span></span>  <br/> |
|<span data-ttu-id="954b5-123">Dictionary</span><span class="sxs-lookup"><span data-stu-id="954b5-123">Dictionary</span></span>  <br/> |<span data-ttu-id="954b5-124">Especifica os tipos de propriedade de dicionário.</span><span class="sxs-lookup"><span data-stu-id="954b5-124">Specifies dictionary property types.</span></span>  <br/> |
|<span data-ttu-id="954b5-125">Nota XMLDATA</span><span class="sxs-lookup"><span data-stu-id="954b5-125">XmlData</span></span>  <br/> |<span data-ttu-id="954b5-126">Especifica os tipos de propriedade de dados XML.</span><span class="sxs-lookup"><span data-stu-id="954b5-126">Specifies XML data property types.</span></span>  <br/> |
|<span data-ttu-id="954b5-127">BinaryData</span><span class="sxs-lookup"><span data-stu-id="954b5-127">BinaryData</span></span>  <br/> |<span data-ttu-id="954b5-128">Especifica tipos de propriedade de dados binários.</span><span class="sxs-lookup"><span data-stu-id="954b5-128">Specifies binary data property types.</span></span>  <br/> |
|<span data-ttu-id="954b5-129">Todos</span><span class="sxs-lookup"><span data-stu-id="954b5-129">All</span></span>  <br/> |<span data-ttu-id="954b5-130">Especifica os tipos de propriedade de identificador, dicionário, dados XML e dados binários.</span><span class="sxs-lookup"><span data-stu-id="954b5-130">Specifies the identifier, dictionary, XML data, and binary data property types.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="954b5-131">Comentários</span><span class="sxs-lookup"><span data-stu-id="954b5-131">Remarks</span></span>

<span data-ttu-id="954b5-132">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="954b5-132">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="954b5-133">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="954b5-133">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="954b5-134">Namespace</span><span class="sxs-lookup"><span data-stu-id="954b5-134">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="954b5-135">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="954b5-135">Schema Name</span></span>  <br/> |<span data-ttu-id="954b5-136">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="954b5-136">Messages schema</span></span>  <br/> |
|<span data-ttu-id="954b5-137">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="954b5-137">Validation File</span></span>  <br/> |<span data-ttu-id="954b5-138">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="954b5-138">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="954b5-139">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="954b5-139">Can be Empty</span></span>  <br/> |<span data-ttu-id="954b5-140">False</span><span class="sxs-lookup"><span data-stu-id="954b5-140">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="954b5-141">Confira também</span><span class="sxs-lookup"><span data-stu-id="954b5-141">See also</span></span>



- [<span data-ttu-id="954b5-142">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="954b5-142">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

