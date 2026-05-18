---
title: "ICanvasRenderingContext2D.PutImageData"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode ICanvasRenderingContext2D. Melukis data dari objek ImageData yang diberikan ke bitmap. Jika sebuah persegi panjang kotor disediakan, hanya piksel dari persegi panjang tersebut yang dilukis. Metode ini tidak terpengaruh oleh matriks transformasi kanvas."
type: docs

url: /id/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(IImageData, double, double) {#putimagedata}

Melukis data dari objek ImageData yang diberikan ke bitmap. Jika persegi panjang kotor disediakan, hanya piksel dari persegi panjang tersebut yang dilukis. Metode ini tidak dipengaruhi oleh matriks transformasi kanvas.

```java
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imagedata | IImageData | Sebuah objek ImageData yang berisi array nilai piksel. |
| dx | Double | Posisi horizontal (koordinat-x) tempat menempatkan data gambar di kanvas tujuan. |
| dy | Double | Posisi vertikal (koordinat-y) tempat menempatkan data gambar di kanvas tujuan. |

### Lihat Juga

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## PutImageData(IImageData, double, double, double, double, double, double) {#putimagedata_1}

Melukis data dari objek ImageData yang diberikan ke bitmap. Jika persegi panjang kotor disediakan, hanya piksel dari persegi panjang tersebut yang dilukis. Metode ini tidak dipengaruhi oleh matriks transformasi kanvas.

```java
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imagedata | IImageData | Sebuah objek ImageData yang berisi array nilai piksel. |
| dx | Double | Posisi horizontal (koordinat-x) tempat menempatkan data gambar di kanvas tujuan. |
| dy | Double | Posisi vertikal (koordinat-y) tempat menempatkan data gambar di kanvas tujuan. |
| dirtyX | Double | Posisi horizontal (koordinat-x). Koordinat x dari sudut kiri atas data Image Anda. Default 0. |
| dirtyY | Double | Posisi vertikal (koordinat-y). Koordinat y dari sudut kiri atas data Image Anda. Default 0. |
| dirtyWidth | Double | Lebar persegi panjang yang akan dilukis. Default lebar image data. |
| dirtyHeight | Double | Tinggi persegi panjang yang akan dilukis. Default tinggi image data. |

### Lihat Juga

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
