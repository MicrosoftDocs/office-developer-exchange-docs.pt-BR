---
title: Operação DeleteAttachment
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- DeleteAttachment
api_type:
- schema
ms.assetid: 4d48e595-b98c-48e7-bbeb-cacf91d12a78
description: A operação DeleteAttachment é usada para excluir anexos de arquivo e um item de um item existente no armazenamento do Exchange.
ms.openlocfilehash: 4b94bfd8d6333c1f52be8ad7d0d111ab2a0552b3
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/25/2018
ms.locfileid: "19751732"
---
# <a name="deleteattachment-operation"></a><span data-ttu-id="a5386-103">Operação DeleteAttachment</span><span class="sxs-lookup"><span data-stu-id="a5386-103">DeleteAttachment operation</span></span>

<span data-ttu-id="a5386-104">A operação DeleteAttachment é usada para excluir anexos de arquivo e um item de um item existente no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="a5386-104">The DeleteAttachment operation is used to delete file and item attachments from an existing item in the Exchange store.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="a5386-105">Comentários</span><span class="sxs-lookup"><span data-stu-id="a5386-105">Remarks</span></span>

<span data-ttu-id="a5386-106">Esta operação permite que você exclua um ou mais anexos por ID.</span><span class="sxs-lookup"><span data-stu-id="a5386-106">This operation allows you to delete one or more attachments by ID.</span></span>
  
## <a name="deleteattachment-request-example"></a><span data-ttu-id="a5386-107">Exemplo de solicitação DeleteAttachment</span><span class="sxs-lookup"><span data-stu-id="a5386-107">DeleteAttachment request example</span></span>

### <a name="description"></a><span data-ttu-id="a5386-108">Descrição</span><span class="sxs-lookup"><span data-stu-id="a5386-108">Description</span></span>

<span data-ttu-id="a5386-109">O exemplo a seguir de uma solicitação de DeleteAttachment mostra como excluir um anexo do item.</span><span class="sxs-lookup"><span data-stu-id="a5386-109">The following example of a DeleteAttachment request shows how to delete an item attachment.</span></span>
  
### <a name="code"></a><span data-ttu-id="a5386-110">Código</span><span class="sxs-lookup"><span data-stu-id="a5386-110">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
               xmlns:xsd="http://www.w3.org/2001/XMLSchema"
               xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/"
               xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
  <soap:Body>
    <DeleteAttachment xmlns="http://schemas.microsoft.com/exchange/services/2006/messages"
                      xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
      <AttachmentIds>
        <t:AttachmentId Id="AAAtAEFkbWluaX"/>
      </AttachmentIds>
    </DeleteAttachment>
  </soap:Body>
</soap:Envelope>
```

### <a name="comments"></a><span data-ttu-id="a5386-111">Comments</span><span class="sxs-lookup"><span data-stu-id="a5386-111">Comments</span></span>

<span data-ttu-id="a5386-112">O identificador de anexo foi reduzido para preservar a legibilidade.</span><span class="sxs-lookup"><span data-stu-id="a5386-112">The attachment identifier has been shortened to preserve readability.</span></span>
  
### <a name="request-elements"></a><span data-ttu-id="a5386-113">Elementos de solicitação</span><span class="sxs-lookup"><span data-stu-id="a5386-113">Request elements</span></span>

<span data-ttu-id="a5386-114">Os seguintes elementos são usados na solicitação:</span><span class="sxs-lookup"><span data-stu-id="a5386-114">The following elements are used in the request:</span></span>
  
- [<span data-ttu-id="a5386-115">DeleteAttachment</span><span class="sxs-lookup"><span data-stu-id="a5386-115">DeleteAttachment</span></span>](deleteattachment.md)
    
- [<span data-ttu-id="a5386-116">AttachmentIds</span><span class="sxs-lookup"><span data-stu-id="a5386-116">AttachmentIds</span></span>](attachmentids.md)
    
- [<span data-ttu-id="a5386-117">AttachmentId</span><span class="sxs-lookup"><span data-stu-id="a5386-117">AttachmentId</span></span>](attachmentid.md)
    
## <a name="deleteattachment-response-example"></a><span data-ttu-id="a5386-118">Exemplo de resposta DeleteAttachment</span><span class="sxs-lookup"><span data-stu-id="a5386-118">DeleteAttachment response example</span></span>

### <a name="description"></a><span data-ttu-id="a5386-119">Descrição</span><span class="sxs-lookup"><span data-stu-id="a5386-119">Description</span></span>

<span data-ttu-id="a5386-120">O exemplo a seguir mostra uma resposta bem-sucedida a uma solicitação de DeleteAttachment.</span><span class="sxs-lookup"><span data-stu-id="a5386-120">The following example shows a successful response to a DeleteAttachment request.</span></span>
  
### <a name="code"></a><span data-ttu-id="a5386-121">Código</span><span class="sxs-lookup"><span data-stu-id="a5386-121">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/" 
               xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
               xmlns:xsd="http://www.w3.org/2001/XMLSchema">
  <soap:Header>
    <t:ServerVersionInfo MajorVersion="8" MinorVersion="0" MajorBuildNumber="662" MinorBuildNumber="0" 
                         xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types"/>
  </soap:Header>
  <soap:Body>
    <DeleteAttachmentResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
                              xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" 
                              xmlns="http://schemas.microsoft.com/exchange/services/2006/messages">
      <m:ResponseMessages>
        <m:DeleteAttachmentResponseMessage xsi:type="m:DeleteAttachmentResponseMessageType" ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:RootItemId RootItemId="AAAtAEFkbWluaXN..." RootItemChangeKey="CQAAABYAA..."/>
        </m:DeleteAttachmentResponseMessage>
      </m:ResponseMessages>
    </DeleteAttachmentResponse>
  </soap:Body>
</soap:Envelope>
```

### <a name="comments"></a><span data-ttu-id="a5386-122">Comments</span><span class="sxs-lookup"><span data-stu-id="a5386-122">Comments</span></span>

<span data-ttu-id="a5386-123">A operação CreateAttachment retorna um elemento do tipo AttachmentIdType que inclui um **RootItemId** e **RootItemChangeKey**.</span><span class="sxs-lookup"><span data-stu-id="a5386-123">The CreateAttachment operation returns an element of AttachmentIdType type that includes a **RootItemId** and **RootItemChangeKey**.</span></span> <span data-ttu-id="a5386-124">Esses atributos não são permitidos para identificadores dentro de uma solicitação de DeleteAttachment.</span><span class="sxs-lookup"><span data-stu-id="a5386-124">These attributes are not permitted for identifiers within a DeleteAttachment request.</span></span> <span data-ttu-id="a5386-125">DeleteAttachment usa elementos do tipo RequestAttachmentIdType, que não incluir esses atributos.</span><span class="sxs-lookup"><span data-stu-id="a5386-125">DeleteAttachment uses elements of type RequestAttachmentIdType, which does not include these attributes.</span></span>
  
<span data-ttu-id="a5386-126">A resposta DeleteAttachment inclui a identificação do item pai.</span><span class="sxs-lookup"><span data-stu-id="a5386-126">The DeleteAttachment response includes the ID of the parent item.</span></span> <span data-ttu-id="a5386-127">Quando os anexos são removidos de um item, alterar a chave do item é modificada.</span><span class="sxs-lookup"><span data-stu-id="a5386-127">When attachments are removed from an item, the item's change key is modified.</span></span> <span data-ttu-id="a5386-128">A nova chave de alteração de item pode ser obtida a resposta DeleteAttachment.</span><span class="sxs-lookup"><span data-stu-id="a5386-128">The new item change key can be obtained from the DeleteAttachment response.</span></span>
  
> [!NOTE]
> <span data-ttu-id="a5386-129">O identificador de [RootItemId](rootitemid.md) e ChangeKey foram diminuídas para preservar a legibilidade.</span><span class="sxs-lookup"><span data-stu-id="a5386-129">The [RootItemId](rootitemid.md) identifier and ChangeKey have been shortened to preserve readability.</span></span> 
  
### <a name="successful-response-elements"></a><span data-ttu-id="a5386-130">Elementos de resposta bem-sucedida</span><span class="sxs-lookup"><span data-stu-id="a5386-130">Successful response elements</span></span>

<span data-ttu-id="a5386-131">Os seguintes elementos são usados na resposta:</span><span class="sxs-lookup"><span data-stu-id="a5386-131">The following elements are used in the response:</span></span>
  
- [<span data-ttu-id="a5386-132">ServerVersionInfo</span><span class="sxs-lookup"><span data-stu-id="a5386-132">ServerVersionInfo</span></span>](serverversioninfo.md)
    
- [<span data-ttu-id="a5386-133">DeleteAttachmentResponse</span><span class="sxs-lookup"><span data-stu-id="a5386-133">DeleteAttachmentResponse</span></span>](deleteattachmentresponse.md)
    
- [<span data-ttu-id="a5386-134">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="a5386-134">ResponseMessages</span></span>](responsemessages.md)
    
- [<span data-ttu-id="a5386-135">DeleteAttachmentResponseMessage</span><span class="sxs-lookup"><span data-stu-id="a5386-135">DeleteAttachmentResponseMessage</span></span>](deleteattachmentresponsemessage.md)
    
- [<span data-ttu-id="a5386-136">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="a5386-136">ResponseCode</span></span>](responsecode.md)
    
- [<span data-ttu-id="a5386-137">RootItemId</span><span class="sxs-lookup"><span data-stu-id="a5386-137">RootItemId</span></span>](rootitemid.md)
    
## <a name="see-also"></a><span data-ttu-id="a5386-138">Confira também</span><span class="sxs-lookup"><span data-stu-id="a5386-138">See also</span></span>

- [<span data-ttu-id="a5386-139">Operação CreateAttachment</span><span class="sxs-lookup"><span data-stu-id="a5386-139">CreateAttachment operation</span></span>](createattachment-operation.md) 
- [<span data-ttu-id="a5386-140">Operação GetAttachment</span><span class="sxs-lookup"><span data-stu-id="a5386-140">GetAttachment operation</span></span>](getattachment-operation.md)

