---
title: SyncFolderId
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- SyncFolderId
api_type:
- schema
ms.assetid: 3645fa03-236d-4e5f-b8b9-5d98f7f35fa2
description: O elemento SyncFolderId representa a pasta que contém os itens a serem sincronizados.
ms.openlocfilehash: c90a20095ca4706f0c6edae3e98eaadd6024d817
ms.sourcegitcommit: 9061fcf40c218ebe88911783f357b7df278846db
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/28/2018
ms.locfileid: "21354397"
---
# <a name="syncfolderid"></a><span data-ttu-id="8bdfa-103">SyncFolderId</span><span class="sxs-lookup"><span data-stu-id="8bdfa-103">SyncFolderId</span></span>

<span data-ttu-id="8bdfa-104">O elemento **SyncFolderId** representa a pasta que contém os itens a serem sincronizados.</span><span class="sxs-lookup"><span data-stu-id="8bdfa-104">The **SyncFolderId** element represents the folder that contains the items to synchronize.</span></span> 
  
```xml
<SyncFolderId>
   <FolderId/>
</SyncFolderId>
```

```xml
<SyncFolderId>
   <DistinguishedFolderId/> 
</SyncFolderId>
```

<span data-ttu-id="8bdfa-105">**TargetFolderIdType**</span><span class="sxs-lookup"><span data-stu-id="8bdfa-105">**TargetFolderIdType**</span></span>

## <a name="attributes-and-elements"></a><span data-ttu-id="8bdfa-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="8bdfa-106">Attributes and elements</span></span>

<span data-ttu-id="8bdfa-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="8bdfa-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="8bdfa-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="8bdfa-108">Attributes</span></span>

<span data-ttu-id="8bdfa-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="8bdfa-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="8bdfa-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="8bdfa-110">Child elements</span></span>

|<span data-ttu-id="8bdfa-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="8bdfa-111">**Element**</span></span>|<span data-ttu-id="8bdfa-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="8bdfa-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="8bdfa-113">FolderId</span><span class="sxs-lookup"><span data-stu-id="8bdfa-113">FolderId</span></span>](folderid.md) <br/> |<span data-ttu-id="8bdfa-114">Contém o identificador e alterar a chave de uma pasta.</span><span class="sxs-lookup"><span data-stu-id="8bdfa-114">Contains the identifier and change key of a folder.</span></span>  <br/> |
|[<span data-ttu-id="8bdfa-115">DistinguishedFolderId</span><span class="sxs-lookup"><span data-stu-id="8bdfa-115">DistinguishedFolderId</span></span>](distinguishedfolderid.md) <br/> |<span data-ttu-id="8bdfa-116">Identifica as pastas de MicrosoftExchange Server 2007 que podem ser referidas por nome.</span><span class="sxs-lookup"><span data-stu-id="8bdfa-116">Identifies MicrosoftExchange Server 2007 folders that can be referenced by name.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="8bdfa-117">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="8bdfa-117">Parent elements</span></span>

|<span data-ttu-id="8bdfa-118">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="8bdfa-118">**Element**</span></span>|<span data-ttu-id="8bdfa-119">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="8bdfa-119">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="8bdfa-120">SyncFolderHierarchy</span><span class="sxs-lookup"><span data-stu-id="8bdfa-120">SyncFolderHierarchy</span></span>](syncfolderhierarchy.md) <br/> |<span data-ttu-id="8bdfa-121">Define uma solicitação para sincronizar uma hierarquia de pastas em um repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="8bdfa-121">Defines a request to synchronize a folder hierarchy in an Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="8bdfa-122">SyncFolderItems</span><span class="sxs-lookup"><span data-stu-id="8bdfa-122">SyncFolderItems</span></span>](syncfolderitems.md) <br/> |<span data-ttu-id="8bdfa-123">Define uma solicitação para sincronizar os itens em uma pasta de repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="8bdfa-123">Defines a request to synchronize items in an Exchange store folder.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="8bdfa-124">Comentários</span><span class="sxs-lookup"><span data-stu-id="8bdfa-124">Remarks</span></span>

<span data-ttu-id="8bdfa-125">O esquema que descreve este elemento está localizado no diretório virtual EWS do computador que está executando o Exchange Server 2007 que possui a função de servidor acesso para cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="8bdfa-125">The schema that describes this element is located in the EWS virtual directory of the computer that is running Exchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="8bdfa-126">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="8bdfa-126">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="8bdfa-127">Namespace</span><span class="sxs-lookup"><span data-stu-id="8bdfa-127">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="8bdfa-128">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="8bdfa-128">Schema name</span></span>  <br/> |<span data-ttu-id="8bdfa-129">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="8bdfa-129">Messages schema</span></span>  <br/> |
|<span data-ttu-id="8bdfa-130">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="8bdfa-130">Validation file</span></span>  <br/> |<span data-ttu-id="8bdfa-131">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="8bdfa-131">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="8bdfa-132">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="8bdfa-132">Can be empty</span></span>  <br/> |<span data-ttu-id="8bdfa-133">False</span><span class="sxs-lookup"><span data-stu-id="8bdfa-133">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="8bdfa-134">Ver também</span><span class="sxs-lookup"><span data-stu-id="8bdfa-134">See also</span></span>

- [<span data-ttu-id="8bdfa-135">Operação SyncFolderItems</span><span class="sxs-lookup"><span data-stu-id="8bdfa-135">SyncFolderItems operation</span></span>](syncfolderitems-operation.md)
- [<span data-ttu-id="8bdfa-136">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="8bdfa-136">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

