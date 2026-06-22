---
title: "Класс CSSValue"
second_title: "Справочник API Aspose.HTML для Java"
description: "класс com.aspose.html.dom.css.CSSValue. Представляет простое или сложное значение. Объект CSSValue встречается только в контексте свойства CSS."
type: docs

url: /ru/java/com.aspose.html.dom.css/cssvalue/
---
## CSSValue class

Представляет простое или сложное значение. Объект CSSValue встречается только в контексте свойства CSS.

```java
public abstract class CSSValue : DOMObject
```

## Свойства

| Имя | Описание |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | Свойство cssText интерфейса `CSSValue` представляет текущее вычисленное значение свойства CSS. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) Код, определяющий тип значения. |

## Методы

| Имя | Описание |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Определяет, равен ли указанный объект этому экземпляру. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Возвращает хеш‑код для этого экземпляра. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | Этот метод используется для получения типа объекта ECMAScript. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Возвращает строку, представляющую этот экземпляр. |
| [operator ==](../../com.aspose.html.dom.css/cssvalue/op_equality/) |  |
| [operator !=](../../com.aspose.html.dom.css/cssvalue/op_inequality/) |  |

## Поля

| Имя | Описание |
| --- | --- |
| const [CSS_CUSTOM](../../com.aspose.html.dom.css/cssvalue/css_custom/) | Значение является пользовательским. |
| const [CSS_INHERIT](../../com.aspose.html.dom.css/cssvalue/css_inherit/) | Значение наследуется, и cssText содержит "inherit". |
| const [CSS_PRIMITIVE_VALUE](../../com.aspose.html.dom.css/cssvalue/css_primitive_value/) | Значение является примитивным, и экземпляр интерфейса CSSPrimitiveValue можно получить, используя специфические для привязки методы приведения типов к этому экземпляру интерфейса CSSValue. |
| const [CSS_VALUE_LIST](../../com.aspose.html.dom.css/cssvalue/css_value_list/) | Значение представляет собой список CSSValue, и экземпляр интерфейса CSSValueList можно получить, используя методы приведения, специфичные для привязки, на этом экземпляре интерфейса CSSValue. |

### См. также

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
