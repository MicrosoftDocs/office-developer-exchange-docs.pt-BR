---
title: TasksFolderPermissionLevel
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- TasksFolderPermissionLevel
api_type:
- schema
ms.assetid: 0f70b79b-3443-4048-b410-692d4e2464fc
description: O elemento TasksFolderPermissionLevel contém as permissões para a pasta padrão tarefas. Este elemento foi introduzido no Microsoft Exchange Server 2007 Service Pack 1 (SP1).
ms.openlocfilehash: 6e3988698575f0c1f935922d1642829a1f1addf9
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44465328"
---
# <a name="tasksfolderpermissionlevel"></a><span data-ttu-id="27b98-104">TasksFolderPermissionLevel</span><span class="sxs-lookup"><span data-stu-id="27b98-104">TasksFolderPermissionLevel</span></span>

<span data-ttu-id="27b98-105">O elemento **TasksFolderPermissionLevel** contém as permissões para a pasta padrão tarefas.</span><span class="sxs-lookup"><span data-stu-id="27b98-105">The **TasksFolderPermissionLevel** element contains the permissions for the default Tasks folder.</span></span> <span data-ttu-id="27b98-106">Este elemento foi introduzido no Microsoft Exchange Server 2007 Service Pack 1 (SP1).</span><span class="sxs-lookup"><span data-stu-id="27b98-106">This element was introduced in Microsoft Exchange Server 2007 Service Pack 1 (SP1).</span></span> 
  
```xml
<TasksFolderPermissionLevel>
   None or Editor or Reviewer or Author or Custom
</TasksFolderPermissionLevel>
```

<span data-ttu-id="27b98-107">**DelegateFolderPermissionLevelType**</span><span class="sxs-lookup"><span data-stu-id="27b98-107">**DelegateFolderPermissionLevelType**</span></span>

## <a name="attributes-and-elements"></a><span data-ttu-id="27b98-108">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="27b98-108">Attributes and elements</span></span>

<span data-ttu-id="27b98-109">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="27b98-109">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="27b98-110">Atributos</span><span class="sxs-lookup"><span data-stu-id="27b98-110">Attributes</span></span>

<span data-ttu-id="27b98-111">Nenhum</span><span class="sxs-lookup"><span data-stu-id="27b98-111">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="27b98-112">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="27b98-112">Child elements</span></span>

<span data-ttu-id="27b98-113">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="27b98-113">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="27b98-114">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="27b98-114">Parent elements</span></span>

|<span data-ttu-id="27b98-115">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="27b98-115">**Element**</span></span>|<span data-ttu-id="27b98-116">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="27b98-116">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="27b98-117">DelegatePermissions</span><span class="sxs-lookup"><span data-stu-id="27b98-117">DelegatePermissions</span></span>](delegatepermissions.md) <br/> |<span data-ttu-id="27b98-118">Contém as configurações de nível de permissão de representante para um usuário.</span><span class="sxs-lookup"><span data-stu-id="27b98-118">Contains the delegate permission level settings for a user.</span></span> <span data-ttu-id="27b98-119">Este elemento foi introduzido no Exchange 2007 SP1.</span><span class="sxs-lookup"><span data-stu-id="27b98-119">This element was introduced in Exchange 2007 SP1.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="27b98-120">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="27b98-120">Text value</span></span>

<span data-ttu-id="27b98-121">A tabela a seguir lista os valores de texto que representam os níveis de permissão.</span><span class="sxs-lookup"><span data-stu-id="27b98-121">The following table lists the text values that represent the permission levels.</span></span>
  
<span data-ttu-id="27b98-122">**Valores de texto do nível de permissão**</span><span class="sxs-lookup"><span data-stu-id="27b98-122">**Permission level text values**</span></span>

|<span data-ttu-id="27b98-123">**Nível de permissão**</span><span class="sxs-lookup"><span data-stu-id="27b98-123">**Permission level**</span></span>|<span data-ttu-id="27b98-124">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="27b98-124">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="27b98-125">Nenhum</span><span class="sxs-lookup"><span data-stu-id="27b98-125">None</span></span>  <br/> |<span data-ttu-id="27b98-126">O usuário delegado não tem permissões de acesso à pasta tarefas.</span><span class="sxs-lookup"><span data-stu-id="27b98-126">The delegate user has no access permissions to the Tasks folder.</span></span>  <br/> |
|<span data-ttu-id="27b98-127">Revisor</span><span class="sxs-lookup"><span data-stu-id="27b98-127">Reviewer</span></span>  <br/> |<span data-ttu-id="27b98-128">O usuário delegado pode ler itens na pasta tarefas.</span><span class="sxs-lookup"><span data-stu-id="27b98-128">The delegate user can read items in the Tasks folder.</span></span>  <br/> |
|<span data-ttu-id="27b98-129">Autor</span><span class="sxs-lookup"><span data-stu-id="27b98-129">Author</span></span>  <br/> |<span data-ttu-id="27b98-130">O usuário delegado pode ler e criar itens na pasta tarefas.</span><span class="sxs-lookup"><span data-stu-id="27b98-130">The delegate user can read and create items in the Tasks folder.</span></span>  <br/> |
|<span data-ttu-id="27b98-131">Editor</span><span class="sxs-lookup"><span data-stu-id="27b98-131">Editor</span></span>  <br/> |<span data-ttu-id="27b98-132">O usuário delegado pode ler, criar e modificar itens na pasta tarefas.</span><span class="sxs-lookup"><span data-stu-id="27b98-132">The delegate user can read, create, and modify items in the Tasks folder.</span></span>  <br/> |
|<span data-ttu-id="27b98-133">Personalizado</span><span class="sxs-lookup"><span data-stu-id="27b98-133">Custom</span></span>  <br/> |<span data-ttu-id="27b98-134">O usuário delegado tem permissões de acesso personalizadas à pasta tarefas.</span><span class="sxs-lookup"><span data-stu-id="27b98-134">The delegate user has custom access permissions to the Tasks folder.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="27b98-135">Comentários</span><span class="sxs-lookup"><span data-stu-id="27b98-135">Remarks</span></span>

<span data-ttu-id="27b98-136">O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o Microsoft Exchange Server 2007 que tem a função de servidor de acesso para Cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="27b98-136">The schema that describes this element is located in the EWS virtual directory of the computer that is running Microsoft Exchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="27b98-137">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="27b98-137">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="27b98-138">Namespace</span><span class="sxs-lookup"><span data-stu-id="27b98-138">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="27b98-139">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="27b98-139">Schema Name</span></span>  <br/> |<span data-ttu-id="27b98-140">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="27b98-140">Types schema</span></span>  <br/> |
|<span data-ttu-id="27b98-141">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="27b98-141">Validation File</span></span>  <br/> |<span data-ttu-id="27b98-142">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="27b98-142">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="27b98-143">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="27b98-143">Can be Empty</span></span>  <br/> |<span data-ttu-id="27b98-144">False</span><span class="sxs-lookup"><span data-stu-id="27b98-144">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="27b98-145">Confira também</span><span class="sxs-lookup"><span data-stu-id="27b98-145">See also</span></span>

- [<span data-ttu-id="27b98-146">Operação AddDelegate</span><span class="sxs-lookup"><span data-stu-id="27b98-146">AddDelegate operation</span></span>](adddelegate-operation.md)
- [<span data-ttu-id="27b98-147">Operação UpdateDelegate</span><span class="sxs-lookup"><span data-stu-id="27b98-147">UpdateDelegate operation</span></span>](updatedelegate-operation.md)
- [<span data-ttu-id="27b98-148">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="27b98-148">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
- [<span data-ttu-id="27b98-149">Adicionar representantes</span><span class="sxs-lookup"><span data-stu-id="27b98-149">Adding Delegates</span></span>](https://msdn.microsoft.com/library/3a744150-66a3-4a13-9433-793603ba5038%28Office.15%29.aspx)

