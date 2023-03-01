---
title: Class SVGDocument
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Svg.SVGDocument sınıf. birSVGBelgesiSVG hiyerarşisinin köküdür ve tüm içeriği tutar. Hiyerarşiye erişim sağlamanın yanı sıra belgeden belirli bilgi kümelerine erişmek için bazı kolaylık sağlayan yöntemler de sağlar. öğesi bir XHTML belgesi XHTML içinde satır içi gömülüyse bir SVGDocument nesnesi mevcut olmaz bunun yerine belge nesnesi hiyerarşisindeki kök nesne HTMLDocument nesnesi gibi farklı türde bir Document nesnesi olacaktır. Ancak XML belge hiyerarşisinin kök öğesi bir svg öğesi olduğunda bir SVGDocument nesnesi gerçekten var olacaktır.  örneğin bağımsız bir SVG dosyasını görüntülerken olduğu gibi yani MIME türü image/svgxml olan bir dosya. Bu durumda SVGDocument nesnesi belge nesne modeli hiyerarşisinin kök nesnesi olacaktır.
type: docs
weight: 2010
url: /tr/net/aspose.html.dom.svg/svgdocument/
---
## SVGDocument class

bir`SVGBelgesi`SVG hiyerarşisinin köküdür ve tüm içeriği tutar. Hiyerarşiye erişim sağlamanın yanı sıra, belgeden belirli bilgi kümelerine erişmek için bazı kolaylık sağlayan yöntemler de sağlar. öğesi bir XHTML belgesi [XHTML] içinde satır içi gömülüyse, bir SVGDocument nesnesi mevcut olmaz; bunun yerine, belge nesnesi hiyerarşisindeki kök nesne, HTMLDocument nesnesi gibi farklı türde bir Document nesnesi olacaktır. Ancak, XML belge hiyerarşisinin kök öğesi bir 'svg' öğesi olduğunda bir SVGDocument nesnesi gerçekten var olacaktır. , örneğin bağımsız bir SVG dosyasını görüntülerken olduğu gibi (yani, MIME türü "image/svg+xml" olan bir dosya). Bu durumda, SVGDocument nesnesi, belge nesne modeli hiyerarşisinin kök nesnesi olacaktır.

```csharp
public class SVGDocument : Document, IDocumentCSS
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [SVGDocument](svgdocument/#constructor)() | Yeni bir örneğini başlatır.`SVGDocument` sınıf. |
| [SVGDocument](svgdocument/#constructor_1)(Configuration) | Yeni bir örneğini başlatır.`SVGDocument` sınıf. |
| [SVGDocument](svgdocument/#constructor_2)(RequestMessage) | Yeni bir örneğini başlatır.`SVGDocument` sınıf. Yapıcı senkronize çalışır, tüm harici kaynakların (resimler, komut dosyaları vb.) yüklenmesini bekler. Belgeyi asenkron olarak yüklemek için yöntemi kullanın[`Navigate`](../../aspose.html.dom/document/navigate/) veya aşırı yüklemeleri. Veya uygun bayrakları ayarlayarak bazı harici kaynakların yüklenmesini devre dışı bırakabilirsiniz.[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_10)(string) | Yeni bir örneğini başlatır.`SVGDocument` sınıf. Yapıcı senkronize çalışır, tüm harici kaynakların (resimler, komut dosyaları vb.) yüklenmesini bekler. Belgeyi asenkron olarak yüklemek için yöntemi kullanın[`Navigate`](../../aspose.html.dom/document/navigate/) veya aşırı yüklemeleri. Veya uygun bayrakları ayarlayarak bazı harici kaynakların yüklenmesini devre dışı bırakabilirsiniz.[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_4)(Url) | Yeni bir örneğini başlatır.`SVGDocument` sınıf. Yapıcı senkronize çalışır, tüm harici kaynakların (resimler, komut dosyaları vb.) yüklenmesini bekler. Belgeyi asenkron olarak yüklemek için yöntemi kullanın[`Navigate`](../../aspose.html.dom/document/navigate/) veya aşırı yüklemeleri. Veya uygun bayrakları ayarlayarak bazı harici kaynakların yüklenmesini devre dışı bırakabilirsiniz.[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_3)(RequestMessage, Configuration) | Yeni bir örneğini başlatır.`SVGDocument` sınıf. Yapıcı senkronize çalışır, tüm harici kaynakların (resimler, komut dosyaları vb.) yüklenmesini bekler. Belgeyi asenkron olarak yüklemek için yöntemi kullanın[`Navigate`](../../aspose.html.dom/document/navigate/) veya aşırı yüklemeleri. Veya uygun bayrakları ayarlayarak bazı harici kaynakların yüklenmesini devre dışı bırakabilirsiniz.[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_8)(Stream, string) | Yeni bir örneğini başlatır.`SVGDocument` sınıf. Yapıcı senkronize çalışır, tüm harici kaynakların (resimler, komut dosyaları vb.) yüklenmesini bekler. Belgeyi asenkron olarak yüklemek için yöntemi kullanın[`Navigate`](../../aspose.html.dom/document/navigate/) veya aşırı yüklemeleri. Veya uygun bayrakları ayarlayarak bazı harici kaynakların yüklenmesini devre dışı bırakabilirsiniz.[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Belge yükleme, akıştaki geçerli konumdan başlar. |
| [SVGDocument](svgdocument/#constructor_6)(Stream, Url) | Yeni bir örneğini başlatır.`SVGDocument` sınıf. Yapıcı senkronize çalışır, tüm harici kaynakların (resimler, komut dosyaları vb.) yüklenmesini bekler. Belgeyi asenkron olarak yüklemek için yöntemi kullanın[`Navigate`](../../aspose.html.dom/document/navigate/) veya aşırı yüklemeleri. Veya uygun bayrakları ayarlayarak bazı harici kaynakların yüklenmesini devre dışı bırakabilirsiniz.[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Belge yükleme, akıştaki geçerli konumdan başlar. |
| [SVGDocument](svgdocument/#constructor_11)(string, Configuration) | Yeni bir örneğini başlatır.`SVGDocument` sınıf. Yapıcı senkronize çalışır, tüm harici kaynakların (resimler, komut dosyaları vb.) yüklenmesini bekler. Belgeyi asenkron olarak yüklemek için yöntemi kullanın[`Navigate`](../../aspose.html.dom/document/navigate/) veya aşırı yüklemeleri. Veya uygun bayrakları ayarlayarak bazı harici kaynakların yüklenmesini devre dışı bırakabilirsiniz.[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_14)(string, string) | Yeni bir örneğini başlatır.`SVGDocument` sınıf. Yapıcı senkronize çalışır, tüm harici kaynakların (resimler, komut dosyaları vb.) yüklenmesini bekler. Belgeyi asenkron olarak yüklemek için yöntemi kullanın[`Navigate`](../../aspose.html.dom/document/navigate/) veya aşırı yüklemeleri. Veya uygun bayrakları ayarlayarak bazı harici kaynakların yüklenmesini devre dışı bırakabilirsiniz.[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_12)(string, Url) | Yeni bir örneğini başlatır.`SVGDocument` sınıf. Yapıcı senkronize çalışır, tüm harici kaynakların (resimler, komut dosyaları vb.) yüklenmesini bekler. Belgeyi asenkron olarak yüklemek için yöntemi kullanın[`Navigate`](../../aspose.html.dom/document/navigate/) veya aşırı yüklemeleri. Veya uygun bayrakları ayarlayarak bazı harici kaynakların yüklenmesini devre dışı bırakabilirsiniz.[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_5)(Url, Configuration) | Yeni bir örneğini başlatır.`SVGDocument` sınıf. Yapıcı senkronize çalışır, tüm harici kaynakların (resimler, komut dosyaları vb.) yüklenmesini bekler. Belgeyi asenkron olarak yüklemek için yöntemi kullanın[`Navigate`](../../aspose.html.dom/document/navigate/) veya aşırı yüklemeleri. Veya uygun bayrakları ayarlayarak bazı harici kaynakların yüklenmesini devre dışı bırakabilirsiniz.[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_9)(Stream, string, Configuration) | Yeni bir örneğini başlatır.`SVGDocument` sınıf. Yapıcı senkronize çalışır, tüm harici kaynakların (resimler, komut dosyaları vb.) yüklenmesini bekler. Belgeyi asenkron olarak yüklemek için yöntemi kullanın[`Navigate`](../../aspose.html.dom/document/navigate/) veya aşırı yüklemeleri. Veya uygun bayrakları ayarlayarak bazı harici kaynakların yüklenmesini devre dışı bırakabilirsiniz.[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Belge yükleme, akıştaki geçerli konumdan başlar. |
| [SVGDocument](svgdocument/#constructor_7)(Stream, Url, Configuration) | Yeni bir örneğini başlatır.`SVGDocument` sınıf. Yapıcı senkronize çalışır, tüm harici kaynakların (resimler, komut dosyaları vb.) yüklenmesini bekler. Belgeyi asenkron olarak yüklemek için yöntemi kullanın[`Navigate`](../../aspose.html.dom/document/navigate/) veya aşırı yüklemeleri. Veya uygun bayrakları ayarlayarak bazı harici kaynakların yüklenmesini devre dışı bırakabilirsiniz.[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Belge yükleme, akıştaki geçerli konumdan başlar. |
| [SVGDocument](svgdocument/#constructor_15)(string, string, Configuration) | Yeni bir örneğini başlatır.`SVGDocument` sınıf. Yapıcı senkronize çalışır, tüm harici kaynakların (resimler, komut dosyaları vb.) yüklenmesini bekler. Belgeyi asenkron olarak yüklemek için yöntemi kullanın[`Navigate`](../../aspose.html.dom/document/navigate/) veya aşırı yüklemeleri. Veya uygun bayrakları ayarlayarak bazı harici kaynakların yüklenmesini devre dışı bırakabilirsiniz.[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_13)(string, Url, Configuration) | Yeni bir örneğini başlatır.`SVGDocument` sınıf. Yapıcı senkronize çalışır, tüm harici kaynakların (resimler, komut dosyaları vb.) yüklenmesini bekler. Belgeyi asenkron olarak yüklemek için yöntemi kullanın[`Navigate`](../../aspose.html.dom/document/navigate/) veya aşırı yüklemeleri. Veya uygun bayrakları ayarlayarak bazı harici kaynakların yüklenmesini devre dışı bırakabilirsiniz.[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes/) { get; } | Bu düğümün özniteliklerini (bir Öğe ise) içeren bir NamedNodeMap veya aksi halde null. |
| override [BaseURI](../../aspose.html.dom/document/baseuri/) { get; } | Bu düğümün mutlak temel URI'si veya uygulama mutlak bir URI elde edemediyse null. |
| [CharacterSet](../../aspose.html.dom/document/characterset/) { get; } | Belgenin kodlamasını alır. |
| [Charset](../../aspose.html.dom/document/charset/) { get; } | Belgenin kodlamasını alır. |
| [ChildElementCount](../../aspose.html.dom/document/childelementcount/) { get; } | Bu öğenin çocukları olan öğe düğümlerinin geçerli sayısını döndürür. 0, eğer bu elemanın nodeType 1. olan alt düğümleri yoksa |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | Bu düğümün tüm alt öğelerini içeren bir NodeList. Alt öğe yoksa bu, düğüm içermeyen bir NodeList'tir.. |
| [Children](../../aspose.html.dom/document/children/) { get; } | Alt öğeleri döndürür. |
| [ContentType](../../aspose.html.dom/document/contenttype/) { get; } | Belge içerik türünü alır. |
| [Context](../../aspose.html.dom/document/context/) { get; } | Geçerli tarama bağlamını alır. |
| [DefaultView](../../aspose.html.dom/document/defaultview/) { get; } | Belge arayüzünün defaultView IDL özniteliği, alınırken, bu Belgenin tarama içeriğinin WindowProxy nesnesini, , eğer bu Belgenin ilişkili bir göz atma bağlamı varsa, yoksa null değerini döndürmelidir. |
| [Doctype](../../aspose.html.dom/document/doctype/) { get; } | Bu belgeyle ilişkili Belge Türü Bildirimi. |
| [DocumentElement](../../aspose.html.dom/document/documentelement/) { get; } | Bu, belgenin belge öğesi olan alt düğüme doğrudan erişim sağlayan bir uygunluk niteliğidir. |
| [DocumentURI](../../aspose.html.dom/document/documenturi/) { get; } | Belgenin konumu veya tanımsızsa boş veya Belge DOMImplementation.createDocument. kullanılarak oluşturulmuşsa |
| [Domain](../../aspose.html.dom.svg/svgdocument/domain/) { get; } | Belgeyi sunan sunucunun etki alanı adı veya sunucu bir etki alanı adıyla tanımlanamıyorsa boş dize. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | Bu düğümün ilk çocuğu. Böyle bir düğüm yoksa bu, null. değerini döndürür. |
| [FirstElementChild](../../aspose.html.dom/document/firstelementchild/) { get; } | Bu öğenin ilk alt öğe düğümünü döndürür. bu öğenin alt öğesi yoksa null. |
| [Implementation](../../aspose.html.dom/document/implementation/) { get; } | Bu belgeyi işleyen DOMImplementation nesnesi. |
| [InputEncoding](../../aspose.html.dom/document/inputencoding/) { get; } | Belgenin kodlamasını alır. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | Bu düğümün son çocuğu. Böyle bir düğüm yoksa bu, null. değerini döndürür. |
| [LastElementChild](../../aspose.html.dom/document/lastelementchild/) { get; } | Bu öğenin son alt öğe düğümünü döndürür. bu öğenin alt öğesi yoksa null. |
| virtual [LocalName](../../aspose.html.dom/node/localname/) { get; } | Bu düğümün nitelikli adının yerel kısmını döndürür. ELEMENT_NODE ve ATTRIBUTE_NODE dışında herhangi bir türdeki düğümler ve Document.createElement() gibi DOM Düzey 1 yöntemiyle oluşturulan düğümler için bu her zaman boştur. |
| [Location](../../aspose.html.dom/document/location/) { get; } | Belgenin konumu. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri/) { get; } | Bu düğümün ad alanı URI'si veya belirtilmemişse boş. |
| [NextElementSibling](../../aspose.html.dom/document/nextelementsibling/) { get; } | Bu öğenin bir sonraki kardeş öğe düğümünü döndürür. Bu öğenin, belge ağacında bundan sonra gelen hiçbir öğe kardeş düğümü yoksa boş değer. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | Bu düğümü hemen takip eden düğüm. Böyle bir düğüm yoksa bu, null. değerini döndürür. |
| override [NodeName](../../aspose.html.dom/document/nodename/) { get; } | Türüne bağlı olarak bu düğümün adı. |
| override [NodeType](../../aspose.html.dom/document/nodetype/) { get; } | Altta yatan nesnenin türünü temsil eden bir kod. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | Türüne bağlı olarak bu düğümün değeri. |
| [Origin](../../aspose.html.dom/document/origin/) { get; } | Belge kaynağını alır. |
| override [OwnerDocument](../../aspose.html.dom/document/ownerdocument/) { get; } | Sahip belgesini alır. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Ebeveyni alır[`Element`](../../aspose.html.dom/element/) bu düğümün. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | Bu düğümün ebeveyni. Attr, Document, DocumentFragment, Entity ve Notation dışındaki tüm düğümlerin bir üst öğesi olabilir. Ancak, bir düğüm yeni oluşturulmuşsa ve henüz ağaca eklenmemişse veya ağaçtan kaldırılmışsa, bu null. olur. |
| virtual [Prefix](../../aspose.html.dom/node/prefix/) { get; set; } | Bu düğümün ad alanı öneki veya belirtilmemişse boş. Boş olarak tanımlandığında, ayarının etkisi yoktur |
| [PreviousElementSibling](../../aspose.html.dom/document/previouselementsibling/) { get; } | Bu öğenin önceki kardeş öğe düğümünü döndürür. Bu öğenin, belge ağacında bundan önce gelen hiçbir öğe kardeş düğümü yoksa boş değer. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | Bu düğümden hemen önceki düğüm. Böyle bir düğüm yoksa bu, null. değerini döndürür. |
| [ReadyState](../../aspose.html.dom/document/readystate/) { get; } | Belgenin hazır olma durumunu döndürür. Belge yüklenirken "yükleme", ayrıştırmayı bitirdiğinde ancak alt kaynakları yüklemeye devam ettiğinde "etkileşimli" ve yüklendiğinde "tamamlandı". |
| [Referrer](../../aspose.html.dom.svg/svgdocument/referrer/) { get; } | Bu sayfaya bağlanan sayfanın URI'sini döndürür. Kullanıcı sayfaya doğrudan gittiyse (bir bağlantı aracılığıyla değil, örneğin bir yer işareti aracılığıyla) değer boş bir dizedir. |
| [RootElement](../../aspose.html.dom.svg/svgdocument/rootelement/) { get; } | Belge hiyerarşisindeki 'svg' kökü. |
| [StrictErrorChecking](../../aspose.html.dom/document/stricterrorchecking/) { get; set; } | Hata denetiminin zorunlu olup olmadığını belirten bir öznitelik. false değerine ayarlandığında uygulama, normalde DOM işlemlerinde tanımlanan her olası hata durumunu test etmemek ve Document.normalizeDocument() kullanırken DOM işlemlerinde herhangi bir DOMException oluşturmamak veya hataları raporlamamak için serbesttir. Hata durumunda, davranış tanımsızdır. Bu öznitelik varsayılan olarak doğrudur. |
| [StyleSheets](../../aspose.html.dom/document/stylesheets/) { get; } | Bir belgeye açıkça bağlantılı veya belgeye katıştırılmış tüm stil sayfalarını içeren bir liste. HTML belgeleri için bu, HTML LINK öğesi aracılığıyla eklenen harici stil sayfalarını ve satır içi STYLE öğelerini içerir. |
| virtual [TextContent](../../aspose.html.dom/node/textcontent/) { get; set; } | Bu öznitelik, bu düğümün ve onun soyundan gelenlerin metin içeriğini döndürür. Null olarak tanımlandığında, ayarının hiçbir etkisi yoktur. Ayarlama sırasında, bu düğümün sahip olabileceği tüm olası alt öğeler kaldırılır ve yeni dize boş veya boş değilse, bu özniteliğin ayarlandığı dizeyi içeren tek bir Metin düğümü ile değiştirilir. |
| [Title](../../aspose.html.dom.svg/svgdocument/title/) { get; } | 'svg' kök öğesinin (örn.,İşte başlık... ) |
| [URL](../../aspose.html.dom.svg/svgdocument/url/) { get; } | Belgenin tam URI'si. |
| [XmlStandalone](../../aspose.html.dom/document/xmlstandalone/) { get; set; } | XML bildiriminin bir parçası olarak bu belgenin bağımsız olup olmadığını belirten bir öznitelik. Bu, belirtilmediğinde yanlıştır. |
| [XmlVersion](../../aspose.html.dom/document/xmlversion/) { get; set; } | XML bildiriminin bir parçası olarak bu belgenin sürüm numarasını belirten bir öznitelik. Beyanname yoksa ve bu belge "XML" özelliğini destekliyorsa değer "1.0" olur. Bu belge "XML" özelliğini desteklemiyorsa, değer her zaman boştur. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine izin verir. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine izin verir. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | Bu yöntem, olay dinleyicilerinin olay hedefine kaydedilmesine izin verir. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | newChild düğümünü bu düğümün çocukları listesinin sonuna ekler. newChild zaten ağaçtaysa, önce kaldırılır. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | Bu düğümün bir kopyasını döndürür, yani düğümler için genel bir kopya oluşturucu görevi görür. Yinelenen düğümün üst öğesi (parentNode boştur) ve kullanıcı verisi yoktur. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | Bu düğümün bir kopyasını döndürür, yani düğümler için genel bir kopya oluşturucu görevi görür. Yinelenen düğümün üst öğesi (parentNode boştur) ve kullanıcı verisi yoktur. |
| [CreateAttribute](../../aspose.html.dom/document/createattribute/)(string) | Belirtilen isimde bir Öznitelik oluşturur. |
| [CreateAttributeNS](../../aspose.html.dom/document/createattributens/)(string, string) | Verilen nitelikli ad ve ad alanı URI'sinin bir özniteliğini oluşturur. |
| [CreateCDATASection](../../aspose.html.dom/document/createcdatasection/)(string) | Değeri belirtilen dize olan bir CDATASection düğümü oluşturur. |
| [CreateComment](../../aspose.html.dom/document/createcomment/)(string) | Belirtilen dize verilen bir Yorum düğümü oluşturur. |
| [CreateDocumentFragment](../../aspose.html.dom/document/createdocumentfragment/)() | Boş bir DocumentFragment nesnesi oluşturur. |
| [CreateDocumentType](../../aspose.html.dom/document/createdocumenttype/)(string, string, string, string) | Bir DocumentType düğümü oluşturur. |
| [CreateElement](../../aspose.html.dom/document/createelement/)(string) | Belirtilen türde bir öğe oluşturur. Döndürülen örneğin Element arabirimini uyguladığını unutmayın, böylece öznitelikler doğrudan döndürülen nesne üzerinde belirtilebilir. |
| [CreateElementNS](../../aspose.html.dom/document/createelementns/)(string, string) | Verilen nitelikli ad ve ad alanı URI'sinin bir öğesini oluşturur. |
| [CreateEntityReference](../../aspose.html.dom/document/createentityreference/)(string) | Bir EntityReference nesnesi oluşturur. Ek olarak, başvurulan varlık biliniyorsa, EntityReference düğümünün alt listesi, karşılık gelen Varlık düğümününkiyle aynı yapılır. |
| [CreateEvent](../../aspose.html.dom/document/createevent/)(string) | oluşturur[`Event`](../../aspose.html.dom.events/event/) uygulama tarafından desteklenen bir tür. |
| [CreateExpression](../../aspose.html.dom/document/createexpression/)(string, IXPathNSResolver) | Çözülmüş ad alanlarıyla ayrıştırılmış bir XPath ifadesi oluşturur. Bu, ifade dizesini daha verimli bir dahili biçimde derlemeyi ve ifade içinde oluşan tüm ad alanı öneklerini önceden çözmeyi mümkün kıldığından, bir ifade bir uygulamada yeniden kullanılacağında yararlıdır. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node) | Belirtilen node. 'de köklenen alt ağaç üzerinde yeni bir NodeIterator oluşturun. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node, long) | Belirtilen node. 'de köklenen alt ağaç üzerinde yeni bir NodeIterator oluşturun. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node, long, INodeFilter) | Belirtilen node. 'de köklenen alt ağaç üzerinde yeni bir NodeIterator oluşturun. |
| [CreateNSResolver](../../aspose.html.dom/document/creatensresolver/)(Node) | Herhangi bir DOM düğümünü ad alanlarını çözecek şekilde uyarlar, böylece bir XPath ifadesi belgede göründüğü düğümün bağlamına göre kolayca değerlendirilebilir. Bu bağdaştırıcı, DOM Düzey 3 yöntemi gibi çalışır `aramaNamespaceURI` namespaceURI öğesini belirli bir önekten çözümlemede düğümlerde, düğümün hiyerarşisinde lookupNamespaceURI çağrıldığında mevcut olan geçerli bilgileri kullanarak, aynı zamanda örtük xml önekini doğru bir şekilde çözerek. |
| [CreateProcessingInstruction](../../aspose.html.dom/document/createprocessinginstruction/)(string, string) | Belirtilen ad ve veri dizileri verilen bir ProcessingInstruction düğümü oluşturur. |
| [CreateTextNode](../../aspose.html.dom/document/createtextnode/)(string) | Belirtilen dize verilen bir Metin düğümü oluşturur. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node) | Belirtilen düğümde köklenen alt ağaç üzerinde yeni bir TreeWalker oluşturun. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node, long) | Belirtilen düğümde köklenen alt ağaç üzerinde yeni bir TreeWalker oluşturun. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node, long, INodeFilter) | Belirtilen düğümde köklenen alt ağaç üzerinde yeni bir TreeWalker oluşturun. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Bu yöntem, olayların uygulama olay modeline gönderilmesine izin verir. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Yönetilmeyen kaynakları serbest bırakma, serbest bırakma veya sıfırlama ile ilişkili uygulama tanımlı görevleri gerçekleştirir. |
| [Evaluate](../../aspose.html.dom/document/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | Bir XPath ifade dizesini değerlendirir ve mümkünse belirtilen türden bir sonuç döndürür. |
| [GetElementById](../../aspose.html.dom/document/getelementbyid/)(string) | Verilen değere sahip bir ID özniteliğine sahip Öğeyi döndürür. Böyle bir öğe yoksa, bu null değerini döndürür. Birden fazla öğenin bu değere sahip bir kimlik özelliği varsa, döndürülen şey undefined. 'dir. |
| [GetElementsByClassName](../../aspose.html.dom/document/getelementsbyclassname/)(string) | Argümanda belirtilen tüm sınıflara sahip belgedeki tüm öğeleri içeren canlı bir NodeList nesnesi döndürür. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/document/getelementsbytagname/)(string) | Belirli bir etiket adı ile belge sırasındaki ve belgede bulunan tüm Öğelerin Düğüm Listesini döndürür. |
| [GetElementsByTagNameNS](../../aspose.html.dom/document/getelementsbytagnamens/)(string, string) | Belirli bir yerel ada ve ad alanı URI'sine sahip tüm Öğelerin bir Düğüm Listesini belge sırasına göre döndürür. |
| [GetOverrideStyle](../../aspose.html.dom.svg/svgdocument/getoverridestyle/)(Element, string) | Bu yöntem, belirtilen bir öğe ve belirtilen sözde öğe için geçersiz kılma stili bildirimini almak için kullanılır. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Bu yöntem ECMAScript nesnesini almak için kullanılır.Type . |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes/)() | Bu düğümün (eğer bir öğe ise) herhangi bir özniteliği olup olmadığını döndürür |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | Bu düğümün herhangi bir alt öğesi olup olmadığını döndürür. |
| [ImportNode](../../aspose.html.dom/document/importnode/)(Node, bool) | Orijinal belgedeki kaynak düğümü değiştirmeden veya çıkarmadan başka bir belgeden bu belgeye bir düğüm aktarır; bu yöntem, kaynak düğümün yeni bir kopyasını oluşturur. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | Düğümü varolan alt düğüm alt öğesinden önce ekler. Child null ise, çocuklar listesinin sonuna düğüm ekleyin. Child bir DocumentFragment nesnesiyse, tüm alt öğeleri aynı sırayla alt öğeden önce eklenir. Çocuk zaten ağaçtaysa, önce kaldırılır. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | Bu yöntem, belirtilen namespaceURI'nin varsayılan ad alanı olup olmadığını kontrol eder. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | İki düğümün eşit olup olmadığını test eder. Bu yöntem, Node.isSameNode() ile test edilebilen aynılığı (yani iki düğümün aynı nesneye referans olup olmadığını) değil, düğümlerin eşitliğini test eder. Aynı olan tüm düğümler de eşit olacaktır, ancak tersi doğru olmayabilir. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | Bu düğümün verilenle aynı düğüm olup olmadığını döndürür. Bu yöntem, uygulama tarafından döndürülen iki Düğüm başvurusunun aynı nesneye başvuruda bulunup bulunmadığını belirlemenin bir yolunu sağlar. İki Düğüm referansı aynı nesneye referans olduğunda, bir proxy üzerinden olsa bile, referanslar tamamen birbirinin yerine kullanılabilir, böylece tüm öznitelikler aynı değerlere sahip olur ve her iki referansta da aynı DOM yöntemini çağırmak her zaman tam olarak aynı etkiye sahip olur. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | Bu düğümden başlayarak verilen önekle ilişkili ad alanı URI'sine bakın. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | Bu düğümden başlayarak verilen ad alanı URI'si ile ilişkili öneki arayın. Varsayılan ad alanı bildirimleri bu yöntem tarafından dikkate alınmaz. Bu yöntem tarafından kullanılan algoritma hakkında ayrıntılar için Ad Alanı Öneki Arama'ya bakın. |
| [Navigate](../../aspose.html.dom/document/navigate/)(RequestMessage) | Önceki içeriği değiştirerek belirtilen istek nesnesine göre belgeyi yükler. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string) | Belirtilen Tekdüzen Kaynak Bulucudaki (URL) belgeyi, önceki içeriği değiştirerek mevcut örneğe yükler. |
| [Navigate](../../aspose.html.dom/document/navigate/)(Url) | Belirtilen Tekdüzen Kaynak Bulucudaki (URL) belgeyi, önceki içeriği değiştirerek mevcut örneğe yükler. |
| [Navigate](../../aspose.html.dom/document/navigate/)(Stream, string) | Belgeyi belirtilen içerikten yükler ve göreli kaynakları çözmek için baseUri kullanarak önceki içeriği değiştirir. Belge yükleme, akıştaki geçerli konumdan başlar. |
| [Navigate](../../aspose.html.dom/document/navigate/)(Stream, Url) | Belgeyi belirtilen içerikten yükler ve göreli kaynakları çözmek için baseUri kullanarak önceki içeriği değiştirir. Belge yükleme, akıştaki geçerli konumdan başlar. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string, string) | Belgeyi belirtilen içerikten yükler ve baseUri kullanarak göreli kaynakları çözerek önceki içeriği değiştirir. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string, Url) | Belgeyi belirtilen içerikten yükler ve baseUri kullanarak göreli kaynakları çözerek önceki içeriği değiştirir. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Öznitelik düğümleri de dahil olmak üzere, bu Düğümün altındaki alt ağacın tüm derinliğindeki tüm Metin düğümlerini, Metni yalnızca yapının (örneğin, öğeler, yorumlar, işleme yönergeleri, CDATA bölümleri ve varlık referansları) ayırdığı "normal" bir forma sokar. düğümler, yani bitişik Metin düğümleri veya boş Metin düğümleri yoktur. Bu, bir belgenin DOM görünümünün, kaydedilmiş ve yeniden yüklenmiş haliyle aynı olmasını sağlamak için kullanılabilir ve belirli bir belge ağacı yapısına bağlı olan işlemler (XPointer [XPointer] aramaları gibi) kullanılmalı Node.ownerDocument'e eklenen DOMConfiguration nesnesinin "normalize-characters" parametresi doğruysa, bu yöntem Metin düğümlerinin karakterlerini de tam olarak normalleştirir. |
| [QuerySelector](../../aspose.html.dom/document/queryselector/)(string) | Belgedeki seçici ile eşleşen ilk Elemanı döndürür |
| [QuerySelectorAll](../../aspose.html.dom/document/queryselectorall/)(string) | Belgedeki tüm Öğelerin seçici ile eşleşen bir Düğüm Listesini döndürür |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | oldChild tarafından belirtilen alt düğümü alt öğe listesinden kaldırır ve onu döndürür. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer bir[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) bir yerden kaldırılır[`EventTarget`](../../aspose.html.dom/eventtarget/) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler, kaldırıldıktan sonra asla çağrılamaz. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer bir[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) bir yerden kaldırılır[`EventTarget`](../../aspose.html.dom/eventtarget/) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler, kaldırıldıktan sonra asla çağrılamaz. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | Bu yöntem, olay dinleyicilerinin olay hedefinden kaldırılmasına izin verir. Eğer bir[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) bir yerden kaldırılır[`EventTarget`](../../aspose.html.dom/eventtarget/) bir olayı işlerken, mevcut eylemler tarafından tetiklenmeyecektir. Olay Dinleyiciler, kaldırıldıktan sonra asla çağrılamaz. |
| override [RenderTo](../../aspose.html.dom.svg/svgdocument/renderto/)(IDevice) | Bu yöntem, geçerli belgenin içeriğini belirtilen aygıta yazdırmak için kullanılır. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | Alt düğüm listesindeki oldChild alt düğümünü newChild ile değiştirir ve oldChild düğümünü döndürür. newChild bir DocumentFragment nesnesiyse, eskiChild aynı sırayla eklenen tüm DocumentFragment alt öğeleriyle değiştirilir. newChild zaten ağaçtaysa, önce kaldırılır. |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save)(IOutputStorage) | Belge içeriğini ve kaynakları çıktı deposuna kaydeder. |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_6)(string) | Belgeyi tarafından belirtilen yerel dosyaya kaydeder.`yol` Bu belgede kullanılan tüm kaynaklar, adı şu şekilde yapılandırılacak olan bitişik klasöre dosyasına kaydedilecektir: output_file_name + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_3)(Url) | Belgeyi tarafından belirtilen yerel dosyaya kaydeder.`url` Bu belgede kullanılan tüm kaynaklar, adı şu şekilde yapılandırılacak olan bitişik klasöre dosyasına kaydedilecektir: output_file_name + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_1)(IOutputStorage, SVGSaveFormat) | Belge içeriğini ve kaynakları çıktı deposuna kaydeder. |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_2)(IOutputStorage, SVGSaveOptions) | Belge içeriğini ve kaynakları çıktı deposuna kaydeder. |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_7)(string, SVGSaveFormat) | Belgeyi tarafından belirtilen yerel dosyaya kaydeder.`yol` Bu belgede kullanılan tüm kaynaklar, adı şu şekilde yapılandırılacak olan bitişik klasöre dosyasına kaydedilecektir: output_file_name + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_8)(string, SVGSaveOptions) | Belgeyi tarafından belirtilen yerel dosyaya kaydeder.`yol` Bu belgede kullanılan tüm kaynaklar, adı şu şekilde yapılandırılacak olan bitişik klasöre dosyasına kaydedilecektir: output_file_name + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_4)(Url, SVGSaveFormat) | Belgeyi tarafından belirtilen yerel dosyaya kaydeder.`url` Bu belgede kullanılan tüm kaynaklar, adı şu şekilde yapılandırılacak olan bitişik klasöre dosyasına kaydedilecektir: output_file_name + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_5)(Url, SVGSaveOptions) | Belgeyi tarafından belirtilen yerel dosyaya kaydeder.`url` Bu belgede kullanılan tüm kaynaklar, adı şu şekilde yapılandırılacak olan bitişik klasöre dosyasına kaydedilecektir: output_file_name + "_files". |
| override [ToString](../../aspose.html.dom/node/tostring/)() | a döndürürString bu örneği temsil eder. |
| [Write](../../aspose.html.dom/document/write/)(params string[]) | open() tarafından açılan bir belge akışına bir metin dizisi yazın. İşlevin, mutlaka bir DTD tarafından yönlendirilmesi gerekmeyen bir document üreteceğini ve bu nedenle, belge bağlamında geçersiz bir sonuç be üretebileceğini unutmayın. |
| [WriteLn](../../aspose.html.dom/document/writeln/)(params string[]) | open() tarafından açılan bir document akışına bir metin dizesi ve ardından yeni satır karakteri yazın. işlevinin bir DTD tarafından yönlendirilmesi gerekmeyen bir belge üreteceğini ve bu nedenle belgesinin the document bağlamında geçersiz bir sonuç üretebileceğini unutmayın. |

## Olaylar

| İsim | Tanım |
| --- | --- |
| event [OnAbort](../../aspose.html.dom/document/onabort/) | OnAbort olayı için olay işleyicisini alır veya ayarlar. |
| event [OnBlur](../../aspose.html.dom/document/onblur/) | OnBlur olayı için olay işleyicisini alır veya ayarlar. |
| event [OnCancel](../../aspose.html.dom/document/oncancel/) | OnCancel olayı için olay işleyicisini alır veya ayarlar. |
| event [OnCanplay](../../aspose.html.dom/document/oncanplay/) | OnCanplay olayı için olay işleyicisini alır veya ayarlar. |
| event [OnCanPlayThrough](../../aspose.html.dom/document/oncanplaythrough/) | OnCanPlayThrough olayı için olay işleyicisini alır veya ayarlar. |
| event [OnChange](../../aspose.html.dom/document/onchange/) | OnChange olayı için olay işleyicisini alır veya ayarlar. |
| event [OnClick](../../aspose.html.dom/document/onclick/) | OnClick olayı için olay işleyicisini alır veya ayarlar. |
| event [OnCueChange](../../aspose.html.dom/document/oncuechange/) | OnCueChange olayı için olay işleyicisini alır veya ayarlar. |
| event [OnDblClick](../../aspose.html.dom/document/ondblclick/) | OnDblClick olayı için olay işleyicisini alır veya ayarlar. |
| event [OnDurationChange](../../aspose.html.dom/document/ondurationchange/) | OnDurationChange olayı için olay işleyicisini alır veya ayarlar. |
| event [OnEmptied](../../aspose.html.dom/document/onemptied/) | OnEmptied olayı için olay işleyicisini alır veya ayarlar. |
| event [OnEnded](../../aspose.html.dom/document/onended/) | OnEnded olayı için olay işleyicisini alır veya ayarlar. |
| event [OnError](../../aspose.html.dom/document/onerror/) | OnError olayı için olay işleyicisini alır veya ayarlar. |
| event [OnFocus](../../aspose.html.dom/document/onfocus/) | OnFocus olayı için olay işleyicisini alır veya ayarlar. |
| event [OnInput](../../aspose.html.dom/document/oninput/) | OnInput olayı için olay işleyicisini alır veya ayarlar. |
| event [OnInvalid](../../aspose.html.dom/document/oninvalid/) | OnInvalid olayı için olay işleyicisini alır veya ayarlar. |
| event [OnKeyDown](../../aspose.html.dom/document/onkeydown/) | OnKeyDown olayı için olay işleyicisini alır veya ayarlar. |
| event [OnKeyPress](../../aspose.html.dom/document/onkeypress/) | OnKeyPress olayı için olay işleyicisini alır veya ayarlar. |
| event [OnKeyUp](../../aspose.html.dom/document/onkeyup/) | OnKeyUp olayı için olay işleyicisini alır veya ayarlar. |
| event [OnLoad](../../aspose.html.dom/document/onload/) | OnLoad olayı için olay işleyicisini alır veya ayarlar. |
| event [OnLoadedData](../../aspose.html.dom/document/onloadeddata/) | OnLoadedData olayı için olay işleyicisini alır veya ayarlar. |
| event [OnLoadedMetadata](../../aspose.html.dom/document/onloadedmetadata/) | OnLoadedMetadata olayı için olay işleyicisini alır veya ayarlar. |
| event [OnLoadStart](../../aspose.html.dom/document/onloadstart/) | OnLoadStart olayı için olay işleyicisini alır veya ayarlar. |
| event [OnMouseDown](../../aspose.html.dom/document/onmousedown/) | OnMouseDown olayı için olay işleyicisini alır veya ayarlar. |
| event [OnMouseEnter](../../aspose.html.dom/document/onmouseenter/) | OnMouseEnter olayı için olay işleyicisini alır veya ayarlar. |
| event [OnMouseLeave](../../aspose.html.dom/document/onmouseleave/) | OnMouseLeave olayı için olay işleyicisini alır veya ayarlar. |
| event [OnMouseMove](../../aspose.html.dom/document/onmousemove/) | OnMouseMove olayı için olay işleyicisini alır veya ayarlar. |
| event [OnMouseOut](../../aspose.html.dom/document/onmouseout/) | OnMouseOut olayı için olay işleyicisini alır veya ayarlar. |
| event [OnMouseOver](../../aspose.html.dom/document/onmouseover/) | OnMouseOver olayı için olay işleyicisini alır veya ayarlar. |
| event [OnMouseUp](../../aspose.html.dom/document/onmouseup/) | OnMouseUp olayı için olay işleyicisini alır veya ayarlar. |
| event [OnMouseWheel](../../aspose.html.dom/document/onmousewheel/) | OnMouseWheel olayı için olay işleyicisini alır veya ayarlar. |
| event [OnPause](../../aspose.html.dom/document/onpause/) | OnPause olayı için olay işleyicisini alır veya ayarlar. |
| event [OnPlay](../../aspose.html.dom/document/onplay/) | OnPlay olayı için olay işleyicisini alır veya ayarlar. |
| event [OnPlaying](../../aspose.html.dom/document/onplaying/) | OnPlaying olayı için olay işleyicisini alır veya ayarlar. |
| event [OnProgress](../../aspose.html.dom/document/onprogress/) | OnProgress olayı için olay işleyicisini alır veya ayarlar. |
| event [OnRateChange](../../aspose.html.dom/document/onratechange/) | OnRateChange olayı için olay işleyicisini alır veya ayarlar. |
| event [OnReadyStateChange](../../aspose.html.dom/document/onreadystatechange/) | OnReadyStateChange olayı için olay işleyicisini alır veya ayarlar. |
| event [OnReset](../../aspose.html.dom/document/onreset/) | OnReset olayı için olay işleyicisini alır veya ayarlar. |
| event [OnResize](../../aspose.html.dom/document/onresize/) | OnResize olayı için olay işleyicisini alır veya ayarlar. |
| event [OnScroll](../../aspose.html.dom/document/onscroll/) | OnScroll olayı için olay işleyicisini alır veya ayarlar. |
| event [OnSeeked](../../aspose.html.dom/document/onseeked/) | OnSeeked olayı için olay işleyicisini alır veya ayarlar. |
| event [OnSeeking](../../aspose.html.dom/document/onseeking/) | OnSeeking olayı için olay işleyicisini alır veya ayarlar. |
| event [OnSelect](../../aspose.html.dom/document/onselect/) | OnSelect olayı için olay işleyicisini alır veya ayarlar. |
| event [OnShow](../../aspose.html.dom/document/onshow/) | OnShow olayı için olay işleyicisini alır veya ayarlar. |
| event [OnStalled](../../aspose.html.dom/document/onstalled/) | OnStalled olayı için olay işleyicisini alır veya ayarlar. |
| event [OnSubmit](../../aspose.html.dom/document/onsubmit/) | OnSubmit olayı için olay işleyicisini alır veya ayarlar. |
| event [OnSuspend](../../aspose.html.dom/document/onsuspend/) | OnSuspend olayı için olay işleyicisini alır veya ayarlar. |
| event [OnTimeUpdate](../../aspose.html.dom/document/ontimeupdate/) | OnTimeUpdate olayı için olay işleyicisini alır veya ayarlar. |
| event [OnToggle](../../aspose.html.dom/document/ontoggle/) | OnToggle olayı için olay işleyicisini alır veya ayarlar. |
| event [OnVolumeChange](../../aspose.html.dom/document/onvolumechange/) | OnVolumeChange olayı için olay işleyicisini alır veya ayarlar. |
| event [OnWaiting](../../aspose.html.dom/document/onwaiting/) | OnWaiting olayı için olay işleyicisini alır veya ayarlar. |

### Ayrıca bakınız

* class [Document](../../aspose.html.dom/document/)
* interface [IDocumentEvent](../../aspose.html.dom.events/idocumentevent/)
* interface [IDocumentCSS](../../aspose.html.dom.css/idocumentcss/)
* ad alanı [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg/)
* toplantı [Aspose.HTML](../../)


