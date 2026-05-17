---
title: "INodeFilter.AcceptNode"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة INodeFilter. تختبر ما إذا كانت عقدة محددة مرئية في العرض المنطقي لـ TreeWalker أو NodeIterator. ستُستدعى هذه الدالة من قبل تنفيذ TreeWalker و NodeIterator ولا تُستدعى عادةً مباشرةً من كود المستخدم. ومع ذلك يمكنك استدعاؤها إذا أردت استخدام نفس المرشح لتوجيه منطق تطبيقك."
type: docs

url: /ar/java/com.aspose.html.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

اختبر ما إذا كانت عقدة محددة مرئية في العرض المنطقي لـ TreeWalker أو NodeIterator. سيتم استدعاء هذه الدالة من قبل تنفيذ TreeWalker و NodeIterator؛ عادةً لا يتم استدعاؤها مباشرةً من كود المستخدم. (مع ذلك يمكنك فعل ذلك إذا أردت استخدام نفس الفلتر لتوجيه منطق تطبيقك.)

```java
public short AcceptNode(Node n)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| n | Node | العقدة التي يتم فحصها لمعرفة ما إذا كانت تجتاز المرشح أم لا. |

### قيمة الإرجاع

ثابت لتحديد ما إذا كانت العقدة مقبولة أو مرفوضة أو متخطاة، كما هو معرف أعلاه.

### انظر أيضًا

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
