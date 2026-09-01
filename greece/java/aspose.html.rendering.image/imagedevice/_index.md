---
title: "ImageDevice Class"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.rendering.image.ImageDevice class. Αντιπροσωπεύει την απόδοση σε μορφές raster jpeg png bmp gif tiff"
type: docs

url: /el/java/com.aspose.html.rendering.image/imagedevice/
---
## ImageDevice class

Αντιπροσωπεύει την απόδοση σε μορφές raster: jpeg, png, bmp, gif, tiff.

```java
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)(ICreateStreamProvider) | Αρχικοποιεί μια νέα παρουσία της κλάσης `ImageDevice`. |
| [ImageDevice](imagedevice/#constructor_4)(Stream) | Αρχικοποιεί μια νέα παρουσία της κλάσης `ImageDevice`. |
| [ImageDevice](imagedevice/#constructor_5)(String) | Αρχικοποιεί μια νέα παρουσία της κλάσης `ImageDevice`. |
| [ImageDevice](imagedevice/#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | Αρχικοποιεί μια νέα παρουσία της κλάσης `ImageDevice` με επιλογές απόδοσης και πάροχο ροής. |
| [ImageDevice](imagedevice/#constructor_2)(ImageRenderingOptions, Stream) | Αρχικοποιεί μια νέα παρουσία της κλάσης `ImageDevice` με επιλογές απόδοσης και ροή εξόδου. |
| [ImageDevice](imagedevice/#constructor_3)(ImageRenderingOptions, String) | Αρχικοποιεί μια νέα παρουσία της κλάσης `ImageDevice` με επιλογές απόδοσης και όνομα αρχείου εξόδου. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Μέθοδοι

| Όνομα | Περιγραφή |
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

## Άλλα μέλη

| Όνομα | Περιγραφή |
| --- | --- |
| class [ImageGraphicContext](../../com.aspose.html.rendering.image/imagedevice.imagegraphiccontext) | Κρατά τις τρέχουσες παραμέτρους ελέγχου γραφικών για το `ImageDevice`. Αυτές οι παράμετροι ορίζουν το παγκόσμιο πλαίσιο μέσα στο οποίο εκτελούνται οι τελεστές γραφικών. |

### Δείτε επίσης

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [ImageRenderingOptions](../imagerenderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
