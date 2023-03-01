---
title: SVGAngle.NewValueSpecifiedUnits
second_title: Aspose.HTML for .NET API Referansı
description: SVGAngle yöntem. İlişkili bir unitType ile değeri bir sayı olarak sıfırlayın böylece nesnedeki tüm özniteliklerin değerlerini değiştirin.
type: docs
weight: 60
url: /tr/net/aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

İlişkili bir unitType ile değeri bir sayı olarak sıfırlayın, böylece nesnedeki tüm özniteliklerin değerlerini değiştirin.

```csharp
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| newUnitType | UInt16 | Değer için birim türü (ör. SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | açı değeri. |

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Kod[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) UnitType SVG_ANGLETYPE_UNKNOWN ise veya geçerli bir birim tipi sabiti değilse yükseltilir (bu arabirimde tanımlanan diğer SVG_ANGLETYPE_* sabitlerinden biri). |
| [DOMException](../../../aspose.html.dom/domexception/) | Kod[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Açı salt okunur bir özniteliğe karşılık geldiğinde veya nesnenin kendisi salt okunur olduğunda yükseltilir. |

### Ayrıca bakınız

* class [SVGAngle](../)
* ad alanı [Aspose.Html.Dom.Svg.DataTypes](../../svgangle/)
* toplantı [Aspose.HTML](../../../)


