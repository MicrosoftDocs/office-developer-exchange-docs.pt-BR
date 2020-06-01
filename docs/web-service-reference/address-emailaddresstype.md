---
title: Endereço (EmailAddresstype)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- Address
api_type:
- schema
ms.assetid: 518641c8-7f6f-496c-86f9-341e7c1bb44c
description: O elemento address representa um endereço de email totalmente resolvido.
ms.openlocfilehash: 591bc675165ec80f69407bd8ee19d16c9ddff15a
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44464900"
---
# <a name="address-emailaddresstype"></a><span data-ttu-id="d479e-103">Endereço (EmailAddresstype)</span><span class="sxs-lookup"><span data-stu-id="d479e-103">Address (EmailAddressType)</span></span>

<span data-ttu-id="d479e-104">O elemento **Address** representa um endereço de email totalmente resolvido.</span><span class="sxs-lookup"><span data-stu-id="d479e-104">The **Address** element represents a fully resolved e-mail address.</span></span> 
  
```XML
<Address>
   <Name/>
   <EmailAddress/>
   <RoutingType/>
   <MailboxType/>
   <ItemId/>
</Address >
```

 <span data-ttu-id="d479e-105">**EmailAddresstype**</span><span class="sxs-lookup"><span data-stu-id="d479e-105">**EmailAddressType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="d479e-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="d479e-106">Attributes and elements</span></span>

<span data-ttu-id="d479e-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="d479e-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="d479e-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="d479e-108">Attributes</span></span>

<span data-ttu-id="d479e-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="d479e-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="d479e-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="d479e-110">Child elements</span></span>

|<span data-ttu-id="d479e-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="d479e-111">**Element**</span></span>|<span data-ttu-id="d479e-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="d479e-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="d479e-113">Nome (EmailAddresstype)</span><span class="sxs-lookup"><span data-stu-id="d479e-113">Name (EmailAddressType)</span></span>](name-emailaddresstype.md) <br/> |<span data-ttu-id="d479e-114">Define o nome do usuário da caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="d479e-114">Defines the name of the mailbox user.</span></span> <span data-ttu-id="d479e-115">Este elemento é opcional.</span><span class="sxs-lookup"><span data-stu-id="d479e-115">This element is optional.</span></span>  <br/> |
|[<span data-ttu-id="d479e-116">EmailAddress (NonEmptyStringType)</span><span class="sxs-lookup"><span data-stu-id="d479e-116">EmailAddress (NonEmptyStringType)</span></span>](emailaddress-nonemptystringtype.md) <br/> |<span data-ttu-id="d479e-117">Define o endereço SMTP (Simple Mail Transfer Protocol) de um usuário de caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="d479e-117">Defines the Simple Mail Transfer Protocol (SMTP) address of a mailbox user.</span></span> <span data-ttu-id="d479e-118">Este elemento é opcional.</span><span class="sxs-lookup"><span data-stu-id="d479e-118">This element is optional.</span></span>  <br/> |
|[<span data-ttu-id="d479e-119">RoutingType (EmailAddress)</span><span class="sxs-lookup"><span data-stu-id="d479e-119">RoutingType (EmailAddress)</span></span>](routingtype-emailaddress.md) <br/> |<span data-ttu-id="d479e-120">Define o roteamento usado para a caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="d479e-120">Defines the routing that is used for the mailbox.</span></span> <span data-ttu-id="d479e-121">O padrão é SMTP.</span><span class="sxs-lookup"><span data-stu-id="d479e-121">The default is SMTP.</span></span> <span data-ttu-id="d479e-122">Este elemento é opcional.</span><span class="sxs-lookup"><span data-stu-id="d479e-122">This element is optional.</span></span>  <br/> |
|[<span data-ttu-id="d479e-123">MailboxType</span><span class="sxs-lookup"><span data-stu-id="d479e-123">MailboxType</span></span>](mailboxtype.md) <br/> |<span data-ttu-id="d479e-124">Define o tipo de caixa de correio de um usuário de caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="d479e-124">Defines the mailbox type of a mailbox user.</span></span> <span data-ttu-id="d479e-125">Este elemento é opcional.</span><span class="sxs-lookup"><span data-stu-id="d479e-125">This element is optional.</span></span>  <br/> |
|[<span data-ttu-id="d479e-126">ItemId</span><span class="sxs-lookup"><span data-stu-id="d479e-126">ItemId</span></span>](itemid.md) <br/> |<span data-ttu-id="d479e-127">Define o identificador de item de um contato ou de uma lista de distribuição privada para destinatários da pasta contatos de um usuário.</span><span class="sxs-lookup"><span data-stu-id="d479e-127">Defines the item identifier of a contact or private distribution list for recipients from a user's Contacts folder.</span></span> <span data-ttu-id="d479e-128">Este elemento é opcional.</span><span class="sxs-lookup"><span data-stu-id="d479e-128">This element is optional.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="d479e-129">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="d479e-129">Parent elements</span></span>

|<span data-ttu-id="d479e-130">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="d479e-130">**Element**</span></span>|<span data-ttu-id="d479e-131">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="d479e-131">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="d479e-132">OriginalRecipients</span><span class="sxs-lookup"><span data-stu-id="d479e-132">OriginalRecipients</span></span>](originalrecipients.md) <br/> |<span data-ttu-id="d479e-133">Contém uma coleção de endereços de email que representam os destinatários originais de uma mensagem rastreada.</span><span class="sxs-lookup"><span data-stu-id="d479e-133">Contains a collection of e-mail addresses that represent the original recipients of a tracked message.</span></span>  <br/> |
|[<span data-ttu-id="d479e-134">RoomLists</span><span class="sxs-lookup"><span data-stu-id="d479e-134">RoomLists</span></span>](roomlists.md) <br/> |<span data-ttu-id="d479e-135">Contém uma lista de salas de reunião em uma organização.</span><span class="sxs-lookup"><span data-stu-id="d479e-135">Contains a list of meeting rooms in an organization.</span></span>  <br/> |
|[<span data-ttu-id="d479e-136">SentToAddresses</span><span class="sxs-lookup"><span data-stu-id="d479e-136">SentToAddresses</span></span>](senttoaddresses.md) <br/> |<span data-ttu-id="d479e-137">Contém uma lista de endereços de email aos quais as mensagens de entrada devem ter sido enviadas para que a condição ou exceção seja aplicada.</span><span class="sxs-lookup"><span data-stu-id="d479e-137">Contains a list of e-mail addresses that incoming messages have to have been sent to in order for the condition or exception to apply.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="d479e-138">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="d479e-138">Text value</span></span>

<span data-ttu-id="d479e-139">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="d479e-139">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="d479e-140">Comentários</span><span class="sxs-lookup"><span data-stu-id="d479e-140">Remarks</span></span>

<span data-ttu-id="d479e-141">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="d479e-141">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="d479e-142">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="d479e-142">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="d479e-143">Namespace</span><span class="sxs-lookup"><span data-stu-id="d479e-143">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="d479e-144">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="d479e-144">Schema Name</span></span>  <br/> |<span data-ttu-id="d479e-145">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="d479e-145">Types schema</span></span>  <br/> |
|<span data-ttu-id="d479e-146">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="d479e-146">Validation File</span></span>  <br/> |<span data-ttu-id="d479e-147">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="d479e-147">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="d479e-148">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="d479e-148">Can be Empty</span></span>  <br/> |<span data-ttu-id="d479e-149">False</span><span class="sxs-lookup"><span data-stu-id="d479e-149">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="d479e-150">Confira também</span><span class="sxs-lookup"><span data-stu-id="d479e-150">See also</span></span>

- [<span data-ttu-id="d479e-151">Operação GetMessageTrackingReport</span><span class="sxs-lookup"><span data-stu-id="d479e-151">GetMessageTrackingReport operation</span></span>](getmessagetrackingreport-operation.md) 
- [<span data-ttu-id="d479e-152">Operação GetRoomLists</span><span class="sxs-lookup"><span data-stu-id="d479e-152">GetRoomLists operation</span></span>](getroomlists-operation.md)
- [<span data-ttu-id="d479e-153">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="d479e-153">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

