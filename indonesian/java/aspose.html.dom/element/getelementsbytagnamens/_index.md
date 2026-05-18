---
title: "Element.GetElementsByTagNameNS"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Element. Mengembalikan objek HTMLCollection yang berisi semua elemen dengan nama lokal tertentu dan String URI paket dalam urutan dokumen."
type: docs

url: /id/java/com.aspose.html.dom/element/getelementsbytagnamens/
---
## Element.GetElementsByTagNameNS method

Mengembalikan objek [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) yang berisi semua [`elements`](../) dengan nama lokal tertentu dan String URI paket dalam urutan dokumen.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| packageURI | String | Representasi String URI paket. |
| localName | String | Representasi String dari nama lokal. |

### Nilai Kembali

Sebuah objek [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) adalah daftar mirip array dari [`elements`](../).

## Catatan

Lihat [spesifikasi](https://dom.spec.whatwg.org/#dom-element-getelementsbytagnamens) resmi.

Anda mungkin juga tertarik pada [documentation](https://docs.aspose.com/html/net/).

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Contoh

```java
# .xhtml input file content
<!DOCTYPE html>
<html lang="en"
   xmlns="http://www.w3.org/1999/xhtml"
   xmlns:custom="http://www.company.com">
<head>
	<meta charset="UTF-8"/>
	<link rel="stylesheet" href="/styles/main.css"/>
	<title>Title</title>
</head>
<body>
<custom:customtag>
	Custom package custom tag content goes here...
</custom:customtag>
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

	HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.company.com", "customtag");
	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// Kode pengguna ditempatkan di sini
}
```

*inputHtmlPath - user input xhtml file path.

# Console output

Ditemukan: 1

Konten tag khusus paket khusus ditempatkan di sini...

### Lihat Juga

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
