---
title: "Interfaccia ISVGAnimatedPathData"
second_title: "Aspose.HTML per Java Riferimento API"
description: "interfaccia com.aspose.html.dom.svg.paths.ISVGAnimatedPathData. L'interfaccia SVGAnimatedPathData supporta gli elementi che hanno un attributo d che contiene dati di percorso SVG e consente di animare tale attributo"
type: docs

url: /it/java/com.aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

L'interfaccia SVGAnimatedPathData supporta gli elementi che hanno un attributo ‘d’ che contiene dati di percorso SVG, e supporta la possibilità di animare tale attributo.

```java
public interface ISVGAnimatedPathData
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getAnimatedPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) Fornisce l'accesso al contenuto animato corrente dell'attributo ‘d’ in una forma che corrisponde uno a uno alla sintassi SVG. Se l'attributo o la proprietà specificata è in animazione, contiene il valore animato corrente dell'attributo o della proprietà, e sia l'oggetto stesso sia i suoi contenuti sono di sola lettura. Se l'attributo o la proprietà specificata non è attualmente in animazione, contiene lo stesso valore di pathSegList. |
| [getPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) Fornisce l'accesso al contenuto di base (cioè statico) dell'attributo ‘d’ in una forma che corrisponde uno a uno alla sintassi SVG. Quindi, se l'attributo ‘d’ ha un comando "moveto assoluto (M)" e un comando "arcto assoluto (A)", allora pathSegList conterrà due voci: un SVG_PATHSEG_MOVETO_ABS e un SVG_PATHSEG_ARC_ABS. |

### Vedi anche

* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
