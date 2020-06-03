---
title: MailTipsConfiguration (MailTipsServiceConfiguration)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- MailTipsConfiguration
api_type:
- schema
ms.assetid: 9a34515e-815b-4c61-b118-d5f66b80238f
description: O elemento MailTipsConfiguration contém informações de configuração de serviço para o serviço de dicas de email.
ms.openlocfilehash: 9128ee99545066899c3b27b624f10a9f1bd36c9d
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44467785"
---
# <a name="mailtipsconfiguration-mailtipsserviceconfiguration"></a><span data-ttu-id="cdb9e-103">MailTipsConfiguration (MailTipsServiceConfiguration)</span><span class="sxs-lookup"><span data-stu-id="cdb9e-103">MailTipsConfiguration (MailTipsServiceConfiguration)</span></span>

<span data-ttu-id="cdb9e-104">O elemento **MailTipsConfiguration** contém informações de configuração de serviço para o serviço de dicas de email.</span><span class="sxs-lookup"><span data-stu-id="cdb9e-104">The **MailTipsConfiguration** element contains service configuration information for the mail tips service.</span></span> 
  
```XML
<MailTipsConfiguration>
   <MailTipsEnabled/>
   <MaxRecipientsPerGetMailTipsRequest/>
   <MaxMessageSize/>
   <LargeAudienceThreshold/>
   <ShowExternalRecipientCount/>
   <InternalDomains/>
</MailTipsConfiguration>
```

 <span data-ttu-id="cdb9e-105">**MailTipsServiceConfiguration**</span><span class="sxs-lookup"><span data-stu-id="cdb9e-105">**MailTipsServiceConfiguration**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="cdb9e-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="cdb9e-106">Attributes and elements</span></span>

<span data-ttu-id="cdb9e-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="cdb9e-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="cdb9e-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="cdb9e-108">Attributes</span></span>

<span data-ttu-id="cdb9e-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="cdb9e-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="cdb9e-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="cdb9e-110">Child elements</span></span>

|<span data-ttu-id="cdb9e-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="cdb9e-111">**Element**</span></span>|<span data-ttu-id="cdb9e-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="cdb9e-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="cdb9e-113">MailTipsEnabled</span><span class="sxs-lookup"><span data-stu-id="cdb9e-113">MailTipsEnabled</span></span>](mailtipsenabled.md) <br/> |<span data-ttu-id="cdb9e-114">Indica se o serviço de dicas de email está disponível.</span><span class="sxs-lookup"><span data-stu-id="cdb9e-114">Indicates whether the mail tips service is available.</span></span> <span data-ttu-id="cdb9e-115">Este elemento é obrigatório.</span><span class="sxs-lookup"><span data-stu-id="cdb9e-115">This element is required.</span></span>  <br/> |
|[<span data-ttu-id="cdb9e-116">MaxRecipientsPerGetMailTipsRequest</span><span class="sxs-lookup"><span data-stu-id="cdb9e-116">MaxRecipientsPerGetMailTipsRequest</span></span>](maxrecipientspergetmailtipsrequest.md) <br/> |<span data-ttu-id="cdb9e-117">Indica o número máximo de destinatários que podem ser passados para a [operação](getmailtips-operation.md)GetQuery.</span><span class="sxs-lookup"><span data-stu-id="cdb9e-117">Indicates the maximum number of recipients that can be passed to the [GetMailTips operation](getmailtips-operation.md).</span></span> <span data-ttu-id="cdb9e-118">Este elemento é obrigatório.</span><span class="sxs-lookup"><span data-stu-id="cdb9e-118">This element is required.</span></span>  <br/> |
|[<span data-ttu-id="cdb9e-119">MaxMessageSize</span><span class="sxs-lookup"><span data-stu-id="cdb9e-119">MaxMessageSize</span></span>](maxmessagesize.md) <br/> |<span data-ttu-id="cdb9e-120">Representa o tamanho máximo de mensagem que um destinatário pode aceitar.</span><span class="sxs-lookup"><span data-stu-id="cdb9e-120">Represents the maximum message size a recipient can accept.</span></span> <span data-ttu-id="cdb9e-121">Este elemento é obrigatório.</span><span class="sxs-lookup"><span data-stu-id="cdb9e-121">This element is required.</span></span>  <br/> |
|[<span data-ttu-id="cdb9e-122">LargeAudienceThreshold</span><span class="sxs-lookup"><span data-stu-id="cdb9e-122">LargeAudienceThreshold</span></span>](largeaudiencethreshold.md) <br/> |<span data-ttu-id="cdb9e-123">Representa o limite de audiência grande para um cliente.</span><span class="sxs-lookup"><span data-stu-id="cdb9e-123">Represents the large audience threshold for a client.</span></span> <span data-ttu-id="cdb9e-124">Este elemento é obrigatório.</span><span class="sxs-lookup"><span data-stu-id="cdb9e-124">This element is required.</span></span>  <br/> |
|[<span data-ttu-id="cdb9e-125">ShowExternalRecipientCount</span><span class="sxs-lookup"><span data-stu-id="cdb9e-125">ShowExternalRecipientCount</span></span>](showexternalrecipientcount.md) <br/> |<span data-ttu-id="cdb9e-126">Indica se os consumidores da [operação](getmailtips-operation.md) GetQuery devem mostrar dicas de email que indicam o número de destinatários externos para os quais uma mensagem é endereçada.</span><span class="sxs-lookup"><span data-stu-id="cdb9e-126">Indicates whether consumers of the [GetMailTips operation](getmailtips-operation.md) have to show mail tips that indicate the number of external recipients to which a message is addressed.</span></span> <span data-ttu-id="cdb9e-127">Este elemento é obrigatório.</span><span class="sxs-lookup"><span data-stu-id="cdb9e-127">This element is required.</span></span>  <br/> |
|[<span data-ttu-id="cdb9e-128">InternalDomains (SmtpDomainList)</span><span class="sxs-lookup"><span data-stu-id="cdb9e-128">InternalDomains (SmtpDomainList)</span></span>](internaldomains-smtpdomainlist.md) <br/> |<span data-ttu-id="cdb9e-129">Identifica a lista de domínios SMTP internos da organização.</span><span class="sxs-lookup"><span data-stu-id="cdb9e-129">Identifies the list of internal SMTP domains of the organization.</span></span> <span data-ttu-id="cdb9e-130">Este elemento é obrigatório.</span><span class="sxs-lookup"><span data-stu-id="cdb9e-130">This element is required.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="cdb9e-131">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="cdb9e-131">Parent elements</span></span>

|<span data-ttu-id="cdb9e-132">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="cdb9e-132">**Element**</span></span>|<span data-ttu-id="cdb9e-133">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="cdb9e-133">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="cdb9e-134">ServiceConfigurationResponseMessageType</span><span class="sxs-lookup"><span data-stu-id="cdb9e-134">ServiceConfigurationResponseMessageType</span></span>](serviceconfigurationresponsemessagetype.md) <br/> |<span data-ttu-id="cdb9e-135">Contém definições de configuração de serviço.</span><span class="sxs-lookup"><span data-stu-id="cdb9e-135">Contains service configuration settings.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="cdb9e-136">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="cdb9e-136">Text value</span></span>

<span data-ttu-id="cdb9e-137">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="cdb9e-137">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="cdb9e-138">Comentários</span><span class="sxs-lookup"><span data-stu-id="cdb9e-138">Remarks</span></span>

<span data-ttu-id="cdb9e-139">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="cdb9e-139">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="cdb9e-140">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="cdb9e-140">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="cdb9e-141">Namespace</span><span class="sxs-lookup"><span data-stu-id="cdb9e-141">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|<span data-ttu-id="cdb9e-142">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="cdb9e-142">Schema Name</span></span>  <br/> |<span data-ttu-id="cdb9e-143">Esquema de mensagens</span><span class="sxs-lookup"><span data-stu-id="cdb9e-143">Messages schema</span></span>  <br/> |
|<span data-ttu-id="cdb9e-144">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="cdb9e-144">Validation File</span></span>  <br/> |<span data-ttu-id="cdb9e-145">Messages.xsd</span><span class="sxs-lookup"><span data-stu-id="cdb9e-145">Messages.xsd</span></span>  <br/> |
|<span data-ttu-id="cdb9e-146">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="cdb9e-146">Can be Empty</span></span>  <br/> |<span data-ttu-id="cdb9e-147">False</span><span class="sxs-lookup"><span data-stu-id="cdb9e-147">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="cdb9e-148">Confira também</span><span class="sxs-lookup"><span data-stu-id="cdb9e-148">See also</span></span>



- [<span data-ttu-id="cdb9e-149">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="cdb9e-149">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

