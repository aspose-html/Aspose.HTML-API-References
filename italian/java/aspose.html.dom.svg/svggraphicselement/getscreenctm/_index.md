---
title: "SVGGraphicsElement.GetScreenCTM"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo SVGGraphicsElement. Restituisce la matrice di trasformazione dalle unità utente correnti, cioè dopo l'applicazione dell'attributo transform, se presente, rispetto al pixel di riferimento dell'agente utente genitore. Per i dispositivi di visualizzazione, idealmente questo rappresenta un pixel fisico dello schermo. Per altri dispositivi o ambienti in cui le dimensioni fisiche del pixel non sono note, può essere usato un algoritmo simile alla definizione di pixel di CSS2. Nota che viene restituito null se questo elemento non è collegato all'albero del documento. Questo metodo sarebbe stato più appropriato chiamarlo getClientCTM, ma il nome getScreenCTM è mantenuto per ragioni storiche."
type: docs

url: /it/java/com.aspose.html.dom.svg/svggraphicselement/getscreenctm/
---
## SVGGraphicsElement.GetScreenCTM method

Restituisce la matrice di trasformazione dalle unità utente correnti (cioè, dopo l'applicazione dell'attributo ‘transform’, se presente) alla notifica del pixel dell'agente utente genitore. Per i dispositivi di visualizzazione, idealmente questo rappresenta un pixel fisico dello schermo. Per altri dispositivi o ambienti in cui le dimensioni fisiche dei pixel non sono note, può essere usato un algoritmo simile alla definizione CSS2 di un “pixel”. Nota che viene restituito null se questo elemento non è collegato all'albero del documento. Questo metodo sarebbe stato più appropriatamente chiamato getClientCTM, ma il nome getScreenCTM è mantenuto per ragioni storiche.

```java
public SVGMatrix GetScreenCTM()
```

### Valore di ritorno

Un oggetto SVGMatrix che definisce la matrice di trasformazione fornita.

### Vedi anche

* class [SVGMatrix](../../../com.aspose.html.dom.svg.datatypes/svgmatrix/)
* class [SVGGraphicsElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
