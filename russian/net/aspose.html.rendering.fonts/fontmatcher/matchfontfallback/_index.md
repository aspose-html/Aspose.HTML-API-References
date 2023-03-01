---
title: FontMatcher.MatchFontFallback
second_title: Справочник по Aspose.HTML для .NET API
description: FontMatcher метод. Этот метод вызывается если в папках поиска шрифтов не найден подходящий шрифт. Он должен возвращать шрифт истинного типа на основеfontMatchingProperties который может отображатьcharCode  илинулевой если такой шрифт недоступен.
type: docs
weight: 10
url: /ru/net/aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Этот метод вызывается, если в папках поиска шрифтов не найден подходящий шрифт. Он должен возвращать шрифт истинного типа на основе*fontMatchingProperties* который может отображать*charCode* , или`нулевой` если такой шрифт недоступен.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Свойства совпадающего шрифта. |
| charCode | UInt32 | Код символа, который будет отображаться с использованием подобранного шрифта. |

### Возвращаемое значение

Массив байтов, содержащий данные шрифтов или`нулевой`.

### Смотрите также

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* пространство имен [Aspose.Html.Rendering.Fonts](../../fontmatcher/)
* сборка [Aspose.HTML](../../../)


