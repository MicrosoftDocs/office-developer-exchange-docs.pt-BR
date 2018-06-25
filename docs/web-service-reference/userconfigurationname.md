---
title: UserConfigurationName
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- UserConfigurationName
api_type:
- schema
ms.assetid: 6947dd03-9727-4379-9b9d-42373fa120c7
description: O elemento UserConfigurationName representa o nome de um objeto de configuração do usuário. O nome de objeto de configuração do usuário é o identificador de um objeto de configuração do usuário.
ms.openlocfilehash: 40580343e92493c3d39b090371708269ec3274b9
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/25/2018
ms.locfileid: "19837972"
---
# <a name="userconfigurationname"></a><span data-ttu-id="b510d-104">UserConfigurationName</span><span class="sxs-lookup"><span data-stu-id="b510d-104">UserConfigurationName</span></span>

<span data-ttu-id="b510d-105">O elemento **UserConfigurationName** representa o nome de um objeto de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="b510d-105">The **UserConfigurationName** element represents the name of a user configuration object.</span></span> <span data-ttu-id="b510d-106">O nome de objeto de configuração do usuário é o identificador de um objeto de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="b510d-106">The user configuration object name is the identifier for a user configuration object.</span></span> 
  
```XML
<UserConfigurationName Name="">
   <FolderId/>
</UserConfigurationName>
```

 <span data-ttu-id="b510d-107">**UserConfigurationNameType**</span><span class="sxs-lookup"><span data-stu-id="b510d-107">**UserConfigurationNameType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="b510d-108">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="b510d-108">Attributes and elements</span></span>

<span data-ttu-id="b510d-109">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="b510d-109">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="b510d-110">Atributos</span><span class="sxs-lookup"><span data-stu-id="b510d-110">Attributes</span></span>

|<span data-ttu-id="b510d-111">**Attribute**</span><span class="sxs-lookup"><span data-stu-id="b510d-111">**Attribute**</span></span>|<span data-ttu-id="b510d-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="b510d-112">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="b510d-113">**Name**</span><span class="sxs-lookup"><span data-stu-id="b510d-113">**Name**</span></span> <br/> |<span data-ttu-id="b510d-114">Contém um valor string que representa o nome de um objeto de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="b510d-114">Contains a string value that represents the name of a user configuration object.</span></span> <span data-ttu-id="b510d-115">Este atributo é necessário.</span><span class="sxs-lookup"><span data-stu-id="b510d-115">This attribute is required.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="b510d-116">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="b510d-116">Child elements</span></span>

|<span data-ttu-id="b510d-117">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="b510d-117">**Element**</span></span>|<span data-ttu-id="b510d-118">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="b510d-118">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="b510d-119">FolderId</span><span class="sxs-lookup"><span data-stu-id="b510d-119">FolderId</span></span>](folderid.md) <br/> |<span data-ttu-id="b510d-120">Representa o identificador de pasta da pasta que contém o objeto de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="b510d-120">Represents the folder identifier of the folder that contains the user configuration object.</span></span>  <br/> |
|[<span data-ttu-id="b510d-121">DistinguishedFolderId</span><span class="sxs-lookup"><span data-stu-id="b510d-121">DistinguishedFolderId</span></span>](distinguishedfolderid.md) <br/> |<span data-ttu-id="b510d-122">Representa um nome diferenciado de pasta da pasta que contém o objeto de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="b510d-122">Represents a distinguished folder name of the folder that contains the user configuration object.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="b510d-123">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="b510d-123">Parent elements</span></span>

|<span data-ttu-id="b510d-124">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="b510d-124">**Element**</span></span>|<span data-ttu-id="b510d-125">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="b510d-125">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="b510d-126">DeleteUserConfiguration</span><span class="sxs-lookup"><span data-stu-id="b510d-126">DeleteUserConfiguration</span></span>](deleteuserconfiguration.md) <br/> |<span data-ttu-id="b510d-127">Representa uma solicitação para excluir um objeto de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="b510d-127">Represents a request to delete a user configuration object.</span></span>  <br/> |
|[<span data-ttu-id="b510d-128">GetUserConfiguration</span><span class="sxs-lookup"><span data-stu-id="b510d-128">GetUserConfiguration</span></span>](getuserconfiguration.md) <br/> |<span data-ttu-id="b510d-129">Representa uma solicitação para obter um objeto de configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="b510d-129">Represents a request to get a user configuration object.</span></span>  <br/> |
|[<span data-ttu-id="b510d-130">UserConfiguration</span><span class="sxs-lookup"><span data-stu-id="b510d-130">UserConfiguration</span></span>](userconfiguration.md) <br/> |<span data-ttu-id="b510d-131">Define um objeto de configuração de usuário único.</span><span class="sxs-lookup"><span data-stu-id="b510d-131">Defines a single user configuration object.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="b510d-132">Text value</span><span class="sxs-lookup"><span data-stu-id="b510d-132">Text value</span></span>

<span data-ttu-id="b510d-133">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="b510d-133">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="b510d-134">Comentários</span><span class="sxs-lookup"><span data-stu-id="b510d-134">Remarks</span></span>

<span data-ttu-id="b510d-135">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="b510d-135">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="b510d-136">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="b510d-136">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="b510d-137">Namespace</span><span class="sxs-lookup"><span data-stu-id="b510d-137">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="b510d-138">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="b510d-138">Schema Name</span></span>  <br/> |<span data-ttu-id="b510d-139">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="b510d-139">Types schema</span></span>  <br/> |
|<span data-ttu-id="b510d-140">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="b510d-140">Validation File</span></span>  <br/> |<span data-ttu-id="b510d-141">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="b510d-141">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="b510d-142">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="b510d-142">Can be Empty</span></span>  <br/> |<span data-ttu-id="b510d-143">False</span><span class="sxs-lookup"><span data-stu-id="b510d-143">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="b510d-144">Ver também</span><span class="sxs-lookup"><span data-stu-id="b510d-144">See also</span></span>



- [<span data-ttu-id="b510d-145">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="b510d-145">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

