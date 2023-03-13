---
title: SVGLength.NewValueSpecifiedUnits
second_title: Aspose.HTML for .NET API Referansı
description: SVGLength yöntem. İlişkili bir unitType ile değeri bir sayı olarak sıfırlayın böylece nesnedeki tüm özniteliklerin değerlerini değiştirin.
type: docs
weight: 60
url: /tr/net/aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

İlişkili bir unitType ile değeri bir sayı olarak sıfırlayın, böylece nesnedeki tüm özniteliklerin değerlerini değiştirin.

```csharp
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| unitType | UInt16 | Değer için birim türü. |
| valueInSpecifiedUnits | Single | yeni değer.. |

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Kod[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) UnitType SVG_LENGTHTYPE_UNKNOWN ise veya geçerli bir birim tipi sabiti değilse yükseltilir (bu arabirimde tanımlanan diğer SVG_LENGTHTYPE_* sabitlerinden biri). |
| [DOMException](../../../aspose.html.dom/domexception/) | Kod[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Uzunluk salt okunur bir özniteliğe karşılık geldiğinde veya nesnenin kendisi salt okunur olduğunda yükseltilir. |

### Ayrıca bakınız

* class [SVGLength](../)
* ad alanı [Aspose.Html.Dom.Svg.DataTypes](../../svglength/)
* toplantı [Aspose.HTML](../../../)


