---
title: Class NodeFilter
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Traversal.Filters.NodeFilter sınıf. Filtreler düğümlerin nasıl filtreleneceğini bilen nesnelerdir.
type: docs
weight: 2460
url: /tr/net/aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Filtreler, düğümlerin nasıl "filtreleneceğini" bilen nesnelerdir.

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## yöntemler

| İsim | Tanım |
| --- | --- |
| abstract [AcceptNode](../../aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | Belirli bir düğümün a TreeWalker veya NodeIterator mantıksal görünümünde görünür olup olmadığını test edin. Bu işlev , TreeWalker ve NodeIterator uygulaması tarafından çağrılacaktır; normalde doğrudan from kullanıcı kodu olarak adlandırılmaz. (Yine de kendi uygulama mantığınıza rehberlik etmesi için same filtresini kullanmak isterseniz bunu yapabilirsiniz.) |
| override [GetPlatformType](../../aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | Bu yöntem ECMAScript nesnesini almak için kullanılır.Type . |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | Düğümü kabul edin. NodeIterator veya TreeWalker için tanımlanan gezinme yöntemleri bu düğümünü döndürür. |
| const [FILTER_REJECT](../../aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | Düğümü reddet. NodeIterator veya TreeWalker için tanımlanan gezinme yöntemleri bu düğümü döndürmez. TreeWalker için, bu düğümünün alt öğeleri de reddedilecektir. NodeIterators, bunu FILTER_SKIP. ile eşanlamlısı olarak ele alır. |
| const [FILTER_SKIP](../../aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | Bu tek düğümü atla. NodeIterator veya TreeWalker için tanımlanan gezinme yöntemleri bu düğümü döndürmez. Hem NodeIterator hem de TreeWalker için, bu düğümün alt öğeleri yine de olarak kabul edilecektir. |
| const [SHOW_ALL](../../aspose.html.dom.traversal.filters/nodefilter/show_all/) | Tüm Düğümleri göster. |
| const [SHOW_ATTRIBUTE](../../aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | Öznitelik düğümlerini göster. Bu yalnızca, kökü olarak bir öznitelik düğümü olan bir yineleyici veya ağaç yürütücü oluştururken anlamlıdır; bu durumda, öznitelik düğümünün yinelemenin veya geçişin ilk konumunda görüneceği anlamına gelir. Nitelikler hiçbir zaman diğer düğümlerin çocukları olmadığından, belge ağacı üzerinde gezinirken görünmezler. |
| const [SHOW_CDATA_SECTION](../../aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | CDATASection düğümlerini göster. |
| const [SHOW_COMMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_comment/) | Yorum düğümlerini göster. |
| const [SHOW_DOCUMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document/) | Belge düğümlerini göster. |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | DocumentFragment düğümlerini göster. |
| const [SHOW_DOCUMENT_TYPE](../../aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | DocumentType düğümlerini göster. |
| const [SHOW_ELEMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_element/) | Öğe düğümlerini göster. |
| const [SHOW_ENTITY](../../aspose.html.dom.traversal.filters/nodefilter/show_entity/) | Varlık düğümlerini göster. Bu yalnızca, kökü olarak bir Varlık düğümü olan bir yineleyici veya ağaç yürütücüsü oluştururken anlamlıdır; bu durumda, Entity düğümünün geçişin ilk konumunda görüneceği anlamına gelir. varlıkları belge ağacının parçası olmadığından, belge ağacı üzerinde gezinirken görünmezler. |
| const [SHOW_ENTITY_REFERENCE](../../aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | EntityReference düğümlerini göster. |
| const [SHOW_NOTATION](../../aspose.html.dom.traversal.filters/nodefilter/show_notation/) | Gösterim düğümlerini göster. Bu yalnızca, kökü olarak bir Gösterim düğümü olan bir yineleyici veya ağaç yürütücüsü oluştururken anlamlıdır; bu durumda, Gösterim düğümünün geçişinin ilk konumunda görüneceği anlamına gelir. Gösterimler belge ağacının parçası olmadığından, belge ağacı üzerinde gezinirken görünmezler. |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | İşleme Talimatı düğümlerini göster. |
| const [SHOW_TEXT](../../aspose.html.dom.traversal.filters/nodefilter/show_text/) | Metin düğümlerini göster. |

### Ayrıca bakınız

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [INodeFilter](../../aspose.html.dom.traversal/inodefilter/)
* ad alanı [Aspose.Html.Dom.Traversal.Filters](../../aspose.html.dom.traversal.filters/)
* toplantı [Aspose.HTML](../../)


