---
title: "com.aspose.html.dom.traversal"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Paket com.aspose.html.dom.traversal berisi metode yang membuat iterator dan tree-walker untuk menavigasi antar elemen serta menelusuri sebuah node dan anak‑anaknya dalam urutan dokumen."
type: docs

url: /id/java/com.aspose.html.dom.traversal/
---
Paket **com.aspose.html.dom.traversal** berisi metode yang membuat iterator dan tree-walker untuk menavigasi antar elemen serta menelusuri sebuah node dan anak-anaknya dalam urutan dokumen.

## Antarmuka

| Antarmuka | Deskripsi |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal berisi metode yang membuat iterator dan tree-walker untuk menelusuri sebuah node dan anak‑anaknya dalam urutan dokumen (depth first, pre‑order traversal, yang setara dengan urutan di mana tag pembuka muncul dalam representasi teks dokumen). Pada DOM yang mendukung fitur Traversal, DocumentTraversal akan diimplementasikan oleh objek yang sama yang mengimplementasikan antarmuka Document. |
| [IElementTraversal](./ielementtraversal/) | Antarmuka ElementTraversal adalah sekumpulan atribut hanya-baca yang memungkinkan penulis dengan mudah menavigasi antar elemen dalam sebuah dokumen. Pada implementasi yang mematuhi Element Traversal, semua objek yang mengimplementasikan Element juga harus mengimplementasikan antarmuka ElementTraversal. |
| [INodeFilter](./inodefilter/) | Filter adalah objek yang mengetahui cara "menyaring" node. Jika sebuah NodeIterator atau TreeWalker diberikan NodeFilter, ia menerapkan filter sebelum mengembalikan node berikutnya. Jika filter menyatakan untuk menerima node, logika penelusuran mengembalikannya; jika tidak, penelusuran mencari node berikutnya dan menganggap node yang ditolak tidak ada. |
| [INodeIterator](./inodeiterator/) | Iterator digunakan untuk melangkah melalui sekumpulan node, misalnya sekumpulan node dalam NodeList, subtree dokumen yang diatur oleh Node tertentu, hasil kueri, atau sekumpulan node lainnya. Sekumpulan node yang akan diiterasi ditentukan oleh implementasi NodeIterator. DOM Level 2 menentukan satu implementasi NodeIterator untuk penelusuran urutan dokumen pada subtree dokumen. Instance iterator ini dibuat dengan memanggil DocumentTraversal .createNodeIterator(). |
| [ITraversal](./itraversal/) | Iterator digunakan untuk melangkah melalui sekumpulan node, misalnya sekumpulan node dalam NodeList, subtree dokumen yang diatur oleh Node tertentu, hasil kueri, atau sekumpulan node lainnya. Sekumpulan node yang akan diiterasi ditentukan oleh implementasi NodeIterator. DOM Level 2 menentukan satu implementasi NodeIterator untuk penelusuran urutan dokumen pada subtree dokumen. Instance iterator ini dibuat dengan memanggil DocumentTraversal .createNodeIterator(). |
| [ITreeWalker](./itreewalker/) | Objek TreeWalker digunakan untuk menavigasi pohon dokumen atau subtree menggunakan tampilan dokumen yang didefinisikan oleh flag whatToShow dan filter mereka (jika ada). Setiap fungsi yang melakukan navigasi menggunakan TreeWalker secara otomatis akan mendukung tampilan apa pun yang didefinisikan oleh TreeWalker. |
