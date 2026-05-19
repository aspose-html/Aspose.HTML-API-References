---
title: "Classe XpsDevice"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.rendering.xps.XpsDevice. Rappresenta il rendering verso un documento xps"
type: docs

url: /it/java/com.aspose.html.rendering.xps/xpsdevice/
---
## XpsDevice class

Rappresenta il rendering verso un documento xps.

```java
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XpsDevice](xpsdevice/#constructor)(ICreateStreamProvider) | Inizializza una nuova istanza della classe `XpsDevice`. |
| [XpsDevice](xpsdevice/#constructor_4)(Stream) | Inizializza una nuova istanza della classe `XpsDevice`. |
| [XpsDevice](xpsdevice/#constructor_5)(String) | Inizializza una nuova istanza della classe `XpsDevice`. |
| [XpsDevice](xpsdevice/#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | Inizializza una nuova istanza della classe `XpsDevice` mediante opzioni di rendering e provider di stream. |
| [XpsDevice](xpsdevice/#constructor_2)(XpsRenderingOptions, Stream) | Inizializza una nuova istanza della classe `XpsDevice` mediante opzioni di rendering e stream di output. |
| [XpsDevice](xpsdevice/#constructor_3)(XpsRenderingOptions, String) | Inizializza una nuova istanza della classe `XpsDevice` mediante opzioni di rendering e nome file di output. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Metodi

| Nome | Descrizione |
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

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [XpsGraphicContext](../../com.aspose.html.rendering.xps/xpsdevice.xpsgraphiccontext) | Contiene i parametri di controllo grafico attuali per l'XpsDevice. Questi parametri definiscono il framework globale entro il quale gli operatori grafici vengono eseguiti. |

### Vedi anche

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext/)
* class [XpsRenderingOptions](../xpsrenderingoptions/)
* package [com.aspose.html.rendering.xps](../../com.aspose.html.rendering.xps/)
* package [Aspose.HTML](../../)
