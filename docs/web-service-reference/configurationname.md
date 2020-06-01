---
title: Configuration
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- ConfigurationName
api_type:
- schema
ms.assetid: 3b524a2f-9c6b-4550-9f3d-f78d176b0f7b
description: O elemento ConfigurationName especifica as configurações de serviço solicitadas por nome.
ms.openlocfilehash: 5e1216253a633af643dbd276827842dbe2db5d5f
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44463920"
---
# <a name="configurationname"></a><span data-ttu-id="794fd-103">Configuration</span><span class="sxs-lookup"><span data-stu-id="794fd-103">ConfigurationName</span></span>

<span data-ttu-id="794fd-104">O elemento **ConfigurationName** especifica as configurações de serviço solicitadas por nome.</span><span class="sxs-lookup"><span data-stu-id="794fd-104">The **ConfigurationName** element specifies the requested service configurations by name.</span></span> 
  
```xml
<ConfigurationName>MailTips or UnifiedMessagingConfiguration or ProtectionRules</ConfigurationName>
```

 <span data-ttu-id="794fd-105">**Naconfigurationtype**</span><span class="sxs-lookup"><span data-stu-id="794fd-105">**ServiceConfigurationType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="794fd-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="794fd-106">Attributes and elements</span></span>

<span data-ttu-id="794fd-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="794fd-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="794fd-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="794fd-108">Attributes</span></span>

<span data-ttu-id="794fd-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="794fd-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="794fd-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="794fd-110">Child elements</span></span>

<span data-ttu-id="794fd-111">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="794fd-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="794fd-112">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="794fd-112">Parent elements</span></span>

|<span data-ttu-id="794fd-113">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="794fd-113">**Element**</span></span>|<span data-ttu-id="794fd-114">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="794fd-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="794fd-115">RequestedConfiguration</span><span class="sxs-lookup"><span data-stu-id="794fd-115">RequestedConfiguration</span></span>](requestedconfiguration.md) <br/> |<span data-ttu-id="794fd-116">Contém as configurações de serviço solicitadas.</span><span class="sxs-lookup"><span data-stu-id="794fd-116">Contains the requested service configurations.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="794fd-117">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="794fd-117">Text value</span></span>

<span data-ttu-id="794fd-118">A tabela a seguir lista os valores possíveis para o elemento **ConfigurationName** .</span><span class="sxs-lookup"><span data-stu-id="794fd-118">The following table lists the possible values for the **ConfigurationName** element.</span></span> 
  
<span data-ttu-id="794fd-119">**Valores do elemento ConfigurationName**</span><span class="sxs-lookup"><span data-stu-id="794fd-119">**ConfigurationName element values**</span></span>

|<span data-ttu-id="794fd-120">**Valor**</span><span class="sxs-lookup"><span data-stu-id="794fd-120">**Value**</span></span>|<span data-ttu-id="794fd-121">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="794fd-121">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="794fd-122">MailTips</span><span class="sxs-lookup"><span data-stu-id="794fd-122">MailTips</span></span>  <br/> |<span data-ttu-id="794fd-123">Identifica a configuração do serviço de dicas de dicas.</span><span class="sxs-lookup"><span data-stu-id="794fd-123">Identifies the MailTips service configuration.</span></span>  <br/> |
|<span data-ttu-id="794fd-124">UnifiedMessagingConfiguration</span><span class="sxs-lookup"><span data-stu-id="794fd-124">UnifiedMessagingConfiguration</span></span>  <br/> |<span data-ttu-id="794fd-125">Identifica a configuração do serviço de Unificação de mensagens.</span><span class="sxs-lookup"><span data-stu-id="794fd-125">Identifies the Unified Messaging service configuration.</span></span>  <br/> |
|<span data-ttu-id="794fd-126">ProtectionRules</span><span class="sxs-lookup"><span data-stu-id="794fd-126">ProtectionRules</span></span>  <br/> |<span data-ttu-id="794fd-127">Identifica a configuração do serviço de regras de proteção.</span><span class="sxs-lookup"><span data-stu-id="794fd-127">Identifies the Protection Rules service configuration.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="794fd-128">Comentários</span><span class="sxs-lookup"><span data-stu-id="794fd-128">Remarks</span></span>

<span data-ttu-id="794fd-129">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="794fd-129">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="794fd-130">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="794fd-130">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="794fd-131">Namespace</span><span class="sxs-lookup"><span data-stu-id="794fd-131">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="794fd-132">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="794fd-132">Schema Name</span></span>  <br/> |<span data-ttu-id="794fd-133">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="794fd-133">Messages schema</span></span>  <br/> |
|<span data-ttu-id="794fd-134">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="794fd-134">Validation File</span></span>  <br/> |<span data-ttu-id="794fd-135">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="794fd-135">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="794fd-136">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="794fd-136">Can be Empty</span></span>  <br/> |<span data-ttu-id="794fd-137">False</span><span class="sxs-lookup"><span data-stu-id="794fd-137">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="794fd-138">Confira também</span><span class="sxs-lookup"><span data-stu-id="794fd-138">See also</span></span>



- [<span data-ttu-id="794fd-139">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="794fd-139">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

