---
title: "Interfaccia IDevice"
second_title: "Riferimento API Aspose.HTML per Java"
description: "interfaccia com.aspose.html.rendering.IDevice. Definisce metodi e proprietà che supportano il rendering personalizzato degli elementi grafici come percorsi, testo e immagini"
type: docs

url: /it/java/com.aspose.html.rendering/idevice/
---
## IDevice interface

Definisce metodi e proprietà che supportano il rendering personalizzato degli elementi grafici come percorsi, testo e immagini.

```java
public interface IDevice : IDisposable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/idevice/graphiccontext/) Ottiene il contesto grafico. |
| [getOptions](../../com.aspose.html.rendering/idevice/options/) Ottiene le opzioni di rendering. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/idevice/addrect/)(RectangleF) | Aggiunge un rettangolo al percorso corrente come sotto-percorso completo. |
| [beginDocument](../../com.aspose.html.rendering/idevice/begindocument/)(Document) | Inizia il rendering del documento. |
| [beginElement](../../com.aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | Inizia il rendering dell'elemento. |
| [beginPage](../../com.aspose.html.rendering/idevice/beginpage/)(SizeF) | Inizia il rendering della nuova pagina. |
| [clip](../../com.aspose.html.rendering/idevice/clip/)(FillRule) | Modifica il percorso di ritaglio corrente intersecandolo con il percorso attuale, usando la FillRule per determinare la regione da riempire. Questo metodo termina il percorso corrente. |
| [closePath](../../com.aspose.html.rendering/idevice/closepath/)() | Chiude il sotto-percorso corrente aggiungendo un segmento di linea retta dal punto corrente al punto di partenza del sotto-percorso. Se il sotto-percorso corrente è già chiuso, "ClosePath" non fa nulla. Questo operatore termina il sotto-percorso corrente. Aggiungere un altro segmento al percorso corrente avvia un nuovo sotto-percorso, anche se il nuovo segmento inizia dal punto finale raggiunto dal metodo "ClosePath". |
| [cubicBezierTo](../../com.aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | Aggiunge una curva Bézier cubica al percorso corrente. La curva si estende dal punto corrente al punto pt3, usando pt1 e pt2 come punti di controllo Bézier. Il nuovo punto corrente è pt3. |
| [drawImage](../../com.aspose.html.rendering/idevice/drawimage/)(byte[], WebImageFormat, RectangleF) | Disegna l'immagine specificata. |
| [endDocument](../../com.aspose.html.rendering/idevice/enddocument/)() | Termina il rendering del documento. |
| [endElement](../../com.aspose.html.rendering/idevice/endelement/)(Element) | Termina il rendering dell'elemento. |
| [endPage](../../com.aspose.html.rendering/idevice/endpage/)() | Termina il rendering della pagina corrente. |
| [fill](../../com.aspose.html.rendering/idevice/fill/)(FillRule) | Riempie l'intera regione delimitata dal percorso corrente. Se il percorso è composto da diversi sotto‑percorsi disconnessi, riempie l'interno di tutti i sotto‑percorsi, considerati insieme. Questo metodo termina il percorso corrente. |
| [fillText](../../com.aspose.html.rendering/idevice/filltext/)(String, PointF) | Riempie la stringa di testo specificata nella posizione specificata. |
| [flush](../../com.aspose.html.rendering/idevice/flush/)() | Svuota tutti i dati nello stream di output. |
| [lineTo](../../com.aspose.html.rendering/idevice/lineto/)(PointF) | Aggiunge un segmento di linea retta dal punto corrente al punto (pt). Il nuovo punto corrente è pt. |
| [moveTo](../../com.aspose.html.rendering/idevice/moveto/)(PointF) | Inizia un nuovo sotto‑percorso spostando il punto corrente alle coordinate del parametro pt, omettendo qualsiasi segmento di linea di collegamento. Se il metodo di costruzione del percorso precedente nel percorso corrente era anche \"MoveTo\", il nuovo \"MoveTo\" lo sovrascrive; non rimane alcuna traccia dell'operazione \"MoveTo\" precedente nel percorso. |
| [restoreGraphicContext](../../com.aspose.html.rendering/idevice/restoregraphiccontext/)() | Ripristina l'intero contesto grafico al suo valore precedente rimuovendolo dallo stack. |
| [saveGraphicContext](../../com.aspose.html.rendering/idevice/savegraphiccontext/)() | Inserisce una copia dell'intero contesto grafico nello stack. |
| [stroke](../../com.aspose.html.rendering/idevice/stroke/)() | Traccia una linea lungo il percorso corrente. La linea tracciata segue ogni segmento rettilineo o curvo del percorso, centrata sul segmento con i lati paralleli ad esso. Ciascuno dei sotto‑percorsi del percorso viene trattato separatamente. Questo metodo termina il percorso corrente. |
| [strokeAndFill](../../com.aspose.html.rendering/idevice/strokeandfill/)(FillRule) | Traccia e riempie il percorso corrente. Questo metodo termina il percorso corrente. |
| [strokeText](../../com.aspose.html.rendering/idevice/stroketext/)(String, PointF) | Traccia la stringa di testo specificata nella posizione specificata. |

### Vedi anche

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
