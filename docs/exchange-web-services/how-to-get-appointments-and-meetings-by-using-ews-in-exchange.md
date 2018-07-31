---
title: Obtenha os compromissos e reuniões usando o EWS no Exchange
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
localization_priority: Normal
ms.assetid: 1bae582a-8cb3-4e77-be2a-7e107fad26fe
description: Saiba como obter compromissos e reuniões usando o EWS Managed API ou o EWS no Exchange.
ms.openlocfilehash: c78d70ca2266bd192b82f644d902ad8c958d2d4a
ms.sourcegitcommit: 9061fcf40c218ebe88911783f357b7df278846db
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/28/2018
ms.locfileid: "21353690"
---
# <a name="get-appointments-and-meetings-by-using-ews-in-exchange"></a><span data-ttu-id="23fa5-103">Obtenha os compromissos e reuniões usando o EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="23fa5-103">Get appointments and meetings by using EWS in Exchange</span></span>

<span data-ttu-id="23fa5-104">Saiba como obter compromissos e reuniões usando o EWS Managed API ou o EWS no Exchange.</span><span class="sxs-lookup"><span data-stu-id="23fa5-104">Learn how to get appointments and meetings by using the EWS Managed API or EWS in Exchange.</span></span>
  
<span data-ttu-id="23fa5-105">É possível recuperar compromissos e reuniões de uma pasta de calendário usando o método de API gerenciada de EWS [CalendarFolder.FindAppointments](http://msdn.microsoft.com/en-us/library/dd636179%28v=exchg.80%29.aspx) ou a operação de EWS [FindItem](http://msdn.microsoft.com/library/ebad6aae-16e7-44de-ae63-a95b24539729%28Office.15%29.aspx) .</span><span class="sxs-lookup"><span data-stu-id="23fa5-105">You can retrieve appointments and meetings from a calendar folder by using the [CalendarFolder.FindAppointments](http://msdn.microsoft.com/en-us/library/dd636179%28v=exchg.80%29.aspx) EWS Managed API method or the [FindItem](http://msdn.microsoft.com/library/ebad6aae-16e7-44de-ae63-a95b24539729%28Office.15%29.aspx) EWS operation.</span></span> 
  
## <a name="get-appointments-by-using-the-ews-managed-api"></a><span data-ttu-id="23fa5-106">Obtenha os compromissos usando a API gerenciada de EWS</span><span class="sxs-lookup"><span data-stu-id="23fa5-106">Get appointments by using the EWS Managed API</span></span>
<span data-ttu-id="23fa5-107"><a name="bk_retrieveappsEWSMA"> </a></span><span class="sxs-lookup"><span data-stu-id="23fa5-107"></span></span>

<span data-ttu-id="23fa5-108">O exemplo de código a seguir mostra como usar a API gerenciada de EWS para recuperar os compromissos do usuário que estão entre um especificados de início e hora de término.</span><span class="sxs-lookup"><span data-stu-id="23fa5-108">The following code example shows how to use the EWS Managed API to retrieve a user's appointments that fall between a specified start and end time.</span></span>
  
```cs
       // Initialize values for the start and end times, and the number of appointments to retrieve.
            DateTime startDate = DateTime.Now;
            DateTime endDate = startDate.AddDays(30);
            const int NUM_APPTS = 5;
            // Initialize the calendar folder object with only the folder ID. 
            CalendarFolder calendar = CalendarFolder.Bind(service, WellKnownFolderName.Calendar, new PropertySet());
            // Set the start and end time and number of appointments to retrieve.
            CalendarView cView = new CalendarView(startDate, endDate, NUM_APPTS);
            // Limit the properties returned to the appointment's subject, start time, and end time.
            cView.PropertySet = new PropertySet(AppointmentSchema.Subject, AppointmentSchema.Start, AppointmentSchema.End);
            // Retrieve a collection of appointments by using the calendar view.
            FindItemsResults<Appointment> appointments = calendar.FindAppointments(cView);
            Console.WriteLine("\nThe first " + NUM_APPTS + " appointments on your calendar from " + startDate.Date.ToShortDateString() + 
                              " to " + endDate.Date.ToShortDateString() + " are: \n");
            
            foreach (Appointment a in appointments)
            {
                Console.Write("Subject: " + a.Subject.ToString() + " ");
                Console.Write("Start: " + a.Start.ToString() + " ");
                Console.Write("End: " + a.End.ToString());
                Console.WriteLine();
            }

```

<br/>

<span data-ttu-id="23fa5-109">A seguir é a saída do código de exemplo.</span><span class="sxs-lookup"><span data-stu-id="23fa5-109">The following is the output from the code example.</span></span>
  
```text
The first five appointments on your calendar from 8/21/2013 to 9/20/2013 are: 
  
Subject: Contoso devs team meeting Start: 8/21/2013 12:30:00 PM End: 8/21/2013 1:00:00 PM
  
Subject: Daily status meeting Start: 8/21/2013 1:00:00 PM End: 8/21/2013 2:00:00 PM
  
Subject: Lunch with sales team Start: 8/21/2013 2:30:00 PM End: 8/21/2013 3:30:00 PM
  
Subject: Tennis at the club Start: 8/22/2013 11:00:00 AM End: 8/22/2013 12:00:00 PM
  
Subject: Online training webcast: 8/22/2013 2:00:00 PM End: 8/22/2013 3:00:00 PM
```

## <a name="get-appointments-by-using-ews"></a><span data-ttu-id="23fa5-110">Obter compromissos usando o EWS</span><span class="sxs-lookup"><span data-stu-id="23fa5-110">Get appointments by using EWS</span></span>
<span data-ttu-id="23fa5-111"><a name="bk_xml"> </a></span><span class="sxs-lookup"><span data-stu-id="23fa5-111"></span></span>

<span data-ttu-id="23fa5-112">O XML a seguir mostra uma solicitação de operação [GetFolder](http://msdn.microsoft.com/library/355bcf93-dc71-4493-b177-622afac5fdb9%28Office.15%29.aspx) para retornar a ID de uma pasta para a operação [FindItem](http://msdn.microsoft.com/library/ebad6aae-16e7-44de-ae63-a95b24539729%28Office.15%29.aspx) .</span><span class="sxs-lookup"><span data-stu-id="23fa5-112">The following XML shows a [GetFolder](http://msdn.microsoft.com/library/355bcf93-dc71-4493-b177-622afac5fdb9%28Office.15%29.aspx) operation request to return a folder ID for the [FindItem](http://msdn.microsoft.com/library/ebad6aae-16e7-44de-ae63-a95b24539729%28Office.15%29.aspx) operation.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
       xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
       xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" 
       xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2007_SP1" />
  </soap:Header>
  <soap:Body>
    <m:GetFolder>
      <m:FolderShape>
        <t:BaseShape>IdOnly</t:BaseShape>
      </m:FolderShape>
      <m:FolderIds>
        <t:DistinguishedFolderId Id="calendar" />
      </m:FolderIds>
    </m:GetFolder>
  </soap:Body>
</soap:Envelope>
```

<br/>

<span data-ttu-id="23fa5-113">O XML a seguir mostra a resposta **GetFolder** .</span><span class="sxs-lookup"><span data-stu-id="23fa5-113">The following XML shows the **GetFolder** response.</span></span> <span data-ttu-id="23fa5-114">Observe que os atributos **FolderID** e **ChangeKey** são reduzidos para melhorar a legibilidade.</span><span class="sxs-lookup"><span data-stu-id="23fa5-114">Note that the **FolderID** and **ChangeKey** attributes are shortened for readability.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<s:Envelope xmlns:s="http://schemas.xmlsoap.org/soap/envelope/">
  <s:Header>
    <h:ServerVersionInfo MajorVersion="15" MinorVersion="0" MajorBuildNumber="731" MinorBuildNumber="10" Version="V2_3" 
 xmlns:h="http://schemas.microsoft.com/exchange/services/2006/types" 
 xmlns="http://schemas.microsoft.com/exchange/services/2006/types" 
 xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" />
  </s:Header>
  <s:Body xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <m:GetFolderResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
 xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
      <m:ResponseMessages>
        <m:GetFolderResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:Folders>
            <t:CalendarFolder>
              <t:FolderId Id="AAMk" ChangeKey="AgAA" />
            </t:CalendarFolder>
          </m:Folders>
        </m:GetFolderResponseMessage>
      </m:ResponseMessages>
    </m:GetFolderResponse>
  </s:Body>
</s:Envelope>
```

<br/>

<span data-ttu-id="23fa5-115">O XML a seguir mostra a solicitação de **FindItem** usada para retornar os compromissos solicitados.</span><span class="sxs-lookup"><span data-stu-id="23fa5-115">The following XML shows the **FindItem** request used to return the requested appointments.</span></span> <span data-ttu-id="23fa5-116">Observe que os atributos **FolderID** e **ChangeKey** são reduzidos para melhorar a legibilidade.</span><span class="sxs-lookup"><span data-stu-id="23fa5-116">Note that the **FolderID** and **ChangeKey** attributes are shortened for readability.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
       xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
       xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" 
       xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2007_SP1" />
  </soap:Header>
  <soap:Body>
    <m:FindItem Traversal="Shallow">
      <m:ItemShape>
        <t:BaseShape>IdOnly</t:BaseShape>
        <t:AdditionalProperties>
          <t:FieldURI FieldURI="item:Subject" />
          <t:FieldURI FieldURI="calendar:Start" />
          <t:FieldURI FieldURI="calendar:End" />
        </t:AdditionalProperties>
      </m:ItemShape>
      <m:CalendarView MaxEntriesReturned="5" StartDate="2013-08-21T17:30:24.127Z" EndDate="2013-09-20T17:30:24.127Z" />
      <m:ParentFolderIds>
        <t:FolderId Id="AAMk" ChangeKey="AgAA" />
      </m:ParentFolderIds>
    </m:FindItem>
  </soap:Body>
</soap:Envelope>
```

<br/>

<span data-ttu-id="23fa5-117">O XML a seguir mostra a resposta **FindItem** .</span><span class="sxs-lookup"><span data-stu-id="23fa5-117">The following XML shows the **FindItem** response.</span></span> <span data-ttu-id="23fa5-118">Observe que os atributos **ItemID** e **ChangeKey** são reduzidos para melhorar a legibilidade.</span><span class="sxs-lookup"><span data-stu-id="23fa5-118">Note that the **ItemID** and **ChangeKey** attributes are shortened for readability.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<s:Envelope xmlns:s="http://schemas.xmlsoap.org/soap/envelope/">
  <s:Header>
    <h:ServerVersionInfo MajorVersion="15" MinorVersion="0" MajorBuildNumber="731" MinorBuildNumber="10" Version="V2_3" 
 xmlns:h="http://schemas.microsoft.com/exchange/services/2006/types" 
 xmlns="http://schemas.microsoft.com/exchange/services/2006/types" 
 xmlns:xsd="http://www.w3.org/2001/XMLSchema" 
 xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" />
  </s:Header>
  <s:Body xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <m:FindItemResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
      <m:ResponseMessages>
        <m:FindItemResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:RootFolder TotalItemsInView="33" IncludesLastItemInRange="false">
            <t:Items>
              <t:CalendarItem>
                <t:ItemId Id="AAMk" ChangeKey="DwAA" />
                <t:Subject>Contoso devs team meeting</t:Subject>
                <t:Start>2013-08-21T19:30:00Z</t:Start>
                <t:End>2013-08-21T20:00:00Z</t:End>
              </t:CalendarItem>
              <t:CalendarItem>
                <t:ItemId Id="AAMk" ChangeKey="DwAA" />
                <t:Subject>Daily status meeting</t:Subject>
                <t:Start>2013-08-21T20:00:00Z</t:Start>
                <t:End>2013-08-21T21:00:00Z</t:End>
              </t:CalendarItem>
              <t:CalendarItem>
                <t:ItemId Id="AAMk" ChangeKey="DwAA" />
                <t:Subject>Lunch with sales team</t:Subject>
                <t:Start>2013-08-21T21:30:00Z</t:Start>
                <t:End>2013-08-21T22:30:00Z</t:End>
              </t:CalendarItem>
              <t:CalendarItem>
                <t:ItemId Id="AAMk" ChangeKey="DwAA" />
                <t:Subject>Tennis at the club</t:Subject>
                <t:Start>2013-08-22T18:00:00Z</t:Start>
                <t:End>2013-08-22T19:00:00Z</t:End>
              </t:CalendarItem>
              <t:CalendarItem>
                <t:ItemId Id="AAMkA" ChangeKey="DwAA" />
                <t:Subject>Online training webcast</t:Subject>
                <t:Start>2013-08-22T21:00:00Z</t:Start>
                <t:End>2013-08-22T22:00:00Z</t:End>
              </t:CalendarItem>
            </t:Items>
          </m:RootFolder>
        </m:FindItemResponseMessage>
      </m:ResponseMessages>
    </m:FindItemResponse>
  </s:Body>
</s:Envelope>
```

## <a name="recurring-meetings-and-the-calendar-view"></a><span data-ttu-id="23fa5-119">Reuniões recorrentes e o modo de exibição de calendário</span><span class="sxs-lookup"><span data-stu-id="23fa5-119">Recurring meetings and the calendar view</span></span>
<span data-ttu-id="23fa5-120"><a name="bk_recurring"> </a></span><span class="sxs-lookup"><span data-stu-id="23fa5-120"></span></span>

<span data-ttu-id="23fa5-121">A pasta de calendário é um pouco diferente de outras pastas em uma caixa de correio porque ocorrências em uma série recorrente e exceções a uma série recorrente não são reais itens na caixa de correio, mas em vez disso, são armazenadas internamente como anexos de um mestre recorrente.</span><span class="sxs-lookup"><span data-stu-id="23fa5-121">The calendar folder is a little different from other folders in a mailbox because occurrences in a recurring series and exceptions to a recurring series are not actual items in the mailbox, but rather are stored internally as attachments to a recurring master.</span></span> <span data-ttu-id="23fa5-122">Isso significa que, embora você pode criar uma solicitação EWS que retorna valores entre um conjunto de **início** e **fim** valores usando um da API gerenciada de EWS **FindItems** sobrecarregar métodos, como [ExchangeService.FindItems](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.exchangeservice.finditems%28v=exchg.80%29.aspx) ou o EWS [ FindItem](http://msdn.microsoft.com/library/ebad6aae-16e7-44de-ae63-a95b24539729%28Office.15%29.aspx) operação, EWS não aparecerá no índice de anexo de cada item de calendário para encontrar exceções e ocorrências.</span><span class="sxs-lookup"><span data-stu-id="23fa5-122">This means that although you can create an EWS request that returns values between a set of **start** and **end** values by using one of the EWS Managed API **FindItems** overload methods, such as [ExchangeService.FindItems](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.exchangeservice.finditems%28v=exchg.80%29.aspx) or the EWS [FindItem](http://msdn.microsoft.com/library/ebad6aae-16e7-44de-ae63-a95b24539729%28Office.15%29.aspx) operation, EWS would not look through the attachment table of every calendar item to find exceptions and occurrences.</span></span> 
  
<span data-ttu-id="23fa5-123">Em vez disso, o que você realmente deseja fazer é algo semelhante a aplicação de uma *exibição de dados* em uma união de duas tabelas do SQL, usando um objeto [CalendarView](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.calendarview%28v=exchg.80%29.aspx) .</span><span class="sxs-lookup"><span data-stu-id="23fa5-123">Instead, what you really want to do is something akin to applying a  *Dataview*  onto a union of two SQL tables, using a [CalendarView](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.calendarview%28v=exchg.80%29.aspx) object.</span></span> <span data-ttu-id="23fa5-124">Observe que por motivos de desempenho, recomendamos que você use a propriedade [PropertySet](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.propertyset%28v=exchg.80%29.aspx) limitar o tamanho da resposta, indicando o número de compromissos ou reuniões a que serem retornadas, bem como as propriedades específicas que você deseja.</span><span class="sxs-lookup"><span data-stu-id="23fa5-124">Note that for performance reasons, we recommend that you use the [PropertySet](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.propertyset%28v=exchg.80%29.aspx) property to limit the size of the response by indicating the number of appointments or meetings you want returned, as well as the specific properties you want.</span></span> 
  
## <a name="see-also"></a><span data-ttu-id="23fa5-125">Confira também</span><span class="sxs-lookup"><span data-stu-id="23fa5-125">See also</span></span>
<span data-ttu-id="23fa5-126"><a name="bk_additional"> </a></span><span class="sxs-lookup"><span data-stu-id="23fa5-126"></span></span>

- [<span data-ttu-id="23fa5-127">Calendários e EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="23fa5-127">Calendars and EWS in Exchange</span></span>](calendars-and-ews-in-exchange.md)   
- [<span data-ttu-id="23fa5-128">Criar compromissos e reuniões usando o EWS no Exchange 2013</span><span class="sxs-lookup"><span data-stu-id="23fa5-128">Create appointments and meetings by using EWS in Exchange 2013</span></span>](how-to-create-appointments-and-meetings-by-using-ews-in-exchange-2013.md)  
- [<span data-ttu-id="23fa5-129">Atualizar compromissos e reuniões usando o EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="23fa5-129">Update appointments and meetings by using EWS in Exchange</span></span>](how-to-update-appointments-and-meetings-by-using-ews-in-exchange.md)  
- [<span data-ttu-id="23fa5-130">Excluir compromissos e cancelar reuniões usando o EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="23fa5-130">Delete appointments and cancel meetings by using EWS in Exchange</span></span>](how-to-delete-appointments-and-cancel-meetings-by-using-ews-in-exchange.md) 
- [<span data-ttu-id="23fa5-131">Develop web service clients for Exchange</span><span class="sxs-lookup"><span data-stu-id="23fa5-131">Develop web service clients for Exchange</span></span>](develop-web-service-clients-for-exchange.md)
    

