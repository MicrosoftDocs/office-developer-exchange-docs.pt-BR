---
title: StartTime
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- StartTime
api_type:
- schema
ms.assetid: 1fac7937-7a06-4d66-9d2a-14423bcb3b37
description: O elemento StartTime representa o início de um período de tempo.
ms.openlocfilehash: 4346797d755bb6e577e1cacb8bec656a7562bf1f
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/25/2018
ms.locfileid: "19825560"
---
# <a name="starttime"></a>StartTime

O elemento **StartTime** representa o início de um período de tempo. 
  
```xml
<StartTime/
```

**dateTime**

## <a name="attributes-and-elements"></a>Attributes and elements

As seções a seguir descrevem os atributos e elementos filho elementos pai.
  
### <a name="attributes"></a>Atributos

Nenhum.
  
### <a name="child-elements"></a>Elementos filho

Nenhum.
  
### <a name="parent-elements"></a>Elementos pai

|**Elemento**|**Descrição**|
|:-----|:-----|
|[TimeWindow](timewindow.md) <br/> |Identifica o intervalo de tempo consultado para as informações de disponibilidade do usuário.  <br/><br/> Este é a expressão XPath para esse elemento:  <br/><br/>  `/GetUserAvailabilityRequest/FreeBusyViewOptions/TimeWindow` <br/> |
|[DetailedSuggestionsWindow](detailedsuggestionswindow.md) <br/> |Identifica o intervalo de tempo que está sendo consultado para obter informações detalhadas sobre reuniões sugeridas.  <br/><br/> Este é a expressão XPath para esse elemento: <br/> <br/>  `/GetUserAvailabilityRequest/SuggestionViewOptions/DetailedSuggestionsWindow` <br/> |
|[Duração (UserOofSettings)](duration-useroofsettings.md) <br/> | Especifica a duração para o qual o status de fora do escritório (OOF) está habilitado se o elemento [OofState](oofstate.md) for definido como **agendado**.  <br/><br/>  A seguir estão as expressões XPath possíveis para esse elemento: <br/> <br/>  `/SetUserOofSettingsRequest/UserOofSettings/Duration` <br/><br/>  `/GetUserOofSettingsResponse/OofSettings/Duration` <br/> |
|[CalendarEvent](calendarevent.md) <br/> |Representa uma ocorrência de item de calendário exclusivo. Isso é usado para fazer consultas sobre a disponibilidade. O elemento **StartTime** é necessária no elemento **CalendarEvent** . O elemento **StartTime** no elemento **CalendarEvent** é exclusivo para o tipo de **CalendarEvent** , embora ele contém os mesmos valores de faceta que contêm os elementos **StartTime** no tipo de **duração** .  <br/><br/> Este é a expressão XPath para esse elemento:  <br/> <br/> `/GetUserAvailabilityResponse/FreeBusyResponseArray/FreeBusyResponse/FreeBusyView/CalendarEventArray/CalendarEvent[i]` <br/> |
   
## <a name="text-value"></a>Text value

É necessário um valor de texto.
  
## <a name="remarks"></a>Comentários

O elemento [EndTime](endtime.md) representa o fim do intervalo de tempo. 
  
O esquema inclui muitos elementos [StartTime](starttime.md) . 
  
> [!NOTE]
> O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o MicrosoftExchange Server 2007 que tem instalada a função de servidor de Acesso para Cliente. 
  
## <a name="element-information"></a>Informações de elemento

|||
|:-----|:-----|
|Namespace  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|Nome do esquema  <br/> |Esquema de tipos  <br/> |
|Arquivo de validação  <br/> |Types.xsd  <br/> |
|Pode ser vazio  <br/> |False  <br/> |
   
## <a name="see-also"></a>Ver também

- [Operação GetUserAvailability](getuseravailability-operation.md)
- [Obtenção de disponibilidade do usuário](http://msdn.microsoft.com/library/d4133fcb-9b0f-4e6b-aadf-a389da83516a%28Office.15%29.aspx)

