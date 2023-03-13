---
title: ITreeWalker.CurrentNode
second_title: Aspose.HTML for .NET API Referansı
description: ITreeWalker mülk. TreeWalkerın şu anda konumlandırıldığı düğüm. DOM ağacındaki değişiklikler geçerli düğümün artık TreeWalkerın ilişkili filtresi tarafından kabul edilmemesine neden olabilir . the kök düğümü tarafından belirtilen alt ağaç içinde veya and whatToShow bayrakları tarafından kabul edilir. Geçerli görünümün parçası olmasa bile currentNodea göre daha fazla geçiş gerçekleşir filtreleri istenen yönde uygulayarak traversal mümkün değilse currentNode değişmez.
type: docs
weight: 10
url: /tr/net/aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

TreeWalker'ın şu anda konumlandırıldığı düğüm. DOM ağacındaki değişiklikler, geçerli düğümün artık TreeWalker'ın ilişkili filtresi tarafından kabul edilmemesine neden olabilir . the kök düğümü tarafından belirtilen alt ağaç içinde veya and whatToShow bayrakları tarafından kabul edilir. Geçerli görünümün parçası olmasa bile currentNode'a göre daha fazla geçiş gerçekleşir, filtreleri istenen yönde uygulayarak; traversal mümkün değilse, currentNode değişmez.

```csharp
public Node CurrentNode { get; set; }
```

### Mülk değeri

Geçerli düğüm.

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: currentNode'u null olarak ayarlamak için bir girişimde bulunulursa yükseltilir. |

### Ayrıca bakınız

* class [Node](../../../aspose.html.dom/node/)
* interface [ITreeWalker](../)
* ad alanı [Aspose.Html.Dom.Traversal](../../itreewalker/)
* toplantı [Aspose.HTML](../../../)


