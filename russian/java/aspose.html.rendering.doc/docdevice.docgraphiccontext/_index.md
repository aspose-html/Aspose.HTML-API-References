---
title: "Класс DocDevice.DocGraphicContext"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.rendering.doc.DocDeviceDocGraphicContext. Содержит текущие параметры управления графикой для DocDevice. Эти параметры определяют глобальную структуру, в которой выполняются графические операторы"
type: docs

url: /ru/java/com.aspose.html.rendering.doc/docdevice.docgraphiccontext/
---
## DocDevice.DocGraphicContext class

Содержит текущие параметры управления графикой для DocDevice. Эти параметры определяют глобальную структуру, в которой выполняются графические операторы.

```java
public class DocGraphicContext : GraphicContext
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [docGraphicContext](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/.ctor)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [characterSpacing](../../com.aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | Устанавливает или получает межсимвольный интервал. |
| [fillBrush](../../com.aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | Устанавливает или получает объект кисти, используемый для заполнения внутренностей путей. |
| [font](../../com.aspose.html.rendering/graphiccontext/font/) { get; set; } | Устанавливает или получает объект шрифта TrueType, используемый для рендеринга текста. |
| [fontSize](../../com.aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | Устанавливает или получает размер шрифта текста. |
| [fontStyle](../../com.aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | Устанавливает или получает стиль шрифта текста. |
| [lineCap](../../com.aspose.html.rendering/graphiccontext/linecap/) { get; set; } | Устанавливает или получает код, определяющий форму конечных точек любого открытого контура, который обводится. |
| [lineDashOffset](../../com.aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | Устанавливает или получает фазовое смещение текущего шаблона пунктирной линии. |
| [lineDashPattern](../../com.aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | Устанавливает или получает описание шаблона пунктиров, используемого при обводке контуров. |
| [lineJoin](../../com.aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | Устанавливает или получает код, определяющий форму соединений между связанными сегментами обводимого контура. |
| [lineWidth](../../com.aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | Устанавливает или получает толщину контуров для обводки. |
| [miterLimit](../../com.aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | Устанавливает или получает максимальную длину срезов соединений линий для обводимых контуров. Этот параметр ограничивает длину «зубцов», образующихся при соединении сегментов линий под острыми углами. |
| [strokeBrush](../../com.aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | Устанавливает или получает объект кисти, используемый для обводимых контуров. |
| [getTextInfo](../../com.aspose.html.rendering/graphiccontext/textinfo/) Получает объект [`TextInfo`](../../com.aspose.html.rendering/textinfo/), который содержит информацию о отрисованном тексте. |
| [transformationMatrix](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/transformationmatrix) { get; set; } | Устанавливает или получает матрицу преобразования. |

## Методы

| Имя | Описание |
| --- | --- |
| [clone](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/clone)() | Создаёт новый экземпляр класса [`GraphicContext`](../../com.aspose.html.rendering/graphiccontext/) с теми же значениями свойств, что и у существующего экземпляра. |
| [transform](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext/transform)(IMatrix) | Изменяет текущую матрицу преобразования, умножая её на указанную матрицу. |

### См. также

* class [GraphicContext](../../com.aspose.html.rendering/graphiccontext/)
* class [DocDevice](../docdevice/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)
