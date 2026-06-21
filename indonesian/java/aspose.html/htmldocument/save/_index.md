---
title: "HTMLDocument.Save"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode HTMLDocument. Menyimpan dokumen ke file lokal yang ditentukan oleh url. Semua sumber daya yang digunakan dalam dokumen ini akan disimpan ke folder terdekat yang namanya akan dibangun sebagai output_file_name _files."
type: docs

url: /id/java/com.aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

Menyimpan dokumen ke file lokal yang ditentukan oleh url. Semua sumber daya yang digunakan dalam dokumen ini akan disimpan ke dalam folder bersebelahan, yang namanya akan dibangun sebagai output_file_name + "_files".

```java
public void Save(Url url)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Lokasi [`URL`](../../url/) ke file output. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar jika `url` yang ditentukan bukan URL file lokal yang valid. |

## Catatan

Simpan HTML

Sebagian besar tugas yang perlu Anda lakukan memerlukan penyimpanan dokumen. Setelah Anda memuat file yang ada atau membuat dokumen HTML dari awal, Anda dapat menyimpan perubahan menggunakan salah satu metode HTMLDocument.Save(). Metode-metode tersebut memungkinkan menyimpan HTML ke file lokal yang ditentukan oleh path, URL, atau penyimpanan output. Lihat [dokumentasi](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) untuk mempelajari lebih lanjut tentang penyimpanan.

Metode Save(Url)

Perlu menentukan jalur Url lengkap - 'outputFilePath' untuk penyimpanan dokumen HTML. Konstruktor Url(url) membuat sebuah instance dari kelas [`Url`](../../url/) dengan url yang ditentukan. Kemudian Anda harus melewatkan instance tersebut ke metode Save(Url). Dokumen akan disimpan ke file lokal yang ditentukan oleh url. Semua sumber daya yang digunakan dalam dokumen ini akan disimpan ke folder terdekat, yang namanya akan dibangun sebagai output_file_name + "_files".

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Contoh

```java
import System;
import System.IO;
import Aspose.Html;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
        
	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(new Url(outputFilePath));
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### Lihat Juga

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler) {#save}

Menyimpan konten dokumen dan sumber daya menggunakan [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Handler sumber daya [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |

### Lihat Juga

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_10}

Menyimpan dokumen ke file lokal yang ditentukan oleh path. Semua sumber daya yang digunakan dalam dokumen ini akan disimpan ke dalam folder terdekat, yang namanya akan dibangun sebagai: output_file_name + "_files".

```java
public void Save(String path)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| jalur | String | Jalur sistem file lokal ke file output. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar jika `path` yang ditentukan bukan path file lokal yang valid. |

## Catatan

Simpan HTML

Sebagian besar tugas yang perlu Anda lakukan memerlukan penyimpanan dokumen. Setelah Anda memuat file yang ada atau membuat dokumen HTML dari awal, Anda dapat menyimpan perubahan menggunakan salah satu metode HTMLDocument.Save(). Metode-metode tersebut memungkinkan menyimpan HTML ke file lokal yang ditentukan oleh path, URL, atau penyimpanan output. Lihat [dokumentasi](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) untuk mempelajari lebih lanjut tentang penyimpanan.

Metode Save(String) menerima sebagai parameter jalur sistem file lokal ke file output dan menyimpan dokumen HTML ke file lokal yang ditentukan oleh path. Semua sumber daya yang digunakan dalam dokumen akan disimpan ke folder terdekat.

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Contoh

```java
import System;
import System.IO;
import Aspose.Html;
...
 using (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (outputHtmlPath == null)
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(outputFilePath);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### Lihat Juga

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveFormat) {#save_11}

Menyimpan dokumen ke file lokal yang ditentukan oleh path. Semua sumber daya yang digunakan dalam dokumen ini akan disimpan ke dalam folder bersebelahan, yang namanya akan dibangun sebagai output_file_name + "_files".

```java
public void Save(String path, HTMLSaveFormat saveFormat)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| jalur | String | Jalur file lokal ke file output. |
| saveFormat | HTMLSaveFormat | Format di mana dokumen disimpan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar jika `path` yang ditentukan bukan path file lokal yang valid. |

## Catatan

Simpan HTML

Sebagian besar tugas yang perlu Anda lakukan memerlukan penyimpanan dokumen. Setelah Anda memuat file yang ada atau membuat dokumen HTML dari awal, Anda dapat menyimpan perubahan menggunakan salah satu metode HTMLDocument.Save(). Metode-metode tersebut memungkinkan menyimpan HTML ke file lokal yang ditentukan oleh path, URL, atau penyimpanan output. Lihat [dokumentasi](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) untuk mempelajari lebih lanjut tentang penyimpanan.

Save(String, HTMLSaveFormat) Metode

Metode Save(String, HTMLSaveFormat) mengambil sebagai parameter jalur sistem file lokal ke file output dan saveFormat. Enum [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) menentukan format di mana dokumen disimpan, dapat berupa format HTML, MHTML, dan MD. Metode tersebut menyimpan dokumen HTML dalam format yang ditentukan ke file lokal yang ditentukan oleh jalur. Semua sumber daya yang digunakan dalam dokumen akan disimpan ke dalam folder yang berdekatan.

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Contoh

```java
# HTML input file content
<!DOCTYPE html>
<html lang="en"
   xmlns:xml="http://www.w3.org/XML/1998/package">
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="styles/main.css">
  <title>Title</title>
</head>
<body>
<div id="uniqueIdentifier">Container with ID - identifier</div>
<div class="custom-class">Customized by css class container</div>

<div>
  <p class="pStyle">First styled by pStyle class paragraph</p>
  <p class="pStyle">Second styled by pStyle class paragraph</p>
  <p class="pStyle">Third styled by pStyle class paragraph</p>
  <span class="pStyle">Span styled by pStyle</span>
</div>

<math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>...</mrow>
</math>

<div id="smart class">
  <p id="p1" class="ddd kkk">Paragraph styled by class name =ddd kkk=</p>
  <p id="p2" class="ddd fff">Paragraph styled by class name =ddd fff=</p>
  <p id="p3" class="kkk fff">Paragraph styled by class name =kkk fff=</p>
</div>

</body>
</html>

# C# code
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}
	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(outputFilePath, HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

# Content of result file

MIME-Version: 1.0

Content-Type: Multipart/related; boundary="boundary";type=Text/HTML

--boundary

Content-Type: text/html;

Content-Location: result.mhtml

&lt;!DOCTYPE html&gt;&lt;html lang="en" xmlns:xml="http://www.w3.org/XML/1998/package"&gt;&lt;head&gt;

&lt;meta charset="UTF-8"&gt;

&lt;link rel="stylesheet" href="main.css"&gt;

&lt;title&gt;Judul&lt;/title&gt;

&lt;/head&gt;

&lt;body&gt;

&lt;div id="uniqueIdentifier"&gt;Kontainer dengan ID - identifier&lt;/div&gt;

&lt;div class="custom-class"&gt;Disesuaikan oleh kontainer kelas css&lt;/div&gt;

&lt;div&gt;

&lt;p class="pStyle"&gt;Paragraf pertama yang ditata oleh kelas pStyle&lt;/p&gt;

&lt;p class="pStyle"&gt;Paragraf kedua yang ditata oleh kelas pStyle&lt;/p&gt;

&lt;p class="pStyle"&gt;Paragraf ketiga yang ditata oleh kelas pStyle&lt;/p&gt;

&lt;span class="pStyle"&gt;Span yang ditata oleh pStyle&lt;/span&gt;

&lt;/div&gt;

&lt;math xmlns="http://www.w3.org/1998/Math/MathML"&gt;

&lt;mrow&gt;...&lt;/mrow&gt;

&lt;/math&gt;

&lt;div id="smart class"&gt;

&lt;p id="p1" class="ddd kkk"&gt;Paragraf yang ditata dengan nama kelas =ddd kkk=&lt;/p&gt;

&lt;p id="p2" class="ddd fff"&gt;Paragraf yang ditata dengan nama kelas =ddd fff=&lt;/p&gt;

&lt;p id="p3" class="kkk fff"&gt;Paragraf yang ditata dengan nama kelas =kkk fff=&lt;/p&gt;

&lt;/div&gt;

&lt;div&gt;Halo dari elemen DIV&lt;/div&gt;&lt;/body&gt;&lt;/html&gt;

--boundary

Tipe-Konten: text/css;

Lokasi-Konten: main.css

.custom-class { color: yellow; background-color: blueviolet; margin-top: 10pt; margin-right: 10pt; margin-bottom: 10pt; margin-left: 10pt; }.pStyle { font-

--boundary--

### Lihat Juga

* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

Menyimpan dokumen ke file lokal yang ditentukan oleh url. Semua sumber daya yang digunakan dalam dokumen ini akan disimpan ke dalam folder bersebelahan, yang namanya akan dibangun sebagai output_file_name + "_files".

```java
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL lokal ke file output. |
| saveFormat | HTMLSaveFormat | Format di mana dokumen disimpan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar jika `url` yang ditentukan bukan URL file lokal yang valid. |

## Catatan

Simpan HTML

Sebagian besar tugas yang perlu Anda lakukan memerlukan penyimpanan dokumen. Setelah Anda memuat file yang ada atau membuat dokumen HTML dari awal, Anda dapat menyimpan perubahan menggunakan salah satu metode HTMLDocument.Save(). Metode-metode tersebut memungkinkan menyimpan HTML ke file lokal yang ditentukan oleh path, URL, atau penyimpanan output. Lihat [dokumentasi](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) untuk mempelajari lebih lanjut tentang penyimpanan.

Save(Url, HTMLSaveFormat) Metode

Diperlukan untuk menentukan jalur Url lengkap - 'outputFilePath' untuk penyimpanan dokumen HTML. Konstruktor Url(url) membuat sebuah instance dari kelas [`Url`](../../url/) dengan url yang ditentukan. Enumerasi [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) menentukan format di mana dokumen disimpan, dapat berupa format HTML, MHTML, dan MD. Selanjutnya Anda harus memberikan parameter ke metode Save(url, saveFormat). Dokumen akan disimpan dalam format yang ditentukan ke file lokal yang ditentukan oleh url.

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Contoh

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(new Url(outputFilePath), HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### Lihat Juga

* class [Url](../../url/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveFormat) {#save_1}

Menyimpan konten dokumen dan sumber daya menggunakan [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveFormat saveFormat)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Handler sumber daya [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveFormat | HTMLSaveFormat | Format di mana dokumen disimpan. |

### Lihat Juga

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveOptions) {#save_12}

Menyimpan dokumen ke file lokal yang ditentukan oleh path. Semua sumber daya yang digunakan dalam dokumen ini akan disimpan ke dalam folder terdekat, yang namanya akan dibangun sebagai: output_file_name + "_files".

```java
public void Save(String path, HTMLSaveOptions saveOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| jalur | String | Path lokal ke file output. |
| saveOptions | HTMLSaveOptions | [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) objek digunakan untuk manajemen proses penanganan sumber daya. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar jika `path` yang ditentukan bukan path file lokal yang valid. |

## Catatan

Simpan HTML

Sebagian besar tugas yang perlu Anda lakukan memerlukan penyimpanan dokumen. Setelah Anda memuat file yang ada atau membuat dokumen HTML dari awal, Anda dapat menyimpan perubahan menggunakan salah satu metode HTMLDocument.Save(). Metode-metode tersebut memungkinkan menyimpan HTML ke file lokal yang ditentukan oleh path, URL, atau penyimpanan output. Lihat [dokumentasi](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) untuk mempelajari lebih lanjut tentang penyimpanan.

Save(String, HTMLSaveOptions) Metode

Metode Save(String, HTMLSaveOptions) menerima sebagai parameter jalur sistem file lokal ke file output, sebuah instance dari kelas [HTMLSaveOptions](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/), dan menyimpan dokumen HTML dengan sumber daya ke file lokal yang ditentukan oleh jalur. Konstruktor HTMLSaveOptions() membuat sebuah instance opsi penyimpanan yang memiliki properti [`ResourceHandlingOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) yang digunakan untuk konfigurasi penanganan sumber daya. Semua sumber daya yang digunakan dalam dokumen akan disimpan ke dalam folder bersebelahan.

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Contoh

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// Definisikan instance kelas opsi
	var options = new HTMLSaveOptions();
	// Pembatasan penanganan halaman
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Lihat Juga

* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

Menyimpan dokumen ke file lokal yang ditentukan oleh url. Semua sumber daya yang digunakan dalam dokumen ini akan disimpan ke dalam folder bersebelahan, yang namanya akan dibangun sebagai: output_file_name + "_files".

```java
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Lokasi [`URL`](../../url/) ke file output. |
| saveOptions | HTMLSaveOptions | [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) objek digunakan untuk manajemen proses penanganan sumber daya. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar jika `url` yang ditentukan bukan URL file lokal yang valid. |

## Catatan

Simpan HTML

Sebagian besar tugas yang perlu Anda lakukan memerlukan penyimpanan dokumen. Setelah Anda memuat file yang ada atau membuat dokumen HTML dari awal, Anda dapat menyimpan perubahan menggunakan salah satu metode HTMLDocument.Save(). Metode-metode tersebut memungkinkan menyimpan HTML ke file lokal yang ditentukan oleh path, URL, atau penyimpanan output. Lihat [dokumentasi](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) untuk mempelajari lebih lanjut tentang penyimpanan.

Save(Url, HTMLSaveOptions) Metode

Diperlukan untuk menentukan jalur Url lengkap untuk penyimpanan dokumen HTML. Konstruktor Url(url) membuat sebuah instance dari kelas [`Url`](../../url/) dengan url yang ditentukan. Konstruktor HTMLSaveOptions() membuat sebuah instance dari kelas [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) yang memiliki properti ResourceHandlingOptions yang digunakan untuk konfigurasi penanganan sumber daya. Metode Save(url, saveOptions) menerima parameter dan menyimpan dokumen HTML dengan sumber daya ke file lokal yang ditentukan oleh url.

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Contoh

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// Definisikan instance kelas opsi
	var options = new HTMLSaveOptions();
	// Pembatasan penanganan halaman
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Lihat Juga

* class [Url](../../url/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveOptions) {#save_2}

Menyimpan konten dokumen dan sumber daya menggunakan [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveOptions saveOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Handler sumber daya [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | HTMLSaveOptions | Opsi penyimpanan HTML. |

### Lihat Juga

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MarkdownSaveOptions) {#save_13}

Menyimpan dokumen ke file lokal yang ditentukan oleh path. Semua sumber daya yang digunakan dalam dokumen ini akan disimpan ke dalam folder terdekat, yang namanya akan dibangun sebagai: output_file_name + "_files".

```java
public void Save(String path, MarkdownSaveOptions saveOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| jalur | String | Path lokal ke file output. |
| saveOptions | MarkdownSaveOptions | Penggunaan objek [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Dokumentasi Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options). |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar jika `path` yang ditentukan bukan path file lokal yang valid. |

## Catatan

Simpan HTML

Sebagian besar tugas yang perlu Anda lakukan memerlukan penyimpanan dokumen. Setelah Anda memuat file yang ada atau membuat dokumen HTML dari awal, Anda dapat menyimpan perubahan menggunakan salah satu metode HTMLDocument.Save(). Metode-metode tersebut memungkinkan menyimpan HTML ke file lokal yang ditentukan oleh path, URL, atau penyimpanan output. Lihat [dokumentasi](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) untuk mempelajari lebih lanjut tentang penyimpanan.

Save(String, MarkdownSaveOptions) Metode

Diperlukan untuk menentukan jalur sistem file lokal ke file output untuk penyimpanan dokumen. Konstruktor MarkdownSaveOptions() membuat sebuah instance dari kelas [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) yang memiliki sekumpulan properti. Misalnya, Anda dapat mengatur gaya pemformatan markdown, menggunakan opsi yang kompatibel dengan GitLab Flavored Markdown yang telah ditentukan, dan mengonfigurasi penanganan sumber daya. Metode Save(path, saveOptions) menerima jalur sistem file lokal ke file output dan instance opsi sebagai parameter, serta menyimpan HTML sebagai dokumen Markdown dengan sumber daya ke file lokal yang ditentukan oleh jalur.

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Contoh

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
     
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// Definisikan instance kelas opsi
	var options = new MarkdownSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### Lihat Juga

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

Menyimpan dokumen ke file lokal yang ditentukan oleh url. Semua sumber daya yang digunakan dalam dokumen ini akan disimpan ke dalam folder bersebelahan, yang namanya akan dibangun sebagai: output_file_name + "_files".

```java
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Lokasi [`URL`](../../url/) ke file output. |
| saveOptions | MarkdownSaveOptions | Penggunaan objek [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [dokumentasi](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options). |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar jika `url` yang ditentukan bukan URL file lokal yang valid. |

## Catatan

Simpan HTML

Sebagian besar tugas yang perlu Anda lakukan memerlukan penyimpanan dokumen. Setelah Anda memuat file yang ada atau membuat dokumen HTML dari awal, Anda dapat menyimpan perubahan menggunakan salah satu metode HTMLDocument.Save(). Metode-metode tersebut memungkinkan menyimpan HTML ke file lokal yang ditentukan oleh path, URL, atau penyimpanan output. Lihat [dokumentasi](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) untuk mempelajari lebih lanjut tentang penyimpanan.

Save(Url, MarkdownSaveOptions) Metode

Diperlukan untuk menentukan jalur Url lengkap untuk penyimpanan dokumen. Konstruktor Url(url) membuat sebuah instance dari kelas [`Url`](../../url/) dengan url yang ditentukan. Konstruktor MarkdownSaveOptions() membuat sebuah instance dari kelas [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) yang memiliki sekumpulan properti. Misalnya, Anda dapat mengatur gaya pemformatan Markdown, menggunakan opsi yang kompatibel dengan GitLab Flavored Markdown yang telah ditentukan, dan mengonfigurasi penanganan sumber daya. Metode Save(url, saveOptions) menerima instance url dan opsi penyimpanan sebagai parameter dan menyimpan dokumen dengan sumber daya ke file lokal yang ditentukan oleh url.

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Contoh

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// Definisikan instance kelas opsi
	var options = new MarkdownSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Lihat Juga

* class [Url](../../url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MarkdownSaveOptions) {#save_3}

Menyimpan konten dokumen dan sumber daya menggunakan [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, MarkdownSaveOptions saveOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Handler sumber daya [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MarkdownSaveOptions | Opsi penyimpanan Markdown. |

### Lihat Juga

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MHTMLSaveOptions) {#save_14}

Menyimpan dokumen ke file lokal yang ditentukan oleh path. Semua sumber daya yang digunakan dalam dokumen ini akan disimpan ke dalam folder terdekat, yang namanya akan dibangun sebagai: output_file_name + "_files".

```java
public void Save(String path, MHTMLSaveOptions saveOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| jalur | String | Path lokal ke file output. |
| saveOptions | MHTMLSaveOptions | Penggunaan objek [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [dokumentasi](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options). |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar jika `path` yang ditentukan bukan path file lokal yang valid. |

## Catatan

Simpan HTML

Sebagian besar tugas yang perlu Anda lakukan memerlukan penyimpanan dokumen. Setelah Anda memuat file yang ada atau membuat dokumen HTML dari awal, Anda dapat menyimpan perubahan menggunakan salah satu metode HTMLDocument.Save(). Metode-metode tersebut memungkinkan menyimpan HTML ke file lokal yang ditentukan oleh path, URL, atau penyimpanan output. Lihat [dokumentasi](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) untuk mempelajari lebih lanjut tentang penyimpanan.

Save(String, MHTMLSaveOptions) Metode

Perlu menentukan jalur sistem file lokal ke file output untuk penyimpanan dokumen. Konstruktor MHTMLSaveOptions() menginisialisasi sebuah instance dari kelas [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) yang memiliki properti ResourceHandlingOptions yang digunakan untuk konfigurasi penanganan sumber daya. Metode Save(path, saveOptions) menerima jalur sistem file lokal ke file output dan sebuah instance opsi penyimpanan sebagai parameter serta menyimpan HTML sebagai dokumen MHTML ke file lokal yang ditentukan oleh path.

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Contoh

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// Definisikan instance kelas opsi
	var options = new MHTMLSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Lihat Juga

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

Menyimpan dokumen ke file lokal yang ditentukan oleh url. Semua sumber daya yang digunakan dalam dokumen ini akan disimpan ke dalam folder bersebelahan, yang namanya akan dibangun sebagai: output_file_name + "_files".

```java
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL lokal ke file output. |
| saveOptions | MHTMLSaveOptions | Penggunaan objek [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [dokumentasi](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options). |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilempar jika `url` yang ditentukan bukan URL file lokal yang valid. |

## Catatan

Simpan HTML

Sebagian besar tugas yang perlu Anda lakukan memerlukan penyimpanan dokumen. Setelah Anda memuat file yang ada atau membuat dokumen HTML dari awal, Anda dapat menyimpan perubahan menggunakan salah satu metode HTMLDocument.Save(). Metode-metode tersebut memungkinkan menyimpan HTML ke file lokal yang ditentukan oleh path, URL, atau penyimpanan output. Lihat [dokumentasi](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) untuk mempelajari lebih lanjut tentang penyimpanan.

Save(Url, MHTMLSaveOptions) Metode

Perlu menentukan jalur Url lengkap untuk penyimpanan dokumen. Konstruktor Url(url) membuat sebuah instance dari kelas [`Url`](../../url/) dengan url yang ditentukan. Konstruktor MHTMLSaveOptions() menginisialisasi sebuah instance dari kelas [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) yang memiliki properti ResourceHandlingOptions yang digunakan untuk konfigurasi penanganan sumber daya. Metode Save(url, saveOptions) menerima url dan opsi sebagai parameter serta menyimpan HTML sebagai dokumen MHTML ke file lokal yang ditentukan oleh url.

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Contoh

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// Definisikan instance kelas opsi
	var options = new MHTMLSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input file path.

*outputHtmlPath - user output folder path.

### Lihat Juga

* class [Url](../../url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MHTMLSaveOptions) {#save_4}

Menyimpan konten dokumen dan sumber daya menggunakan [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, MHTMLSaveOptions saveOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Handler sumber daya [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MHTMLSaveOptions | Opsi penyimpanan MHTML. |

### Lihat Juga

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
