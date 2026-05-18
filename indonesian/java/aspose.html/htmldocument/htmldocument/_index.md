---
title: "HTMLDocument"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Konstruktor HTMLDocument. Konstruktor HTMLDocument membuat objek HTML Document baru yang merupakan halaman web yang dimuat di browser dan berfungsi sebagai titik masuk ke konten halaman."
type: docs

url: /id/java/com.aspose.html/htmldocument/htmldocument/
---
## HTMLDocument() {#constructor}

Konstruktor HTMLDocument membuat objek Dokumen HTML baru yang merupakan halaman web yang dimuat di peramban dan berfungsi sebagai titik masuk ke konten halaman.

```java
public HTMLDocument()
```

## Catatan

Catatan: Dokumen dibuat dengan nilai default untuk properti base-url yang sama dengan 'about:blank'.

Referensi:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Contoh

Setelah objek dokumen dibuat, ia dapat diisi kemudian dengan elemen HTML. Potongan kode berikut menunjukkan penggunaan konstruktor default HTMLDocument() untuk membuat dokumen HTML kosong dan menyimpannya ke sebuah file.

```java
import (var document = new HTMLDocument())
{
	// Bekerja dengan dokumen di sini
	...	
	
	// Simpan dokumen ke sebuah file
	document.Save("document.html");
}
```

### Lihat Juga

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Configuration) {#constructor_1}

Konstruktor HTMLDocument membuat objek Dokumen HTML baru yang merupakan halaman web yang dimuat di peramban dan berfungsi sebagai titik masuk ke konten halaman.

```java
public HTMLDocument(Configuration configuration)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konfigurasi | Konfigurasi | Konfigurasi lingkungan seperti kebijakan skrip, stylesheet pengguna khusus, dll. |

## Catatan

Catatan: Dokumen dibuat dengan nilai default untuk properti base-url yang sama dengan 'about:blank'.

Referensi:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Contoh

Contoh berikut menunjukkan cara menggunakan objek konfigurasi untuk menonaktifkan skrip:

```java
// Siapkan kode HTML dan simpan ke sebuah file
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Buat sebuah instance dari Configuration
import (var configuration = new Configuration())
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
```

### Lihat Juga

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url) {#constructor_4}

Memuat dokumen HTML dari sebuah URL.

Catatan: Jika Anda memberikan URL yang salah dan tidak dapat dijangkau saat ini, perpustakaan akan melempar [`DOMException`](../../../com.aspose.html.dom/domexception/) dengan kode khusus ‘NetworkError’ untuk memberi tahu Anda bahwa sumber daya yang dipilih tidak dapat ditemukan.

```java
public HTMLDocument(Url url)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL dokumen HTML yang akan dibuka. |

## Catatan

Referensi:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Contoh

Muat dokumen dari halaman web 'https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html':

```java
import (var document = new HTMLDocument("https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html"))
{
	// Tulis konten dokumen ke aliran output
	Console.WriteLine(document.DocumentElement.OuterHTML);
}
```

### Lihat Juga

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url, Configuration) {#constructor_5}

Memuat dokumen HTML dari sebuah URL dengan pengaturan konfigurasi lingkungan yang ditentukan.

Catatan: Jika Anda memberikan URL yang salah dan tidak dapat dijangkau saat ini, perpustakaan akan melempar [DOMException](T:com.aspose.html.dom.DOMException) dengan kode khusus ‘NetworkError’ untuk memberi tahu Anda bahwa sumber daya yang dipilih tidak dapat ditemukan.

```java
public HTMLDocument(Url url, Configuration configuration)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL dokumen HTML yang akan dibuka. |
| konfigurasi | Konfigurasi | Konfigurasi lingkungan seperti kebijakan skrip, stylesheet pengguna khusus, dll. |

## Catatan

Referensi:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Contoh

```java
The following example demonstrates how to use the configuration object to disable scripts:

// Siapkan kode HTML dan simpan ke sebuah file
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Buat sebuah instance dari Configuration
import (var configuration = new Configuration())
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
```

### Lihat Juga

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String) {#constructor_10}

Memuat dokumen HTML dari sebuah alamat.

Catatan: Jika Anda memberikan URL yang salah dan tidak dapat dijangkau saat ini, perpustakaan akan melempar [`DOMException`](../../../com.aspose.html.dom/domexception/) dengan kode khusus ‘NetworkError’ untuk memberi tahu Anda bahwa sumber daya yang dipilih tidak dapat ditemukan.

```java
public HTMLDocument(String address)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alamat | String | Alamat dokumen HTML yang akan dibuka. |

## Catatan

Referensi:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Contoh

Inisialisasi dokumen HTML dari sebuah alamat.

```java
import (var document = new HTMLDocument("./my-folder/document.html")))
{
	...
}
```

### Lihat Juga

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Configuration) {#constructor_11}

Memuat dokumen HTML dari sebuah alamat dengan pengaturan konfigurasi lingkungan yang ditentukan.

Catatan: Jika Anda memberikan URL yang salah dan tidak dapat dijangkau saat ini, perpustakaan akan melempar [`DOMException`](../../../com.aspose.html.dom/domexception/) dengan kode khusus ‘NetworkError’ untuk memberi tahu Anda bahwa sumber daya yang dipilih tidak dapat ditemukan.

```java
public HTMLDocument(String address, Configuration configuration)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alamat | String | Alamat dokumen HTML yang akan dibuka. |
| konfigurasi | Konfigurasi | Konfigurasi lingkungan seperti kebijakan skrip, stylesheet pengguna khusus, dll. |

## Catatan

Referensi:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Contoh

```java
// Buat sebuah instance dari Configuration
import (var configuration = new Configuration())
{
	// Tandai 'scripts' sebagai sumber daya yang tidak dipercaya
	configuration.Security |= Sandbox.Scripts;
	
	using (var document = new HTMLDocument("./my-folder/document.html", configuration)))
	{
		...
	}
}
```

### Lihat Juga

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String) {#constructor_14}

Membuat dokumen HTML dari konten String dengan base-uri yang ditentukan.

```java
public HTMLDocument(String content, String baseUri)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | Konten String untuk memuat dokumen. |
| baseUri | String | URI dasar dokumen. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Melempar jika parameter base-uri bernilai null. |

## Catatan

Referensi:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Contoh

```java
// Siapkan kode HTML
var html_code = "<p>Hello World!</p>";

// Inisialisasi dokumen dari variabel String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Lihat Juga

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String, Configuration) {#constructor_15}

Membuat dokumen HTML dari konten String dengan base-uri dan pengaturan konfigurasi lingkungan yang ditentukan.

```java
public HTMLDocument(String content, String baseUri, Configuration configuration)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | Konten String untuk memuat dokumen. |
| baseUri | String | URI dasar dokumen. |
| konfigurasi | Konfigurasi | Konfigurasi lingkungan seperti kebijakan skrip, stylesheet pengguna khusus, dll. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Melempar jika parameter base-uri bernilai null. |

## Catatan

Referensi:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Contoh

```java
// Siapkan kode HTML
var html_code = "<p>Hello World!</p>";

// Inisialisasi dokumen dari variabel String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Lihat Juga

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url) {#constructor_12}

Membuat dokumen HTML dari konten String dengan base-uri yang ditentukan.

```java
public HTMLDocument(String content, Url baseUri)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | Konten String untuk memuat dokumen. |
| baseUri | Url | URI dasar dokumen. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Melempar jika parameter base-uri bernilai null. |

## Catatan

Referensi:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Contoh

```java
// Siapkan kode HTML
var html_code = "<p>Hello World!</p>";

// Inisialisasi dokumen dari variabel String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Lihat Juga

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url, Configuration) {#constructor_13}

Membuat dokumen HTML dari konten String dengan base-uri dan pengaturan konfigurasi lingkungan yang ditentukan.

```java
public HTMLDocument(String content, Url baseUri, Configuration configuration)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | Konten String untuk memuat dokumen. |
| baseUri | Url | URI dasar dokumen. |
| konfigurasi | Konfigurasi | Konfigurasi lingkungan seperti kebijakan skrip, stylesheet pengguna khusus, dll. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Melempar jika parameter base-uri bernilai null. |

## Catatan

Referensi:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Contoh

```java
// Siapkan kode HTML
var html_code = "<p>Hello World!</p>";

// Inisialisasi dokumen dari variabel String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Lihat Juga

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String) {#constructor_8}

Membuat dokumen HTML dari konten [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) dengan base-uri yang ditentukan yang digunakan untuk menyelesaikan jalur sumber daya relatif.

```java
public HTMLDocument(Stream content, String baseUri)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| content | Stream | Konten [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) untuk memuat dokumen. |
| baseUri | String | URI dasar dokumen. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Melempar jika parameter base-uri bernilai null. |

## Catatan

Referensi:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Contoh

```java
// Buat objek memory stream
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Tulis kode HTML ke dalam objek memori
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Penting untuk mengatur posisi ke awal karena HTMLDocument memulai pembacaan tepat dari posisi saat ini dalam aliran.
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Inisialisasi dokumen dari variabel String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Simpan dokumen ke disk.
		document.Save("load-from-stream.html");
	}
}
```

### Lihat Juga

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String, Configuration) {#constructor_9}

Membuat dokumen HTML dari konten [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) dengan base-uri dan pengaturan konfigurasi lingkungan yang ditentukan.

```java
public HTMLDocument(Stream content, String baseUri, Configuration configuration)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| content | Stream | Konten [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) untuk memuat dokumen. |
| baseUri | String | URI dasar dokumen. |
| konfigurasi | Konfigurasi | Konfigurasi lingkungan seperti kebijakan skrip, stylesheet pengguna khusus, dll. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Melempar jika parameter base-uri bernilai null. |

## Catatan

Referensi:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Contoh

```java
// Buat objek memory stream
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Tulis kode HTML ke dalam objek memori
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Penting untuk mengatur posisi ke awal karena HTMLDocument memulai pembacaan tepat dari posisi saat ini dalam aliran.
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Inisialisasi dokumen dari variabel String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Simpan dokumen ke disk.
		document.Save("load-from-stream.html");
	}
}
```

### Lihat Juga

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url) {#constructor_6}

Membuat dokumen HTML dari konten [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) dengan base-uri yang ditentukan yang digunakan untuk menyelesaikan jalur sumber daya relatif.

```java
public HTMLDocument(Stream content, Url baseUri)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| content | Stream | Konten [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) untuk memuat dokumen. |
| baseUri | Url | URI dasar dokumen. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Melempar jika parameter base-uri bernilai null. |

## Catatan

Referensi:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Contoh

```java
// Buat objek memory stream
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Tulis kode HTML ke dalam objek memori
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Penting untuk mengatur posisi ke awal karena HTMLDocument memulai pembacaan tepat dari posisi saat ini dalam aliran.
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Inisialisasi dokumen dari variabel String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Simpan dokumen ke disk.
		document.Save("load-from-stream.html");
	}
}
```

### Lihat Juga

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url, Configuration) {#constructor_7}

Membuat dokumen HTML dari konten [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) dengan base-uri dan pengaturan konfigurasi lingkungan yang ditentukan.

```java
public HTMLDocument(Stream content, Url baseUri, Configuration configuration)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| content | Stream | Konten [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) untuk memuat dokumen. |
| baseUri | Url | URI dasar dokumen. |
| konfigurasi | Konfigurasi | Konfigurasi lingkungan seperti kebijakan skrip, stylesheet pengguna khusus, dll. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Melempar jika parameter base-uri bernilai null. |

## Catatan

Referensi:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Contoh

```java
// Buat objek memory stream
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Tulis kode HTML ke dalam objek memori
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Penting untuk mengatur posisi ke awal karena HTMLDocument memulai pembacaan tepat dari posisi saat ini dalam aliran.
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Inisialisasi dokumen dari variabel String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Simpan dokumen ke disk.
		document.Save("load-from-stream.html");
	}
}
```

### Lihat Juga

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage) {#constructor_2}

Membuat dokumen HTML dari objek [`RequestMessage`](../../../com.aspose.html.net/requestmessage/).

```java
public HTMLDocument(RequestMessage request)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| request | RequestMessage | Pesan permintaan yang berisi [`body`](../../../com.aspose.html.net/requestmessage/content/) dengan konten dokumen. |

## Catatan

Menurut definisi, message handler adalah kelas yang menerima permintaan Web dan mengembalikan respons Web. Dengan kata lain, message handler digunakan untuk memproses permintaan layanan Web selama input dan/atau memproses respons selama output.

Silakan kunjungi [situs dokumentasi](https://docs.aspose.com/html/net/message-handlers/) kami untuk melihat lebih banyak skenario tentang cara menggunakan konstruktor ini.

Referensi:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Lihat Juga

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage, Configuration) {#constructor_3}

Membuat dokumen HTML dari objek [RequestMessage](T:com.aspose.html.net.RequestMessage).

```java
public HTMLDocument(RequestMessage request, Configuration configuration)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| request | RequestMessage | Pesan permintaan yang berisi [body](P:com.aspose.html.net.RequestMessage.Content) dengan konten dokumen. |
| konfigurasi | Konfigurasi | Konfigurasi lingkungan seperti kebijakan skrip, stylesheet pengguna khusus, dll. |

## Catatan

Menurut definisi, message handler adalah kelas yang menerima permintaan Web dan mengembalikan respons Web. Dengan kata lain, message handler digunakan untuk memproses permintaan layanan Web selama input dan/atau memproses respons selama output.

Silakan kunjungi [situs dokumentasi](https://docs.aspose.com/html/net/message-handlers/) kami untuk melihat lebih banyak skenario tentang cara menggunakan konstruktor ini.

Referensi:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Lihat Juga

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
