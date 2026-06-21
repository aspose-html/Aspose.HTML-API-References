---
title: "Kelas CharacterData"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.dom.CharacterData. CharacterData memperluas Node dengan sekumpulan atribut dan metode untuk mengakses data karakter dalam DOM"
type: docs

url: /id/java/com.aspose.html.dom/characterdata/
---
## CharacterData class

CharacterData memperluas Node dengan sekumpulan atribut dan metode untuk mengakses data karakter dalam DOM.

```java
public abstract class CharacterData : Node
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Properti read-only baseURI dari antarmuka Node mengembalikan URL dasar absolut dari dokumen yang berisi node tersebut. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Properti read-only childNodes dari antarmuka Node mengembalikan sebuah [`NodeList`](../../com.aspose.html.collections/nodelist/) yang hidup berisi node anak dari elemen yang diberikan di mana node anak pertama diberikan indeks 0. Node anak mencakup elemen, teks, dan komentar. |
| [data](../../com.aspose.html.dom/characterdata/data/) { get; set; } | Data karakter dari node yang mengimplementasikan antarmuka ini. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Properti read-only firstChild dari antarmuka [`Node`](../node/) mengembalikan anak pertama node dalam pohon, atau null jika node tidak memiliki anak. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Properti read-only lastChild dari antarmuka [`Node`](../node/) mengembalikan anak terakhir dari node. Jika induknya adalah sebuah elemen, maka anak tersebut biasanya berupa node elemen, node teks, atau node komentar. Mengembalikan null jika tidak ada elemen anak. |
| [getLength](../../com.aspose.html.dom/characterdata/length/) Jumlah unit 16-bit yang tersedia melalui data dan metode subStringData di bawah ini. Nilainya dapat nol, yaitu node CharacterData dapat kosong. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Mengembalikan bagian lokal dari nama yang memenuhi syarat node ini. Untuk node dari tipe apa pun selain [`ELEMENT_NODE`](../node/element_node/) dan [`ATTRIBUTE_NODE`](../node/attribute_node/) serta node yang dibuat dengan metode DOM Level 1, seperti [`Document.createElement()`](../document/createelement/), nilai ini selalu null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Properti read-only Element.packageURI mengembalikan URI paket dari elemen, atau null jika elemen tidak berada dalam paket. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Properti read-only nextSibling dari antarmuka [`Node`](../node/) mengembalikan node yang langsung mengikuti node yang ditentukan dalam [`childNodes`](../node/childnodes/) milik orang tuanya, atau mengembalikan null jika node yang ditentukan adalah anak terakhir dalam elemen induk. |
| abstract [getNodeName](../../com.aspose.html.dom/node/nodename/) Properti read-only nodeName dari Node mengembalikan nama node saat ini sebagai String. |
| abstract [getNodeType](../../com.aspose.html.dom/node/nodetype/) Kode yang mewakili tipe objek yang mendasarinya. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Properti nodeValue dari antarmuka [`Node `](../node/) mengembalikan atau mengatur nilai node saat ini. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Properti read-only ownerDocument dari antarmuka Node mengembalikan objek dokumen tingkat atas dari node. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Properti read-only parentElement dari antarmuka [`Node`](../node/) mengembalikan [`Element`](../element/) induk node DOM, atau null jika node tidak memiliki induk, atau induknya bukan Elemen DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Properti read-only parentNode dari antarmuka Node mengembalikan induk dari node yang ditentukan dalam pohon DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | Properti read-only prefix mengembalikan awalan paket dari elemen yang ditentukan, atau null jika tidak ada awalan yang ditentukan. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Properti read-only previousSibling dari antarmuka [`Node`](../node/) mengembalikan node yang langsung mendahului node yang ditentukan dalam daftar [`childNodes`](../node/firstchild/) milik orang tuanya, atau null jika node yang ditentukan adalah yang pertama dalam daftar tersebut. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | Properti textContent dari antarmuka [`Node`](../node/) merepresentasikan konten teks dari node dan turunannya. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Metode addEventListener() dari antarmuka [`EventTarget `](../eventtarget/) menyiapkan sebuah fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Metode addEventListener() dari antarmuka [EventTarget ](T:com.aspose.html.dom.EventTarget) menetapkan sebuah fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Metode addEventListener() dari antarmuka [EventTarget ](T:com.aspose.html.dom.EventTarget) menetapkan sebuah fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Metode appendChild() dari antarmuka Node menambahkan sebuah node ke akhir daftar anak dari node induk yang ditentukan. Jika anak yang diberikan merupakan referensi ke node yang sudah ada dalam dokumen, appendChild() memindahkannya dari posisi saat ini ke posisi baru (tidak ada keharusan untuk menghapus node dari node induknya sebelum menambahkannya ke node lain). |
| [appendData](../../com.aspose.html.dom/characterdata/appenddata/)(String) | Tambahkan String ke akhir data karakter node. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Metode cloneNode() dari antarmuka Node mengembalikan duplikat dari node tempat metode ini dipanggil. Parameternya mengontrol apakah subtree yang terdapat dalam node juga digandakan atau tidak. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Metode cloneNode() dari antarmuka Node mengembalikan duplikat dari node tempat metode ini dipanggil. Parameternya mengontrol apakah subtree yang terdapat dalam node juga digandakan atau tidak. |
| [deleteData](../../com.aspose.html.dom/characterdata/deletedata/)(int, int) | Hapus rentang unit 16-bit dari node. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Menyebarkan sebuah Event pada [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) yang ditentukan, (secara sinkron) memanggil EventListeners yang terpengaruh dalam urutan yang tepat. Aturan pemrosesan event normal (termasuk fase penangkapan dan fase gelembung opsional) juga berlaku untuk event yang disebarkan secara manual dengan [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Melakukan tugas yang ditentukan aplikasi terkait dengan pembebasan, pelepasan, atau pengaturan ulang sumber daya yang tidak dikelola. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Metode hasChildNodes() dari antarmuka Node mengembalikan nilai boolean yang menunjukkan apakah [`Node`](../node/) yang diberikan memiliki node anak atau tidak. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Metode insertBefore() dari antarmuka Node menyisipkan sebuah node sebelum node referensi sebagai anak dari node induk yang ditentukan. |
| [insertData](../../com.aspose.html.dom/characterdata/insertdata/)(int, String) | Sisipkan String pada offset unit 16-bit yang ditentukan. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Metode isDefaultNamespace() dari antarmuka Node menerima sebuah URI paket sebagai argumen. Ia mengembalikan nilai boolean yang true jika paket tersebut adalah paket default pada node yang diberikan dan false jika tidak. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Metode isEqualNode() dari antarmuka [`Node`](../node/) menguji apakah dua node sama. Dua node dianggap sama ketika mereka memiliki tipe yang sama, karakteristik penentu (untuk elemen, ini meliputi ID, jumlah anak, dan sebagainya), atributnya cocok, dan seterusnya. Set data spesifik yang harus cocok bervariasi tergantung pada tipe node. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Metode isSameNode() dari antarmuka Node adalah alias warisan untuk operator kesetaraan ketat ===. Artinya, ia menguji apakah dua node sama (dengan kata lain, apakah mereka merujuk ke objek yang sama). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Metode lookupNamespaceURI() dari antarmuka Node mengambil sebuah prefiks sebagai parameter dan mengembalikan URI paket yang terkait dengannya pada node yang diberikan jika ditemukan (dan null jika tidak). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Metode lookupPrefix() dari antarmuka Node mengembalikan sebuah String yang berisi prefiks untuk URI paket tertentu, jika ada, dan null jika tidak. Ketika beberapa prefiks memungkinkan, prefiks pertama yang dikembalikan. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Menempatkan semua node [`Text`](../text/) pada kedalaman penuh sub‑pohon di bawah Node ini, termasuk node atribut, ke dalam bentuk "normal" di mana hanya struktur (misalnya, [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), dan [`entity references`](../entityreference/)) yang memisahkan node [`Text`](../text/), yaitu tidak ada node Text yang bersebelahan maupun node Text kosong. Ini dapat digunakan untuk memastikan tampilan DOM dari sebuah dokumen sama seperti jika dokumen tersebut disimpan dan dimuat kembali, dan berguna ketika operasi (seperti pencarian XPointer [XPointer]) yang bergantung pada struktur pohon dokumen tertentu akan digunakan. Jika parameter "normalize-characters" dari objek [`DOMConfiguration`](../../com.aspose.html/configuration/) yang terlampir pada [`Node.ownerDocument`](../node/ownerdocument/) bernilai true, metode ini juga akan sepenuhnya menormalkan karakter pada node Text. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Metode removeChild() pada antarmuka Node menghapus node anak dari DOM dan mengembalikan node yang dihapus. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Metode ini memungkinkan penghapusan pendengar peristiwa dari target peristiwa. Jika sebuah pendengar dihapus saat sedang memproses peristiwa, ia tidak akan dipicu oleh aksi saat ini. Pendengar Peristiwa tidak pernah dapat dipanggil setelah dihapus. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Metode ini memungkinkan penghapusan pendengar peristiwa dari target peristiwa. Jika sebuah pendengar dihapus saat sedang memproses peristiwa, ia tidak akan dipicu oleh aksi saat ini. Pendengar Peristiwa tidak pernah dapat dipanggil setelah dihapus. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Metode ini memungkinkan penghapusan pendengar peristiwa dari target peristiwa. Jika sebuah pendengar dihapus saat sedang memproses peristiwa, ia tidak akan dipicu oleh aksi saat ini. Pendengar Peristiwa tidak pernah dapat dipanggil setelah dihapus. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Mengganti node anak oldChild dengan newChild dalam daftar anak, dan mengembalikan node oldChild. Jika newChild adalah objek [`DocumentFragment`](../documentfragment/), oldChild digantikan oleh semua anak [`DocumentFragment`](../documentfragment/) yang dimasukkan dalam urutan yang sama. Jika newChild sudah berada dalam pohon, ia pertama‑tama dihapus. |
| [replaceData](../../com.aspose.html.dom/characterdata/replacedata/)(int, int, String) | Ganti karakter mulai dari offset unit 16-bit yang ditentukan dengan String yang diberikan. |
| [subStringData](../../com.aspose.html.dom/characterdata/subStringdata/)(int, int) | Mengekstrak rentang data dari node. |
| [toString](../../com.aspose.html.dom/characterdata/toString/)() | Mengembalikan String yang mewakili instance ini. |

### Lihat Juga

* class [Node](../node/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
