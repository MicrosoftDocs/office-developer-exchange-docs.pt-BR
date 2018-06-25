---
title: Operação de PlayOnPhone (EWS)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- PlayOnPhone
api_type:
- schema
ms.assetid: 70e6ef33-2046-4eb8-9987-e106009be04b
description: A operação PlayOnPhone inicia uma chamada de saída e reproduz uma mensagem por telefone.
ms.openlocfilehash: ec77720c69862e210316d61975b0d58c9530a40c
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/25/2018
ms.locfileid: "19824819"
---
# <a name="playonphone-operation-ews"></a><span data-ttu-id="8d468-103">Operação de PlayOnPhone (EWS)</span><span class="sxs-lookup"><span data-stu-id="8d468-103">PlayOnPhone operation (EWS)</span></span>

<span data-ttu-id="8d468-104">A operação **PlayOnPhone** inicia uma chamada de saída e reproduz uma mensagem por telefone.</span><span class="sxs-lookup"><span data-stu-id="8d468-104">The **PlayOnPhone** operation initiates an outbound call and plays a message over the telephone.</span></span> 
  
## <a name="playonphone-request-example"></a><span data-ttu-id="8d468-105">Exemplo de solicitação de PlayOnPhone</span><span class="sxs-lookup"><span data-stu-id="8d468-105">PlayOnPhone request example</span></span>

### <a name="description"></a><span data-ttu-id="8d468-106">Descrição</span><span class="sxs-lookup"><span data-stu-id="8d468-106">Description</span></span>

<span data-ttu-id="8d468-107">O exemplo a seguir de uma solicitação de **PlayOnPhone** mostra como uma solicitação para reproduzir uma mensagem em um telefone de formulário.</span><span class="sxs-lookup"><span data-stu-id="8d468-107">The following example of a **PlayOnPhone** request shows how to form a request to play a message on a phone.</span></span> 
  
### <a name="code"></a><span data-ttu-id="8d468-108">Código</span><span class="sxs-lookup"><span data-stu-id="8d468-108">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
               xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages"
               xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types"
               xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/"
               xmlns:xs="http://www.w3.org/2001/XMLSchema">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2010" />
  </soap:Header>
  <soap:Body>
    <m:PlayOnPhone>
      <m:ItemId Id="AkAjzQTbY/i="/>
      <m:DialString>5555551212</m:DialString>
    </m:PlayOnPhone>
  </soap:Body>
</soap:Envelope>
```

## <a name="playonphone-response-example"></a><span data-ttu-id="8d468-109">Exemplo de resposta PlayOnPhone</span><span class="sxs-lookup"><span data-stu-id="8d468-109">PlayOnPhone response example</span></span>

### <a name="description"></a><span data-ttu-id="8d468-110">Descrição</span><span class="sxs-lookup"><span data-stu-id="8d468-110">Description</span></span>

<span data-ttu-id="8d468-111">O exemplo a seguir mostra uma resposta bem-sucedida à solicitação **PlayOnPhone** .</span><span class="sxs-lookup"><span data-stu-id="8d468-111">The following example shows a successful response to the **PlayOnPhone** request.</span></span> 
  
### <a name="code"></a><span data-ttu-id="8d468-112">Código</span><span class="sxs-lookup"><span data-stu-id="8d468-112">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8"?>
<s:Envelope xmlns:s="http://schemas.xmlsoap.org/soap/envelope/">
  <s:Header>
    <h:ServerVersionInfo MajorVersion="14" 
                         MinorVersion="0" 
                         MajorBuildNumber="639" 
                         MinorBuildNumber="20" 
                         Version="Exchange2010" 
                         xmlns:h="http://schemas.microsoft.com/exchange/services/2006/types" 
                         xmlns="http://schemas.microsoft.com/exchange/services/2006/types" 
                         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
                         xmlns:xsd="http://www.w3.org/2001/XMLSchema"/>
  </s:Header>
  <s:Body xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
          xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <PlayOnPhoneResponse ResponseClass="Success" 
                         xmlns="http://schemas.microsoft.com/exchange/services/2006/messages">
      <ResponseCode>NoError</ResponseCode>
      <PhoneCallId Id="ZWMtWYtMY29t"/>
    </PlayOnPhoneResponse>
  </s:Body>
</s:Envelope>
```

## <a name="see-also"></a><span data-ttu-id="8d468-113">Confira também</span><span class="sxs-lookup"><span data-stu-id="8d468-113">See also</span></span>

- [<span data-ttu-id="8d468-114">Operações do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="8d468-114">EWS operations in Exchange</span></span>](ews-operations-in-exchange.md)
- [<span data-ttu-id="8d468-115">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="8d468-115">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

