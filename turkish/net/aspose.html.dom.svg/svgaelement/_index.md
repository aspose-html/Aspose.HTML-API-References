---
title: Class SVGAElement
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Svg.SVGAElement sınıf. SVGAElement arabirimi a öğesine karşılık gelir.
type: docs
weight: 1900
url: /tr/net/aspose.html.dom.svg/svgaelement/
---
## SVGAElement class

SVGAElement arabirimi 'a' öğesine karşılık gelir.

```csharp
public class SVGAElement : SVGGraphicsElement, ISVGURIReference
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| override [Attributes](../../aspose.html.dom/element/attributes/) { get; } | Bu düğümün özniteliklerini (bir Öğe ise) içeren bir NamedNodeMap veya aksi halde null. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri/) { get; } | Bu düğümün mutlak temel URI'si veya uygulama mutlak bir URI elde edemediyse null. |
| [ChildElementCount](../../aspose.html.dom/element/childelementcount/) { get; } | Bu öğenin çocukları olan öğe düğümlerinin geçerli sayısını döndürür. 0, eğer bu elemanın nodeType 1. olan alt düğümleri yoksa |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | Bu düğümün tüm alt öğelerini içeren bir NodeList. Alt öğe yoksa bu, düğüm içermeyen bir NodeList'tir.. |
| [Children](../../aspose.html.dom/element/children/) { get; } | Geçerli öğenin alt öğelerini döndürür. |
| [ClassList](../../aspose.html.dom/element/classlist/) { get; } | "class" niteliğinin ayrıştırılmasından alınan belirteçleri içeren canlı bir DOMTokenList döndürür. |
| [ClassName](../../aspose.html.dom.svg/svgelement/classname/) { get; } | Belirtilen öğede 'sınıf' özniteliğine karşılık gelir. |
| [ClassName](../../aspose.html.dom/element/classname/) { get; set; } | Öğenin sınıf özniteliği. Bu öznitelik, birçok dilde kullanılan "class" anahtar sözcüğüyle çakışması için due olarak yeniden adlandırıldı. See HTML 4.01. 'deki sınıf özelliği tanımı |
| [FarthestViewportElement](../../aspose.html.dom.svg/svggraphicselement/farthestviewportelement/) { get; } | En uzak ata 'svg' öğesi. Geçerli öğe en dıştaki svg öğesiyse boş. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | Bu düğümün ilk çocuğu. Böyle bir düğüm yoksa bu, null. değerini döndürür. |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild/) { get; } | Bu öğenin ilk alt öğe düğümünü döndürür. bu öğenin alt öğesi yoksa null. |
| [Href](../../aspose.html.dom.svg/svgaelement/href/) { get; } | Belirtilen öğede 'xlink:href' özelliğine karşılık gelir. |
| [Id](../../aspose.html.dom.svg/svgelement/id/) { get; set; } | Belirtilen öğedeki 'id' özniteliğinin değeri veya 'id' yoksa boş dize. |
| [InnerHTML](../../aspose.html.dom/element/innerhtml/) { get; set; } | Öğenin içeriğini temsil eden bir HTML veya XML parçası döndürür. Öğenin içeriğini verilen dizgiden ayrıştırılan düğümlerle değiştirmek için ayarlanabilir. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | Bu düğümün son çocuğu. Böyle bir düğüm yoksa bu, null. değerini döndürür. |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild/) { get; } | Bu öğenin son alt öğe düğümünü döndürür. bu öğenin alt öğesi yoksa null. |
| override [LocalName](../../aspose.html.dom/element/localname/) { get; } | Bu düğümün nitelikli adının yerel kısmını döndürür. ELEMENT_NODE ve ATTRIBUTE_NODE dışında herhangi bir türdeki düğümler ve Document.createElement() gibi DOM Düzey 1 yöntemiyle oluşturulan düğümler için bu her zaman boştur. |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri/) { get; } | Bu düğümün ad alanı URI'si veya belirtilmemişse boş. |
| [NearestViewportElement](../../aspose.html.dom.svg/svggraphicselement/nearestviewportelement/) { get; } | Geçerli görünümü oluşturan öğe. Genellikle en yakın ata olan 'svg' öğesi. Geçerli öğe en dıştaki svg öğesiyse boş. |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling/) { get; } | Bu öğenin bir sonraki kardeş öğe düğümünü döndürür. Bu öğenin, belge ağacında bundan sonra gelen hiçbir öğe kardeş düğümü yoksa boş değer. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | Bu düğümü hemen takip eden düğüm. Böyle bir düğüm yoksa bu, null. değerini döndürür. |
| override [NodeName](../../aspose.html.dom/element/nodename/) { get; } | Türüne bağlı olarak bu düğümün adı. |
| override [NodeType](../../aspose.html.dom/element/nodetype/) { get; } | Altta yatan nesnenin türünü temsil eden bir kod. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | Türüne bağlı olarak bu düğümün değeri. |
| [OuterHTML](../../aspose.html.dom/element/outerhtml/) { get; set; } | Öğeyi ve içeriğini temsil eden bir HTML veya XML parçasını döndürür. Öğeyi verilen dizgiden ayrıştırılan düğümlerle değiştirmek için ayarlanabilir. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument/) { get; } | Bu düğümle ilişkili Belge nesnesi. Bu aynı zamanda yeni düğümler oluşturmak için kullanılan Belge nesnesidir. Bu düğüm, henüz herhangi bir Belge ile kullanılmayan bir Belge veya Belge Türü olduğunda, bu null. |
| [OwnerSVGElement](../../aspose.html.dom.svg/svgelement/ownersvgelement/) { get; } | En yakın ata 'svg' öğesi. Belirtilen öğe en dıştaki svg öğesiyse boş. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Ebeveyni alır[`Element`](../../aspose.html.dom/element/) bu düğümün. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | Bu düğümün ebeveyni. Attr, Document, DocumentFragment, Entity ve Notation dışındaki tüm düğümlerin bir üst öğesi olabilir. Ancak, bir düğüm yeni oluşturulmuşsa ve henüz ağaca eklenmemişse veya ağaçtan kaldırılmışsa, bu null. olur. |
| override [Prefix](../../aspose.html.dom/element/prefix/) { get; } | Bu düğümün ad alanı öneki veya belirtilmemişse boş. Boş olarak tanımlandığında, ayarının etkisi yoktur |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling/) { get; } | Bu öğenin önceki kardeş öğe düğümünü döndürür. Bu öğenin, belge ağacında bundan önce gelen hiçbir öğe kardeş düğümü yoksa boş değer. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | Bu düğümden hemen önceki düğüm. Böyle bir düğüm yoksa bu, null. değerini döndürür. |
| [RequiredExtensions](../../aspose.html.dom.svg/svggraphicselement/requiredextensions/) { get; } | Belirtilen öğede 'requiredExtensions' özniteliğine karşılık gelir. |
| [RequiredFeatures](../../aspose.html.dom.svg/svggraphicselement/requiredfeatures/) { get; } | Belirtilen öğede 'requiredFeatures' özniteliğine karşılık gelir. |
| [SchemaTypeInfo](../../aspose.html.dom/element/schematypeinfo/) { get; } | Bu öğeyle ilişkili tür bilgisi. |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot/) { get; } | Bu öğede depolanan shadowRoot'u veya kapalıysa boş değeri döndürür. |
| [Style](../../aspose.html.dom.svg/svgelement/style/) { get; } | Verilen öğedeki 'stil' özniteliğine karşılık gelir. Kullanıcı aracısı CSS ile stil vermeyi desteklemiyorsa, bu öznitelik her zaman null. değerine sahip olmalıdır. |
| [SystemLanguage](../../aspose.html.dom.svg/svggraphicselement/systemlanguage/) { get; } | Verilen öğedeki 'systemLanguage' özniteliğine karşılık gelir. |
| [TagName](../../aspose.html.dom/element/tagname/) { get; } | Öğenin adı. |
| [Target](../../aspose.html.dom.svg/svgaelement/target/) { get; } | Verilen 'a' öğesindeki 'hedef' özniteliğine karşılık gelir. |
| override [TextContent](../../aspose.html.dom/element/textcontent/) { get; set; } | Bu öznitelik, bu düğümün ve onun soyundan gelenlerin metin içeriğini döndürür. Null olarak tanımlandığında, ayarının hiçbir etkisi yoktur. Ayarlama sırasında, bu düğümün sahip olabileceği tüm olası alt öğeler kaldırılır ve yeni dize boş veya boş değilse, bu özniteliğin ayarlandığı dizeyi içeren tek bir Metin düğümü ile değiştirilir. |
| [Transform](../../aspose.html.dom.svg/svggraphicselement/transform/) { get; } | Belirtilen öğede 'dönüştürme' özelliğine karşılık gelir. |
| [ViewportElement](../../aspose.html.dom.svg/svgelement/viewportelement/) { get; } | Geçerli görünümü oluşturan öğe. Genellikle en yakın ata olan 'svg' öğesi. Belirtilen öğe en dıştaki svg öğesiyse boş. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine izin verir. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine izin verir. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine izin verir. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | newChild düğümünü bu düğümün çocukları listesinin sonuna ekler. newChild zaten ağaçtaysa, önce kaldırılır. |
| [AttachShadow](../../aspose.html.dom/element/attachshadow/)(ShadowRootMode) | Gölge kökü oluşturur ve onu geçerli öğeye ekler. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | Bu düğümün bir kopyasını döndürür, yani düğümler için genel bir kopya oluşturucu görevi görür. Yinelenen düğümün üst öğesi (parentNode boştur) ve kullanıcı verisi yoktur. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | Bu düğümün bir kopyasını döndürür, yani düğümler için genel bir kopya oluşturucu görevi görür. Yinelenen düğümün üst öğesi (parentNode boştur) ve kullanıcı verisi yoktur. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Bu yöntem, olayların uygulama olay modeline gönderilmesine izin verir. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Yönetilmeyen kaynakları serbest bırakma, serbest bırakma veya sıfırlama ile ilişkili uygulama tanımlı görevleri gerçekleştirir. |
| [GetAttribute](../../aspose.html.dom/element/getattribute/)(string) | Ada göre bir öznitelik değeri alır. |
| [GetAttributeNode](../../aspose.html.dom/element/getattributenode/)(string) | Ada göre bir öznitelik düğümü alır. |
| [GetAttributeNodeNS](../../aspose.html.dom/element/getattributenodens/)(string, string) | Yerel ada ve ad alanı URI'sine göre bir Öznitelik düğümü alır. |
| [GetAttributeNS](../../aspose.html.dom/element/getattributens/)(string, string) | Yerel ada ve ad alanı URI'sine göre bir öznitelik değeri alır. |
| [GetBBox](../../aspose.html.dom.svg/svggraphicselement/getbbox/)() | Vuruş, kırpma, maskeleme ve filtre efektleri hariç, içerilen tüm grafik öğelerinin geometrisinde geçerli kullanıcı alanındaki (yani, varsa 'dönüştürme' özniteliğinin uygulanmasından sonra) sıkı sınırlayıcı kutuyu döndürür. Öğe henüz oluşturulmamış olsa bile getBBox'ın yöntemin çağrıldığı sırada asıl sınırlayıcı kutuyu döndürmesi gerektiğini unutmayın. |
| [GetCTM](../../aspose.html.dom.svg/svggraphicselement/getctm/)() | Geçerli kullanıcı birimlerinden (yani, varsa 'transform' özniteliğinin uygulanmasından sonra) en yakın ViewportElement. için görünüm alanı koordinat sistemine dönüşüm matrisini döndürür |
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname/)(string) | Argümanda belirtilen tüm sınıflara sahip belgedeki tüm öğeleri içeren canlı bir NodeList nesnesi döndürür. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname/)(string) | Belirli bir etiket adına sahip tüm alt Elemanların belge sırasına göre bir Düğüm Listesini döndürür. |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens/)(string, string) | Belirli bir yerel ada ve ad alanı URI'sine sahip tüm alt Elemanların bir Düğüm Listesini belge sırasına göre döndürür. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Bu yöntem ECMAScript nesnesini almak için kullanılır.Type . |
| [GetScreenCTM](../../aspose.html.dom.svg/svggraphicselement/getscreenctm/)() | Geçerli kullanıcı birimlerinden (yani, varsa 'dönüştürme' özniteliğinin uygulanmasından sonra) ana kullanıcı aracısının bir "piksel" bildirimine dönüşüm matrisini döndürür. Görüntüleme cihazları için ideal olarak bu, fiziksel bir ekran pikselini temsil eder. Fiziksel piksel boyutlarının bilinmediği diğer cihazlar veya ortamlar için bunun yerine CSS2'nin "piksel" tanımına benzer bir algoritma kullanılabilir. Bu öğe belge ağacına bağlı değilse null döndürüldüğünü unutmayın. Bu yöntem daha uygun bir şekilde getClientCTM olarak adlandırılabilirdi, ancak getScreenCTM adı tarihsel nedenlerle korunuyor. |
| [HasAttribute](../../aspose.html.dom/element/hasattribute/)(string) | Bu öğede belirli bir ada sahip bir öznitelik belirtildiğinde veya varsayılan bir değere sahip olduğunda true, aksi takdirde false döndürür. |
| [HasAttributeNS](../../aspose.html.dom/element/hasattributens/)(string, string) | Bu öğede belirli bir yerel ada ve ad alanı URI'sine sahip bir öznitelik belirtildiğinde veya varsayılan bir değere sahip olduğunda doğru, aksi takdirde yanlış olur. |
| override [HasAttributes](../../aspose.html.dom/element/hasattributes/)() | Bu düğümün (eğer bir öğe ise) herhangi bir özniteliği olup olmadığını döndürür |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | Bu düğümün herhangi bir alt öğesi olup olmadığını döndürür. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | Düğümü varolan alt düğüm alt öğesinden önce ekler. Child null ise, çocuklar listesinin sonuna düğüm ekleyin. Child bir DocumentFragment nesnesiyse, tüm alt öğeleri aynı sırayla alt öğeden önce eklenir. Çocuk zaten ağaçtaysa, önce kaldırılır. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | Bu yöntem, belirtilen namespaceURI'nin varsayılan ad alanı olup olmadığını kontrol eder. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | İki düğümün eşit olup olmadığını test eder. Bu yöntem, Node.isSameNode() ile test edilebilen aynılığı (yani iki düğümün aynı nesneye referans olup olmadığını) değil, düğümlerin eşitliğini test eder. Aynı olan tüm düğümler de eşit olacaktır, ancak tersi doğru olmayabilir. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | Bu düğümün verilenle aynı düğüm olup olmadığını döndürür. Bu yöntem, uygulama tarafından döndürülen iki Düğüm başvurusunun aynı nesneye başvuruda bulunup bulunmadığını belirlemenin bir yolunu sağlar. İki Düğüm referansı aynı nesneye referans olduğunda, bir proxy üzerinden olsa bile, referanslar tamamen birbirinin yerine kullanılabilir, böylece tüm öznitelikler aynı değerlere sahip olur ve her iki referansta da aynı DOM yöntemini çağırmak her zaman tam olarak aynı etkiye sahip olur. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | Bu düğümden başlayarak verilen önekle ilişkili ad alanı URI'sine bakın. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | Bu düğümden başlayarak verilen ad alanı URI'si ile ilişkili öneki arayın. Varsayılan ad alanı bildirimleri bu yöntem tarafından dikkate alınmaz. Bu yöntem tarafından kullanılan algoritma hakkında ayrıntılar için Ad Alanı Öneki Arama'ya bakın. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Öznitelik düğümleri de dahil olmak üzere, bu Düğümün altındaki alt ağacın tüm derinliğindeki tüm Metin düğümlerini, Metni yalnızca yapının (örneğin, öğeler, yorumlar, işleme yönergeleri, CDATA bölümleri ve varlık referansları) ayırdığı "normal" bir forma sokar. düğümler, yani bitişik Metin düğümleri veya boş Metin düğümleri yoktur. Bu, bir belgenin DOM görünümünün, kaydedilmiş ve yeniden yüklenmiş haliyle aynı olmasını sağlamak için kullanılabilir ve belirli bir belge ağacı yapısına bağlı olan işlemler (XPointer [XPointer] aramaları gibi) kullanılmalı Node.ownerDocument'e eklenen DOMConfiguration nesnesinin "normalize-characters" parametresi doğruysa, bu yöntem Metin düğümlerinin karakterlerini de tam olarak normalleştirir. |
| [QuerySelector](../../aspose.html.dom/element/queryselector/)(string) | Belgedeki seçici ile eşleşen ilk Elemanı döndürür |
| [QuerySelectorAll](../../aspose.html.dom/element/queryselectorall/)(string) | Belgedeki tüm Öğelerin seçici ile eşleşen bir Düğüm Listesini döndürür |
| [Remove](../../aspose.html.dom/element/remove/)() | Bu örneği kaldırır. |
| [RemoveAttribute](../../aspose.html.dom/element/removeattribute/)(string) | Ada göre bir özniteliği kaldırır. |
| [RemoveAttributeNode](../../aspose.html.dom/element/removeattributenode/)(Attr) | Belirtilen özniteliği kaldırır node. |
| [RemoveAttributeNS](../../aspose.html.dom/element/removeattributens/)(string, string) | Yerel ada ve ad alanı URI'sine göre bir özniteliği kaldırır. |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | oldChild tarafından belirtilen alt düğümü alt öğe listesinden kaldırır ve onu döndürür. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer bir[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) bir yerden kaldırılır[`EventTarget`](../../aspose.html.dom/eventtarget/) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler, kaldırıldıktan sonra asla çağrılamaz. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer bir[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) bir yerden kaldırılır[`EventTarget`](../../aspose.html.dom/eventtarget/) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler, kaldırıldıktan sonra asla çağrılamaz. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer bir[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) bir yerden kaldırılır[`EventTarget`](../../aspose.html.dom/eventtarget/) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler, kaldırıldıktan sonra asla çağrılamaz. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | Alt düğüm listesindeki oldChild alt düğümünü newChild ile değiştirir ve oldChild düğümünü döndürür. newChild bir DocumentFragment nesnesiyse, eskiChild aynı sırayla eklenen tüm DocumentFragment alt öğeleriyle değiştirilir. newChild zaten ağaçtaysa, önce kaldırılır. |
| [SetAttribute](../../aspose.html.dom/element/setattribute/)(string, string) | Yeni bir özellik ekler. Öğede bu ada sahip bir öznitelik zaten mevcutsa, değeri parametre değerine dönüştürülür. |
| [SetAttributeNode](../../aspose.html.dom/element/setattributenode/)(Attr) | Yeni bir öznitelik düğümü ekler. Öğede bu ada (nodeName) sahip bir öznitelik zaten varsa, yenisi ile değiştirilir. |
| [SetAttributeNodeNS](../../aspose.html.dom/element/setattributenodens/)(Attr) | Yeni bir özellik ekler. Öğede bu yerel ada ve ad alanı URI'sine sahip bir öznitelik zaten mevcutsa, yenisi ile değiştirilir. |
| [SetAttributeNS](../../aspose.html.dom/element/setattributens/)(string, string, string) | Yeni bir özellik ekler. Öğede aynı yerel ada ve ad alanı URI'sine sahip bir öznitelik zaten mevcutsa, öneki, nitelikliAdı'nın önek kısmı olarak değiştirilir ve değeri, value parametresi olarak değiştirilir. |
| [SetIdAttribute](../../aspose.html.dom/element/setidattribute/)(string, bool) | isId parametresi true ise, bu yöntem belirtilen özniteliği kullanıcı tarafından belirlenen bir kimlik özniteliği olarak bildirir. |
| [SetIdAttributeNode](../../aspose.html.dom/element/setidattributenode/)(Attr, bool) | isId parametresi true ise, bu yöntem belirtilen özniteliği kullanıcı tarafından belirlenen bir kimlik özniteliği olarak bildirir. |
| [SetIdAttributeNS](../../aspose.html.dom/element/setidattributens/)(string, string, bool) | isId parametresi true ise, bu yöntem belirtilen özniteliği kullanıcı tarafından belirlenen bir kimlik özniteliği olarak bildirir. |
| override [ToString](../../aspose.html.dom/node/tostring/)() | a döndürürString bu örneği temsil eder. |

### Ayrıca bakınız

* class [SVGGraphicsElement](../svggraphicselement/)
* interface [ISVGURIReference](../isvgurireference/)
* ad alanı [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg/)
* toplantı [Aspose.HTML](../../)


