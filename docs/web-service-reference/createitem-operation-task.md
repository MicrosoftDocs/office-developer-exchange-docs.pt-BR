---
title: Operação CreateItem (tarefa)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- CreateItem
api_type:
- schema
ms.assetid: 12c5da4d-290c-4a8a-a965-0bf5d55c7978
description: A operação CreateItem cria itens de tarefa no repositório do Exchange.
ms.openlocfilehash: 502108843193e7ed8377b0fade9e106ef3d1976c
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44457099"
---
# <a name="createitem-operation-task"></a><span data-ttu-id="c67fb-103">Operação CreateItem (tarefa)</span><span class="sxs-lookup"><span data-stu-id="c67fb-103">CreateItem operation (task)</span></span>

<span data-ttu-id="c67fb-104">A operação CreateItem cria itens de tarefa no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="c67fb-104">The CreateItem operation creates task items in the Exchange store.</span></span>
  
## <a name="task-createitem-request"></a><span data-ttu-id="c67fb-105">Solicitação de Tarefa CreateItem</span><span class="sxs-lookup"><span data-stu-id="c67fb-105">Task CreateItem Request</span></span>

### <a name="description"></a><span data-ttu-id="c67fb-106">Descrição</span><span class="sxs-lookup"><span data-stu-id="c67fb-106">Description</span></span>

<span data-ttu-id="c67fb-107">O exemplo a seguir de uma solicitação CreateItem mostra como criar um item de tarefa em uma caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="c67fb-107">The following example of a CreateItem request shows how to create a task item in a mailbox.</span></span>
  
### <a name="code"></a><span data-ttu-id="c67fb-108">Código</span><span class="sxs-lookup"><span data-stu-id="c67fb-108">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
               xmlns:xsd="http://www.w3.org/2001/XMLSchema"
               xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/"
               xmlns:t="https://schemas.microsoft.com/exchange/services/2006/types">
  <soap:Body>
    <CreateItem xmlns="https://schemas.microsoft.com/exchange/services/2006/messages"
                xmlns:t="https://schemas.microsoft.com/exchange/services/2006/types" 
                MessageDisposition="SaveOnly">
      <Items>
        <t:Task>
          <t:Subject>My task</t:Subject>
          <t:DueDate>2006-10-26T21:32:52</t:DueDate>
          <t:Status>NotStarted</t:Status>
        </t:Task>
      </Items>
    </CreateItem>
  </soap:Body>
</soap:Envelope>
```

### <a name="comments"></a><span data-ttu-id="c67fb-109">Comentários</span><span class="sxs-lookup"><span data-stu-id="c67fb-109">Comments</span></span>

<span data-ttu-id="c67fb-110">As solicitações de tarefas recorrentes são alteradas quando recebidas pelo computador que está executando o Microsoft Exchange Server 2007 que tem a função de servidor de acesso para Cliente instalada.</span><span class="sxs-lookup"><span data-stu-id="c67fb-110">Requests for recurring tasks are altered when they are received by the computer that is running Microsoft Exchange Server 2007 that has the Client Access server role installed.</span></span> <span data-ttu-id="c67fb-111">Ocorrem as seguintes alterações:</span><span class="sxs-lookup"><span data-stu-id="c67fb-111">The following changes occur:</span></span>
  
- <span data-ttu-id="c67fb-112">Somente a data é salva para a propriedade [StartDate (Recurrence)](startdate-recurrence.md) do intervalo de recorrência da tarefa.</span><span class="sxs-lookup"><span data-stu-id="c67fb-112">Only the date is saved for the [StartDate (Recurrence)](startdate-recurrence.md) property of the recurrence range of the task.</span></span> <span data-ttu-id="c67fb-113">A parte de tempo é truncada.</span><span class="sxs-lookup"><span data-stu-id="c67fb-113">The time part is truncated.</span></span> 
    
- <span data-ttu-id="c67fb-114">A propriedade [StartDate (Recurrence)](startdate-recurrence.md) pode ser ajustada, dependendo do padrão de recorrência.</span><span class="sxs-lookup"><span data-stu-id="c67fb-114">The [StartDate (Recurrence)](startdate-recurrence.md) property may be adjusted, depending on the recurrence pattern.</span></span> <span data-ttu-id="c67fb-115">Por exemplo, se o padrão de recorrência for especificado como cada segunda-feira e o StartDate estiver definido como 26 de outubro de 2006, que é uma quinta-feira, StartDate será ajustado para 30 de outubro de 2006, que é a próxima segunda-feira.</span><span class="sxs-lookup"><span data-stu-id="c67fb-115">For example, if the recurrence pattern is specified as every Monday and the StartDate is set to October 26, 2006, which is a Thursday, StartDate is adjusted to October 30, 2006, which is the next Monday.</span></span> 
    
- <span data-ttu-id="c67fb-116">Se a propriedade [StartDate](startdate.md) da tarefa for definida, ela será atualizada para corresponder ao [StartDate (recorrência)](startdate-recurrence.md) do intervalo de recorrência.</span><span class="sxs-lookup"><span data-stu-id="c67fb-116">If the [StartDate](startdate.md) property of the task is set, it is updated to match the [StartDate (Recurrence)](startdate-recurrence.md) of the recurrence range.</span></span> <span data-ttu-id="c67fb-117">A propriedade [DueDate](duedate.md) da tarefa também é atualizada com base no novo [StartDate](startdate.md).</span><span class="sxs-lookup"><span data-stu-id="c67fb-117">The [DueDate](duedate.md) property of the task is also updated based on the new [StartDate](startdate.md).</span></span>
    
- <span data-ttu-id="c67fb-118">Se o [StartDate](startdate.md) não for definido, somente a propriedade [DueDate](duedate.md) será atualizada para corresponder ao [StartDate (recorrência)](startdate-recurrence.md) do intervalo de recorrência.</span><span class="sxs-lookup"><span data-stu-id="c67fb-118">If the [StartDate](startdate.md) is not set, only the [DueDate](duedate.md) property is updated to match the [StartDate (Recurrence)](startdate-recurrence.md) of the recurrence range.</span></span> 
    
<span data-ttu-id="c67fb-119">A tabela a seguir mostra as alterações que o servidor de acesso para cliente realiza em uma tarefa recorrente que tem um Task. Recurrence. Pattern de cada segunda-feira.</span><span class="sxs-lookup"><span data-stu-id="c67fb-119">The following table shows the changes that the Client Access server makes to a recurring task that has a Task.Recurrence.Pattern of every Monday.</span></span>
  
<span data-ttu-id="c67fb-120">**Alterações em uma tarefa recorrente**</span><span class="sxs-lookup"><span data-stu-id="c67fb-120">**Changes to a recurring task**</span></span>

|<span data-ttu-id="c67fb-121">**Propriedade**</span><span class="sxs-lookup"><span data-stu-id="c67fb-121">**Property**</span></span>|<span data-ttu-id="c67fb-122">**Valor original**</span><span class="sxs-lookup"><span data-stu-id="c67fb-122">**Original Value**</span></span>|<span data-ttu-id="c67fb-123">**Valor atualizado**</span><span class="sxs-lookup"><span data-stu-id="c67fb-123">**Updated Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="c67fb-124">Task. StartDate</span><span class="sxs-lookup"><span data-stu-id="c67fb-124">Task.StartDate</span></span>  <br/> |<span data-ttu-id="c67fb-125">1º de janeiro de 2006</span><span class="sxs-lookup"><span data-stu-id="c67fb-125">January 1, 2006</span></span>  <br/> |<span data-ttu-id="c67fb-126">30 de outubro de 2006</span><span class="sxs-lookup"><span data-stu-id="c67fb-126">October 30, 2006</span></span>  <br/> |
|<span data-ttu-id="c67fb-127">Task. DueDate</span><span class="sxs-lookup"><span data-stu-id="c67fb-127">Task.DueDate</span></span>  <br/> |<span data-ttu-id="c67fb-128">3 de janeiro de 2006</span><span class="sxs-lookup"><span data-stu-id="c67fb-128">January 3, 2006</span></span>  <br/> |<span data-ttu-id="c67fb-129">1 de novembro de 2006</span><span class="sxs-lookup"><span data-stu-id="c67fb-129">November 1, 2006</span></span>  <br/> |
|<span data-ttu-id="c67fb-130">Task. rerecurrence. Range. StartDate</span><span class="sxs-lookup"><span data-stu-id="c67fb-130">Task.Recurrence.Range.StartDate</span></span>  <br/> |<span data-ttu-id="c67fb-131">26 de outubro de 2006</span><span class="sxs-lookup"><span data-stu-id="c67fb-131">October 26, 2006</span></span>  <br/> |<span data-ttu-id="c67fb-132">30 de outubro de 2006</span><span class="sxs-lookup"><span data-stu-id="c67fb-132">October 30, 2006</span></span>  <br/> |
   
<span data-ttu-id="c67fb-133">Por padrão, se uma pasta de destino não for especificada, os itens de tarefa serão criados na pasta tarefas.</span><span class="sxs-lookup"><span data-stu-id="c67fb-133">By default, if a destination folder is not specified, task items are created in the Tasks folder.</span></span>
  
### <a name="request-elements"></a><span data-ttu-id="c67fb-134">Elementos Request</span><span class="sxs-lookup"><span data-stu-id="c67fb-134">Request elements</span></span>

<span data-ttu-id="c67fb-135">Os seguintes elementos são usados na solicitação:</span><span class="sxs-lookup"><span data-stu-id="c67fb-135">The following elements are used in the request:</span></span>
  
- [<span data-ttu-id="c67fb-136">CreateItem</span><span class="sxs-lookup"><span data-stu-id="c67fb-136">CreateItem</span></span>](createitem.md)
    
- [<span data-ttu-id="c67fb-137">Itens (NonEmptyArrayOfAllItemsType)</span><span class="sxs-lookup"><span data-stu-id="c67fb-137">Items (NonEmptyArrayOfAllItemsType)</span></span>](items-nonemptyarrayofallitemstype.md)
    
- [<span data-ttu-id="c67fb-138">Tarefa</span><span class="sxs-lookup"><span data-stu-id="c67fb-138">Task</span></span>](task.md)
    
- [<span data-ttu-id="c67fb-139">Assunto</span><span class="sxs-lookup"><span data-stu-id="c67fb-139">Subject</span></span>](subject.md)
    
- [<span data-ttu-id="c67fb-140">DueDate</span><span class="sxs-lookup"><span data-stu-id="c67fb-140">DueDate</span></span>](duedate.md)
    
- [<span data-ttu-id="c67fb-141">Status</span><span class="sxs-lookup"><span data-stu-id="c67fb-141">Status</span></span>](status.md)
    
## <a name="successful-task-createitem-response"></a><span data-ttu-id="c67fb-142">Resposta CreateItem de tarefa bem-sucedida</span><span class="sxs-lookup"><span data-stu-id="c67fb-142">Successful Task CreateItem Response</span></span>

### <a name="description"></a><span data-ttu-id="c67fb-143">Descrição</span><span class="sxs-lookup"><span data-stu-id="c67fb-143">Description</span></span>

<span data-ttu-id="c67fb-144">O exemplo a seguir mostra uma resposta bem-sucedida à solicitação CreateItem.</span><span class="sxs-lookup"><span data-stu-id="c67fb-144">The following example shows a successful response to the CreateItem request.</span></span>
  
### <a name="code"></a><span data-ttu-id="c67fb-145">Código</span><span class="sxs-lookup"><span data-stu-id="c67fb-145">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/" 
               xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
               xmlns:xsd="http://www.w3.org/2001/XMLSchema">
  <soap:Header>
    <t:ServerVersionInfo MajorVersion="8" MinorVersion="0" MajorBuildNumber="653" MinorBuildNumber="0" 
                         xmlns:t="https://schemas.microsoft.com/exchange/services/2006/types"/>
  </soap:Header>
  <soap:Body>
    <CreateItemResponse xmlns:m="https://schemas.microsoft.com/exchange/services/2006/messages" 
                        xmlns:t="https://schemas.microsoft.com/exchange/services/2006/types" 
                        xmlns="https://schemas.microsoft.com/exchange/services/2006/messages">
      <m:ResponseMessages>
        <m:CreateItemResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:Items>
            <t:Task>
              <t:ItemId Id="AAAtAE=" ChangeKey="EwAAABYA"/>
            </t:Task>
          </m:Items>
        </m:CreateItemResponseMessage>
      </m:ResponseMessages>
    </CreateItemResponse>
  </soap:Body>
</soap:Envelope>
```

### <a name="successful-response-elements"></a><span data-ttu-id="c67fb-146">Elementos de resposta bem-sucedidos</span><span class="sxs-lookup"><span data-stu-id="c67fb-146">Successful response elements</span></span>

<span data-ttu-id="c67fb-147">Os seguintes elementos estão incluídos na resposta:</span><span class="sxs-lookup"><span data-stu-id="c67fb-147">The following elements are included in the response:</span></span>
  
- [<span data-ttu-id="c67fb-148">ServerVersionInfo</span><span class="sxs-lookup"><span data-stu-id="c67fb-148">ServerVersionInfo</span></span>](serverversioninfo.md)
    
- [<span data-ttu-id="c67fb-149">CreateItemResponse</span><span class="sxs-lookup"><span data-stu-id="c67fb-149">CreateItemResponse</span></span>](createitemresponse.md)
    
- [<span data-ttu-id="c67fb-150">ResponseMessages</span><span class="sxs-lookup"><span data-stu-id="c67fb-150">ResponseMessages</span></span>](responsemessages.md)
    
- [<span data-ttu-id="c67fb-151">CreateItemResponseMessage</span><span class="sxs-lookup"><span data-stu-id="c67fb-151">CreateItemResponseMessage</span></span>](createitemresponsemessage.md)
    
- [<span data-ttu-id="c67fb-152">ResponseCode</span><span class="sxs-lookup"><span data-stu-id="c67fb-152">ResponseCode</span></span>](responsecode.md)
    
- [<span data-ttu-id="c67fb-153">Itens (NonEmptyArrayOfAllItemsType)</span><span class="sxs-lookup"><span data-stu-id="c67fb-153">Items (NonEmptyArrayOfAllItemsType)</span></span>](items-nonemptyarrayofallitemstype.md)
    
- [<span data-ttu-id="c67fb-154">Tarefa</span><span class="sxs-lookup"><span data-stu-id="c67fb-154">Task</span></span>](task.md)
    
- [<span data-ttu-id="c67fb-155">ItemId</span><span class="sxs-lookup"><span data-stu-id="c67fb-155">ItemId</span></span>](itemid.md)
    
## <a name="see-also"></a><span data-ttu-id="c67fb-156">Confira também</span><span class="sxs-lookup"><span data-stu-id="c67fb-156">See also</span></span>



[<span data-ttu-id="c67fb-157">Operação CreateItem</span><span class="sxs-lookup"><span data-stu-id="c67fb-157">CreateItem operation</span></span>](createitem-operation.md)


[<span data-ttu-id="c67fb-158">Criando tarefas</span><span class="sxs-lookup"><span data-stu-id="c67fb-158">Creating Tasks</span></span>](https://msdn.microsoft.com/library/0ef97334-e8a0-4f67-a23a-dd9e2bbad49f%28Office.15%29.aspx)
  
[<span data-ttu-id="c67fb-159">Atualizando tarefas</span><span class="sxs-lookup"><span data-stu-id="c67fb-159">Updating Tasks</span></span>](https://msdn.microsoft.com/library/0a1bf360-d40c-4a99-929b-4c73a14394d5%28Office.15%29.aspx)
  
[<span data-ttu-id="c67fb-160">Excluir tarefas</span><span class="sxs-lookup"><span data-stu-id="c67fb-160">Deleting Tasks</span></span>](https://msdn.microsoft.com/library/a3d7e25f-8a35-4901-b1d9-d31f418ab340%28Office.15%29.aspx)

