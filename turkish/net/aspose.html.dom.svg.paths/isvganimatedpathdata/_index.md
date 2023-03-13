---
title: Interface ISVGAnimatedPathData
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Svg.Paths.ISVGAnimatedPathData arayüz. SVGAnimatedPathData arabirimi SVG yolu verilerini tutan d özniteliğine sahip öğeleri ve bu özniteliği canlandırma yeteneğini destekler.
type: docs
weight: 1680
url: /tr/net/aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

SVGAnimatedPathData arabirimi, SVG yolu verilerini tutan 'd' özniteliğine sahip öğeleri ve bu özniteliği canlandırma yeteneğini destekler.

```csharp
public interface ISVGAnimatedPathData
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AnimatedPathSegList](../../aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) { get; } | SVG'nin sözdizimiyle bire bir eşleşen bir biçimde 'd' özniteliğinin geçerli animasyonlu içeriğine erişim sağlar. Belirtilen öznitelik veya özellik canlandırılıyorsa, öznitelik veya özelliğin geçerli animasyonlu değerini içerir ve hem nesnenin kendisi hem de içeriği salt okunurdur. Belirtilen öznitelik veya özellik şu anda canlandırılmıyorsa, pathSegList. ile aynı değeri içerir. |
| [PathSegList](../../aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) { get; } | SVG'nin sözdizimiyle bire bir eşleşen bir biçimde 'd' özniteliğinin temel (yani statik) içeriğine erişim sağlar. Dolayısıyla, 'd' özniteliği bir "mutlak hareket (M)" ve bir "mutlak ark (A)" komutuna sahipse, pathSegList'in iki girişi olacaktır: bir SVG_PATHSEG_MOVETO_ABS ve bir SVG_PATHSEG_ARC_ABS. |

### Ayrıca bakınız

* ad alanı [Aspose.Html.Dom.Svg.Paths](../../aspose.html.dom.svg.paths/)
* toplantı [Aspose.HTML](../../)


