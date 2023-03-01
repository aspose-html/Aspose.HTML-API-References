---
title: Class SVGLength
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Svg.DataTypes.SVGLength sınıf. SVGLength arabirimi uzunluk temel veri türüne karşılık gelir. Bir SVGLength nesnesi salt okunur olarak belirlenebilir bu nesneyi değiştirme girişimlerinin aşağıda açıklandığı gibi bir istisnanın atılmasına neden olacağı anlamına gelir.
type: docs
weight: 1200
url: /tr/net/aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

SVGLength arabirimi, uzunluk temel veri türüne karşılık gelir. Bir SVGLength nesnesi salt okunur olarak belirlenebilir; bu, nesneyi değiştirme girişimlerinin, aşağıda açıklandığı gibi bir istisnanın atılmasına neden olacağı anlamına gelir.

```csharp
public class SVGLength : SVGValueType
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [UnitType](../../aspose.html.dom.svg.datatypes/svglength/unittype/) { get; } | Bu arabirimde tanımlanan SVG_LENGTHTYPE_* sabitlerinden biri tarafından belirtilen değerin türü. |
| [Value](../../aspose.html.dom.svg.datatypes/svglength/value/) { get; set; } | Kullanıcı birimleri cinsinden kayan nokta değeri olarak değer. Bu özniteliğin ayarlanması, valueInSpecifiedUnits ve valueAsString'in bu ayarı yansıtacak şekilde otomatik olarak güncellenmesine neden olur. |
| [ValueAsString](../../aspose.html.dom.svg.datatypes/svglength/valueasstring/) { get; set; } | UnitType tarafından ifade edilen birimlerde dize değeri olarak değer. Bu özniteliğin ayarlanması, value, valueInSpecifiedUnits ve unitType'ın bu ayarı yansıtacak şekilde otomatik olarak güncellenmesine neden olur. |
| [ValueInSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/valueinspecifiedunits/) { get; set; } | UnitType tarafından ifade edilen birimlerde kayan nokta değeri olarak değer. Bu özniteliğin ayarlanması, value ve valueAsString'in bu ayarı yansıtacak şekilde otomatik olarak güncellenmesine neden olur. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | Aynı temel depolanan değeri koruyun, ancak depolanan birim tanımlayıcısını verilen unitType'a sıfırlayın. UnitType, valueInSpecifiedUnits ve valueAsString nesne nitelikleri bu yöntemin bir sonucu olarak değiştirilebilir. Örneğin, orijinal değer "0,5cm" ise ve yöntem milimetreye dönüştürmek için çağrıldıysa, o zaman unitType SVG_LENGTHTYPE_MM olarak değiştirilir, valueInSpecifiedUnits sayısal değer 5 olarak değiştirilir ve valueAsString "5mm" olarak değiştirilir. |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Yönetilmeyen ve - isteğe bağlı olarak - yönetilen kaynakları serbest bırakır. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Bu yöntem ECMAScript nesnesini almak için kullanılır.Type . |
| [NewValueSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | İlişkili bir unitType ile değeri bir sayı olarak sıfırlayın, böylece nesnedeki tüm özniteliklerin değerlerini değiştirin. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svglength/tostring/)() | a döndürürString bu örneği temsil eder. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | CSS2. 'de tanımlanan cm birimleri kullanılarak bir değer belirtildi |
| const [SVG_LENGTHTYPE_EMS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | CSS2. 'de tanımlanan em birimleri kullanılarak bir değer belirtildi |
| const [SVG_LENGTHTYPE_EXS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | CSS2. 'de tanımlanan eski birimler kullanılarak bir değer belirtildi |
| const [SVG_LENGTHTYPE_IN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | CSS2. 'de tanımlanan in birimleri kullanılarak bir değer belirtildi |
| const [SVG_LENGTHTYPE_MM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | CSS2. 'de tanımlanan mm birimleri kullanılarak bir değer belirtildi |
| const [SVG_LENGTHTYPE_NUMBER](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | Kullanıcı birimleri cinsinden bir değeri gösteren birim türü sağlanmadı (yani birimsiz bir değer belirtildi). |
| const [SVG_LENGTHTYPE_PC](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | CSS2. 'de tanımlanan bilgisayar birimleri kullanılarak bir değer belirtildi |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | Bir yüzde değeri belirtildi. |
| const [SVG_LENGTHTYPE_PT](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | CSS2. 'de tanımlanan pt birimleri kullanılarak bir değer belirtildi |
| const [SVG_LENGTHTYPE_PX](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | CSS2. 'de tanımlanan px birimleri kullanılarak bir değer belirtildi |
| const [SVG_LENGTHTYPE_UNKNOWN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | Birim türü, önceden tanımlanmış birim türlerinden biri değil. Bu türde yeni bir değer tanımlamaya veya mevcut bir değeri bu türe değiştirmeye çalışmak geçersizdir. |

### Ayrıca bakınız

* class [SVGValueType](../svgvaluetype/)
* ad alanı [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* toplantı [Aspose.HTML](../../)


