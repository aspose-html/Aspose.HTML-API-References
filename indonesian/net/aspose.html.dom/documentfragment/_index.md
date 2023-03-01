---
title: Class DocumentFragment
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.DocumentFragment kelas. DocumentFragment adalah objek Dokumen ringan atau minimal. Sangat umum jika ingin dapat mengekstraksi sebagian pohon dokumen atau membuat fragmen baru dari dokumen.
type: docs
weight: 670
url: /id/net/aspose.html.dom/documentfragment/
---
## DocumentFragment class

DocumentFragment adalah objek Dokumen "ringan" atau "minimal". Sangat umum jika ingin dapat mengekstraksi sebagian pohon dokumen atau membuat fragmen baru dari dokumen.

```csharp
public class DocumentFragment : Node, IParentNode
```

## Properti

| Nama | Keterangan |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes/) { get; } | NamedNodeMap yang berisi atribut node ini (jika itu adalah Elemen) atau null jika tidak. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri/) { get; } | URI dasar absolut dari node ini atau nol jika implementasi tidak dapat memperoleh URI absolut. |
| [ChildElementCount](../../aspose.html.dom/documentfragment/childelementcount/) { get; } | Mengembalikan jumlah node elemen saat ini yang merupakan turunan dari elemen ini. 0 jika elemen ini tidak memiliki node anak dengan nodeType 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | Sebuah NodeList yang berisi semua anak dari node ini. Jika tidak ada anak, ini adalah NodeList yang tidak berisi node.. |
| [Children](../../aspose.html.dom/documentfragment/children/) { get; } | Mengembalikan elemen turunan dari elemen saat ini. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | Anak pertama dari node ini. Jika tidak ada simpul seperti itu, ini mengembalikan null. |
| [FirstElementChild](../../aspose.html.dom/documentfragment/firstelementchild/) { get; } | Mengembalikan simpul elemen anak pertama dari elemen ini. null jika elemen ini tidak memiliki elemen turunan. |
| [InnerHTML](../../aspose.html.dom/documentfragment/innerhtml/) { get; set; } | Mengembalikan fragmen HTML atau XML yang mewakili konten elemen. Dapat diatur, untuk mengganti konten elemen dengan node yang diuraikan dari string yang diberikan. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | Anak terakhir dari node ini. Jika tidak ada simpul seperti itu, ini mengembalikan null. |
| [LastElementChild](../../aspose.html.dom/documentfragment/lastelementchild/) { get; } | Mengembalikan simpul elemen anak terakhir dari elemen ini. null jika elemen ini tidak memiliki elemen turunan. |
| virtual [LocalName](../../aspose.html.dom/node/localname/) { get; } | Mengembalikan bagian lokal dari nama yang memenuhi syarat dari node ini. Untuk node jenis apa pun selain ELEMENT_NODE dan ATTRIBUTE_NODE dan node yang dibuat dengan metode DOM Level 1, seperti Document.createElement(), ini selalu null. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri/) { get; } | Namespace URI node ini, atau null jika tidak ditentukan. |
| [NextElementSibling](../../aspose.html.dom/documentfragment/nextelementsibling/) { get; } | Mengembalikan simpul elemen saudara berikutnya dari elemen ini. null jika elemen ini tidak memiliki simpul saudara elemen yang muncul setelah elemen ini di pohon dokumen. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | Simpul yang langsung mengikuti simpul ini. Jika tidak ada simpul seperti itu, ini mengembalikan null. |
| override [NodeName](../../aspose.html.dom/documentfragment/nodename/) { get; } | Nama node ini, tergantung jenisnya. |
| override [NodeType](../../aspose.html.dom/documentfragment/nodetype/) { get; } | Kode yang mewakili jenis objek yang mendasarinya. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | Nilai simpul ini, tergantung pada jenisnya. |
| [OuterHTML](../../aspose.html.dom/documentfragment/outerhtml/) { get; set; } | Mengembalikan fragmen HTML atau XML yang mewakili elemen dan isinya. Dapat diatur, untuk mengganti elemen dengan node yang diuraikan dari string yang diberikan. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument/) { get; } | Objek Dokumen yang terkait dengan node ini. Ini juga merupakan objek Dokumen yang digunakan untuk membuat node baru. Ketika simpul ini adalah Dokumen atau Jenis Dokumen yang belum digunakan dengan Dokumen apa pun, ini adalah null. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Mendapatkan induknya[`Element`](../element/) dari simpul ini. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | Induk dari node ini. Semua node, kecuali Attr, Document, DocumentFragment, Entity, dan Notation mungkin memiliki induk. Namun, jika sebuah simpul baru saja dibuat dan belum ditambahkan ke pohon, atau jika telah dihapus dari pohon, ini adalah null. |
| virtual [Prefix](../../aspose.html.dom/node/prefix/) { get; set; } | Awalan namespace node ini, atau null jika tidak ditentukan. Ketika didefinisikan sebagai null, menyetelnya tidak berpengaruh |
| [PreviousElementSibling](../../aspose.html.dom/documentfragment/previouselementsibling/) { get; } | Mengembalikan simpul elemen saudara sebelumnya dari elemen ini. null jika elemen ini tidak memiliki simpul saudara elemen yang datang sebelum elemen ini di pohon dokumen. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | Node tepat sebelum node ini. Jika tidak ada simpul seperti itu, ini mengembalikan null. |
| override [TextContent](../../aspose.html.dom/documentfragment/textcontent/) { get; set; } | Atribut ini mengembalikan konten teks dari node ini dan turunannya. Ketika didefinisikan sebagai nol, pengaturan itu tidak berpengaruh. Pada pengaturan, setiap anak yang mungkin dimiliki simpul ini dihapus dan, jika string baru tidak kosong atau nol, diganti dengan simpul Teks tunggal yang berisi string yang disetel ke atribut ini. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | Metode ini memungkinkan pendaftaran event listener pada target event. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | Metode ini memungkinkan pendaftaran event listener pada target event. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | Metode ini memungkinkan pendaftaran event listener pada target event. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | Menambahkan node newChild ke akhir daftar anak dari node ini. Jika newChild sudah ada di pohon, pertama dihapus. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | Mengembalikan duplikat dari node ini, misalnya berfungsi sebagai pembuat salinan umum untuk node. Node duplikat tidak memiliki induk (parentNode adalah null) dan tidak ada data pengguna. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | Mengembalikan duplikat dari node ini, misalnya berfungsi sebagai pembuat salinan umum untuk node. Node duplikat tidak memiliki induk (parentNode adalah null) dan tidak ada data pengguna. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Metode ini memungkinkan pengiriman event ke dalam model event implementasi. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau menyetel ulang sumber daya yang tidak dikelola. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScriptType . |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes/)() | Mengembalikan apakah simpul ini (jika berupa elemen) memiliki atribut apapun |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | Mengembalikan apakah simpul ini memiliki turunan. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | Menyisipkan simpul sebelum anak simpul anak yang ada. Jika anak adalah null, sisipkan simpul di akhir daftar anak. Jika anak adalah objek DocumentFragment, semua anak disisipkan, dalam urutan yang sama, sebelum anak. Jika anak sudah ada di pohon, pertama-tama dihapus. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | Metode ini memeriksa apakah namespaceURI yang ditentukan adalah namespace default atau tidak. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | Menguji apakah dua node sama. Metode ini menguji kesamaan node, bukan kesamaan (yakni, apakah kedua node merujuk ke objek yang sama) yang dapat diuji dengan Node.isSameNode(). Semua node yang sama juga akan sama, meskipun kebalikannya mungkin tidak benar. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | Mengembalikan apakah node ini adalah node yang sama dengan yang diberikan. Metode ini menyediakan cara untuk menentukan apakah dua referensi Node dikembalikan oleh implementasi referensi objek yang sama. Ketika dua referensi Node adalah referensi ke objek yang sama, bahkan jika melalui proxy, referensi dapat digunakan sepenuhnya secara bergantian, sehingga semua atribut memiliki nilai yang sama dan memanggil metode DOM yang sama pada salah satu referensi selalu memiliki efek yang persis sama. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | Cari URI namespace yang terkait dengan awalan yang diberikan, mulai dari node ini. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | Cari awalan yang terkait dengan URI namespace yang diberikan, mulai dari node ini. Deklarasi namespace default diabaikan oleh metode ini. Lihat Namespace Prefix Lookup untuk detail tentang algoritme yang digunakan oleh metode ini. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Menempatkan semua simpul Teks di kedalaman penuh sub-pohon di bawah Node ini, termasuk simpul atribut, ke dalam bentuk "normal" di mana hanya struktur (misalnya, elemen, komentar, instruksi pemrosesan, bagian CDATA, dan referensi entitas) yang memisahkan Teks node, yaitu, tidak ada node Teks yang berdekatan atau node Teks kosong. Ini dapat digunakan untuk memastikan bahwa tampilan DOM dokumen sama seperti jika disimpan dan dimuat ulang, dan berguna saat operasi (seperti pencarian XPointer [XPointer]) yang bergantung pada struktur pohon dokumen tertentu akan digunakan. Jika parameter "normalize-characters" dari objek DOMConfiguration yang dilampirkan ke Node.ownerDocument benar, metode ini juga akan sepenuhnya menormalkan karakter dari Text nodes. |
| [QuerySelector](../../aspose.html.dom/documentfragment/queryselector/)(string) | Mengembalikan Elemen pertama dalam dokumen, yang cocok dengan pemilih |
| [QuerySelectorAll](../../aspose.html.dom/documentfragment/queryselectorall/)(string) | Mengembalikan NodeList dari semua Elemen dalam dokumen, yang cocok dengan selector |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | Menghapus node anak yang ditunjukkan oleh oldChild dari daftar anak, dan mengembalikannya. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | Metode ini memungkinkan penghapusan pendengar acara dari target acara. Jika[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) dihapus dari sebuah[`EventTarget`](../eventtarget/) saat sedang memproses suatu peristiwa, peristiwa itu tidak akan dipicu oleh tindakan saat ini. Pemroses Peristiwa tidak akan pernah bisa dipanggil setelah dihapus. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | Metode ini memungkinkan penghapusan pendengar acara dari target acara. Jika[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) dihapus dari sebuah[`EventTarget`](../eventtarget/) saat sedang memproses suatu peristiwa, peristiwa itu tidak akan dipicu oleh tindakan saat ini. Pemroses Peristiwa tidak akan pernah bisa dipanggil setelah dihapus. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | Metode ini memungkinkan penghapusan pendengar acara dari target acara. Jika[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) dihapus dari sebuah[`EventTarget`](../eventtarget/) saat sedang memproses suatu peristiwa, peristiwa itu tidak akan dipicu oleh tindakan saat ini. Pemroses Peristiwa tidak akan pernah bisa dipanggil setelah dihapus. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | Mengganti node anak oldChild dengan newChild dalam daftar anak, dan mengembalikan node oldChild. Jika newChild adalah objek DocumentFragment, oldChild digantikan oleh semua turunan DocumentFragment, yang disisipkan dalam urutan yang sama. Jika newChild sudah ada di pohon, pertama dihapus. |
| override [ToString](../../aspose.html.dom/node/tostring/)() | Mengembalikan aString yang mewakili instance ini. |

### Lihat juga

* class [Node](../node/)
* interface [IParentNode](../iparentnode/)
* ruang nama [Aspose.Html.Dom](../../aspose.html.dom/)
* perakitan [Aspose.HTML](../../)


