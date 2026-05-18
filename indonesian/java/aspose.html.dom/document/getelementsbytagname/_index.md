---
title: "Document.GetElementsByTagName"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Document. Metode getElementsByTagName dari antarmuka Document mengembalikan HTMLCollection elemen dengan nama tag yang diberikan."
type: docs

url: /id/java/com.aspose.html.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

Metode getElementsByTagName dari antarmuka [`Document`](../) mengembalikan [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) elemen dengan nama tag yang diberikan.

Seluruh dokumen dicari, termasuk node akar. [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) yang dikembalikan bersifat live, artinya ia memperbarui dirinya secara otomatis agar tetap sinkron dengan pohon DOM tanpa harus memanggil document.getElementsByTagName() lagi.

```java
public HTMLCollection GetElementsByTagName(String tagname)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tagname | String | String yang mewakili nama elemen. String khusus "*" mewakili semua elemen. |

### Nilai Kembali

`HTMLCollection` live [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) dari elemen yang ditemukan dalam urutan kemunculannya di pohon.

## Catatan

Lihat [spesifikasi](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname) resmi.

Konten praktik pengembangan web dapat ditemukan di [w3schools](https://www.w3schools.com/jsref/met_document_getelementsbytagname.asp).

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Contoh

```java
var elements = document.GetElementsByTagName(name);
```

```java
#HTML content
<div>
	<p class="pStyle">First styled by pStyle class paragraph</p>
	<p class="pStyle">Second styled by pStyle class paragraph</p>
	<p class="pStyle">Third styled by pStyle class paragraph</p>
	<span class="pStyle">Span styled by pStyle</span>
</div>
<div id="smart class">
	<p id="p1" class="ddd kkk">Paragraph styled by class name =ddd kkk=</p>
	<p id="p2" class="ddd fff">Paragraph styled by class name =ddd fff=</p>
	<p id="p3" class="kkk fff">Paragraph styled by class name =kkk fff=</p>
</div>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;

import (var document = new HTMLDocument(inputHtmlPath))
{
    HTMLCollection htmlCollection = document.GetElementsByTagName("p");
    Console.WriteLine($"Found: {htmlCollection.Length}" );
    foreach (Element element in htmlCollection)
    {
      Console.WriteLine(element.InnerHTML);
    }

    // Kode pengguna ditempatkan di sini
}
```

# Console output

Ditemukan: 6

Paragraf pertama yang ditata oleh kelas pStyle

Paragraf kedua yang ditata oleh kelas pStyle

Paragraf ketiga yang ditata oleh kelas pStyle

Paragraf yang ditata oleh nama kelas =ddd kkk=

Paragraf yang ditata oleh nama kelas =ddd fff=

Paragraf yang ditata oleh nama kelas =kkk fff=

*inputHtmlPath - user input html file path

### Lihat Juga

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
