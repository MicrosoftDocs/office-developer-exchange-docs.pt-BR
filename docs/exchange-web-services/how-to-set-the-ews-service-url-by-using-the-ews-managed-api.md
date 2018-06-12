---
title: Definir a URL de serviço do EWS usando a API gerenciada de EWS
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
localization_priority: Normal
ms.assetid: cddf6525-1c04-484b-a911-56c2f0f1f7b6
description: Encontre informações sobre como definir a URL do serviço EWS no seu aplicativo do EWS Managed API.
ms.openlocfilehash: e1a414f7c6f13bd61a58403c9d2be546c0226a69
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19750819"
---
# <a name="set-the-ews-service-url-by-using-the-ews-managed-api"></a><span data-ttu-id="71a9a-103">Definir a URL de serviço do EWS usando a API gerenciada de EWS</span><span class="sxs-lookup"><span data-stu-id="71a9a-103">Set the EWS service URL by using the EWS Managed API</span></span>

<span data-ttu-id="71a9a-104">Encontre informações sobre como definir a URL do serviço EWS no seu aplicativo do EWS Managed API.</span><span class="sxs-lookup"><span data-stu-id="71a9a-104">Find information about how to set the EWS service URL in your EWS Managed API application.</span></span>
  
<span data-ttu-id="71a9a-105">A URL do serviço é o endereço que o Exchange usa para se comunicar com o Exchange Web Services (EWS).</span><span class="sxs-lookup"><span data-stu-id="71a9a-105">The service URL is the address that Exchange uses to communicate with Exchange Web Services (EWS).</span></span> <span data-ttu-id="71a9a-106">Depois que seu aplicativo EWS Managed API tem esse endereço e tem o acesso apropriado para [se comunicar com o EWS](how-to-communicate-with-ews-by-using-the-ews-managed-api.md), ele pode fazer chamadas para a [classe ExchangeService](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.exchangeservice%28v=exchg.80%29.aspx).</span><span class="sxs-lookup"><span data-stu-id="71a9a-106">After your EWS Managed API application has this address, and has appropriate access to [communicate with EWS](how-to-communicate-with-ews-by-using-the-ews-managed-api.md), it can make calls to the [ExchangeService class](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.exchangeservice%28v=exchg.80%29.aspx).</span></span> <span data-ttu-id="71a9a-107">A URL do serviço para um servidor do Exchange local pode parecer com o seguinte.</span><span class="sxs-lookup"><span data-stu-id="71a9a-107">The service URL for an on-premises Exchange server might look like the following.</span></span> 
  
```HTML
https://computer.domain.contoso.com/EWS/Exchange.asmx
```

<span data-ttu-id="71a9a-108">Você pode definir a URL do EWS em seu aplicativo em algumas maneiras.</span><span class="sxs-lookup"><span data-stu-id="71a9a-108">You can set the EWS URL in your application in a couple of ways.</span></span> <span data-ttu-id="71a9a-109">É recomendável que você usar o [serviço de descoberta automática](http://msdn.microsoft.com/library/39726b67-2eb2-451b-9307-cfd0b518b55c%28Office.15%29.aspx) para obter a URL, como em uma floresta grande de servidores, a URL pode ser alterado se a caixa de correio for transferida para outro servidor.</span><span class="sxs-lookup"><span data-stu-id="71a9a-109">We recommend that you use the [Autodiscover service](http://msdn.microsoft.com/library/39726b67-2eb2-451b-9307-cfd0b518b55c%28Office.15%29.aspx) to get the URL because in a large forest of servers, the URL can change if the mailbox is migrated to another server.</span></span> <span data-ttu-id="71a9a-110">No entanto, como chamar a descoberta automática pode levar algum tempo e pode diminuir seu aplicativo se você precisar fazer várias chamadas em um curto período de tempo, talvez você queira cache o valor URL você fazer a partir de descoberta automática e definir manualmente a URL do serviço do EWS com esse cache va Lue.</span><span class="sxs-lookup"><span data-stu-id="71a9a-110">However, because calling Autodiscover can take some time and can slow down your application if you need to make multiple calls in a short period of time, you might want to cache the URL value you get from Autodiscover and manually set the EWS service URL with this cached value.</span></span> <span data-ttu-id="71a9a-111">Isso irá melhorar o desempenho do seu aplicativo; apenas certifique-se de que você usar descoberta automática para atualizar seu valor em cache periodicamente caso o valor é alterado no servidor.</span><span class="sxs-lookup"><span data-stu-id="71a9a-111">This will improve the performance of your application; just make sure that you use Autodiscover to update your cached value periodically in case the value changes on the server.</span></span> 
  
## <a name="set-the-ews-service-url-by-using-the-autodiscover-service"></a><span data-ttu-id="71a9a-112">Definir a URL de serviço do EWS usando o serviço de descoberta automática</span><span class="sxs-lookup"><span data-stu-id="71a9a-112">Set the EWS service URL by using the Autodiscover service</span></span>
<span data-ttu-id="71a9a-113"><a name="bk_SetURLusingAutoDiscover"> </a></span><span class="sxs-lookup"><span data-stu-id="71a9a-113"></span></span>

<span data-ttu-id="71a9a-114">O método [AutodiscoverUrl](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.exchangeservice.autodiscoverurl%28v=exchg.80%29.aspx) usa o endereço de email para definir o ponto de extremidade [ExchangeService](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.exchangeservice%28v=exchg.80%29.aspx) e habilita o seu aplicativo para usar quaisquer métodos incluídos nas classes proxy **ExchangeService** .</span><span class="sxs-lookup"><span data-stu-id="71a9a-114">The [AutodiscoverUrl](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.exchangeservice.autodiscoverurl%28v=exchg.80%29.aspx) method uses the email address to set the [ExchangeService](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.exchangeservice%28v=exchg.80%29.aspx) endpoint and enables your application to use any methods included in the **ExchangeService** proxy classes.</span></span> <span data-ttu-id="71a9a-115">O exemplo a seguir mostra como usar o método **AutodiscoverURL** .</span><span class="sxs-lookup"><span data-stu-id="71a9a-115">The following example shows how to use the **AutodiscoverURL** method.</span></span> 
  
```cs
// Create the binding.
ExchangeService service = new ExchangeService();
// Set the credentials for the on-premises server.
service.Credentials = new WebCredentials("user1@contoso.com", "password");
// Set the URL.
service.AutodiscoverUrl("User1@contoso.com");

```

## <a name="set-the-exchange-service-url-manually"></a><span data-ttu-id="71a9a-116">Definir a URL do serviço Exchange manualmente</span><span class="sxs-lookup"><span data-stu-id="71a9a-116">Set the Exchange service URL manually</span></span>
<span data-ttu-id="71a9a-117"><a name="bk_SetURLmanually"> </a></span><span class="sxs-lookup"><span data-stu-id="71a9a-117"></span></span>

<span data-ttu-id="71a9a-118">O exemplo a seguir mostra como definir a URL do serviço EWS utilizando-se um valor em cache.</span><span class="sxs-lookup"><span data-stu-id="71a9a-118">The following example shows you how to set the EWS service URL by using a cached value.</span></span> <span data-ttu-id="71a9a-119">Antes de fazer isso, verifique se usar o serviço Descoberta automática para obter a URL do EWS.</span><span class="sxs-lookup"><span data-stu-id="71a9a-119">Before you do this, make sure to use the Autodiscover service to get the EWS URL.</span></span>
  
```cs
// Create the binding.
ExchangeService service = new ExchangeService();
// Set the credentials for the on-premises server.
service.Credentials = new WebCredentials("user1@contoso.com", "password");
// Set the URL.
service.Url = new Uri("https://computername.domain.contoso.com/EWS/Exchange.asmx");

```

## <a name="see-also"></a><span data-ttu-id="71a9a-120">Confira também</span><span class="sxs-lookup"><span data-stu-id="71a9a-120">See also</span></span>

- [<span data-ttu-id="71a9a-121">Introdução aos aplicativos de cliente API gerenciada de EWS</span><span class="sxs-lookup"><span data-stu-id="71a9a-121">Get started with EWS Managed API client applications</span></span>](get-started-with-ews-managed-api-client-applications.md)   
- [<span data-ttu-id="71a9a-122">Configurando o ambiente de desenvolvimento de aplicativos do Exchange</span><span class="sxs-lookup"><span data-stu-id="71a9a-122">Setting up your Exchange application development environment</span></span>](setting-up-your-exchange-application-development-environment.md)   
- [<span data-ttu-id="71a9a-123">Controlar o acesso a EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="71a9a-123">Control access to EWS in Exchange</span></span>](how-to-control-access-to-ews-in-exchange.md) 
- [<span data-ttu-id="71a9a-124">Comunicar-se com o EWS usando a API gerenciada de EWS</span><span class="sxs-lookup"><span data-stu-id="71a9a-124">Communicate with EWS by using the EWS Managed API</span></span>](how-to-communicate-with-ews-by-using-the-ews-managed-api.md)  
- [<span data-ttu-id="71a9a-125">Usar descoberta automática para encontrar os pontos de conexão</span><span class="sxs-lookup"><span data-stu-id="71a9a-125">Use Autodiscover to find connection points</span></span>](how-to-use-autodiscover-to-find-connection-points.md)
    

