---
title: "Classe PdfDevice.PdfGraphicContext"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Classe com.aspose.html.rendering.pdf.PdfDevicePdfGraphicContext. Contiene i parametri di controllo grafico correnti per il PdfDevice. Questi parametri definiscono il framework globale entro il quale gli operatori grafici vengono eseguiti."
type: docs

url: /it/java/com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext/
---
## PdfDevice.PdfGraphicContext class

Contiene i parametri di controllo grafico correnti per il PdfDevice. Questi parametri definiscono il framework globale entro il quale gli operatori grafici vengono eseguiti.

```java
public class PdfGraphicContext : GraphicContext
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [pdfGraphicContext](../../com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext/.ctor)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [characterSpacing](../../com.aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Imposta o ottiene la spaziatura dei caratteri. |
| [fillBrush](../../com.aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | Imposta o ottiene l'oggetto pennello utilizzato per riempire gli interni dei percorsi. |
| [font](../../com.aspose.html.rendering/graphiccontext/font/) { get; set; } | Imposta o ottiene l'oggetto font TrueType utilizzato per il rendering del testo. |
| [fontSize](../../com.aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Imposta o ottiene la dimensione del font del testo. |
| [fontStyle](../../com.aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Imposta o ottiene lo stile del font del testo. |
| [lineCap](../../com.aspose.html.rendering/graphiccontext/linecap/) { get; set; } | Imposta o ottiene il codice che specifica la forma delle estremità per qualsiasi percorso aperto che viene tracciato. |
| [lineDashOffset](../../com.aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Imposta o ottiene l'offset di fase del modello di tratteggio della linea corrente. |
| [lineDashPattern](../../com.aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Imposta o ottiene la descrizione del modello di tratteggio da utilizzare quando i percorsi sono tracciati. |
| [lineJoin](../../com.aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | Imposta o ottiene il codice che specifica la forma delle giunzioni tra segmenti collegati di un percorso tracciato. |
| [lineWidth](../../com.aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | Imposta o ottiene lo spessore dei percorsi da tracciare. |
| [miterLimit](../../com.aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | Imposta o ottiene la lunghezza massima delle giunzioni a spigolo per i percorsi tracciati. Questo parametro limita la lunghezza dei "spikes" prodotti quando i segmenti di linea si uniscono ad angoli acuti. |
| [strokeBrush](../../com.aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | Imposta o ottiene l'oggetto pennello utilizzato per i percorsi tracciati. |
| [getTextInfo](../../com.aspose.html.rendering/graphiccontext/textinfo/) Ottiene un oggetto [`TextInfo`](../../com.aspose.html.rendering/textinfo/) che contiene informazioni sul testo renderizzato. |
| [transformationMatrix](../../com.aspose.html.rendering/graphiccontext/transformationmatrix/) { get; set; } | Imposta o ottiene la matrice di trasformazione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [clone](../../com.aspose.html.rendering/graphiccontext/clone/)() | Crea una nuova istanza della classe GraphicContext con gli stessi valori di proprietà di un'istanza esistente. |
| [transform](../../com.aspose.html.rendering/graphiccontext/transform/)(IMatrix) | Modifica la matrice di trasformazione corrente moltiplicando per la matrice specificata. |

### Vedi anche

* class [GraphicContext](../../com.aspose.html.rendering/graphiccontext/)
* class [PdfDevice](../pdfdevice/)
* package [com.aspose.html.rendering.pdf](../../com.aspose.html.rendering.pdf/)
* package [Aspose.HTML](../../)
