---
title: "Element.GetElementsByTagName"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Element. Mengembalikan objek HTMLCollection yang berisi semua elemen dengan nama tag tertentu dalam urutan dokumen"
type: docs

url: /id/java/com.aspose.html.dom/element/getelementsbytagname/
---
## Element.GetElementsByTagName method

Mengembalikan objek [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) yang berisi semua [`elements`](../) dengan nama tag tertentu, dalam urutan dokumen.

```java
public HTMLCollection GetElementsByTagName(String name)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | String | Nama tag. Representasi string dari nama tag. |

### Nilai Kembali

Sebuah objek [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) adalah daftar mirip array dari [`elements`](../).

## Catatan

Rujuk ke [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagname) resmi.

Anda mungkin juga tertarik pada [documentation](https://docs.aspose.com/html/net/).

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Contoh

```java
# Html input content
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Title</title>
</head>
<body>
<div id="divElementContainerId">
	<p class="pStyle">The paragraph styled pStyle class content...</p>
	<p>The second paragraph content...</p>
	<p>The third paragraph content...</p>
	<div class="pStyle">The div element styled pStyle class...</div>
</div>
</body>
</html>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	// Kode pengguna ditempatkan di sini

	HTMLCollection htmlCollection = document.GetElementsByTagName("p");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// Kode pengguna ditempatkan di sini
}
```

*inputHtmlPath - user input html file.

# Console output

Ditemukan: 3

Paragraf dengan kelas pStyle yang bergaya...

Isi paragraf kedua...

Isi paragraf ketiga...

### Lihat Juga

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
