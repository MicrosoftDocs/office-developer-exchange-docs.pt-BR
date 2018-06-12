---
title: Trabalhar com pastas de pesquisa usando o EWS no Exchange
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
localization_priority: Normal
ms.assetid: abe703c5-6d85-46d9-bf20-230c34782a9f
description: Descubra como criar, obter, atualizar e excluir pastas de pesquisa usando a API gerenciada de EWS ou EWS no Exchange.
ms.openlocfilehash: e38ff50fcdb5e42cea3f4b2e25345375f84ae6eb
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19750873"
---
# <a name="work-with-search-folders-by-using-ews-in-exchange"></a><span data-ttu-id="82aff-103">Trabalhar com pastas de pesquisa usando o EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="82aff-103">Work with search folders by using EWS in Exchange</span></span>

<span data-ttu-id="82aff-104">Descubra como criar, obter, atualizar e excluir pastas de pesquisa usando a API gerenciada de EWS ou EWS no Exchange.</span><span class="sxs-lookup"><span data-stu-id="82aff-104">Find out how to create, get, update, and delete search folders by using the EWS Managed API or EWS in Exchange.</span></span>
  
<span data-ttu-id="82aff-105">Uma pasta de pesquisa representa uma pesquisa persistente "always on" na caixa de correio do usuário.</span><span class="sxs-lookup"><span data-stu-id="82aff-105">A search folder represents a persistent "always-on" search in a user's mailbox.</span></span> <span data-ttu-id="82aff-106">Uma pasta de pesquisa procura e atua como uma pasta de caixa de correio regulares.</span><span class="sxs-lookup"><span data-stu-id="82aff-106">A search folder looks and acts like a regular mailbox folder.</span></span> <span data-ttu-id="82aff-107">No entanto, em vez de que contém itens, ele contém uma cópia de "virtual" itens do quaisquer pastas no seu escopo de pesquisa que correspondem aos critérios de pesquisa definidas na pasta.</span><span class="sxs-lookup"><span data-stu-id="82aff-107">However, instead of containing items, it contains a "virtual" copy of items from any folders in its search scope that match the search criteria set on the folder.</span></span> <span data-ttu-id="82aff-108">Aplicativos e usuários finais podem usar pastas de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="82aff-108">Both applications and end-users can use search folders.</span></span> <span data-ttu-id="82aff-109">Seu aplicativo precisa realiza a mesma pesquisa repetidamente?</span><span class="sxs-lookup"><span data-stu-id="82aff-109">Does your application need to perform the same search over and over?</span></span> <span data-ttu-id="82aff-110">Pastas de pesquisa são uma excelente ferramenta para esta tarefa.</span><span class="sxs-lookup"><span data-stu-id="82aff-110">Search folders are a great tool for this task.</span></span> <span data-ttu-id="82aff-111">Ou talvez você queira apenas dar aos usuários a capacidade de acessar e gerenciar pastas de pesquisa no seu cliente.</span><span class="sxs-lookup"><span data-stu-id="82aff-111">Or maybe you just want to give your users the ability to access and manage search folders in your client.</span></span> <span data-ttu-id="82aff-112">Qualquer item seu cenário, o EWS Managed API e EWS habilitar seu aplicativo totalmente interagir com pastas de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="82aff-112">Whatever your scenario, the EWS Managed API and EWS enable your application to fully interact with search folders.</span></span>
  
<span data-ttu-id="82aff-113">**Tabela 1. Métodos de API gerenciada de EWS e operações de EWS para trabalhar com pastas de pesquisa**</span><span class="sxs-lookup"><span data-stu-id="82aff-113">**Table 1. EWS Managed API methods and EWS operations for working with search folders**</span></span>

|<span data-ttu-id="82aff-114">**Se você quiser …**</span><span class="sxs-lookup"><span data-stu-id="82aff-114">**If you want to…**</span></span>|<span data-ttu-id="82aff-115">**Na API gerenciada do EWS, use …**</span><span class="sxs-lookup"><span data-stu-id="82aff-115">**In the EWS Managed API, use…**</span></span>|<span data-ttu-id="82aff-116">**No EWS, use …**</span><span class="sxs-lookup"><span data-stu-id="82aff-116">**In EWS, use…**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="82aff-117">Crie uma pasta de pesquisa</span><span class="sxs-lookup"><span data-stu-id="82aff-117">Create a search folder</span></span>  <br/> |[<span data-ttu-id="82aff-118">SearchFolder.Save</span><span class="sxs-lookup"><span data-stu-id="82aff-118">SearchFolder.Save</span></span>](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.searchfolder.save%28v=exchg.80%29.aspx) <br/> |[<span data-ttu-id="82aff-119">Operação CreateFolder</span><span class="sxs-lookup"><span data-stu-id="82aff-119">CreateFolder operation</span></span>](http://msdn.microsoft.com/library/6f6c334c-b190-4e55-8f0a-38f2a018d1b3%28Office.15%29.aspx) <br/> |
|<span data-ttu-id="82aff-120">Obtenha uma pasta de pesquisa</span><span class="sxs-lookup"><span data-stu-id="82aff-120">Get a search folder</span></span>  <br/> |[<span data-ttu-id="82aff-121">SearchFolder.Bind</span><span class="sxs-lookup"><span data-stu-id="82aff-121">SearchFolder.Bind</span></span>](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.searchfolder.bind%28v=exchg.80%29.aspx) <br/> |[<span data-ttu-id="82aff-122">Operação GetFolder</span><span class="sxs-lookup"><span data-stu-id="82aff-122">GetFolder operation</span></span>](http://msdn.microsoft.com/library/355bcf93-dc71-4493-b177-622afac5fdb9%28Office.15%29.aspx) <br/> |
|<span data-ttu-id="82aff-123">Atualizar uma pasta de pesquisa</span><span class="sxs-lookup"><span data-stu-id="82aff-123">Update a search folder</span></span>  <br/> |[<span data-ttu-id="82aff-124">SearchFolder.Update</span><span class="sxs-lookup"><span data-stu-id="82aff-124">SearchFolder.Update</span></span>](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.folder.update%28v=exchg.80%29.aspx) <br/> |[<span data-ttu-id="82aff-125">Operação UpdateFolder</span><span class="sxs-lookup"><span data-stu-id="82aff-125">UpdateFolder operation</span></span>](http://msdn.microsoft.com/library/3494c996-b834-4813-b1ca-d99642d8b4e7%28Office.15%29.aspx) <br/> |
|<span data-ttu-id="82aff-126">Excluir uma pasta de pesquisa</span><span class="sxs-lookup"><span data-stu-id="82aff-126">Delete a search folder</span></span>  <br/> |[<span data-ttu-id="82aff-127">SearchFolder.Delete</span><span class="sxs-lookup"><span data-stu-id="82aff-127">SearchFolder.Delete</span></span>](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.folder.delete%28v=exchg.80%29.aspx) <br/> |[<span data-ttu-id="82aff-128">Operação DeleteFolder</span><span class="sxs-lookup"><span data-stu-id="82aff-128">DeleteFolder operation</span></span>](http://msdn.microsoft.com/library/b0f92682-4895-4bcf-a4a1-e4c2e8403979%28Office.15%29.aspx) <br/> |
   
## <a name="core-concepts-to-know-for-working-with-search-folders"></a><span data-ttu-id="82aff-129">Principais conceitos saber para trabalhar com pastas de pesquisa</span><span class="sxs-lookup"><span data-stu-id="82aff-129">Core concepts to know for working with search folders</span></span>
<span data-ttu-id="82aff-130"><a name="bk_CoreConcepts"> </a></span><span class="sxs-lookup"><span data-stu-id="82aff-130"></span></span>

<span data-ttu-id="82aff-131">Antes de começar a trabalhar com pastas de pesquisa, você vai querer estar familiarizado com como os filtros de pesquisa funcionam.</span><span class="sxs-lookup"><span data-stu-id="82aff-131">Before you start working with search folders, you'll want to be familiar with how search filters work.</span></span> <span data-ttu-id="82aff-132">Pastas de pesquisa dependem de filtros para expressar seus critérios de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="82aff-132">Search folders rely on search filters to express their criteria.</span></span> <span data-ttu-id="82aff-133">Filtros de pesquisa para as pastas de pesquisa são construídos da mesma maneira que [os filtros de pesquisa das operações de pesquisa](how-to-use-search-filters-with-ews-in-exchange.md) são construídas.</span><span class="sxs-lookup"><span data-stu-id="82aff-133">Search filters for search folders are constructed in the same way that [search filters for search operations](how-to-use-search-filters-with-ews-in-exchange.md) are constructed.</span></span> 
  
## <a name="create-a-search-folder-by-using-the-ews-managed-api"></a><span data-ttu-id="82aff-134">Crie uma pasta de pesquisa usando a API gerenciada de EWS</span><span class="sxs-lookup"><span data-stu-id="82aff-134">Create a search folder by using the EWS Managed API</span></span>
<span data-ttu-id="82aff-135"><a name="bk_CreateEWSMA"> </a></span><span class="sxs-lookup"><span data-stu-id="82aff-135"></span></span>

<span data-ttu-id="82aff-136">Basicamente, você pode criar uma pasta de pesquisa usando o EWS Managed API da mesma maneira que você criar uma pasta regular.</span><span class="sxs-lookup"><span data-stu-id="82aff-136">Basically, you create a search folder using the EWS Managed API in the same way that you create a regular folder.</span></span> <span data-ttu-id="82aff-137">No entanto, em vez de usar a [classe de pasta](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.folder%28v=exchg.80%29.aspx), você usa a [classe SearchFolder](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.searchfolder%28v=exchg.80%29.aspx)e defina a [propriedade SearchParameters](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.searchfolder.searchparameters%28v=exchg.80%29.aspx) para configurar os critérios de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="82aff-137">However, instead of using the [Folder class](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.folder%28v=exchg.80%29.aspx), you use the [SearchFolder class](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.searchfolder%28v=exchg.80%29.aspx), and set the [SearchParameters property](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.searchfolder.searchparameters%28v=exchg.80%29.aspx) to configure the search criteria.</span></span> 
  
<span data-ttu-id="82aff-138">No exemplo a seguir, uma pasta de pesquisa é criada para localizar todas as mensagens de caixa de entrada e suas subpastas que foram enviadas pelo gerente do usuário, sadie@contoso.com.</span><span class="sxs-lookup"><span data-stu-id="82aff-138">In the following example, a search folder is created to find all messages in the Inbox and its subfolders that were sent by the user's manager, sadie@contoso.com.</span></span> <span data-ttu-id="82aff-139">A pasta é criada como um filho da pasta pastas de pesquisa na caixa de correio do usuário.</span><span class="sxs-lookup"><span data-stu-id="82aff-139">The folder is created as a child of the Search Folders folder in the user's mailbox.</span></span>
  
> [!NOTE]
> <span data-ttu-id="82aff-140">Você pode criar uma pasta de pesquisa como uma filha de qualquer pasta na caixa de correio do usuário.</span><span class="sxs-lookup"><span data-stu-id="82aff-140">You can create a search folder as a child of any folder in the user's mailbox.</span></span> <span data-ttu-id="82aff-141">No entanto, se desejar que a pasta recém-criada seja mostrada em pastas de pesquisa no Outlook, criá-lo sob a pasta conhecida pastas de pesquisa, usando o valor **SearchFolders** da [enumeração WellKnownFolderName](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.wellknownfoldername%28v=exchg.80%29.aspx).</span><span class="sxs-lookup"><span data-stu-id="82aff-141">However, if you want the newly created folder to show up under Search Folders in Outlook, create it under the Search Folders well-known folder, using the **SearchFolders** value of the [WellKnownFolderName enumeration](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.wellknownfoldername%28v=exchg.80%29.aspx).</span></span> 
  
<span data-ttu-id="82aff-142">Este exemplo pressupõe que o objeto **ExchangeService** foi inicializado com valores válidos nas propriedades [credenciais](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.exchangeservicebase.credentials%28v=exchg.80%29.aspx) e [Url](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.exchangeservice.url%28v=exchg.80%29.aspx) .</span><span class="sxs-lookup"><span data-stu-id="82aff-142">This example assumes that the **ExchangeService** object has been initialized with valid values in the [Credentials](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.exchangeservicebase.credentials%28v=exchg.80%29.aspx) and [Url](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.exchangeservice.url%28v=exchg.80%29.aspx) properties.</span></span> 
  
```cs
using Microsoft.Exchange.WebServices.Data;
static void CreateSearchFolder(ExchangeService service)
{
    // Create the folder.
    SearchFolder searchFolder = new SearchFolder(service);
    searchFolder.DisplayName = "From Manager";
    // Create a search filter to express the criteria
    // for the folder.
    EmailAddress manager = new EmailAddress("sadie@contoso.com");
    SearchFilter.IsEqualTo fromManagerFilter =
        new SearchFilter.IsEqualTo(EmailMessageSchema.Sender, manager);
    // Set the search filter.
    searchFolder.SearchParameters.SearchFilter = fromManagerFilter;
    // Set the folder to search.
    searchFolder.SearchParameters.RootFolderIds.Add(WellKnownFolderName.Inbox);
    // Set the search traversal. Deep will search all subfolders.
    searchFolder.SearchParameters.Traversal = SearchFolderTraversal.Deep;
    // Call Save to make the EWS call to create the folder.
    searchFolder.Save(WellKnownFolderName.SearchFolders);
}
```

## <a name="create-a-search-folder-by-using-ews"></a><span data-ttu-id="82aff-143">Criar uma pasta de pesquisa usando o EWS</span><span class="sxs-lookup"><span data-stu-id="82aff-143">Create a search folder by using EWS</span></span>
<span data-ttu-id="82aff-144"><a name="bk_CreateEWS"> </a></span><span class="sxs-lookup"><span data-stu-id="82aff-144"></span></span>

<span data-ttu-id="82aff-145">Se você estiver usando o EWS, use a [operação CreateFolder](http://msdn.microsoft.com/library/6f6c334c-b190-4e55-8f0a-38f2a018d1b3%28Office.15%29.aspx) com um elemento [SearchFolder](http://msdn.microsoft.com/library/1a7d408b-2e98-4391-8834-085ed6d5757c%28Office.15%29.aspx) para criar uma pasta de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="82aff-145">If you are using EWS, use the [CreateFolder operation](http://msdn.microsoft.com/library/6f6c334c-b190-4e55-8f0a-38f2a018d1b3%28Office.15%29.aspx) with a [SearchFolder](http://msdn.microsoft.com/library/1a7d408b-2e98-4391-8834-085ed6d5757c%28Office.15%29.aspx) element to create a search folder.</span></span> <span data-ttu-id="82aff-146">No exemplo a seguir solicitação, uma pasta de pesquisa é criada para localizar todas as mensagens de caixa de entrada e suas subpastas que foram enviadas pelo gerente do usuário, sadie@contoso.com.</span><span class="sxs-lookup"><span data-stu-id="82aff-146">In the following request example, a search folder is created to find all messages in the Inbox and its subfolders that were sent by the user's manager, sadie@contoso.com.</span></span> <span data-ttu-id="82aff-147">A pasta é criada na pasta pastas de pesquisa na caixa de correio do usuário.</span><span class="sxs-lookup"><span data-stu-id="82aff-147">The folder is created in the Search Folders folder in the user's mailbox.</span></span> 
  
> [!NOTE]
> <span data-ttu-id="82aff-148">Você pode criar uma pasta de pesquisa como uma filha de qualquer pasta na caixa de correio do usuário.</span><span class="sxs-lookup"><span data-stu-id="82aff-148">You can create a search folder as a child of any folder in the user's mailbox.</span></span> <span data-ttu-id="82aff-149">No entanto, se desejar que a pasta recém-criada seja mostrada em pastas de pesquisa no Outlook, criá-lo sob a pasta conhecida pastas de pesquisa, usando o valor de **searchfolders** no atributo **Id** do elemento [DistinguishedFolderId](http://msdn.microsoft.com/library/50018162-2941-4227-8a5b-d6b4686bb32f%28Office.15%29.aspx) .</span><span class="sxs-lookup"><span data-stu-id="82aff-149">However, if you want the newly created folder to show up under Search Folders in Outlook, create it under the Search Folders well-known folder, using the **searchfolders** value in the **Id** attribute of the [DistinguishedFolderId](http://msdn.microsoft.com/library/50018162-2941-4227-8a5b-d6b4686bb32f%28Office.15%29.aspx) element.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
    xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
    xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" 
    xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2007_SP1" />
    <t:TimeZoneContext>
      <t:TimeZoneDefinition Id="Eastern Standard Time" />
    </t:TimeZoneContext>
  </soap:Header>
  <soap:Body>
    <m:CreateFolder>
      <m:ParentFolderId>
        <t:DistinguishedFolderId Id="searchfolders" />
      </m:ParentFolderId>
      <m:Folders>
        <t:SearchFolder>
          <t:DisplayName>From Manager</t:DisplayName>
          <t:SearchParameters Traversal="Deep">
            <t:Restriction>
              <t:IsEqualTo>
                <t:FieldURI FieldURI="message:Sender" />
                <t:FieldURIOrConstant>
                  <t:Constant Value="sadie@contoso.com" />
                </t:FieldURIOrConstant>
              </t:IsEqualTo>
            </t:Restriction>
            <t:BaseFolderIds>
              <t:DistinguishedFolderId Id="inbox" />
            </t:BaseFolderIds>
          </t:SearchParameters>
        </t:SearchFolder>
      </m:Folders>
    </m:CreateFolder>
  </soap:Body>
</soap:Envelope>
```

<span data-ttu-id="82aff-150">O servidor responde com uma mensagem de [CreateFolderResponse](http://msdn.microsoft.com/library/158adecc-491a-47d9-af73-acc2cd3f8566%28Office.15%29.aspx) que inclui um valor de [ResponseCode](http://msdn.microsoft.com/library/4b84d670-74c9-4d6d-84e7-f0a9f76f0d93%28Office.15%29.aspx) de **NoError**, que indica o sucesso.</span><span class="sxs-lookup"><span data-stu-id="82aff-150">The server responds with a [CreateFolderResponse](http://msdn.microsoft.com/library/158adecc-491a-47d9-af73-acc2cd3f8566%28Office.15%29.aspx) message that includes a [ResponseCode](http://msdn.microsoft.com/library/4b84d670-74c9-4d6d-84e7-f0a9f76f0d93%28Office.15%29.aspx) value of **NoError**, which indicates success.</span></span>
  
## <a name="get-a-search-folder-by-using-the-ews-managed-api"></a><span data-ttu-id="82aff-151">Obtenha uma pasta de pesquisa usando a API gerenciada de EWS</span><span class="sxs-lookup"><span data-stu-id="82aff-151">Get a search folder by using the EWS Managed API</span></span>
<span data-ttu-id="82aff-152"><a name="bk_RetrieveEWSMA"> </a></span><span class="sxs-lookup"><span data-stu-id="82aff-152"></span></span>

<span data-ttu-id="82aff-153">Use o método de API gerenciada de EWS [ExchangeService.FindFolders](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.exchangeservice.findfolders%28v=exchg.80%29.aspx) para localizar pastas de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="82aff-153">Use the [ExchangeService.FindFolders](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.exchangeservice.findfolders%28v=exchg.80%29.aspx) EWS Managed API method to find search folders.</span></span> <span data-ttu-id="82aff-154">No entanto, observe que você não pode limitar os resultados para incluir somente as pastas de pesquisa; Você vai querer que lembre-se ao processar os resultados.</span><span class="sxs-lookup"><span data-stu-id="82aff-154">Note, however, that you can't limit your results to only include search folders; you'll want to keep that in mind when you process the results.</span></span> <span data-ttu-id="82aff-155">Use o método [SearchFolder.Bind](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.searchfolder.bind%28v=exchg.80%29.aspx) para obter as pastas de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="82aff-155">Use the [SearchFolder.Bind](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.searchfolder.bind%28v=exchg.80%29.aspx) method to get search folders.</span></span> 
  
<span data-ttu-id="82aff-156">O exemplo a seguir localiza as 10 primeiros pastas na pasta pastas de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="82aff-156">The following example finds the first 10 folders in the Search Folders folder.</span></span> <span data-ttu-id="82aff-157">Ele verifica para determinar se cada um deles é uma pasta de pesquisa e se assim, ele obtém a pasta de pesquisa e exibe quantas pastas de destino, ele pesquisará.</span><span class="sxs-lookup"><span data-stu-id="82aff-157">It checks to determine whether each one is a search folder, and if so, it gets the search folder and displays how many target folders it searches.</span></span>
  
```cs
using Microsoft.Exchange.WebServices.Data;
static void GetSearchFolders(ExchangeService service)
{
    FolderView folderView = new FolderView(10);
    folderView.PropertySet = new PropertySet(FolderSchema.DisplayName);
    try
    {
        FindFoldersResults findResults = service.FindFolders(WellKnownFolderName.SearchFolders, folderView);
        foreach (Folder folder in findResults.Folders)
        {
            // You can't request only search folders in 
            // a FindFolders request, so other search folders might also be present.
            if (folder is SearchFolder)
            {
                Console.WriteLine("{0} is a search folder.", folder.DisplayName);
                // In order to access the SearchParameters property,
                // you have to bind to the folder. SearchParameters are not
                // returned in FindFolders results.
                SearchFolder searchFolder = SearchFolder.Bind(service, folder.Id);
                Console.WriteLine("Number of folders searched: {0}.",
                    searchFolder.SearchParameters.RootFolderIds.Count);
            }
            else
            {
                Console.WriteLine("{0} is NOT a search folder.", folder.DisplayName);
            }
        }
    }
    catch (Exception ex)
    {
        Console.WriteLine("Exception while enumerating results: {0}", ex.Message);
    }
}
```

## <a name="get-a-search-folder-by-using-ews"></a><span data-ttu-id="82aff-158">Obter uma pasta de pesquisa usando o EWS</span><span class="sxs-lookup"><span data-stu-id="82aff-158">Get a search folder by using EWS</span></span>
<span data-ttu-id="82aff-159"><a name="bk_RetrieveEWS"> </a></span><span class="sxs-lookup"><span data-stu-id="82aff-159"></span></span>

<span data-ttu-id="82aff-160">Se você estiver usando o EWS, use a [operação FindFolder](http://msdn.microsoft.com/library/7a9855aa-06cc-45ba-ad2a-645c15b7d031%28Office.15%29.aspx) para localizar pastas de pesquisa e a [operação GetFolder](http://msdn.microsoft.com/library/355bcf93-dc71-4493-b177-622afac5fdb9%28Office.15%29.aspx) para obter as pastas de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="82aff-160">If you're using EWS, use the [FindFolder operation](http://msdn.microsoft.com/library/7a9855aa-06cc-45ba-ad2a-645c15b7d031%28Office.15%29.aspx) to find search folders, and the [GetFolder operation](http://msdn.microsoft.com/library/355bcf93-dc71-4493-b177-622afac5fdb9%28Office.15%29.aspx) to get search folders.</span></span> <span data-ttu-id="82aff-161">Uma resposta **GetFolder** bem-sucedida de uma pasta de pesquisa irá conter um elemento [SearchFolder](http://msdn.microsoft.com/library/1a7d408b-2e98-4391-8834-085ed6d5757c%28Office.15%29.aspx) .</span><span class="sxs-lookup"><span data-stu-id="82aff-161">A successful **GetFolder** response for a search folder will contain a [SearchFolder](http://msdn.microsoft.com/library/1a7d408b-2e98-4391-8834-085ed6d5757c%28Office.15%29.aspx) element.</span></span> <span data-ttu-id="82aff-162">O exemplo a seguir solicitação localiza as 10 primeiros pastas na pasta pastas de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="82aff-162">The following request example finds the first 10 folders in the Search Folders folder.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
    xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
    xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" 
    xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2007_SP1" />
    <t:TimeZoneContext>
      <t:TimeZoneDefinition Id="Eastern Standard Time" />
    </t:TimeZoneContext>
  </soap:Header>
  <soap:Body>
    <m:FindFolder Traversal="Shallow">
      <m:FolderShape>
        <t:BaseShape>IdOnly</t:BaseShape>
        <t:AdditionalProperties>
          <t:FieldURI FieldURI="folder:DisplayName" />
        </t:AdditionalProperties>
      </m:FolderShape>
      <m:IndexedPageFolderView MaxEntriesReturned="10" Offset="0" BasePoint="Beginning" />
      <m:ParentFolderIds>
        <t:DistinguishedFolderId Id="searchfolders" />
      </m:ParentFolderIds>
    </m:FindFolder>
  </soap:Body>
</soap:Envelope>
```

<span data-ttu-id="82aff-163">O servidor retorna a resposta a seguir, que mostra uma pasta de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="82aff-163">The server returns the following response, which shows one search folder.</span></span>
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<s:Envelope xmlns:s="http://schemas.xmlsoap.org/soap/envelope/">
  <s:Header>
    <h:ServerVersionInfo MajorVersion="15" MinorVersion="0" MajorBuildNumber="712" MinorBuildNumber="22" Version="V2_3" 
        xmlns:h="http://schemas.microsoft.com/exchange/services/2006/types" 
        xmlns="http://schemas.microsoft.com/exchange/services/2006/types" 
        xmlns:xsd="http://www.w3.org/2001/XMLSchema" 
        xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" />
  </s:Header>
  <s:Body xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <m:FindFolderResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
        xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
      <m:ResponseMessages>
        <m:FindFolderResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:RootFolder IndexedPagingOffset="3" TotalItemsInView="3" IncludesLastItemInRange="true">
            <t:Folders>
              <t:SearchFolder>
                <t:FolderId Id="AAMkAGM2..." ChangeKey="CAAAABYA..." />
                <t:DisplayName>From Manager</t:DisplayName>
              </t:SearchFolder>
            </t:Folders>
          </m:RootFolder>
        </m:FindFolderResponseMessage>
      </m:ResponseMessages>
    </m:FindFolderResponse>
  </s:Body>
</s:Envelope>
```

<span data-ttu-id="82aff-164">O exemplo a seguir de uma solicitação usa o valor do elemento [FolderId](http://msdn.microsoft.com/library/00d14e3e-4365-4f21-8f88-eaeea73b9bf7%28Office.15%29.aspx) da resposta anterior em uma solicitação de operação **GetFolder** para obter a pasta de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="82aff-164">The following example of a request uses the value of the [FolderId](http://msdn.microsoft.com/library/00d14e3e-4365-4f21-8f88-eaeea73b9bf7%28Office.15%29.aspx) element from the previous response in a **GetFolder** operation request to get the search folder.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
    xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
    xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" 
    xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2007_SP1" />
    <t:TimeZoneContext>
      <t:TimeZoneDefinition Id="Eastern Standard Time" />
    </t:TimeZoneContext>
  </soap:Header>
  <soap:Body>
    <m:GetFolder>
      <m:FolderShape>
        <t:BaseShape>AllProperties</t:BaseShape>
      </m:FolderShape>
      <m:FolderIds>
        <t:FolderId Id="AAMkAGM2..." ChangeKey="CAAAABYA..." />
      </m:FolderIds>
    </m:GetFolder>
  </soap:Body>
</soap:Envelope>
```

<span data-ttu-id="82aff-165">O servidor retorna a seguinte resposta com todas as propriedades de primeira classe para a pasta de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="82aff-165">The server returns the following response with all the first-class properties for the search folder.</span></span>
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<s:Envelope xmlns:s="http://schemas.xmlsoap.org/soap/envelope/">
  <s:Header>
    <h:ServerVersionInfo MajorVersion="15" MinorVersion="0" MajorBuildNumber="712" MinorBuildNumber="22" Version="V2_3" 
        xmlns:h="http://schemas.microsoft.com/exchange/services/2006/types" 
        xmlns="http://schemas.microsoft.com/exchange/services/2006/types" 
        xmlns:xsd="http://www.w3.org/2001/XMLSchema" 
        xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" />
  </s:Header>
  <s:Body xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <m:GetFolderResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
        xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
      <m:ResponseMessages>
        <m:GetFolderResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:Folders>
            <t:SearchFolder>
              <t:FolderId Id="AAMkAGM2..." ChangeKey="CAAAABYA..." />
              <t:ParentFolderId Id="AQMkAGM2..." ChangeKey="AQAAAA==" />
              <t:FolderClass>IPF.Note</t:FolderClass>
              <t:DisplayName>From Manager</t:DisplayName>
              <t:TotalCount>8</t:TotalCount>
              <t:ChildFolderCount>0</t:ChildFolderCount>
              <t:EffectiveRights>
                <t:CreateAssociated>true</t:CreateAssociated>
                <t:CreateContents>true</t:CreateContents>
                <t:CreateHierarchy>true</t:CreateHierarchy>
                <t:Delete>true</t:Delete>
                <t:Modify>true</t:Modify>
                <t:Read>true</t:Read>
                <t:ViewPrivateItems>true</t:ViewPrivateItems>
              </t:EffectiveRights>
              <t:UnreadCount>0</t:UnreadCount>
              <t:SearchParameters Traversal="Deep">
                <t:Restriction>
                  <t:IsEqualTo>
                    <t:FieldURI FieldURI="message:Sender" />
                    <t:FieldURIOrConstant>
                      <t:Constant Value="/o=First Organization/ou=Exchange Administrative Group (FYDIBOHF23SPDLT)/cn=Recipients/cn=8d84a3f4cbb34d48838a3aecf99795c0-Sadie" />
                    </t:FieldURIOrConstant>
                  </t:IsEqualTo>
                </t:Restriction>
                <t:BaseFolderIds>
                  <t:FolderId Id="AQMkAGM2..." ChangeKey="AQAAAA==" />
                </t:BaseFolderIds>
              </t:SearchParameters>
            </t:SearchFolder>
          </m:Folders>
        </m:GetFolderResponseMessage>
      </m:ResponseMessages>
    </m:GetFolderResponse>
  </s:Body>
</s:Envelope>
```

## <a name="update-a-search-folder-by-using-the-ews-managed-api"></a><span data-ttu-id="82aff-166">Atualizar uma pasta de pesquisa usando a API gerenciada de EWS</span><span class="sxs-lookup"><span data-stu-id="82aff-166">Update a search folder by using the EWS Managed API</span></span>
<span data-ttu-id="82aff-167"><a name="bk_UpdateEWSMA"> </a></span><span class="sxs-lookup"><span data-stu-id="82aff-167"></span></span>

<span data-ttu-id="82aff-168">Use o método de API gerenciada de EWS [Folder.Update](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.folder.update%28v=exchg.80%29.aspx) em um objeto **SearchFolder** para atualizar uma pasta de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="82aff-168">Use the [Folder.Update](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.folder.update%28v=exchg.80%29.aspx) EWS Managed API method on a **SearchFolder** object to update a search folder.</span></span> <span data-ttu-id="82aff-169">O exemplo a seguir atualiza os critérios de pesquisa em uma pasta de pesquisa com o nome para exibição "Gerente de".</span><span class="sxs-lookup"><span data-stu-id="82aff-169">The following example updates the search criteria on a search folder with the display name "From Manager".</span></span> 
  
```cs
using Microsoft.Exchange.WebServices.Data;
static void UpdateSearchFolder(ExchangeService service)
{
    FolderView folderView = new FolderView(10);
    folderView.PropertySet = new PropertySet(FolderSchema.DisplayName);
    try
    {
        FindFoldersResults findResults = service.FindFolders(WellKnownFolderName.SearchFolders, folderView);
        foreach (Folder folder in findResults.Folders)
        {
            // You cannot request only search folders in 
            // a FindFolders request, so other search folders might also be present.
            if (folder is SearchFolder &amp;&amp; folder.DisplayName.Equals("From Manager"))
            {
                Console.WriteLine("\"{0}\" folder found.", folder.DisplayName);
                SearchFolder searchFolder = folder as SearchFolder;
                EmailAddress newManager = new EmailAddress("hope@contoso.com");
                SearchFilter.IsEqualTo newManagerFilter =
                    new SearchFilter.IsEqualTo(EmailMessageSchema.Sender, newManager);
                searchFolder.SearchParameters.SearchFilter = newManagerFilter;
                searchFolder.SearchParameters.RootFolderIds.Add(WellKnownFolderName.Inbox);
                searchFolder.SearchParameters.Traversal = SearchFolderTraversal.Deep;
                searchFolder.Update();
                Console.WriteLine("\"{0}\" folder updated.", folder.DisplayName);
            }
        }
    }
    catch (Exception ex)
    {
        Console.WriteLine("Exception while enumerating results: {0}", ex.Message);
    }
}
```

## <a name="update-a-search-folder-by-using-ews"></a><span data-ttu-id="82aff-170">Atualizar uma pasta de pesquisa usando o EWS</span><span class="sxs-lookup"><span data-stu-id="82aff-170">Update a search folder by using EWS</span></span>
<span data-ttu-id="82aff-171"><a name="bk_UpdateEWS"> </a></span><span class="sxs-lookup"><span data-stu-id="82aff-171"></span></span>

<span data-ttu-id="82aff-172">Se você estiver usando o EWS, use a [operação UpdateFolder](http://msdn.microsoft.com/library/3494c996-b834-4813-b1ca-d99642d8b4e7%28Office.15%29.aspx) com um elemento [SearchFolder](http://msdn.microsoft.com/library/1a7d408b-2e98-4391-8834-085ed6d5757c%28Office.15%29.aspx) para atualizar uma pasta de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="82aff-172">If you're using EWS, use the [UpdateFolder operation](http://msdn.microsoft.com/library/3494c996-b834-4813-b1ca-d99642d8b4e7%28Office.15%29.aspx) with a [SearchFolder](http://msdn.microsoft.com/library/1a7d408b-2e98-4391-8834-085ed6d5757c%28Office.15%29.aspx) element to update a search folder.</span></span> <span data-ttu-id="82aff-173">O exemplo a seguir solicitação atualiza os critérios de pesquisa na pasta de pesquisa "Gerente de".</span><span class="sxs-lookup"><span data-stu-id="82aff-173">The following request example updates the search criteria on the "From Manager" search folder.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
    xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
    xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" 
    xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2007_SP1" />
    <t:TimeZoneContext>
      <t:TimeZoneDefinition Id="Eastern Standard Time" />
    </t:TimeZoneContext>
  </soap:Header>
  <soap:Body>
    <m:UpdateFolder>
      <m:FolderChanges>
        <t:FolderChange>
          <t:FolderId Id="AAMkAGM2..." ChangeKey="CAAAABYA..." />
          <t:Updates>
            <t:SetFolderField>
              <t:FieldURI FieldURI="folder:SearchParameters" />
              <t:SearchFolder>
                <t:SearchParameters Traversal="Deep">
                  <t:Restriction>
                    <t:IsEqualTo>
                      <t:FieldURI FieldURI="message:Sender" />
                      <t:FieldURIOrConstant>
                        <t:Constant Value="hope@contoso.com" />
                      </t:FieldURIOrConstant>
                    </t:IsEqualTo>
                  </t:Restriction>
                  <t:BaseFolderIds>
                    <t:DistinguishedFolderId Id="inbox" />
                  </t:BaseFolderIds>
                </t:SearchParameters>
              </t:SearchFolder>
            </t:SetFolderField>
          </t:Updates>
        </t:FolderChange>
      </m:FolderChanges>
    </m:UpdateFolder>
  </soap:Body>
</soap:Envelope>
```

<span data-ttu-id="82aff-174">O servidor responde com uma mensagem de [UpdateFolderResponse](http://msdn.microsoft.com/library/31f47739-dc9c-46ba-9e3f-cce25dc85e6e%28Office.15%29.aspx) que inclui um valor de [ResponseCode](http://msdn.microsoft.com/library/4b84d670-74c9-4d6d-84e7-f0a9f76f0d93%28Office.15%29.aspx) de **NoError**, que indica o sucesso.</span><span class="sxs-lookup"><span data-stu-id="82aff-174">The server responds with an [UpdateFolderResponse](http://msdn.microsoft.com/library/31f47739-dc9c-46ba-9e3f-cce25dc85e6e%28Office.15%29.aspx) message that includes a [ResponseCode](http://msdn.microsoft.com/library/4b84d670-74c9-4d6d-84e7-f0a9f76f0d93%28Office.15%29.aspx) value of **NoError**, which indicates success.</span></span>
  
## <a name="delete-a-search-folder-by-using-the-ews-managed-api"></a><span data-ttu-id="82aff-175">Excluir uma pasta de pesquisa usando a API gerenciada de EWS</span><span class="sxs-lookup"><span data-stu-id="82aff-175">Delete a search folder by using the EWS Managed API</span></span>
<span data-ttu-id="82aff-176"><a name="bk_DeleteEWSMA"> </a></span><span class="sxs-lookup"><span data-stu-id="82aff-176"></span></span>

<span data-ttu-id="82aff-177">Use o método de API gerenciada de EWS [Folder.Delete](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.folder.delete%28v=exchg.80%29.aspx) em um objeto **SearchFolder** para excluir uma pasta de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="82aff-177">Use the [Folder.Delete](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.folder.delete%28v=exchg.80%29.aspx) EWS Managed API method on a **SearchFolder** object to delete a search folder.</span></span> <span data-ttu-id="82aff-178">O exemplo a seguir exclui uma pasta de pesquisa com o nome para exibição "Gerente de".</span><span class="sxs-lookup"><span data-stu-id="82aff-178">The following example deletes a search folder with the display name "From Manager".</span></span> <span data-ttu-id="82aff-179">A pasta de pesquisa excluídos é movida para a pasta Itens excluídos.</span><span class="sxs-lookup"><span data-stu-id="82aff-179">The deleted search folder is moved to the Deleted Items folder.</span></span> 
  
```cs
using Microsoft.Exchange.WebServices.Data;
static void DeleteSearchFolder(ExchangeService service)
{
    FolderView folderView = new FolderView(10);
    folderView.PropertySet = new PropertySet(FolderSchema.DisplayName);
    try
    {
        FindFoldersResults findResults = service.FindFolders(WellKnownFolderName.SearchFolders, folderView);
        foreach (Folder folder in findResults.Folders)
        {
            // You cannot request only search folders in 
            // a FindFolders request, so other folders might also be present.
            if (folder is SearchFolder &amp;&amp; folder.DisplayName.Equals("From Manager"))
            {
                Console.WriteLine("\"{0}\" folder found.", folder.DisplayName);
                folder.Delete(DeleteMode.MoveToDeletedItems);
                Console.WriteLine("\"{0}\" folder deleted.", folder.DisplayName);
            }
        }
    }
    catch (Exception ex)
    {
        Console.WriteLine("Exception while enumerating results: {0}", ex.Message);
    }
}
```

## <a name="delete-a-search-folder-by-using-ews"></a><span data-ttu-id="82aff-180">Excluir uma pasta de pesquisa usando o EWS</span><span class="sxs-lookup"><span data-stu-id="82aff-180">Delete a search folder by using EWS</span></span>
<span data-ttu-id="82aff-181"><a name="bk_DeleteEWS"> </a></span><span class="sxs-lookup"><span data-stu-id="82aff-181"></span></span>

<span data-ttu-id="82aff-182">Se você estiver usando o EWS, use a [operação DeleteFolder](http://msdn.microsoft.com/library/b0f92682-4895-4bcf-a4a1-e4c2e8403979%28Office.15%29.aspx) para excluir uma pasta de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="82aff-182">If you're using EWS, use the [DeleteFolder operation](http://msdn.microsoft.com/library/b0f92682-4895-4bcf-a4a1-e4c2e8403979%28Office.15%29.aspx) to delete a search folder.</span></span> <span data-ttu-id="82aff-183">O exemplo a seguir exclui uma pasta de pesquisa e o move para a pasta Itens excluídos.</span><span class="sxs-lookup"><span data-stu-id="82aff-183">The following example deletes a search folder and moves it to the Deleted Items folder.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
    xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
    xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" 
    xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2007_SP1" />
    <t:TimeZoneContext>
      <t:TimeZoneDefinition Id="Eastern Standard Time" />
    </t:TimeZoneContext>
  </soap:Header>
  <soap:Body>
    <m:DeleteFolder DeleteType="MoveToDeletedItems">
      <m:FolderIds>
        <t:FolderId Id="AAMkAGM2..." ChangeKey="CAAAABYA..." />
      </m:FolderIds>
    </m:DeleteFolder>
  </soap:Body>
</soap:Envelope>
```

<span data-ttu-id="82aff-184">O servidor responde com uma mensagem de [DeleteFolderResponse](http://msdn.microsoft.com/library/27578bda-ef0a-4a33-bccc-2c1bc1735424%28Office.15%29.aspx) que inclui um valor de [ResponseCode](http://msdn.microsoft.com/library/4b84d670-74c9-4d6d-84e7-f0a9f76f0d93%28Office.15%29.aspx) de **NoError**, que indica o sucesso.</span><span class="sxs-lookup"><span data-stu-id="82aff-184">The server responds with a [DeleteFolderResponse](http://msdn.microsoft.com/library/27578bda-ef0a-4a33-bccc-2c1bc1735424%28Office.15%29.aspx) message that includes a [ResponseCode](http://msdn.microsoft.com/library/4b84d670-74c9-4d6d-84e7-f0a9f76f0d93%28Office.15%29.aspx) value of **NoError**, which indicates success.</span></span>
  
## <a name="see-also"></a><span data-ttu-id="82aff-185">Confira também</span><span class="sxs-lookup"><span data-stu-id="82aff-185">See also</span></span>


- [<span data-ttu-id="82aff-186">Pesquisa e EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="82aff-186">Search and EWS in Exchange</span></span>](search-and-ews-in-exchange.md)
    
- [<span data-ttu-id="82aff-187">Use os filtros de pesquisa com o EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="82aff-187">Use search filters with EWS in Exchange</span></span>](how-to-use-search-filters-with-ews-in-exchange.md)
    
- [<span data-ttu-id="82aff-188">Classe SearchFolder</span><span class="sxs-lookup"><span data-stu-id="82aff-188">SearchFolder class</span></span>](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.searchfolder%28v=exchg.80%29.aspx)
    
- [<span data-ttu-id="82aff-189">Operação CreateFolder</span><span class="sxs-lookup"><span data-stu-id="82aff-189">CreateFolder operation</span></span>](http://msdn.microsoft.com/library/6f6c334c-b190-4e55-8f0a-38f2a018d1b3%28Office.15%29.aspx)
    
- [<span data-ttu-id="82aff-190">Operação FindFolder</span><span class="sxs-lookup"><span data-stu-id="82aff-190">FindFolder operation</span></span>](http://msdn.microsoft.com/library/7a9855aa-06cc-45ba-ad2a-645c15b7d031%28Office.15%29.aspx)
    
- [<span data-ttu-id="82aff-191">Operação GetFolder</span><span class="sxs-lookup"><span data-stu-id="82aff-191">GetFolder operation</span></span>](http://msdn.microsoft.com/library/355bcf93-dc71-4493-b177-622afac5fdb9%28Office.15%29.aspx)
    
- [<span data-ttu-id="82aff-192">Operação UpdateFolder</span><span class="sxs-lookup"><span data-stu-id="82aff-192">UpdateFolder operation</span></span>](http://msdn.microsoft.com/library/3494c996-b834-4813-b1ca-d99642d8b4e7%28Office.15%29.aspx)
    
- [<span data-ttu-id="82aff-193">Operação DeleteFolder</span><span class="sxs-lookup"><span data-stu-id="82aff-193">DeleteFolder operation</span></span>](http://msdn.microsoft.com/library/b0f92682-4895-4bcf-a4a1-e4c2e8403979%28Office.15%29.aspx)
    

