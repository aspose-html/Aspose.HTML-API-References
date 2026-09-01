---
title: "EventTarget.AddEventListener"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode EventTarget. Metode addEventListener pada antarmuka EventTarget menyiapkan sebuah fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target"
type: docs

url: /id/java/com.aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(String, DOMEventHandler, bool) {#addeventlistener}

Metode addEventListener() dari antarmuka [EventTarget ](T:com.aspose.html.dom.EventTarget) menetapkan sebuah fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target.

Cara kerjanya dengan menambahkan sebuah fungsi, atau objek yang mengimplementasikan [EventListener](T:com.aspose.html.dom.events.IEventListener), ke dalam daftar pendengar peristiwa untuk tipe peristiwa yang ditentukan pada EventTarget tempat fungsi tersebut dipanggil. Jika fungsi atau objek tersebut sudah ada dalam daftar pendengar peristiwa untuk target ini, mereka tidak akan ditambahkan lagi.

```java
public void AddEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tipe | String | Tipe peristiwa yang didaftarkan oleh pengguna |
| handler | DOMEventHandler | Menerima sebuah untuk dipanggil ketika peristiwa terjadi. |
| useCapture | Boolean | Jika true, useCapture menunjukkan bahwa pengguna ingin memulai penangkapan. Setelah memulai penangkapan, semua event dengan tipe yang ditentukan akan disebarkan ke yang terdaftar sebelum disebarkan ke Event Target mana pun di bawahnya dalam pohon. Event yang naik melalui pohon dengan gelembung tidak akan memicu yang ditunjuk untuk menggunakan penangkapan. |

## Catatan

Jika sebuah ditambahkan ke sementara sedang memproses sebuah event, itu tidak akan dipicu oleh tindakan saat ini tetapi dapat dipicu pada tahap alur event berikutnya, seperti fase gelembung. Jika beberapa Event Listener yang identik terdaftar pada yang sama dengan parameter yang sama, instance duplikat akan dibuang. Mereka tidak menyebabkan dipanggil dua kali dan karena dibuang, mereka tidak perlu dihapus dengan metode tersebut.

### Lihat Juga

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener) {#addeventlistener_1}

Metode addEventListener() pada antarmuka [`EventTarget `](../)menyiapkan sebuah fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target.

Cara kerjanya dengan menambahkan sebuah fungsi, atau objek yang mengimplementasikan [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/), ke dalam daftar pendengar peristiwa untuk tipe peristiwa yang ditentukan pada EventTarget tempat fungsi tersebut dipanggil. Jika fungsi atau objek tersebut sudah ada dalam daftar pendengar peristiwa untuk target ini, mereka tidak akan ditambahkan lagi.

```java
public void AddEventListener(String type, IEventListener listener)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tipe | String | Tipe peristiwa yang didaftarkan oleh pengguna |
| listener | IEventListener | Menerima sebuah antarmuka yang diimplementasikan oleh pengguna yang berisi metode-metode yang akan dipanggil ketika event terjadi. |

## Catatan

Jika sebuah ditambahkan ke sementara sedang memproses sebuah event, itu tidak akan dipicu oleh tindakan saat ini tetapi dapat dipicu pada tahap alur event berikutnya, seperti fase gelembung. Jika beberapa Event Listener yang identik terdaftar pada yang sama dengan parameter yang sama, instance duplikat akan dibuang. Mereka tidak menyebabkan dipanggil dua kali dan karena dibuang, mereka tidak perlu dihapus dengan metode tersebut.

### Lihat Juga

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_2}

Metode addEventListener() dari antarmuka [EventTarget ](T:com.aspose.html.dom.EventTarget) menetapkan sebuah fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan dikirim ke target.

Cara kerjanya dengan menambahkan sebuah fungsi, atau objek yang mengimplementasikan [EventListener](T:com.aspose.html.dom.events.IEventListener), ke dalam daftar pendengar peristiwa untuk tipe peristiwa yang ditentukan pada EventTarget tempat fungsi tersebut dipanggil. Jika fungsi atau objek tersebut sudah ada dalam daftar pendengar peristiwa untuk target ini, mereka tidak akan ditambahkan lagi.

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tipe | String | Tipe peristiwa yang didaftarkan oleh pengguna |
| listener | IEventListener | Menerima sebuah antarmuka yang diimplementasikan oleh pengguna yang berisi metode-metode yang akan dipanggil ketika event terjadi. |
| useCapture | Boolean | Jika true, useCapture menunjukkan bahwa pengguna ingin memulai penangkapan. Setelah memulai penangkapan, semua event dengan tipe yang ditentukan akan disebarkan ke yang terdaftar sebelum disebarkan ke Event Target mana pun di bawahnya dalam pohon. Event yang naik melalui pohon dengan gelembung tidak akan memicu yang ditunjuk untuk menggunakan penangkapan. |

## Catatan

Jika sebuah ditambahkan ke sementara sedang memproses sebuah event, itu tidak akan dipicu oleh tindakan saat ini tetapi dapat dipicu pada tahap alur event berikutnya, seperti fase gelembung. Jika beberapa Event Listener yang identik terdaftar pada yang sama dengan parameter yang sama, instance duplikat akan dibuang. Mereka tidak menyebabkan dipanggil dua kali dan karena dibuang, mereka tidak perlu dihapus dengan metode tersebut.

### Lihat Juga

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
