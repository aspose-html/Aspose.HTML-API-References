---
title: "ICSS2Properties.ListStyleType"
second_title: "Справочник API Aspose.HTML для Java"
description: "Свойство ICSS2Properties. Это свойство определяет внешний вид маркера элемента списка, если list-style-image имеет значение none или если изображение по указанному URI не может быть отображено. Значение none указывает отсутствие маркера, иначе существуют три типа маркеров: глифы, системы нумерации и алфавитные системы. Примечание. Нумерованные списки повышают доступность документа, упрощая навигацию по спискам."
type: docs

url: /ru/java/com.aspose.html.dom.css/icss2properties/liststyletype/
---
## ICSS2Properties.ListStyleType property

Это свойство определяет внешний вид маркера элемента списка, если ['list-style-image'](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#propdef-list-style-image) имеет значение 'none' или если изображение по указанному URI не может быть отображено. Значение 'none' указывает отсутствие маркера, иначе существуют три типа маркеров: глифы, системы нумерации и алфавитные системы. Примечание. Нумерованные списки повышают доступность документа, упрощая навигацию по спискам.

Глифы задаются с помощью disc, circle и square. Их точное отображение зависит от пользовательского агента.

Системы нумерации задаются с помощью:

decimal - Десятичные числа, начиная с 1.decimal-leading-zero - Десятичные числа, дополненные начальными нулями (например, 01, 02, 03, ..., 98, 99).lower-roman - Римские цифры нижнего регистра (i, ii, iii, iv, v и т.д.).upper-roman - Римские цифры верхнего регистра (I, II, III, IV, V и т.д.).hebrew - Традиционная еврейская нумерация.georgian - Традиционная грузинская нумерация (an, ban, gan, ..., he, tan, in, in-an, ...).armenian - Традиционная армянская нумерация.cjk-ideographic - Простой идеографический набор чиселhiragana - a, i, u, e, o, ka, ki, ...katakana - A, I, U, E, O, KA, KI, ...hiragana-iroha - i, ro, ha, ni, ...katakana-iroha - I, RO, HA, NI, HO, HE, TO, ...

```java
public String ListStyleType { get; set; }
```

### Возвращаемое значение

свойство list-style-type

### См. также

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
