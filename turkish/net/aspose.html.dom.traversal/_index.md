---
title: Aspose.Html.Dom.Traversal
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Traversalad alanı öğeler arasında gezinmek için yineleyiciler ve ağaç yürüyüşçüleri oluşturan yöntemleri içerir ve bir düğümü ve alt öğelerini belge sırasında dolaşır.
type: docs
weight: 170
url: /tr/net/aspose.html.dom.traversal/
---
**Aspose.Html.Dom.Traversal**ad alanı, öğeler arasında gezinmek için yineleyiciler ve ağaç yürüyüşçüleri oluşturan yöntemleri içerir ve bir düğümü ve alt öğelerini belge sırasında dolaşır.

## Arayüzler

| Arayüz | Tanım |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal, bir düğümü ve alt öğelerini belge sırasına göre (önce derinlik , ön sipariş geçişi; döküman). Geçiş özelliğini destekleyen DOM'larda DocumentTraversal, Belge arabirimini uygulayan aynı nesneler tarafından uygulanacaktır. |
| [IElementTraversal](./ielementtraversal/) | ElementTraversal arabirimi, bir yazarın bir belgedeki öğeler arasında kolayca gezinmesini sağlayan bir dizi salt okunur özniteliktir. Element Traversal'ın uyumlu uygulamalarında, Element'i uygulayan tüm nesnelerin ElementTraversal arayüzünü de uygulaması gerekir. |
| [INodeFilter](./inodefilter/) | Filtreler, düğümlerin nasıl "filtreleneceğini" bilen nesnelerdir. Bir NodeIterator veya TreeWalker'a bir NodeFilter verilirse, sonraki düğümünü döndürmeden önce filtreyi uygular. Filtre düğümü kabul et diyorsa, geçiş mantığı onu döndürür; aksi takdirde, geçiş bir sonraki düğümü arar ve reddedilen düğümü orada değilmiş gibi davranır. |
| [INodeIterator](./inodeiterator/) | Yineleyiciler, örneğin bir NodeList'teki düğüm kümesi, belirli bir Düğüm tarafından yönetilen belge alt ağacı, bir sorgunun sonuçları veya başka herhangi bir düğüm kümesi gibi bir dizi düğüm arasında ilerlemek için kullanılır. Yinelenecek düğüm kümesi, NodeIterator'ın uygulaması tarafından belirlenir. DOM Düzey 2, bir belge alt ağacının belge sırası geçişi için bir tek NodeIterator uygulamasını belirtir. Bu yineleyicilerin örnekleri DocumentTraversal .createNodeIterator(). çağrılarak oluşturulur. |
| [ITraversal](./itraversal/) | Yineleyiciler, örneğin bir NodeList'teki düğüm kümesi, belirli bir Düğüm tarafından yönetilen belge alt ağacı, bir sorgunun sonuçları veya başka herhangi bir düğüm kümesi gibi bir dizi düğüm arasında ilerlemek için kullanılır. Yinelenecek düğüm kümesi, NodeIterator'ın uygulaması tarafından belirlenir. DOM Düzey 2, bir belge alt ağacının belge sırası geçişi için bir tek NodeIterator uygulamasını belirtir. Bu yineleyicilerin örnekleri DocumentTraversal .createNodeIterator(). çağrılarak oluşturulur. |
| [ITreeWalker](./itreewalker/) | TreeWalker nesneleri, whatToShow bayrakları ve (varsa) filtresi tarafından tanımlanan belgenin görünümünü kullanarak bir belge ağacında veya alt ağacında gezinmek için kullanılır. 'nin bir TreeWalker kullanarak gezinme gerçekleştirdiği herhangi bir işlev, bir TreeWalker. tarafından tanımlanan herhangi bir görünümü otomatik olarak destekleyecektir. |


