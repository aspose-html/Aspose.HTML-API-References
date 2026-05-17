---
title: "فئة SelectElement"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "فئة com.aspose.html.forms.SelectElement. تمثل SelectElement غلافًا مرتبطًا بـ HTMLSelectElement."
type: docs

url: /ar/java/com.aspose.html.forms/selectelement/
---
## SelectElement class

العنصر SelectElement يمثل غلافًا مرتبطًا بـ HTMLSelectElement.

```java
public class SelectElement : FormElement<HTMLSelectElement>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getElementType](../../com.aspose.html.forms/formelement/elementtype/) يحصل على نوع العنصر. |
| [getHtmlElement](../../com.aspose.html.forms/formelement-1/htmlelement/) |
| [id](../../com.aspose.html.forms/selectelement/id/) { get; set; } | يمثل سمة Id لعنصر الإدخال. |
[getMultiple]
[setMultiple] If true, multiple `OPTION` elements may be selected in this `SELECT`. See the multiple attribute definition in HTML 4.01. |
| [name](../../com.aspose.html.forms/selectelement/name/) { get; set; } | يمثل سمة name لعنصر الإدخال. |
| [getOptions](../../com.aspose.html.forms/selectelement/options/) يُرجِع قائمة من الخيارات |
| [getSelectedOptions](../../com.aspose.html.forms/selectelement/selectedoptions/) يُرجِع قائمة من الخيارات المحددة |
| [getType](../../com.aspose.html.forms/selectelement/type/) نوع عنصر التحكم في النموذج هذا. يكون السلسلة \"select-multiple\" عندما تكون السمة multiple `true` والسلسلة \"select-one\" عندما تكون `false`. |
| [value](../../com.aspose.html.forms/selectelement/value/) { get; set; } | عند الاستدعاء، يجب إرجاع قيمة أول عنصر خيار في قائمة الخيارات بترتيب الشجرة الذي تم تعيين خاصية الاختيار له إلى true، إذا وجد. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems)(params int[]) | هذه الطريقة تسمح باختيار خيارات متعددة حسب فهارسها. |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems_1)(params String[]) | هذه الطريقة تسمح باختيار خيارات متعددة حسب قيمها. |

### انظر أيضًا

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLSelectElement](../../com.aspose.html/htmlselectelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
