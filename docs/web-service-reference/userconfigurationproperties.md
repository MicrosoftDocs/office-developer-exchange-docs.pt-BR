---
title: UserConfigurationProperties
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
description: O elemento UserConfigurationProperties Especifica os tipos de propriedade a ser obtido em uma operação de GetUserConfiguration.
ms.openlocfilehash: 4f993765bb7c36f28a41a3f2fa7e28698a3f709e
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19837976"
---
# <a name="userconfigurationproperties"></a><span data-ttu-id="061e0-103">UserConfigurationProperties</span><span class="sxs-lookup"><span data-stu-id="061e0-103">UserConfigurationProperties</span></span>

<span data-ttu-id="061e0-104">O elemento **UserConfigurationProperties** Especifica os tipos de propriedade a ser obtido em uma operação de GetUserConfiguration.</span><span class="sxs-lookup"><span data-stu-id="061e0-104">The **UserConfigurationProperties** element specifies the property types to get in a GetUserConfiguration operation.</span></span> 
  
```xml
<UserConfigurationProperties>Id | Dictionary | XmlData | BinaryData | All</UserConfigurationProperties>
```

 <span data-ttu-id="061e0-105">**UserConfigurationPropertyType**</span><span class="sxs-lookup"><span data-stu-id="061e0-105">**UserConfigurationPropertyType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="061e0-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="061e0-106">Attributes and elements</span></span>

<span data-ttu-id="061e0-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="061e0-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="061e0-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="061e0-108">Attributes</span></span>

<span data-ttu-id="061e0-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="061e0-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="061e0-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="061e0-110">Child elements</span></span>

<span data-ttu-id="061e0-111">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="061e0-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="061e0-112">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="061e0-112">Parent elements</span></span>

|<span data-ttu-id="061e0-113">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="061e0-113">**Element**</span></span>|<span data-ttu-id="061e0-114">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="061e0-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="061e0-115">GetUserConfiguration</span><span class="sxs-lookup"><span data-stu-id="061e0-115">GetUserConfiguration</span></span>](getuserconfiguration.md) <br/> |<span data-ttu-id="061e0-116">Especifica uma solicitação para obter um objeto de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="061e0-116">Specifies a request to get a user configuration object.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="061e0-117">Text value</span><span class="sxs-lookup"><span data-stu-id="061e0-117">Text value</span></span>

<span data-ttu-id="061e0-118">A tabela a seguir lista os valores possíveis para o elemento **UserConfigurationProperties** .</span><span class="sxs-lookup"><span data-stu-id="061e0-118">The following table lists the possible values for the **UserConfigurationProperties** element.</span></span> 
  
|<span data-ttu-id="061e0-119">**Valor**</span><span class="sxs-lookup"><span data-stu-id="061e0-119">**Value**</span></span>|<span data-ttu-id="061e0-120">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="061e0-120">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="061e0-121">Id</span><span class="sxs-lookup"><span data-stu-id="061e0-121">Id</span></span>  <br/> |<span data-ttu-id="061e0-122">Especifica a propriedade identifier.</span><span class="sxs-lookup"><span data-stu-id="061e0-122">Specifies the identifier property.</span></span>  <br/> |
|<span data-ttu-id="061e0-123">Dictionary</span><span class="sxs-lookup"><span data-stu-id="061e0-123">Dictionary</span></span>  <br/> |<span data-ttu-id="061e0-124">Especifica os tipos de propriedade do dicionário.</span><span class="sxs-lookup"><span data-stu-id="061e0-124">Specifies dictionary property types.</span></span>  <br/> |
|<span data-ttu-id="061e0-125">Xmldatahttp</span><span class="sxs-lookup"><span data-stu-id="061e0-125">XmlData</span></span>  <br/> |<span data-ttu-id="061e0-126">Especifica os tipos de propriedade de dados XML.</span><span class="sxs-lookup"><span data-stu-id="061e0-126">Specifies XML data property types.</span></span>  <br/> |
|<span data-ttu-id="061e0-127">BinaryData</span><span class="sxs-lookup"><span data-stu-id="061e0-127">BinaryData</span></span>  <br/> |<span data-ttu-id="061e0-128">Especifica os tipos de propriedades de dados binários.</span><span class="sxs-lookup"><span data-stu-id="061e0-128">Specifies binary data property types.</span></span>  <br/> |
|<span data-ttu-id="061e0-129">Todos</span><span class="sxs-lookup"><span data-stu-id="061e0-129">All</span></span>  <br/> |<span data-ttu-id="061e0-130">Especifica o identificador, dicionário, dados XML e os tipos de propriedades de dados binários.</span><span class="sxs-lookup"><span data-stu-id="061e0-130">Specifies the identifier, dictionary, XML data, and binary data property types.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="061e0-131">Comentários</span><span class="sxs-lookup"><span data-stu-id="061e0-131">Remarks</span></span>

<span data-ttu-id="061e0-132">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="061e0-132">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="061e0-133">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="061e0-133">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="061e0-134">Namespace</span><span class="sxs-lookup"><span data-stu-id="061e0-134">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="061e0-135">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="061e0-135">Schema Name</span></span>  <br/> |<span data-ttu-id="061e0-136">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="061e0-136">Messages schema</span></span>  <br/> |
|<span data-ttu-id="061e0-137">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="061e0-137">Validation File</span></span>  <br/> |<span data-ttu-id="061e0-138">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="061e0-138">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="061e0-139">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="061e0-139">Can be Empty</span></span>  <br/> |<span data-ttu-id="061e0-140">False</span><span class="sxs-lookup"><span data-stu-id="061e0-140">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="061e0-141">Ver também</span><span class="sxs-lookup"><span data-stu-id="061e0-141">See also</span></span>



- [<span data-ttu-id="061e0-142">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="061e0-142">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
