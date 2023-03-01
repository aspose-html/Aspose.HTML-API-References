---
title: Class SVGDocument
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Svg.SVGDocument kelas. AnDokumen SVGadalah akar dari hierarki SVG dan menampung seluruh konten. Selain menyediakan akses ke hierarki ini juga menyediakan beberapa metode kemudahan untuk mengakses kumpulan informasi tertentu dari dokumen. Saat elemen svg disematkan sebaris sebagai komponen dokumen dari namespace lain seperti saat svg elemen disematkan sebaris dalam dokumen XHTML XHTML maka objek SVGDocument tidak akan ada sebagai gantinya objek root dalam hierarki objek dokumen akan menjadi objek Dokumen dari jenis yang berbeda seperti objek HTMLDocument. Namun objek SVGDocument memang akan ada jika elemen root dari hierarki dokumen XML adalah elemen svg  seperti saat melihat file SVG yang berdiri sendiri yaitu file dengan tipe MIME image/svgxml. Dalam hal ini objek SVGDocument akan menjadi objek root dari hierarki model objek dokumen.
type: docs
weight: 2010
url: /id/net/aspose.html.dom.svg/svgdocument/
---
## SVGDocument class

An`Dokumen SVG`adalah akar dari hierarki SVG dan menampung seluruh konten. Selain menyediakan akses ke hierarki, ini juga menyediakan beberapa metode kemudahan untuk mengakses kumpulan informasi tertentu dari dokumen. Saat elemen 'svg' disematkan sebaris sebagai komponen dokumen dari namespace lain, seperti saat 'svg' elemen disematkan sebaris dalam dokumen XHTML [XHTML], maka objek SVGDocument tidak akan ada; sebagai gantinya, objek root dalam hierarki objek dokumen akan menjadi objek Dokumen dari jenis yang berbeda, seperti objek HTMLDocument. Namun, objek SVGDocument memang akan ada jika elemen root dari hierarki dokumen XML adalah elemen 'svg' , seperti saat melihat file SVG yang berdiri sendiri (yaitu, file dengan tipe MIME "image/svg+xml"). Dalam hal ini, objek SVGDocument akan menjadi objek root dari hierarki model objek dokumen.

```csharp
public class SVGDocument : Document, IDocumentCSS
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [SVGDocument](svgdocument/#constructor)() | Menginisialisasi instance baru dari`SVGDocument` kelas. |
| [SVGDocument](svgdocument/#constructor_1)(Configuration) | Menginisialisasi instance baru dari`SVGDocument` kelas. |
| [SVGDocument](svgdocument/#constructor_2)(RequestMessage) | Menginisialisasi instance baru dari`SVGDocument` kelas. Konstruktor bekerja secara sinkron, menunggu pemuatan semua sumber daya eksternal (gambar, skrip, dll.). Untuk memuat dokumen secara asinkron, gunakan metode[`Navigate`](../../aspose.html.dom/document/navigate/) atau kelebihannya. Atau Anda dapat menonaktifkan pemuatan beberapa sumber daya eksternal dengan menyetel bendera yang sesuai[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_10)(string) | Menginisialisasi instance baru dari`SVGDocument` kelas. Konstruktor bekerja secara sinkron, menunggu pemuatan semua sumber daya eksternal (gambar, skrip, dll.). Untuk memuat dokumen secara asinkron, gunakan metode[`Navigate`](../../aspose.html.dom/document/navigate/) atau kelebihannya. Atau Anda dapat menonaktifkan pemuatan beberapa sumber daya eksternal dengan menyetel bendera yang sesuai[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_4)(Url) | Menginisialisasi instance baru dari`SVGDocument` kelas. Konstruktor bekerja secara sinkron, menunggu pemuatan semua sumber daya eksternal (gambar, skrip, dll.). Untuk memuat dokumen secara asinkron, gunakan metode[`Navigate`](../../aspose.html.dom/document/navigate/) atau kelebihannya. Atau Anda dapat menonaktifkan pemuatan beberapa sumber daya eksternal dengan menyetel bendera yang sesuai[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_3)(RequestMessage, Configuration) | Menginisialisasi instance baru dari`SVGDocument` kelas. Konstruktor bekerja secara sinkron, menunggu pemuatan semua sumber daya eksternal (gambar, skrip, dll.). Untuk memuat dokumen secara asinkron, gunakan metode[`Navigate`](../../aspose.html.dom/document/navigate/) atau kelebihannya. Atau Anda dapat menonaktifkan pemuatan beberapa sumber daya eksternal dengan menyetel bendera yang sesuai[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_8)(Stream, string) | Menginisialisasi instance baru dari`SVGDocument` kelas. Konstruktor bekerja secara sinkron, menunggu pemuatan semua sumber daya eksternal (gambar, skrip, dll.). Untuk memuat dokumen secara asinkron, gunakan metode[`Navigate`](../../aspose.html.dom/document/navigate/) atau kelebihannya. Atau Anda dapat menonaktifkan pemuatan beberapa sumber daya eksternal dengan menyetel bendera yang sesuai[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Pemuatan dokumen dimulai dari posisi arus saat ini. |
| [SVGDocument](svgdocument/#constructor_6)(Stream, Url) | Menginisialisasi instance baru dari`SVGDocument` kelas. Konstruktor bekerja secara sinkron, menunggu pemuatan semua sumber daya eksternal (gambar, skrip, dll.). Untuk memuat dokumen secara asinkron, gunakan metode[`Navigate`](../../aspose.html.dom/document/navigate/) atau kelebihannya. Atau Anda dapat menonaktifkan pemuatan beberapa sumber daya eksternal dengan menyetel bendera yang sesuai[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Pemuatan dokumen dimulai dari posisi arus saat ini. |
| [SVGDocument](svgdocument/#constructor_11)(string, Configuration) | Menginisialisasi instance baru dari`SVGDocument` kelas. Konstruktor bekerja secara sinkron, menunggu pemuatan semua sumber daya eksternal (gambar, skrip, dll.). Untuk memuat dokumen secara asinkron, gunakan metode[`Navigate`](../../aspose.html.dom/document/navigate/) atau kelebihannya. Atau Anda dapat menonaktifkan pemuatan beberapa sumber daya eksternal dengan menyetel bendera yang sesuai[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_14)(string, string) | Menginisialisasi instance baru dari`SVGDocument` kelas. Konstruktor bekerja secara sinkron, menunggu pemuatan semua sumber daya eksternal (gambar, skrip, dll.). Untuk memuat dokumen secara asinkron, gunakan metode[`Navigate`](../../aspose.html.dom/document/navigate/) atau kelebihannya. Atau Anda dapat menonaktifkan pemuatan beberapa sumber daya eksternal dengan menyetel bendera yang sesuai[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_12)(string, Url) | Menginisialisasi instance baru dari`SVGDocument` kelas. Konstruktor bekerja secara sinkron, menunggu pemuatan semua sumber daya eksternal (gambar, skrip, dll.). Untuk memuat dokumen secara asinkron, gunakan metode[`Navigate`](../../aspose.html.dom/document/navigate/) atau kelebihannya. Atau Anda dapat menonaktifkan pemuatan beberapa sumber daya eksternal dengan menyetel bendera yang sesuai[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_5)(Url, Configuration) | Menginisialisasi instance baru dari`SVGDocument` kelas. Konstruktor bekerja secara sinkron, menunggu pemuatan semua sumber daya eksternal (gambar, skrip, dll.). Untuk memuat dokumen secara asinkron, gunakan metode[`Navigate`](../../aspose.html.dom/document/navigate/) atau kelebihannya. Atau Anda dapat menonaktifkan pemuatan beberapa sumber daya eksternal dengan menyetel bendera yang sesuai[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_9)(Stream, string, Configuration) | Menginisialisasi instance baru dari`SVGDocument` kelas. Konstruktor bekerja secara sinkron, menunggu pemuatan semua sumber daya eksternal (gambar, skrip, dll.). Untuk memuat dokumen secara asinkron, gunakan metode[`Navigate`](../../aspose.html.dom/document/navigate/) atau kelebihannya. Atau Anda dapat menonaktifkan pemuatan beberapa sumber daya eksternal dengan menyetel bendera yang sesuai[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Pemuatan dokumen dimulai dari posisi arus saat ini. |
| [SVGDocument](svgdocument/#constructor_7)(Stream, Url, Configuration) | Menginisialisasi instance baru dari`SVGDocument` kelas. Konstruktor bekerja secara sinkron, menunggu pemuatan semua sumber daya eksternal (gambar, skrip, dll.). Untuk memuat dokumen secara asinkron, gunakan metode[`Navigate`](../../aspose.html.dom/document/navigate/) atau kelebihannya. Atau Anda dapat menonaktifkan pemuatan beberapa sumber daya eksternal dengan menyetel bendera yang sesuai[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . Pemuatan dokumen dimulai dari posisi arus saat ini. |
| [SVGDocument](svgdocument/#constructor_15)(string, string, Configuration) | Menginisialisasi instance baru dari`SVGDocument` kelas. Konstruktor bekerja secara sinkron, menunggu pemuatan semua sumber daya eksternal (gambar, skrip, dll.). Untuk memuat dokumen secara asinkron, gunakan metode[`Navigate`](../../aspose.html.dom/document/navigate/) atau kelebihannya. Atau Anda dapat menonaktifkan pemuatan beberapa sumber daya eksternal dengan menyetel bendera yang sesuai[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [SVGDocument](svgdocument/#constructor_13)(string, Url, Configuration) | Menginisialisasi instance baru dari`SVGDocument` kelas. Konstruktor bekerja secara sinkron, menunggu pemuatan semua sumber daya eksternal (gambar, skrip, dll.). Untuk memuat dokumen secara asinkron, gunakan metode[`Navigate`](../../aspose.html.dom/document/navigate/) atau kelebihannya. Atau Anda dapat menonaktifkan pemuatan beberapa sumber daya eksternal dengan menyetel bendera yang sesuai[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |

## Properti

| Nama | Keterangan |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes/) { get; } | NamedNodeMap yang berisi atribut node ini (jika itu adalah Elemen) atau null jika tidak. |
| override [BaseURI](../../aspose.html.dom/document/baseuri/) { get; } | URI dasar absolut dari node ini atau null jika implementasi tidak dapat memperoleh URI absolut. |
| [CharacterSet](../../aspose.html.dom/document/characterset/) { get; } | Mendapatkan penyandian dokumen. |
| [Charset](../../aspose.html.dom/document/charset/) { get; } | Mendapatkan penyandian dokumen. |
| [ChildElementCount](../../aspose.html.dom/document/childelementcount/) { get; } | Mengembalikan jumlah node elemen saat ini yang merupakan turunan dari elemen ini. 0 jika elemen ini tidak memiliki node anak dengan nodeType 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | Sebuah NodeList yang berisi semua anak dari node ini. Jika tidak ada anak, ini adalah NodeList yang tidak berisi node.. |
| [Children](../../aspose.html.dom/document/children/) { get; } | Mengembalikan elemen turunan. |
| [ContentType](../../aspose.html.dom/document/contenttype/) { get; } | Mendapatkan jenis konten dokumen. |
| [Context](../../aspose.html.dom/document/context/) { get; } | Mendapat konteks penelusuran saat ini. |
| [DefaultView](../../aspose.html.dom/document/defaultview/) { get; } | Atribut defaultView IDL dari antarmuka Dokumen, saat mendapatkan, harus mengembalikan objek WindowProxy konteks penelusuran Dokumen ini, jika Dokumen ini memiliki konteks penelusuran terkait, atau null sebaliknya. |
| [Doctype](../../aspose.html.dom/document/doctype/) { get; } | Deklarasi Jenis Dokumen yang terkait dengan dokumen ini. |
| [DocumentElement](../../aspose.html.dom/document/documentelement/) { get; } | Ini adalah atribut kemudahan yang memungkinkan akses langsung ke simpul anak yang merupakan elemen dokumen dari dokumen. |
| [DocumentURI](../../aspose.html.dom/document/documenturi/) { get; } | Lokasi dokumen atau null jika tidak ditentukan atau jika Dokumen dibuat menggunakan DOMImplementation.createDocument. |
| [Domain](../../aspose.html.dom.svg/svgdocument/domain/) { get; } | Nama domain dari server yang menyajikan dokumen, atau string nol jika server tidak dapat diidentifikasi dengan nama domain. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | Anak pertama dari node ini. Jika tidak ada simpul seperti itu, ini mengembalikan null. |
| [FirstElementChild](../../aspose.html.dom/document/firstelementchild/) { get; } | Mengembalikan simpul elemen anak pertama dari elemen ini. null jika elemen ini tidak memiliki elemen turunan. |
| [Implementation](../../aspose.html.dom/document/implementation/) { get; } | Objek DOMImplementation yang menangani dokumen ini. |
| [InputEncoding](../../aspose.html.dom/document/inputencoding/) { get; } | Mendapatkan penyandian dokumen. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | Anak terakhir dari node ini. Jika tidak ada simpul seperti itu, ini mengembalikan null. |
| [LastElementChild](../../aspose.html.dom/document/lastelementchild/) { get; } | Mengembalikan simpul elemen anak terakhir dari elemen ini. null jika elemen ini tidak memiliki elemen turunan. |
| virtual [LocalName](../../aspose.html.dom/node/localname/) { get; } | Mengembalikan bagian lokal dari nama yang memenuhi syarat dari node ini. Untuk node jenis apa pun selain ELEMENT_NODE dan ATTRIBUTE_NODE dan node yang dibuat dengan metode DOM Level 1, seperti Document.createElement(), ini selalu null. |
| [Location](../../aspose.html.dom/document/location/) { get; } | Lokasi dokumen. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri/) { get; } | Namespace URI node ini, atau null jika tidak ditentukan. |
| [NextElementSibling](../../aspose.html.dom/document/nextelementsibling/) { get; } | Mengembalikan simpul elemen saudara berikutnya dari elemen ini. null jika elemen ini tidak memiliki simpul saudara elemen yang muncul setelah elemen ini di pohon dokumen. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | Simpul yang langsung mengikuti simpul ini. Jika tidak ada simpul seperti itu, ini mengembalikan null. |
| override [NodeName](../../aspose.html.dom/document/nodename/) { get; } | Nama node ini, tergantung jenisnya. |
| override [NodeType](../../aspose.html.dom/document/nodetype/) { get; } | Kode yang mewakili jenis objek yang mendasarinya. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | Nilai simpul ini, tergantung pada jenisnya. |
| [Origin](../../aspose.html.dom/document/origin/) { get; } | Mendapatkan asal dokumen. |
| override [OwnerDocument](../../aspose.html.dom/document/ownerdocument/) { get; } | Mendapatkan dokumen pemilik. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Mendapatkan induknya[`Element`](../../aspose.html.dom/element/) dari simpul ini. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | Induk dari node ini. Semua node, kecuali Attr, Document, DocumentFragment, Entity, dan Notation mungkin memiliki induk. Namun, jika sebuah simpul baru saja dibuat dan belum ditambahkan ke pohon, atau jika telah dihapus dari pohon, ini adalah null. |
| virtual [Prefix](../../aspose.html.dom/node/prefix/) { get; set; } | Awalan namespace node ini, atau null jika tidak ditentukan. Ketika didefinisikan sebagai null, menyetelnya tidak berpengaruh |
| [PreviousElementSibling](../../aspose.html.dom/document/previouselementsibling/) { get; } | Mengembalikan simpul elemen saudara sebelumnya dari elemen ini. null jika elemen ini tidak memiliki simpul saudara elemen yang datang sebelum elemen ini di pohon dokumen. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | Node tepat sebelum node ini. Jika tidak ada simpul seperti itu, ini mengembalikan null. |
| [ReadyState](../../aspose.html.dom/document/readystate/) { get; } | Mengembalikan kesiapan dokumen. "Memuat" saat Dokumen sedang dimuat, "interaktif" setelah selesai menguraikan tetapi masih memuat sub-sumber daya, dan "menyelesaikan" setelah dimuat. |
| [Referrer](../../aspose.html.dom.svg/svgdocument/referrer/) { get; } | Mengembalikan URI halaman yang ditautkan ke halaman ini. Nilainya berupa string kosong jika pengguna membuka halaman secara langsung (tidak melalui tautan, tetapi, misalnya, melalui bookmark). |
| [RootElement](../../aspose.html.dom.svg/svgdocument/rootelement/) { get; } | Akar 'svg' dalam hierarki dokumen. |
| [StrictErrorChecking](../../aspose.html.dom/document/stricterrorchecking/) { get; set; } | Atribut yang menentukan apakah pemeriksaan kesalahan diterapkan atau tidak. Jika disetel ke false, implementasi bebas untuk tidak menguji setiap kemungkinan kasus kesalahan yang biasanya didefinisikan pada operasi DOM, dan tidak memunculkan DOMException apa pun pada operasi DOM atau melaporkan kesalahan saat menggunakan Document.normalizeDocument(). Jika terjadi kesalahan, perilaku tidak ditentukan. Atribut ini benar secara default. |
| [StyleSheets](../../aspose.html.dom/document/stylesheets/) { get; } | Daftar yang berisi semua style sheet yang secara eksplisit ditautkan atau disematkan dalam dokumen. Untuk dokumen HTML, ini termasuk lembar gaya eksternal, disertakan melalui elemen HTML LINK, dan elemen STYLE inline. |
| virtual [TextContent](../../aspose.html.dom/node/textcontent/) { get; set; } | Atribut ini mengembalikan konten teks dari node ini dan turunannya. Ketika didefinisikan sebagai nol, pengaturan itu tidak berpengaruh. Pada pengaturan, setiap anak yang mungkin dimiliki simpul ini dihapus dan, jika string baru tidak kosong atau nol, diganti dengan simpul Teks tunggal yang berisi string yang disetel ke atribut ini. |
| [Title](../../aspose.html.dom.svg/svgdocument/title/) { get; } | Judul dokumen seperti yang ditentukan oleh sub-elemen 'judul' dari elemen root 'svg' (yaitu,Ini judulnya... ) |
| [URL](../../aspose.html.dom.svg/svgdocument/url/) { get; } | URI lengkap dokumen. |
| [XmlStandalone](../../aspose.html.dom/document/xmlstandalone/) { get; set; } | Sebuah atribut yang menentukan, sebagai bagian dari deklarasi XML, apakah dokumen ini berdiri sendiri. Ini salah jika tidak ditentukan. |
| [XmlVersion](../../aspose.html.dom/document/xmlversion/) { get; set; } | Atribut yang menentukan, sebagai bagian dari deklarasi XML, nomor versi dokumen ini. Jika tidak ada deklarasi dan jika dokumen ini mendukung fitur "XML", nilainya adalah "1.0". Jika dokumen ini tidak mendukung fitur "XML", nilainya selalu null. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | Metode ini memungkinkan pendaftaran event listener pada target event. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | Metode ini memungkinkan pendaftaran event listener pada target event. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | Metode ini memungkinkan pendaftaran event listener pada target event. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | Menambahkan node newChild ke akhir daftar anak dari node ini. Jika newChild sudah ada di pohon, pertama dihapus. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | Mengembalikan duplikat dari node ini, misalnya berfungsi sebagai pembuat salinan umum untuk node. Node duplikat tidak memiliki induk (parentNode adalah null) dan tidak ada data pengguna. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | Mengembalikan duplikat dari node ini, misalnya berfungsi sebagai pembuat salinan umum untuk node. Node duplikat tidak memiliki induk (parentNode adalah null) dan tidak ada data pengguna. |
| [CreateAttribute](../../aspose.html.dom/document/createattribute/)(string) | Membuat Attr dari nama yang diberikan. |
| [CreateAttributeNS](../../aspose.html.dom/document/createattributens/)(string, string) | Membuat atribut dari URI namespace dan namespace yang memenuhi syarat. |
| [CreateCDATASection](../../aspose.html.dom/document/createcdatasection/)(string) | Membuat node CDATASection yang nilainya adalah string yang ditentukan. |
| [CreateComment](../../aspose.html.dom/document/createcomment/)(string) | Membuat simpul Komentar dengan string yang ditentukan. |
| [CreateDocumentFragment](../../aspose.html.dom/document/createdocumentfragment/)() | Membuat objek DocumentFragment kosong. |
| [CreateDocumentType](../../aspose.html.dom/document/createdocumenttype/)(string, string, string, string) | Membuat simpul DocumentType. |
| [CreateElement](../../aspose.html.dom/document/createelement/)(string) | Membuat elemen dari tipe yang ditentukan. Perhatikan bahwa instance yang dikembalikan mengimplementasikan antarmuka Elemen, sehingga atribut dapat ditentukan langsung pada objek yang dikembalikan. |
| [CreateElementNS](../../aspose.html.dom/document/createelementns/)(string, string) | Membuat elemen dari URI namespace dan namespace yang memenuhi syarat. |
| [CreateEntityReference](../../aspose.html.dom/document/createentityreference/)(string) | Membuat objek EntityReference. Selain itu, jika entitas yang direferensikan diketahui, daftar anak dari node EntityReference dibuat sama dengan node Entity yang sesuai. |
| [CreateEvent](../../aspose.html.dom/document/createevent/)(string) | Membuat sebuah[`Event`](../../aspose.html.dom.events/event/) dari jenis yang didukung oleh implementasi. |
| [CreateExpression](../../aspose.html.dom/document/createexpression/)(string, IXPathNSResolver) | Membuat ekspresi XPath yang diurai dengan ruang nama yang diselesaikan. Ini berguna saat ekspresi akan digunakan kembali dalam aplikasi karena memungkinkan untuk mengompilasi string ekspresi ke dalam bentuk internal yang lebih efisien dan melakukan preresolve semua prefiks namespace yang terjadi di dalam ekspresi. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node) | Buat NodeIterator baru di atas subtree yang di-root pada node yang ditentukan. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node, long) | Buat NodeIterator baru di atas subtree yang di-root pada node yang ditentukan. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node, long, INodeFilter) | Buat NodeIterator baru di atas subtree yang di-root pada node yang ditentukan. |
| [CreateNSResolver](../../aspose.html.dom/document/creatensresolver/)(Node) | Menyesuaikan node DOM apa pun untuk menyelesaikan ruang nama sehingga ekspresi XPath dapat dengan mudah dievaluasi relatif terhadap konteks node tempat ekspresi tersebut muncul di dalam dokumen. Adaptor ini berfungsi seperti metode DOM Level 3`lookupNamespaceURI` pada node dalam menyelesaikan namespaceURI dari awalan yang diberikan menggunakan informasi terkini yang tersedia dalam hierarki node pada saat lookupNamespaceURI dipanggil, juga menyelesaikan dengan benar awalan xml implisit. |
| [CreateProcessingInstruction](../../aspose.html.dom/document/createprocessinginstruction/)(string, string) | Membuat node ProcessingInstruction dengan nama dan string data yang ditentukan. |
| [CreateTextNode](../../aspose.html.dom/document/createtextnode/)(string) | Membuat simpul Teks dengan string yang ditentukan. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node) | Buat TreeWalker baru di atas subtree yang di-root di node yang ditentukan. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node, long) | Buat TreeWalker baru di atas subtree yang di-root di node yang ditentukan. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node, long, INodeFilter) | Buat TreeWalker baru di atas subtree yang di-root di node yang ditentukan. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Metode ini memungkinkan pengiriman event ke dalam model event implementasi. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Melakukan tugas yang ditentukan aplikasi terkait dengan membebaskan, melepaskan, atau menyetel ulang sumber daya yang tidak dikelola. |
| [Evaluate](../../aspose.html.dom/document/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | Mengevaluasi string ekspresi XPath dan mengembalikan hasil dari tipe yang ditentukan jika memungkinkan. |
| [GetElementById](../../aspose.html.dom/document/getelementbyid/)(string) | Mengembalikan Elemen yang memiliki atribut ID dengan nilai yang diberikan. Jika tidak ada elemen seperti itu, ini mengembalikan nol. Jika lebih dari satu elemen memiliki atribut ID dengan nilai tersebut, yang dikembalikan adalah undefined. |
| [GetElementsByClassName](../../aspose.html.dom/document/getelementsbyclassname/)(string) | Mengembalikan objek NodeList langsung yang berisi semua elemen dalam dokumen yang memiliki semua kelas yang ditentukan dalam argumen. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/document/getelementsbytagname/)(string) | Mengembalikan NodeList dari semua Elemen dalam urutan dokumen dengan nama tag yang diberikan dan dimuat dalam dokumen. |
| [GetElementsByTagNameNS](../../aspose.html.dom/document/getelementsbytagnamens/)(string, string) | Mengembalikan NodeList dari semua Elemen dengan nama lokal tertentu dan URI namespace dalam urutan dokumen. |
| [GetOverrideStyle](../../aspose.html.dom.svg/svgdocument/getoverridestyle/)(Element, string) | Metode ini digunakan untuk mengambil deklarasi gaya override untuk elemen tertentu dan elemen semu tertentu. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScriptType . |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes/)() | Mengembalikan apakah simpul ini (jika berupa elemen) memiliki atribut apapun |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | Mengembalikan apakah simpul ini memiliki turunan. |
| [ImportNode](../../aspose.html.dom/document/importnode/)(Node, bool) | Mengimpor node dari dokumen lain ke dokumen ini, tanpa mengubah atau menghapus node sumber dari dokumen asli; metode ini membuat salinan baru dari node sumber. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | Menyisipkan simpul sebelum anak simpul anak yang ada. Jika anak adalah null, sisipkan simpul di akhir daftar anak. Jika anak adalah objek DocumentFragment, semua anak disisipkan, dalam urutan yang sama, sebelum anak. Jika anak sudah ada di pohon, pertama-tama dihapus. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | Metode ini memeriksa apakah namespaceURI yang ditentukan adalah namespace default atau tidak. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | Menguji apakah dua node sama. Metode ini menguji kesamaan node, bukan kesamaan (yakni, apakah kedua node merujuk ke objek yang sama) yang dapat diuji dengan Node.isSameNode(). Semua node yang sama juga akan sama, meskipun kebalikannya mungkin tidak benar. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | Mengembalikan apakah node ini adalah node yang sama dengan yang diberikan. Metode ini menyediakan cara untuk menentukan apakah dua referensi Node dikembalikan oleh implementasi referensi objek yang sama. Ketika dua referensi Node adalah referensi ke objek yang sama, bahkan jika melalui proxy, referensi dapat digunakan sepenuhnya secara bergantian, sehingga semua atribut memiliki nilai yang sama dan memanggil metode DOM yang sama pada salah satu referensi selalu memiliki efek yang persis sama. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | Cari URI namespace yang terkait dengan awalan yang diberikan, mulai dari node ini. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | Cari awalan yang terkait dengan URI namespace yang diberikan, mulai dari node ini. Deklarasi namespace default diabaikan oleh metode ini. Lihat Namespace Prefix Lookup untuk detail tentang algoritme yang digunakan oleh metode ini. |
| [Navigate](../../aspose.html.dom/document/navigate/)(RequestMessage) | Memuat dokumen berdasarkan objek permintaan yang ditentukan, menggantikan konten sebelumnya. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string) | Memuat dokumen di Uniform Resource Locator (URL) yang ditentukan ke dalam instance saat ini, menggantikan konten sebelumnya. |
| [Navigate](../../aspose.html.dom/document/navigate/)(Url) | Memuat dokumen di Uniform Resource Locator (URL) yang ditentukan ke dalam instance saat ini, menggantikan konten sebelumnya. |
| [Navigate](../../aspose.html.dom/document/navigate/)(Stream, string) | Memuat dokumen dari konten tertentu dan menggunakan baseUri untuk menyelesaikan sumber daya relatif, menggantikan konten sebelumnya. Pemuatan dokumen dimulai dari posisi saat ini di aliran. |
| [Navigate](../../aspose.html.dom/document/navigate/)(Stream, Url) | Memuat dokumen dari konten tertentu dan menggunakan baseUri untuk menyelesaikan sumber daya relatif, menggantikan konten sebelumnya. Pemuatan dokumen dimulai dari posisi saat ini di aliran. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string, string) | Memuat dokumen dari konten tertentu dan menggunakan baseUri untuk menyelesaikan sumber daya relatif, menggantikan konten sebelumnya. |
| [Navigate](../../aspose.html.dom/document/navigate/)(string, Url) | Memuat dokumen dari konten tertentu dan menggunakan baseUri untuk menyelesaikan sumber daya relatif, menggantikan konten sebelumnya. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Menempatkan semua simpul Teks di kedalaman penuh sub-pohon di bawah Node ini, termasuk simpul atribut, ke dalam bentuk "normal" di mana hanya struktur (misalnya, elemen, komentar, instruksi pemrosesan, bagian CDATA, dan referensi entitas) yang memisahkan Teks node, yaitu, tidak ada node Teks yang berdekatan atau node Teks kosong. Ini dapat digunakan untuk memastikan bahwa tampilan DOM dokumen sama seperti jika disimpan dan dimuat ulang, dan berguna saat operasi (seperti pencarian XPointer [XPointer]) yang bergantung pada struktur pohon dokumen tertentu akan digunakan. Jika parameter "normalize-characters" dari objek DOMConfiguration yang dilampirkan ke Node.ownerDocument benar, metode ini juga akan sepenuhnya menormalkan karakter dari Text nodes. |
| [QuerySelector](../../aspose.html.dom/document/queryselector/)(string) | Mengembalikan Elemen pertama dalam dokumen, yang cocok dengan pemilih |
| [QuerySelectorAll](../../aspose.html.dom/document/queryselectorall/)(string) | Mengembalikan NodeList dari semua Elemen dalam dokumen, yang cocok dengan selector |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | Menghapus node anak yang ditunjukkan oleh oldChild dari daftar anak, dan mengembalikannya. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | Metode ini memungkinkan penghapusan pendengar acara dari target acara. Jika[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) dihapus dari sebuah[`EventTarget`](../../aspose.html.dom/eventtarget/) saat sedang memproses suatu peristiwa, peristiwa itu tidak akan dipicu oleh tindakan saat ini. Pemroses Peristiwa tidak akan pernah bisa dipanggil setelah dihapus. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | Metode ini memungkinkan penghapusan pendengar acara dari target acara. Jika[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) dihapus dari sebuah[`EventTarget`](../../aspose.html.dom/eventtarget/) saat sedang memproses suatu peristiwa, peristiwa itu tidak akan dipicu oleh tindakan saat ini. Pemroses Peristiwa tidak akan pernah bisa dipanggil setelah dihapus. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | Metode ini memungkinkan penghapusan pendengar acara dari target acara. Jika[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) dihapus dari sebuah[`EventTarget`](../../aspose.html.dom/eventtarget/) saat sedang memproses suatu peristiwa, peristiwa itu tidak akan dipicu oleh tindakan saat ini. Pemroses Peristiwa tidak akan pernah bisa dipanggil setelah dihapus. |
| override [RenderTo](../../aspose.html.dom.svg/svgdocument/renderto/)(IDevice) | Metode ini digunakan untuk mencetak isi dokumen saat ini ke perangkat yang ditentukan. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | Mengganti node anak oldChild dengan newChild dalam daftar anak, dan mengembalikan node oldChild. Jika newChild adalah objek DocumentFragment, oldChild digantikan oleh semua turunan DocumentFragment, yang disisipkan dalam urutan yang sama. Jika newChild sudah ada di pohon, pertama dihapus. |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save)(IOutputStorage) | Menyimpan konten dokumen dan sumber daya ke penyimpanan keluaran. |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_6)(string) | Menyimpan dokumen ke file lokal yang ditentukan oleh`jalur` Semua sumber daya yang digunakan dalam dokumen ini akan disimpan dalam ke folder yang berdekatan, yang namanya akan dibuat sebagai: nama_file_output + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_3)(Url) | Menyimpan dokumen ke file lokal yang ditentukan oleh`url` Semua sumber daya yang digunakan dalam dokumen ini akan disimpan dalam ke folder yang berdekatan, yang namanya akan dibuat sebagai: nama_file_output + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_1)(IOutputStorage, SVGSaveFormat) | Menyimpan konten dokumen dan sumber daya ke penyimpanan keluaran. |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_2)(IOutputStorage, SVGSaveOptions) | Menyimpan konten dokumen dan sumber daya ke penyimpanan keluaran. |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_7)(string, SVGSaveFormat) | Menyimpan dokumen ke file lokal yang ditentukan oleh`jalur` Semua sumber daya yang digunakan dalam dokumen ini akan disimpan dalam ke folder yang berdekatan, yang namanya akan dibuat sebagai: nama_file_output + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_8)(string, SVGSaveOptions) | Menyimpan dokumen ke file lokal yang ditentukan oleh`jalur` Semua sumber daya yang digunakan dalam dokumen ini akan disimpan dalam ke folder yang berdekatan, yang namanya akan dibuat sebagai: nama_file_output + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_4)(Url, SVGSaveFormat) | Menyimpan dokumen ke file lokal yang ditentukan oleh`url` Semua sumber daya yang digunakan dalam dokumen ini akan disimpan dalam ke folder yang berdekatan, yang namanya akan dibuat sebagai: nama_file_output + "_files". |
| [Save](../../aspose.html.dom.svg/svgdocument/save/#save_5)(Url, SVGSaveOptions) | Menyimpan dokumen ke file lokal yang ditentukan oleh`url` Semua sumber daya yang digunakan dalam dokumen ini akan disimpan dalam ke folder yang berdekatan, yang namanya akan dibuat sebagai: nama_file_output + "_files". |
| override [ToString](../../aspose.html.dom/node/tostring/)() | Mengembalikan aString yang mewakili instance ini. |
| [Write](../../aspose.html.dom/document/write/)(params string[]) | Tulis string teks ke aliran dokumen yang dibuka oleh open(). Perhatikan bahwa fungsi akan menghasilkan document yang tidak harus didorong oleh DTD dan oleh karena itu mungkin be menghasilkan hasil yang tidak valid dalam konteks dokumen. |
| [WriteLn](../../aspose.html.dom/document/writeln/)(params string[]) | Tulis string teks diikuti dengan karakter baris baru ke aliran document yang dibuka oleh open(). Perhatikan bahwa fungsi will menghasilkan dokumen yang belum tentu didorong oleh DTD dan oleh karena itu mungkin menghasilkan hasil yang tidak valid dalam konteks dokumen |

## Acara

| Nama | Keterangan |
| --- | --- |
| event [OnAbort](../../aspose.html.dom/document/onabort/) | Mendapat atau mengatur event handler untuk event OnAbort. |
| event [OnBlur](../../aspose.html.dom/document/onblur/) | Mendapat atau mengatur event handler untuk event OnBlur. |
| event [OnCancel](../../aspose.html.dom/document/oncancel/) | Mendapat atau mengatur event handler untuk event OnCancel. |
| event [OnCanplay](../../aspose.html.dom/document/oncanplay/) | Mendapat atau mengatur event handler untuk event OnCanplay. |
| event [OnCanPlayThrough](../../aspose.html.dom/document/oncanplaythrough/) | Mendapat atau menyetel event handler untuk event OnCanPlayThrough. |
| event [OnChange](../../aspose.html.dom/document/onchange/) | Mendapat atau mengatur event handler untuk event OnChange. |
| event [OnClick](../../aspose.html.dom/document/onclick/) | Mendapat atau mengatur event handler untuk event OnClick. |
| event [OnCueChange](../../aspose.html.dom/document/oncuechange/) | Mendapat atau mengatur event handler untuk event OnCueChange. |
| event [OnDblClick](../../aspose.html.dom/document/ondblclick/) | Mendapat atau mengatur event handler untuk event OnDblClick. |
| event [OnDurationChange](../../aspose.html.dom/document/ondurationchange/) | Mendapat atau mengatur event handler untuk event OnDurationChange. |
| event [OnEmptied](../../aspose.html.dom/document/onemptied/) | Mendapat atau mengatur event handler untuk event OnEmptied. |
| event [OnEnded](../../aspose.html.dom/document/onended/) | Mendapat atau menyetel event handler untuk event OnEnded. |
| event [OnError](../../aspose.html.dom/document/onerror/) | Mendapat atau mengatur event handler untuk event OnError. |
| event [OnFocus](../../aspose.html.dom/document/onfocus/) | Mendapat atau menyetel event handler untuk event OnFocus. |
| event [OnInput](../../aspose.html.dom/document/oninput/) | Mendapat atau mengatur event handler untuk event OnInput. |
| event [OnInvalid](../../aspose.html.dom/document/oninvalid/) | Mendapat atau mengatur event handler untuk event OnInvalid. |
| event [OnKeyDown](../../aspose.html.dom/document/onkeydown/) | Mendapat atau mengatur event handler untuk event OnKeyDown. |
| event [OnKeyPress](../../aspose.html.dom/document/onkeypress/) | Mendapat atau mengatur event handler untuk event OnKeyPress. |
| event [OnKeyUp](../../aspose.html.dom/document/onkeyup/) | Mendapat atau mengatur event handler untuk event OnKeyUp. |
| event [OnLoad](../../aspose.html.dom/document/onload/) | Mendapat atau mengatur event handler untuk event OnLoad. |
| event [OnLoadedData](../../aspose.html.dom/document/onloadeddata/) | Mendapat atau mengatur event handler untuk event OnLoadedData. |
| event [OnLoadedMetadata](../../aspose.html.dom/document/onloadedmetadata/) | Mendapat atau mengatur event handler untuk event OnLoadedMetadata. |
| event [OnLoadStart](../../aspose.html.dom/document/onloadstart/) | Mendapat atau mengatur event handler untuk event OnLoadStart. |
| event [OnMouseDown](../../aspose.html.dom/document/onmousedown/) | Mendapat atau mengatur event handler untuk event OnMouseDown. |
| event [OnMouseEnter](../../aspose.html.dom/document/onmouseenter/) | Mendapat atau mengatur event handler untuk event OnMouseEnter. |
| event [OnMouseLeave](../../aspose.html.dom/document/onmouseleave/) | Mendapat atau mengatur event handler untuk event OnMouseLeave. |
| event [OnMouseMove](../../aspose.html.dom/document/onmousemove/) | Mendapat atau mengatur event handler untuk event OnMouseMove. |
| event [OnMouseOut](../../aspose.html.dom/document/onmouseout/) | Mendapat atau mengatur event handler untuk event OnMouseOut. |
| event [OnMouseOver](../../aspose.html.dom/document/onmouseover/) | Mendapat atau mengatur event handler untuk event OnMouseOver. |
| event [OnMouseUp](../../aspose.html.dom/document/onmouseup/) | Mendapat atau mengatur event handler untuk event OnMouseUp. |
| event [OnMouseWheel](../../aspose.html.dom/document/onmousewheel/) | Mendapat atau mengatur event handler untuk event OnMouseWheel. |
| event [OnPause](../../aspose.html.dom/document/onpause/) | Mendapat atau menyetel event handler untuk event OnPause. |
| event [OnPlay](../../aspose.html.dom/document/onplay/) | Mendapat atau menyetel event handler untuk event OnPlay. |
| event [OnPlaying](../../aspose.html.dom/document/onplaying/) | Mendapat atau menyetel event handler untuk event OnPlaying. |
| event [OnProgress](../../aspose.html.dom/document/onprogress/) | Mendapat atau mengatur event handler untuk event OnProgress. |
| event [OnRateChange](../../aspose.html.dom/document/onratechange/) | Mendapat atau mengatur event handler untuk event OnRateChange. |
| event [OnReadyStateChange](../../aspose.html.dom/document/onreadystatechange/) | Mendapat atau mengatur event handler untuk event OnReadyStateChange. |
| event [OnReset](../../aspose.html.dom/document/onreset/) | Mendapat atau mengatur event handler untuk event OnReset. |
| event [OnResize](../../aspose.html.dom/document/onresize/) | Mendapat atau mengatur event handler untuk event OnResize. |
| event [OnScroll](../../aspose.html.dom/document/onscroll/) | Mendapat atau mengatur event handler untuk event OnScroll. |
| event [OnSeeked](../../aspose.html.dom/document/onseeked/) | Mendapat atau mengatur event handler untuk event OnSeeked. |
| event [OnSeeking](../../aspose.html.dom/document/onseeking/) | Mendapat atau mengatur event handler untuk event OnSeeking. |
| event [OnSelect](../../aspose.html.dom/document/onselect/) | Mendapat atau mengatur event handler untuk event OnSelect. |
| event [OnShow](../../aspose.html.dom/document/onshow/) | Mendapat atau mengatur event handler untuk event OnShow. |
| event [OnStalled](../../aspose.html.dom/document/onstalled/) | Mendapat atau mengatur event handler untuk event OnStalled. |
| event [OnSubmit](../../aspose.html.dom/document/onsubmit/) | Mendapat atau mengatur event handler untuk event OnSubmit. |
| event [OnSuspend](../../aspose.html.dom/document/onsuspend/) | Mendapat atau menyetel event handler untuk event OnSuspend. |
| event [OnTimeUpdate](../../aspose.html.dom/document/ontimeupdate/) | Mendapat atau mengatur event handler untuk event OnTimeUpdate. |
| event [OnToggle](../../aspose.html.dom/document/ontoggle/) | Mendapat atau menyetel event handler untuk event OnToggle. |
| event [OnVolumeChange](../../aspose.html.dom/document/onvolumechange/) | Mendapat atau mengatur event handler untuk event OnVolumeChange. |
| event [OnWaiting](../../aspose.html.dom/document/onwaiting/) | Mendapat atau menyetel event handler untuk event OnWaiting. |

### Lihat juga

* class [Document](../../aspose.html.dom/document/)
* interface [IDocumentEvent](../../aspose.html.dom.events/idocumentevent/)
* interface [IDocumentCSS](../../aspose.html.dom.css/idocumentcss/)
* ruang nama [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg/)
* perakitan [Aspose.HTML](../../)


