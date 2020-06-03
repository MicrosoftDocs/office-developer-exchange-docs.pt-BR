---
title: Participantes
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: 837bb372-39eb-48ae-9c09-0d2552511f93
description: O elemento participantes especifica os destinatários de um convite para uma reunião.
ms.openlocfilehash: 3a63bdf7e49309697ac503be5f4c95eb805b9635
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44460327"
---
# <a name="attendees"></a><span data-ttu-id="537f1-103">Participantes</span><span class="sxs-lookup"><span data-stu-id="537f1-103">Attendees</span></span>

<span data-ttu-id="537f1-104">O elemento **participantes** especifica os destinatários de um convite para uma reunião.</span><span class="sxs-lookup"><span data-stu-id="537f1-104">The **Attendees** element specifies the recipients of an invitation to a meeting.</span></span> 
  
```XML
<Attendees>
    <EmailUser></EmailUser>
</Attendees>
```

 <span data-ttu-id="537f1-105">**ArrayOfEmailUsersType**</span><span class="sxs-lookup"><span data-stu-id="537f1-105">**ArrayOfEmailUsersType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="537f1-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="537f1-106">Attributes and elements</span></span>

<span data-ttu-id="537f1-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="537f1-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="537f1-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="537f1-108">Attributes</span></span>

<span data-ttu-id="537f1-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="537f1-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="537f1-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="537f1-110">Child elements</span></span>

|<span data-ttu-id="537f1-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="537f1-111">**Element**</span></span>|<span data-ttu-id="537f1-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="537f1-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="537f1-113">EmailUser</span><span class="sxs-lookup"><span data-stu-id="537f1-113">EmailUser</span></span>](emailuser.md) <br/> |<span data-ttu-id="537f1-114">Especifica um destinatário de email ou contato do Active Directory.</span><span class="sxs-lookup"><span data-stu-id="537f1-114">Specifies an email recipient or Active Directory contact.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="537f1-115">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="537f1-115">Parent elements</span></span>

|<span data-ttu-id="537f1-116">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="537f1-116">**Element**</span></span>|<span data-ttu-id="537f1-117">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="537f1-117">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="537f1-118">MeetingSuggestion</span><span class="sxs-lookup"><span data-stu-id="537f1-118">MeetingSuggestion</span></span>](meetingsuggestion.md) <br/> |<span data-ttu-id="537f1-119">Especifica uma reunião proposta.</span><span class="sxs-lookup"><span data-stu-id="537f1-119">Specifies a proposed meeting.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="537f1-120">Comentários</span><span class="sxs-lookup"><span data-stu-id="537f1-120">Remarks</span></span>

<span data-ttu-id="537f1-121">Este elemento foi introduzido no Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="537f1-121">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="537f1-122">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="537f1-122">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="537f1-123">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="537f1-123">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="537f1-124">Namespace</span><span class="sxs-lookup"><span data-stu-id="537f1-124">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="537f1-125">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="537f1-125">Schema Name</span></span>  <br/> |<span data-ttu-id="537f1-126">Esquema de tipo</span><span class="sxs-lookup"><span data-stu-id="537f1-126">Type schema</span></span>  <br/> |
|<span data-ttu-id="537f1-127">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="537f1-127">Validation File</span></span>  <br/> |<span data-ttu-id="537f1-128">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="537f1-128">types.xsd</span></span>  <br/> |
|<span data-ttu-id="537f1-129">Pode estar vazio</span><span class="sxs-lookup"><span data-stu-id="537f1-129">Can Be Empty</span></span>  <br/> ||
   
## <a name="see-also"></a><span data-ttu-id="537f1-130">Confira também</span><span class="sxs-lookup"><span data-stu-id="537f1-130">See also</span></span>

- [<span data-ttu-id="537f1-131">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="537f1-131">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

