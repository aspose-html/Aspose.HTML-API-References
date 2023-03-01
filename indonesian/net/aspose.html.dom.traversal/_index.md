---
title: Aspose.Html.Dom.Traversal
second_title: Aspose.HTML untuk Referensi .NET API
description: Itu Aspose.Html.Dom.Traversalnamespace berisi metode yang membuat iterator dan treewalker untuk bernavigasi di antara elemen dan melintasi node dan turunannya dalam urutan dokumen.
type: docs
weight: 170
url: /id/net/aspose.html.dom.traversal/
---
Itu **Aspose.Html.Dom.Traversal**namespace berisi metode yang membuat iterator dan tree-walker untuk bernavigasi di antara elemen dan melintasi node dan turunannya dalam urutan dokumen.

## Antarmuka

| Antarmuka | Keterangan |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal berisi metode yang membuat iterator dan tree-walker untuk melintasi node dan turunannya dalam urutan dokumen (kedalaman pertama, traversal pre-order, yang setara dengan urutan di mana tag awal muncul dalam representasi teks dari dokumen). Di DOM yang mendukung fitur Traversal, DocumentTraversal akan diimplementasikan oleh objek yang sama yang mengimplementasikan antarmuka Dokumen. |
| [IElementTraversal](./ielementtraversal/) | Antarmuka ElementTraversal adalah sekumpulan atribut hanya-baca yang memungkinkan penulis untuk dengan mudah menavigasi antar elemen dalam dokumen. Dalam menyesuaikan implementasi Element Traversal, semua objek yang mengimplementasikan Element juga harus mengimplementasikan antarmuka ElementTraversal. |
| [INodeFilter](./inodefilter/) | Filter adalah objek yang mengetahui cara "memfilter" node. Jika NodeIterator atau TreeWalker diberi NodeFilter, ini menerapkan filter sebelum mengembalikan node berikutnya. Jika filter mengatakan menerima node, logika traversal mengembalikan itu; jika tidak, traversal mencari node berikutnya dan berpura-pura bahwa node yang ditolak tidak ada. |
| [INodeIterator](./inodeiterator/) | Iterators digunakan untuk melangkah melalui satu set node, misalnya set node dalam NodeList, subpohon dokumen yang diatur oleh Node tertentu, hasil kueri, atau set node lainnya. Kumpulan node yang akan diulang ditentukan oleh implementasi dari NodeIterator. DOM Level 2 menentukan implementasi NodeIterator tunggal untuk traversal urutan dokumen dari subpohon dokumen. Instance dari iterator ini dibuat dengan memanggil DocumentTraversal .createNodeIterator(). |
| [ITraversal](./itraversal/) | Iterators digunakan untuk melangkah melalui satu set node, misalnya set node dalam NodeList, subpohon dokumen yang diatur oleh Node tertentu, hasil kueri, atau set node lainnya. Kumpulan node yang akan diulang ditentukan oleh implementasi dari NodeIterator. DOM Level 2 menentukan implementasi NodeIterator tunggal untuk traversal urutan dokumen dari subpohon dokumen. Instance dari iterator ini dibuat dengan memanggil DocumentTraversal .createNodeIterator(). |
| [ITreeWalker](./itreewalker/) | Objek TreeWalker digunakan untuk menavigasi pohon dokumen atau subpohon menggunakan tampilan dokumen yang ditentukan oleh tanda dan filter whatToShow mereka (jika ada). Fungsi apa pun yang melakukan navigasi menggunakan TreeWalker akan secara otomatis mendukung tampilan apa pun yang ditentukan oleh TreeWalker. |


