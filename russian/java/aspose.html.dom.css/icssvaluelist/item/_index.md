---
title: "ICSSValueList.Item"
second_title: "Справочник API Aspose.HTML для Java"
description: "Свойство ICSSValueList. Этот метод используется для получения CSSValue по порядковому индексу. Порядок в этой коллекции соответствует порядку значений в CSS‑свойстве стиля. Если индекс больше или равен количеству значений в списке, метод возвращает null"
type: docs

url: /ru/java/com.aspose.html.dom.css/icssvaluelist/item/
---
## ICSSValueList indexer

Этот метод используется для получения CSSValue по порядковому индексу. Порядок в этой коллекции представляет порядок значений в свойстве CSS‑стиля. Если индекс больше или равен количеству значений в списке, возвращается null.

Смотрите также [CSSOM](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList)[#CSSValueList](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList).

```java
public CSSValue this[int index] { get; }
```

### Возвращаемое значение

Элемент [`CSSValue`](../../cssvalue/) на позиции индекса в [`CSSValueList`](../../cssvaluelist/), или null, если индекс недействителен.

### Property Value

Индекс в коллекции.

## Примечания

Эта возможность изначально была определена в спецификации [DOM Style Level 2](https://www.w3.org/TR/DOM-Level-2-Style), но с тех пор была исключена из всех усилий по стандартизации.

Она была заменена современной, но несовместимой, [CSS Typed Object Model API](https://developer.mozilla.org/en-US/docs/Web/API/CSS_Typed_OM_API), которая теперь находится в процессе стандартизации.

### См. также

* class [CSSValue](../../cssvalue/)
* interface [ICSSValueList](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
