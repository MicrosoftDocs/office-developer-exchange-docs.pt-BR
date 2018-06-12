---
title: GetAttachmentResponseMessage
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- GetAttachmentResponseMessage
api_type:
- schema
ms.assetid: f0a841af-422d-4c82-b710-41e2038dbee4
description: O elemento GetAttachmentResponseMessage contém o status e o resultado de uma única solicitação de operação GetAttachment.
ms.openlocfilehash: 3bf5aac8ba85675e2941acef6f06eb24f0667d17
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19752413"
---
# <a name="getattachmentresponsemessage"></a><span data-ttu-id="fc029-103">GetAttachmentResponseMessage</span><span class="sxs-lookup"><span data-stu-id="fc029-103">GetAttachmentResponseMessage</span></span>

<span data-ttu-id="fc029-104">O elemento **GetAttachmentResponseMessage** contém o status e o resultado de uma única [operação GetAttachment](getattachment-operation.md) solicitação.</span><span class="sxs-lookup"><span data-stu-id="fc029-104">The **GetAttachmentResponseMessage** element contains the status and result of a single [GetAttachment operation](getattachment-operation.md) request.</span></span> 
  
- [<span data-ttu-id="fc029-105">GetAttachmentResponse</span><span class="sxs-lookup"><span data-stu-id="fc029-105">GetAttachmentResponse</span></span>](getattachmentresponse.md) 
- [<span data-ttu-id="fc029-106">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="fc029-106">ResponseMessages</span></span>](responsemessages.md) 
- [<span data-ttu-id="fc029-107">GetAttachmentResponseMessage</span><span class="sxs-lookup"><span data-stu-id="fc029-107">GetAttachmentResponseMessage</span></span>](getattachmentresponsemessage.md)
  
```xml
<GetAttachmentResponseMessage ResponseClass="">
   <MessageText/>
   <ResponseCode/>
   <DescriptiveLinkKey/>
   <MessageXml/>
   <Attachments/>
</GetAttachmentResponseMessage>
```

 <span data-ttu-id="fc029-108">**AttachmentInfoResponseMessageType**</span><span class="sxs-lookup"><span data-stu-id="fc029-108">**AttachmentInfoResponseMessageType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="fc029-109">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="fc029-109">Attributes and elements</span></span>

<span data-ttu-id="fc029-110">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="fc029-110">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="fc029-111">Atributos</span><span class="sxs-lookup"><span data-stu-id="fc029-111">Attributes</span></span>

|<span data-ttu-id="fc029-112">**Attribute**</span><span class="sxs-lookup"><span data-stu-id="fc029-112">**Attribute**</span></span>|<span data-ttu-id="fc029-113">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="fc029-113">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="fc029-114">**ResponseClass**</span><span class="sxs-lookup"><span data-stu-id="fc029-114">**ResponseClass**</span></span> <br/> | <span data-ttu-id="fc029-115">Descreve o status de uma resposta [GetAttachment operação](getattachment-operation.md) .</span><span class="sxs-lookup"><span data-stu-id="fc029-115">Describes the status of a [GetAttachment operation](getattachment-operation.md) response.</span></span><br/><br/> <span data-ttu-id="fc029-116">Os seguintes valores são válidos para este atributo:</span><span class="sxs-lookup"><span data-stu-id="fc029-116">The following values are valid for this attribute:</span></span> <br/> <br/><span data-ttu-id="fc029-117">-Êxito</span><span class="sxs-lookup"><span data-stu-id="fc029-117">-  Success</span></span>  <br/><span data-ttu-id="fc029-118">-Aviso</span><span class="sxs-lookup"><span data-stu-id="fc029-118">-  Warning</span></span>  <br/><span data-ttu-id="fc029-119">-Erro</span><span class="sxs-lookup"><span data-stu-id="fc029-119">-  Error</span></span>  <br/> |
   
#### <a name="responseclass-attribute"></a><span data-ttu-id="fc029-120">Atributo ResponseClass</span><span class="sxs-lookup"><span data-stu-id="fc029-120">ResponseClass Attribute</span></span>

|<span data-ttu-id="fc029-121">**Valor**</span><span class="sxs-lookup"><span data-stu-id="fc029-121">**Value**</span></span>|<span data-ttu-id="fc029-122">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="fc029-122">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="fc029-123">Êxito</span><span class="sxs-lookup"><span data-stu-id="fc029-123">Success</span></span>  <br/> |<span data-ttu-id="fc029-124">Descreve uma solicitação que seja cumprida.</span><span class="sxs-lookup"><span data-stu-id="fc029-124">Describes a request that is fulfilled.</span></span>  <br/> |
|<span data-ttu-id="fc029-125">Aviso</span><span class="sxs-lookup"><span data-stu-id="fc029-125">Warning</span></span>  <br/> | <span data-ttu-id="fc029-126">Descreve uma solicitação que não foi processada.</span><span class="sxs-lookup"><span data-stu-id="fc029-126">Describes a request that was not processed.</span></span> <span data-ttu-id="fc029-127">Um aviso pode ser retornado se ocorreu um erro quando um item na solicitação estava processando e itens subsequentes não pôde ser processados.</span><span class="sxs-lookup"><span data-stu-id="fc029-127">A warning may be returned if an error occurred while an item in the request was processing and subsequent items could not be processed.</span></span> <br/><br/><span data-ttu-id="fc029-128">Estes são exemplos de fontes de avisos de:</span><span class="sxs-lookup"><span data-stu-id="fc029-128">The following are examples of sources of warnings:</span></span> <br/> <br/><span data-ttu-id="fc029-129">-O armazenamento do Exchange está offline durante o lote.</span><span class="sxs-lookup"><span data-stu-id="fc029-129">-  The Exchange store is offline during the batch.</span></span>  <br/><span data-ttu-id="fc029-130">-Active Directory Domain Services (AD DS) está offline.</span><span class="sxs-lookup"><span data-stu-id="fc029-130">-  Active Directory Domain Services (AD DS) is offline.</span></span>  <br/><span data-ttu-id="fc029-131">-Caixas de correio são movidas.</span><span class="sxs-lookup"><span data-stu-id="fc029-131">-  Mailboxes are moved.</span></span>  <br/><span data-ttu-id="fc029-132">-O banco de dados de mensagens (MDB) está offline.</span><span class="sxs-lookup"><span data-stu-id="fc029-132">-  The message database (MDB) is offline.</span></span>  <br/><span data-ttu-id="fc029-133">-Uma senha expirou.</span><span class="sxs-lookup"><span data-stu-id="fc029-133">-  A password is expired.</span></span>  <br/><span data-ttu-id="fc029-134">-Uma cota for excedida.</span><span class="sxs-lookup"><span data-stu-id="fc029-134">-  A quota is exceeded.</span></span>  <br/> |
|<span data-ttu-id="fc029-135">Erro</span><span class="sxs-lookup"><span data-stu-id="fc029-135">Error</span></span>  <br/> | <span data-ttu-id="fc029-136">Descreve uma solicitação que não puder ser atendida.</span><span class="sxs-lookup"><span data-stu-id="fc029-136">Describes a request that cannot be fulfilled.</span></span> <br/><br/><span data-ttu-id="fc029-137">Estes são exemplos de fontes de erros:</span><span class="sxs-lookup"><span data-stu-id="fc029-137">The following are examples of sources of errors:</span></span>  <br/><br/><span data-ttu-id="fc029-138">-Inválido atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="fc029-138">-  Invalid attributes or elements</span></span>  <br/><span data-ttu-id="fc029-139">-Atributos ou elementos fora do intervalo</span><span class="sxs-lookup"><span data-stu-id="fc029-139">-  Attributes or elements out of range</span></span>  <br/><span data-ttu-id="fc029-140">-Marca desconhecida</span><span class="sxs-lookup"><span data-stu-id="fc029-140">-  Unknown tag</span></span>  <br/><span data-ttu-id="fc029-141">-Atributo ou elemento não é válido no contexto</span><span class="sxs-lookup"><span data-stu-id="fc029-141">-  Attribute or element not valid in the context</span></span>  <br/><span data-ttu-id="fc029-142">-Tentativa de acesso não autorizado de qualquer cliente</span><span class="sxs-lookup"><span data-stu-id="fc029-142">-  Unauthorized access attempt by any client</span></span>  <br/><span data-ttu-id="fc029-143">-Falha server-side em resposta a uma chamada de cliente válida</span><span class="sxs-lookup"><span data-stu-id="fc029-143">-  Server-side failure in response to a valid client-side call</span></span>  <br/><br/>  <span data-ttu-id="fc029-144">Informações sobre o erro podem ser encontradas nos elementos [ResponseCode](responsecode.md) e [MessageText](messagetext.md) .</span><span class="sxs-lookup"><span data-stu-id="fc029-144">Information about the error can be found in the [ResponseCode](responsecode.md) and [MessageText](messagetext.md) elements.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="fc029-145">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="fc029-145">Child elements</span></span>

|<span data-ttu-id="fc029-146">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="fc029-146">**Element**</span></span>|<span data-ttu-id="fc029-147">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="fc029-147">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="fc029-148">MessageText</span><span class="sxs-lookup"><span data-stu-id="fc029-148">MessageText</span></span>](messagetext.md) <br/> |<span data-ttu-id="fc029-149">Fornece uma descrição de texto do status da resposta.</span><span class="sxs-lookup"><span data-stu-id="fc029-149">Provides a text description of the status of the response.</span></span>  <br/> |
|[<span data-ttu-id="fc029-150">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="fc029-150">ResponseCode</span></span>](responsecode.md) <br/> |<span data-ttu-id="fc029-151">Fornece um código de erro que identifica o erro específico que enfrentaram a solicitação.</span><span class="sxs-lookup"><span data-stu-id="fc029-151">Provides an error code that identifies the specific error that the request encountered.</span></span>  <br/> |
|[<span data-ttu-id="fc029-152">DescriptiveLinkKey</span><span class="sxs-lookup"><span data-stu-id="fc029-152">DescriptiveLinkKey</span></span>](descriptivelinkkey.md) <br/> |<span data-ttu-id="fc029-153">No momento não utilizados e está reservado para uso futuro.</span><span class="sxs-lookup"><span data-stu-id="fc029-153">Currently unused and is reserved for future use.</span></span> <span data-ttu-id="fc029-154">Ele contém um valor de 0.</span><span class="sxs-lookup"><span data-stu-id="fc029-154">It contains a value of 0.</span></span>  <br/> |
|[<span data-ttu-id="fc029-155">MessageXml</span><span class="sxs-lookup"><span data-stu-id="fc029-155">MessageXml</span></span>](messagexml.md) <br/> |<span data-ttu-id="fc029-156">Fornece informações de resposta de erro adicionais.</span><span class="sxs-lookup"><span data-stu-id="fc029-156">Provides additional error response information.</span></span>  <br/> |
|[<span data-ttu-id="fc029-157">Anexos</span><span class="sxs-lookup"><span data-stu-id="fc029-157">Attachments</span></span>](attachments-ex15websvcsotherref.md) <br/> |<span data-ttu-id="fc029-158">Contém os itens ou arquivos que estão ttached a um item no armazenamento do Exchange.</span><span class="sxs-lookup"><span data-stu-id="fc029-158">Contains the items or files that are ttached to an item in the Exchange store.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="fc029-159">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="fc029-159">Parent elements</span></span>

|<span data-ttu-id="fc029-160">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="fc029-160">**Element**</span></span>|<span data-ttu-id="fc029-161">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="fc029-161">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="fc029-162">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="fc029-162">ResponseMessages</span></span>](responsemessages.md) <br/> |<span data-ttu-id="fc029-163">Contém as mensagens de resposta para uma solicitação de serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="fc029-163">Contains the response messages for an Exchange Web Services request.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="fc029-164">Coment�rios</span><span class="sxs-lookup"><span data-stu-id="fc029-164">Remarks</span></span>

<span data-ttu-id="fc029-165">O esquema que descreve este elemento está localizado no diretório virtual EWS do computador que está executando o Microsoft Exchange Server 2010 que tem a função de servidor acesso para cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="fc029-165">The schema that describes this element is located in the EWS virtual directory of the computer that is running Microsoft Exchange Server 2010 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="fc029-166">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="fc029-166">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="fc029-167">Namespace</span><span class="sxs-lookup"><span data-stu-id="fc029-167">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="fc029-168">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="fc029-168">Schema Name</span></span>  <br/> |<span data-ttu-id="fc029-169">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="fc029-169">Messages schema</span></span>  <br/> |
|<span data-ttu-id="fc029-170">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="fc029-170">Validation File</span></span>  <br/> |<span data-ttu-id="fc029-171">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="fc029-171">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="fc029-172">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="fc029-172">Can be Empty</span></span>  <br/> |<span data-ttu-id="fc029-173">False</span><span class="sxs-lookup"><span data-stu-id="fc029-173">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="fc029-174">Ver também</span><span class="sxs-lookup"><span data-stu-id="fc029-174">See also</span></span>

- [<span data-ttu-id="fc029-175">GetAttachment</span><span class="sxs-lookup"><span data-stu-id="fc029-175">GetAttachment</span></span>](getattachment.md) 
- [<span data-ttu-id="fc029-176">Operação GetAttachment</span><span class="sxs-lookup"><span data-stu-id="fc029-176">GetAttachment operation</span></span>](getattachment-operation.md)

