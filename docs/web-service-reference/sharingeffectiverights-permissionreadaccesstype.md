---
title: SharingEffectiveRights (PermissionReadAccessType)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- SharingEffectiveRights
api_type:
- schema
ms.assetid: 808bb4a1-aa2d-48c5-94b3-551b52c348bd
description: O elemento SharingEffectiveRights indica as permissões que o usuário tem para os dados de contato que está sendo compartilhados.
ms.openlocfilehash: 19e67827dd2dbff6fb70423980d670da5cc257a3
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19825486"
---
# <a name="sharingeffectiverights-permissionreadaccesstype"></a><span data-ttu-id="f3821-103">SharingEffectiveRights (PermissionReadAccessType)</span><span class="sxs-lookup"><span data-stu-id="f3821-103">SharingEffectiveRights (PermissionReadAccessType)</span></span>

<span data-ttu-id="f3821-104">O elemento **SharingEffectiveRights** indica as permissões que o usuário tem para os dados de contato que está sendo compartilhados.</span><span class="sxs-lookup"><span data-stu-id="f3821-104">The **SharingEffectiveRights** element indicates the permissions that the user has for the contact data that is being shared.</span></span> 
  
```XML
<SharingEffectiveRights>None | FullDetails</SharingEffectiveRights >
```

 <span data-ttu-id="f3821-105">**PermissionReadAccessType**</span><span class="sxs-lookup"><span data-stu-id="f3821-105">**PermissionReadAccessType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="f3821-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="f3821-106">Attributes and elements</span></span>

<span data-ttu-id="f3821-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="f3821-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="f3821-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="f3821-108">Attributes</span></span>

<span data-ttu-id="f3821-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="f3821-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="f3821-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="f3821-110">Child elements</span></span>

<span data-ttu-id="f3821-111">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="f3821-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="f3821-112">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="f3821-112">Parent elements</span></span>

|<span data-ttu-id="f3821-113">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="f3821-113">**Element**</span></span>|<span data-ttu-id="f3821-114">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="f3821-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="f3821-115">ContactsFolder</span><span class="sxs-lookup"><span data-stu-id="f3821-115">ContactsFolder</span></span>](contactsfolder.md) <br/> |<span data-ttu-id="f3821-116">Representa uma pasta de contatos que está contida em uma caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="f3821-116">Represents a Contacts folder that is contained in a mailbox.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="f3821-117">Text value</span><span class="sxs-lookup"><span data-stu-id="f3821-117">Text value</span></span>

<span data-ttu-id="f3821-118">A tabela a seguir lista os valores possíveis para o elemento **SharingEffectiveRights** .</span><span class="sxs-lookup"><span data-stu-id="f3821-118">The following table lists the possible values for the **SharingEffectiveRights** element.</span></span> 
  
<span data-ttu-id="f3821-119">**Valores de texto do elemento SharingEffectiveRights**</span><span class="sxs-lookup"><span data-stu-id="f3821-119">**SharingEffectiveRights element text values**</span></span>

|<span data-ttu-id="f3821-120">**Valor**</span><span class="sxs-lookup"><span data-stu-id="f3821-120">**Value**</span></span>|<span data-ttu-id="f3821-121">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="f3821-121">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="f3821-122">None</span><span class="sxs-lookup"><span data-stu-id="f3821-122">None</span></span>  <br/> |<span data-ttu-id="f3821-123">Indica que o usuário não tem permissão para ler itens na pasta.</span><span class="sxs-lookup"><span data-stu-id="f3821-123">Indicates that the user does not have permission to read items in the folder.</span></span>  <br/> |
|<span data-ttu-id="f3821-124">FullDetails</span><span class="sxs-lookup"><span data-stu-id="f3821-124">FullDetails</span></span>  <br/> |<span data-ttu-id="f3821-125">Indica que o usuário tem permissão para ler todos os itens na pasta.</span><span class="sxs-lookup"><span data-stu-id="f3821-125">Indicates that the user has permission to read all items in the folder.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="f3821-126">Comentários</span><span class="sxs-lookup"><span data-stu-id="f3821-126">Remarks</span></span>

<span data-ttu-id="f3821-127">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="f3821-127">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="f3821-128">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="f3821-128">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="f3821-129">Namespace</span><span class="sxs-lookup"><span data-stu-id="f3821-129">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="f3821-130">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="f3821-130">Schema Name</span></span>  <br/> |<span data-ttu-id="f3821-131">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="f3821-131">Types schema</span></span>  <br/> |
|<span data-ttu-id="f3821-132">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="f3821-132">Validation File</span></span>  <br/> |<span data-ttu-id="f3821-133">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="f3821-133">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="f3821-134">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="f3821-134">Can be Empty</span></span>  <br/> |<span data-ttu-id="f3821-135">False</span><span class="sxs-lookup"><span data-stu-id="f3821-135">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="f3821-136">Ver também</span><span class="sxs-lookup"><span data-stu-id="f3821-136">See also</span></span>



- [<span data-ttu-id="f3821-137">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="f3821-137">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

