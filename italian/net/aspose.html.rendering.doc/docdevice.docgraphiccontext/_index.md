---
title: Class DocDevice.DocGraphicContext
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Rendering.Doc.DocDeviceDocGraphicContext classe. Contiene i parametri di controllo della grafica correnti per DocDevice. Questi parametri definiscono la struttura globale allinterno della quale vengono eseguiti gli operatori grafici.
type: docs
weight: 4180
url: /it/net/aspose.html.rendering.doc/docdevice.docgraphiccontext/
---
## DocDevice.DocGraphicContext class

Contiene i parametri di controllo della grafica correnti per DocDevice. Questi parametri definiscono la struttura globale all'interno della quale vengono eseguiti gli operatori grafici.

```csharp
public class DocGraphicContext : GraphicContext
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DocGraphicContext](docgraphiccontext/)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Imposta o ottiene la spaziatura dei caratteri. |
| virtual [FillBrush](../../aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | Imposta o ottiene l'oggetto pennello utilizzato per riempire gli interni dei tracciati. |
| virtual [Font](../../aspose.html.rendering/graphiccontext/font/) { get; set; } | Imposta o ottiene l'oggetto font true type utilizzato per il rendering del testo. |
| virtual [FontSize](../../aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Imposta o ottiene la dimensione del carattere del testo. |
| virtual [FontStyle](../../aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Imposta o ottiene lo stile del carattere del testo. |
| virtual [LineCap](../../aspose.html.rendering/graphiccontext/linecap/) { get; set; } | Imposta o ottiene il codice che specifica la forma degli estremi per qualsiasi percorso aperto che viene tracciato. |
| virtual [LineDashOffset](../../aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Imposta o ottiene l'offset di fase del modello di linea tratteggiata corrente. |
| virtual [LineDashPattern](../../aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Imposta o ottiene la descrizione del modello di tratteggio da utilizzare quando vengono tracciati i percorsi. |
| virtual [LineDashStyle](../../aspose.html.rendering/graphiccontext/linedashstyle/) { get; set; } | Gli insiemi ottengono lo stile delle linee tratteggiate di un percorso tracciato. |
| virtual [LineJoin](../../aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | Imposta o ottiene il codice che specifica la forma dei giunti tra i segmenti collegati di un percorso tracciato. |
| virtual [LineWidth](../../aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | Imposta o ottiene lo spessore dei tracciati da tracciare. |
| virtual [MiterLimit](../../aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | Imposta o ottiene la lunghezza massima delle giunzioni delle linee squadrate per i percorsi tracciati. Questo parametro limita la lunghezza delle "punte" prodotte quando i segmenti di linea si uniscono ad angoli acuti. |
| virtual [StrokeBrush](../../aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | Imposta o ottiene l'oggetto pennello utilizzato per i tracciati tracciati. |
| virtual [TextInfo](../../aspose.html.rendering/graphiccontext/textinfo/) { get; } | Ottiene a[`TextInfo`](../../aspose.html.rendering/textinfo/) oggetto che contiene informazioni sul testo renderizzato. |
| override [TransformationMatrix](../../aspose.html.rendering.doc/docgraphiccontext/transformationmatrix/) { get; set; } | Imposta o ottiene la matrice di trasformazione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Clone](../../aspose.html.rendering.doc/docgraphiccontext/clone/)() | Crea una nuova istanza di a[`GraphicContext`](../../aspose.html.rendering/graphiccontext/) class con gli stessi valori di proprietà di un'istanza esistente. |
| override [Transform](../../aspose.html.rendering.doc/docgraphiccontext/transform/)(Matrix) | Modifica la matrice di trasformazione corrente moltiplicando la matrice specificata. |

### Guarda anche

* class [GraphicContext](../../aspose.html.rendering/graphiccontext/)
* class [DocDevice](../docdevice/)
* spazio dei nomi [Aspose.Html.Rendering.Doc](../../aspose.html.rendering.doc/)
* assemblea [Aspose.HTML](../../)


