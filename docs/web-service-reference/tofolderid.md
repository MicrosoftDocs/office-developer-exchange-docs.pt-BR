---
title: ToFolderId
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- ToFolderId
api_type:
- schema
ms.assetid: bd6a4265-ad40-43f6-bcc4-0bf5df4e984c
description: O elemento ToFolderId representa a pasta de destino para um item movido ou copiada ou uma pasta.
ms.openlocfilehash: a48309f0b7f5c9bf667fc2eb653a0502832bc996
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19837758"
---
# <a name="tofolderid"></a><span data-ttu-id="ae2da-103">ToFolderId</span><span class="sxs-lookup"><span data-stu-id="ae2da-103">ToFolderId</span></span>

<span data-ttu-id="ae2da-104">O elemento **ToFolderId** representa a pasta de destino para um item movido ou copiada ou uma pasta.</span><span class="sxs-lookup"><span data-stu-id="ae2da-104">The **ToFolderId** element represents the destination folder for a copied or moved item or folder.</span></span> 
  
```xml
<ToFolderId>
   <FolderId/>
</ToFolderId>
```

 <span data-ttu-id="ae2da-105">**TargetFolderIdType**</span><span class="sxs-lookup"><span data-stu-id="ae2da-105">**TargetFolderIdType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="ae2da-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="ae2da-106">Attributes and elements</span></span>

<span data-ttu-id="ae2da-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="ae2da-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="ae2da-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="ae2da-108">Attributes</span></span>

<span data-ttu-id="ae2da-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="ae2da-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="ae2da-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="ae2da-110">Child elements</span></span>

|<span data-ttu-id="ae2da-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="ae2da-111">**Element**</span></span>|<span data-ttu-id="ae2da-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="ae2da-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="ae2da-113">FolderId</span><span class="sxs-lookup"><span data-stu-id="ae2da-113">FolderId</span></span>](folderid.md) <br/> |<span data-ttu-id="ae2da-114">Contém o identificador de uma pasta de destino para um item movido ou copiada ou uma pasta.</span><span class="sxs-lookup"><span data-stu-id="ae2da-114">Contains the identifier of a destination folder for a copied or moved item or folder.</span></span>  <br/> |
|[<span data-ttu-id="ae2da-115">DistinguishedFolderId</span><span class="sxs-lookup"><span data-stu-id="ae2da-115">DistinguishedFolderId</span></span>](distinguishedfolderid.md) <br/> |<span data-ttu-id="ae2da-116">Identifica uma pasta de destino nomeado para um item movido ou copiada ou uma pasta.</span><span class="sxs-lookup"><span data-stu-id="ae2da-116">Identifies a named destination folder for a copied or moved item or folder.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="ae2da-117">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="ae2da-117">Parent elements</span></span>

|<span data-ttu-id="ae2da-118">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="ae2da-118">**Element**</span></span>|<span data-ttu-id="ae2da-119">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="ae2da-119">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="ae2da-120">MoveFolder</span><span class="sxs-lookup"><span data-stu-id="ae2da-120">MoveFolder</span></span>](movefolder.md) <br/> |<span data-ttu-id="ae2da-121">Define uma solicitação para mover uma pasta no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="ae2da-121">Defines a request to move a folder in the Exchange store.</span></span>  <br/> <span data-ttu-id="ae2da-122">Este é a expressão XPath para esse elemento:</span><span class="sxs-lookup"><span data-stu-id="ae2da-122">The following is the XPath expression to this element:</span></span>  <br/>  `/MoveFolder` <br/> |
|[<span data-ttu-id="ae2da-123">CopyFolder</span><span class="sxs-lookup"><span data-stu-id="ae2da-123">CopyFolder</span></span>](copyfolder.md) <br/> |<span data-ttu-id="ae2da-124">Define uma solicitação para copiar uma pasta no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="ae2da-124">Defines a request to copy a folder in the Exchange store.</span></span>  <br/> <span data-ttu-id="ae2da-125">Este é a expressão XPath para esse elemento:</span><span class="sxs-lookup"><span data-stu-id="ae2da-125">The following is the XPath expression to this element:</span></span>  <br/>  `/CopyFolder` <br/> |
|[<span data-ttu-id="ae2da-126">MoveItem</span><span class="sxs-lookup"><span data-stu-id="ae2da-126">MoveItem</span></span>](moveitem.md) <br/> |<span data-ttu-id="ae2da-127">Define uma solicitação para mover um item no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="ae2da-127">Defines a request to move an item in the Exchange store.</span></span>  <br/> <span data-ttu-id="ae2da-128">Este é a expressão XPath para esse elemento:</span><span class="sxs-lookup"><span data-stu-id="ae2da-128">The following is the XPath expression to this element:</span></span>  <br/>  `/MoveItem` <br/> |
|[<span data-ttu-id="ae2da-129">CopyItem</span><span class="sxs-lookup"><span data-stu-id="ae2da-129">CopyItem</span></span>](copyitem.md) <br/> |<span data-ttu-id="ae2da-130">Define uma solicitação para copiar um item no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="ae2da-130">Defines a request to copy an item in the Exchange store.</span></span>  <br/> <span data-ttu-id="ae2da-131">Este é a expressão XPath para esse elemento:</span><span class="sxs-lookup"><span data-stu-id="ae2da-131">The following is the XPath expression to this element:</span></span>  <br/>  `/CopyItem` <br/> |
   
## <a name="remarks"></a><span data-ttu-id="ae2da-132">Comentários</span><span class="sxs-lookup"><span data-stu-id="ae2da-132">Remarks</span></span>

<span data-ttu-id="ae2da-133">O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o MicrosoftExchange Server 2007 que tem instalada a função de servidor de Acesso para Cliente.</span><span class="sxs-lookup"><span data-stu-id="ae2da-133">The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="ae2da-134">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="ae2da-134">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="ae2da-135">Namespace</span><span class="sxs-lookup"><span data-stu-id="ae2da-135">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="ae2da-136">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="ae2da-136">Schema Name</span></span>  <br/> |<span data-ttu-id="ae2da-137">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="ae2da-137">Messages schema</span></span>  <br/> |
|<span data-ttu-id="ae2da-138">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="ae2da-138">Validation File</span></span>  <br/> |<span data-ttu-id="ae2da-139">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="ae2da-139">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="ae2da-140">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="ae2da-140">Can be Empty</span></span>  <br/> |<span data-ttu-id="ae2da-141">False</span><span class="sxs-lookup"><span data-stu-id="ae2da-141">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="ae2da-142">Ver também</span><span class="sxs-lookup"><span data-stu-id="ae2da-142">See also</span></span>



[<span data-ttu-id="ae2da-143">Operação MoveFolder</span><span class="sxs-lookup"><span data-stu-id="ae2da-143">MoveFolder operation</span></span>](movefolder-operation.md)
  
[<span data-ttu-id="ae2da-144">Operação CopyFolder</span><span class="sxs-lookup"><span data-stu-id="ae2da-144">CopyFolder operation</span></span>](copyfolder-operation.md)
  
[<span data-ttu-id="ae2da-145">Operação MoveItem</span><span class="sxs-lookup"><span data-stu-id="ae2da-145">MoveItem operation</span></span>](moveitem-operation.md)
  
[<span data-ttu-id="ae2da-146">Operação CopyItem</span><span class="sxs-lookup"><span data-stu-id="ae2da-146">CopyItem operation</span></span>](copyitem-operation.md)

