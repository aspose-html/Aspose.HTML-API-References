---
title: "FontMatcher.MatchFontFallback"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод FontMatcher. Этот метод вызывается, если в папках поиска шрифтов не найден подходящий шрифт. Он должен возвращать шрифт истинного типа на основе fontMatchingProperties, который может отрисовывать charCode или null, если такой шрифт недоступен."
type: docs

url: /ru/java/com.aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Этот метод вызывается, если в папках поиска шрифтов не найден подходящий шрифт. Он должен возвращать шрифт истинного типа на основе *fontMatchingProperties*, который может отрисовать *charCode*, или `null`, если такой шрифт недоступен.

```java
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Свойства найденного шрифта. |
| charCode | UInt32 | Код символа, который будет отрисован с использованием найденного шрифта. |

### Возвращаемое значение

Массив байтов, содержащий данные шрифтов, или `null`.

### См. также

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* package [com.aspose.html.rendering.fonts](../../../com.aspose.html.rendering.fonts/)
* package [Aspose.HTML](../../../)
