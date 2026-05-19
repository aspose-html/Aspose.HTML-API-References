---
title: "Classe Path2D"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.dom.canvas.Path2D. L'interfaccia Path2D dell'API Canvas 2D è usata per dichiarare percorsi che vengono poi utilizzati su oggetti CanvasRenderingContext2D. I metodi di percorso dell'interfaccia CanvasRenderingContext2D sono presenti anche su questa interfaccia e consentono di creare percorsi che è possibile conservare e riprodurre secondo necessità su un canvas."
type: docs

url: /it/java/com.aspose.html.dom.canvas/path2d/
---
## Path2D class

L'interfaccia Path2D dell'API Canvas 2D è usata per dichiarare percorsi che vengono poi successivamente utilizzati sugli oggetti CanvasRenderingContext2D. I metodi di percorso dell'interfaccia CanvasRenderingContext2D sono presenti anche su questa interfaccia e consentono di creare percorsi che è possibile conservare e riprodurre, se necessario, su un canvas.

```java
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Path2D](path2d/#constructor)() | restituisce un nuovo oggetto Path2D appena istanziato |
| [Path2D](path2d/#constructor_1)(Path2D) | restituisce un nuovo oggetto Path2D appena istanziato con un altro percorso come argomento (crea una copia) |
| [Path2D](path2d/#constructor_2)(String) | restituisce un nuovo oggetto Path2D appena istanziato con una stringa contenente dati di percorso SVG. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | Aggiunge al percorso il percorso fornito come argomento. |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | Aggiunge al percorso il percorso fornito come argomento. |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | Aggiunge un arco al percorso centrato nella posizione (x, y) con raggio r, iniziando da startAngle e terminando a endAngle, procedendo nella direzione indicata in senso antiorario (predefinito in senso orario). |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | Aggiunge un arco al percorso centrato nella posizione (x, y) con raggio r, iniziando da startAngle e terminando a endAngle, procedendo nella direzione indicata in senso antiorario (predefinito in senso orario). |
| [arcTo](../../com.aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | Aggiunge un arco al percorso con i punti di controllo forniti e il raggio, collegato al punto precedente da una linea retta. |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | Aggiunge una curva Bézier cubica al percorso. Richiede tre punti. I primi due punti sono punti di controllo e il terzo è il punto finale. Il punto di partenza è l'ultimo punto nel percorso corrente, che può essere modificato usando moveTo() prima di creare la curva Bézier. |
| [closePath](../../com.aspose.html.dom.canvas/path2d/closepath/)() | Fa sì che il punto della penna torni all'inizio del sotto-percorso corrente. Tenta di disegnare una linea retta dal punto corrente all'inizio. Se la forma è già chiusa o ha solo un punto, questa funzione non fa nulla. |
| [dispose](../../com.aspose.html.dom.canvas/path2d/dispose/)() | Rilascia l'oggetto. |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | Aggiunge un'ellisse al percorso centrata nella posizione (x, y) con i raggi radiusX e radiusY, iniziando da startAngle e terminando a endAngle, procedendo nella direzione indicata in senso antiorario (predefinito in senso orario). |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Aggiunge un'ellisse al percorso centrata nella posizione (x, y) con i raggi radiusX e radiusY, iniziando da startAngle e terminando a endAngle, procedendo nella direzione indicata in senso antiorario (predefinito in senso orario). |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Questo metodo è usato per recuperare l'oggetto ECMAScript. |
| [lineTo](../../com.aspose.html.dom.canvas/path2d/lineto/)(double, double) | Collega l'ultimo punto del sotto-percorso alle coordinate x, y con una linea retta. |
| [moveTo](../../com.aspose.html.dom.canvas/path2d/moveto/)(double, double) | Sposta il punto di partenza di un nuovo sotto-percorso alle coordinate (x, y). |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | Aggiunge una curva Bézier quadratica al percorso corrente. |
| [rect](../../com.aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | Crea un percorso per un rettangolo nella posizione (x, y) con una dimensione determinata da larghezza e altezza. |

### Vedi anche

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
