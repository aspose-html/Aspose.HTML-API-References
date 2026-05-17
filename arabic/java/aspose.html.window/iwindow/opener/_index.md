---
title: "IWindow.Opener"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "IWindow خاصية. يجب أن تُعيد سمة opener IDL على كائن Window عند القراءة كائن WindowProxy لسياق التصفح الذي تم إنشاء سياق التصفح الحالي منه (سياق التصفح المفتاح إذا كان موجوداً وما زال متاحاً ولم يتخلَّ سياق التصفح الحالي عن المفتاح) وإلا تُعيد null. عند الكتابة، إذا كانت القيمة الجديدة null يجب على سياق التصفح الحالي أن يتخلى عن المفتاح الخاص به؛ إذا كانت القيمة الجديدة أي شيء آخر يجب على وكيل المستخدم استدعاء الطريقة الداخلية DefineOwnProperty لكائن Window مع تمرير اسم الخاصية \"opener\" كمفتاح للخاصية وواصف الخاصية { Value: value, Writable: true, Enumerable: true, Configurable: true } حيث value هي القيمة الجديدة."
type: docs

url: /ar/java/com.aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

سمة opener IDL على كائن Window، عند القراءة، يجب أن تُعيد كائن WindowProxy لسياق التصفح الذي تم إنشاء سياق التصفح الحالي منه (سياق التصفح المفتاح)، إذا كان موجوداً، وإذا كان ما زال متاحاً، وإذا لم يتخلَّ سياق التصفح الحالي عن المفتاح؛ وإلا يجب أن تُعيد null. عند الكتابة، إذا كانت القيمة الجديدة null يجب على سياق التصفح الحالي أن يتخلى عن المفتاح؛ إذا كانت القيمة الجديدة أي شيء آخر يجب على وكيل المستخدم استدعاء الطريقة الداخلية [[DefineOwnProperty]] لكائن Window، مع تمرير اسم الخاصية "opener" كمفتاح للخاصية، وواصف الخاصية { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } كواصف للخاصية، حيث value هي القيمة الجديدة.

```java
public IWindow Opener { get; }
```

### Property Value

المفتاح.

### انظر أيضًا

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
