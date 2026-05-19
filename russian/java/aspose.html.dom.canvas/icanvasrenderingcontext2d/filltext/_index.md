---
title: "ICanvasRenderingContext2D.FillText"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод ICanvasRenderingContext2D. Рисует и заполняет заданный текст в указанной позиции xy."
type: docs

url: /ru/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/
---
## FillText(String, double, double) {#filltext}

Рисует (заполняет) заданный текст в указанной позиции (x,y).

```java
public void FillText(String text, double x, double y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| текст | String | Текст, который следует отрисовать, используя текущие значения шрифта, textAlign, textBaseline и direction. |
| x | Double | Ось x координаты начальной точки текста. |
| y | Double | Ось y координаты начальной точки текста. |

### См. также

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## FillText(String, double, double, double) {#filltext_1}

Рисует (заполняет) заданный текст в указанной позиции (x,y).

```java
public void FillText(String text, double x, double y, double maxWidth)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| текст | String | Текст, который следует отрисовать, используя текущие значения шрифта, textAlign, textBaseline и direction. |
| x | Double | Ось x координаты начальной точки текста. |
| y | Double | Ось y координаты начальной точки текста. |
| maxWidth | Double | Максимальная ширина для отрисовки. Если указано, и строка вычислена шире этой ширины, шрифт корректируется, чтобы использовать более горизонтально сжатый шрифт (если такой доступен или если можно синтезировать достаточно читаемый шрифт, масштабируя текущий шрифт по горизонтали) или меньший шрифт. |

### См. также

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
