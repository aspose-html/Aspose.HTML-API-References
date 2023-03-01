---
title: IXPathResult.SnapshotItem
second_title: Aspose.HTML for .NET API Referansı
description: IXPathResult yöntem. şunu döndürürdizin anlık görüntü koleksiyonundaki öğe. Eğerdizin den büyük veya listedeki düğüm sayısına eşitse bu yöntem döndürürhükümsüz . yineleyici sonucunun aksine anlık görüntü geçersiz olmaz ancak mutasyona uğrarsa geçerli belgesine karşılık gelmeyebilir.
type: docs
weight: 90
url: /tr/net/aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

şunu döndürür:`dizin` anlık görüntü koleksiyonundaki öğe. Eğer`dizin` 'den büyük veya listedeki düğüm sayısına eşitse, bu yöntem döndürür`hükümsüz` . yineleyici sonucunun aksine, anlık görüntü geçersiz olmaz, ancak mutasyona uğrarsa geçerli belgesine karşılık gelmeyebilir.

```csharp
public Node SnapshotItem(int index)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| index | Int32 | Anlık görüntü koleksiyonuna dizin. |

### Geri dönüş değeri

noktasındaki düğüm`dizin` inci pozisyon`Düğüm Listesi` , veya`hükümsüz` ise bu geçerli bir dizin değildir.

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: şu durumlarda yükseltilir:`sonuçTürü` değil`Sırasız Düğüm Anlık Görüntüsü` yazın veya`OrderedNodeSnapshot` tip. |

### Ayrıca bakınız

* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathResult](../)
* ad alanı [Aspose.Html.Dom.XPath](../../ixpathresult/)
* toplantı [Aspose.HTML](../../../)


