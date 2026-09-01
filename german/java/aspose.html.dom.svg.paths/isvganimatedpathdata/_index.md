---
title: "ISVGAnimatedPathData Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.svg.paths.ISVGAnimatedPathData Schnittstelle. Das SVGAnimatedPathData Interface unterstützt Elemente, die ein d-Attribut besitzen, das SVG-Pfaddaten enthält, und ermöglicht die Animation dieses Attributs."
type: docs

url: /de/java/com.aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

Das SVGAnimatedPathData-Interface unterstützt Elemente, die ein ‘d’-Attribut besitzen, das SVG-Pfaddaten enthält, und unterstützt die Möglichkeit, dieses Attribut zu animieren.

```java
public interface ISVGAnimatedPathData
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getAnimatedPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) Bietet Zugriff auf die aktuellen animierten Inhalte des ‘d’-Attributs in einer Form, die eins-zu-eins mit der SVG‑Syntax übereinstimmt. Wenn das angegebene Attribut oder die Eigenschaft animiert wird, enthält es den aktuellen animierten Wert des Attributs oder der Eigenschaft, und sowohl das Objekt selbst als auch dessen Inhalte sind schreibgeschützt. Wenn das angegebene Attribut oder die Eigenschaft derzeit nicht animiert wird, enthält es denselben Wert wie pathSegList. |
| [getPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) Bietet Zugriff auf die Basis‑ (d.h. statischen) Inhalte des ‘d’-Attributs in einer Form, die eins-zu-eins mit der SVG‑Syntax übereinstimmt. So hat das ‘d’-Attribut, wenn es einen "absoluten moveto (M)"‑ und einen "absoluten arcto (A)"‑Befehl enthält, dann wird pathSegList zwei Einträge haben: einen SVG_PATHSEG_MOVETO_ABS und einen SVG_PATHSEG_ARC_ABS. |

### Siehe auch

* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
