---
title: Class DocDevice.DocGraphicContext
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Rendering.Doc.DocDeviceDocGraphicContext сорт. Содержит текущие параметры управления графикой для DocDevice. Эти параметры определяют глобальную структуру в которой выполняются графические операторы.
type: docs
weight: 4180
url: /ru/net/aspose.html.rendering.doc/docdevice.docgraphiccontext/
---
## DocDevice.DocGraphicContext class

Содержит текущие параметры управления графикой для DocDevice. Эти параметры определяют глобальную структуру, в которой выполняются графические операторы.

```csharp
public class DocGraphicContext : GraphicContext
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DocGraphicContext](docgraphiccontext/)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Устанавливает или получает межсимвольный интервал. |
| virtual [FillBrush](../../aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | Устанавливает или получает объект кисти, который используется для заполнения внутренней части контуров. |
| virtual [Font](../../aspose.html.rendering/graphiccontext/font/) { get; set; } | Задает или получает объект шрифта истинного типа, который используется для рендеринга текста. |
| virtual [FontSize](../../aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Задает или получает размер шрифта текста. |
| virtual [FontStyle](../../aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Устанавливает или получает стиль шрифта текста. |
| virtual [LineCap](../../aspose.html.rendering/graphiccontext/linecap/) { get; set; } | Устанавливает или получает код, определяющий форму конечных точек для любого открытого пути, который обведен. |
| virtual [LineDashOffset](../../aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Устанавливает или получает смещение фазы текущего шаблона пунктирной линии. |
| virtual [LineDashPattern](../../aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Задает или получает описание шаблона пунктира, который будет использоваться при обводке контуров. |
| virtual [LineDashStyle](../../aspose.html.rendering/graphiccontext/linedashstyle/) { get; set; } | Наборы стилей штриховых линий штрихового контура. |
| virtual [LineJoin](../../aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | Устанавливает или получает код, определяющий форму стыков между соединенными сегментами заштрихованного пути. |
| virtual [LineWidth](../../aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | Устанавливает или получает толщину обводимых контуров. |
| virtual [MiterLimit](../../aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | Устанавливает или получает максимальную длину соединения линий под углом для обведенных путей. Этот параметр ограничивает длину «выступов», возникающих при соединении сегментов под острыми углами. |
| virtual [StrokeBrush](../../aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | Устанавливает или получает объект-кисть, который используется для обведенных контуров. |
| virtual [TextInfo](../../aspose.html.rendering/graphiccontext/textinfo/) { get; } | Получает[`TextInfo`](../../aspose.html.rendering/textinfo/) объект, который содержит информацию о отображаемом тексте. |
| override [TransformationMatrix](../../aspose.html.rendering.doc/docgraphiccontext/transformationmatrix/) { get; set; } | Устанавливает или получает матрицу преобразования. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../aspose.html.rendering.doc/docgraphiccontext/clone/)() | Создает новый экземпляр[`GraphicContext`](../../aspose.html.rendering/graphiccontext/) класс с теми же значениями свойств, что и существующий экземпляр. |
| override [Transform](../../aspose.html.rendering.doc/docgraphiccontext/transform/)(Matrix) | Изменить текущую матрицу преобразования, умножив указанную матрицу. |

### Смотрите также

* class [GraphicContext](../../aspose.html.rendering/graphiccontext/)
* class [DocDevice](../docdevice/)
* пространство имен [Aspose.Html.Rendering.Doc](../../aspose.html.rendering.doc/)
* сборка [Aspose.HTML](../../)


