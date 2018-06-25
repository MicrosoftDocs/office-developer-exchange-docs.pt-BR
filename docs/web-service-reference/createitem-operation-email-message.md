---
title: Operação CreateItem (mensagem de email)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- CreateItem
api_type:
- schema
ms.assetid: fe6bb7fc-8918-4e6e-b0a1-b7e0ef44c3d1
description: A operação CreateItem é usada para criar mensagens de email.
ms.openlocfilehash: 591209165cfbafc2d5f4036dd8fab6659523a044
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/25/2018
ms.locfileid: "19751603"
---
# <a name="createitem-operation-email-message"></a><span data-ttu-id="49e09-103">Operação CreateItem (mensagem de email)</span><span class="sxs-lookup"><span data-stu-id="49e09-103">CreateItem operation (email message)</span></span>

<span data-ttu-id="49e09-104">A operação CreateItem é usada para criar mensagens de email.</span><span class="sxs-lookup"><span data-stu-id="49e09-104">The CreateItem operation is used to create e-mail messages.</span></span>
  
## <a name="createitem-request-example"></a><span data-ttu-id="49e09-105">Exemplo de solicitação CreateItem</span><span class="sxs-lookup"><span data-stu-id="49e09-105">CreateItem request example</span></span>

### <a name="description"></a><span data-ttu-id="49e09-106">Descrição</span><span class="sxs-lookup"><span data-stu-id="49e09-106">Description</span></span>

<span data-ttu-id="49e09-107">O exemplo a seguir de uma solicitação de CreateItem mostra como criar uma nova mensagem de email, enviar a mensagem e salvar uma cópia na pasta Rascunhos.</span><span class="sxs-lookup"><span data-stu-id="49e09-107">The following example of a CreateItem request shows how to create a new e-mail message, send the message, and save a copy of it in the drafts folder.</span></span>
  
### <a name="code"></a><span data-ttu-id="49e09-108">Código</span><span class="sxs-lookup"><span data-stu-id="49e09-108">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/"
  xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
  <soap:Body>
    <CreateItem MessageDisposition="SendAndSaveCopy" xmlns="http://schemas.microsoft.com/exchange/services/2006/messages">
      <SavedItemFolderId>
        <t:DistinguishedFolderId Id="drafts" />
      </SavedItemFolderId>
      <Items>
        <t:Message>
          <t:ItemClass>IPM.Note</t:ItemClass>
          <t:Subject>Project Action</t:Subject>
          <t:Body BodyType="Text">Priority - Update specification</t:Body>
          <t:ToRecipients>
            <t:Mailbox>
              <t:EmailAddress>sschmidt@example.com</t:EmailAddress>
            </t:Mailbox>
          </t:ToRecipients>
          <t:IsRead>false</t:IsRead>
        </t:Message>
      </Items>
    </CreateItem>
  </soap:Body>
</soap:Envelope>
```

### <a name="request-elements"></a><span data-ttu-id="49e09-109">Elementos de solicitação</span><span class="sxs-lookup"><span data-stu-id="49e09-109">Request elements</span></span>

<span data-ttu-id="49e09-110">Os seguintes elementos são usados na solicitação:</span><span class="sxs-lookup"><span data-stu-id="49e09-110">The following elements are used in the request:</span></span> 
  
- [<span data-ttu-id="49e09-111">CreateItem</span><span class="sxs-lookup"><span data-stu-id="49e09-111">CreateItem</span></span>](createitem.md)
    
- [<span data-ttu-id="49e09-112">SavedItemFolderId</span><span class="sxs-lookup"><span data-stu-id="49e09-112">SavedItemFolderId</span></span>](saveditemfolderid.md)
    
- [<span data-ttu-id="49e09-113">Itens (NonEmptyArrayOfAllItemsType)</span><span class="sxs-lookup"><span data-stu-id="49e09-113">Items (NonEmptyArrayOfAllItemsType)</span></span>](items-nonemptyarrayofallitemstype.md)
    
- [<span data-ttu-id="49e09-114">Mensagem</span><span class="sxs-lookup"><span data-stu-id="49e09-114">Message</span></span>](message-ex15websvcsotherref.md)
    
- [<span data-ttu-id="49e09-115">ItemClass</span><span class="sxs-lookup"><span data-stu-id="49e09-115">ItemClass</span></span>](itemclass.md)
    
- [<span data-ttu-id="49e09-116">Assunto</span><span class="sxs-lookup"><span data-stu-id="49e09-116">Subject</span></span>](subject.md)
    
- [<span data-ttu-id="49e09-117">Corpo</span><span class="sxs-lookup"><span data-stu-id="49e09-117">Body</span></span>](body.md)
    
- [<span data-ttu-id="49e09-118">ToRecipients</span><span class="sxs-lookup"><span data-stu-id="49e09-118">ToRecipients</span></span>](torecipients.md)
    
- [<span data-ttu-id="49e09-119">Caixa de correio</span><span class="sxs-lookup"><span data-stu-id="49e09-119">Mailbox</span></span>](mailbox.md)
    
- [<span data-ttu-id="49e09-120">EmailAddress (NonEmptyStringType)</span><span class="sxs-lookup"><span data-stu-id="49e09-120">EmailAddress (NonEmptyStringType)</span></span>](emailaddress-nonemptystringtype.md)
    
- [<span data-ttu-id="49e09-121">Foi lido</span><span class="sxs-lookup"><span data-stu-id="49e09-121">IsRead</span></span>](isread.md)
    
<span data-ttu-id="49e09-122">Para localizar outras opções para a mensagem de solicitação da operação CreateItem, explore a hierarquia de esquema.</span><span class="sxs-lookup"><span data-stu-id="49e09-122">To find other options for the request message of the CreateItem operation, explore the schema hierarchy.</span></span> <span data-ttu-id="49e09-123">Inicie o elemento [CreateItem](createitem.md) .</span><span class="sxs-lookup"><span data-stu-id="49e09-123">Start at the [CreateItem](createitem.md) element.</span></span> 
  
## <a name="successful-createitem-response"></a><span data-ttu-id="49e09-124">Resposta de CreateItem bem-sucedida</span><span class="sxs-lookup"><span data-stu-id="49e09-124">Successful CreateItem Response</span></span>

### <a name="description"></a><span data-ttu-id="49e09-125">Descrição</span><span class="sxs-lookup"><span data-stu-id="49e09-125">Description</span></span>

<span data-ttu-id="49e09-126">O exemplo a seguir mostra uma resposta bem-sucedida à solicitação de CreateItem.</span><span class="sxs-lookup"><span data-stu-id="49e09-126">The following example shows a successful response to the CreateItem request.</span></span>
  
### <a name="code"></a><span data-ttu-id="49e09-127">Código</span><span class="sxs-lookup"><span data-stu-id="49e09-127">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8" ?>
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/" 
               xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
               xmlns:xsd="http://www.w3.org/2001/XMLSchema">
  <soap:Header>
    <t:ServerVersionInfo MajorVersion="8" MinorVersion="0" MajorBuildNumber="595" MinorBuildNumber="0" xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" />
  </soap:Header>
  <soap:Body>
    <CreateItemResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
                        xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" 
                        xmlns="http://schemas.microsoft.com/exchange/services/2006/messages">
      <m:ResponseMessages>
        <m:CreateItemResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:Items />
        </m:CreateItemResponseMessage>
      </m:ResponseMessages>
    </CreateItemResponse>
  </soap:Body>
</soap:Envelope>
```

### <a name="successful-response-elements"></a><span data-ttu-id="49e09-128">Elementos de resposta bem-sucedida</span><span class="sxs-lookup"><span data-stu-id="49e09-128">Successful response elements</span></span>

<span data-ttu-id="49e09-129">Os seguintes elementos são incluídos na resposta:</span><span class="sxs-lookup"><span data-stu-id="49e09-129">The following elements are included in the response:</span></span> 
  
- [<span data-ttu-id="49e09-130">CreateItemResponse</span><span class="sxs-lookup"><span data-stu-id="49e09-130">CreateItemResponse</span></span>](createitemresponse.md)
    
- [<span data-ttu-id="49e09-131">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="49e09-131">ResponseMessages</span></span>](responsemessages.md)
    
- [<span data-ttu-id="49e09-132">CreateItemResponseMessage</span><span class="sxs-lookup"><span data-stu-id="49e09-132">CreateItemResponseMessage</span></span>](createitemresponsemessage.md)
    
- [<span data-ttu-id="49e09-133">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="49e09-133">ResponseCode</span></span>](responsecode.md)
    
- [<span data-ttu-id="49e09-134">Items</span><span class="sxs-lookup"><span data-stu-id="49e09-134">Items</span></span>](items.md)
    
<span data-ttu-id="49e09-135">Para localizar outras opções para a mensagem de resposta da operação CreateItem, explore a hierarquia de esquema.</span><span class="sxs-lookup"><span data-stu-id="49e09-135">To find other options for the response message of the CreateItem operation, explore the schema hierarchy.</span></span> <span data-ttu-id="49e09-136">Inicie o elemento [CreateItemResponse](createitemresponse.md) .</span><span class="sxs-lookup"><span data-stu-id="49e09-136">Start at the [CreateItemResponse](createitemresponse.md) element.</span></span> 
  
## <a name="error-createitem-response"></a><span data-ttu-id="49e09-137">Erro CreateItem resposta</span><span class="sxs-lookup"><span data-stu-id="49e09-137">Error CreateItem Response</span></span>

### <a name="description"></a><span data-ttu-id="49e09-138">Descrição</span><span class="sxs-lookup"><span data-stu-id="49e09-138">Description</span></span>

<span data-ttu-id="49e09-139">O exemplo a seguir mostra uma resposta de erro a uma solicitação de CreateItem.</span><span class="sxs-lookup"><span data-stu-id="49e09-139">The following example shows an error response to a CreateItem request.</span></span>
  
### <a name="code"></a><span data-ttu-id="49e09-140">Código</span><span class="sxs-lookup"><span data-stu-id="49e09-140">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8" ?>
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/" 
               xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
               xmlns:xsd="http://www.w3.org/2001/XMLSchema">
  <soap:Header>
    <t:ServerVersionInfo MajorVersion="8" MinorVersion="0" MajorBuildNumber="595" MinorBuildNumber="0" xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" />
  </soap:Header>
  <soap:Body>
    <CreateItemResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
                        xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" 
                        xmlns="http://schemas.microsoft.com/exchange/services/2006/messages">
      <m:ResponseMessages>
        <m:CreateItemResponseMessage ResponseClass="Error">
          <m:MessageText>The user account which was used to submit this request does not have the right to send mail on behalf of the specified sending account.</m:MessageText>
          <m:ResponseCode>ErrorSendAsDenied</m:ResponseCode>
          <m:DescriptiveLinkKey>0</m:DescriptiveLinkKey>
          <m:Items />
        </m:CreateItemResponseMessage>
      </m:ResponseMessages>
    </CreateItemResponse>
  </soap:Body>
</soap:Envelope>
```

### <a name="error-response-elements"></a><span data-ttu-id="49e09-141">Elementos de resposta de erro</span><span class="sxs-lookup"><span data-stu-id="49e09-141">Error response elements</span></span>

<span data-ttu-id="49e09-142">Os seguintes elementos são usados na resposta de erro:</span><span class="sxs-lookup"><span data-stu-id="49e09-142">The following elements are used in the error response:</span></span> 
  
- [<span data-ttu-id="49e09-143">CreateItemResponse</span><span class="sxs-lookup"><span data-stu-id="49e09-143">CreateItemResponse</span></span>](createitemresponse.md)
    
- [<span data-ttu-id="49e09-144">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="49e09-144">ResponseMessages</span></span>](responsemessages.md)
    
- [<span data-ttu-id="49e09-145">CreateItemResponseMessage</span><span class="sxs-lookup"><span data-stu-id="49e09-145">CreateItemResponseMessage</span></span>](createitemresponsemessage.md)
    
- [<span data-ttu-id="49e09-146">MessageText</span><span class="sxs-lookup"><span data-stu-id="49e09-146">MessageText</span></span>](messagetext.md)
    
- [<span data-ttu-id="49e09-147">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="49e09-147">ResponseCode</span></span>](responsecode.md)
    
- [<span data-ttu-id="49e09-148">DescriptiveLinkKey</span><span class="sxs-lookup"><span data-stu-id="49e09-148">DescriptiveLinkKey</span></span>](descriptivelinkkey.md)
    
- [<span data-ttu-id="49e09-149">Items</span><span class="sxs-lookup"><span data-stu-id="49e09-149">Items</span></span>](items.md)
    
<span data-ttu-id="49e09-150">Para localizar outras opções para a mensagem de resposta de erro da operação CreateItem, explore a hierarquia de esquema.</span><span class="sxs-lookup"><span data-stu-id="49e09-150">To find other options for the error response message of the CreateItem operation, explore the schema hierarchy.</span></span> <span data-ttu-id="49e09-151">Inicie o elemento [CreateItemResponse](createitemresponse.md) .</span><span class="sxs-lookup"><span data-stu-id="49e09-151">Start at the [CreateItemResponse](createitemresponse.md) element.</span></span> 
  
## <a name="see-also"></a><span data-ttu-id="49e09-152">Confira também</span><span class="sxs-lookup"><span data-stu-id="49e09-152">See also</span></span>



[<span data-ttu-id="49e09-153">Operação CreateItem</span><span class="sxs-lookup"><span data-stu-id="49e09-153">CreateItem operation</span></span>](createitem-operation.md)

