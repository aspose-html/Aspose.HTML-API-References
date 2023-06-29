---
title: Class HTMLInputElement
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.HTMLInputElement kelas. Kontrol formulir. Bergantung pada lingkungan di mana halaman sedang dilihat properti nilai mungkin bersifat hanyabaca untuk jenis masukan unggahan file . Untuk jenis input sandi nilai sebenarnya yang dikembalikan mungkin disamarkan untuk mencegah penggunaan yang tidak sah. Lihat definisi elemen INPUT di HTML4.01 .
type: docs
weight: 3320
url: /id/net/aspose.html/htmlinputelement/
---
## HTMLInputElement class

Kontrol formulir. Bergantung pada lingkungan di mana halaman sedang dilihat, properti nilai mungkin bersifat hanya-baca untuk jenis masukan unggahan file . Untuk jenis input "sandi", nilai sebenarnya yang dikembalikan mungkin disamarkan untuk mencegah penggunaan yang tidak sah. Lihat definisi elemen INPUT di [[HTML4.01](http://www.w3.org/TR/1999/REC-html401-19991224) ].

Lihat juga[Document object Model (DOM) Spesifikasi HTML Level 2](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109) .

```csharp
public class HTMLInputElement : HTMLElement
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Accept](../../aspose.html/htmlinputelement/accept/) { get; set; } | Daftar jenis konten yang dipisahkan koma yang akan ditangani dengan benar oleh server yang memproses formulir ini. Lihat definisi atribut terima di HTML 4.01. |
| [AccessKey](../../aspose.html/htmlinputelement/accesskey/) { get; set; } | Kunci akses karakter tunggal untuk memberikan akses ke kontrol formulir. Lihat definisi atribut accesskey di HTML 4.01. |
| [Align](../../aspose.html/htmlinputelement/align/) { get; set; } | Meratakan objek ini (vertikal atau horizontal) sehubungan dengan teks di sekitarnya. Lihat definisi atribut align di HTML 4.01. Atribut ini tidak digunakan lagi di HTML 4.01. |
| [Alt](../../aspose.html/htmlinputelement/alt/) { get; set; } | Teks alternatif untuk agen pengguna yang tidak merender konten normal elemen ini. Lihat definisi atribut alt di HTML 4.01. |
| override [Attributes](../../aspose.html.dom/element/attributes/) { get; } | NamedNodeMap yang berisi atribut node ini (jika itu adalah Elemen) atau null jika tidak. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri/) { get; } | URI dasar absolut dari node ini atau nol jika implementasi tidak dapat memperoleh URI absolut. |
| [Checked](../../aspose.html/htmlinputelement/checked/) { get; set; } | Ketika`jenis`atribut elemen memiliki nilai "radio" atau "kotak centang", ini mewakili kondisi saat ini dari bentuk kontrol , dalam agen pengguna interaktif. Perubahan pada atribut ini mengubah status kontrol formulir, tetapi tidak mengubah nilai atribut HTML yang diperiksa dari elemen INPUT. Selama penanganan peristiwa klik pada elemen input dengan atribut tipe yang memiliki nilai "radio" atau "kotak centang", beberapa implementasi dapat mengubah nilai properti ini sebelum acara dikirim dalam dokumen . Jika tindakan default acara dibatalkan, nilai properti dapat diubah kembali ke nilai aslinya. Ini berarti bahwa nilai properti ini selama penanganan peristiwa klik bergantung pada implementasi. |
| [ChildElementCount](../../aspose.html.dom/element/childelementcount/) { get; } | Mengembalikan jumlah node elemen saat ini yang merupakan turunan dari elemen ini. 0 jika elemen ini tidak memiliki node anak dengan nodeType 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | Sebuah NodeList yang berisi semua anak dari node ini. Jika tidak ada anak, ini adalah NodeList yang tidak berisi node.. |
| [Children](../../aspose.html.dom/element/children/) { get; } | Mengembalikan elemen turunan dari elemen saat ini. |
| [ClassList](../../aspose.html.dom/element/classlist/) { get; } | Mengembalikan DOMTokenList langsung yang berisi token yang diterima dari parsing atribut "class". |
| [ClassName](../../aspose.html/htmlelement/classname/) { get; set; } | Atribut kelas elemen. Atribut ini telah diganti namanya karena bertentangan dengan kata kunci "class" yang diekspos oleh banyak bahasa. Lihat definisi atribut kelas di HTML 4.01. |
| [DefaultChecked](../../aspose.html/htmlinputelement/defaultchecked/) { get; set; } | Kapan`jenis` memiliki nilai "radio" atau "kotak centang", ini mewakili atribut HTML elemen yang diperiksa. Nilai atribut ini tidak berubah jika status kontrol formulir yang sesuai, dalam agen pengguna interaktif, berubah. Lihat definisi atribut yang dicentang di HTML 4.01. |
| [DefaultValue](../../aspose.html/htmlinputelement/defaultvalue/) { get; set; } | Ketika`jenis`atribut elemen memiliki nilai "text", "file" atau "password", ini mewakili nilai HTML atribut elemen. Nilai atribut ini tidak berubah jika konten kontrol formulir yang sesuai, dalam agen pengguna interaktif, berubah. Lihat definisi atribut nilai dalam HTML 4.01. |
| [Dir](../../aspose.html/htmlelement/dir/) { get; set; } | Menentukan arah dasar teks netral arah dan arah tabel. Lihat definisi atribut dir dalam HTML 4.01. |
| [Disabled](../../aspose.html/htmlinputelement/disabled/) { get; set; } | Kontrol tidak tersedia dalam konteks ini. Lihat definisi atribut yang dinonaktifkan di HTML 4.01. |
| [Files](../../aspose.html/htmlinputelement/files/) { get; } | Atribut IDL file memungkinkan skrip untuk mengakses file elemen yang dipilih. Saat menerima, jika atribut IDL berlaku, ia harus mengembalikan objek FileList yang mewakili file yang dipilih saat ini. Objek yang sama harus dikembalikan hingga daftar file yang dipilih berubah. Jika atribut IDL tidak berlaku, maka atribut tersebut harus mengembalikan nol. [FILEAPI] |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | Anak pertama dari node ini. Jika tidak ada simpul seperti itu, ini mengembalikan null. |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild/) { get; } | Mengembalikan simpul elemen anak pertama dari elemen ini. null jika elemen ini tidak memiliki elemen turunan. |
| [Form](../../aspose.html/htmlinputelement/form/) { get; set; } | Mengembalikan`MEMBENTUK` elemen yang mengandung kontrol ini. Pengembalian `batal` jika kontrol ini tidak dalam konteks formulir . |
| [Id](../../aspose.html/htmlelement/id/) { get; set; } | Pengidentifikasi elemen. Lihat definisi atribut id di HTML 4.01. |
| [InnerHTML](../../aspose.html.dom/element/innerhtml/) { get; set; } | Mengembalikan fragmen HTML atau XML yang mewakili konten elemen. Dapat diatur, untuk mengganti konten elemen dengan node yang diuraikan dari string yang diberikan. |
| [Lang](../../aspose.html/htmlelement/lang/) { get; set; } | Kode bahasa didefinisikan dalam RFC 1766. Lihat definisi atribut lang di HTML 4.01. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | Anak terakhir dari node ini. Jika tidak ada simpul seperti itu, ini mengembalikan null. |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild/) { get; } | Mengembalikan simpul elemen anak terakhir dari elemen ini. null jika elemen ini tidak memiliki elemen turunan. |
| [List](../../aspose.html/htmlinputelement/list/) { get; set; } | Atribut daftar digunakan untuk mengidentifikasi elemen yang mencantumkan opsi yang telah ditentukan yang disarankan kepada pengguna. Jika ada, nilainya harus berupa ID elemen datalist dalam dokumen yang sama. |
| override [LocalName](../../aspose.html.dom/element/localname/) { get; } | Mengembalikan bagian lokal dari nama yang memenuhi syarat dari node ini. Untuk node jenis apa pun selain ELEMENT_NODE dan ATTRIBUTE_NODE dan node yang dibuat dengan metode DOM Level 1, seperti Document.createElement(), ini selalu null. |
| [MaxLength](../../aspose.html/htmlinputelement/maxlength/) { get; set; } | Jumlah maksimum karakter untuk bidang teks, saat`jenis` memiliki nilai "text" atau "password". Lihat definisi atribut maxlength di HTML 4.01. |
| [Name](../../aspose.html/htmlinputelement/name/) { get; set; } | Kontrol formulir atau nama objek saat dikirimkan dengan formulir. Lihat definisi atribut nama di HTML 4.01. |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri/) { get; } | Namespace URI node ini, atau null jika tidak ditentukan. |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling/) { get; } | Mengembalikan simpul elemen saudara berikutnya dari elemen ini. null jika elemen ini tidak memiliki simpul saudara elemen yang muncul setelah elemen ini di pohon dokumen. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | Simpul yang langsung mengikuti simpul ini. Jika tidak ada simpul seperti itu, ini mengembalikan null. |
| override [NodeName](../../aspose.html.dom/element/nodename/) { get; } | Nama node ini, tergantung jenisnya. |
| override [NodeType](../../aspose.html.dom/element/nodetype/) { get; } | Kode yang mewakili jenis objek yang mendasarinya. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | Nilai simpul ini, tergantung pada jenisnya. |
| [OuterHTML](../../aspose.html.dom/element/outerhtml/) { get; set; } | Mengembalikan fragmen HTML atau XML yang mewakili elemen dan isinya. Dapat diatur, untuk mengganti elemen dengan node yang diuraikan dari string yang diberikan. |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument/) { get; } | Objek Dokumen yang terkait dengan node ini. Ini juga merupakan objek Dokumen yang digunakan untuk membuat node baru. Ketika simpul ini adalah Dokumen atau Jenis Dokumen yang belum digunakan dengan Dokumen apa pun, ini adalah null. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Mendapatkan induknya[`Element`](../../aspose.html.dom/element/) dari simpul ini. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | Induk dari node ini. Semua node, kecuali Attr, Document, DocumentFragment, Entity, dan Notation mungkin memiliki induk. Namun, jika sebuah simpul baru saja dibuat dan belum ditambahkan ke pohon, atau jika telah dihapus dari pohon, ini adalah null. |
| override [Prefix](../../aspose.html.dom/element/prefix/) { get; } | Awalan namespace node ini, atau null jika tidak ditentukan. Ketika didefinisikan sebagai null, menyetelnya tidak berpengaruh |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling/) { get; } | Mengembalikan simpul elemen saudara sebelumnya dari elemen ini. null jika elemen ini tidak memiliki simpul saudara elemen yang datang sebelum elemen ini di pohon dokumen. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | Node tepat sebelum node ini. Jika tidak ada simpul seperti itu, ini mengembalikan null. |
| [ReadOnly](../../aspose.html/htmlinputelement/readonly/) { get; set; } | Kontrol ini hanya bisa dibaca. Relevan hanya bila`jenis` memiliki nilai "teks" atau "kata sandi". Lihat definisi atribut readonly di HTML 4.01. |
| [SchemaTypeInfo](../../aspose.html.dom/element/schematypeinfo/) { get; } | Jenis informasi yang terkait dengan elemen ini. |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot/) { get; } | Mengembalikan shadowRoot yang disimpan pada elemen ini atau null jika ditutup. |
| [Size](../../aspose.html/htmlinputelement/size/) { get; set; } | Informasi ukuran. Arti tepatnya khusus untuk setiap jenis bidang . Lihat definisi atribut ukuran di HTML 4.01. @version DOM Level 2 |
| [Src](../../aspose.html/htmlinputelement/src/) { get; set; } | Ketika`jenis`atribut memiliki nilai "gambar", atribut ini menentukan lokasi gambar yang akan digunakan untuk menghias tombol kirim grafis. Lihat definisi atribut src di HTML 4.01. |
| [Style](../../aspose.html/htmlelement/style/) { get; } | Mewakili atribut gaya yang memungkinkan penulis menerapkan informasi gaya secara langsung ke elemen tertentu. |
| [TabIndex](../../aspose.html/htmlinputelement/tabindex/) { get; set; } | Indeks yang mewakili posisi elemen dalam urutan tab. Lihat definisi atribut tabindex di HTML 4.01. |
| [TagName](../../aspose.html.dom/element/tagname/) { get; } | Nama elemen. |
| override [TextContent](../../aspose.html.dom/element/textcontent/) { get; set; } | Atribut ini mengembalikan konten teks dari node ini dan turunannya. Ketika didefinisikan sebagai nol, pengaturan itu tidak berpengaruh. Pada pengaturan, setiap anak yang mungkin dimiliki simpul ini dihapus dan, jika string baru tidak kosong atau nol, diganti dengan simpul Teks tunggal yang berisi string yang disetel ke atribut ini. |
| [Title](../../aspose.html/htmlelement/title/) { get; set; } | Judul penasehat elemen. Lihat definisi atribut judul di HTML 4.01. |
| [Type](../../aspose.html/htmlinputelement/type/) { get; set; } | Jenis kontrol dibuat (semua huruf kecil). Lihat definisi atribut tipe di HTML 4.01. @versi DOM Tingkat 2 |
| [UseMap](../../aspose.html/htmlinputelement/usemap/) { get; set; } | Gunakan peta gambar sisi klien. Lihat definisi atribut usemap di HTML 4.01. |
| [Value](../../aspose.html/htmlinputelement/value/) { get; set; } | Ketika`jenis` atribut elemen memiliki nilai "teks", "file" atau "kata sandi", ini mewakili konten saat ini dari kontrol formulir yang sesuai, dalam agen pengguna interaktif. Mengubah atribut ini mengubah konten kontrol formulir, tetapi tidak mengubah nilai atribut nilai HTML dari elemen tersebut. Ketika`jenis`atribut elemen memiliki nilai "tombol", "tersembunyi", "kirim", "reset", "gambar", "kotak centang" atau "radio", ini mewakili atribut nilai HTML dari elemen tersebut. Lihat definisi atribut nilai dalam HTML 4.01. |

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
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname/)(string) | Mengembalikan objek NodeList langsung yang berisi semua elemen dalam dokumen yang memiliki semua kelas yang ditentukan dalam argumen. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname/)(string) | Mengembalikan NodeList dari semua Elemen turunan dengan nama tag tertentu, dalam urutan dokumen. |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens/)(string, string) | Mengembalikan NodeList dari semua Elemen turunan dengan nama lokal dan namespace URI yang diberikan dalam urutan dokumen. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScriptType . |
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

## Acara

| Nama | Keterangan |
| --- | --- |
| event [OnAbort](../../aspose.html/htmlelement/onabort/) | Mendapat atau mengatur event handler untuk event OnAbort. |
| event [OnBlur](../../aspose.html/htmlelement/onblur/) | Mendapat atau mengatur event handler untuk event OnBlur. |
| event [OnCancel](../../aspose.html/htmlelement/oncancel/) | Mendapat atau mengatur event handler untuk event OnCancel. |
| event [OnCanplay](../../aspose.html/htmlelement/oncanplay/) | Mendapat atau mengatur event handler untuk event OnCanplay. |
| event [OnCanPlayThrough](../../aspose.html/htmlelement/oncanplaythrough/) | Mendapat atau menyetel event handler untuk event OnCanPlayThrough. |
| event [OnChange](../../aspose.html/htmlelement/onchange/) | Mendapat atau mengatur event handler untuk event OnChange. |
| event [OnClick](../../aspose.html/htmlelement/onclick/) | Mendapat atau mengatur event handler untuk event OnClick. |
| event [OnCueChange](../../aspose.html/htmlelement/oncuechange/) | Mendapat atau mengatur event handler untuk event OnCueChange. |
| event [OnDblClick](../../aspose.html/htmlelement/ondblclick/) | Mendapat atau mengatur event handler untuk event OnDblClick. |
| event [OnDurationChange](../../aspose.html/htmlelement/ondurationchange/) | Mendapat atau mengatur event handler untuk event OnDurationChange. |
| event [OnEmptied](../../aspose.html/htmlelement/onemptied/) | Mendapat atau mengatur event handler untuk event OnEmptied. |
| event [OnEnded](../../aspose.html/htmlelement/onended/) | Mendapat atau menyetel event handler untuk event OnEnded. |
| event [OnError](../../aspose.html/htmlelement/onerror/) | Mendapat atau mengatur event handler untuk event OnError. |
| event [OnFocus](../../aspose.html/htmlelement/onfocus/) | Mendapat atau menyetel event handler untuk event OnFocus. |
| event [OnInput](../../aspose.html/htmlelement/oninput/) | Mendapat atau mengatur event handler untuk event OnInput. |
| event [OnInvalid](../../aspose.html/htmlelement/oninvalid/) | Mendapat atau mengatur event handler untuk event OnInvalid. |
| event [OnKeyDown](../../aspose.html/htmlelement/onkeydown/) | Mendapat atau mengatur event handler untuk event OnKeyDown. |
| event [OnKeyPress](../../aspose.html/htmlelement/onkeypress/) | Mendapat atau mengatur event handler untuk event OnKeyPress. |
| event [OnKeyUp](../../aspose.html/htmlelement/onkeyup/) | Mendapat atau mengatur event handler untuk event OnKeyUp. |
| event [OnLoad](../../aspose.html/htmlelement/onload/) | Mendapat atau mengatur event handler untuk event OnLoad. |
| event [OnLoadedData](../../aspose.html/htmlelement/onloadeddata/) | Mendapat atau mengatur event handler untuk event OnLoadedData. |
| event [OnLoadedMetadata](../../aspose.html/htmlelement/onloadedmetadata/) | Mendapat atau mengatur event handler untuk event OnLoadedMetadata. |
| event [OnLoadStart](../../aspose.html/htmlelement/onloadstart/) | Mendapat atau mengatur event handler untuk event OnLoadStart. |
| event [OnMouseDown](../../aspose.html/htmlelement/onmousedown/) | Mendapat atau mengatur event handler untuk event OnMouseDown. |
| event [OnMouseEnter](../../aspose.html/htmlelement/onmouseenter/) | Mendapat atau mengatur event handler untuk event OnMouseEnter. |
| event [OnMouseLeave](../../aspose.html/htmlelement/onmouseleave/) | Mendapat atau mengatur event handler untuk event OnMouseLeave. |
| event [OnMouseMove](../../aspose.html/htmlelement/onmousemove/) | Mendapat atau mengatur event handler untuk event OnMouseMove. |
| event [OnMouseOut](../../aspose.html/htmlelement/onmouseout/) | Mendapat atau mengatur event handler untuk event OnMouseOut. |
| event [OnMouseOver](../../aspose.html/htmlelement/onmouseover/) | Mendapat atau mengatur event handler untuk event OnMouseOver. |
| event [OnMouseUp](../../aspose.html/htmlelement/onmouseup/) | Mendapat atau mengatur event handler untuk event OnMouseUp. |
| event [OnMouseWheel](../../aspose.html/htmlelement/onmousewheel/) | Mendapat atau mengatur event handler untuk event OnMouseWheel. |
| event [OnPause](../../aspose.html/htmlelement/onpause/) | Mendapat atau menyetel event handler untuk event OnPause. |
| event [OnPlay](../../aspose.html/htmlelement/onplay/) | Mendapat atau menyetel event handler untuk event OnPlay. |
| event [OnPlaying](../../aspose.html/htmlelement/onplaying/) | Mendapat atau menyetel event handler untuk event OnPlaying. |
| event [OnProgress](../../aspose.html/htmlelement/onprogress/) | Mendapat atau mengatur event handler untuk event OnProgress. |
| event [OnRateChange](../../aspose.html/htmlelement/onratechange/) | Mendapat atau mengatur event handler untuk event OnRateChange. |
| event [OnReset](../../aspose.html/htmlelement/onreset/) | Mendapat atau mengatur event handler untuk event OnReset. |
| event [OnResize](../../aspose.html/htmlelement/onresize/) | Mendapat atau mengatur event handler untuk event OnResize. |
| event [OnScroll](../../aspose.html/htmlelement/onscroll/) | Mendapat atau mengatur event handler untuk event OnScroll. |
| event [OnSeeked](../../aspose.html/htmlelement/onseeked/) | Mendapat atau mengatur event handler untuk event OnSeeked. |
| event [OnSeeking](../../aspose.html/htmlelement/onseeking/) | Mendapat atau mengatur event handler untuk event OnSeeking. |
| event [OnSelect](../../aspose.html/htmlelement/onselect/) | Mendapat atau mengatur event handler untuk event OnSelect. |
| event [OnShow](../../aspose.html/htmlelement/onshow/) | Mendapat atau mengatur event handler untuk event OnShow. |
| event [OnStalled](../../aspose.html/htmlelement/onstalled/) | Mendapat atau mengatur event handler untuk event OnStalled. |
| event [OnSubmit](../../aspose.html/htmlelement/onsubmit/) | Mendapat atau mengatur event handler untuk event OnSubmit. |
| event [OnSuspend](../../aspose.html/htmlelement/onsuspend/) | Mendapat atau menyetel event handler untuk event OnSuspend. |
| event [OnTimeUpdate](../../aspose.html/htmlelement/ontimeupdate/) | Mendapat atau mengatur event handler untuk event OnTimeUpdate. |
| event [OnToggle](../../aspose.html/htmlelement/ontoggle/) | Mendapat atau menyetel event handler untuk event OnToggle. |
| event [OnVolumeChange](../../aspose.html/htmlelement/onvolumechange/) | Mendapat atau mengatur event handler untuk event OnVolumeChange. |
| event [OnWaiting](../../aspose.html/htmlelement/onwaiting/) | Mendapat atau menyetel event handler untuk event OnWaiting. |

### Lihat juga

* class [HTMLElement](../htmlelement/)
* ruang nama [Aspose.Html](../../aspose.html/)
* perakitan [Aspose.HTML](../../)

