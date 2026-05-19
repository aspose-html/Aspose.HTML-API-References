---
title: "Interfaccia ICanvasPathMethods"
second_title: "Riferimento API Aspose.HTML per Java"
description: "interfaccia com.aspose.html.dom.canvas.ICanvasPathMethods. L'interfaccia ICanvasPathMethods è usata per manipolare i percorsi degli oggetti."
type: docs

url: /it/java/com.aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

L'interfaccia ICanvasPathMethods è usata per manipolare i percorsi degli oggetti.

```java
public interface ICanvasPathMethods
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | Aggiunge un arco al percorso centrato nella posizione (x, y) con raggio r, iniziando da startAngle e terminando a endAngle, procedendo nella direzione indicata in senso antiorario (predefinito in senso orario). |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | Aggiunge un arco al percorso centrato nella posizione (x, y) con raggio r, iniziando da startAngle e terminando a endAngle, procedendo nella direzione indicata in senso antiorario (predefinito in senso orario). |
| [arcTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | Aggiunge un arco al percorso con i punti di controllo forniti e il raggio, collegato al punto precedente da una linea retta. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | Aggiunge una curva Bézier cubica al percorso. Richiede tre punti. I primi due punti sono punti di controllo e il terzo è il punto finale. Il punto di partenza è l'ultimo punto nel percorso corrente, che può essere modificato usando moveTo() prima di creare la curva Bézier. |
| [closePath](../../com.aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | Fa sì che il punto della penna torni all'inizio del sotto-percorso corrente. Tenta di disegnare una linea retta dal punto corrente all'inizio. Se la forma è già chiusa o ha solo un punto, questa funzione non fa nulla. |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | Aggiunge un'ellisse al percorso centrata nella posizione (x, y) con i raggi radiusX e radiusY, iniziando da startAngle e terminando a endAngle, procedendo nella direzione indicata in senso antiorario (predefinito in senso orario). |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Aggiunge un'ellisse al percorso centrata nella posizione (x, y) con i raggi radiusX e radiusY, iniziando da startAngle e terminando a endAngle, procedendo nella direzione indicata in senso antiorario (predefinito in senso orario). |
| [lineTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | Collega l'ultimo punto del sotto-percorso alle coordinate x, y con una linea retta. |
| [moveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | Sposta il punto di partenza di un nuovo sotto-percorso alle coordinate (x, y). |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | Aggiunge una curva Bézier quadratica al percorso corrente. |
| [rect](../../com.aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | Crea un percorso per un rettangolo nella posizione (x, y) con una dimensione determinata da larghezza e altezza. |

### Vedi anche

* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
