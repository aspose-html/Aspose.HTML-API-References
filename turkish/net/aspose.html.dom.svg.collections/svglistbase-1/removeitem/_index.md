---
title: SVGListBase1.RemoveItem
second_title: Aspose.HTML for .NET API Referansı
description: SVGListBase yöntem. Mevcut bir öğeyi listeden kaldırır.
type: docs
weight: 100
url: /tr/net/aspose.html.dom.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase&lt;T&gt;.RemoveItem method

Mevcut bir öğeyi listeden kaldırır.

```csharp
public T RemoveItem(ulong index)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| index | UInt64 | Kaldırılacak öğenin dizini. İlk öğe 0 numaradır. |

### Geri dönüş değeri

Kaldırılan öğe.

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | kod[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). Liste değiştirilemediğinde tetiklenir. |
| [DOMException](../../../aspose.html.dom/domexception/) | kod[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). İndeks numarası, itemOfItems'den büyük veya ona eşitse yükseltilir. |

### Ayrıca bakınız

* class [SVGListBase&lt;T&gt;](../)
* ad alanı [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* toplantı [Aspose.HTML](../../../)


