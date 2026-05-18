---
title: "Kelas NodeFilter"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.dom.traversal.filters.NodeFilter. Filter adalah objek yang tahu cara menyaring node"
type: docs

url: /id/java/com.aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Filter adalah objek yang tahu cara "menyaring" node.

```java
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| abstract [AcceptNode](../../com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | Uji apakah sebuah node tertentu terlihat dalam tampilan logis TreeWalker atau NodeIterator. Fungsi ini akan dipanggil oleh implementasi TreeWalker dan NodeIterator; biasanya tidak dipanggil secara langsung dari kode pengguna. (Meskipun Anda dapat melakukannya jika ingin menggunakan filter yang sama untuk mengarahkan logika aplikasi Anda.) |
| [getPlatformType](../../com.aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | Metode ini digunakan untuk mengambil Tipe objek ECMAScript. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [FILTER_ACCEPT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | Terima node. Metode navigasi yang didefinisikan untuk NodeIterator atau TreeWalker akan mengembalikan node ini. |
| const [FILTER_REJECT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | Tolak node. Metode navigasi yang didefinisikan untuk NodeIterator atau TreeWalker tidak akan mengembalikan node ini. Untuk TreeWalker, anak-anak node ini juga akan ditolak. NodeIterators memperlakukan ini sebagai sinonim untuk FILTER_SKIP. |
| const [FILTER_SKIP](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | Lewati node tunggal ini. Metode navigasi yang didefinisikan untuk NodeIterator atau TreeWalker tidak akan mengembalikan node ini. Untuk kedua NodeIterator dan TreeWalker, anak-anak node ini tetap akan dipertimbangkan. |
| const [SHOW_ALL](../../com.aspose.html.dom.traversal.filters/nodefilter/show_all/) | Tampilkan semua Node. |
| const [SHOW_ATTRIBUTE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | Tampilkan node Attr. Ini hanya bermakna saat membuat iterator atau tree-walker dengan node atribut sebagai akar; dalam hal ini, berarti node atribut akan muncul di posisi pertama iterasi atau penelusuran. Karena atribut tidak pernah menjadi anak node lain, mereka tidak muncul saat menelusuri pohon dokumen. |
| const [SHOW_CDATA_SECTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | Tampilkan node CDATASection. |
| const [SHOW_COMMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_comment/) | Tampilkan node Comment. |
| const [SHOW_DOCUMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document/) | Tampilkan node Document. |
| const [SHOW_DOCUMENT_FRAGMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | Tampilkan node DocumentFragment. |
| const [SHOW_DOCUMENT_TYPE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | Tampilkan node DocumentType. |
| const [SHOW_ELEMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_element/) | Tampilkan node Element. |
| const [SHOW_ENTITY](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity/) | Tampilkan node Entity. Ini hanya bermakna saat membuat iterator atau tree-walker dengan node Entity sebagai akar; dalam hal ini, berarti node Entity akan muncul di posisi pertama penelusuran. Karena entitas bukan bagian dari pohon dokumen, mereka tidak muncul saat menelusuri pohon dokumen. |
| const [SHOW_ENTITY_REFERENCE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | Tampilkan node EntityReference. |
| const [SHOW_NOTATION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_notation/) | Tampilkan node Notation. Ini hanya bermakna saat membuat iterator atau tree-walker dengan node Notation sebagai akar; dalam kasus ini, berarti node Notation akan muncul pada posisi pertama dalam penelusuran. Karena notasi tidak termasuk dalam pohon dokumen, mereka tidak muncul saat menelusuri pohon dokumen. |
| const [SHOW_PROCESSING_INSTRUCTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | Tampilkan node ProcessingInstruction. |
| const [SHOW_TEXT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_text/) | Tampilkan node Text. |

### Lihat Juga

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [INodeFilter](../../com.aspose.html.dom.traversal/inodefilter/)
* package [com.aspose.html.dom.traversal.filters](../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../)
