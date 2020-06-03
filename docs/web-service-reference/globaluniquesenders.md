---
title: GlobalUniqueSenders
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- GlobalUniqueSenders
api_type:
- schema
ms.assetid: 6bd9e9cb-19c8-45af-b211-dfb8a6003b1b
description: O elemento GlobalUniqueSender contém uma lista de todos os remetentes de itens de conversa na caixa de correio.
ms.openlocfilehash: 0e85e201017e175a9ffc6b923976020d4157d5b7
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44459059"
---
# <a name="globaluniquesenders"></a><span data-ttu-id="8122b-103">GlobalUniqueSenders</span><span class="sxs-lookup"><span data-stu-id="8122b-103">GlobalUniqueSenders</span></span>

<span data-ttu-id="8122b-104">O elemento **GlobalUniqueSender** contém uma lista de todos os remetentes de itens de conversa na caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="8122b-104">The **GlobalUniqueSender** element contains a list of all the senders of conversation items in the mailbox.</span></span> 
  
[<span data-ttu-id="8122b-105">FindConversationResponse</span><span class="sxs-lookup"><span data-stu-id="8122b-105">FindConversationResponse</span></span>](findconversationresponse.md)
  
[<span data-ttu-id="8122b-106">Conversas</span><span class="sxs-lookup"><span data-stu-id="8122b-106">Conversations</span></span>](conversations-ex15websvcsotherref.md)
  
[<span data-ttu-id="8122b-107">Conversa (Conversatype)</span><span class="sxs-lookup"><span data-stu-id="8122b-107">Conversation (ConversationType)</span></span>](conversation-conversationtype.md)
  
[<span data-ttu-id="8122b-108">GlobalUniqueSenders</span><span class="sxs-lookup"><span data-stu-id="8122b-108">GlobalUniqueSenders</span></span>](globaluniquesenders.md)
  
```XML
<GlobalUniqueSender>
   <String/>
</GlobalUniqueSender>
```

 <span data-ttu-id="8122b-109">**ArrayOfStringsType**</span><span class="sxs-lookup"><span data-stu-id="8122b-109">**ArrayOfStringsType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="8122b-110">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="8122b-110">Attributes and elements</span></span>

<span data-ttu-id="8122b-111">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="8122b-111">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="8122b-112">Atributos</span><span class="sxs-lookup"><span data-stu-id="8122b-112">Attributes</span></span>

<span data-ttu-id="8122b-113">Nenhum</span><span class="sxs-lookup"><span data-stu-id="8122b-113">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="8122b-114">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="8122b-114">Child elements</span></span>

|<span data-ttu-id="8122b-115">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="8122b-115">**Element**</span></span>|<span data-ttu-id="8122b-116">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="8122b-116">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="8122b-117">String</span><span class="sxs-lookup"><span data-stu-id="8122b-117">String</span></span>](string.md) <br/> |<span data-ttu-id="8122b-118">Contém um único remetente de conversa.</span><span class="sxs-lookup"><span data-stu-id="8122b-118">Contains a single conversation sender.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="8122b-119">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="8122b-119">Parent elements</span></span>

|<span data-ttu-id="8122b-120">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="8122b-120">**Element**</span></span>|<span data-ttu-id="8122b-121">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="8122b-121">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="8122b-122">Conversa (Conversatype)</span><span class="sxs-lookup"><span data-stu-id="8122b-122">Conversation (ConversationType)</span></span>](conversation-conversationtype.md) <br/> |<span data-ttu-id="8122b-123">Representa uma única conversa.</span><span class="sxs-lookup"><span data-stu-id="8122b-123">Represents a single conversation.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="8122b-124">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="8122b-124">Text value</span></span>

<span data-ttu-id="8122b-125">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="8122b-125">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="8122b-126">Comentários</span><span class="sxs-lookup"><span data-stu-id="8122b-126">Remarks</span></span>

<span data-ttu-id="8122b-127">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os serviços Web do Exchange. este elemento foi introduzido no Exchange Server 2010 Service Pack 1 (SP1).</span><span class="sxs-lookup"><span data-stu-id="8122b-127">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.This element was introduced in Exchange Server 2010 Service Pack 1 (SP1).</span></span>
  
## <a name="element-information"></a><span data-ttu-id="8122b-128">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="8122b-128">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="8122b-129">Namespace</span><span class="sxs-lookup"><span data-stu-id="8122b-129">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="8122b-130">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="8122b-130">Schema name</span></span>  <br/> |<span data-ttu-id="8122b-131">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="8122b-131">Types schema</span></span>  <br/> |
|<span data-ttu-id="8122b-132">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="8122b-132">Validation file</span></span>  <br/> |<span data-ttu-id="8122b-133">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="8122b-133">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="8122b-134">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="8122b-134">Can be empty</span></span>  <br/> |<span data-ttu-id="8122b-135">False</span><span class="sxs-lookup"><span data-stu-id="8122b-135">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="8122b-136">Confira também</span><span class="sxs-lookup"><span data-stu-id="8122b-136">See also</span></span>



[<span data-ttu-id="8122b-137">Operação FindConversation</span><span class="sxs-lookup"><span data-stu-id="8122b-137">FindConversation operation</span></span>](findconversation-operation.md)
  
[<span data-ttu-id="8122b-138">Operação ApplyConversationAction</span><span class="sxs-lookup"><span data-stu-id="8122b-138">ApplyConversationAction operation</span></span>](applyconversationaction-operation.md)


[<span data-ttu-id="8122b-139">Conversas no EWS</span><span class="sxs-lookup"><span data-stu-id="8122b-139">Conversations in EWS</span></span>](https://msdn.microsoft.com/library/91e64629-db6c-4c94-9dcb-d386232e8467%28Office.15%29.aspx)

