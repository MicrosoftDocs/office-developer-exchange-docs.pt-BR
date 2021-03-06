---
title: NormalizedBodyType
manager: sethgros
ms.date: 03/9/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
ms.assetid: c6973aee-ec7b-44c1-b328-f2204d9de5d1
description: O elemento NormalizedBodyType especifica se o corpo normalizado é retornado no formato de texto ou HTML.
ms.openlocfilehash: e5d968673403eba24a68c67175e3ebcbb35eca39
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44462658"
---
# <a name="normalizedbodytype"></a>NormalizedBodyType

O elemento **NormalizedBodyType** especifica se o corpo normalizado é retornado no formato de texto ou HTML. 
  
```XML
<NormalizedBodyType> Best | HTML | Text </NormalizedBodyType>
```

 **BodyTypeResponseType**
## <a name="attributes-and-elements"></a>Atributos e elementos

As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.
  
### <a name="attributes"></a>Atributos

Nenhum
  
### <a name="child-elements"></a>Elementos filho

Nenhum.
  
### <a name="parent-elements"></a>Elementos pai

[Shape](itemshape.md)
  
## <a name="text-value"></a>Valor de texto

O valor de texto do elemento **NormalizedBodyType** indica o formato em que o corpo normalizado é retornado. A tabela a seguir lista os valores possíveis para este elemento. 
  
****

|**Valor**|**Descrição**|
|:-----|:-----|
|Melhor  <br/> |A resposta retornará o conteúdo mais avançado disponível do corpo de texto. Isso é útil se for desconhecido se o conteúdo for texto ou HTML.  <br/> O corpo retornado será texto se o corpo armazenado for texto sem formatação. Caso contrário, a resposta retornará HTML se o corpo armazenado estiver em formato HTML ou RTF.  <br/> Esse é o valor padrão.  <br/> |
|HTML  <br/> |A resposta retornará um corpo normalizado como HTML.  <br/> |
|Texto  <br/> |A resposta retornará um corpo normalizado como texto sem formatação.  <br/> |
   
## <a name="remarks"></a>Comentários

Este elemento foi introduzido no Exchange Server 2013 Service Pack 1 (SP1).
  
O esquema que descreve este elemento está localizado no diretório virtual do IIS que hospeda os Serviços Web do Exchange.
  
## <a name="element-information"></a>Elemento de informações

|||
|:-----|:-----|
|Namespace  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|Nome do esquema  <br/> |Esquema de tipos  <br/> |
|Arquivo de validação  <br/> |Types. xsd  <br/> |
|Pode ser vazio  <br/> |Verdadeiro  <br/> |
   
## <a name="see-also"></a>Confira também



[Shape](itemshape.md)


- [Elementos XML do EWS no Exchange](ews-xml-elements-in-exchange.md)

