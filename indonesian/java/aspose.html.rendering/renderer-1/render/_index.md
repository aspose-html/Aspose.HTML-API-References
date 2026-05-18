---
title: "Renderer-1.Render"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Renderer. Mendefinisikan metode untuk merender TDocument ke dalam IDevice yang ditentukan"
type: docs

url: /id/java/com.aspose.html.rendering/renderer-1/render/
---
## Render(IDevice, TSource) {#render_3}

Mendefinisikan metode untuk merender !:TDocument ke dalam [`IDevice`](../../idevice/) yang ditentukan.

```java
public void Render(IDevice device, TSource source)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| perangkat | IDevice | Perangkat keluaran. |
| dokumen | TSource | Dokumen. |

### Lihat Juga

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, TimeSpan) {#render_5}

Mendefinisikan metode untuk merender !:TDocument ke dalam [`IDevice`](../../idevice/) yang ditentukan. Rendering akan dilakukan setelah tidak ada operasi jaringan untuk memuat sumber daya, timer aktif, tugas animasi, atau batas waktu yang ditentukan telah berlalu.

```java
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| perangkat | IDevice | Perangkat keluaran. |
| dokumen | TSource | Dokumen. |
| timeout | TimeSpan | TimeSpan yang mewakili jumlah milidetik untuk menunggu, atau TimeSpan yang mewakili -1 milidetik untuk menunggu tanpa batas. |

### Lihat Juga

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, int) {#render_4}

Mendefinisikan metode untuk merender !:TDocument ke dalam [`IDevice`](../../idevice/) yang ditentukan. Rendering akan dilakukan setelah tidak ada operasi jaringan untuk memuat sumber daya, timer aktif, tugas animasi, atau batas waktu yang ditentukan telah berlalu.

```java
public void Render(IDevice device, TSource source, int timeout)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| perangkat | IDevice | Perangkat keluaran. |
| dokumen | TSource | Dokumen. |
| timeout | Int32 | Jumlah milidetik yang mewakili jumlah milidetik untuk menunggu, atau -1 milidetik untuk menunggu tanpa batas. |

### Lihat Juga

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, params TSource[]) {#render_6}

```java
public void Render(IDevice device, params TSource[] sources)
```

### Lihat Juga

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, int, params TSource[]) {#render}

```java
public void Render(IDevice device, int timeout, params TSource[] sources)
```

### Lihat Juga

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TimeSpan, params TSource[]) {#render_2}

```java
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

### Lihat Juga

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params TSource[]) {#render_1}

```java
public abstract void Render(IDevice device, CancellationToken cancellationToken, 
    params TSource[] sources)
```

### Lihat Juga

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
