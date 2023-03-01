---
title: Class DeviceTGraphicContextTRenderingOptions
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Rendering.Device2TGraphicContextTRenderingOptions classe. Rappresenta la classe base per limplementazione di particolari dispositivi di rendering.
type: docs
weight: 4140
url: /it/net/aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

Rappresenta la classe base per l'implementazione di particolari dispositivi di rendering.

```csharp
public abstract class Device<TGraphicContext, TRenderingOptions> : IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Parametro | Descrizione |
| --- | --- |
| TGraphicContext | Contesto grafico che contiene i parametri di controllo della grafica correnti |
| TRenderingOptions | Opzioni di rendering |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } | Ottiene il contesto grafico |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } | Ottiene le opzioni di rendering. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| abstract [AddRect](../../aspose.html.rendering/device-2/addrect/)(RectangleF) | Aggiunge un rettangolo al percorso corrente come sottopercorso completo. |
| virtual [BeginDocument](../../aspose.html.rendering/device-2/begindocument/)(Document) | Inizia il rendering del documento. |
| abstract [BeginElement](../../aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | Inizia il rendering del nodo. |
| virtual [BeginPage](../../aspose.html.rendering/device-2/beginpage/)(SizeF) | Inizia il rendering della nuova pagina. |
| abstract [Clip](../../aspose.html.rendering/device-2/clip/)(FillMode) | Modifica il tracciato di ritaglio corrente intersecandolo con il tracciato corrente, utilizzando la regola FillMode per determinare l'area da riempire. Questo metodo termina il percorso corrente. |
| abstract [ClosePath](../../aspose.html.rendering/device-2/closepath/)() | Chiude il sottotracciato corrente aggiungendo un segmento di linea retta dal punto corrente al punto iniziale del sottotracciato. Se il sottopercorso corrente è già chiuso, "ClosePath" non fa nulla. Questo operatore termina il sottopercorso corrente. L'aggiunta di un altro segmento al percorso corrente inizia un nuovo sottopercorso, anche se il nuovo segmento inizia dall'endpoint raggiunto dal metodo "ClosePath". |
| abstract [CubicBezierTo](../../aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | Aggiunge una curva di Bézier cubica al percorso corrente. La curva si estende dal punto corrente al punto pt2, utilizzando pt1 e pt2 come punti di controllo Bézier. Il nuovo punto corrente è pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() | Esegue attività definite dall'applicazione associate alla liberazione, al rilascio o al ripristino di risorse non gestite. |
| abstract [DrawImage](../../aspose.html.rendering/device-2/drawimage/)(byte[], ImageType, RectangleF) | Disegna l'immagine specificata. |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() | Termina il rendering del documento. |
| abstract [EndElement](../../aspose.html.rendering/device-2/endelement/)(Element) | Termina il rendering del nodo. |
| virtual [EndPage](../../aspose.html.rendering/device-2/endpage/)() | Termina il rendering della pagina corrente. |
| abstract [Fill](../../aspose.html.rendering/device-2/fill/)(FillMode) | Riempie l'intera regione racchiusa dal percorso corrente. Se il percorso è costituito da diversi sottopercorsi disconnessi, riempie l'interno di tutti i sottopercorsi, considerati insieme. Questo metodo termina il percorso corrente. |
| abstract [FillText](../../aspose.html.rendering/device-2/filltext/)(string, PointF) | Riempie la stringa di testo specificata nella posizione specificata. |
| virtual [Flush](../../aspose.html.rendering/device-2/flush/)() | Scarica tutti i dati nel flusso di output. |
| abstract [LineTo](../../aspose.html.rendering/device-2/lineto/)(PointF) | Aggiunge un segmento di linea retta dal punto corrente al punto (pt). Il nuovo punto corrente è pt. |
| abstract [MoveTo](../../aspose.html.rendering/device-2/moveto/)(PointF) | Inizia un nuovo sottotracciato spostando il punto corrente alle coordinate del parametro pt, omettendo qualsiasi segmento di linea di collegamento. Se anche il precedente metodo di costruzione del percorso nel percorso corrente era "MoveTo", il nuovo "MoveTo" lo sovrascrive; nessuna traccia della precedente operazione "Sposta su" rimane nel percorso. |
| virtual [RestoreGraphicContext](../../aspose.html.rendering/device-2/restoregraphiccontext/)() | Ripristina l'intero contesto grafico al suo valore precedente estraendolo dallo stack. |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device-2/savegraphiccontext/)() | Inserisce una copia dell'intero contesto grafico nello stack. |
| abstract [Stroke](../../aspose.html.rendering/device-2/stroke/)() | Traccia una linea lungo il percorso corrente. La linea tracciata segue ogni segmento rettilineo o curvo nel percorso, centrato sul segmento con i lati paralleli ad esso. Ciascun sottopercorso del percorso viene trattato separatamente. Questo metodo termina il percorso corrente. |
| abstract [StrokeAndFill](../../aspose.html.rendering/device-2/strokeandfill/)(FillMode) | Traccia e riempie il percorso corrente. Questo metodo termina il percorso corrente. |
| abstract [StrokeText](../../aspose.html.rendering/device-2/stroketext/)(string, PointF) | Accarezza la stringa di testo specificata nella posizione specificata. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](device-2.deviceconfiguration-2/) | Rappresenta l'oggetto di configurazione per i dispositivi. |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](device-2.pagewritingstrategy-2/) | Specifica i tipi di strategie per la scrittura delle pagine nel flusso di output\stream. |

### Guarda anche

* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* spazio dei nomi [Aspose.Html.Rendering](../../aspose.html.rendering/)
* assemblea [Aspose.HTML](../../)


