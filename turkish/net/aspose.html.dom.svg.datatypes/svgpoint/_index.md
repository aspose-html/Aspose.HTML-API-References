---
title: Class SVGPoint
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Svg.DataTypes.SVGPoint sınıf. SVG DOM arabirimlerinin çoğu SVGPoint sınıfındaki nesnelere atıfta bulunur. Bir SVGPoint bir x y koordinat çiftidir. Matris işlemlerinde kullanıldığında bir SVGPoint şu biçimde bir vektör olarak ele alınır x y 1 Bir SVGRect nesnesi salt okunur olarak belirlenmişse o zaman özniteliklerinden birine atamaya çalışmak bir istisnanın atılmasına neden olur.
type: docs
weight: 1250
url: /tr/net/aspose.html.dom.svg.datatypes/svgpoint/
---
## SVGPoint class

SVG DOM arabirimlerinin çoğu, SVGPoint sınıfındaki nesnelere atıfta bulunur. Bir SVGPoint, bir (x, y) koordinat çiftidir. Matris işlemlerinde kullanıldığında, bir SVGPoint şu biçimde bir vektör olarak ele alınır: [x] [y] [1] Bir SVGRect nesnesi salt okunur olarak belirlenmişse, o zaman özniteliklerinden birine atamaya çalışmak bir istisnanın atılmasına neden olur.

```csharp
public class SVGPoint : SVGValueType
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [X](../../aspose.html.dom.svg.datatypes/svgpoint/x/) { get; set; } | X koordinatı. |
| [Y](../../aspose.html.dom.svg.datatypes/svgpoint/y/) { get; set; } | Y koordinatı. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Yönetilmeyen ve - isteğe bağlı olarak - yönetilen kaynakları serbest bırakır. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Bu yöntem ECMAScript nesnesini almak için kullanılır.Type . |
| [MatrixTransform](../../aspose.html.dom.svg.datatypes/svgpoint/matrixtransform/)(SVGMatrix) | Bu SVGPoint nesnesine 2x3 matris dönüşümü uygular ve yeni, dönüştürülmüş bir SVGPoint nesnesi döndürür: newpoint = matrix* thispoint |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgpoint/tostring/)() | a döndürürString bu örneği temsil eder. |

### Ayrıca bakınız

* class [SVGValueType](../svgvaluetype/)
* ad alanı [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* toplantı [Aspose.HTML](../../)


