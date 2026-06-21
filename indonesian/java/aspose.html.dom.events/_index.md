---
title: "com.aspose.html.dom.events"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Paket **com.aspose.html.dom.events** menyediakan objek untuk setiap peristiwa yang terkait dengan pembaruan DOM. Paket ini mencakup langganan pada pengamatan informasi kontekstual spesifik yang terkait dengan peristiwa serta konstruksi peristiwa khusus."
type: docs

url: /id/java/com.aspose.html.dom.events/
---
Paket **com.aspose.html.dom.events** menyediakan objek untuk semua peristiwa yang terkait dengan pembaruan DOM. Paket ini mencakup langganan untuk pengamatan informasi kontekstual spesifik yang terkait dengan peristiwa serta pembuatan peristiwa kustom.

## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [CustomEvent](./customevent/) | Peristiwa yang menggunakan antarmuka **CustomEvent** dapat digunakan untuk membawa data khusus. |
| [DocumentLoadErrorEvent](./documentloaderrorevent/) | **DocumentLoadErrorEvent** terjadi ketika sumber daya yang diminta tidak tersedia. |
| [DOMEventHandler](./domeventhandler/) | Mewakili delegasi callback generik untuk penanganan peristiwa Document Object Model (DOM). |
| [ErrorEvent](./errorevent/) | ErrorEvent menyediakan informasi kontekstual tentang kesalahan yang terjadi selama runtime. |
| [Event](./event/) | Ini digunakan untuk menyediakan informasi kontekstual tentang suatu peristiwa kepada penangan yang memproses peristiwa tersebut. |
| [FocusEvent](./focusevent/) | Antarmuka FocusEvent menyediakan informasi kontekstual spesifik yang terkait dengan peristiwa Fokus. |
| [InputEvent](./inputevent/) | Peristiwa input dikirim sebagai notifikasi setiap kali DOM diperbarui. |
| [KeyboardEvent](./keyboardevent/) | Antarmuka KeyboardEvent menyediakan informasi kontekstual spesifik yang terkait dengan perangkat keyboard. Setiap peristiwa keyboard merujuk pada sebuah tombol menggunakan nilai. Peristiwa keyboard biasanya diarahkan ke elemen yang memiliki fokus. |
| [MouseEvent](./mouseevent/) | Antarmuka MouseEvent menyediakan informasi kontekstual spesifik yang terkait dengan peristiwa Mouse. |
| [UIEvent](./uievent/) | Antarmuka UIEvent menyediakan informasi kontekstual spesifik yang terkait dengan peristiwa Antarmuka Pengguna. |
| [WheelEvent](./wheelevent/) | Antarmuka WheelEvent menyediakan informasi kontekstual spesifik yang terkait dengan peristiwa roda. Untuk membuat instance antarmuka WheelEvent, gunakan konstruktor WheelEvent dengan memberikan kamus opsional WheelEventInit. |
## Antarmuka

| Antarmuka | Deskripsi |
| --- | --- |
| [IDocumentEvent](./idocumentevent/) | Antarmuka DocumentEvent menyediakan mekanisme yang memungkinkan pengguna membuat Event dengan tipe yang didukung oleh implementasi. Diharapkan antarmuka DocumentEvent akan diimplementasikan pada objek yang sama yang mengimplementasikan antarmuka Document dalam implementasi yang mendukung model Event. |
| [IEventListener](./ieventlistener/) | Antarmuka ini adalah metode utama untuk menangani peristiwa. Pengguna mengimplementasikan antarmuka dan mendaftarkan pendengar mereka menggunakan metode tersebut. Pengguna juga harus menghapus pendengar mereka setelah selesai menggunakannya. |
| [IEventTarget](./ieventtarget/) | Antarmuka EventTarget diimplementasikan oleh semua Node dalam implementasi yang mendukung Model Peristiwa DOM. Oleh karena itu, antarmuka ini dapat diperoleh dengan menggunakan metode casting khusus binding pada sebuah instance antarmuka Node. Antarmuka ini memungkinkan pendaftaran dan penghapusan Event Listener pada sebuah objek serta pengiriman peristiwa ke objek tersebut. |
