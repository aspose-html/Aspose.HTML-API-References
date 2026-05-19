---
title: "ICSS2Properties.UnicodeBidi"
second_title: "Справочник API Aspose.HTML для Java"
description: "ICSS2Properties property. Значения этого свойства имеют следующие значения"
type: docs

url: /ru/java/com.aspose.html.dom.css/icss2properties/unicodebidi/
---
## ICSS2Properties.UnicodeBidi property

Значения этого свойства имеют следующие значения:

normal - Элемент не открывает дополнительный уровень вложения относительно двунаправленного алгоритма. Для встроенных (inline) элементов неявное переупорядочивание работает через границы элементов. embed - Если элемент является inline, это значение открывает дополнительный уровень вложения относительно двунаправленного алгоритма. Направление этого уровня задаётся свойством ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction). Внутри элемента переупорядочивание происходит неявно. Это соответствует добавлению LRE (U+202A; для 'direction: ltr') или RLE (U+202B; для 'direction: rtl') в начало элемента и PDF (U+202C) в конец элемента. bidi-override - Если элемент является inline или блочным элементом, содержащим только inline‑элементы, это создаёт переопределение. Это означает, что внутри элемента переупорядочивание строго следует последовательности, указанной в свойстве ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction); неявная часть двунаправленного алгоритма игнорируется. Это соответствует добавлению LRO (U+202D; для 'direction: ltr') или RLO (U+202E; для 'direction: rtl') в начало элемента и PDF (U+202C) в конец элемента.

```java
public String UnicodeBidi { get; set; }
```

### Возвращаемое значение

свойство unicode-bidi

### См. также

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
