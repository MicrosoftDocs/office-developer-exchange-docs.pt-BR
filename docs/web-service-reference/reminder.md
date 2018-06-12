---
title: Lembrete
manager: sethgros
ms.date: 03/9/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: 54dd748a-23a5-4ea2-88f2-b74c68a3c48f
description: O elemento de lembrete Especifica um lembrete para uma tarefa ou um item de calendário.
ms.openlocfilehash: cfa1160bd25f5045a3da5a98f081c9dcb3debe7b
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19825056"
---
# <a name="reminder"></a><span data-ttu-id="281dd-103">Lembrete</span><span class="sxs-lookup"><span data-stu-id="281dd-103">Reminder</span></span>

<span data-ttu-id="281dd-104">O elemento de **lembrete** Especifica um lembrete para uma tarefa ou um item de calendário.</span><span class="sxs-lookup"><span data-stu-id="281dd-104">The **Reminder** element specifies a reminder for a task or a calendar item.</span></span> 
  
```XML
<Reminder>
   <Subject></Subject>
   <Location></Location>
   <ReminderTime></ReminderTime>
   <StartDate></StartDate>
   <EndDate></EndDate>
   <ItemId></ItemId>
   <RecurringMasterItemId></RecurringMasterItemId>
   <ReminderGroup></ReminderGroup>
   <UID></UID>
</Reminder>

```

 <span data-ttu-id="281dd-105">**ReminderType**</span><span class="sxs-lookup"><span data-stu-id="281dd-105">**ReminderType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="281dd-106">Attributes and elements</span><span class="sxs-lookup"><span data-stu-id="281dd-106">Attributes and elements</span></span>

<span data-ttu-id="281dd-107">As seções a seguir descrevem os atributos e elementos filho elementos pai.</span><span class="sxs-lookup"><span data-stu-id="281dd-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="281dd-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="281dd-108">Attributes</span></span>

<span data-ttu-id="281dd-109">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="281dd-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="281dd-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="281dd-110">Child elements</span></span>

<span data-ttu-id="281dd-111">[Assunto](subject.md) | [local](location.md) | [ReminderTime](remindertime.md) | [StartDate](startdate.md) | [EndDate (ReminderType)](enddate-remindertype.md) | [ItemId](itemid.md) | [RecurringMasterItemId (ItemIdType)](recurringmasteritemid-itemidtype.md)  |  [ReminderGroup](remindergroup.md) | [UID](uid.md)</span><span class="sxs-lookup"><span data-stu-id="281dd-111">[Subject](subject.md) | [Location](location.md) | [ReminderTime](remindertime.md) | [StartDate](startdate.md) | [EndDate (ReminderType)](enddate-remindertype.md) | [ItemId](itemid.md) | [RecurringMasterItemId (ItemIdType)](recurringmasteritemid-itemidtype.md) | [ReminderGroup](remindergroup.md) | [UID](uid.md)</span></span>
  
### <a name="parent-elements"></a><span data-ttu-id="281dd-112">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="281dd-112">Parent elements</span></span>

[<span data-ttu-id="281dd-113">Reminders</span><span class="sxs-lookup"><span data-stu-id="281dd-113">Reminders</span></span>](reminders.md)
  
## <a name="remarks"></a><span data-ttu-id="281dd-114">Coment�rios</span><span class="sxs-lookup"><span data-stu-id="281dd-114">Remarks</span></span>

<span data-ttu-id="281dd-115">Este elemento foi introduzido no Exchange Server 2013.</span><span class="sxs-lookup"><span data-stu-id="281dd-115">This element was introduced in Exchange Server 2013.</span></span>
  
<span data-ttu-id="281dd-116">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="281dd-116">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="281dd-117">Informações de elemento</span><span class="sxs-lookup"><span data-stu-id="281dd-117">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="281dd-118">Namespace</span><span class="sxs-lookup"><span data-stu-id="281dd-118">Namespace</span></span>  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="281dd-119">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="281dd-119">Schema Name</span></span>  <br/> |<span data-ttu-id="281dd-120">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="281dd-120">Types schema</span></span>  <br/> |
|<span data-ttu-id="281dd-121">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="281dd-121">Validation File</span></span>  <br/> |<span data-ttu-id="281dd-122">Types.xsd</span><span class="sxs-lookup"><span data-stu-id="281dd-122">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="281dd-123">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="281dd-123">Can be Empty</span></span>  <br/> |<span data-ttu-id="281dd-124">False</span><span class="sxs-lookup"><span data-stu-id="281dd-124">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="281dd-125">Ver também</span><span class="sxs-lookup"><span data-stu-id="281dd-125">See also</span></span>



[<span data-ttu-id="281dd-126">Reminders</span><span class="sxs-lookup"><span data-stu-id="281dd-126">Reminders</span></span>](reminders.md)


- [<span data-ttu-id="281dd-127">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="281dd-127">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

