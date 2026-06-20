---
title: "Node.LookupPrefix"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة Node. طريقة lookupPrefix في واجهة Node تُعيد سلسلة نصية تحتوي على البادئة لعنوان URI للحزمة المحددة إذا كانت موجودة، وتُعيد null إذا لم تكن. عندما تكون هناك عدة بادئات ممكنة، تُعيد البادئة الأولى."
type: docs

url: /ar/java/com.aspose.html.dom/node/lookupprefix/
---
## Node.LookupPrefix method

طريقة lookupPrefix() الخاصة بواجهة Node تُعيد سلسلة تحتوي على البادئة لعنوان حزمة URI معين، إذا كانت موجودة، وnull إذا لم تكن. عندما تكون هناك عدة بادئات ممكنة، تُعيد أول بادئة.

```java
public String LookupPrefix(String packageURI)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| packageURI | String | سلسلة نصية تحتوي على الحزمة للبحث عن البادئة. |

### قيمة الإرجاع

سلسلة نصية تحتوي على البادئة المقابلة، أو null إذا لم يتم العثور على أي منها. إذا كانت الحزمة null، أو السلسلة فارغة، تُعيد lookupPrefix() null.

إذا كانت العقدة [`DocumentType`](../../documenttype/) أو [`DocumentFragment`](../../documentfragment/)، فإن lookupPrefix() تُعيد دائمًا null.

### انظر أيضًا

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
