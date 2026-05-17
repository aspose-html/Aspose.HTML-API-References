---
title: "واجهة IElementTraversal"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "واجهة com.aspose.html.dom.traversal.IElementTraversal. واجهة ElementTraversal هي مجموعة من السمات للقراءة فقط التي تسمح للمؤلف بالتنقل بسهولة بين العناصر في المستند. في التطبيقات المتوافقة مع Element Traversal، يجب على جميع الكائنات التي تنفّذ Element أن تنفّذ أيضًا واجهة ElementTraversal."
type: docs

url: /ar/java/com.aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

واجهة ElementTraversal هي مجموعة من الخصائص للقراءة فقط تسمح للمؤلف بالتنقل بسهولة بين العناصر في المستند. في التطبيقات المتوافقة مع Element Traversal، يجب على جميع الكائنات التي تنفذ Element أن تنفذ أيضاً واجهة ElementTraversal.

```java
public interface IElementTraversal
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getChildElementCount](../../com.aspose.html.dom.traversal/ielementtraversal/childelementcount/) يُعيد العدد الحالي لعقد العنصر التي هي أبناء لهذا العنصر. 0 إذا لم يكن لهذا العنصر أي عقدة فرعية من نوع nodeType 1. |
| [getFirstElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/firstelementchild/) يُعيد أول عقدة عنصر فرعية لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر فرعية. |
| [getLastElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/lastelementchild/) يُعيد آخر عقدة عنصر فرعية لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر فرعية. |
| [getNextElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) يُعيد عقدة العنصر الأخ التالي لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد أخ عنصرية تأتي بعده في شجرة المستند. |
| [getPreviousElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) يُعيد عقدة العنصر الأخ السابق لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد أخ عنصرية تأتي قبلها في شجرة المستند. |

### انظر أيضًا

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
