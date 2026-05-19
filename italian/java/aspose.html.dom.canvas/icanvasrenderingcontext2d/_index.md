---
title: "Interfaccia ICanvasRenderingContext2D"
second_title: "Riferimento API Aspose.HTML per Java"
description: "interfaccia com.aspose.html.dom.canvas.ICanvasRenderingContext2D. L'interfaccia ICanvasRenderingContext2D è usata per disegnare rettangoli, testo, immagini e altri oggetti sull'elemento canvas. Fornisce il contesto di rendering 2D per la superficie di disegno di un elemento canvas"
type: docs

url: /it/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

L'interfaccia ICanvasRenderingContext2D è usata per disegnare rettangoli, testo, immagini e altri oggetti sull'elemento canvas. Fornisce il contesto di rendering 2D per la superficie di disegno di un elemento canvas.

```java
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getCanvas](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) Un riferimento di sola lettura all'HTMLCanvasElement. Potrebbe essere null se non è associato a un elemento canvas. |
[getFillStyle]
[setFillStyle] Color or style to use inside shapes. Default: (black). |
[getGlobalAlpha]
[setGlobalAlpha] Alpha value that is applied to shapes and images before they are composited onto the canvas. Default 1.0 (opaque). |
[getGlobalCompositeOperation]
[setGlobalCompositeOperation] With globalAlpha applied this sets how shapes and images are drawn onto the existing bitmap. Default: (source-over) |
[getImageSmoothingEnabled]
[setImageSmoothingEnabled] Image smoothing mode; if disabled, images will not be smoothed if scaled. |
[getShadowBlur]
[setShadowBlur] Specifies the blurring effect. Default 0 |
[getShadowColor]
[setShadowColor] Color of the shadow. Default fully-transparent black. |
[getShadowOffsetX]
[setShadowOffsetX] Horizontal distance the shadow will be offset. Default 0. |
[getShadowOffsetY]
[setShadowOffsetY] Vertical distance the shadow will be offset. Default 0. |
[getStrokeStyle]
[setStrokeStyle] Color or style to use for the lines around shapes. Default: (black). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [addHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;String, String&gt;) |  |
| [beginPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | Inizia un nuovo percorso svuotando l'elenco dei sotto-percorsi. Chiama questo metodo quando vuoi creare un nuovo percorso. |
| [clearHitRegions](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | Rimuove tutte le regioni di hit dal canvas. |
| [clearRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | Imposta tutti i pixel nel rettangolo definito dal punto di partenza (x, y) e dalle dimensioni (larghezza, altezza) a nero trasparente, cancellando qualsiasi contenuto disegnato precedentemente. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | Crea una nuova regione di ritaglio calcolando l'intersezione tra la regione di ritaglio corrente e l'area descritta dal percorso, usando la regola del numero di avvolgimento non zero. I sotto-percorsi aperti devono essere chiusi implicitamente durante il calcolo della regione di ritaglio, senza influenzare i sotto-percorsi effettivi. La nuova regione di ritaglio sostituisce quella corrente. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | Crea una nuova regione di ritaglio calcolando l'intersezione tra la regione di ritaglio corrente e l'area descritta dal percorso, usando la regola del numero di avvolgimento non zero. I sotto-percorsi aperti devono essere chiusi implicitamente durante il calcolo della regione di ritaglio, senza influenzare i sotto-percorsi effettivi. La nuova regione di ritaglio sostituisce quella corrente. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | Crea una nuova regione di ritaglio calcolando l'intersezione tra la regione di ritaglio corrente e l'area descritta dal percorso, usando la regola del numero di avvolgimento non zero. I sotto-percorsi aperti devono essere chiusi implicitamente durante il calcolo della regione di ritaglio, senza influenzare i sotto-percorsi effettivi. La nuova regione di ritaglio sostituisce quella corrente. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | Crea un nuovo oggetto ImageData vuoto con le dimensioni specificate. Tutti i pixel nel nuovo oggetto sono neri trasparenti. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | Crea un nuovo oggetto ImageData vuoto con le dimensioni specificate. Tutti i pixel nel nuovo oggetto sono neri trasparenti. |
| [createLinearGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | Crea un gradiente lineare lungo la linea definita dalle coordinate rappresentate dai parametri. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, String) | Crea un pattern utilizzando l'immagine specificata (un CanvasImageSource). Ripete la sorgente nelle direzioni specificate dall'argomento repetition. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, String) | Crea un pattern utilizzando l'immagine specificata (un CanvasImageSource). Ripete la sorgente nelle direzioni specificate dall'argomento repetition. |
| [createRadialGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | Crea un gradiente radiale dato dalle coordinate dei due cerchi rappresentati dai parametri. |
| [drawFocusIfNeeded](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | Se un dato elemento è focalizzato, questo metodo disegna un anello di messa a fuoco attorno al percorso corrente. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | Disegna l'immagine specificata. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | Disegna l'immagine specificata. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | Disegna l'immagine specificata. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | Disegna l'immagine specificata. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Disegna l'immagine specificata. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | Disegna l'immagine specificata. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | Riempie i sotto‑percorsi con lo stile di riempimento corrente e l'algoritmo predefinito CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | Riempie i sotto‑percorsi con lo stile di riempimento corrente. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | Riempie i sotto‑percorsi con lo stile di riempimento corrente e l'algoritmo predefinito CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | Riempie i sotto‑percorsi con lo stile di riempimento corrente. |
| [fillRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | Disegna un rettangolo riempito nella posizione (x, y) la cui dimensione è determinata da larghezza e altezza. |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(String, double, double) | Disegna (riempie) un testo dato nella posizione (x,y) specificata. |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(String, double, double, double) | Disegna (riempie) un testo dato nella posizione (x,y) specificata. |
| [getImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | Restituisce un oggetto ImageData che rappresenta i dati pixel sottostanti per l'area della canvas indicata dal rettangolo che inizia in (sx, sy) e ha una larghezza sw e un'altezza sh. Questo metodo non è influenzato dalla matrice di trasformazione della canvas. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | Riporta se il punto specificato è contenuto o meno nel percorso corrente. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | Riporta se il punto specificato è contenuto o meno nel percorso corrente. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | Riporta se il punto specificato è contenuto o meno nel percorso corrente. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | Riporta se il punto specificato è contenuto o meno nel percorso corrente. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | Riporta se il punto specificato è all'interno dell'area contenuta dal tracciamento di un percorso. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | Riporta se il punto specificato è all'interno dell'area contenuta dal tracciamento di un percorso. |
| [measureText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(String) | Restituisce un oggetto TextMetrics. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | Dipinge i dati dall'oggetto ImageData fornito sul bitmap. Se viene fornito un rettangolo sporco, vengono dipinti solo i pixel di quel rettangolo. Questo metodo non è influenzato dalla matrice di trasformazione della canvas. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | Dipinge i dati dall'oggetto ImageData fornito sul bitmap. Se viene fornito un rettangolo sporco, vengono dipinti solo i pixel di quel rettangolo. Questo metodo non è influenzato dalla matrice di trasformazione della canvas. |
| [removeHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(String) | Rimuove la regione di hit con l'ID specificato dalla canvas. |
| [resetTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | Reimposta la trasformazione corrente con la matrice identità. |
| [restore](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | Ripristina lo stato dello stile di disegno all'ultimo elemento dello 'stack di stato' salvato da save(). |
| [rotate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | Aggiunge una rotazione alla matrice di trasformazione. L'argomento angolo rappresenta un angolo di rotazione in senso orario ed è espresso in radianti. |
| [save](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | Salva lo stato attuale dello stile di disegno usando uno stack così da poter annullare qualsiasi modifica apportata usando restore(). |
| [scale](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | Aggiunge una trasformazione di scala alle unità della canvas per x orizzontalmente e per y verticalmente. |
| [setTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | Reimposta la trasformazione corrente alla matrice identità, quindi invoca il metodo transform() con gli stessi argomenti. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | Traccia i sotto‑percorsi con lo stile di contorno corrente. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | Traccia i sotto‑percorsi con lo stile di contorno corrente. |
| [strokeRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | Dipinge un rettangolo che ha un punto di partenza in (x, y) e una larghezza w e un'altezza h sulla canvas, usando lo stile di contorno corrente. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(String, double, double) | Disegna (traccia) un testo dato nella posizione (x, y) specificata. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(String, double, double, double?) | Disegna (traccia) un testo dato nella posizione (x, y) specificata. |
| [transform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | Moltiplica la matrice di trasformazione corrente con la matrice descritta dai suoi argomenti. |
| [translate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | Aggiunge una trasformazione di traslazione spostando la canvas e la sua origine x orizzontalmente e y verticalmente sulla griglia. |

### Vedi anche

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
