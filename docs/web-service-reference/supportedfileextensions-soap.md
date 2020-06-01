---
title: SupportedFileExtensions (SOAP)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
localization_priority: Normal
ms.assetid: 6f73d18c-7bb1-4ab6-a23b-6d948e590b53
description: O elemento SupportedFileExtensions lista as extensões de arquivo que podem ser armazenadas em um local de compartilhamento de documentos.
ms.openlocfilehash: d783b147a25ebbe3bff59c2142012b50bd80004e
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44433984"
---
# <a name="supportedfileextensions-soap"></a><span data-ttu-id="d0d01-103">SupportedFileExtensions (SOAP)</span><span class="sxs-lookup"><span data-stu-id="d0d01-103">SupportedFileExtensions (SOAP)</span></span>

<span data-ttu-id="d0d01-104">O elemento **SupportedFileExtensions** lista as extensões de arquivo que podem ser armazenadas em um local de compartilhamento de documentos.</span><span class="sxs-lookup"><span data-stu-id="d0d01-104">The **SupportedFileExtensions** element lists the file extensions that can be stored in a document sharing location.</span></span> 
  
```XML
<SupportedFileExtensions /> 
```

 <span data-ttu-id="d0d01-105">**ArrayOfFileExtension**</span><span class="sxs-lookup"><span data-stu-id="d0d01-105">**ArrayOfFileExtension**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="d0d01-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="d0d01-106">Attributes and elements</span></span>

<span data-ttu-id="d0d01-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="d0d01-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="d0d01-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="d0d01-108">Attributes</span></span>

<span data-ttu-id="d0d01-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="d0d01-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="d0d01-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="d0d01-110">Child elements</span></span>

|<span data-ttu-id="d0d01-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="d0d01-111">**Element**</span></span>|<span data-ttu-id="d0d01-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="d0d01-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="d0d01-113">ExtensãoDeArquivo (SOAP)</span><span class="sxs-lookup"><span data-stu-id="d0d01-113">FileExtension (SOAP)</span></span>](fileextension-soap.md) <br/> |<span data-ttu-id="d0d01-114">Representa uma extensão de arquivo.</span><span class="sxs-lookup"><span data-stu-id="d0d01-114">Represents a file extension.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="d0d01-115">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="d0d01-115">Parent elements</span></span>

|<span data-ttu-id="d0d01-116">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="d0d01-116">**Element**</span></span>|<span data-ttu-id="d0d01-117">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="d0d01-117">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="d0d01-118">DocumentSharingLocation (SOAP)</span><span class="sxs-lookup"><span data-stu-id="d0d01-118">DocumentSharingLocation (SOAP)</span></span>](documentsharinglocation-soap.md) <br/> |<span data-ttu-id="d0d01-119">Representa informações de localização e metadados de um local de compartilhamento de documentos.</span><span class="sxs-lookup"><span data-stu-id="d0d01-119">Represents location and metadata information for a document sharing location.</span></span>  <br/> |
   
## <a name="element-information"></a><span data-ttu-id="d0d01-120">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="d0d01-120">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="d0d01-121">Namespace</span><span class="sxs-lookup"><span data-stu-id="d0d01-121">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/2010/Autodiscover  <br/> |
|<span data-ttu-id="d0d01-122">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="d0d01-122">Schema Name</span></span>  <br/> |<span data-ttu-id="d0d01-123">Esquema de descoberta automática</span><span class="sxs-lookup"><span data-stu-id="d0d01-123">Autodiscover schema</span></span>  <br/> |
|<span data-ttu-id="d0d01-124">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="d0d01-124">Validation File</span></span>  <br/> |<span data-ttu-id="d0d01-125">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="d0d01-125">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="d0d01-126">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="d0d01-126">Can be Empty</span></span>  <br/> |<span data-ttu-id="d0d01-127">Verdadeiro</span><span class="sxs-lookup"><span data-stu-id="d0d01-127">True</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="d0d01-128">Também consulte</span><span class="sxs-lookup"><span data-stu-id="d0d01-128">See also</span></span>



[<span data-ttu-id="d0d01-129">Operação GetUserSettings (SOAP)</span><span class="sxs-lookup"><span data-stu-id="d0d01-129">GetUserSettings operation (SOAP)</span></span>](getusersettings-operation-soap.md)


[<span data-ttu-id="d0d01-130">Referência do serviço Web de descoberta automática do Exchange</span><span class="sxs-lookup"><span data-stu-id="d0d01-130">Autodiscover web service reference for Exchange</span></span>](autodiscover-web-service-reference-for-exchange.md)
  
[<span data-ttu-id="d0d01-131">Elementos XML de descoberta automática SOAP para o Exchange 2013</span><span class="sxs-lookup"><span data-stu-id="d0d01-131">SOAP Autodiscover XML elements for Exchange 2013</span></span>](soap-autodiscover-xml-elements-for-exchange-2013.md)

