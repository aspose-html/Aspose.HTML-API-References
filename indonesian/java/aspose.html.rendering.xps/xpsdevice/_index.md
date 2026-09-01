---
title: "Kelas XpsDevice"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.rendering.xps.XpsDevice. Mewakili proses rendering ke dokumen xps"
type: docs

url: /id/java/com.aspose.html.rendering.xps/xpsdevice/
---
## XpsDevice class

Mewakili proses rendering ke dokumen xps.

```java
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [XpsDevice](xpsdevice/#constructor)(ICreateStreamProvider) | Menginisialisasi instance baru dari kelas `XpsDevice`. |
| [XpsDevice](xpsdevice/#constructor_4)(Stream) | Menginisialisasi instance baru dari kelas `XpsDevice`. |
| [XpsDevice](xpsdevice/#constructor_5)(String) | Menginisialisasi instance baru dari kelas `XpsDevice`. |
| [XpsDevice](xpsdevice/#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | Menginisialisasi instance baru dari kelas `XpsDevice` dengan opsi rendering dan penyedia aliran. |
| [XpsDevice](xpsdevice/#constructor_2)(XpsRenderingOptions, Stream) | Menginisialisasi instance baru dari kelas `XpsDevice` dengan opsi rendering dan aliran output. |
| [XpsDevice](xpsdevice/#constructor_3)(XpsRenderingOptions, String) | Menginisialisasi instance baru dari kelas `XpsDevice` dengan opsi rendering dan nama file output. |

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

## Anggota Lain

| Nama | Deskripsi |
| --- | --- |
| class [XpsGraphicContext](../../com.aspose.html.rendering.xps/xpsdevice.xpsgraphiccontext) | Menyimpan parameter kontrol grafis saat ini untuk XpsDevice. Parameter ini mendefinisikan kerangka kerja global di mana operator grafis dijalankan. |

### Lihat Juga

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext/)
* class [XpsRenderingOptions](../xpsrenderingoptions/)
* package [com.aspose.html.rendering.xps](../../com.aspose.html.rendering.xps/)
* package [Aspose.HTML](../../)
