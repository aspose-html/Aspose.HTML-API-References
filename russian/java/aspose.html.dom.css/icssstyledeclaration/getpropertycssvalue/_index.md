---
title: "ICSSStyleDeclaration.GetPropertyCSSValue"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод ICSSStyleDeclaration. Используется для получения объектного представления значения CSS‑свойства, если оно было явно задано в этом блоке объявлений. Этот метод возвращает null, если свойство является сокращённым. Значения сокращённых свойств могут быть получены и изменены только как строки с помощью методов getPropertyValue и setProperty."
type: docs

url: /ru/java/com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/
---
## ICSSStyleDeclaration.GetPropertyCSSValue method

Используется для получения объектного представления значения CSS‑свойства, если оно было явно установлено в этом блоке объявлений. Этот метод возвращает null, если свойство является сокращённым. Значения сокращённых свойств могут быть доступны и изменяться только как строки, с помощью методов getPropertyValue и setProperty.

```java
public CSSValue GetPropertyCSSValue(String propertyName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| propertyName | String | propertyName — строка, представляющая имя свойства, которое нужно получить. |

### Возвращаемое значение

value — объект CSSValue, содержащий CSS‑значение свойства. Если его нет, возвращает null.

### См. также

* class [CSSValue](../../cssvalue/)
* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
