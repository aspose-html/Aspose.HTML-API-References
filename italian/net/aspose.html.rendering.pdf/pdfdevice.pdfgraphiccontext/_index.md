---
title: Class PdfDevice.PdfGraphicContext
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Rendering.Pdf.PdfDevicePdfGraphicContext classe. Contiene i parametri di controllo della grafica correnti per PdfDevice. Questi parametri definiscono il framework globale allinterno del quale vengono eseguiti gli operatori grafici.
type: docs
weight: 4450
url: /it/net/aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext/
---
## PdfDevice.PdfGraphicContext class

Contiene i parametri di controllo della grafica correnti per PdfDevice. Questi parametri definiscono il framework globale all'interno del quale vengono eseguiti gli operatori grafici.

```csharp
public class PdfGraphicContext : GraphicContext
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfGraphicContext](pdfgraphiccontext/)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Imposta o ottiene la spaziatura dei caratteri. |
| override [FillBrush](../../aspose.html.rendering.pdf/pdfgraphiccontext/fillbrush/) { get; set; } | Imposta o ottiene l'oggetto pennello utilizzato per riempire gli interni dei tracciati. |
| virtual [Font](../../aspose.html.rendering/graphiccontext/font/) { get; set; } | Imposta o ottiene l'oggetto font true type utilizzato per il rendering del testo. |
| virtual [FontSize](../../aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Imposta o ottiene la dimensione del carattere del testo. |
| virtual [FontStyle](../../aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Imposta o ottiene lo stile del carattere del testo. |
| override [LineCap](../../aspose.html.rendering.pdf/pdfgraphiccontext/linecap/) { get; set; } | Imposta o ottiene il codice che specifica la forma degli estremi per qualsiasi percorso aperto che viene tracciato. |
| virtual [LineDashOffset](../../aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Imposta o ottiene l'offset di fase del modello di linea tratteggiata corrente. |
| virtual [LineDashPattern](../../aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Imposta o ottiene la descrizione del modello di tratteggio da utilizzare quando vengono tracciati i percorsi. |
| virtual [LineDashStyle](../../aspose.html.rendering/graphiccontext/linedashstyle/) { get; set; } | Gli insiemi ottengono lo stile delle linee tratteggiate di un percorso tracciato. |
| override [LineJoin](../../aspose.html.rendering.pdf/pdfgraphiccontext/linejoin/) { get; set; } | Imposta o ottiene il codice che specifica la forma dei giunti tra i segmenti collegati di un percorso tracciato. |
| override [LineWidth](../../aspose.html.rendering.pdf/pdfgraphiccontext/linewidth/) { get; set; } | Imposta o ottiene lo spessore dei tracciati da tracciare. |
| override [MiterLimit](../../aspose.html.rendering.pdf/pdfgraphiccontext/miterlimit/) { get; set; } | Imposta o ottiene la lunghezza massima delle giunzioni delle linee squadrate per i percorsi tracciati. Questo parametro limita la lunghezza delle "punte" prodotte quando i segmenti di linea si uniscono ad angoli acuti. |
| override [StrokeBrush](../../aspose.html.rendering.pdf/pdfgraphiccontext/strokebrush/) { get; set; } | Imposta o ottiene l'oggetto pennello utilizzato per i tracciati tracciati. |
| virtual [TextInfo](../../aspose.html.rendering/graphiccontext/textinfo/) { get; } | Ottiene a[`TextInfo`](../../aspose.html.rendering/textinfo/) oggetto che contiene informazioni sul testo renderizzato. |
| override [TransformationMatrix](../../aspose.html.rendering.pdf/pdfgraphiccontext/transformationmatrix/) { get; set; } | Imposta o ottiene la matrice di trasformazione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../aspose.html.rendering.pdf/pdfgraphiccontext/clone/)() | Crea una nuova istanza di una classe con gli stessi valori di proprietà di un'istanza esistente. |
| override [Transform](../../aspose.html.rendering.pdf/pdfgraphiccontext/transform/)(Matrix) | Modifica la matrice di trasformazione corrente moltiplicando la matrice specificata. |

### Guarda anche

* class [GraphicContext](../../aspose.html.rendering/graphiccontext/)
* class [PdfDevice](../pdfdevice/)
* spazio dei nomi [Aspose.Html.Rendering.Pdf](../../aspose.html.rendering.pdf/)
* assemblea [Aspose.HTML](../../)


