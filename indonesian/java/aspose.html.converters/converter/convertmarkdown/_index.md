---
title: "Converter.ConvertMarkdown"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Converter. Mengonversi sumber markdown MD yang disajikan melalui aliran masukan ke html. Hasilnya adalah HTMLDocument yang dapat disimpan melalui jalur file output."
type: docs

url: /id/java/com.aspose.html.converters/converter/convertmarkdown/
---
## ConvertMarkdown(Stream, String) {#convertmarkdown}

Mengonversi sumber MD (markdown) yang disajikan melalui aliran masukan ke html. Hasilnya adalah [`HTMLDocument`](../../../com.aspose.html/htmldocument/) yang dapat disimpan melalui jalur file output.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran data masukan konversi MD (Markdown). |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |

### Nilai Kembali

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) baru yang dibentuk sebagai hasil konversi yang dapat disimpan melalui jalur file output.

## Catatan

Konverter Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Langkah konversi

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file MD lokal yang ada atau buat aliran data masukan sebagai sumber konversi. Hasil konversi. Anda dapat memperoleh langsung [`HTMLDocument`](../../../com.aspose.html/htmldocument/) atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Gunakan metode ConvertMarkdown() dari kelas Converter untuk menyimpan MD sebagai hasil html. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Konverter MD daring.

Anda mungkin juga tertarik pada [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) daring gratis yang mengonversi MD ke HTML dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik! Anda juga dapat memeriksa konverter MD daring lainnya: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) dan temukan [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) yang sesuai.

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.html");
       
      // Buka file sumber sebagai aliran
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Mulai proses konversi
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty);
         
        // Simpan hasil konversi
        document.Save(resultPath);
      }





*InputFolder - user source folder path.



```

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration) {#convertmarkdown_1}

Mengonversi sumber MD (markdown) yang disajikan melalui aliran masukan ke html. Hasilnya adalah [`HTMLDocument`](../../../com.aspose.html/htmldocument/) yang dapat disimpan melalui jalur file output.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri, 
    Configuration configuration)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran data masukan konversi MD (Markdown). |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |

### Nilai Kembali

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) baru yang dibentuk sebagai hasil konversi yang dapat disimpan melalui jalur file output.

## Catatan

Konverter Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Langkah konversi

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file MD lokal yang ada atau buat aliran data masukan sebagai sumber konversi. Hasil konversi. Anda dapat memperoleh langsung [`HTMLDocument`](../../../com.aspose.html/htmldocument/) atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Gunakan metode ConvertMarkdown() dari kelas Converter untuk menyimpan MD sebagai hasil html. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Konverter MD daring.

Anda mungkin juga tertarik pada [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) daring gratis yang mengonversi MD ke HTML dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik! Anda juga dapat memeriksa konverter MD daring lainnya: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) dan temukan [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) yang sesuai.

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Buka file sumber sebagai aliran
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Mulai proses konversi dengan konfigurasi default
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration());

        // Simpan hasil konversi
        document.Save(resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, String) {#convertmarkdown_5}

Konversi sumber MD (markdown) yang disajikan melalui aliran masukan ke html. Hasilnya adalah file html yang dibentuk oleh jalur file output.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran data masukan konversi MD (Markdown). |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| outputPath | String | Jalur file html lengkap sebagai hasil konversi output. |

## Catatan

Konverter Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Langkah konversi

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file MD lokal yang ada atau buat aliran data masukan sebagai sumber konversi. Hasil konversi. Anda dapat memperoleh langsung [`HTMLDocument`](../../../com.aspose.html/htmldocument/) atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Gunakan metode ConvertMarkdown() dari kelas Converter untuk menyimpan MD sebagai hasil html. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Konverter MD daring.

Anda mungkin juga tertarik pada [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) daring gratis yang mengonversi MD ke HTML dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik! Anda juga dapat memeriksa konverter MD daring lainnya: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) dan temukan [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) yang sesuai.

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Buka file sumber sebagai aliran
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Mulai proses konversi
        Converter.ConvertMarkdown(sourceStream, String.Empty, resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### Lihat Juga

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration, String) {#convertmarkdown_4}

Konversi sumber MD (markdown) yang disajikan melalui aliran masukan ke html. Hasilnya adalah file html yang dibentuk oleh jalur file output.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, Configuration configuration, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran data masukan konversi MD (Markdown). |
| baseUri | String | URI dasar dokumen. Ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| outputPath | String | Jalur file html lengkap sebagai hasil konversi output. |

## Catatan

Konverter Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Langkah konversi

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file MD lokal yang ada atau buat aliran data masukan sebagai sumber konversi. Hasil konversi. Anda dapat memperoleh langsung [`HTMLDocument`](../../../com.aspose.html/htmldocument/) atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Gunakan metode ConvertMarkdown() dari kelas Converter untuk menyimpan MD sebagai hasil html. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Konverter MD daring.

Anda mungkin juga tertarik pada [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) daring gratis yang mengonversi MD ke HTML dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik! Anda juga dapat memeriksa konverter MD daring lainnya: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) dan temukan [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) yang sesuai.

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Buka file sumber sebagai aliran
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // Mulai proses konversi dengan konfigurasi default
        Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration(), resultPath);
      }
```

*InputFolder - user source folder path.

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String) {#convertmarkdown_2}

Mengonversi sumber MD (markdown) yang disajikan melalui jalur file lengkap ke html. Hasilnya adalah [`HTMLDocument`](../../../com.aspose.html/htmldocument/) yang dapat disimpan melalui jalur file output.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber MD (Markdown). |

### Nilai Kembali

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) baru yang dibentuk sebagai hasil konversi yang dapat disimpan melalui jalur file output.

## Catatan

Konverter Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Langkah konversi

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file MD lokal yang ada atau buat aliran data masukan sebagai sumber konversi. Hasil konversi. Anda dapat memperoleh langsung [`HTMLDocument`](../../../com.aspose.html/htmldocument/) atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Gunakan metode ConvertMarkdown() dari kelas Converter untuk menyimpan MD sebagai hasil html. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Konverter MD daring.

Anda mungkin juga tertarik pada [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) daring gratis yang mengonversi MD ke HTML dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik! Anda juga dapat memeriksa konverter MD daring lainnya: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) dan temukan [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) yang sesuai.

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Mulai proses konversi
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath))
      {
        // Simpan hasil konversi sebagai file lokal
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration) {#convertmarkdown_3}

Mengonversi sumber MD (markdown) yang disajikan melalui jalur file lengkap ke html. Hasilnya adalah [`HTMLDocument`](../../../com.aspose.html/htmldocument/) yang dapat disimpan melalui jalur file output.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath, Configuration configuration)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur file lengkap sumber MD (Markdown). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |

### Nilai Kembali

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) baru yang dibentuk sebagai hasil konversi yang dapat disimpan melalui jalur file output.

## Catatan

Konverter Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Langkah konversi

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file MD lokal yang ada atau buat aliran data masukan sebagai sumber konversi. Hasil konversi. Anda dapat memperoleh langsung [`HTMLDocument`](../../../com.aspose.html/htmldocument/) atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Gunakan metode ConvertMarkdown() dari kelas Converter untuk menyimpan MD sebagai hasil html. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Konverter MD daring.

Anda mungkin juga tertarik pada [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) daring gratis yang mengonversi MD ke HTML dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik! Anda juga dapat memeriksa konverter MD daring lainnya: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) dan temukan [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) yang sesuai.

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Mulai proses konversi dengan konfigurasi default
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath, new Configuration()))
      {
        // Simpan hasil konversi sebagai file lokal
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, String) {#convertmarkdown_7}

Konversi sumber MD (markdown) yang disajikan melalui jalur file lengkap ke html. Hasilnya adalah file html yang dibentuk oleh jalur file output.

```java
public static void ConvertMarkdown(String sourcePath, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur ke file Markdown sumber. Itu akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| outputPath | String | Jalur file html lengkap sebagai hasil konversi output. |

## Catatan

Konverter Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Langkah konversi

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file MD lokal yang ada atau buat aliran data masukan sebagai sumber konversi. Hasil konversi. Anda dapat memperoleh langsung [`HTMLDocument`](../../../com.aspose.html/htmldocument/) atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Gunakan metode ConvertMarkdown() dari kelas Converter untuk menyimpan MD sebagai hasil html. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Konverter MD daring.

Anda mungkin juga tertarik pada [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) daring gratis yang mengonversi MD ke HTML dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik! Anda juga dapat memeriksa konverter MD daring lainnya: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) dan temukan [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) yang sesuai.

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Mulai proses konversi
      Converter.ConvertMarkdown(sourcePath, resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Lihat Juga

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration, String) {#convertmarkdown_6}

Konversi sumber MD (markdown) yang disajikan melalui jalur file lengkap ke html. Hasilnya adalah file html yang dibentuk oleh jalur file output.

```java
public static void ConvertMarkdown(String sourcePath, Configuration configuration, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Jalur ke file Markdown sumber. Itu akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| outputPath | String | Jalur file html lengkap sebagai hasil konversi output. |

## Catatan

Konverter Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

Langkah konversi

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

Sumber konversi. Deteksi file MD lokal yang ada atau buat aliran data masukan sebagai sumber konversi. Hasil konversi. Anda dapat memperoleh langsung [`HTMLDocument`](../../../com.aspose.html/htmldocument/) atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Gunakan metode ConvertMarkdown() dari kelas Converter untuk menyimpan MD sebagai hasil html. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Konverter MD daring.

Anda mungkin juga tertarik pada [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) daring gratis yang mengonversi MD ke HTML dengan kualitas tinggi, mudah, dan cepat. Cukup unggah, konversi file Anda, dan dapatkan hasil dalam beberapa detik! Anda juga dapat memeriksa konverter MD daring lainnya: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf), [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx), [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) dan temukan [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) yang sesuai.

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertMarkdown(sourcePath, new Configuration(), resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
