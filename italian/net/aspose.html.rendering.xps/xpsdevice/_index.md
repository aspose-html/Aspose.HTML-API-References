---
title: Class XpsDevice
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Rendering.Xps.XpsDevice classe. Rappresenta il rendering in un documento xps.
type: docs
weight: 4530
url: /it/net/aspose.html.rendering.xps/xpsdevice/
---
## XpsDevice class

Rappresenta il rendering in un documento xps.

```csharp
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XpsDevice](xpsdevice/#constructor)(ICreateStreamProvider) | Inizializza una nuova istanza di`XpsDevice` classe. |
| [XpsDevice](xpsdevice/#constructor_4)(Stream) | Inizializza una nuova istanza di`XpsDevice` classe. |
| [XpsDevice](xpsdevice/#constructor_5)(string) | Inizializza una nuova istanza di`XpsDevice` classe. |
| [XpsDevice](xpsdevice/#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | Inizializza una nuova istanza di`XpsDevice` class in base alle opzioni di rendering e allo stream provider. |
| [XpsDevice](xpsdevice/#constructor_2)(XpsRenderingOptions, Stream) | Inizializza una nuova istanza di`XpsDevice`classe tramite opzioni di rendering e flusso di output. |
| [XpsDevice](xpsdevice/#constructor_3)(XpsRenderingOptions, string) | Inizializza una nuova istanza di`XpsDevice` class in base alle opzioni di rendering e al nome del file di output. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.xps/xpsdevice/addrect/)(RectangleF) | Aggiunge un rettangolo al percorso corrente come sottopercorso completo. |
| override [BeginDocument](../../aspose.html.rendering.xps/xpsdevice/begindocument/)(Document) | Inizia il rendering del documento. |
| override [BeginElement](../../aspose.html.rendering.xps/xpsdevice/beginelement/)(Element, RectangleF) | Inizia il rendering dell'elemento. |
| override [BeginPage](../../aspose.html.rendering.xps/xpsdevice/beginpage/)(SizeF) | Inizia il rendering della nuova pagina. |
| override [Clip](../../aspose.html.rendering.xps/xpsdevice/clip/)(FillMode) | Modifica il tracciato di ritaglio corrente intersecandolo con il tracciato corrente, utilizzando la regola FillMode per determinare l'area da riempire. Questo metodo termina il percorso corrente. |
| override [ClosePath](../../aspose.html.rendering.xps/xpsdevice/closepath/)() | Chiude il sottotracciato corrente aggiungendo un segmento di linea retta dal punto corrente al punto iniziale del sottotracciato. Se il sottopercorso corrente è già chiuso, "ClosePath" non fa nulla. Questo operatore termina il sottopercorso corrente. L'aggiunta di un altro segmento al percorso corrente inizia un nuovo sottopercorso, anche se il nuovo segmento inizia dall'endpoint raggiunto dal metodo "ClosePath". |
| override [CubicBezierTo](../../aspose.html.rendering.xps/xpsdevice/cubicbezierto/)(PointF, PointF, PointF) | Aggiunge una curva di Bézier cubica al percorso corrente. La curva si estende dal punto corrente al punto pt2, utilizzando pt1 e pt2 come punti di controllo Bézier. Il nuovo punto corrente è pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.xps/xpsdevice/drawimage/)(byte[], ImageType, RectangleF) | Disegna l'immagine specificata. |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() |  |
| override [EndElement](../../aspose.html.rendering.xps/xpsdevice/endelement/)(Element) | Termina il rendering dell'elemento. |
| override [EndPage](../../aspose.html.rendering.xps/xpsdevice/endpage/)() | Termina il rendering della pagina corrente. |
| override [Fill](../../aspose.html.rendering.xps/xpsdevice/fill/)(FillMode) | Riempie l'intera regione racchiusa dal percorso corrente. Se il percorso è costituito da diversi sottopercorsi disconnessi, riempie l'interno di tutti i sottopercorsi, considerati insieme. Questo metodo termina il percorso corrente. |
| override [FillText](../../aspose.html.rendering.xps/xpsdevice/filltext/)(string, PointF) | Riempie la stringa di testo specificata nella posizione specificata. |
| override [Flush](../../aspose.html.rendering.xps/xpsdevice/flush/)() | Scarica tutti i dati nel flusso di output. |
| override [LineTo](../../aspose.html.rendering.xps/xpsdevice/lineto/)(PointF) | Aggiunge un segmento di linea retta dal punto corrente al punto (pt). Il nuovo punto corrente è pt. |
| override [MoveTo](../../aspose.html.rendering.xps/xpsdevice/moveto/)(PointF) | Inizia un nuovo sottotracciato spostando il punto corrente alle coordinate del parametro pt, omettendo qualsiasi segmento di linea di collegamento. Se anche il precedente metodo di costruzione del percorso nel percorso corrente era "MoveTo", il nuovo "MoveTo" lo sovrascrive; nessuna traccia della precedente operazione "Sposta su" rimane nel percorso. |
| override [RestoreGraphicContext](../../aspose.html.rendering.xps/xpsdevice/restoregraphiccontext/)() | Ripristina l'intero contesto grafico al suo valore precedente estraendolo dallo stack. |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| override [Stroke](../../aspose.html.rendering.xps/xpsdevice/stroke/)() | Traccia una linea lungo il percorso corrente. La linea tracciata segue ogni segmento rettilineo o curvo nel percorso, centrato sul segmento con i lati paralleli ad esso. Ciascun sottopercorso del percorso viene trattato separatamente. Questo metodo termina il percorso corrente. |
| override [StrokeAndFill](../../aspose.html.rendering.xps/xpsdevice/strokeandfill/)(FillMode) | Traccia e riempie il percorso corrente. Questo metodo termina il percorso corrente. |
| override [StrokeText](../../aspose.html.rendering.xps/xpsdevice/stroketext/)(string, PointF) | Accarezza la stringa di testo specificata nella posizione specificata. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [XpsGraphicContext](xpsdevice.xpsgraphiccontext/) | Contiene i parametri di controllo della grafica correnti per XpsDevice. Questi parametri definiscono il framework globale all'interno del quale vengono eseguiti gli operatori grafici. |

### Guarda anche

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext/)
* class [XpsRenderingOptions](../xpsrenderingoptions/)
* spazio dei nomi [Aspose.Html.Rendering.Xps](../../aspose.html.rendering.xps/)
* assemblea [Aspose.HTML](../../)


