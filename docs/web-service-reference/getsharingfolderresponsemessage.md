---
title: GetSharingFolderResponseMessage
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- GetSharingFolderResponseMessage
api_type:
- schema
ms.assetid: b6f5fd09-09f3-4e34-84b4-2f6c1f10f28f
description: O elemento GetSharingFolderResponseMessage contém o status e o resultado de uma única solicitação de operação GetSharingFolder.
ms.openlocfilehash: 13ce3f628ff125140fc7459df5d567a67ddf7bc2
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19823672"
---
# <a name="getsharingfolderresponsemessage"></a><span data-ttu-id="c660a-103">GetSharingFolderResponseMessage</span><span class="sxs-lookup"><span data-stu-id="c660a-103">GetSharingFolderResponseMessage</span></span>

<span data-ttu-id="c660a-104">O elemento **GetSharingFolderResponseMessage** contém o status e o resultado de uma única solicitação de [operação GetSharingFolder](getsharingfolder-operation.md) .</span><span class="sxs-lookup"><span data-stu-id="c660a-104">The **GetSharingFolderResponseMessage** element contains the status and result of a single [GetSharingFolder operation](getsharingfolder-operation.md) request.</span></span> 
  
```xml
<GetSharingFolderResponseMessage ResponseClass="">
   <MessageText/>
   <ResponseCode/>
   <DescriptiveLinkKey/>
   <MessageXml/>   <SharingFolderId/>
</GetSharingFolderResponseMessage>
```

 <span data-ttu-id="c660a-105">**GetSharingFolderResponseMessageType**</span><span class="sxs-lookup"><span data-stu-id="c660a-105">**GetSharingFolderResponseMessageType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="c660a-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="c660a-106">Attributes and elements</span></span>

<span data-ttu-id="c660a-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="c660a-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="c660a-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="c660a-108">Attributes</span></span>

|<span data-ttu-id="c660a-109">**Attribute**</span><span class="sxs-lookup"><span data-stu-id="c660a-109">**Attribute**</span></span>|<span data-ttu-id="c660a-110">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="c660a-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="c660a-111">**ResponseClass**</span><span class="sxs-lookup"><span data-stu-id="c660a-111">**ResponseClass**</span></span> <br/> | <span data-ttu-id="c660a-112">Descreve o status da resposta.</span><span class="sxs-lookup"><span data-stu-id="c660a-112">Describes the status of the response.</span></span> <br/><br/><span data-ttu-id="c660a-113">Os seguintes valores são válidos para este atributo:</span><span class="sxs-lookup"><span data-stu-id="c660a-113">The following values are valid for this attribute:</span></span>  <br/><br/><span data-ttu-id="c660a-114">-Êxito</span><span class="sxs-lookup"><span data-stu-id="c660a-114">-  Success</span></span>  <br/><span data-ttu-id="c660a-115">-Aviso</span><span class="sxs-lookup"><span data-stu-id="c660a-115">-  Warning</span></span>  <br/><span data-ttu-id="c660a-116">-Erro</span><span class="sxs-lookup"><span data-stu-id="c660a-116">-  Error</span></span>  <br/> |
   
#### <a name="responseclass-attribute-values"></a><span data-ttu-id="c660a-117">Valores de atributo ResponseClass</span><span class="sxs-lookup"><span data-stu-id="c660a-117">ResponseClass attribute values</span></span>

|<span data-ttu-id="c660a-118">**Valor**</span><span class="sxs-lookup"><span data-stu-id="c660a-118">**Value**</span></span>|<span data-ttu-id="c660a-119">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="c660a-119">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="c660a-120">**Sucesso**</span><span class="sxs-lookup"><span data-stu-id="c660a-120">**Success**</span></span> <br/> |<span data-ttu-id="c660a-121">Descreve uma solicitação que seja cumprida.</span><span class="sxs-lookup"><span data-stu-id="c660a-121">Describes a request that is fulfilled.</span></span>  <br/> |
|<span data-ttu-id="c660a-122">**Warning**</span><span class="sxs-lookup"><span data-stu-id="c660a-122">**Warning**</span></span> <br/> | <span data-ttu-id="c660a-123">Descreve uma solicitação que não foi processada.</span><span class="sxs-lookup"><span data-stu-id="c660a-123">Describes a request that was not processed.</span></span> <span data-ttu-id="c660a-124">Um aviso pode ser retornado se ocorreu um erro quando um item na solicitação estava processando e itens subsequentes não pôde ser processados.</span><span class="sxs-lookup"><span data-stu-id="c660a-124">A warning may be returned if an error occurred while an item in the request was processing and subsequent items could not be processed.</span></span> <br/><br/><span data-ttu-id="c660a-125">Estes são exemplos de fontes de avisos de:</span><span class="sxs-lookup"><span data-stu-id="c660a-125">The following are examples of sources of warnings:</span></span>  <br/><br/><span data-ttu-id="c660a-126">-O armazenamento do Exchange está offline durante o lote.</span><span class="sxs-lookup"><span data-stu-id="c660a-126">-  The Exchange store is offline during the batch.</span></span>  <br/><span data-ttu-id="c660a-127">-O serviço de diretório do Active Directory está offline.</span><span class="sxs-lookup"><span data-stu-id="c660a-127">-  The Active Directory directory service is offline.</span></span>  <br/><span data-ttu-id="c660a-128">-Caixas de correio foram movidos.</span><span class="sxs-lookup"><span data-stu-id="c660a-128">-  Mailboxes were moved.</span></span>  <br/><span data-ttu-id="c660a-129">-O banco de dados de mensagens (MDB) está offline.</span><span class="sxs-lookup"><span data-stu-id="c660a-129">-  The message database (MDB) is offline.</span></span>  <br/><span data-ttu-id="c660a-130">-Uma senha expirou.</span><span class="sxs-lookup"><span data-stu-id="c660a-130">-  A password is expired.</span></span>  <br/><span data-ttu-id="c660a-131">-Uma cota foi excedida.</span><span class="sxs-lookup"><span data-stu-id="c660a-131">-  A quota has been exceeded.</span></span>  <br/> |
|<span data-ttu-id="c660a-132">**Erro**</span><span class="sxs-lookup"><span data-stu-id="c660a-132">**Error**</span></span> <br/> | <span data-ttu-id="c660a-133">Descreve uma solicitação que não puder ser atendida.</span><span class="sxs-lookup"><span data-stu-id="c660a-133">Describes a request that cannot be fulfilled.</span></span> <br/><br/><span data-ttu-id="c660a-134">Estes são exemplos de fontes de erros:</span><span class="sxs-lookup"><span data-stu-id="c660a-134">The following are examples of sources of errors:</span></span>  <br/><br/><span data-ttu-id="c660a-135">-Inválido atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="c660a-135">-  Invalid attributes or elements</span></span>  <br/><span data-ttu-id="c660a-136">-Atributos ou elementos fora do intervalo</span><span class="sxs-lookup"><span data-stu-id="c660a-136">-  Attributes or elements out of range</span></span>  <br/><span data-ttu-id="c660a-137">-Marca desconhecida</span><span class="sxs-lookup"><span data-stu-id="c660a-137">-  Unknown tag</span></span>  <br/><span data-ttu-id="c660a-138">-Atributo ou elemento não é válido no contexto</span><span class="sxs-lookup"><span data-stu-id="c660a-138">-  Attribute or element not valid in the context</span></span>  <br/><span data-ttu-id="c660a-139">-Tentativa de acesso não autorizado de qualquer cliente</span><span class="sxs-lookup"><span data-stu-id="c660a-139">-  Unauthorized access attempt by any client</span></span>  <br/><span data-ttu-id="c660a-140">-Falha server-side em resposta a uma chamada de cliente válida</span><span class="sxs-lookup"><span data-stu-id="c660a-140">-  Server-side failure in response to a valid client-side call</span></span>  <br/><br/>  <span data-ttu-id="c660a-141">Informações sobre o erro podem ser encontradas nos elementos [ResponseCode](responsecode.md) e [MessageText](messagetext.md) .</span><span class="sxs-lookup"><span data-stu-id="c660a-141">Information about the error can be found in the [ResponseCode](responsecode.md) and [MessageText](messagetext.md) elements.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="c660a-142">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="c660a-142">Child elements</span></span>

|<span data-ttu-id="c660a-143">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="c660a-143">**Element**</span></span>|<span data-ttu-id="c660a-144">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="c660a-144">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="c660a-145">MessageText</span><span class="sxs-lookup"><span data-stu-id="c660a-145">MessageText</span></span>](messagetext.md) <br/> |<span data-ttu-id="c660a-146">Fornece uma descrição de texto do status da resposta.</span><span class="sxs-lookup"><span data-stu-id="c660a-146">Provides a text description of the status of the response.</span></span>  <br/> |
|[<span data-ttu-id="c660a-147">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="c660a-147">ResponseCode</span></span>](responsecode.md) <br/> |<span data-ttu-id="c660a-148">Fornece um código de erro que identifica o erro específico que enfrentaram a solicitação.</span><span class="sxs-lookup"><span data-stu-id="c660a-148">Provides an error code that identifies the specific error that the request encountered.</span></span>  <br/> |
|[<span data-ttu-id="c660a-149">DescriptiveLinkKey</span><span class="sxs-lookup"><span data-stu-id="c660a-149">DescriptiveLinkKey</span></span>](descriptivelinkkey.md) <br/> |<span data-ttu-id="c660a-150">No momento não utilizados e reservada para uso futuro.</span><span class="sxs-lookup"><span data-stu-id="c660a-150">Currently unused and reserved for future use.</span></span> <span data-ttu-id="c660a-151">Esse elemento contém um valor de 0.</span><span class="sxs-lookup"><span data-stu-id="c660a-151">This element contains a value of 0.</span></span>  <br/> |
|[<span data-ttu-id="c660a-152">MessageXml</span><span class="sxs-lookup"><span data-stu-id="c660a-152">MessageXml</span></span>](messagexml.md) <br/> |<span data-ttu-id="c660a-153">Fornece informações de resposta de erro adicionais.</span><span class="sxs-lookup"><span data-stu-id="c660a-153">Provides additional error response information.</span></span>  <br/> |
|[<span data-ttu-id="c660a-154">SharingFolderId</span><span class="sxs-lookup"><span data-stu-id="c660a-154">SharingFolderId</span></span>](sharingfolderid.md) <br/> |<span data-ttu-id="c660a-155">Representa o identificador da pasta local em uma relação de compartilhamento.</span><span class="sxs-lookup"><span data-stu-id="c660a-155">Represents the identifier of the local folder in a sharing relationship.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="c660a-156">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="c660a-156">Parent elements</span></span>

|<span data-ttu-id="c660a-157">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="c660a-157">**Element**</span></span>|<span data-ttu-id="c660a-158">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="c660a-158">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="c660a-159">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="c660a-159">ResponseMessages</span></span>](responsemessages.md) <br/> |<span data-ttu-id="c660a-160">Contém as mensagens de resposta para uma solicitação de serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="c660a-160">Contains the response messages for an Exchange Web Services request.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="c660a-161">Coment�rios</span><span class="sxs-lookup"><span data-stu-id="c660a-161">Remarks</span></span>

<span data-ttu-id="c660a-162">O esquema que descreve este elemento está localizado no diretório Virtual do IIS que hospeda o Exchange Web Services do computador que está executando o Microsoft Exchange Server que tem a função de servidor acesso para cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="c660a-162">The schema that describes this element is located in the IIS Virtual directory that hosts Exchange Web Services of the computer that is running Microsoft Exchange Server that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="c660a-163">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="c660a-163">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="c660a-164">Namespace</span><span class="sxs-lookup"><span data-stu-id="c660a-164">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="c660a-165">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="c660a-165">Schema Name</span></span>  <br/> |<span data-ttu-id="c660a-166">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="c660a-166">Messages schema</span></span>  <br/> |
|<span data-ttu-id="c660a-167">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="c660a-167">Validation File</span></span>  <br/> |<span data-ttu-id="c660a-168">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="c660a-168">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="c660a-169">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="c660a-169">Can be Empty</span></span>  <br/> |<span data-ttu-id="c660a-170">False</span><span class="sxs-lookup"><span data-stu-id="c660a-170">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="c660a-171">Ver também</span><span class="sxs-lookup"><span data-stu-id="c660a-171">See also</span></span>

- [<span data-ttu-id="c660a-172">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="c660a-172">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

