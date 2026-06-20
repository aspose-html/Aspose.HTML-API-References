---
title: "INodeFilter.AcceptNode"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة INodeFilter.AcceptNode. اختبر ما إذا كانت عقدة محددة مرئية في العرض المنطقي لـ TreeWalker أو NodeIterator. ستستدعي هذه الدالة تنفيذ TreeWalker و NodeIterator، ولا تُستدعى عادةً مباشرةً من كود المستخدم. ومع ذلك يمكنك استدعاؤها إذا رغبت في استخدام نفس الفلتر لتوجيه منطق تطبيقك."
type: docs

url: /ar/java/com.aspose.html.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

اختبر ما إذا كانت عقدة محددة مرئية في العرض المنطقي لـ TreeWalker أو NodeIterator. سيتم استدعاء هذه الدالة من قبل تنفيذ TreeWalker و NodeIterator؛ عادةً لا يتم استدعاؤها مباشرةً من كود المستخدم. (مع ذلك يمكنك القيام بذلك إذا أردت استخدام نفس الفلتر لتوجيه منطق تطبيقك.)

```java
public short AcceptNode(Node n)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| n | Node | العقدة للتحقق مما إذا كانت تجتاز الفلتر أم لا. |

### قيمة الإرجاع

ثابت لتحديد ما إذا كانت العقدة مقبولة أو مرفوضة أو متخطاة، كما هو معرف أعلاه.

### انظر أيضًا

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
