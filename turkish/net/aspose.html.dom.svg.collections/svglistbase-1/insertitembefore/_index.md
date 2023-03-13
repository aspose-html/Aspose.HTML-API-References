---
title: SVGListBase1.InsertItemBefore
second_title: Aspose.HTML for .NET API Referansı
description: SVGListBase yöntem. Belirtilen konumda listeye yeni bir öğe ekler. İlk öğe numarası 0.
type: docs
weight: 90
url: /tr/net/aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

Belirtilen konumda listeye yeni bir öğe ekler. İlk öğe numarası 0.

```csharp
public T InsertItemBefore(T newItem, ulong index)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| newItem | T | Listeye eklenecek öğe. |
| index | UInt64 | Yeni öğenin ekleneceği öğenin dizini. İlk öğe 0'dır. Dizin 0'a eşitse, yeni öğe listenin önüne eklenir. Dizin, itemOfItems'den büyük veya ona eşitse, yeni öğe listenin sonuna eklenir. |

### Geri dönüş değeri

Girilen öğe.

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | kod[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). Liste değiştirilemediğinde tetiklenir. |

### Ayrıca bakınız

* class [SVGListBase&lt;T&gt;](../)
* ad alanı [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* toplantı [Aspose.HTML](../../../)


