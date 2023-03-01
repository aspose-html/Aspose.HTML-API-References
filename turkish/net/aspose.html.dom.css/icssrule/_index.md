---
title: Interface ICSSRule
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Css.ICSSRule arayüz. CSSRule arabirimi herhangi bir CSS ifadesi türü için soyut temel arabirimdir. Buna hem kural kümeleri hem de atkuralları dahildir. Bir uygulamanın kural ayrıştırıcı tarafından tanınmasa bile CSS stil sayfasında belirtilen tüm kuralları koruması beklenir. Tanınmayan kurallar kullanılarak temsil edilirICSSUnknownRule arayüz.
type: docs
weight: 470
url: /tr/net/aspose.html.dom.css/icssrule/
---
## ICSSRule interface

CSSRule arabirimi, herhangi bir CSS ifadesi türü için soyut temel arabirimdir. Buna hem kural kümeleri hem de at-kuralları dahildir. Bir uygulamanın, kural ayrıştırıcı tarafından tanınmasa bile CSS stil sayfasında belirtilen tüm kuralları koruması beklenir. Tanınmayan kurallar kullanılarak temsil edilir!:ICSSUnknownRule arayüz.

```csharp
public interface ICSSRule
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssrule/csstext/) { get; set; } | Kuralın ayrıştırılabilir metinsel gösterimi. Bu, kuralın mevcut durumunu yansıtır ve başlangıç değerini yansıtmaz. |
| [ParentRule](../../aspose.html.dom.css/icssrule/parentrule/) { get; } | Bu kural başka bir kuralın içinde yer alıyorsa (örn. bir @media bloğunun içindeki bir stil kuralı), bu içerme kuralıdır. Bu kural başka herhangi bir kuralın içinde iç içe değilse, null. değerini döndürür. |
| [ParentStyleSheet](../../aspose.html.dom.css/icssrule/parentstylesheet/) { get; } | Bu kuralı içeren stil sayfası. |
| [Type](../../aspose.html.dom.css/icssrule/type/) { get; } | Yukarıda tanımlandığı gibi kuralın türü. Beklenti, bağlamaya özgü atama yöntemlerinin, CSSRule arabiriminin bir örneğinden type. tarafından ima edilen belirli türetilmiş arabirime dönüştürmek için kullanılabileceği yönündedir. |

### Ayrıca bakınız

* ad alanı [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* toplantı [Aspose.HTML](../../)


