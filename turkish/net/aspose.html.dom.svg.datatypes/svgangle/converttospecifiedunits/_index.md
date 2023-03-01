---
title: SVGAngle.ConvertToSpecifiedUnits
second_title: Aspose.HTML for .NET API Referansı
description: SVGAngle yöntem. Aynı temel depolanan değeri koruyun ancak depolanan birim tanımlayıcısını verilen unitTypea sıfırlayın. UnitType valueInSpecifiedUnits ve valueAsString nesne nitelikleri bu yöntemin bir sonucu olarak değiştirilebilir.
type: docs
weight: 50
url: /tr/net/aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Aynı temel depolanan değeri koruyun, ancak depolanan birim tanımlayıcısını verilen unitType'a sıfırlayın. UnitType, valueInSpecifiedUnits ve valueAsString nesne nitelikleri bu yöntemin bir sonucu olarak değiştirilebilir.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| unitType | UInt16 | Geçiş yapılacak birim tipi (örn. SVG_ANGLETYPE_DEG). |

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Kod[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) UnitType SVG_ANGLETYPE_UNKNOWN ise veya geçerli bir birim tipi sabiti değilse yükseltilir (bu arabirimde tanımlanan diğer SVG_ANGLETYPE_* sabitlerinden biri). |
| [DOMException](../../../aspose.html.dom/domexception/) | Kod[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Açı salt okunur bir özniteliğe karşılık geldiğinde veya nesnenin kendisi salt okunur olduğunda yükseltilir. |

### Ayrıca bakınız

* class [SVGAngle](../)
* ad alanı [Aspose.Html.Dom.Svg.DataTypes](../../svgangle/)
* toplantı [Aspose.HTML](../../../)


