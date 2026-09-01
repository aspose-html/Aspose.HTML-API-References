---
title: "Interfaccia IMediaList"
second_title: "Aspose.HTML per Java Riferimento API"
description: "com.aspose.html.dom.css.IMediaList interfaccia. L'interfaccia MediaList fornisce l'astrazione di una collezione ordinata di media senza definire o vincolare il modo in cui questa collezione è implementata. Una lista vuota è la stessa di una lista che contiene tutti i media"
type: docs

url: /it/java/com.aspose.html.dom.css/imedialist/
---
## IMediaList interface

L'interfaccia MediaList fornisce l'astrazione di una collezione ordinata di media, senza definire o vincolare il modo in cui questa collezione è implementata. Un elenco vuoto è lo stesso di un elenco che contiene il medium "all".

Vedi anche il [CSS Object Model (CSSOM) # ](https://www.w3.org/TR/cssom-1/#the-medialist-interface)[MediaList](https://www.w3.org/TR/cssom-1/#the-medialist-interface).

```java
public interface IMediaList : IEnumerable<String>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/imedialist/item/) Il metodo item(index) deve restituire una serializzazione della query media nella collezione di query media fornita dall'indice, o null, se l'indice è maggiore o uguale al numero di query media nella collezione. |
| [getLength](../../com.aspose.html.dom.css/imedialist/length/) L'attributo length deve restituire il numero di query media nella collezione di query media. L'intervallo di media valido è da 0 a length-1 inclusi. |
| [getMediaText](../../com.aspose.html.dom.css/imedialist/mediatext/) Un Stringifier che restituisce un DOMString che rappresenta la MediaList come testo, e consente anche di impostare una nuova MediaList. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [appendMedium](../../com.aspose.html.dom.css/imedialist/appendmedium/)(String) | Aggiunge il medium newMedium alla fine della lista. Se newMedium è già utilizzato, viene prima rimosso. |
| [deleteMedium](../../com.aspose.html.dom.css/imedialist/deletemedium/)(String) | Elimina il medium indicato da oldMedium dalla lista. |

## Osservazioni

Nota: MediaList è una lista live; aggiornare la lista usando le proprietà o i metodi elencati di seguito aggiornerà immediatamente il comportamento del documento.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Riferimento

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # medialist](https://drafts.csswg.org/cssom/#medialist) – The CSSOM definition.

## Esempi

Il seguente registrerebbe sulla console una rappresentazione testuale della MediaList del primo foglio di stile applicato al documento corrente.

```java
var stylesheets = document.StyleSheets;
var stylesheet = stylesheets[0];
Console.Write(stylesheet.Media.MediaText);
```

### Vedi anche

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
