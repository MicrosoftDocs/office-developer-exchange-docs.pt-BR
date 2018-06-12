---
title: OldFolderId
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- OldFolderId
api_type:
- schema
ms.assetid: da554a97-ab87-4950-9fc4-26b1972381bb
description: O elemento OldFolderId contém o identificador original de uma pasta que foi movido ou copiada.
ms.openlocfilehash: ef73cad73213a1e8b5341907cd22177d8e1ba628
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19824645"
---
# <a name="oldfolderid"></a><span data-ttu-id="fe92e-103">OldFolderId</span><span class="sxs-lookup"><span data-stu-id="fe92e-103">OldFolderId</span></span>

<span data-ttu-id="fe92e-104">O elemento **OldFolderId** contém o identificador original de uma pasta que foi movido ou copiada.</span><span class="sxs-lookup"><span data-stu-id="fe92e-104">The **OldFolderId** element contains the original identifier of a folder that was moved or copied.</span></span> 
  
```xml
<OldFolderId Id="" ChangeKey=""/>
```

 <span data-ttu-id="fe92e-105">**FolderIdType**</span><span class="sxs-lookup"><span data-stu-id="fe92e-105">**FolderIdType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="fe92e-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="fe92e-106">Attributes and elements</span></span>

<span data-ttu-id="fe92e-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="fe92e-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="fe92e-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="fe92e-108">Attributes</span></span>

|<span data-ttu-id="fe92e-109">**Attribute**</span><span class="sxs-lookup"><span data-stu-id="fe92e-109">**Attribute**</span></span>|<span data-ttu-id="fe92e-110">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="fe92e-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="fe92e-111">**ID de**</span><span class="sxs-lookup"><span data-stu-id="fe92e-111">**Id**</span></span> <br/> |<span data-ttu-id="fe92e-112">Contém uma cadeia de caracteres que identifica uma pasta no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="fe92e-112">Contains a string that identifies a folder in the Exchange store.</span></span> <span data-ttu-id="fe92e-113">Este atributo é necessário.</span><span class="sxs-lookup"><span data-stu-id="fe92e-113">This attribute is required.</span></span>  <br/> |
|<span data-ttu-id="fe92e-114">**ChangeKey**</span><span class="sxs-lookup"><span data-stu-id="fe92e-114">**ChangeKey**</span></span> <br/> |<span data-ttu-id="fe92e-115">Contém uma cadeia de caracteres que identifica uma versão de uma pasta que é identificada pelo atributo Id.</span><span class="sxs-lookup"><span data-stu-id="fe92e-115">Contains a string that identifies a version of a folder that is identified by the Id attribute.</span></span> <span data-ttu-id="fe92e-116">Este atributo é opcional.</span><span class="sxs-lookup"><span data-stu-id="fe92e-116">This attribute is optional.</span></span> <span data-ttu-id="fe92e-117">Use este atributo para certificar-se de que a versão correta de uma pasta é usada.</span><span class="sxs-lookup"><span data-stu-id="fe92e-117">Use this attribute to make sure that the correct version of a folder is used.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="fe92e-118">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="fe92e-118">Child elements</span></span>

<span data-ttu-id="fe92e-119">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="fe92e-119">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="fe92e-120">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="fe92e-120">Parent elements</span></span>

|<span data-ttu-id="fe92e-121">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="fe92e-121">**Element**</span></span>|<span data-ttu-id="fe92e-122">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="fe92e-122">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="fe92e-123">CopiedEvent</span><span class="sxs-lookup"><span data-stu-id="fe92e-123">CopiedEvent</span></span>](copiedevent.md) <br/> |<span data-ttu-id="fe92e-124">Representa um evento no qual uma pasta ou um item é copiada.</span><span class="sxs-lookup"><span data-stu-id="fe92e-124">Represents an event in which an item or folder is copied.</span></span>  <br/> |
|[<span data-ttu-id="fe92e-125">MovedEvent</span><span class="sxs-lookup"><span data-stu-id="fe92e-125">MovedEvent</span></span>](movedevent.md) <br/> |<span data-ttu-id="fe92e-126">Representa um evento na qual um item ou pasta é movida de uma pasta pai para outra pasta pai.</span><span class="sxs-lookup"><span data-stu-id="fe92e-126">Represents an event in which an item or folder is moved from one parent folder to another parent folder.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="fe92e-127">Coment�rios</span><span class="sxs-lookup"><span data-stu-id="fe92e-127">Remarks</span></span>

<span data-ttu-id="fe92e-128">O esquema que descreve este elemento está localizado no diretório virtual EWS do computador que está executando o Microsoft Exchange Server 2007 que possui a função de servidor acesso para cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="fe92e-128">The schema that describes this element is located in the EWS virtual directory of the computer that is running Microsoft Exchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="fe92e-129">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="fe92e-129">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="fe92e-130">Namespace</span><span class="sxs-lookup"><span data-stu-id="fe92e-130">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="fe92e-131">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="fe92e-131">Schema Name</span></span>  <br/> |<span data-ttu-id="fe92e-132">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="fe92e-132">Types schema</span></span>  <br/> |
|<span data-ttu-id="fe92e-133">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="fe92e-133">Validation File</span></span>  <br/> |<span data-ttu-id="fe92e-134">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="fe92e-134">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="fe92e-135">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="fe92e-135">Can be Empty</span></span>  <br/> |<span data-ttu-id="fe92e-136">False</span><span class="sxs-lookup"><span data-stu-id="fe92e-136">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="fe92e-137">Ver também</span><span class="sxs-lookup"><span data-stu-id="fe92e-137">See also</span></span>



[<span data-ttu-id="fe92e-138">Inscrever-se a operação</span><span class="sxs-lookup"><span data-stu-id="fe92e-138">Subscribe operation</span></span>](subscribe-operation.md)
  
[<span data-ttu-id="fe92e-139">Operação GetEvents</span><span class="sxs-lookup"><span data-stu-id="fe92e-139">GetEvents operation</span></span>](getevents-operation.md)
  
[<span data-ttu-id="fe92e-140">Cancelar a operação</span><span class="sxs-lookup"><span data-stu-id="fe92e-140">Unsubscribe operation</span></span>](unsubscribe-operation.md)


- [<span data-ttu-id="fe92e-141">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="fe92e-141">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

