---
title: TokenType (ClientAccessTokenType)
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: 96103f15-a3e0-497c-af21-90adbf9a4b14
description: O elemento TokenType identifica o tipo de token de acesso para cliente que será retornado na resposta GetClientAccessToken.
ms.openlocfilehash: 49ba2973967b12396e0c7f56129c89c40ccbcf97
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44466049"
---
# <a name="tokentype-clientaccesstokentype"></a>TokenType (ClientAccessTokenType)

O elemento **TokenType** identifica o tipo de token de acesso para cliente que será retornado na resposta **GetClientAccessToken** . 
  
```XML
<TokenType>CallerIdentity | ExtensionCallback | ScopedToken</TokenType>
```

 **ClientAccessTokenTypeType**
## <a name="attributes-and-elements"></a>Atributos e elementos

As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.
  
### <a name="attributes"></a>Atributos

Nenhum
  
### <a name="child-elements"></a>Elementos filho

Nenhum.
  
### <a name="parent-elements"></a>Elementos pai

[TokenRequest](tokenrequest.md)  |  [Token (ClientAccessTokenType)](token-clientaccesstokentype.md)
  
## <a name="text-value"></a>Valor de texto

Um valor de texto **CallerIdentity** significa que um token de acesso para cliente de identidade do chamador é retornado. Um valor de texto **ExtensionCallback** indica que um token de retorno de chamada de cliente de extensão é retornado. Um valor de texto de **ScopedToken** indica que o token de acesso do cliente é um token de escopo. 
  
## <a name="remarks"></a>Comentários

Este elemento foi introduzido no Exchange Server 2013.
  
O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.
  
## <a name="element-information"></a>Elemento de informações

|||
|:-----|:-----|
|Namespace  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|Nome do esquema  <br/> |Esquema de tipos  <br/> |
|Arquivo de validação  <br/> |Types. xsd  <br/> |
|Pode estar vazio  <br/> |falso  <br/> |
   

