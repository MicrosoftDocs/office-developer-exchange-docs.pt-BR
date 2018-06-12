---
title: IsReadReceipt
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- IsReadReceipt
api_type:
- schema
ms.assetid: e60e525f-c136-469a-b68b-b3dc01f400a6
description: O elemento IsReadReceipt indica se as mensagens de entrada devem ser confirmações de leitura na ordem para a condição ou uma exceção a ser aplicado.
ms.openlocfilehash: 78714aafb116a609a69d77b3b4f0fd15695bda34
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19824094"
---
# <a name="isreadreceipt"></a>IsReadReceipt

O elemento **IsReadReceipt** indica se as mensagens de entrada devem ser confirmações de leitura na ordem para a condição ou uma exceção a ser aplicado. 
  
```XML
<IsReadReceipt> true | false</IsReadReceipt>
```

 **Boolean**
## <a name="attributes-and-elements"></a>Attributes and elements

As seções a seguir descrevem os atributos e elementos filho elementos pai.
  
### <a name="attributes"></a>Atributos

Nenhum.
  
### <a name="child-elements"></a>Elementos filho

Nenhum.
  
### <a name="parent-elements"></a>Elementos pai

|**Elemento**|**Descrição**|
|:-----|:-----|
|[Condições](conditions.md) <br/> |Representa as condições que, quando atendida, irá disparar as ações de regra para essa regra.  <br/> |
|[Exceções](exceptions.md) <br/> |Representa todas as condições de exceção de regra disponíveis para a regra de caixa de entrada.  <br/> |
   
## <a name="text-value"></a>Text value

Um valor de texto de **true** indica que a mensagem deve ser uma confirmação de leitura na ordem para a condição ou uma exceção a ser aplicado. Se a mensagem não precisa ser uma confirmação de leitura para a condição ou uma exceção que se aplique, o valor é **false**.
  
## <a name="remarks"></a>Comentários

O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.
  
## <a name="element-information"></a>Informações de elemento

|||
|:-----|:-----|
|Namespace  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|Nome do esquema  <br/> |Esquema de mensagens  <br/> |
|Arquivo de validação  <br/> |Messages.xsd  <br/> |
|Pode ser vazio  <br/> |Verdadeiro  <br/> |
   
## <a name="see-also"></a>Ver também



- [Elementos XML do EWS no Exchange](ews-xml-elements-in-exchange.md)

