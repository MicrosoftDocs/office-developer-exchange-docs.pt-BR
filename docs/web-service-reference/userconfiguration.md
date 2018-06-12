---
title: UserConfiguration
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- UserConfiguration
api_type:
- schema
ms.assetid: 1811df99-ca5b-48a3-b160-b3fd70320c34
description: O elemento de UserConfiguration define um objeto de configuração de usuário único.
ms.openlocfilehash: ce3eaa470ef592c5a8e5a7ef24c377bb2feeca2e
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19837973"
---
# <a name="userconfiguration"></a><span data-ttu-id="7bd14-103">UserConfiguration</span><span class="sxs-lookup"><span data-stu-id="7bd14-103">UserConfiguration</span></span>

<span data-ttu-id="7bd14-104">O elemento de **UserConfiguration** define um objeto de configuração de usuário único.</span><span class="sxs-lookup"><span data-stu-id="7bd14-104">The **UserConfiguration** element defines a single user configuration object.</span></span> 
  
```XML
<UserConfiguration>
   <UserConfigurationName/>
   <ItemId/>
   <Dictionary/>
   <XmlData/>
  <BinaryData/>
</UserConfiguration>
```

 <span data-ttu-id="7bd14-105">**UserConfigurationType**</span><span class="sxs-lookup"><span data-stu-id="7bd14-105">**UserConfigurationType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="7bd14-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="7bd14-106">Attributes and elements</span></span>

<span data-ttu-id="7bd14-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="7bd14-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="7bd14-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="7bd14-108">Attributes</span></span>

<span data-ttu-id="7bd14-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="7bd14-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="7bd14-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="7bd14-110">Child elements</span></span>

|<span data-ttu-id="7bd14-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="7bd14-111">**Element**</span></span>|<span data-ttu-id="7bd14-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="7bd14-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="7bd14-113">UserConfigurationName</span><span class="sxs-lookup"><span data-stu-id="7bd14-113">UserConfigurationName</span></span>](userconfigurationname.md) <br/> |<span data-ttu-id="7bd14-114">Representa o nome de um objeto de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="7bd14-114">Represents the name of a user configuration object.</span></span> <span data-ttu-id="7bd14-115">Este elemento deve ser usado quando você cria um objeto de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="7bd14-115">This element must be used when you create a user configuration object.</span></span>  <br/> |
|[<span data-ttu-id="7bd14-116">ItemId</span><span class="sxs-lookup"><span data-stu-id="7bd14-116">ItemId</span></span>](itemid.md) <br/> |<span data-ttu-id="7bd14-117">Define o identificador de item do objeto de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="7bd14-117">Defines the user configuration object item identifier.</span></span>  <br/> |
|[<span data-ttu-id="7bd14-118">dicionário</span><span class="sxs-lookup"><span data-stu-id="7bd14-118">Dictionary</span></span>](dictionary.md) <br/> |<span data-ttu-id="7bd14-119">Define um conjunto de entradas de propriedade de dicionário para um objeto de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="7bd14-119">Defines a set of dictionary property entries for a user configuration object.</span></span>  <br/> |
|[<span data-ttu-id="7bd14-120">Xmldatahttp</span><span class="sxs-lookup"><span data-stu-id="7bd14-120">XmlData</span></span>](xmldata.md) <br/> |<span data-ttu-id="7bd14-121">Possui conteúdo de propriedade de dados XML para um objeto de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="7bd14-121">Contains XML data property content for a user configuration object.</span></span>  <br/> |
|[<span data-ttu-id="7bd14-122">BinaryData</span><span class="sxs-lookup"><span data-stu-id="7bd14-122">BinaryData</span></span>](binarydata.md) <br/> |<span data-ttu-id="7bd14-123">Contém dados binários conteúdo de propriedade para um objeto de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="7bd14-123">Contains binary data property content for a user configuration object.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="7bd14-124">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="7bd14-124">Parent elements</span></span>

|<span data-ttu-id="7bd14-125">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="7bd14-125">**Element**</span></span>|<span data-ttu-id="7bd14-126">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="7bd14-126">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="7bd14-127">CreateUserConfiguration</span><span class="sxs-lookup"><span data-stu-id="7bd14-127">CreateUserConfiguration</span></span>](createuserconfiguration.md) <br/> |<span data-ttu-id="7bd14-128">Representa uma solicitação para criar um objeto de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="7bd14-128">Represents a request to create a user configuration object.</span></span>  <br/> |
|[<span data-ttu-id="7bd14-129">GetUserConfigurationResponseMessage</span><span class="sxs-lookup"><span data-stu-id="7bd14-129">GetUserConfigurationResponseMessage</span></span>](getuserconfigurationresponsemessage.md) <br/> |<span data-ttu-id="7bd14-130">Representa uma resposta que retorna um objeto de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="7bd14-130">Represents a response that returns a user configuration object.</span></span>  <br/> |
|[<span data-ttu-id="7bd14-131">UpdateUserConfiguration</span><span class="sxs-lookup"><span data-stu-id="7bd14-131">UpdateUserConfiguration</span></span>](updateuserconfiguration.md) <br/> |<span data-ttu-id="7bd14-132">Representa uma solicitação para atualizar um objeto de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="7bd14-132">Represents a request to update a user configuration object.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="7bd14-133">Comentários</span><span class="sxs-lookup"><span data-stu-id="7bd14-133">Remarks</span></span>

<span data-ttu-id="7bd14-134">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="7bd14-134">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="7bd14-135">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="7bd14-135">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="7bd14-136">Namespace</span><span class="sxs-lookup"><span data-stu-id="7bd14-136">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="7bd14-137">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="7bd14-137">Schema Name</span></span>  <br/> |<span data-ttu-id="7bd14-138">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="7bd14-138">Messages schema</span></span>  <br/> |
|<span data-ttu-id="7bd14-139">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="7bd14-139">Validation File</span></span>  <br/> |<span data-ttu-id="7bd14-140">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="7bd14-140">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="7bd14-141">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="7bd14-141">Can be Empty</span></span>  <br/> |<span data-ttu-id="7bd14-142">False</span><span class="sxs-lookup"><span data-stu-id="7bd14-142">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="7bd14-143">Ver também</span><span class="sxs-lookup"><span data-stu-id="7bd14-143">See also</span></span>



- [<span data-ttu-id="7bd14-144">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="7bd14-144">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

