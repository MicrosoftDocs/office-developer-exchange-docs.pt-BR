---
title: DeleteAttachmentResponseMessage
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- DeleteAttachmentResponseMessage
api_type:
- schema
ms.assetid: 1edb085f-1674-48e5-8ec3-42351adeac7d
description: O elemento DeleteAttachmentResponseMessage contém o status e o resultado de uma única solicitação de operação de DeleteAttachment.
ms.openlocfilehash: 3ff253a5c2b6cbd69b7b976f7f41ca8b83814a74
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44464256"
---
# <a name="deleteattachmentresponsemessage"></a><span data-ttu-id="d4785-103">DeleteAttachmentResponseMessage</span><span class="sxs-lookup"><span data-stu-id="d4785-103">DeleteAttachmentResponseMessage</span></span>

<span data-ttu-id="d4785-104">O elemento **DeleteAttachmentResponseMessage** contém o status e o resultado de uma única solicitação de [operação de DeleteAttachment](deleteattachment-operation.md) .</span><span class="sxs-lookup"><span data-stu-id="d4785-104">The **DeleteAttachmentResponseMessage** element contains the status and result of a single [DeleteAttachment operation](deleteattachment-operation.md) request.</span></span> 
  
- [<span data-ttu-id="d4785-105">DeleteAttachmentResponse</span><span class="sxs-lookup"><span data-stu-id="d4785-105">DeleteAttachmentResponse</span></span>](deleteattachmentresponse.md)  
- [<span data-ttu-id="d4785-106">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="d4785-106">ResponseMessages</span></span>](responsemessages.md)  
- [<span data-ttu-id="d4785-107">DeleteAttachmentResponseMessage</span><span class="sxs-lookup"><span data-stu-id="d4785-107">DeleteAttachmentResponseMessage</span></span>](deleteattachmentresponsemessage.md)
  
```xml
<DeleteAttachmentResponseMessage ResponseClass="">
   <MessageText/>
   <ResponseCode/>
   <DescriptiveLinkKey/>
   <MessageXml/>
   <RootItemId/>
</DeleteAttachmentResponseMessage>
```

<span data-ttu-id="d4785-108">**DeleteAttachmentResponseMessageType**</span><span class="sxs-lookup"><span data-stu-id="d4785-108">**DeleteAttachmentResponseMessageType**</span></span>

## <a name="attributes-and-elements"></a><span data-ttu-id="d4785-109">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="d4785-109">Attributes and elements</span></span>

<span data-ttu-id="d4785-110">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="d4785-110">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="d4785-111">Atributos</span><span class="sxs-lookup"><span data-stu-id="d4785-111">Attributes</span></span>

|<span data-ttu-id="d4785-112">**Atributo**</span><span class="sxs-lookup"><span data-stu-id="d4785-112">**Attribute**</span></span>|<span data-ttu-id="d4785-113">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="d4785-113">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="d4785-114">**ResponseClass**</span><span class="sxs-lookup"><span data-stu-id="d4785-114">**ResponseClass**</span></span> <br/> | <span data-ttu-id="d4785-115">Descreve o status de uma resposta de [operação do DeleteAttachment](deleteattachment-operation.md) .</span><span class="sxs-lookup"><span data-stu-id="d4785-115">Describes the status of a [DeleteAttachment operation](deleteattachment-operation.md) response.</span></span><br/><br/><span data-ttu-id="d4785-116">Os seguintes valores são válidos para este atributo:</span><span class="sxs-lookup"><span data-stu-id="d4785-116">The following values are valid for this attribute:</span></span><br/><br/><span data-ttu-id="d4785-117">-Êxito</span><span class="sxs-lookup"><span data-stu-id="d4785-117">-  Success</span></span>  <br/><span data-ttu-id="d4785-118">-Aviso</span><span class="sxs-lookup"><span data-stu-id="d4785-118">-  Warning</span></span>  <br/><span data-ttu-id="d4785-119">-Erro</span><span class="sxs-lookup"><span data-stu-id="d4785-119">-  Error</span></span>  <br/> |
   
#### <a name="responseclass-attribute-values"></a><span data-ttu-id="d4785-120">Valores de atributo ResponseClass</span><span class="sxs-lookup"><span data-stu-id="d4785-120">ResponseClass attribute values</span></span>

|<span data-ttu-id="d4785-121">**Valor**</span><span class="sxs-lookup"><span data-stu-id="d4785-121">**Value**</span></span>|<span data-ttu-id="d4785-122">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="d4785-122">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="d4785-123">**Success**</span><span class="sxs-lookup"><span data-stu-id="d4785-123">**Success**</span></span> <br/> |<span data-ttu-id="d4785-124">Descreve uma solicitação que é atendida.</span><span class="sxs-lookup"><span data-stu-id="d4785-124">Describes a request that is fulfilled.</span></span>  <br/> |
|<span data-ttu-id="d4785-125">**Aviso**</span><span class="sxs-lookup"><span data-stu-id="d4785-125">**Warning**</span></span> <br/> | <span data-ttu-id="d4785-126">Descreve uma solicitação que não foi processada.</span><span class="sxs-lookup"><span data-stu-id="d4785-126">Describes a request that was not processed.</span></span> <span data-ttu-id="d4785-127">Um aviso pode ser retornado se um erro ocorreu enquanto um item na solicitação estava sendo processado e não foi possível processar os itens subsequentes.</span><span class="sxs-lookup"><span data-stu-id="d4785-127">A warning may be returned if an error occurred while an item in the request was processing and subsequent items could not be processed.</span></span><br/><br/><span data-ttu-id="d4785-128">A seguir estão exemplos de fontes de avisos:</span><span class="sxs-lookup"><span data-stu-id="d4785-128">The following are examples of sources of warnings:</span></span><br/><br/><span data-ttu-id="d4785-129">– O repositório do Exchange está offline durante o lote.</span><span class="sxs-lookup"><span data-stu-id="d4785-129">- The Exchange store is offline during the batch.</span></span>  <br/><span data-ttu-id="d4785-130">– Os serviços de domínio do Active Directory (AD DS) estão offline.</span><span class="sxs-lookup"><span data-stu-id="d4785-130">-  Active Directory Domain Services (AD DS) is offline.</span></span>  <br/><span data-ttu-id="d4785-131">-As caixas de correio são movidas.</span><span class="sxs-lookup"><span data-stu-id="d4785-131">-  Mailboxes are moved.</span></span>  <br/><span data-ttu-id="d4785-132">– O banco de dados de mensagens (MDB) está offline.</span><span class="sxs-lookup"><span data-stu-id="d4785-132">-  The message database (MDB) is offline.</span></span>  <br/><span data-ttu-id="d4785-133">-Uma senha expirou.</span><span class="sxs-lookup"><span data-stu-id="d4785-133">-  A password is expired.</span></span>  <br/><span data-ttu-id="d4785-134">-Uma cota foi excedida.</span><span class="sxs-lookup"><span data-stu-id="d4785-134">-  A quota is exceeded.</span></span>  <br/> |
|<span data-ttu-id="d4785-135">**Error**</span><span class="sxs-lookup"><span data-stu-id="d4785-135">**Error**</span></span> <br/> | <span data-ttu-id="d4785-136">Descreve uma solicitação que não pode ser atendida.</span><span class="sxs-lookup"><span data-stu-id="d4785-136">Describes a request that cannot be fulfilled.</span></span><br/><br/><span data-ttu-id="d4785-137">A seguir estão exemplos de fontes de erros:</span><span class="sxs-lookup"><span data-stu-id="d4785-137">The following are examples of sources of errors:</span></span><br/><br/><span data-ttu-id="d4785-138">-Atributos ou elementos inválidos</span><span class="sxs-lookup"><span data-stu-id="d4785-138">- Invalid attributes or elements</span></span>  <br/><span data-ttu-id="d4785-139">-Atributos ou elementos fora do intervalo</span><span class="sxs-lookup"><span data-stu-id="d4785-139">-  Attributes or elements out of range</span></span>  <br/><span data-ttu-id="d4785-140">– Marca desconhecida</span><span class="sxs-lookup"><span data-stu-id="d4785-140">-  Unknown tag</span></span>  <br/><span data-ttu-id="d4785-141">-Atributo ou elemento não válido no contexto</span><span class="sxs-lookup"><span data-stu-id="d4785-141">-  Attribute or element not valid in the context</span></span>  <br/><span data-ttu-id="d4785-142">– Tentativa de acesso não autorizado por qualquer cliente</span><span class="sxs-lookup"><span data-stu-id="d4785-142">-  Unauthorized access attempt by any client</span></span>  <br/><span data-ttu-id="d4785-143">-Falha do servidor em resposta a uma chamada válida do lado do cliente</span><span class="sxs-lookup"><span data-stu-id="d4785-143">-  Server-side failure in response to a valid client-side call</span></span><br/><br/>  <span data-ttu-id="d4785-144">As informações sobre o erro podem ser encontradas nos elementos [ResponseCode](responsecode.md) e [MessageText](messagetext.md) .</span><span class="sxs-lookup"><span data-stu-id="d4785-144">Information about the error can be found in the [ResponseCode](responsecode.md) and [MessageText](messagetext.md) elements.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="d4785-145">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="d4785-145">Child elements</span></span>

|<span data-ttu-id="d4785-146">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="d4785-146">**Element**</span></span>|<span data-ttu-id="d4785-147">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="d4785-147">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="d4785-148">MessageText</span><span class="sxs-lookup"><span data-stu-id="d4785-148">MessageText</span></span>](messagetext.md) <br/> |<span data-ttu-id="d4785-149">Fornece uma descrição de texto do status da resposta.</span><span class="sxs-lookup"><span data-stu-id="d4785-149">Provides a text description of the status of the response.</span></span>  <br/> |
|[<span data-ttu-id="d4785-150">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="d4785-150">ResponseCode</span></span>](responsecode.md) <br/> |<span data-ttu-id="d4785-151">Fornece um código de erro que identifica o erro específico que a solicitação encontrou.</span><span class="sxs-lookup"><span data-stu-id="d4785-151">Provides an error code that identifies the specific error that the request encountered.</span></span>  <br/> |
|[<span data-ttu-id="d4785-152">DescriptiveLinkKey</span><span class="sxs-lookup"><span data-stu-id="d4785-152">DescriptiveLinkKey</span></span>](descriptivelinkkey.md) <br/> |<span data-ttu-id="d4785-153">Não utilizado no momento e está reservado para uso futuro.</span><span class="sxs-lookup"><span data-stu-id="d4785-153">Currently unused and is reserved for future use.</span></span> <span data-ttu-id="d4785-154">Ele contém um valor de 0.</span><span class="sxs-lookup"><span data-stu-id="d4785-154">It contains a value of 0.</span></span>  <br/> |
|[<span data-ttu-id="d4785-155">MessageXml</span><span class="sxs-lookup"><span data-stu-id="d4785-155">MessageXml</span></span>](messagexml.md) <br/> |<span data-ttu-id="d4785-156">Fornece informações adicionais de resposta de erro.</span><span class="sxs-lookup"><span data-stu-id="d4785-156">Provides additional error response information.</span></span>  <br/> |
|[<span data-ttu-id="d4785-157">RootItemId</span><span class="sxs-lookup"><span data-stu-id="d4785-157">RootItemId</span></span>](rootitemid.md) <br/> |<span data-ttu-id="d4785-158">Identifica o item pai de um anexo excluído.</span><span class="sxs-lookup"><span data-stu-id="d4785-158">Identifies the parent item of a deleted attachment.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="d4785-159">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="d4785-159">Parent elements</span></span>

|<span data-ttu-id="d4785-160">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="d4785-160">**Element**</span></span>|<span data-ttu-id="d4785-161">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="d4785-161">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="d4785-162">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="d4785-162">ResponseMessages</span></span>](responsemessages.md) <br/> |<span data-ttu-id="d4785-163">Contém as mensagens de resposta para uma solicitação de serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="d4785-163">Contains the response messages for an Exchange Web Services request.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="d4785-164">Comentários</span><span class="sxs-lookup"><span data-stu-id="d4785-164">Remarks</span></span>

<span data-ttu-id="d4785-165">O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o Exchange Server com a função de servidor de acesso para Cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="d4785-165">The schema that describes this element is located in the EWS virtual directory of the computer that is running Exchange Server with the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="d4785-166">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="d4785-166">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="d4785-167">Namespace</span><span class="sxs-lookup"><span data-stu-id="d4785-167">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="d4785-168">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="d4785-168">Schema Name</span></span>  <br/> |<span data-ttu-id="d4785-169">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="d4785-169">Messages schema</span></span>  <br/> |
|<span data-ttu-id="d4785-170">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="d4785-170">Validation File</span></span>  <br/> |<span data-ttu-id="d4785-171">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="d4785-171">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="d4785-172">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="d4785-172">Can be Empty</span></span>  <br/> |<span data-ttu-id="d4785-173">False</span><span class="sxs-lookup"><span data-stu-id="d4785-173">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="d4785-174">Confira também</span><span class="sxs-lookup"><span data-stu-id="d4785-174">See also</span></span>

- [<span data-ttu-id="d4785-175">DeleteAttachment</span><span class="sxs-lookup"><span data-stu-id="d4785-175">DeleteAttachment</span></span>](deleteattachment.md) 
- [<span data-ttu-id="d4785-176">Operação DeleteAttachment</span><span class="sxs-lookup"><span data-stu-id="d4785-176">DeleteAttachment operation</span></span>](deleteattachment-operation.md)
- [<span data-ttu-id="d4785-177">Referência do EWS para Exchange</span><span class="sxs-lookup"><span data-stu-id="d4785-177">EWS reference for Exchange</span></span>](ews-reference-for-exchange.md) 
- [<span data-ttu-id="d4785-178">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="d4785-178">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

