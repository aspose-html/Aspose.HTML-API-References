---
title: SVGLength.ConvertToSpecifiedUnits
second_title: Aspose.HTML for .NET API Referansı
description: SVGLength yöntem. Aynı temel depolanan değeri koruyun ancak depolanan birim tanımlayıcısını verilen unitTypea sıfırlayın. UnitType valueInSpecifiedUnits ve valueAsString nesne nitelikleri bu yöntemin bir sonucu olarak değiştirilebilir. Örneğin orijinal değer 05cm ise ve yöntem milimetreye dönüştürmek için çağrıldıysa o zaman unitType SVG_LENGTHTYPE_MM olarak değiştirilir valueInSpecifiedUnits sayısal değer 5 olarak değiştirilir ve valueAsString 5mm olarak değiştirilir.
type: docs
weight: 50
url: /tr/net/aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Aynı temel depolanan değeri koruyun, ancak depolanan birim tanımlayıcısını verilen unitType'a sıfırlayın. UnitType, valueInSpecifiedUnits ve valueAsString nesne nitelikleri bu yöntemin bir sonucu olarak değiştirilebilir. Örneğin, orijinal değer "0,5cm" ise ve yöntem milimetreye dönüştürmek için çağrıldıysa, o zaman unitType SVG_LENGTHTYPE_MM olarak değiştirilir, valueInSpecifiedUnits sayısal değer 5 olarak değiştirilir ve valueAsString "5mm" olarak değiştirilir.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| unitType | UInt16 | Geçiş yapılacak birim tipi (örn. SVG_LENGTHTYPE_MM). |

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Kod[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) UnitType SVG_LENGTHTYPE_UNKNOWN ise veya geçerli bir birim tipi sabiti değilse yükseltilir (bu arabirimde tanımlanan diğer SVG_LENGTHTYPE_* sabitlerinden biri). |
| [DOMException](../../../aspose.html.dom/domexception/) | Kod[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Uzunluk salt okunur bir özniteliğe karşılık geldiğinde veya nesnenin kendisi salt okunur olduğunda yükseltilir. |

### Ayrıca bakınız

* class [SVGLength](../)
* ad alanı [Aspose.Html.Dom.Svg.DataTypes](../../svglength/)
* toplantı [Aspose.HTML](../../../)


