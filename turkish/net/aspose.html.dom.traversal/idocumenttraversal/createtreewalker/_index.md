---
title: IDocumentTraversal.CreateTreeWalker
second_title: Aspose.HTML for .NET API Referansı
description: IDocumentTraversal yöntem. Belirtilen düğümde köklenen alt ağaç üzerinde yeni bir TreeWalker oluşturun.
type: docs
weight: 20
url: /tr/net/aspose.html.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Belirtilen düğümde köklenen alt ağaç üzerinde yeni bir TreeWalker oluşturun.

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| root | Node | the TreeWalker için kök görevi görecek düğüm. Bu değer ayarlanırken whatToShow bayrakları ve the NodeFilter dikkate alınmaz; herhangi bir düğüm türü kök olarak kabul edilir. TreeWalker'ın currentNode is , görünür olsun ya da olmasın bu düğüme başlatıldı. kökü, parentNode ve nextNode gibi belge yapısında yukarı bakan traversal yöntemleri için bir durma noktası işlevi görür. Kök must boş olmamalıdır. |

### Geri dönüş değeri

Yeni oluşturulan TreeWalker.

### Ayrıca bakınız

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* ad alanı [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* toplantı [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Belirtilen düğümde köklenen alt ağaç üzerinde yeni bir TreeWalker oluşturun.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| root | Node | the TreeWalker için kök görevi görecek düğüm. Bu değer ayarlanırken whatToShow bayrakları ve the NodeFilter dikkate alınmaz; herhangi bir düğüm türü kök olarak kabul edilir. TreeWalker'ın currentNode is , görünür olsun ya da olmasın bu düğüme başlatıldı. kökü, parentNode ve nextNode gibi belge yapısında yukarı bakan traversal yöntemleri için bir durma noktası işlevi görür. Kök must boş olmamalıdır. |
| whatToShow | Int64 | bayrak, ağaç gezgini tarafından sunulan ağacın mantıksal görünümünde içinde hangi düğüm türlerinin görünebileceğini belirtir. Olası SHOW_ değerleri kümesi için NodeFilter'ın açıklamasına bakın. Bu bayraklar OR kullanılarak birleştirilebilir. |

### Geri dönüş değeri

Yeni oluşturulan TreeWalker.

### Ayrıca bakınız

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* ad alanı [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* toplantı [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Belirtilen düğümde köklenen alt ağaç üzerinde yeni bir TreeWalker oluşturun.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| root | Node | the TreeWalker için kök görevi görecek düğüm. Bu değer ayarlanırken whatToShow bayrakları ve the NodeFilter dikkate alınmaz; herhangi bir düğüm türü kök olarak kabul edilir. TreeWalker'ın currentNode is , görünür olsun ya da olmasın bu düğüme başlatıldı. kökü, parentNode ve nextNode gibi belge yapısında yukarı bakan traversal yöntemleri için bir durma noktası işlevi görür. Kök must boş olmamalıdır. |
| whatToShow | Int64 | bayrak, ağaç gezgini tarafından sunulan ağacın mantıksal görünümünde içinde hangi düğüm türlerinin görünebileceğini belirtir. Olası SHOW_ değerleri kümesi için NodeFilter'ın açıklamasına bakın. Bu bayraklar OR kullanılarak birleştirilebilir. |
| filter | INodeFilter | this TreeWalker ile kullanılacak NodeFilter veya filtre olmadığını belirtmek için null. |

### Geri dönüş değeri

Yeni oluşturulan TreeWalker.

### Ayrıca bakınız

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* ad alanı [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* toplantı [Aspose.HTML](../../../)


