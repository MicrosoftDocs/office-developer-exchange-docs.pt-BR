---
title: Operação GetPhoneCallInformation
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- GetPhoneCallInformation
api_type:
- schema
ms.assetid: 418bd6ca-39d9-49a9-841e-7a71ede1fa51
description: A operação GetPhoneCallInformation retorna informações sobre a chamada de telefone especificada.
ms.openlocfilehash: 8f98ca5dd304eadffc307fa47620b7db6401c782
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19752604"
---
# <a name="getphonecallinformation-operation"></a><span data-ttu-id="ec0fb-103">Operação GetPhoneCallInformation</span><span class="sxs-lookup"><span data-stu-id="ec0fb-103">GetPhoneCallInformation operation</span></span>

<span data-ttu-id="ec0fb-104">A operação **GetPhoneCallInformation** retorna informações sobre a chamada de telefone especificada.</span><span class="sxs-lookup"><span data-stu-id="ec0fb-104">The **GetPhoneCallInformation** operation returns information about the specified telephone call.</span></span> 
  
## <a name="getphonecallinformation-request-example"></a><span data-ttu-id="ec0fb-105">Exemplo de solicitação de GetPhoneCallInformation</span><span class="sxs-lookup"><span data-stu-id="ec0fb-105">GetPhoneCallInformation request example</span></span>

### <a name="description"></a><span data-ttu-id="ec0fb-106">Descrição</span><span class="sxs-lookup"><span data-stu-id="ec0fb-106">Description</span></span>

<span data-ttu-id="ec0fb-107">O exemplo a seguir de uma solicitação de **GetPhoneCallInformation** mostra como uma solicitação para obter mais informações sobre uma chamada telefônica específica de formulário.</span><span class="sxs-lookup"><span data-stu-id="ec0fb-107">The following example of a **GetPhoneCallInformation** request shows how to form a request to get information about a specific telephone call.</span></span> 
  
### <a name="code"></a><span data-ttu-id="ec0fb-108">Código</span><span class="sxs-lookup"><span data-stu-id="ec0fb-108">Code</span></span>

```xml
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
    <m:GetPhoneCallInformation>
      <m:PhoneCallId Id="NDDY5uY29y9t"/>
    </m:GetPhoneCallInformation>
  </soap:Body>
</soap:Envelope>
```

## <a name="getphonecallinformation-response-example"></a><span data-ttu-id="ec0fb-109">Exemplo de resposta GetPhoneCallInformation</span><span class="sxs-lookup"><span data-stu-id="ec0fb-109">GetPhoneCallInformation response example</span></span>

### <a name="description"></a><span data-ttu-id="ec0fb-110">Descrição</span><span class="sxs-lookup"><span data-stu-id="ec0fb-110">Description</span></span>

<span data-ttu-id="ec0fb-111">O exemplo a seguir mostra uma resposta bem-sucedida à solicitação **GetPhoneCallInformation** .</span><span class="sxs-lookup"><span data-stu-id="ec0fb-111">The following example shows a successful response to the **GetPhoneCallInformation** request.</span></span> <span data-ttu-id="ec0fb-112">A resposta representa uma chamada telefônica que está conectada.</span><span class="sxs-lookup"><span data-stu-id="ec0fb-112">The response represents a telephone call that is currently connected.</span></span> 
  
### <a name="code"></a><span data-ttu-id="ec0fb-113">Código</span><span class="sxs-lookup"><span data-stu-id="ec0fb-113">Code</span></span>

```xml
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
    <GetPhoneCallInformationResponse ResponseClass="Success" 
                                     xmlns="http://schemas.microsoft.com/exchange/services/2006/messages">
      <ResponseCode>NoError</ResponseCode>
      <m:PhoneCallInformation xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages">
        <t:PhoneCallState xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">Connected</t:PhoneCallState>
        <t:ConnectionFailureCause xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">None</t:ConnectionFailureCause>
      </m:PhoneCallInformation>
    </GetPhoneCallInformationResponse>
  </s:Body>
</s:Envelope>
```

## <a name="see-also"></a><span data-ttu-id="ec0fb-114">Confira também</span><span class="sxs-lookup"><span data-stu-id="ec0fb-114">See also</span></span>

- [<span data-ttu-id="ec0fb-115">Operações do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="ec0fb-115">EWS operations in Exchange</span></span>](ews-operations-in-exchange.md)
- [<span data-ttu-id="ec0fb-116">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="ec0fb-116">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

