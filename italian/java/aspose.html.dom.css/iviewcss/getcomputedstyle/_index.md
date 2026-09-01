---
title: "IViewCSS.GetComputedStyle"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo IViewCSS. Il metodo IViewCSS.getComputedStyle restituisce un oggetto contenente i valori di tutte le proprietà CSS di un elemento dopo l'applicazione dei fogli di stile attivi e la risoluzione di eventuali calcoli di base che tali valori possono contenere."
type: docs

url: /it/java/com.aspose.html.dom.css/iviewcss/getcomputedstyle/
---
## GetComputedStyle(Element) {#getcomputedstyle}

Il metodo IViewCSS.getComputedStyle() restituisce un oggetto contenente i valori di tutte le proprietà CSS di un elemento, dopo aver applicato i fogli di stile attivi e risolto eventuali calcoli di base che quei valori possono contenere.

I valori individuali delle proprietà CSS sono accessibili tramite le API fornite dall'oggetto, o indicizzando con i nomi delle proprietà CSS.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | Element | L'[`Element`](../../../com.aspose.html.dom/element/) per il quale ottenere lo stile calcolato. Questo parametro non può essere null. |

### Valore di ritorno

Lo stile restituito è un oggetto [`CSSStyleDeclaration`](../../icssstyledeclaration/) live, che si aggiorna automaticamente quando gli stili dell'elemento vengono modificati.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| Errore di tipo | Se l'oggetto passato non è un Element o pseudoElt non è un selettore di pseudo-elemento valido. |

## Osservazioni

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Riferimento

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### Vedi anche

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

---

## GetComputedStyle(Element, String) {#getcomputedstyle_1}

Il metodo IViewCSS.getComputedStyle() restituisce un oggetto contenente i valori di tutte le proprietà CSS di un elemento, dopo aver applicato i fogli di stile attivi e risolto eventuali calcoli di base che quei valori possono contenere.

I valori individuali delle proprietà CSS sono accessibili tramite le API fornite dall'oggetto, o indicizzando con i nomi delle proprietà CSS.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element, String pseudoElement)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | Element | L'[`Element`](../../../com.aspose.html.dom/element/) per il quale ottenere lo stile calcolato. Questo parametro non può essere null. |
| pseudoElement | String | Una stringa che specifica il pseudo-elemento da corrispondere. Omettuta (o null) per gli elementi reali. |

### Valore di ritorno

Lo stile restituito è un oggetto [`CSSStyleDeclaration`](../../icssstyledeclaration/) live, che si aggiorna automaticamente quando gli stili dell'elemento vengono modificati.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| Errore di tipo | Se l'oggetto passato non è un Element o pseudoElt non è un selettore di pseudo-elemento valido. |

## Osservazioni

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Riferimento

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### Vedi anche

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
