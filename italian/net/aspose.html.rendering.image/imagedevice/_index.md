---
title: Class ImageDevice
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Rendering.Image.ImageDevice classe. Rappresenta il rendering nei formati raster jpeg png bmp gif tiff.
type: docs
weight: 4300
url: /it/net/aspose.html.rendering.image/imagedevice/
---
## ImageDevice class

Rappresenta il rendering nei formati raster: jpeg, png, bmp, gif, tiff.

```csharp
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)(ICreateStreamProvider) | Inizializza una nuova istanza di`ImageDevice` classe. |
| [ImageDevice](imagedevice/#constructor_4)(Stream) | Inizializza una nuova istanza di`ImageDevice` classe. |
| [ImageDevice](imagedevice/#constructor_5)(string) | Inizializza una nuova istanza di`ImageDevice` classe. |
| [ImageDevice](imagedevice/#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | Inizializza una nuova istanza di`ImageDevice` class in base alle opzioni di rendering e allo stream provider. |
| [ImageDevice](imagedevice/#constructor_2)(ImageRenderingOptions, Stream) | Inizializza una nuova istanza di`ImageDevice`classe tramite opzioni di rendering e flusso di output. |
| [ImageDevice](imagedevice/#constructor_3)(ImageRenderingOptions, string) | Inizializza una nuova istanza di`ImageDevice` class in base alle opzioni di rendering e al nome del file di output. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| virtual [Graphics](../../aspose.html.rendering.image/imagedevice/graphics/) { get; } | Ottiene l'istanza di Graphics. |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.image/imagedevice/addrect/)(RectangleF) | Aggiunge un rettangolo al percorso corrente come sottopercorso completo. |
| override [BeginDocument](../../aspose.html.rendering.image/imagedevice/begindocument/)(Document) | Inizia il rendering del documento. |
| override [BeginElement](../../aspose.html.rendering.image/imagedevice/beginelement/)(Element, RectangleF) | Inizia il rendering dell'elemento. |
| override [BeginPage](../../aspose.html.rendering.image/imagedevice/beginpage/)(SizeF) | Inizia il rendering della nuova pagina. |
| override [Clip](../../aspose.html.rendering.image/imagedevice/clip/)(FillMode) | Modifica il tracciato di ritaglio corrente intersecandolo con il tracciato corrente, utilizzando la regola FillMode per determinare l'area da riempire. Questo metodo termina il percorso corrente. |
| override [ClosePath](../../aspose.html.rendering.image/imagedevice/closepath/)() | Chiude il sottotracciato corrente aggiungendo un segmento di linea retta dal punto corrente al punto iniziale del sottotracciato. Se il sottopercorso corrente è già chiuso, "ClosePath" non fa nulla. Questo operatore termina il sottopercorso corrente. L'aggiunta di un altro segmento al percorso corrente inizia un nuovo sottopercorso, anche se il nuovo segmento inizia dall'endpoint raggiunto dal metodo "ClosePath". |
| override [CubicBezierTo](../../aspose.html.rendering.image/imagedevice/cubicbezierto/)(PointF, PointF, PointF) | Aggiunge una curva di Bézier cubica al percorso corrente. La curva si estende dal punto corrente al punto pt2, utilizzando pt1 e pt2 come punti di controllo Bézier. Il nuovo punto corrente è pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.image/imagedevice/drawimage/)(byte[], ImageType, RectangleF) | Disegna l'immagine specificata. |
| override [EndDocument](../../aspose.html.rendering.image/imagedevice/enddocument/)() | Termina il rendering del documento. |
| override [EndElement](../../aspose.html.rendering.image/imagedevice/endelement/)(Element) | Termina il rendering dell'elemento. |
| override [EndPage](../../aspose.html.rendering.image/imagedevice/endpage/)() | Termina il rendering della pagina corrente. |
| override [Fill](../../aspose.html.rendering.image/imagedevice/fill/)(FillMode) | Riempie l'intera regione racchiusa dal percorso corrente. Se il percorso è costituito da diversi sottopercorsi disconnessi, riempie l'interno di tutti i sottopercorsi, considerati insieme. Questo metodo termina il percorso corrente. |
| override [FillText](../../aspose.html.rendering.image/imagedevice/filltext/)(string, PointF) | Riempie la stringa di testo specificata nella posizione specificata. |
| override [Flush](../../aspose.html.rendering.image/imagedevice/flush/)() | Scarica tutti i dati nel flusso di output. |
| override [LineTo](../../aspose.html.rendering.image/imagedevice/lineto/)(PointF) | Aggiunge un segmento di linea retta dal punto corrente al punto (pt). Il nuovo punto corrente è pt. |
| override [MoveTo](../../aspose.html.rendering.image/imagedevice/moveto/)(PointF) | Inizia un nuovo sottotracciato spostando il punto corrente alle coordinate del parametro pt, omettendo qualsiasi segmento di linea di collegamento. Se anche il precedente metodo di costruzione del percorso nel percorso corrente era "MoveTo", il nuovo "MoveTo" lo sovrascrive; nessuna traccia della precedente operazione "Sposta su" rimane nel percorso. |
| override [RestoreGraphicContext](../../aspose.html.rendering.image/imagedevice/restoregraphiccontext/)() | Ripristina l'intero contesto grafico al suo valore precedente estraendolo dallo stack. |
| override [SaveGraphicContext](../../aspose.html.rendering.image/imagedevice/savegraphiccontext/)() | Inserisce una copia dell'intero contesto grafico nello stack. |
| override [Stroke](../../aspose.html.rendering.image/imagedevice/stroke/)() | Traccia una linea lungo il percorso corrente. La linea tracciata segue ogni segmento rettilineo o curvo nel percorso, centrato sul segmento con i lati paralleli ad esso. Ciascun sottopercorso del percorso viene trattato separatamente. Questo metodo termina il percorso corrente. |
| override [StrokeAndFill](../../aspose.html.rendering.image/imagedevice/strokeandfill/)(FillMode) | Traccia e riempie il percorso corrente. Questo metodo termina il percorso corrente. |
| override [StrokeText](../../aspose.html.rendering.image/imagedevice/stroketext/)(string, PointF) | Accarezza la stringa di testo specificata nella posizione specificata. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [ImageGraphicContext](imagedevice.imagegraphiccontext/) | Contiene i parametri di controllo della grafica correnti per il file`ImageDevice` . Questi parametri definiscono il framework globale all'interno del quale vengono eseguiti gli operatori grafici. |

### Guarda anche

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [ImageRenderingOptions](../imagerenderingoptions/)
* spazio dei nomi [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* assemblea [Aspose.HTML](../../)


