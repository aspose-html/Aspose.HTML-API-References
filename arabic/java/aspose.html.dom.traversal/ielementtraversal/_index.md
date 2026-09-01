---
title: "واجهة IElementTraversal"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "واجهة com.aspose.html.dom.traversal.IElementTraversal. تُعد واجهة ElementTraversal مجموعة من السمات للقراءة فقط التي تسمح للمؤلف بالتنقل بسهولة بين العناصر في المستند. في تنفيذات Element Traversal المتوافقة، يجب على جميع الكائنات التي تُنفّذ Element أيضًا تنفيذ واجهة ElementTraversal."
type: docs

url: /ar/java/com.aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

واجهة ElementTraversal هي مجموعة من الخصائص للقراءة فقط تسمح للمؤلف بالتنقل بسهولة بين العناصر في المستند. في تنفيذات Element Traversal المتوافقة، يجب على جميع الكائنات التي تنفذ Element أن تنفذ أيضًا واجهة ElementTraversal.

```java
public interface IElementTraversal
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getChildElementCount](../../com.aspose.html.dom.traversal/ielementtraversal/childelementcount/) يُعيد العدد الحالي لعقد العنصر التي هي أبناء لهذا العنصر. 0 إذا لم يكن لهذا العنصر أي عقد أبناء من النوع nodeType 1. |
| [getFirstElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/firstelementchild/) يُعيد أول عقدة عنصر ابن لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر أبناء. |
| [getLastElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/lastelementchild/) يُعيد آخر عقدة عنصر ابن لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر أبناء. |
| [getNextElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) يُعيد عقدة العنصر الشقيقة التالية لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد شقيقة عنصر تأتي بعده في شجرة المستند. |
| [getPreviousElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) يُعيد عقدة العنصر الشقيقة السابقة لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد شقيقة عنصر تأتي قبلها في شجرة المستند. |

### انظر أيضًا

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
