---
title: "Класс PdfDevice.PdfGraphicContext"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.rendering.pdf.PdfDevicePdfGraphicContext. Содержит текущие параметры управления графикой для PdfDevice. Эти параметры определяют глобальную структуру, в которой выполняются графические операторы."
type: docs

url: /ru/java/com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext/
---
## PdfDevice.PdfGraphicContext class

Содержит текущие параметры управления графикой для PdfDevice. Эти параметры определяют глобальную структуру, в которой выполняются графические операторы.

```java
public class PdfGraphicContext : GraphicContext
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [pdfGraphicContext](../../com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext/.ctor)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [characterSpacing](../../com.aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Устанавливает или получает межсимвольный интервал. |
| [fillBrush](../../com.aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | Устанавливает или получает объект кисти, используемый для заполнения внутренних областей путей. |
| [font](../../com.aspose.html.rendering/graphiccontext/font/) { get; set; } | Устанавливает или получает объект шрифта TrueType, используемый для отображения текста. |
| [fontSize](../../com.aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Устанавливает или получает размер шрифта текста. |
| [fontStyle](../../com.aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Устанавливает или получает стиль шрифта текста. |
| [lineCap](../../com.aspose.html.rendering/graphiccontext/linecap/) { get; set; } | Устанавливает или получает код, определяющий форму конечных точек любого открытого контура, который обводится. |
| [lineDashOffset](../../com.aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Устанавливает или получает фазовый сдвиг текущего шаблона штриховки линии. |
| [lineDashPattern](../../com.aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Устанавливает или получает описание шаблона штриховки, используемого при обводке контуров. |
| [lineJoin](../../com.aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | Устанавливает или получает код, определяющий форму соединений между смежными сегментами обводимого контура. |
| [lineWidth](../../com.aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | Устанавливает или получает толщину обводимых контуров. |
| [miterLimit](../../com.aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | Устанавливает или получает максимальную длину срезов соединений линий для обводимых контуров. Этот параметр ограничивает длину \"зубцов\", образующихся при соединении сегментов линий под острыми углами. |
| [strokeBrush](../../com.aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | Устанавливает или получает объект кисти, используемый для обводки контуров. |
| [getTextInfo](../../com.aspose.html.rendering/graphiccontext/textinfo/) Получает объект [`TextInfo`](../../com.aspose.html.rendering/textinfo/), содержащий информацию о отрисованном тексте. |
| [transformationMatrix](../../com.aspose.html.rendering/graphiccontext/transformationmatrix/) { get; set; } | Устанавливает или получает матрицу преобразования. |

## Методы

| Имя | Описание |
| --- | --- |
| [clone](../../com.aspose.html.rendering/graphiccontext/clone/)() | Создаёт новый экземпляр класса GraphicContext с теми же значениями свойств, что и у существующего экземпляра. |
| [transform](../../com.aspose.html.rendering/graphiccontext/transform/)(IMatrix) | Изменяет текущую матрицу преобразования, умножая её на указанную матрицу. |

### См. также

* class [GraphicContext](../../com.aspose.html.rendering/graphiccontext/)
* class [PdfDevice](../pdfdevice/)
* package [com.aspose.html.rendering.pdf](../../com.aspose.html.rendering.pdf/)
* package [Aspose.HTML](../../)
