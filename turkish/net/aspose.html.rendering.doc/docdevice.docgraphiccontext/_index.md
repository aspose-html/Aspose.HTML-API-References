---
title: Class DocDevice.DocGraphicContext
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Rendering.Doc.DocDeviceDocGraphicContext sınıf. DocDevice için geçerli grafik kontrol parametrelerini tutar. Bu parametreler grafik işleçlerinin yürüttüğü genel çerçeveyi tanımlar.
type: docs
weight: 4180
url: /tr/net/aspose.html.rendering.doc/docdevice.docgraphiccontext/
---
## DocDevice.DocGraphicContext class

DocDevice için geçerli grafik kontrol parametrelerini tutar. Bu parametreler, grafik işleçlerinin yürüttüğü genel çerçeveyi tanımlar.

```csharp
public class DocGraphicContext : GraphicContext
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [DocGraphicContext](docgraphiccontext/)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Karakter aralığını ayarlar veya alır. |
| virtual [FillBrush](../../aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | Yolların içini doldurmak için kullanılan fırça nesnesini ayarlar veya alır. |
| virtual [Font](../../aspose.html.rendering/graphiccontext/font/) { get; set; } | Metin oluşturmak için kullanılan gerçek tip yazı tipi nesnesini ayarlar veya alır. |
| virtual [FontSize](../../aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Metin yazı tipi boyutunu ayarlar veya alır. |
| virtual [FontStyle](../../aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Metin yazı tipi stilini ayarlar veya alır. |
| virtual [LineCap](../../aspose.html.rendering/graphiccontext/linecap/) { get; set; } | Vurgulanan herhangi bir açık yol için uç noktaların şeklini belirten kodu ayarlar veya alır. |
| virtual [LineDashOffset](../../aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Geçerli çizgi çizgi deseninin faz ofsetini ayarlar veya alır. |
| virtual [LineDashPattern](../../aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Yollar konturlandığında kullanılacak kısa çizgi deseninin açıklamasını ayarlar veya alır. |
| virtual [LineDashStyle](../../aspose.html.rendering/graphiccontext/linedashstyle/) { get; set; } | Setleri, konturlu bir yolun kesikli çizgilerinin stilini alır. |
| virtual [LineJoin](../../aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | Konturlu bir yolun bağlı parçaları arasındaki eklemlerin şeklini belirleyen kodu ayarlar veya alır. |
| virtual [LineWidth](../../aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | Vurulacak yolların kalınlığını ayarlar veya alır. |
| virtual [MiterLimit](../../aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | Konturlu yollar için azaltılmış çizgi birleştirmelerinin maksimum uzunluğunu ayarlar veya alır. Bu parametre, çizgi parçaları keskin açılarda birleştiğinde üretilen "çivilerin" uzunluğunu sınırlar. |
| virtual [StrokeBrush](../../aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | Konturlu yollar için kullanılan fırça nesnesini ayarlar veya alır. |
| virtual [TextInfo](../../aspose.html.rendering/graphiccontext/textinfo/) { get; } | Bir alır[`TextInfo`](../../aspose.html.rendering/textinfo/) işlenmiş metin hakkında bilgi içeren nesne. |
| override [TransformationMatrix](../../aspose.html.rendering.doc/docgraphiccontext/transformationmatrix/) { get; set; } | Dönüşüm matrisini ayarlar veya alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Clone](../../aspose.html.rendering.doc/docgraphiccontext/clone/)() | Yeni bir örneğini oluşturur[`GraphicContext`](../../aspose.html.rendering/graphiccontext/) mevcut bir örnekle aynı özellik değerlerine sahip sınıf. |
| override [Transform](../../aspose.html.rendering.doc/docgraphiccontext/transform/)(Matrix) | Geçerli dönüşüm matrisini, belirtilen matrisi çarparak değiştirin. |

### Ayrıca bakınız

* class [GraphicContext](../../aspose.html.rendering/graphiccontext/)
* class [DocDevice](../docdevice/)
* ad alanı [Aspose.Html.Rendering.Doc](../../aspose.html.rendering.doc/)
* toplantı [Aspose.HTML](../../)


