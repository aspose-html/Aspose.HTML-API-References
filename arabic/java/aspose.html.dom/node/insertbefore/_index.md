---
title: "Node.InsertBefore"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة Node. طريقة insertBefore في واجهة Node تُدرج عقدة قبل عقدة مرجعية كطفل لعقدة أب محددة"
type: docs

url: /ar/java/com.aspose.html.dom/node/insertbefore/
---
## Node.InsertBefore method

تُدرج طريقة insertBefore() في واجهة Node عقدة قبل عقدة مرجعية كطفل لعقدة أب محددة.

إذا كانت العقدة المعطاة موجودة بالفعل في المستند، فإن insertBefore() تنقلها من موقعها الحالي إلى الموقع الجديد. (أي أنها ستُزال تلقائيًا من الأب الحالي قبل إلحاقها بالأب الجديد المحدد.)

هذا يعني أن العقدة لا يمكن أن تكون في موقعين في المستند في آن واحد.

```java
public Node InsertBefore(Node node, Node child)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العقدة | Node | العقدة التي سيتم إدراجها. |
| العنصر | Node | العقدة التي يُدرج قبلها newNode. إذا كانت هذه القيمة null، فسيُدرج newNode في نهاية العقد الفرعية للعقدة. |

### قيمة الإرجاع

يرجع الطفل المضاف (ما لم يكن newNode هو [`DocumentFragment`](../../documentfragment/)، وفي هذه الحالة يُرجع [`DocumentFragment`](../../documentfragment/) الفارغ).

### انظر أيضًا

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
