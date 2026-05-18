---
title: "Converter.ConvertEPUB"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Converter. Konversi sumber EPUB yang disajikan oleh stream input data. Hasilnya adalah file yang dibentuk oleh jalur file output."
type: docs

url: /id/java/com.aspose.html.converters/converter/convertepub/
---
## ConvertEPUB(Stream, ImageSaveOptions, String) {#convertepub_27}

Konversi sumber EPUB yang disajikan oleh aliran data masukan. Hasilnya adalah file yang dibentuk oleh jalur file output.

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Stream input sebagai sumber konversi. |
| options | ImageSaveOptions | Opsi gambar baru yang dibentuk seperti format, resolusi, dll. Lihat kelas [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) dan [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Cara mengonversi EPUB ke Gambar

EPUB adalah format file e-book yang menyediakan format publikasi digital standar. Format ini dibuat oleh International Digital Publishing Forum (IDPF), dan kini didukung oleh banyak e-reader serta aplikasi perangkat lunak.

Mengonversi file EPUB ke format PNG dapat berguna jika Anda perlu menyertakan file dalam presentasi PowerPoint atau mengirimnya melalui email. Silakan konversi mereka ke format gambar dan gunakan sesuai keinginan! Anda dapat menggunakan parameter konversi tambahan untuk memperoleh hasil yang diinginkan.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini memberikan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melaksanakannya menggunakan kelas Converter yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan EPUB Converter, Anda menemukan artikel-artikel berikut:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konversi EPUB ke Gambar

Untuk mengonversi EPUB ke format file Gambar, Anda harus mengikuti beberapa langkah:

Tentukan Url berdasarkan file EPUB yang ada pada jalur yang ditentukan. Tentukan jalur file output hasil. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan ImageFormat yang diperlukan. Secara default, properti Format adalah PNG. Gunakan metode ConvertEPUB() dari kelas Converter untuk menyimpan EPUB sebagai gambar. Anda juga perlu melewatkan objek ImageSaveOptions dan Configuration untuk konversi gambar. Konverter EPUB daring

Aspose.HTML menawarkan Konverter [EPUB ke PNG](https://products.aspose.app/html/en/conversion/epub-to-png) daring gratis yang mengonversi EPUB ke gambar PNG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Buka file yang ada untuk dibaca sebagai aliran
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// Tentukan jalur file output
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Tentukan instance opsi default
var options = new ImageSaveOptions();

// Mulai proses konversi
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, String) {#convertepub_43}

Konversi sumber EPUB yang disajikan oleh jalur file lengkap. Hasilnya adalah file gambar yang dibentuk oleh jalur file keluaran. Format gambar ditentukan oleh objek ImageSaveOptions.

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file sumber EPUB sebagai parameter masukan. |
| options | ImageSaveOptions | Penggunaan objek ImageSaveOptions memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Cara mengonversi EPUB ke Gambar

EPUB adalah format file e-book yang menyediakan format publikasi digital standar. Format ini dibuat oleh International Digital Publishing Forum (IDPF), dan kini didukung oleh banyak e-reader serta aplikasi perangkat lunak.

Mengonversi file EPUB ke format PNG dapat berguna jika Anda perlu menyertakan file dalam presentasi PowerPoint atau mengirimnya melalui email. Silakan konversi mereka ke format gambar dan gunakan sesuai keinginan! Anda dapat menggunakan parameter konversi tambahan untuk memperoleh hasil yang diinginkan.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini memberikan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melaksanakannya menggunakan kelas Converter yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan EPUB Converter, Anda menemukan artikel-artikel berikut:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konversi EPUB ke Gambar

Untuk mengonversi EPUB ke format file Gambar, Anda harus mengikuti beberapa langkah:

Tentukan Url berdasarkan file EPUB yang ada pada jalur yang ditentukan. Tentukan jalur file output hasil. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan ImageFormat yang diperlukan. Secara default, properti Format adalah PNG. Gunakan metode ConvertEPUB() dari kelas Converter untuk menyimpan EPUB sebagai gambar. Anda juga perlu melewatkan objek ImageSaveOptions dan Configuration untuk konversi gambar. Konverter EPUB daring

Aspose.HTML menawarkan Konverter [EPUB ke PNG](https://products.aspose.app/html/en/conversion/epub-to-png) daring gratis yang mengonversi EPUB ke gambar PNG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Formulir jalur file sumber
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Buat jalur file hasil output
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// Tentukan instance objek ImageSaveOptions default
var options = new ImageSaveOptions(); 

// Mulai proses konversi
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - custom output folder path.

### Lihat Juga

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, String) {#convertepub_11}

Konversi sumber EPUB yang didefinisikan oleh URL. Hasilnya adalah file gambar yang dibentuk oleh jalur file keluaran. Format gambar ditentukan oleh objek ImageSaveOptions.

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL sumber EPUB - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | ImageSaveOptions | Penggunaan objek ImageSaveOptions memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat kelas [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/). |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Cara mengonversi EPUB ke Gambar

EPUB adalah format file e-book yang menyediakan format publikasi digital standar. Format ini dibuat oleh International Digital Publishing Forum (IDPF), dan kini didukung oleh banyak e-reader serta aplikasi perangkat lunak.

Mengonversi file EPUB ke format PNG dapat berguna jika Anda perlu menyertakan file dalam presentasi PowerPoint atau mengirimnya melalui email. Silakan konversi mereka ke format gambar dan gunakan sesuai keinginan! Anda dapat menggunakan parameter konversi tambahan untuk memperoleh hasil yang diinginkan.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini memberikan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melaksanakannya menggunakan kelas Converter yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan EPUB Converter, Anda menemukan artikel-artikel berikut:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konversi EPUB ke Gambar

Untuk mengonversi EPUB ke format file Gambar, Anda harus mengikuti beberapa langkah:

Tentukan Url berdasarkan file EPUB yang ada pada jalur yang ditentukan. Tentukan jalur file output hasil. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan ImageFormat yang diperlukan. Secara default, properti Format adalah PNG. Gunakan metode ConvertEPUB() dari kelas Converter untuk menyimpan EPUB sebagai gambar. Anda juga perlu melewatkan objek ImageSaveOptions dan Configuration untuk konversi gambar. Konverter EPUB daring

Aspose.HTML menawarkan Konverter [EPUB ke PNG](https://products.aspose.app/html/en/conversion/epub-to-png) daring gratis yang mengonversi EPUB ke gambar PNG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Buat Url berdasarkan jalur file masukan
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Buat jalur file hasil output
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Tentukan instance opsi default
var options = new ImageSaveOptions();

// Mulai proses konversi
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, String) {#convertepub_19}

Konversi sumber EPUB yang disajikan oleh aliran data masukan. Hasilnya adalah file gambar yang dibentuk oleh jalur file keluaran. Format gambar ditentukan oleh objek ImageSaveOptions.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Stream input sebagai sumber konversi. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek ImageSaveOptions memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Cara mengonversi EPUB ke Gambar

EPUB adalah format file e-book yang menyediakan format publikasi digital standar. Format ini dibuat oleh International Digital Publishing Forum (IDPF), dan kini didukung oleh banyak e-reader serta aplikasi perangkat lunak.

Mengonversi file EPUB ke format PNG dapat berguna jika Anda perlu menyertakan file dalam presentasi PowerPoint atau mengirimnya melalui email. Silakan konversi mereka ke format gambar dan gunakan sesuai keinginan! Anda dapat menggunakan parameter konversi tambahan untuk memperoleh hasil yang diinginkan.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini memberikan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melaksanakannya menggunakan kelas Converter yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan EPUB Converter, Anda menemukan artikel-artikel berikut:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konversi EPUB ke Gambar

Untuk mengonversi EPUB ke format file Gambar, Anda harus mengikuti beberapa langkah:

Tentukan Url berdasarkan file EPUB yang ada pada jalur yang ditentukan. Tentukan jalur file output hasil. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan ImageFormat yang diperlukan. Secara default, properti Format adalah PNG. Gunakan metode ConvertEPUB() dari kelas Converter untuk menyimpan EPUB sebagai gambar. Anda juga perlu melewatkan objek ImageSaveOptions dan Configuration untuk konversi gambar. Konverter EPUB daring

Aspose.HTML menawarkan Konverter [EPUB ke PNG](https://products.aspose.app/html/en/conversion/epub-to-png) daring gratis yang mengonversi EPUB ke gambar PNG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Buka file yang ada untuk dibaca sebagai aliran
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// Tentukan jalur file output
var resultPath = Path.Combine(OutputFolder, "sample.png");

// Tentukan instance opsi default
var options = new ImageSaveOptions();

// Mulai proses konversi dengan objek konfigurasi default
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
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

## ConvertEPUB(String, Configuration, ImageSaveOptions, String) {#convertepub_35}

Konversi sumber EPUB yang disajikan oleh jalur file lengkap. Hasilnya adalah file gambar yang dibentuk oleh jalur file keluaran. Format gambar ditentukan oleh objek ImageSaveOptions.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file sumber EPUB sebagai parameter masukan. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek ImageSaveOptions memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat kelas [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/). |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Cara mengonversi EPUB ke Gambar

EPUB adalah format file e-book yang menyediakan format publikasi digital standar. Format ini dibuat oleh International Digital Publishing Forum (IDPF), dan kini didukung oleh banyak e-reader serta aplikasi perangkat lunak.

Mengonversi file EPUB ke format PNG dapat berguna jika Anda perlu menyertakan file dalam presentasi PowerPoint atau mengirimnya melalui email. Silakan konversi mereka ke format gambar dan gunakan sesuai keinginan! Anda dapat menggunakan parameter konversi tambahan untuk memperoleh hasil yang diinginkan.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini memberikan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melaksanakannya menggunakan kelas Converter yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan EPUB Converter, Anda menemukan artikel-artikel berikut:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konversi EPUB ke Gambar

Untuk mengonversi EPUB ke format file Gambar, Anda harus mengikuti beberapa langkah:

Tentukan Url berdasarkan file EPUB yang ada pada jalur yang ditentukan. Tentukan jalur file output hasil. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan ImageFormat yang diperlukan. Secara default, properti Format adalah PNG. Gunakan metode ConvertEPUB() dari kelas Converter untuk menyimpan EPUB sebagai gambar. Anda juga perlu melewatkan objek ImageSaveOptions dan Configuration untuk konversi gambar. Konverter EPUB daring

Aspose.HTML menawarkan Konverter [EPUB ke PNG](https://products.aspose.app/html/en/conversion/epub-to-png) daring gratis yang mengonversi EPUB ke gambar PNG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Formulir jalur file sumber
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Buat jalur file hasil output
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// Tentukan instance objek ImageSaveOptions default
var options = new ImageSaveOptions(); 

// Mulai proses konversi dengan objek konfigurasi default
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
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

## ConvertEPUB(Url, Configuration, ImageSaveOptions, String) {#convertepub_3}

Konversi sumber EPUB yang didefinisikan oleh URL. Hasilnya adalah file gambar yang dibentuk oleh jalur file keluaran. Format gambar ditentukan oleh objek ImageSaveOptions.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL sumber EPUB - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek ImageSaveOptions memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [page size](https://apireference.aspose.com/html/net/aspose.html.rendering/renderingoptions/properties/pagesetup), [margins](https://apireference.aspose.com/html/net/aspose.html.drawing/page/properties/margin), [CSS media-type](https://apireference.aspose.com/html/net/aspose.html.rendering/mediatype), dll. Lihat kelas [ImageSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions). |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Cara mengonversi EPUB ke Gambar

EPUB adalah format file e-book yang menyediakan format publikasi digital standar. Format ini dibuat oleh International Digital Publishing Forum (IDPF), dan kini didukung oleh banyak e-reader serta aplikasi perangkat lunak.

Mengonversi file EPUB ke format PNG dapat berguna jika Anda perlu menyertakan file dalam presentasi PowerPoint atau mengirimnya melalui email. Silakan konversi mereka ke format gambar dan gunakan sesuai keinginan! Anda dapat menggunakan parameter konversi tambahan untuk memperoleh hasil yang diinginkan.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini memberikan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melaksanakannya menggunakan kelas Converter yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan EPUB Converter, Anda menemukan artikel-artikel berikut:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konversi EPUB ke Gambar

Untuk mengonversi EPUB ke format file Gambar, Anda harus mengikuti beberapa langkah:

Tentukan Url berdasarkan file EPUB yang ada pada jalur yang ditentukan. Tentukan jalur file output hasil. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan ImageFormat yang diperlukan. Secara default, properti Format adalah PNG. Gunakan metode ConvertEPUB() dari kelas Converter untuk menyimpan EPUB sebagai gambar. Anda juga perlu melewatkan objek ImageSaveOptions dan Configuration untuk konversi gambar. Konverter EPUB daring

Aspose.HTML menawarkan Konverter [EPUB ke PNG](https://products.aspose.app/html/en/conversion/epub-to-png) daring gratis yang mengonversi EPUB ke gambar PNG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// Buat Url berdasarkan jalur file masukan
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));  

// Tentukan jalur file output
var resultPath = Path.Combine(OutputFolder, "sample.png"); 
 
// Tentukan instance opsi default
var options = new ImageSaveOptions(); 

// Mulai proses konversi dengan objek konfigurasi default
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);  
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

## ConvertEPUB(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertepub_26}

Konversi sumber epub yang disajikan oleh [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) masukan ke gambar. Hasilnya adalah file gambar yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Stream input sebagai sumber konversi. |
| options | ImageSaveOptions | Penggunaan objek ImageSaveOptions memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat kelas [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/). |
| provider | ICreateStreamProvider | Implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang akan digunakan untuk mendapatkan aliran output. Lihat contoh lanjutan di [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke Gambar

EPUB adalah format file e-book yang menyediakan format publikasi digital standar. Format ini dibuat oleh International Digital Publishing Forum (IDPF), dan kini didukung oleh banyak e-reader serta aplikasi perangkat lunak.

Mengonversi file EPUB ke format PNG dapat berguna jika Anda perlu menyertakan file dalam presentasi PowerPoint atau mengirimnya melalui email. Silakan konversi mereka ke format gambar dan gunakan sesuai keinginan! Anda dapat menggunakan parameter konversi tambahan untuk memperoleh hasil yang diinginkan.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini memberikan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melaksanakannya menggunakan kelas Converter yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan EPUB Converter, Anda menemukan artikel-artikel berikut:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konversi EPUB ke Gambar

Untuk mengonversi EPUB ke format file Gambar, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang ada. Dalam contoh, kami menggunakan metode OpenRead() dari kelas System.IO.FileStream untuk membuka dan membaca file EPUB dari sistem file pada jalur yang ditentukan. Gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai penyangga data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan ImageFormat yang diperlukan. Secara default, properti Format adalah PNG. Gunakan metode ConvertEPUB() dari kelas Converter untuk menyimpan EPUB sebagai gambar. Anda harus melewatkan EPUB inputStream, ImageSaveOptions, dan aliran output ke metode ConvertEPUB() untuk konversi EPUB ke Gambar. Konverter EPUB daring

Aspose.HTML menawarkan Konverter [EPUB ke PNG](https://products.aspose.app/html/en/conversion/epub-to-png) daring gratis yang mengonversi EPUB ke gambar PNG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Buka file yang ada untuk dibaca sebagai aliran  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Lihat implementasi antarmuka ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Buat instance opsi default  
var options = new ImageSaveOptions();    

// Mulai proses konversi  
Converter.ConvertEPUB(inputStream, options, sp);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder path.

### Lihat Juga

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, ICreateStreamProvider) {#convertepub_42}

Konversi sumber EPUB yang disajikan oleh jalur file ke gambar. Hasilnya adalah file gambar yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file sumber EPUB. Itu akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | ImageSaveOptions | Opsi gambar baru yang dibentuk seperti format, resolusi, dll. Lihat kelas [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) dan [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options). |
| provider | ICreateStreamProvider | Implementasi antarmuka, yang akan digunakan untuk mendapatkan aliran output. Info lebih lanjut tentang penyedia dapat dilihat di [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke Gambar

EPUB adalah format file e-book yang menyediakan format publikasi digital standar. Format ini dibuat oleh International Digital Publishing Forum (IDPF), dan kini didukung oleh banyak e-reader serta aplikasi perangkat lunak.

Mengonversi file EPUB ke format PNG dapat berguna jika Anda perlu menyertakan file dalam presentasi PowerPoint atau mengirimnya melalui email. Silakan konversi mereka ke format gambar dan gunakan sesuai keinginan! Anda dapat menggunakan parameter konversi tambahan untuk memperoleh hasil yang diinginkan.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini memberikan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melaksanakannya menggunakan kelas Converter yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan EPUB Converter, Anda menemukan artikel-artikel berikut:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konversi EPUB ke Gambar

Untuk mengonversi EPUB ke format file Gambar, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang ada. Dalam contoh, kami menggunakan metode OpenRead() dari kelas System.IO.FileStream untuk membuka dan membaca file EPUB dari sistem file pada jalur yang ditentukan. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai penyangga data output. Buat objek ImageSaveOptions baru dengan ImageFormat yang diperlukan. Secara default, properti Format adalah PNG. Gunakan metode ConvertEPUB() dari kelas Converter untuk menyimpan EPUB sebagai gambar. Anda harus melewatkan EPUB inputStream, ImageSaveOptions, dan aliran output ke metode ConvertEPUB() untuk konversi EPUB ke Gambar. Konverter EPUB daring

Aspose.HTML menawarkan Konverter [EPUB ke PNG](https://products.aspose.app/html/en/conversion/epub-to-png) daring gratis yang mengonversi EPUB ke gambar PNG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

EPUB ke JPG dengan dua baris kode

```java
import System.IO;
import com.aspose.html.converters;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
// Buka file EPUB yang ada untuk dibaca.
import var stream = File.OpenRead(DataDir + "input.epub");

// Panggil metode ConvertEPUB untuk mengonversi kode EPUB menjadi gambar JPG      
Converter.ConvertEPUB(stream, new ImageSaveOptions(ImageFormat.Jpeg), Path.Combine(OutputDir, "convert-by-two-lines.jpg"));
```

*DataDir - user source file path.

*OutputDir - user output file path.

### Lihat Juga

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, ICreateStreamProvider) {#convertepub_10}

Konversi sumber epub yang disajikan melalui URL menjadi gambar. Hasilnya adalah file gambar yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL sumber EPUB - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | ImageSaveOptions | Penggunaan objek ImageSaveOptions memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat kelas [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/). |
| provider | ICreateStreamProvider | Implementasi antarmuka, yang akan digunakan untuk mendapatkan aliran output. Info lebih lanjut tentang penyedia dapat dilihat di [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke Gambar

EPUB adalah format file e-book yang menyediakan format publikasi digital standar. Format ini dibuat oleh International Digital Publishing Forum (IDPF), dan kini didukung oleh banyak e-reader serta aplikasi perangkat lunak.

Mengonversi file EPUB ke format PNG dapat berguna jika Anda perlu menyertakan file dalam presentasi PowerPoint atau mengirimnya melalui email. Silakan konversi mereka ke format gambar dan gunakan sesuai keinginan! Anda dapat menggunakan parameter konversi tambahan untuk memperoleh hasil yang diinginkan.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini memberikan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melaksanakannya menggunakan kelas Converter yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan EPUB Converter, Anda menemukan artikel-artikel berikut:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konversi EPUB ke Gambar

Untuk mengonversi EPUB ke format file Gambar, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang ada. Dalam contoh, kami menggunakan metode OpenRead() dari kelas System.IO.FileStream untuk membuka dan membaca file EPUB dari sistem file pada jalur yang ditentukan. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai penyangga data output. Buat objek ImageSaveOptions baru dengan ImageFormat yang diperlukan. Secara default, properti Format adalah PNG. Gunakan metode ConvertEPUB() dari kelas Converter untuk menyimpan EPUB sebagai gambar. Anda harus melewatkan EPUB inputStream, ImageSaveOptions, dan aliran output ke metode ConvertEPUB() untuk konversi EPUB ke Gambar. Konverter EPUB daring

Aspose.HTML menawarkan Konverter [EPUB ke PNG](https://products.aspose.app/html/en/conversion/epub-to-png) daring gratis yang mengonversi EPUB ke gambar PNG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  

// Buat Url berdasarkan jalur file masukan
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Lihat implementasi antarmuka ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Buat instance opsi default  
var options = new ImageSaveOptions();

// Mulai proses konversi  
Converter.ConvertEPUB(sourceUrl, options, sp);
```

*InputFolder - user input folder.

*OutputFolder - user output folder.

*ImageSaveOptions supposes PNG format of new formed image.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_18}

Konversi sumber epub yang disajikan oleh [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) masukan ke gambar. Hasilnya adalah file gambar yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Stream input sebagai sumber konversi. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek ImageSaveOptions memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| penyedia | ICreateStreamProvider | Implementasi antarmuka, yang akan digunakan untuk mendapatkan aliran keluaran. |

## Catatan

Cara mengonversi EPUB ke Gambar

EPUB adalah format file e-book yang menyediakan format publikasi digital standar. Format ini dibuat oleh International Digital Publishing Forum (IDPF), dan kini didukung oleh banyak e-reader serta aplikasi perangkat lunak.

Mengonversi file EPUB ke format PNG dapat berguna jika Anda perlu menyertakan file dalam presentasi PowerPoint atau mengirimnya melalui email. Silakan konversi mereka ke format gambar dan gunakan sesuai keinginan! Anda dapat menggunakan parameter konversi tambahan untuk memperoleh hasil yang diinginkan.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini memberikan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melaksanakannya menggunakan kelas Converter yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan EPUB Converter, Anda menemukan artikel-artikel berikut:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konversi EPUB ke Gambar

Untuk mengonversi EPUB ke format file Gambar, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang ada. Dalam contoh, kami menggunakan metode OpenRead() dari kelas System.IO.FileStream untuk membuka dan membaca file EPUB dari sistem file pada jalur yang ditentukan. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai penyangga data output. Buat objek ImageSaveOptions baru dengan ImageFormat yang diperlukan. Secara default, properti Format adalah PNG. Gunakan metode ConvertEPUB() dari kelas Converter untuk menyimpan EPUB sebagai gambar. Anda harus melewatkan EPUB inputStream, ImageSaveOptions, dan aliran output ke metode ConvertEPUB() untuk konversi EPUB ke Gambar. Konverter EPUB daring

Aspose.HTML menawarkan Konverter [EPUB ke PNG](https://products.aspose.app/html/en/conversion/epub-to-png) daring gratis yang mengonversi EPUB ke gambar PNG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Buka file yang ada untuk dibaca sebagai aliran  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  


// Lihat implementasi antarmuka ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  


// Buat instance opsi default  
var options = new ImageSaveOptions();    


// Mulai proses konversi dengan konfigurasi default  
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_34}

Konversi sumber epub yang disajikan melalui jalur file menjadi gambar. Hasilnya adalah file gambar yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Sumber EPUB yang ditentukan oleh jalur file. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek ImageSaveOptions memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Implementasi antarmuka, yang akan digunakan untuk mendapatkan aliran keluaran. Lihat contoh implementasi ICreateStreamProvider di [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke Gambar

EPUB adalah format file e-book yang menyediakan format publikasi digital standar. Format ini dibuat oleh International Digital Publishing Forum (IDPF), dan kini didukung oleh banyak e-reader serta aplikasi perangkat lunak.

Mengonversi file EPUB ke format PNG dapat berguna jika Anda perlu menyertakan file dalam presentasi PowerPoint atau mengirimnya melalui email. Silakan konversi mereka ke format gambar dan gunakan sesuai keinginan! Anda dapat menggunakan parameter konversi tambahan untuk memperoleh hasil yang diinginkan.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini memberikan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melaksanakannya menggunakan kelas Converter yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan EPUB Converter, Anda menemukan artikel-artikel berikut:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konversi EPUB ke Gambar

Untuk mengonversi EPUB ke format file Gambar, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang ada. Dalam contoh, kami menggunakan metode OpenRead() dari kelas System.IO.FileStream untuk membuka dan membaca file EPUB dari sistem file pada jalur yang ditentukan. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai penyangga data output. Buat objek ImageSaveOptions baru dengan ImageFormat yang diperlukan. Secara default, properti Format adalah PNG. Gunakan metode ConvertEPUB() dari kelas Converter untuk menyimpan EPUB sebagai gambar. Anda harus melewatkan EPUB inputStream, ImageSaveOptions, dan aliran output ke metode ConvertEPUB() untuk konversi EPUB ke Gambar. Konverter EPUB daring

Aspose.HTML menawarkan Konverter [EPUB ke PNG](https://products.aspose.app/html/en/conversion/epub-to-png) daring gratis yang mengonversi EPUB ke gambar PNG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Formulir jalur file sumber
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// Lihat implementasi antarmuka ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Tentukan instance objek ImageSaveOptions default
var options = new ImageSaveOptions(); 

// Mulai proses konversi dengan objek konfigurasi default
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_2}

Konversi sumber epub yang disajikan oleh URL ke gambar. Hasilnya adalah file gambar yang dibentuk oleh implementasi antarmuka [ICreateStreamProvider](https://apireference.aspose.com/html/net/aspose.html.io/icreatestreamprovider).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL sumber EPUB - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek ImageSaveOptions memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Implementasi antarmuka, yang akan digunakan untuk mendapatkan aliran keluaran. Lihat contoh implementasi ICreateStreamProvider di [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke Gambar

EPUB adalah format file e-book yang menyediakan format publikasi digital standar. Format ini dibuat oleh International Digital Publishing Forum (IDPF), dan kini didukung oleh banyak e-reader serta aplikasi perangkat lunak.

Mengonversi file EPUB ke format PNG dapat berguna jika Anda perlu menyertakan file dalam presentasi PowerPoint atau mengirimnya melalui email. Silakan konversi mereka ke format gambar dan gunakan sesuai keinginan! Anda dapat menggunakan parameter konversi tambahan untuk memperoleh hasil yang diinginkan.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini memberikan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melaksanakannya menggunakan kelas Converter yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan EPUB Converter, Anda menemukan artikel-artikel berikut:

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

Konversi EPUB ke Gambar

Untuk mengonversi EPUB ke format file Gambar, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang ada. Dalam contoh, kami menggunakan metode OpenRead() dari kelas System.IO.FileStream untuk membuka dan membaca file EPUB dari sistem file pada jalur yang ditentukan. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai penyangga data output. Buat objek ImageSaveOptions baru dengan ImageFormat yang diperlukan. Secara default, properti Format adalah PNG. Gunakan metode ConvertEPUB() dari kelas Converter untuk menyimpan EPUB sebagai gambar. Anda harus melewatkan EPUB inputStream, ImageSaveOptions, dan aliran output ke metode ConvertEPUB() untuk konversi EPUB ke Gambar. Konverter EPUB daring

Aspose.HTML menawarkan Konverter [EPUB ke PNG](https://products.aspose.app/html/en/conversion/epub-to-png) daring gratis yang mengonversi EPUB ke gambar PNG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Anda mungkin juga tertarik pada konversi format gambar tertentu

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// Buat URL sumber dari jalur file masukan
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Lihat implementasi antarmuka ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// Buat instance opsi default  
var options = new ImageSaveOptions();

// Mulai proses konversi dengan konfigurasi default
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);

```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, XpsSaveOptions, String) {#convertepub_31}

Konversi sumber epub yang disajikan oleh aliran masukan ke xps. Hasilnya adalah file xps yang ditentukan oleh jalur lengkap.

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Aliran masukan sebagai sumber konversi. Lihat spesifikasi Stream di [official source](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). |
| options | XpsSaveOptions | Opsi konversi. Penggunaan objek [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan ukuran halaman, margin, CSS, dll. |
| outputPath | String | Jalur file .xps lengkap sebagai hasil konversi keluaran. |

## Catatan

Cara mengonversi EPUB ke XPS

File XPS mewakili file tata letak halaman yang berbasis pada Spesifikasi Kertas XML yang dibuat oleh Microsoft. File ini dikembangkan sebagai pengganti format file EMF dan mirip dengan format file PDF, tetapi menggunakan XML dalam tata letak, tampilan, dan informasi pencetakan dokumen.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter XPS, Anda menemukan artikel berikut:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konversi EPUB ke XPS

Untuk mengonversi format file EPUB ke XPS, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai penampung data keluaran. Kita dapat menggunakan alternatif yang lebih sederhana berupa jalur file keluaran hasil. Buat objek XpsSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default kelas XpsSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file xps. Anda perlu memberikan tanggal sumber EPUB, XpsSaveOptions, dan penampung data keluaran dalam bentuk apa pun untuk memulai proses konversi. Online EPUB to XPS converter

Aspose.HTML menawarkan Converter online gratis [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi EPUB ke file XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System.Drawing;
import com.aspose.html.drawing;
...
  // Buka file EPUB yang ada untuk dibaca
  using var stream = File.OpenRead(DataDir + "input.epub");

  // Siapkan jalur untuk menyimpan file yang dikonversi 
  String savePath = Path.Combine(OutputDir, "input-options.xps");
   
  // Buat instance XpsSaveOptions. Atur ukuran halaman dan ubah warna latar belakang menjadi LightGray 
  var options = new XpsSaveOptions()
  {
    PageSetup =
      {
        AnyPage = new Page()
        {
          Size = new com.aspose.html.drawing.Size(Length.FromPixels(500), Length.FromPixels(500))
        }
      },
    BackgroundColor = Color.LightGray
  };
   
  // Panggil metode ConvertEPUB untuk mengonversi EPUB ke XPS
  Converter.ConvertEPUB(stream, options, savePath); 
```

*DataDir - some user input folder.

*OutputDir - user output folder.

### Lihat Juga

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, String) {#convertepub_47}

Konversi sumber epub yang disajikan oleh jalur file EPUB masukan ke xps. Hasilnya adalah file xps yang ditentukan oleh jalur lengkap.

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file sumber EPUB. Itu akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | XpsSaveOptions | Opsi konversi. Penggunaan objek [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| outputPath | String | Jalur file .xps lengkap sebagai hasil konversi keluaran. |

## Catatan

Cara mengonversi EPUB ke XPS

File XPS mewakili file tata letak halaman yang berbasis pada Spesifikasi Kertas XML yang dibuat oleh Microsoft. File ini dikembangkan sebagai pengganti format file EMF dan mirip dengan format file PDF, tetapi menggunakan XML dalam tata letak, tampilan, dan informasi pencetakan dokumen.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter XPS, Anda menemukan artikel berikut:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konversi EPUB ke XPS

Untuk mengonversi format file EPUB ke XPS, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai penampung data keluaran. Kita dapat menggunakan alternatif yang lebih sederhana berupa jalur file keluaran hasil. Buat objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default kelas XpsSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file xps. Anda perlu memberikan tanggal sumber EPUB, [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/), dan penampung data keluaran dalam bentuk apa pun untuk memulai proses konversi. Online EPUB to XPS converter

Aspose.HTML menawarkan Converter online gratis [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi EPUB ke file XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Formulir jalur file sumber
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Buat jalur file hasil output
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Buat instance opsi default  
var options = new XpsSaveOptions();

// Mulai proses konversi dengan konfigurasi default
Converter.ConvertEPUB(sourcePath, options, resultPath);  
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, XpsSaveOptions, String) {#convertepub_15}

Konversi sumber epub yang disajikan oleh URL ke file xps yang ditentukan oleh jalur lengkap. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL sumber EPUB - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | XpsSaveOptions | Opsi konversi. Penggunaan objek [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| outputPath | String | Jalur file .xps lengkap sebagai hasil konversi keluaran. |

## Catatan

Cara mengonversi EPUB ke XPS

File XPS mewakili file tata letak halaman yang berbasis pada Spesifikasi Kertas XML yang dibuat oleh Microsoft. File ini dikembangkan sebagai pengganti format file EMF dan mirip dengan format file PDF, tetapi menggunakan XML dalam tata letak, tampilan, dan informasi pencetakan dokumen.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter XPS, Anda menemukan artikel berikut:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konversi EPUB ke XPS

Untuk mengonversi format file EPUB ke XPS, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang sudah ada. Sebagai contoh, kita dapat mendefinisikan path file sumber sebagai parameter pertama dari metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai buffer data output. Kita dapat menggunakan alternatif yang lebih sederhana sebagai path file output hasil. Buat objek XpsSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default dari kelas XpsSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file xps. Anda perlu memberikan data sumber EPUB, XpsSaveOptions, dan buffer data output dalam bentuk apa pun untuk memulai proses konversi.

Konverter EPUB ke XPS daring

Aspose.HTML menawarkan Converter online gratis [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi EPUB ke file XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// Buat URL sumber dari jalur file masukan
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Buat jalur file hasil output
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Buat instance opsi default  
var options = new XpsSaveOptions();

// Mulai proses konversi
Converter.ConvertEPUB(sourceUrl, options, resultPath);





*InputFolder - user input directory.

```

*OutputFolder - user output directory.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, String) {#convertepub_23}

Konversi sumber epub yang disajikan oleh input [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) ke xps. Hasilnya adalah file xps yang ditentukan oleh jalur lengkap.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Stream input sebagai sumber konversi. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Opsi konversi. Penggunaan objek [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| outputPath | String | Jalur file .xps lengkap sebagai hasil konversi keluaran. |

## Catatan

Cara mengonversi EPUB ke XPS

File XPS mewakili file tata letak halaman yang berbasis pada Spesifikasi Kertas XML yang dibuat oleh Microsoft. File ini dikembangkan sebagai pengganti format file EMF dan mirip dengan format file PDF, tetapi menggunakan XML dalam tata letak, tampilan, dan informasi pencetakan dokumen.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter XPS, Anda menemukan artikel berikut:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konversi EPUB ke XPS

Untuk mengonversi format file EPUB ke XPS, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang sudah ada. Sebagai contoh, kita dapat mendefinisikan path file sumber sebagai parameter pertama dari metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai buffer data output. Kita dapat menggunakan alternatif yang lebih sederhana sebagai path file output hasil. Buat objek XpsSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default dari kelas XpsSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file xps. Anda perlu memberikan data sumber EPUB, XpsSaveOptions, dan buffer data output dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke XPS daring

Aspose.HTML menawarkan Converter online gratis [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi EPUB ke file XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...

// Buka file EPUB yang ada untuk dibaca
import var stream = File.OpenRead(DataDir + "input.epub");

// Siapkan path untuk menyimpan file yang dikonversi 
String savePath = Path.Combine(OutputDir, "input-output.xps");       
   
// Inisialisasi XpsSaveOptions 
var options = new XpsSaveOptions();
   
// Panggil metode ConvertEPUB untuk mengonversi EPUB ke XPS
Converter.ConvertEPUB(stream, new Configuration(), options, savePath);





*DataDir - user input folder.

```

*OutputDir - user output folder.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, XpsSaveOptions, String) {#convertepub_39}

Konversi sumber epub yang disajikan oleh jalur file EPUB masukan ke xps. Hasilnya adalah file xps yang ditentukan oleh jalur lengkap.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file sumber EPUB. Itu akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Opsi konversi. Penggunaan objek [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan ukuran halaman, margin, CSS, dll. |
| outputPath | String | Jalur file .xps lengkap sebagai hasil konversi keluaran. |

## Catatan

Cara mengonversi EPUB ke XPS

File XPS mewakili file tata letak halaman yang berbasis pada Spesifikasi Kertas XML yang dibuat oleh Microsoft. File ini dikembangkan sebagai pengganti format file EMF dan mirip dengan format file PDF, tetapi menggunakan XML dalam tata letak, tampilan, dan informasi pencetakan dokumen.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter XPS, Anda menemukan artikel berikut:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konversi EPUB ke XPS

Untuk mengonversi format file EPUB ke XPS, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang sudah ada. Sebagai contoh, kita dapat mendefinisikan path file sumber sebagai parameter pertama dari metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai buffer data output. Kita dapat menggunakan alternatif yang lebih sederhana sebagai path file output hasil. Buat objek XpsSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default dari kelas XpsSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file xps. Anda perlu memberikan data sumber EPUB, XpsSaveOptions, dan buffer data output dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke XPS daring

Aspose.HTML menawarkan Converter online gratis [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi EPUB ke file XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Formulir jalur file sumber
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Buat jalur file hasil output
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Buat instance opsi default  
var options = new XpsSaveOptions();

// Mulai proses konversi dengan konfigurasi default
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);  
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

## ConvertEPUB(Url, Configuration, XpsSaveOptions, String) {#convertepub_7}

Konversi sumber epub yang disajikan oleh URL ke file xps yang ditentukan oleh jalur lengkap. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL sumber EPUB - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Opsi konversi. Penggunaan objek [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan ukuran halaman, margin, CSS, dll. |
| outputPath | String | Jalur file .xps lengkap sebagai hasil konversi keluaran. |

## Catatan

Cara mengonversi EPUB ke XPS

File XPS mewakili file tata letak halaman yang berbasis pada Spesifikasi Kertas XML yang dibuat oleh Microsoft. File ini dikembangkan sebagai pengganti format file EMF dan mirip dengan format file PDF, tetapi menggunakan XML dalam tata letak, tampilan, dan informasi pencetakan dokumen.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter XPS, Anda menemukan artikel berikut:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konversi EPUB ke XPS

Untuk mengonversi format file EPUB ke XPS, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang sudah ada. Sebagai contoh, kita dapat mendefinisikan path file sumber sebagai parameter pertama dari metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai buffer data output. Kita dapat menggunakan alternatif yang lebih sederhana sebagai path file output hasil. Buat objek XpsSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default dari kelas XpsSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file xps. Anda perlu memberikan data sumber EPUB, XpsSaveOptions, dan buffer data output dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke XPS daring

Aspose.HTML menawarkan Converter online gratis [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi EPUB ke file XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// Buat URL sumber dari jalur file masukan
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Buat jalur file hasil output
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// Buat instance opsi default  
var options = new XpsSaveOptions();

// Mulai proses konversi dengan konfigurasi default 
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertepub_30}

Konversi sumber epub yang diberikan melalui input [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) ke xps. Hasilnya adalah data output xps yang didefinisikan oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom.

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Stream input sebagai sumber konversi. |
| options | XpsSaveOptions | Opsi konversi. Penggunaan objek [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`ukuran halaman`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margin`](../../../com.aspose.html.drawing/page/margin/), [`tipe media CSS`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Implementasi antarmuka yang akan digunakan untuk mendapatkan stream output. Lihat contoh implementasi ICreateStreamProvider di [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke XPS

File XPS mewakili file tata letak halaman yang berbasis pada Spesifikasi Kertas XML yang dibuat oleh Microsoft. File ini dikembangkan sebagai pengganti format file EMF dan mirip dengan format file PDF, tetapi menggunakan XML dalam tata letak, tampilan, dan informasi pencetakan dokumen.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter XPS, Anda menemukan artikel berikut:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konversi EPUB ke XPS

Untuk mengonversi format file EPUB ke XPS, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang sudah ada. Sebagai contoh, kita dapat mendefinisikan path file sumber sebagai parameter pertama dari metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai buffer data output. Kita dapat menggunakan alternatif yang lebih sederhana sebagai path file output hasil. Buat objek XpsSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default dari kelas XpsSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file xps. Anda perlu memberikan data sumber EPUB, XpsSaveOptions, dan buffer data output dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke XPS daring

Aspose.HTML menawarkan Converter online gratis [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi EPUB ke file XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import Aspose.Html;
import System.Linq;
import com.aspose.html.converters;
import com.aspose.html.saving;
...
 // Buat instance MemoryStreamProvider
 using var streamProvider = new MemoryStreamProvider();

 // Buka file EPUB yang ada untuk dibaca
 using var stream = File.OpenRead(DataDir + "input.epub");
  
 // Siapkan jalur untuk menyimpan file yang dikonversi 
 String savePath = Path.Combine(OutputDir, "stream-provider.xps");
  
 // Konversi EPUB ke XPS dengan menggunakan kelas MemoryStreamProvider
 Converter.ConvertEPUB(stream, new XpsSaveOptions(), streamProvider);
  
 // Dapatkan akses ke memory stream yang berisi data hasil
 var memory = streamProvider.Streams.First();
 memory.Seek(0, SeekOrigin.Begin);

 // Flush data hasil ke file output
 using (FileStream fs = File.Create(savePath))
 {
  memory.CopyTo(fs);
 }
```

*DataDir - user source file path.

*OutputDir- user output file path.

*See MemoryStreamProvider class as ICreateStreamProvider implementation in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers).

### Lihat Juga

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, ICreateStreamProvider) {#convertepub_46}

Konversi sumber epub yang diberikan melalui path file EPUB input ke xps. Hasilnya adalah data output xps yang didefinisikan oleh implementasi antarmuka [`ICreateStreamProvider `](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom.

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file sumber EPUB. Itu akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | XpsSaveOptions | Opsi konversi. Penggunaan objek [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan ukuran halaman, margin, CSS, dll. |
| provider | ICreateStreamProvider | Implementasi antarmuka yang akan digunakan untuk mendapatkan stream output. Lihat contoh lanjutan di [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke XPS

File XPS mewakili file tata letak halaman yang berbasis pada Spesifikasi Kertas XML yang dibuat oleh Microsoft. File ini dikembangkan sebagai pengganti format file EMF dan mirip dengan format file PDF, tetapi menggunakan XML dalam tata letak, tampilan, dan informasi pencetakan dokumen.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter XPS, Anda menemukan artikel berikut:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konversi EPUB ke XPS

Untuk mengonversi format file EPUB ke XPS, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai penampung data keluaran. Kita dapat menggunakan alternatif yang lebih sederhana berupa jalur file keluaran hasil. Buat objek XpsSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default kelas XpsSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file xps. Anda perlu memberikan tanggal sumber EPUB, XpsSaveOptions, dan penampung data keluaran dalam bentuk apa pun untuk memulai proses konversi. Online EPUB to XPS converter

Aspose.HTML menawarkan Converter online gratis [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi EPUB ke file XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Formulir jalur file sumber
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Lihat implementasi antarmuka ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Buat instance opsi default  
var options = new XpsSaveOptions();

// Mulai proses konversi dengan konfigurasi default
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, XpsSaveOptions, ICreateStreamProvider) {#convertepub_14}

Konversi sumber epub yang diberikan melalui URL ke file xps yang ditentukan oleh path lengkap. Hasilnya adalah data output xps yang didefinisikan oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom.

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL sumber EPUB - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | XpsSaveOptions | Opsi konversi. Penggunaan objek [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan ukuran halaman, margin, CSS, dll. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementasi [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) yang akan digunakan untuk mendapatkan stream output. Lihat contoh lanjutan di [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke XPS

File XPS mewakili file tata letak halaman yang berbasis pada Spesifikasi Kertas XML yang dibuat oleh Microsoft. File ini dikembangkan sebagai pengganti format file EMF dan mirip dengan format file PDF, tetapi menggunakan XML dalam tata letak, tampilan, dan informasi pencetakan dokumen.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter XPS, Anda menemukan artikel berikut:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konversi EPUB ke XPS

Untuk mengonversi format file EPUB ke XPS, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang sudah ada. Sebagai contoh, kita dapat mendefinisikan path file sumber sebagai parameter pertama dari metode ConvertEPUB. Gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Kita dapat menggunakan alternatif yang lebih sederhana sebagai path file output hasil. Buat objek XpsSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default dari kelas XpsSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file xps. Anda perlu memberikan data sumber EPUB, XpsSaveOptions, dan buffer data output dalam bentuk apa pun untuk memulai proses konversi. Konverter EPUB ke XPS daring

Aspose.HTML menawarkan Converter online gratis [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi EPUB ke file XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Buat URL sumber dari jalur file masukan
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Lihat implementasi antarmuka ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Buat instance opsi default  
var options = new XpsSaveOptions();

// Mulai proses konversi
Converter.ConvertEPUB(sourceUrl, options, sp);
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

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_22}

Konversi sumber epub yang diberikan melalui input [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) ke xps. Hasilnya adalah data output xps yang didefinisikan oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Stream input sebagai sumber konversi. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Opsi konversi. Penggunaan objek [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`ukuran halaman`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margin`](../../../com.aspose.html.drawing/page/margin/), [`tipe media CSS`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang akan digunakan untuk mendapatkan stream output. Lihat contoh lanjutan di [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke XPS

File XPS mewakili file tata letak halaman yang berbasis pada Spesifikasi Kertas XML yang dibuat oleh Microsoft. File ini dikembangkan sebagai pengganti format file EMF dan mirip dengan format file PDF, tetapi menggunakan XML dalam tata letak, tampilan, dan informasi pencetakan dokumen.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter XPS, Anda menemukan artikel berikut:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konversi EPUB ke XPS

Untuk mengonversi format file EPUB ke XPS, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang sudah ada. Sebagai contoh, kita dapat mendefinisikan path file sumber sebagai parameter pertama dari metode ConvertEPUB. Gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Kita dapat menggunakan alternatif yang lebih sederhana sebagai path file output hasil. Buat objek XpsSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default dari kelas XpsSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file xps. Anda perlu memberikan data sumber EPUB, XpsSaveOptions, dan buffer data output dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke XPS daring

Aspose.HTML menawarkan Converter online gratis [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi EPUB ke file XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Buka file yang ada untuk dibaca sebagai aliran  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Lihat implementasi antarmuka ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Buat instance opsi default  
var options = new XpsSaveOptions();

// Mulai proses konversi dengan konfigurasi default
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
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

## ConvertEPUB(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_38}

Konversi sumber epub yang diberikan melalui path file EPUB input ke xps. Hasilnya adalah data output xps yang didefinisikan oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file sumber EPUB. Itu akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Opsi konversi. Penggunaan objek [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan ukuran halaman, margin, CSS, dll. |
| provider | ICreateStreamProvider | Implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang akan digunakan untuk mendapatkan stream output. Lihat contoh lanjutan di [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke XPS

File XPS mewakili file tata letak halaman yang berbasis pada Spesifikasi Kertas XML yang dibuat oleh Microsoft. File ini dikembangkan sebagai pengganti format file EMF dan mirip dengan format file PDF, tetapi menggunakan XML dalam tata letak, tampilan, dan informasi pencetakan dokumen.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter XPS, Anda menemukan artikel berikut:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konversi EPUB ke XPS

Untuk mengonversi format file EPUB ke XPS, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang sudah ada. Sebagai contoh, kita dapat mendefinisikan path file sumber sebagai parameter pertama dari metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai buffer data output. Kita dapat menggunakan alternatif yang lebih sederhana sebagai path file output hasil. Buat objek XpsSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default dari kelas XpsSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file xps. Anda perlu memberikan data sumber EPUB, XpsSaveOptions, dan buffer data output dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke XPS daring

Aspose.HTML menawarkan Converter online gratis [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi EPUB ke file XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Formulir jalur file sumber
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Lihat implementasi antarmuka ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// Buat instance opsi default  
var options = new XpsSaveOptions();

// Mulai proses konversi dengan konfigurasi default
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_6}

Konversi sumber epub yang diberikan melalui URL ke file xps yang ditentukan oleh path lengkap. Hasilnya adalah data output xps yang didefinisikan oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL sumber EPUB - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Opsi konversi. Penggunaan objek [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`ukuran halaman`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margin`](../../../com.aspose.html.drawing/page/margin/), [`tipe media CSS`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang akan digunakan untuk mendapatkan stream output. Lihat contoh lanjutan di [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke XPS

File XPS mewakili file tata letak halaman yang berbasis pada Spesifikasi Kertas XML yang dibuat oleh Microsoft. File ini dikembangkan sebagai pengganti format file EMF dan mirip dengan format file PDF, tetapi menggunakan XML dalam tata letak, tampilan, dan informasi pencetakan dokumen.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter XPS, Anda menemukan artikel berikut:

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

Konversi EPUB ke XPS

Untuk mengonversi format file EPUB ke XPS, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang sudah ada. Sebagai contoh, kita dapat mendefinisikan path file sumber sebagai parameter pertama dari metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai buffer data output. Kita dapat menggunakan alternatif yang lebih sederhana sebagai path file output hasil. Buat objek XpsSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default dari kelas XpsSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file xps. Anda perlu memberikan data sumber EPUB, XpsSaveOptions, dan buffer data output dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke XPS daring

Aspose.HTML menawarkan Converter online gratis [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi EPUB ke file XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// Buat URL sumber dari jalur file masukan
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Buat jalur file hasil output
var resultPath = Path.Combine(OutputFolder, " sample.xps");

// Buat instance opsi default  
var options = new XpsSaveOptions();

// Mulai proses konversi dengan konfigurasi default
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, DocSaveOptions, String) {#convertepub_25}

Konversi file sumber EPUB yang diberikan dengan jalur lengkap ke DOCX. Hasilnya adalah file docx yang ditentukan oleh jalur lengkap.

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Sumber konversi yang diberikan melalui input [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). |
| options | DocSaveOptions | Opsi konversi. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) penggunaan objek memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Jalur file .docx lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi EPUB ke DOCX

DOCX adalah format yang terkenal untuk dokumen Microsoft Word. Format ini populer karena mendukung berbagai fitur pemformatan dan menawarkan pengguna berbagai opsi untuk menulis jenis dokumen apa pun. File DOCX dapat dibuka dengan Word 2007 dan versi-versi selanjutnya tetapi tidak dengan versi Word MS yang lebih lama, yang hanya mendukung ekstensi file DOC. Konversi EPUB ke DOCX sering diperlukan untuk memanfaatkan format DOCX bagi tugas-tugas pengguna tertentu.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter untuk DOCX, Anda akan menemukan artikel berikut:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke DOCX

Untuk mengonversi format file EPUB ke DOCX, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama dari metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai penyangga data output. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file output hasil. Buat objek DocSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default dari kelas DocSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file docx. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance DocSaveOptions, dan penyangga data output dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke DOCX daring

Aspose.HTML menawarkan Konverter daring gratis [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi file EPUB ke DOCX dengan kualitas tinggi, mudah dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Buka file yang ada untuk dibaca sebagai aliran  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Buat jalur file hasil output
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Buat instance opsi default  
var options = new DocSaveOptions();   

// Mulai proses konversi
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, DocSaveOptions, String) {#convertepub_41}

Konversi sumber EPUB yang disajikan oleh jalur file lengkap ke DOCX. Hasilnya adalah file docx yang dibentuk oleh jalur file keluaran.

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file sumber EPUB sebagai parameter masukan. |
| options | DocSaveOptions | Opsi konversi. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) penggunaan objek memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/),[` margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Jalur file .docx lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi EPUB ke DOCX

DOCX adalah format yang terkenal untuk dokumen Microsoft Word. Format ini populer karena mendukung berbagai fitur pemformatan dan menawarkan pengguna berbagai opsi untuk menulis jenis dokumen apa pun. File DOCX dapat dibuka dengan Word 2007 dan versi-versi selanjutnya tetapi tidak dengan versi Word MS yang lebih lama, yang hanya mendukung ekstensi file DOC. Konversi EPUB ke DOCX sering diperlukan untuk memanfaatkan format DOCX bagi tugas-tugas pengguna tertentu.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter untuk DOCX, Anda akan menemukan artikel berikut:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke DOCX

Untuk mengonversi format file EPUB ke DOCX, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama dari metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai penyangga data output. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file output hasil. Buat objek DocSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default dari kelas DocSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file docx. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance DocSaveOptions, dan penyangga data output dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke DOCX daring

Aspose.HTML menawarkan Konverter daring gratis [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi file EPUB ke DOCX dengan kualitas tinggi, mudah dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formulir jalur file sumber
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Buat jalur file hasil output
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Tentukan instance opsi default
var options = new DocSaveOptions();

// Mulai proses konversi
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, DocSaveOptions, String) {#convertepub_9}

Konversi sumber EPUB yang disajikan oleh URL. Hasilnya adalah file docx yang dibentuk oleh jalur file keluaran.

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL sumber EPUB - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) penggunaan memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Jalur file .docx lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi EPUB ke DOCX

DOCX adalah format yang terkenal untuk dokumen Microsoft Word. Format ini populer karena mendukung berbagai fitur pemformatan dan menawarkan pengguna berbagai opsi untuk menulis jenis dokumen apa pun. File DOCX dapat dibuka dengan Word 2007 dan versi-versi selanjutnya tetapi tidak dengan versi Word MS yang lebih lama, yang hanya mendukung ekstensi file DOC. Konversi EPUB ke DOCX sering diperlukan untuk memanfaatkan format DOCX bagi tugas-tugas pengguna tertentu.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter untuk DOCX, Anda akan menemukan artikel berikut:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke DOCX

Untuk mengonversi format file EPUB ke DOCX, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama dari metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai penyangga data output. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file output hasil. Buat objek DocSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default dari kelas DocSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file docx. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance DocSaveOptions, dan penyangga data output dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke DOCX daring

Aspose.HTML menawarkan Konverter daring gratis [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi file EPUB ke DOCX dengan kualitas tinggi, mudah dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Buat URL sumber dari jalur file masukan
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Buat jalur file hasil output
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Tentukan instance opsi default
var options = new DocSaveOptions();

// Mulai proses konversi
Converter.ConvertEPUB(sourceUrl, options, resultPath);
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

## ConvertEPUB(Stream, Configuration, DocSaveOptions, String) {#convertepub_17}

Konversi sumber EPUB yang disajikan oleh aliran data masukan. Hasilnya adalah file docx yang dibentuk oleh jalur file keluaran.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Stream input sebagai sumber konversi. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | Opsi konversi. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) penggunaan objek memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Jalur file .docx lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi EPUB ke DOCX

DOCX adalah format yang terkenal untuk dokumen Microsoft Word. Format ini populer karena mendukung berbagai fitur pemformatan dan menawarkan pengguna berbagai opsi untuk menulis jenis dokumen apa pun. File DOCX dapat dibuka dengan Word 2007 dan versi-versi selanjutnya tetapi tidak dengan versi Word MS yang lebih lama, yang hanya mendukung ekstensi file DOC. Konversi EPUB ke DOCX sering diperlukan untuk memanfaatkan format DOCX bagi tugas-tugas pengguna tertentu.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter untuk DOCX, Anda akan menemukan artikel berikut:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke DOCX

Untuk mengonversi format file EPUB ke DOCX, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama dari metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai penyangga data output. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file output hasil. Buat objek DocSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default dari kelas DocSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file docx. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance DocSaveOptions, dan penyangga data output dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke DOCX daring

Aspose.HTML menawarkan Konverter daring gratis [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi file EPUB ke DOCX dengan kualitas tinggi, mudah dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Buka file yang ada untuk dibaca sebagai aliran  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Buat jalur file hasil output
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Buat instance opsi default  
var options = new DocSaveOptions();   

// Mulai proses konversi dengan konfigurasi default 
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
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

## ConvertEPUB(String, Configuration, DocSaveOptions, String) {#convertepub_33}

Konversi sumber EPUB yang disajikan oleh jalur file lengkap ke DOCX. Hasilnya adalah file docx yang dibentuk oleh jalur file keluaran.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file sumber EPUB. Itu akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | Opsi konversi. [DocSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/docsaveoptions) penggunaan objek memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan ukuran halaman, margin, CSS, dll. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Jalur file .docx lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi EPUB ke DOCX

DOCX adalah format yang terkenal untuk dokumen Microsoft Word. Format ini populer karena mendukung berbagai fitur pemformatan dan menawarkan pengguna berbagai opsi untuk menulis jenis dokumen apa pun. File DOCX dapat dibuka dengan Word 2007 dan versi-versi selanjutnya tetapi tidak dengan versi Word MS yang lebih lama, yang hanya mendukung ekstensi file DOC. Konversi EPUB ke DOCX sering diperlukan untuk memanfaatkan format DOCX bagi tugas-tugas pengguna tertentu.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter untuk DOCX, Anda akan menemukan artikel berikut:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke DOCX

Untuk mengonversi format file EPUB ke DOCX, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama dari metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai penyangga data output. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file output hasil. Buat objek DocSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default dari kelas DocSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file docx. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance DocSaveOptions, dan penyangga data output dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke DOCX daring

Aspose.HTML menawarkan Konverter daring gratis [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi file EPUB ke DOCX dengan kualitas tinggi, mudah dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formulir jalur file sumber
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Buat jalur file hasil output
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Tentukan instance opsi default
var options = new DocSaveOptions();

// Mulai proses konversi dengan konfigurasi default
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
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

## ConvertEPUB(Url, Configuration, DocSaveOptions, String) {#convertepub_1}

Konversi sumber EPUB yang disajikan oleh URL. Hasilnya adalah file docx yang dibentuk oleh jalur file keluaran.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL sumber EPUB - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) penggunaan memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| outputPath | String | Jalur file .docx lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi EPUB ke DOCX

DOCX adalah format yang terkenal untuk dokumen Microsoft Word. Format ini populer karena mendukung berbagai fitur pemformatan dan menawarkan pengguna berbagai opsi untuk menulis jenis dokumen apa pun. File DOCX dapat dibuka dengan Word 2007 dan versi-versi selanjutnya tetapi tidak dengan versi Word MS yang lebih lama, yang hanya mendukung ekstensi file DOC. Konversi EPUB ke DOCX sering diperlukan untuk memanfaatkan format DOCX bagi tugas-tugas pengguna tertentu.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter untuk DOCX, Anda akan menemukan artikel berikut:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke DOCX

Untuk mengonversi format file EPUB ke DOCX, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama dari metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai penyangga data output. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file output hasil. Buat objek DocSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default dari kelas DocSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file docx. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance DocSaveOptions, dan penyangga data output dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke DOCX daring

Aspose.HTML menawarkan Konverter daring gratis [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi file EPUB ke DOCX dengan kualitas tinggi, mudah dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Buat URL sumber dari jalur file masukan
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Jalur file hasil konversi formulir
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// Buat instance opsi default  
var options = new DocSaveOptions();

// Mulai proses konversi dengan konfigurasi default  
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, DocSaveOptions, ICreateStreamProvider) {#convertepub_24}

Konversi sumber EPUB sebagai aliran masukan ke DOCX. Hasilnya adalah file docx yang dibentuk oleh implementasi ICreateStreamProvider.

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Stream input sebagai sumber konversi. |
| options | DocSaveOptions | Opsi konversi. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) penggunaan objek memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang akan digunakan untuk mendapatkan aliran output. Lihat contoh lanjutan di [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke DOCX

DOCX adalah format yang terkenal untuk dokumen Microsoft Word. Format ini populer karena mendukung berbagai fitur pemformatan dan menawarkan pengguna berbagai opsi untuk menulis jenis dokumen apa pun. File DOCX dapat dibuka dengan Word 2007 dan versi-versi selanjutnya tetapi tidak dengan versi Word MS yang lebih lama, yang hanya mendukung ekstensi file DOC. Konversi EPUB ke DOCX sering diperlukan untuk memanfaatkan format DOCX bagi tugas-tugas pengguna tertentu.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter untuk DOCX, Anda akan menemukan artikel berikut:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke DOCX

Untuk mengonversi format file EPUB ke DOCX, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama dari metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai penyangga data output. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file output hasil. Buat objek DocSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default dari kelas DocSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file docx. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance DocSaveOptions, dan penyangga data output dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke DOCX daring

Aspose.HTML menawarkan Konverter daring gratis [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi file EPUB ke DOCX dengan kualitas tinggi, mudah dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Buka file yang ada untuk dibaca sebagai aliran  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Lihat implementasi antarmuka ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Buat instance opsi default  
var options = new DocSaveOptions();   

// Mulai proses konversi
Converter.ConvertEPUB(inputStream, options, sp);
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

## ConvertEPUB(String, DocSaveOptions, ICreateStreamProvider) {#convertepub_40}

Konversi sumber EPUB yang disajikan dengan jalur file lengkap ke DOCX. Hasilnya adalah data output yang dibentuk oleh implementasi [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file sumber EPUB. Itu akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | DocSaveOptions | Opsi konversi. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) penggunaan objek memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang akan digunakan untuk mendapatkan aliran output. Lihat contoh lanjutan di [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke DOCX

DOCX adalah format yang terkenal untuk dokumen Microsoft Word. Format ini populer karena mendukung berbagai fitur pemformatan dan menawarkan pengguna berbagai opsi untuk menulis jenis dokumen apa pun. File DOCX dapat dibuka dengan Word 2007 dan versi-versi selanjutnya tetapi tidak dengan versi Word MS yang lebih lama, yang hanya mendukung ekstensi file DOC. Konversi EPUB ke DOCX sering diperlukan untuk memanfaatkan format DOCX bagi tugas-tugas pengguna tertentu.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter untuk DOCX, Anda akan menemukan artikel berikut:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke DOCX

Untuk mengonversi format file EPUB ke DOCX, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama dari metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai penyangga data output. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file output hasil. Buat objek DocSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default dari kelas DocSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file docx. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance DocSaveOptions, dan penyangga data output dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke DOCX daring

Aspose.HTML menawarkan Konverter daring gratis [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi file EPUB ke DOCX dengan kualitas tinggi, mudah dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formulir jalur file sumber
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Lihat implementasi antarmuka ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Buat instance opsi default  
var options = new DocSaveOptions ();   

// Mulai proses konversi  
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, DocSaveOptions, ICreateStreamProvider) {#convertepub_8}

Konversi sumber EPUB yang disajikan oleh URL. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka ICreateStreamProvider.

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL sumber EPUB - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | DocSaveOptions | Penggunaan [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan ukuran halaman, margin, resolusi, CSS, dll. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang akan digunakan untuk mendapatkan aliran output. Lihat contoh lanjutan di [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke DOCX

DOCX adalah format yang terkenal untuk dokumen Microsoft Word. Format ini populer karena mendukung berbagai fitur pemformatan dan menawarkan pengguna berbagai opsi untuk menulis jenis dokumen apa pun. File DOCX dapat dibuka dengan Word 2007 dan versi-versi selanjutnya tetapi tidak dengan versi Word MS yang lebih lama, yang hanya mendukung ekstensi file DOC. Konversi EPUB ke DOCX sering diperlukan untuk memanfaatkan format DOCX bagi tugas-tugas pengguna tertentu.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter untuk DOCX, Anda akan menemukan artikel berikut:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke DOCX

Untuk mengonversi format file EPUB ke DOCX, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama dari metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai penyangga data output. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file output hasil. Buat objek DocSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default dari kelas DocSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file docx. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance DocSaveOptions, dan penyangga data output dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke DOCX daring

Aspose.HTML menawarkan Konverter daring gratis [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi file EPUB ke DOCX dengan kualitas tinggi, mudah dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Buat URL sumber dari jalur file masukan
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Lihat implementasi antarmuka ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Buat instance opsi default  
var options = new DocSaveOptions ();   

// Mulai proses konversi
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_16}

Konversi sumber EPUB yang disajikan oleh aliran data masukan. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka ICreateStreamProvider.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Stream input sebagai sumber konversi. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) penggunaan memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang akan digunakan untuk mendapatkan aliran output. Lihat contoh lanjutan di [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke DOCX

DOCX adalah format yang terkenal untuk dokumen Microsoft Word. Format ini populer karena mendukung berbagai fitur pemformatan dan menawarkan pengguna berbagai opsi untuk menulis jenis dokumen apa pun. File DOCX dapat dibuka dengan Word 2007 dan versi-versi selanjutnya tetapi tidak dengan versi Word MS yang lebih lama, yang hanya mendukung ekstensi file DOC. Konversi EPUB ke DOCX sering diperlukan untuk memanfaatkan format DOCX bagi tugas-tugas pengguna tertentu.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter untuk DOCX, Anda akan menemukan artikel berikut:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke DOCX

Untuk mengonversi format file EPUB ke DOCX, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama dari metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai penyangga data output. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file output hasil. Buat objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default dari kelas DocSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file docx. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance DocSaveOptions, dan penyangga data output dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke DOCX daring

Aspose.HTML menawarkan Konverter daring gratis [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi file EPUB ke DOCX dengan kualitas tinggi, mudah dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Buka file yang ada untuk dibaca sebagai aliran  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Lihat implementasi antarmuka ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Buat instance opsi default  
var options = new DocSaveOptions();   

// Mulai proses konversi dengan konfigurasi default 
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_32}

Konversi sumber EPUB yang disajikan dengan jalur file lengkap ke DOCX. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file sumber EPUB. Itu akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | Opsi konversi. [`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) penggunaan objek memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang akan digunakan untuk mendapatkan aliran output. Lihat contoh lanjutan di [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke DOCX

DOCX adalah format yang terkenal untuk dokumen Microsoft Word. Format ini populer karena mendukung berbagai fitur pemformatan dan menawarkan pengguna berbagai opsi untuk menulis jenis dokumen apa pun. File DOCX dapat dibuka dengan Word 2007 dan versi-versi selanjutnya tetapi tidak dengan versi Word MS yang lebih lama, yang hanya mendukung ekstensi file DOC. Konversi EPUB ke DOCX sering diperlukan untuk memanfaatkan format DOCX bagi tugas-tugas pengguna tertentu.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter untuk DOCX, Anda akan menemukan artikel berikut:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke DOCX

Untuk mengonversi format file EPUB ke DOCX, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama dari metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai penyangga data output. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file output hasil. Buat objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default dari kelas DocSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file docx. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance DocSaveOptions, dan penyangga data output dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke DOCX daring

Aspose.HTML menawarkan Konverter daring gratis [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi file EPUB ke DOCX dengan kualitas tinggi, mudah dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formulir jalur file sumber
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Lihat implementasi antarmuka ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Buat instance opsi default  
var options = new DocSaveOptions ();   

// Mulai proses konversi  
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub}

Konversi sumber EPUB yang disajikan melalui URL. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL sumber EPUB - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) penggunaan memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`resolutions`](../../../com.aspose.html.rendering.image/imagerenderingoptions/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang akan digunakan untuk mendapatkan aliran output. Lihat contoh lanjutan di [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke DOCX

DOCX adalah format yang terkenal untuk dokumen Microsoft Word. Format ini populer karena mendukung berbagai fitur pemformatan dan menawarkan pengguna berbagai opsi untuk menulis jenis dokumen apa pun. File DOCX dapat dibuka dengan Word 2007 dan versi-versi selanjutnya tetapi tidak dengan versi Word MS yang lebih lama, yang hanya mendukung ekstensi file DOC. Konversi EPUB ke DOCX sering diperlukan untuk memanfaatkan format DOCX bagi tugas-tugas pengguna tertentu.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter untuk DOCX, Anda akan menemukan artikel berikut:

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke DOCX

Untuk mengonversi format file EPUB ke DOCX, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama dari metode ConvertEPUB. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau kustom sebagai penyangga data output. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file output hasil. Buat objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default dari kelas DocSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file docx. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance DocSaveOptions, dan penyangga data output dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke DOCX daring

Aspose.HTML menawarkan Konverter daring gratis [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) yang mengonversi file EPUB ke DOCX dengan kualitas tinggi, mudah dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Buat Url berdasarkan jalur file masukan
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Lihat implementasi antarmuka ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// Buat instance opsi default  
var options = new DocSaveOptions();   

// Mulai proses konversi dengan konfigurasi default 
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);





*InputFolder - user source file path.



```

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

## ConvertEPUB(Stream, PdfSaveOptions, String) {#convertepub_29}

Konversi sumber EPUB yang disajikan oleh aliran data masukan. Hasilnya adalah file pdf yang dibentuk oleh jalur file output.

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Jalur file sumber EPUB sebagai parameter masukan. |
| options | PdfSaveOptions | Opsi konversi. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) penggunaan objek memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Jalur file .pdf lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi EPUB ke PDF

EPUB adalah format file e-book yang menyediakan standar format publikasi digital. Format ini dibuat oleh International Digital Publishing Forum ([IDPF](http://idpf.org/)), dan kini didukung oleh banyak e-reader dan aplikasi perangkat lunak. Konversi EPUB ke PDF sering diperlukan untuk memanfaatkan format PDF. Format file PDF memiliki kemampuan penuh untuk berisi informasi seperti teks, gambar, tautan, bidang formulir, media kaya, metadata, dll. File PDF dapat dibuka di Adobe Acrobat Reader/Writer dan sebagian besar peramban modern seperti Chrome, Safari, Firefox. Mereka dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda juga dapat mengonfigurasi pengaturan keamanan untuk PDF.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter PDF, Anda menemukan artikel berikut:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke PDF

Untuk mengonversi format file EPUB ke PDF, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang sudah ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama metode ConvertEPUB. Sebagai alternatif, kita dapat menggunakan aliran masukan atau instance objek Url. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau khusus sebagai penampung data keluaran. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file keluaran hasil. Buat objek PdfSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default kelas PdfSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file pdf. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance PdfSaveOptions, dan penampung data keluaran dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke PDF daring

Aspose.HTML menawarkan Konverter [EPUB ke PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) daring gratis yang mengonversi file EPUB ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Buka file yang ada untuk dibaca sebagai aliran  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Jalur file hasil formulir  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// Buat instance opsi default  
var options = new PdfSaveOptions();   

// Mulai proses konversi  
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, PdfSaveOptions, String) {#convertepub_45}

Konversi sumber EPUB yang disajikan oleh jalur file lengkap ke PDF. Hasilnya adalah file pdf yang dibentuk oleh jalur file keluaran.

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file sumber EPUB. Itu akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | PdfSaveOptions | Opsi konversi. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) penggunaan objek memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Jalur file .pdf lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi EPUB ke PDF

EPUB adalah format file e-book yang menyediakan standar format publikasi digital. Format ini dibuat oleh International Digital Publishing Forum ([IDPF](http://idpf.org/)), dan kini didukung oleh banyak e-reader dan aplikasi perangkat lunak. Konversi EPUB ke PDF sering diperlukan untuk memanfaatkan format PDF. Format file PDF memiliki kemampuan penuh untuk berisi informasi seperti teks, gambar, tautan, bidang formulir, media kaya, metadata, dll. File PDF dapat dibuka di Adobe Acrobat Reader/Writer dan sebagian besar peramban modern seperti Chrome, Safari, Firefox. Mereka dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda juga dapat mengonfigurasi pengaturan keamanan untuk PDF.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter PDF, Anda menemukan artikel berikut:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke PDF

Untuk mengonversi format file EPUB ke PDF, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang sudah ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama metode ConvertEPUB. Sebagai alternatif, kita dapat menggunakan aliran masukan atau instance objek Url. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau khusus sebagai penampung data keluaran. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file keluaran hasil. Buat objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default kelas PdfSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file pdf. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance PdfSaveOptions, dan penampung data keluaran dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke PDF daring

Aspose.HTML menawarkan Konverter [EPUB ke PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) daring gratis yang mengonversi file EPUB ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formulir jalur file sumber
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Buat jalur file hasil output
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Tentukan instance opsi default
var options = new PdfSaveOptions();

// Mulai proses konversi
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, PdfSaveOptions, String) {#convertepub_13}

Konversi sumber EPUB yang disajikan oleh URL. Hasilnya adalah file pdf yang dibentuk oleh jalur file keluaran.

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL sumber EPUB - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | PdfSaveOptions | Penggunaan [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`ukuran halaman`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margin`](../../../com.aspose.html.drawing/page/margin/), [`izin file`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`tipe media CSS`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Dokumentasi Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Jalur file .pdf lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi EPUB ke PDF

EPUB adalah format file e-book yang menyediakan standar format publikasi digital. Format ini dibuat oleh International Digital Publishing Forum ([IDPF](http://idpf.org/)), dan kini didukung oleh banyak e-reader dan aplikasi perangkat lunak. Konversi EPUB ke PDF sering diperlukan untuk memanfaatkan format PDF. Format file PDF memiliki kemampuan penuh untuk berisi informasi seperti teks, gambar, tautan, bidang formulir, media kaya, metadata, dll. File PDF dapat dibuka di Adobe Acrobat Reader/Writer dan sebagian besar peramban modern seperti Chrome, Safari, Firefox. Mereka dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda juga dapat mengonfigurasi pengaturan keamanan untuk PDF.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter PDF, Anda menemukan artikel berikut:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke PDF

Untuk mengonversi format file EPUB ke PDF, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang sudah ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama metode ConvertEPUB. Sebagai alternatif, kita dapat menggunakan aliran masukan atau instance objek Url. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau khusus sebagai penampung data keluaran. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file keluaran hasil. Buat objek PdfSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default kelas PdfSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file pdf. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance PdfSaveOptions, dan penampung data keluaran dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke PDF daring

Aspose.HTML menawarkan Konverter [EPUB ke PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) daring gratis yang mengonversi file EPUB ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 

// Buat Url berdasarkan jalur file masukan
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Buat jalur file hasil output
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Tentukan instance opsi default
var options = new com.aspose.html.saving.PdfSaveOptions();

// Mulai proses konversi
Converter.ConvertEPUB(sourceUrl, options, resultPath);
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

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, String) {#convertepub_21}

Konversi sumber EPUB yang disajikan oleh aliran data masukan. Hasilnya adalah file pdf yang dibentuk oleh jalur file output.

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Stream input sebagai sumber konversi. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Opsi konversi. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) penggunaan objek memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Jalur file .pdf lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi EPUB ke PDF

EPUB adalah format file e-book yang menyediakan standar format publikasi digital. Format ini dibuat oleh International Digital Publishing Forum ([IDPF](http://idpf.org/)), dan kini didukung oleh banyak e-reader dan aplikasi perangkat lunak. Konversi EPUB ke PDF sering diperlukan untuk memanfaatkan format PDF. Format file PDF memiliki kemampuan penuh untuk berisi informasi seperti teks, gambar, tautan, bidang formulir, media kaya, metadata, dll. File PDF dapat dibuka di Adobe Acrobat Reader/Writer dan sebagian besar peramban modern seperti Chrome, Safari, Firefox. Mereka dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda juga dapat mengonfigurasi pengaturan keamanan untuk PDF.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter PDF, Anda menemukan artikel berikut:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke PDF

Untuk mengonversi format file EPUB ke PDF, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang sudah ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama metode ConvertEPUB. Sebagai alternatif, kita dapat menggunakan aliran masukan atau instance objek Url. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau khusus sebagai penampung data keluaran. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file keluaran hasil. Buat objek PdfSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default kelas PdfSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file pdf. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance PdfSaveOptions, dan penampung data keluaran dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke PDF daring

Aspose.HTML menawarkan Konverter [EPUB ke PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) daring gratis yang mengonversi file EPUB ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Buka file yang ada untuk dibaca sebagai aliran  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Jalur file hasil formulir  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// Buat instance opsi default  
var options = new PdfSaveOptions();   

// Mulai proses konversi dengan konfigurasi default 
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, PdfSaveOptions, String) {#convertepub_37}

Konversi sumber EPUB yang disajikan oleh aliran data masukan. Hasilnya adalah file pdf yang dibentuk oleh jalur file output.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file sumber EPUB. Itu akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Opsi konversi. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) penggunaan objek memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Jalur file .pdf lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi EPUB ke PDF

EPUB adalah format file e-book yang menyediakan standar format publikasi digital. Format ini dibuat oleh International Digital Publishing Forum ([IDPF](http://idpf.org/)), dan kini didukung oleh banyak e-reader dan aplikasi perangkat lunak. Konversi EPUB ke PDF sering diperlukan untuk memanfaatkan format PDF. Format file PDF memiliki kemampuan penuh untuk berisi informasi seperti teks, gambar, tautan, bidang formulir, media kaya, metadata, dll. File PDF dapat dibuka di Adobe Acrobat Reader/Writer dan sebagian besar peramban modern seperti Chrome, Safari, Firefox. Mereka dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda juga dapat mengonfigurasi pengaturan keamanan untuk PDF.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter PDF, Anda menemukan artikel berikut:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke PDF

Untuk mengonversi format file EPUB ke PDF, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang sudah ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama metode ConvertEPUB. Sebagai alternatif, kita dapat menggunakan aliran masukan atau instance objek Url. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau khusus sebagai penampung data keluaran. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file keluaran hasil. Buat objek PdfSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default kelas PdfSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file pdf. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance PdfSaveOptions, dan penampung data keluaran dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke PDF daring

Aspose.HTML menawarkan Konverter [EPUB ke PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) daring gratis yang mengonversi file EPUB ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Formulir jalur file sumber
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// Buat jalur file hasil output
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Tentukan instance opsi default
var options = new PdfSaveOptions();

// Mulai proses konversi dengan konfigurasi default
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, PdfSaveOptions, String) {#convertepub_5}

Konversi sumber EPUB yang disajikan oleh URL. Hasilnya adalah file pdf yang dibentuk oleh jalur file keluaran.

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL sumber EPUB - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Penggunaan [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`ukuran halaman`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margin`](../../../com.aspose.html.drawing/page/margin/), [`izin file`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`tipe media CSS`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Dokumentasi Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| outputPath | String | Jalur file .pdf lengkap sebagai hasil konversi output. |

## Catatan

Cara mengonversi EPUB ke PDF

EPUB adalah format file e-book yang menyediakan standar format publikasi digital. Format ini dibuat oleh International Digital Publishing Forum ([IDPF](http://idpf.org/)), dan kini didukung oleh banyak e-reader dan aplikasi perangkat lunak. Konversi EPUB ke PDF sering diperlukan untuk memanfaatkan format PDF. Format file PDF memiliki kemampuan penuh untuk berisi informasi seperti teks, gambar, tautan, bidang formulir, media kaya, metadata, dll. File PDF dapat dibuka di Adobe Acrobat Reader/Writer dan sebagian besar peramban modern seperti Chrome, Safari, Firefox. Mereka dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda juga dapat mengonfigurasi pengaturan keamanan untuk PDF.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter PDF, Anda menemukan artikel berikut:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke PDF

Untuk mengonversi format file EPUB ke PDF, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang sudah ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama metode ConvertEPUB. Sebagai alternatif, kita dapat menggunakan aliran masukan atau instance objek Url. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau khusus sebagai penampung data keluaran. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file keluaran hasil. Buat objek PdfSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default kelas PdfSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file pdf. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance PdfSaveOptions, dan penampung data keluaran dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke PDF daring

Aspose.HTML menawarkan Konverter [EPUB ke PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) daring gratis yang mengonversi file EPUB ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;
import com.aspose.html.converters;
...  
// Buat Url berdasarkan jalur file masukan
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Buat jalur file hasil output
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// Tentukan instance opsi default
var options = new PdfSaveOptions();

// Mulai proses konversi dengan konfigurasi default
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.



```

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertepub_28}

Konversi sumber EPUB yang disajikan melalui aliran masukan data. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Stream input sebagai sumber konversi. |
| options | PdfSaveOptions | Opsi konversi. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) penggunaan objek memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Diketahui (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kustom. |

## Catatan

Cara mengonversi EPUB ke PDF

EPUB adalah format file e-book yang menyediakan standar format publikasi digital. Format ini dibuat oleh International Digital Publishing Forum ([IDPF](http://idpf.org/)), dan kini didukung oleh banyak e-reader dan aplikasi perangkat lunak. Konversi EPUB ke PDF sering diperlukan untuk memanfaatkan format PDF. Format file PDF memiliki kemampuan penuh untuk berisi informasi seperti teks, gambar, tautan, bidang formulir, media kaya, metadata, dll. File PDF dapat dibuka di Adobe Acrobat Reader/Writer dan sebagian besar peramban modern seperti Chrome, Safari, Firefox. Mereka dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda juga dapat mengonfigurasi pengaturan keamanan untuk PDF.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter PDF, Anda menemukan artikel berikut:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke PDF

Untuk mengonversi format file EPUB ke PDF, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang sudah ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama metode ConvertEPUB. Sebagai alternatif, kita dapat menggunakan aliran masukan atau instance objek Url. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau khusus sebagai penampung data keluaran. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file keluaran hasil. Buat objek PdfSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default kelas PdfSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file pdf. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance PdfSaveOptions, dan penampung data keluaran dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke PDF daring

Aspose.HTML menawarkan Konverter [EPUB ke PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) daring gratis yang mengonversi file EPUB ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Buka file yang ada untuk dibaca sebagai aliran  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Lihat implementasi antarmuka ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Buat instance opsi default  
var options = new PdfSaveOptions ();   

// Mulai proses konversi  
Converter.ConvertEPUB(inputStream, options, sp);
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

## ConvertEPUB(String, PdfSaveOptions, ICreateStreamProvider) {#convertepub_44}

Konversi sumber EPUB yang disajikan melalui jalur file lengkap ke PDF. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file sumber EPUB. Itu akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | PdfSaveOptions | Opsi konversi. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) penggunaan objek memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran keluaran. Lihat contoh lanjutan di [Dokumentasi Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke PDF

EPUB adalah format file e-book yang menyediakan standar format publikasi digital. Format ini dibuat oleh International Digital Publishing Forum ([IDPF](http://idpf.org/)), dan kini didukung oleh banyak e-reader dan aplikasi perangkat lunak. Konversi EPUB ke PDF sering diperlukan untuk memanfaatkan format PDF. Format file PDF memiliki kemampuan penuh untuk berisi informasi seperti teks, gambar, tautan, bidang formulir, media kaya, metadata, dll. File PDF dapat dibuka di Adobe Acrobat Reader/Writer dan sebagian besar peramban modern seperti Chrome, Safari, Firefox. Mereka dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda juga dapat mengonfigurasi pengaturan keamanan untuk PDF.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter PDF, Anda menemukan artikel berikut:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke PDF

Untuk mengonversi format file EPUB ke PDF, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang sudah ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama metode ConvertEPUB. Sebagai alternatif, kita dapat menggunakan aliran masukan atau instance objek Url. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau khusus sebagai penampung data keluaran. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file keluaran hasil. Buat objek PdfSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default kelas PdfSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file pdf. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance PdfSaveOptions, dan penampung data keluaran dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke PDF daring

Aspose.HTML menawarkan Konverter [EPUB ke PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) daring gratis yang mengonversi file EPUB ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formulir jalur file sumber
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// Lihat implementasi antarmuka ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Buat instance opsi default  
var options = new PdfSaveOptions();   

// Mulai proses konversi  
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, PdfSaveOptions, ICreateStreamProvider) {#convertepub_12}

Konversi sumber EPUB yang disajikan melalui URL. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL sumber EPUB - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | PdfSaveOptions | Penggunaan [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`ukuran halaman`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margin`](../../../com.aspose.html.drawing/page/margin/), [`izin file`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`tipe media CSS`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Dokumentasi Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementasi antarmuka [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider), yang akan digunakan untuk mendapatkan aliran keluaran. Lihat contoh lanjutan di [Dokumentasi Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke PDF

EPUB adalah format file e-book yang menyediakan standar format publikasi digital. Format ini dibuat oleh International Digital Publishing Forum ([IDPF](http://idpf.org/)), dan kini didukung oleh banyak e-reader dan aplikasi perangkat lunak. Konversi EPUB ke PDF sering diperlukan untuk memanfaatkan format PDF. Format file PDF memiliki kemampuan penuh untuk berisi informasi seperti teks, gambar, tautan, bidang formulir, media kaya, metadata, dll. File PDF dapat dibuka di Adobe Acrobat Reader/Writer dan sebagian besar peramban modern seperti Chrome, Safari, Firefox. Mereka dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda juga dapat mengonfigurasi pengaturan keamanan untuk PDF.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter PDF, Anda menemukan artikel berikut:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke PDF

Untuk mengonversi format file EPUB ke PDF, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang sudah ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama metode ConvertEPUB. Sebagai alternatif, kita dapat menggunakan aliran masukan atau instance objek Url. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau khusus sebagai penampung data keluaran. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file keluaran hasil. Buat objek PdfSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default kelas PdfSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file pdf. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance PdfSaveOptions, dan penampung data keluaran dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke PDF daring

Aspose.HTML menawarkan Konverter [EPUB ke PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) daring gratis yang mengonversi file EPUB ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;   
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Buat Url berdasarkan jalur file masukan
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Lihat implementasi antarmuka ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// Tentukan instance opsi default
var options = new PdfSaveOptions();

// Mulai proses konversi
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_20}

Konversi sumber EPUB yang disajikan melalui aliran masukan data. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Stream input sebagai sumber konversi. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Opsi konversi. [`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) penggunaan objek memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran keluaran. Lihat contoh lanjutan di [Dokumentasi Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke PDF

EPUB adalah format file e-book yang menyediakan standar format publikasi digital. Format ini dibuat oleh International Digital Publishing Forum ([IDPF](http://idpf.org/)), dan kini didukung oleh banyak e-reader dan aplikasi perangkat lunak. Konversi EPUB ke PDF sering diperlukan untuk memanfaatkan format PDF. Format file PDF memiliki kemampuan penuh untuk berisi informasi seperti teks, gambar, tautan, bidang formulir, media kaya, metadata, dll. File PDF dapat dibuka di Adobe Acrobat Reader/Writer dan sebagian besar peramban modern seperti Chrome, Safari, Firefox. Mereka dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda juga dapat mengonfigurasi pengaturan keamanan untuk PDF.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku digital dan publikasi, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket [`com.aspose.html.converters`](../) menyediakan akses mudah ke metode konversi. Paket ini menawarkan berbagai konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter PDF, Anda menemukan artikel berikut:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke PDF

Untuk mengonversi format file EPUB ke PDF, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang sudah ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama metode ConvertEPUB. Sebagai alternatif, kita dapat menggunakan aliran masukan atau instance objek Url. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau khusus sebagai penampung data keluaran. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file keluaran hasil. Buat objek PdfSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default kelas PdfSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file pdf. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance PdfSaveOptions, dan penampung data keluaran dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke PDF daring

Aspose.HTML menawarkan Konverter [EPUB ke PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) daring gratis yang mengonversi file EPUB ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Buka file yang ada untuk dibaca sebagai aliran  
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// Lihat implementasi antarmuka ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Buat instance opsi default  
var options = new PdfSaveOptions ();   

// Mulai proses konversi dengan objek konfigurasi default  
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
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

## ConvertEPUB(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_36}

Konversi sumber EPUB yang disajikan oleh jalur file lengkap ke PDF. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka ICreateStreamProvider.

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file sumber EPUB. Itu akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Opsi konversi. Penggunaan objek [PdfSaveOption](https://apireference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions) memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan ukuran halaman, margin, CSS, dll. Lihat [Dokumentasi Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementasi antarmuka [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider), yang akan digunakan untuk mendapatkan aliran keluaran. Lihat contoh lanjutan di [Dokumentasi Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke PDF

EPUB adalah format file e-book yang menyediakan standar format publikasi digital. Format ini dibuat oleh International Digital Publishing Forum ([IDPF](http://idpf.org/)), dan kini didukung oleh banyak e-reader dan aplikasi perangkat lunak. Konversi EPUB ke PDF sering diperlukan untuk memanfaatkan format PDF. Format file PDF memiliki kemampuan penuh untuk berisi informasi seperti teks, gambar, tautan, bidang formulir, media kaya, metadata, dll. File PDF dapat dibuka di Adobe Acrobat Reader/Writer dan sebagian besar peramban modern seperti Chrome, Safari, Firefox. Mereka dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda juga dapat mengonfigurasi pengaturan keamanan untuk PDF.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter PDF, Anda menemukan artikel berikut:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke PDF

Untuk mengonversi format file EPUB ke PDF, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang sudah ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama metode ConvertEPUB. Sebagai alternatif, kita dapat menggunakan aliran masukan atau instance objek Url. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau khusus sebagai penampung data keluaran. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file keluaran hasil. Buat objek PdfSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default kelas PdfSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file pdf. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance PdfSaveOptions, dan penampung data keluaran dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke PDF daring

Aspose.HTML menawarkan Konverter [EPUB ke PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) daring gratis yang mengonversi file EPUB ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// Formulir jalur file sumber
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// Lihat implementasi antarmuka ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// Buat instance opsi default  
var options = new PdfSaveOptions();   

// Mulai proses konversi dengan objek konfigurasi default 
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_4}

Konversi sumber EPUB yang disajikan melalui URL. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL sumber EPUB - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Penggunaan [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering; Anda dapat menentukan [`ukuran halaman`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margin`](../../../com.aspose.html.drawing/page/margin/), [`izin file`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/), [`tipe media CSS`](../../../com.aspose.html.rendering/mediatype/), dll. Lihat [Dokumentasi Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementasi antarmuka [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider), yang akan digunakan untuk mendapatkan aliran keluaran. Lihat contoh lanjutan di [Dokumentasi Aspose](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers). |

## Catatan

Cara mengonversi EPUB ke PDF

EPUB adalah format file e-book yang menyediakan standar format publikasi digital. Format ini dibuat oleh International Digital Publishing Forum ([IDPF](http://idpf.org/)), dan kini didukung oleh banyak e-reader dan aplikasi perangkat lunak. Konversi EPUB ke PDF sering diperlukan untuk memanfaatkan format PDF. Format file PDF memiliki kemampuan penuh untuk berisi informasi seperti teks, gambar, tautan, bidang formulir, media kaya, metadata, dll. File PDF dapat dibuka di Adobe Acrobat Reader/Writer dan sebagian besar peramban modern seperti Chrome, Safari, Firefox. Mereka dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda juga dapat mengonfigurasi pengaturan keamanan untuk PDF.

Fitur utama Aspose.HTML adalah kemampuan konversi. EPUB adalah format berbasis XML terbuka untuk buku dan publikasi digital, yang dapat dilihat dan dibaca di smartphone, tablet, dan komputer. Paket com.aspose.html.converters menyediakan akses mudah ke metode konversi. Paket ini menawarkan beragam konversi [EPUB](https://docs.fileformat.com/ebook/epub/) ke format populer, seperti [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), dan [GIF](https://docs.fileformat.com/image/gif/).

Bagian ini menyediakan informasi tentang daftar skenario konversi EPUB yang didukung dan cara melakukannya menggunakan kelas [`Converter`](../) yang mengelompokkan semua operasi konversi tingkat rendah dalam satu kelas agar nyaman dan mudah digunakan. Dalam panduan khusus EPUB Converter PDF, Anda menemukan artikel berikut:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

Konversi EPUB ke PDF

Untuk mengonversi format file EPUB ke PDF, Anda harus mengikuti beberapa langkah:

Buka file EPUB yang sudah ada. Sebagai contoh, kita dapat menentukan jalur file sumber sebagai parameter pertama metode ConvertEPUB. Sebagai alternatif, kita dapat menggunakan aliran masukan atau instance objek Url. Gunakan implementasi antarmuka ICreateStreamProvider yang dikenal atau khusus sebagai penampung data keluaran. Kita juga dapat menggunakan alternatif yang lebih sederhana berupa jalur file keluaran hasil. Buat objek PdfSaveOptions baru dengan sejumlah parameter yang diinginkan seperti ukuran halaman, margin, CSS, dll. Dimungkinkan untuk menggunakan instance default kelas PdfSaveOptions. Gunakan metode ConvertEPUB() dari kelas statis Converter untuk menyimpan EPUB sebagai file pdf. Anda perlu memberikan sumber EPUB sebagai jalur file atau aliran masukan serta Url, instance PdfSaveOptions, dan penampung data keluaran dalam bentuk apa pun untuk memulai proses konversi. Anda dapat menggunakan konfigurasi yang mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan aplikasi. Konverter EPUB ke PDF daring

Aspose.HTML menawarkan Konverter [EPUB ke PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) daring gratis yang mengonversi file EPUB ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// Buat Url berdasarkan jalur file masukan
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// Lihat implementasi antarmuka ICreateStreamProvider  
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// Tentukan instance opsi default
var options = new PdfSaveOptions();

// Mulai proses konversi dengan objek konfigurasi default
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
