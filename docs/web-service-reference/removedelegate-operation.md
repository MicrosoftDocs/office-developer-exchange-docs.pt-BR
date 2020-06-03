---
title: Operação RemoveDelegate
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- RemoveDelegate
api_type:
- schema
ms.assetid: 1d42d5ff-8fde-4f8a-b18d-57b1ef7a946a
description: A operação RemoveDelegate remove um ou mais representantes da caixa de correio de um usuário.
ms.openlocfilehash: b2e342225e7e79c44dcd86b76b4b7d47b16b860b
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44466595"
---
# <a name="removedelegate-operation"></a><span data-ttu-id="2c714-103">Operação RemoveDelegate</span><span class="sxs-lookup"><span data-stu-id="2c714-103">RemoveDelegate operation</span></span>

<span data-ttu-id="2c714-104">A operação **RemoveDelegate** remove um ou mais representantes da caixa de correio de um usuário.</span><span class="sxs-lookup"><span data-stu-id="2c714-104">The **RemoveDelegate** operation removes one or more delegates from a user's mailbox.</span></span> 
  
## <a name="soap-headers"></a><span data-ttu-id="2c714-105">Cabeçalhos SOAP</span><span class="sxs-lookup"><span data-stu-id="2c714-105">SOAP Headers</span></span>

<span data-ttu-id="2c714-106">A operação **RemoveDelegate** pode usar os cabeçalhos SOAP listados e descritos na tabela a seguir.</span><span class="sxs-lookup"><span data-stu-id="2c714-106">The **RemoveDelegate** operation can use the SOAP headers that are listed and described in the following table.</span></span> 
  
|<span data-ttu-id="2c714-107">**Header**</span><span class="sxs-lookup"><span data-stu-id="2c714-107">**Header**</span></span>|<span data-ttu-id="2c714-108">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="2c714-108">**Element**</span></span>|<span data-ttu-id="2c714-109">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="2c714-109">**Description**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="2c714-110">Representação</span><span class="sxs-lookup"><span data-stu-id="2c714-110">Impersonation</span></span>  <br/> |[<span data-ttu-id="2c714-111">ExchangeImpersonation</span><span class="sxs-lookup"><span data-stu-id="2c714-111">ExchangeImpersonation</span></span>](exchangeimpersonation.md) <br/> |<span data-ttu-id="2c714-112">Identifica o usuário que o aplicativo cliente está representando.</span><span class="sxs-lookup"><span data-stu-id="2c714-112">Identifies the user whom the client application is impersonating.</span></span>  <br/> |
|<span data-ttu-id="2c714-113">MailboxCulture</span><span class="sxs-lookup"><span data-stu-id="2c714-113">MailboxCulture</span></span>  <br/> |[<span data-ttu-id="2c714-114">MailboxCulture</span><span class="sxs-lookup"><span data-stu-id="2c714-114">MailboxCulture</span></span>](mailboxculture.md) <br/> |<span data-ttu-id="2c714-115">Identifica a cultura RFC3066 a ser usada para acessar a caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="2c714-115">Identifies the RFC3066 culture to be used to access the mailbox.</span></span>  <br/> |
|<span data-ttu-id="2c714-116">RequestVersion</span><span class="sxs-lookup"><span data-stu-id="2c714-116">RequestVersion</span></span>  <br/> |[<span data-ttu-id="2c714-117">RequestServerVersion</span><span class="sxs-lookup"><span data-stu-id="2c714-117">RequestServerVersion</span></span>](requestserverversion.md) <br/> |<span data-ttu-id="2c714-118">Identifica a versão do esquema para a solicitação de operação.</span><span class="sxs-lookup"><span data-stu-id="2c714-118">Identifies the schema version for the operation request.</span></span>  <br/> |
|<span data-ttu-id="2c714-119">ServerVersion</span><span class="sxs-lookup"><span data-stu-id="2c714-119">ServerVersion</span></span>  <br/> |[<span data-ttu-id="2c714-120">ServerVersionInfo</span><span class="sxs-lookup"><span data-stu-id="2c714-120">ServerVersionInfo</span></span>](serverversioninfo.md) <br/> |<span data-ttu-id="2c714-121">Identifica a versão do servidor que respondeu à solicitação.</span><span class="sxs-lookup"><span data-stu-id="2c714-121">Identifies the version of the server that responded to the request.</span></span>  <br/> |
   
## <a name="removedelegate-request-example"></a><span data-ttu-id="2c714-122">Exemplo de solicitação RemoveDelegate</span><span class="sxs-lookup"><span data-stu-id="2c714-122">RemoveDelegate request example</span></span>

### <a name="description"></a><span data-ttu-id="2c714-123">Descrição</span><span class="sxs-lookup"><span data-stu-id="2c714-123">Description</span></span>

<span data-ttu-id="2c714-124">O exemplo de código a seguir mostra como remover dois representantes da caixa de correio do user1's.</span><span class="sxs-lookup"><span data-stu-id="2c714-124">The following code example shows how to remove two delegates from user1's mailbox.</span></span> <span data-ttu-id="2c714-125">Neste exemplo, um representante é removido usando o endereço SMTP principal do representante e o outro é removido usando o identificador de segurança (SID) do representante.</span><span class="sxs-lookup"><span data-stu-id="2c714-125">In this example, one delegate is removed by using the delegate's primary SMTP address, and the other one is removed by using the delegate's security identifier (SID).</span></span>
  
### <a name="code"></a><span data-ttu-id="2c714-126">Código</span><span class="sxs-lookup"><span data-stu-id="2c714-126">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/"
               xmlns:t="https://schemas.microsoft.com/exchange/services/2006/types">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2007_SP1"/>
  </soap:Header>
  <soap:Body>
    <RemoveDelegate xmlns="https://schemas.microsoft.com/exchange/services/2006/messages"
                    xmlns:t="https://schemas.microsoft.com/exchange/services/2006/types">
      <Mailbox>
        <t:EmailAddress>user1@example.com</t:EmailAddress>
      </Mailbox>
      <UserIds>
        <t:UserId>
          <t:PrimarySmtpAddress>user2@example.com</t:PrimarySmtpAddress>
        </t:UserId>
        <t:UserId>
          <t:SID>S-1-5-21-1333220396-2200287332-232816053-1118</t:SID>
        </t:UserId>
      </UserIds>
    </RemoveDelegate>
  </soap:Body>
</soap:Envelope>
```

### <a name="comments"></a><span data-ttu-id="2c714-127">Comentários</span><span class="sxs-lookup"><span data-stu-id="2c714-127">Comments</span></span>

<span data-ttu-id="2c714-128">A operação **RemoveDelegate** não exige que o usuário delegado especificado tenha uma caixa de correio ou exista no serviço de diretório do Active Directory.</span><span class="sxs-lookup"><span data-stu-id="2c714-128">The **RemoveDelegate** operation does not require the specified delegate user to have a mailbox or to exist in the Active Directory directory service.</span></span> <span data-ttu-id="2c714-129">A operação **RemoveDelegate** será bem-sucedida se a entrada de representante estiver órfão.</span><span class="sxs-lookup"><span data-stu-id="2c714-129">The **RemoveDelegate** operation will succeed if the delegate entry is orphaned.</span></span> 
  
## <a name="removedelegate-response-example"></a><span data-ttu-id="2c714-130">Exemplo de resposta RemoveDelegate</span><span class="sxs-lookup"><span data-stu-id="2c714-130">RemoveDelegate response example</span></span>

### <a name="description"></a><span data-ttu-id="2c714-131">Descrição</span><span class="sxs-lookup"><span data-stu-id="2c714-131">Description</span></span>

<span data-ttu-id="2c714-132">O exemplo a seguir de uma resposta **RemoveDelegate** mostra uma resposta bem-sucedida a uma solicitação **RemoveDelegate** .</span><span class="sxs-lookup"><span data-stu-id="2c714-132">The following example of a **RemoveDelegate** response shows a successful response to a **RemoveDelegate** request.</span></span> <span data-ttu-id="2c714-133">A resposta contém um elemento **DelegateUserResponseMessageType** para cada representante removido da caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="2c714-133">The response contains a **DelegateUserResponseMessageType** element for each delegate that is removed from the mailbox.</span></span> 
  
### <a name="code"></a><span data-ttu-id="2c714-134">Código</span><span class="sxs-lookup"><span data-stu-id="2c714-134">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/" 
               xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
               xmlns:xsd="http://www.w3.org/2001/XMLSchema">
  <soap:Header>
    <t:ServerVersionInfo MajorVersion="8" 
                         MinorVersion="1" 
                         MajorBuildNumber="206" 
                         MinorBuildNumber="0" 
                         Version="Exchange2007_SP1" 
                         xmlns:t="https://schemas.microsoft.com/exchange/services/2006/types" />
  </soap:Header>
  <soap:Body>
    <m:RemoveDelegateResponse xmlns:t="https://schemas.microsoft.com/exchange/services/2006/types" 
                              ResponseClass="Success" 
                              xmlns:m="https://schemas.microsoft.com/exchange/services/2006/messages">
      <m:ResponseCode>NoError</m:ResponseCode>
      <m:ResponseMessages>
        <m:DelegateUserResponseMessageType ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
        </m:DelegateUserResponseMessageType>
        <m:DelegateUserResponseMessageType ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
        </m:DelegateUserResponseMessageType>
      </m:ResponseMessages>
      </m:RemoveDelegateResponse>
  </soap:Body>
</soap:Envelope>
```

## <a name="removedelegate-error-response-example"></a><span data-ttu-id="2c714-135">Exemplo de resposta de erro RemoveDelegate</span><span class="sxs-lookup"><span data-stu-id="2c714-135">RemoveDelegate Error response example</span></span>

### <a name="description"></a><span data-ttu-id="2c714-136">Descrição</span><span class="sxs-lookup"><span data-stu-id="2c714-136">Description</span></span>

<span data-ttu-id="2c714-137">O exemplo a seguir de uma resposta de erro do **RemoveDelegate** mostra os resultados de uma solicitação para remover um representante que não existe.</span><span class="sxs-lookup"><span data-stu-id="2c714-137">The following example of a **RemoveDelegate** error response shows the results of a request to remove a delegate that does not exist.</span></span> 
  
### <a name="code"></a><span data-ttu-id="2c714-138">Código</span><span class="sxs-lookup"><span data-stu-id="2c714-138">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/"
               xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
               xmlns:xsd="http://www.w3.org/2001/XMLSchema">
  <soap:Header>
    <t:ServerVersionInfo MajorVersion="8"
                         MinorVersion="1"
                         MajorBuildNumber="206"
                         MinorBuildNumber="0"
                         Version="Exchange2007_SP1"
                         xmlns:t="https://schemas.microsoft.com/exchange/services/2006/types" />
  </soap:Header>
  <soap:Body>
    <m:RemoveDelegateResponse xmlns:t="https://schemas.microsoft.com/exchange/services/2006/types"
                              ResponseClass="Success"
                              xmlns:m="https://schemas.microsoft.com/exchange/services/2006/messages">
      <m:ResponseCode>NoError</m:ResponseCode>
      <m:ResponseMessages>
        <m:DelegateUserResponseMessageType ResponseClass="Error">
          <m:MessageText>The user is not a delegate for the mailbox.</m:MessageText>
          <m:ResponseCode>ErrorNotDelegate</m:ResponseCode>
          <m:DescriptiveLinkKey>0</m:DescriptiveLinkKey>
        </m:DelegateUserResponseMessageType>
      </m:ResponseMessages>
    </m:RemoveDelegateResponse>
  </soap:Body>
</soap:Envelope>
```

## <a name="see-also"></a><span data-ttu-id="2c714-139">Confira também</span><span class="sxs-lookup"><span data-stu-id="2c714-139">See also</span></span>



- [<span data-ttu-id="2c714-140">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="2c714-140">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

