---
title: Operação de PlayOnPhoneGreeting (serviço web de Unificação de mensagens)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
localization_priority: Normal
api_name:
- PlayOnPhoneGreeting
api_type:
- schema
ms.assetid: 6deafc40-290b-4bce-9914-b6bcc529f38a
description: A operação PlayOnPhoneGreeting faz uma chamada de saída e reproduz uma das mensagens de dois saudação pelo telefone.
ms.openlocfilehash: 85ba76c7638911678c1ef1aef88f47fdab2c6a4e
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19824828"
---
# <a name="playonphonegreeting-operation-um-web-service"></a><span data-ttu-id="2fa4a-103">Operação de PlayOnPhoneGreeting (serviço web de Unificação de mensagens)</span><span class="sxs-lookup"><span data-stu-id="2fa4a-103">PlayOnPhoneGreeting operation (UM web service)</span></span>

<span data-ttu-id="2fa4a-104">A operação PlayOnPhoneGreeting faz uma chamada de saída e reproduz uma das mensagens de dois saudação pelo telefone.</span><span class="sxs-lookup"><span data-stu-id="2fa4a-104">The PlayOnPhoneGreeting operation makes an outbound call and plays one of the two greeting messages on the telephone.</span></span>
  
## <a name="playonphonegreeting-request-example"></a><span data-ttu-id="2fa4a-105">Exemplo de solicitação de PlayOnPhoneGreeting</span><span class="sxs-lookup"><span data-stu-id="2fa4a-105">PlayOnPhoneGreeting request example</span></span>

### <a name="description"></a><span data-ttu-id="2fa4a-106">Descrição</span><span class="sxs-lookup"><span data-stu-id="2fa4a-106">Description</span></span>

<span data-ttu-id="2fa4a-107">O exemplo a seguir de uma solicitação de PlayOnPhoneGreeting mostra como uma solicitação para fazer uma chamada realizada e reproduzir a mensagem de saudação normal em um telefone de formulário.</span><span class="sxs-lookup"><span data-stu-id="2fa4a-107">The following example of a PlayOnPhoneGreeting request shows how to form a request to make an outbound call and play the normal greeting message on a telephone.</span></span>
  
### <a name="code"></a><span data-ttu-id="2fa4a-108">Código</span><span class="sxs-lookup"><span data-stu-id="2fa4a-108">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Body>
    <PlayOnPhoneGreeting xmlns="http://schemas.microsoft.com/exchange/services/2006/messages">
      <GreetingType>NormalCustom</GreetingType>
      <DialString>12345</DialString>
    </PlayOnPhoneGreeting>
  </soap:Body>
</soap:Envelope>
```

## <a name="successful-playonphonegreeting-response-example"></a><span data-ttu-id="2fa4a-109">Exemplo de resposta bem-sucedida PlayOnPhoneGreeting</span><span class="sxs-lookup"><span data-stu-id="2fa4a-109">Successful PlayOnPhoneGreeting response example</span></span>

### <a name="description"></a><span data-ttu-id="2fa4a-110">Descrição</span><span class="sxs-lookup"><span data-stu-id="2fa4a-110">Description</span></span>

<span data-ttu-id="2fa4a-111">O exemplo a seguir de uma resposta PlayOnPhoneGreeting mostra uma resposta à solicitação de PlayOnPhoneGreeting.</span><span class="sxs-lookup"><span data-stu-id="2fa4a-111">The following example of a PlayOnPhoneGreeting response shows a response to the PlayOnPhoneGreeting request.</span></span>
  
### <a name="code"></a><span data-ttu-id="2fa4a-112">Código</span><span class="sxs-lookup"><span data-stu-id="2fa4a-112">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8" ?> 
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
  <soap:Body>
    <PlayOnPhoneGreetingResponse xmlns="http://schemas.microsoft.com/exchange/services/2006/messages">
    <PlayOnPhoneGreetingResponse>MjA4MTQ5MmItMTBmZC00ZGFmLThiMzEtNDllNDJjM2Y3MjIxQGRmLWV1bS0wMS5leGNoYW5nZS5jb3JwLm1pY3Jvc29mdC5jb20=</PlayOnPhoneGreetingResponse> 
    </PlayOnPhoneGreetingResponse>
  </soap:Body>
</soap:Envelope>
```

## <a name="see-also"></a><span data-ttu-id="2fa4a-113">Confira também</span><span class="sxs-lookup"><span data-stu-id="2fa4a-113">See also</span></span>



[<span data-ttu-id="2fa4a-114">PlayOnPhoneGreeting (serviço web de Unificação de mensagens)</span><span class="sxs-lookup"><span data-stu-id="2fa4a-114">PlayOnPhoneGreeting (UM web service)</span></span>](playonphonegreeting-um-web-service.md)
  
[<span data-ttu-id="2fa4a-115">PlayOnPhoneGreetingResponse (serviço web de Unificação de mensagens)</span><span class="sxs-lookup"><span data-stu-id="2fa4a-115">PlayOnPhoneGreetingResponse (UM web service)</span></span>](playonphonegreetingresponse-um-web-service.md)
  
[<span data-ttu-id="2fa4a-116">GreetingType (serviço web de Unificação de mensagens)</span><span class="sxs-lookup"><span data-stu-id="2fa4a-116">GreetingType (UM web service)</span></span>](greetingtype-um-web-service.md)
  
[<span data-ttu-id="2fa4a-117">dialString (serviço web de Unificação de mensagens)</span><span class="sxs-lookup"><span data-stu-id="2fa4a-117">dialString (UM web service)</span></span>](dialstring-um-web-service.md)

