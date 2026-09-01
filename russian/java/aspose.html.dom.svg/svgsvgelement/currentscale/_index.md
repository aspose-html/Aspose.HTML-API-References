---
title: "SVGSVGElement.CurrentScale"
second_title: "Справочник API Aspose.HTML для Java"
description: "Свойство SVGSVGElement. На внешнем элементе svg этот атрибут указывает текущий коэффициент масштабирования относительно начального представления, учитывая увеличение пользователем и операции панорамирования, как описано в разделе «Увеличение и панорамирование». Атрибуты DOM currentScale и currentTranslate эквивалентны 2x3 матрице a b c d e f  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y. Если увеличение включено, т.е. zoomAndPanmagnify, то эффект аналогичен добавлению дополнительного преобразования на внешнем уровне фрагмента SVG‑документа, т.е. за пределами внешнего элемента svg. При доступе к атрибуту на элементе svg, который не является внешним, поведение этого атрибута не определено."
type: docs

url: /ru/java/com.aspose.html.dom.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

На внешнем элементе svg этот атрибут указывает текущий коэффициент масштабирования относительно начального представления, учитывая увеличение пользователем и операции панорамирования, как описано в разделе «Увеличение и панорамирование». Атрибуты DOM currentScale и currentTranslate эквивалентны 2x3 матрице [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. Если включено \"magnification\" (т.е. zoomAndPan=\"magnify\"), то эффект аналогичен добавлению дополнительного преобразования на внешнем уровне фрагмента SVG‑документа (т.е. за пределами внешнего элемента svg). При доступе к атрибуту на элементе ‘svg’, который не является внешним, поведение этого атрибута не определено.

```java
public float CurrentScale { get; set; }
```

### Property Value

Текущий масштаб.

### См. также

* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
