---
title: "Element.GetElementsByClassName"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Element. Mengembalikan objek HTMLCollection yang berisi semua elemen dalam elemen yang memiliki semua kelas yang ditentukan dalam argumen"
type: docs

url: /id/java/com.aspose.html.dom/element/getelementsbyclassname/
---
## Element.GetElementsByClassName method

Mengembalikan objek [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) yang berisi semua elemen dalam [`element`](../) yang memiliki semua kelas yang ditentukan dalam argumen.

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| classNames | String | The String String yang berisi sekumpulan token unik yang dipisahkan spasi tanpa urutan yang mewakili kelas (nama kelas) |

### Nilai Kembali

Sebuah objek [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) adalah daftar mirip array dari [`elements`](../).

## Catatan

Lihat spesifikasi resmi [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbyclassname).

Anda mungkin juga tertarik pada [documentation](https://docs.aspose.com/html/net/).

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Contoh

```java
# HTML source content
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

	Element container = document.GetElementById("divElementContainerId");
	HTMLCollection htmlCollection = container.GetElementsByClassName("pStyle");

	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// Kode pengguna ditempatkan di sini
}
```

*inputHtmlPath - user input html file path.

# Console output

Ditemukan: 2

Paragraf yang bergaya kelas pStyle...

Elemen div yang bergaya kelas pStyle...

### Lihat Juga

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
