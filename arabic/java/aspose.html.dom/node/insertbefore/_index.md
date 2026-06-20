---
title: "Node.InsertBefore"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة Node. تقوم طريقة insertBefore في واجهة Node بإدراج عقدة قبل عقدة مرجعية كطفل لعقدة أب محددة."
type: docs

url: /ar/java/com.aspose.html.dom/node/insertbefore/
---
## Node.InsertBefore method

طريقة insertBefore() الخاصة بواجهة Node تُدرج عقدة قبل عقدة مرجعية كطفل لعقدة أصلية محددة.

إذا كانت العقدة المعطاة موجودة بالفعل في المستند، فإن insertBefore() تنقلها من موقعها الحالي إلى الموقع الجديد. (أي أنه سيتم إزالتها تلقائيًا من الأب الحالي قبل إلحاقها بالأب الجديد المحدد.)

هذا يعني أن العقدة لا يمكن أن تكون في موقعين في المستند في آن واحد.

```java
public Node InsertBefore(Node node, Node child)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العقدة | Node | العقدة التي سيتم إدراجها. |
| العنصر الفرعي | Node | العقدة التي يُدرج قبلها newNode. إذا كانت هذه القيمة null، فسيُدرج newNode في نهاية عقد الأطفال. |

### قيمة الإرجاع

يعيد الطفل المضاف (ما لم يكن newNode هو [`DocumentFragment`](../../documentfragment/)، وفي هذه الحالة يتم إرجاع [`DocumentFragment`](../../documentfragment/) الفارغ).

### انظر أيضًا

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
