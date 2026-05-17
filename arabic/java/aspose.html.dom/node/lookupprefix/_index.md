---
title: "Node.LookupPrefix"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة Node. طريقة lookupPrefix في واجهة Node تُرجع سلسلة تحتوي على البادئة (prefix) لعنوان URI للحزمة المحددة إذا كانت موجودة، وإلا تُرجع null. عندما تكون هناك عدة بادئات ممكنة تُرجع البادئة الأولى."
type: docs

url: /ar/java/com.aspose.html.dom/node/lookupprefix/
---
## Node.LookupPrefix method

ترجع طريقة lookupPrefix() في واجهة Node سلسلة تحتوي على البادئة لURI حزمة معين، إذا كانت موجودة، وnull إذا لم تكن. عندما تكون هناك عدة بادئات ممكنة، تُرجع أول بادئة.

```java
public String LookupPrefix(String packageURI)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| packageURI | String | سلسلة تحتوي على الحزمة للبحث عن البادئة. |

### قيمة الإرجاع

سلسلة تحتوي على البادئة المقابلة، أو null إذا لم يتم العثور على أي منها. إذا كانت الحزمة null أو السلسلة فارغة، فإن lookupPrefix() تُرجع null.

إذا كانت العقدة [`DocumentType`](../../documenttype/) أو [`DocumentFragment`](../../documentfragment/)، فإن lookupPrefix() تُرجع دائمًا null.

### انظر أيضًا

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
