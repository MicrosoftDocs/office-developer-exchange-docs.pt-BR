---
title: Entrada (EmailAddress)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- Entry
api_type:
- schema
ms.assetid: b028c5c7-3494-4ecd-96d1-78783daa660f
description: O elemento de entrada representa um único endereço de email de um contato.
ms.openlocfilehash: 1852584e507c38da030815c37f85f7c4af4e2ba4
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19752076"
---
# <a name="entry-emailaddress"></a>Entrada (EmailAddress)

O elemento de **entrada** representa um único endereço de email de um contato. 
  
```XML
<Entry Key="" Name="" RoutingType="" MailboxType="" />
```

**EmailAddressDictionaryEntryType**

## <a name="attributes-and-elements"></a>Attributes and elements

As seções a seguir descrevem os atributos e elementos filho elementos pai.
  
### <a name="attributes"></a>Atributos

|**Attribute**|**Descrição**|
|:-----|:-----|
|**Key** <br/> | Identifica o endereço de email.<br/><br/>Estes são os valores possíveis para este atributo:<br/><br/>-EmailAddress1  <br/>-EmailAddress2  <br/>-EmailAddress3 <br/><br/>  Este atributo é necessário.  <br/> |
|**Name** <br/> |Define o nome do usuário da caixa de correio. Este atributo é opcional.  <br/> |
|**RoutingType** <br/> |Define o roteamento que é usado para a caixa de correio. O padrão é SMTP. Este atributo é opcional.  <br/> |
|**MailboxType** <br/> |Define o tipo de caixa de correio de um usuário de caixa de correio. Este atributo é opcional.  <br/> |
   
### <a name="child-elements"></a>Elementos filho

Nenhum.
  
### <a name="parent-elements"></a>Elementos pai

|**Elemento**|**Descrição**|
|:-----|:-----|
|[EmailAddresses](emailaddresses.md) <br/> |Representa uma coleção de endereços de email de um contato.  <br/> |
   
## <a name="remarks"></a>Coment�rios

Este elemento foi introduzido no Exchange Server 2013.
  
O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.
  
## <a name="element-information"></a>Informações de elemento

|||
|:-----|:-----|
|Namespace  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|Nome do esquema  <br/> |Esquema de tipos  <br/> |
|Arquivo de validação  <br/> |Types.xsd  <br/> |
|Pode estar vazio  <br/> |False  <br/> |
   
## <a name="see-also"></a>Ver também

- [Elementos XML do EWS no Exchange](ews-xml-elements-in-exchange.md)

