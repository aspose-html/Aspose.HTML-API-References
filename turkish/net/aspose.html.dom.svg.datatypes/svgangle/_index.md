---
title: Class SVGAngle
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Svg.DataTypes.SVGAngle sınıf. SVGAngle arayüzü açı temel veri tipine karşılık gelir.
type: docs
weight: 1060
url: /tr/net/aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

SVGAngle arayüzü açı temel veri tipine karşılık gelir.

```csharp
public class SVGAngle : SVGValueType
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [UnitType](../../aspose.html.dom.svg.datatypes/svgangle/unittype/) { get; } | Bu arabirimde tanımlanan SVG_ANGLETYPE_* sabitlerinden biri tarafından belirtilen değerin türü. |
| [Value](../../aspose.html.dom.svg.datatypes/svgangle/value/) { get; set; } | Derece cinsinden kayan nokta değeri olarak açı değeri. Bu özniteliğin ayarlanması, valueInSpecifiedUnits ve valueAsString'in bu ayarı yansıtacak şekilde otomatik olarak güncellenmesine neden olur. |
| [ValueAsString](../../aspose.html.dom.svg.datatypes/svgangle/valueasstring/) { get; set; } | UnitType tarafından ifade edilen birimlerde dize değeri olarak açı değeri. Bu özniteliğin ayarlanması, value, valueInSpecifiedUnits ve unitType'ın bu ayarı yansıtacak şekilde otomatik olarak güncellenmesine neden olur. |
| [ValueInSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/valueinspecifiedunits/) { get; set; } | UnitType tarafından ifade edilen birimlerde kayan nokta değeri olarak açı değeri. Bu özniteliğin ayarlanması, value ve valueAsString'in bu ayarı yansıtacak şekilde otomatik olarak güncellenmesine neden olur. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | Aynı temel depolanan değeri koruyun, ancak depolanan birim tanımlayıcısını verilen unitType'a sıfırlayın. UnitType, valueInSpecifiedUnits ve valueAsString nesne nitelikleri bu yöntemin bir sonucu olarak değiştirilebilir. |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Yönetilmeyen ve - isteğe bağlı olarak - yönetilen kaynakları serbest bırakır. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Bu yöntem ECMAScript nesnesini almak için kullanılır.Type . |
| [NewValueSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | İlişkili bir unitType ile değeri bir sayı olarak sıfırlayın, böylece nesnedeki tüm özniteliklerin değerlerini değiştirin. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgangle/tostring/)() | a döndürürString bu örneği temsil eder. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | Birim türü açıkça derece olarak ayarlandı. |
| const [SVG_ANGLETYPE_GRAD](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | Birim türü radyandır. |
| const [SVG_ANGLETYPE_RAD](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | Birim türü radyandır. |
| const [SVG_ANGLETYPE_UNKNOWN](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | Birim türü, önceden tanımlanmış birim türlerinden biri değil. Bu türde yeni bir değer tanımlamaya veya mevcut bir değeri bu türe değiştirmeye çalışmak geçersizdir. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | Birim türü sağlanmadı (yani, birimsiz bir değer belirtildi). Açılar için birimsiz bir değer, derece belirtilmiş gibi ele alınır. |

### Ayrıca bakınız

* class [SVGValueType](../svgvaluetype/)
* ad alanı [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* toplantı [Aspose.HTML](../../)


