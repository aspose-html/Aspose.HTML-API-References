---
title: "DocDevice Class"
second_title: "Aspose.HTML per Java Riferimento API"
description: "com.aspose.html.rendering.doc.DocDevice class. Rappresenta il rendering in un documento DOCX"
type: docs

url: /it/java/com.aspose.html.rendering.doc/docdevice/
---
## DocDevice class

Rappresenta il rendering in un documento DOCX.

```java
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | Inizializza una nuova istanza della classe `DocDevice`. |
| [DocDevice](docdevice/#constructor_4)(Stream) | Inizializza una nuova istanza della classe `DocDevice` tramite stream di output. |
| [DocDevice](docdevice/#constructor_5)(String) | Inizializza una nuova istanza della classe `DocDevice` tramite nome file di output. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | Inizializza una nuova istanza della classe `DocDevice` tramite opzioni di rendering e provider di stream. |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | Inizializza una nuova istanza della classe `DocDevice` tramite opzioni di rendering e stream di output. |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, String) | Inizializza una nuova istanza della classe `DocDevice` tramite opzioni di rendering e nome file di output. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [addRect](../../com.aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | Aggiunge un rettangolo al percorso corrente come sotto-percorso completo. |
| [beginDocument](../../com.aspose.html.rendering.doc/docdevice/begindocument/)(Document) | Inizia il rendering del documento. |
| [beginElement](../../com.aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | Inizia il rendering del nodo html. |
| [beginPage](../../com.aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | Inizia il rendering della nuova pagina. |
| [clip](../../com.aspose.html.rendering.doc/docdevice/clip/)(FillRule) | Modifica il percorso di ritaglio corrente intersectandolo con il percorso corrente, usando la regola FillMode per determinare l'area da riempire. Questo metodo termina il percorso corrente. |
| [closePath](../../com.aspose.html.rendering.doc/docdevice/closepath/)() | Chiude il sotto-percorso corrente aggiungendo un segmento di linea retta dal punto corrente al punto di partenza del sotto-percorso. Se il sotto-percorso corrente è già chiuso, "ClosePath" non fa nulla. Questo operatore termina il sotto-percorso corrente. Aggiungere un altro segmento al percorso corrente avvia un nuovo sotto-percorso, anche se il nuovo segmento inizia dal punto finale raggiunto dal metodo "ClosePath". |
| [cubicBezierTo](../../com.aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | Aggiunge una curva cubica Bézier al percorso corrente. La curva si estende dal punto corrente al punto pt2, usando pt1 e pt2 come punti di controllo Bézier. Il nuovo punto corrente è pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering.doc/docdevice/drawimage/)(byte[], WebImageFormat, RectangleF) | Disegna l'immagine specificata. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering.doc/docdevice/endelement/)(Element) | Termina il rendering del nodo html. |
| [endPage](../../com.aspose.html.rendering.doc/docdevice/endpage/)() | Termina il rendering della pagina corrente. |
| [fill](../../com.aspose.html.rendering.doc/docdevice/fill/)(FillRule) | Riempie l'intera regione racchiusa dal percorso corrente. Se il percorso è composto da diversi sotto‑percorso disconnessi, riempie l'interno di tutti i sotto‑percorso, considerati insieme. Questo metodo termina il percorso corrente. |
| [fillText](../../com.aspose.html.rendering.doc/docdevice/filltext/)(String, PointF) | Riempie la stringa di testo specificata nella posizione specificata. |
| [flush](../../com.aspose.html.rendering.doc/docdevice/flush/)() | Svuota tutti i dati nello stream di output. |
| [lineTo](../../com.aspose.html.rendering.doc/docdevice/lineto/)(PointF) | Aggiunge un segmento di linea retta dal punto corrente al punto (pt). Il nuovo punto corrente è pt. |
| [moveTo](../../com.aspose.html.rendering.doc/docdevice/moveto/)(PointF) | Inizia un nuovo sotto‑percorso spostando il punto corrente alle coordinate del parametro pt, omettendo qualsiasi segmento di collegamento. Se il metodo di costruzione del percorso precedente nel percorso corrente era anche \"MoveTo\", il nuovo \"MoveTo\" lo sovrascrive; non rimane alcuna traccia dell'operazione \"MoveTo\" precedente nel percorso. |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering.doc/docdevice/stroke/)() | Traccia una linea lungo il percorso corrente. La linea tracciata segue ogni segmento rettilineo o curvo del percorso, centrata sul segmento con i lati paralleli ad esso. Ognuno dei sotto‑percorso del percorso è trattato separatamente. Questo metodo termina il percorso corrente. |
| [strokeAndFill](../../com.aspose.html.rendering.doc/docdevice/strokeandfill/)(FillRule) | Traccia e riempie il percorso corrente. Questo metodo termina il percorso corrente. |
| [strokeText](../../com.aspose.html.rendering.doc/docdevice/stroketext/)(String, PointF) | Traccia la stringa di testo specificata nella posizione specificata. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| class [DocGraphicContext](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext) | Contiene i parametri di controllo grafico correnti per il DocDevice. Questi parametri definiscono il framework globale entro il quale vengono eseguiti gli operatori grafici. |

### Vedi anche

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)
