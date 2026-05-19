---
title: "Interfaccia IViewCSS"
second_title: "Riferimento API Aspose.HTML per Java"
description: "interfaccia com.aspose.html.dom.css.IViewCSS. L'interfaccia IViewCSS rappresenta un'estensione dell'oggetto Window che fornisce l'accesso ai valori di tutte le proprietà CSS di un elemento."
type: docs

url: /it/java/com.aspose.html.dom.css/iviewcss/
---
## IViewCSS interface

L'interfaccia IViewCSS rappresenta un'estensione dell'oggetto Window che fornisce l'accesso ai valori di tutte le proprietà CSS di un elemento.

Lo stile CSS per un determinato elemento può essere ottenuto utilizzando il metodo IViewCSS.GetComputedStyle().

```java
public interface IViewCSS : IAbstractView
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle)(Element) | Il metodo IViewCSS.getComputedStyle() restituisce un oggetto contenente i valori di tutte le proprietà CSS di un elemento, dopo l'applicazione dei fogli di stile attivi e la risoluzione di eventuali calcoli di base contenuti in tali valori. |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle_1)(Element, String) | Il metodo IViewCSS.getComputedStyle() restituisce un oggetto contenente i valori di tutte le proprietà CSS di un elemento, dopo l'applicazione dei fogli di stile attivi e la risoluzione di eventuali calcoli di base contenuti in tali valori. |

## Osservazioni

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Riferimento

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### Vedi anche

* interface [IAbstractView](../../com.aspose.html.dom.views/iabstractview/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
