---
title: DiscoverySearchConfigurations
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: f04b14c9-384c-4016-b113-52a49e15e73b
description: O elemento DiscoverySearchConfigurations especifica uma matriz de elementos DiscoverySearchConfiguration.
ms.openlocfilehash: 6af4c8198f2ad73f8b39f9718e11b88aa8075c39
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44461377"
---
# <a name="discoverysearchconfigurations"></a><span data-ttu-id="1bd21-103">DiscoverySearchConfigurations</span><span class="sxs-lookup"><span data-stu-id="1bd21-103">DiscoverySearchConfigurations</span></span>

<span data-ttu-id="1bd21-104">O elemento **DiscoverySearchConfigurations** especifica uma matriz de elementos **DiscoverySearchConfiguration** .</span><span class="sxs-lookup"><span data-stu-id="1bd21-104">The **DiscoverySearchConfigurations** element specifies an array of **DiscoverySearchConfiguration** elements.</span></span> 
  
```XML
<DiscoverySearchConfigurations>
    <DiscoverySearchConfiguration></DiscoverySearchConfiguration>
</DiscoverySearchConfigurations>
```

 <span data-ttu-id="1bd21-105">**ArrayOfDiscoverySearchConfigurationType**</span><span class="sxs-lookup"><span data-stu-id="1bd21-105">**ArrayOfDiscoverySearchConfigurationType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="1bd21-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="1bd21-106">Attributes and elements</span></span>

<span data-ttu-id="1bd21-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="1bd21-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="1bd21-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="1bd21-108">Attributes</span></span>

<span data-ttu-id="1bd21-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="1bd21-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="1bd21-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="1bd21-110">Child elements</span></span>

|<span data-ttu-id="1bd21-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="1bd21-111">**Element**</span></span>|<span data-ttu-id="1bd21-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="1bd21-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="1bd21-113">DiscoverySearchConfiguration</span><span class="sxs-lookup"><span data-stu-id="1bd21-113">DiscoverySearchConfiguration</span></span>](discoverysearchconfiguration.md) <br/> |<span data-ttu-id="1bd21-114">Especifica a configuração da pesquisa de descoberta eletrônica.</span><span class="sxs-lookup"><span data-stu-id="1bd21-114">Specifies the configuration for eDiscovery search.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="1bd21-115">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="1bd21-115">Parent elements</span></span>

|<span data-ttu-id="1bd21-116">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="1bd21-116">**Element**</span></span>|<span data-ttu-id="1bd21-117">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="1bd21-117">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="1bd21-118">GetDiscoverySearchConfigurationResponseMessage</span><span class="sxs-lookup"><span data-stu-id="1bd21-118">GetDiscoverySearchConfigurationResponseMessage</span></span>](getdiscoverysearchconfigurationresponsemessage.md) <br/> |<span data-ttu-id="1bd21-119">Especifica a mensagem de resposta para uma solicitação **GetDiscoverySearchConfiguration** .</span><span class="sxs-lookup"><span data-stu-id="1bd21-119">Specifies the response message for a **GetDiscoverySearchConfiguration** request.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="1bd21-120">Comentários</span><span class="sxs-lookup"><span data-stu-id="1bd21-120">Remarks</span></span>

<span data-ttu-id="1bd21-121">Este elemento foi introduzido no Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="1bd21-121">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="1bd21-122">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="1bd21-122">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="1bd21-123">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="1bd21-123">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="1bd21-124">Namespace</span><span class="sxs-lookup"><span data-stu-id="1bd21-124">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="1bd21-125">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="1bd21-125">Schema Name</span></span>  <br/> |<span data-ttu-id="1bd21-126">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="1bd21-126">Message schema</span></span>  <br/> |
|<span data-ttu-id="1bd21-127">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="1bd21-127">Validation File</span></span>  <br/> |<span data-ttu-id="1bd21-128">messages. xsd</span><span class="sxs-lookup"><span data-stu-id="1bd21-128">messages.xsd</span></span>  <br/> |
|<span data-ttu-id="1bd21-129">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="1bd21-129">Can Be Empty</span></span>  <br/> ||
   
## <a name="see-also"></a><span data-ttu-id="1bd21-130">Também consulte</span><span class="sxs-lookup"><span data-stu-id="1bd21-130">See also</span></span>

- [<span data-ttu-id="1bd21-131">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="1bd21-131">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

