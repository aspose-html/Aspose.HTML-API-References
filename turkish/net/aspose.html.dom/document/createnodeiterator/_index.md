---
title: Document.CreateNodeIterator
second_title: Aspose.HTML for .NET API Referansı
description: Document yöntem. Belirtilen node. de köklenen alt ağaç üzerinde yeni bir NodeIterator oluşturun.
type: docs
weight: 900
url: /tr/net/aspose.html.dom/document/createnodeiterator/
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
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Belirtilen kök is null ise yükseltilir. |

### Ayrıca bakınız

* interface [INodeIterator](../../../aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* ad alanı [Aspose.Html.Dom](../../document/)
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
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Belirtilen kök is null ise yükseltilir. |

### Ayrıca bakınız

* interface [INodeIterator](../../../aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* ad alanı [Aspose.Html.Dom](../../document/)
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
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Belirtilen kök is null ise yükseltilir. |

### Ayrıca bakınız

* interface [INodeIterator](../../../aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* ad alanı [Aspose.Html.Dom](../../document/)
* toplantı [Aspose.HTML](../../../)


