---
title: ForwardToRecipients
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- ForwardToRecipients
api_type:
- schema
ms.assetid: dd58fd72-591d-4891-b226-465bcf12c19b
description: O elemento ForwardToRecipients indica os endereços de email para os quais as mensagens devem ser encaminhadas.
ms.openlocfilehash: d565fa9f59794a4e10e91b05a507354a2f6ef0c9
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44458317"
---
# <a name="forwardtorecipients"></a><span data-ttu-id="4e65d-103">ForwardToRecipients</span><span class="sxs-lookup"><span data-stu-id="4e65d-103">ForwardToRecipients</span></span>

<span data-ttu-id="4e65d-104">O elemento **ForwardToRecipients** indica os endereços de email para os quais as mensagens devem ser encaminhadas.</span><span class="sxs-lookup"><span data-stu-id="4e65d-104">The **ForwardToRecipients** element indicates the e-mail addresses to which messages are to be forwarded.</span></span> 
  
```XML
<ForwardToRecipients>
   <Address/>
</ForwardToRecipients>
```

 <span data-ttu-id="4e65d-105">**ArrayOfEmailAddressesType**</span><span class="sxs-lookup"><span data-stu-id="4e65d-105">**ArrayOfEmailAddressesType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="4e65d-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="4e65d-106">Attributes and elements</span></span>

<span data-ttu-id="4e65d-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="4e65d-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="4e65d-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="4e65d-108">Attributes</span></span>

<span data-ttu-id="4e65d-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="4e65d-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="4e65d-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="4e65d-110">Child elements</span></span>

|<span data-ttu-id="4e65d-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="4e65d-111">**Element**</span></span>|<span data-ttu-id="4e65d-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="4e65d-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="4e65d-113">Endereço (EmailAddresstype)</span><span class="sxs-lookup"><span data-stu-id="4e65d-113">Address (EmailAddressType)</span></span>](address-emailaddresstype.md) <br/> |<span data-ttu-id="4e65d-114">Representa um endereço de email totalmente resolvido.</span><span class="sxs-lookup"><span data-stu-id="4e65d-114">Represents a fully resolved e-mail address.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="4e65d-115">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="4e65d-115">Parent elements</span></span>

|<span data-ttu-id="4e65d-116">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="4e65d-116">**Element**</span></span>|<span data-ttu-id="4e65d-117">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="4e65d-117">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="4e65d-118">Actions</span><span class="sxs-lookup"><span data-stu-id="4e65d-118">Actions</span></span>](actions.md) <br/> |<span data-ttu-id="4e65d-119">Representa o conjunto de ações que estão disponíveis para serem realizadas em uma mensagem quando as condições forem atendidas.</span><span class="sxs-lookup"><span data-stu-id="4e65d-119">Represents the set of actions that are available to be taken on a message when the conditions are fulfilled.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="4e65d-120">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="4e65d-120">Text value</span></span>

<span data-ttu-id="4e65d-121">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="4e65d-121">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="4e65d-122">Comentários</span><span class="sxs-lookup"><span data-stu-id="4e65d-122">Remarks</span></span>

<span data-ttu-id="4e65d-123">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="4e65d-123">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="4e65d-124">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="4e65d-124">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="4e65d-125">Namespace</span><span class="sxs-lookup"><span data-stu-id="4e65d-125">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="4e65d-126">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="4e65d-126">Schema Name</span></span>  <br/> |<span data-ttu-id="4e65d-127">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="4e65d-127">Messages schema</span></span>  <br/> |
|<span data-ttu-id="4e65d-128">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="4e65d-128">Validation File</span></span>  <br/> |<span data-ttu-id="4e65d-129">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="4e65d-129">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="4e65d-130">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="4e65d-130">Can be Empty</span></span>  <br/> |<span data-ttu-id="4e65d-131">Verdadeiro</span><span class="sxs-lookup"><span data-stu-id="4e65d-131">True</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="4e65d-132">Confira também</span><span class="sxs-lookup"><span data-stu-id="4e65d-132">See also</span></span>



- [<span data-ttu-id="4e65d-133">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="4e65d-133">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

