---
title: "فئة FormEditor"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "فئة com.aspose.html.forms.FormEditor. تمثل هذه الفئة المحرر فوق HTMLFormElement الذي يوفر طريقة أسهل لمطوري .net لتعديل نماذج html."
type: docs

url: /ar/java/com.aspose.html.forms/formeditor/
---
## FormEditor class

تمثل هذه الفئة المحرر فوق [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) الذي يوفر طريقة أسهل لمطوري .net لتعديل نماذج html.

```java
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
| [getCount](../../com.aspose.html.forms/formeditor/count/) عدد عناصر التحكم في النموذج. |
| [getForm](../../com.aspose.html.forms/formeditor/form/) العنصر الأصلي [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) المرتبط بالمثيل الحالي من `FormEditor`. |
| [getItem](../../com.aspose.html.forms/formeditor/item/) يُرجِع العنصر وفق الفهرس المحدد. (2 فهارس) |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | ينشئ `FormEditor` جديدًا استنادًا إلى [`HTMLFormElement`](../../com.aspose.html/htmlformelement/). |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | ينشئ `FormEditor` جديدًا استنادًا إلى [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) المحدد من مجموعة [`Forms`](../../com.aspose.html/htmldocument/forms/) حسب الفهرس. |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, String) | ينشئ `FormEditor` جديدًا استنادًا إلى [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) المحدد من المستند حسب المعرف. |
| static [CreateNew](../../com.aspose.html.forms/formeditor/createnew/)(HTMLDocument) | ينشئ [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) جديدًا ويربطه بـ `FormEditor`. يتم إنشاء [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) في حالة منفصلة عن المستند؛ لإرفاقه بالمستند، يرجى اختيار الموقع المناسب واستخدام طريقة [`AppendChild`](../../com.aspose.html.dom/node/appendchild/). |
| [Add&lt;T&gt;](../../com.aspose.html.forms/formeditor/add/)(String) | ينشئ [`HTMLElement`](../../com.aspose.html/htmlelement/) جديدًا ويضيفه إلى نهاية النموذج. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput)(String) | ينشئ [`InputElement`](../inputelement/) جديدًا ويضيفه إلى نهاية النموذج. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput_1)(String, InputElementType) | ينشئ [`InputElement`](../inputelement/) جديدًا ويضيفه إلى نهاية النموذج. |
| [dispose](../../com.aspose.html.forms/formeditor/dispose/)() | يطلق الموارد غير المُدارة والمُدارة. |
| [fill](../../com.aspose.html.forms/formeditor/fill/)(Dictionary&lt;String, String&gt;) |  |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement)(int) | يُرجِع العنصر وفق الفهرس المحدد. |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement_1)(String) | يُرجِع العنصر وفق الاسم المحدد. |
| [getEnumerator](../../com.aspose.html.forms/formeditor/getenumerator/)() | الحصول على المُعدِّد. |

### انظر أيضًا

* class [FormElement](../formelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
