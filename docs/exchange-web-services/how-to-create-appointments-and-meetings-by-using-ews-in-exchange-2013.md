---
title: Criar compromissos e reuniões usando o EWS no Exchange 2013
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
localization_priority: Normal
ms.assetid: fdea70a4-9267-4e5d-9152-b749e2acc3b0
description: Saiba como criar compromissos e reuniões usando o EWS Managed API ou o EWS no Exchange.
ms.openlocfilehash: 1c840fac2ecca9fb51a28044dfac6299cb4fc038
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19750708"
---
# <a name="create-appointments-and-meetings-by-using-ews-in-exchange-2013"></a><span data-ttu-id="d4235-103">Criar compromissos e reuniões usando o EWS no Exchange 2013</span><span class="sxs-lookup"><span data-stu-id="d4235-103">Create appointments and meetings by using EWS in Exchange 2013</span></span>

<span data-ttu-id="d4235-104">Saiba como criar compromissos e reuniões usando o EWS Managed API ou o EWS no Exchange.</span><span class="sxs-lookup"><span data-stu-id="d4235-104">Learn how to create appointments and meetings by using the EWS Managed API or EWS in Exchange.</span></span>
  
<span data-ttu-id="d4235-105">A diferença essencial entre reuniões e compromissos é que reuniões possuem participantes, e não de compromissos.</span><span class="sxs-lookup"><span data-stu-id="d4235-105">The essential difference between meetings and appointments is that meetings have attendees, and appointments don't.</span></span> <span data-ttu-id="d4235-106">Compromissos e reuniões podem ser instâncias única ou parte de uma série recorrente, mas como compromissos não incluem os participantes, salas ou recursos, eles não exigem uma mensagem a ser enviada.</span><span class="sxs-lookup"><span data-stu-id="d4235-106">Both appointments and meetings can be single instances or part of a recurring series, but because appointments don't include attendees, rooms, or resources, they do not require a message to be sent.</span></span> <span data-ttu-id="d4235-107">Internamente, o Exchange usa o mesmo objeto para reuniões e compromissos.</span><span class="sxs-lookup"><span data-stu-id="d4235-107">Internally, Exchange uses the same object for both meetings and appointments.</span></span> <span data-ttu-id="d4235-108">Use a API gerenciada de EWS [classe de compromisso](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.appointment%28v=exchg.80%29.aspx) ou o elemento do EWS [CalendarItem](http://msdn.microsoft.com/library/Title Topic ID Project Name Writer Editor Publish Preview.aspx) para trabalhar com compromissos e reuniões.</span><span class="sxs-lookup"><span data-stu-id="d4235-108">You use the EWS Managed API [Appointment class](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.appointment%28v=exchg.80%29.aspx) or the EWS [CalendarItem](http://msdn.microsoft.com/library/Title Topic ID Project Name Writer Editor Publish Preview.aspx) element to work with meetings and appointments.</span></span> 
  
<span data-ttu-id="d4235-109">**Tabela 1. Métodos de API gerenciada de EWS e operações de EWS para trabalhar com os compromissos e reuniões**</span><span class="sxs-lookup"><span data-stu-id="d4235-109">**Table 1. EWS Managed API methods and EWS operations for working with appointments and meetings**</span></span>

|<span data-ttu-id="d4235-110">**Método API gerenciada de EWS**</span><span class="sxs-lookup"><span data-stu-id="d4235-110">**EWS Managed API method**</span></span>|<span data-ttu-id="d4235-111">**Operação do EWS**</span><span class="sxs-lookup"><span data-stu-id="d4235-111">**EWS operation**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="d4235-112">Appointment.Save</span><span class="sxs-lookup"><span data-stu-id="d4235-112">Appointment.Save</span></span>](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.appointment.save%28v=exchg.80%29.aspx) <br/> |[<span data-ttu-id="d4235-113">Operação CreateItem (item de calendário)</span><span class="sxs-lookup"><span data-stu-id="d4235-113">CreateItem operation (calendar item)</span></span>](http://msdn.microsoft.com/library/aa4a7c94-f668-4bd2-8079-c855f6ab17e1%28Office.15%29.aspx) <br/> |
|[<span data-ttu-id="d4235-114">Item.Bind</span><span class="sxs-lookup"><span data-stu-id="d4235-114">Item.Bind</span></span>](http://msdn.microsoft.com/en-us/library/dd634410%28v=exchg.80%29.aspx) <br/> |[<span data-ttu-id="d4235-115">Operação GetItem (item de calendário)</span><span class="sxs-lookup"><span data-stu-id="d4235-115">GetItem operation (calendar item)</span></span>](http://msdn.microsoft.com/library/a41c29c9-c4e6-4aa4-8e28-ccb0b478fee8%28Office.15%29.aspx) <br/> |
   
## <a name="create-an-appointment-by-using-the-ews-managed-api"></a><span data-ttu-id="d4235-116">Criar um compromisso usando a API gerenciada de EWS</span><span class="sxs-lookup"><span data-stu-id="d4235-116">Create an appointment by using the EWS Managed API</span></span>
<span data-ttu-id="d4235-117"><a name="bk_CreateApptEWSMA"> </a></span><span class="sxs-lookup"><span data-stu-id="d4235-117"></span></span>

<span data-ttu-id="d4235-118">O exemplo de código a seguir mostra como usar o [objeto de compromisso](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.appointment%28v=exchg.80%29.aspx) para criar um compromisso, o método [Save](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.appointment.save%28v=exchg.80%29.aspx) para salvá-lo à sua pasta de calendário e o método [Item.Bind](http://msdn.microsoft.com/en-us/library/dd634410%28v=exchg.80%29.aspx) para verificar se o compromisso foi criado.</span><span class="sxs-lookup"><span data-stu-id="d4235-118">The following code example shows how to use the [Appointment object](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.appointment%28v=exchg.80%29.aspx) to create an appointment, the [Save](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.appointment.save%28v=exchg.80%29.aspx) method to save it to your calendar folder, and the [Item.Bind](http://msdn.microsoft.com/en-us/library/dd634410%28v=exchg.80%29.aspx) method to verify that the appointment was created.</span></span> 
  
<span data-ttu-id="d4235-119">Este exemplo pressupõe que você tenha autenticado com um servidor Exchange e adquiriu um objeto [ExchangeService](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.exchangeservice%28v=exchg.80%29.aspx) denominado **service**.</span><span class="sxs-lookup"><span data-stu-id="d4235-119">This example assumes that you have authenticated to an Exchange server and have acquired an [ExchangeService](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.exchangeservice%28v=exchg.80%29.aspx) object named **service**.</span></span> 
  
```cs
Appointment appointment = new Appointment(service);
// Set the properties on the appointment object to create the appointment.
appointment.Subject = "Tennis lesson";
appointment.Body = "Focus on backhand this week.";
appointment.Start = DateTime.Now.AddDays(2);
appointment.End = appointment.Start.AddHours(1);
appointment.Location = "Tennis club";
appointment.ReminderDueBy = DateTime.Now;
// Save the appointment to your calendar.
appointment.Save(SendInvitationsMode.SendToNone);
// Verify that the appointment was created by using the appointment's item ID.
Item item = Item.Bind(service, appointment.Id, new PropertySet(ItemSchema.Subject));
Console.WriteLine("\nAppointment created: " + item.Subject + "\n");

```

<span data-ttu-id="d4235-120">Depois de configurar as propriedades no objeto de compromisso, salve o compromisso para a pasta de calendário usando o método [Save](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.appointment.save%28v=exchg.80%29.aspx) do objeto compromisso.</span><span class="sxs-lookup"><span data-stu-id="d4235-120">After setting the properties on the appointment object, you save the appointment to the calendar folder by using the appointment object's [Save](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.appointment.save%28v=exchg.80%29.aspx) method.</span></span> 
  
<span data-ttu-id="d4235-121">Observe que a etapa de verificação, você usa a [Id](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.item.id%28v=exchg.80%29.aspx) associada ao compromisso do item para verificar se o compromisso está na pasta Calendário.</span><span class="sxs-lookup"><span data-stu-id="d4235-121">Note that in the verification step, you use the item [Id](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.item.id%28v=exchg.80%29.aspx) associated with the appointment to verify that the appointment is in the calendar folder.</span></span> <span data-ttu-id="d4235-122">Como prática recomendada, limitar as propriedades retornadas pelo servidor para que apenas o que você precisa — neste caso, o compromisso do assunto.</span><span class="sxs-lookup"><span data-stu-id="d4235-122">As a best practice, limit the properties returned by the server to only what you need — in this case, the appointment's subject.</span></span> 
  
## <a name="create-an-appointment-by-using-ews"></a><span data-ttu-id="d4235-123">Criar um compromisso usando o EWS</span><span class="sxs-lookup"><span data-stu-id="d4235-123">Create an appointment by using EWS</span></span>
<span data-ttu-id="d4235-124"><a name="bk_CreateApptEWS"> </a></span><span class="sxs-lookup"><span data-stu-id="d4235-124"></span></span>

<span data-ttu-id="d4235-125">A solicitação e a resposta XML nos exemplos a seguir correspondem às chamadas feitas pelo código do API gerenciada de EWS em [criar um compromisso usando a API gerenciada de EWS](#bk_CreateApptEWSMA).</span><span class="sxs-lookup"><span data-stu-id="d4235-125">The request and response XML in the following examples correspond to calls made by the EWS Managed API code in [Create an appointment by using the EWS Managed API](#bk_CreateApptEWSMA).</span></span> <span data-ttu-id="d4235-126">A solicitação e a resposta XML que verifica se os itens de compromisso estão na pasta de calendário são mostrados também.</span><span class="sxs-lookup"><span data-stu-id="d4235-126">The request and response XML that verifies that the appointment items are in the calendar folder are shown as well.</span></span>
  
<span data-ttu-id="d4235-127">O exemplo a seguir mostra a solicitação XML quando você usar a operação [CreateItem](http://msdn.microsoft.com/library/aa4a7c94-f668-4bd2-8079-c855f6ab17e1%28Office.15%29.aspx) para criar um compromisso.</span><span class="sxs-lookup"><span data-stu-id="d4235-127">The following example shows the request XML when you use the [CreateItem](http://msdn.microsoft.com/library/aa4a7c94-f668-4bd2-8079-c855f6ab17e1%28Office.15%29.aspx) operation to create an appointment.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
       xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
       xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" 
       xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2007_SP1" />
    <t:TimeZoneContext>
      <t:TimeZoneDefinition Id="Pacific Standard Time" />
    </t:TimeZoneContext>
  </soap:Header>
  <soap:Body>
    <m:CreateItem SendMeetingInvitations="SendToNone">
      <m:Items>
        <t:CalendarItem>
          <t:Subject>Tennis lesson</t:Subject>
          <t:Body BodyType="HTML">Focus on backhand this week.</t:Body>
          <t:ReminderDueBy>2013-09-19T14:37:10.732-07:00</t:ReminderDueBy>
          <t:Start>2013-09-21T19:00:00.000Z</t:Start>
          <t:End>2013-09-21T20:00:00.000Z</t:End>
          <t:Location>Tennis club</t:Location>
          <t:MeetingTimeZone TimeZoneName="Pacific Standard Time" />
        </t:CalendarItem>
      </m:Items>
    </m:CreateItem>
  </soap:Body>
</soap:Envelope>
```

 <span data-ttu-id="d4235-128">O exemplo a seguir mostra a resposta XML retornada pela operação de **CreateItem** .</span><span class="sxs-lookup"><span data-stu-id="d4235-128">The following example shows the response XML that is returned by the **CreateItem** operation.</span></span> 
  
> [!NOTE]
> <span data-ttu-id="d4235-129">Os atributos **ItemId** e **ChangeKey** foram diminuídos para melhorar a legibilidade.</span><span class="sxs-lookup"><span data-stu-id="d4235-129">The **ItemId** and **ChangeKey** attributes have been shortened for readability.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<s:Envelope xmlns:s="http://schemas.xmlsoap.org/soap/envelope/">
  <s:Header>
    <h:ServerVersionInfo MajorVersion="15" MinorVersion="0" MajorBuildNumber="775" MinorBuildNumber="7" Version="V2_4" 
 xmlns:h="http://schemas.microsoft.com/exchange/services/2006/types" 
 xmlns="http://schemas.microsoft.com/exchange/services/2006/types" 
 xmlns:xsd="http://www.w3.org/2001/XMLSchema" 
 xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" />
  </s:Header>
  <s:Body xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <m:CreateItemResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
  xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
      <m:ResponseMessages>
        <m:CreateItemResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:Items>
            <t:CalendarItem>
              <t:ItemId Id="AAMkA" ChangeKey="DwAAA" />
            </t:CalendarItem>
          </m:Items>
        </m:CreateItemResponseMessage>
      </m:ResponseMessages>
    </m:CreateItemResponse>
  </s:Body>
</s:Envelope>

```

<span data-ttu-id="d4235-130">O exemplo a seguir mostra a solicitação XML que é gerado quando você usar a operação de [GetItem](http://msdn.microsoft.com/library/a41c29c9-c4e6-4aa4-8e28-ccb0b478fee8%28Office.15%29.aspx) para verificar se o compromisso foi criado.</span><span class="sxs-lookup"><span data-stu-id="d4235-130">The following example shows the request XML that is generated when you use the [GetItem](http://msdn.microsoft.com/library/a41c29c9-c4e6-4aa4-8e28-ccb0b478fee8%28Office.15%29.aspx) operation to verify that the appointment was created.</span></span> 
  
> [!NOTE]
> <span data-ttu-id="d4235-131">Os atributos **ItemId** e **ChangeKey** foram diminuídos para melhorar a legibilidade.</span><span class="sxs-lookup"><span data-stu-id="d4235-131">The **ItemId** and **ChangeKey** attributes have been shortened for readability.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
       xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
       xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" 
       xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2007_SP1" />
    <t:TimeZoneContext>
      <t:TimeZoneDefinition Id="Pacific Standard Time" />
    </t:TimeZoneContext>
  </soap:Header>
  <soap:Body>
    <m:GetItem>
      <m:ItemShape>
        <t:BaseShape>IdOnly</t:BaseShape>
        <t:AdditionalProperties>
          <t:FieldURI FieldURI="item:Subject" />
        </t:AdditionalProperties>
      </m:ItemShape>
      <m:ItemIds>
        <t:ItemId Id="AAMkA" ChangeKey="DwAAA" />
      </m:ItemIds>
    </m:GetItem>
  </soap:Body>
</soap:Envelope>

```

 <span data-ttu-id="d4235-132">O exemplo a seguir mostra a resposta XML retornada pela operação de **GetItem** .</span><span class="sxs-lookup"><span data-stu-id="d4235-132">The following example shows the response XML that is returned by the **GetItem** operation.</span></span> 
  
> [!NOTE]
> <span data-ttu-id="d4235-133">Os atributos **ItemId** e **ChangeKey** foram diminuídos para melhorar a legibilidade.</span><span class="sxs-lookup"><span data-stu-id="d4235-133">The **ItemId** and **ChangeKey** attributes have been shortened for readability.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<s:Envelope xmlns:s="http://schemas.xmlsoap.org/soap/envelope/">
  <s:Header>
    <h:ServerVersionInfo MajorVersion="15" MinorVersion="0" MajorBuildNumber="775" MinorBuildNumber="7" Version="V2_4" 
 xmlns:h="http://schemas.microsoft.com/exchange/services/2006/types" 
 xmlns="http://schemas.microsoft.com/exchange/services/2006/types" 
 xmlns:xsd="http://www.w3.org/2001/XMLSchema" 
 xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" />
  </s:Header>
  <s:Body xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <m:GetItemResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
      <m:ResponseMessages>
        <m:GetItemResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:Items>
            <t:CalendarItem>
              <t:ItemId Id="AAMkA" ChangeKey="DwAAA" />
              <t:Subject>Tennis lesson</t:Subject>
            </t:CalendarItem>
          </m:Items>
        </m:GetItemResponseMessage>
      </m:ResponseMessages>
    </m:GetItemResponse>
  </s:Body>
</s:Envelope>
```

## <a name="create-a-meeting-by-using-the-ews-managed-api"></a><span data-ttu-id="d4235-134">Criar uma reunião usando a API gerenciada de EWS</span><span class="sxs-lookup"><span data-stu-id="d4235-134">Create a meeting by using the EWS Managed API</span></span>
<span data-ttu-id="d4235-135"><a name="bk_CreateMtgEWSMA"> </a></span><span class="sxs-lookup"><span data-stu-id="d4235-135"></span></span>

<span data-ttu-id="d4235-136">Quando você cria uma reunião, além de salvar um item na pasta de calendário, também, normalmente você deseja enviar solicitações de reunião a participantes.</span><span class="sxs-lookup"><span data-stu-id="d4235-136">When you create a meeting, in addition to saving an item to the calendar folder, you also typically want to send meeting requests to attendees.</span></span> <span data-ttu-id="d4235-137">O exemplo de código a seguir mostra como criar uma reunião e enviar solicitações de reunião.</span><span class="sxs-lookup"><span data-stu-id="d4235-137">The following code example shows how to create a meeting and send meeting requests.</span></span>
  
<span data-ttu-id="d4235-138">Este exemplo pressupõe que você tenha autenticado com um servidor Exchange e adquiriu um objeto [ExchangeService](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.exchangeservice%28v=exchg.80%29.aspx) denominado **service**.</span><span class="sxs-lookup"><span data-stu-id="d4235-138">This example assumes that you have authenticated to an Exchange server and have acquired an [ExchangeService](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.exchangeservice%28v=exchg.80%29.aspx) object named **service**.</span></span> 
  
```cs
Appointment meeting = new Appointment(service);
// Set the properties on the meeting object to create the meeting.
meeting.Subject = "Team building exercise";
meeting.Body = "Let's learn to really work as a team and then have lunch!";
meeting.Start = DateTime.Now.AddDays(2);            
meeting.End = meeting.Start.AddHours(4);
meeting.Location = "Conference Room 12";
meeting.RequiredAttendees.Add("Mack@contoso.com");
meeting.RequiredAttendees.Add("Sadie@contoso.com");
meeting.OptionalAttendees.Add("Magdalena@contoso.com");
meeting.ReminderMinutesBeforeStart = 60;
// Save the meeting to the Calendar folder and send the meeting request.
meeting.Save(SendInvitationsMode.SendToAllAndSaveCopy);
// Verify that the meeting was created.
Item item = Item.Bind(service, meeting.Id, new PropertySet(ItemSchema.Subject));
Console.WriteLine("\nMeeting created: " + item.Subject + "\n");

```

<span data-ttu-id="d4235-139">Depois de configurar as propriedades no objeto de [compromisso](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.appointment%28v=exchg.80%29.aspx) , salve a reunião para a pasta de calendário usando o método [Save](http://msdn.microsoft.com/en-us/library/dd635394%28v=exchg.80%29.aspx) .</span><span class="sxs-lookup"><span data-stu-id="d4235-139">After setting the properties on the [Appointment](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.appointment%28v=exchg.80%29.aspx) object, save the meeting to your calendar folder by using the [Save](http://msdn.microsoft.com/en-us/library/dd635394%28v=exchg.80%29.aspx) method.</span></span> <span data-ttu-id="d4235-140">Quando você definir o valor de enumeração [SendInvitationsMode](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.sendinvitationsmode%28v=exchg.80%29.aspx) como **SendOnlyToAll** ou **SendToAllAndSaveCopy**, os convites serão enviadas aos participantes.</span><span class="sxs-lookup"><span data-stu-id="d4235-140">When you set the [SendInvitationsMode](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.sendinvitationsmode%28v=exchg.80%29.aspx) enumeration value to **SendOnlyToAll** or **SendToAllAndSaveCopy**, invitations are sent to attendees.</span></span>
  
<span data-ttu-id="d4235-141">Use o item [Id](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.item.id%28v=exchg.80%29.aspx) associada a reunião para verificar que ele foi salvo na pasta de calendário.</span><span class="sxs-lookup"><span data-stu-id="d4235-141">Use the item [Id](http://msdn.microsoft.com/en-us/library/microsoft.exchange.webservices.data.item.id%28v=exchg.80%29.aspx) associated with the meeting to verify that it was saved in the calendar folder.</span></span> <span data-ttu-id="d4235-142">Como prática recomendada, limite as propriedades retornadas pelo servidor para que apenas o que você precisa - nesse caso, assunto da reunião.</span><span class="sxs-lookup"><span data-stu-id="d4235-142">As a best practice, limit the properties returned by the server to only what you need - in this case, the meeting's subject.</span></span> 
  
## <a name="create-a-meeting-by-using-ews"></a><span data-ttu-id="d4235-143">Criar uma reunião usando o EWS</span><span class="sxs-lookup"><span data-stu-id="d4235-143">Create a meeting by using EWS</span></span>
<span data-ttu-id="d4235-144"><a name="bk_CreateMtgEWS"> </a></span><span class="sxs-lookup"><span data-stu-id="d4235-144"></span></span>

<span data-ttu-id="d4235-145">A solicitação e a resposta XML nos exemplos a seguir correspondem às chamadas feitas pelo código do API gerenciada de EWS em [criar uma reunião usando a API gerenciada de EWS](#bk_CreateMtgEWSMA).</span><span class="sxs-lookup"><span data-stu-id="d4235-145">The request and response XML in the following examples correspond to calls made by the EWS Managed API code in [Create a meeting by using the EWS Managed API](#bk_CreateMtgEWSMA).</span></span> <span data-ttu-id="d4235-146">A solicitação e a resposta XML que verifica se os itens de reunião estão na pasta de calendário são mostrados também.</span><span class="sxs-lookup"><span data-stu-id="d4235-146">The request and response XML that verifies that the meeting items are in the calendar folder are shown as well.</span></span>
  
<span data-ttu-id="d4235-147">O exemplo a seguir mostra a solicitação XML quando você usar a operação [CreateItem](http://msdn.microsoft.com/library/aa4a7c94-f668-4bd2-8079-c855f6ab17e1%28Office.15%29.aspx) para criar uma reunião.</span><span class="sxs-lookup"><span data-stu-id="d4235-147">The following example shows the request XML when you use the [CreateItem](http://msdn.microsoft.com/library/aa4a7c94-f668-4bd2-8079-c855f6ab17e1%28Office.15%29.aspx) operation to create a meeting.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
       xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2007_SP1" />
    <t:TimeZoneContext>
      <t:TimeZoneDefinition Id="Pacific Standard Time" />
    </t:TimeZoneContext>
  </soap:Header>
  <soap:Body>
    <m:CreateItem SendMeetingInvitations="SendToAllAndSaveCopy">
      <m:Items>
        <t:CalendarItem>
          <t:Subject>Team building exercise</t:Subject>
          <t:Body BodyType="HTML">Let's learn to really work as a team and then have lunch!</t:Body>
          <t:ReminderMinutesBeforeStart>60</t:ReminderMinutesBeforeStart>
          <t:Start>2013-09-21T16:00:00.000Z</t:Start>
          <t:End>2013-09-21T20:00:00.000Z</t:End>
          <t:Location>Conference Room 12</t:Location>
          <t:RequiredAttendees>
            <t:Attendee>
              <t:Mailbox>
                <t:EmailAddress>Mack.Chaves@contoso.com</t:EmailAddress>
              </t:Mailbox>
            </t:Attendee>
            <t:Attendee>
              <t:Mailbox>
                <t:EmailAddress>Sadie.Daniels@contoso.com</t:EmailAddress>
              </t:Mailbox>
            </t:Attendee>
          </t:RequiredAttendees>
          <t:OptionalAttendees>
            <t:Attendee>
              <t:Mailbox>
                <t:EmailAddress>Magdalena.Kemp@contoso.com</t:EmailAddress>
              </t:Mailbox>
            </t:Attendee>
          </t:OptionalAttendees>
          <t:MeetingTimeZone TimeZoneName="Pacific Standard Time" />
        </t:CalendarItem>
      </m:Items>
    </m:CreateItem>
  </soap:Body>
</soap:Envelope>
```

<span data-ttu-id="d4235-148">O exemplo a seguir mostra a resposta XML retornada pela operação de **CreateItem** .</span><span class="sxs-lookup"><span data-stu-id="d4235-148">The following example shows the response XML that is returned by the **CreateItem** operation.</span></span> 
  
> [!NOTE]
> <span data-ttu-id="d4235-149">Os atributos **ItemId** e **ChangeKey** foram diminuídos para melhorar a legibilidade.</span><span class="sxs-lookup"><span data-stu-id="d4235-149">The **ItemId** and **ChangeKey** attributes have been shortened for readability.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<s:Envelope xmlns:s="http://schemas.xmlsoap.org/soap/envelope/">
  <s:Header>
    <h:ServerVersionInfo MajorVersion="15" MinorVersion="0" MajorBuildNumber="775" MinorBuildNumber="7" Version="V2_4" 
 xmlns:h="http://schemas.microsoft.com/exchange/services/2006/types" 
 xmlns="http://schemas.microsoft.com/exchange/services/2006/types" 
 xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" />
  </s:Header>
  <s:Body xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <m:CreateItemResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
      <m:ResponseMessages>
        <m:CreateItemResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:Items>
            <t:CalendarItem>
              <t:ItemId Id="AAMkA" ChangeKey="DwAAA" />
            </t:CalendarItem>
          </m:Items>
        </m:CreateItemResponseMessage>
      </m:ResponseMessages>
    </m:CreateItemResponse>
  </s:Body>
</s:Envelope>
```

<span data-ttu-id="d4235-150">O exemplo a seguir mostra a solicitação XML gerado pela operação de [GetItem](http://msdn.microsoft.com/library/a41c29c9-c4e6-4aa4-8e28-ccb0b478fee8%28Office.15%29.aspx) quando você verificar se a reunião foi criada.</span><span class="sxs-lookup"><span data-stu-id="d4235-150">The following example shows the request XML that is generated by the [GetItem](http://msdn.microsoft.com/library/a41c29c9-c4e6-4aa4-8e28-ccb0b478fee8%28Office.15%29.aspx) operation when you verify that the meeting was created.</span></span> 
  
> [!NOTE]
> <span data-ttu-id="d4235-151">Os atributos **ItemId** e **ChangeKey** foram diminuídos para melhorar a legibilidade.</span><span class="sxs-lookup"><span data-stu-id="d4235-151">The **ItemId** and **ChangeKey** attributes have been shortened for readability.</span></span> 
  
```xml
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" 
       xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types" xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2007_SP1" />
    <t:TimeZoneContext>
      <t:TimeZoneDefinition Id="Pacific Standard Time" />
    </t:TimeZoneContext>
  </soap:Header>
  <soap:Body>
    <m:GetItem>
      <m:ItemShape>
        <t:BaseShape>IdOnly</t:BaseShape>
        <t:AdditionalProperties>
          <t:FieldURI FieldURI="item:Subject" />
        </t:AdditionalProperties>
      </m:ItemShape>
      <m:ItemIds>
        <t:ItemId Id="AAMkA" ChangeKey="DwAAA" />
      </m:ItemIds>
    </m:GetItem>
  </soap:Body>
</soap:Envelope>
```

<span data-ttu-id="d4235-152">O exemplo a seguir mostra a resposta XML retornada pela operação de **GetItem** .</span><span class="sxs-lookup"><span data-stu-id="d4235-152">The following example shows the response XML that is returned by the **GetItem** operation.</span></span> 
  
> [!NOTE]
> <span data-ttu-id="d4235-153">Os atributos **ItemId** e **ChangeKey** foram diminuídos para melhorar a legibilidade.</span><span class="sxs-lookup"><span data-stu-id="d4235-153">The **ItemId** and **ChangeKey** attributes have been shortened for readability.</span></span> 
  
```XML
<?xml version="1.0" encoding="utf-8"?>
<s:Envelope xmlns:s="http://schemas.xmlsoap.org/soap/envelope/">
  <s:Header>
    <h:ServerVersionInfo MajorVersion="15" MinorVersion="0" MajorBuildNumber="775" MinorBuildNumber="7" Version="V2_4" 
 xmlns:h="http://schemas.microsoft.com/exchange/services/2006/types" 
 xmlns="http://schemas.microsoft.com/exchange/services/2006/types" 
 xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" />
  </s:Header>
  <s:Body xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <m:GetItemResponse xmlns:m="http://schemas.microsoft.com/exchange/services/2006/messages" xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">
      <m:ResponseMessages>
        <m:GetItemResponseMessage ResponseClass="Success">
          <m:ResponseCode>NoError</m:ResponseCode>
          <m:Items>
            <t:CalendarItem>
              <t:ItemId Id="AAMkA" ChangeKey="DwAAA" />
              <t:Subject>Team building exercise</t:Subject>
            </t:CalendarItem>
          </m:Items>
        </m:GetItemResponseMessage>
      </m:ResponseMessages>
    </m:GetItemResponse>
  </s:Body>
</s:Envelope>
```

## <a name="see-also"></a><span data-ttu-id="d4235-154">Confira também</span><span class="sxs-lookup"><span data-stu-id="d4235-154">See also</span></span>

- [<span data-ttu-id="d4235-155">Calendários e EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="d4235-155">Calendars and EWS in Exchange</span></span>](calendars-and-ews-in-exchange.md)  
- [<span data-ttu-id="d4235-156">Obtenha os compromissos e reuniões usando o EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="d4235-156">Get appointments and meetings by using EWS in Exchange</span></span>](how-to-get-appointments-and-meetings-by-using-ews-in-exchange.md)  
- [<span data-ttu-id="d4235-157">Atualizar compromissos e reuniões usando o EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="d4235-157">Update appointments and meetings by using EWS in Exchange</span></span>](how-to-update-appointments-and-meetings-by-using-ews-in-exchange.md) 
- [<span data-ttu-id="d4235-158">Excluir compromissos e cancelar reuniões usando o EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="d4235-158">Delete appointments and cancel meetings by using EWS in Exchange</span></span>](how-to-delete-appointments-and-cancel-meetings-by-using-ews-in-exchange.md) 
- [<span data-ttu-id="d4235-159">Propor um novo horário de reunião usando o EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="d4235-159">Propose a new meeting time by using EWS in Exchange</span></span>](how-to-propose-a-new-meeting-time-by-using-ews-in-exchange.md)
    

