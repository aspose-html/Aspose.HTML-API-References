---
title: "Document.GetElementById"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Document. Metode Document getElementById mengembalikan objek Element yang mewakili elemen yang properti id‑nya cocok dengan String yang ditentukan. Karena ID elemen harus unik bila ditentukan, mereka merupakan cara yang berguna untuk mengakses elemen tertentu dengan cepat."
type: docs

url: /id/java/com.aspose.html.dom/document/getelementbyid/
---
## Document.GetElementById method

Metode Document getElementById() mengembalikan objek [`Element`](../../element/) yang mewakili elemen yang properti id‑nya cocok dengan String yang ditentukan. Karena ID elemen harus unik bila ditentukan, mereka merupakan cara yang berguna untuk mengakses elemen tertentu dengan cepat.

Jika Anda perlu mengakses elemen yang tidak memiliki ID, Anda dapat menggunakan querySelector() untuk menemukan elemen tersebut dengan selector apa pun.

```java
public Element GetElementById(String elementId)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| elementId | String | ID elemen yang akan dicari. ID adalah String yang sensitif huruf besar/kecil dan unik dalam dokumen; hanya satu elemen yang dapat memiliki ID tertentu. |

### Nilai Kembali

Objek [`Element`](../../element/) yang menggambarkan objek elemen DOM yang cocok dengan ID yang ditentukan, atau null jika tidak ada elemen yang cocok ditemukan dalam dokumen.

## Catatan

Lihat [spesifikasi](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid) resmi.

Konten praktik pengembangan web dapat ditemukan di [w3schools](https://www.w3schools.com/jsref/met_document_getelementbyid.asp).

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Contoh

```java
// Konten HTML
<div id="uniqueIdentifier">Container with ID - identifier</div>

// Kode C#
import System;
import Aspose.Html;
import com.aspose.html.dom;
...
	using (var document = new HTMLDocument(inputHtmlPath))
		{
			Element element = document.GetElementById("uniqueIdentifier");
			HTMLDivElement divElement = (HTMLDivElement) element;
			Console.WriteLine(divElement.InnerHTML);

			// Kode pengguna ditempatkan di sini
   }
```

// Output konsol

Kontainer dengan ID - pengidentifikasi

*inputHtmlPath - user input html file path

### Lihat Juga

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
