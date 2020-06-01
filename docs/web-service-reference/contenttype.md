---
title: ContentType
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- ContentType
api_type:
- schema
ms.assetid: f91ff0df-0d8a-43ea-a188-d80f0e885f19
description: O elemento ContentType descreve o tipo MIME (Multipurpose Internet Mail Extensions) do conteúdo do anexo.
ms.openlocfilehash: cb326bb761ea28e0e9f77501bf754c7c1f0318fb
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44455223"
---
# <a name="contenttype"></a><span data-ttu-id="70d60-103">ContentType</span><span class="sxs-lookup"><span data-stu-id="70d60-103">ContentType</span></span>

<span data-ttu-id="70d60-104">O elemento **ContentType** descreve o tipo MIME (Multipurpose Internet Mail Extensions) do conteúdo do anexo.</span><span class="sxs-lookup"><span data-stu-id="70d60-104">The **ContentType** element describes the Multipurpose Internet Mail Extensions (MIME) type of the attachment content.</span></span> 
  
```xml
<ContentType/>
```

 <span data-ttu-id="70d60-105">**String**</span><span class="sxs-lookup"><span data-stu-id="70d60-105">**String**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="70d60-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="70d60-106">Attributes and elements</span></span>

<span data-ttu-id="70d60-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="70d60-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="70d60-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="70d60-108">Attributes</span></span>

<span data-ttu-id="70d60-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="70d60-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="70d60-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="70d60-110">Child elements</span></span>

<span data-ttu-id="70d60-111">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="70d60-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="70d60-112">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="70d60-112">Parent elements</span></span>

|<span data-ttu-id="70d60-113">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="70d60-113">**Element**</span></span>|<span data-ttu-id="70d60-114">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="70d60-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="70d60-115">ItemAttachment</span><span class="sxs-lookup"><span data-stu-id="70d60-115">ItemAttachment</span></span>](itemattachment.md) <br/> |<span data-ttu-id="70d60-116">Representa um item do Exchange anexado a outro item do Exchange.</span><span class="sxs-lookup"><span data-stu-id="70d60-116">Represents an Exchange item that is attached to another Exchange item.</span></span>  <br/> |
|[<span data-ttu-id="70d60-117">FileAttachment</span><span class="sxs-lookup"><span data-stu-id="70d60-117">FileAttachment</span></span>](fileattachment.md) <br/> |<span data-ttu-id="70d60-118">Representa um arquivo anexado a um item no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="70d60-118">Represents a file that is attached to an item in the Exchange store.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="70d60-119">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="70d60-119">Text value</span></span>

<span data-ttu-id="70d60-120">O valor de texto é um valor String que representa o tipo de conteúdo do anexo.</span><span class="sxs-lookup"><span data-stu-id="70d60-120">The text value is a string value that represents the content type of the attachment.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="70d60-121">Comentários</span><span class="sxs-lookup"><span data-stu-id="70d60-121">Remarks</span></span>

<span data-ttu-id="70d60-122">O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o MicrosoftExchange Server 2007 que tem instalada a função de servidor de Acesso para Cliente.</span><span class="sxs-lookup"><span data-stu-id="70d60-122">The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="70d60-123">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="70d60-123">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="70d60-124">Namespace</span><span class="sxs-lookup"><span data-stu-id="70d60-124">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="70d60-125">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="70d60-125">Schema name</span></span>  <br/> |<span data-ttu-id="70d60-126">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="70d60-126">Types schema</span></span>  <br/> |
|<span data-ttu-id="70d60-127">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="70d60-127">Validation file</span></span>  <br/> |<span data-ttu-id="70d60-128">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="70d60-128">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="70d60-129">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="70d60-129">Can be empty</span></span>  <br/> |<span data-ttu-id="70d60-130">False</span><span class="sxs-lookup"><span data-stu-id="70d60-130">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="70d60-131">Confira também</span><span class="sxs-lookup"><span data-stu-id="70d60-131">See also</span></span>



- [<span data-ttu-id="70d60-132">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="70d60-132">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

