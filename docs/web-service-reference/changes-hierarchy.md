---
title: Alterações (hierarquia)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- Changes
api_type:
- schema
ms.assetid: 918a0d1f-90a5-4eef-9592-07e15bef94e6
description: O elemento de alterações contém uma matriz sequenciada dos tipos de alteração que representam o tipo das diferenças entre as pastas no cliente e as pastas no computador que está executando o Microsoft Exchange Server 2007.
ms.openlocfilehash: 15e4f9f37c5e4a4083260dcf379a49beb2260030
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19751391"
---
# <a name="changes-hierarchy"></a><span data-ttu-id="7f7fd-103">Alterações (hierarquia)</span><span class="sxs-lookup"><span data-stu-id="7f7fd-103">Changes (Hierarchy)</span></span>

<span data-ttu-id="7f7fd-104">O elemento de **alterações** contém uma matriz sequenciada dos tipos de alteração que representam o tipo das diferenças entre as pastas no cliente e as pastas no computador que está executando o Microsoft Exchange Server 2007.</span><span class="sxs-lookup"><span data-stu-id="7f7fd-104">The **Changes** element contains a sequenced array of change types that represent the type of differences between the folders on the client and the folders on the computer that is running Microsoft Exchange Server 2007.</span></span> 
  
[<span data-ttu-id="7f7fd-105">SyncFolderHierarchyResponse</span><span class="sxs-lookup"><span data-stu-id="7f7fd-105">SyncFolderHierarchyResponse</span></span>](syncfolderhierarchyresponse.md)
  
[<span data-ttu-id="7f7fd-106">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="7f7fd-106">ResponseMessages</span></span>](responsemessages.md)
  
[<span data-ttu-id="7f7fd-107">SyncFolderHierarchyResponseMessage</span><span class="sxs-lookup"><span data-stu-id="7f7fd-107">SyncFolderHierarchyResponseMessage</span></span>](syncfolderhierarchyresponsemessage.md)
  
[<span data-ttu-id="7f7fd-108">Alterações (hierarquia)</span><span class="sxs-lookup"><span data-stu-id="7f7fd-108">Changes (Hierarchy)</span></span>](changes-hierarchy.md)
  
```xml
<Changes>
   <Create/>
   <Update/>
   <Delete/>
</Changes>
```

 <span data-ttu-id="7f7fd-109">**SyncFolderHierarchyChangesType**</span><span class="sxs-lookup"><span data-stu-id="7f7fd-109">**SyncFolderHierarchyChangesType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="7f7fd-110">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="7f7fd-110">Attributes and elements</span></span>

<span data-ttu-id="7f7fd-111">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="7f7fd-111">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="7f7fd-112">Atributos</span><span class="sxs-lookup"><span data-stu-id="7f7fd-112">Attributes</span></span>

<span data-ttu-id="7f7fd-113">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="7f7fd-113">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="7f7fd-114">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="7f7fd-114">Child elements</span></span>

|<span data-ttu-id="7f7fd-115">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="7f7fd-115">**Element**</span></span>|<span data-ttu-id="7f7fd-116">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="7f7fd-116">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="7f7fd-117">Criar (FolderSync)</span><span class="sxs-lookup"><span data-stu-id="7f7fd-117">Create (FolderSync)</span></span>](create-foldersync.md) <br/> |<span data-ttu-id="7f7fd-118">Identifica uma única pasta para criar no repositório de cliente local.</span><span class="sxs-lookup"><span data-stu-id="7f7fd-118">Identifies a single folder to create in the local client store.</span></span>  <br/> |
|[<span data-ttu-id="7f7fd-119">Atualização (FolderSync)</span><span class="sxs-lookup"><span data-stu-id="7f7fd-119">Update (FolderSync)</span></span>](update-foldersync.md) <br/> |<span data-ttu-id="7f7fd-120">Identifica uma única pasta ao atualizar no repositório de cliente local.</span><span class="sxs-lookup"><span data-stu-id="7f7fd-120">Identifies a single folder to update in the local client store.</span></span>  <br/> |
|[<span data-ttu-id="7f7fd-121">Excluir (FolderSync)</span><span class="sxs-lookup"><span data-stu-id="7f7fd-121">Delete (FolderSync)</span></span>](delete-foldersync.md) <br/> |<span data-ttu-id="7f7fd-122">Identifica uma única pasta a ser excluído no repositório de cliente local.</span><span class="sxs-lookup"><span data-stu-id="7f7fd-122">Identifies a single folder to delete in the local client store.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="7f7fd-123">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="7f7fd-123">Parent elements</span></span>

|<span data-ttu-id="7f7fd-124">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="7f7fd-124">**Element**</span></span>|<span data-ttu-id="7f7fd-125">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="7f7fd-125">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="7f7fd-126">SyncFolderHierarchyResponseMessage</span><span class="sxs-lookup"><span data-stu-id="7f7fd-126">SyncFolderHierarchyResponseMessage</span></span>](syncfolderhierarchyresponsemessage.md) <br/> |<span data-ttu-id="7f7fd-127">Contém o status e o resultado de uma solicitação de SyncFolderHierarchy.</span><span class="sxs-lookup"><span data-stu-id="7f7fd-127">Contains the status and result of a SyncFolderHierarchy request.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="7f7fd-128">Text value</span><span class="sxs-lookup"><span data-stu-id="7f7fd-128">Text value</span></span>

<span data-ttu-id="7f7fd-129">É necessário um valor de texto que representa um valor booleano.</span><span class="sxs-lookup"><span data-stu-id="7f7fd-129">A text value that represents a Boolean value is required.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="7f7fd-130">Coment�rios</span><span class="sxs-lookup"><span data-stu-id="7f7fd-130">Remarks</span></span>

<span data-ttu-id="7f7fd-131">O esquema que descreve este elemento está localizado no diretório virtual EWS do Exchange 2007 computador que possui a função de servidor acesso para cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="7f7fd-131">The schema that describes this element is located in the EWS virtual directory of the Exchange 2007 computer that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="7f7fd-132">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="7f7fd-132">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="7f7fd-133">Namespace</span><span class="sxs-lookup"><span data-stu-id="7f7fd-133">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="7f7fd-134">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="7f7fd-134">Schema name</span></span>  <br/> |<span data-ttu-id="7f7fd-135">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="7f7fd-135">Messages schema</span></span>  <br/> |
|<span data-ttu-id="7f7fd-136">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="7f7fd-136">Validation file</span></span>  <br/> |<span data-ttu-id="7f7fd-137">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="7f7fd-137">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="7f7fd-138">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="7f7fd-138">Can be empty</span></span>  <br/> |<span data-ttu-id="7f7fd-139">False</span><span class="sxs-lookup"><span data-stu-id="7f7fd-139">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="7f7fd-140">Ver também</span><span class="sxs-lookup"><span data-stu-id="7f7fd-140">See also</span></span>



[<span data-ttu-id="7f7fd-141">Operação SyncFolderHierarchy</span><span class="sxs-lookup"><span data-stu-id="7f7fd-141">SyncFolderHierarchy operation</span></span>](syncfolderhierarchy-operation.md)


[<span data-ttu-id="7f7fd-142">Referência do EWS para Exchange</span><span class="sxs-lookup"><span data-stu-id="7f7fd-142">EWS reference for Exchange</span></span>](ews-reference-for-exchange.md)
  
- [<span data-ttu-id="7f7fd-143">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="7f7fd-143">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

