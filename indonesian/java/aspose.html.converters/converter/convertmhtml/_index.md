---
title: "Converter.ConvertMHTML"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Converter. Konversi sumber MHTML yang disajikan oleh aliran input. Hasilnya adalah file xps yang dibentuk oleh jalur file output"
type: docs

url: /id/java/com.aspose.html.converters/converter/convertmhtml/
---
## ConvertMHTML(Stream, XpsSaveOptions, String) {#convertmhtml_31}

Konversi sumber MHTML yang disajikan melalui input [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). Hasilnya adalah file xps yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran data mhtml (.mht) input. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Jalur file xps lengkap sebagai hasil konversi output. |

## Catatan

Konverter MHTML

Konversi MHTML ke [XPS](https://docs.fileformat.com/page-description-language/xps/) sering diperlukan untuk memanfaatkan format XPS dalam tugas tertentu. File XPS mewakili file tata letak halaman yang berbasis pada XML Paper Specifications, dibuat oleh Microsoft.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi MHTML ke XPS menggunakan metode ConvertHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke XPS

Kelas Converter menawarkan beberapa konversi khusus MHTML ke XPS. Untuk mengonversi MHTML ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratis daring yang mengonversi MHTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulir jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definisikan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Mulai proses konversi
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, String) {#convertmhtml_47}

Konversi sumber MHTML yang disajikan oleh jalur file lengkap ke XPS. Hasilnya adalah file xps yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber MHTML. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Jalur file xps lengkap sebagai hasil konversi output. |

## Catatan

Konverter MHTML

Konversi MHTML ke [XPS](https://docs.fileformat.com/page-description-language/xps/) sering diperlukan untuk memanfaatkan format XPS dalam tugas tertentu. File XPS mewakili file tata letak halaman yang berbasis pada XML Paper Specifications, dibuat oleh Microsoft.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi MHTML ke XPS menggunakan metode ConvertHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke XPS

Kelas Converter menawarkan beberapa konversi khusus MHTML ke XPS. Untuk mengonversi MHTML ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratis daring yang mengonversi MHTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulir jalur file sumber
	var sourcePath = Path.Combine(InputFolder, "sample.mht");

	// Formulir jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Definisikan objek XpsSaveOptions default
	var options = new XpsSaveOptions();

	// Mulai proses konversi
	Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, String) {#convertmhtml_15}

Konversi sumber MHTML yang disajikan oleh URL. Hasilnya adalah file xps yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL dokumen sumber MHTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Jalur file xps lengkap sebagai hasil konversi output. |

## Catatan

Konverter MHTML

Konversi MHTML ke [XPS](https://docs.fileformat.com/page-description-language/xps/) sering diperlukan untuk memanfaatkan format XPS dalam tugas tertentu. File XPS mewakili file tata letak halaman yang berbasis pada XML Paper Specifications, dibuat oleh Microsoft.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi MHTML ke XPS menggunakan metode ConvertHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke XPS

Kelas Converter menawarkan beberapa konversi khusus MHTML ke XPS. Untuk mengonversi MHTML ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratis daring yang mengonversi MHTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Formulir jalur file sumber
	var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

	// Formulir jalur file hasil
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Definisikan objek XpsSaveOptions default
	var options = new XpsSaveOptions();

	// Mulai proses konversi
	Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, String) {#convertmhtml_23}

Konversi sumber MHTML yang disajikan oleh [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) masukan. Hasilnya adalah file xps yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran data sumber konversi mhtml (.mht). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Jalur file xps lengkap sebagai hasil konversi output. |

## Catatan

Konverter MHTML

Konversi MHTML ke [XPS](https://docs.fileformat.com/page-description-language/xps/) sering diperlukan untuk memanfaatkan format XPS dalam tugas tertentu. File XPS mewakili file tata letak halaman yang berbasis pada XML Paper Specifications, dibuat oleh Microsoft.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi MHTML ke XPS menggunakan metode ConvertHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke XPS

Kelas Converter menawarkan beberapa konversi khusus MHTML ke XPS. Untuk mengonversi MHTML ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratis daring yang mengonversi MHTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulir jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definisikan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(File.OpenRead(sourcePath), new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, String) {#convertmhtml_39}

Konversi sumber MHTML yang disajikan oleh jalur file lengkap ke XPS. Hasilnya adalah file xps yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber MHTML. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Jalur file xps lengkap sebagai hasil konversi output. |

## Catatan

Konverter MHTML

Konversi MHTML ke [XPS](https://docs.fileformat.com/page-description-language/xps/) sering diperlukan untuk memanfaatkan format XPS dalam tugas tertentu. File XPS mewakili file tata letak halaman yang berbasis pada XML Paper Specifications, dibuat oleh Microsoft.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi MHTML ke XPS menggunakan metode ConvertHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke XPS

Kelas Converter menawarkan beberapa konversi khusus MHTML ke XPS. Untuk mengonversi MHTML ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratis daring yang mengonversi MHTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulir jalur file sumber
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definisikan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, XpsSaveOptions, String) {#convertmhtml_7}

Konversi sumber MHTML yang disajikan oleh URL. Hasilnya adalah file xps yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL dokumen sumber MHTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Jalur file xps lengkap sebagai hasil konversi output. |

## Catatan

Konverter MHTML

Konversi MHTML ke [XPS](https://docs.fileformat.com/page-description-language/xps/) sering diperlukan untuk memanfaatkan format XPS dalam tugas tertentu. File XPS mewakili file tata letak halaman yang berbasis pada XML Paper Specifications, dibuat oleh Microsoft.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi MHTML ke XPS menggunakan metode ConvertHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke XPS

Kelas Converter menawarkan beberapa konversi khusus MHTML ke XPS. Untuk mengonversi MHTML ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratis daring yang mengonversi MHTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulir jalur file sumber
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Definisikan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_30}

Konversi sumber MHTML yang disajikan melalui aliran masukan. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran data sumber konversi mhtml (.mht). |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter MHTML

Konversi MHTML ke [XPS](https://docs.fileformat.com/page-description-language/xps/) sering diperlukan untuk memanfaatkan format XPS dalam tugas tertentu. File XPS mewakili file tata letak halaman yang berbasis pada XML Paper Specifications, dibuat oleh Microsoft.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi MHTML ke XPS menggunakan metode ConvertHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke XPS

Kelas Converter menawarkan beberapa konversi khusus MHTML ke XPS. Untuk mengonversi MHTML ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratis daring yang mengonversi MHTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definisikan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Mulai proses konversi
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Lihat Juga

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_46}

Konversi sumber MHTML yang disajikan melalui jalur file lengkap ke XPS. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber MHTML. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Diketahui (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kustom. |

## Catatan

Konverter MHTML

Konversi MHTML ke [XPS](https://docs.fileformat.com/page-description-language/xps/) sering diperlukan untuk memanfaatkan format XPS dalam tugas tertentu. File XPS mewakili file tata letak halaman yang berbasis pada XML Paper Specifications, dibuat oleh Microsoft.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi MHTML ke XPS menggunakan metode ConvertHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke XPS

Kelas Converter menawarkan beberapa konversi khusus MHTML ke XPS. Untuk mengonversi MHTML ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratis daring yang mengonversi MHTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisikan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi
      Converter.ConvertMHTML(sourcePath, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Lihat Juga

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_14}

Konversi sumber MHTML yang disajikan melalui [`URL`](../../../com.aspose.html/url/). Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL dokumen sumber MHTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter MHTML

Konversi MHTML ke [XPS](https://docs.fileformat.com/page-description-language/xps/) sering diperlukan untuk memanfaatkan format XPS dalam tugas tertentu. File XPS mewakili file tata letak halaman yang berbasis pada XML Paper Specifications, dibuat oleh Microsoft.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi MHTML ke XPS menggunakan metode ConvertHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke XPS

Kelas Converter menawarkan beberapa konversi khusus MHTML ke XPS. Untuk mengonversi MHTML ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratis daring yang mengonversi MHTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisikan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi
      Converter.ConvertMHTML(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_22}

Konversi sumber MHTML yang disajikan melalui aliran masukan. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran data sumber konversi mhtml (.mht). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter MHTML

Konversi MHTML ke [XPS](https://docs.fileformat.com/page-description-language/xps/) sering diperlukan untuk memanfaatkan format XPS dalam tugas tertentu. File XPS mewakili file tata letak halaman yang berbasis pada XML Paper Specifications, dibuat oleh Microsoft.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi MHTML ke XPS menggunakan metode ConvertHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke XPS

Kelas Converter menawarkan beberapa konversi khusus MHTML ke XPS. Untuk mengonversi MHTML ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratis daring yang mengonversi MHTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Definisikan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertMHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_38}

Konversi sumber MHTML yang disajikan melalui jalur file lengkap ke XPS. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber MHTML. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Diketahui (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kustom. |

## Catatan

Konverter MHTML

Konversi MHTML ke [XPS](https://docs.fileformat.com/page-description-language/xps/) sering diperlukan untuk memanfaatkan format XPS dalam tugas tertentu. File XPS mewakili file tata letak halaman yang berbasis pada XML Paper Specifications, dibuat oleh Microsoft.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi MHTML ke XPS menggunakan metode ConvertHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke XPS

Kelas Converter menawarkan beberapa konversi khusus MHTML ke XPS. Untuk mengonversi MHTML ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratis daring yang mengonversi MHTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisikan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_6}

Konversi sumber MHTML yang disajikan melalui URL. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL dokumen sumber MHTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | XpsSaveOptions | Penggunaan objek [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Diketahui (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kustom. |

## Catatan

Konverter MHTML

Konversi MHTML ke [XPS](https://docs.fileformat.com/page-description-language/xps/) sering diperlukan untuk memanfaatkan format XPS dalam tugas tertentu. File XPS mewakili file tata letak halaman yang berbasis pada XML Paper Specifications, dibuat oleh Microsoft.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) di mana Anda menemukan informasi tentang cara mengonversi MHTML ke XPS menggunakan metode ConvertHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke XPS

Kelas Converter menawarkan beberapa konversi khusus MHTML ke XPS. Untuk mengonversi MHTML ke XPS, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil XPS dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratis daring yang mengonversi MHTML ke XPS dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Definisikan objek XpsSaveOptions default
      var options = new XpsSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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

## ConvertMHTML(Stream, DocSaveOptions, String) {#convertmhtml_25}

Konversi sumber MHTML yang disajikan melalui aliran masukan. Hasilnya adalah file docx yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran data masukan konversi MHTML. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Jalur lengkap file docx sebagai hasil konversi output. |

## Catatan

Konverter MHTML

Konversi MHTML ke DOCX sering diperlukan untuk memanfaatkan format [DOCX](https://docs.fileformat.com/word-processing/docx/) pada tugas tertentu. DOCX adalah format yang dikenal luas untuk dokumen Microsoft Word. Format ini dapat berisi berbagai jenis data, termasuk teks, tabel, grafik raster dan vektor, video, suara, serta diagram. Format ini populer karena mendukung fitur pemformatan kompleks dan menawarkan pengguna berbagai opsi untuk menulis segala jenis dokumen.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dimana Anda menemukan informasi tentang cara mengonversi MHTML ke DOCX menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke DOCX

Kelas Converter menawarkan beberapa konversi khusus MHTML ke DOCX. Untuk mengonversi MHTML ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) daring gratis yang mengonversi MHTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Lihat Juga

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, String) {#convertmhtml_41}

Konversi sumber MHTML yang disajikan melalui jalur file lengkap ke DOCX. Hasilnya adalah file docx yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file sumber MHTML. Jalur ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Jalur lengkap file docx sebagai hasil konversi output. |

## Catatan

Konverter MHTML

Konversi MHTML ke DOCX sering diperlukan untuk memanfaatkan format [DOCX](https://docs.fileformat.com/word-processing/docx/) pada tugas tertentu. DOCX adalah format yang dikenal luas untuk dokumen Microsoft Word. Format ini dapat berisi berbagai jenis data, termasuk teks, tabel, grafik raster dan vektor, video, suara, serta diagram. Format ini populer karena mendukung fitur pemformatan kompleks dan menawarkan pengguna berbagai opsi untuk menulis segala jenis dokumen.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dimana Anda menemukan informasi tentang cara mengonversi MHTML ke DOCX menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke DOCX

Kelas Converter menawarkan beberapa konversi khusus MHTML ke DOCX. Untuk mengonversi MHTML ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) daring gratis yang mengonversi MHTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, String) {#convertmhtml_9}

Konversi sumber MHTML yang disajikan oleh URL. Hasilnya adalah file docx yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL dokumen sumber MHTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Jalur lengkap file docx sebagai hasil konversi output. |

## Catatan

Konverter MHTML

Konversi MHTML ke DOCX sering diperlukan untuk memanfaatkan format [DOCX](https://docs.fileformat.com/word-processing/docx/) pada tugas tertentu. DOCX adalah format yang dikenal luas untuk dokumen Microsoft Word. Format ini dapat berisi berbagai jenis data, termasuk teks, tabel, grafik raster dan vektor, video, suara, serta diagram. Format ini populer karena mendukung fitur pemformatan kompleks dan menawarkan pengguna berbagai opsi untuk menulis segala jenis dokumen.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dimana Anda menemukan informasi tentang cara mengonversi MHTML ke DOCX menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke DOCX

Kelas Converter menawarkan beberapa konversi khusus MHTML ke DOCX. Untuk mengonversi MHTML ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) daring gratis yang mengonversi MHTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi
      Converter.ConvertMHTML(sourceUrl, options, resultPath);





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

## ConvertMHTML(Stream, Configuration, DocSaveOptions, String) {#convertmhtml_17}

Konversi sumber MHTML yang disajikan melalui aliran masukan. Hasilnya adalah file docx yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran data masukan konversi MHTML. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Jalur lengkap file docx sebagai hasil konversi output. |

## Catatan

Konverter MHTML

Konversi MHTML ke DOCX sering diperlukan untuk memanfaatkan format [DOCX](https://docs.fileformat.com/word-processing/docx/) pada tugas tertentu. DOCX adalah format yang dikenal luas untuk dokumen Microsoft Word. Format ini dapat berisi berbagai jenis data, termasuk teks, tabel, grafik raster dan vektor, video, suara, serta diagram. Format ini populer karena mendukung fitur pemformatan kompleks dan menawarkan pengguna berbagai opsi untuk menulis segala jenis dokumen.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dimana Anda menemukan informasi tentang cara mengonversi MHTML ke DOCX menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke DOCX

Kelas Converter menawarkan beberapa konversi khusus MHTML ke DOCX. Untuk mengonversi MHTML ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) daring gratis yang mengonversi MHTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, DocSaveOptions, String) {#convertmhtml_33}

Konversi sumber MHTML yang disajikan melalui jalur file lengkap ke DOCX. Hasilnya adalah file docx yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber MHTML. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Jalur lengkap file docx sebagai hasil konversi output. |

## Catatan

Konverter MHTML

Konversi MHTML ke DOCX sering diperlukan untuk memanfaatkan format [DOCX](https://docs.fileformat.com/word-processing/docx/) pada tugas tertentu. DOCX adalah format yang dikenal luas untuk dokumen Microsoft Word. Format ini dapat berisi berbagai jenis data, termasuk teks, tabel, grafik raster dan vektor, video, suara, serta diagram. Format ini populer karena mendukung fitur pemformatan kompleks dan menawarkan pengguna berbagai opsi untuk menulis segala jenis dokumen.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dimana Anda menemukan informasi tentang cara mengonversi MHTML ke DOCX menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke DOCX

Kelas Converter menawarkan beberapa konversi khusus MHTML ke DOCX. Untuk mengonversi MHTML ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) daring gratis yang mengonversi MHTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, DocSaveOptions, String) {#convertmhtml_1}

Konversi sumber MHTML yang disajikan melalui [`URL`](../../../com.aspose.html/url/). Hasilnya adalah file docx yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | Dokumen sumber MHTML [`URL`](../../../com.aspose.html/url/) - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Jalur lengkap file docx sebagai hasil konversi output. |

## Catatan

Konverter MHTML

Konversi MHTML ke DOCX sering diperlukan untuk memanfaatkan format [DOCX](https://docs.fileformat.com/word-processing/docx/) pada tugas tertentu. DOCX adalah format yang dikenal luas untuk dokumen Microsoft Word. Format ini dapat berisi berbagai jenis data, termasuk teks, tabel, grafik raster dan vektor, video, suara, serta diagram. Format ini populer karena mendukung fitur pemformatan kompleks dan menawarkan pengguna berbagai opsi untuk menulis segala jenis dokumen.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dimana Anda menemukan informasi tentang cara mengonversi MHTML ke DOCX menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke DOCX

Kelas Converter menawarkan beberapa konversi khusus MHTML ke DOCX. Untuk mengonversi MHTML ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) daring gratis yang mengonversi MHTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_24}

Konversi sumber MHTML yang disajikan melalui aliran masukan. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran data masukan konversi MHTML. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter MHTML

Konversi MHTML ke DOCX sering diperlukan untuk memanfaatkan format [DOCX](https://docs.fileformat.com/word-processing/docx/) pada tugas tertentu. DOCX adalah format yang dikenal luas untuk dokumen Microsoft Word. Format ini dapat berisi berbagai jenis data, termasuk teks, tabel, grafik raster dan vektor, video, suara, serta diagram. Format ini populer karena mendukung fitur pemformatan kompleks dan menawarkan pengguna berbagai opsi untuk menulis segala jenis dokumen.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dimana Anda menemukan informasi tentang cara mengonversi MHTML ke DOCX menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke DOCX

Kelas Converter menawarkan beberapa konversi khusus MHTML ke DOCX. Untuk mengonversi MHTML ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) daring gratis yang mengonversi MHTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_40}

Konversi sumber MHTML yang disajikan melalui jalur file lengkap ke DOCX. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber MHTML. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter MHTML

Konversi MHTML ke DOCX sering diperlukan untuk memanfaatkan format [DOCX](https://docs.fileformat.com/word-processing/docx/) pada tugas tertentu. DOCX adalah format yang dikenal luas untuk dokumen Microsoft Word. Format ini dapat berisi berbagai jenis data, termasuk teks, tabel, grafik raster dan vektor, video, suara, serta diagram. Format ini populer karena mendukung fitur pemformatan kompleks dan menawarkan pengguna berbagai opsi untuk menulis segala jenis dokumen.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dimana Anda menemukan informasi tentang cara mengonversi MHTML ke DOCX menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke DOCX

Kelas Converter menawarkan beberapa konversi khusus MHTML ke DOCX. Untuk mengonversi MHTML ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) daring gratis yang mengonversi MHTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_8}

Konversi sumber MHTML yang disajikan melalui URL. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | Dokumen sumber MHTML [`URL`](../../../com.aspose.html/url/) - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Diketahui (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kustom. |

## Catatan

Konverter MHTML

Konversi MHTML ke DOCX sering diperlukan untuk memanfaatkan format [DOCX](https://docs.fileformat.com/word-processing/docx/) pada tugas tertentu. DOCX adalah format yang dikenal luas untuk dokumen Microsoft Word. Format ini dapat berisi berbagai jenis data, termasuk teks, tabel, grafik raster dan vektor, video, suara, serta diagram. Format ini populer karena mendukung fitur pemformatan kompleks dan menawarkan pengguna berbagai opsi untuk menulis segala jenis dokumen.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dimana Anda menemukan informasi tentang cara mengonversi MHTML ke DOCX menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke DOCX

Kelas Converter menawarkan beberapa konversi khusus MHTML ke DOCX. Untuk mengonversi MHTML ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) daring gratis yang mengonversi MHTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi
      Converter.ConvertMHTML(sourceUrl, options, sp);
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

## ConvertMHTML(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_16}

Konversi sumber MHTML yang disajikan melalui aliran masukan. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran data masukan konversi MHTML. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Diketahui (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kustom. |

## Catatan

Konverter MHTML

Konversi MHTML ke DOCX sering diperlukan untuk memanfaatkan format [DOCX](https://docs.fileformat.com/word-processing/docx/) pada tugas tertentu. DOCX adalah format yang dikenal luas untuk dokumen Microsoft Word. Format ini dapat berisi berbagai jenis data, termasuk teks, tabel, grafik raster dan vektor, video, suara, serta diagram. Format ini populer karena mendukung fitur pemformatan kompleks dan menawarkan pengguna berbagai opsi untuk menulis segala jenis dokumen.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dimana Anda menemukan informasi tentang cara mengonversi MHTML ke DOCX menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke DOCX

Kelas Converter menawarkan beberapa konversi khusus MHTML ke DOCX. Untuk mengonversi MHTML ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) daring gratis yang mengonversi MHTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_32}

Konversi sumber MHTML yang disajikan melalui jalur file lengkap ke DOCX. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber MHTML. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter MHTML

Konversi MHTML ke DOCX sering diperlukan untuk memanfaatkan format [DOCX](https://docs.fileformat.com/word-processing/docx/) pada tugas tertentu. DOCX adalah format yang dikenal luas untuk dokumen Microsoft Word. Format ini dapat berisi berbagai jenis data, termasuk teks, tabel, grafik raster dan vektor, video, suara, serta diagram. Format ini populer karena mendukung fitur pemformatan kompleks dan menawarkan pengguna berbagai opsi untuk menulis segala jenis dokumen.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dimana Anda menemukan informasi tentang cara mengonversi MHTML ke DOCX menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke DOCX

Kelas Converter menawarkan beberapa konversi khusus MHTML ke DOCX. Untuk mengonversi MHTML ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) daring gratis yang mengonversi MHTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml}

Konversi sumber MHTML yang disajikan melalui [`URL`](../../../com.aspose.html/url/). Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | Dokumen sumber MHTML [`URL`](../../../com.aspose.html/url/) - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | DocSaveOptions | Penggunaan objek [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter MHTML

Konversi MHTML ke DOCX sering diperlukan untuk memanfaatkan format [DOCX](https://docs.fileformat.com/word-processing/docx/) pada tugas tertentu. DOCX adalah format yang dikenal luas untuk dokumen Microsoft Word. Format ini dapat berisi berbagai jenis data, termasuk teks, tabel, grafik raster dan vektor, video, suara, serta diagram. Format ini populer karena mendukung fitur pemformatan kompleks dan menawarkan pengguna berbagai opsi untuk menulis segala jenis dokumen.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) dimana Anda menemukan informasi tentang cara mengonversi MHTML ke DOCX menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke DOCX

Kelas Converter menawarkan beberapa konversi khusus MHTML ke DOCX. Untuk mengonversi MHTML ke DOCX, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau remote [`Url`](../../../com.aspose.html/url/) sebagai sumber konversi. Anda juga dapat menggunakan aliran standar atau khusus sebagai sumber konversi. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) dengan pengaturan khusus atau default. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi. Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil DOCX dengan tiga atau lebih parameter tergantung pada skenario pengguna. Konverter MHTML daring

Aspose.HTML menawarkan [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) daring gratis yang mengonversi MHTML ke DOCX dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek DocSaveOptions default
      var options = new DocSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source folder path.

*OutputFolder - user output folder path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, String) {#convertmhtml_29}

Konversi sumber MHTML yang disajikan melalui aliran masukan. Hasilnya adalah file pdf yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran data masukan konversi MHTML. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Jalur file pdf lengkap sebagai hasil konversi output. |

## Catatan

Konverter MHTML

Konversi MHTML ke PDF sering diperlukan untuk memanfaatkan format [PDF](https://docs.fileformat.com/pdf/) pada tugas tertentu. PDF memiliki banyak manfaat yang tidak dimiliki file lain. Misalnya, banyak program dan aplikasi mendukung dokumen PDF; file PDF dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda dapat mengonfigurasi pengaturan keamanan untuk file PDF - menonaktifkan pencetakan, penyuntingan, penggunaan tanda tangan elektronik, dll.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dimana Anda menemukan informasi tentang cara mengonversi MHTML ke PDF menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke PDF

Kelas Converter menawarkan beberapa konversi khusus MHTML ke PDF. Untuk mengonversi MHTML ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file MHTML (.mht) lokal yang ada atau Url remote sebagai sumber konversi. Anda juga dapat menggunakan [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standar atau khusus sebagai sumber.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan spesifik atau default. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online gratis yang mengonversi MHTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Mulai proses konversi
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, String) {#convertmhtml_45}

Konversi sumber MHTML yang disajikan oleh jalur file lengkap ke PDF. Hasilnya adalah file pdf yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber MHTML. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Jalur file pdf lengkap sebagai hasil konversi output. |

## Catatan

Konverter MHTML

Konversi MHTML ke PDF sering diperlukan untuk memanfaatkan format [PDF](https://docs.fileformat.com/pdf/) pada tugas tertentu. PDF memiliki banyak manfaat yang tidak dimiliki file lain. Misalnya, banyak program dan aplikasi mendukung dokumen PDF; file PDF dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda dapat mengonfigurasi pengaturan keamanan untuk file PDF - menonaktifkan pencetakan, penyuntingan, penggunaan tanda tangan elektronik, dll.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dimana Anda menemukan informasi tentang cara mengonversi MHTML ke PDF menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke PDF

Kelas Converter menawarkan beberapa konversi khusus MHTML ke PDF. Untuk mengonversi MHTML ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file MHTML (.mht) lokal yang ada atau Url remote sebagai sumber konversi. Anda juga dapat menggunakan [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standar atau khusus sebagai sumber.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan spesifik atau default. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online gratis yang mengonversi MHTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Mulai proses konversi
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, String) {#convertmhtml_13}

Konversi sumber MHTML yang disajikan oleh URL. Hasilnya adalah file pdf yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL dokumen sumber MHTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Jalur file pdf lengkap sebagai hasil konversi output. |

## Catatan

Konverter MHTML

Konversi MHTML ke PDF sering diperlukan untuk memanfaatkan format [PDF](https://docs.fileformat.com/pdf/) pada tugas tertentu. PDF memiliki banyak manfaat yang tidak dimiliki file lain. Misalnya, banyak program dan aplikasi mendukung dokumen PDF; file PDF dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda dapat mengonfigurasi pengaturan keamanan untuk file PDF - menonaktifkan pencetakan, penyuntingan, penggunaan tanda tangan elektronik, dll.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dimana Anda menemukan informasi tentang cara mengonversi MHTML ke PDF menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke PDF

Kelas Converter menawarkan beberapa konversi khusus MHTML ke PDF. Untuk mengonversi MHTML ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file MHTML (.mht) lokal yang ada atau Url remote sebagai sumber konversi. Anda juga dapat menggunakan [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standar atau khusus sebagai sumber.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan spesifik atau default. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online gratis yang mengonversi MHTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Mulai proses konversi
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, String) {#convertmhtml_21}

Konversi sumber MHTML yang disajikan melalui aliran masukan. Hasilnya adalah file pdf yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran data masukan konversi MHTML. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Jalur file pdf lengkap sebagai hasil konversi output. |

## Catatan

Konverter MHTML

Konversi MHTML ke PDF sering diperlukan untuk memanfaatkan format [PDF](https://docs.fileformat.com/pdf/) pada tugas tertentu. PDF memiliki banyak manfaat yang tidak dimiliki file lain. Misalnya, banyak program dan aplikasi mendukung dokumen PDF; file PDF dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda dapat mengonfigurasi pengaturan keamanan untuk file PDF - menonaktifkan pencetakan, penyuntingan, penggunaan tanda tangan elektronik, dll.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dimana Anda menemukan informasi tentang cara mengonversi MHTML ke PDF menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke PDF

Kelas Converter menawarkan beberapa konversi khusus MHTML ke PDF. Untuk mengonversi MHTML ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file MHTML (.mht) lokal yang ada atau Url remote sebagai sumber konversi. Anda juga dapat menggunakan [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standar atau khusus sebagai sumber.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan spesifik atau default. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online gratis yang mengonversi MHTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, PdfSaveOptions, String) {#convertmhtml_37}

Konversi sumber MHTML yang disajikan oleh jalur file lengkap ke PDF. Hasilnya adalah file pdf yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file sumber MHTML. Jalur ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Jalur file pdf lengkap sebagai hasil konversi output. |

## Catatan

Konverter MHTML

Konversi MHTML ke PDF sering diperlukan untuk memanfaatkan format [PDF](https://docs.fileformat.com/pdf/) pada tugas tertentu. PDF memiliki banyak manfaat yang tidak dimiliki file lain. Misalnya, banyak program dan aplikasi mendukung dokumen PDF; file PDF dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda dapat mengonfigurasi pengaturan keamanan untuk file PDF - menonaktifkan pencetakan, penyuntingan, penggunaan tanda tangan elektronik, dll.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dimana Anda menemukan informasi tentang cara mengonversi MHTML ke PDF menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke PDF

Kelas Converter menawarkan beberapa konversi khusus MHTML ke PDF. Untuk mengonversi MHTML ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file MHTML (.mht) lokal yang ada atau Url remote sebagai sumber konversi. Anda juga dapat menggunakan [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standar atau khusus sebagai sumber.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan spesifik atau default. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online gratis yang mengonversi MHTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, PdfSaveOptions, String) {#convertmhtml_5}

Konversi sumber MHTML yang disajikan oleh URL. Hasilnya adalah file pdf yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL dokumen sumber MHTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Jalur file pdf lengkap sebagai hasil konversi output. |

## Catatan

Konverter MHTML

Konversi MHTML ke PDF sering diperlukan untuk memanfaatkan format [PDF](https://docs.fileformat.com/pdf/) pada tugas tertentu. PDF memiliki banyak manfaat yang tidak dimiliki file lain. Misalnya, banyak program dan aplikasi mendukung dokumen PDF; file PDF dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda dapat mengonfigurasi pengaturan keamanan untuk file PDF - menonaktifkan pencetakan, penyuntingan, penggunaan tanda tangan elektronik, dll.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dimana Anda menemukan informasi tentang cara mengonversi MHTML ke PDF menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke PDF

Kelas Converter menawarkan beberapa konversi khusus MHTML ke PDF. Untuk mengonversi MHTML ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file MHTML (.mht) lokal yang ada atau Url remote sebagai sumber konversi. Anda juga dapat menggunakan [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standar atau khusus sebagai sumber.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan spesifik atau default. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online gratis yang mengonversi MHTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_28}

Konversi sumber MHTML yang disajikan melalui aliran masukan. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran data masukan konversi MHTML. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Diketahui (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kustom. |

## Catatan

Konverter MHTML

Konversi MHTML ke PDF sering diperlukan untuk memanfaatkan format [PDF](https://docs.fileformat.com/pdf/) pada tugas tertentu. PDF memiliki banyak manfaat yang tidak dimiliki file lain. Misalnya, banyak program dan aplikasi mendukung dokumen PDF; file PDF dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda dapat mengonfigurasi pengaturan keamanan untuk file PDF - menonaktifkan pencetakan, penyuntingan, penggunaan tanda tangan elektronik, dll.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dimana Anda menemukan informasi tentang cara mengonversi MHTML ke PDF menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke PDF

Kelas Converter menawarkan beberapa konversi khusus MHTML ke PDF. Untuk mengonversi MHTML ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file MHTML (.mht) lokal yang ada atau Url remote sebagai sumber konversi. Anda juga dapat menggunakan [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standar atau khusus sebagai sumber.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan spesifik atau default. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online gratis yang mengonversi MHTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Mulai proses konversi
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_44}

Konversi sumber MHTML yang disajikan dengan jalur file lengkap ke PDF. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file sumber MHTML. Jalur ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter MHTML

Konversi MHTML ke PDF sering diperlukan untuk memanfaatkan format [PDF](https://docs.fileformat.com/pdf/) pada tugas tertentu. PDF memiliki banyak manfaat yang tidak dimiliki file lain. Misalnya, banyak program dan aplikasi mendukung dokumen PDF; file PDF dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda dapat mengonfigurasi pengaturan keamanan untuk file PDF - menonaktifkan pencetakan, penyuntingan, penggunaan tanda tangan elektronik, dll.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dimana Anda menemukan informasi tentang cara mengonversi MHTML ke PDF menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke PDF

Kelas Converter menawarkan beberapa konversi khusus MHTML ke PDF. Untuk mengonversi MHTML ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file MHTML (.mht) lokal yang ada atau Url remote sebagai sumber konversi. Anda juga dapat menggunakan [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standar atau khusus sebagai sumber.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan spesifik atau default. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online gratis yang mengonversi MHTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_12}

Konversi sumber MHTML yang disajikan melalui URL. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL dokumen sumber MHTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter MHTML

Konversi MHTML ke PDF sering diperlukan untuk memanfaatkan format [PDF](https://docs.fileformat.com/pdf/) pada tugas tertentu. PDF memiliki banyak manfaat yang tidak dimiliki file lain. Misalnya, banyak program dan aplikasi mendukung dokumen PDF; file PDF dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda dapat mengonfigurasi pengaturan keamanan untuk file PDF - menonaktifkan pencetakan, penyuntingan, penggunaan tanda tangan elektronik, dll.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dimana Anda menemukan informasi tentang cara mengonversi MHTML ke PDF menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke PDF

Kelas Converter menawarkan beberapa konversi khusus MHTML ke PDF. Untuk mengonversi MHTML ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file MHTML (.mht) lokal yang ada atau Url remote sebagai sumber konversi. Anda juga dapat menggunakan [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standar atau khusus sebagai sumber.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan spesifik atau default. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online gratis yang mengonversi MHTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi
      Converter.ConvertMHTML(sourceUrl, options, sp);
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

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_20}

Konversi sumber MHTML yang disajikan melalui aliran masukan. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran data masukan konversi MHTML. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter MHTML

Konversi MHTML ke PDF sering diperlukan untuk memanfaatkan format [PDF](https://docs.fileformat.com/pdf/) pada tugas tertentu. PDF memiliki banyak manfaat yang tidak dimiliki file lain. Misalnya, banyak program dan aplikasi mendukung dokumen PDF; file PDF dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda dapat mengonfigurasi pengaturan keamanan untuk file PDF - menonaktifkan pencetakan, penyuntingan, penggunaan tanda tangan elektronik, dll.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dimana Anda menemukan informasi tentang cara mengonversi MHTML ke PDF menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke PDF

Kelas Converter menawarkan beberapa konversi khusus MHTML ke PDF. Untuk mengonversi MHTML ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file MHTML (.mht) lokal yang ada atau Url remote sebagai sumber konversi. Anda juga dapat menggunakan [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standar atau khusus sebagai sumber.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan spesifik atau default. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online gratis yang mengonversi MHTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_36}

Konversi sumber MHTML yang disajikan dengan jalur file lengkap ke PDF. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber MHTML. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter MHTML

Konversi MHTML ke PDF sering diperlukan untuk memanfaatkan format [PDF](https://docs.fileformat.com/pdf/) pada tugas tertentu. PDF memiliki banyak manfaat yang tidak dimiliki file lain. Misalnya, banyak program dan aplikasi mendukung dokumen PDF; file PDF dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda dapat mengonfigurasi pengaturan keamanan untuk file PDF - menonaktifkan pencetakan, penyuntingan, penggunaan tanda tangan elektronik, dll.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dimana Anda menemukan informasi tentang cara mengonversi MHTML ke PDF menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke PDF

Kelas Converter menawarkan beberapa konversi khusus MHTML ke PDF. Untuk mengonversi MHTML ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file MHTML (.mht) lokal yang ada atau Url remote sebagai sumber konversi. Anda juga dapat menggunakan [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standar atau khusus sebagai sumber.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan spesifik atau default. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online gratis yang mengonversi MHTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_4}

Konversi sumber MHTML yang disajikan melalui [`URL`](../../../com.aspose.html/url/). Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL dokumen sumber MHTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | PdfSaveOptions | Penggunaan objek [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Untuk info lebih lanjut lihat [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter MHTML

Konversi MHTML ke PDF sering diperlukan untuk memanfaatkan format [PDF](https://docs.fileformat.com/pdf/) pada tugas tertentu. PDF memiliki banyak manfaat yang tidak dimiliki file lain. Misalnya, banyak program dan aplikasi mendukung dokumen PDF; file PDF dioptimalkan untuk pencetakan, dan ideal untuk membuat salinan fisik dokumen Anda; Anda dapat mengonfigurasi pengaturan keamanan untuk file PDF - menonaktifkan pencetakan, penyuntingan, penggunaan tanda tangan elektronik, dll.

Lihat [article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), dimana Anda menemukan informasi tentang cara mengonversi MHTML ke PDF menggunakan metode ConvertMHTML() dari kelas [`Converter`](../) dan cara menerapkan parameter [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) serta [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke PDF

Kelas Converter menawarkan beberapa konversi khusus MHTML ke PDF. Untuk mengonversi MHTML ke PDF, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Source konversi. Deteksi file MHTML (.mht) lokal yang ada atau Url remote sebagai sumber konversi. Anda juga dapat menggunakan [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standar atau khusus sebagai sumber.Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output.Buat objek baru [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) dengan pengaturan spesifik atau default. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil PDF dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) online gratis yang mengonversi MHTML ke PDF dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek PdfSaveOptions default
      var options = new PdfSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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

## ConvertMHTML(Stream, ImageSaveOptions, String) {#convertmhtml_27}

Konversi sumber MHTML yang disajikan melalui aliran masukan ke gambar. Hasilnya adalah file gambar yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran data masukan konversi MHTML. |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Konverter MHTML

File dengan ekstensi [MHTML](https://docs.fileformat.com/web/mhtml/) merupakan format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. Format ini dikenal sebagai format arsip karena menyimpan kode HTML web dan sumber daya terkait dalam satu file. Sumber daya ini mencakup apa saja yang terhubung ke halaman web seperti gambar, applet, animasi, file audio, dan sebagainya. File MHTML dapat dibuka dalam berbagai aplikasi seperti Internet Explorer dan Microsoft Word. Spesifikasi sebenarnya dari format ini dijelaskan secara detail oleh [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Rujuk ke artikel, di mana Anda menemukan informasi tentang cara mengonversi MHTML ke gambar dalam berbagai format menggunakan metode ConvertMHTML() dari kelas Converter serta cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke Gambar

Kelas Converter menawarkan beberapa konversi khusus MHTML ke gambar. Format yang didukung adalah [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/), dan [TIFF](https://docs.fileformat.com/image/tiff/). Untuk mengonversi MHTML ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau [`Url`](../../../com.aspose.html/url/) remote sebagai sumber konversi. Anda juga dapat menggunakan stream standar atau khusus sebagai sumber. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Format gambar default adalah PNG. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online gratis yang mengonversi MHTML ke file jpeg dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Mulai proses konversi
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, String) {#convertmhtml_43}

Konversi sumber MHTML yang disajikan melalui jalur file lengkap. Hasilnya adalah file gambar yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber MHTML. |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Konverter MHTML

File dengan ekstensi [MHTML](https://docs.fileformat.com/web/mhtml/) merupakan format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. Format ini dikenal sebagai format arsip karena menyimpan kode HTML web dan sumber daya terkait dalam satu file. Sumber daya ini mencakup apa saja yang terhubung ke halaman web seperti gambar, applet, animasi, file audio, dan sebagainya. File MHTML dapat dibuka dalam berbagai aplikasi seperti Internet Explorer dan Microsoft Word. Spesifikasi sebenarnya dari format ini dijelaskan secara detail oleh [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Rujuk ke artikel, di mana Anda menemukan informasi tentang cara mengonversi MHTML ke gambar dalam berbagai format menggunakan metode ConvertMHTML() dari kelas Converter serta cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke Gambar

Kelas Converter menawarkan beberapa konversi khusus MHTML ke gambar. Format yang didukung adalah [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/), dan [TIFF](https://docs.fileformat.com/image/tiff/). Untuk mengonversi MHTML ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau [`Url`](../../../com.aspose.html/url/) remote sebagai sumber konversi. Anda juga dapat menggunakan stream standar atau khusus sebagai sumber. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Format gambar default adalah PNG. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online gratis yang mengonversi MHTML ke file jpeg dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Mulai proses konversi
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Lihat Juga

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, String) {#convertmhtml_11}

Konversi sumber MHTML yang disajikan oleh URL. Hasilnya adalah file gambar yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL dokumen sumber MHTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Konverter MHTML

File dengan ekstensi [MHTML](https://docs.fileformat.com/web/mhtml/) merupakan format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. Format ini dikenal sebagai format arsip karena menyimpan kode HTML web dan sumber daya terkait dalam satu file. Sumber daya ini mencakup apa saja yang terhubung ke halaman web seperti gambar, applet, animasi, file audio, dan sebagainya. File MHTML dapat dibuka dalam berbagai aplikasi seperti Internet Explorer dan Microsoft Word. Spesifikasi sebenarnya dari format ini dijelaskan secara detail oleh [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Rujuk ke artikel, di mana Anda menemukan informasi tentang cara mengonversi MHTML ke gambar dalam berbagai format menggunakan metode ConvertMHTML() dari kelas Converter serta cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke Gambar

Kelas Converter menawarkan beberapa konversi khusus MHTML ke gambar. Format yang didukung adalah [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/), dan [TIFF](https://docs.fileformat.com/image/tiff/). Untuk mengonversi MHTML ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau [`Url`](../../../com.aspose.html/url/) remote sebagai sumber konversi. Anda juga dapat menggunakan stream standar atau khusus sebagai sumber. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Format gambar default adalah PNG. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online gratis yang mengonversi MHTML ke file jpeg dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Mulai proses konversi
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, String) {#convertmhtml_19}

Konversi sumber MHTML yang disajikan melalui aliran masukan ke gambar. Hasilnya adalah file gambar yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran data masukan konversi MHTML. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Konverter MHTML

File dengan ekstensi [MHTML](https://docs.fileformat.com/web/mhtml/) merupakan format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. Format ini dikenal sebagai format arsip karena menyimpan kode HTML web dan sumber daya terkait dalam satu file. Sumber daya ini mencakup apa saja yang terhubung ke halaman web seperti gambar, applet, animasi, file audio, dan sebagainya. File MHTML dapat dibuka dalam berbagai aplikasi seperti Internet Explorer dan Microsoft Word. Spesifikasi sebenarnya dari format ini dijelaskan secara detail oleh [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Rujuk ke artikel, di mana Anda menemukan informasi tentang cara mengonversi MHTML ke gambar dalam berbagai format menggunakan metode ConvertMHTML() dari kelas Converter serta cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke Gambar

Kelas Converter menawarkan beberapa konversi khusus MHTML ke gambar. Format yang didukung adalah [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/), dan [TIFF](https://docs.fileformat.com/image/tiff/). Untuk mengonversi MHTML ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau [`Url`](../../../com.aspose.html/url/) remote sebagai sumber konversi. Anda juga dapat menggunakan stream standar atau khusus sebagai sumber. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Format gambar default adalah PNG. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online gratis yang mengonversi MHTML ke file jpeg dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, ImageSaveOptions, String) {#convertmhtml_35}

Konversi sumber MHTML yang disajikan melalui jalur file lengkap. Hasilnya adalah file gambar yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber MHTML. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Konverter MHTML

File dengan ekstensi [MHTML](https://docs.fileformat.com/web/mhtml/) merupakan format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. Format ini dikenal sebagai format arsip karena menyimpan kode HTML web dan sumber daya terkait dalam satu file. Sumber daya ini mencakup apa saja yang terhubung ke halaman web seperti gambar, applet, animasi, file audio, dan sebagainya. File MHTML dapat dibuka dalam berbagai aplikasi seperti Internet Explorer dan Microsoft Word. Spesifikasi sebenarnya dari format ini dijelaskan secara detail oleh [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Rujuk ke artikel, di mana Anda menemukan informasi tentang cara mengonversi MHTML ke gambar dalam berbagai format menggunakan metode ConvertMHTML() dari kelas Converter serta cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke Gambar

Kelas Converter menawarkan beberapa konversi khusus MHTML ke gambar. Format yang didukung adalah [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/), dan [TIFF](https://docs.fileformat.com/image/tiff/). Untuk mengonversi MHTML ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau [`Url`](../../../com.aspose.html/url/) remote sebagai sumber konversi. Anda juga dapat menggunakan stream standar atau khusus sebagai sumber. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Format gambar default adalah PNG. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online gratis yang mengonversi MHTML ke file jpeg dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, ImageSaveOptions, String) {#convertmhtml_3}

Konversi sumber MHTML yang disajikan oleh URL. Hasilnya adalah file gambar yang dibentuk oleh jalur file output.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL dokumen sumber MHTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| outputPath | String | Jalur lengkap file gambar sebagai hasil konversi output. |

## Catatan

Konverter MHTML

File dengan ekstensi [MHTML](https://docs.fileformat.com/web/mhtml/) merupakan format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. Format ini dikenal sebagai format arsip karena menyimpan kode HTML web dan sumber daya terkait dalam satu file. Sumber daya ini mencakup apa saja yang terhubung ke halaman web seperti gambar, applet, animasi, file audio, dan sebagainya. File MHTML dapat dibuka dalam berbagai aplikasi seperti Internet Explorer dan Microsoft Word. Spesifikasi sebenarnya dari format ini dijelaskan secara detail oleh [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Rujuk ke artikel, di mana Anda menemukan informasi tentang cara mengonversi MHTML ke gambar dalam berbagai format menggunakan metode ConvertMHTML() dari kelas Converter serta cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke Gambar

Kelas Converter menawarkan beberapa konversi khusus MHTML ke gambar. Format yang didukung adalah [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/), dan [TIFF](https://docs.fileformat.com/image/tiff/). Untuk mengonversi MHTML ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau [`Url`](../../../com.aspose.html/url/) remote sebagai sumber konversi. Anda juga dapat menggunakan stream standar atau khusus sebagai sumber. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Format gambar default adalah PNG. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online gratis yang mengonversi MHTML ke file jpeg dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_26}

Konversi sumber MHTML yang disajikan melalui aliran masukan. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran data masukan konversi MHTML. |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter MHTML

File dengan ekstensi [MHTML](https://docs.fileformat.com/web/mhtml/) merupakan format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. Format ini dikenal sebagai format arsip karena menyimpan kode HTML web dan sumber daya terkait dalam satu file. Sumber daya ini mencakup apa saja yang terhubung ke halaman web seperti gambar, applet, animasi, file audio, dan sebagainya. File MHTML dapat dibuka dalam berbagai aplikasi seperti Internet Explorer dan Microsoft Word. Spesifikasi sebenarnya dari format ini dijelaskan secara detail oleh [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Rujuk ke artikel, di mana Anda menemukan informasi tentang cara mengonversi MHTML ke gambar dalam berbagai format menggunakan metode ConvertMHTML() dari kelas Converter serta cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke Gambar

Kelas Converter menawarkan beberapa konversi khusus MHTML ke gambar. Format yang didukung adalah [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/), dan [TIFF](https://docs.fileformat.com/image/tiff/). Untuk mengonversi MHTML ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau [`Url`](../../../com.aspose.html/url/) remote sebagai sumber konversi. Anda juga dapat menggunakan stream standar atau khusus sebagai sumber. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Format gambar default adalah PNG. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online gratis yang mengonversi MHTML ke file jpeg dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions();

      // Mulai proses konversi
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_42}

Konversi sumber MHTML yang disajikan dengan jalur file lengkap ke gambar. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber MHTML. |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Diketahui (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kustom. |

## Catatan

Konverter MHTML

File dengan ekstensi [MHTML](https://docs.fileformat.com/web/mhtml/) merupakan format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. Format ini dikenal sebagai format arsip karena menyimpan kode HTML web dan sumber daya terkait dalam satu file. Sumber daya ini mencakup apa saja yang terhubung ke halaman web seperti gambar, applet, animasi, file audio, dan sebagainya. File MHTML dapat dibuka dalam berbagai aplikasi seperti Internet Explorer dan Microsoft Word. Spesifikasi sebenarnya dari format ini dijelaskan secara detail oleh [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Rujuk ke artikel, di mana Anda menemukan informasi tentang cara mengonversi MHTML ke gambar dalam berbagai format menggunakan metode ConvertMHTML() dari kelas Converter serta cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke Gambar

Kelas Converter menawarkan beberapa konversi khusus MHTML ke gambar. Format yang didukung adalah [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/), dan [TIFF](https://docs.fileformat.com/image/tiff/). Untuk mengonversi MHTML ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau [`Url`](../../../com.aspose.html/url/) remote sebagai sumber konversi. Anda juga dapat menggunakan stream standar atau khusus sebagai sumber. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Format gambar default adalah PNG. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online gratis yang mengonversi MHTML ke file jpeg dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_10}

Konversi sumber MHTML yang disajikan melalui URL. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL dokumen sumber MHTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Diketahui (lihat [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) atau implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) kustom. |

## Catatan

Konverter MHTML

File dengan ekstensi [MHTML](https://docs.fileformat.com/web/mhtml/) merupakan format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. Format ini dikenal sebagai format arsip karena menyimpan kode HTML web dan sumber daya terkait dalam satu file. Sumber daya ini mencakup apa saja yang terhubung ke halaman web seperti gambar, applet, animasi, file audio, dan sebagainya. File MHTML dapat dibuka dalam berbagai aplikasi seperti Internet Explorer dan Microsoft Word. Spesifikasi sebenarnya dari format ini dijelaskan secara detail oleh [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Rujuk ke artikel, di mana Anda menemukan informasi tentang cara mengonversi MHTML ke gambar dalam berbagai format menggunakan metode ConvertMHTML() dari kelas Converter serta cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke Gambar

Kelas Converter menawarkan beberapa konversi khusus MHTML ke gambar. Format yang didukung adalah [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/), dan [TIFF](https://docs.fileformat.com/image/tiff/). Untuk mengonversi MHTML ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau [`Url`](../../../com.aspose.html/url/) remote sebagai sumber konversi. Anda juga dapat menggunakan stream standar atau khusus sebagai sumber. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Format gambar default adalah PNG. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online gratis yang mengonversi MHTML ke file jpeg dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi
      Converter.ConvertMHTML(sourceUrl, options, sp);
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

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_18}

Konversi sumber MHTML yang disajikan melalui aliran masukan. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran data masukan konversi MHTML. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter MHTML

File dengan ekstensi [MHTML](https://docs.fileformat.com/web/mhtml/) merupakan format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. Format ini dikenal sebagai format arsip karena menyimpan kode HTML web dan sumber daya terkait dalam satu file. Sumber daya ini mencakup apa saja yang terhubung ke halaman web seperti gambar, applet, animasi, file audio, dan sebagainya. File MHTML dapat dibuka dalam berbagai aplikasi seperti Internet Explorer dan Microsoft Word. Spesifikasi sebenarnya dari format ini dijelaskan secara detail oleh [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Rujuk ke artikel, di mana Anda menemukan informasi tentang cara mengonversi MHTML ke gambar dalam berbagai format menggunakan metode ConvertMHTML() dari kelas Converter serta cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke Gambar

Kelas Converter menawarkan beberapa konversi khusus MHTML ke gambar. Format yang didukung adalah [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/), dan [TIFF](https://docs.fileformat.com/image/tiff/). Untuk mengonversi MHTML ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau [`Url`](../../../com.aspose.html/url/) remote sebagai sumber konversi. Anda juga dapat menggunakan stream standar atau khusus sebagai sumber. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Format gambar default adalah PNG. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online gratis yang mengonversi MHTML ke file jpeg dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions();

      // Mulai proses konversi
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_34}

Konversi sumber MHTML yang disajikan dengan jalur file lengkap ke gambar. Hasilnya adalah data output yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber MHTML. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Implementasi dari [` interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan stream output. |

## Catatan

Konverter MHTML

File dengan ekstensi [MHTML](https://docs.fileformat.com/web/mhtml/) merupakan format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. Format ini dikenal sebagai format arsip karena menyimpan kode HTML web dan sumber daya terkait dalam satu file. Sumber daya ini mencakup apa saja yang terhubung ke halaman web seperti gambar, applet, animasi, file audio, dan sebagainya. File MHTML dapat dibuka dalam berbagai aplikasi seperti Internet Explorer dan Microsoft Word. Spesifikasi sebenarnya dari format ini dijelaskan secara detail oleh [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Rujuk ke artikel, di mana Anda menemukan informasi tentang cara mengonversi MHTML ke gambar dalam berbagai format menggunakan metode ConvertMHTML() dari kelas Converter serta cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke Gambar

Kelas Converter menawarkan beberapa konversi khusus MHTML ke gambar. Format yang didukung adalah [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/), dan [TIFF](https://docs.fileformat.com/image/tiff/). Untuk mengonversi MHTML ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau [`Url`](../../../com.aspose.html/url/) remote sebagai sumber konversi. Anda juga dapat menggunakan stream standar atau khusus sebagai sumber. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Format gambar default adalah PNG. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online gratis yang mengonversi MHTML ke file jpeg dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions();

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_2}

Konversi sumber MHTML yang disajikan melalui URL. Hasilnya adalah data keluaran yang dibentuk oleh implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceUrl | Url | URL dokumen sumber MHTML - menyediakan representasi objek dari pengidentifikasi universal (URL). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| options | ImageSaveOptions | Penggunaan objek [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) memungkinkan Anda menyesuaikan proses rendering. Anda dapat menentukan [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), dll. |
| provider | ICreateStreamProvider | Implementasi dari [`interface`](../../../com.aspose.html.io/icreatestreamprovider/), yang akan digunakan untuk mendapatkan aliran output. |

## Catatan

Konverter MHTML

File dengan ekstensi [MHTML](https://docs.fileformat.com/web/mhtml/) merupakan format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. Format ini dikenal sebagai format arsip karena menyimpan kode HTML web dan sumber daya terkait dalam satu file. Sumber daya ini mencakup apa saja yang terhubung ke halaman web seperti gambar, applet, animasi, file audio, dan sebagainya. File MHTML dapat dibuka dalam berbagai aplikasi seperti Internet Explorer dan Microsoft Word. Spesifikasi sebenarnya dari format ini dijelaskan secara detail oleh [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Rujuk ke artikel, di mana Anda menemukan informasi tentang cara mengonversi MHTML ke gambar dalam berbagai format menggunakan metode ConvertMHTML() dari kelas Converter serta cara menerapkan parameter [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dan [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Konversi MHTML ke Gambar

Kelas Converter menawarkan beberapa konversi khusus MHTML ke gambar. Format yang didukung adalah [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/), dan [TIFF](https://docs.fileformat.com/image/tiff/). Untuk mengonversi MHTML ke gambar, Anda harus mengikuti salah satu skenario sederhana yang terdiri dari beberapa langkah:

Sumber konversi. Deteksi file MHTML (.mht) lokal yang ada atau [`Url`](../../../com.aspose.html/url/) remote sebagai sumber konversi. Anda juga dapat menggunakan stream standar atau khusus sebagai sumber. Hasil konversi. Tentukan jalur file output hasil atau gunakan implementasi antarmuka [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) yang dikenal atau khusus sebagai buffer data output. Buat objek baru [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) dengan pengaturan spesifik atau default. Format gambar default adalah PNG. Anda juga dapat menambahkan konfigurasi sebagai parameter opsi.Gunakan metode ConvertMHTML() dari kelas Converter untuk menyimpan MHTML sebagai hasil gambar dengan tiga atau lebih parameter tergantung pada skenario pengguna.Online MHTML converter

Aspose.HTML menawarkan [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) online gratis yang mengonversi MHTML ke file jpeg dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Formulir jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result");

      // Tentukan objek ImageSaveOptions default
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // Gunakan salah satu implementasi ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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
