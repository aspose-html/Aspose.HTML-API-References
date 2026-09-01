---
title: "ICanvasRenderingContext2D.Clip"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo di ICanvasRenderingContext2D. Crea una nuova regione di ritaglio calcolando l'intersezione tra la regione di ritaglio corrente e l'area descritta dal percorso usando la regola del numero di avvolgimento non zero. I sotto‑percorsi aperti devono essere chiusi implicitamente durante il calcolo della regione di ritaglio senza influire sui sotto‑percorsi effettivi. La nuova regione di ritaglio sostituisce la regione di ritaglio corrente."
type: docs

url: /it/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/
---
## Clip() {#clip}

Crea una nuova regione di ritaglio calcolando l'intersezione tra la regione di ritaglio corrente e l'area descritta dal percorso, utilizzando la regola del numero di avvolgimento non zero. I sotto-percorsi aperti devono essere chiusi implicitamente durante il calcolo della regione di ritaglio, senza influire sui sotto-percorsi effettivi. La nuova regione di ritaglio sostituisce quella corrente.

```java
public void Clip()
```

### Vedi anche

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(CanvasFillRule) {#clip_1}

Crea una nuova regione di ritaglio calcolando l'intersezione tra la regione di ritaglio corrente e l'area descritta dal percorso, utilizzando la regola del numero di avvolgimento non zero. I sotto-percorsi aperti devono essere chiusi implicitamente durante il calcolo della regione di ritaglio, senza influire sui sotto-percorsi effettivi. La nuova regione di ritaglio sostituisce quella corrente.

```java
public void Clip(CanvasFillRule fillRule)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fillRule | CanvasFillRule | L'algoritmo per determinare se un punto è all'interno o all'esterno di un percorso |

### Vedi anche

* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(Path2D, CanvasFillRule) {#clip_2}

Crea una nuova regione di ritaglio calcolando l'intersezione tra la regione di ritaglio corrente e l'area descritta dal percorso, utilizzando la regola del numero di avvolgimento non zero. I sotto-percorsi aperti devono essere chiusi implicitamente durante il calcolo della regione di ritaglio, senza influire sui sotto-percorsi effettivi. La nuova regione di ritaglio sostituisce quella corrente.

```java
public void Clip(Path2D path, CanvasFillRule fillRule)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | Path2D | Un percorso Path2D da ritagliare. |
| fillRule | CanvasFillRule | L'algoritmo con cui determinare se un punto è dentro o fuori un percorso. |

### Vedi anche

* class [Path2D](../../path2d/)
* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
