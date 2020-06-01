---
title: Caixa de correio (disponibilidade)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- Mailbox
api_type:
- schema
ms.assetid: affd192e-8914-473f-9098-d9bdf898de2c
description: O elemento Mailbox representa o usuário de caixa de correio de uma solicitação SetUserOofSettings ou GetUserOofSettings.
ms.openlocfilehash: 1bda6e8b90551b86b4e1c2711ac25693a65e5410
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44458072"
---
# <a name="mailbox-availability"></a><span data-ttu-id="75bdc-103">Caixa de correio (disponibilidade)</span><span class="sxs-lookup"><span data-stu-id="75bdc-103">Mailbox (Availability)</span></span>

<span data-ttu-id="75bdc-104">O elemento **Mailbox** representa o usuário de caixa de correio de uma solicitação SetUserOofSettings ou GetUserOofSettings.</span><span class="sxs-lookup"><span data-stu-id="75bdc-104">The **Mailbox** element represents the mailbox user for a SetUserOofSettings or GetUserOofSettings request.</span></span> 
  
```xml
<Mailbox>
   <Name>...</Name>
   <Address>...</Address>
   <RoutingType>...</RoutingType>
</Mailbox>
```

<span data-ttu-id="75bdc-105">**EmailAddresstype**</span><span class="sxs-lookup"><span data-stu-id="75bdc-105">**EmailAddressType**</span></span>

## <a name="attributes-and-elements"></a><span data-ttu-id="75bdc-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="75bdc-106">Attributes and elements</span></span>

<span data-ttu-id="75bdc-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="75bdc-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="75bdc-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="75bdc-108">Attributes</span></span>

<span data-ttu-id="75bdc-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="75bdc-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="75bdc-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="75bdc-110">Child elements</span></span>

|<span data-ttu-id="75bdc-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="75bdc-111">**Element**</span></span>|<span data-ttu-id="75bdc-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="75bdc-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="75bdc-113">Nome (EmailAddress)</span><span class="sxs-lookup"><span data-stu-id="75bdc-113">Name (EmailAddress)</span></span>](name-emailaddress.md) <br/> |<span data-ttu-id="75bdc-114">Representa o nome de exibição do usuário da caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="75bdc-114">Represents the display name of the mailbox user.</span></span> <span data-ttu-id="75bdc-115">Este elemento é opcional no SetUserOofSettingsRequest.</span><span class="sxs-lookup"><span data-stu-id="75bdc-115">This element is optional in the SetUserOofSettingsRequest.</span></span> <span data-ttu-id="75bdc-116">O GetUserOofSettingsRequest retornará este elemento.</span><span class="sxs-lookup"><span data-stu-id="75bdc-116">The GetUserOofSettingsRequest will return this element.</span></span>  <br/> |
|[<span data-ttu-id="75bdc-117">Endereço (cadeia de caracteres)</span><span class="sxs-lookup"><span data-stu-id="75bdc-117">Address (string)</span></span>](address-string.md) <br/> |<span data-ttu-id="75bdc-118">Representa o endereço de email do usuário da caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="75bdc-118">Represents the e-mail address of the mailbox user.</span></span> <span data-ttu-id="75bdc-119">Este elemento é obrigatório.</span><span class="sxs-lookup"><span data-stu-id="75bdc-119">This element is required.</span></span>  <br/> |
|[<span data-ttu-id="75bdc-120">RoutingType (EmailAddress)</span><span class="sxs-lookup"><span data-stu-id="75bdc-120">RoutingType (EmailAddress)</span></span>](routingtype-emailaddress.md) <br/> |<span data-ttu-id="75bdc-121">Representa o protocolo de roteamento para a mensagem.</span><span class="sxs-lookup"><span data-stu-id="75bdc-121">Represents the routing protocol for the message.</span></span> <span data-ttu-id="75bdc-122">Este elemento é opcional no SetUserOofSettingsRequest.</span><span class="sxs-lookup"><span data-stu-id="75bdc-122">This element is optional in the SetUserOofSettingsRequest.</span></span> <span data-ttu-id="75bdc-123">O GetUserOofSettingsRequest retornará este elemento.</span><span class="sxs-lookup"><span data-stu-id="75bdc-123">The GetUserOofSettingsRequest will return this element.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="75bdc-124">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="75bdc-124">Parent elements</span></span>

|<span data-ttu-id="75bdc-125">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="75bdc-125">**Element**</span></span>|<span data-ttu-id="75bdc-126">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="75bdc-126">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="75bdc-127">GetUserOofSettingsRequest</span><span class="sxs-lookup"><span data-stu-id="75bdc-127">GetUserOofSettingsRequest</span></span>](getuseroofsettingsrequest.md) <br/> |<span data-ttu-id="75bdc-128">Usado para obter as configurações e mensagens de ausência temporária (OOF) de um usuário de caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="75bdc-128">Used to get a mailbox user's Out of Office (OOF) settings and messages.</span></span>  <br/> <span data-ttu-id="75bdc-129">A seguir está a expressão XPath para este elemento:</span><span class="sxs-lookup"><span data-stu-id="75bdc-129">The following is the XPath expression to this element:</span></span>  <br/>  `/GetUserOofSettingsRequest` <br/> |
|[<span data-ttu-id="75bdc-130">SetUserOofSettingsRequest</span><span class="sxs-lookup"><span data-stu-id="75bdc-130">SetUserOofSettingsRequest</span></span>](setuseroofsettingsrequest.md) <br/> |<span data-ttu-id="75bdc-131">Usado para definir as configurações e mensagens de ausência temporária de um usuário de caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="75bdc-131">Used to set a mailbox user's OOF settings and messages.</span></span>  <br/> <span data-ttu-id="75bdc-132">A seguir está a expressão XPath para este elemento:</span><span class="sxs-lookup"><span data-stu-id="75bdc-132">The following is the XPath expression to this element:</span></span>  <br/>  `/SetUserOofSettingsRequest` <br/> |
   
## <a name="remarks"></a><span data-ttu-id="75bdc-133">Comentários</span><span class="sxs-lookup"><span data-stu-id="75bdc-133">Remarks</span></span>

<span data-ttu-id="75bdc-134">O endereço de email é usado para identificar a pasta de calendário que contém as configurações de ausência temporária.</span><span class="sxs-lookup"><span data-stu-id="75bdc-134">The e-mail address is used to identify the calendar folder that contains the OOF settings.</span></span> 
  
<span data-ttu-id="75bdc-135">O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o MicrosoftExchange Server 2007 que tem instalada a função de servidor de Acesso para Cliente.</span><span class="sxs-lookup"><span data-stu-id="75bdc-135">The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="75bdc-136">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="75bdc-136">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="75bdc-137">Namespace</span><span class="sxs-lookup"><span data-stu-id="75bdc-137">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="75bdc-138">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="75bdc-138">Schema Name</span></span>  <br/> |<span data-ttu-id="75bdc-139">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="75bdc-139">Types schema</span></span>  <br/> |
|<span data-ttu-id="75bdc-140">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="75bdc-140">Validation File</span></span>  <br/> |<span data-ttu-id="75bdc-141">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="75bdc-141">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="75bdc-142">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="75bdc-142">Can be Empty</span></span>  <br/> |<span data-ttu-id="75bdc-143">False</span><span class="sxs-lookup"><span data-stu-id="75bdc-143">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="75bdc-144">Confira também</span><span class="sxs-lookup"><span data-stu-id="75bdc-144">See also</span></span>

- [<span data-ttu-id="75bdc-145">Operação GetUserOofSettings</span><span class="sxs-lookup"><span data-stu-id="75bdc-145">GetUserOofSettings operation</span></span>](getuseroofsettings-operation.md)
- [<span data-ttu-id="75bdc-146">Operação SetUserOofSettings</span><span class="sxs-lookup"><span data-stu-id="75bdc-146">SetUserOofSettings operation</span></span>](setuseroofsettings-operation.md)

