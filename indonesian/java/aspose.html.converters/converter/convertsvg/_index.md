---
title: "Converter.ConvertSVG"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Converter. Konversi sumber SVG yang disajikan oleh SVGDocument. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka ICreateStreamProvider"
type: docs

url: /id/java/com.aspose.html.converters/converter/convertsvg/
---
## ConvertSVG(SVGDocument, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_6}

Konversi sumber SVG yang disajikan oleh [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | SVGDocument | Sumber konversi yang disajikan oleh [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke XPS menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke XPS

Kelas Converter menawarkan beberapa konversi khusus SVG ke XPS. Untuk mengonversi SVG ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) daring gratis yang mengonversi SVG ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Bentuk dokumen SVG sebagai sumber konversi
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
			// Mulai proses konversi dengan konfigurasi default
			Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_22}

Konversi sumber SVG yang disajikan oleh [`URL`](../../../com.aspose.html/url/). Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Dokumen sumber SVG [`URL`](../../../com.aspose.html/url/) - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) khusus. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke XPS menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke XPS

Kelas Converter menawarkan beberapa konversi khusus SVG ke XPS. Untuk mengonversi SVG ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) daring gratis yang mengonversi SVG ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Form jalur file sumber
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_14}

Konversi sumber SVG yang disajikan oleh [`URL`](../../../com.aspose.html/url/). Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Dokumen sumber SVG [`URL`](../../../com.aspose.html/url/) - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) khusus. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke XPS menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke XPS

Kelas Converter menawarkan beberapa konversi khusus SVG ke XPS. Untuk mengonversi SVG ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) daring gratis yang mengonversi SVG ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Form jalur file sumber
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_38}

Konversi sumber SVG yang disajikan oleh jalur file lengkap ke XPS. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber SVG. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke XPS menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke XPS

Kelas Converter menawarkan beberapa konversi khusus SVG ke XPS. Untuk mengonversi SVG ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) daring gratis yang mengonversi SVG ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_30}

Konversi sumber SVG yang disajikan oleh jalur file lengkap ke XPS. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber SVG. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke XPS menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke XPS

Kelas Converter menawarkan beberapa konversi khusus SVG ke XPS. Untuk mengonversi SVG ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) daring gratis yang mengonversi SVG ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_54}

Konversi sumber SVG yang disajikan oleh konten inline ke XPS. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten SVG inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke XPS menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke XPS

Kelas Converter menawarkan beberapa konversi khusus SVG ke XPS. Untuk mengonversi SVG ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) daring gratis yang mengonversi SVG ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Tentukan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Mulai proses konversi
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_46}

Konversi sumber SVG yang disajikan oleh konten inline ke XPS. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten SVG inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) khusus. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke XPS menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke XPS

Kelas Converter menawarkan beberapa konversi khusus SVG ke XPS. Untuk mengonversi SVG ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) daring gratis yang mengonversi SVG ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Tentukan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, DocSaveOptions, String) {#convertsvg_1}

Konversi sumber SVG yang disajikan oleh [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Hasilnya adalah file docx yang dibentuk oleh jalur file output.

```java
public static void ConvertSVG(SVGDocument source, DocSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | SVGDocument | Sumber konversi yang disajikan oleh [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Jalur file docx lengkap sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke [DOCX](https://docs.fileformat.com/word-processing/docx/) menggunakan metode ConvertSVG() dari kelas Converter dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke DOCX

Kelas Converter menawarkan beberapa konversi khusus SVG ke DOCX. Untuk mengonversi SVG ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) online gratis yang mengonversi SVG ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Bentuk dokumen SVG sebagai sumber konversi
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Mulai proses konversi dengan konfigurasi default
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, String) {#convertsvg_17}

Konversi sumber SVG yang disajikan oleh [`URL`](../../../com.aspose.html/url/). Hasilnya adalah file docx yang dibentuk oleh jalur file output.

```java
public static void ConvertSVG(Url url, DocSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Dokumen sumber SVG [`URL`](../../../com.aspose.html/url/) - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Jalur file docx lengkap sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke [DOCX](https://docs.fileformat.com/word-processing/docx/) menggunakan metode ConvertSVG() dari kelas Converter dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke DOCX

Kelas Converter menawarkan beberapa konversi khusus SVG ke DOCX. Untuk mengonversi SVG ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) online gratis yang mengonversi SVG ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Buat Url berdasarkan jalur file input
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi
      Converter.ConvertSVG(sourceUrl, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, DocSaveOptions, String) {#convertsvg_9}

Konversi sumber SVG yang disajikan oleh [`URL`](../../../com.aspose.html/url/). Hasilnya adalah file docx yang dibentuk oleh jalur file output.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Dokumen sumber SVG [`URL`](../../../com.aspose.html/url/) - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Jalur file docx lengkap sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke [DOCX](https://docs.fileformat.com/word-processing/docx/) menggunakan metode ConvertSVG() dari kelas Converter dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke DOCX

Kelas Converter menawarkan beberapa konversi khusus SVG ke DOCX. Untuk mengonversi SVG ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) online gratis yang mengonversi SVG ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Buat Url berdasarkan jalur file input
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, String) {#convertsvg_33}

Konversi sumber SVG yang disajikan melalui jalur file lengkap ke DOCX. Hasilnya berupa file docx yang dibentuk oleh jalur file output.

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber SVG. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Jalur file docx lengkap sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke [DOCX](https://docs.fileformat.com/word-processing/docx/) menggunakan metode ConvertSVG() dari kelas Converter dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke DOCX

Kelas Converter menawarkan beberapa konversi khusus SVG ke DOCX. Untuk mengonversi SVG ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) online gratis yang mengonversi SVG ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi
      Converter.ConvertSVG(sourcePath, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Lihat Juga

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, DocSaveOptions, String) {#convertsvg_25}

Konversi sumber SVG yang disajikan melalui jalur file lengkap ke DOCX. Hasilnya berupa file docx yang dibentuk oleh jalur file output.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber SVG. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Jalur file docx lengkap sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke [DOCX](https://docs.fileformat.com/word-processing/docx/) menggunakan metode ConvertSVG() dari kelas Converter dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke DOCX

Kelas Converter menawarkan beberapa konversi khusus SVG ke DOCX. Untuk mengonversi SVG ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) online gratis yang mengonversi SVG ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, DocSaveOptions, String) {#convertsvg_49}

Konversi sumber SVG yang disajikan melalui konten inline. Hasilnya adalah file docx yang dibuat berdasarkan jalur file output.

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten SVG inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Jalur file docx lengkap sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke [DOCX](https://docs.fileformat.com/word-processing/docx/) menggunakan metode ConvertSVG() dari kelas Converter dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke DOCX

Kelas Converter menawarkan beberapa konversi khusus SVG ke DOCX. Untuk mengonversi SVG ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) online gratis yang mengonversi SVG ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form konten SVG inline
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, String) {#convertsvg_41}

Konversi sumber SVG yang disajikan melalui konten inline. Hasilnya adalah file docx yang dibuat berdasarkan jalur file output.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten SVG inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Jalur file docx lengkap sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke [DOCX](https://docs.fileformat.com/word-processing/docx/) menggunakan metode ConvertSVG() dari kelas Converter dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke DOCX

Kelas Converter menawarkan beberapa konversi khusus SVG ke DOCX. Untuk mengonversi SVG ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) online gratis yang mengonversi SVG ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form konten SVG inline
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, DocSaveOptions, ICreateStreamProvider) {#convertsvg}

Konversi sumber SVG yang disajikan oleh [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | SVGDocument | Sumber konversi yang disajikan oleh [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) khusus. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke [DOCX](https://docs.fileformat.com/word-processing/docx/) menggunakan metode ConvertSVG() dari kelas Converter dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke DOCX

Kelas Converter menawarkan beberapa konversi khusus SVG ke DOCX. Untuk mengonversi SVG ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) online gratis yang mengonversi SVG ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Bentuk dokumen SVG sebagai sumber konversi
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Mulai proses konversi dengan konfigurasi default
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, ICreateStreamProvider) {#convertsvg_16}

Konversi sumber SVG yang disajikan oleh [`URL`](../../../com.aspose.html/url/). Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Dokumen sumber SVG [`URL`](../../../com.aspose.html/url/) - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke [DOCX](https://docs.fileformat.com/word-processing/docx/) menggunakan metode ConvertSVG() dari kelas Converter dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke DOCX

Kelas Converter menawarkan beberapa konversi khusus SVG ke DOCX. Untuk mengonversi SVG ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) online gratis yang mengonversi SVG ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Buat Url berdasarkan jalur file input
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi
      Converter.ConvertSVG(sourceUrl, options, sp);





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

## ConvertSVG(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_8}

Konversi sumber SVG yang disajikan oleh [`URL`](../../../com.aspose.html/url/). Hasilnya adalah file docx yang dibentuk oleh jalur file output.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Dokumen sumber SVG [`URL`](../../../com.aspose.html/url/) - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) khusus. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke [DOCX](https://docs.fileformat.com/word-processing/docx/) menggunakan metode ConvertSVG() dari kelas Converter dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke DOCX

Kelas Converter menawarkan beberapa konversi khusus SVG ke DOCX. Untuk mengonversi SVG ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) online gratis yang mengonversi SVG ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Buat Url berdasarkan jalur file input
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);





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

## ConvertSVG(String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_32}

Konversi sumber SVG yang disajikan oleh jalur file lengkap ke DOCX. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber SVG. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) khusus. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke [DOCX](https://docs.fileformat.com/word-processing/docx/) menggunakan metode ConvertSVG() dari kelas Converter dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke DOCX

Kelas Converter menawarkan beberapa konversi khusus SVG ke DOCX. Untuk mengonversi SVG ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) online gratis yang mengonversi SVG ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_24}

Konversi sumber SVG yang disajikan oleh jalur file lengkap ke DOCX. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber SVG. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke [DOCX](https://docs.fileformat.com/word-processing/docx/) menggunakan metode ConvertSVG() dari kelas Converter dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke DOCX

Kelas Converter menawarkan beberapa konversi khusus SVG ke DOCX. Untuk mengonversi SVG ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) online gratis yang mengonversi SVG ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_48}

Konversi sumber SVG yang disajikan oleh konten inline ke DOCX. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten SVG inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke [DOCX](https://docs.fileformat.com/word-processing/docx/) menggunakan metode ConvertSVG() dari kelas Converter dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke DOCX

Kelas Converter menawarkan beberapa konversi khusus SVG ke DOCX. Untuk mengonversi SVG ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) online gratis yang mengonversi SVG ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_40}

Konversi sumber SVG yang disajikan oleh konten inline ke DOCX. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) interface implementation.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten SVG inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke [DOCX](https://docs.fileformat.com/word-processing/docx/) menggunakan metode ConvertSVG() dari kelas Converter dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke DOCX

Kelas Converter menawarkan beberapa konversi khusus SVG ke DOCX. Untuk mengonversi SVG ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) online gratis yang mengonversi SVG ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, PdfSaveOptions, String) {#convertsvg_5}

Konversi sumber SVG yang disajikan oleh [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ke PDF. Hasilnya adalah file pdf yang dibentuk oleh jalur file output.

```java
public static void ConvertSVG(SVGDocument source, PdfSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | SVGDocument | Sumber konversi yang disajikan oleh [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Jalur file pdf lengkap sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke PDF menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke PDF

Kelas Converter menawarkan beberapa konversi khusus SVG ke PDF. Untuk mengonversi SVG ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online gratis yang mengonversi SVG ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Bentuk dokumen SVG sebagai sumber konversi
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Mulai proses konversi dengan konfigurasi default
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, String) {#convertsvg_21}

Konversi sumber SVG yang disajikan oleh [`URL`](../../../com.aspose.html/url/). Hasilnya adalah file pdf yang dibentuk oleh jalur file output.

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Dokumen sumber SVG [`URL`](../../../com.aspose.html/url/) - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Jalur file pdf lengkap sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke PDF menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke PDF

Kelas Converter menawarkan beberapa konversi khusus SVG ke PDF. Untuk mengonversi SVG ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online gratis yang mengonversi SVG ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Buat Url berdasarkan jalur file input
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Mulai proses konversi
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, PdfSaveOptions, String) {#convertsvg_13}

Konversi sumber SVG yang disajikan oleh [`URL`](../../../com.aspose.html/url/). Hasilnya adalah file pdf yang dibentuk oleh jalur file output.

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Dokumen sumber SVG [`URL`](../../../com.aspose.html/url/) - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Jalur file pdf lengkap sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke PDF menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke PDF

Kelas Converter menawarkan beberapa konversi khusus SVG ke PDF. Untuk mengonversi SVG ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online gratis yang mengonversi SVG ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Buat Url berdasarkan jalur file input
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertSVG(String, PdfSaveOptions, String) {#convertsvg_37}

Konversi sumber SVG yang disajikan melalui jalur file lengkap ke PDF. Hasilnya berupa file pdf yang dibentuk oleh jalur file output.

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber SVG. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Jalur file pdf lengkap sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke PDF menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke PDF

Kelas Converter menawarkan beberapa konversi khusus SVG ke PDF. Untuk mengonversi SVG ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online gratis yang mengonversi SVG ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Mulai proses konversi
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, PdfSaveOptions, String) {#convertsvg_29}

Konversi sumber SVG yang disajikan melalui jalur file lengkap ke PDF. Hasilnya berupa file pdf yang dibentuk oleh jalur file output.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber SVG. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Jalur file pdf lengkap sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke PDF menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke PDF

Kelas Converter menawarkan beberapa konversi khusus SVG ke PDF. Untuk mengonversi SVG ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online gratis yang mengonversi SVG ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, PdfSaveOptions, String) {#convertsvg_53}

Konversi sumber SVG yang disajikan melalui konten inline ke PDF. Hasilnya adalah file pdf yang dibuat berdasarkan jalur file output.

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten SVG inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Jalur file pdf lengkap sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke PDF menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke PDF

Kelas Converter menawarkan beberapa konversi khusus SVG ke PDF. Untuk mengonversi SVG ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online gratis yang mengonversi SVG ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form konten SVG inline
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Mulai proses konversi
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, String) {#convertsvg_45}

Konversi sumber SVG yang disajikan melalui konten inline ke PDF. Hasilnya adalah file pdf yang dibuat berdasarkan jalur file output.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten SVG inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Jalur file pdf lengkap sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke PDF menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke PDF

Kelas Converter menawarkan beberapa konversi khusus SVG ke PDF. Untuk mengonversi SVG ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online gratis yang mengonversi SVG ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form konten SVG inline
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_4}

Konversi sumber SVG yang disajikan oleh [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ke PDF. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | SVGDocument | Sumber konversi yang disajikan oleh [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) khusus. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke PDF menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke PDF

Kelas Converter menawarkan beberapa konversi khusus SVG ke PDF. Untuk mengonversi SVG ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online gratis yang mengonversi SVG ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Bentuk dokumen SVG sebagai sumber konversi
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Mulai proses konversi dengan konfigurasi default
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_20}

Konversi sumber SVG yang disajikan oleh [`URL`](../../../com.aspose.html/url/). Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Dokumen sumber SVG [`URL`](../../../com.aspose.html/url/) - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) khusus. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke PDF menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke PDF

Kelas Converter menawarkan beberapa konversi khusus SVG ke PDF. Untuk mengonversi SVG ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online gratis yang mengonversi SVG ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Buat Url berdasarkan jalur file input
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi
      Converter.ConvertSVG(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_12}

Konversi sumber SVG yang disajikan oleh [`URL`](../../../com.aspose.html/url/). Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Dokumen sumber SVG [`URL`](../../../com.aspose.html/url/) - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) khusus. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke PDF menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke PDF

Kelas Converter menawarkan beberapa konversi khusus SVG ke PDF. Untuk mengonversi SVG ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online gratis yang mengonversi SVG ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Buat Url berdasarkan jalur file input
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

---

## ConvertSVG(String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_36}

Konversi sumber SVG yang disajikan oleh jalur file lengkap ke PDF. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber SVG. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke PDF menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke PDF

Kelas Converter menawarkan beberapa konversi khusus SVG ke PDF. Untuk mengonversi SVG ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online gratis yang mengonversi SVG ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_28}

Konversi sumber SVG yang disajikan oleh jalur file lengkap ke PDF. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber SVG. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke PDF menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke PDF

Kelas Converter menawarkan beberapa konversi khusus SVG ke PDF. Untuk mengonversi SVG ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online gratis yang mengonversi SVG ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_52}

Konversi sumber SVG yang disajikan oleh konten inline ke PDF. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten SVG inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke PDF menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke PDF

Kelas Converter menawarkan beberapa konversi khusus SVG ke PDF. Untuk mengonversi SVG ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online gratis yang mengonversi SVG ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Mulai proses konversi
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_44}

Konversi sumber SVG yang disajikan oleh konten inline ke PDF. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten SVG inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) khusus. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke PDF menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke PDF

Kelas Converter menawarkan beberapa konversi khusus SVG ke PDF. Untuk mengonversi SVG ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna. Online SVG converter

Aspose.HTML menawarkan [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) online gratis yang mengonversi SVG ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Mulai proses konversi
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, ImageSaveOptions, String) {#convertsvg_3}

Konversi sumber SVG yang disajikan oleh [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Hasilnya adalah file gambar yang dibentuk oleh jalur file output.

```java
public static void ConvertSVG(SVGDocument source, ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | SVGDocument | Sumber konversi yang disajikan oleh [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dimana Anda menemukan informasi tentang cara mengonversi SVG ke JPG menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Artikel terkait format gambar populer lainnya: [konversi SVG ke PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [konversi SVG ke BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [konversi SVG ke GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) dan [konversi SVG ke TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konversi SVG ke Gambar

Kelas Converter menawarkan beberapa konversi khusus SVG ke gambar dalam format populer. Untuk mengonversi SVG ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Perhatikan bahwa format gambar default adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [Konverter SVG ke JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) daring gratis yang mengonversi SVG ke JPG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Konverter gambar populer lainnya untuk format berbeda dapat ditemukan di sini: [Konverter SVG ke PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Konverter SVG ke BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Konverter SVG ke GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) dan [Konverter SVG ke TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions();

      // Bentuk dokumen SVG sebagai sumber konversi
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Mulai proses konversi dengan konfigurasi default
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, String) {#convertsvg_19}

Konversi sumber SVG yang disajikan oleh [`URL`](../../../com.aspose.html/url/). Hasilnya adalah file gambar yang dibentuk oleh jalur file output.

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Dokumen sumber SVG [`URL`](../../../com.aspose.html/url/) - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dimana Anda menemukan informasi tentang cara mengonversi SVG ke JPG menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Artikel terkait format gambar populer lainnya: [konversi SVG ke PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [konversi SVG ke BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [konversi SVG ke GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) dan [konversi SVG ke TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konversi SVG ke Gambar

Kelas Converter menawarkan beberapa konversi khusus SVG ke gambar dalam format populer. Untuk mengonversi SVG ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Perhatikan bahwa format gambar default adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [Konverter SVG ke JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) daring gratis yang mengonversi SVG ke JPG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Konverter gambar populer lainnya untuk format berbeda dapat ditemukan di sini: [Konverter SVG ke PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Konverter SVG ke BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Konverter SVG ke GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) dan [Konverter SVG ke TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Buat Url berdasarkan jalur file input
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Mulai proses konversi
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, ImageSaveOptions, String) {#convertsvg_11}

Konversi sumber SVG yang disajikan oleh [`URL`](../../../com.aspose.html/url/). Hasilnya adalah file gambar yang dibentuk oleh jalur file output.

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Dokumen sumber SVG [`URL`](../../../com.aspose.html/url/) - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dimana Anda menemukan informasi tentang cara mengonversi SVG ke JPG menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Artikel terkait format gambar populer lainnya: [konversi SVG ke PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [konversi SVG ke BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [konversi SVG ke GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) dan [konversi SVG ke TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konversi SVG ke Gambar

Kelas Converter menawarkan beberapa konversi khusus SVG ke gambar dalam format populer. Untuk mengonversi SVG ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Perhatikan bahwa format gambar default adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [Konverter SVG ke JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) daring gratis yang mengonversi SVG ke JPG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Konverter gambar populer lainnya untuk format berbeda dapat ditemukan di sini: [Konverter SVG ke PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Konverter SVG ke BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Konverter SVG ke GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) dan [Konverter SVG ke TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Buat Url berdasarkan jalur file input
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertSVG(String, ImageSaveOptions, String) {#convertsvg_35}

Konversi sumber SVG yang disajikan melalui jalur file lengkap ke gambar. Hasilnya berupa file gambar yang dibentuk oleh jalur file output.

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber SVG. |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dimana Anda menemukan informasi tentang cara mengonversi SVG ke JPG menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Artikel terkait format gambar populer lainnya: [konversi SVG ke PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [konversi SVG ke BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [konversi SVG ke GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) dan [konversi SVG ke TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konversi SVG ke Gambar

Kelas Converter menawarkan beberapa konversi khusus SVG ke gambar dalam format populer. Untuk mengonversi SVG ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Perhatikan bahwa format gambar default adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [Konverter SVG ke JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) daring gratis yang mengonversi SVG ke JPG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Konverter gambar populer lainnya untuk format berbeda dapat ditemukan di sini: [Konverter SVG ke PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Konverter SVG ke BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Konverter SVG ke GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) dan [Konverter SVG ke TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Mulai proses konversi
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, ImageSaveOptions, String) {#convertsvg_27}

Konversi sumber SVG yang disajikan melalui jalur file lengkap ke gambar. Hasilnya berupa file gambar yang dibentuk oleh jalur file output.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber SVG. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dimana Anda menemukan informasi tentang cara mengonversi SVG ke JPG menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Artikel terkait format gambar populer lainnya: [konversi SVG ke PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [konversi SVG ke BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [konversi SVG ke GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) dan [konversi SVG ke TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konversi SVG ke Gambar

Kelas Converter menawarkan beberapa konversi khusus SVG ke gambar dalam format populer. Untuk mengonversi SVG ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Perhatikan bahwa format gambar default adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [Konverter SVG ke JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) daring gratis yang mengonversi SVG ke JPG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Konverter gambar populer lainnya untuk format berbeda dapat ditemukan di sini: [Konverter SVG ke PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Konverter SVG ke BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Konverter SVG ke GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) dan [Konverter SVG ke TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, ImageSaveOptions, String) {#convertsvg_51}

Konversi sumber SVG yang disajikan melalui konten inline ke gambar. Hasilnya adalah file gambar yang dibuat berdasarkan jalur file output.

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten SVG inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dimana Anda menemukan informasi tentang cara mengonversi SVG ke JPG menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Artikel terkait format gambar populer lainnya: [konversi SVG ke PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [konversi SVG ke BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [konversi SVG ke GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) dan [konversi SVG ke TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konversi SVG ke Gambar

Kelas Converter menawarkan beberapa konversi khusus SVG ke gambar dalam format populer. Untuk mengonversi SVG ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Perhatikan bahwa format gambar default adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [Konverter SVG ke JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) daring gratis yang mengonversi SVG ke JPG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Konverter gambar populer lainnya untuk format berbeda dapat ditemukan di sini: [Konverter SVG ke PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Konverter SVG ke BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Konverter SVG ke GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) dan [Konverter SVG ke TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form konten SVG inline
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions();

      // Mulai proses konversi
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, String) {#convertsvg_43}

Konversi sumber SVG yang disajikan melalui konten inline ke gambar. Hasilnya adalah file gambar yang dibuat berdasarkan jalur file output.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten SVG inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dimana Anda menemukan informasi tentang cara mengonversi SVG ke JPG menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Artikel terkait format gambar populer lainnya: [konversi SVG ke PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [konversi SVG ke BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [konversi SVG ke GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) dan [konversi SVG ke TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konversi SVG ke Gambar

Kelas Converter menawarkan beberapa konversi khusus SVG ke gambar dalam format populer. Untuk mengonversi SVG ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Perhatikan bahwa format gambar default adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [Konverter SVG ke JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) daring gratis yang mengonversi SVG ke JPG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Konverter gambar populer lainnya untuk format berbeda dapat ditemukan di sini: [Konverter SVG ke PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Konverter SVG ke BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Konverter SVG ke GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) dan [Konverter SVG ke TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form konten SVG inline
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_2}

Konversi sumber SVG yang disajikan oleh [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | SVGDocument | Sumber konversi yang disajikan oleh [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) khusus. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dimana Anda menemukan informasi tentang cara mengonversi SVG ke JPG menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Artikel terkait format gambar populer lainnya: [konversi SVG ke PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [konversi SVG ke BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [konversi SVG ke GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) dan [konversi SVG ke TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konversi SVG ke Gambar

Kelas Converter menawarkan beberapa konversi khusus SVG ke gambar dalam format populer. Untuk mengonversi SVG ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Perhatikan bahwa format gambar default adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [Konverter SVG ke JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) daring gratis yang mengonversi SVG ke JPG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Konverter gambar populer lainnya untuk format berbeda dapat ditemukan di sini: [Konverter SVG ke PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Konverter SVG ke BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Konverter SVG ke GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) dan [Konverter SVG ke TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Bentuk dokumen SVG sebagai sumber konversi
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Mulai proses konversi
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_18}

Konversi sumber SVG yang disajikan oleh [`URL`](../../../com.aspose.html/url/). Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Dokumen sumber SVG [`URL`](../../../com.aspose.html/url/) - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dimana Anda menemukan informasi tentang cara mengonversi SVG ke JPG menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Artikel terkait format gambar populer lainnya: [konversi SVG ke PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [konversi SVG ke BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [konversi SVG ke GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) dan [konversi SVG ke TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konversi SVG ke Gambar

Kelas Converter menawarkan beberapa konversi khusus SVG ke gambar dalam format populer. Untuk mengonversi SVG ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Perhatikan bahwa format gambar default adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [Konverter SVG ke JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) daring gratis yang mengonversi SVG ke JPG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Konverter gambar populer lainnya untuk format berbeda dapat ditemukan di sini: [Konverter SVG ke PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Konverter SVG ke BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Konverter SVG ke GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) dan [Konverter SVG ke TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Buat Url berdasarkan jalur file input
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_10}

Konversi sumber SVG yang disajikan oleh [`URL`](../../../com.aspose.html/url/). Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Dokumen sumber SVG [`URL`](../../../com.aspose.html/url/) - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dimana Anda menemukan informasi tentang cara mengonversi SVG ke JPG menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Artikel terkait format gambar populer lainnya: [konversi SVG ke PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [konversi SVG ke BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [konversi SVG ke GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) dan [konversi SVG ke TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konversi SVG ke Gambar

Kelas Converter menawarkan beberapa konversi khusus SVG ke gambar dalam format populer. Untuk mengonversi SVG ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Perhatikan bahwa format gambar default adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [Konverter SVG ke JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) daring gratis yang mengonversi SVG ke JPG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Konverter gambar populer lainnya untuk format berbeda dapat ditemukan di sini: [Konverter SVG ke PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Konverter SVG ke BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Konverter SVG ke GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) dan [Konverter SVG ke TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Buat Url berdasarkan jalur file input
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_34}

Konversi sumber SVG yang disajikan oleh jalur file lengkap ke gambar. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber SVG. |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dimana Anda menemukan informasi tentang cara mengonversi SVG ke JPG menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Artikel terkait format gambar populer lainnya: [konversi SVG ke PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [konversi SVG ke BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [konversi SVG ke GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) dan [konversi SVG ke TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konversi SVG ke Gambar

Kelas Converter menawarkan beberapa konversi khusus SVG ke gambar dalam format populer. Untuk mengonversi SVG ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Perhatikan bahwa format gambar default adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [Konverter SVG ke JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) daring gratis yang mengonversi SVG ke JPG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Konverter gambar populer lainnya untuk format berbeda dapat ditemukan di sini: [Konverter SVG ke PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Konverter SVG ke BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Konverter SVG ke GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) dan [Konverter SVG ke TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_26}

Konversi sumber SVG yang disajikan oleh jalur file lengkap ke gambar. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber SVG. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) khusus. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dimana Anda menemukan informasi tentang cara mengonversi SVG ke JPG menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Artikel terkait format gambar populer lainnya: [konversi SVG ke PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [konversi SVG ke BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [konversi SVG ke GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) dan [konversi SVG ke TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konversi SVG ke Gambar

Kelas Converter menawarkan beberapa konversi khusus SVG ke gambar dalam format populer. Untuk mengonversi SVG ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Perhatikan bahwa format gambar default adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [Konverter SVG ke JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) daring gratis yang mengonversi SVG ke JPG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Konverter gambar populer lainnya untuk format berbeda dapat ditemukan di sini: [Konverter SVG ke PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Konverter SVG ke BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Konverter SVG ke GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) dan [Konverter SVG ke TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_50}

Konversi sumber SVG yang disajikan oleh konten inline ke gambar. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten SVG inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Dikenal (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) khusus. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dimana Anda menemukan informasi tentang cara mengonversi SVG ke JPG menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Artikel terkait format gambar populer lainnya: [konversi SVG ke PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [konversi SVG ke BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [konversi SVG ke GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) dan [konversi SVG ke TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konversi SVG ke Gambar

Kelas Converter menawarkan beberapa konversi khusus SVG ke gambar dalam format populer. Untuk mengonversi SVG ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Perhatikan bahwa format gambar default adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [Konverter SVG ke JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) daring gratis yang mengonversi SVG ke JPG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Konverter gambar populer lainnya untuk format berbeda dapat ditemukan di sini: [Konverter SVG ke PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Konverter SVG ke BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Konverter SVG ke GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) dan [Konverter SVG ke TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions();

      // Mulai proses konversi
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_42}

Konversi sumber SVG yang disajikan oleh konten inline ke gambar. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten SVG inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) dimana Anda menemukan informasi tentang cara mengonversi SVG ke JPG menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Artikel terkait format gambar populer lainnya: [konversi SVG ke PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [konversi SVG ke BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [konversi SVG ke GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) dan [konversi SVG ke TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Konversi SVG ke Gambar

Kelas Converter menawarkan beberapa konversi khusus SVG ke gambar dalam format populer. Untuk mengonversi SVG ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Perhatikan bahwa format gambar default adalah PNG. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [Konverter SVG ke JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) daring gratis yang mengonversi SVG ke JPG dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Konverter gambar populer lainnya untuk format berbeda dapat ditemukan di sini: [Konverter SVG ke PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [Konverter SVG ke BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [Konverter SVG ke GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) dan [Konverter SVG ke TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions();

      // Mulai proses konversi
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, XpsSaveOptions, String) {#convertsvg_7}

Konversi sumber SVG yang disajikan oleh [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Hasilnya adalah file xps yang dibentuk oleh jalur file output.

```java
public static void ConvertSVG(SVGDocument source, XpsSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | SVGDocument | Sumber konversi yang disajikan oleh [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Jalur file xps lengkap sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke XPS menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke XPS

Kelas Converter menawarkan beberapa konversi khusus SVG ke XPS. Untuk mengonversi SVG ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) daring gratis yang mengonversi SVG ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Bentuk dokumen SVG sebagai sumber konversi
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
		// Mulai proses konversi dengan konfigurasi default
		Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, String) {#convertsvg_23}

Konversi sumber SVG yang disajikan oleh [`URL`](../../../com.aspose.html/url/). Hasilnya adalah file xps yang dibentuk oleh jalur file output.

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Dokumen sumber SVG [`URL`](../../../com.aspose.html/url/) - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Jalur file xps lengkap sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke XPS menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke XPS

Kelas Converter menawarkan beberapa konversi khusus SVG ke XPS. Untuk mengonversi SVG ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) daring gratis yang mengonversi SVG ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Buat Url berdasarkan jalur file input
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Tentukan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Mulai proses konversi
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, XpsSaveOptions, String) {#convertsvg_15}

Konversi sumber SVG yang disajikan oleh [`URL`](../../../com.aspose.html/url/). Hasilnya adalah file xps yang dibentuk oleh jalur file output.

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Dokumen sumber SVG [`URL`](../../../com.aspose.html/url/) - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Jalur file xps lengkap sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke XPS menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke XPS

Kelas Converter menawarkan beberapa konversi khusus SVG ke XPS. Untuk mengonversi SVG ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) daring gratis yang mengonversi SVG ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Buat Url berdasarkan jalur file input
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Tentukan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, XpsSaveOptions, String) {#convertsvg_39}

Konversi sumber SVG yang disajikan melalui jalur file lengkap ke XPS. Hasilnya berupa file xps yang dibentuk oleh jalur file output.

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber SVG. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. |
| outputPath | String | Jalur file xps lengkap sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke XPS menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke XPS

Kelas Converter menawarkan beberapa konversi khusus SVG ke XPS. Untuk mengonversi SVG ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) daring gratis yang mengonversi SVG ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Tentukan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Mulai proses konversi
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, String) {#convertsvg_31}

Konversi sumber SVG yang disajikan melalui jalur file lengkap ke XPS. Hasilnya berupa file xps yang dibentuk oleh jalur file output.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber SVG. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Jalur file xps lengkap sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke XPS menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke XPS

Kelas Converter menawarkan beberapa konversi khusus SVG ke XPS. Untuk mengonversi SVG ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) daring gratis yang mengonversi SVG ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Form jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Tentukan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, XpsSaveOptions, String) {#convertsvg_55}

Konversi sumber SVG yang disajikan melalui konten inline ke XPS. Hasilnya adalah file xps yang dibuat berdasarkan jalur file output.

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten SVG inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. |
| outputPath | String | Jalur file xps lengkap sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke XPS menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke XPS

Kelas Converter menawarkan beberapa konversi khusus SVG ke XPS. Untuk mengonversi SVG ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) daring gratis yang mengonversi SVG ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Form konten SVG inline
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Tentukan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Mulai proses konversi
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, String) {#convertsvg_47}

Konversi sumber SVG yang disajikan melalui konten inline ke XPS. Hasilnya adalah file xps yang dibuat berdasarkan jalur file output.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | String sebagai konten SVG inline. |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Jalur file xps lengkap sebagai hasil konversi output. |

## Catatan

Konverter SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi SVG ke XPS menggunakan metode ConvertSVG() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi SVG ke XPS

Kelas Converter menawarkan beberapa konversi khusus SVG ke XPS. Untuk mengonversi SVG ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file SVG lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat mendefinisikan [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) sebagai sumber konversi atau bahkan menggunakan konten SVG inline yang disajikan oleh sumber String. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau kustom sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertSVG() dari kelas Converter untuk menyimpan SVG sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter SVG daring

Aspose.HTML menawarkan [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) daring gratis yang mengonversi SVG ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Form konten SVG inline
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Tentukan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
