---
title: DeleteFolderResponse
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- DeleteFolderResponse
api_type:
- schema
ms.assetid: 27578bda-ef0a-4a33-bccc-2c1bc1735424
description: O elemento DeleteFolderResponse define uma resposta a uma solicitação DeleteFolder.
ms.openlocfilehash: 58b814662c769784c5fd682a9e039863a9787d8d
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44458485"
---
# <a name="deletefolderresponse"></a>DeleteFolderResponse

O elemento **DeleteFolderResponse** define uma resposta a uma solicitação DeleteFolder. 
  
```xml
<DeleteFolderResponse>
   <ResponseMessages/>
</DeleteFolderResponse>
```

 **DeleteFolderResponseType**
## <a name="attributes-and-elements"></a>Atributos e elementos

As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.
  
### <a name="attributes"></a>Atributos

Nenhum
  
### <a name="child-elements"></a>Elementos filho

|**Elemento**|**Descrição**|
|:-----|:-----|
|[ResponseMessages](responsemessages.md) <br/> |Contém as mensagens de resposta para uma solicitação de serviços Web do Exchange.  <br/> |
   
### <a name="parent-elements"></a>Elementos pai

Nenhum
  
## <a name="remarks"></a>Comentários

O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o MicrosoftExchange Server 2007 que tem instalada a função de servidor de Acesso para Cliente.
  
## <a name="element-information"></a>Elemento de informações

|||
|:-----|:-----|
|Namespace  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|Nome do esquema  <br/> |Esquema de mensagens  <br/> |
|Arquivo de validação  <br/> |Messages.xsd  <br/> |
|Pode estar vazio  <br/> |False  <br/> |
   
## <a name="see-also"></a>Confira também

- [Operação DeleteFolder](deletefolder-operation.md) 
- [DeleteFolder](deletefolder.md)
- [Elementos XML do EWS no Exchange](ews-xml-elements-in-exchange.md)

