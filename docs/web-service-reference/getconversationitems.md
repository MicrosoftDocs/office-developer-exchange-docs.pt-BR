---
title: GetConversationItems
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: 4f7bcd0f-140c-4cbc-a5ed-daeffded1df1
description: O elemento GetConversationItems define uma solicitação para obter um conjunto de itens que estão relacionados por estarem na mesma conversa.
ms.openlocfilehash: cde4bc2c39ccbc51b7436c87c4bc06e3b8d7e52c
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44457743"
---
# <a name="getconversationitems"></a><span data-ttu-id="edcaf-103">GetConversationItems</span><span class="sxs-lookup"><span data-stu-id="edcaf-103">GetConversationItems</span></span>

<span data-ttu-id="edcaf-104">O elemento **GetConversationItems** define uma solicitação para obter um conjunto de itens que estão relacionados por estarem na mesma conversa.</span><span class="sxs-lookup"><span data-stu-id="edcaf-104">The **GetConversationItems** element defines a request to get a set of items that are related by being in the same conversation.</span></span> 
  
```XML
<GetConversationItems>
   <ItemShape/>
   <FoldersToIgnore/>
   <MaxItemsToReturn/>
   <SortOrder/>
   <MailboxScope/>
   <Conversations/>
</GetConversationItems>
```

 <span data-ttu-id="edcaf-105">**GetConversationItemsType**</span><span class="sxs-lookup"><span data-stu-id="edcaf-105">**GetConversationItemsType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="edcaf-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="edcaf-106">Attributes and elements</span></span>

<span data-ttu-id="edcaf-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="edcaf-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="edcaf-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="edcaf-108">Attributes</span></span>

<span data-ttu-id="edcaf-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="edcaf-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="edcaf-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="edcaf-110">Child elements</span></span>

<span data-ttu-id="edcaf-111">[Shape](itemshape.md)  |  [FoldersToIgnore](folderstoignore.md)  |  [MaxItemsToReturn](maxitemstoreturn.md)  |  [SortOrder (ConversationNodeSortOrder)](sortorder-conversationnodesortorder.md)  |  [MailboxScope](mailboxscope.md)  |  [Conversas](conversations-ex15websvcsotherref.md)</span><span class="sxs-lookup"><span data-stu-id="edcaf-111">[ItemShape](itemshape.md) | [FoldersToIgnore](folderstoignore.md) | [MaxItemsToReturn](maxitemstoreturn.md) | [SortOrder (ConversationNodeSortOrder)](sortorder-conversationnodesortorder.md) | [MailboxScope](mailboxscope.md) | [Conversations](conversations-ex15websvcsotherref.md)</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="edcaf-112">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="edcaf-112">Parent elements</span></span>

<span data-ttu-id="edcaf-113">Nenhum</span><span class="sxs-lookup"><span data-stu-id="edcaf-113">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="edcaf-114">Comentários</span><span class="sxs-lookup"><span data-stu-id="edcaf-114">Remarks</span></span>

<span data-ttu-id="edcaf-115">Este elemento foi introduzido no Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="edcaf-115">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="edcaf-116">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="edcaf-116">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="edcaf-117">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="edcaf-117">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="edcaf-118">Namespace</span><span class="sxs-lookup"><span data-stu-id="edcaf-118">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="edcaf-119">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="edcaf-119">Schema name</span></span>  <br/> |<span data-ttu-id="edcaf-120">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="edcaf-120">Messages schema</span></span>  <br/> |
|<span data-ttu-id="edcaf-121">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="edcaf-121">Validation file</span></span>  <br/> |<span data-ttu-id="edcaf-122">messages. xsd</span><span class="sxs-lookup"><span data-stu-id="edcaf-122">messages.xsd</span></span>  <br/> |
|<span data-ttu-id="edcaf-123">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="edcaf-123">Can be empty</span></span>  <br/> |<span data-ttu-id="edcaf-124">falso</span><span class="sxs-lookup"><span data-stu-id="edcaf-124">false</span></span>  <br/> |
   

