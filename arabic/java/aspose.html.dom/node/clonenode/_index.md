---
title: "Node.CloneNode"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة Node. تُعيد طريقة cloneNode في واجهة Node نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان يتم نسخ الشجرة الفرعية المحتواة في العقدة أم لا."
type: docs

url: /ar/java/com.aspose.html.dom/node/clonenode/
---
## CloneNode() {#clonenode}

طريقة cloneNode() الخاصة بواجهة Node تُعيد نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الشجرة الفرعية الموجودة داخل العقدة تُستنسخ أيضاً أم لا.

إن نسخ عقدة ينسخ جميع سماتها وقيمها، بما في ذلك المستمعين الداخليين (inline). لا ينسخ مستمعي الأحداث الذين تم إضافتهم باستخدام [`addEventListener()`](../../../com.aspose.html.dom.events/ieventtarget/addeventlistener/) أو الذين تم تعيينهم لخصائص العنصر (مثال: node.onclick = someFunction). بالإضافة إلى ذلك، بالنسبة لعنصر [`&lt;canvas&gt;`](../../../com.aspose.html/htmlcanvaselement/)، لا يتم نسخ الصورة المرسومة.

```java
public Node CloneNode()
```

### قيمة الإرجاع

العقدة الجديدة [`Node`](../) تم نسخها. العقدة المنسوخة لا تحتوي على أصل ولا تكون جزءًا من المستند، حتى يتم إضافتها إلى عقدة أخرى هي جزء من المستند، باستخدام [`Node.appendChild()`](../appendchild/) أو طريقة مشابهة.

### انظر أيضًا

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CloneNode(bool) {#clonenode_1}

طريقة cloneNode() الخاصة بواجهة Node تُعيد نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الشجرة الفرعية الموجودة داخل العقدة تُستنسخ أيضاً أم لا.

إن نسخ عقدة ينسخ جميع سماتها وقيمها، بما في ذلك المستمعين الداخليين (inline). لا ينسخ مستمعي الأحداث الذين تم إضافتهم باستخدام [addEventListener()](M:com.aspose.html.dom.events.IEventTarget.AddEventListener(System.String,com.aspose.html.dom.events.IEventListener)) أو الذين تم تعيينهم لخصائص العنصر (مثال: node.onclick = someFunction). بالإضافة إلى ذلك، بالنسبة لعنصر [&lt;canvas&gt;](T:Aspose.Html.HTMLCanvasElement)، لا يتم نسخ الصورة المرسومة.

```java
public Node CloneNode(bool deep)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| deep | Boolean | إذا كان true، فإن العقدة وشجرتها الفرعية بالكامل، بما في ذلك النص الذي قد يكون في عقد الأطفال [`Text`](../../text/)، يتم نسخها أيضًا. |

### قيمة الإرجاع

العقدة الجديدة [Node](T:com.aspose.html.dom.Node) تم نسخها. العقدة المنسوخة لا تحتوي على أصل ولا تكون جزءًا من المستند، حتى يتم إضافتها إلى عقدة أخرى هي جزء من المستند، باستخدام [Node.appendChild()](M:com.aspose.html.dom.Node.AppendChild(com.aspose.html.dom.Node)) أو طريقة مشابهة.

### انظر أيضًا

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
