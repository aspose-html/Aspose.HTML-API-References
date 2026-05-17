---
title: "Node.RemoveChild"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة Node. طريقة removeChild في واجهة Node تُزيل عقدة فرعية من DOM وتُرجع العقدة المُزالة."
type: docs

url: /ar/java/com.aspose.html.dom/node/removechild/
---
## Node.RemoveChild method

طريقة removeChild() في واجهة Node تزيل عقدةً فرعيةً من DOM وتعيد العقدة التي أزيلت.

ملاحظة: طالما تم الاحتفاظ بإشارة إلى العنصر الفرعي المُزال، فإنه لا يزال موجودًا في الذاكرة، لكنه لم يعد جزءًا من DOM. يمكن إعادة استخدامه لاحقًا في الشيفرة. إذا لم يتم تخزين القيمة المرجعة من removeChild() ولم تُحفظ أي إشارة أخرى، فسيتم حذفها تلقائيًا من الذاكرة بعد فترة قصيرة.

```java
public Node RemoveChild(Node child)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| child | Node | ـ[`Node`](../) التي هي العقدة الفرعية التي سيتم إزالتها من DOM. |

### قيمة الإرجاع

على عكس [`Node.cloneNode()`](../clonenode/) فإن القيمة المرجعة تحتفظ بكائنات [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/) المرتبطة بها.

### انظر أيضًا

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
