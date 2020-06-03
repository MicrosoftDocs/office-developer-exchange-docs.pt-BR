---
title: Operação GetSharingMetadata
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- GetSharingMetadata
api_type:
- schema
ms.assetid: eaf29427-ecf8-4a5e-9a54-db2e6414b35e
description: A operação GetSharingMetadata Obtém um token de autenticação opaco que identifica um convite de compartilhamento.
ms.openlocfilehash: 0390b9caa7b2e9847b1e8dcdc1b911a35e3c5864
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44530180"
---
# <a name="getsharingmetadata-operation"></a><span data-ttu-id="f4b84-103">Operação GetSharingMetadata</span><span class="sxs-lookup"><span data-stu-id="f4b84-103">GetSharingMetadata operation</span></span>

<span data-ttu-id="f4b84-104">A operação **GetSharingMetadata** Obtém um token de autenticação opaco que identifica um convite de compartilhamento.</span><span class="sxs-lookup"><span data-stu-id="f4b84-104">The **GetSharingMetadata** operation gets an opaque authentication token that identifies a sharing invitation.</span></span> 
  
## <a name="soap-headers"></a><span data-ttu-id="f4b84-105">Cabeçalhos SOAP</span><span class="sxs-lookup"><span data-stu-id="f4b84-105">SOAP Headers</span></span>

<span data-ttu-id="f4b84-106">A operação **GetSharingMetadata** pode usar os cabeçalhos SOAP listados e descritos na tabela a seguir.</span><span class="sxs-lookup"><span data-stu-id="f4b84-106">The **GetSharingMetadata** operation can use the SOAP headers that are listed and described in the following table.</span></span> 
  
|<span data-ttu-id="f4b84-107">**Header**</span><span class="sxs-lookup"><span data-stu-id="f4b84-107">**Header**</span></span>|<span data-ttu-id="f4b84-108">**Elemento**</span><span class="sxs-lookup"><span data-stu-id="f4b84-108">**Element**</span></span>|<span data-ttu-id="f4b84-109">**Descrição**</span><span class="sxs-lookup"><span data-stu-id="f4b84-109">**Description**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="f4b84-110">RequestVersion</span><span class="sxs-lookup"><span data-stu-id="f4b84-110">RequestVersion</span></span>  <br/> |[<span data-ttu-id="f4b84-111">RequestServerVersion</span><span class="sxs-lookup"><span data-stu-id="f4b84-111">RequestServerVersion</span></span>](requestserverversion.md) <br/> |<span data-ttu-id="f4b84-112">Identifica a versão do esquema para a solicitação de operação.</span><span class="sxs-lookup"><span data-stu-id="f4b84-112">Identifies the schema version for the operation request.</span></span>  <br/> |
|<span data-ttu-id="f4b84-113">ServerVersion</span><span class="sxs-lookup"><span data-stu-id="f4b84-113">ServerVersion</span></span>  <br/> |[<span data-ttu-id="f4b84-114">ServerVersionInfo</span><span class="sxs-lookup"><span data-stu-id="f4b84-114">ServerVersionInfo</span></span>](serverversioninfo.md) <br/> |<span data-ttu-id="f4b84-115">Identifica a versão do servidor que respondeu à solicitação.</span><span class="sxs-lookup"><span data-stu-id="f4b84-115">Identifies the version of the server that responded to the request.</span></span>  <br/> |
   
## <a name="getsharingmetadata-request-example"></a><span data-ttu-id="f4b84-116">Exemplo de solicitação GetSharingMetadata</span><span class="sxs-lookup"><span data-stu-id="f4b84-116">GetSharingMetadata request example</span></span>

### <a name="description"></a><span data-ttu-id="f4b84-117">Descrição</span><span class="sxs-lookup"><span data-stu-id="f4b84-117">Description</span></span>

<span data-ttu-id="f4b84-118">O exemplo a seguir mostra como formar uma solicitação para obter um token de autenticação opaco que identifica um convite de compartilhamento.</span><span class="sxs-lookup"><span data-stu-id="f4b84-118">The following example shows how to form a request to get an opaque authentication token that identifies a sharing invitation.</span></span> <span data-ttu-id="f4b84-119">Neste exemplo, o user1@contoso.com deseja compartilhar a pasta especificada pelo elemento [IdOfFolderToShare](idoffoldertoshare.md) com user1@fabikam.com e user2@test.com.</span><span class="sxs-lookup"><span data-stu-id="f4b84-119">In this example, user1@contoso.com wants to share the folder that is specified by the [IdOfFolderToShare](idoffoldertoshare.md) element with user1@fabikam.com and user2@test.com.</span></span> 
  
### <a name="code"></a><span data-ttu-id="f4b84-120">Código</span><span class="sxs-lookup"><span data-stu-id="f4b84-120">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/"
               xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
               xmlns:xsd="http://www.w3.org/2001/XMLSchema"
               xmlns:m="https://schemas.microsoft.com/exchange/services/2006/messages"
               xmlns:t="https://schemas.microsoft.com/exchange/services/2006/types">
  <soap:Header>
    <t:RequestServerVersion Version="Exchange2010"/>
  </soap:Header>
  <soap:Body>
    <m:GetSharingMetadata>
      <m:IdOfFolderToShare Id="AAMkAD=" ChangeKey="AwAAA=" />
      <m:SenderSmtpAddress>user1@contoso.com</m:SenderSmtpAddress>
      <m:Recipients>
        <t:SmtpAddress>user1@fabrikam.com</t:SmtpAddress>
        <t:SmtpAddress>user2@test.com</t:SmtpAddress>
      </m:Recipients>
    </m:GetSharingMetadata>
  </soap:Body>
</soap:Envelope>
```

### <a name="comments"></a><span data-ttu-id="f4b84-121">Comentários</span><span class="sxs-lookup"><span data-stu-id="f4b84-121">Comments</span></span>

<span data-ttu-id="f4b84-122">O elemento [Recipients (ArrayOfSmtpAddressType)](recipients-arrayofsmtpaddresstype.md) contém um elemento [smtpAddress](smtpaddress.md) para cada destinatário pretendido do convite de compartilhamento.</span><span class="sxs-lookup"><span data-stu-id="f4b84-122">The [Recipients (ArrayOfSmtpAddressType)](recipients-arrayofsmtpaddresstype.md) element contains one [SmtpAddress](smtpaddress.md) element for each intended recipient of the sharing invitation.</span></span> 
  
## <a name="successful-getsharingmetadata-response"></a><span data-ttu-id="f4b84-123">Resposta GetSharingMetadata bem-sucedida</span><span class="sxs-lookup"><span data-stu-id="f4b84-123">Successful GetSharingMetadata Response</span></span>

### <a name="description"></a><span data-ttu-id="f4b84-124">Descrição</span><span class="sxs-lookup"><span data-stu-id="f4b84-124">Description</span></span>

<span data-ttu-id="f4b84-125">O exemplo a seguir mostra uma resposta bem-sucedida a uma solicitação **GetSharingMetadata** .</span><span class="sxs-lookup"><span data-stu-id="f4b84-125">The following example shows a successful response to a **GetSharingMetadata** request.</span></span> <span data-ttu-id="f4b84-126">Neste exemplo, dois destinatários foram especificados na solicitação **GetSharingMetadata** correspondente: user1@fabrikam.com e user2@test.com.</span><span class="sxs-lookup"><span data-stu-id="f4b84-126">In this example, two recipients were specified in the corresponding **GetSharingMetadata** request: user1@fabrikam.com and user2@test.com.</span></span> 
  
### <a name="code"></a><span data-ttu-id="f4b84-127">Código</span><span class="sxs-lookup"><span data-stu-id="f4b84-127">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/" 
               xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
               xmlns:xsd="http://www.w3.org/2001/XMLSchema">
  <soap:Header>
    <t:ServerVersionInfo MajorVersion="14" 
                         MinorVersion="0" 
                         MajorBuildNumber="639" 
                         MinorBuildNumber="11" 
                         Version="Exchange2010" 
                         xmlns:t="https://schemas.microsoft.com/exchange/services/2006/types" />
  </soap:Header>
  <soap:Body>
    <GetSharingMetadataResponseMessage ResponseClass="Success" 
                                xmlns:t="https://schemas.microsoft.com/exchange/services/2006/types"
                                xmlns:m="https://schemas.microsoft.com/exchange/services/2006/messages"
                                xmlns="https://schemas.microsoft.com/exchange/services/2006/messages">
      <m:ResponseCode>NoError</ResponseCode>
      <m:EncryptedSharedFolderDataCollection>
        <t:EncryptedSharedFolderData>
          <t:Token>
            <EncryptedData Id="Assertion0" Type="http://www.w3.org/2001/04/xmlenc#Element" xmlns="http://www.w3.org/2001/04/xmlenc#">
              <EncryptionMethod Algorithm="http://www.w3.org/2001/04/xmlenc#tripledes-cbc"></EncryptionMethod>
              <ds:KeyInfo xmlns:ds="http://www.w3.org/2000/09/xmldsig#">
                <EncryptedKey>
                  <EncryptionMethod Algorithm="http://www.w3.org/2001/04/xmlenc#rsa-oaep-mgf1p"></EncryptionMethod>
                  <ds:KeyInfo Id="keyinfo">
                    <wsse:SecurityTokenReference xmlns:wsse="http://docs.oasis-open.org/wss/2004/01/oasis-200401-wss-wssecurity-secext-1.0.xsd">
                      <wsse:KeyIdentifier 
                                  EncodingType="http://docs.oasis-open.org/wss/2004/01/oasis-200401-wss-soap-message-security-1.0#Base64Binary" 
                                  ValueType="http://docs.oasis-open.org/wss/2004/01/oasis-200401-wss-x509-token-profile-1.0#X509SubjectKeyIdentifier">
                        B4VEEAf=
                      </wsse:KeyIdentifier>
                    </wsse:SecurityTokenReference>
                  </ds:KeyInfo>
                  <CipherData>
                    <CipherValue>GI/Dxqvw2na==</CipherValue>
                  </CipherData>
                </EncryptedKey>
              </ds:KeyInfo>
              <CipherData>
                <CipherValue>L77I7Hr06z</CipherValue>
              </CipherData>
            </EncryptedData>
          </t:Token>
          <t:Data>
            <EncryptedData Type="http://www.w3.org/2001/04/xmlenc#Element" xmlns="http://www.w3.org/2001/04/xmlenc#">
              <EncryptionMethod Algorithm="http://www.w3.org/2001/04/xmlenc#aes256-cbc" />
              <KeyInfo xmlns="http://www.w3.org/2000/09/xmldsig#">
                <EncryptedKey xmlns="http://www.w3.org/2001/04/xmlenc#">
                  <EncryptionMethod Algorithm="http://www.w3.org/2001/04/xmlenc#kw-tripledes" />
                  <KeyInfo xmlns="http://www.w3.org/2000/09/xmldsig#">
                    <KeyName>key</KeyName>
                  </KeyInfo>
                  <CipherData>
                    <CipherValue>9UgtjrHiU</CipherValue>
                  </CipherData>
                </EncryptedKey>
              </KeyInfo>
              <CipherData>
                <CipherValue>NCNsJoGtQ==</CipherValue>
              </CipherData>
            </EncryptedData>
          </t:Data>
        </t:EncryptedSharedFolderData>
      </m:EncryptedSharedFolderDataCollection>
      <m:InvalidRecipients>
        <t:InvalidRecipient>
          <t:SmtpAddress>user2@test.com</t:SmtpAddress>
          <t:ResponseCode>RecipientOrganizationNotFederated</t:ResponseCode>
          <m:MessageText>The organization of these recipients is not federated for external sharing.</m:MessageText>
        </t:InvalidRecipient>
      </m:InvalidRecipients>
    </GetSharingMetadataResponseMessage>
  </soap:Body>
</soap:Envelope>
```

### <a name="comments"></a><span data-ttu-id="f4b84-128">Comentários</span><span class="sxs-lookup"><span data-stu-id="f4b84-128">Comments</span></span>

<span data-ttu-id="f4b84-129">A resposta contém um elemento [EncryptedSharedFolderData](encryptedsharedfolderdata.md) para cada organização representada por destinatários válidos que são especificados na solicitação **GetSharingMetadata** .</span><span class="sxs-lookup"><span data-stu-id="f4b84-129">The response contains one [EncryptedSharedFolderData](encryptedsharedfolderdata.md) element for each organization that is represented by valid recipients that are specified in the **GetSharingMetadata** request.</span></span> 
  
<span data-ttu-id="f4b84-130">A solicitação **GetSharingMetadata** será bem-sucedida mesmo se destinatários inválidos forem especificados na solicitação.</span><span class="sxs-lookup"><span data-stu-id="f4b84-130">The **GetSharingMetadata** request will succeed even if invalid recipients are specified in the request.</span></span> <span data-ttu-id="f4b84-131">O elemento [InvalidRecipients](invalidrecipients.md) contém informações sobre destinatários inválidos.</span><span class="sxs-lookup"><span data-stu-id="f4b84-131">The [InvalidRecipients](invalidrecipients.md) element contains information about invalid recipients.</span></span> <span data-ttu-id="f4b84-132">Para obter informações sobre os motivos pelos quais um destinatário pode ser inválido, consulte [ResponseCode (InvalidRecipientResponseCodeType)](responsecode-invalidrecipientresponsecodetype.md).</span><span class="sxs-lookup"><span data-stu-id="f4b84-132">For information about the reasons why a recipient might be invalid, see [ResponseCode (InvalidRecipientResponseCodeType)](responsecode-invalidrecipientresponsecodetype.md).</span></span>
  
<span data-ttu-id="f4b84-133">Se todos os destinatários pretendidos forem inválidos, o elemento [EncryptedSharedFolderDataCollection](encryptedsharedfolderdatacollection.md) estará vazio.</span><span class="sxs-lookup"><span data-stu-id="f4b84-133">If all intended recipients are invalid, the [EncryptedSharedFolderDataCollection](encryptedsharedfolderdatacollection.md) element will be empty.</span></span> 
  
## <a name="getsharingmetadata-error-response"></a><span data-ttu-id="f4b84-134">Resposta de erro GetSharingMetadata</span><span class="sxs-lookup"><span data-stu-id="f4b84-134">GetSharingMetadata error response</span></span>

### <a name="description"></a><span data-ttu-id="f4b84-135">Descrição</span><span class="sxs-lookup"><span data-stu-id="f4b84-135">Description</span></span>

<span data-ttu-id="f4b84-136">O exemplo a seguir mostra uma resposta de erro a uma solicitação **GetSharingMetadata** .</span><span class="sxs-lookup"><span data-stu-id="f4b84-136">The following example shows an error response to a **GetSharingMetadata** request.</span></span> 
  
### <a name="code"></a><span data-ttu-id="f4b84-137">Código</span><span class="sxs-lookup"><span data-stu-id="f4b84-137">Code</span></span>

```XML
<?xml version="1.0" encoding="utf-8"?>
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/" 
               xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
               xmlns:xsd="http://www.w3.org/2001/XMLSchema">
  <soap:Header>
    <t:ServerVersionInfo MajorVersion="14" 
                         MinorVersion="0" 
                         MajorBuildNumber="639" 
                         MinorBuildNumber="11" 
                         Version="Exchange2010" 
                         xmlns:t="https://schemas.microsoft.com/exchange/services/2006/types" />
  </soap:Header>
  <soap:Body>
    <GetSharingMetadataResponseMessage ResponseClass="Error" 
                                xmlns:t="https://schemas.microsoft.com/exchange/services/2006/types"
                                xmlns:m="https://schemas.microsoft.com/exchange/services/2006/messages"
                                xmlns="https://schemas.microsoft.com/exchange/services/2006/messages">
      <m:MessageText>The SMTP address format is invalid.</MessageText>
      <m:ResponseCode>ErrorInvalidSmtpAddress</ResponseCode>
      <m:DescriptiveLinkKey>0</DescriptiveLinkKey>
    </GetSharingMetadataResponseMessage>
  </soap:Body>
</soap:Envelope>
```

## <a name="see-also"></a><span data-ttu-id="f4b84-138">Confira também</span><span class="sxs-lookup"><span data-stu-id="f4b84-138">See also</span></span>



[<span data-ttu-id="f4b84-139">GetSharingMetadata</span><span class="sxs-lookup"><span data-stu-id="f4b84-139">GetSharingMetadata</span></span>](getsharingmetadata.md)
  
[<span data-ttu-id="f4b84-140">GetSharingMetadataType</span><span class="sxs-lookup"><span data-stu-id="f4b84-140">GetSharingMetadataType</span></span>](https://msdn.microsoft.com/library/ExchangeWebServices.GetSharingMetadataType.aspx)
  
[<span data-ttu-id="f4b84-141">GetSharingMetadataResponseMessage</span><span class="sxs-lookup"><span data-stu-id="f4b84-141">GetSharingMetadataResponseMessage</span></span>](getsharingmetadataresponsemessage.md)
  
[<span data-ttu-id="f4b84-142">GetSharingMetadataResponseMessageType</span><span class="sxs-lookup"><span data-stu-id="f4b84-142">GetSharingMetadataResponseMessageType</span></span>](https://msdn.microsoft.com/library/ExchangeWebServices.GetSharingMetadataResponseMessageType.aspx)


[<span data-ttu-id="f4b84-143">Operações do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="f4b84-143">EWS operations in Exchange</span></span>](ews-operations-in-exchange.md)
  
- [<span data-ttu-id="f4b84-144">Elementos XML do EWS no Exchange</span><span class="sxs-lookup"><span data-stu-id="f4b84-144">EWS XML elements in Exchange</span></span>](ews-xml-elements-in-exchange.md)

