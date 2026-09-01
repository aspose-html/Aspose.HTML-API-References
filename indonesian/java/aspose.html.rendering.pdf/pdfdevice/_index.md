---
title: "Kelas PdfDevice"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.rendering.pdf.PdfDevice. Mewakili rendering ke dokumen pdf"
type: docs

url: /id/java/com.aspose.html.rendering.pdf/pdfdevice/
---
## PdfDevice class

Mewakili proses rendering ke dokumen PDF.

```java
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(ICreateStreamProvider) | Menginisialisasi instance baru dari kelas `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_4)(Stream) | Menginisialisasi instance baru dari kelas `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_5)(String) | Menginisialisasi instance baru dari kelas `PdfDevice`. |
| [PdfDevice](pdfdevice/#constructor_1)(PdfRenderingOptions, ICreateStreamProvider) | Menginisialisasi instance baru dari kelas `PdfDevice` dengan opsi rendering dan penyedia aliran. |
| [PdfDevice](pdfdevice/#constructor_2)(PdfRenderingOptions, Stream) | Menginisialisasi instance baru dari kelas `PdfDevice` dengan opsi rendering dan aliran output. |
| [PdfDevice](pdfdevice/#constructor_3)(PdfRenderingOptions, String) | Menginisialisasi instance baru dari kelas `PdfDevice` dengan opsi rendering dan nama file output. |

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
| class [PdfGraphicContext](../../com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext) | Menyimpan parameter kontrol grafis saat ini untuk PdfDevice. Parameter ini mendefinisikan kerangka kerja global di mana operator grafis dijalankan. |

### Lihat Juga

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* package [com.aspose.html.rendering.pdf](../../com.aspose.html.rendering.pdf/)
* package [Aspose.HTML](../../)
