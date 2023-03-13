---
title: Interface ICanvasRenderingContext2D
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Canvas.ICanvasRenderingContext2D interfaccia. Linterfaccia ICanvasRenderingContext2D viene utilizzata per disegnare rettangoli testo immagini e altri oggetti sullelemento canvas. Fornisce il contesto di rendering 2D per la superficie di disegno di un elemento canvas.
type: docs
weight: 260
url: /it/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

L'interfaccia ICanvasRenderingContext2D viene utilizzata per disegnare rettangoli, testo, immagini e altri oggetti sull'elemento canvas. Fornisce il contesto di rendering 2D per la superficie di disegno di un elemento canvas.

```csharp
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Canvas](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) { get; } | Un riferimento a ritroso di sola lettura a HTMLCanvasElement. Potrebbe essere null se non è associato a un elemento canvas. |
| [FillStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillstyle/) { get; set; } | Colore o stile da utilizzare all'interno delle forme. Predefinito: (nero). |
| [GlobalAlpha](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalalpha/) { get; set; } | Valore alfa applicato a forme e immagini prima che vengano composte nell'area di disegno. Predefinito 1.0 (opaco). |
| [GlobalCompositeOperation](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalcompositeoperation/) { get; set; } | Con globalAlpha applicato, imposta il modo in cui le forme e le immagini vengono disegnate sulla bitmap esistente. Predefinito: (source-over) |
| [ImageSmoothingEnabled](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/imagesmoothingenabled/) { get; set; } | Modalità levigatura immagine; se disabilitato, le immagini non verranno uniformate se ridimensionate. |
| [ShadowBlur](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowblur/) { get; set; } | Specifica l'effetto di sfocatura. Predefinito 0 |
| [ShadowColor](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowcolor/) { get; set; } | Colore dell'ombra. Predefinito nero completamente trasparente. |
| [ShadowOffsetX](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsetx/) { get; set; } | Distanza orizzontale in cui l'ombra verrà sfalsata. Predefinito 0. |
| [ShadowOffsetY](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsety/) { get; set; } | Distanza verticale in cui l'ombra verrà sfalsata. Predefinito 0. |
| [StrokeStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokestyle/) { get; set; } | Colore o stile da utilizzare per le linee attorno alle forme. Predefinito: (nero). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;string, string&gt;) | Aggiunge un'area attiva all'area di disegno. Ciò ti consente di semplificare il rilevamento dei colpi, ti consente di indirizzare gli eventi agli elementi DOM, e consente agli utenti di esplorare la tela senza vederla. |
| [BeginPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | Inizia un nuovo percorso svuotando l'elenco dei sottopercorsi. Chiama questo metodo quando vuoi creare un nuovo percorso. |
| [ClearHitRegions](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | Rimuove tutte le aree interessate dall'area di disegno. |
| [ClearRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | Imposta tutti i pixel nel rettangolo definito dal punto iniziale (x, y) e dalle dimensioni (larghezza, altezza) su nero trasparente, cancellando qualsiasi contenuto precedentemente disegnato. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | Crea una nuova area di ritaglio calcolando l'intersezione dell'area di ritaglio corrente e dell'area descritta dal tracciato, utilizzando la regola del numero di avvolgimento diverso da zero. I sottotracciati aperti devono essere implicitamente chiusi durante il calcolo dell'area di ritaglio, senza influire sui sottotracciati effettivi . La nuova area di ritaglio sostituisce l'attuale area di ritaglio. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | Crea una nuova area di ritaglio calcolando l'intersezione dell'area di ritaglio corrente e dell'area descritta dal percorso, utilizzando la regola del numero di avvolgimento diverso da zero. I sottotracciati aperti devono essere chiusi implicitamente durante il calcolo dell'area di ritaglio, senza influire sui sottotracciati effettivi. La nuova area di ritaglio sostituisce l'attuale area di ritaglio. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | Crea una nuova area di ritaglio calcolando l'intersezione dell'area di ritaglio corrente e dell'area descritta dal percorso, utilizzando la regola del numero di avvolgimento diverso da zero. I sottotracciati aperti devono essere chiusi implicitamente durante il calcolo dell'area di ritaglio, senza influire sui sottotracciati effettivi. La nuova area di ritaglio sostituisce l'attuale area di ritaglio. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | Crea un nuovo oggetto ImageData vuoto con le dimensioni specificate. Tutti i pixel nel nuovo oggetto sono neri trasparenti. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | Crea un nuovo oggetto ImageData vuoto con le dimensioni specificate. Tutti i pixel nel nuovo oggetto sono neri trasparenti. |
| [CreateLinearGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | Crea un gradiente lineare lungo la linea data dalle coordinate rappresentate dai parametri. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, string) | Crea un motivo utilizzando l'immagine specificata (un CanvasImageSource). Ripete la sorgente nelle direzioni specificate dall'argomento di ripetizione. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, string) | Crea un motivo utilizzando l'immagine specificata (un CanvasImageSource). Ripete la sorgente nelle direzioni specificate dall'argomento di ripetizione. |
| [CreateRadialGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | Crea un gradiente radiale dato dalle coordinate dei due cerchi rappresentati dai parametri. |
| [DrawFocusIfNeeded](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | Se un dato elemento è focalizzato, questo metodo disegna un anello di messa a fuoco attorno al percorso corrente. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | Disegna l'immagine specificata. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | Disegna l'immagine specificata. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | Disegna l'immagine specificata. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | Disegna l'immagine specificata. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Disegna l'immagine specificata. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | Disegna l'immagine specificata. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | Riempie i sottotracciati con lo stile di riempimento corrente e l'algoritmo predefinito CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | Riempie i sottotracciati con lo stile di riempimento corrente. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | Riempie i sottotracciati con lo stile di riempimento corrente e l'algoritmo predefinito CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | Riempie i sottotracciati con lo stile di riempimento corrente. |
| [FillRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | Disegna un rettangolo pieno in posizione (x, y) la cui dimensione è determinata da larghezza e altezza. |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(string, double, double) | Disegna (riempie) un dato testo nella posizione data (x,y). |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(string, double, double, double) | Disegna (riempie) un dato testo nella posizione data (x,y). |
| [GetImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | Restituisce un oggetto ImageData che rappresenta i dati dei pixel sottostanti per l'area della tela indicata dal rettangolo che inizia a (sx, sy) e ha una larghezza sw e un'altezza sh. Questo metodo non è influenzato dalla matrice di trasformazione della tela. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | Riporta se il punto specificato è contenuto o meno nel percorso corrente. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | Riporta se il punto specificato è contenuto o meno nel percorso corrente. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | Riporta se il punto specificato è contenuto o meno nel percorso corrente. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | Riporta se il punto specificato è contenuto o meno nel percorso corrente. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | Riporta se il punto specificato si trova o meno all'interno dell'area contenuta dalla tracciatura di un tracciato. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | Riporta se il punto specificato si trova o meno all'interno dell'area contenuta dalla tracciatura di un tracciato. |
| [MeasureText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(string) | Restituisce un oggetto TextMetrics. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | Dipinge i dati dall'oggetto ImageData specificato sulla bitmap. Se viene fornito un rettangolo sporco, vengono dipinti solo i pixel di quel rettangolo. Questo metodo non è influenzato dalla matrice di trasformazione della tela. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | Dipinge i dati dall'oggetto ImageData specificato sulla bitmap. Se viene fornito un rettangolo sporco, vengono dipinti solo i pixel di quel rettangolo. Questo metodo non è influenzato dalla matrice di trasformazione della tela. |
| [RemoveHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(string) | Rimuove la regione colpita con l'ID specificato dall'area di disegno. |
| [ResetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | Reimposta la trasformazione corrente mediante la matrice identità. |
| [Restore](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | Ripristina lo stato dello stile di disegno sull'ultimo elemento nello 'state stack' salvato da save(). |
| [Rotate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | Aggiunge una rotazione alla matrice di trasformazione. L'argomento angolo rappresenta un angolo di rotazione in senso orario ed è espresso in radianti. |
| [Save](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | Salva lo stato dello stile di disegno corrente utilizzando uno stack in modo da poter ripristinare qualsiasi modifica apportata utilizzando restore(). |
| [Scale](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | Aggiunge una trasformazione di ridimensionamento alle unità della tela di x orizzontalmente e di y verticalmente. |
| [SetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | Reimposta la trasformazione corrente sulla matrice identità, quindi richiama il metodo transform() con gli stessi argomenti. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | Traccia i sottotracciati con lo stile di tratto corrente. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | Traccia i sottotracciati con lo stile di tratto corrente. |
| [StrokeRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | Disegna un rettangolo che ha un punto iniziale in (x, y) e ha una larghezza w e un'altezza h sulla tela, usando lo stile di tratto corrente. |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(string, double, double) | Disegna (tratti) un dato testo nella posizione data (x, y). |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(string, double, double, double?) | Disegna (tratti) un dato testo nella posizione data (x, y). |
| [Transform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | Moltiplica la matrice di trasformazione corrente per la matrice descritta dai suoi argomenti. |
| [Translate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | Aggiunge una trasformazione di traduzione spostando la tela e la sua origine x orizzontalmente e y verticalmente sulla griglia. |

### Guarda anche

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* spazio dei nomi [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* assemblea [Aspose.HTML](../../)


