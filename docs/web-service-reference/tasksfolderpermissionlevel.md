---
title: TasksFolderPermissionLevel
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
localization_priority: Normal
api_name:
- TasksFolderPermissionLevel
api_type:
- schema
ms.assetid: 0f70b79b-3443-4048-b410-692d4e2464fc
description: O elemento TasksFolderPermissionLevel contém as permissões para a pasta padrão tarefas. Este elemento foi introduzido no Microsoft Exchange Server 2007 Service Pack 1 (SP1).
ms.openlocfilehash: 6e3988698575f0c1f935922d1642829a1f1addf9
ms.sourcegitcommit: 88ec988f2bb67c1866d06b361615f3674a24e795
ms.translationtype: MT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/03/2020
ms.locfileid: "44465328"
---
# <a name="tasksfolderpermissionlevel"></a>TasksFolderPermissionLevel

O elemento **TasksFolderPermissionLevel** contém as permissões para a pasta padrão tarefas. Este elemento foi introduzido no Microsoft Exchange Server 2007 Service Pack 1 (SP1). 
  
```xml
<TasksFolderPermissionLevel>
   None or Editor or Reviewer or Author or Custom
</TasksFolderPermissionLevel>
```

**DelegateFolderPermissionLevelType**

## <a name="attributes-and-elements"></a>Atributos e elementos

As seções a seguir descrevem os atributos, os elementos filhos e os elementos pai.
  
### <a name="attributes"></a>Atributos

Nenhum
  
### <a name="child-elements"></a>Elementos filho

Nenhum.
  
### <a name="parent-elements"></a>Elementos pai

|**Elemento**|**Descrição**|
|:-----|:-----|
|[DelegatePermissions](delegatepermissions.md) <br/> |Contém as configurações de nível de permissão de representante para um usuário. Este elemento foi introduzido no Exchange 2007 SP1.  <br/> |
   
## <a name="text-value"></a>Valor de texto

A tabela a seguir lista os valores de texto que representam os níveis de permissão.
  
**Valores de texto do nível de permissão**

|**Nível de permissão**|**Descrição**|
|:-----|:-----|
|Nenhum  <br/> |O usuário delegado não tem permissões de acesso à pasta tarefas.  <br/> |
|Revisor  <br/> |O usuário delegado pode ler itens na pasta tarefas.  <br/> |
|Autor  <br/> |O usuário delegado pode ler e criar itens na pasta tarefas.  <br/> |
|Editor  <br/> |O usuário delegado pode ler, criar e modificar itens na pasta tarefas.  <br/> |
|Personalizado  <br/> |O usuário delegado tem permissões de acesso personalizadas à pasta tarefas.  <br/> |
   
## <a name="remarks"></a>Comentários

O esquema que descreve este elemento está localizado no diretório virtual do EWS do computador que está executando o Microsoft Exchange Server 2007 que tem a função de servidor de acesso para Cliente instalada.
  
## <a name="element-information"></a>Elemento de informações

|||
|:-----|:-----|
|Namespace  <br/> |https://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|Nome do esquema  <br/> |Esquema de tipos  <br/> |
|Arquivo de validação  <br/> |Types. xsd  <br/> |
|Pode ser vazio  <br/> |False  <br/> |
   
## <a name="see-also"></a>Confira também

- [Operação AddDelegate](adddelegate-operation.md)
- [Operação UpdateDelegate](updatedelegate-operation.md)
- [Elementos XML do EWS no Exchange](ews-xml-elements-in-exchange.md)
- [Adicionar representantes](https://msdn.microsoft.com/library/3a744150-66a3-4a13-9433-793603ba5038%28Office.15%29.aspx)

