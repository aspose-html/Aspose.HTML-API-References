---
title: "ITraversal Interface"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "واجهة com.aspose.html.dom.traversal.ITraversal. تُستخدم المكررات (Iterators) للتنقل عبر مجموعة من العقد، مثل مجموعة العقد في NodeList، أو شجرة المستند التي تحكمها عقدة معينة، أو نتائج استعلام أو أي مجموعة أخرى من العقد. تُحدد مجموعة العقد التي سيتم تكرارها من قبل تنفيذ NodeIterator. يحدد DOM Level 2 تنفيذًا واحدًا لـ NodeIterator لتجوال المستند بترتيب الوثيقة لشجرة المستند. يتم إنشاء مثيلات هذه المكررات عن طريق استدعاء DocumentTraversal.createNodeIterator."
type: docs

url: /ar/java/com.aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

تُستخدم المتكررات للانتقال عبر مجموعة من العقد، مثل مجموعة العقد في NodeList، أو شجرة المستند الفرعية التي يتحكم فيها عقدة معينة، أو نتائج استعلام، أو أي مجموعة أخرى من العقد. تُحدد مجموعة العقد التي سيتم تكرارها بواسطة تنفيذ NodeIterator. يحدد DOM Level 2 تنفيذًا واحدًا لـ NodeIterator لتصفح شجرة المستند الفرعية بترتيب المستند. تُنشأ مثيلات هذه المتكررات باستدعاء DocumentTraversal .createNodeIterator().

انظر أيضًا إلى [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITraversal : IDisposable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getFilter](../../com.aspose.html.dom.traversal/itraversal/filter/) NodeFilter المستخدم لتصفية العقد. |
| [getRoot](../../com.aspose.html.dom.traversal/itraversal/root/) العقدة الجذرية لـ NodeIterator، كما تم تحديدها عند إنشائه. |
| [getWhatToShow](../../com.aspose.html.dom.traversal/itraversal/whattoshow/) هذه الخاصية تحدد أي أنواع العقد تُعرض عبر المكرّر. مجموعة الثوابت المتاحة مُعرفة في واجهة NodeFilter. العقد التي لا تُقبل بواسطة whatToShow سيتم تخطيها، لكن قد تُؤخذ أبناؤها في الاعتبار. لاحظ أن هذا التخطي له أولوية على الفلتر، إذا كان موجودًا. |

### انظر أيضًا

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
