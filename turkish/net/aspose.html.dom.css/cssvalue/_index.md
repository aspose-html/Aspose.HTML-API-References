---
title: Class CSSValue
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Css.CSSValue sınıf. Basit veya karmaşık bir değeri temsil eder. Bir CSSValue nesnesi yalnızca bir CSS özelliği bağlamında oluşur.
type: docs
weight: 340
url: /tr/net/aspose.html.dom.css/cssvalue/
---
## CSSValue class

Basit veya karmaşık bir değeri temsil eder. Bir CSSValue nesnesi yalnızca bir CSS özelliği bağlamında oluşur.

```csharp
public abstract class CSSValue : DOMObject
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| abstract [CSSText](../../aspose.html.dom.css/cssvalue/csstext/) { get; set; } | Geçerli değerin dize gösterimi. |
| [CSSValueType](../../aspose.html.dom.css/cssvalue/cssvaluetype/) { get; } | Değerin türünü tanımlayan bir kod. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Equals](../../aspose.html.dom.css/cssvalue/equals/)(object) | Belirtilenin olup olmadığını belirler.Object bu örneğe eşittir. |
| override [GetHashCode](../../aspose.html.dom.css/cssvalue/gethashcode/)() | Bu örnek için bir karma kod döndürür. |
| override [GetPlatformType](../../aspose.html.dom.css/cssvalue/getplatformtype/)() | Bu yöntem ECMAScript nesnesini almak için kullanılır.Type . |
| override [ToString](../../aspose.html.dom.css/cssvalue/tostring/)() | a döndürürString bu örneği temsil eder. |
| [operator ==](../../aspose.html.dom.css/cssvalue/op_equality/) | ==. operatörünü uygular |
| [operator !=](../../aspose.html.dom.css/cssvalue/op_inequality/) | !=. operatörünü uygular |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [CSS_CUSTOM](../../aspose.html.dom.css/cssvalue/css_custom/) | Değer, özel bir değerdir. |
| const [CSS_INHERIT](../../aspose.html.dom.css/cssvalue/css_inherit/) | Değer devralınır ve cssText "inherit" içerir. |
| const [CSS_PRIMITIVE_VALUE](../../aspose.html.dom.css/cssvalue/css_primitive_value/) | Değer ilkel bir değerdir ve CSSPrimitiveValue arabiriminin bir örneği, CSSValue arabiriminin bu örneğinde bağlamaya özel dönüştürme yöntemleri kullanılarak elde edilebilir. |
| const [CSS_VALUE_LIST](../../aspose.html.dom.css/cssvalue/css_value_list/) | Değer bir CSSValue listesidir ve CSSValueList arabiriminin bir örneği, CSSValue arabiriminin bu örneğinde bağlamaya özel atama yöntemleri kullanılarak elde edilebilir. |

### Ayrıca bakınız

* class [DOMObject](../../aspose.html.dom/domobject/)
* ad alanı [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* toplantı [Aspose.HTML](../../)


