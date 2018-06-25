---
title: ConfigurationName
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
description: O elemento ConfigurationName Especifica as configurações de serviço solicitado pelo nome.
ms.openlocfilehash: a03a0bc0ab7ecbc1c2aec31f864503ee0f560908
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/25/2018
ms.locfileid: "19751419"
---
# <a name="configurationname"></a><span data-ttu-id="74587-103">ConfigurationName</span><span class="sxs-lookup"><span data-stu-id="74587-103">ConfigurationName</span></span>

<span data-ttu-id="74587-104">O elemento **ConfigurationName** Especifica as configurações de serviço solicitado pelo nome.</span><span class="sxs-lookup"><span data-stu-id="74587-104">The **ConfigurationName** element specifies the requested service configurations by name.</span></span> 
  
```xml
<ConfigurationName>MailTips or UnifiedMessagingConfiguration or ProtectionRules</ConfigurationName>
```

 <span data-ttu-id="74587-105">**ServiceConfigurationType**</span><span class="sxs-lookup"><span data-stu-id="74587-105">**ServiceConfigurationType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="74587-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="74587-106">Attributes and elements</span></span>

<span data-ttu-id="74587-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="74587-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="74587-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="74587-108">Attributes</span></span>

<span data-ttu-id="74587-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="74587-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="74587-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="74587-110">Child elements</span></span>

<span data-ttu-id="74587-111">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="74587-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="74587-112">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="74587-112">Parent elements</span></span>

|<span data-ttu-id="74587-113">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="74587-113">**Element**</span></span>|<span data-ttu-id="74587-114">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="74587-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="74587-115">RequestedConfiguration</span><span class="sxs-lookup"><span data-stu-id="74587-115">RequestedConfiguration</span></span>](requestedconfiguration.md) <br/> |<span data-ttu-id="74587-116">Contém as configurações do serviço solicitado.</span><span class="sxs-lookup"><span data-stu-id="74587-116">Contains the requested service configurations.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="74587-117">Text value</span><span class="sxs-lookup"><span data-stu-id="74587-117">Text value</span></span>

<span data-ttu-id="74587-118">A tabela a seguir lista os valores possíveis para o elemento **ConfigurationName** .</span><span class="sxs-lookup"><span data-stu-id="74587-118">The following table lists the possible values for the **ConfigurationName** element.</span></span> 
  
<span data-ttu-id="74587-119">**Valores de elemento ConfigurationName**</span><span class="sxs-lookup"><span data-stu-id="74587-119">**ConfigurationName element values**</span></span>

|<span data-ttu-id="74587-120">**Valor**</span><span class="sxs-lookup"><span data-stu-id="74587-120">**Value**</span></span>|<span data-ttu-id="74587-121">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="74587-121">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="74587-122">Dicas de email</span><span class="sxs-lookup"><span data-stu-id="74587-122">MailTips</span></span>  <br/> |<span data-ttu-id="74587-123">Identifica a configuração do serviço de dicas de email.</span><span class="sxs-lookup"><span data-stu-id="74587-123">Identifies the MailTips service configuration.</span></span>  <br/> |
|<span data-ttu-id="74587-124">UnifiedMessagingConfiguration</span><span class="sxs-lookup"><span data-stu-id="74587-124">UnifiedMessagingConfiguration</span></span>  <br/> |<span data-ttu-id="74587-125">Identifica a configuração do serviço de Unificação de mensagens.</span><span class="sxs-lookup"><span data-stu-id="74587-125">Identifies the Unified Messaging service configuration.</span></span>  <br/> |
|<span data-ttu-id="74587-126">ProtectionRules</span><span class="sxs-lookup"><span data-stu-id="74587-126">ProtectionRules</span></span>  <br/> |<span data-ttu-id="74587-127">Identifica a configuração de regras de proteção do serviço.</span><span class="sxs-lookup"><span data-stu-id="74587-127">Identifies the Protection Rules service configuration.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="74587-128">Comentários</span><span class="sxs-lookup"><span data-stu-id="74587-128">Remarks</span></span>

<span data-ttu-id="74587-129">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="74587-129">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="74587-130">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="74587-130">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="74587-131">Namespace</span><span class="sxs-lookup"><span data-stu-id="74587-131">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="74587-132">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="74587-132">Schema Name</span></span>  <br/> |<span data-ttu-id="74587-133">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="74587-133">Messages schema</span></span>  <br/> |
|<span data-ttu-id="74587-134">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="74587-134">Validation File</span></span>  <br/> |<span data-ttu-id="74587-135">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="74587-135">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="74587-136">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="74587-136">Can be Empty</span></span>  <br/> |<span data-ttu-id="74587-137">False</span><span class="sxs-lookup"><span data-stu-id="74587-137">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="74587-138">Ver também</span><span class="sxs-lookup"><span data-stu-id="74587-138">See also</span></span>



- [<span data-ttu-id="74587-139">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="74587-139">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

