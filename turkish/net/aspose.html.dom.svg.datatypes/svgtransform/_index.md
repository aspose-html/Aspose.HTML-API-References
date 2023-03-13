---
title: Class SVGTransform
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Svg.DataTypes.SVGTransform sınıf. SVGTransform bir SVGTransformList içindeki bileşen dönüşümlerinden birinin arayüzüdür bu nedenle bir SVGTransform nesnesi bir dönüştürme öznitelik belirtimi içindeki tek bir bileşene örneğin ölçek veya matris karşılık gelir.
type: docs
weight: 1300
url: /tr/net/aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform, bir SVGTransformList içindeki bileşen dönüşümlerinden birinin arayüzüdür; bu nedenle, bir SVGTransform nesnesi, bir 'dönüştürme' öznitelik belirtimi içindeki tek bir bileşene (örneğin, 'ölçek(…)' veya 'matris(…)') karşılık gelir.

```csharp
public class SVGTransform : SVGValueType
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Angle](../../aspose.html.dom.svg.datatypes/svgtransform/angle/) { get; } | SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX ve SVG_TRANSFORM_SKEWY için uygunluk özelliği. Belirtilen açıyı tutar. SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE ve SVG_TRANSFORM_SCALE için açı sıfır olacaktır. |
| [Matrix](../../aspose.html.dom.svg.datatypes/svgtransform/matrix/) { get; } | Bu dönüşümü temsil eden matris. Matris nesnesi canlıdır, yani SVGTransform nesnesinde yapılan herhangi bir değişiklik anında matris nesnesine yansıtılır ve bunun tersi de geçerlidir. Matris nesnesinin doğrudan değiştirilmesi durumunda (yani, SVGTransform arayüzünün kendisindeki yöntemler kullanılmadan), SVGTransform'un türü SVG_TRANSFORM_MATRIX. olarak değişir. SVG_TRANSFORM_MATRIX için, matris a, b, c, d, e, f'yi içerir. kullanıcı tarafından sağlanan değerler. SVG_TRANSFORM_TRANSLATE için e ve f çeviri miktarlarını temsil eder(a= 1, b= 0, c= 0 ve d = 1). SVG_TRANSFORM_SCALE için a ve d ölçek miktarlarını temsil eder(b= 0 , c= 0, e= 0 ve f = 0). SVG_TRANSFORM_SKEWX ve SVG_TRANSFORM_SKEWY için, a, b, c ve d verilen çarpıklığı verecek matrisi temsil eder(e= 0 ve f = 0). SVG_TRANSFORM_ROTATE için , a, b, c, d, e ve f birlikte verilen dönüşü sağlayacak matrisi temsil eder. Dönme merkez nokta (0, 0) etrafında olduğunda, e ve f sıfır olacaktır. |
| [Type](../../aspose.html.dom.svg.datatypes/svgtransform/type/) { get; } | Bu arabirimde tanımlanan SVG_TRANSFORM_* sabitlerinden biri tarafından belirtilen değerin türü. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Yönetilmeyen ve - isteğe bağlı olarak - yönetilen kaynakları serbest bırakır. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Bu yöntem ECMAScript nesnesini almak için kullanılır.Type . |
| [SetMatrix](../../aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | Dönüştürme türünü, yeni dönüşümü tanımlayan parametre matrisiyle SVG_TRANSFORM_MATRIX olarak ayarlar. Parametre matrisindeki değerler kopyalanır, matrix parametresi SVGTransform::matrix. yerine geçmez |
| [SetRotate](../../aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | Dönüşüm türünü SVG_TRANSFORM_ROTATE olarak ayarlar, açı parametresi dönüş açısını tanımlar ve cx ve cy parametreleri isteğe bağlı dönüş merkezini tanımlar. |
| [SetScale](../../aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | Ölçek tutarlarını tanımlayan sx ve sy parametreleriyle dönüşüm türünü SVG_TRANSFORM_SCALE olarak ayarlar. |
| [SetSkewX](../../aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | Dönüştürme türünü SVG_TRANSFORM_SKEWX olarak ayarlar, açı parametresi eğim miktarını tanımlar. |
| [SetSkewY](../../aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | Dönüştürme türünü SVG_TRANSFORM_SKEWY olarak ayarlar, açı parametresi eğim miktarını tanımlar. |
| [SetTranslate](../../aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | Çeviri miktarlarını tanımlayan tx ve ty parametreleriyle dönüştürme türünü SVG_TRANSFORM_TRANSLATE olarak ayarlar. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgtransform/tostring/)() | a döndürürString bu örneği temsil eder. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | Bir 'matris(…)' dönüşümü. |
| const [SVG_TRANSFORM_ROTATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | Bir 'döndür(…)' dönüşümü. |
| const [SVG_TRANSFORM_SCALE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | Bir 'ölçek(…)' dönüşümü. |
| const [SVG_TRANSFORM_SKEWX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | Bir 'skewX(…)' dönüşümü. |
| const [SVG_TRANSFORM_SKEWY](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | Bir 'çarpıkY(…)' dönüşümü. |
| const [SVG_TRANSFORM_TRANSLATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | Bir 'çevir(…)' dönüşümü. |
| const [SVG_TRANSFORM_UNKNOWN](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | Birim tipi önceden tanımlanmış tiplerden biri değil. Bu türde yeni bir değer tanımlamaya veya mevcut bir değeri bu türe değiştirmeye çalışmak geçersizdir. |

### Ayrıca bakınız

* class [SVGValueType](../svgvaluetype/)
* ad alanı [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* toplantı [Aspose.HTML](../../)


