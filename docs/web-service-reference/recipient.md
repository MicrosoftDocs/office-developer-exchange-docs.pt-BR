---
title: Destinatário
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- Recipient
api_type:
- schema
ms.assetid: 52adbb30-3bfd-48aa-9ea8-9f7d3b4bee44
description: O elemento de destinatário representa o destinatário para o qual o evento ocorreu.
ms.openlocfilehash: e8e8f9d6031d27c7441017c85eb26a143258b183
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/25/2018
ms.locfileid: "19824971"
---
# <a name="recipient"></a><span data-ttu-id="90446-103">Destinatário</span><span class="sxs-lookup"><span data-stu-id="90446-103">Recipient</span></span>

<span data-ttu-id="90446-104">O elemento de **destinatário** representa o destinatário para o qual o evento ocorreu.</span><span class="sxs-lookup"><span data-stu-id="90446-104">The **Recipient** element represents the recipient for whom the event occurred.</span></span> 
  
```XML
<Recipient>
   <Name/>
   <EmailAddress/>
   <RoutingType/>
   <MailboxType/>
   <ItemId/>
</Recipient>
```

 <span data-ttu-id="90446-105">**EmailAddressType**</span><span class="sxs-lookup"><span data-stu-id="90446-105">**EmailAddressType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="90446-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="90446-106">Attributes and elements</span></span>

<span data-ttu-id="90446-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="90446-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="90446-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="90446-108">Attributes</span></span>

<span data-ttu-id="90446-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="90446-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="90446-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="90446-110">Child elements</span></span>

|<span data-ttu-id="90446-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="90446-111">**Element**</span></span>|<span data-ttu-id="90446-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="90446-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="90446-113">Nome (EmailAddressType)</span><span class="sxs-lookup"><span data-stu-id="90446-113">Name (EmailAddressType)</span></span>](name-emailaddresstype.md) <br/> |<span data-ttu-id="90446-114">Representa o nome do usuário da caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="90446-114">Represents the name of the mailbox user.</span></span> <span data-ttu-id="90446-115">Esse elemento é opcional.</span><span class="sxs-lookup"><span data-stu-id="90446-115">This element is optional.</span></span>  <br/> |
|[<span data-ttu-id="90446-116">EmailAddress (NonEmptyStringType)</span><span class="sxs-lookup"><span data-stu-id="90446-116">EmailAddress (NonEmptyStringType)</span></span>](emailaddress-nonemptystringtype.md) <br/> |<span data-ttu-id="90446-117">Define o endereço de Simple Mail Transfer Protocol (SMTP) principal de um usuário de caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="90446-117">Defines the primary Simple Mail Transfer Protocol (SMTP) address of a mailbox user.</span></span> <span data-ttu-id="90446-118">Esse elemento é opcional.</span><span class="sxs-lookup"><span data-stu-id="90446-118">This element is optional.</span></span>  <br/> |
|[<span data-ttu-id="90446-119">RoutingType (EmailAddress)</span><span class="sxs-lookup"><span data-stu-id="90446-119">RoutingType (EmailAddress)</span></span>](routingtype-emailaddress.md) <br/> |<span data-ttu-id="90446-120">Define o roteamento que é usado para a caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="90446-120">Defines the routing that is used for the mailbox.</span></span> <span data-ttu-id="90446-121">O valor padrão é SMTP.</span><span class="sxs-lookup"><span data-stu-id="90446-121">The default value is SMTP.</span></span> <span data-ttu-id="90446-122">Esse elemento é opcional.</span><span class="sxs-lookup"><span data-stu-id="90446-122">This element is optional.</span></span>  <br/> |
|[<span data-ttu-id="90446-123">MailboxType</span><span class="sxs-lookup"><span data-stu-id="90446-123">MailboxType</span></span>](mailboxtype.md) <br/> |<span data-ttu-id="90446-124">Representa o tipo de caixa de correio que é representado por um endereço de email.</span><span class="sxs-lookup"><span data-stu-id="90446-124">Represents the type of mailbox that is represented by the e-mail address.</span></span> <span data-ttu-id="90446-125">Esse elemento é opcional.</span><span class="sxs-lookup"><span data-stu-id="90446-125">This element is optional.</span></span>  <br/> |
|[<span data-ttu-id="90446-126">ItemId</span><span class="sxs-lookup"><span data-stu-id="90446-126">ItemId</span></span>](itemid.md) <br/> |<span data-ttu-id="90446-127">Define o identificador do item de um contato ou uma lista de distribuição particular para destinatários da pasta de contatos do usuário.</span><span class="sxs-lookup"><span data-stu-id="90446-127">Defines the item identifier of a contact or private distribution list for recipients from a user's Contacts folder.</span></span> <span data-ttu-id="90446-128">Esse elemento é opcional.</span><span class="sxs-lookup"><span data-stu-id="90446-128">This element is optional.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="90446-129">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="90446-129">Parent elements</span></span>

|<span data-ttu-id="90446-130">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="90446-130">**Element**</span></span>|<span data-ttu-id="90446-131">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="90446-131">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="90446-132">RecipientTrackingEvent</span><span class="sxs-lookup"><span data-stu-id="90446-132">RecipientTrackingEvent</span></span>](recipienttrackingevent.md) <br/> |<span data-ttu-id="90446-133">Contém informações para um único evento de um destinatário.</span><span class="sxs-lookup"><span data-stu-id="90446-133">Contains information for a single event for a recipient.</span></span>  <br/> |
|[<span data-ttu-id="90446-134">FindMessageTrackingReport</span><span class="sxs-lookup"><span data-stu-id="90446-134">FindMessageTrackingReport</span></span>](findmessagetrackingreport.md) <br/> |<span data-ttu-id="90446-135">Especifica os critérios para os tipos de mensagens para encontrar.</span><span class="sxs-lookup"><span data-stu-id="90446-135">Specifies criteria for the types of messages to find.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="90446-136">Text value</span><span class="sxs-lookup"><span data-stu-id="90446-136">Text value</span></span>

<span data-ttu-id="90446-137">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="90446-137">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="90446-138">Comentários</span><span class="sxs-lookup"><span data-stu-id="90446-138">Remarks</span></span>

<span data-ttu-id="90446-139">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="90446-139">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="90446-140">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="90446-140">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="90446-141">Namespace</span><span class="sxs-lookup"><span data-stu-id="90446-141">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="90446-142">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="90446-142">Schema Name</span></span>  <br/> |<span data-ttu-id="90446-143">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="90446-143">Types schema</span></span>  <br/> |
|<span data-ttu-id="90446-144">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="90446-144">Validation File</span></span>  <br/> |<span data-ttu-id="90446-145">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="90446-145">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="90446-146">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="90446-146">Can be Empty</span></span>  <br/> |<span data-ttu-id="90446-147">False</span><span class="sxs-lookup"><span data-stu-id="90446-147">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="90446-148">Ver também</span><span class="sxs-lookup"><span data-stu-id="90446-148">See also</span></span>



- [<span data-ttu-id="90446-149">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="90446-149">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

