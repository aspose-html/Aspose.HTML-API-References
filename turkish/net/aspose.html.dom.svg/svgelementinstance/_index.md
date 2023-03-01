---
title: Class SVGElementInstance
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Svg.SVGElementInstance sınıf. Her kullanım öğesi gölge ağacının kök nesnesi SVGUseElementShadowRoot arabirimini uygular. Bu arabirim şu anda ShadowRoot arabirimi ve DocumentOrShadowRoot karışımı için tanımlanan özellik ve yöntemlere yönelik herhangi bir uzantı tanımlamamaktadır. Ancak bu düğümde köklenen ağaç yazar komut dosyaları açısından tamamen salt okunurdur.
type: docs
weight: 2030
url: /tr/net/aspose.html.dom.svg/svgelementinstance/
---
## SVGElementInstance class

Her kullanım öğesi gölge ağacının kök nesnesi, SVGUseElementShadowRoot arabirimini uygular. Bu arabirim şu anda ShadowRoot arabirimi ve DocumentOrShadowRoot karışımı için tanımlanan özellik ve yöntemlere yönelik herhangi bir uzantı tanımlamamaktadır. Ancak, bu düğümde köklenen ağaç, yazar komut dosyaları açısından tamamen salt okunurdur.

```csharp
public class SVGElementInstance : ShadowRoot
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes/) { get; } | Bu düğümün özniteliklerini (bir Öğe ise) içeren bir NamedNodeMap veya aksi halde null. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri/) { get; } | Bu düğümün mutlak temel URI'si veya uygulama mutlak bir URI elde edemediyse null. |
| [ChildElementCount](../../aspose.html.dom/documentfragment/childelementcount/) { get; } | Bu öğenin çocukları olan öğe düğümlerinin geçerli sayısını döndürür. 0, eğer bu elemanın nodeType 1. olan alt düğümleri yoksa |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | Bu düğümün tüm alt öğelerini içeren bir NodeList. Alt öğe yoksa bu, düğüm içermeyen bir NodeList'tir.. |
| [Children](../../aspose.html.dom/documentfragment/children/) { get; } | Geçerli öğenin alt öğelerini döndürür. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | Bu düğümün ilk çocuğu. Böyle bir düğüm yoksa bu, null. değerini döndürür. |
| [FirstElementChild](../../aspose.html.dom/documentfragment/firstelementchild/) { get; } | Bu öğenin ilk alt öğe düğümünü döndürür. bu öğenin alt öğesi yoksa null. |
| [Host](../../aspose.html.dom/shadowroot/host/) { get; } | Host, bu ShadowRoot'u içeren bir öğedir. |
| [InnerHTML](../../aspose.html.dom/documentfragment/innerhtml/) { get; set; } | Öğenin içeriğini temsil eden bir HTML veya XML parçası döndürür. Öğenin içeriğini verilen dizgiden ayrıştırılan düğümlerle değiştirmek için ayarlanabilir. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | Bu düğümün son çocuğu. Böyle bir düğüm yoksa bu, null. değerini döndürür. |
| [LastElementChild](../../aspose.html.dom/documentfragment/lastelementchild/) { get; } | Bu öğenin son alt öğe düğümünü döndürür. bu öğenin alt öğesi yoksa null. |
| virtual [LocalName](../../aspose.html.dom/node/localname/) { get; } | Bu düğümün nitelikli adının yerel kısmını döndürür. ELEMENT_NODE ve ATTRIBUTE_NODE dışında herhangi bir türdeki düğümler ve Document.createElement() gibi DOM Düzey 1 yöntemiyle oluşturulan düğümler için bu her zaman boştur. |
| [Mode](../../aspose.html.dom/shadowroot/mode/) { get; } | Bu ShadowRoot'un çalıştığı mod. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri/) { get; } | Bu düğümün ad alanı URI'si veya belirtilmemişse boş. |
| [NextElementSibling](../../aspose.html.dom/documentfragment/nextelementsibling/) { get; } | Bu öğenin bir sonraki kardeş öğe düğümünü döndürür. Bu öğenin, belge ağacında bundan sonra gelen hiçbir öğe kardeş düğümü yoksa boş değer. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | Bu düğümü hemen takip eden düğüm. Böyle bir düğüm yoksa bu, null. değerini döndürür. |
| override [NodeName](../../aspose.html.dom/documentfragment/nodename/) { get; } | Türüne bağlı olarak bu düğümün adı. |
| override [NodeType](../../aspose.html.dom/documentfragment/nodetype/) { get; } | Altta yatan nesnenin türünü temsil eden bir kod. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | Türüne bağlı olarak bu düğümün değeri. |
| [OuterHTML](../../aspose.html.dom/documentfragment/outerhtml/) { get; set; } | Öğeyi ve içeriğini temsil eden bir HTML veya XML parçasını döndürür. Öğeyi verilen dizgiden ayrıştırılan düğümlerle değiştirmek için ayarlanabilir. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument/) { get; } | Bu düğümle ilişkili Belge nesnesi. Bu aynı zamanda yeni düğümler oluşturmak için kullanılan Belge nesnesidir. Bu düğüm, henüz herhangi bir Belge ile kullanılmayan bir Belge veya Belge Türü olduğunda, bu null. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Ebeveyni alır[`Element`](../../aspose.html.dom/element/) bu düğümün. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | Bu düğümün ebeveyni. Attr, Document, DocumentFragment, Entity ve Notation dışındaki tüm düğümlerin bir üst öğesi olabilir. Ancak, bir düğüm yeni oluşturulmuşsa ve henüz ağaca eklenmemişse veya ağaçtan kaldırılmışsa, bu null. olur. |
| virtual [Prefix](../../aspose.html.dom/node/prefix/) { get; set; } | Bu düğümün ad alanı öneki veya belirtilmemişse boş. Boş olarak tanımlandığında, ayarının etkisi yoktur |
| [PreviousElementSibling](../../aspose.html.dom/documentfragment/previouselementsibling/) { get; } | Bu öğenin önceki kardeş öğe düğümünü döndürür. Bu öğenin, belge ağacında bundan önce gelen hiçbir öğe kardeş düğümü yoksa boş değer. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | Bu düğümden hemen önceki düğüm. Böyle bir düğüm yoksa bu, null. değerini döndürür. |
| override [TextContent](../../aspose.html.dom/documentfragment/textcontent/) { get; set; } | Bu öznitelik, bu düğümün ve onun soyundan gelenlerin metin içeriğini döndürür. Null olarak tanımlandığında, ayarının hiçbir etkisi yoktur. Ayarlama sırasında, bu düğümün sahip olabileceği tüm olası alt öğeler kaldırılır ve yeni dize boş veya boş değilse, bu özniteliğin ayarlandığı dizeyi içeren tek bir Metin düğümü ile değiştirilir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine izin verir. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine izin verir. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine izin verir. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | newChild düğümünü bu düğümün çocukları listesinin sonuna ekler. newChild zaten ağaçtaysa, önce kaldırılır. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | Bu düğümün bir kopyasını döndürür, yani düğümler için genel bir kopya oluşturucu görevi görür. Yinelenen düğümün üst öğesi (parentNode boştur) ve kullanıcı verisi yoktur. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | Bu düğümün bir kopyasını döndürür, yani düğümler için genel bir kopya oluşturucu görevi görür. Yinelenen düğümün üst öğesi (parentNode boştur) ve kullanıcı verisi yoktur. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Bu yöntem, olayların uygulama olay modeline gönderilmesine izin verir. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Yönetilmeyen kaynakları serbest bırakma, serbest bırakma veya sıfırlama ile ilişkili uygulama tanımlı görevleri gerçekleştirir. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Bu yöntem ECMAScript nesnesini almak için kullanılır.Type . |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes/)() | Bu düğümün (eğer bir öğe ise) herhangi bir özniteliği olup olmadığını döndürür |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | Bu düğümün herhangi bir alt öğesi olup olmadığını döndürür. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | Düğümü varolan alt düğüm alt öğesinden önce ekler. Child null ise, çocuklar listesinin sonuna düğüm ekleyin. Child bir DocumentFragment nesnesiyse, tüm alt öğeleri aynı sırayla alt öğeden önce eklenir. Çocuk zaten ağaçtaysa, önce kaldırılır. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | Bu yöntem, belirtilen namespaceURI'nin varsayılan ad alanı olup olmadığını kontrol eder. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | İki düğümün eşit olup olmadığını test eder. Bu yöntem, Node.isSameNode() ile test edilebilen aynılığı (yani iki düğümün aynı nesneye referans olup olmadığını) değil, düğümlerin eşitliğini test eder. Aynı olan tüm düğümler de eşit olacaktır, ancak tersi doğru olmayabilir. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | Bu düğümün verilenle aynı düğüm olup olmadığını döndürür. Bu yöntem, uygulama tarafından döndürülen iki Düğüm başvurusunun aynı nesneye başvuruda bulunup bulunmadığını belirlemenin bir yolunu sağlar. İki Düğüm referansı aynı nesneye referans olduğunda, bir proxy üzerinden olsa bile, referanslar tamamen birbirinin yerine kullanılabilir, böylece tüm öznitelikler aynı değerlere sahip olur ve her iki referansta da aynı DOM yöntemini çağırmak her zaman tam olarak aynı etkiye sahip olur. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | Bu düğümden başlayarak verilen önekle ilişkili ad alanı URI'sine bakın. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | Bu düğümden başlayarak verilen ad alanı URI'si ile ilişkili öneki arayın. Varsayılan ad alanı bildirimleri bu yöntem tarafından dikkate alınmaz. Bu yöntem tarafından kullanılan algoritma hakkında ayrıntılar için Ad Alanı Öneki Arama'ya bakın. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Öznitelik düğümleri de dahil olmak üzere, bu Düğümün altındaki alt ağacın tüm derinliğindeki tüm Metin düğümlerini, Metni yalnızca yapının (örneğin, öğeler, yorumlar, işleme yönergeleri, CDATA bölümleri ve varlık referansları) ayırdığı "normal" bir forma sokar. düğümler, yani bitişik Metin düğümleri veya boş Metin düğümleri yoktur. Bu, bir belgenin DOM görünümünün, kaydedilmiş ve yeniden yüklenmiş haliyle aynı olmasını sağlamak için kullanılabilir ve belirli bir belge ağacı yapısına bağlı olan işlemler (XPointer [XPointer] aramaları gibi) kullanılmalı Node.ownerDocument'e eklenen DOMConfiguration nesnesinin "normalize-characters" parametresi doğruysa, bu yöntem Metin düğümlerinin karakterlerini de tam olarak normalleştirir. |
| [QuerySelector](../../aspose.html.dom/documentfragment/queryselector/)(string) | Belgedeki seçici ile eşleşen ilk Elemanı döndürür |
| [QuerySelectorAll](../../aspose.html.dom/documentfragment/queryselectorall/)(string) | Belgedeki tüm Öğelerin seçici ile eşleşen bir Düğüm Listesini döndürür |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | oldChild tarafından belirtilen alt düğümü alt öğe listesinden kaldırır ve onu döndürür. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer bir[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) bir yerden kaldırılır[`EventTarget`](../../aspose.html.dom/eventtarget/) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler, kaldırıldıktan sonra asla çağrılamaz. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer bir[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) bir yerden kaldırılır[`EventTarget`](../../aspose.html.dom/eventtarget/) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler, kaldırıldıktan sonra asla çağrılamaz. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer bir[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) bir yerden kaldırılır[`EventTarget`](../../aspose.html.dom/eventtarget/) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler, kaldırıldıktan sonra asla çağrılamaz. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | Alt düğüm listesindeki oldChild alt düğümünü newChild ile değiştirir ve oldChild düğümünü döndürür. newChild bir DocumentFragment nesnesiyse, eskiChild aynı sırayla eklenen tüm DocumentFragment alt öğeleriyle değiştirilir. newChild zaten ağaçtaysa, önce kaldırılır. |
| override [ToString](../../aspose.html.dom/node/tostring/)() | a döndürürString bu örneği temsil eder. |

### Ayrıca bakınız

* class [ShadowRoot](../../aspose.html.dom/shadowroot/)
* ad alanı [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg/)
* toplantı [Aspose.HTML](../../)


