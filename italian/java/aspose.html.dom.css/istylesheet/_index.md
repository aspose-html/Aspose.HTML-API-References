---
title: "Interfaccia IStyleSheet"
second_title: "Riferimento API Aspose.HTML per Java"
description: "interfaccia com.aspose.html.dom.css.IStyleSheet. L'interfaccia StyleSheet è l'interfaccia base astratta per qualsiasi tipo di foglio di stile. Rappresenta un singolo foglio di stile associato a un documento strutturato. In HTML l'interfaccia StyleSheet rappresenta sia un foglio di stile esterno incluso tramite l'elemento HTML LINK sia un elemento STYLE inline. In XML questa interfaccia rappresenta un foglio di stile esterno incluso tramite un'istruzione di elaborazione del foglio di stile. I fogli di stile CSS implementeranno ulteriormente l'interfaccia più specializzata CSSStyleSheet."
type: docs

url: /it/java/com.aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

L'interfaccia StyleSheet è l'interfaccia base astratta per qualsiasi tipo di foglio di stile. Rappresenta un singolo foglio di stile associato a un documento strutturato. In HTML, l'interfaccia StyleSheet rappresenta sia un foglio di stile esterno, incluso tramite l'elemento HTML LINK, sia un elemento STYLE inline. In XML, questa interfaccia rappresenta un foglio di stile esterno, incluso tramite un'istruzione di elaborazione del foglio di stile. I fogli di stile CSS implementeranno ulteriormente l'interfaccia più specializzata [`CSSStyleSheet`](../icssstylesheet/).

Vedi anche la [CSS Object Model (CSSOM) # StyleSheet Interface Specification](https://drafts.csswg.org/cssom/#the-stylesheet-interface).

```java
public interface IStyleSheet
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
[getDisabled]
[setDisabled] The disabled property of the `StyleSheet` interface determines whether the style sheet is prevented from applying to the document. |
| [getHref](../../com.aspose.html.dom.css/istylesheet/href/) La proprietà href dell'interfaccia `StyleSheet` restituisce la posizione del foglio di stile. |
| [getMedia](../../com.aspose.html.dom.css/istylesheet/media/) La proprietà media dell'interfaccia `StyleSheet` specifica il supporto di destinazione previsto per le informazioni di stile. È un oggetto di sola lettura, simile a un array, [`MediaList`](../imedialist/), e può essere rimosso con deleteMedium() e aggiunto con appendMedium(). |
| [getOwnerNode](../../com.aspose.html.dom.css/istylesheet/ownernode/) Il nodo che associa questo foglio di stile al documento. Per HTML, può essere l'elemento LINK o STYLE corrispondente. Per XML, può essere l'istruzione di elaborazione di collegamento. Per i fogli di stile inclusi da altri fogli di stile, il valore di questo attributo è null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/istylesheet/parentstylesheet/) Per i linguaggi di fogli di stile che supportano il concetto di inclusione di fogli di stile, questo attributo rappresenta il foglio di stile includente, se esiste. Se il foglio di stile è un foglio di livello superiore, o il linguaggio di fogli di stile non supporta l'inclusione, il valore di questo attributo è null. |
| [getTitle](../../com.aspose.html.dom.css/istylesheet/title/) La proprietà title dell'interfaccia `StyleSheet` restituisce il titolo consigliato del foglio di stile corrente. |
| [getType](../../com.aspose.html.dom.css/istylesheet/type/) Questo specifica il linguaggio del foglio di stile per questo foglio di stile. Il linguaggio del foglio di stile è specificato come tipo di contenuto (ad es. "text/css"). |

## Osservazioni

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Riferimento

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[The StyleSheet Interface](https://drafts.csswg.org/cssom/#the-stylesheet-interface) – The official CSSOM definition.

### Vedi anche

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
