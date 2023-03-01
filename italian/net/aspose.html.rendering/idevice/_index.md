---
title: Interface IDevice
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Rendering.IDevice interfaccia. Definisce metodi e proprietà che supportano il rendering personalizzato degli elementi grafici come percorsi testo e immagini.
type: docs
weight: 4280
url: /it/net/aspose.html.rendering/idevice/
---
## IDevice interface

Definisce metodi e proprietà che supportano il rendering personalizzato degli elementi grafici come percorsi, testo e immagini.

```csharp
public interface IDevice : IDisposable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/idevice/graphiccontext/) { get; } | Ottiene il contesto grafico. |
| [Options](../../aspose.html.rendering/idevice/options/) { get; } | Ottiene le opzioni di rendering. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddRect](../../aspose.html.rendering/idevice/addrect/)(RectangleF) | Aggiunge un rettangolo al percorso corrente come sottopercorso completo. |
| [BeginDocument](../../aspose.html.rendering/idevice/begindocument/)(Document) | Inizia il rendering del documento. |
| [BeginElement](../../aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | Inizia il rendering dell'elemento. |
| [BeginPage](../../aspose.html.rendering/idevice/beginpage/)(SizeF) | Inizia il rendering della nuova pagina. |
| [Clip](../../aspose.html.rendering/idevice/clip/)(FillMode) | Modifica il tracciato di ritaglio corrente intersecandolo con il tracciato corrente, utilizzando la regola FillMode per determinare l'area da riempire. Questo metodo termina il percorso corrente. |
| [ClosePath](../../aspose.html.rendering/idevice/closepath/)() | Chiude il sottotracciato corrente aggiungendo un segmento di linea retta dal punto corrente al punto iniziale del sottotracciato. Se il sottopercorso corrente è già chiuso, "ClosePath" non fa nulla. Questo operatore termina il sottopercorso corrente. L'aggiunta di un altro segmento al percorso corrente inizia un nuovo sottopercorso, anche se il nuovo segmento inizia dall'endpoint raggiunto dal metodo "ClosePath". |
| [CubicBezierTo](../../aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | Aggiunge una curva di Bézier cubica al percorso corrente. La curva si estende dal punto corrente al punto pt3, utilizzando pt1 e pt2 come punti di controllo Bézier. Il nuovo punto corrente è pt3. |
| [DrawImage](../../aspose.html.rendering/idevice/drawimage/)(byte[], ImageType, RectangleF) | Disegna l'immagine specificata. |
| [EndDocument](../../aspose.html.rendering/idevice/enddocument/)() | Termina il rendering del documento. |
| [EndElement](../../aspose.html.rendering/idevice/endelement/)(Element) | Termina il rendering dell'elemento. |
| [EndPage](../../aspose.html.rendering/idevice/endpage/)() | Termina il rendering della pagina corrente. |
| [Fill](../../aspose.html.rendering/idevice/fill/)(FillMode) | Riempie l'intera regione racchiusa dal percorso corrente. Se il percorso è costituito da diversi sottopercorsi disconnessi, riempie l'interno di tutti i sottopercorsi, considerati insieme. Questo metodo termina il percorso corrente. |
| [FillText](../../aspose.html.rendering/idevice/filltext/)(string, PointF) | Riempie la stringa di testo specificata nella posizione specificata. |
| [Flush](../../aspose.html.rendering/idevice/flush/)() | Scarica tutti i dati nel flusso di output. |
| [LineTo](../../aspose.html.rendering/idevice/lineto/)(PointF) | Aggiunge un segmento di linea retta dal punto corrente al punto (pt). Il nuovo punto corrente è pt. |
| [MoveTo](../../aspose.html.rendering/idevice/moveto/)(PointF) | Inizia un nuovo sottotracciato spostando il punto corrente alle coordinate del parametro pt, omettendo qualsiasi segmento di linea di collegamento. Se anche il precedente metodo di costruzione del percorso nel percorso corrente era "MoveTo", il nuovo "MoveTo" lo sovrascrive; nessuna traccia della precedente operazione "Sposta su" rimane nel percorso. |
| [RestoreGraphicContext](../../aspose.html.rendering/idevice/restoregraphiccontext/)() | Ripristina l'intero contesto grafico al suo valore precedente estraendolo dallo stack. |
| [SaveGraphicContext](../../aspose.html.rendering/idevice/savegraphiccontext/)() | Inserisce una copia dell'intero contesto grafico nello stack. |
| [Stroke](../../aspose.html.rendering/idevice/stroke/)() | Traccia una linea lungo il percorso corrente. La linea tracciata segue ogni segmento rettilineo o curvo nel percorso, centrato sul segmento con i lati paralleli ad esso. Ciascun sottopercorso del percorso viene trattato separatamente. Questo metodo termina il percorso corrente. |
| [StrokeAndFill](../../aspose.html.rendering/idevice/strokeandfill/)(FillMode) | Traccia e riempie il percorso corrente. Questo metodo termina il percorso corrente. |
| [StrokeText](../../aspose.html.rendering/idevice/stroketext/)(string, PointF) | Accarezza la stringa di testo specificata nella posizione specificata. |

### Guarda anche

* spazio dei nomi [Aspose.Html.Rendering](../../aspose.html.rendering/)
* assemblea [Aspose.HTML](../../)


