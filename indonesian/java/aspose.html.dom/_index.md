---
title: "com.aspose.html.dom"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Paket com.aspose.html.dom Document Object Model menyediakan API yang merepresentasikan dan berinteraksi dengan dokumen HTML, XML, atau SVG apa pun. DOM adalah model dokumen yang dimuat di peramban dan merepresentasikan dokumen sebagai pohon node di mana setiap node mewakili bagian dari dokumen, misalnya elemen, teks, string, atau komentar."
type: docs

url: /id/java/com.aspose.html.dom/
---
Paket **com.aspose.html.dom (Document Object Model)** menyediakan API yang merepresentasikan dan berinteraksi dengan dokumen HTML, XML, atau SVG apa pun. DOM adalah model dokumen yang dimuat di peramban dan merepresentasikan dokumen sebagai pohon node, di mana setiap node mewakili bagian dari dokumen (misalnya elemen, string teks, atau komentar).

## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [Attr](./attr/) | Antarmuka Attr merepresentasikan atribut dalam objek Element. Biasanya nilai yang diizinkan untuk atribut tersebut didefinisikan dalam skema yang terkait dengan dokumen. |
| [CDATASection](./cdatasection/) | Bagian CDATA digunakan untuk meng-escape blok teks yang berisi karakter yang seharusnya dianggap sebagai markup. |
| [CharacterData](./characterdata/) | CharacterData memperluas Node dengan sekumpulan atribut dan metode untuk mengakses data karakter dalam DOM. |
| [Comment](./comment/) | Mewarisi dari CharacterData dan merepresentasikan konten komentar, yaitu semua karakter di antara tanda '' pembuka. |
| [Document](./document/) | Document merepresentasikan seluruh dokumen HTML, XML, atau SVG. Secara konseptual, ia adalah akar dari pohon dokumen, dan menyediakan akses utama ke data dokumen. |
| [DocumentFragment](./documentfragment/) | DocumentFragment adalah objek Document yang "ringan" atau "minimal". Sangat umum ingin dapat mengekstrak sebagian pohon dokumen atau membuat fragmen baru dari sebuah dokumen. |
| [DocumentType](./documenttype/) | DocumentType menyediakan antarmuka ke daftar entitas yang didefinisikan untuk dokumen. |
| [DOMException](./domexception/) | Antarmuka DOMException merepresentasikan peristiwa abnormal (disebut pengecualian) yang terjadi sebagai hasil pemanggilan metode atau mengakses properti dari sebuah web API. Pada dasarnya inilah cara kondisi kesalahan dijelaskan dalam web API. |
| [DOMObject](./domobject/) | Tipe DOMObject digunakan untuk merepresentasikan objek dasar bagi seluruh Document Object Model. Untuk Java dan ECMAScript, DOMObject terikat pada tipe Object. |
| [Element](./element/) | Antarmuka Element merepresentasikan sebuah elemen dalam dokumen HTML atau XML. |
| [Entity](./entity/) | Mewakili entitas yang dikenal, baik yang diurai maupun tidak diurai, dalam dokumen XML. |
| [EntityReference](./entityreference/) | Node EntityReference dapat digunakan untuk mewakili referensi entitas dalam pohon. |
| [EventTarget](./eventtarget/) | Antarmuka **EventTarget** diimplementasikan oleh objek yang dapat menerima peristiwa dan mungkin memiliki pendengar untuknya. Dengan kata lain, setiap target peristiwa mengimplementasikan tiga metode yang terkait dengan antarmuka ini. |
| [Node](./node/) | Antarmuka **Node** adalah tipe data utama untuk seluruh Document Object Model. Ia mewakili satu node tunggal dalam pohon dokumen. Meskipun semua objek yang mengimplementasikan antarmuka **Node** menyediakan metode untuk menangani anak, tidak semua objek yang mengimplementasikan antarmuka **Node** dapat memiliki anak. Misalnya, node [`Text`](../com.aspose.html.dom/text/) mungkin tidak memiliki anak, dan menambahkan anak ke node tersebut menyebabkan sebuah [`DOMException`](../com.aspose.html.dom/domexception/) diangkat. |
| [Notation](./notation/) | Mewakili notasi yang dideklarasikan dalam DTD. |
| [ProcessingInstruction](./processinginstruction/) | **ProcessingInstruction** mewakili "processing instruction", yang digunakan dalam XML sebagai cara untuk menyimpan informasi spesifik prosesor dalam teks dokumen. |
| [QualifiedName](./qualifiedname/) | Mewakili nama yang memenuhi syarat HTML. |
| [ShadowRoot](./shadowroot/) | **ShadowRoot** adalah node akar dari pohon bayangan. |
| [Text](./text/) | Antarmuka **Text** mewarisi dari **CharacterData** dan mewakili konten teks (disebut data karakter dalam XML) dari sebuah **Element** atau **Attr**. |
| [TypeInfo](./typeinfo/) | Antarmuka **TypeInfo** mewakili tipe yang dirujuk dari node **Element** atau **Attr**, yang ditentukan dalam skema yang terkait dengan dokumen. |
## Antarmuka

| Antarmuka | Deskripsi |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | Konteks penelusuran adalah lingkungan di mana objek [`Document`](../com.aspose.html.dom/document/) disajikan kepada pengguna. |
| [IChildNode](./ichildnode/) | Mendefinisikan antarmuka [`IChildNode`](../com.aspose.html.dom/ichildnode/) yang harus diimplementasikan oleh [`Node`](../com.aspose.html.dom/node/) yang dapat memiliki induk. |
| [IDOMImplementation](./idomimplementation/) | Antarmuka **DOMImplementation** menyediakan sejumlah metode untuk melakukan operasi yang independen dari instance tertentu dari model objek dokumen. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | Mewakili antarmuka yang harus diwarisi oleh semua elemen yang mendukung penanganan peristiwa sistem. |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | Mendefinisikan [`IChildNode`](../com.aspose.html.dom/ichildnode/) yang bukan [`DOCUMENT_TYPE_NODE`](../com.aspose.html.dom/node/document_type_node/). |
| [INonElementParentNode](./inonelementparentnode/) | Mendefinisikan [`IParentNode`](../com.aspose.html.dom/iparentnode/) yang bukan tipe **Element**. |
| [IParentNode](./iparentnode/) | Mendefinisikan antarmuka [`IParentNode`](../com.aspose.html.dom/iparentnode/) yang diimplementasikan oleh semua induk yang memungkinkan. |
| [IStorage](./istorage/) | Antarmuka ini dari Web Storage API menyediakan akses ke penyimpanan sesi atau lokal untuk domain tertentu. Lihat spesifikasi Web Storage: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage) |
## Enumerasi

| Enumerasi | Deskripsi |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | Mode-mode di mana **ShadowRoot** dapat beroperasi. |
