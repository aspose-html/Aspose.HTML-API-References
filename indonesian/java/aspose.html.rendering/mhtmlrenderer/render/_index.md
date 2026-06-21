---
title: "MhtmlRenderer.Render"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode MhtmlRenderer. Merender beberapa dokumen MHTML ke dalam IDevice yang ditentukan. Rendering akan dilakukan setelah tidak ada operasi jaringan untuk memuat sumber daya, timer aktif, tugas animasi, atau batas waktu yang ditentukan telah berlalu"
type: docs

url: /id/java/com.aspose.html.rendering/mhtmlrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

Merender beberapa dokumen MHTML ke dalam [`IDevice`](../../idevice/). Rendering akan dilakukan setelah tidak ada operasi jaringan untuk memuat sumber daya, timer aktif, tugas animasi, atau batas waktu yang ditentukan telah berlalu.

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| perangkat | IDevice | Perangkat. |
| timeout | TimeSpan | Sebuah TimeSpan yang mewakili jumlah milidetik untuk menunggu, atau sebuah TimeSpan yang mewakili -1 milidetik untuk menunggu tanpa batas. |
| dokumen | Stream[] | Dokumen yang akan dirender. |

### Lihat Juga

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

Mendefinisikan metode untuk merender beberapa dokumen MHTML ke dalam [`IDevice`](../../idevice/) tertentu, menggunakan token pembatalan untuk meminta pembatalan operasi.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| perangkat | IDevice | Perangkat keluaran. |
| cancellationToken | CancellationToken | Sebuah CancellationToken untuk dipantau saat menunggu tugas selesai. |
| sumber | Stream[] | Dokumen MHTML yang akan dirender. |

### Lihat Juga

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

Merender dokumen MHTML ke dalam [`IDevice`](../../idevice/) yang ditentukan.

```java
public void Render(IDevice device, Stream source, Configuration configuration)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| perangkat | IDevice | Perangkat. |
| dokumen | Aliran | Dokumen. |
| konfigurasi | Konfigurasi | Konfigurasi. |

### Lihat Juga

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

Merender dokumen MHTML ke dalam [`IDevice`](../../idevice/) yang ditentukan. Rendering akan dilakukan setelah tidak ada operasi jaringan untuk memuat sumber daya, timer aktif, tugas animasi, atau batas waktu yang ditentukan telah berlalu.

```java
public void Render(IDevice device, Stream source, Configuration configuration, TimeSpan timeout)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| perangkat | IDevice | Perangkat. |
| dokumen | Aliran | Dokumen. |
| konfigurasi | Konfigurasi | Konfigurasi. |
| timeout | TimeSpan | Sebuah TimeSpan yang mewakili jumlah milidetik untuk menunggu, atau sebuah TimeSpan yang mewakili -1 milidetik untuk menunggu tanpa batas. |

### Lihat Juga

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

Merender beberapa dokumen MHTML ke dalam [`IDevice`](../../idevice/) yang ditentukan.

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| perangkat | IDevice | Perangkat. |
| dokumen | IList`1 | IList dokumen yang akan dirender. |
| konfigurasi | Konfigurasi | Konfigurasi. |

### Lihat Juga

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

Merender beberapa dokumen MHTML ke dalam [`IDevice`](../../idevice/). Rendering akan dilakukan setelah tidak ada operasi jaringan untuk memuat sumber daya, timer aktif, tugas animasi, atau batas waktu yang ditentukan telah berlalu.

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration, 
    TimeSpan timeout)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| perangkat | IDevice | Perangkat. |
| dokumen | IList`1 | IList dokumen yang akan dirender. |
| konfigurasi | Konfigurasi | Konfigurasi. |
| timeout | TimeSpan | Sebuah TimeSpan yang mewakili jumlah milidetik untuk menunggu, atau sebuah TimeSpan yang mewakili -1 milidetik untuk menunggu tanpa batas. |

### Lihat Juga

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
