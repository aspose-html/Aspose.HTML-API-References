---
title: "Document.GetElementsByTagNameNS"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Document. Mengembalikan daftar elemen dengan nama tag yang diberikan yang termasuk dalam paket yang diberikan. Seluruh dokumen dicari termasuk node akar."
type: docs

url: /id/java/com.aspose.html.dom/document/getelementsbytagnamens/
---
## Document.GetElementsByTagNameNS method

Mengembalikan daftar elemen dengan nama tag yang diberikan yang termasuk dalam paket yang ditentukan. Seluruh dokumen dicari, termasuk node akar.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| packageURI | String | URI paket dari elemen yang dicari. |
| localName | String | Baik nama lokal elemen yang dicari atau nilai khusus *, yang cocok dengan semua elemen. |

### Nilai Kembali

Sebuah [`NodeList`](../../../com.aspose.html.collections/nodelist/) langsung (tetapi lihat catatan di bawah) dari elemen yang ditemukan dalam urutan mereka muncul di pohon.

## Catatan

Lihat [spesifikasi](https://dom.spec.whatwg.org/#dom-document-getelementsbytagnamens) resmi.

Konten praktik pengembangan web dapat ditemukan di [w3schools](https://www.w3schools.com/xml/met_document_getelementsbytagnamens.asp).

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Contoh

```java
var elements = document.GetElementsByTagNameNS(@package, name);
```

```java
# HTML content. File extension - xhtml
<!DOCTYPE html>
<html lang="en"
	xmlns="http://www.w3.org/1999/xhtml"
	xmlns:xml="http://www.w3.org/XML/1998/package">
...
<xml:uniquetag>
  xml package uniquetag content goes here...
</xml:uniquetag>
...
</html>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
    HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.w3.org/XML/1998/package","uniquetag");
    Console.WriteLine($"Found: {htmlCollection.Length}" );
    foreach (Element element in htmlCollection)
    {
      Console.WriteLine(element.InnerHTML);
    }  
    // Kode pengguna ditempatkan di sini
}





# Console output

Found: 1

xml package uniquetag content goes here...




```

*inputHtmlPath - user input xhtml file path

```java
# HTML content. File extension - xhtml
<!DOCTYPE html>
<html lang="en"
   xmlns="http://www.w3.org/1999/xhtml"
   xmlns:custom="http://www.company.com"
   xmlns:xml="http://www.w3.org/XML/1998/package">
...
<xml:CATALOG>
	<xml:CD>
    <xml:TITLE>Empire Burlesque</xml:TITLE>
    <xml:ARTIST>Bob Dylan</xml:ARTIST>
    <xml:COUNTRY>USA</xml:COUNTRY>
    <xml:COMPANY>Columbia</xml:COMPANY>
    <xml:PRICE>10.90</xml:PRICE>
    <xml:YEAR>1985</xml:YEAR>
  </xml:CD>
...

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = 
          document.GetElementsByTagNameNS("http://www.w3.org/XML/1998/package", "ARTIST");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// Kode pengguna ditempatkan di sini
}
```

# Console output

Ditemukan: 3

Bob Dylan

Bonnie Tyler

Dolly Parton

*inputHtmlPath - user input xhtml file path

### Lihat Juga

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
