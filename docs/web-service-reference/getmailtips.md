---
title: GetMailTips
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- GetMailTips
api_type:
- schema
ms.assetid: 4a24ff79-f1ae-43a1-9ac2-49baf3eaa173
description: O elemento GetMailTips representa os destinatários e os tipos de dicas de email para recuperar.
ms.openlocfilehash: aad3b3d9dd578d0c92bf7d48ee8b78b58c63e23d
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/25/2018
ms.locfileid: "19752553"
---
# <a name="getmailtips"></a><span data-ttu-id="d97d4-103">GetMailTips</span><span class="sxs-lookup"><span data-stu-id="d97d4-103">GetMailTips</span></span>

<span data-ttu-id="d97d4-104">O elemento **GetMailTips** representa os destinatários e os tipos de dicas de email para recuperar.</span><span class="sxs-lookup"><span data-stu-id="d97d4-104">The **GetMailTips** element represents the recipients and types of mail tips to retrieve.</span></span> 
  
```XML
<GetMailTips>
   <SendingAs/>
   <Recipients/>
   <MailTipsRequested/>
</GetMailTips>
```

 <span data-ttu-id="d97d4-105">**GetMailTipsType**</span><span class="sxs-lookup"><span data-stu-id="d97d4-105">**GetMailTipsType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="d97d4-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="d97d4-106">Attributes and elements</span></span>

<span data-ttu-id="d97d4-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="d97d4-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="d97d4-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="d97d4-108">Attributes</span></span>

<span data-ttu-id="d97d4-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="d97d4-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="d97d4-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="d97d4-110">Child elements</span></span>

|<span data-ttu-id="d97d4-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="d97d4-111">**Element**</span></span>|<span data-ttu-id="d97d4-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="d97d4-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="d97d4-113">SendingAs</span><span class="sxs-lookup"><span data-stu-id="d97d4-113">SendingAs</span></span>](sendingas.md) <br/> |<span data-ttu-id="d97d4-114">Contém um endereço de email que um usuário está tentando enviar como.</span><span class="sxs-lookup"><span data-stu-id="d97d4-114">Contains an e-mail address that a user is trying to send as.</span></span>  <br/> |
|[<span data-ttu-id="d97d4-115">Destinatários (ArrayOfRecipientsType)</span><span class="sxs-lookup"><span data-stu-id="d97d4-115">Recipients (ArrayOfRecipientsType)</span></span>](recipients-arrayofrecipientstype.md) <br/> |<span data-ttu-id="d97d4-116">Contém uma lista de destinatários para verificar se há dicas de email.</span><span class="sxs-lookup"><span data-stu-id="d97d4-116">Contains a list of recipients to check for mail tips.</span></span>  <br/> |
|[<span data-ttu-id="d97d4-117">MailTipsRequested</span><span class="sxs-lookup"><span data-stu-id="d97d4-117">MailTipsRequested</span></span>](mailtipsrequested.md) <br/> |<span data-ttu-id="d97d4-118">Contém os tipos de dicas de email solicitadas do serviço.</span><span class="sxs-lookup"><span data-stu-id="d97d4-118">Contains the types of mail tips requested from the service.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="d97d4-119">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="d97d4-119">Parent elements</span></span>

<span data-ttu-id="d97d4-120">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="d97d4-120">None.</span></span>
  
## <a name="text-value"></a><span data-ttu-id="d97d4-121">Text value</span><span class="sxs-lookup"><span data-stu-id="d97d4-121">Text value</span></span>

<span data-ttu-id="d97d4-122">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="d97d4-122">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="d97d4-123">Comentários</span><span class="sxs-lookup"><span data-stu-id="d97d4-123">Remarks</span></span>

<span data-ttu-id="d97d4-124">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="d97d4-124">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="d97d4-125">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="d97d4-125">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="d97d4-126">Namespace</span><span class="sxs-lookup"><span data-stu-id="d97d4-126">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="d97d4-127">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="d97d4-127">Schema Name</span></span>  <br/> |<span data-ttu-id="d97d4-128">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="d97d4-128">Messages schema</span></span>  <br/> |
|<span data-ttu-id="d97d4-129">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="d97d4-129">Validation File</span></span>  <br/> |<span data-ttu-id="d97d4-130">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="d97d4-130">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="d97d4-131">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="d97d4-131">Can be Empty</span></span>  <br/> |<span data-ttu-id="d97d4-132">False</span><span class="sxs-lookup"><span data-stu-id="d97d4-132">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="d97d4-133">Ver também</span><span class="sxs-lookup"><span data-stu-id="d97d4-133">See also</span></span>



- [<span data-ttu-id="d97d4-134">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="d97d4-134">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

