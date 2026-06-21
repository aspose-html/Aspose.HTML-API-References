---
title: "Converter.ConvertHTML"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Converter. Mengonversi sumber HTML yang disajikan oleh HTMLDocument. Hasilnya adalah file docx yang dibentuk oleh jalur file output."
type: docs

url: /id/java/com.aspose.html.converters/converter/converthtml/
---
## ConvertHTML(HTMLDocument, DocSaveOptions, String) {#converthtml_1}

Mengonversi sumber HTML yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Hasilnya adalah file docx yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(HTMLDocument document, DocSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | HTMLDocument | Instansi [`HTMLDocument`](../../../com.aspose.html/htmldocument/) sebagai sumber konversi. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Jalur file docx lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi DOCX

File DOCX adalah dokumen Microsoft Word yang biasanya berisi teks tetapi dapat berisi berbagai jenis data, termasuk tabel, grafik raster dan vektor, video, suara, dan diagram. File DOCX sangat dapat diedit, mudah digunakan, dan berukuran terkelola. Format ini populer karena beragam opsi yang ditawarkannya kepada pengguna untuk menulis segala jenis dokumen. Format file ini merupakan salah satu yang paling banyak digunakan dan tersedia melalui banyak program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) gratis daring yang mengonversi HTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	// Form jalur file sumber
	var sourcePath = Path.Combine(InputFolder, "source.html");
	
    // Instansiasi objek konfigurasi default
    var configuration = new Configuration();  

	using (var document = new HTMLDocument(sourcePath, configuration))
	{
		// Tentukan jalur file output
        var resultPath = Path.Combine(OutputFolder, "result.docx");
         
		// Tentukan objek DocSaveOptions default
        var options = new DocSaveOptions();
         
		// Mulai proses konversi dengan objek konfigurasi default
		Converter.ConvertHTML(document, options, resultPath);
	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, DocSaveOptions, String) {#converthtml_23}

Konversi sumber HTML yang disajikan melalui URL. Hasilnya adalah file docx yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(Url url, DocSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL dokumen sumber HTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Jalur file docx lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi DOCX

File DOCX adalah dokumen Microsoft Word yang biasanya berisi teks tetapi dapat berisi berbagai jenis data, termasuk tabel, grafik raster dan vektor, video, suara, dan diagram. File DOCX sangat dapat diedit, mudah digunakan, dan berukuran terkelola. Format ini populer karena beragam opsi yang ditawarkannya kepada pengguna untuk menulis segala jenis dokumen. Format file ini merupakan salah satu yang paling banyak digunakan dan tersedia melalui banyak program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) gratis daring yang mengonversi HTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Buat Url berdasarkan jalur file input
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi
      Converter.ConvertHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, DocSaveOptions, String) {#converthtml_12}

Konversi sumber HTML yang disajikan melalui URL. Hasilnya adalah file docx yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL dokumen sumber HTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Jalur file docx lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi DOCX

File DOCX adalah dokumen Microsoft Word yang biasanya berisi teks tetapi dapat berisi berbagai jenis data, termasuk tabel, grafik raster dan vektor, video, suara, dan diagram. File DOCX sangat dapat diedit, mudah digunakan, dan berukuran terkelola. Format ini populer karena beragam opsi yang ditawarkannya kepada pengguna untuk menulis segala jenis dokumen. Format file ini merupakan salah satu yang paling banyak digunakan dan tersedia melalui banyak program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) gratis daring yang mengonversi HTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Buat Url berdasarkan jalur file input
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi dengan objek konfigurasi default
      Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, DocSaveOptions, String) {#converthtml_45}

Konversi sumber HTML yang disajikan melalui jalur file lengkap menjadi DOCX. Hasilnya adalah file docx yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file lengkap Html. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Jalur file docx lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi DOCX

File DOCX adalah dokumen Microsoft Word yang biasanya berisi teks tetapi dapat berisi berbagai jenis data, termasuk tabel, grafik raster dan vektor, video, suara, dan diagram. File DOCX sangat dapat diedit, mudah digunakan, dan berukuran terkelola. Format ini populer karena beragam opsi yang ditawarkannya kepada pengguna untuk menulis segala jenis dokumen. Format file ini merupakan salah satu yang paling banyak digunakan dan tersedia melalui banyak program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) gratis daring yang mengonversi HTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi
      Converter.ConvertHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, DocSaveOptions, String) {#converthtml_34}

Konversi sumber HTML yang disajikan melalui jalur file lengkap menjadi DOCX. Hasilnya adalah file docx yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file lengkap Html. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Jalur file docx lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi DOCX

File DOCX adalah dokumen Microsoft Word yang biasanya berisi teks tetapi dapat berisi berbagai jenis data, termasuk tabel, grafik raster dan vektor, video, suara, dan diagram. File DOCX sangat dapat diedit, mudah digunakan, dan berukuran terkelola. Format ini populer karena beragam opsi yang ditawarkannya kepada pengguna untuk menulis segala jenis dokumen. Format file ini merupakan salah satu yang paling banyak digunakan dan tersedia melalui banyak program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) gratis daring yang mengonversi HTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Form jalur file sumber
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Form jalur file hasil
   var resultPath = Path.Combine(OutputFolder, "result.docx");

   // Tentukan objek DocSaveOptions default
   var options = new DocSaveOptions();

   // Mulai proses konversi dengan konfigurasi default
   Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, DocSaveOptions, String) {#converthtml_67}

Konversi sumber HTML yang disajikan melalui konten inline. Hasilnya adalah file docx yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten html inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Jalur file docx lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi DOCX

File DOCX adalah dokumen Microsoft Word yang biasanya berisi teks tetapi dapat berisi berbagai jenis data, termasuk tabel, grafik raster dan vektor, video, suara, dan diagram. File DOCX sangat dapat diedit, mudah digunakan, dan berukuran terkelola. Format ini populer karena beragam opsi yang ditawarkannya kepada pengguna untuk menulis segala jenis dokumen. Format file ini merupakan salah satu yang paling banyak digunakan dan tersedia melalui banyak program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) gratis daring yang mengonversi HTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Bentuk konten html inline		
	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";
	
	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result.docx");

	// Tentukan objek DocSaveOptions default
   	var options = new DocSaveOptions();

	// Mulai proses konversi
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, DocSaveOptions, String) {#converthtml_56}

Konversi sumber HTML yang disajikan melalui konten inline. Hasilnya adalah file docx yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten html inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| outputPath | String | Jalur file docx lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi DOCX

File DOCX adalah dokumen Microsoft Word yang biasanya berisi teks tetapi dapat berisi berbagai jenis data, termasuk tabel, grafik raster dan vektor, video, suara, dan diagram. File DOCX sangat dapat diedit, mudah digunakan, dan berukuran terkelola. Format ini populer karena beragam opsi yang ditawarkannya kepada pengguna untuk menulis segala jenis dokumen. Format file ini merupakan salah satu yang paling banyak digunakan dan tersedia melalui banyak program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) gratis daring yang mengonversi HTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Bentuk konten html inline		
	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";
	
	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result.docx");
	
	// Tentukan objek DocSaveOptions default
   	var options = new DocSaveOptions();

	// Mulai proses konversi dengan konfigurasi default
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, DocSaveOptions, ICreateStreamProvider) {#converthtml}

Konversi sumber HTML yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(HTMLDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | HTMLDocument | Sumber konversi yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Cara mengonversi HTML ke DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi DOCX

File DOCX adalah dokumen Microsoft Word yang biasanya berisi teks tetapi dapat berisi berbagai jenis data, termasuk tabel, grafik raster dan vektor, video, suara, dan diagram. File DOCX sangat dapat diedit, mudah digunakan, dan berukuran terkelola. Format ini populer karena beragam opsi yang ditawarkannya kepada pengguna untuk menulis segala jenis dokumen. Format file ini merupakan salah satu yang paling banyak digunakan dan tersedia melalui banyak program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) gratis daring yang mengonversi HTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// Tentukan konten html inline
      	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

      	// Instansiasi objek konfigurasi default
      	var configuration = new Configuration();

      	// Buat dokumen HTML dengan salah satu dari beberapa cara
      	using (var document = new HTMLDocument(content, String.Empty, configuration))
     	 {
        	// Tentukan jalur file hasil tanpa ekstensi
        	var resultPath = Path.Combine(OutputFolder, "result");

        	// Gunakan salah satu implementasi ICreateStreamProvider
        	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

			// Tentukan objek DocSaveOptions default
			var options = new DocSaveOptions();

        	// Mulai proses konversi
        	Converter.ConvertHTML(document, options, provider);
      	}
```

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, DocSaveOptions, ICreateStreamProvider) {#converthtml_22}

Konversi sumber HTML yang disajikan oleh URL. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL dokumen sumber HTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Cara mengonversi HTML ke DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi DOCX

File DOCX adalah dokumen Microsoft Word yang biasanya berisi teks tetapi dapat berisi berbagai jenis data, termasuk tabel, grafik raster dan vektor, video, suara, dan diagram. File DOCX sangat dapat diedit, mudah digunakan, dan berukuran terkelola. Format ini populer karena beragam opsi yang ditawarkannya kepada pengguna untuk menulis segala jenis dokumen. Format file ini merupakan salah satu yang paling banyak digunakan dan tersedia melalui banyak program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) gratis daring yang mengonversi HTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 	 
 	  // Bentuk URL sumber
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Tentukan jalur file hasil tanpa ekstensi
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gunakan implementasi ICreateStreamProvider yang dikenal
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi
      Converter.ConvertHTML(sourceUrl, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_11}

Konversi sumber HTML yang disajikan oleh URL. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL dokumen sumber HTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Cara mengonversi HTML ke DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi DOCX

File DOCX adalah dokumen Microsoft Word yang biasanya berisi teks tetapi dapat berisi berbagai jenis data, termasuk tabel, grafik raster dan vektor, video, suara, dan diagram. File DOCX sangat dapat diedit, mudah digunakan, dan berukuran terkelola. Format ini populer karena beragam opsi yang ditawarkannya kepada pengguna untuk menulis segala jenis dokumen. Format file ini merupakan salah satu yang paling banyak digunakan dan tersedia melalui banyak program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) gratis daring yang mengonversi HTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 	 
   // Bentuk URL sumber
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Tentukan jalur file hasil tanpa ekstensi
   var resultPath = Path.Combine(OutputFolder, "result");

   // Gunakan implementasi ICreateStreamProvider yang dikenal
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Tentukan objek DocSaveOptions default
   var options = new DocSaveOptions();

   // Mulai proses konversi dengan konfigurasi default
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, DocSaveOptions, ICreateStreamProvider) {#converthtml_44}

Konversi sumber HTML yang disajikan oleh jalur file lengkap ke DOCX. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file lengkap Html. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Cara mengonversi HTML ke DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi DOCX

File DOCX adalah dokumen Microsoft Word yang biasanya berisi teks tetapi dapat berisi berbagai jenis data, termasuk tabel, grafik raster dan vektor, video, suara, dan diagram. File DOCX sangat dapat diedit, mudah digunakan, dan berukuran terkelola. Format ini populer karena beragam opsi yang ditawarkannya kepada pengguna untuk menulis segala jenis dokumen. Format file ini merupakan salah satu yang paling banyak digunakan dan tersedia melalui banyak program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) gratis daring yang mengonversi HTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Bentuk jalur file html sumber
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Tentukan jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gunakan implementasi ICreateStreamProvider default
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi
      Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_33}

Konversi sumber HTML yang disajikan oleh jalur file lengkap ke DOCX. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file lengkap Html. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) khusus. |

## Catatan

Cara mengonversi HTML ke DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi DOCX

File DOCX adalah dokumen Microsoft Word yang biasanya berisi teks tetapi dapat berisi berbagai jenis data, termasuk tabel, grafik raster dan vektor, video, suara, dan diagram. File DOCX sangat dapat diedit, mudah digunakan, dan berukuran terkelola. Format ini populer karena beragam opsi yang ditawarkannya kepada pengguna untuk menulis segala jenis dokumen. Format file ini merupakan salah satu yang paling banyak digunakan dan tersedia melalui banyak program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) gratis daring yang mengonversi HTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Bentuk jalur file html sumber
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Tentukan jalur file hasil
   var resultPath = Path.Combine(OutputFolder, "result");

   // Gunakan implementasi ICreateStreamProvider default
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Tentukan objek DocSaveOptions default
   var options = new DocSaveOptions();

   // Mulai proses konversi dengan objek konfigurasi default
   Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, DocSaveOptions, ICreateStreamProvider) {#converthtml_66}

Konversi sumber HTML yang disajikan oleh konten inline ke DOCX. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten html inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Cara mengonversi HTML ke DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi DOCX

File DOCX adalah dokumen Microsoft Word yang biasanya berisi teks tetapi dapat berisi berbagai jenis data, termasuk tabel, grafik raster dan vektor, video, suara, dan diagram. File DOCX sangat dapat diedit, mudah digunakan, dan berukuran terkelola. Format ini populer karena beragam opsi yang ditawarkannya kepada pengguna untuk menulis segala jenis dokumen. Format file ini merupakan salah satu yang paling banyak digunakan dan tersedia melalui banyak program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) gratis daring yang mengonversi HTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	  // Bentuk konten html inline
      var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

      // Tentukan jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gunakan implementasi ICreateStreamProvider yang berorientasi file lokal yang dikenal
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // Instansiasi objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi
      Converter.ConvertHTML(content, String.Empty, options, provider);





```

*OutputFolder - user output file path.

### Lihat Juga

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_55}

Konversi sumber HTML yang disajikan oleh konten inline ke DOCX. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten html inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) khusus. |

## Catatan

Cara mengonversi HTML ke DOCX

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi DOCX

File DOCX adalah dokumen Microsoft Word yang biasanya berisi teks tetapi dapat berisi berbagai jenis data, termasuk tabel, grafik raster dan vektor, video, suara, dan diagram. File DOCX sangat dapat diedit, mudah digunakan, dan berukuran terkelola. Format ini populer karena beragam opsi yang ditawarkannya kepada pengguna untuk menulis segala jenis dokumen. Format file ini merupakan salah satu yang paling banyak digunakan dan tersedia melalui banyak program.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke DOCX

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) gratis daring yang mengonversi HTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	 // Bentuk konten html inline
   var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

   // Tentukan jalur file hasil
   var resultPath = Path.Combine(OutputFolder, "result");

   // Gunakan implementasi ICreateStreamProvider yang berorientasi file lokal yang dikenal
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Instansiasi objek DocSaveOptions default
   var options = new DocSaveOptions();

   // Mulai proses konversi dengan konfigurasi default
   Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);





```

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, PdfSaveOptions, String) {#converthtml_7}

Konversi sumber HTML yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Hasilnya adalah file pdf yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(HTMLDocument document, PdfSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | HTMLDocument | Sumber konversi yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut, lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Jalur file pdf lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi PDF

Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan format file ini adalah memperkenalkan standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. File PDF adalah sekumpulan byte yang dapat dikelompokkan menjadi token sesuai aturan sintaks yang ditetapkan oleh spesifikasi PDF. Satu atau lebih token digabungkan menjadi entitas sintaks tingkat tinggi, terutama objek, yang merupakan nilai data dasar dari mana sebuah dokumen PDF dibangun.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Konversi format populer lainnya

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi.Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Konverter HTML daring

Aspose.HTML menawarkan [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) daring gratis yang mengonversi HTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
 	  // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Instansiasi objek konfigurasi default
      var configuration = new Configuration();

      // Buat dokumen html dengan salah satu dari beberapa cara
      using (var document = new HTMLDocument(sourcePath, configuration))
      {
		// Form jalur file hasil
        var resultPath = Path.Combine(OutputFolder, "result.pdf");

        // Tentukan objek PdfSaveOptions default
        var options = new PdfSaveOptions();

		// Instansiasi proses konversi
        Converter.ConvertHTML(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, PdfSaveOptions, String) {#converthtml_29}

Konversi sumber HTML yang disajikan melalui URL. Hasilnya adalah file pdf yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(Url url, PdfSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL dokumen sumber HTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut, lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Jalur file pdf lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi PDF

Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan format file ini adalah memperkenalkan standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. File PDF adalah sekumpulan byte yang dapat dikelompokkan menjadi token sesuai aturan sintaks yang ditetapkan oleh spesifikasi PDF. Satu atau lebih token digabungkan menjadi entitas sintaks tingkat tinggi, terutama objek, yang merupakan nilai data dasar dari mana sebuah dokumen PDF dibangun.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Konversi format populer lainnya

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi.Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Konverter HTML daring

Aspose.HTML menawarkan [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) daring gratis yang mengonversi HTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...      
      // Bentuk Url sumber berbasis file
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Mulai proses konversi
      Converter.ConvertHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, PdfSaveOptions, String) {#converthtml_18}

Konversi sumber HTML yang disajikan melalui URL. Hasilnya adalah file pdf yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL dokumen sumber HTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut, lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Jalur file pdf lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi PDF

Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan format file ini adalah memperkenalkan standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. File PDF adalah sekumpulan byte yang dapat dikelompokkan menjadi token sesuai aturan sintaks yang ditetapkan oleh spesifikasi PDF. Satu atau lebih token digabungkan menjadi entitas sintaks tingkat tinggi, terutama objek, yang merupakan nilai data dasar dari mana sebuah dokumen PDF dibangun.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Konversi format populer lainnya

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi.Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Konverter HTML daring

Aspose.HTML menawarkan [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) daring gratis yang mengonversi HTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...    
   // Bentuk Url sumber berbasis file
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Form jalur file hasil
   var resultPath = Path.Combine(OutputFolder, "result.pdf");

   // Tentukan objek PdfSaveOptions default
   var options = new PdfSaveOptions();

   // Mulai proses konversi dengan objek konfigurasi default
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, PdfSaveOptions, String) {#converthtml_51}

Konversi sumber HTML yang disajikan melalui jalur file lengkap menjadi PDF. Hasilnya adalah file pdf yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file lengkap Html. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut, lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Jalur file pdf lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi PDF

Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan format file ini adalah memperkenalkan standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. File PDF adalah sekumpulan byte yang dapat dikelompokkan menjadi token sesuai aturan sintaks yang ditetapkan oleh spesifikasi PDF. Satu atau lebih token digabungkan menjadi entitas sintaks tingkat tinggi, terutama objek, yang merupakan nilai data dasar dari mana sebuah dokumen PDF dibangun.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Konversi format populer lainnya

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi.Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Konverter HTML daring

Aspose.HTML menawarkan [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) daring gratis yang mengonversi HTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Form jalur file sumber
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Form jalur file hasil
   var resultPath = Path.Combine(OutputFolder, "result.pdf");

   // Tentukan objek PdfSaveOptions default
   var options = new PdfSaveOptions();

   // Mulai proses konversi
   Converter.ConvertHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, PdfSaveOptions, String) {#converthtml_40}

Konversi sumber HTML yang disajikan melalui jalur file lengkap menjadi PDF. Hasilnya adalah file pdf yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file lengkap Html. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut, lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Jalur file pdf lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi PDF

Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan format file ini adalah memperkenalkan standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. File PDF adalah sekumpulan byte yang dapat dikelompokkan menjadi token sesuai aturan sintaks yang ditetapkan oleh spesifikasi PDF. Satu atau lebih token digabungkan menjadi entitas sintaks tingkat tinggi, terutama objek, yang merupakan nilai data dasar dari mana sebuah dokumen PDF dibangun.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Konversi format populer lainnya

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi.Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Konverter HTML daring

Aspose.HTML menawarkan [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) daring gratis yang mengonversi HTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
  // Form jalur file sumber
  var sourcePath = Path.Combine(InputFolder, "source.html");

  // Form jalur file hasil
  var resultPath = Path.Combine(OutputFolder, "result.pdf");

  // Tentukan objek PdfSaveOptions default
  var options = new PdfSaveOptions();

  // Mulai proses konversi dengan konfigurasi default
  Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, PdfSaveOptions, String) {#converthtml_73}

Konversi sumber HTML yang disajikan melalui konten inline ke PDF. Hasilnya adalah file pdf yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten html inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut, lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Jalur file pdf lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi PDF

Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan format file ini adalah memperkenalkan standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. File PDF adalah sekumpulan byte yang dapat dikelompokkan menjadi token sesuai aturan sintaks yang ditetapkan oleh spesifikasi PDF. Satu atau lebih token digabungkan menjadi entitas sintaks tingkat tinggi, terutama objek, yang merupakan nilai data dasar dari mana sebuah dokumen PDF dibangun.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Konversi format populer lainnya

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi.Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Konverter HTML daring

Aspose.HTML menawarkan [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) daring gratis yang mengonversi HTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Bentuk konten html inline		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result.pdf");

	// Tentukan objek PdfSaveOptions default
   	var options = new PdfSaveOptions();

	// Mulai proses konversi
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, PdfSaveOptions, String) {#converthtml_62}

Konversi sumber HTML yang disajikan melalui konten inline ke PDF. Hasilnya adalah file pdf yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten html inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut, lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| outputPath | String | Jalur file pdf lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi PDF

Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan format file ini adalah memperkenalkan standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. File PDF adalah sekumpulan byte yang dapat dikelompokkan menjadi token sesuai aturan sintaks yang ditetapkan oleh spesifikasi PDF. Satu atau lebih token digabungkan menjadi entitas sintaks tingkat tinggi, terutama objek, yang merupakan nilai data dasar dari mana sebuah dokumen PDF dibangun.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Konversi format populer lainnya

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi.Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Konverter HTML daring

Aspose.HTML menawarkan [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) daring gratis yang mengonversi HTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Bentuk konten html inline		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result.pdf");

	// Tentukan objek PdfSaveOptions default
  	var options = new PdfSaveOptions();

	// Mulai proses konversi dengan konfigurasi default
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, PdfSaveOptions, ICreateStreamProvider) {#converthtml_6}

Konversi sumber HTML yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/) ke PDF. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(HTMLDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | HTMLDocument | Sumber konversi yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut, lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) khusus. |

## Catatan

Cara mengonversi HTML ke PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi PDF

Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan format file ini adalah memperkenalkan standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. File PDF adalah sekumpulan byte yang dapat dikelompokkan menjadi token sesuai aturan sintaks yang ditetapkan oleh spesifikasi PDF. Satu atau lebih token digabungkan menjadi entitas sintaks tingkat tinggi, terutama objek, yang merupakan nilai data dasar dari mana sebuah dokumen PDF dibangun.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Konversi format populer lainnya

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi.Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Konverter HTML daring

Aspose.HTML menawarkan [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) daring gratis yang mengonversi HTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Tentukan konten html inline
   	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

   	// Instansiasi objek konfigurasi default
   	var configuration = new Configuration();

   	// Buat dokumen HTML dengan salah satu dari beberapa cara
   	using (var document = new HTMLDocument(content, String.Empty, configuration))
   	{
		// Tentukan jalur file hasil tanpa ekstensi
		var resultPath = Path.Combine(OutputFolder, "result");

		// Gunakan salah satu implementasi ICreateStreamProvider
		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

		// Tentukan objek PdfSaveOptions default
		var options = new PdfSaveOptions();

		// Mulai proses konversi
		Converter.ConvertHTML(document, options, provider);
   	}
```

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#converthtml_28}

Konversi sumber HTML yang disajikan oleh URL. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL dokumen sumber HTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut, lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Cara mengonversi HTML ke PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi PDF

Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan format file ini adalah memperkenalkan standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. File PDF adalah sekumpulan byte yang dapat dikelompokkan menjadi token sesuai aturan sintaks yang ditetapkan oleh spesifikasi PDF. Satu atau lebih token digabungkan menjadi entitas sintaks tingkat tinggi, terutama objek, yang merupakan nilai data dasar dari mana sebuah dokumen PDF dibangun.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Konversi format populer lainnya

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi.Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Konverter HTML daring

Aspose.HTML menawarkan [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) daring gratis yang mengonversi HTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Buat Url berdasarkan jalur file input
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Form jalur file hasil
   var resultPath = Path.Combine(OutputFolder, "result");

   // Gunakan salah satu implementasi ICreateStreamProvider
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Tentukan objek PdfSaveOptions default
   var options = new PdfSaveOptions();

   // Mulai proses konversi
   Converter.ConvertHTML(sourceUrl, options, provider);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_17}

Konversi sumber HTML yang disajikan oleh URL. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL dokumen sumber HTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut, lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) khusus. |

## Catatan

Cara mengonversi HTML ke PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi PDF

Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan format file ini adalah memperkenalkan standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. File PDF adalah sekumpulan byte yang dapat dikelompokkan menjadi token sesuai aturan sintaks yang ditetapkan oleh spesifikasi PDF. Satu atau lebih token digabungkan menjadi entitas sintaks tingkat tinggi, terutama objek, yang merupakan nilai data dasar dari mana sebuah dokumen PDF dibangun.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Konversi format populer lainnya

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi.Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Konverter HTML daring

Aspose.HTML menawarkan [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) daring gratis yang mengonversi HTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Buat Url berdasarkan jalur file input
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // Form jalur file hasil
   var resultPath = Path.Combine(OutputFolder, "result ");

   // Gunakan salah satu implementasi ICreateStreamProvider
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Tentukan objek PdfSaveOptions default
   var options = new PdfSaveOptions();

   // Mulai proses konversi dengan konfigurasi default
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, PdfSaveOptions, ICreateStreamProvider) {#converthtml_50}

Konversi sumber HTML yang disajikan oleh jalur file lengkap ke PDF. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file lengkap Html. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut, lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Cara mengonversi HTML ke PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi PDF

Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan format file ini adalah memperkenalkan standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. File PDF adalah sekumpulan byte yang dapat dikelompokkan menjadi token sesuai aturan sintaks yang ditetapkan oleh spesifikasi PDF. Satu atau lebih token digabungkan menjadi entitas sintaks tingkat tinggi, terutama objek, yang merupakan nilai data dasar dari mana sebuah dokumen PDF dibangun.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Konversi format populer lainnya

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi.Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Konverter HTML daring

Aspose.HTML menawarkan [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) daring gratis yang mengonversi HTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // Buat jalur file sumber
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // Form jalur file hasil
   var resultPath = Path.Combine(OutputFolder, "result");

   // Gunakan salah satu implementasi ICreateStreamProvider
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // Tentukan objek PdfSaveOptions default
   var options = new PdfSaveOptions();

   // Mulai proses konversi
   Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_39}

Konversi sumber HTML yang disajikan oleh jalur file lengkap ke PDF. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file lengkap Html. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut, lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) khusus. |

## Catatan

Cara mengonversi HTML ke PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi PDF

Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan format file ini adalah memperkenalkan standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. File PDF adalah sekumpulan byte yang dapat dikelompokkan menjadi token sesuai aturan sintaks yang ditetapkan oleh spesifikasi PDF. Satu atau lebih token digabungkan menjadi entitas sintaks tingkat tinggi, terutama objek, yang merupakan nilai data dasar dari mana sebuah dokumen PDF dibangun.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Konversi format populer lainnya

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi.Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Konverter HTML daring

Aspose.HTML menawarkan [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) daring gratis yang mengonversi HTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
  // Buat jalur file sumber
  var sourcePath = Path.Combine(InputFolder, "source.html");

  // Form jalur file hasil
  var resultPath = Path.Combine(OutputFolder, "result");

  // Gunakan salah satu implementasi ICreateStreamProvider
  ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

  // Tentukan objek PdfSaveOptions default
  var options = new PdfSaveOptions();

  // Mulai proses konversi dengan konfigurasi default
  Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, PdfSaveOptions, ICreateStreamProvider) {#converthtml_72}

Konversi sumber HTML yang disajikan oleh konten inline ke PDF. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten html inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut, lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka khusus [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Catatan

Cara mengonversi HTML ke PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi PDF

Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan format file ini adalah memperkenalkan standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. File PDF adalah sekumpulan byte yang dapat dikelompokkan menjadi token sesuai aturan sintaks yang ditetapkan oleh spesifikasi PDF. Satu atau lebih token digabungkan menjadi entitas sintaks tingkat tinggi, terutama objek, yang merupakan nilai data dasar dari mana sebuah dokumen PDF dibangun.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Konversi format populer lainnya

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi.Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Konverter HTML daring

Aspose.HTML menawarkan [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) daring gratis yang mengonversi HTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Bentuk konten html inline		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result");

	// Gunakan salah satu implementasi ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Tentukan objek PdfSaveOptions default
  	var options = new PdfSaveOptions();

	// Mulai proses konversi
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_61}

Konversi sumber HTML yang disajikan oleh konten inline ke PDF. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten html inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut, lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Cara mengonversi HTML ke PDF

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi PDF

Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan format file ini adalah memperkenalkan standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. File PDF adalah sekumpulan byte yang dapat dikelompokkan menjadi token sesuai aturan sintaks yang ditetapkan oleh spesifikasi PDF. Satu atau lebih token digabungkan menjadi entitas sintaks tingkat tinggi, terutama objek, yang merupakan nilai data dasar dari mana sebuah dokumen PDF dibangun.

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

Konversi format populer lainnya

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke PDF

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi.Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Konverter HTML daring

Aspose.HTML menawarkan [HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) daring gratis yang mengonversi HTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Bentuk konten html inline		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result");

	// Gunakan salah satu implementasi ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Tentukan objek PdfSaveOptions default
 	var options = new PdfSaveOptions();

	// Mulai proses konversi dengan konfigurasi default
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, MHTMLSaveOptions, String) {#converthtml_5}

Konversi sumber HTML yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Hasilnya adalah file mhtml (.mht) yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(HTMLDocument document, MHTMLSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | HTMLDocument | Sumber konversi yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | MHTMLSaveOptions | Penggunaan objek [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Jalur file mhtml (.mht) lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Konversi format populer lainnya

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apa pun.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi.Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil MHTML dengan tiga atau lebih parameter tergantung pada skenario pengguna.Konverter HTML daring

Aspose.HTML menawarkan [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) daring gratis yang mengonversi HTML ke MHTML dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Bentuk dokumen HTML
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Buat dokumen HTML dengan salah satu dari beberapa cara
	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
	{
		// Tentukan objek MHTMLSaveOptions default
 		var options = new MHTMLSaveOptions();

		// Form jalur file hasil
		var resultPath = Path.Combine(OutputFolder, "result.mht");

		// Mulai proses konversi
 		Converter.ConvertHTML(document, options, resultPath);
}
```

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, MHTMLSaveOptions, String) {#converthtml_27}

Konversi sumber HTML yang disajikan melalui URL. Hasilnya adalah file mhtml (.mht) yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(Url url, MHTMLSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL dokumen sumber HTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | MHTMLSaveOptions | Penggunaan objek [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Jalur file mhtml (.mht) lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Konversi format populer lainnya

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apa pun.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi.Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil MHTML dengan tiga atau lebih parameter tergantung pada skenario pengguna.Konverter HTML daring

Aspose.HTML menawarkan [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) daring gratis yang mengonversi HTML ke MHTML dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Buat Url berdasarkan jalur file input
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

	// Tentukan objek MHTMLSaveOptions default
	var options = new MHTMLSaveOptions();

	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Mulai proses konversi
	Converter.ConvertHTML(sourceUrl, options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, MHTMLSaveOptions, String) {#converthtml_16}

Konversi sumber HTML yang disajikan melalui URL. Hasilnya adalah file mhtml (.mht) yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(Url url, Configuration configuration, MHTMLSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL dokumen sumber HTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | MHTMLSaveOptions | Penggunaan objek [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Jalur file mhtml (.mht) lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Konversi format populer lainnya

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apa pun.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi.Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil MHTML dengan tiga atau lebih parameter tergantung pada skenario pengguna.Konverter HTML daring

Aspose.HTML menawarkan [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) daring gratis yang mengonversi HTML ke MHTML dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Buat Url berdasarkan jalur file input
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

	// Tentukan objek MHTMLSaveOptions default
	var options = new MHTMLSaveOptions();

	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Mulai proses konversi dengan konfigurasi default
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, MHTMLSaveOptions, String) {#converthtml_49}

Konversi sumber HTML yang disajikan melalui jalur file lengkap menjadi MHTML. Hasilnya adalah file mhtml (.mht) yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String sourcePath, MHTMLSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file HTML. Jalur ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | MHTMLSaveOptions | Penggunaan objek [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Jalur file mhtml (.mht) lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Konversi format populer lainnya

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apa pun.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi.Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil MHTML dengan tiga atau lebih parameter tergantung pada skenario pengguna.Konverter HTML daring

Aspose.HTML menawarkan [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) daring gratis yang mengonversi HTML ke MHTML dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Form jalur file sumber
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Tentukan objek MHTMLSaveOptions default
	var options = new MHTMLSaveOptions();

	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Mulai proses konversi
	Converter.ConvertHTML(sourcePath, options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, MHTMLSaveOptions, String) {#converthtml_38}

Konversi sumber HTML yang disajikan melalui jalur file lengkap menjadi MHTML. Hasilnya adalah file mhtml (.mht) yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    MHTMLSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file lengkap Html. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | MHTMLSaveOptions | Penggunaan objek [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Jalur file mhtml (.mht) lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Konversi format populer lainnya

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apa pun.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi.Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil MHTML dengan tiga atau lebih parameter tergantung pada skenario pengguna.Konverter HTML daring

Aspose.HTML menawarkan [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) daring gratis yang mengonversi HTML ke MHTML dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Form jalur file sumber
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Tentukan objek MHTMLSaveOptions default
	var options = new MHTMLSaveOptions();

	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// Mulai proses konversi dengan konfigurasi default
	Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, MHTMLSaveOptions, String) {#converthtml_71}

Konversi sumber HTML yang disajikan melalui konten inline ke MHTML. Hasilnya adalah file mhtml (.mht) yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String content, String baseUri, MHTMLSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten html inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | MHTMLSaveOptions | Penggunaan objek [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Jalur file mhtml (.mht) lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Konversi format populer lainnya

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apa pun.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi.Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil MHTML dengan tiga atau lebih parameter tergantung pada skenario pengguna.Konverter HTML daring

Aspose.HTML menawarkan [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) daring gratis yang mengonversi HTML ke MHTML dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Bentuk konten html inline		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result");

	// Tentukan objek opsi penyimpanan default
  	var options = new MHTMLSaveOptions();

	// Mulai proses konversi
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, MHTMLSaveOptions, String) {#converthtml_60}

Konversi sumber HTML yang disajikan melalui konten inline ke MHTML. Hasilnya adalah file mhtml (.mht) yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    MHTMLSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten html inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | MHTMLSaveOptions | Penggunaan objek [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions). |
| outputPath | String | Jalur file mhtml (.mht) lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke MHTML

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi MHTML

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

Konversi format populer lainnya

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke MHTML

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil MHTML dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) daring gratis yang mengonversi HTML ke MHTML dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Bentuk konten html inline		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result");

	// Tentukan objek opsi penyimpanan default
 	var options = new MHTMLSaveOptions();

	// Mulai proses konversi dengan konfigurasi default
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, MarkdownSaveOptions, String) {#converthtml_4}

Konversi sumber HTML yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Hasilnya adalah file markdown (.md) yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(HTMLDocument document, MarkdownSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | HTMLDocument | Sumber konversi yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | MarkdownSaveOptions | Penggunaan objek [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Jalur file md lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konversi format populer lainnya

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil Markdown dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) daring gratis yang mengonversi HTML ke MD dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// Form jalur file sumber
		var sourcePath = Path.Combine(InputFolder, "source.html");
       
      	// Form jalur file hasil
      	var outputPath = Path.Combine(OutputFolder, "result.md");

		using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
		{
			// Tentukan instance objek opsi penyimpanan
			var options = new MarkdownSaveOptions();

			// Mulai proses konversi
			Converter.ConvertHTML(document, options, outputPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, MarkdownSaveOptions, String) {#converthtml_26}

Konversi sumber HTML yang disajikan melalui URL. Hasilnya adalah file markdown (.md) yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(Url url, MarkdownSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL dokumen sumber HTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | MarkdownSaveOptions | Penggunaan objek [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Jalur file md lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konversi format populer lainnya

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil Markdown dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) daring gratis yang mengonversi HTML ke MD dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Buat Url berdasarkan jalur file input
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));
    
   	// Form jalur file hasil
   	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Tentukan instance objek opsi penyimpanan
	var options = new MarkdownSaveOptions();

	// Mulai proses konversi
	Converter.ConvertHTML(sourceUrl, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, MarkdownSaveOptions, String) {#converthtml_15}

Konversi sumber HTML yang disajikan melalui URL. Hasilnya adalah file markdown (.md) yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(Url url, Configuration configuration, MarkdownSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL dokumen sumber HTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | MarkdownSaveOptions | Penggunaan objek [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Jalur file md lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konversi format populer lainnya

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil Markdown dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) daring gratis yang mengonversi HTML ke MD dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Buat Url berdasarkan jalur file input
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));
   
  	// Form jalur file hasil
  	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Tentukan instance objek opsi penyimpanan
	var options = new MarkdownSaveOptions();

	// Mulai proses konversi dengan konfigurasi default
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, MarkdownSaveOptions, String) {#converthtml_48}

Konversi sumber HTML yang disajikan melalui jalur file lengkap menjadi Markdown. Hasilnya adalah file markdown (.md) yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String sourcePath, MarkdownSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file HTML. Jalur ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | MarkdownSaveOptions | Penggunaan objek [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Jalur file md lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konversi format populer lainnya

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil Markdown dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) daring gratis yang mengonversi HTML ke MD dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Form jalur file sumber
	var sourcePath = Path.Combine(InputFolder, "source.html");
    
   	// Form jalur file hasil
   	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Tentukan instance objek opsi penyimpanan
	var options = new MarkdownSaveOptions();

	// Mulai proses konversi
	Converter.ConvertHTML(sourcePath, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, MarkdownSaveOptions, String) {#converthtml_37}

Konversi sumber HTML yang disajikan melalui jalur file lengkap menjadi Markdown. Hasilnya adalah file markdown (.md) yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    MarkdownSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file HTML. Jalur ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | MarkdownSaveOptions | Penggunaan objek [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Jalur file md lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konversi format populer lainnya

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil Markdown dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) daring gratis yang mengonversi HTML ke MD dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Form jalur file sumber
	var sourcePath = Path.Combine(InputFolder, "source.html");
   
  	// Form jalur file hasil
  	var outputPath = Path.Combine(OutputFolder, "result.md");

	// Tentukan instance objek opsi penyimpanan
	var options = new MarkdownSaveOptions();

	// Mulai proses konversi dengan konfigurasi default
	Converter.ConvertHTML(sourcePath, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, MarkdownSaveOptions, String) {#converthtml_70}

Konversi sumber HTML yang disajikan melalui konten inline ke Markdown. Hasilnya adalah file mhtml (.mht) yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String content, String baseUri, MarkdownSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten html inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | MarkdownSaveOptions | Penggunaan objek [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Jalur file md lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konversi format populer lainnya

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil Markdown dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) daring gratis yang mengonversi HTML ke MD dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Bentuk konten html inline		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result");

	// Tentukan objek opsi penyimpanan default
  	var options = new MarkdownSaveOptions();

	// Mulai proses konversi
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, MarkdownSaveOptions, String) {#converthtml_59}

Konversi sumber HTML yang disajikan melalui konten inline ke Markdown. Hasilnya adalah file mhtml (.mht) yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    MarkdownSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten html inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | MarkdownSaveOptions | Penggunaan objek [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions). |
| outputPath | String | Jalur file md lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke Markdown

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi Markdown

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konversi format populer lainnya

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke Markdown

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML ([`HTMLDocument`](../../../com.aspose.html/htmldocument/)) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil Markdown dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) daring gratis yang mengonversi HTML ke MD dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Bentuk konten html inline		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result");

	// Tentukan objek opsi penyimpanan default
 	var options = new MarkdownSaveOptions();

	// Mulai proses konversi dengan konfigurasi default
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, XpsSaveOptions, String) {#converthtml_10}

Konversi sumber HTML yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Hasilnya adalah file xps yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(HTMLDocument document, XpsSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | HTMLDocument | Sumber konversi yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Jalur file xps lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) daring gratis yang mengonversi HTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// Form jalur file sumber
      	var sourcePath = Path.Combine(InputFolder, "source.html");

      	// Form jalur file hasil
      	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
		// Buat dokumen HTML dengan salah satu dari beberapa cara
      	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
      	{
        	// Tentukan instance objek opsi penyimpanan
        	var options = new XpsSaveOptions();

        	// Mulai proses konversi
        	Converter.ConvertHTML(document, options, outputPath);
      	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, XpsSaveOptions, String) {#converthtml_32}

Konversi sumber HTML yang disajikan melalui URL. Hasilnya adalah file xps yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(Url url, XpsSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL dokumen sumber HTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Jalur file xps lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) daring gratis yang mengonversi HTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Buat Url berdasarkan jalur file input
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Form jalur file hasil
   	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Tentukan instance objek opsi penyimpanan
	var options = new XpsSaveOptions();

	// Mulai proses konversi
	Converter.ConvertHTML(sourceUrl, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, XpsSaveOptions, String) {#converthtml_21}

Konversi sumber HTML yang disajikan melalui URL. Hasilnya adalah file xps yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL dokumen sumber HTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. |
| outputPath | String | Jalur file xps lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) daring gratis yang mengonversi HTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Buat Url berdasarkan jalur file input
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Form jalur file hasil
  	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Tentukan instance objek opsi penyimpanan
	var options = new XpsSaveOptions();

	// Mulai proses konversi dengan konfigurasi default
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, XpsSaveOptions, String) {#converthtml_54}

Konversi sumber HTML yang disajikan melalui jalur file lengkap menjadi XPS. Hasilnya adalah file xps yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file HTML. Jalur ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Jalur file xps lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) daring gratis yang mengonversi HTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Form jalur file sumber
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Form jalur file hasil
   	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Tentukan instance objek opsi penyimpanan
	var options = new XpsSaveOptions();

	// Mulai proses konversi
	Converter.ConvertHTML(sourcePath, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, XpsSaveOptions, String) {#converthtml_43}

Konversi sumber HTML yang disajikan melalui jalur file lengkap menjadi XPS. Hasilnya adalah file xps yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file lengkap Html. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Jalur file xps lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) daring gratis yang mengonversi HTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Form jalur file sumber
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Form jalur file hasil
  	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// Tentukan instance objek opsi penyimpanan
	var options = new XpsSaveOptions();

	// Mulai proses konversi dengan konfigurasi default
	Converter.ConvertHTML(sourcePath, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, XpsSaveOptions, String) {#converthtml_76}

Konversi sumber HTML yang disajikan melalui konten inline ke XPS. Hasilnya adalah file xps yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten html inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions). |
| outputPath | String | Jalur file xps lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) daring gratis yang mengonversi HTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Bentuk konten html inline		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result");

	// Tentukan objek opsi penyimpanan default
  	var options = new XpsSaveOptions();

	// Mulai proses konversi
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, XpsSaveOptions, String) {#converthtml_65}

Konversi sumber HTML yang disajikan melalui konten inline ke XPS. Hasilnya adalah file xps yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten html inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. |
| outputPath | String | Jalur file xps lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) daring gratis yang mengonversi HTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Bentuk konten html inline		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result");

	// Tentukan objek opsi penyimpanan default
 	var options = new XpsSaveOptions();

	// Mulai proses konversi dengan konfigurasi default
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, XpsSaveOptions, ICreateStreamProvider) {#converthtml_9}

Konversi sumber HTML yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(HTMLDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | HTMLDocument | Sumber konversi yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Cara mengonversi HTML ke XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) daring gratis yang mengonversi HTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Form jalur file sumber
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Form jalur file hasil
   	var resultPath = Path.Combine(OutputFolder, "result.xps");
		
	// Buat dokumen HTML dengan salah satu dari beberapa cara
   	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
   	{
    	// Tentukan instance objek opsi penyimpanan
    	var options = new XpsSaveOptions();

		// Gunakan salah satu implementasi ICreateStreamProvider yang dikenal
  		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

    	// Mulai proses konversi
    	Converter.ConvertHTML(document, options, provider);
   	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#converthtml_31}

Konversi sumber HTML yang disajikan oleh URL. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL dokumen sumber HTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Cara mengonversi HTML ke XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) daring gratis yang mengonversi HTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Buat Url berdasarkan jalur file input
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Form jalur file hasil
   	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Gunakan salah satu implementasi ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Tentukan instance objek opsi penyimpanan
	var options = new XpsSaveOptions();

	// Mulai proses konversi
	Converter.ConvertHTML(sourceUrl, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_20}

Konversi sumber HTML yang disajikan oleh URL. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL sumber HTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Cara mengonversi HTML ke XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) daring gratis yang mengonversi HTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Buat Url berdasarkan jalur file input
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Form jalur file hasil
  	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Gunakan salah satu implementasi ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Tentukan instance objek opsi penyimpanan
	var options = new XpsSaveOptions();

	// Mulai proses konversi dengan konfigurasi default
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, XpsSaveOptions, ICreateStreamProvider) {#converthtml_53}

Konversi sumber HTML yang disajikan oleh jalur file lengkap ke XPS. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file HTML. Jalur ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka khusus [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Catatan

Cara mengonversi HTML ke XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) daring gratis yang mengonversi HTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Form jalur file sumber
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Form jalur file hasil
   	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Gunakan salah satu implementasi ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Tentukan instance objek opsi penyimpanan
	var options = new XpsSaveOptions();

	// Mulai proses konversi
	Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_42}

Konversi sumber HTML yang disajikan oleh jalur file lengkap ke XPS. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file HTML. Jalur ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Cara mengonversi HTML ke XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) daring gratis yang mengonversi HTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Form jalur file sumber
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Form jalur file hasil
  	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Gunakan salah satu implementasi ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// Tentukan instance objek opsi penyimpanan
	var options = new XpsSaveOptions();

	// Mulai proses konversi dengan konfigurasi default
	Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, XpsSaveOptions, ICreateStreamProvider) {#converthtml_75}

Konversi sumber HTML yang disajikan oleh konten inline ke XPS. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertHTML(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten html inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Cara mengonversi HTML ke XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan konverter online gratis [HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps) yang mengonversi HTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Bentuk konten html inline		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result");

	// Gunakan salah satu implementasi ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Tentukan objek opsi penyimpanan default
  	var options = new XpsSaveOptions();

	// Mulai proses konversi
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_64}

Konversi sumber HTML yang disajikan oleh konten inline ke XPS. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten html inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka khusus [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Catatan

Cara mengonversi HTML ke XPS

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi XPS

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi HTML ke XPS

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat menentukan konten HTML inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apapun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) baru dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML daring

Aspose.HTML menawarkan [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) daring gratis yang mengonversi HTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Coba gunakan konversi format populer lainnya

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Bentuk konten html inline		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result");

	// Gunakan salah satu implementasi ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Tentukan objek opsi penyimpanan default
 	var options = new XpsSaveOptions();

	// Mulai proses konversi dengan konfigurasi default
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, ImageSaveOptions, String) {#converthtml_3}

Konversi sumber HTML yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Hasilnya adalah file gambar yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(HTMLDocument document, ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | HTMLDocument | Sumber konversi yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke Gambar

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi gambar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konversi HTML ke Gambar

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) yang diperlukan. Secara default, properti Format adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML online

Aspose.HTML menawarkan konverter online gratis [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) yang mengonversi HTML ke gambar dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
// Form jalur file sumber
var sourcePath = Path.Combine(InputFolder, "source.html");

// Form jalur file hasil
var outputPath = Path.Combine(OutputFolder, "result.jpg");

import (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
{
	// Tentukan instance objek opsi penyimpanan
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Mulai proses konversi
	Converter.ConvertHTML(document, options, outputPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, ImageSaveOptions, String) {#converthtml_25}

Konversi sumber HTML yang disajikan melalui URL. Hasilnya adalah file gambar yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(Url url, ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL sumber HTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke Gambar

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi gambar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konversi HTML ke Gambar

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) yang diperlukan. Secara default, properti Format adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML online

Aspose.HTML menawarkan konverter online gratis [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) yang mengonversi HTML ke gambar dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Buat Url berdasarkan jalur file input
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Form jalur file hasil
   	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Tentukan instance objek opsi penyimpanan
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Mulai proses konversi
	Converter.ConvertHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, ImageSaveOptions, String) {#converthtml_14}

Konversi sumber HTML yang disajikan melalui URL. Hasilnya adalah file gambar yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL sumber HTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek ImageSaveOptions memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke Gambar

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi gambar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konversi HTML ke Gambar

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) yang diperlukan. Secara default, properti Format adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML online

Aspose.HTML menawarkan konverter online gratis [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) yang mengonversi HTML ke gambar dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Buat Url berdasarkan jalur file input
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Form jalur file hasil
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Tentukan instance objek opsi penyimpanan
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Mulai proses konversi dengan konfigurasi default
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, ImageSaveOptions, String) {#converthtml_47}

Konversi sumber HTML yang disajikan melalui jalur file lengkap menjadi gambar. Hasilnya adalah file gambar yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file HTML. Jalur ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | ImageSaveOptions | Untuk mempelajari lebih lanjut tentang kelas [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) , silakan baca artikel [Fine-Tuning Converters](https://docs.aspose.com/html/net/converting-between-formats/fine-tuning-converters/). |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke Gambar

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi gambar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konversi HTML ke Gambar

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) yang diperlukan. Secara default, properti Format adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML online

Aspose.HTML menawarkan konverter online gratis [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) yang mengonversi HTML ke gambar dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Form jalur file sumber
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// Form jalur file hasil
   	var resultPath = Path.Combine(OutputFolder, "result.png");
		
	// Tentukan instance objek opsi penyimpanan. PNG adalah format gambar secara default
	var options = new ImageSaveOptions();

	// Mulai proses konversi
	Converter.ConvertHTML(sourcePath , options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, ImageSaveOptions, String) {#converthtml_36}

Konversi sumber HTML yang disajikan melalui jalur file lengkap menjadi gambar. Hasilnya adalah file gambar yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file HTML. Jalur ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Untuk mempelajari lebih lanjut tentang kelas [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) , silakan baca artikel [Fine-Tuning Converters](https://docs.aspose.com/html/net/converting-between-formats/fine-tuning-converters/). |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke Gambar

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi gambar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konversi HTML ke Gambar

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) yang diperlukan. Secara default, properti Format adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML online

Aspose.HTML menawarkan konverter online gratis [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) yang mengonversi HTML ke gambar dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Form jalur file sumber
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Form jalur file hasil
  	var resultPath = Path.Combine(OutputFolder, "result.png");
		
	// Tentukan instance objek opsi penyimpanan. PNG adalah format gambar secara default
	var options = new ImageSaveOptions();

	// Mulai proses konversi dengan konfigurasi default
	Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, ImageSaveOptions, String) {#converthtml_69}

Konversi sumber HTML yang disajikan melalui konten inline ke gambar. Hasilnya adalah file gambar yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten html inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | ImageSaveOptions | Opsi gambar baru yang terbentuk seperti format, resolusi, dll. Lihat kelas [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke Gambar

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi gambar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konversi HTML ke Gambar

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) yang diperlukan. Secara default, properti Format adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML online

Aspose.HTML menawarkan konverter online gratis [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) yang mengonversi HTML ke gambar dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Bentuk konten html inline		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Tentukan objek opsi penyimpanan default
  	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Mulai proses konversi
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, ImageSaveOptions, String) {#converthtml_58}

Konversi sumber HTML yang disajikan melalui konten inline ke gambar. Hasilnya adalah file gambar yang dibentuk oleh jalur file output.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten html inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Opsi gambar baru yang terbentuk seperti format, resolusi, dll. Lihat kelas [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Cara mengonversi HTML ke Gambar

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi gambar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konversi HTML ke Gambar

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) yang diperlukan. Secara default, properti Format adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML online

Aspose.HTML menawarkan konverter online gratis [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) yang mengonversi HTML ke gambar dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Bentuk konten html inline		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Tentukan objek opsi penyimpanan default
 	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Mulai proses konversi dengan konfigurasi default
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, ImageSaveOptions, ICreateStreamProvider) {#converthtml_2}

Konversi sumber HTML yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/). Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(HTMLDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | HTMLDocument | Sumber konversi yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Cara mengonversi HTML ke Gambar

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi gambar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konversi HTML ke Gambar

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) yang diperlukan. Secara default, properti Format adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML online

Aspose.HTML menawarkan konverter online gratis [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) yang mengonversi HTML ke gambar dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Form jalur file sumber
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result");

	// Buat dokumen HTML dengan salah satu dari beberapa cara
	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
	{
  		// Tentukan instance objek opsi penyimpanan
  		var options = new ImageSaveOptions(ImageFormat.Jpeg);

  		// Gunakan salah satu implementasi ICreateStreamProvider
  		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

  		// Mulai proses konversi
  		Converter.ConvertHTML(document, options, provider);
	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#converthtml_24}

Konversi sumber HTML yang disajikan oleh URL. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL sumber HTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | ImageSaveOptions | Penggunaan objek ImageSaveOptions memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka khusus [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Catatan

Cara mengonversi HTML ke Gambar

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi gambar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konversi HTML ke Gambar

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) yang diperlukan. Secara default, properti Format adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML online

Aspose.HTML menawarkan konverter online gratis [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) yang mengonversi HTML ke gambar dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Buat Url berdasarkan jalur file input
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// Form jalur file hasil
   	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Tentukan instance objek opsi penyimpanan
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Gunakan salah satu implementasi ICreateStreamProvider
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Mulai proses konversi
	Converter.ConvertHTML(sourceUrl, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_13}

Konversi sumber HTML yang disajikan oleh URL. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertHTML(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL sumber HTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek ImageSaveOptions memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Implementasi antarmuka, yang akan digunakan untuk mendapatkan aliran output. Info lebih lanjut tentang penyedia dapat dilihat di [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Catatan

Cara mengonversi HTML ke Gambar

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi gambar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konversi HTML ke Gambar

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) yang diperlukan. Secara default, properti Format adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML online

Aspose.HTML menawarkan konverter online gratis [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) yang mengonversi HTML ke gambar dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Buat Url berdasarkan jalur file input
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// Form jalur file hasil
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Tentukan instance objek opsi penyimpanan
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Gunakan salah satu implementasi ICreateStreamProvider
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Mulai proses konversi dengan konfigurasi default
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, ImageSaveOptions, ICreateStreamProvider) {#converthtml_46}

Konversi sumber HTML yang disajikan oleh jalur file lengkap ke gambar. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file lengkap Html. |
| options | ImageSaveOptions | Penggunaan objek ImageSaveOptions memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Implementasi antarmuka, yang akan digunakan untuk mendapatkan aliran output. Info lebih lanjut tentang penyedia dapat dilihat di [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Catatan

Cara mengonversi HTML ke Gambar

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi gambar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konversi HTML ke Gambar

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) yang diperlukan. Secara default, properti Format adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML online

Aspose.HTML menawarkan konverter online gratis [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) yang mengonversi HTML ke gambar dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Form jalur file sumber
   	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// Form jalur file hasil
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Tentukan instance objek opsi penyimpanan
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Gunakan salah satu implementasi ICreateStreamProvider yang dikenal
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Mulai proses konversi
	Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_35}

Konversi sumber HTML yang disajikan oleh jalur file lengkap ke gambar. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file HTML. Jalur ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek ImageSaveOptions memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Implementasi antarmuka, yang akan digunakan untuk mendapatkan aliran output. Info lebih lanjut tentang penyedia dapat dilihat di [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Catatan

Cara mengonversi HTML ke Gambar

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi gambar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konversi HTML ke Gambar

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) yang diperlukan. Secara default, properti Format adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML online

Aspose.HTML menawarkan konverter online gratis [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) yang mengonversi HTML ke gambar dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Form jalur file sumber
  	var sourcePath = Path.Combine(InputFolder, "source.html");

 	// Form jalur file hasil
 	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// Tentukan instance objek opsi penyimpanan
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Gunakan salah satu implementasi ICreateStreamProvider yang dikenal
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Mulai proses konversi dengan konfigurasi default
	Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, ImageSaveOptions, ICreateStreamProvider) {#converthtml_68}

Konversi sumber HTML yang disajikan oleh konten inline ke gambar. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertHTML(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten html inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | ImageSaveOptions | Penggunaan objek ImageSaveOptions memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka khusus [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Catatan

Cara mengonversi HTML ke Gambar

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi gambar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konversi HTML ke Gambar

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) yang diperlukan. Secara default, properti Format adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML online

Aspose.HTML menawarkan konverter online gratis [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) yang mengonversi HTML ke gambar dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Bentuk konten html inline		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Tentukan objek opsi penyimpanan default
  	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Gunakan salah satu implementasi ICreateStreamProvider yang dikenal
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Mulai proses konversi
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_57}

Konversi sumber HTML yang disajikan oleh konten inline ke gambar. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten html inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration `](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek ImageSaveOptions memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Implementasi [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. Info lebih lanjut tentang penyedia dapat dilihat di [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers). |

## Catatan

Cara mengonversi HTML ke Gambar

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Fitur utama Aspose.HTML adalah kemampuan konversi. Mengonversi antar format diperlukan untuk berbagai alasan: untuk bekerja dalam format yang familiar dan nyaman atau memanfaatkan format yang berbeda untuk tugas tertentu. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi HTML ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), dan [MD](https://docs.fileformat.com/word-processing/md/).

Artikel ini memberikan informasi tentang daftar konversi HTML yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan HTML Converter, Anda menemukan artikel-artikel berikut:

Konversi gambar

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

Konversi format populer lainnya

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

Konversi HTML ke Gambar

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file HTML lokal yang ada atau Url remote sebagai sumber konversi. Anda bahkan dapat mendefinisikan konten html inline sebagai sumber konversi atau membuat dokumen HTML (HTMLDocument) dengan cara apa pun. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan [`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/) yang diperlukan. Secara default, properti Format adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertHTML() dari kelas Converter untuk menyimpan HTML sebagai gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter HTML online

Aspose.HTML menawarkan konverter online gratis [HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png) yang mengonversi HTML ke gambar dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Bentuk konten html inline		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// Form jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// Tentukan objek opsi penyimpanan default
 	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// Gunakan salah satu implementasi ICreateStreamProvider yang dikenal
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// Mulai proses konversi dengan konfigurasi default
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, TextSaveOptions, String) {#converthtml_8}

Konversi dokumen html menjadi teks. Hasilnya adalah file TXT.

```java
public static void ConvertHTML(HTMLDocument document, TextSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | HTMLDocument | Sumber konversi. |
| opsi | TextSaveOptions | Opsi konversi. |
| outputPath | String | Jalur file output. |

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, TextSaveOptions, String) {#converthtml_30}

Konversi dokumen html menjadi teks. Hasilnya adalah file TXT.

```java
public static void ConvertHTML(Url url, TextSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL dokumen. |
| opsi | TextSaveOptions | Opsi konversi. |
| outputPath | String | Jalur file output. |

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, TextSaveOptions, String) {#converthtml_19}

Konversi dokumen html menjadi teks. Hasilnya adalah file TXT.

```java
public static void ConvertHTML(Url url, Configuration configuration, TextSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL dokumen. |
| konfigurasi | Konfigurasi | Konfigurasi lingkungan. |
| opsi | TextSaveOptions | Opsi konversi. |
| outputPath | String | Jalur file output. |

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, TextSaveOptions, String) {#converthtml_52}

Konversi dokumen html menjadi teks. Hasilnya adalah file TXT.

```java
public static void ConvertHTML(String sourcePath, TextSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file HTML. Jalur ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| opsi | TextSaveOptions | Opsi konversi. |
| outputPath | String | Jalur file output. |

### Lihat Juga

* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, TextSaveOptions, String) {#converthtml_41}

Konversi dokumen html menjadi teks. Hasilnya adalah file TXT.

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    TextSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur sumber file HTML. Jalur ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| konfigurasi | Konfigurasi | Konfigurasi lingkungan. |
| opsi | TextSaveOptions | Opsi konversi. |
| outputPath | String | Jalur file output. |

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, TextSaveOptions, String) {#converthtml_74}

Konversi dokumen html menjadi teks. Hasilnya adalah file TXT.

```java
public static void ConvertHTML(String content, String baseUri, TextSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | Konten html String inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| opsi | TextSaveOptions | Opsi konversi. |
| outputPath | String | Jalur file output. |

### Lihat Juga

* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, TextSaveOptions, String) {#converthtml_63}

Konversi dokumen html menjadi teks. Hasilnya adalah file TXT.

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    TextSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | Konten html String inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| konfigurasi | Konfigurasi | Konfigurasi lingkungan. |
| opsi | TextSaveOptions | Opsi konversi. |
| outputPath | String | Jalur file output. |

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
