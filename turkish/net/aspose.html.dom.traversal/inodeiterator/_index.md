---
title: Interface INodeIterator
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Traversal.INodeIterator arayüz. Yineleyiciler örneğin bir NodeListteki düğüm kümesi belirli bir Düğüm tarafından yönetilen belge alt ağacı bir sorgunun sonuçları veya başka herhangi bir düğüm kümesi gibi bir dizi düğüm arasında ilerlemek için kullanılır. Yinelenecek düğüm kümesi NodeIteratorın uygulaması tarafından belirlenir. DOM Düzey 2 bir belge alt ağacının belge sırası geçişi için bir tek NodeIterator uygulamasını belirtir. Bu yineleyicilerin örnekleri DocumentTraversal .createNodeIterator. çağrılarak oluşturulur.
type: docs
weight: 2500
url: /tr/net/aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

Yineleyiciler, örneğin bir NodeList'teki düğüm kümesi, belirli bir Düğüm tarafından yönetilen belge alt ağacı, bir sorgunun sonuçları veya başka herhangi bir düğüm kümesi gibi bir dizi düğüm arasında ilerlemek için kullanılır. Yinelenecek düğüm kümesi, NodeIterator'ın uygulaması tarafından belirlenir. DOM Düzey 2, bir belge alt ağacının belge sırası geçişi için bir tek NodeIterator uygulamasını belirtir. Bu yineleyicilerin örnekleri DocumentTraversal .createNodeIterator(). çağrılarak oluşturulur.

Ayrıca bkz.[Belge nesnesi Modeli (DOM) Düzey 2 Geçiş ve Aralık Spesifikasyonu](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @dOM Düzey 2 beri

```csharp
public interface INodeIterator : ITraversal
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | Bu bayrağın değeri, entity referans düğümlerinin alt öğelerinin yineleyici tarafından görülüp görülmediğini belirler. Yanlışsa, onlar ve onların soyundan gelen reddedilecektir. Bu reddetmenin, whatToShow ve filtreye göre önceliğe sahip olduğunu unutmayın. Ayrıca, , şu anda, NodeIterators'ın tek tek düğümleri atlamak yerine tam bir alt ağacı reddedebileceği tek durumun bu olduğuna dikkat edin. node varlık referansını gizleyin ve the yineleyiciyi oluştururken ExpandEntityReferences değerini true olarak ayarlayın. Varlık referansı düğümleri olan ancak varlık genişletmesi olmayan belgenin bir görünümünü oluşturmak için, varlık referans düğümünü göstermek için whatToShow flags öğesini kullanın ve false. olarak set genişletEntityReferences öğesini kullanın. |
| [ReferenceNode](../../aspose.html.dom.traversal/inodeiterator/referencenode/) { get; } | Geçerli referans düğümü. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Detach](../../aspose.html.dom.traversal/inodeiterator/detach/)() | NodeIterator'ı, üzerinde yinelediği kümesinden ayırır, tüm hesaplama kaynaklarını serbest bırakır ve iterator öğesini GEÇERSİZ duruma getirir. Ayırma işlemi başlatıldıktan sonra, nextNode'a veya öncekiNode'a yapılan çağrıları INVALID_STATE_ERR. istisnasını yükseltir |
| [NextNode](../../aspose.html.dom.traversal/inodeiterator/nextnode/)() | Kümedeki sonraki düğümü döndürür ve kümedeki yineleyicinin konumunu ilerletir. Bir NodeIterator oluşturulduktan sonra, nextNode() öğesine yapılan ilk çağrı, set. içindeki ilk düğümü döndürür. |
| [PreviousNode](../../aspose.html.dom.traversal/inodeiterator/previousnode/)() | Kümedeki önceki düğümü döndürür ve NodeIterator'ın konumunu kümede geriye doğru taşır. |

### Ayrıca bakınız

* interface [ITraversal](../itraversal/)
* ad alanı [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* toplantı [Aspose.HTML](../../)


