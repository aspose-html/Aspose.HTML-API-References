---
title: IDocumentTraversal.CreateNodeIterator
second_title: Aspose.HTML for .NET API Referansı
description: IDocumentTraversal yöntem. Belirtilen node. de köklenen alt ağaç üzerinde yeni bir NodeIterator oluşturun.
type: docs
weight: 10
url: /tr/net/aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

Belirtilen node. 'de köklenen alt ağaç üzerinde yeni bir NodeIterator oluşturun.

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| root | Node | çocukları ile birlikte yinelenecek olan düğüm. Yineleyici başlangıçta bu düğümden hemen önce konumlandırılır. The whatToShow bayrakları ve varsa filtre, bu konumu ayarlarken not dikkate alınır. Kök, null olmamalıdır. |

### Geri dönüş değeri

Yeni oluşturulan NodeIterator.

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Belirtilen kök is null ise yükseltilir. |

### Ayrıca bakınız

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* ad alanı [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* toplantı [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

Belirtilen node. 'de köklenen alt ağaç üzerinde yeni bir NodeIterator oluşturun.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| root | Node | çocukları ile birlikte yinelenecek olan düğüm. Yineleyici başlangıçta bu düğümden hemen önce konumlandırılır. The whatToShow bayrakları ve varsa filtre, bu konumu ayarlarken not dikkate alınır. Kök, null olmamalıdır. |
| whatToShow | Int64 | flag, yineleyici tarafından sunulan ağacın mantıksal görünümünde içinde hangi düğüm türlerinin görünebileceğini belirtir. Olası SHOW_ değerleri kümesi için NodeFilter'ın açıklamasına bakın. Bu bayraklar, OR kullanılarak birleştirilebilir. |

### Geri dönüş değeri

Yeni oluşturulan NodeIterator.

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Belirtilen kök is null ise yükseltilir. |

### Ayrıca bakınız

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* ad alanı [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* toplantı [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

Belirtilen node. 'de köklenen alt ağaç üzerinde yeni bir NodeIterator oluşturun.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| root | Node | çocukları ile birlikte yinelenecek olan düğüm. Yineleyici başlangıçta bu düğümden hemen önce konumlandırılır. The whatToShow bayrakları ve varsa filtre, bu konumu ayarlarken not dikkate alınır. Kök, null olmamalıdır. |
| whatToShow | Int64 | flag, yineleyici tarafından sunulan ağacın mantıksal görünümünde içinde hangi düğüm türlerinin görünebileceğini belirtir. Olası SHOW_ değerleri kümesi için NodeFilter'ın açıklamasına bakın. Bu bayraklar, OR kullanılarak birleştirilebilir. |
| filter | INodeFilter | this TreeWalker ile kullanılacak NodeFilter veya filtre olmadığını belirtmek için null. |

### Geri dönüş değeri

Yeni oluşturulan NodeIterator.

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Belirtilen kök is null ise yükseltilir. |

### Ayrıca bakınız

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* ad alanı [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* toplantı [Aspose.HTML](../../../)


