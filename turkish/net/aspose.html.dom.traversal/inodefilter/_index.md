---
title: Interface INodeFilter
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Traversal.INodeFilter arayüz. Filtreler düğümlerin nasıl filtreleneceğini bilen nesnelerdir. Bir NodeIterator veya TreeWalkera bir NodeFilter verilirse sonraki düğümünü döndürmeden önce filtreyi uygular. Filtre düğümü kabul et diyorsa geçiş mantığı onu döndürür aksi takdirde geçiş bir sonraki düğümü arar ve reddedilen düğümü orada değilmiş gibi davranır.
type: docs
weight: 2490
url: /tr/net/aspose.html.dom.traversal/inodefilter/
---
## INodeFilter interface

Filtreler, düğümlerin nasıl "filtreleneceğini" bilen nesnelerdir. Bir NodeIterator veya TreeWalker'a bir NodeFilter verilirse, sonraki düğümünü döndürmeden önce filtreyi uygular. Filtre düğümü kabul et diyorsa, geçiş mantığı onu döndürür; aksi takdirde, geçiş bir sonraki düğümü arar ve reddedilen düğümü orada değilmiş gibi davranır.

DOM herhangi bir filtre sağlamaz. NodeFilter, kullanıcıların kendi filtrelerini sağlamak için uygulayabilecekleri yalnızca bir arabirimidir.

NodeFilters'ın düğümünden düğüme nasıl geçileceğini bilmesi veya 'nin katedildiği veri yapısı hakkında hiçbir şey bilmesi gerekmez. Bu, filtre yazmayı çok kolaylaştırır, çünkü 'nin nasıl yapacaklarını bilmeleri gereken tek şey, tek bir düğümü değerlendirmektir. Bir filtresi, birkaç farklı geçiş türüyle birlikte kullanılabilir, kodun yeniden kullanılmasını teşvik eder.

Ayrıca bkz.[Belge nesnesi Modeli (DOM) Düzey 2 Geçiş ve Aralık Spesifikasyonu](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @dOM Düzey 2 beri

```csharp
public interface INodeFilter
```

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AcceptNode](../../aspose.html.dom.traversal/inodefilter/acceptnode/)(Node) | Belirli bir düğümün bir TreeWalker veya NodeIterator mantıksal görünümünde görünür olup olmadığını test edin. Bu işlevi, TreeWalker ve NodeIterator uygulaması tarafından çağrılacaktır; normalde doğrudan kullanıcı kodundan çağrılmaz. (Yine de kendi uygulama mantığınıza rehberlik etmesi için aynı filtresini kullanmak isterseniz bunu yapabilirsiniz.) |

### Ayrıca bakınız

* ad alanı [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* toplantı [Aspose.HTML](../../)


