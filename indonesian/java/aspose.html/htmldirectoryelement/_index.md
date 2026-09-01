---
title: "Kelas HTMLDirectoryElement"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.HTMLDirectoryElement. Daftar direktori. Lihat definisi elemen DIR dalam HTML 4.01. Elemen ini tidak lagi digunakan dalam HTML 4.01"
type: docs

url: /id/java/com.aspose.html/htmldirectoryelement/
---
## HTMLDirectoryElement class

Daftar direktori. Lihat definisi elemen DIR dalam HTML 4.01. Elemen ini sudah tidak dipakai lagi dalam HTML 4.01.

Lihat juga [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109).

```java
public class HTMLDirectoryElement : HTMLElement
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getAttributes](../../com.aspose.html.dom/element/attributes/) NamedNodeMap yang berisi atribut-atribut node ini (jika itu adalah Element) atau null jika tidak. |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Properti read-only baseURI dari antarmuka Node mengembalikan URL dasar absolut dari dokumen yang berisi node tersebut. |
| [getChildElementCount](../../com.aspose.html.dom/element/childelementcount/) Mengembalikan jumlah saat ini dari node elemen yang menjadi anak dari elemen ini. 0 jika elemen ini tidak memiliki node anak dengan nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Properti read-only childNodes dari antarmuka Node mengembalikan sebuah [`NodeList`](../../com.aspose.html.collections/nodelist/) yang hidup berisi node anak dari elemen yang diberikan di mana node anak pertama diberikan indeks 0. Node anak mencakup elemen, teks, dan komentar. |
| [getChildren](../../com.aspose.html.dom/element/children/) Mengembalikan elemen anak dari elemen saat ini. |
| [getClassList](../../com.aspose.html.dom/element/classlist/) Mengembalikan DOMTokenList yang hidup yang berisi token-token yang diperoleh dari parsing atribut "class". |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
[getCompact]
[setCompact] Reduce spacing between list items. See the compact attribute definition in HTML 4.01. This attribute is deprecated in HTML 4.01. |
[getDir]
[setDir] Specifies the base direction of directionally neutral text and the directionality of tables. See the dir attribute definition in HTML 4.01. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Properti read-only firstChild dari antarmuka [`Node`](../../com.aspose.html.dom/node/) mengembalikan anak pertama node dalam pohon, atau null jika node tidak memiliki anak. |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) Mengembalikan node elemen anak pertama dari elemen ini. null jika elemen ini tidak memiliki elemen anak. |
[getId]
[setId] The element's identifier. See the id attribute definition in HTML 4.01. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
[getLang]
[setLang] Language code defined in RFC 1766. See the lang attribute definition in HTML 4.01. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Properti read-only lastChild dari antarmuka [`Node`](../../com.aspose.html.dom/node/) mengembalikan anak terakhir dari node. Jika induknya adalah sebuah elemen, maka anak tersebut biasanya berupa node elemen, node teks, atau node komentar. Ia mengembalikan null jika tidak ada elemen anak |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) Mengembalikan node elemen anak terakhir dari elemen ini. null jika elemen ini tidak memiliki elemen anak. |
| [getLocalName](../../com.aspose.html.dom/element/localname/) Mengembalikan bagian lokal dari nama yang memenuhi syarat dari node ini. Untuk node dengan tipe apa pun selain ELEMENT_NODE dan ATTRIBUTE_NODE serta node yang dibuat dengan metode DOM Level 1, seperti Document.createElement(), nilai ini selalu null. |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) URI paket dari node ini, atau null jika tidak ditentukan. |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) Mengembalikan node elemen saudara berikutnya dari elemen ini. null jika elemen ini tidak memiliki node elemen saudara yang datang setelahnya dalam pohon dokumen. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Properti read-only nextSibling dari antarmuka [`Node`](../../com.aspose.html.dom/node/) mengembalikan node yang langsung mengikuti node yang ditentukan dalam [`childNodes`](../../com.aspose.html.dom/node/childnodes/) milik orang tuanya, atau mengembalikan null jika node yang ditentukan adalah anak terakhir dalam elemen induk. |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) Nama node ini, tergantung pada tipenya. |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) Kode yang mewakili tipe objek dasar. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Properti nodeValue dari antarmuka [`Node `](../../com.aspose.html.dom/node/) mengembalikan atau mengatur nilai node saat ini. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Properti read-only ownerDocument dari antarmuka Node mengembalikan objek dokumen tingkat atas dari node. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Properti read-only parentElement dari antarmuka [`Node`](../../com.aspose.html.dom/node/) mengembalikan induk [`Element`](../../com.aspose.html.dom/element/) dari node DOM, atau null jika node tidak memiliki induk, atau induknya bukan Element DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Properti read-only parentNode dari antarmuka Node mengembalikan induk dari node yang ditentukan dalam pohon DOM. |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) Prefiks paket dari node ini, atau null jika tidak ditentukan. Ketika diatur menjadi null, pengaturannya tidak berpengaruh |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) Mengembalikan node elemen saudara sebelumnya dari elemen ini. null jika elemen ini tidak memiliki node elemen saudara yang datang sebelumnya dalam pohon dokumen. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Properti read-only previousSibling dari antarmuka [`Node`](../../com.aspose.html.dom/node/) mengembalikan node yang langsung mendahului node yang ditentukan dalam daftar [`childNodes`](../../com.aspose.html.dom/node/firstchild/) milik orang tuanya, atau null jika node yang ditentukan adalah yang pertama dalam daftar tersebut. |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) Mengembalikan shadowRoot yang disimpan pada elemen ini atau null jika ditutup. |
| [getStyle](../../com.aspose.html/htmlelement/style/) Mewakili atribut gaya yang memungkinkan penulis untuk langsung menerapkan informasi gaya ke elemen tertentu. |
| [getTagName](../../com.aspose.html.dom/element/tagname/) Nama elemen. |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | Atribut ini mengembalikan konten teks dari node ini dan turunannya. Ketika diatur menjadi null, pengaturannya tidak berpengaruh. Saat diatur, semua anak yang mungkin dimiliki node ini dihapus dan, jika String baru tidak kosong atau null, digantikan oleh satu node Text yang berisi String yang ditetapkan pada atribut ini. |
[getTitle]
[setTitle] The element's advisory title. See the title attribute definition in HTML 4.01. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Metode addEventListener() dari antarmuka [`EventTarget `](../../com.aspose.html.dom/eventtarget/) menyiapkan fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Metode addEventListener() dari antarmuka [EventTarget ](T:com.aspose.html.dom.EventTarget) menetapkan sebuah fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Metode addEventListener() dari antarmuka [EventTarget ](T:com.aspose.html.dom.EventTarget) menetapkan sebuah fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Metode appendChild() dari antarmuka Node menambahkan sebuah node ke akhir daftar anak dari node induk yang ditentukan. Jika anak yang diberikan merupakan referensi ke node yang sudah ada dalam dokumen, appendChild() memindahkannya dari posisi saat ini ke posisi baru (tidak ada keharusan untuk menghapus node dari node induknya sebelum menambahkannya ke node lain). |
| [attachShadow](../../com.aspose.html.dom/element/attachshadow/)(ShadowRootMode) | Membuat shadow root dan melampirkannya ke elemen saat ini. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Metode cloneNode() dari antarmuka Node mengembalikan duplikat dari node tempat metode ini dipanggil. Parameternya mengontrol apakah subtree yang terdapat dalam node juga digandakan atau tidak. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Metode cloneNode() dari antarmuka Node mengembalikan duplikat dari node tempat metode ini dipanggil. Parameternya mengontrol apakah subtree yang terdapat dalam node juga digandakan atau tidak. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Menyebarkan sebuah Event pada [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) yang ditentukan, (secara sinkron) memanggil EventListeners yang terpengaruh dalam urutan yang tepat. Aturan pemrosesan event normal (termasuk fase penangkapan dan fase gelembung opsional) juga berlaku untuk event yang disebarkan secara manual dengan [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Melakukan tugas yang ditentukan aplikasi terkait dengan pembebasan, pelepasan, atau pengaturan ulang sumber daya yang tidak dikelola. |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | Mengambil nilai atribut berdasarkan nama. |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | Mengembalikan nama-nama atribut elemen sebagai Array of Strings. Jika elemen tidak memiliki atribut, ia mengembalikan array kosong. |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | Mengambil node atribut berdasarkan nama. |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | Mengambil node Attr berdasarkan nama lokal dan URI paket. |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | Mengambil nilai atribut berdasarkan nama lokal dan URI paket. |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | Mengembalikan objek [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) yang berisi semua elemen di dalam [`element`](../../com.aspose.html.dom/element/) yang memiliki semua kelas yang ditentukan dalam argumen. |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | Mengembalikan objek [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) yang berisi semua [`elements`](../../com.aspose.html.dom/element/) dengan nama tag tertentu, dalam urutan dokumen. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | Mengembalikan objek [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) yang berisi semua [`elements`](../../com.aspose.html.dom/element/) dengan nama lokal dan String URI paket tertentu dalam urutan dokumen. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | Mengembalikan true ketika atribut dengan nama tertentu ditentukan pada elemen ini atau memiliki nilai default, false sebaliknya. |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | Mengembalikan true ketika atribut dengan nama lokal dan URI paket tertentu ditentukan pada elemen ini atau memiliki nilai default, false sebaliknya. |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | Mengembalikan apakah node ini (jika merupakan elemen) memiliki atribut apa pun |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Metode hasChildNodes() dari antarmuka Node mengembalikan nilai boolean yang menunjukkan apakah [`Node`](../../com.aspose.html.dom/node/) yang diberikan memiliki node anak atau tidak. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Metode insertBefore() dari antarmuka Node menyisipkan sebuah node sebelum node referensi sebagai anak dari node induk yang ditentukan. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Metode isDefaultNamespace() dari antarmuka Node menerima sebuah URI paket sebagai argumen. Ia mengembalikan nilai boolean yang true jika paket tersebut adalah paket default pada node yang diberikan dan false jika tidak. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Metode isEqualNode() dari antarmuka [`Node`](../../com.aspose.html.dom/node/) menguji apakah dua node sama. Dua node dianggap sama ketika mereka memiliki tipe yang sama, karakteristik penentu (untuk elemen, ini meliputi ID, jumlah anak, dan sebagainya), atributnya cocok, dan seterusnya. Set data spesifik yang harus cocok bervariasi tergantung pada tipe node. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Metode isSameNode() dari antarmuka Node adalah alias warisan untuk operator kesetaraan ketat ===. Artinya, ia menguji apakah dua node sama (dengan kata lain, apakah mereka merujuk ke objek yang sama). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Metode lookupNamespaceURI() dari antarmuka Node mengambil sebuah prefiks sebagai parameter dan mengembalikan URI paket yang terkait dengannya pada node yang diberikan jika ditemukan (dan null jika tidak). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Metode lookupPrefix() dari antarmuka Node mengembalikan sebuah String yang berisi prefiks untuk URI paket tertentu, jika ada, dan null jika tidak. Ketika beberapa prefiks memungkinkan, prefiks pertama yang dikembalikan. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Menempatkan semua node [`Text`](../../com.aspose.html.dom/text/) pada kedalaman penuh sub‑pohon di bawah Node ini, termasuk node atribut, ke dalam bentuk "normal" di mana hanya struktur (misalnya, [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), dan [`entity references`](../../com.aspose.html.dom/entityreference/)) yang memisahkan node [`Text`](../../com.aspose.html.dom/text/), yaitu tidak ada node Text yang bersebelahan atau node Text kosong. Ini dapat digunakan untuk memastikan tampilan DOM dari sebuah dokumen sama seperti jika dokumen tersebut disimpan dan dimuat kembali, dan berguna ketika operasi (seperti pencarian XPointer [XPointer]) yang bergantung pada struktur pohon dokumen tertentu akan digunakan. Jika parameter "normalize-characters" dari objek [`DOMConfiguration`](../configuration/) yang terlampir pada [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) bernilai true, metode ini juga akan sepenuhnya menormalkan karakter pada node Text. |
| [querySelector](../../com.aspose.html.dom/element/queryselector/)(String) | Mengembalikan Element pertama dalam dokumen yang cocok dengan selector |
| [querySelectorAll](../../com.aspose.html.dom/element/queryselectorall/)(String) | Mengembalikan NodeList dari semua Element dalam dokumen yang cocok dengan selector |
| [remove](../../com.aspose.html.dom/element/remove/)() | Menghapus instance ini. |
| [removeAttribute](../../com.aspose.html.dom/element/removeattribute/)(String) | Menghapus atribut berdasarkan nama. |
| [removeAttributeNode](../../com.aspose.html.dom/element/removeattributenode/)(Attr) | Menghapus node atribut yang ditentukan. |
| [removeAttributeNS](../../com.aspose.html.dom/element/removeattributens/)(String, String) | Menghapus atribut berdasarkan nama lokal dan URI paket. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Metode removeChild() pada antarmuka Node menghapus node anak dari DOM dan mengembalikan node yang dihapus. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Metode ini memungkinkan penghapusan pendengar peristiwa dari target peristiwa. Jika sebuah pendengar dihapus saat sedang memproses peristiwa, ia tidak akan dipicu oleh aksi saat ini. Pendengar Peristiwa tidak pernah dapat dipanggil setelah dihapus. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Metode ini memungkinkan penghapusan pendengar peristiwa dari target peristiwa. Jika sebuah pendengar dihapus saat sedang memproses peristiwa, ia tidak akan dipicu oleh aksi saat ini. Pendengar Peristiwa tidak pernah dapat dipanggil setelah dihapus. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Metode ini memungkinkan penghapusan pendengar peristiwa dari target peristiwa. Jika sebuah pendengar dihapus saat sedang memproses peristiwa, ia tidak akan dipicu oleh aksi saat ini. Pendengar Peristiwa tidak pernah dapat dipanggil setelah dihapus. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Mengganti node anak oldChild dengan newChild dalam daftar anak, dan mengembalikan node oldChild. Jika newChild adalah objek [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), oldChild digantikan oleh semua anak [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) yang dimasukkan dalam urutan yang sama. Jika newChild sudah berada dalam pohon, ia pertama-tama dihapus. |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | Menambahkan atribut baru. Jika atribut dengan nama tersebut sudah ada dalam elemen, nilainya diubah menjadi nilai parameter. |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | Menambahkan node atribut baru. Jika atribut dengan nama tersebut (nodeName) sudah ada dalam elemen, ia digantikan oleh yang baru. |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | Menambahkan atribut baru. Jika atribut dengan nama lokal dan URI paket tersebut sudah ada dalam elemen, ia digantikan oleh yang baru. |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | Menambahkan atribut baru. Jika atribut dengan nama lokal dan URI paket yang sama sudah ada pada elemen, prefiksnya diubah menjadi bagian prefiks dari qualifiedName, dan nilainya diubah menjadi nilai parameter. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String) | Jika force tidak diberikan, "toggles" qualifiedName, menghapusnya jika ada dan menambahkannya jika tidak ada. Jika force true, menambahkan qualifiedName. Jika force false, menghapus qualifiedName. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String, bool) | Jika force tidak diberikan, "toggles" qualifiedName, menghapusnya jika ada dan menambahkannya jika tidak ada. Jika force true, menambahkan qualifiedName. Jika force false, menghapus qualifiedName. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Mengembalikan String yang mewakili instance ini. |

## Peristiwa

| Nama | Deskripsi |
| --- | --- |
| event [OnAbort](../../com.aspose.html/htmlelement/onabort/) | Mendapatkan atau mengatur penangan peristiwa untuk event OnAbort. |
| event [OnBlur](../../com.aspose.html/htmlelement/onblur/) | Mendapatkan atau mengatur penangan peristiwa untuk event OnBlur. |
| event [OnCancel](../../com.aspose.html/htmlelement/oncancel/) | Mendapatkan atau mengatur penangan peristiwa untuk event OnCancel. |
| event [OnCanplay](../../com.aspose.html/htmlelement/oncanplay/) | Mendapatkan atau mengatur penangan peristiwa untuk event OnCanplay. |
| event [OnCanPlayThrough](../../com.aspose.html/htmlelement/oncanplaythrough/) | Mendapatkan atau mengatur penangan peristiwa untuk event OnCanPlayThrough. |
| event [OnChange](../../com.aspose.html/htmlelement/onchange/) | Mendapatkan atau mengatur penangan peristiwa untuk event OnChange. |
| event [OnClick](../../com.aspose.html/htmlelement/onclick/) | Mendapatkan atau mengatur penangan peristiwa untuk event OnClick. |
| event [OnCueChange](../../com.aspose.html/htmlelement/oncuechange/) | Mendapatkan atau mengatur penangan peristiwa untuk event OnCueChange. |
| event [OnDblClick](../../com.aspose.html/htmlelement/ondblclick/) | Mendapatkan atau mengatur penangan peristiwa untuk event OnDblClick. |
| event [OnDurationChange](../../com.aspose.html/htmlelement/ondurationchange/) | Mendapatkan atau mengatur penangan peristiwa untuk event OnDurationChange. |
| event [OnEmptied](../../com.aspose.html/htmlelement/onemptied/) | Mendapatkan atau mengatur penangan peristiwa untuk event OnEmptied. |
| event [OnEnded](../../com.aspose.html/htmlelement/onended/) | Mendapatkan atau mengatur penangan peristiwa untuk event OnEnded. |
| event [OnError](../../com.aspose.html/htmlelement/onerror/) | Mendapatkan atau mengatur penangan peristiwa untuk event OnError. |
| event [OnFocus](../../com.aspose.html/htmlelement/onfocus/) | Mendapatkan atau mengatur penangan peristiwa untuk event OnFocus. |
| event [OnInput](../../com.aspose.html/htmlelement/oninput/) | Mendapatkan atau mengatur penangan peristiwa untuk event OnInput. |
| event [OnInvalid](../../com.aspose.html/htmlelement/oninvalid/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnInvalid. |
| event [OnKeyDown](../../com.aspose.html/htmlelement/onkeydown/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnKeyDown. |
| event [OnKeyPress](../../com.aspose.html/htmlelement/onkeypress/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnKeyPress. |
| event [OnKeyUp](../../com.aspose.html/htmlelement/onkeyup/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnKeyUp. |
| event [OnLoad](../../com.aspose.html/htmlelement/onload/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnLoad. |
| event [OnLoadedData](../../com.aspose.html/htmlelement/onloadeddata/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnLoadedData. |
| event [OnLoadedMetadata](../../com.aspose.html/htmlelement/onloadedmetadata/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnLoadedMetadata. |
| event [OnLoadStart](../../com.aspose.html/htmlelement/onloadstart/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnLoadStart. |
| event [OnMouseDown](../../com.aspose.html/htmlelement/onmousedown/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnMouseDown. |
| event [OnMouseEnter](../../com.aspose.html/htmlelement/onmouseenter/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnMouseEnter. |
| event [OnMouseLeave](../../com.aspose.html/htmlelement/onmouseleave/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnMouseLeave. |
| event [OnMouseMove](../../com.aspose.html/htmlelement/onmousemove/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnMouseMove. |
| event [OnMouseOut](../../com.aspose.html/htmlelement/onmouseout/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnMouseOut. |
| event [OnMouseOver](../../com.aspose.html/htmlelement/onmouseover/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnMouseOver. |
| event [OnMouseUp](../../com.aspose.html/htmlelement/onmouseup/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnMouseUp. |
| event [OnMouseWheel](../../com.aspose.html/htmlelement/onmousewheel/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnMouseWheel. |
| event [OnPause](../../com.aspose.html/htmlelement/onpause/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnPause. |
| event [OnPlay](../../com.aspose.html/htmlelement/onplay/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnPlay. |
| event [OnPlaying](../../com.aspose.html/htmlelement/onplaying/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnPlaying. |
| event [OnProgress](../../com.aspose.html/htmlelement/onprogress/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnProgress. |
| event [OnRateChange](../../com.aspose.html/htmlelement/onratechange/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnRateChange. |
| event [OnReset](../../com.aspose.html/htmlelement/onreset/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnReset. |
| event [OnResize](../../com.aspose.html/htmlelement/onresize/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnResize. |
| event [OnScroll](../../com.aspose.html/htmlelement/onscroll/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnScroll. |
| event [OnSeeked](../../com.aspose.html/htmlelement/onseeked/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnSeeked. |
| event [OnSeeking](../../com.aspose.html/htmlelement/onseeking/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnSeeking. |
| event [OnSelect](../../com.aspose.html/htmlelement/onselect/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnSelect. |
| event [OnShow](../../com.aspose.html/htmlelement/onshow/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnShow. |
| event [OnStalled](../../com.aspose.html/htmlelement/onstalled/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnStalled. |
| event [OnSubmit](../../com.aspose.html/htmlelement/onsubmit/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnSubmit. |
| event [OnSuspend](../../com.aspose.html/htmlelement/onsuspend/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnSuspend. |
| event [OnTimeUpdate](../../com.aspose.html/htmlelement/ontimeupdate/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnTimeUpdate. |
| event [OnToggle](../../com.aspose.html/htmlelement/ontoggle/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnToggle. |
| event [OnVolumeChange](../../com.aspose.html/htmlelement/onvolumechange/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnVolumeChange. |
| event [OnWaiting](../../com.aspose.html/htmlelement/onwaiting/) | Mendapatkan atau mengatur penangan peristiwa untuk peristiwa OnWaiting. |

### Lihat Juga

* class [HTMLElement](../htmlelement/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
