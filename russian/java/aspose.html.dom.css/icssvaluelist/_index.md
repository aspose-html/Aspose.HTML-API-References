---
title: "ICSSValueList Интерфейс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.css.ICSSValueList интерфейс. Интерфейс CSSValueList наследуется от интерфейса CSSValue и предоставляет абстракцию упорядоченной коллекции значений CSS."
type: docs

url: /ru/java/com.aspose.html.dom.css/icssvaluelist/
---
## ICSSValueList interface

Интерфейс CSSValueList наследуется от интерфейса [`CSSValue`](../cssvalue/) и предоставляет абстракцию упорядоченной коллекции значений CSS.

Некоторые свойства допускают пустой список в своей синтаксисе. В этом случае такие свойства используют идентификатор none. Таким образом, пустой список означает, что свойство имеет значение none.

Элементы в CSSValueList доступны через целочисленный индекс, начиная с 0.

```java
public interface ICSSValueList
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssvaluelist/item/) Этот метод используется для получения CSSValue по порядковому индексу. Порядок в этой коллекции представляет порядок значений в свойстве стиля CSS. Если индекс больше или равен количеству значений в списке, возвращается null. |
| [getLength](../../com.aspose.html.dom.css/icssvaluelist/length/) Свойство length только для чтения интерфейса CSSValueList представляет количество CSSValue в списке. Диапазон допустимых значений индексов — от 0 до length‑1 включительно. |

## Примечания

Этот интерфейс был частью попытки создать типизированную модель объектного CSS (CSS Object Model). Эта попытка была прекращена, и большинство браузеров её не реализуют.

Чтобы достичь вашей цели, вы можете использовать:

нетипизированную [CSS Object Model](https://drafts.csswg.org/cssom/), широко поддерживаемую, или современный [CSS Typed Object Model API](https://drafts.css-houdini.org/css-typed-om/#stylevalue-objects), менее поддерживаемый и считающийся экспериментальным.

### См. также

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
