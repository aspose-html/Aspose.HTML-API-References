---
title: Interface ICSSCharsetRule
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Css.ICSSCharsetRule интерфейс. Интерфейс CSSCharsetRule представляет правило charset в таблице стилей CSS. Значение атрибута encoding не влияет на кодировку текстовых данных в объектах DOM эта кодировка всегда UTF16. После загрузки таблицы стилей значением атрибута encoding является значение найденное в правиле charset. Если в исходном документе не было charset CSSCharsetRule не создается. Значение атрибута encoding может также использоваться как подсказка для кодировки используемой при сериализации таблицы стилей.
type: docs
weight: 380
url: /ru/net/aspose.html.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

Интерфейс CSSCharsetRule представляет правило @charset в таблице стилей CSS. Значение атрибута encoding не влияет на кодировку текстовых данных в объектах DOM; эта кодировка всегда UTF-16. После загрузки таблицы стилей значением атрибута encoding является значение, найденное в правиле @charset. Если в исходном документе не было @charset, CSSCharsetRule не создается. Значение атрибута encoding может также использоваться как подсказка для кодировки, используемой при сериализации таблицы стилей.

```csharp
public interface ICSSCharsetRule : ICSSRule
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Encoding](../../aspose.html.dom.css/icsscharsetrule/encoding/) { get; set; } | Информация о кодировке, используемая в этом правиле @charset. |

### Смотрите также

* interface [ICSSRule](../icssrule/)
* пространство имен [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* сборка [Aspose.HTML](../../)


