---
title: SVGListBase1.ReplaceItem
second_title: Aspose.HTML for .NET API Referansı
description: SVGListBase yöntem. Listedeki mevcut bir öğeyi yeni bir öğeyle değiştirir.
type: docs
weight: 110
url: /tr/net/aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

Listedeki mevcut bir öğeyi yeni bir öğeyle değiştirir.

```csharp
public T ReplaceItem(T newItem, ulong index)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| newItem | T | Listeye eklenecek öğe. |
| index | UInt64 | Değiştirilecek öğenin dizini. İlk öğe 0 numaradır. |

### Geri dönüş değeri

Girilen öğe.

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | kod[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). Liste değiştirilemediğinde tetiklenir. |
| [DOMException](../../../aspose.html.dom/domexception/) | kod[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). İndeks numarası, itemOfItems'den büyük veya ona eşitse yükseltilir. |

### Ayrıca bakınız

* class [SVGListBase&lt;T&gt;](../)
* ad alanı [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* toplantı [Aspose.HTML](../../../)


