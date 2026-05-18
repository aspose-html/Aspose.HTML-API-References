---
title: "Kelas Document"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.dom.Document. Document merepresentasikan seluruh dokumen HTML, XML, atau SVG. Secara konseptual, ia adalah akar dari pohon dokumen dan menyediakan akses utama ke data dokumen."
type: docs

url: /id/java/com.aspose.html.dom/document/
---
## Document class

Document merepresentasikan seluruh dokumen HTML, XML, atau SVG. Secara konseptual, ia adalah akar dari pohon dokumen, dan menyediakan akses utama ke data dokumen.

```java
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) URI dasar absolut dari node ini atau null jika implementasi tidak dapat memperoleh URI absolut. |
| [getCharacterSet](../../com.aspose.html.dom/document/characterset/) Mendapatkan enkoding dokumen. |
| [getCharset](../../com.aspose.html.dom/document/charset/) Mendapatkan enkoding dokumen. |
| [getChildElementCount](../../com.aspose.html.dom/document/childelementcount/) Mengembalikan jumlah saat ini dari node elemen yang menjadi anak dari elemen ini. 0 jika elemen ini tidak memiliki node anak yang berjenis nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Properti read-only childNodes dari antarmuka Node mengembalikan sebuah [`NodeList`](../../com.aspose.html.collections/nodelist/) yang hidup berisi node anak dari elemen yang diberikan dimana node anak pertama memiliki indeks 0. Node anak mencakup elemen, teks, dan komentar. |
| [getChildren](../../com.aspose.html.dom/document/children/) Mengembalikan elemen anak. |
| [getContentType](../../com.aspose.html.dom/document/contenttype/) Mendapatkan tipe konten dokumen. |
| [getContext](../../com.aspose.html.dom/document/context/) Mendapatkan konteks penjelajahan saat ini. |
| [getDefaultView](../../com.aspose.html.dom/document/defaultview/) Atribut IDL defaultView dari antarmuka Document, saat diakses, harus mengembalikan objek WindowProxy dari konteks penjelajahan Document ini, jika Document ini memiliki konteks penjelajahan yang terkait, atau null jika tidak. |
| [getDoctype](../../com.aspose.html.dom/document/doctype/) Deklarasi Tipe Dokumen yang terkait dengan dokumen ini. |
| [getDocumentElement](../../com.aspose.html.dom/document/documentelement/) Ini adalah atribut kenyamanan yang memungkinkan akses langsung ke node anak yang merupakan elemen dokumen dari dokumen. |
| [getDocumentURI](../../com.aspose.html.dom/document/documenturi/) Lokasi dokumen atau null jika tidak terdefinisi atau jika Dokumen dibuat menggunakan DOMImplementation.createDocument. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Properti read-only firstChild dari antarmuka [`Node`](../node/) mengembalikan anak pertama node dalam pohon, atau null jika node tidak memiliki anak. |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) Mengembalikan node elemen anak pertama dari elemen ini. null jika elemen ini tidak memiliki elemen anak. |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) Objek DOMImplementation yang menangani dokumen ini. |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) Mendapatkan enkoding dokumen. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Properti read-only lastChild dari antarmuka [`Node`](../node/) mengembalikan anak terakhir dari node. Jika induknya adalah elemen, maka anak tersebut biasanya berupa node elemen, node teks, atau node komentar. Mengembalikan null jika tidak ada elemen anak. |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) Mengembalikan node elemen anak terakhir dari elemen ini. null jika elemen ini tidak memiliki elemen anak. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Mengembalikan bagian lokal dari nama lengkap node ini. Untuk node dari tipe apa pun selain [`ELEMENT_NODE`](../node/element_node/) dan [`ATTRIBUTE_NODE`](../node/attribute_node/) serta node yang dibuat dengan metode DOM Level 1, seperti [`Document.createElement()`](./createelement/), nilai ini selalu null. |
| [getLocation](../../com.aspose.html.dom/document/location/) Lokasi dokumen. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Properti read-only Element.packageURI mengembalikan URI paket dari elemen, atau null jika elemen tidak berada dalam paket. |
| [getNextElementSibling](../../com.aspose.html.dom/document/nextelementsibling/) Mengembalikan node elemen saudara berikutnya dari elemen ini. null jika elemen ini tidak memiliki node elemen saudara yang muncul setelahnya dalam pohon dokumen. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Properti read-only nextSibling dari antarmuka [`Node`](../node/) mengembalikan node yang langsung mengikuti node yang ditentukan dalam [`childNodes`](../node/childnodes/) milik orang tuanya, atau mengembalikan null jika node yang ditentukan adalah anak terakhir dalam elemen induk. |
| [getNodeName](../../com.aspose.html.dom/document/nodename/) Nama node ini, tergantung pada tipenya. |
| [getNodeType](../../com.aspose.html.dom/document/nodetype/) Kode yang mewakili tipe objek dasar. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Properti nodeValue dari antarmuka [`Node `](../node/) mengembalikan atau mengatur nilai node saat ini. |
| [getOrigin](../../com.aspose.html.dom/document/origin/) Mendapatkan asal dokumen. |
| [getOwnerDocument](../../com.aspose.html.dom/document/ownerdocument/) Mendapatkan dokumen pemilik. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Properti read-only parentElement dari antarmuka [`Node`](../node/) mengembalikan [`Element`](../element/) induk node DOM, atau null jika node tidak memiliki induk, atau induknya bukan Element DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Properti read-only parentNode dari antarmuka Node mengembalikan induk dari node yang ditentukan dalam pohon DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | Properti read-only prefix mengembalikan awalan paket dari elemen yang ditentukan, atau null jika tidak ada awalan yang ditentukan. |
| [getPreviousElementSibling](../../com.aspose.html.dom/document/previouselementsibling/) Mengembalikan node elemen saudara sebelumnya dari elemen ini. null jika elemen ini tidak memiliki node elemen saudara yang muncul sebelumnya dalam pohon dokumen. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Properti read-only previousSibling dari antarmuka [`Node`](../node/) mengembalikan node yang langsung mendahului node yang ditentukan dalam daftar [`childNodes`](../node/firstchild/) milik orang tuanya, atau null jika node yang ditentukan adalah yang pertama dalam daftar tersebut. |
| [getReadyState](../../com.aspose.html.dom/document/readystate/) Mengembalikan status kesiapan dokumen. "loading" saat Dokumen sedang dimuat, "interactive" setelah selesai parsing tetapi masih memuat sub-sumber daya, dan "complete" setelah selesai dimuat. |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) Daftar yang berisi semua lembar gaya yang secara eksplisit ditautkan atau disematkan dalam sebuah dokumen. Untuk dokumen HTML, ini mencakup lembar gaya eksternal, yang disertakan melalui elemen HTML LINK, dan elemen STYLE inline. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | Properti textContent dari antarmuka [`Node`](../node/) merepresentasikan konten teks dari node dan turunannya. |
[getXmlStandalone]
[setXmlStandalone] An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
[getXmlVersion]
[setXmlVersion] An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Metode addEventListener() dari antarmuka [`EventTarget `](../eventtarget/) menyiapkan fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Metode addEventListener() dari antarmuka [EventTarget ](T:com.aspose.html.dom.EventTarget) mengatur sebuah fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Metode addEventListener() dari antarmuka [EventTarget ](T:com.aspose.html.dom.EventTarget) mengatur sebuah fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Metode appendChild() dari antarmuka Node menambahkan sebuah node ke akhir daftar anak dari node induk yang ditentukan. Jika anak yang diberikan merupakan referensi ke node yang sudah ada dalam dokumen, appendChild() memindahkannya dari posisi saat ini ke posisi baru (tidak ada keharusan untuk menghapus node dari node induknya sebelum menambahkannya ke node lain). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Metode cloneNode() dari antarmuka Node mengembalikan duplikat dari node tempat metode ini dipanggil. Parameternya mengontrol apakah subtree yang terdapat dalam node juga digandakan atau tidak. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Metode cloneNode() dari antarmuka Node mengembalikan duplikat dari node tempat metode ini dipanggil. Parameternya mengontrol apakah subtree yang terdapat dalam node juga digandakan atau tidak. |
| [createAttribute](../../com.aspose.html.dom/document/createattribute/)(String) | Metode Document.createAttribute() membuat node atribut baru, dan mengembalikannya. Objek yang dibuat adalah node yang mengimplementasikan antarmuka [`Attr`](../attr/). DOM tidak memaksa jenis atribut apa yang dapat ditambahkan ke elemen tertentu dengan cara ini. |
| [createAttributeNS](../../com.aspose.html.dom/document/createattributens/)(String, String) | Metode Document.createAttribute() membuat node atribut baru, dan mengembalikannya. Objek yang dibuat adalah node yang mengimplementasikan antarmuka [Attr](T:com.aspose.html.dom.Attr). DOM tidak memaksa jenis atribut apa yang dapat ditambahkan ke elemen tertentu dengan cara ini. |
| [createCDATASection](../../com.aspose.html.dom/document/createcdatasection/)(String) | Membuat node [`CDATASection`](../cdatasection/) yang nilainya adalah String yang ditentukan. |
| [createComment](../../com.aspose.html.dom/document/createcomment/)(String) | Membuat node [`Comment`](../comment/) dengan String yang diberikan. |
| [createDocumentFragment](../../com.aspose.html.dom/document/createdocumentfragment/)() | Membuat [`DocumentFragment`](../documentfragment/) kosong baru yang dapat diisi dengan node DOM untuk membangun pohon DOM di luar layar. |
| [createDocumentType](../../com.aspose.html.dom/document/createdocumenttype/)(String, String, String, String) | Metode ini mengembalikan objek [`DocumentType`](../documenttype/) yang dapat digunakan dengan DOMImplementation.createDocument saat pembuatan dokumen atau dapat dimasukkan ke dalam dokumen melalui metode seperti Node.insertBefore() atau Node.replaceChild(). |
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | Dalam dokumen HTML, metode document.createElement() membuat elemen HTML yang ditentukan oleh tagName, atau sebuah [`HTMLUnknownElement`](../../com.aspose.html/htmlunknownelement/) jika tagName tidak dikenali. |
| [createElementNS](../../com.aspose.html.dom/document/createelementns/)(String, String) | Membuat elemen dengan nama yang memenuhi syarat dan URI paket yang diberikan. |
| [createEntityReference](../../com.aspose.html.dom/document/createentityreference/)(String) | Membuat objek EntityReference. Selain itu, jika entitas yang dirujuk diketahui, daftar anak node EntityReference dibuat sama dengan node Entity yang bersangkutan. |
| [createEvent](../../com.aspose.html.dom/document/createevent/)(String) | Membuat sebuah [`Event`](../../com.aspose.html.dom.events/event/) dengan tipe yang didukung oleh implementasi. |
| [createExpression](../../com.aspose.html.dom/document/createexpression/)(String, IXPathNSResolver) | Membuat ekspresi XPath yang telah diparsir dengan paket yang diselesaikan. Ini berguna ketika sebuah ekspresi akan digunakan kembali dalam aplikasi karena memungkinkan kompilasi String ekspresi ke dalam bentuk internal yang lebih efisien dan menyelesaikan terlebih dahulu semua prefiks paket yang muncul dalam ekspresi. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator)(Node) | Membuat NodeIterator baru atas subtree yang berakar pada node yang ditentukan. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator_1)(Node, long) | Membuat NodeIterator baru atas subtree yang berakar pada node yang ditentukan. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Membuat NodeIterator baru atas subtree yang berakar pada node yang ditentukan. |
| [createNSResolver](../../com.aspose.html.dom/document/creatensresolver/)(Node) | Menyesuaikan setiap node DOM untuk menyelesaikan paket sehingga ekspresi XPath dapat dievaluasi dengan mudah relatif terhadap konteks node tempat ia muncul dalam dokumen. Adapter ini berfungsi seperti metode DOM Level 3 `lookupNamespaceURI` pada node dalam menyelesaikan packageURI dari prefiks yang diberikan menggunakan informasi terkini yang tersedia dalam hierarki node pada saat `lookupNamespaceURI` dipanggil, juga menyelesaikan prefiks xml implisit dengan benar. |
| [createProcessingInstruction](../../com.aspose.html.dom/document/createprocessinginstruction/)(String, String) | Membuat node ProcessingInstruction dengan nama dan String data yang ditentukan. |
| [createTextNode](../../com.aspose.html.dom/document/createtextnode/)(String) | Membuat node Text dengan String yang ditentukan. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker)(Node) | Membuat TreeWalker baru atas subtree yang berakar pada node yang ditentukan. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker_1)(Node, long) | Membuat TreeWalker baru atas subtree yang berakar pada node yang ditentukan. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Membuat TreeWalker baru atas subtree yang berakar pada node yang ditentukan. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Menyebarkan sebuah Event pada [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) yang ditentukan, (secara sinkron) memanggil EventListeners yang terpengaruh dalam urutan yang tepat. Aturan pemrosesan event normal (termasuk fase penangkapan dan fase bubbling opsional) juga berlaku untuk event yang disebarkan secara manual dengan [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Melakukan tugas yang ditentukan aplikasi terkait dengan pembebasan, pelepasan, atau pengaturan ulang sumber daya yang tidak dikelola. |
| [evaluate](../../com.aspose.html.dom/document/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Mengevaluasi String ekspresi XPath dan mengembalikan hasil dengan tipe yang ditentukan jika memungkinkan. |
| [getElementById](../../com.aspose.html.dom/document/getelementbyid/)(String) | Metode Document getElementById() mengembalikan objek [`Element`](../element/) yang merepresentasikan elemen yang properti id‑nya cocok dengan String yang diberikan. Karena ID elemen harus unik bila ditentukan, ini merupakan cara yang berguna untuk mengakses elemen tertentu dengan cepat. |
| [getElementsByClassName](../../com.aspose.html.dom/document/getelementsbyclassname/)(String) | Metode getElementsByClassName dari antarmuka `Document` mengembalikan objek mirip array berisi semua elemen anak yang memiliki semua nama kelas yang diberikan. |
| [getElementsByTagName](../../com.aspose.html.dom/document/getelementsbytagname/)(String) | Metode getElementsByTagName dari antarmuka `Document` mengembalikan [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) berisi elemen‑elemen dengan nama tag yang diberikan. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/document/getelementsbytagnamens/)(String, String) | Mengembalikan daftar elemen dengan nama tag yang diberikan yang termasuk dalam paket yang ditentukan. Seluruh dokumen dicari, termasuk node akar. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Metode hasChildNodes() dari antarmuka Node mengembalikan nilai boolean yang menunjukkan apakah [`Node`](../node/) yang diberikan memiliki node anak atau tidak. |
| [importNode](../../com.aspose.html.dom/document/importnode/)(Node, bool) | Mengimpor sebuah node dari dokumen lain ke dokumen ini, tanpa mengubah atau menghapus node sumber dari dokumen asli; metode ini membuat salinan baru dari node sumber. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Metode insertBefore() dari antarmuka Node menyisipkan sebuah node sebelum node referensi sebagai anak dari node induk yang ditentukan. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Metode isDefaultNamespace() dari antarmuka Node menerima sebuah URI paket sebagai argumen. Ia mengembalikan nilai boolean yang true jika paket tersebut adalah paket default pada node yang diberikan dan false jika tidak. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Metode isEqualNode() dari antarmuka [`Node`](../node/) menguji apakah dua node sama. Dua node dianggap sama ketika mereka memiliki tipe yang sama, karakteristik penentu (untuk elemen, misalnya ID, jumlah anak, dll.), atributnya cocok, dan sebagainya. Set data spesifik yang harus cocok bervariasi tergantung pada tipe node. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Metode isSameNode() dari antarmuka Node adalah alias warisan untuk operator kesetaraan ketat ===. Artinya, ia menguji apakah dua node sama (dengan kata lain, apakah mereka merujuk ke objek yang sama). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Metode lookupNamespaceURI() dari antarmuka Node mengambil sebuah prefiks sebagai parameter dan mengembalikan URI paket yang terkait dengannya pada node yang diberikan jika ditemukan (dan null jika tidak). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Metode lookupPrefix() dari antarmuka Node mengembalikan sebuah String yang berisi prefiks untuk URI paket tertentu, jika ada, dan null jika tidak. Ketika beberapa prefiks memungkinkan, prefiks pertama yang dikembalikan. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate)(RequestMessage) | Memuat dokumen berdasarkan objek permintaan yang ditentukan, menggantikan konten sebelumnya. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_4)(String) | Memuat dokumen pada Uniform Resource Locator (URL) yang ditentukan ke dalam instance saat ini, menggantikan konten sebelumnya. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_1)(Url) | Memuat dokumen pada Uniform Resource Locator (URL) yang ditentukan ke dalam instance saat ini, menggantikan konten sebelumnya. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_3)(Stream, String) | Memuat dokumen dari konten yang ditentukan dan menggunakan baseUri untuk menyelesaikan sumber daya relatif, menggantikan konten sebelumnya. Pemuatan dokumen dimulai dari posisi saat ini dalam aliran. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_2)(Stream, Url) | Memuat dokumen dari konten yang ditentukan dan menggunakan baseUri untuk menyelesaikan sumber daya relatif, menggantikan konten sebelumnya. Pemuatan dokumen dimulai dari posisi saat ini dalam aliran. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_6)(String, String) | Memuat dokumen dari konten yang ditentukan dan menggunakan baseUri untuk menyelesaikan sumber daya relatif, menggantikan konten sebelumnya. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_5)(String, Url) | Memuat dokumen dari konten yang ditentukan dan menggunakan baseUri untuk menyelesaikan sumber daya relatif, menggantikan konten sebelumnya. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Menempatkan semua node [`Text`](../text/) pada kedalaman penuh sub‑tree di bawah Node ini, termasuk node atribut, ke dalam bentuk "normal" di mana hanya struktur (misalnya, [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), dan [`entity references`](../entityreference/)) yang memisahkan node [`Text`](../text/), yaitu tidak ada node Text yang bersebelahan maupun node Text kosong. Ini dapat digunakan untuk memastikan tampilan DOM dari sebuah dokumen sama seperti jika dokumen tersebut disimpan dan dimuat kembali, serta berguna ketika operasi (seperti pencarian XPointer [XPointer]) yang bergantung pada struktur pohon dokumen tertentu akan digunakan. Jika parameter "normalize-characters" dari objek [`DOMConfiguration`](../../com.aspose.html/configuration/) yang terlampir pada [`Node.ownerDocument`](../node/ownerdocument/) bernilai true, metode ini juga akan sepenuhnya menormalkan karakter pada node Text. |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | Mengembalikan Element pertama dalam dokumen, yang cocok dengan selector |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | Mengembalikan NodeList dari semua Element dalam dokumen, yang cocok dengan selector |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Metode removeChild() dari antarmuka Node menghapus node anak dari DOM dan mengembalikan node yang dihapus. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Metode ini memungkinkan penghapusan event listeners dari target event. Jika sebuah listener dihapus dari sebuah elemen saat sedang memproses sebuah event, listener tersebut tidak akan dipicu oleh aksi saat ini. Event Listeners tidak pernah dapat dipanggil setelah dihapus. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Metode ini memungkinkan penghapusan event listeners dari target event. Jika sebuah listener dihapus dari sebuah elemen saat sedang memproses sebuah event, listener tersebut tidak akan dipicu oleh aksi saat ini. Event Listeners tidak pernah dapat dipanggil setelah dihapus. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Metode ini memungkinkan penghapusan event listeners dari target event. Jika sebuah listener dihapus dari sebuah elemen saat sedang memproses sebuah event, listener tersebut tidak akan dipicu oleh aksi saat ini. Event Listeners tidak pernah dapat dipanggil setelah dihapus. |
| [renderTo](../../com.aspose.html.dom/document/renderto/)(IDevice) | Metode ini digunakan untuk merender isi dokumen saat ini ke perangkat grafis yang ditentukan. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Mengganti node anak oldChild dengan newChild dalam daftar anak, dan mengembalikan node oldChild. Jika newChild adalah objek [`DocumentFragment`](../documentfragment/), oldChild digantikan oleh semua anak [`DocumentFragment`](../documentfragment/) yang dimasukkan dalam urutan yang sama. Jika newChild sudah berada dalam pohon, ia pertama‑tama dihapus. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Mengembalikan String yang mewakili instance ini. |
| [write](../../com.aspose.html.dom/document/write/)(params String[]) | Menulis sebuah String teks ke aliran dokumen yang dibuka oleh open(). Perhatikan bahwa fungsi ini akan menghasilkan dokumen yang tidak selalu dipandu oleh DTD sehingga mungkin menghasilkan hasil yang tidak valid dalam konteks dokumen. |
| [writeLn](../../com.aspose.html.dom/document/writeln/)(params String[]) | Menulis sebuah String teks yang diikuti oleh karakter baris baru ke aliran dokumen yang dibuka oleh open(). Perhatikan bahwa fungsi ini akan menghasilkan dokumen yang tidak selalu dipandu oleh DTD sehingga mungkin menghasilkan hasil yang tidak valid dalam konteks dokumen. |

## Acara

| Nama | Deskripsi |
| --- | --- |
| event [OnAbort](../../com.aspose.html.dom/document/onabort/) | Mendapatkan atau mengatur penangan acara untuk acara OnAbort. |
| event [OnBlur](../../com.aspose.html.dom/document/onblur/) | Mendapatkan atau mengatur penangan acara untuk acara OnBlur. |
| event [OnCancel](../../com.aspose.html.dom/document/oncancel/) | Mendapatkan atau mengatur penangan acara untuk acara OnCancel. |
| event [OnCanplay](../../com.aspose.html.dom/document/oncanplay/) | Mendapatkan atau mengatur penangan acara untuk acara OnCanplay. |
| event [OnCanPlayThrough](../../com.aspose.html.dom/document/oncanplaythrough/) | Mendapatkan atau mengatur penangan acara untuk acara OnCanPlayThrough. |
| event [OnChange](../../com.aspose.html.dom/document/onchange/) | Mendapatkan atau mengatur penangan acara untuk acara OnChange. |
| event [OnClick](../../com.aspose.html.dom/document/onclick/) | Mendapatkan atau mengatur penangan acara untuk acara OnClick. |
| event [OnCueChange](../../com.aspose.html.dom/document/oncuechange/) | Mendapatkan atau mengatur penangan acara untuk acara OnCueChange. |
| event [OnDblClick](../../com.aspose.html.dom/document/ondblclick/) | Mendapatkan atau mengatur penangan acara untuk acara OnDblClick. |
| event [OnDurationChange](../../com.aspose.html.dom/document/ondurationchange/) | Mendapatkan atau mengatur penangan acara untuk acara OnDurationChange. |
| event [OnEmptied](../../com.aspose.html.dom/document/onemptied/) | Mendapatkan atau mengatur penangan acara untuk acara OnEmptied. |
| event [OnEnded](../../com.aspose.html.dom/document/onended/) | Mendapatkan atau mengatur penangan acara untuk acara OnEnded. |
| event [OnError](../../com.aspose.html.dom/document/onerror/) | Mendapatkan atau mengatur penangan acara untuk acara OnError. |
| event [OnFocus](../../com.aspose.html.dom/document/onfocus/) | Mendapatkan atau mengatur penangan acara untuk acara OnFocus. |
| event [OnInput](../../com.aspose.html.dom/document/oninput/) | Mendapatkan atau mengatur penangan acara untuk acara OnInput. |
| event [OnInvalid](../../com.aspose.html.dom/document/oninvalid/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnInvalid. |
| event [OnKeyDown](../../com.aspose.html.dom/document/onkeydown/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnKeyDown. |
| event [OnKeyPress](../../com.aspose.html.dom/document/onkeypress/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnKeyPress. |
| event [OnKeyUp](../../com.aspose.html.dom/document/onkeyup/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnKeyUp. |
| event [OnLoad](../../com.aspose.html.dom/document/onload/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnLoad. |
| event [OnLoadedData](../../com.aspose.html.dom/document/onloadeddata/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnLoadedData. |
| event [OnLoadedMetadata](../../com.aspose.html.dom/document/onloadedmetadata/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnLoadedMetadata. |
| event [OnLoadStart](../../com.aspose.html.dom/document/onloadstart/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnLoadStart. |
| event [OnMouseDown](../../com.aspose.html.dom/document/onmousedown/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnMouseDown. |
| event [OnMouseEnter](../../com.aspose.html.dom/document/onmouseenter/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnMouseEnter. |
| event [OnMouseLeave](../../com.aspose.html.dom/document/onmouseleave/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnMouseLeave. |
| event [OnMouseMove](../../com.aspose.html.dom/document/onmousemove/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnMouseMove. |
| event [OnMouseOut](../../com.aspose.html.dom/document/onmouseout/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnMouseOut. |
| event [OnMouseOver](../../com.aspose.html.dom/document/onmouseover/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnMouseOver. |
| event [OnMouseUp](../../com.aspose.html.dom/document/onmouseup/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnMouseUp. |
| event [OnMouseWheel](../../com.aspose.html.dom/document/onmousewheel/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnMouseWheel. |
| event [OnPause](../../com.aspose.html.dom/document/onpause/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnPause. |
| event [OnPlay](../../com.aspose.html.dom/document/onplay/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnPlay. |
| event [OnPlaying](../../com.aspose.html.dom/document/onplaying/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnPlaying. |
| event [OnProgress](../../com.aspose.html.dom/document/onprogress/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnProgress. |
| event [OnRateChange](../../com.aspose.html.dom/document/onratechange/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnRateChange. |
| event [OnReadyStateChange](../../com.aspose.html.dom/document/onreadystatechange/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnReadyStateChange. |
| event [OnReset](../../com.aspose.html.dom/document/onreset/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnReset. |
| event [OnResize](../../com.aspose.html.dom/document/onresize/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnResize. |
| event [OnScroll](../../com.aspose.html.dom/document/onscroll/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnScroll. |
| event [OnSeeked](../../com.aspose.html.dom/document/onseeked/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnSeeked. |
| event [OnSeeking](../../com.aspose.html.dom/document/onseeking/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnSeeking. |
| event [OnSelect](../../com.aspose.html.dom/document/onselect/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnSelect. |
| event [OnShow](../../com.aspose.html.dom/document/onshow/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnShow. |
| event [OnStalled](../../com.aspose.html.dom/document/onstalled/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnStalled. |
| event [OnSubmit](../../com.aspose.html.dom/document/onsubmit/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnSubmit. |
| event [OnSuspend](../../com.aspose.html.dom/document/onsuspend/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnSuspend. |
| event [OnTimeUpdate](../../com.aspose.html.dom/document/ontimeupdate/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnTimeUpdate. |
| event [OnToggle](../../com.aspose.html.dom/document/ontoggle/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnToggle. |
| event [OnVolumeChange](../../com.aspose.html.dom/document/onvolumechange/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnVolumeChange. |
| event [OnWaiting](../../com.aspose.html.dom/document/onwaiting/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnWaiting. |

### Lihat Juga

* class [Node](../node/)
* interface [IDocumentEvent](../../com.aspose.html.dom.events/idocumentevent/)
* interface [IDocumentStyle](../../com.aspose.html.dom.css/idocumentstyle/)
* interface [IDocumentTraversal](../../com.aspose.html.dom.traversal/idocumenttraversal/)
* interface [IGlobalEventHandlers](../iglobaleventhandlers/)
* interface [INonElementParentNode](../inonelementparentnode/)
* interface [IParentNode](../iparentnode/)
* interface [IXPathEvaluator](../../com.aspose.html.dom.xpath/ixpathevaluator/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
