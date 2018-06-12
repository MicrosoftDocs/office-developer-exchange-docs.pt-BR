---
title: FolderClass
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- FolderClass
api_type:
- schema
ms.assetid: 0041d135-2869-4612-89a5-d1aa86aa1093
description: O elemento FolderClass representa a classe de pasta para uma pasta.
ms.openlocfilehash: 87be00563d0375abebf32159ff38d62d03112b95
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19752326"
---
# <a name="folderclass"></a>FolderClass

O elemento **FolderClass** representa a classe de pasta para uma pasta. 
  
```xml
<FolderClass/>
```

 **cadeia de caracteres**
## <a name="attributes-and-elements"></a>Attributes and elements

As seções a seguir descrevem os atributos e elementos filho elementos pai.
  
### <a name="attributes"></a>Atributos

Nenhum.
  
### <a name="child-elements"></a>Elementos filho

Nenhum.
  
### <a name="parent-elements"></a>Elementos pai

|**Elemento**|**Descrição**|
|:-----|:-----|
|[Folder](folder.md) <br/> |Representa uma pasta em uma caixa de correio.  <br/> |
|[CalendarFolder](calendarfolder.md) <br/> |Representa uma pasta de calendário em uma caixa de correio.  <br/> |
|[ContactsFolder](contactsfolder.md) <br/> |Representa uma pasta de contatos em uma caixa de correio.  <br/> |
|[SearchFolder](searchfolder.md) <br/> |Representa uma pasta de pesquisa em uma caixa de correio.  <br/> |
|[TasksFolder](tasksfolder.md) <br/> |Representa uma pasta de tarefa em uma caixa de correio.  <br/> |
   
## <a name="text-value"></a>Text value

É necessário um valor de texto. Classes de pasta geralmente começar com "IPF."
  
## <a name="remarks"></a>Comentários

O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o MicrosoftExchange Server 2007 que tem instalada a função de servidor de Acesso para Cliente.
  
## <a name="element-information"></a>Informações de elemento

|||
|:-----|:-----|
|Namespace  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|Nome do esquema  <br/> |Esquema de tipos  <br/> |
|Arquivo de validação  <br/> |Types.xsd  <br/> |
|Pode ser vazio  <br/> |False  <br/> |
   
## <a name="see-also"></a>Ver também



- [Elementos XML do EWS no Exchange](ews-xml-elements-in-exchange.md)

