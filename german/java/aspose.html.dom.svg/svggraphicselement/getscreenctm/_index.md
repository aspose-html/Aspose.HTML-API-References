---
title: "SVGGraphicsElement.GetScreenCTM"
second_title: "Aspose.HTML für Java API-Referenz"
description: "SVGGraphicsElement-Methode. Gibt die Transformationsmatrix von den aktuellen Benutzereinheiten zurück, d. h. nach Anwendung des Transformationsattributs, falls vorhanden, auf die übergeordnete Benutzereinheit, die einem Pixel entspricht. Für Anzeigegeräte stellt sie idealerweise ein physikalisches Bildschirmpixel dar. Für andere Geräte oder Umgebungen, in denen die physikalische Pixelgröße nicht bekannt ist, kann stattdessen ein Algorithmus verwendet werden, der der CSS2-Definition eines Pixels ähnelt. Hinweis: Es wird null zurückgegeben, wenn dieses Element nicht im Dokumentbaum verankert ist. Diese Methode hätte besser getClientCTM heißen können, aber der Name getScreenCTM wird aus historischen Gründen beibehalten"
type: docs

url: /de/java/com.aspose.html.dom.svg/svggraphicselement/getscreenctm/
---
## SVGGraphicsElement.GetScreenCTM method

Gibt die Transformationsmatrix von den aktuellen Benutzereinheiten (d. i. nach Anwendung des Attributs ‘transform’, falls vorhanden) zur Wahrnehmung eines \"pixel\" durch den übergeordneten User‑Agent zurück. Für Anzeigegeräte entspricht dies idealerweise einem physischen Bildschirm‑Pixel. Für andere Geräte oder Umgebungen, in denen die physische Pixelgröße nicht bekannt ist, kann stattdessen ein Algorithmus verwendet werden, der der CSS2‑Definition eines \"pixel\" ähnelt. Hinweis: Es wird null zurückgegeben, wenn dieses Element nicht im Dokumentbaum verankert ist. Diese Methode hätte besser den Namen getClientCTM tragen können, aber der Name getScreenCTM wird aus historischen Gründen beibehalten.

```java
public SVGMatrix GetScreenCTM()
```

### Rückgabewert

Ein SVGMatrix-Objekt, das die gegebene Transformationsmatrix definiert.

### Siehe auch

* class [SVGMatrix](../../../com.aspose.html.dom.svg.datatypes/svgmatrix/)
* class [SVGGraphicsElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
