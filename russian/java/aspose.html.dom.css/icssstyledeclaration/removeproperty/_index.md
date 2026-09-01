---
title: "ICSSStyleDeclaration.RemoveProperty"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод ICSSStyleDeclaration. Интерфейс метода CSSStyleDeclaration.removeProperty удаляет свойство из объекта CSS‑стиля объявлений."
type: docs

url: /ru/java/com.aspose.html.dom.css/icssstyledeclaration/removeproperty/
---
## ICSSStyleDeclaration.RemoveProperty method

Метод интерфейса CSSStyleDeclaration.removeProperty() удаляет свойство из объекта CSS‑объявления стиля.

```java
public String RemoveProperty(String propertyName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| propertyName | String | propertyName — строка, представляющая имя свойства, которое следует удалить. Обратите внимание, что многословные имена свойств пишутся через дефис, а не в camelCase. |

### Возвращаемое значение

oldValue — DOMString, равный значению CSS‑свойства до его удаления.

### Исключения

| исключение | условие |
| --- | --- |
| DOMException | NO_MODIFICATION_ALLOWED_ERR: если свойство или блок объявлений доступен только для чтения. |

### См. также

* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
