---
title: StartTimeZone
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- StartTimeZone
api_type:
- schema
ms.assetid: d38c4dc1-4ecb-42a1-8d57-a451b16a2de2
description: O elemento StartTimeZone define o fuso horário para a hora de início de um CalendarItem ou MeetingRequest.
ms.openlocfilehash: fa88f676c0f6a7a2e934f51274942ed3bccbc789
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 05/31/2020
ms.locfileid: "44458520"
---
# <a name="starttimezone"></a>StartTimeZone

O elemento **StartTimeZone** define o fuso horário para a hora de início de um [CalendarItem](calendaritem.md) ou [MeetingRequest](meetingrequest.md).
  
```xml
<StartTimeZone Id="" Name="">
   <Periods/>
   <TransitionsGroups/>
   <Transitions/>
</StartTimeZone>
```

**TimeZoneDefinitionType**

## <a name="attributes-and-elements"></a>Atributos e elementos

As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.
  
### <a name="attributes"></a>Atributos

|**Atributo**|**Descrição**|
|:-----|:-----|
|Id  <br/> |Representa o identificador exclusivo da definição de fuso horário.  <br/> |
|Nome  <br/> |Representa o nome descritivo da definição de fuso horário.  <br/> |
   
### <a name="child-elements"></a>Elementos filho

|**Elemento**|**Descrição**|
|:-----|:-----|
|[Períodos](periods.md) <br/> |Representa uma matriz de elementos [period](period.md) que definem a diferença de tempo em diferentes estágios do fuso horário.  <br/> |
|[TransitionsGroups](transitionsgroups.md) <br/> |Representa uma matriz de elementos [TransitionsGroup](transitionsgroup.md) que especificam transições de fuso horário.  <br/> |
|[Transições](transitions.md) <br/> |Representa uma matriz de transições de fuso horário.  <br/> |
   
### <a name="parent-elements"></a>Elementos pai

|**Elemento**|**Descrição**|
|:-----|:-----|
|[CalendarItem](calendaritem.md) <br/> |Representa um item de calendário do Exchange.  <br/> |
|[MeetingRequest](meetingrequest.md) <br/> |Representa uma solicitação de reunião no repositório do Exchange.  <br/> |
   
## <a name="remarks"></a>Comentários

O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o Microsoft Exchange Server que tem a função de servidor de acesso para Cliente instalada.
  
## <a name="element-information"></a>Elemento de informações

|||
|:-----|:-----|
|Namespace  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|Nome do esquema  <br/> |Esquema de tipos  <br/> |
|Arquivo de validação  <br/> |Types. xsd  <br/> |
|Pode ser vazio  <br/> |False  <br/> |
   
## <a name="see-also"></a>Confira também

- [Elementos XML do EWS no Exchange](ews-xml-elements-in-exchange.md)

