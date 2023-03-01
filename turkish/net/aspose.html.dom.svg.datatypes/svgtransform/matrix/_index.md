---
title: SVGTransform.Matrix
second_title: Aspose.HTML for .NET API Referansı
description: SVGTransform mülk. Bu dönüşümü temsil eden matris. Matris nesnesi canlıdır yani SVGTransform nesnesinde yapılan herhangi bir değişiklik anında matris nesnesine yansıtılır ve bunun tersi de geçerlidir. Matris nesnesinin doğrudan değiştirilmesi durumunda yani SVGTransform arayüzünün kendisindeki yöntemler kullanılmadan SVGTransformun türü SVG_TRANSFORM_MATRIX. olarak değişir. SVG_TRANSFORM_MATRIX için matris a b c d e fyi içerir. kullanıcı tarafından sağlanan değerler. SVG_TRANSFORM_TRANSLATE için e ve f çeviri miktarlarını temsil edera 1 b 0 c 0 ve d  1. SVG_TRANSFORM_SCALE için a ve d ölçek miktarlarını temsil ederb 0  c 0 e 0 ve f  0. SVG_TRANSFORM_SKEWX ve SVG_TRANSFORM_SKEWY için a b c ve d verilen çarpıklığı verecek matrisi temsil edere 0 ve f  0. SVG_TRANSFORM_ROTATE için  a b c d e ve f birlikte verilen dönüşü sağlayacak matrisi temsil eder. Dönme merkez nokta 0 0 etrafında olduğunda e ve f sıfır olacaktır.
type: docs
weight: 20
url: /tr/net/aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

Bu dönüşümü temsil eden matris. Matris nesnesi canlıdır, yani SVGTransform nesnesinde yapılan herhangi bir değişiklik anında matris nesnesine yansıtılır ve bunun tersi de geçerlidir. Matris nesnesinin doğrudan değiştirilmesi durumunda (yani, SVGTransform arayüzünün kendisindeki yöntemler kullanılmadan), SVGTransform'un türü SVG_TRANSFORM_MATRIX. olarak değişir. SVG_TRANSFORM_MATRIX için, matris a, b, c, d, e, f'yi içerir. kullanıcı tarafından sağlanan değerler. SVG_TRANSFORM_TRANSLATE için e ve f çeviri miktarlarını temsil eder(a= 1, b= 0, c= 0 ve d = 1). SVG_TRANSFORM_SCALE için a ve d ölçek miktarlarını temsil eder(b= 0 , c= 0, e= 0 ve f = 0). SVG_TRANSFORM_SKEWX ve SVG_TRANSFORM_SKEWY için, a, b, c ve d verilen çarpıklığı verecek matrisi temsil eder(e= 0 ve f = 0). SVG_TRANSFORM_ROTATE için , a, b, c, d, e ve f birlikte verilen dönüşü sağlayacak matrisi temsil eder. Dönme merkez nokta (0, 0) etrafında olduğunda, e ve f sıfır olacaktır.

```csharp
public SVGMatrix Matrix { get; }
```

### Mülk değeri

Bu dönüşümü temsil eden matris.

### Ayrıca bakınız

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* ad alanı [Aspose.Html.Dom.Svg.DataTypes](../../svgtransform/)
* toplantı [Aspose.HTML](../../../)


