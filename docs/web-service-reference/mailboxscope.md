---
title: MailboxScope
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: c9778823-f290-4827-ba19-5f391ed4f877
description: O elemento MailboxScope identifica se uma pesquisa ou busca de uma conversa deve abranger a caixa de correio principal, a caixa de correio de arquivo morto ou a caixa de correio principal e de arquivo morto.
ms.openlocfilehash: 92823c06d4fe186917c3cfb532eda821bd6a95a7
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44455370"
---
# <a name="mailboxscope"></a><span data-ttu-id="e7cd8-103">MailboxScope</span><span class="sxs-lookup"><span data-stu-id="e7cd8-103">MailboxScope</span></span>

<span data-ttu-id="e7cd8-104">O elemento **MailboxScope** identifica se uma pesquisa ou busca de uma conversa deve abranger a caixa de correio principal, a caixa de correio de arquivo morto ou a caixa de correio principal e de arquivo morto.</span><span class="sxs-lookup"><span data-stu-id="e7cd8-104">The **MailboxScope** element identifies whether a search or fetch for a conversation should span either the primary mailbox, archive mailbox, or both the primary and archive mailbox.</span></span> 
  
```XML
<MailboxScope> PrimaryOnly | ArchiveOnly | All </MailboxScope>
```

<span data-ttu-id="e7cd8-105">**MailboxSearchLocationType**</span><span class="sxs-lookup"><span data-stu-id="e7cd8-105">**MailboxSearchLocationType**</span></span>

## <a name="attributes-and-elements"></a><span data-ttu-id="e7cd8-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="e7cd8-106">Attributes and elements</span></span>

<span data-ttu-id="e7cd8-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="e7cd8-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="e7cd8-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="e7cd8-108">Attributes</span></span>

<span data-ttu-id="e7cd8-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="e7cd8-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="e7cd8-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="e7cd8-110">Child elements</span></span>

<span data-ttu-id="e7cd8-111">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="e7cd8-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="e7cd8-112">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="e7cd8-112">Parent elements</span></span>

<span data-ttu-id="e7cd8-113">[FindConversation](findconversation.md)  |  [GetConversationItems](getconversationitems.md)  |  [Conversa (conversatype)](conversation-conversationtype.md)</span><span class="sxs-lookup"><span data-stu-id="e7cd8-113">[FindConversation](findconversation.md) | [GetConversationItems](getconversationitems.md) | [Conversation (ConversationType)](conversation-conversationtype.md)</span></span>
  
## <a name="text-value"></a><span data-ttu-id="e7cd8-114">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="e7cd8-114">Text value</span></span>

<span data-ttu-id="e7cd8-115">O valor de texto do elemento **MailboxScope** é o escopo para localizar ou obter itens em uma conversa entre caixas de correio primárias, caixas de correio de arquivo morto ou caixas de correio primárias e de arquivo morto.</span><span class="sxs-lookup"><span data-stu-id="e7cd8-115">The text value of the **MailboxScope** element is the scope for finding or getting items in a conversation across either primary mailboxes, archive mailboxes, or both primary and archive mailboxes.</span></span> <span data-ttu-id="e7cd8-116">Um valor de texto **PrimaryOnly** indica um escopo que direciona a caixa de correio principal de um usuário.</span><span class="sxs-lookup"><span data-stu-id="e7cd8-116">A text value of **PrimaryOnly** indicates a scope that targets the primary mailbox for a user.</span></span> <span data-ttu-id="e7cd8-117">Um valor de texto **ArchiveOnly** indica um escopo direcionado para a caixa de correio de arquivo morto de um usuário.</span><span class="sxs-lookup"><span data-stu-id="e7cd8-117">A text value of **ArchiveOnly** indicates a scope that targets the archive mailbox for a user.</span></span> <span data-ttu-id="e7cd8-118">Um valor de texto **All** indica um escopo que direciona a caixa de correio principal e a caixa de correio de arquivo morto.</span><span class="sxs-lookup"><span data-stu-id="e7cd8-118">A text value of **All** indicates a scope that targets both the primary mailbox and archive mailbox.</span></span> 
  
## <a name="remarks"></a><span data-ttu-id="e7cd8-119">Comentários</span><span class="sxs-lookup"><span data-stu-id="e7cd8-119">Remarks</span></span>

<span data-ttu-id="e7cd8-120">Este elemento foi introduzido no Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="e7cd8-120">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="e7cd8-121">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="e7cd8-121">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="e7cd8-122">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="e7cd8-122">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="e7cd8-123">Namespace</span><span class="sxs-lookup"><span data-stu-id="e7cd8-123">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="e7cd8-124">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="e7cd8-124">Schema name</span></span>  <br/> |<span data-ttu-id="e7cd8-125">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="e7cd8-125">Messages schema</span></span>  <br/> |
|<span data-ttu-id="e7cd8-126">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="e7cd8-126">Validation file</span></span>  <br/> |<span data-ttu-id="e7cd8-127">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="e7cd8-127">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="e7cd8-128">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="e7cd8-128">Can be empty</span></span>  <br/> |<span data-ttu-id="e7cd8-129">falso</span><span class="sxs-lookup"><span data-stu-id="e7cd8-129">false</span></span>  <br/> |
   

