---
title: Interface ISVGAnimatedPathData
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Svg.Paths.ISVGAnimatedPathData интерфейс. Интерфейс SVGAnimatedPathData поддерживает элементы с атрибутом d который содержит данные пути SVG и поддерживает возможность анимации этого атрибута.
type: docs
weight: 1680
url: /ru/net/aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

Интерфейс SVGAnimatedPathData поддерживает элементы с атрибутом 'd', который содержит данные пути SVG, и поддерживает возможность анимации этого атрибута.

```csharp
public interface ISVGAnimatedPathData
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AnimatedPathSegList](../../aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) { get; } | Предоставляет доступ к текущему анимированному содержимому атрибута 'd' в форме, которая полностью соответствует синтаксису SVG. Если данный атрибут или свойство анимируется, содержит текущее анимированное значение атрибута или свойства, а сам объект и его содержимое доступны только для чтения. Если данный атрибут или свойство в настоящее время не анимируются, содержит то же значение, что и pathSegList. |
| [PathSegList](../../aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) { get; } | Предоставляет доступ к базовому (т.е. статическому) содержимому атрибута 'd' в форме, которая полностью соответствует синтаксису SVG. Таким образом, если атрибут 'd' имеет команду "абсолютный переход (M)" и "абсолютный arcto (A)", то pathSegList будет иметь две записи: SVG_PATHSEG_MOVETO_ABS и SVG_PATHSEG_ARC_ABS. |

### Смотрите также

* пространство имен [Aspose.Html.Dom.Svg.Paths](../../aspose.html.dom.svg.paths/)
* сборка [Aspose.HTML](../../)


