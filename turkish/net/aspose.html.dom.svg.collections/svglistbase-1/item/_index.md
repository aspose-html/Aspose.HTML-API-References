---
title: SVGListBase1.Item
second_title: Aspose.HTML for .NET API Referansı
description: SVGListBase mülk. Listedeki dizinci öğeyi döndürür.
type: docs
weight: 10
url: /tr/net/aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

Listedeki dizinci öğeyi döndürür.

```csharp
public T this[ulong index] { get; set; }
```

| Parametre | Tanım |
| --- | --- |
| index | Listedeki dizin. |

### Geri dönüş değeri

Listedeki indeksinci pozisyonda saklanan nesne.

### Mülk değeri

list. içinde depolanan öğenin türü

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | kod[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). Liste değiştirilemediğinde tetiklenir. |
| [DOMException](../../../aspose.html.dom/domexception/) | kod[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). İndeks numarası, itemOfItems'den büyük veya ona eşitse yükseltilir. |

### Ayrıca bakınız

* class [SVGListBase&lt;T&gt;](../)
* ad alanı [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* toplantı [Aspose.HTML](../../../)


