---
title: "ISVGAnimatedPathData Интерфейс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.svg.paths.ISVGAnimatedPathData интерфейс. Интерфейс SVGAnimatedPathData поддерживает элементы, имеющие атрибут d, содержащий данные пути SVG, и поддерживает возможность анимировать этот атрибут."
type: docs

url: /ru/java/com.aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

Интерфейс SVGAnimatedPathData поддерживает элементы, имеющие атрибут ‘d’, содержащий данные пути SVG, и предоставляет возможность анимировать этот атрибут.

```java
public interface ISVGAnimatedPathData
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getAnimatedPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) Предоставляет доступ к текущему анимированному содержимому атрибута ‘d’ в форме, полностью соответствующей синтаксису SVG. Если указанный атрибут или свойство анимируется, содержит текущее анимированное значение атрибута или свойства, и как объект, так и его содержимое доступны только для чтения. Если указанный атрибут или свойство в данный момент не анимируется, содержит то же значение, что и pathSegList. |
| [getPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) Предоставляет доступ к базовому (т.е. статическому) содержимому атрибута ‘d’ в форме, полностью соответствующей синтаксису SVG. Таким образом, если атрибут ‘d’ содержит команду «абсолютный перемещение (M)» и команду «абсолютный арк (A)», то pathSegList будет иметь две записи: SVG_PATHSEG_MOVETO_ABS и SVG_PATHSEG_ARC_ABS. |

### См. также

* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
