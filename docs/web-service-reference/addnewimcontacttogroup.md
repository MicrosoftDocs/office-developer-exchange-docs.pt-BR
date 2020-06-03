---
title: AddNewImContactToGroup
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: d5913619-0c13-429d-b9d2-057e8af220f1
description: O elemento AddNewImContactToGroup define uma solicitação para adicionar um novo contato de sistema de mensagens instantâneas a um grupo de mensagens instantâneas.
ms.openlocfilehash: c493ba81b23832a462acd425eb60297801f8768f
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44463647"
---
# <a name="addnewimcontacttogroup"></a><span data-ttu-id="334aa-103">AddNewImContactToGroup</span><span class="sxs-lookup"><span data-stu-id="334aa-103">AddNewImContactToGroup</span></span>

<span data-ttu-id="334aa-104">O elemento **AddNewImContactToGroup** define uma solicitação para adicionar um novo contato de sistema de mensagens instantâneas a um grupo de mensagens instantâneas.</span><span class="sxs-lookup"><span data-stu-id="334aa-104">The **AddNewImContactToGroup** element defines a request to add a new instant messaging contact to an instant messaging group.</span></span> 
  
```XML
<AddNewImContactToGroup>
   <ImAddress/>
   <DisplayName/>
   <GroupId/>
</AddNewImContactToGroup>
```

 <span data-ttu-id="334aa-105">**AddNewImContactToGroupType**</span><span class="sxs-lookup"><span data-stu-id="334aa-105">**AddNewImContactToGroupType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="334aa-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="334aa-106">Attributes and elements</span></span>

<span data-ttu-id="334aa-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="334aa-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="334aa-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="334aa-108">Attributes</span></span>

<span data-ttu-id="334aa-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="334aa-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="334aa-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="334aa-110">Child elements</span></span>

<span data-ttu-id="334aa-111">[IMAddress (NonEmptyStringType)](imaddress-nonemptystringtype.md)  |  [DisplayName (NonEmptyStringType)](displayname-nonemptystringtype.md)  |  [GroupId](groupid.md)</span><span class="sxs-lookup"><span data-stu-id="334aa-111">[ImAddress (NonEmptyStringType)](imaddress-nonemptystringtype.md) | [DisplayName (NonEmptyStringType)](displayname-nonemptystringtype.md) | [GroupId](groupid.md)</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="334aa-112">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="334aa-112">Parent elements</span></span>

<span data-ttu-id="334aa-113">Nenhum</span><span class="sxs-lookup"><span data-stu-id="334aa-113">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="334aa-114">Comentários</span><span class="sxs-lookup"><span data-stu-id="334aa-114">Remarks</span></span>

<span data-ttu-id="334aa-115">Este elemento foi introduzido no Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="334aa-115">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="334aa-116">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="334aa-116">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="334aa-117">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="334aa-117">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="334aa-118">Namespace</span><span class="sxs-lookup"><span data-stu-id="334aa-118">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="334aa-119">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="334aa-119">Schema name</span></span>  <br/> |<span data-ttu-id="334aa-120">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="334aa-120">Messages schema</span></span>  <br/> |
|<span data-ttu-id="334aa-121">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="334aa-121">Validation file</span></span>  <br/> |<span data-ttu-id="334aa-122">messages. xsd</span><span class="sxs-lookup"><span data-stu-id="334aa-122">messages.xsd</span></span>  <br/> |
|<span data-ttu-id="334aa-123">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="334aa-123">Can be empty</span></span>  <br/> |<span data-ttu-id="334aa-124">falso</span><span class="sxs-lookup"><span data-stu-id="334aa-124">false</span></span>  <br/> |
   

