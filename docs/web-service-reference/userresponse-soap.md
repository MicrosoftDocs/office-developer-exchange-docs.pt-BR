---
title: Resposta SOAP)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
localization_priority: Normal
api_type:
- schema
ms.assetid: 5007b1ba-bfcc-40d7-b1cb-e32fbaf54ffd
description: O elemento de resposta representa uma resposta a uma solicitação de GetUserSettings para um usuário individual.
ms.openlocfilehash: 6fcd82e06916df5acdd317cb44161c1b69e58574
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/25/2018
ms.locfileid: "19837996"
---
# <a name="userresponse-soap"></a><span data-ttu-id="b2233-103">Resposta SOAP)</span><span class="sxs-lookup"><span data-stu-id="b2233-103">UserResponse (SOAP)</span></span>

<span data-ttu-id="b2233-104">O elemento de **resposta** representa uma resposta a uma solicitação de GetUserSettings para um usuário individual.</span><span class="sxs-lookup"><span data-stu-id="b2233-104">The **UserResponse** element represents a response to a GetUserSettings request for an individual user.</span></span> 
  
```XML
<UserResponse>
   <ErrorCode/>
   <ErrorMessage/>
   <RedirectTarget/>
   <UserSettingErrors/>
   <UserSettings/>
</UserResponse>
```

 <span data-ttu-id="b2233-105">**Resposta**</span><span class="sxs-lookup"><span data-stu-id="b2233-105">**UserResponse**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="b2233-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="b2233-106">Attributes and elements</span></span>

<span data-ttu-id="b2233-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="b2233-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="b2233-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="b2233-108">Attributes</span></span>

<span data-ttu-id="b2233-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="b2233-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="b2233-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="b2233-110">Child elements</span></span>

|<span data-ttu-id="b2233-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="b2233-111">**Element**</span></span>|<span data-ttu-id="b2233-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="b2233-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="b2233-113">ErrorCode (SOAP)</span><span class="sxs-lookup"><span data-stu-id="b2233-113">ErrorCode (SOAP)</span></span>](errorcode-soap.md) <br/> |<span data-ttu-id="b2233-114">Representa um código de erro retornado pelo serviço de descoberta automática.</span><span class="sxs-lookup"><span data-stu-id="b2233-114">Represents an error code that is returned by the Autodiscover service.</span></span>  <br/> |
|[<span data-ttu-id="b2233-115">ErrorMessage (SOAP)</span><span class="sxs-lookup"><span data-stu-id="b2233-115">ErrorMessage (SOAP)</span></span>](errormessage-soap.md) <br/> |<span data-ttu-id="b2233-116">Representa uma mensagem que está associada um código de erro retornado pelo serviço de descoberta automática.</span><span class="sxs-lookup"><span data-stu-id="b2233-116">Represents a message that is associated with an error code that is returned by the Autodiscover service.</span></span>  <br/> |
|[<span data-ttu-id="b2233-117">RedirectTarget (SOAP)</span><span class="sxs-lookup"><span data-stu-id="b2233-117">RedirectTarget (SOAP)</span></span>](redirecttarget-soap.md) <br/> |<span data-ttu-id="b2233-118">Contém o destino do endereço de email ou a URL de redirecionamento.</span><span class="sxs-lookup"><span data-stu-id="b2233-118">Contains the target of the redirection URL or email address.</span></span>  <br/> |
|[<span data-ttu-id="b2233-119">UserSettingErrors (SOAP)</span><span class="sxs-lookup"><span data-stu-id="b2233-119">UserSettingErrors (SOAP)</span></span>](usersettingerrors-soap.md) <br/> |<span data-ttu-id="b2233-120">Representa uma coleção de informações sobre as configurações que não puderam ser retornadas.</span><span class="sxs-lookup"><span data-stu-id="b2233-120">Represents a collection of information about settings that could not be returned.</span></span>  <br/> |
|[<span data-ttu-id="b2233-121">UserSettings (SOAP)</span><span class="sxs-lookup"><span data-stu-id="b2233-121">UserSettings (SOAP)</span></span>](usersettings-soap.md) <br/> |<span data-ttu-id="b2233-122">As configurações solicitadas para o usuário.</span><span class="sxs-lookup"><span data-stu-id="b2233-122">The requested settings for the user.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="b2233-123">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="b2233-123">Parent elements</span></span>

|<span data-ttu-id="b2233-124">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="b2233-124">**Element**</span></span>|<span data-ttu-id="b2233-125">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="b2233-125">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="b2233-126">ArrayOfUserResponse (SOAP)</span><span class="sxs-lookup"><span data-stu-id="b2233-126">ArrayOfUserResponse (SOAP)</span></span>](arrayofuserresponse-soap.md) <br/> |<span data-ttu-id="b2233-127">Contém uma matriz de respostas do usuário.</span><span class="sxs-lookup"><span data-stu-id="b2233-127">Contains an array of user responses.</span></span>  <br/> |
|[<span data-ttu-id="b2233-128">UserResponses (SOAP)</span><span class="sxs-lookup"><span data-stu-id="b2233-128">UserResponses (SOAP)</span></span>](userresponses-soap.md) <br/> |<span data-ttu-id="b2233-129">Contém as definições de configuração para cada usuário solicitado.</span><span class="sxs-lookup"><span data-stu-id="b2233-129">Contains the configuration settings for each requested user.</span></span>  <br/> |
   
## <a name="element-information"></a><span data-ttu-id="b2233-130">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="b2233-130">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="b2233-131">Namespace</span><span class="sxs-lookup"><span data-stu-id="b2233-131">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/2010/Autodiscover  <br/> |
|<span data-ttu-id="b2233-132">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="b2233-132">Schema Name</span></span>  <br/> |<span data-ttu-id="b2233-133">Esquema de descoberta automática</span><span class="sxs-lookup"><span data-stu-id="b2233-133">Autodiscover schema</span></span>  <br/> |
|<span data-ttu-id="b2233-134">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="b2233-134">Validation File</span></span>  <br/> |<span data-ttu-id="b2233-135">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="b2233-135">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="b2233-136">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="b2233-136">Can be Empty</span></span>  <br/> |<span data-ttu-id="b2233-137">Verdadeiro</span><span class="sxs-lookup"><span data-stu-id="b2233-137">True</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="b2233-138">Ver também</span><span class="sxs-lookup"><span data-stu-id="b2233-138">See also</span></span>



[<span data-ttu-id="b2233-139">Elementos de Autodiscover XML SOAP para o Exchange 2013</span><span class="sxs-lookup"><span data-stu-id="b2233-139">SOAP Autodiscover XML elements for Exchange 2013</span></span>](soap-autodiscover-xml-elements-for-exchange-2013.md)

