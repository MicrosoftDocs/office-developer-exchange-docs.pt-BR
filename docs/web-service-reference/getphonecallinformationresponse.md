---
title: GetPhoneCallInformationResponse
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- GetPhoneCallInformationResponse
api_type:
- schema
ms.assetid: 17f79875-46ec-4289-b974-b3c35af429cd
description: O elemento de GetPhoneCallInformationResponse define uma resposta a uma única solicitação GetPhoneCallInformation.
ms.openlocfilehash: 5a03d63198cd00997b8975b18a5ae0eb5fca1af2
ms.sourcegitcommit: 34041125dc8c5f993b21cebfc4f8b72f0fd2cb6f
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/11/2018
ms.locfileid: "19752605"
---
# <a name="getphonecallinformationresponse"></a>GetPhoneCallInformationResponse

O elemento de **GetPhoneCallInformationResponse** define uma resposta a uma única solicitação GetPhoneCallInformation. 
  
```xml
<GetPhoneCallInformationResponse ResponseClass="">
   <MessageText/>
   <ResponseCode/>
   <DescriptiveLinkKey/>
   <MessageXml/>   <PhoneCallInformation/>
</GetPhoneCallInformationResponse>
```

 **GetPhoneCallInformationResponseMessageType**
## <a name="attributes-and-elements"></a>Attributes and elements

As seções a seguir descrevem os atributos e elementos filho elementos pai.
  
### <a name="attributes"></a>Atributos

|**Attribute**|**Descrição**|
|:-----|:-----|
|**ResponseClass** <br/> | Descreve o status da resposta. <br/><br/>Os seguintes valores são válidos para este atributo: <br/> <br/>-Êxito  <br/>-Aviso  <br/>-Erro  <br/> |
   
#### <a name="responseclass-attribute-values"></a>Valores de atributo ResponseClass

|**Valor**|**Descrição**|
|:-----|:-----|
|**Sucesso** <br/> |Descreve uma solicitação que seja cumprida.  <br/> |
|**Warning** <br/> | Descreve uma solicitação que não foi processada. Um aviso pode ser retornado se ocorreu um erro quando um item na solicitação estava processando e itens subsequentes não pôde ser processados.<br/><br/> Estes são exemplos de fontes de avisos de: <br/> <br/>-O armazenamento do Exchange está offline durante o lote.  <br/>-O serviço de diretório do Active Directory está offline.  <br/>-Caixas de correio foram movidos.  <br/>-O banco de dados de mensagens (MDB) está offline.  <br/>-Uma senha expirou.  <br/>-Uma cota foi excedida.  <br/> |
|**Erro** <br/> | Descreve uma solicitação que não puder ser atendida. <br/><br/>Estes são exemplos de fontes de erros:  <br/><br/>-Inválido atributos e elementos  <br/>-Atributos ou elementos fora do intervalo  <br/>-Marca desconhecida  <br/>-Atributo ou elemento não é válido no contexto  <br/>-Tentativa de acesso não autorizado de qualquer cliente  <br/>-Falha server-side em resposta a uma chamada de cliente válida  <br/><br/>  Informações sobre o erro podem ser encontradas nos elementos [ResponseCode](responsecode.md) e [MessageText](messagetext.md) .  <br/> |
   
### <a name="child-elements"></a>Elementos filho

|**Elemento**|**Descrição**|
|:-----|:-----|
|[MessageText](messagetext.md) <br/> |Fornece uma descrição de texto do status da resposta.  <br/> |
|[ResponseCode](responsecode.md) <br/> |Fornece um código de erro que identifica o erro específico que enfrentaram a solicitação.  <br/> |
|[DescriptiveLinkKey](descriptivelinkkey.md) <br/> |No momento não utilizados e reservada para uso futuro. Esse elemento contém um valor de 0.  <br/> |
|[MessageXml](messagexml.md) <br/> |Fornece informações de resposta de erro adicionais.  <br/> |
|[PhoneCallInformation](phonecallinformation.md) <br/> |Especifica as informações de estado de uma chamada telefônica.  <br/> |
   
### <a name="parent-elements"></a>Elementos pai

Nenhum.
  
## <a name="remarks"></a>Comentários

O esquema que descreve este elemento está localizado no diretório virtual EWS do computador que está executando o Exchange Server com a função de servidor acesso para cliente instalada.
  
## <a name="element-information"></a>Informações de elemento

|||
|:-----|:-----|
|Namespace  <br/> |http://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|Nome do esquema  <br/> |Esquema de mensagens  <br/> |
|Arquivo de validação  <br/> |Messages.xsd  <br/> |
|Pode ser vazio  <br/> |False  <br/> |
   
## <a name="see-also"></a>Ver também

- [Elementos XML do EWS no Exchange](ews-xml-elements-in-exchange.md)

