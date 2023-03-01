---
title: Interface ICSSImportRule
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Css.ICSSImportRule arayüz. CSSImportRule arabirimi bir CSS stil sayfası içinde bir import kuralını temsil eder. import kuralı diğer stil sayfalarından stil kurallarını içe aktarmak için kullanılır.
type: docs
weight: 410
url: /tr/net/aspose.html.dom.css/icssimportrule/
---
## ICSSImportRule interface

CSSImportRule arabirimi, bir CSS stil sayfası içinde bir @import kuralını temsil eder. @import kuralı, diğer stil sayfalarından stil kurallarını içe aktarmak için kullanılır.

```csharp
public interface ICSSImportRule : ICSSRule
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Href](../../aspose.html.dom.css/icssimportrule/href/) { get; } | İçe aktarılacak stil sayfasının konumu. Öznitelik, URI. çevresinde "url(...)" belirticisini içermeyecektir. |
| [Media](../../aspose.html.dom.css/icssimportrule/media/) { get; } | Bu stil sayfasının kullanılabileceği ortam türlerinin listesi. |
| [StyleSheet](../../aspose.html.dom.css/icssimportrule/stylesheet/) { get; } | Yüklendiyse, bu kural tarafından atıfta bulunulan stil sayfası. Stil sayfası henüz yüklenmediyse veya yüklenmeyecekse (örneğin, stil sayfası kullanıcı aracısı tarafından desteklenmeyen bir ortam türü içinse) bu özniteliğin değeri boştur. |

### Ayrıca bakınız

* interface [ICSSRule](../icssrule/)
* ad alanı [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* toplantı [Aspose.HTML](../../)


