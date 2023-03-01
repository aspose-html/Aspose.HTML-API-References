---
title: FontMatcher.MatchFontFallback
second_title: Aspose.HTML for .NET API Referansı
description: FontMatcher yöntem. Yazı tipi arama klasörlerinde uygun bir yazı tipi yoksa bu yöntem çağrılır. fontMatchingProperties hangisi işleyebilircharCode  veyahükümsüz eğer böyle bir yazı tipi mevcut değilse.
type: docs
weight: 10
url: /tr/net/aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Yazı tipi arama klasörlerinde uygun bir yazı tipi yoksa bu yöntem çağrılır. *fontMatchingProperties* hangisi işleyebilir*charCode* , veya`hükümsüz` eğer böyle bir yazı tipi mevcut değilse.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Eşleşen yazı tipinin özellikleri. |
| charCode | UInt32 | Eşleşen yazı tipi kullanılarak oluşturulacak karakterin kodu. |

### Geri dönüş değeri

Yazı tipi verilerini içeren bir bayt dizisi veya`hükümsüz`.

### Ayrıca bakınız

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* ad alanı [Aspose.Html.Rendering.Fonts](../../fontmatcher/)
* toplantı [Aspose.HTML](../../../)


