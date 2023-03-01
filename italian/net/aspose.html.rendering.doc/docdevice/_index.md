---
title: Class DocDevice
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Rendering.Doc.DocDevice classe. Rappresenta il rendering in un documento DOCX.
type: docs
weight: 4170
url: /it/net/aspose.html.rendering.doc/docdevice/
---
## DocDevice class

Rappresenta il rendering in un documento DOCX.

```csharp
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | Inizializza una nuova istanza di`DocDevice` classe. |
| [DocDevice](docdevice/#constructor_4)(Stream) | Inizializza una nuova istanza di`DocDevice` classe per flusso di output. |
| [DocDevice](docdevice/#constructor_5)(string) | Inizializza una nuova istanza di`DocDevice` classe per nome file di output. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | Inizializza una nuova istanza di`DocDevice` class in base alle opzioni di rendering e allo stream provider. |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | Inizializza una nuova istanza di`DocDevice` class tramite le opzioni di rendering e il flusso di output. |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, string) | Inizializza una nuova istanza di`DocDevice` class in base alle opzioni di rendering e al nome del file di output. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | Aggiunge un rettangolo al percorso corrente come sottopercorso completo. |
| override [BeginDocument](../../aspose.html.rendering.doc/docdevice/begindocument/)(Document) | Inizia il rendering del documento. |
| override [BeginElement](../../aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | Inizia il rendering del nodo html. |
| override [BeginPage](../../aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | Inizia il rendering della nuova pagina. |
| override [Clip](../../aspose.html.rendering.doc/docdevice/clip/)(FillMode) | Modifica il tracciato di ritaglio corrente intersecandolo con il tracciato corrente, utilizzando la regola FillMode per determinare l'area da riempire. Questo metodo termina il percorso corrente. |
| override [ClosePath](../../aspose.html.rendering.doc/docdevice/closepath/)() | Chiude il sottotracciato corrente aggiungendo un segmento di linea retta dal punto corrente al punto iniziale del sottotracciato. Se il sottopercorso corrente è già chiuso, "ClosePath" non fa nulla. Questo operatore termina il sottopercorso corrente. L'aggiunta di un altro segmento al percorso corrente inizia un nuovo sottopercorso, anche se il nuovo segmento inizia dall'endpoint raggiunto dal metodo "ClosePath". |
| override [CubicBezierTo](../../aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | Aggiunge una curva di Bézier cubica al percorso corrente. La curva si estende dal punto corrente al punto pt2, utilizzando pt1 e pt2 come punti di controllo Bézier. Il nuovo punto corrente è pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.doc/docdevice/drawimage/)(byte[], ImageType, RectangleF) | Disegna l'immagine specificata. |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() |  |
| override [EndElement](../../aspose.html.rendering.doc/docdevice/endelement/)(Element) | Termina il rendering del nodo html. |
| override [EndPage](../../aspose.html.rendering.doc/docdevice/endpage/)() | Termina il rendering della pagina corrente. |
| override [Fill](../../aspose.html.rendering.doc/docdevice/fill/)(FillMode) | Riempie l'intera regione racchiusa dal percorso corrente. Se il percorso è costituito da diversi sottopercorsi disconnessi, riempie l'interno di tutti i sottopercorsi, considerati insieme. Questo metodo termina il percorso corrente. |
| override [FillText](../../aspose.html.rendering.doc/docdevice/filltext/)(string, PointF) | Riempie la stringa di testo specificata nella posizione specificata. |
| override [Flush](../../aspose.html.rendering.doc/docdevice/flush/)() | Scarica tutti i dati nel flusso di output. |
| override [LineTo](../../aspose.html.rendering.doc/docdevice/lineto/)(PointF) | Aggiunge un segmento di linea retta dal punto corrente al punto (pt). Il nuovo punto corrente è pt. |
| override [MoveTo](../../aspose.html.rendering.doc/docdevice/moveto/)(PointF) | Inizia un nuovo sottotracciato spostando il punto corrente alle coordinate del parametro pt, omettendo qualsiasi segmento di linea di collegamento. Se anche il precedente metodo di costruzione del percorso nel percorso corrente era "MoveTo", il nuovo "MoveTo" lo sovrascrive; nessuna traccia della precedente operazione "Sposta su" rimane nel percorso. |
| override [RestoreGraphicContext](../../aspose.html.rendering.doc/docdevice/restoregraphiccontext/)() | Ripristina l'intero contesto grafico al suo valore precedente estraendolo dallo stack. |
| override [SaveGraphicContext](../../aspose.html.rendering.doc/docdevice/savegraphiccontext/)() | Inserisce una copia dell'intero contesto grafico nello stack. |
| override [Stroke](../../aspose.html.rendering.doc/docdevice/stroke/)() | Traccia una linea lungo il percorso corrente. La linea tracciata segue ogni segmento rettilineo o curvo nel percorso, centrato sul segmento con i lati paralleli ad esso. Ciascun sottopercorso del percorso viene trattato separatamente. Questo metodo termina il percorso corrente. |
| override [StrokeAndFill](../../aspose.html.rendering.doc/docdevice/strokeandfill/)(FillMode) | Traccia e riempie il percorso corrente. Questo metodo termina il percorso corrente. |
| override [StrokeText](../../aspose.html.rendering.doc/docdevice/stroketext/)(string, PointF) | Accarezza la stringa di testo specificata nella posizione specificata. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [DocGraphicContext](docdevice.docgraphiccontext/) | Contiene i parametri di controllo della grafica correnti per DocDevice. Questi parametri definiscono la struttura globale all'interno della quale vengono eseguiti gli operatori grafici. |

### Guarda anche

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* spazio dei nomi [Aspose.Html.Rendering.Doc](../../aspose.html.rendering.doc/)
* assemblea [Aspose.HTML](../../)


