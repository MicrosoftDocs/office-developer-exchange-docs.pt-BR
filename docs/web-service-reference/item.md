---
title: Item
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- Item
api_type:
- schema
ms.assetid: 4dfe8f48-e7b4-444d-bdf9-a34e180f598b
description: O elemento item representa um item genérico no repositório do Exchange.
ms.openlocfilehash: 72d8b1344bea3bcd105a0e293365b17f37193ac3
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44460313"
---
# <a name="item"></a><span data-ttu-id="82fa9-103">Item</span><span class="sxs-lookup"><span data-stu-id="82fa9-103">Item</span></span>

<span data-ttu-id="82fa9-104">O elemento **Item** representa um item genérico no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="82fa9-104">The **Item** element represents a generic item in the Exchange store.</span></span> 
  
```xml
<Item>
   <MimeContent/>
   <ItemId/>
   <ParentFolderId/>
   <ItemClass/>
   <Subject/>
   <Sensitivity/>
   <Body/>
   <Attachments/>
   <DateTimeReceived/>
   <Size/>
   <Categories/>
   <Importance/>
   <InReplyTo/>
   <IsSubmitted/>
   <IsDraft/>
   <IsFromMe/>
   <IsResend/>
   <IsUnmodified/>
   <InternetMessageHeaders/>
   <DateTimeSent/>
   <DateTimeCreated/>
   <ResponseObjects/>
   <ReminderDueBy/>
   <ReminderIsSet/>
   <ReminderMinutesBeforeStart/>
   <DisplayCc/>
   <DisplayTo/>
   <HasAttachments/>
   <ExtendedProperty/>
   <Culture/>
   <EffectiveRights/>
   <LastModifiedName/>
   <LastModifiedTime/>
   <IsAssociated/>
   <WebClientReadFormQueryString/>
   <WebClientEditFormQueryString/>
   <ConversationId/>
   <UniqueBody/>
</Item>
```

 <span data-ttu-id="82fa9-105">**ItemType**</span><span class="sxs-lookup"><span data-stu-id="82fa9-105">**ItemType**</span></span>
## <a name="attributes-and-elements"></a><span data-ttu-id="82fa9-106">Atributos e elementos</span><span class="sxs-lookup"><span data-stu-id="82fa9-106">Attributes and elements</span></span>

<span data-ttu-id="82fa9-107">As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.</span><span class="sxs-lookup"><span data-stu-id="82fa9-107">The following sections describe attributes, child elements, and parent elements.</span></span>
  
### <a name="attributes"></a><span data-ttu-id="82fa9-108">Atributos</span><span class="sxs-lookup"><span data-stu-id="82fa9-108">Attributes</span></span>

<span data-ttu-id="82fa9-109">Nenhum</span><span class="sxs-lookup"><span data-stu-id="82fa9-109">None.</span></span>
  
### <a name="child-elements"></a><span data-ttu-id="82fa9-110">Elementos filho</span><span class="sxs-lookup"><span data-stu-id="82fa9-110">Child elements</span></span>

|<span data-ttu-id="82fa9-111">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="82fa9-111">**Element**</span></span>|<span data-ttu-id="82fa9-112">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="82fa9-112">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="82fa9-113">MimeContent</span><span class="sxs-lookup"><span data-stu-id="82fa9-113">MimeContent</span></span>](mimecontent.md) <br/> |<span data-ttu-id="82fa9-114">Contém o fluxo MIME (Multipurpose Internet Mail Extensions) nativo de um objeto representado no formato base64Binary.</span><span class="sxs-lookup"><span data-stu-id="82fa9-114">Contains the native Multipurpose Internet Mail Extensions (MIME) stream of an object that is represented in base64Binary format.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-115">ItemId</span><span class="sxs-lookup"><span data-stu-id="82fa9-115">ItemId</span></span>](itemid.md) <br/> |<span data-ttu-id="82fa9-116">Contém o identificador exclusivo e a chave de alteração de um item no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="82fa9-116">Contains the unique identifier and change key of an item in the Exchange store.</span></span> <span data-ttu-id="82fa9-117">Essa propriedade é somente leitura.</span><span class="sxs-lookup"><span data-stu-id="82fa9-117">This property is read-only.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-118">ParentFolderId</span><span class="sxs-lookup"><span data-stu-id="82fa9-118">ParentFolderId</span></span>](parentfolderid.md) <br/> |<span data-ttu-id="82fa9-119">Representa o identificador da pasta pai que contém o item ou a pasta.</span><span class="sxs-lookup"><span data-stu-id="82fa9-119">Represents the identifier of the parent folder that contains the item or folder.</span></span> <span data-ttu-id="82fa9-120">Essa propriedade é somente leitura.</span><span class="sxs-lookup"><span data-stu-id="82fa9-120">This property is read-only.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-121">ItemClass</span><span class="sxs-lookup"><span data-stu-id="82fa9-121">ItemClass</span></span>](itemclass.md) <br/> |<span data-ttu-id="82fa9-122">Representa a classe de mensagem de um item.</span><span class="sxs-lookup"><span data-stu-id="82fa9-122">Represents the message class of an item.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-123">Assunto</span><span class="sxs-lookup"><span data-stu-id="82fa9-123">Subject</span></span>](subject.md) <br/> |<span data-ttu-id="82fa9-124">Representa o assunto de itens do repositório do Exchange e objetos de resposta.</span><span class="sxs-lookup"><span data-stu-id="82fa9-124">Represents the subject for Exchange store items and response objects.</span></span> <span data-ttu-id="82fa9-125">O assunto está limitado a 255 caracteres.</span><span class="sxs-lookup"><span data-stu-id="82fa9-125">The subject is limited to 255 characters.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-126">Sensitivity</span><span class="sxs-lookup"><span data-stu-id="82fa9-126">Sensitivity</span></span>](sensitivity.md) <br/> |<span data-ttu-id="82fa9-127">Indica o nível de sensibilidade de um item.</span><span class="sxs-lookup"><span data-stu-id="82fa9-127">Indicates the sensitivity level of an item.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-128">Body</span><span class="sxs-lookup"><span data-stu-id="82fa9-128">Body</span></span>](body.md) <br/> |<span data-ttu-id="82fa9-129">Representa o conteúdo real do corpo de uma mensagem.</span><span class="sxs-lookup"><span data-stu-id="82fa9-129">Represents the actual body content of a message.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-130">Anexos</span><span class="sxs-lookup"><span data-stu-id="82fa9-130">Attachments</span></span>](attachments-ex15websvcsotherref.md) <br/> |<span data-ttu-id="82fa9-131">Contém os itens ou arquivos anexados a um item no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="82fa9-131">Contains the items or files that are attached to an item in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-132">DateTimeReceived</span><span class="sxs-lookup"><span data-stu-id="82fa9-132">DateTimeReceived</span></span>](datetimereceived.md) <br/> |<span data-ttu-id="82fa9-133">Representa a data e a hora em que um item foi recebido em uma caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="82fa9-133">Represents the date and time that an item in a mailbox was received.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-134">Tamanho</span><span class="sxs-lookup"><span data-stu-id="82fa9-134">Size</span></span>](size.md) <br/> |<span data-ttu-id="82fa9-135">Representa o tamanho em bytes de um item.</span><span class="sxs-lookup"><span data-stu-id="82fa9-135">Represents the size in bytes of an item.</span></span> <span data-ttu-id="82fa9-136">Essa propriedade é somente leitura.</span><span class="sxs-lookup"><span data-stu-id="82fa9-136">This property is read-only.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-137">Categorias</span><span class="sxs-lookup"><span data-stu-id="82fa9-137">Categories</span></span>](categories-ex15websvcsotherref.md) <br/> |<span data-ttu-id="82fa9-138">Representa uma coleção de cadeias de caracteres que identificam a quais categorias um item da caixa de correio pertence.</span><span class="sxs-lookup"><span data-stu-id="82fa9-138">Represents a collection of strings that identify to which categories an item in the mailbox belongs.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-139">Importance</span><span class="sxs-lookup"><span data-stu-id="82fa9-139">Importance</span></span>](importance.md) <br/> |<span data-ttu-id="82fa9-140">Descreve a importância de um item.</span><span class="sxs-lookup"><span data-stu-id="82fa9-140">Describes the importance of an item.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-141">Inresponderto</span><span class="sxs-lookup"><span data-stu-id="82fa9-141">InReplyTo</span></span>](inreplyto.md) <br/> |<span data-ttu-id="82fa9-142">Representa o identificador do item para o qual este item é uma resposta.</span><span class="sxs-lookup"><span data-stu-id="82fa9-142">Represents the identifier of the item to which this item is a reply.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-143">Isenviado</span><span class="sxs-lookup"><span data-stu-id="82fa9-143">IsSubmitted</span></span>](issubmitted.md) <br/> |<span data-ttu-id="82fa9-144">Indica se um item foi enviado para a pasta padrão da pasta de saída.</span><span class="sxs-lookup"><span data-stu-id="82fa9-144">Indicates whether an item has been submitted to the Outbox default folder.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-145">IsDraft</span><span class="sxs-lookup"><span data-stu-id="82fa9-145">IsDraft</span></span>](isdraft.md) <br/> |<span data-ttu-id="82fa9-146">Indica se um item ainda não foi enviado.</span><span class="sxs-lookup"><span data-stu-id="82fa9-146">Represents whether an item has not yet been sent.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-147">IsFromMe</span><span class="sxs-lookup"><span data-stu-id="82fa9-147">IsFromMe</span></span>](isfromme.md) <br/> |<span data-ttu-id="82fa9-148">Indica se um usuário enviou um item para si mesmo.</span><span class="sxs-lookup"><span data-stu-id="82fa9-148">Indicates whether a user sent an item to itself.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-149">IsResend</span><span class="sxs-lookup"><span data-stu-id="82fa9-149">IsResend</span></span>](isresend.md) <br/> |<span data-ttu-id="82fa9-150">Indica se o item foi enviado anteriormente.</span><span class="sxs-lookup"><span data-stu-id="82fa9-150">Indicates whether the item had previously been sent.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-151">IsUnmodified</span><span class="sxs-lookup"><span data-stu-id="82fa9-151">IsUnmodified</span></span>](isunmodified.md) <br/> |<span data-ttu-id="82fa9-152">Indica se o item foi modificado.</span><span class="sxs-lookup"><span data-stu-id="82fa9-152">Indicates whether the item has been modified.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-153">Propriedadeinternetmessageheaders</span><span class="sxs-lookup"><span data-stu-id="82fa9-153">InternetMessageHeaders</span></span>](internetmessageheaders.md) <br/> |<span data-ttu-id="82fa9-154">Representa a coleção de todos os cabeçalhos de mensagens da Internet que estão contidos em um item em uma caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="82fa9-154">Represents the collection of all Internet message headers that are contained within an item in a mailbox.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-155">DateTimeSent</span><span class="sxs-lookup"><span data-stu-id="82fa9-155">DateTimeSent</span></span>](datetimesent.md) <br/> |<span data-ttu-id="82fa9-156">Representa a data e a hora em que um item em uma caixa de correio foi enviado.</span><span class="sxs-lookup"><span data-stu-id="82fa9-156">Represents the date and time that an item in a mailbox was sent.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-157">DateTimeCreated</span><span class="sxs-lookup"><span data-stu-id="82fa9-157">DateTimeCreated</span></span>](datetimecreated.md) <br/> |<span data-ttu-id="82fa9-158">Representa a data e a hora em que um determinado item da caixa de correio foi criado.</span><span class="sxs-lookup"><span data-stu-id="82fa9-158">Represents the date and time that a given item in the mailbox was created.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-159">ResponseObjects</span><span class="sxs-lookup"><span data-stu-id="82fa9-159">ResponseObjects</span></span>](responseobjects.md) <br/> |<span data-ttu-id="82fa9-160">Contém uma coleção de todos os objetos Response associados a um item no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="82fa9-160">Contains a collection of all the response objects that are associated with an item in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-161">ReminderDueBy</span><span class="sxs-lookup"><span data-stu-id="82fa9-161">ReminderDueBy</span></span>](reminderdueby.md) <br/> |<span data-ttu-id="82fa9-162">Representa a data e a hora em que o evento ocorre.</span><span class="sxs-lookup"><span data-stu-id="82fa9-162">Represents the date and time when the event occurs.</span></span> <span data-ttu-id="82fa9-163">Isso é usado pelo elemento [ReminderMinutesBeforeStart](reminderminutesbeforestart.md) para determinar quando o lembrete é exibido.</span><span class="sxs-lookup"><span data-stu-id="82fa9-163">This is used by the [ReminderMinutesBeforeStart](reminderminutesbeforestart.md) element to determine when the reminder is displayed.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-164">ReminderIsSet</span><span class="sxs-lookup"><span data-stu-id="82fa9-164">ReminderIsSet</span></span>](reminderisset.md) <br/> |<span data-ttu-id="82fa9-165">Indica se um lembrete foi definido para um item no repositório do Exchange.</span><span class="sxs-lookup"><span data-stu-id="82fa9-165">Indicates whether a reminder has been set for an item in the Exchange store.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-166">ReminderMinutesBeforeStart</span><span class="sxs-lookup"><span data-stu-id="82fa9-166">ReminderMinutesBeforeStart</span></span>](reminderminutesbeforestart.md) <br/> |<span data-ttu-id="82fa9-167">Representa o número de minutos antes de um evento quando um lembrete é exibido.</span><span class="sxs-lookup"><span data-stu-id="82fa9-167">Represents the number of minutes before an event when a reminder is displayed.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-168">DisplayCc</span><span class="sxs-lookup"><span data-stu-id="82fa9-168">DisplayCc</span></span>](displaycc.md) <br/> |<span data-ttu-id="82fa9-169">Representa a cadeia de caracteres de exibição usada para o conteúdo da caixa CC.</span><span class="sxs-lookup"><span data-stu-id="82fa9-169">Represents the display string that is used for the contents of the Cc box.</span></span> <span data-ttu-id="82fa9-170">Esta é a cadeia de caracteres concatenada de todos os nomes de exibição de destinatários CC.</span><span class="sxs-lookup"><span data-stu-id="82fa9-170">This is the concatenated string of all Cc recipient display names.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-171">DisplayTo</span><span class="sxs-lookup"><span data-stu-id="82fa9-171">DisplayTo</span></span>](displayto.md) <br/> |<span data-ttu-id="82fa9-172">Representa a cadeia de caracteres de exibição usada para o conteúdo da caixa para.</span><span class="sxs-lookup"><span data-stu-id="82fa9-172">Represents the display string that is used for the contents of the To box.</span></span> <span data-ttu-id="82fa9-173">Esta é a cadeia de caracteres concatenada de todos os nomes de exibição de destinatários.</span><span class="sxs-lookup"><span data-stu-id="82fa9-173">This is the concatenated string of all To recipient display names.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-174">HasAttachments</span><span class="sxs-lookup"><span data-stu-id="82fa9-174">HasAttachments</span></span>](hasattachments.md) <br/> |<span data-ttu-id="82fa9-175">Representa uma propriedade que é definida como **true** se um item tem anexos de pelo menos um anexo visível.</span><span class="sxs-lookup"><span data-stu-id="82fa9-175">Represents a property that is set to **true** if an item has attachments at least one visible attachment.</span></span> <span data-ttu-id="82fa9-176">Essa propriedade é somente leitura.</span><span class="sxs-lookup"><span data-stu-id="82fa9-176">This property is read-only.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-177">ExtendedProperty</span><span class="sxs-lookup"><span data-stu-id="82fa9-177">ExtendedProperty</span></span>](extendedproperty.md) <br/> |<span data-ttu-id="82fa9-178">Identifica as propriedades estendidas em pastas e itens.</span><span class="sxs-lookup"><span data-stu-id="82fa9-178">Identifies extended properties on folders and items.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-179">Cultura</span><span class="sxs-lookup"><span data-stu-id="82fa9-179">Culture</span></span>](culture.md) <br/> |<span data-ttu-id="82fa9-180">Representa a cultura de um determinado item em uma caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="82fa9-180">Represents the culture for a given item in a mailbox.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-181">EffectiveRights</span><span class="sxs-lookup"><span data-stu-id="82fa9-181">EffectiveRights</span></span>](effectiverights.md) <br/> |<span data-ttu-id="82fa9-182">Contém os direitos do cliente com base nas configurações de permissão para o item ou pasta.</span><span class="sxs-lookup"><span data-stu-id="82fa9-182">Contains the client's rights based on the permission settings for the item or folder.</span></span> <span data-ttu-id="82fa9-183">Este elemento é somente leitura.</span><span class="sxs-lookup"><span data-stu-id="82fa9-183">This element is read-only.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-184">LastModified</span><span class="sxs-lookup"><span data-stu-id="82fa9-184">LastModifiedName</span></span>](lastmodifiedname.md) <br/> |<span data-ttu-id="82fa9-185">Contém o nome de exibição do último usuário a modificar um item.</span><span class="sxs-lookup"><span data-stu-id="82fa9-185">Contains the display name of the last user to modify an item.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-186">LastModifiedTime</span><span class="sxs-lookup"><span data-stu-id="82fa9-186">LastModifiedTime</span></span>](lastmodifiedtime.md) <br/> |<span data-ttu-id="82fa9-187">Indica quando um item foi modificado pela última vez.</span><span class="sxs-lookup"><span data-stu-id="82fa9-187">Indicates when an item was last modified.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-188">Isassociated</span><span class="sxs-lookup"><span data-stu-id="82fa9-188">IsAssociated</span></span>](isassociated.md) <br/> |<span data-ttu-id="82fa9-189">Indica se o item está associado a uma pasta.</span><span class="sxs-lookup"><span data-stu-id="82fa9-189">Indicates whether the item is associated with a folder.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-190">WebClientReadFormQueryString</span><span class="sxs-lookup"><span data-stu-id="82fa9-190">WebClientReadFormQueryString</span></span>](webclientreadformquerystring.md) <br/> |<span data-ttu-id="82fa9-191">Representa uma URL para concatenar ao ponto de extremidade do Microsoft Office Outlook Web App para ler um item no Outlook Web App.</span><span class="sxs-lookup"><span data-stu-id="82fa9-191">Represents a URL to concatenate to the Microsoft Office Outlook Web App endpoint to read an item in Outlook Web App.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-192">WebClientEditFormQueryString</span><span class="sxs-lookup"><span data-stu-id="82fa9-192">WebClientEditFormQueryString</span></span>](webclienteditformquerystring.md) <br/> |<span data-ttu-id="82fa9-193">Representa uma URL para concatenar ao ponto de extremidade do Outlook Web App para editar um item no Outlook Web App.</span><span class="sxs-lookup"><span data-stu-id="82fa9-193">Represents a URL to concatenate to the Outlook Web App endpoint to edit an item in Outlook Web App.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-194">ConversationId</span><span class="sxs-lookup"><span data-stu-id="82fa9-194">ConversationId</span></span>](conversationid.md) <br/> |<span data-ttu-id="82fa9-195">Contém o identificador de um item ou uma conversa.</span><span class="sxs-lookup"><span data-stu-id="82fa9-195">Contains the identifier of an item or conversation.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-196">UniqueBody</span><span class="sxs-lookup"><span data-stu-id="82fa9-196">UniqueBody</span></span>](uniquebody.md) <br/> |<span data-ttu-id="82fa9-197">Representa um fragmento HTML ou texto sem formatação que representa o corpo exclusivo desta conversa.</span><span class="sxs-lookup"><span data-stu-id="82fa9-197">Represents an HTML fragment or plain text which represents the unique body of this conversation.</span></span>  <br/> |
   
### <a name="parent-elements"></a><span data-ttu-id="82fa9-198">Elementos pai</span><span class="sxs-lookup"><span data-stu-id="82fa9-198">Parent elements</span></span>

|<span data-ttu-id="82fa9-199">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="82fa9-199">**Element**</span></span>|<span data-ttu-id="82fa9-200">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="82fa9-200">**Description**</span></span>|
|:-----|:-----|
|[<span data-ttu-id="82fa9-201">AdjacentMeetings</span><span class="sxs-lookup"><span data-stu-id="82fa9-201">AdjacentMeetings</span></span>](adjacentmeetings.md) <br/> |<span data-ttu-id="82fa9-202">Descreve todos os itens de calendário adjacentes a um horário de reunião.</span><span class="sxs-lookup"><span data-stu-id="82fa9-202">Describes all calendar items that are adjacent to a meeting time.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-203">AppendToItemField</span><span class="sxs-lookup"><span data-stu-id="82fa9-203">AppendToItemField</span></span>](appendtoitemfield.md) <br/> |<span data-ttu-id="82fa9-204">Identifica os dados a serem acrescentados a uma única propriedade de um item/pasta durante uma [operação UpdateItem](updateitem-operation.md).</span><span class="sxs-lookup"><span data-stu-id="82fa9-204">Identifies data to append to a single property of an item/folder during an [UpdateItem operation](updateitem-operation.md).</span></span>  <br/> |
|[<span data-ttu-id="82fa9-205">ConflictingMeetings</span><span class="sxs-lookup"><span data-stu-id="82fa9-205">ConflictingMeetings</span></span>](conflictingmeetings.md) <br/> |<span data-ttu-id="82fa9-206">Identifica todos os itens que entram em conflito com um horário de reunião.</span><span class="sxs-lookup"><span data-stu-id="82fa9-206">Identifies all items that conflict with a meeting time.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-207">Create (issync)</span><span class="sxs-lookup"><span data-stu-id="82fa9-207">Create (ItemSync)</span></span>](create-itemsync.md) <br/> |<span data-ttu-id="82fa9-208">Identifica um único item a ser criado no armazenamento do cliente local.</span><span class="sxs-lookup"><span data-stu-id="82fa9-208">Identifies a single item to create in the local client store.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-209">ItemAttachment</span><span class="sxs-lookup"><span data-stu-id="82fa9-209">ItemAttachment</span></span>](itemattachment.md) <br/> |<span data-ttu-id="82fa9-210">Representa um item do Exchange anexado a outro item do Exchange.</span><span class="sxs-lookup"><span data-stu-id="82fa9-210">Represents an Exchange item that is attached to another Exchange item.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-211">Itens</span><span class="sxs-lookup"><span data-stu-id="82fa9-211">Items</span></span>](items.md) <br/> |<span data-ttu-id="82fa9-212">Contém uma matriz de itens.</span><span class="sxs-lookup"><span data-stu-id="82fa9-212">Contains an array of items.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-213">Itens (NonEmptyArrayOfAllItemsType)</span><span class="sxs-lookup"><span data-stu-id="82fa9-213">Items (NonEmptyArrayOfAllItemsType)</span></span>](items-nonemptyarrayofallitemstype.md) <br/> |<span data-ttu-id="82fa9-214">Contém uma matriz de itens a serem criados na pasta que é identificada pelo elemento [ParentFolderId (TargetFolderIdType)](parentfolderid-targetfolderidtype.md) .</span><span class="sxs-lookup"><span data-stu-id="82fa9-214">Contains an array of items to create in the folder that is identified by the [ParentFolderId (TargetFolderIdType)](parentfolderid-targetfolderidtype.md) element.</span></span>  <br/> |
|[<span data-ttu-id="82fa9-215">Setitemfield</span><span class="sxs-lookup"><span data-stu-id="82fa9-215">SetItemField</span></span>](setitemfield.md) <br/> |<span data-ttu-id="82fa9-216">Representa uma atualização de uma única propriedade de um item em uma [operação UpdateItem](updateitem-operation.md).</span><span class="sxs-lookup"><span data-stu-id="82fa9-216">Represents an update to a single property of an item in an [UpdateItem operation](updateitem-operation.md).</span></span>  <br/> |
|[<span data-ttu-id="82fa9-217">Atualização (issync)</span><span class="sxs-lookup"><span data-stu-id="82fa9-217">Update (ItemSync)</span></span>](update-itemsync.md) <br/> |<span data-ttu-id="82fa9-218">Identifica um único item a ser atualizado no repositório do cliente local.</span><span class="sxs-lookup"><span data-stu-id="82fa9-218">Identifies a single item to update in the local client store.</span></span>  <br/> |
   
## <a name="text-value"></a><span data-ttu-id="82fa9-219">Valor de texto</span><span class="sxs-lookup"><span data-stu-id="82fa9-219">Text value</span></span>

<span data-ttu-id="82fa9-220">Nenhum.</span><span class="sxs-lookup"><span data-stu-id="82fa9-220">None.</span></span>
  
## <a name="remarks"></a><span data-ttu-id="82fa9-221">Comentários</span><span class="sxs-lookup"><span data-stu-id="82fa9-221">Remarks</span></span>

<span data-ttu-id="82fa9-222">É importante observar que **ItemType** é o tipo base para [Task](task.md), [CalendarItem](calendaritem.md), [Contact](contact.md), [DistributionList](distributionlist.md)e [Message](message-ex15websvcsotherref.md).</span><span class="sxs-lookup"><span data-stu-id="82fa9-222">It is important to note that **ItemType** is the base type for [Task](task.md), [CalendarItem](calendaritem.md), [Contact](contact.md), [DistributionList](distributionlist.md), and [Message](message-ex15websvcsotherref.md).</span></span>
  
<span data-ttu-id="82fa9-223">Os elementos da [mensagem](message-ex15websvcsotherref.md) representam mensagens de email e todos os outros itens que não são digitados com rigidez pelo esquema dos serviços Web do Exchange (EWS).</span><span class="sxs-lookup"><span data-stu-id="82fa9-223">[Message](message-ex15websvcsotherref.md) elements represent e-mail messages and all other items that are not strongly typed by the Exchange Web Services (EWS) schema.</span></span> <span data-ttu-id="82fa9-224">Itens como IPM. O compartilhamento e o IPM. InfoPath são retornados como elementos de **mensagem** .</span><span class="sxs-lookup"><span data-stu-id="82fa9-224">Items such as IPM.Sharing and IPM.InfoPath are returned as **Message** elements.</span></span> <span data-ttu-id="82fa9-225">O Microsoft Exchange Server 2010 não retorna o elemento de **Item** base nas respostas.</span><span class="sxs-lookup"><span data-stu-id="82fa9-225">Microsoft Exchange Server 2010 does not return the base **Item** element in responses.</span></span> 
  
<span data-ttu-id="82fa9-226">O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.</span><span class="sxs-lookup"><span data-stu-id="82fa9-226">The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.</span></span>
  
## <a name="element-information"></a><span data-ttu-id="82fa9-227">Elemento de informações</span><span class="sxs-lookup"><span data-stu-id="82fa9-227">Element information</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="82fa9-228">Namespace</span><span class="sxs-lookup"><span data-stu-id="82fa9-228">Namespace</span></span>  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|<span data-ttu-id="82fa9-229">Nome do esquema</span><span class="sxs-lookup"><span data-stu-id="82fa9-229">Schema Name</span></span>  <br/> |<span data-ttu-id="82fa9-230">Esquema de tipos</span><span class="sxs-lookup"><span data-stu-id="82fa9-230">Types schema</span></span>  <br/> |
|<span data-ttu-id="82fa9-231">Arquivo de validação</span><span class="sxs-lookup"><span data-stu-id="82fa9-231">Validation File</span></span>  <br/> |<span data-ttu-id="82fa9-232">Types. xsd</span><span class="sxs-lookup"><span data-stu-id="82fa9-232">Types.xsd</span></span>  <br/> |
|<span data-ttu-id="82fa9-233">Pode ser vazio</span><span class="sxs-lookup"><span data-stu-id="82fa9-233">Can be Empty</span></span>  <br/> |<span data-ttu-id="82fa9-234">False</span><span class="sxs-lookup"><span data-stu-id="82fa9-234">False</span></span>  <br/> |
   
## <a name="see-also"></a><span data-ttu-id="82fa9-235">Confira também</span><span class="sxs-lookup"><span data-stu-id="82fa9-235">See also</span></span>



- [<span data-ttu-id="82fa9-236">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="82fa9-236">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)
  
[<span data-ttu-id="82fa9-237">Referência do EWS para Exchange</span><span class="sxs-lookup"><span data-stu-id="82fa9-237">EWS reference for Exchange</span></span>](ews-reference-for-exchange.md)

