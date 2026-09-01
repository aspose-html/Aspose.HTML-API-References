---
title: "ICSSStyleDeclaration Интерфейс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.css.ICSSStyleDeclaration интерфейс. Интерфейс CSSStyleDeclaration представляет объект, являющийся блоком CSS‑объявлений, и предоставляет информацию о стилях, а также различные методы и свойства, связанные со стилями."
type: docs

url: /ru/java/com.aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

Интерфейс CSSStyleDeclaration представляет объект, который является блоком CSS‑объявлений, и предоставляет информацию о стилях и различные методы и свойства, связанные со стилями.

Объект CSSStyleDeclaration может быть получен с помощью трёх различных API:

Через HTMLElement.style, который работает с встроенными стилями отдельного элемента. Через API [`CSSStyleSheet`](../icssstylesheet/). Например, document.styleSheets[0].cssRules[0].style возвращает объект `CSSStyleDeclaration` для первого CSS‑правила в первой таблице стилей документа. Через Window.getComputedStyle(), который предоставляет объект `CSSStyleDeclaration` как интерфейс только для чтения.

```java
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<String>
```

## Свойства

| Имя | Описание |
| --- | --- |
[getCSSText]
[setCSSText] The parsable textual representation of the declaration block (excluding the surrounding curly braces). Setting this attribute will result in the parsing of the new value and resetting of all the properties in the declaration block including the removal or addition of properties. |
| [getItem](../../com.aspose.html.dom.css/icssstyledeclaration/item/) Используется для получения свойств, явно установленных в этом блоке объявлений. Порядок получаемых этим методом свойств не обязан соответствовать порядку их установки. Этот метод можно использовать для перебора всех свойств в этом блоке объявлений. |
| [getLength](../../com.aspose.html.dom.css/icssstyledeclaration/length/) Свойство только для чтения возвращает целое число свойств, явно установленных в этом блоке CSS‑объявлений. Диапазон допустимых индексов — от 0 до length‑1 включительно. |
| [getParentRule](../../com.aspose.html.dom.css/icssstyledeclaration/parentrule/) Свойство только для чтения CSSStyleDeclaration.parentRule возвращает объект CSSRule, являющийся родителем этого блока стилей, например, [`CSSStyleRule`](../icssstylerule/), представляющий стиль для CSS‑селектора. |

## Методы

| Имя | Описание |
| --- | --- |
| [getPropertyCSSValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(String) | Используется для получения объектного представления значения CSS‑свойства, если оно было явно установлено в этом блоке объявлений. Этот метод возвращает null, если свойство является сокращённым. Значения сокращённых свойств могут быть доступны и изменяться только как строки, с помощью методов getPropertyValue и setProperty. |
| [getPropertyPriority](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(String) | Используется для получения приоритета CSS‑свойства (например, квалификатора "important"), если свойство было явно установлено в этом блоке объявлений. |
| [getPropertyValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(String) | Метод интерфейса CSSStyleDeclaration.getPropertyValue() возвращает строку, содержащую значение указанного CSS‑свойства. |
| [removeProperty](../../com.aspose.html.dom.css/icssstyledeclaration/removeproperty/)(String) | Метод интерфейса CSSStyleDeclaration.removeProperty() удаляет свойство из объекта CSS‑объявления стиля. |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(String, String) | Метод интерфейса CSSStyleDeclaration.setProperty() используется для установки значения свойства с приоритетом по умолчанию в этом блоке объявлений. Приоритет по умолчанию не является "important", т.е. String.Empty. |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(String, String, String) | Метод интерфейса CSSStyleDeclaration.setProperty() используется для установки значения свойства с приоритетом по умолчанию в этом блоке объявлений. Приоритет по умолчанию не является "important", т.е. String.Empty. |

## Примечания

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Ссылка

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstyledeclaration](https://drafts.csswg.org/cssom/#cssstyledeclaration) – The CSSOM definition.

### См. также

* interface [ICSS2Properties](../icss2properties/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
