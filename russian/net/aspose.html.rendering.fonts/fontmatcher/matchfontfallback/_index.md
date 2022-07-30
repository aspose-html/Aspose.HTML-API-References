---
title: MatchFontFallback
second_title: Справочник по Aspose.HTML для .NET API
description: Этот метод вызывается если в папках поиска шрифтов не найден подходящий шрифт. Он должен возвращать шрифт истинного типа на основеfontMatchingPropertiesкоторый может отображатьcharCodeили null если такого шрифта нет.
type: docs
weight: 10
url: /ru/net/aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Этот метод вызывается, если в папках поиска шрифтов не найден подходящий шрифт. Он должен возвращать шрифт истинного типа на основе*fontMatchingProperties*который может отображать*charCode*или` null` если такого шрифта нет.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Свойства соответствующего шрифта. |
| charCode | UInt32 | Код символа, который будет отображаться с использованием подобранного шрифта. |

### Возвращаемое значение

Массив байтов, содержащий данные шрифтов или` null` .

### Смотрите также

* class [FontMatchingProperties](../../fontmatchingproperties)
* class [FontMatcher](../../fontmatcher)
* пространство имен [Aspose.Html.Rendering.Fonts](../../fontmatcher)
* сборка [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->