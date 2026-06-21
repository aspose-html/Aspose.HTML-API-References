---
title: "Kelas SVGElementInstance"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.dom.svg.SVGElementInstance. Objek akar dari setiap pohon bayangan use-element mengimplementasikan antarmuka SVGUseElementShadowRoot. Antarmuka ini saat ini tidak mendefinisikan ekstensi apa pun pada properti dan metode yang didefinisikan untuk antarmuka ShadowRoot dan campuran DocumentOrShadowRoot. Namun pohon yang berakar pada node ini sepenuhnya hanya-baca dari perspektif skrip penulis."
type: docs

url: /id/java/com.aspose.html.dom.svg/svgelementinstance/
---
## SVGElementInstance class

Objek akar setiap pohon bayangan use-element mengimplementasikan antarmuka SVGUseElementShadowRoot. Antarmuka ini saat ini tidak mendefinisikan ekstensi apa pun pada properti dan metode yang didefinisikan untuk antarmuka ShadowRoot dan campuran DocumentOrShadowRoot. Namun, pohon yang berakar pada node ini sepenuhnya hanya-baca dari perspektif skrip penulis.

```java
public class SVGElementInstance : ShadowRoot
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Properti read-only baseURI dari antarmuka Node mengembalikan URL dasar absolut dari dokumen yang berisi node tersebut. |
| [getChildElementCount](../../com.aspose.html.dom/documentfragment/childelementcount/) Mengembalikan jumlah saat ini node elemen yang menjadi anak dari elemen ini. 0 jika elemen ini tidak memiliki node anak yang berjenis nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Properti read-only childNodes dari antarmuka Node mengembalikan sebuah [`NodeList`](../../com.aspose.html.collections/nodelist/) yang hidup berisi node anak dari elemen yang diberikan di mana node anak pertama diberikan indeks 0. Node anak mencakup elemen, teks, dan komentar. |
| [getChildren](../../com.aspose.html.dom/documentfragment/children/) Mengembalikan elemen anak dari elemen saat ini. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Properti read-only firstChild dari antarmuka [`Node`](../../com.aspose.html.dom/node/) mengembalikan anak pertama node dalam pohon, atau null jika node tidak memiliki anak. |
| [getFirstElementChild](../../com.aspose.html.dom/documentfragment/firstelementchild/) Mengembalikan node elemen anak pertama dari elemen ini. null jika elemen ini tidak memiliki elemen anak. |
| [getHost](../../com.aspose.html.dom/shadowroot/host/) Host adalah elemen yang berisi ShadowRoot ini. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Properti read-only lastChild dari antarmuka [`Node`](../../com.aspose.html.dom/node/) mengembalikan anak terakhir dari node. Jika induknya adalah sebuah elemen, maka anak tersebut biasanya berupa node elemen, node teks, atau node komentar. Ia mengembalikan null jika tidak ada elemen anak |
| [getLastElementChild](../../com.aspose.html.dom/documentfragment/lastelementchild/) Mengembalikan node elemen anak terakhir dari elemen ini. null jika elemen ini tidak memiliki elemen anak. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Mengembalikan bagian lokal dari nama terkualifikasi node ini. Untuk node dengan tipe apa pun selain [`ELEMENT_NODE`](../../com.aspose.html.dom/node/element_node/) dan [`ATTRIBUTE_NODE`](../../com.aspose.html.dom/node/attribute_node/) serta node yang dibuat dengan metode DOM Level 1, seperti [`Document.createElement()`](../../com.aspose.html.dom/document/createelement/), nilai ini selalu null. |
| [getMode](../../com.aspose.html.dom/shadowroot/mode/) Mode di mana ShadowRoot ini beroperasi. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Properti read-only Element.packageURI mengembalikan URI paket dari elemen, atau null jika elemen tidak berada dalam paket. |
| [getNextElementSibling](../../com.aspose.html.dom/documentfragment/nextelementsibling/) Mengembalikan node elemen saudara berikutnya dari elemen ini. null jika elemen ini tidak memiliki node saudara elemen yang datang setelahnya dalam pohon dokumen. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Properti read-only nextSibling dari antarmuka [`Node`](../../com.aspose.html.dom/node/) mengembalikan node yang langsung mengikuti node yang ditentukan dalam [`childNodes`](../../com.aspose.html.dom/node/childnodes/) milik orang tuanya, atau mengembalikan null jika node yang ditentukan adalah anak terakhir dalam elemen induk. |
| [getNodeName](../../com.aspose.html.dom/documentfragment/nodename/) Nama node ini, tergantung pada tipenya. |
| [getNodeType](../../com.aspose.html.dom/documentfragment/nodetype/) Kode yang mewakili tipe objek dasar. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Properti nodeValue dari antarmuka [`Node `](../../com.aspose.html.dom/node/) mengembalikan atau mengatur nilai node saat ini. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Properti read-only ownerDocument dari antarmuka Node mengembalikan objek dokumen tingkat atas dari node. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Properti read-only parentElement dari antarmuka [`Node`](../../com.aspose.html.dom/node/) mengembalikan induk [`Element`](../../com.aspose.html.dom/element/) dari node DOM, atau null jika node tidak memiliki induk, atau induknya bukan Element DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Properti read-only parentNode dari antarmuka Node mengembalikan induk dari node yang ditentukan dalam pohon DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | Properti read-only prefix mengembalikan awalan paket dari elemen yang ditentukan, atau null jika tidak ada awalan yang ditentukan. |
| [getPreviousElementSibling](../../com.aspose.html.dom/documentfragment/previouselementsibling/) Mengembalikan node elemen saudara sebelumnya dari elemen ini. null jika elemen ini tidak memiliki node saudara elemen yang datang sebelumnya dalam pohon dokumen. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Properti read-only previousSibling dari antarmuka [`Node`](../../com.aspose.html.dom/node/) mengembalikan node yang langsung mendahului node yang ditentukan dalam daftar [`childNodes`](../../com.aspose.html.dom/node/firstchild/) milik orang tuanya, atau null jika node yang ditentukan adalah yang pertama dalam daftar tersebut. |
| [textContent](../../com.aspose.html.dom/documentfragment/textcontent/) { get; set; } | Atribut ini mengembalikan konten teks dari node ini dan turunannya. Ketika diatur menjadi null, pengaturannya tidak berpengaruh. Saat diatur, semua anak yang mungkin dimiliki node ini dihapus dan, jika String baru tidak kosong atau null, digantikan oleh satu node Text yang berisi String yang ditetapkan pada atribut ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Metode addEventListener() dari antarmuka [`EventTarget `](../../com.aspose.html.dom/eventtarget/) menyiapkan fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Metode addEventListener() dari antarmuka [EventTarget ](T:com.aspose.html.dom.EventTarget) menetapkan sebuah fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Metode addEventListener() dari antarmuka [EventTarget ](T:com.aspose.html.dom.EventTarget) menetapkan sebuah fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Metode appendChild() dari antarmuka Node menambahkan sebuah node ke akhir daftar anak dari node induk yang ditentukan. Jika anak yang diberikan merupakan referensi ke node yang sudah ada dalam dokumen, appendChild() memindahkannya dari posisi saat ini ke posisi baru (tidak ada keharusan untuk menghapus node dari node induknya sebelum menambahkannya ke node lain). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Metode cloneNode() dari antarmuka Node mengembalikan duplikat dari node tempat metode ini dipanggil. Parameternya mengontrol apakah subtree yang terdapat dalam node juga digandakan atau tidak. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Metode cloneNode() dari antarmuka Node mengembalikan duplikat dari node tempat metode ini dipanggil. Parameternya mengontrol apakah subtree yang terdapat dalam node juga digandakan atau tidak. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Menyebarkan sebuah Event pada [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) yang ditentukan, (secara sinkron) memanggil EventListeners yang terpengaruh dalam urutan yang tepat. Aturan pemrosesan event normal (termasuk fase penangkapan dan fase gelembung opsional) juga berlaku untuk event yang disebarkan secara manual dengan [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Melakukan tugas yang ditentukan aplikasi terkait dengan pembebasan, pelepasan, atau pengaturan ulang sumber daya yang tidak dikelola. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Metode hasChildNodes() dari antarmuka Node mengembalikan nilai boolean yang menunjukkan apakah [`Node`](../../com.aspose.html.dom/node/) yang diberikan memiliki node anak atau tidak. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Metode insertBefore() dari antarmuka Node menyisipkan sebuah node sebelum node referensi sebagai anak dari node induk yang ditentukan. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Metode isDefaultNamespace() dari antarmuka Node menerima sebuah URI paket sebagai argumen. Ia mengembalikan nilai boolean yang true jika paket tersebut adalah paket default pada node yang diberikan dan false jika tidak. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Metode isEqualNode() dari antarmuka [`Node`](../../com.aspose.html.dom/node/) menguji apakah dua node sama. Dua node dianggap sama ketika mereka memiliki tipe yang sama, karakteristik penentu (untuk elemen, ini meliputi ID, jumlah anak, dan sebagainya), atributnya cocok, dan seterusnya. Set data spesifik yang harus cocok bervariasi tergantung pada tipe node. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Metode isSameNode() dari antarmuka Node adalah alias warisan untuk operator kesetaraan ketat ===. Artinya, ia menguji apakah dua node sama (dengan kata lain, apakah mereka merujuk ke objek yang sama). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Metode lookupNamespaceURI() dari antarmuka Node mengambil sebuah prefiks sebagai parameter dan mengembalikan URI paket yang terkait dengannya pada node yang diberikan jika ditemukan (dan null jika tidak). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Metode lookupPrefix() dari antarmuka Node mengembalikan sebuah String yang berisi prefiks untuk URI paket tertentu, jika ada, dan null jika tidak. Ketika beberapa prefiks memungkinkan, prefiks pertama yang dikembalikan. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Menempatkan semua node [`Text`](../../com.aspose.html.dom/text/) pada kedalaman penuh sub‑tree di bawah Node ini, termasuk node atribut, ke dalam bentuk "normal" di mana hanya struktur (misalnya, [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), dan [`entity references`](../../com.aspose.html.dom/entityreference/)) yang memisahkan node [`Text`](../../com.aspose.html.dom/text/), yaitu tidak ada node Text yang bersebelahan maupun node Text kosong. Ini dapat digunakan untuk memastikan bahwa tampilan DOM dari sebuah dokumen sama seperti jika dokumen tersebut disimpan dan dimuat kembali, dan berguna ketika operasi (seperti pencarian XPointer [XPointer]) yang bergantung pada struktur pohon dokumen tertentu akan digunakan. Jika parameter "normalize-characters" dari objek [`DOMConfiguration`](../../com.aspose.html/configuration/) yang terlampir pada [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) bernilai true, metode ini juga akan sepenuhnya menormalkan karakter node Text. |
| [querySelector](../../com.aspose.html.dom/documentfragment/queryselector/)(String) | Mengembalikan Element pertama dalam dokumen yang cocok dengan selector |
| [querySelectorAll](../../com.aspose.html.dom/documentfragment/queryselectorall/)(String) | Mengembalikan NodeList dari semua Element dalam dokumen yang cocok dengan selector |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Metode removeChild() pada antarmuka Node menghapus node anak dari DOM dan mengembalikan node yang dihapus. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Metode ini memungkinkan penghapusan pendengar peristiwa dari target peristiwa. Jika sebuah pendengar dihapus saat sedang memproses peristiwa, ia tidak akan dipicu oleh aksi saat ini. Pendengar Peristiwa tidak pernah dapat dipanggil setelah dihapus. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Metode ini memungkinkan penghapusan pendengar peristiwa dari target peristiwa. Jika sebuah pendengar dihapus saat sedang memproses peristiwa, ia tidak akan dipicu oleh aksi saat ini. Pendengar Peristiwa tidak pernah dapat dipanggil setelah dihapus. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Metode ini memungkinkan penghapusan pendengar peristiwa dari target peristiwa. Jika sebuah pendengar dihapus saat sedang memproses peristiwa, ia tidak akan dipicu oleh aksi saat ini. Pendengar Peristiwa tidak pernah dapat dipanggil setelah dihapus. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Mengganti node anak oldChild dengan newChild dalam daftar anak, dan mengembalikan node oldChild. Jika newChild adalah objek [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), oldChild digantikan oleh semua anak [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) yang dimasukkan dalam urutan yang sama. Jika newChild sudah berada dalam pohon, ia pertama-tama dihapus. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Mengembalikan String yang mewakili instance ini. |

### Lihat Juga

* class [ShadowRoot](../../com.aspose.html.dom/shadowroot/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
