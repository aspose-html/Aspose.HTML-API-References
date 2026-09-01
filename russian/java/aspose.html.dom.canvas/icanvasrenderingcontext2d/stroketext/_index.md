---
title: "ICanvasRenderingContext2D.StrokeText"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод ICanvasRenderingContext2D. Рисует обводку заданного текста в указанной позиции x и y."
type: docs

url: /ru/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/
---
## StrokeText(String, double, double) {#stroketext}

Рисует (обводит) заданный текст в указанной позиции (x, y).

```java
public void StrokeText(String text, double x, double y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | String | Текст, который нужно отрисовать, используя текущие значения шрифта, textAlign, textBaseline и direction. |
| x | Double | Ось x координаты начальной точки текста. |
| y | Double | Ось y координаты начальной точки текста. |

### См. также

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## StrokeText(String, double, double, double?) {#stroketext_1}

Рисует (обводит) заданный текст в указанной позиции (x, y).

```java
public void StrokeText(String text, double x, double y, double? maxWidth)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | String | Текст, который нужно отрисовать, используя текущие значения шрифта, textAlign, textBaseline и direction. |
| x | Double | Ось x координаты начальной точки текста. |
| y | Double | Ось y координаты начальной точки текста. |
| maxWidth | Nullable`1 | Максимальная ширина для отрисовки. Если указана и вычисленная строка оказывается шире этой ширины, шрифт корректируется, используя более горизонтально сжатый шрифт (если такой доступен или если его можно синтезировать, масштабируя текущий шрифт по горизонтали) или более маленький шрифт. |

### См. также

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
