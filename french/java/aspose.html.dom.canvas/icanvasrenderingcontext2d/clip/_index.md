---
title: "ICanvasRenderingContext2D.Clip"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode ICanvasRenderingContext2D. Crée une nouvelle région de découpage en calculant l'intersection de la région de découpage actuelle et de la zone décrite par le chemin en utilisant la règle du nombre de tours non nul. Les sous-chemins ouverts doivent être fermés implicitement lors du calcul de la région de découpage sans affecter les sous-chemins réels. La nouvelle région de découpage remplace la région de découpage actuelle."
type: docs

url: /fr/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/
---
## Clip() {#clip}

Crée une nouvelle région de découpage en calculant l'intersection de la région de découpage actuelle et de la zone décrite par le chemin, en utilisant la règle du nombre de tours non nul. Les sous-chemins ouverts doivent être fermés implicitement lors du calcul de la région de découpage, sans affecter les sous-chemins réels. La nouvelle région de découpage remplace la région de découpage actuelle.

```java
public void Clip()
```

### Voir aussi

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(CanvasFillRule) {#clip_1}

Crée une nouvelle région de découpage en calculant l'intersection de la région de découpage actuelle et de la zone décrite par le chemin, en utilisant la règle du nombre de tours non nul. Les sous-chemins ouverts doivent être fermés implicitement lors du calcul de la région de découpage, sans affecter les sous-chemins réels. La nouvelle région de découpage remplace la région de découpage actuelle.

```java
public void Clip(CanvasFillRule fillRule)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fillRule | CanvasFillRule | L'algorithme permettant de déterminer si un point est à l'intérieur ou à l'extérieur d'un chemin. |

### Voir aussi

* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(Path2D, CanvasFillRule) {#clip_2}

Crée une nouvelle région de découpage en calculant l'intersection de la région de découpage actuelle et de la zone décrite par le chemin, en utilisant la règle du nombre de tours non nul. Les sous-chemins ouverts doivent être fermés implicitement lors du calcul de la région de découpage, sans affecter les sous-chemins réels. La nouvelle région de découpage remplace la région de découpage actuelle.

```java
public void Clip(Path2D path, CanvasFillRule fillRule)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | Path2D | Un chemin Path2D à découper. |
| fillRule | CanvasFillRule | L'algorithme permettant de déterminer si un point est à l'intérieur ou à l'extérieur d'un chemin. |

### Voir aussi

* class [Path2D](../../path2d/)
* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
