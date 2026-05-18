---
title: "Configuration Kelas"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "com.aspose.html.Configuration class. Mewakili objek konteks konfigurasi yang digunakan untuk mengatur pengaturan lingkungan bagi aplikasi. Dengan mengelola konfigurasi Anda dapat menimpa gaya dokumen dengan menerapkan stylesheet pengguna khusus atau menangani permintaan web apa pun dari aplikasi serta mengonfigurasi kebijakan skrip. Rincian ada di panduan Environment Configuration."
type: docs

url: /id/java/com.aspose.html/configuration/
---
## Configuration class

Mewakili objek konteks konfigurasi yang digunakan untuk menyiapkan pengaturan lingkungan bagi aplikasi. Dengan mengelola konfigurasi, Anda dapat mengganti gaya dokumen dengan menerapkan stylesheet pengguna khusus, atau menangani permintaan web apa pun dari aplikasi serta mengonfigurasi kebijakan skrip. Rincian ada di [Environment Configuration guide](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/).

```java
public class Configuration : IDisposable, IServiceProvider
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Configuration](configuration/)() | Menginisialisasi instance baru dari `class`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
[getSecurity]
[setSecurity] Gets or sets the sandboxing flag of the configuration. Refer to article about [sandboxing](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/#sandboxing). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [Create](../../com.aspose.html/configuration/create/#create)() | Buat dan konfigurasikan instance objek Configuration. |
| static [Create](../../com.aspose.html/configuration/create/#create_1)(Action&lt;IConfigurationBuilder&gt;) | Buat dan konfigurasikan instance objek Configuration. |
| [dispose](../../com.aspose.html/configuration/dispose/)() | Melakukan tugas yang ditentukan aplikasi terkait dengan pembebasan, pelepasan, atau pengaturan ulang sumber daya yang tidak dikelola. |
| [getService](../../com.aspose.html/configuration/getservice/#getservice)(Type) | Mendapatkan layanan yang diminta. |
| [GetService&lt;T&gt;](../../com.aspose.html/configuration/getservice/#getservice_1)() | Mendapatkan layanan yang diminta. |

## Catatan

Anda dapat mengunduh contoh lengkap dan file data dari [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Contoh

```java
import System;
import System.Diagnostics;
import System.IO;
import Aspose.Html;
import com.aspose.html.net;
import com.aspose.html.services;

    // Penangan pesan ini mencetak pesan tentang mulai dan selesai memproses permintaan.
    public class LogMessageHandler : MessageHandler
    {
      // Timpa metode Invoke()
      public void Invoke(INetworkOperationContext context)
      {
        Debug.WriteLine("Start processing request: " + context.Request.RequestUri);

        // Panggil penangan pesan berikutnya dalam rantai.
        Next(context);

        Debug.WriteLine("Finish processing request: " + context.Request.RequestUri);
      }
    }
```

```java
    public void CreateACustomMessageHandlerTest()
    {
      // Buat sebuah instance dari kelas Configuration
      using var configuration = new Configuration();

      // Tambahkan LogMessageHandler ke rantai penangan pesan yang ada
      var service = configuration.GetService<INetworkService>();
      var handlers = service.MessageHandlers;
           
      handlers.Insert(0, new LogMessageHandler());

      // Siapkan jalur ke file dokumen sumber
      String documentPath = Path.Combine(DataDir, "input.htm");

      // Inisialisasi dokumen HTML dengan konfigurasi yang ditentukan
      using var document = new HTMLDocument(documentPath, configuration);
    }
```

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.net;
import com.aspose.html.saving;
import com.aspose.html.services;
import System;
import System.Collections.Generic;
import System.IO;
import System.Net;
import System.Text;

public void SandboxingSample()
    {
      // Siapkan kode HTML dan simpan ke sebuah file
      var code = "<span>Hello World!!</span> " +
            "<script>document.write('Have a nice day!');</script>";

      File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

      // Buat sebuah instance dari Configuration
      using (var configuration = new Configuration())
      {
        // Tandai 'scripts' sebagai sumber daya yang tidak dipercaya
        configuration.Security |= Sandbox.Scripts;

        // Inisialisasi dokumen HTML dengan konfigurasi yang ditentukan
        using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
        {
          // Konversi HTML ke PDF
          Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
        }
      }       
    }
```

*OutputDir - user output folder path.

### Lihat Juga

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
