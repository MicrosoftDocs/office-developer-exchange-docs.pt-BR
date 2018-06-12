---
title: DelegatePermissions
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- DelegatePermissions
api_type:
- schema
ms.assetid: 292badc7-bab3-4368-9d7c-9a8b7edb279b
description: O elemento DelegatePermissions contém as configurações de nível de permissão do representante de um usuário. Este elemento foi introduzido no Microsoft Exchange Server 2007 Service Pack 1 (SP1).
ms.openlocfilehash: 319592b6c3386a07b3094115c335c7fb8ffe1130
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19751718"
---
# <a name="delegatepermissions"></a><span data-ttu-id="e5ba5-104">DelegatePermissions</span><span class="sxs-lookup"><span data-stu-id="e5ba5-104">DelegatePermissions</span></span>

<span data-ttu-id="e5ba5-105">O elemento **DelegatePermissions** contém as configurações de nível de permissão do representante de um usuário.</span><span class="sxs-lookup"><span data-stu-id="e5ba5-105">The **DelegatePermissions** element contains the delegate permission-level settings for a user.</span></span> <span data-ttu-id="e5ba5-106">Este elemento foi introduzido no Microsoft Exchange Server 2007 Service Pack 1 (SP1).</span><span class="sxs-lookup"><span data-stu-id="e5ba5-106">This element was introduced in Microsoft Exchange Server 2007 Service Pack 1 (SP1).</span></span> 
  
```xml
<DelegatePermissions>
   <CalendarFolderPermissionLevel/>
   <TasksFolderPermissionLevel/>
   <InboxFolderPermissionLevel/>
   <ContactsFolderPermissionLevel/>
   <NotesFolderPermissionLevel/>
   <JournalFolderPermissionLevel/>
</DelegatePermissions>
```

<span data-ttu-id="e5ba5-107">**DelegatePermissionsType**</span><span class="sxs-lookup"><span data-stu-id="e5ba5-107">**DelegatePermissionsType**</span></span>

## <a name="attributes-and-elements"></a><span data-ttu-id="e5ba5-108">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="e5ba5-108">Attributes and elements</span></span>

<span data-ttu-id="e5ba5-109">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="e5ba5-109">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="e5ba5-110">Atributos</span><span class="sxs-lookup"><span data-stu-id="e5ba5-110">Attributes</span></span>

<span data-ttu-id="e5ba5-111">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="e5ba5-111">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="e5ba5-112">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="e5ba5-112">Child elements</span></span>

|<span data-ttu-id="e5ba5-113">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="e5ba5-113">**Element**</span></span>|<span data-ttu-id="e5ba5-114">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="e5ba5-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="e5ba5-115">CalendarFolderPermissionLevel</span><span class="sxs-lookup"><span data-stu-id="e5ba5-115">CalendarFolderPermissionLevel</span></span>](calendarfolderpermissionlevel.md) <br/> |<span data-ttu-id="e5ba5-116">Contém as permissões para a pasta de calendário padrão.</span><span class="sxs-lookup"><span data-stu-id="e5ba5-116">Contains the permissions for the default Calendar folder.</span></span> <span data-ttu-id="e5ba5-117">Este elemento foi introduzido no Exchange 2007 SP1.</span><span class="sxs-lookup"><span data-stu-id="e5ba5-117">This element was introduced in Exchange 2007 SP1.</span></span>  <br/> |
|[<span data-ttu-id="e5ba5-118">TasksFolderPermissionLevel</span><span class="sxs-lookup"><span data-stu-id="e5ba5-118">TasksFolderPermissionLevel</span></span>](tasksfolderpermissionlevel.md) <br/> |<span data-ttu-id="e5ba5-119">Contém as permissões para a pasta de tarefa padrão.</span><span class="sxs-lookup"><span data-stu-id="e5ba5-119">Contains the permissions for the default Task folder.</span></span> <span data-ttu-id="e5ba5-120">Este elemento foi introduzido no Exchange 2007 SP1.</span><span class="sxs-lookup"><span data-stu-id="e5ba5-120">This element was introduced in Exchange 2007 SP1.</span></span>  <br/> |
|[<span data-ttu-id="e5ba5-121">InboxFolderPermissionLevel</span><span class="sxs-lookup"><span data-stu-id="e5ba5-121">InboxFolderPermissionLevel</span></span>](inboxfolderpermissionlevel.md) <br/> |<span data-ttu-id="e5ba5-122">Contém as permissões para a pasta de caixa de entrada padrão.</span><span class="sxs-lookup"><span data-stu-id="e5ba5-122">Contains the permissions for the default Inbox folder.</span></span> <span data-ttu-id="e5ba5-123">Este elemento foi introduzido no Exchange 2007 SP1.</span><span class="sxs-lookup"><span data-stu-id="e5ba5-123">This element was introduced in Exchange 2007 SP1.</span></span>  <br/> |
|[<span data-ttu-id="e5ba5-124">ContactsFolderPermissionLevel</span><span class="sxs-lookup"><span data-stu-id="e5ba5-124">ContactsFolderPermissionLevel</span></span>](contactsfolderpermissionlevel.md) <br/> |<span data-ttu-id="e5ba5-125">Contém as permissões para a pasta padrão Contatos.</span><span class="sxs-lookup"><span data-stu-id="e5ba5-125">Contains the permissions for the default Contacts folder.</span></span> <span data-ttu-id="e5ba5-126">Este elemento foi introduzido no Exchange 2007 SP1.</span><span class="sxs-lookup"><span data-stu-id="e5ba5-126">This element was introduced in Exchange 2007 SP1.</span></span>  <br/> |
|[<span data-ttu-id="e5ba5-127">NotesFolderPermissionLevel</span><span class="sxs-lookup"><span data-stu-id="e5ba5-127">NotesFolderPermissionLevel</span></span>](notesfolderpermissionlevel.md) <br/> |<span data-ttu-id="e5ba5-128">Contém as permissões para a pasta de anotações padrão.</span><span class="sxs-lookup"><span data-stu-id="e5ba5-128">Contains the permissions for the default Notes folder.</span></span> <span data-ttu-id="e5ba5-129">Este elemento foi introduzido no Exchange 2007 SP1.</span><span class="sxs-lookup"><span data-stu-id="e5ba5-129">This element was introduced in Exchange 2007 SP1.</span></span>  <br/> |
|[<span data-ttu-id="e5ba5-130">JournalFolderPermissionLevel</span><span class="sxs-lookup"><span data-stu-id="e5ba5-130">JournalFolderPermissionLevel</span></span>](journalfolderpermissionlevel.md) <br/> |<span data-ttu-id="e5ba5-131">Contém as permissões para a pasta de diário padrão.</span><span class="sxs-lookup"><span data-stu-id="e5ba5-131">Contains the permissions for the default Journal folder.</span></span> <span data-ttu-id="e5ba5-132">Este elemento foi introduzido no Exchange 2007 SP1.</span><span class="sxs-lookup"><span data-stu-id="e5ba5-132">This element was introduced in Exchange 2007 SP1.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="e5ba5-133">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="e5ba5-133">Parent elements</span></span>

|<span data-ttu-id="e5ba5-134">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="e5ba5-134">**Element**</span></span>|<span data-ttu-id="e5ba5-135">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="e5ba5-135">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="e5ba5-136">DelegateUser</span><span class="sxs-lookup"><span data-stu-id="e5ba5-136">DelegateUser</span></span>](delegateuser.md) <br/> |<span data-ttu-id="e5ba5-137">Identifica um único representante para adicionar ou atualizar em uma caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="e5ba5-137">Identifies a single delegate to add or update in a mailbox.</span></span> <span data-ttu-id="e5ba5-138">Este elemento foi introduzido no Exchange 2007 SP1.</span><span class="sxs-lookup"><span data-stu-id="e5ba5-138">This element was introduced in Exchange 2007 SP1.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="e5ba5-139">Coment�rios</span><span class="sxs-lookup"><span data-stu-id="e5ba5-139">Remarks</span></span>

<span data-ttu-id="e5ba5-140">O esquema que descreve este elemento está localizado no diretório virtual EWS do computador que está executando o Microsoft Exchange Server 2007 que possui a função de servidor acesso para cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="e5ba5-140">The schema that describes this element is located in the EWS virtual directory of the computer that is running Microsoft Exchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="e5ba5-141">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="e5ba5-141">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="e5ba5-142">Namespace</span><span class="sxs-lookup"><span data-stu-id="e5ba5-142">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="e5ba5-143">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="e5ba5-143">Schema Name</span></span>  <br/> |<span data-ttu-id="e5ba5-144">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="e5ba5-144">Types schema</span></span>  <br/> |
|<span data-ttu-id="e5ba5-145">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="e5ba5-145">Validation File</span></span>  <br/> |<span data-ttu-id="e5ba5-146">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="e5ba5-146">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="e5ba5-147">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="e5ba5-147">Can be Empty</span></span>  <br/> |<span data-ttu-id="e5ba5-148">False</span><span class="sxs-lookup"><span data-stu-id="e5ba5-148">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="e5ba5-149">Ver também</span><span class="sxs-lookup"><span data-stu-id="e5ba5-149">See also</span></span>

- [<span data-ttu-id="e5ba5-150">Operação AddDelegate</span><span class="sxs-lookup"><span data-stu-id="e5ba5-150">AddDelegate operation</span></span>](adddelegate-operation.md) 
- [<span data-ttu-id="e5ba5-151">Operação UpdateDelegate</span><span class="sxs-lookup"><span data-stu-id="e5ba5-151">UpdateDelegate operation</span></span>](updatedelegate-operation.md)
- [<span data-ttu-id="e5ba5-152">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="e5ba5-152">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
- [<span data-ttu-id="e5ba5-153">Adicionando representantes</span><span class="sxs-lookup"><span data-stu-id="e5ba5-153">Adding Delegates</span></span>](http://msdn.microsoft.com/library/3a744150-66a3-4a13-9433-793603ba5038%28Office.15%29.aspx)

