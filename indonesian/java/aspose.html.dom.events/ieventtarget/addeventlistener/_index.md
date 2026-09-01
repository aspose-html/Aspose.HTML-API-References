---
title: "IEventTarget.AddEventListener"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode IEventTarget. Metode EventTarget addEventListener menyiapkan sebuah fungsi yang akan dipanggil setiap kali event yang ditentukan disampaikan ke target"
type: docs

url: /id/java/com.aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(String, IEventListener) {#addeventlistener}

Metode EventTarget addEventListener() menyiapkan fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan disampaikan ke target.

Target umum adalah Element, Document, dan Window, tetapi target dapat berupa objek apa pun yang mendukung event (seperti XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tipe | String | String yang peka huruf besar/kecil yang mewakili tipe event untuk didengarkan. |
| listener | IEventListener | Menerima sebuah antarmuka yang diimplementasikan oleh pengguna yang berisi metode-metode yang akan dipanggil ketika event terjadi. |

## Catatan

Jika sebuah ditambahkan ke sementara sedang memproses sebuah event, itu tidak akan dipicu oleh tindakan saat ini tetapi dapat dipicu pada tahap alur event berikutnya, seperti fase gelembung. Jika beberapa Event Listener yang identik terdaftar pada yang sama dengan parameter yang sama, instance duplikat akan dibuang. Mereka tidak menyebabkan dipanggil dua kali dan karena dibuang, mereka tidak perlu dihapus dengan metode tersebut.

### Lihat Juga

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_1}

Metode EventTarget addEventListener() menyiapkan fungsi yang akan dipanggil setiap kali peristiwa yang ditentukan disampaikan ke target.

Target umum adalah Element, Document, dan Window, tetapi target dapat berupa objek apa pun yang mendukung event (seperti XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tipe | String | String yang peka huruf besar/kecil yang mewakili tipe event untuk didengarkan. |
| listener | IEventListener | Menerima sebuah antarmuka yang diimplementasikan oleh pengguna yang berisi metode-metode yang akan dipanggil ketika event terjadi. |
| useCapture | Boolean | Jika true, useCapture menunjukkan bahwa pengguna ingin memulai penangkapan. Setelah memulai penangkapan, semua event dengan tipe yang ditentukan akan disebarkan ke yang terdaftar sebelum disebarkan ke Event Target mana pun di bawahnya dalam pohon. Event yang naik melalui pohon dengan gelembung tidak akan memicu yang ditunjuk untuk menggunakan penangkapan. |

## Catatan

Jika sebuah ditambahkan ke sementara sedang memproses sebuah event, itu tidak akan dipicu oleh tindakan saat ini tetapi dapat dipicu pada tahap alur event berikutnya, seperti fase gelembung. Jika beberapa Event Listener yang identik terdaftar pada yang sama dengan parameter yang sama, instance duplikat akan dibuang. Mereka tidak menyebabkan dipanggil dua kali dan karena dibuang, mereka tidak perlu dihapus dengan metode tersebut.

### Lihat Juga

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
