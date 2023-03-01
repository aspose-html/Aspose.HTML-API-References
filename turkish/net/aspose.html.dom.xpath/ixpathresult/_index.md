---
title: Interface IXPathResult
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.XPath.IXPathResult arayüz. XPathSonucu arabirim belirli bir düğüm bağlamında bir XPath 1.0 ifadesinin değerlendirilmesinin sonucunu temsil eder. Bir XPath ifadesinin değerlendirmesi çeşitli sonuç türleriyle sonuçlanabileceğinden bu nesne sonucun türünü ve değerini keşfetmeyi ve değiştirmeyi mümkün kılar.
type: docs
weight: 2600
url: /tr/net/aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

`XPathSonucu` arabirim, belirli bir düğüm bağlamında bir XPath 1.0 ifadesinin değerlendirilmesinin sonucunu temsil eder. Bir XPath ifadesinin değerlendirmesi, çeşitli sonuç türleriyle sonuçlanabileceğinden, bu nesne, sonucun türünü ve değerini keşfetmeyi ve değiştirmeyi mümkün kılar.

```csharp
public interface IXPathResult
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BooleanValue](../../aspose.html.dom.xpath/ixpathresult/booleanvalue/) { get; } | Bu boole sonucunun değeri. |
| [InvalidIteratorState](../../aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | Yineleyicinin geçersiz hale geldiğini belirtir. Doğru ise`sonuçTürü``UnorderedNodeYineleyici` yazın veya`OrderedNodeIterator` yazın ve bu sonuç döndürüldüğünden beri belge değiştirildi. |
| [NumberValue](../../aspose.html.dom.xpath/ixpathresult/numbervalue/) { get; } | Bu sayı sonucunun değeri. |
| [ResultType](../../aspose.html.dom.xpath/ixpathresult/resulttype/) { get; } | http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult tarafından tanımlanan, bu sonucun türünü temsil eden bir kod[`XPathResultType`](../xpathresulttype/) numaralandırma. |
| [SingleNodeValue](../../aspose.html.dom.xpath/ixpathresult/singlenodevalue/) { get; } | Bu tek düğüm sonucunun değeri;`hükümsüz` . |
| [SnapshotLength](../../aspose.html.dom.xpath/ixpathresult/snapshotlength/) { get; } | Sonuç anlık görüntüsündeki düğüm sayısı. snapshotItem dizinleri için geçerli değerler:`0` ile`anlık görüntüLength-1` dahil. |
| [StringValue](../../aspose.html.dom.xpath/ixpathresult/stringvalue/) { get; } | Bu dizi sonucunun değeri. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [IterateNext](../../aspose.html.dom.xpath/ixpathresult/iteratenext/)() | Düğüm kümesinden bir sonraki düğümü yineler ve döndürür veya`hükümsüz` başka düğüm yoksa. |
| [SnapshotItem](../../aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | şunu döndürür:`dizin` anlık görüntü koleksiyonundaki öğe. Eğer`dizin` 'den büyük veya listedeki düğüm sayısına eşitse, bu yöntem döndürür`hükümsüz` . yineleyici sonucunun aksine, anlık görüntü geçersiz olmaz, ancak mutasyona uğrarsa geçerli belgesine karşılık gelmeyebilir. |

### Ayrıca bakınız

* ad alanı [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* toplantı [Aspose.HTML](../../)


