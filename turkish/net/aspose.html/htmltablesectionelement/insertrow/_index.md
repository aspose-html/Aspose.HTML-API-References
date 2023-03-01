---
title: HTMLTableSectionElement.InsertRow
second_title: Aspose.HTML for .NET API Referansı
description: HTMLTableSectionElement yöntem. Bu bölüme bir satır ekleyin. Yeni satır geçerli satırdan hemen önce eklenirdizin bu bölümdeki inci sıra. isedizin 1 veya bu bölümündeki satır sayısına eşitse yeni satır eklenir.
type: docs
weight: 70
url: /tr/net/aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

Bu bölüme bir satır ekleyin. Yeni satır, geçerli satırdan hemen önce eklenir`dizin` bu bölümdeki inci sıra. ise`dizin` -1 veya bu bölümündeki satır sayısına eşitse, yeni satır eklenir.

```csharp
public HTMLElement InsertRow(int index)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| index | Int32 | Yeni bir satırın ekleneceği satır numarası. Bu dizini 0'dan başlar ve tablodaki tüm satırlarla değil, yalnızca bu bölüm içinde yer alan satırlarla ilişkilidir. |

### Geri dönüş değeri

Yeni oluşturulan satır.

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Belirtilen dizin satır sayısından büyükse, dizin -1. dışında bir negatif sayıysa yükseltilir @version DOM Düzey 2 |

### Ayrıca bakınız

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* ad alanı [Aspose.Html](../../htmltablesectionelement/)
* toplantı [Aspose.HTML](../../../)


