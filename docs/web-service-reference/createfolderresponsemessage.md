---
title: CreateFolderResponseMessage
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- CreateFolderResponseMessage
api_type:
- schema
ms.assetid: 1301dd15-b008-4fd9-8c89-b15a20b186e2
description: O elemento CreateFolderResponseMessage contém o status e o resultado de uma única solicitação de operação CreateFolder.
ms.openlocfilehash: c587cca1f935b295a0ed30ab2210de40af28d06d
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/25/2018
ms.locfileid: "19751594"
---
# <a name="createfolderresponsemessage"></a><span data-ttu-id="9e5fa-103">CreateFolderResponseMessage</span><span class="sxs-lookup"><span data-stu-id="9e5fa-103">CreateFolderResponseMessage</span></span>

<span data-ttu-id="9e5fa-104">O elemento **CreateFolderResponseMessage** contém o status e o resultado de uma única [operação CreateFolder](createfolder-operation.md) solicitação.</span><span class="sxs-lookup"><span data-stu-id="9e5fa-104">The **CreateFolderResponseMessage** element contains the status and result of a single [CreateFolder operation](createfolder-operation.md) request.</span></span> 
  
```xml
<CreateFolderResponseMessage ResponseClass="">
   <MessageText/>
   <ResponseCode/>
   <DescriptiveLinkKey/>
   <MessageXml/>
   <Folders/>
</CreateFolderResponseMessage>
```

<span data-ttu-id="9e5fa-105">**FolderInfoResponseMessageType**</span><span class="sxs-lookup"><span data-stu-id="9e5fa-105">**FolderInfoResponseMessageType**</span></span>

## <a name="attributes-and-elements"></a><span data-ttu-id="9e5fa-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="9e5fa-106">Attributes and elements</span></span>

<span data-ttu-id="9e5fa-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="9e5fa-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="9e5fa-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="9e5fa-108">Attributes</span></span>

|<span data-ttu-id="9e5fa-109">**Attribute**</span><span class="sxs-lookup"><span data-stu-id="9e5fa-109">**Attribute**</span></span>|<span data-ttu-id="9e5fa-110">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="9e5fa-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="9e5fa-111">**ResponseClass**</span><span class="sxs-lookup"><span data-stu-id="9e5fa-111">**ResponseClass**</span></span> <br/> | <span data-ttu-id="9e5fa-112">Descreve o status de uma resposta [CreateFolder operação](createfolder-operation.md) .</span><span class="sxs-lookup"><span data-stu-id="9e5fa-112">Describes the status of a [CreateFolder operation](createfolder-operation.md) response.</span></span><br/><br/><span data-ttu-id="9e5fa-113">Os seguintes valores são válidos para este atributo:</span><span class="sxs-lookup"><span data-stu-id="9e5fa-113">The following values are valid for this attribute:</span></span><br/><br/><span data-ttu-id="9e5fa-114">-Êxito</span><span class="sxs-lookup"><span data-stu-id="9e5fa-114">-  Success</span></span>  <br/><span data-ttu-id="9e5fa-115">-Aviso</span><span class="sxs-lookup"><span data-stu-id="9e5fa-115">-  Warning</span></span>  <br/><span data-ttu-id="9e5fa-116">-Erro</span><span class="sxs-lookup"><span data-stu-id="9e5fa-116">-  Error</span></span>  <br/> |
   
#### <a name="responseclass-attribute-values"></a><span data-ttu-id="9e5fa-117">Valores de atributo ResponseClass</span><span class="sxs-lookup"><span data-stu-id="9e5fa-117">ResponseClass attribute values</span></span>

|<span data-ttu-id="9e5fa-118">**Valor**</span><span class="sxs-lookup"><span data-stu-id="9e5fa-118">**Value**</span></span>|<span data-ttu-id="9e5fa-119">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="9e5fa-119">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="9e5fa-120">**Sucesso**</span><span class="sxs-lookup"><span data-stu-id="9e5fa-120">**Success**</span></span> <br/> |<span data-ttu-id="9e5fa-121">Descreve uma solicitação que seja cumprida.</span><span class="sxs-lookup"><span data-stu-id="9e5fa-121">Describes a request that is fulfilled.</span></span>  <br/> |
|<span data-ttu-id="9e5fa-122">**Warning**</span><span class="sxs-lookup"><span data-stu-id="9e5fa-122">**Warning**</span></span> <br/> | <span data-ttu-id="9e5fa-123">Descreve uma solicitação que não foi processada.</span><span class="sxs-lookup"><span data-stu-id="9e5fa-123">Describes a request that was not processed.</span></span> <span data-ttu-id="9e5fa-124">Um aviso pode ser retornado se ocorreu um erro quando um item na solicitação estava processando e itens subsequentes não pôde ser processados.</span><span class="sxs-lookup"><span data-stu-id="9e5fa-124">A warning may be returned if an error occurred while an item in the request was processing and subsequent items could not be processed.</span></span><br/><br/><span data-ttu-id="9e5fa-125">Estes são exemplos de fontes de avisos de:</span><span class="sxs-lookup"><span data-stu-id="9e5fa-125">The following are examples of sources of warnings:</span></span><br/><br/><span data-ttu-id="9e5fa-126">-O armazenamento do Exchange está offline durante o lote.</span><span class="sxs-lookup"><span data-stu-id="9e5fa-126">-  The Exchange store is offline during the batch.</span></span>  <br/><span data-ttu-id="9e5fa-127">-Active Directory Domain Services (AD DS) está offline.</span><span class="sxs-lookup"><span data-stu-id="9e5fa-127">-  Active Directory Domain Services (AD DS) is offline.</span></span>  <br/><span data-ttu-id="9e5fa-128">-Caixas de correio são movidas.</span><span class="sxs-lookup"><span data-stu-id="9e5fa-128">-  Mailboxes are moved.</span></span>  <br/><span data-ttu-id="9e5fa-129">-O banco de dados de mensagens (MDB) está offline.</span><span class="sxs-lookup"><span data-stu-id="9e5fa-129">-  The message database (MDB) is offline.</span></span>  <br/><span data-ttu-id="9e5fa-130">-Uma senha expirou.</span><span class="sxs-lookup"><span data-stu-id="9e5fa-130">-  A password is expired.</span></span>  <br/><span data-ttu-id="9e5fa-131">-Uma cota for excedida.</span><span class="sxs-lookup"><span data-stu-id="9e5fa-131">-  A quota is exceeded.</span></span>  <br/> |
|<span data-ttu-id="9e5fa-132">**Erro**</span><span class="sxs-lookup"><span data-stu-id="9e5fa-132">**Error**</span></span> <br/> | <span data-ttu-id="9e5fa-133">Descreve uma solicitação que não puder ser atendida.</span><span class="sxs-lookup"><span data-stu-id="9e5fa-133">Describes a request that cannot be fulfilled.</span></span><br/><br/><span data-ttu-id="9e5fa-134">Estes são exemplos de fontes de erros:</span><span class="sxs-lookup"><span data-stu-id="9e5fa-134">The following are examples of sources of errors:</span></span>  <br/><br/><span data-ttu-id="9e5fa-135">-Inválido atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="9e5fa-135">-  Invalid attributes or elements</span></span>  <br/><span data-ttu-id="9e5fa-136">-Atributos ou elementos fora do intervalo</span><span class="sxs-lookup"><span data-stu-id="9e5fa-136">-  Attributes or elements out of range</span></span>  <br/><span data-ttu-id="9e5fa-137">-Marca desconhecida</span><span class="sxs-lookup"><span data-stu-id="9e5fa-137">-  Unknown tag</span></span>  <br/><span data-ttu-id="9e5fa-138">-Atributo ou elemento não é válido no contexto</span><span class="sxs-lookup"><span data-stu-id="9e5fa-138">-  Attribute or element not valid in the context</span></span>  <br/><span data-ttu-id="9e5fa-139">-Tentativa de acesso não autorizado de qualquer cliente</span><span class="sxs-lookup"><span data-stu-id="9e5fa-139">-  Unauthorized access attempt by any client</span></span>  <br/><span data-ttu-id="9e5fa-140">-Falha server-side em resposta a uma chamada de cliente válida</span><span class="sxs-lookup"><span data-stu-id="9e5fa-140">-  Server-side failure in response to a valid client-side call</span></span><br/><br/>  <span data-ttu-id="9e5fa-141">Informações sobre o erro podem ser encontradas nos elementos [ResponseCode](responsecode.md) e [MessageText](messagetext.md) .</span><span class="sxs-lookup"><span data-stu-id="9e5fa-141">Information about the error can be found in the [ResponseCode](responsecode.md) and [MessageText](messagetext.md) elements.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="9e5fa-142">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="9e5fa-142">Child elements</span></span>

|<span data-ttu-id="9e5fa-143">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="9e5fa-143">**Element**</span></span>|<span data-ttu-id="9e5fa-144">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="9e5fa-144">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="9e5fa-145">MessageText</span><span class="sxs-lookup"><span data-stu-id="9e5fa-145">MessageText</span></span>](messagetext.md) <br/> |<span data-ttu-id="9e5fa-146">Fornece uma descrição de texto do status da resposta.</span><span class="sxs-lookup"><span data-stu-id="9e5fa-146">Provides a text description of the status of the response.</span></span>  <br/> |
|[<span data-ttu-id="9e5fa-147">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="9e5fa-147">ResponseCode</span></span>](responsecode.md) <br/> |<span data-ttu-id="9e5fa-148">Fornece um código de erro que identifica o erro específico que enfrentaram a solicitação.</span><span class="sxs-lookup"><span data-stu-id="9e5fa-148">Provides an error code that identifies the specific error that the request encountered.</span></span>  <br/> |
|[<span data-ttu-id="9e5fa-149">DescriptiveLinkKey</span><span class="sxs-lookup"><span data-stu-id="9e5fa-149">DescriptiveLinkKey</span></span>](descriptivelinkkey.md) <br/> |<span data-ttu-id="9e5fa-150">No momento não utilizados e está reservado para uso futuro.</span><span class="sxs-lookup"><span data-stu-id="9e5fa-150">Currently unused and is reserved for future use.</span></span> <span data-ttu-id="9e5fa-151">Ele contém um valor de 0.</span><span class="sxs-lookup"><span data-stu-id="9e5fa-151">It contains a value of 0.</span></span>  <br/> |
|[<span data-ttu-id="9e5fa-152">MessageXml</span><span class="sxs-lookup"><span data-stu-id="9e5fa-152">MessageXml</span></span>](messagexml.md) <br/> |<span data-ttu-id="9e5fa-153">Fornece informações de resposta de erro adicionais.</span><span class="sxs-lookup"><span data-stu-id="9e5fa-153">Provides additional error response information.</span></span>  <br/> |
|[<span data-ttu-id="9e5fa-154">Pastas</span><span class="sxs-lookup"><span data-stu-id="9e5fa-154">Folders</span></span>](folders-ex15websvcsotherref.md) <br/> |<span data-ttu-id="9e5fa-155">Contém uma matriz de pastas criadas.</span><span class="sxs-lookup"><span data-stu-id="9e5fa-155">Contains an array of created folders.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="9e5fa-156">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="9e5fa-156">Parent elements</span></span>

|<span data-ttu-id="9e5fa-157">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="9e5fa-157">**Element**</span></span>|<span data-ttu-id="9e5fa-158">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="9e5fa-158">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="9e5fa-159">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="9e5fa-159">ResponseMessages</span></span>](responsemessages.md) <br/> |<span data-ttu-id="9e5fa-160">Contém as mensagens de resposta para uma solicitação de serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="9e5fa-160">Contains the response messages for an Exchange Web Services request.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="9e5fa-161">Comentários</span><span class="sxs-lookup"><span data-stu-id="9e5fa-161">Remarks</span></span>

<span data-ttu-id="9e5fa-162">O esquema que descreve este elemento está localizado no diretório virtual EWS do computador que está executando o Exchange Server com a função de servidor acesso para cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="9e5fa-162">The schema that describes this element is located in the EWS virtual directory of the computer that is running Exchange Server with the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="9e5fa-163">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="9e5fa-163">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="9e5fa-164">Namespace</span><span class="sxs-lookup"><span data-stu-id="9e5fa-164">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="9e5fa-165">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="9e5fa-165">Schema Name</span></span>  <br/> |<span data-ttu-id="9e5fa-166">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="9e5fa-166">Messages schema</span></span>  <br/> |
|<span data-ttu-id="9e5fa-167">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="9e5fa-167">Validation File</span></span>  <br/> |<span data-ttu-id="9e5fa-168">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="9e5fa-168">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="9e5fa-169">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="9e5fa-169">Can be Empty</span></span>  <br/> |<span data-ttu-id="9e5fa-170">False</span><span class="sxs-lookup"><span data-stu-id="9e5fa-170">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="9e5fa-171">Ver também</span><span class="sxs-lookup"><span data-stu-id="9e5fa-171">See also</span></span>

- [<span data-ttu-id="9e5fa-172">Operação CreateFolder</span><span class="sxs-lookup"><span data-stu-id="9e5fa-172">CreateFolder operation</span></span>](createfolder-operation.md)
- [<span data-ttu-id="9e5fa-173">Referência do EWS para Exchange</span><span class="sxs-lookup"><span data-stu-id="9e5fa-173">EWS reference for Exchange</span></span>](ews-reference-for-exchange.md) 
- [<span data-ttu-id="9e5fa-174">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="9e5fa-174">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

