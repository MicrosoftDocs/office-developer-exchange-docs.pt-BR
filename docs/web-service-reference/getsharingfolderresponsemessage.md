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
description: O elemento GetSharingFolderResponseMessage contém o status e o resultado de uma única solicitação de operação de GetSharingFolder.
ms.openlocfilehash: 85a78a23bac72942c6278b5d97e2bb4c2992ab46
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44463955"
---
# <a name="getsharingfolderresponsemessage"></a><span data-ttu-id="13b2f-103">GetSharingFolderResponseMessage</span><span class="sxs-lookup"><span data-stu-id="13b2f-103">GetSharingFolderResponseMessage</span></span>

<span data-ttu-id="13b2f-104">O elemento **GetSharingFolderResponseMessage** contém o status e o resultado de uma única solicitação de [operação de GetSharingFolder](getsharingfolder-operation.md) .</span><span class="sxs-lookup"><span data-stu-id="13b2f-104">The **GetSharingFolderResponseMessage** element contains the status and result of a single [GetSharingFolder operation](getsharingfolder-operation.md) request.</span></span> 
  
```xml
<GetSharingFolderResponseMessage ResponseClass="">
   <MessageText/>
   <ResponseCode/>
   <DescriptiveLinkKey/>
   <MessageXml/>   <SharingFolderId/>
</GetSharingFolderResponseMessage>
```

 <span data-ttu-id="13b2f-105">**GetSharingFolderResponseMessageType**</span><span class="sxs-lookup"><span data-stu-id="13b2f-105">**GetSharingFolderResponseMessageType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="13b2f-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="13b2f-106">Attributes and elements</span></span>

<span data-ttu-id="13b2f-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="13b2f-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="13b2f-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="13b2f-108">Attributes</span></span>

|<span data-ttu-id="13b2f-109">**Atributo**</span><span class="sxs-lookup"><span data-stu-id="13b2f-109">**Attribute**</span></span>|<span data-ttu-id="13b2f-110">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="13b2f-110">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="13b2f-111">**ResponseClass**</span><span class="sxs-lookup"><span data-stu-id="13b2f-111">**ResponseClass**</span></span> <br/> | <span data-ttu-id="13b2f-112">Descreve o status da resposta.</span><span class="sxs-lookup"><span data-stu-id="13b2f-112">Describes the status of the response.</span></span> <br/><br/><span data-ttu-id="13b2f-113">Os seguintes valores são válidos para este atributo:</span><span class="sxs-lookup"><span data-stu-id="13b2f-113">The following values are valid for this attribute:</span></span>  <br/><br/><span data-ttu-id="13b2f-114">-Êxito</span><span class="sxs-lookup"><span data-stu-id="13b2f-114">-  Success</span></span>  <br/><span data-ttu-id="13b2f-115">-Aviso</span><span class="sxs-lookup"><span data-stu-id="13b2f-115">-  Warning</span></span>  <br/><span data-ttu-id="13b2f-116">-Erro</span><span class="sxs-lookup"><span data-stu-id="13b2f-116">-  Error</span></span>  <br/> |
   
#### <a name="responseclass-attribute-values"></a><span data-ttu-id="13b2f-117">Valores de atributo ResponseClass</span><span class="sxs-lookup"><span data-stu-id="13b2f-117">ResponseClass attribute values</span></span>

|<span data-ttu-id="13b2f-118">**Valor**</span><span class="sxs-lookup"><span data-stu-id="13b2f-118">**Value**</span></span>|<span data-ttu-id="13b2f-119">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="13b2f-119">**Description**</span></span>|
|:-----|:-----|
|<span data-ttu-id="13b2f-120">**Success**</span><span class="sxs-lookup"><span data-stu-id="13b2f-120">**Success**</span></span> <br/> |<span data-ttu-id="13b2f-121">Descreve uma solicitação que é atendida.</span><span class="sxs-lookup"><span data-stu-id="13b2f-121">Describes a request that is fulfilled.</span></span>  <br/> |
|<span data-ttu-id="13b2f-122">**Aviso**</span><span class="sxs-lookup"><span data-stu-id="13b2f-122">**Warning**</span></span> <br/> | <span data-ttu-id="13b2f-123">Descreve uma solicitação que não foi processada.</span><span class="sxs-lookup"><span data-stu-id="13b2f-123">Describes a request that was not processed.</span></span> <span data-ttu-id="13b2f-124">Um aviso pode ser retornado se um erro ocorreu enquanto um item na solicitação estava sendo processado e não foi possível processar os itens subsequentes.</span><span class="sxs-lookup"><span data-stu-id="13b2f-124">A warning may be returned if an error occurred while an item in the request was processing and subsequent items could not be processed.</span></span> <br/><br/><span data-ttu-id="13b2f-125">A seguir estão exemplos de fontes de avisos:</span><span class="sxs-lookup"><span data-stu-id="13b2f-125">The following are examples of sources of warnings:</span></span>  <br/><br/><span data-ttu-id="13b2f-126">– O repositório do Exchange está offline durante o lote.</span><span class="sxs-lookup"><span data-stu-id="13b2f-126">-  The Exchange store is offline during the batch.</span></span>  <br/><span data-ttu-id="13b2f-127">– O serviço de diretório do Active Directory está offline.</span><span class="sxs-lookup"><span data-stu-id="13b2f-127">-  The Active Directory directory service is offline.</span></span>  <br/><span data-ttu-id="13b2f-128">-As caixas de correio foram movidas.</span><span class="sxs-lookup"><span data-stu-id="13b2f-128">-  Mailboxes were moved.</span></span>  <br/><span data-ttu-id="13b2f-129">– O banco de dados de mensagens (MDB) está offline.</span><span class="sxs-lookup"><span data-stu-id="13b2f-129">-  The message database (MDB) is offline.</span></span>  <br/><span data-ttu-id="13b2f-130">-Uma senha expirou.</span><span class="sxs-lookup"><span data-stu-id="13b2f-130">-  A password is expired.</span></span>  <br/><span data-ttu-id="13b2f-131">-Uma cota foi excedida.</span><span class="sxs-lookup"><span data-stu-id="13b2f-131">-  A quota has been exceeded.</span></span>  <br/> |
|<span data-ttu-id="13b2f-132">**Error**</span><span class="sxs-lookup"><span data-stu-id="13b2f-132">**Error**</span></span> <br/> | <span data-ttu-id="13b2f-133">Descreve uma solicitação que não pode ser atendida.</span><span class="sxs-lookup"><span data-stu-id="13b2f-133">Describes a request that cannot be fulfilled.</span></span> <br/><br/><span data-ttu-id="13b2f-134">A seguir estão exemplos de fontes de erros:</span><span class="sxs-lookup"><span data-stu-id="13b2f-134">The following are examples of sources of errors:</span></span>  <br/><br/><span data-ttu-id="13b2f-135">-Atributos ou elementos inválidos</span><span class="sxs-lookup"><span data-stu-id="13b2f-135">-  Invalid attributes or elements</span></span>  <br/><span data-ttu-id="13b2f-136">-Atributos ou elementos fora do intervalo</span><span class="sxs-lookup"><span data-stu-id="13b2f-136">-  Attributes or elements out of range</span></span>  <br/><span data-ttu-id="13b2f-137">– Marca desconhecida</span><span class="sxs-lookup"><span data-stu-id="13b2f-137">-  Unknown tag</span></span>  <br/><span data-ttu-id="13b2f-138">-Atributo ou elemento não válido no contexto</span><span class="sxs-lookup"><span data-stu-id="13b2f-138">-  Attribute or element not valid in the context</span></span>  <br/><span data-ttu-id="13b2f-139">– Tentativa de acesso não autorizado por qualquer cliente</span><span class="sxs-lookup"><span data-stu-id="13b2f-139">-  Unauthorized access attempt by any client</span></span>  <br/><span data-ttu-id="13b2f-140">-Falha do servidor em resposta a uma chamada válida do lado do cliente</span><span class="sxs-lookup"><span data-stu-id="13b2f-140">-  Server-side failure in response to a valid client-side call</span></span>  <br/><br/>  <span data-ttu-id="13b2f-141">As informações sobre o erro podem ser encontradas nos elementos [ResponseCode](responsecode.md) e [MessageText](messagetext.md) .</span><span class="sxs-lookup"><span data-stu-id="13b2f-141">Information about the error can be found in the [ResponseCode](responsecode.md) and [MessageText](messagetext.md) elements.</span></span>  <br/> |
   
### <a name="child-elements"></a><span data-ttu-id="13b2f-142">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="13b2f-142">Child elements</span></span>

|<span data-ttu-id="13b2f-143">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="13b2f-143">**Element**</span></span>|<span data-ttu-id="13b2f-144">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="13b2f-144">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="13b2f-145">MessageText</span><span class="sxs-lookup"><span data-stu-id="13b2f-145">MessageText</span></span>](messagetext.md) <br/> |<span data-ttu-id="13b2f-146">Fornece uma descrição de texto do status da resposta.</span><span class="sxs-lookup"><span data-stu-id="13b2f-146">Provides a text description of the status of the response.</span></span>  <br/> |
|[<span data-ttu-id="13b2f-147">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="13b2f-147">ResponseCode</span></span>](responsecode.md) <br/> |<span data-ttu-id="13b2f-148">Fornece um código de erro que identifica o erro específico que a solicitação encontrou.</span><span class="sxs-lookup"><span data-stu-id="13b2f-148">Provides an error code that identifies the specific error that the request encountered.</span></span>  <br/> |
|[<span data-ttu-id="13b2f-149">DescriptiveLinkKey</span><span class="sxs-lookup"><span data-stu-id="13b2f-149">DescriptiveLinkKey</span></span>](descriptivelinkkey.md) <br/> |<span data-ttu-id="13b2f-150">Atualmente não usado e reservado para uso futuro.</span><span class="sxs-lookup"><span data-stu-id="13b2f-150">Currently unused and reserved for future use.</span></span> <span data-ttu-id="13b2f-151">Este elemento contém um valor de 0.</span><span class="sxs-lookup"><span data-stu-id="13b2f-151">This element contains a value of 0.</span></span>  <br/> |
|[<span data-ttu-id="13b2f-152">MessageXml</span><span class="sxs-lookup"><span data-stu-id="13b2f-152">MessageXml</span></span>](messagexml.md) <br/> |<span data-ttu-id="13b2f-153">Fornece informações adicionais de resposta de erro.</span><span class="sxs-lookup"><span data-stu-id="13b2f-153">Provides additional error response information.</span></span>  <br/> |
|[<span data-ttu-id="13b2f-154">SharingFolderId</span><span class="sxs-lookup"><span data-stu-id="13b2f-154">SharingFolderId</span></span>](sharingfolderid.md) <br/> |<span data-ttu-id="13b2f-155">Representa o identificador da pasta local em uma relação de compartilhamento.</span><span class="sxs-lookup"><span data-stu-id="13b2f-155">Represents the identifier of the local folder in a sharing relationship.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="13b2f-156">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="13b2f-156">Parent elements</span></span>

|<span data-ttu-id="13b2f-157">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="13b2f-157">**Element**</span></span>|<span data-ttu-id="13b2f-158">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="13b2f-158">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="13b2f-159">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="13b2f-159">ResponseMessages</span></span>](responsemessages.md) <br/> |<span data-ttu-id="13b2f-160">Contém as mensagens de resposta para uma solicitação de serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="13b2f-160">Contains the response messages for an Exchange Web Services request.</span></span>  <br/> |
   
## <a name="remarks"></a><span data-ttu-id="13b2f-161">Comentários</span><span class="sxs-lookup"><span data-stu-id="13b2f-161">Remarks</span></span>

<span data-ttu-id="13b2f-162">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os serviços Web do Exchange do computador que está executando o Microsoft Exchange Server que tem a função de servidor de acesso para Cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="13b2f-162">The schema that describes this element is located in the IIS Virtual directory that hosts Exchange Web Services of the computer that is running Microsoft Exchange Server that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="13b2f-163">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="13b2f-163">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="13b2f-164">Namespace</span><span class="sxs-lookup"><span data-stu-id="13b2f-164">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="13b2f-165">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="13b2f-165">Schema Name</span></span>  <br/> |<span data-ttu-id="13b2f-166">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="13b2f-166">Messages schema</span></span>  <br/> |
|<span data-ttu-id="13b2f-167">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="13b2f-167">Validation File</span></span>  <br/> |<span data-ttu-id="13b2f-168">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="13b2f-168">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="13b2f-169">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="13b2f-169">Can be Empty</span></span>  <br/> |<span data-ttu-id="13b2f-170">False</span><span class="sxs-lookup"><span data-stu-id="13b2f-170">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="13b2f-171">Confira também</span><span class="sxs-lookup"><span data-stu-id="13b2f-171">See also</span></span>

- [<span data-ttu-id="13b2f-172">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="13b2f-172">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

