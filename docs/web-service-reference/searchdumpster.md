---
title: SearchDumpster
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: ddb62dce-c87a-4714-8023-a6b697a29699
description: O elemento SearchDumpster especifica se deve pesquisar no dumpster do Exchange.
ms.openlocfilehash: 067bf8ea3e589aa392c6b8ba6d4dc10b430c1f28
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44460488"
---
# <a name="searchdumpster"></a><span data-ttu-id="94120-103">SearchDumpster</span><span class="sxs-lookup"><span data-stu-id="94120-103">SearchDumpster</span></span>

<span data-ttu-id="94120-104">O elemento **SearchDumpster** especifica se deve pesquisar no dumpster do Exchange.</span><span class="sxs-lookup"><span data-stu-id="94120-104">The **SearchDumpster** element specifies whether to search in the Exchange Dumpster.</span></span> 
  
```XML
<SearchDumpster> true | false </SearchDumpster>
```

 ****
## <a name="attributes-and-elements"></a><span data-ttu-id="94120-105">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="94120-105">Attributes and elements</span></span>

<span data-ttu-id="94120-106">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="94120-106">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="94120-107">Atributos</span><span class="sxs-lookup"><span data-stu-id="94120-107">Attributes</span></span>

<span data-ttu-id="94120-108">Nenhum</span><span class="sxs-lookup"><span data-stu-id="94120-108">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="94120-109">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="94120-109">Child elements</span></span>

<span data-ttu-id="94120-110">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="94120-110">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="94120-111">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="94120-111">Parent elements</span></span>

[<span data-ttu-id="94120-112">FindMailboxStatisticsByKeywords</span><span class="sxs-lookup"><span data-stu-id="94120-112">FindMailboxStatisticsByKeywords</span></span>](findmailboxstatisticsbykeywords.md)
  
## <a name="text-value"></a><span data-ttu-id="94120-113">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="94120-113">Text value</span></span>

<span data-ttu-id="94120-114">Um valor de texto **true** para o elemento **SearchDumpster** indica que a pesquisa de estatísticas de caixa de correio inclui o dumpster do Exchange.</span><span class="sxs-lookup"><span data-stu-id="94120-114">A text value of **true** for the **SearchDumpster** element indicates that the mailbox statistics search includes the Exchange Dumpster.</span></span> <span data-ttu-id="94120-115">Um valor **false** indica que o dumpster do Exchange não é pesquisado.</span><span class="sxs-lookup"><span data-stu-id="94120-115">A value of **false** indicates that the Exchange Dumpster is not searched.</span></span> 
  
## <a name="remarks"></a><span data-ttu-id="94120-116">Comentários</span><span class="sxs-lookup"><span data-stu-id="94120-116">Remarks</span></span>

<span data-ttu-id="94120-117">Este elemento foi introduzido no Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="94120-117">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="94120-118">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="94120-118">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="94120-119">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="94120-119">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="94120-120">Namespace</span><span class="sxs-lookup"><span data-stu-id="94120-120">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="94120-121">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="94120-121">Schema name</span></span>  <br/> |<span data-ttu-id="94120-122">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="94120-122">Types schema</span></span>  <br/> |
|<span data-ttu-id="94120-123">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="94120-123">Validation file</span></span>  <br/> |<span data-ttu-id="94120-124">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="94120-124">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="94120-125">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="94120-125">Can be empty</span></span>  <br/> ||
   

