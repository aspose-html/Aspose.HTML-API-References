---
title: Interface ITreeWalker
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Traversal.ITreeWalker arayüz. TreeWalker nesneleri whatToShow bayrakları ve varsa filtresi tarafından tanımlanan belgenin görünümünü kullanarak bir belge ağacında veya alt ağacında gezinmek için kullanılır. nin bir TreeWalker kullanarak gezinme gerçekleştirdiği herhangi bir işlev bir TreeWalker. tarafından tanımlanan herhangi bir görünümü otomatik olarak destekleyecektir.
type: docs
weight: 2520
url: /tr/net/aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

TreeWalker nesneleri, whatToShow bayrakları ve (varsa) filtresi tarafından tanımlanan belgenin görünümünü kullanarak bir belge ağacında veya alt ağacında gezinmek için kullanılır. 'nin bir TreeWalker kullanarak gezinme gerçekleştirdiği herhangi bir işlev, bir TreeWalker. tarafından tanımlanan herhangi bir görünümü otomatik olarak destekleyecektir.

Bir alt ağacın mantıksal görünümünden düğümlerin atlanması, eksiksiz, filtrelenmemiş belgedeki aynı alt ağaçtan büyük ölçüde farklı olan bir yapısına neden olabilir. TreeWalker görünümünde kardeş olan düğümler, orijinal görünümde farklı, geniş ölçüde ayrılmış düğümlerin çocukları olabilir. Örneğin, bir belgenin kök düğümü olan Metin düğümleri ve dışındaki tüm düğümleri atlayan bir NodeFilter düşünün. Ortaya çıkan mantıksal görünümde, tüm metin düğümleri kardeş olacak ve orijinal belgenin yapısı ne kadar derine yuvalanmış olursa olsun hiçbir şey kardeş olacak ve kök düğümün doğrudan çocukları olarak görünecektir.

Ayrıca bkz.[Belge nesnesi Modeli (DOM) Düzey 2 Geçiş ve Aralık Spesifikasyonu](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @dOM Düzey 2 beri

```csharp
public interface ITreeWalker : ITraversal
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CurrentNode](../../aspose.html.dom.traversal/itreewalker/currentnode/) { get; set; } | TreeWalker'ın şu anda konumlandırıldığı düğüm. DOM ağacındaki değişiklikler, geçerli düğümün artık TreeWalker'ın ilişkili filtresi tarafından kabul edilmemesine neden olabilir . the kök düğümü tarafından belirtilen alt ağaç içinde veya and whatToShow bayrakları tarafından kabul edilir. Geçerli görünümün parçası olmasa bile currentNode'a göre daha fazla geçiş gerçekleşir, filtreleri istenen yönde uygulayarak; traversal mümkün değilse, currentNode değişmez. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [FirstChild](../../aspose.html.dom.traversal/itreewalker/firstchild/)() | TreeWalker'ı geçerli düğümünün ilk görünür alt öğesine taşır ve yeni düğümü döndürür. Geçerli düğümün no görünür alt öğesi yoksa, boş değer döndürür ve current düğümünü korur. |
| [LastChild](../../aspose.html.dom.traversal/itreewalker/lastchild/)() | TreeWalker'ı geçerli düğümünün son görünür alt öğesine taşır ve yeni düğümü döndürür. Geçerli düğümün no görünür alt öğesi yoksa, boş değer döndürür ve current düğümünü korur. |
| [NextNode](../../aspose.html.dom.traversal/itreewalker/nextnode/)() | TreeWalker'ı geçerli düğüme göre document sırasına göre bir sonraki görünür düğüme taşır ve yeni düğümü döndürür. Geçerli düğümünün bir sonraki düğümü yoksa veya nextNode araması, TreeWalker'ın root düğümünden yukarı doğru adım atmaya girişiminde bulunursa, null değerini döndürür ve geçerli düğümü korur. |
| [NextSibling](../../aspose.html.dom.traversal/itreewalker/nextsibling/)() | TreeWalker'ı current düğümünün bir sonraki kardeşine taşır ve yeni düğümü döndürür. Geçerli düğümün bir sonraki kardeş görünür 'si yoksa, null değerini döndürür ve geçerli düğümü korur. |
| [ParentNode](../../aspose.html.dom.traversal/itreewalker/parentnode/)() | Geçerli düğümünün en yakın görünen ata düğümüne gider ve onu döndürür. parentNode araması, TreeWalker'ın kök düğümünden yukarı adımını atmaya çalışırsa veya görünür bir ata düğümü bulamazsa 'yi denerse, bu yöntem, geçerli konumunu korur ve null. değerini döndürür. |
| [PreviousNode](../../aspose.html.dom.traversal/itreewalker/previousnode/)() | Geçerli düğüme göre belge sırasında TreeWalker'ı önceki görünür düğüme taşır ve new düğümünü döndürür. Geçerli düğümün önceki düğümü yoksa veya for öncekiNode araması, TreeWalker'ın kök düğümünden yukarı doğru adım atmaya çalışırsa, null değerini döndürür ve geçerli düğümü korur. |
| [PreviousSibling](../../aspose.html.dom.traversal/itreewalker/previoussibling/)() | TreeWalker'ı geçerli düğümün önceki kardeşine taşır ve yeni düğümü döndürür. Geçerli düğümde görünür önceki kardeş yok varsa, null değerini döndürür ve geçerli düğümünü korur. |

### Ayrıca bakınız

* interface [ITraversal](../itraversal/)
* ad alanı [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* toplantı [Aspose.HTML](../../)


