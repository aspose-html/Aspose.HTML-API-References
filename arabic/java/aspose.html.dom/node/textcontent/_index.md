---
title: "Node.TextContent"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "خاصية Node. تمثل خاصية textContent في واجهة Node محتوى النص للعقدة وفروعها"
type: docs

url: /ar/java/com.aspose.html.dom/node/textcontent/
---
## Node.TextContent property

خاصية textContent في واجهة [`Node`](../) تمثل محتوى النص للعقدة وفروعها.

```java
public String TextContent { get; set; }
```

### Property Value

سلسلة نصية، أو null. قيمتها تعتمد على الحالة:

إذا كان العقدة مستندًا أو نوع مستند (doctype)، فإن textContent تُرجع null. ملاحظة: للحصول على كل النص وبيانات CDATA للمستند بأكمله، استخدم document.documentElement.textContent. إذا كانت العقدة قسم CDATA أو تعليقًا أو تعليمًا للمعالجة أو عقدة نصية، فإن textContent تُرجع أو تُعيّن النص داخل العقدة، أي [`Node.nodeValue`](../nodevalue/). بالنسبة لأنواع العقد الأخرى، تُرجع textContent concatenation لنصوص textContent لكل عقدة فرعية، مع استبعاد التعليقات وتعليمات المعالجة.

## ملاحظات

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-textcontent](https://dom.spec.whatwg.org/#dom-node-textcontent).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### انظر أيضًا

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
