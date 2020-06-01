---
title: Caixa de correio (SOAP)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
localization_priority: Normal
api_type:
- schema
ms.assetid: 4ad59e5b-4047-4c34-a318-ca06c31d3de8
description: O elemento Mailbox contém o endereço de email do usuário a ser descoberto.
ms.openlocfilehash: e050cd9d3ca4a2d2450f315f1eedd3862328d096
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44467281"
---
# <a name="mailbox-soap"></a><span data-ttu-id="0c15d-103">Caixa de correio (SOAP)</span><span class="sxs-lookup"><span data-stu-id="0c15d-103">Mailbox (SOAP)</span></span>

<span data-ttu-id="0c15d-104">O elemento **Mailbox** contém o endereço de email do usuário a ser descoberto.</span><span class="sxs-lookup"><span data-stu-id="0c15d-104">The **Mailbox** element contains the e-mail address of the user to be discovered.</span></span> 
  
```XML
<Mailbox/>
```

<span data-ttu-id="0c15d-105">**cadeia de caracteres**</span><span class="sxs-lookup"><span data-stu-id="0c15d-105">**string**</span></span>

## <a name="attributes-and-elements"></a><span data-ttu-id="0c15d-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="0c15d-106">Attributes and elements</span></span>

<span data-ttu-id="0c15d-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="0c15d-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="0c15d-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="0c15d-108">Attributes</span></span>

<span data-ttu-id="0c15d-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="0c15d-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="0c15d-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="0c15d-110">Child elements</span></span>

<span data-ttu-id="0c15d-111">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="0c15d-111">None.</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="0c15d-112">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="0c15d-112">Parent elements</span></span>

|<span data-ttu-id="0c15d-113">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="0c15d-113">**Element**</span></span>|<span data-ttu-id="0c15d-114">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="0c15d-114">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="0c15d-115">Usuário (SOAP)</span><span class="sxs-lookup"><span data-stu-id="0c15d-115">User (SOAP)</span></span>](user-soap.md) <br/> |<span data-ttu-id="0c15d-116">Representa a identidade de um único usuário.</span><span class="sxs-lookup"><span data-stu-id="0c15d-116">Represents the identity of a single user.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="0c15d-117">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="0c15d-117">Text value</span></span>

<span data-ttu-id="0c15d-118">O valor de texto do elemento **Mailbox** é o endereço de email do usuário a ser descoberto.</span><span class="sxs-lookup"><span data-stu-id="0c15d-118">The text value of the **Mailbox** element is the e-mail address of the user to be discovered.</span></span> 
  
## <a name="element-information"></a><span data-ttu-id="0c15d-119">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="0c15d-119">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="0c15d-120">Namespace</span><span class="sxs-lookup"><span data-stu-id="0c15d-120">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/2010/Autodiscover  <br/> |
|<span data-ttu-id="0c15d-121">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="0c15d-121">Schema Name</span></span>  <br/> |<span data-ttu-id="0c15d-122">Esquema de descoberta automática</span><span class="sxs-lookup"><span data-stu-id="0c15d-122">Autodiscover schema</span></span>  <br/> |
|<span data-ttu-id="0c15d-123">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="0c15d-123">Validation File</span></span>  <br/> |<span data-ttu-id="0c15d-124">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="0c15d-124">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="0c15d-125">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="0c15d-125">Can be Empty</span></span>  <br/> |<span data-ttu-id="0c15d-126">Verdadeiro</span><span class="sxs-lookup"><span data-stu-id="0c15d-126">True</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="0c15d-127">Também consulte</span><span class="sxs-lookup"><span data-stu-id="0c15d-127">See also</span></span>

- [<span data-ttu-id="0c15d-128">Operação GetUserSettings (SOAP)</span><span class="sxs-lookup"><span data-stu-id="0c15d-128">GetUserSettings operation (SOAP)</span></span>](getusersettings-operation-soap.md)

