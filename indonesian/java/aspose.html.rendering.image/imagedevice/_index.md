---
title: "Kelas ImageDevice"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Kelas com.aspose.html.rendering.image.ImageDevice. Mewakili rendering ke format raster jpeg png bmp gif tiff."
type: docs

url: /id/java/com.aspose.html.rendering.image/imagedevice/
---
## ImageDevice class

Mewakili rendering ke format raster: jpeg, png, bmp, gif, tiff.

```java
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)(ICreateStreamProvider) | Menginisialisasi instance baru dari kelas `ImageDevice`. |
| [ImageDevice](imagedevice/#constructor_4)(Stream) | Menginisialisasi instance baru dari kelas `ImageDevice`. |
| [ImageDevice](imagedevice/#constructor_5)(String) | Menginisialisasi instance baru dari kelas `ImageDevice`. |
| [ImageDevice](imagedevice/#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | Menginisialisasi instance baru dari kelas `ImageDevice` dengan opsi rendering dan penyedia aliran. |
| [ImageDevice](imagedevice/#constructor_2)(ImageRenderingOptions, Stream) | Menginisialisasi instance baru dari kelas `ImageDevice` dengan opsi rendering dan aliran keluaran. |
| [ImageDevice](imagedevice/#constructor_3)(ImageRenderingOptions, String) | Menginisialisasi instance baru dari kelas `ImageDevice` dengan opsi rendering dan nama berkas keluaran. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/device-2/addrect/)(RectangleF) |  |
| [beginDocument](../../com.aspose.html.rendering/device-2/begindocument/)(Document) |  |
| [beginElement](../../com.aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) |  |
| [beginPage](../../com.aspose.html.rendering/device-2/beginpage/)(SizeF) |  |
| [clip](../../com.aspose.html.rendering/device-2/clip/)(FillRule) |  |
| [closePath](../../com.aspose.html.rendering/device-2/closepath/)() |  |
| [cubicBezierTo](../../com.aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) |  |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) |  |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering/device-2/endelement/)(Element) |  |
| [endPage](../../com.aspose.html.rendering/device-2/endpage/)() |  |
| [fill](../../com.aspose.html.rendering/device-2/fill/)(FillRule) |  |
| [fillText](../../com.aspose.html.rendering/device-2/filltext/)(String, PointF) |  |
| [flush](../../com.aspose.html.rendering/device-2/flush/)() |  |
| [lineTo](../../com.aspose.html.rendering/device-2/lineto/)(PointF) |  |
| [moveTo](../../com.aspose.html.rendering/device-2/moveto/)(PointF) |  |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering/device-2/stroke/)() |  |
| [strokeAndFill](../../com.aspose.html.rendering/device-2/strokeandfill/)(FillRule) |  |
| [strokeText](../../com.aspose.html.rendering/device-2/stroketext/)(String, PointF) |  |

## Anggota Lainnya

| Nama | Deskripsi |
| --- | --- |
| class [ImageGraphicContext](../../com.aspose.html.rendering.image/imagedevice.imagegraphiccontext) | Menyimpan parameter kontrol grafis saat ini untuk `ImageDevice`. Parameter ini mendefinisikan kerangka kerja global tempat operator grafis dijalankan. |

### Lihat Juga

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [ImageRenderingOptions](../imagerenderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
