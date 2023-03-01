---
title: Class PdfDevice.PdfGraphicContext
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Rendering.Pdf.PdfDevicePdfGraphicContext сорт. Содержит текущие параметры управления графикой для PdfDevice. Эти параметры определяют глобальную структуру в которой выполняются графические операторы.
type: docs
weight: 4450
url: /ru/net/aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext/
---
## PdfDevice.PdfGraphicContext class

Содержит текущие параметры управления графикой для PdfDevice. Эти параметры определяют глобальную структуру, в которой выполняются графические операторы.

```csharp
public class PdfGraphicContext : GraphicContext
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfGraphicContext](pdfgraphiccontext/)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Устанавливает или получает межсимвольный интервал. |
| override [FillBrush](../../aspose.html.rendering.pdf/pdfgraphiccontext/fillbrush/) { get; set; } | Устанавливает или получает объект кисти, который используется для заполнения внутренней части контуров. |
| virtual [Font](../../aspose.html.rendering/graphiccontext/font/) { get; set; } | Задает или получает объект шрифта истинного типа, который используется для рендеринга текста. |
| virtual [FontSize](../../aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Задает или получает размер шрифта текста. |
| virtual [FontStyle](../../aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Устанавливает или получает стиль шрифта текста. |
| override [LineCap](../../aspose.html.rendering.pdf/pdfgraphiccontext/linecap/) { get; set; } | Устанавливает или получает код, определяющий форму конечных точек для любого открытого пути, который обведен. |
| virtual [LineDashOffset](../../aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Устанавливает или получает смещение фазы текущего шаблона пунктирной линии. |
| virtual [LineDashPattern](../../aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Задает или получает описание шаблона пунктира, который будет использоваться при обводке контуров. |
| virtual [LineDashStyle](../../aspose.html.rendering/graphiccontext/linedashstyle/) { get; set; } | Наборы стилей штриховых линий штрихового контура. |
| override [LineJoin](../../aspose.html.rendering.pdf/pdfgraphiccontext/linejoin/) { get; set; } | Устанавливает или получает код, определяющий форму стыков между соединенными сегментами заштрихованного пути. |
| override [LineWidth](../../aspose.html.rendering.pdf/pdfgraphiccontext/linewidth/) { get; set; } | Устанавливает или получает толщину обводимых контуров. |
| override [MiterLimit](../../aspose.html.rendering.pdf/pdfgraphiccontext/miterlimit/) { get; set; } | Устанавливает или получает максимальную длину соединения линий под углом для обведенных путей. Этот параметр ограничивает длину «выступов», возникающих при соединении сегментов под острыми углами. |
| override [StrokeBrush](../../aspose.html.rendering.pdf/pdfgraphiccontext/strokebrush/) { get; set; } | Устанавливает или получает объект-кисть, который используется для обведенных контуров. |
| virtual [TextInfo](../../aspose.html.rendering/graphiccontext/textinfo/) { get; } | Получает[`TextInfo`](../../aspose.html.rendering/textinfo/) объект, который содержит информацию о отображаемом тексте. |
| override [TransformationMatrix](../../aspose.html.rendering.pdf/pdfgraphiccontext/transformationmatrix/) { get; set; } | Устанавливает или получает матрицу преобразования. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../aspose.html.rendering.pdf/pdfgraphiccontext/clone/)() | Создает новый экземпляр класса с теми же значениями свойств, что и существующий экземпляр. |
| override [Transform](../../aspose.html.rendering.pdf/pdfgraphiccontext/transform/)(Matrix) | Изменить текущую матрицу преобразования, умножив указанную матрицу. |

### Смотрите также

* class [GraphicContext](../../aspose.html.rendering/graphiccontext/)
* class [PdfDevice](../pdfdevice/)
* пространство имен [Aspose.Html.Rendering.Pdf](../../aspose.html.rendering.pdf/)
* сборка [Aspose.HTML](../../)


