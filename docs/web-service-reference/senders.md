---
title: Remetentes
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: 69d88bb1-397c-4fb8-bd2b-21cccc5bb35d
description: O elemento remetentes especifica uma matriz de endereços SMTP (Simple Mail Transfer Protocol).
ms.openlocfilehash: 125d448be53b2ae297cd1e7249a04da6eda5d960
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44530569"
---
# <a name="senders"></a>Remetentes

O elemento **remetentes** especifica uma matriz de endereços SMTP (Simple Mail Transfer Protocol). 
  
```XML
<Senders>
   <SmtpAddress/>
</Senders>
```

 **ArrayOfSmtpAddressType**
## <a name="attributes-and-elements"></a>Atributos e elementos

As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.
  
### <a name="attributes"></a>Atributos

Nenhum
  
### <a name="child-elements"></a>Elementos filho

[SmtpAddress](smtpaddress.md)
  
### <a name="parent-elements"></a>Elementos pai

[FindMailboxStatisticsByKeywords](findmailboxstatisticsbykeywords.md)
  
## <a name="remarks"></a>Comentários

Este elemento foi introduzido no Exchange Server 2013.
  
O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.
  
## <a name="element-information"></a>Elemento de informações

|||
|:-----|:-----|
|Namespace  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|Nome do esquema  <br/> |Esquema de tipos  <br/> |
|Arquivo de validação  <br/> |Types. xsd  <br/> |
|Pode estar vazio  <br/> ||
   

