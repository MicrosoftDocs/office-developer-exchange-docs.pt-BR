---
title: GlobalHasAttachments
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- GlobalHasAttachments
api_type:
- schema
ms.assetid: 3d075e93-14bc-479d-957f-9b7873d1db39
description: O elemento GlobalHasAttachments contém um valor que indica se pelo menos um item de conversa em uma caixa de correio tem um anexo.
ms.openlocfilehash: e314e8e5c06ca7d7820b910c05b381765e88911f
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44459473"
---
# <a name="globalhasattachments"></a><span data-ttu-id="bb10d-103">GlobalHasAttachments</span><span class="sxs-lookup"><span data-stu-id="bb10d-103">GlobalHasAttachments</span></span>

<span data-ttu-id="bb10d-104">O elemento **GlobalHasAttachments** contém um valor que indica se pelo menos um item de conversa em uma caixa de correio tem um anexo.</span><span class="sxs-lookup"><span data-stu-id="bb10d-104">The **GlobalHasAttachments** element contains a value that indicates whether at least one conversation item in a mailbox has an attachment.</span></span> 
  
[<span data-ttu-id="bb10d-105">FindConversationResponse</span><span class="sxs-lookup"><span data-stu-id="bb10d-105">FindConversationResponse</span></span>](findconversationresponse.md)
  
[<span data-ttu-id="bb10d-106">Conversas</span><span class="sxs-lookup"><span data-stu-id="bb10d-106">Conversations</span></span>](conversations-ex15websvcsotherref.md)
  
[<span data-ttu-id="bb10d-107">Conversa (Conversatype)</span><span class="sxs-lookup"><span data-stu-id="bb10d-107">Conversation (ConversationType)</span></span>](conversation-conversationtype.md)
  
[<span data-ttu-id="bb10d-108">GlobalHasAttachments</span><span class="sxs-lookup"><span data-stu-id="bb10d-108">GlobalHasAttachments</span></span>](globalhasattachments.md)
  
```XML
<GlobalHasAttachments/>
```

 <span data-ttu-id="bb10d-109">**Boolean**</span><span class="sxs-lookup"><span data-stu-id="bb10d-109">**Boolean**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="bb10d-110">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="bb10d-110">Attributes and elements</span></span>

<span data-ttu-id="bb10d-111">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="bb10d-111">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="bb10d-112">Atributos</span><span class="sxs-lookup"><span data-stu-id="bb10d-112">Attributes</span></span>

<span data-ttu-id="bb10d-113">Nenhum</span><span class="sxs-lookup"><span data-stu-id="bb10d-113">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="bb10d-114">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="bb10d-114">Child elements</span></span>

<span data-ttu-id="bb10d-115">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="bb10d-115">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="bb10d-116">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="bb10d-116">Parent elements</span></span>

|<span data-ttu-id="bb10d-117">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="bb10d-117">**Element**</span></span>|<span data-ttu-id="bb10d-118">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="bb10d-118">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="bb10d-119">Conversa (Conversatype)</span><span class="sxs-lookup"><span data-stu-id="bb10d-119">Conversation (ConversationType)</span></span>](conversation-conversationtype.md) <br/> |<span data-ttu-id="bb10d-120">Representa uma única conversa.</span><span class="sxs-lookup"><span data-stu-id="bb10d-120">Represents a single conversation.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="bb10d-121">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="bb10d-121">Text value</span></span>

<span data-ttu-id="bb10d-122">O valor do elemento **GlobalHasAttachments** indica se pelo menos um item de conversa em uma caixa de correio tem um anexo.</span><span class="sxs-lookup"><span data-stu-id="bb10d-122">The value of the **GlobalHasAttachments** element indicates whether at least one conversation item in a mailbox has an attachment.</span></span> <span data-ttu-id="bb10d-123">Um valor de texto que representa um valor booliano é necessário.</span><span class="sxs-lookup"><span data-stu-id="bb10d-123">A text value that represents a Boolean value is required.</span></span> <span data-ttu-id="bb10d-124">Um valor **true** significa que a conversa tem pelo menos um anexo visível.</span><span class="sxs-lookup"><span data-stu-id="bb10d-124">A value of **true** means that the conversation has at least one visible attachment.</span></span> <span data-ttu-id="bb10d-125">Um valor **false** significa que a conversa não tem anexos ou tem apenas anexos ocultos.</span><span class="sxs-lookup"><span data-stu-id="bb10d-125">A value of **false** means that the conversation either has no attachments or has only hidden attachments.</span></span> 
  
## <a name="remarks"></a><span data-ttu-id="bb10d-126">Comentários</span><span class="sxs-lookup"><span data-stu-id="bb10d-126">Remarks</span></span>

<span data-ttu-id="bb10d-127">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os serviços Web do Exchange. este elemento foi introduzido no Exchange Server 2010 Service Pack 1 (SP1).</span><span class="sxs-lookup"><span data-stu-id="bb10d-127">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.This element was introduced in Exchange Server 2010 Service Pack 1 (SP1).</span></span>
  
## <a name="element-information"></a><span data-ttu-id="bb10d-128">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="bb10d-128">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="bb10d-129">Namespace</span><span class="sxs-lookup"><span data-stu-id="bb10d-129">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="bb10d-130">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="bb10d-130">Schema name</span></span>  <br/> |<span data-ttu-id="bb10d-131">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="bb10d-131">Types schema</span></span>  <br/> |
|<span data-ttu-id="bb10d-132">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="bb10d-132">Validation file</span></span>  <br/> |<span data-ttu-id="bb10d-133">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="bb10d-133">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="bb10d-134">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="bb10d-134">Can be empty</span></span>  <br/> |<span data-ttu-id="bb10d-135">False</span><span class="sxs-lookup"><span data-stu-id="bb10d-135">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="bb10d-136">Confira também</span><span class="sxs-lookup"><span data-stu-id="bb10d-136">See also</span></span>



[<span data-ttu-id="bb10d-137">Operação FindConversation</span><span class="sxs-lookup"><span data-stu-id="bb10d-137">FindConversation operation</span></span>](findconversation-operation.md)
  
[<span data-ttu-id="bb10d-138">Operação ApplyConversationAction</span><span class="sxs-lookup"><span data-stu-id="bb10d-138">ApplyConversationAction operation</span></span>](applyconversationaction-operation.md)


[<span data-ttu-id="bb10d-139">Conversas no EWS</span><span class="sxs-lookup"><span data-stu-id="bb10d-139">Conversations in EWS</span></span>](https://msdn.microsoft.com/library/91e64629-db6c-4c94-9dcb-d386232e8467%28Office.15%29.aspx)

