---
title: "Converter.ConvertTemplate"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Converter. Menggabungkan sumber templat yang disajikan oleh HTMLDocument dengan data templat XML JSON. Hasilnya adalah file html yang dibentuk oleh jalur file output."
type: docs

url: /id/java/com.aspose.html.converters/converter/converttemplate/
---
## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions, String) {#converttemplate_7}

Gabungkan sumber templat yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/) dengan data templat (XML, JSON). Hasilnya adalah file html yang dibentuk oleh jalur file output.

```java
public static void ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| template | HTMLDocument | Menggabungkan kerangka sumber yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| data | TemplateData | Data templat untuk penggabungan - substitusi (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objek instance. Ini digunakan untuk menentukan apakah nama templat dan item data cocok, terlepas dari huruf besar/kecil atau tidak (opsi). |
| outputPath | String | Jalur file html lengkap sebagai hasil konversi output. |

## Catatan

Penggabung Templat

Ide penggabungan templat adalah membuat dokumen HTML berdasarkan templat HTML dan mengisinya dari sumber data. Aspose.HTML menyediakan sintaks ekspresi inline untuk bekerja dengan templat dan berbagai jenis sumber data, seperti XML dan JSON. Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dimana Anda dapat menemukan informasi lebih lanjut tentang penggabungan templat dan penggunaan metode ConvertTemplate().

Langkah Konversi (Penggabungan)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sumber templat. Tentukan sumber templat HTML melalui file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objek instance, atau bahkan melalui konten inline. Hasil konversi. Anda dapat memperoleh langsung HTMLDocument yang dihasilkan atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Buat instance dari [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gunakan metode ConvertTemplate() dari kelas Converter untuk menggabungkan templat dengan data. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Bentuk jalur file sumber html kerangka
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Bentuk jalur file data templat xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");
      
      // Tentukan instance objek TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Tentukan objek TemplateLoadOptions default
      var options = new TemplateLoadOptions();

      // Bentuk dokumen HTML sebagai sumber konversi
      var document = new HTMLDocument(sourcePath, new Configuration());

      // Mulai proses konversi
      Converter.ConvertTemplate(document, templateData, options, resultPath);

      // Bersihkan sumber daya
      document.Dispose();





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions, String) {#converttemplate_9}

Gabungkan sumber HTML templat yang disajikan oleh [`URL`](../../../com.aspose.html/url/) dengan data templat (XML, JSON). Hasilnya adalah file html yang dibentuk oleh jalur file output.

```java
public static void ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options, 
    String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Menggabungkan kerangka sumber HTML yang disajikan oleh [`URL`](../../../com.aspose.html/url/). |
| data | TemplateData | Data templat untuk penggabungan - substitusi (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objek instance. Ini digunakan untuk menentukan apakah nama templat dan item data cocok, terlepas dari huruf besar/kecil atau tidak (opsi). |
| outputPath | String | Jalur file html lengkap sebagai hasil konversi output. |

## Catatan

Penggabung Templat

Ide penggabungan templat adalah membuat dokumen HTML berdasarkan templat HTML dan mengisinya dari sumber data. Aspose.HTML menyediakan sintaks ekspresi inline untuk bekerja dengan templat dan berbagai jenis sumber data, seperti XML dan JSON. Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dimana Anda dapat menemukan informasi lebih lanjut tentang penggabungan templat dan penggunaan metode ConvertTemplate().

Langkah Konversi (Penggabungan)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sumber templat. Tentukan sumber templat HTML melalui file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objek instance, atau bahkan melalui konten inline. Hasil konversi. Anda dapat memperoleh langsung HTMLDocument yang dihasilkan atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Buat instance dari [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gunakan metode ConvertTemplate() dari kelas Converter untuk menggabungkan templat dengan data. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Bentuk URL sumber html kerangka
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Bentuk jalur file data templat xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Tentukan instance objek TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Tentukan objek TemplateLoadOptions default
      var options = new TemplateLoadOptions();

      // Mulai proses konversi
      Converter.ConvertTemplate(sourceUrl, templateData, options, resultPath);





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_8}

Gabungkan sumber HTML templat yang disajikan oleh [`URL`](../../../com.aspose.html/url/) dengan data templat (XML, JSON). Hasilnya adalah file html yang dibentuk oleh jalur file output.

```java
public static void ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Menggabungkan kerangka sumber HTML yang disajikan oleh [`URL`](../../../com.aspose.html/url/). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| data | TemplateData | Data templat untuk penggabungan - substitusi (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objek instance. Ini digunakan untuk menentukan apakah nama templat dan item data cocok, terlepas dari huruf besar/kecil atau tidak (opsi). |
| outputPath | String | Jalur file html lengkap sebagai hasil konversi output. |

## Catatan

Penggabung Templat

Ide penggabungan templat adalah membuat dokumen HTML berdasarkan templat HTML dan mengisinya dari sumber data. Aspose.HTML menyediakan sintaks ekspresi inline untuk bekerja dengan templat dan berbagai jenis sumber data, seperti XML dan JSON. Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dimana Anda dapat menemukan informasi lebih lanjut tentang penggabungan templat dan penggunaan metode ConvertTemplate().

Langkah Konversi (Penggabungan)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sumber templat. Tentukan sumber templat HTML melalui file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objek instance, atau bahkan melalui konten inline. Hasil konversi. Anda dapat memperoleh langsung HTMLDocument yang dihasilkan atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Buat instance dari [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gunakan metode ConvertTemplate() dari kelas Converter untuk menggabungkan templat dengan data. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Bentuk URL sumber html kerangka
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Bentuk jalur file data templat xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Tentukan instance objek TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Tentukan objek TemplateLoadOptions default
      var options = new TemplateLoadOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions, String) {#converttemplate_11}

Gabungkan sumber HTML templat yang disajikan melalui jalur file lengkap dengan data templat (XML, JSON). Hasilnya adalah file html yang dibuat berdasarkan jalur file output.

```java
public static void ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Menggabungkan kerangka sumber HTML yang disajikan oleh jalur file lengkap. |
| data | TemplateData | Data templat untuk penggabungan - substitusi (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objek instance. Ini digunakan untuk menentukan apakah nama templat dan item data cocok, terlepas dari huruf besar/kecil atau tidak (opsi). |
| outputPath | String | Jalur file html lengkap sebagai hasil konversi output. |

## Catatan

Penggabung Templat

Ide penggabungan templat adalah membuat dokumen HTML berdasarkan templat HTML dan mengisinya dari sumber data. Aspose.HTML menyediakan sintaks ekspresi inline untuk bekerja dengan templat dan berbagai jenis sumber data, seperti XML dan JSON. Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dimana Anda dapat menemukan informasi lebih lanjut tentang penggabungan templat dan penggunaan metode ConvertTemplate().

Langkah Konversi (Penggabungan)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sumber templat. Tentukan sumber templat HTML melalui file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objek instance, atau bahkan melalui konten inline. Hasil konversi. Anda dapat memperoleh langsung HTMLDocument yang dihasilkan atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Buat instance dari [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gunakan metode ConvertTemplate() dari kelas Converter untuk menggabungkan templat dengan data. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Bentuk jalur file sumber html kerangka
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Bentuk jalur file data templat xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Tentukan instance objek TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Tentukan objek TemplateLoadOptions default
      var options = new TemplateLoadOptions();

      // Mulai proses konversi
      Converter.ConvertTemplate(sourcePath, templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Lihat Juga

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_10}

Gabungkan sumber HTML templat yang disajikan melalui jalur file lengkap dengan data templat (XML, JSON). Hasilnya adalah file html yang dibuat berdasarkan jalur file output.

```java
public static void ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Menggabungkan kerangka sumber HTML yang disajikan oleh jalur file lengkap. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| data | TemplateData | Data templat untuk penggabungan - substitusi (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objek instance. Ini digunakan untuk menentukan apakah nama templat dan item data cocok, terlepas dari huruf besar/kecil atau tidak (opsi). |
| outputPath | String | Jalur file html lengkap sebagai hasil konversi output. |

## Catatan

Penggabung Templat

Ide penggabungan templat adalah membuat dokumen HTML berdasarkan templat HTML dan mengisinya dari sumber data. Aspose.HTML menyediakan sintaks ekspresi inline untuk bekerja dengan templat dan berbagai jenis sumber data, seperti XML dan JSON. Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dimana Anda dapat menemukan informasi lebih lanjut tentang penggabungan templat dan penggunaan metode ConvertTemplate().

Langkah Konversi (Penggabungan)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sumber templat. Tentukan sumber templat HTML melalui file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objek instance, atau bahkan melalui konten inline. Hasil konversi. Anda dapat memperoleh langsung HTMLDocument yang dihasilkan atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Buat instance dari [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gunakan metode ConvertTemplate() dari kelas Converter untuk menggabungkan templat dengan data. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Bentuk jalur file sumber html kerangka
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Bentuk jalur file data templat xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Tentukan instance objek TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Tentukan objek TemplateLoadOptions default
      var options = new TemplateLoadOptions();

      // Mulai proses konversi dengan konfigurasi default
      Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions, String) {#converttemplate_13}

Gabungkan sumber HTML templat yang disajikan melalui konten inline dengan data templat (XML, JSON). Hasilnya adalah file html yang dibuat berdasarkan jalur file output.

```java
public static void ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | Menggabungkan kerangka sumber HTML yang disajikan oleh konten String inline. |
| baseUrl | String | URI dasar templat html. Itu akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| data | TemplateData | Data templat untuk penggabungan - substitusi (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objek instance. Ini digunakan untuk menentukan apakah nama templat dan item data cocok, terlepas dari huruf besar/kecil atau tidak (opsi). |
| outputPath | String | Jalur file html lengkap sebagai hasil konversi output. |

## Catatan

Penggabung Templat

Ide penggabungan templat adalah membuat dokumen HTML berdasarkan templat HTML dan mengisinya dari sumber data. Aspose.HTML menyediakan sintaks ekspresi inline untuk bekerja dengan templat dan berbagai jenis sumber data, seperti XML dan JSON. Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dimana Anda dapat menemukan informasi lebih lanjut tentang penggabungan templat dan penggunaan metode ConvertTemplate().

Langkah Konversi (Penggabungan)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sumber templat. Tentukan sumber templat HTML melalui file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objek instance, atau bahkan melalui konten inline. Hasil konversi. Anda dapat memperoleh langsung HTMLDocument yang dihasilkan atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Buat instance dari [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gunakan metode ConvertTemplate() dari kelas Converter untuk menggabungkan templat dengan data. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	  // Bentuk konten sumber inline sebagai templat
      String templateContent =
        "<html>" + 
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";
       
      // Bentuk jalur file data templat xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Tentukan instance objek TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Bentuk output sebagai hasil penggabungan
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Tentukan objek TemplateLoadOptions default
      var options = new TemplateLoadOptions();
	  
      // Mulai proses konversi
      Converter.ConvertTemplate(templateContent, String.Empty, templateData, options, resultFilePath);

*TemplateFolder - user template data folder.
*OutputFolder - user output file path.

Below is sample data file to merge with source

<?xml version="1.0" encoding="utf-8" ?>
<Data>
	<Person>
	<Title>Title 1</Title>
	<Name>John</Name>
	<Surname>Smith</Surname>
	<Address>
		<Number>200</Number>
		<Street>Austin rd.</Street>
		<City>Dallas</City>
	</Address>
	</Person>
	<Person>
	<Title>Title 2</Title>
	<Name>Mike</Name>
	<Surname>Milbert</Surname>
	<Address>
		<Number>126</Number>
		<Street>First Avenue</Street>
		<City>Chicago</City>
	</Address>
	</Person>
</Data>
```

### Lihat Juga

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_12}

Gabungkan sumber HTML templat yang disajikan melalui konten inline dengan data templat (XML, JSON). Hasilnya adalah file html yang dibuat berdasarkan jalur file output.

```java
public static void ConvertTemplate(String content, String baseUrl, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | Menggabungkan kerangka sumber HTML yang disajikan oleh konten String inline. |
| baseUrl | String | URI dasar templat html. Itu akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| data | TemplateData | Data templat untuk penggabungan - substitusi (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objek instance. Ini digunakan untuk menentukan apakah nama templat dan item data cocok, terlepas dari huruf besar/kecil atau tidak (opsi). |
| outputPath | String | Jalur file html lengkap sebagai hasil konversi output. |

## Catatan

Penggabung Templat

Ide penggabungan templat adalah membuat dokumen HTML berdasarkan templat HTML dan mengisinya dari sumber data. Aspose.HTML menyediakan sintaks ekspresi inline untuk bekerja dengan templat dan berbagai jenis sumber data, seperti XML dan JSON. Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dimana Anda dapat menemukan informasi lebih lanjut tentang penggabungan templat dan penggunaan metode ConvertTemplate().

Langkah Konversi (Penggabungan)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sumber templat. Tentukan sumber templat HTML melalui file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objek instance, atau bahkan melalui konten inline. Hasil konversi. Anda dapat memperoleh langsung HTMLDocument yang dihasilkan atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Buat instance dari [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gunakan metode ConvertTemplate() dari kelas Converter untuk menggabungkan templat dengan data. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
   // Bentuk konten sumber inline sebagai templat
   String templateContent =
    "<html>" + 
    "<body>" +
    "<div data_merge=\"{{#foreach Person}}\">" +
    "<p>{{Title}}</p>" +
    "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
    "<p>Address:</p>" +
    "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
    "</div>" +
    "</body></html>";
    
   // Bentuk jalur file data templat xml (json)
   var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

   // Tentukan instance objek TemplateData
   var templateData = new TemplateData(templateDataPath);

   // Bentuk output sebagai hasil penggabungan
   var resultFilePath = Path.Combine(OutputFolder, "result.html");

   // Tentukan instance objek configuration
   var configuration = new Configuration();

   // Tentukan objek TemplateLoadOptions default
   var options = new TemplateLoadOptions();

   // Mulai proses konversi dengan konfigurasi default
   Converter.ConvertTemplate(templateContent, String.Empty,
        configuration, templateData, options, resultFilePath);
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

Berikut adalah file data untuk digabungkan dengan sumber sebagai templat

```java
<?xml version="1.0" encoding="utf-8" ?>
<Data>
	<Person>
	<Title>Title 1</Title>
	<Name>John</Name>
	<Surname>Smith</Surname>
	<Address>
		<Number>200</Number>
		<Street>Austin rd.</Street>
		<City>Dallas</City>
	</Address>
	</Person>
	<Person>
	<Title>Title 2</Title>
	<Name>Mike</Name>
	<Surname>Milbert</Surname>
	<Address>
		<Number>126</Number>
		<Street>First Avenue</Street>
		<City>Chicago</City>
	</Address>
	</Person>
</Data>
```

### Lihat Juga

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions) {#converttemplate}

Gabungkan sumber templat yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/) dengan data templat (XML, JSON). Hasilnya adalah HTMLDocument baru yang dapat disimpan sebagai file.

```java
public static HTMLDocument ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| template | HTMLDocument | Menggabungkan kerangka sumber yang disajikan oleh [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| data | TemplateData | Data templat untuk penggabungan - substitusi (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objek instance. Ini digunakan untuk menentukan apakah nama templat dan item data cocok, terlepas dari huruf besar/kecil atau tidak (opsi). |

### Nilai Kembali

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) baru yang dibentuk sebagai hasil konversi yang dapat disimpan melalui jalur file output.

## Catatan

Penggabung Templat

Ide penggabungan templat adalah membuat dokumen HTML berdasarkan templat HTML dan mengisinya dari sumber data. Aspose.HTML menyediakan sintaks ekspresi inline untuk bekerja dengan templat dan berbagai jenis sumber data, seperti XML dan JSON. Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dimana Anda dapat menemukan informasi lebih lanjut tentang penggabungan templat dan penggunaan metode ConvertTemplate().

Langkah Konversi (Penggabungan)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sumber templat. Tentukan sumber templat HTML melalui file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objek instance, atau bahkan melalui konten inline. Hasil konversi. Anda dapat memperoleh langsung HTMLDocument yang dihasilkan atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Buat instance dari [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gunakan metode ConvertTemplate() dari kelas Converter untuk menggabungkan templat dengan data. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Bentuk jalur file sumber html kerangka
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Bentuk jalur file data templat xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Tentukan instance objek TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Tentukan objek TemplateLoadOptions default
      var options = new TemplateLoadOptions();
      
      // Bentuk dokumen HTML sebagai sumber konversi
      using (var template = new HTMLDocument(sourcePath, new Configuration()))
      {
        // Mulai proses konversi
        var document = Converter.ConvertTemplate(template, templateData, options);
         
        // Simpan hasil dengan sumber daya yang terhubung
        document.Save(new Url(resultPath));
      }





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions) {#converttemplate_2}

Gabungkan sumber HTML templat yang disajikan oleh [`URL`](../../../com.aspose.html/url/) dengan data templat (XML, JSON). Hasilnya adalah [`HTMLDocument`](../../../com.aspose.html/htmldocument/) baru yang dapat disimpan sebagai file.

```java
public static HTMLDocument ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Menggabungkan kerangka sumber HTML yang disajikan oleh [`URL`](../../../com.aspose.html/url/). |
| data | TemplateData | Data templat untuk penggabungan - substitusi (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objek instance. Ini digunakan untuk menentukan apakah nama templat dan item data cocok, terlepas dari huruf besar/kecil atau tidak (opsi). |

### Nilai Kembali

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) baru yang dibentuk sebagai hasil konversi yang dapat disimpan melalui jalur file output.

## Catatan

Penggabung Templat

Ide penggabungan templat adalah membuat dokumen HTML berdasarkan templat HTML dan mengisinya dari sumber data. Aspose.HTML menyediakan sintaks ekspresi inline untuk bekerja dengan templat dan berbagai jenis sumber data, seperti XML dan JSON. Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dimana Anda dapat menemukan informasi lebih lanjut tentang penggabungan templat dan penggunaan metode ConvertTemplate().

Langkah Konversi (Penggabungan)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sumber templat. Tentukan sumber templat HTML melalui file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objek instance, atau bahkan melalui konten inline. Hasil konversi. Anda dapat memperoleh langsung HTMLDocument yang dihasilkan atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Buat instance dari [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gunakan metode ConvertTemplate() dari kelas Converter untuk menggabungkan templat dengan data. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Bentuk Url menjadi file sumber html kerangka
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Bentuk jalur file data templat xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Tentukan instance objek TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Tentukan objek TemplateLoadOptions default
      var options = new TemplateLoadOptions();

      // Mulai proses konversi
      using (var document = Converter.ConvertTemplate(sourceUrl, templateData, options))
      {
        // Simpan hasil dengan sumber daya yang terhubung
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_1}

Gabungkan sumber HTML templat yang disajikan oleh [`URL`](../../../com.aspose.html/url/) dengan data templat (XML, JSON). Hasilnya adalah [`HTMLDocument`](../../../com.aspose.html/htmldocument/) baru yang dapat disimpan sebagai file.

```java
public static HTMLDocument ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | Menggabungkan kerangka sumber HTML yang disajikan oleh [`URL`](../../../com.aspose.html/url/). |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| data | TemplateData | Data templat untuk penggabungan - substitusi (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objek instance. Ini digunakan untuk menentukan apakah nama templat dan item data cocok, terlepas dari huruf besar/kecil atau tidak (opsi). |

### Nilai Kembali

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) baru yang dibentuk sebagai hasil konversi yang dapat disimpan melalui jalur file output.

## Catatan

Penggabung Templat

Ide penggabungan templat adalah membuat dokumen HTML berdasarkan templat HTML dan mengisinya dari sumber data. Aspose.HTML menyediakan sintaks ekspresi inline untuk bekerja dengan templat dan berbagai jenis sumber data, seperti XML dan JSON. Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dimana Anda dapat menemukan informasi lebih lanjut tentang penggabungan templat dan penggunaan metode ConvertTemplate().

Langkah Konversi (Penggabungan)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sumber templat. Tentukan sumber templat HTML melalui file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objek instance, atau bahkan melalui konten inline. Hasil konversi. Anda dapat memperoleh langsung HTMLDocument yang dihasilkan atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Buat instance dari [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gunakan metode ConvertTemplate() dari kelas Converter untuk menggabungkan templat dengan data. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Bentuk Url menjadi file sumber html kerangka
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // Bentuk jalur file data templat xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Tentukan instance objek TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Tentukan objek TemplateLoadOptions default
      var options = new TemplateLoadOptions();

      // Mulai proses konversi dengan konfigurasi default
      using (var document = Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options))
      {
        // Simpan hasil dengan sumber daya yang terhubung
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions) {#converttemplate_4}

Gabungkan sumber HTML templat yang disajikan oleh jalur file lengkap dengan data templat (XML, JSON). Hasilnya adalah [`HTMLDocument`](../../../com.aspose.html/htmldocument/) baru yang dapat disimpan sebagai file.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Menggabungkan kerangka sumber HTML yang disajikan oleh jalur file lengkap. |
| data | TemplateData | Data templat untuk penggabungan - substitusi (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objek instance. Ini digunakan untuk menentukan apakah nama templat dan item data cocok, terlepas dari huruf besar/kecil atau tidak (opsi). |

### Nilai Kembali

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) baru yang dibentuk sebagai hasil konversi yang dapat disimpan melalui jalur file output.

## Catatan

Penggabung Templat

Ide penggabungan templat adalah membuat dokumen HTML berdasarkan templat HTML dan mengisinya dari sumber data. Aspose.HTML menyediakan sintaks ekspresi inline untuk bekerja dengan templat dan berbagai jenis sumber data, seperti XML dan JSON. Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dimana Anda dapat menemukan informasi lebih lanjut tentang penggabungan templat dan penggunaan metode ConvertTemplate().

Langkah Konversi (Penggabungan)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sumber templat. Tentukan sumber templat HTML melalui file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objek instance, atau bahkan melalui konten inline. Hasil konversi. Anda dapat memperoleh langsung HTMLDocument yang dihasilkan atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Buat instance dari [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gunakan metode ConvertTemplate() dari kelas Converter untuk menggabungkan templat dengan data. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Bentuk jalur file sumber html kerangka
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Bentuk jalur file data templat xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Tentukan instance objek TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Tentukan objek TemplateLoadOptions default
      var options = new TemplateLoadOptions();

      // Mulai proses konversi
      using (var document = Converter.ConvertTemplate(sourcePath, templateData, options))
      {
        // Simpan hasil dengan sumber daya yang terhubung
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_3}

Gabungkan sumber HTML templat yang disajikan oleh jalur file lengkap dengan data templat (XML, JSON). Hasilnya adalah [`HTMLDocument`](../../../com.aspose.html/htmldocument/) baru yang dapat disimpan sebagai file.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourcePath | String | Menggabungkan kerangka sumber HTML yang disajikan oleh jalur file lengkap. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| data | TemplateData | Data templat untuk penggabungan - substitusi (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objek instance. Ini digunakan untuk menentukan apakah nama templat dan item data cocok, terlepas dari huruf besar/kecil atau tidak (opsi). |

### Nilai Kembali

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) baru yang dibentuk sebagai hasil konversi yang dapat disimpan melalui jalur file output.

## Catatan

Penggabung Templat

Ide penggabungan templat adalah membuat dokumen HTML berdasarkan templat HTML dan mengisinya dari sumber data. Aspose.HTML menyediakan sintaks ekspresi inline untuk bekerja dengan templat dan berbagai jenis sumber data, seperti XML dan JSON. Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dimana Anda dapat menemukan informasi lebih lanjut tentang penggabungan templat dan penggunaan metode ConvertTemplate().

Langkah Konversi (Penggabungan)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sumber templat. Tentukan sumber templat HTML melalui file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objek instance, atau bahkan melalui konten inline. Hasil konversi. Anda dapat memperoleh langsung HTMLDocument yang dihasilkan atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Buat instance dari [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gunakan metode ConvertTemplate() dari kelas Converter untuk menggabungkan templat dengan data. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Bentuk jalur file sumber html kerangka
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // Bentuk jalur file data templat xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Tentukan instance objek TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Form jalur file hasil
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // Tentukan objek TemplateLoadOptions default
      var options = new TemplateLoadOptions();

      // Mulai proses konversi dengan konfigurasi default
      using (var document = Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options))
      {
        // Simpan hasil dengan sumber daya yang terhubung
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions) {#converttemplate_6}

Gabungkan sumber HTML templat yang disajikan oleh konten inline dengan data templat (XML, JSON). Hasilnya adalah [`HTMLDocument`](../../../com.aspose.html/htmldocument/) baru yang dapat disimpan sebagai file.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | Menggabungkan kerangka sumber HTML yang disajikan oleh konten String inline. |
| baseUrl | String | URI dasar templat html. Itu akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| data | TemplateData | Data templat untuk penggabungan - substitusi (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objek instance. Ini digunakan untuk menentukan apakah nama templat dan item data cocok, terlepas dari huruf besar/kecil atau tidak (opsi). |

### Nilai Kembali

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) baru yang dibentuk sebagai hasil konversi yang dapat disimpan melalui jalur file output.

## Catatan

Penggabung Templat

Ide penggabungan templat adalah membuat dokumen HTML berdasarkan templat HTML dan mengisinya dari sumber data. Aspose.HTML menyediakan sintaks ekspresi inline untuk bekerja dengan templat dan berbagai jenis sumber data, seperti XML dan JSON. Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dimana Anda dapat menemukan informasi lebih lanjut tentang penggabungan templat dan penggunaan metode ConvertTemplate().

Langkah Konversi (Penggabungan)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sumber templat. Tentukan sumber templat HTML melalui file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objek instance, atau bahkan melalui konten inline. Hasil konversi. Anda dapat memperoleh langsung HTMLDocument yang dihasilkan atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Buat instance dari [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gunakan metode ConvertTemplate() dari kelas Converter untuk menggabungkan templat dengan data. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Bentuk konten sumber inline sebagai templat
      String templateContent =
        "<html>" +
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";

      // Bentuk jalur file data templat xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Tentukan instance objek TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Bentuk output sebagai hasil penggabungan
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Tentukan objek TemplateLoadOptions default
      var options = new TemplateLoadOptions();

      // Mulai proses konversi dan simpan hasil
      using (var document = Converter.ConvertTemplate(
        templateContent, String.Empty,
        templateData,
        options))
      {
        document.Save(new Url(resultFilePath));
      }
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_5}

Gabungkan sumber HTML templat yang disajikan oleh konten inline dengan data templat (XML, JSON). Hasilnya adalah [`HTMLDocument`](../../../com.aspose.html/htmldocument/) baru yang dapat disimpan sebagai file.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, 
    Configuration configuration, TemplateData data, TemplateLoadOptions options)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | Menggabungkan kerangka sumber HTML yang disajikan oleh konten String inline. |
| baseUrl | String | URI dasar templat html. Itu akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |
| configuration | Configuration | Konfigurasi lingkungan. Mewakili objek konteks [`configuration`](../../../com.aspose.html/configuration/) yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. |
| data | TemplateData | Data templat untuk penggabungan - substitusi (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) objek instance. Ini digunakan untuk menentukan apakah nama templat dan item data cocok, terlepas dari huruf besar/kecil atau tidak (opsi). |

### Nilai Kembali

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) baru yang dibentuk sebagai hasil konversi yang dapat disimpan melalui jalur file output.

## Catatan

Penggabung Templat

Ide penggabungan templat adalah membuat dokumen HTML berdasarkan templat HTML dan mengisinya dari sumber data. Aspose.HTML menyediakan sintaks ekspresi inline untuk bekerja dengan templat dan berbagai jenis sumber data, seperti XML dan JSON. Lihat [artikel](https://docs.aspose.com/html/net/converting-between-formats/html-template/) dimana Anda dapat menemukan informasi lebih lanjut tentang penggabungan templat dan penggunaan metode ConvertTemplate().

Langkah Konversi (Penggabungan)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

Sumber templat. Tentukan sumber templat HTML melalui file, [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) objek instance, atau bahkan melalui konten inline. Hasil konversi. Anda dapat memperoleh langsung HTMLDocument yang dihasilkan atau menentukan jalur file output hasil tergantung pada tanda tangan metode. Buat instance dari [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). Gunakan metode ConvertTemplate() dari kelas Converter untuk menggabungkan templat dengan data. Anda juga dapat menambahkan [`configuration`](../../../com.aspose.html/configuration/) sebagai parameter opsi. Kode sumber

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Contoh

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Bentuk konten sumber inline sebagai templat
      String templateContent =
        "<html>" + 
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";
       
      // Bentuk jalur file data templat xml (json)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // Tentukan instance objek TemplateData
      var templateData = new TemplateData(templateDataPath);

      // Bentuk output sebagai hasil penggabungan
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // Tentukan instance objek configuration
      var configuration = new Configuration();

      // Tentukan objek TemplateLoadOptions default
      var options = new TemplateLoadOptions();

      // Mulai proses konversi dan simpan hasil
      using (var document = Converter.ConvertTemplate(
        templateContent, String.Empty,
        configuration,
        templateData,
        options))
      {
        document.Save(new Url(resultFilePath));
      }
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### Lihat Juga

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
