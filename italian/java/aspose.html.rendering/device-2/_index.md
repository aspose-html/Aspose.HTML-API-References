---
title: "Classe DeviceTGraphicContextTRenderingOptions"
second_title: "Aspose.HTML per Java Riferimento API"
description: "classe com.aspose.html.rendering.Device2TGraphicContextTRenderingOptions. Rappresenta la classe base per l'implementazione di dispositivi di rendering particolari"
type: docs

url: /it/java/com.aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

Rappresenta la classe base per l'implementazione di dispositivi di rendering particolari.

```java
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Parametro | Descrizione |
| --- | --- |
| TGraphicContext | Contesto grafico che contiene i parametri di controllo grafico correnti |
| TRenderingOptions | Opzioni di rendering |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) Ottiene il contesto grafico |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) Ottiene le opzioni di rendering. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/device-2/addrect/)(RectangleF) | Aggiunge un rettangolo al percorso corrente come sotto-percorso completo. |
| [beginDocument](../../com.aspose.html.rendering/device-2/begindocument/)(Document) | Inizia il rendering del documento. |
| [beginElement](../../com.aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | Inizia il rendering del nodo. |
| [beginPage](../../com.aspose.html.rendering/device-2/beginpage/)(SizeF) | Inizia il rendering della nuova pagina. |
| [clip](../../com.aspose.html.rendering/device-2/clip/)(FillRule) | Modifica il percorso di ritaglio corrente intersecandolo con il percorso corrente, usando il FillRule per determinare la regione da riempire. Questo metodo termina il percorso corrente. |
| [closePath](../../com.aspose.html.rendering/device-2/closepath/)() | Chiude il sotto-percorso corrente aggiungendo un segmento di linea retta dal punto corrente al punto di partenza del sotto-percorso. Se il sotto-percorso corrente è già chiuso, "ClosePath" non fa nulla. Questo operatore termina il sotto-percorso corrente. Aggiungere un altro segmento al percorso corrente avvia un nuovo sotto-percorso, anche se il nuovo segmento inizia dal punto finale raggiunto dal metodo "ClosePath". |
| [cubicBezierTo](../../com.aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | Aggiunge una curva cubica Bézier al percorso corrente. La curva si estende dal punto corrente al punto pt2, usando pt1 e pt2 come punti di controllo Bézier. Il nuovo punto corrente è pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() | Esegue attività definite dall'applicazione associate al rilascio, alla liberazione o al reset di risorse non gestite. |
| [drawImage](../../com.aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) | Disegna l'immagine specificata. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() | Termina il rendering del documento. |
| [endElement](../../com.aspose.html.rendering/device-2/endelement/)(Element) | Termina il rendering del nodo. |
| [endPage](../../com.aspose.html.rendering/device-2/endpage/)() | Termina il rendering della pagina corrente. |
| [fill](../../com.aspose.html.rendering/device-2/fill/)(FillRule) | Riempie l'intera regione racchiusa dal percorso corrente. Se il percorso è composto da diversi sotto‑percorso disconnessi, riempie l'interno di tutti i sotto‑percorso, considerati insieme. Questo metodo termina il percorso corrente. |
| [fillText](../../com.aspose.html.rendering/device-2/filltext/)(String, PointF) | Riempie la stringa di testo specificata nella posizione specificata. |
| [flush](../../com.aspose.html.rendering/device-2/flush/)() | Svuota tutti i dati nello stream di output. |
| [lineTo](../../com.aspose.html.rendering/device-2/lineto/)(PointF) | Aggiunge un segmento di linea retta dal punto corrente al punto (pt). Il nuovo punto corrente è pt. |
| [moveTo](../../com.aspose.html.rendering/device-2/moveto/)(PointF) | Inizia un nuovo sotto‑percorso spostando il punto corrente alle coordinate del parametro pt, omettendo qualsiasi segmento di collegamento. Se il metodo di costruzione del percorso precedente nel percorso corrente era anche \"MoveTo\", il nuovo \"MoveTo\" lo sovrascrive; non rimane alcuna traccia dell'operazione \"MoveTo\" precedente nel percorso. |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() | Ripristina l'intero contesto grafico al suo valore precedente rimuovendolo dallo stack. |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() | Inserisce una copia dell'intero contesto grafico nello stack. |
| [stroke](../../com.aspose.html.rendering/device-2/stroke/)() | Traccia una linea lungo il percorso corrente. La linea tracciata segue ogni segmento rettilineo o curvo del percorso, centrata sul segmento con i lati paralleli ad esso. Ognuno dei sotto‑percorso del percorso è trattato separatamente. Questo metodo termina il percorso corrente. |
| [strokeAndFill](../../com.aspose.html.rendering/device-2/strokeandfill/)(FillRule) | Traccia e riempie il percorso corrente. Questo metodo termina il percorso corrente. |
| [strokeText](../../com.aspose.html.rendering/device-2/stroketext/)(String, PointF) | Traccia la stringa di testo specificata nella posizione specificata. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.deviceconfiguration-2) |  |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.pagewritingstrategy-2) | Specifica i tipi di strategie per scrivere le pagine in stream\streams. |

### Vedi anche

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
