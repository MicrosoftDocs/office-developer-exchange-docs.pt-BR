---
title: MailboxHoldResult
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: da03b877-37c6-4ecb-8549-c639f140302e
description: O elemento MailboxHoldResult contém o resultado da solicitação GetHoldOnMailboxes.
ms.openlocfilehash: 333a2d2d4a30a63a78660d167cefe75653f8ea82
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19824289"
---
# <a name="mailboxholdresult"></a><span data-ttu-id="53b07-103">MailboxHoldResult</span><span class="sxs-lookup"><span data-stu-id="53b07-103">MailboxHoldResult</span></span>

<span data-ttu-id="53b07-104">O elemento **MailboxHoldResult** contém o resultado da solicitação **GetHoldOnMailboxes** .</span><span class="sxs-lookup"><span data-stu-id="53b07-104">The **MailboxHoldResult** element contains the result of the **GetHoldOnMailboxes** request.</span></span> 
  
```XML
<MailboxHoldResult>
   <HoldId/>
   <Query/>
   <MailboxHoldStatuses/>
</MailboxHoldResult>
```

<span data-ttu-id="53b07-105">**MailboxHoldResultType**</span><span class="sxs-lookup"><span data-stu-id="53b07-105">**MailboxHoldResultType**</span></span>

## <a name="attributes-and-elements"></a><span data-ttu-id="53b07-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="53b07-106">Attributes and elements</span></span>

<span data-ttu-id="53b07-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="53b07-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="53b07-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="53b07-108">Attributes</span></span>

<span data-ttu-id="53b07-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="53b07-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="53b07-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="53b07-110">Child elements</span></span>

<span data-ttu-id="53b07-111">[HoldId](holdid.md) | [consulta](query.md) | [MailboxHoldStatuses](mailboxholdstatuses.md)</span><span class="sxs-lookup"><span data-stu-id="53b07-111">[HoldId](holdid.md) | [Query](query.md) | [MailboxHoldStatuses](mailboxholdstatuses.md)</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="53b07-112">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="53b07-112">Parent elements</span></span>

<span data-ttu-id="53b07-113">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="53b07-113">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="53b07-114">Comentários</span><span class="sxs-lookup"><span data-stu-id="53b07-114">Remarks</span></span>

<span data-ttu-id="53b07-115">Este elemento foi introduzido no Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="53b07-115">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="53b07-116">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="53b07-116">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="53b07-117">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="53b07-117">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="53b07-118">Namespace</span><span class="sxs-lookup"><span data-stu-id="53b07-118">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="53b07-119">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="53b07-119">Schema name</span></span>  <br/> |<span data-ttu-id="53b07-120">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="53b07-120">Messages schema</span></span>  <br/> |
|<span data-ttu-id="53b07-121">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="53b07-121">Validation file</span></span>  <br/> |<span data-ttu-id="53b07-122">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="53b07-122">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="53b07-123">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="53b07-123">Can be empty</span></span>  <br/> ||
   

