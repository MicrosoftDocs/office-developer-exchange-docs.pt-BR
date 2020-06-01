---
title: UserSettingError (SOAP)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
localization_priority: Normal
api_type:
- schema
ms.assetid: abb175c5-4f38-4dcc-81e3-b511686862eb
description: O elemento UserSettingError representa um erro retornado como resultado de uma tentativa de obter uma configuração de usuário.
ms.openlocfilehash: 61603038ce93780f690d72226b1356b239d2002d
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44468604"
---
# <a name="usersettingerror-soap"></a><span data-ttu-id="1c017-103">UserSettingError (SOAP)</span><span class="sxs-lookup"><span data-stu-id="1c017-103">UserSettingError (SOAP)</span></span>

<span data-ttu-id="1c017-104">O elemento **UserSettingError** representa um erro retornado como resultado de uma tentativa de obter uma configuração de usuário.</span><span class="sxs-lookup"><span data-stu-id="1c017-104">The **UserSettingError** element represents an error that is returned as a result of an attempt to get a user setting.</span></span> 
  
```XML
<UserSettingError>
    <ErrorCode/>
    <ErrorMessage/>
    <SettingName/>
</UserSettingError>
```

 <span data-ttu-id="1c017-105">**UserSettingError**</span><span class="sxs-lookup"><span data-stu-id="1c017-105">**UserSettingError**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="1c017-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="1c017-106">Attributes and elements</span></span>

<span data-ttu-id="1c017-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="1c017-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="1c017-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="1c017-108">Attributes</span></span>

<span data-ttu-id="1c017-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="1c017-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="1c017-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="1c017-110">Child elements</span></span>

|<span data-ttu-id="1c017-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="1c017-111">**Element**</span></span>|<span data-ttu-id="1c017-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="1c017-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="1c017-113">ErrorCode (SOAP)</span><span class="sxs-lookup"><span data-stu-id="1c017-113">ErrorCode (SOAP)</span></span>](errorcode-soap.md) <br/> |<span data-ttu-id="1c017-114">Representa um código de erro retornado pelo serviço de descoberta automática.</span><span class="sxs-lookup"><span data-stu-id="1c017-114">Represents an error code that is returned by the Autodiscover service.</span></span>  <br/> |
|[<span data-ttu-id="1c017-115">ErrorMessage (SOAP)</span><span class="sxs-lookup"><span data-stu-id="1c017-115">ErrorMessage (SOAP)</span></span>](errormessage-soap.md) <br/> |<span data-ttu-id="1c017-116">Pasta uma mensagem associada a um código de erro retornado pelo serviço de descoberta automática.</span><span class="sxs-lookup"><span data-stu-id="1c017-116">Respresents a message associated with an error code that is returned by the Autodiscover service.</span></span>  <br/> |
|[<span data-ttu-id="1c017-117">SettingName (SOAP)</span><span class="sxs-lookup"><span data-stu-id="1c017-117">SettingName (SOAP)</span></span>](settingname-soap.md) <br/> |<span data-ttu-id="1c017-118">Representa o nome de uma configuração do usuário.</span><span class="sxs-lookup"><span data-stu-id="1c017-118">Represents the name of a user setting.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="1c017-119">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="1c017-119">Parent elements</span></span>

|<span data-ttu-id="1c017-120">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="1c017-120">**Element**</span></span>|<span data-ttu-id="1c017-121">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="1c017-121">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="1c017-122">UserSettingErrors (SOAP)</span><span class="sxs-lookup"><span data-stu-id="1c017-122">UserSettingErrors (SOAP)</span></span>](usersettingerrors-soap.md) <br/> |<span data-ttu-id="1c017-123">Representa uma coleção de informações sobre as configurações que não puderam ser retornadas.</span><span class="sxs-lookup"><span data-stu-id="1c017-123">Represents a collection of information about settings that could not be returned.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="1c017-124">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="1c017-124">Text value</span></span>

<span data-ttu-id="1c017-125">Nenhum</span><span class="sxs-lookup"><span data-stu-id="1c017-125">None.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="1c017-126">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="1c017-126">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="1c017-127">Namespace</span><span class="sxs-lookup"><span data-stu-id="1c017-127">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/2010/Autodiscover  <br/> |
|<span data-ttu-id="1c017-128">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="1c017-128">Schema Name</span></span>  <br/> |<span data-ttu-id="1c017-129">Esquema de descoberta automática</span><span class="sxs-lookup"><span data-stu-id="1c017-129">Autodiscover schema</span></span>  <br/> |
|<span data-ttu-id="1c017-130">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="1c017-130">Validation File</span></span>  <br/> |<span data-ttu-id="1c017-131">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="1c017-131">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="1c017-132">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="1c017-132">Can be Empty</span></span>  <br/> |<span data-ttu-id="1c017-133">Verdadeiro</span><span class="sxs-lookup"><span data-stu-id="1c017-133">True</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="1c017-134">Também consulte</span><span class="sxs-lookup"><span data-stu-id="1c017-134">See also</span></span>



[<span data-ttu-id="1c017-135">Elementos XML de descoberta automática SOAP para o Exchange 2013</span><span class="sxs-lookup"><span data-stu-id="1c017-135">SOAP Autodiscover XML elements for Exchange 2013</span></span>](soap-autodiscover-xml-elements-for-exchange-2013.md)

