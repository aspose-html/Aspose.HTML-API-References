---
title: ICSS2Properties.ListStyleType
second_title: Aspose.HTML for .NET API Reference
description: ICSS2Properties property. This property specifies appearance of the list item marker if list-style-image has the value none or if the image pointed to by the URI cannot be displayed. The value none specifies no marker otherwise there are three types of marker glyphs numbering systems and alphabetic systems. Note. Numbered lists improve document accessibility by making lists easier to navigate
type: docs
weight: 620
url: /net/aspose.html.dom.css/icss2properties/liststyletype/
---
## ICSS2Properties.ListStyleType property

This property specifies appearance of the list item marker if ['list-style-image'](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#propdef-list-style-image) has the value 'none' or if the image pointed to by the URI cannot be displayed. The value 'none' specifies no marker, otherwise there are three types of marker: glyphs, numbering systems, and alphabetic systems. Note. Numbered lists improve document accessibility by making lists easier to navigate.

Glyphs are specified with disc, circle, and square. Their exact rendering depends on the user agent.

Numbering systems are specified with:

decimal - Decimal numbers, beginning with 1.decimal-leading-zero - Decimal numbers padded by initial zeros (e.g., 01, 02, 03, ..., 98, 99).lower-roman - Lowercase roman numerals (i, ii, iii, iv, v, etc.).upper-roman - Uppercase roman numerals (I, II, III, IV, V, etc.).hebrew - Traditional Hebrew numbering.georgian - Traditional Georgian numbering (an, ban, gan, ..., he, tan, in, in-an, ...).armenian - Traditional Armenian numbering.cjk-ideographic - Plain ideographic numbershiragana - a, i, u, e, o, ka, ki, ...katakana - A, I, U, E, O, KA, KI, ...hiragana-iroha - i, ro, ha, ni, ho, he, to, ...katakana-iroha - I, RO, HA, NI, HO, HE, TO, ...

```csharp
public string ListStyleType { get; set; }
```

### Return Value

list-style-type property

### See Also

* interface [ICSS2Properties](../)
* namespace [Aspose.Html.Dom.Css](../../icss2properties/)
* assembly [Aspose.HTML](../../../)
