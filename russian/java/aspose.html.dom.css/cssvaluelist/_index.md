---
title: "CSSValueList Класс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.css.CSSValueList класс. Интерфейс CSSValueList предоставляет абстракцию упорядоченной коллекции CSS‑значений."
type: docs

url: /ru/java/com.aspose.html.dom.css/cssvaluelist/
---
## CSSValueList class

Интерфейс CSSValueList предоставляет абстракцию упорядоченной коллекции значений CSS.

Примечание: Этот интерфейс был частью попытки создать типизированную модель объектного CSS. Эта попытка была прекращена, и большинство браузеров её не реализуют.

```java
public class CSSValueList : CSSValue, ICSSValueList, IEnumerable<CSSValue>
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CSSValueList](cssvaluelist/#constructor)() | Инициализирует новый экземпляр класса `CSSValueList`. |
| [CSSValueList](cssvaluelist/#constructor_1)(params CSSValue[]) | Инициализирует новый экземпляр класса `CSSValueList`. |
| [CSSValueList](cssvaluelist/#constructor_2)(IEnumerable&lt;CSSValue&gt;) | Инициализирует новый экземпляр класса `CSSValueList`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [cSSText](../../com.aspose.html.dom.css/cssvaluelist/csstext/) { get; set; } | Свойство cssText интерфейса [`CSSValue`](../cssvalue/) представляет текущее вычисленное значение CSS‑свойства. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) Код, определяющий тип значения. |
| [getItem](../../com.aspose.html.dom.css/cssvaluelist/item/) Метод item() интерфейса CSSValueList используется для получения CSSValue по порядковому индексу. |
| [getLength](../../com.aspose.html.dom.css/cssvaluelist/length/) Свойство только для чтения length интерфейса CSSValueList представляет количество CSSValue в списке. Диапазон допустимых значений индексов — от 0 до length‑1 включительно. |

## Методы

| Имя | Описание |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Определяет, равен ли указанный объект этому экземпляру. |
| [getEnumerator](../../com.aspose.html.dom.css/cssvaluelist/getenumerator/)() | Возвращает перечислитель, который перебирает элементы коллекции. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Возвращает хеш‑код для этого экземпляра. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvaluelist/getplatformtype/)() | Этот метод используется для получения типа объекта ECMAScript. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Возвращает строку, представляющую этот экземпляр. |

### См. также

* class [CSSValue](../cssvalue/)
* interface [ICSSValueList](../icssvaluelist/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
