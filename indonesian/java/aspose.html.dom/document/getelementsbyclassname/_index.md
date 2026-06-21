---
title: "Document.GetElementsByClassName"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Document. Metode getElementsByClassName dari antarmuka Document mengembalikan objek mirip array dari semua elemen anak yang memiliki semua nama kelas yang diberikan."
type: docs

url: /id/java/com.aspose.html.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

Metode getElementsByClassName dari antarmuka [`Document`](../) mengembalikan objek mirip array dari semua elemen anak yang memiliki semua nama kelas yang diberikan.

Ketika dipanggil pada objek dokumen, seluruh dokumen akan dicari, termasuk node akar. Anda juga dapat memanggil getElementsByClassName() pada elemen apa pun; itu akan mengembalikan hanya elemen yang merupakan keturunan dari elemen akar yang ditentukan dengan nama kelas yang diberikan.

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| classNames | String | The String String yang berisi sekumpulan token unik yang dipisahkan spasi tanpa urutan yang mewakili kelas (nama kelas) |

### Nilai Kembali

Sebuah [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) langsung dari elemen yang ditemukan.

## Catatan

Lihat [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname) resmi.

Konten praktik pengembangan web dapat ditemukan di [w3schools](https://www.w3schools.com/jsref/met_element_getelementsbyclassname.asp).

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Contoh

```java
var elements = document.GetElementsByClassName("red test");
```

```java
// Konten HTML
<div class="custom-class">Customized by css class container</div>

// Kode C#
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("custom-class");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// Kode pengguna ditempatkan di sini
}
```

// Output konsol

Ditemukan: 1

Disesuaikan oleh kelas css container

*inputHtmlPath - user input html file path

```java
// Gaya CSS
.ddd{
	padding: 10pt;
}

.kkk{
	background-color: chartreuse;
}

// Konten HTML
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
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("ddd");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
		Console.WriteLine($"Element type: {element.GetType()}");
	}
         
	// Kode pengguna ditempatkan di sini
}
```

# Console output

Ditemukan: 2

Paragraf yang ditata oleh nama kelas =ddd kkk=

Tipe elemen: Aspose.Html.HTMLParagraphElement

Paragraf yang ditata oleh nama kelas =ddd fff=

Tipe elemen: Aspose.Html.HTMLParagraphElement

*inputHtmlPath - user input html file path

```java
// Gaya CSS
.pStyle{
  font-
}

# HTML content
<div>
	<p class="pStyle">First styled by pStyle class paragraph</p>
	<p class="pStyle">Second styled by pStyle class paragraph</p>
	<p class="pStyle">Third styled by pStyle class paragraph</p>
	<span class="pStyle">Span styled by pStyle</span>
</div>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("pStyle");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
		Console.WriteLine($"Element type: {element.GetType()}");
	}
         
	// Kode pengguna ditempatkan di sini
}
```

# Console output

Ditemukan: 4

Paragraf pertama yang ditata oleh kelas pStyle

Tipe elemen: Aspose.Html.HTMLParagraphElement

Paragraf kedua yang ditata oleh kelas pStyle

Tipe elemen: Aspose.Html.HTMLParagraphElement

Paragraf ketiga yang ditata oleh kelas pStyle

Tipe elemen: Aspose.Html.HTMLParagraphElement

Span dengan gaya pStyle

Tipe elemen: Aspose.Html.HTMLElement

*inputHtmlPath - user input html file path

### Lihat Juga

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
