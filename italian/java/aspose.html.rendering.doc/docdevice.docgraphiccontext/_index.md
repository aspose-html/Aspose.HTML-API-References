---
title: "Classe DocDevice.DocGraphicContext"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.rendering.doc.DocDeviceDocGraphicContext. Contiene i parametri di controllo grafico correnti per il DocDevice. Questi parametri definiscono il quadro globale entro il quale gli operatori grafici vengono eseguiti"
type: docs

url: /it/java/com.aspose.html.rendering.doc/docdevice.docgraphiccontext/
---
## DocDevice.DocGraphicContext class

Contiene i parametri di controllo grafico correnti per il DocDevice. Questi parametri definiscono il quadro globale entro il quale vengono eseguiti gli operatori grafici.

```java
public class DocGraphicContext : GraphicContext
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [docGraphicContext](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/.ctor)() | Il costruttore predefinito. |

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
| [transformationMatrix](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/transformationmatrix) { get; set; } | Imposta o ottiene la matrice di trasformazione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [clone](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/clone)() | Crea una nuova istanza di una classe [`GraphicContext`](../../com.aspose.html.rendering/graphiccontext/) con gli stessi valori di proprietà di un'istanza esistente. |
| [transform](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/transform)(IMatrix) | Modifica la matrice di trasformazione corrente moltiplicando per la matrice specificata. |

### Vedi anche

* class [GraphicContext](../../com.aspose.html.rendering/graphiccontext/)
* class [DocDevice](../docdevice/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)
