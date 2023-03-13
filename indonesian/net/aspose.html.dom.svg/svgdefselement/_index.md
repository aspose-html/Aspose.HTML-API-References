---
title: Class SVGDefsElement
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Svg.SVGDefsElement kelas. Antarmuka SVGDefsElement sesuai dengan elemen defs.
type: docs
weight: 1990
url: /id/net/aspose.html.dom.svg/svgdefselement/
---
## SVGDefsElement class

Antarmuka SVGDefsElement sesuai dengan elemen 'defs'.

```csharp
public class SVGDefsElement : SVGGraphicsElement
```

## Properti

| Nama | Keterangan |
| --- | --- |
| override [Attributes](../../aspose.html.dom/element/attributes/) { get; } | NamedNodeMap yang berisi atribut node ini (jika itu adalah Elemen) atau null jika tidak. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri/) { get; } | URI dasar absolut dari node ini atau nol jika implementasi tidak dapat memperoleh URI absolut. |
| [ChildElementCount](../../aspose.html.dom/element/childelementcount/) { get; } | Mengembalikan jumlah node elemen saat ini yang merupakan turunan dari elemen ini. 0 jika elemen ini tidak memiliki node anak dengan nodeType 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | Sebuah NodeList yang berisi semua anak dari node ini. Jika tidak ada anak, ini adalah NodeList yang tidak berisi node.. |
| [Children](../../aspose.html.dom/element/children/) { get; } | Mengembalikan elemen turunan dari elemen saat ini. |
| [ClassList](../../aspose.html.dom/element/classlist/) { get; } | Mengembalikan DOMTokenList langsung yang berisi token yang diterima dari parsing atribut "class". |
| [ClassName](../../aspose.html.dom.svg/svgelement/classname/) { get; } | Sesuai dengan atribut 'kelas' pada elemen yang diberikan. |
| [ClassName](../../aspose.html.dom/element/classname/) { get; set; } | Atribut kelas elemen. Atribut ini telah diganti namanya karena bertentangan dengan kata kunci "class" yang diekspos oleh banyak bahasa. Lihat definisi atribut kelas di HTML 4.01. |
| [FarthestViewportElement](../../aspose.html.dom.svg/svggraphicselement/farthestviewportelement/) { get; } | Elemen 'svg' leluhur terjauh. Null jika elemen saat ini adalah elemen svg terluar. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | Anak pertama dari node ini. Jika tidak ada simpul seperti itu, ini mengembalikan null. |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild/) { get; } | Mengembalikan simpul elemen anak pertama dari elemen ini. null jika elemen ini tidak memiliki elemen turunan. |
| [Id](../../aspose.html.dom.svg/svgelement/id/) { get; set; } | Nilai atribut 'id' pada elemen yang diberikan, atau string kosong jika 'id' tidak ada. |
| [InnerHTML](../../aspose.html.dom/element/innerhtml/) { get; set; } | Mengembalikan fragmen HTML atau XML yang mewakili konten elemen. Dapat diatur, untuk mengganti konten elemen dengan node yang diuraikan dari string yang diberikan. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | Anak terakhir dari node ini. Jika tidak ada simpul seperti itu, ini mengembalikan null. |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild/) { get; } | Mengembalikan simpul elemen anak terakhir dari elemen ini. null jika elemen ini tidak memiliki elemen turunan. |
| override [LocalName](../../aspose.html.dom/element/localname/) { get; } | Mengembalikan bagian lokal dari nama yang memenuhi syarat dari node ini. Untuk node jenis apa pun selain ELEMENT_NODE dan ATTRIBUTE_NODE dan node yang dibuat dengan metode DOM Level 1, seperti Document.createElement(), ini selalu null. |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri/) { get; } | Namespace URI node ini, atau null jika tidak ditentukan. |
| [NearestViewportElement](../../aspose.html.dom.svg/svggraphicselement/nearestviewportelement/) { get; } | Elemen yang membentuk viewport saat ini. Seringkali, elemen 'svg' leluhur terdekat. Null jika elemen saat ini adalah elemen svg terluar. |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling/) { get; } | Mengembalikan simpul elemen saudara berikutnya dari elemen ini. null jika elemen ini tidak memiliki simpul saudara elemen yang muncul setelah elemen ini di pohon dokumen. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | Simpul yang langsung mengikuti simpul ini. Jika tidak ada simpul seperti itu, ini mengembalikan null. |
| override [NodeName](../../aspose.html.dom/element/nodename/) { get; } | Nama node ini, tergantung jenisnya. |
| override [NodeType](../../aspose.html.dom/element/nodetype/) { get; } | Kode yang mewakili jenis objek yang mendasarinya. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | Nilai simpul ini, tergantung pada jenisnya. |
| [OuterHTML](../../aspose.html.dom/element/outerhtml/) { get; set; } | Mengembalikan fragmen HTML atau XML yang mewakili elemen dan isinya. Dapat diatur, untuk mengganti elemen dengan node yang diuraikan dari string yang diberikan. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument/) { get; } | Objek Dokumen yang terkait dengan node ini. Ini juga merupakan objek Dokumen yang digunakan untuk membuat node baru. Ketika simpul ini adalah Dokumen atau Jenis Dokumen yang belum digunakan dengan Dokumen apa pun, ini adalah null. |
| [OwnerSVGElement](../../aspose.html.dom.svg/svgelement/ownersvgelement/) { get; } | Elemen 'svg' leluhur terdekat. Null jika elemen yang diberikan adalah elemen svg terluar. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Mendapatkan induknya[`Element`](../../aspose.html.dom/element/) dari simpul ini. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | Induk dari node ini. Semua node, kecuali Attr, Document, DocumentFragment, Entity, dan Notation mungkin memiliki induk. Namun, jika sebuah simpul baru saja dibuat dan belum ditambahkan ke pohon, atau jika telah dihapus dari pohon, ini adalah null. |
| override [Prefix](../../aspose.html.dom/element/prefix/) { get; } | Awalan namespace node ini, atau null jika tidak ditentukan. Ketika didefinisikan sebagai null, menyetelnya tidak berpengaruh |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling/) { get; } | Mengembalikan simpul elemen saudara sebelumnya dari elemen ini. null jika elemen ini tidak memiliki simpul saudara elemen yang datang sebelum elemen ini di pohon dokumen. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | Node tepat sebelum node ini. Jika tidak ada simpul seperti itu, ini mengembalikan null. |
| [RequiredExtensions](../../aspose.html.dom.svg/svggraphicselement/requiredextensions/) { get; } | Sesuai dengan atribut 'requiredExtensions' pada elemen yang diberikan. |
| [RequiredFeatures](../../aspose.html.dom.svg/svggraphicselement/requiredfeatures/) { get; } | Sesuai dengan atribut 'requiredFeatures' pada elemen yang diberikan. |
| [SchemaTypeInfo](../../aspose.html.dom/element/schematypeinfo/) { get; } | Jenis informasi yang terkait dengan elemen ini. |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot/) { get; } | Mengembalikan shadowRoot yang disimpan pada elemen ini atau null jika ditutup. |
| [Style](../../aspose.html.dom.svg/svgelement/style/) { get; } | Sesuai dengan atribut 'gaya' pada elemen yang diberikan. Jika agen pengguna tidak mendukung gaya dengan CSS, maka atribut ini harus selalu bernilai null. |
| [SystemLanguage](../../aspose.html.dom.svg/svggraphicselement/systemlanguage/) { get; } | Sesuai dengan atribut 'systemLanguage' pada elemen yang diberikan. |
| [TagName](../../aspose.html.dom/element/tagname/) { get; } | Nama elemen. |
| override [TextContent](../../aspose.html.dom/element/textcontent/) { get; set; } | Atribut ini mengembalikan konten teks dari node ini dan turunannya. Ketika didefinisikan sebagai nol, pengaturan itu tidak berpengaruh. Pada pengaturan, setiap anak yang mungkin dimiliki simpul ini dihapus dan, jika string baru tidak kosong atau nol, diganti dengan simpul Teks tunggal yang berisi string yang disetel ke atribut ini. |
| [Transform](../../aspose.html.dom.svg/svggraphicselement/transform/) { get; } | Sesuai dengan atribut 'transform' pada elemen yang diberikan. |
| [ViewportElement](../../aspose.html.dom.svg/svgelement/viewportelement/) { get; } | Elemen yang membentuk viewport saat ini. Seringkali, elemen 'svg' leluhur terdekat. Null jika elemen yang diberikan adalah elemen svg terluar. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | Metode ini memungkinkan pendaftaran event listener pada target event. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | Metode ini memungkinkan pendaftaran event listener pada target event. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | Metode ini memungkinkan pendaftaran event listener pada target event. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | Menambahkan node newChild ke akhir daftar anak dari node ini. Jika newChild sudah ada di pohon, pertama dihapus. |
| [AttachShadow](../../aspose.html.dom/element/attachshadow/)(ShadowRootMode) | Membuat akar bayangan dan menempelkannya ke elemen saat ini. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | Mengembalikan duplikat dari node ini, misalnya berfungsi sebagai pembuat salinan umum untuk node. Node duplikat tidak memiliki induk (parentNode adalah null) dan tidak ada data pengguna. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | Mengembalikan duplikat dari node ini, misalnya berfungsi sebagai pembuat salinan umum untuk node. Node duplikat tidak memiliki induk (parentNode adalah null) dan tidak ada data pengguna. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Metode ini memungkinkan pengiriman event ke dalam model event implementasi. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau menyetel ulang sumber daya yang tidak dikelola. |
| [GetAttribute](../../aspose.html.dom/element/getattribute/)(string) | Mengambil nilai atribut berdasarkan nama. |
| [GetAttributeNode](../../aspose.html.dom/element/getattributenode/)(string) | Mengambil simpul atribut berdasarkan nama. |
| [GetAttributeNodeNS](../../aspose.html.dom/element/getattributenodens/)(string, string) | Mengambil node Attr dengan nama lokal dan namespace URI. |
| [GetAttributeNS](../../aspose.html.dom/element/getattributens/)(string, string) | Mengambil nilai atribut dengan nama lokal dan namespace URI. |
| [GetBBox](../../aspose.html.dom.svg/svggraphicselement/getbbox/)() | Mengembalikan kotak pembatas yang ketat di ruang pengguna saat ini (yaitu, setelah penerapan atribut 'transform', jika ada) pada geometri semua elemen grafik yang terkandung, tidak termasuk efek stroke, clipping, masking dan filter). Perhatikan bahwa getBBox harus mengembalikan kotak pembatas yang sebenarnya pada saat metode dipanggil, meskipun elemen belum dirender. |
| [GetCTM](../../aspose.html.dom.svg/svggraphicselement/getctm/)() | Mengembalikan matriks transformasi dari unit pengguna saat ini (yaitu, setelah penerapan atribut 'transform', jika ada) ke sistem koordinat area pandang untuk ViewportElement. terdekat |
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname/)(string) | Mengembalikan objek NodeList langsung yang berisi semua elemen dalam dokumen yang memiliki semua kelas yang ditentukan dalam argumen. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname/)(string) | Mengembalikan NodeList dari semua Elemen turunan dengan nama tag tertentu, dalam urutan dokumen. |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens/)(string, string) | Mengembalikan NodeList dari semua Elemen turunan dengan nama lokal dan namespace URI yang diberikan dalam urutan dokumen. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScriptType . |
| [GetScreenCTM](../../aspose.html.dom.svg/svggraphicselement/getscreenctm/)() | Mengembalikan matriks transformasi dari unit pengguna saat ini (yaitu, setelah penerapan atribut 'transformasi', jika ada) ke pemberitahuan "piksel" dari agen pengguna induk. Untuk perangkat tampilan, idealnya ini mewakili piksel layar fisik. Untuk perangkat atau lingkungan lain di mana ukuran piksel fisik tidak diketahui, maka algoritme yang mirip dengan definisi "piksel" CSS2 dapat digunakan sebagai gantinya. Perhatikan bahwa null dikembalikan jika elemen ini tidak terhubung ke pohon dokumen. Metode ini akan lebih tepat disebut sebagai getClientCTM, tetapi nama getScreenCTM disimpan karena alasan historis. |
| [HasAttribute](../../aspose.html.dom/element/hasattribute/)(string) | Mengembalikan nilai benar ketika atribut dengan nama tertentu ditentukan pada elemen ini atau memiliki nilai default, salah jika sebaliknya. |
| [HasAttributeNS](../../aspose.html.dom/element/hasattributens/)(string, string) | Mengembalikan nilai true ketika atribut dengan nama lokal tertentu dan URI namespace ditentukan pada elemen ini atau memiliki nilai default, false sebaliknya. |
| override [HasAttributes](../../aspose.html.dom/element/hasattributes/)() | Mengembalikan apakah simpul ini (jika berupa elemen) memiliki atribut apapun |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | Mengembalikan apakah simpul ini memiliki turunan. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | Menyisipkan simpul sebelum anak simpul anak yang ada. Jika anak adalah null, sisipkan simpul di akhir daftar anak. Jika anak adalah objek DocumentFragment, semua anak disisipkan, dalam urutan yang sama, sebelum anak. Jika anak sudah ada di pohon, pertama-tama dihapus. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | Metode ini memeriksa apakah namespaceURI yang ditentukan adalah namespace default atau tidak. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | Menguji apakah dua node sama. Metode ini menguji kesamaan node, bukan kesamaan (yakni, apakah kedua node merujuk ke objek yang sama) yang dapat diuji dengan Node.isSameNode(). Semua node yang sama juga akan sama, meskipun kebalikannya mungkin tidak benar. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | Mengembalikan apakah node ini adalah node yang sama dengan yang diberikan. Metode ini menyediakan cara untuk menentukan apakah dua referensi Node dikembalikan oleh implementasi referensi objek yang sama. Ketika dua referensi Node adalah referensi ke objek yang sama, bahkan jika melalui proxy, referensi dapat digunakan sepenuhnya secara bergantian, sehingga semua atribut memiliki nilai yang sama dan memanggil metode DOM yang sama pada salah satu referensi selalu memiliki efek yang persis sama. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | Cari URI namespace yang terkait dengan awalan yang diberikan, mulai dari node ini. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | Cari awalan yang terkait dengan URI namespace yang diberikan, mulai dari node ini. Deklarasi namespace default diabaikan oleh metode ini. Lihat Namespace Prefix Lookup untuk detail tentang algoritme yang digunakan oleh metode ini. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Menempatkan semua simpul Teks di kedalaman penuh sub-pohon di bawah Node ini, termasuk simpul atribut, ke dalam bentuk "normal" di mana hanya struktur (misalnya, elemen, komentar, instruksi pemrosesan, bagian CDATA, dan referensi entitas) yang memisahkan Teks node, yaitu, tidak ada node Teks yang berdekatan atau node Teks kosong. Ini dapat digunakan untuk memastikan bahwa tampilan DOM dokumen sama seperti jika disimpan dan dimuat ulang, dan berguna saat operasi (seperti pencarian XPointer [XPointer]) yang bergantung pada struktur pohon dokumen tertentu akan digunakan. Jika parameter "normalize-characters" dari objek DOMConfiguration yang dilampirkan ke Node.ownerDocument benar, metode ini juga akan sepenuhnya menormalkan karakter dari Text nodes. |
| [QuerySelector](../../aspose.html.dom/element/queryselector/)(string) | Mengembalikan Elemen pertama dalam dokumen, yang cocok dengan pemilih |
| [QuerySelectorAll](../../aspose.html.dom/element/queryselectorall/)(string) | Mengembalikan NodeList dari semua Elemen dalam dokumen, yang cocok dengan selector |
| [Remove](../../aspose.html.dom/element/remove/)() | Menghapus kejadian ini. |
| [RemoveAttribute](../../aspose.html.dom/element/removeattribute/)(string) | Menghapus atribut berdasarkan nama. |
| [RemoveAttributeNode](../../aspose.html.dom/element/removeattributenode/)(Attr) | Menghapus node atribut yang ditentukan. |
| [RemoveAttributeNS](../../aspose.html.dom/element/removeattributens/)(string, string) | Menghapus atribut dengan nama lokal dan namespace URI. |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | Menghapus node anak yang ditunjukkan oleh oldChild dari daftar anak, dan mengembalikannya. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | Metode ini memungkinkan penghapusan pendengar acara dari target acara. Jika[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) dihapus dari sebuah[`EventTarget`](../../aspose.html.dom/eventtarget/) saat sedang memproses suatu peristiwa, peristiwa itu tidak akan dipicu oleh tindakan saat ini. Pemroses Peristiwa tidak akan pernah bisa dipanggil setelah dihapus. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | Metode ini memungkinkan penghapusan pendengar acara dari target acara. Jika[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) dihapus dari sebuah[`EventTarget`](../../aspose.html.dom/eventtarget/) saat sedang memproses suatu peristiwa, peristiwa itu tidak akan dipicu oleh tindakan saat ini. Pemroses Peristiwa tidak akan pernah bisa dipanggil setelah dihapus. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | Metode ini memungkinkan penghapusan pendengar acara dari target acara. Jika[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) dihapus dari sebuah[`EventTarget`](../../aspose.html.dom/eventtarget/) saat sedang memproses suatu peristiwa, peristiwa itu tidak akan dipicu oleh tindakan saat ini. Pemroses Peristiwa tidak akan pernah bisa dipanggil setelah dihapus. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | Mengganti node anak oldChild dengan newChild dalam daftar anak, dan mengembalikan node oldChild. Jika newChild adalah objek DocumentFragment, oldChild digantikan oleh semua turunan DocumentFragment, yang disisipkan dalam urutan yang sama. Jika newChild sudah ada di pohon, pertama dihapus. |
| [SetAttribute](../../aspose.html.dom/element/setattribute/)(string, string) | Menambahkan atribut baru. Jika atribut dengan nama itu sudah ada di elemen, nilainya diubah menjadi nilai parameter |
| [SetAttributeNode](../../aspose.html.dom/element/setattributenode/)(Attr) | Menambahkan simpul atribut baru. Jika atribut dengan nama tersebut (nodeName) sudah ada di elemen, maka akan diganti dengan yang baru. |
| [SetAttributeNodeNS](../../aspose.html.dom/element/setattributenodens/)(Attr) | Menambahkan atribut baru. Jika atribut dengan nama lokal tersebut dan URI namespace tersebut sudah ada dalam elemen, maka akan diganti dengan yang baru. |
| [SetAttributeNS](../../aspose.html.dom/element/setattributens/)(string, string, string) | Menambahkan atribut baru. Jika atribut dengan nama lokal dan URI namespace yang sama sudah ada pada elemen, prefiksnya diubah menjadi bagian prefiks dari QualifiedName, dan nilainya diubah menjadi parameter value. |
| [SetIdAttribute](../../aspose.html.dom/element/setidattribute/)(string, bool) | Jika parameter isId benar, metode ini mendeklarasikan atribut yang ditentukan sebagai atribut ID yang ditentukan pengguna. |
| [SetIdAttributeNode](../../aspose.html.dom/element/setidattributenode/)(Attr, bool) | Jika parameter isId benar, metode ini mendeklarasikan atribut yang ditentukan sebagai atribut ID yang ditentukan pengguna. |
| [SetIdAttributeNS](../../aspose.html.dom/element/setidattributens/)(string, string, bool) | Jika parameter isId benar, metode ini mendeklarasikan atribut yang ditentukan sebagai atribut ID yang ditentukan pengguna. |
| override [ToString](../../aspose.html.dom/node/tostring/)() | Mengembalikan aString yang mewakili instance ini. |

### Lihat juga

* class [SVGGraphicsElement](../svggraphicselement/)
* ruang nama [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg/)
* perakitan [Aspose.HTML](../../)


