---
title: Aspose.Html.Dom
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom Belge Nesne Modeli ad alanı nin herhangi bir HTML XML veya SVG belgesini temsil ettiği ve bunlarla etkileşime girdiği APIyi sağlar. DOM tarayıcıya yüklenen bir belge modelidir ve  belgeyi bir düğüm ağacı olarak temsil eder burada her düğüm  belgenin bir bölümünü örn. bir öğe metin temsil eder. dize veya yorum.
type: docs
weight: 40
url: /tr/net/aspose.html.dom/
---
**Aspose.Html.Dom (Belge Nesne Modeli)** ad alanı, 'nin herhangi bir HTML, XML veya SVG belgesini temsil ettiği ve bunlarla etkileşime girdiği API'yi sağlar. DOM, tarayıcıya yüklenen bir belge modelidir ve , belgeyi bir düğüm ağacı olarak temsil eder; burada her düğüm , belgenin bir bölümünü (örn. bir öğe, metin) temsil eder. dize veya yorum).

## sınıflar

| Sınıf | Tanım |
| --- | --- |
| [Attr](./attr/) | Attr arabirimi, bir Element nesnesindeki bir özniteliği temsil eder. Tipik olarak, öznitelik için izin verilen değerler, belgeyle ilişkili bir şemada tanımlanır. |
| [CDATASection](./cdatasection/) | CDATA bölümleri, normalde biçimlendirme olarak kabul edilecek karakterleri içeren metin bloklarından kaçmak için kullanılır. |
| [CharacterData](./characterdata/) | CharacterData, DOM. içindeki karakter verilerine erişmek için Düğümü bir dizi öznitelik ve yöntemle genişletir |
| [Comment](./comment/) | CharacterData'dan devralır ve bir yorumun içeriğini temsil eder, yani ' ile başlayan arasındaki tüm karakterler . |
| [Document](./document/) | Belge, tüm HTML, XML veya SVG belgesini temsil eder. Kavramsal olarak, belge ağacının köküdür ve belgenin verilerine birincil erişimi sağlar. |
| [DocumentFragment](./documentfragment/) | DocumentFragment, "hafif" veya "minimum" bir Belge nesnesidir. Bir belge ağacının bir bölümünü ayıklayabilmek veya bir belgenin yeni bir parçasını oluşturmak istemek çok yaygın bir durumdur. |
| [DocumentType](./documenttype/) | DocumentType, document için tanımlanan varlıkların listesine bir arabirim sağlar. |
| [DOMException](./domexception/) | DOMException arabirimi, bir yöntemi çağırmanın veya bir web API özelliğine erişmenin sonucu olarak meydana gelen (istisna adı verilen) anormal bir olayı temsil eder. Bu, temel olarak web API'lerinde hata koşullarının nasıl açıklandığıdır. |
| [DOMObject](./domobject/) | DOMObject türü, tüm Belge Nesne Modeli için bir temel nesneyi temsil etmek üzere kullanılır. Java ve ECMAScript için DOMObject, Nesne türüne bağlıdır. |
| [Element](./element/) | Öğe arabirimi, bir HTML veya XML belgesindeki bir öğeyi temsil eder. |
| [Entity](./entity/) | Bir XML belgesinde ayrıştırılmış veya ayrıştırılmamış olarak bilinen bir varlığı temsil eder. |
| [EntityReference](./entityreference/) | EntityReference düğümleri, ağaçta bir varlık referansını temsil etmek için kullanılabilir. |
| [EventTarget](./eventtarget/) | [`EventTarget`](../aspose.html.dom/eventtarget/) arayüz, DOM Olay Modelini destekleyen bir uygulamadaki tüm Düğümler tarafından uygulanır. Bu nedenle, bu arayüz, Düğüm arayüzünün bir örneğinde bağlamaya özgü döküm yöntemleri kullanılarak elde edilebilir. Arayüz, Olay Dinleyicilerin kaydedilmesine ve kaldırılmasına izin verir. BİR[`EventTarget`](../aspose.html.dom/eventtarget/) ve olayların buna gönderilmesi[`IEventTarget`](../aspose.html.dom.events/ieventtarget/) . |
| [Node](./node/) | Düğüm arabirimi, tüm Belge nesnesi Modeli için birincil veri türüdür. Belge ağacında tek bir düğümü temsil eder. |
| [Notation](./notation/) | DTD. 'de bildirilen bir notasyonu temsil eder. |
| [ProcessingInstruction](./processinginstruction/) | ProcessingInstruction, XML'de işlemciye özgü bilgileri belge metninde tutmanın bir yolu olarak kullanılan bir "işleme yönergesini" temsil eder. |
| [ShadowRoot](./shadowroot/) | ShadowRoot, gölge ağacının kök düğümüdür. |
| [Text](./text/) | Metin arabirimi, CharacterData'dan devralır ve bir Öğenin veya Attr. 'nin metin içeriğini (XML'de karakter verileri olarak adlandırılır) temsil eder. |
| [TypeInfo](./typeinfo/) | TypeInfo, Document. ile ilişkili şemalarda belirtilen Element veya Attr düğümlerinden başvurulan bir türü temsil eder. |
## Arayüzler

| Arayüz | Tanım |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | Tarama bağlamı, içinde[`Document`](../aspose.html.dom/document/) nesneler kullanıcıya sunulur. |
| [IChildNode](./ichildnode/) | tanımlar[`IChildNode`](../aspose.html.dom/ichildnode/) tarafından uygulanması gereken arayüz[`Node`](../aspose.html.dom/node/) bunun bir ebeveyni olabilir. |
| [IDocumentInit](./idocumentinit/) | Bu arayüz şunları sağlar:[`Document`](../aspose.html.dom/document/) başlatma bilgisi. |
| [IDOMImplementation](./idomimplementation/) | DOMImplementation arabirimi, belge nesne modelinin herhangi bir özel örneğinden bağımsız işlemleri gerçekleştirmek için bir dizi yöntem sağlar. |
| [IElementInit](./ielementinit/) | Bu arayüz şunları sağlar:[`Element`](../aspose.html.dom/element/) başlatma bilgisi. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | Desteklenen tüm öğeler tarafından devralınması gereken arabirimi temsil eder sistem olayı işleme |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | tanımlar[`IChildNode`](../aspose.html.dom/ichildnode/) bu değil[`DOCUMENT_TYPE_NODE`](../aspose.html.dom/node/document_type_node/) . |
| [INonElementParentNode](./inonelementparentnode/) | tanımlar[`IParentNode`](../aspose.html.dom/iparentnode/) Öğe türü olmayanlar. |
| [IParentNode](./iparentnode/) | [`IParentNode`](../aspose.html.dom/iparentnode/) olası ebeveynler tarafından uygulanan arayüz. |
## numaralandırma

| numaralandırma | Tanım |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | ShadowRoot'un çalışabileceği modlar. |


