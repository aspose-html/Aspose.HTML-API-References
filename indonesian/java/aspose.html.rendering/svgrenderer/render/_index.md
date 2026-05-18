---
title: "SvgRenderer.Render"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "metode SvgRenderer. Mendefinisikan metode untuk merender banyak SVGDocuments ke IDevice tertentu. Rendering akan dilakukan setelah tidak ada operasi jaringan untuk memuat sumber daya, timer aktif, tugas animasi, atau batas waktu yang ditentukan telah berlalu."
type: docs

url: /id/java/com.aspose.html.rendering/svgrenderer/render/
---
## Render(IDevice, TimeSpan, params SVGDocument[]) {#render_6}

Mendefinisikan metode untuk merender banyak [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ke [`IDevice`](../../idevice/) tertentu. Rendering akan dilakukan setelah tidak ada operasi jaringan untuk memuat sumber daya, timer aktif, tugas animasi, atau batas waktu yang ditentukan telah berlalu.

```java
public void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| perangkat | IDevice | Perangkat keluaran. |
| timeout | TimeSpan | TimeSpan yang mewakili jumlah milidetik untuk menunggu, atau TimeSpan yang mewakili -1 milidetik untuk menunggu tanpa batas. |
| dokumen | SVGDocument[] | Dokumen untuk dirender. |

### Lihat Juga

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params SVGDocument[]) {#render_5}

Mendefinisikan metode untuk merender banyak [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) ke [`IDevice`](../../idevice/) tertentu, menggunakan token pembatalan untuk meminta pembatalan operasi.

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| perangkat | IDevice | Perangkat keluaran. |
| cancellationToken | CancellationToken | Token pembatalan untuk dipantau saat menunggu tugas selesai. |
| sumber | SVGDocument[] | Dokumen SVG yang akan dirender. |

### Lihat Juga

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
