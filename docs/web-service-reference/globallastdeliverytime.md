---
title: GlobalLastDeliveryTime
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- GlobalLastDeliveryTime
api_type:
- schema
ms.assetid: a88dada9-c527-43a7-b2d3-31aad330def9
description: O elemento GlobalLastDeliveryTime contém o tempo de entrega da mensagem que foi recebida pela última vez nesta conversa em todas as pastas da caixa de correio.
ms.openlocfilehash: b6d4d7c1d51c206e44973a717d25df4066845ada
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44459409"
---
# <a name="globallastdeliverytime"></a><span data-ttu-id="4b5b4-103">GlobalLastDeliveryTime</span><span class="sxs-lookup"><span data-stu-id="4b5b4-103">GlobalLastDeliveryTime</span></span>

<span data-ttu-id="4b5b4-104">O elemento **GlobalLastDeliveryTime** contém o tempo de entrega da mensagem que foi recebida pela última vez nesta conversa em todas as pastas da caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="4b5b4-104">The **GlobalLastDeliveryTime** element contains the delivery time of the message that was last received in this conversation across all folders in the mailbox.</span></span> 
  
[<span data-ttu-id="4b5b4-105">FindConversationResponse</span><span class="sxs-lookup"><span data-stu-id="4b5b4-105">FindConversationResponse</span></span>](findconversationresponse.md)
  
[<span data-ttu-id="4b5b4-106">Conversas</span><span class="sxs-lookup"><span data-stu-id="4b5b4-106">Conversations</span></span>](conversations-ex15websvcsotherref.md)
  
[<span data-ttu-id="4b5b4-107">Conversa (Conversatype)</span><span class="sxs-lookup"><span data-stu-id="4b5b4-107">Conversation (ConversationType)</span></span>](conversation-conversationtype.md)
  
[<span data-ttu-id="4b5b4-108">GlobalLastDeliveryTime</span><span class="sxs-lookup"><span data-stu-id="4b5b4-108">GlobalLastDeliveryTime</span></span>](globallastdeliverytime.md)
  
```XML
<GlobalLastDeliveryTime/>
```

 <span data-ttu-id="4b5b4-109">**xs: dateTime**</span><span class="sxs-lookup"><span data-stu-id="4b5b4-109">**xs:dateTime**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="4b5b4-110">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="4b5b4-110">Attributes and elements</span></span>

<span data-ttu-id="4b5b4-111">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="4b5b4-111">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="4b5b4-112">Atributos</span><span class="sxs-lookup"><span data-stu-id="4b5b4-112">Attributes</span></span>

<span data-ttu-id="4b5b4-113">Nenhum</span><span class="sxs-lookup"><span data-stu-id="4b5b4-113">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="4b5b4-114">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="4b5b4-114">Child elements</span></span>

<span data-ttu-id="4b5b4-115">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="4b5b4-115">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="4b5b4-116">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="4b5b4-116">Parent elements</span></span>

|<span data-ttu-id="4b5b4-117">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="4b5b4-117">**Element**</span></span>|<span data-ttu-id="4b5b4-118">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="4b5b4-118">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="4b5b4-119">Conversa (Conversatype)</span><span class="sxs-lookup"><span data-stu-id="4b5b4-119">Conversation (ConversationType)</span></span>](conversation-conversationtype.md) <br/> |<span data-ttu-id="4b5b4-120">Representa uma única conversa.</span><span class="sxs-lookup"><span data-stu-id="4b5b4-120">Represents a single conversation.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="4b5b4-121">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="4b5b4-121">Text value</span></span>

<span data-ttu-id="4b5b4-122">O valor de texto do elemento **GlobalLastDeliveryTime** é a data e a hora da última mensagem recebida nesta conversa em todas as pastas da caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="4b5b4-122">The text value of the **GlobalLastDeliveryTime** element is the date and time of the message that was last received in this conversation across all folders in the mailbox.</span></span> 
  
## <a name="remarks"></a><span data-ttu-id="4b5b4-123">Comentários</span><span class="sxs-lookup"><span data-stu-id="4b5b4-123">Remarks</span></span>

<span data-ttu-id="4b5b4-124">Este elemento foi introduzido no Exchange Server 2010 Service Pack 1 (SP1). O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="4b5b4-124">This element was introduced in Exchange Server 2010 Service Pack 1 (SP1).The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="4b5b4-125">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="4b5b4-125">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="4b5b4-126">Namespace</span><span class="sxs-lookup"><span data-stu-id="4b5b4-126">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="4b5b4-127">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="4b5b4-127">Schema name</span></span>  <br/> |<span data-ttu-id="4b5b4-128">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="4b5b4-128">Types schema</span></span>  <br/> |
|<span data-ttu-id="4b5b4-129">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="4b5b4-129">Validation file</span></span>  <br/> |<span data-ttu-id="4b5b4-130">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="4b5b4-130">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="4b5b4-131">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="4b5b4-131">Can be empty</span></span>  <br/> |<span data-ttu-id="4b5b4-132">False</span><span class="sxs-lookup"><span data-stu-id="4b5b4-132">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="4b5b4-133">Confira também</span><span class="sxs-lookup"><span data-stu-id="4b5b4-133">See also</span></span>



[<span data-ttu-id="4b5b4-134">Operação FindConversation</span><span class="sxs-lookup"><span data-stu-id="4b5b4-134">FindConversation operation</span></span>](findconversation-operation.md)
  
[<span data-ttu-id="4b5b4-135">Operação ApplyConversationAction</span><span class="sxs-lookup"><span data-stu-id="4b5b4-135">ApplyConversationAction operation</span></span>](applyconversationaction-operation.md)


[<span data-ttu-id="4b5b4-136">Conversas no EWS</span><span class="sxs-lookup"><span data-stu-id="4b5b4-136">Conversations in EWS</span></span>](https://msdn.microsoft.com/library/91e64629-db6c-4c94-9dcb-d386232e8467%28Office.15%29.aspx)

