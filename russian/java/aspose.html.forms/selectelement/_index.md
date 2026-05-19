---
title: "Класс SelectElement"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.forms.SelectElement. SelectElement представляет собой оболочку, связанную с HTMLSelectElement."
type: docs

url: /ru/java/com.aspose.html.forms/selectelement/
---
## SelectElement class

SelectElement представляет обёртку, связанную с HTMLSelectElement.

```java
public class SelectElement : FormElement<HTMLSelectElement>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getElementType](../../com.aspose.html.forms/formelement/elementtype/) Получает тип элемента. |
| [getHtmlElement](../../com.aspose.html.forms/formelement-1/htmlelement/) |
| [id](../../com.aspose.html.forms/selectelement/id/) { get; set; } | Представляет атрибут Id элемента input. |
[getMultiple]
[setMultiple] If true, multiple `OPTION` elements may be selected in this `SELECT`. See the multiple attribute definition in HTML 4.01. |
| [name](../../com.aspose.html.forms/selectelement/name/) { get; set; } | Представляет атрибут name элемента input. |
| [getOptions](../../com.aspose.html.forms/selectelement/options/) Возвращает список вариантов. |
| [getSelectedOptions](../../com.aspose.html.forms/selectelement/selectedoptions/) Возвращает список выбранных вариантов. |
| [getType](../../com.aspose.html.forms/selectelement/type/) Тип этого элемента формы. Это строка "select-multiple", когда атрибут multiple имеет значение `true`, и строка "select-one", когда `false`. |
| [value](../../com.aspose.html.forms/selectelement/value/) { get; set; } | При получении должно возвращать значение первого элемента option в списке вариантов в порядке дерева, у которого свойство selected установлено в true, если такой есть. |

## Методы

| Имя | Описание |
| --- | --- |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems)(params int[]) | Этот метод позволяет выбирать несколько вариантов по их индексам. |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems_1)(params String[]) | Этот метод позволяет выбирать несколько вариантов по их значениям. |

### См. также

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLSelectElement](../../com.aspose.html/htmlselectelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
