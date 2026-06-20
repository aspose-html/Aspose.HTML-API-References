---
title: "واجهة IWindowTimers"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "واجهة com.aspose.html.window.IWindowTimers. تسمح للمؤلفين بجدولة استدعاءات رد النداء القائمة على المؤقت."
type: docs

url: /ar/java/com.aspose.html.window/iwindowtimers/
---
## IWindowTimers interface

يسمح للمؤلفين بجدولة ردود نداء تعتمد على المؤقت.

```java
public interface IWindowTimers
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [clearInterval](../../com.aspose.html.window/iwindowtimers/clearinterval/)(int) | يلغي مهلة الوقت المحددة بواسطة setInterval() والمحددة بالمعرف handle. |
| [clearTimeout](../../com.aspose.html.window/iwindowtimers/cleartimeout/)(int) | يلغي مهلة الوقت المحددة بواسطة setTimeout() والمحددة بالمعرف handle. |
| [setInterval](../../com.aspose.html.window/iwindowtimers/setinterval/)(object, int, params object[]) | جدولة مهلة لتشغيل المعالج كل timeout مللي ثانية. يتم تمرير أي وسائط مباشرة إلى المعالج. |
| [setTimeout](../../com.aspose.html.window/iwindowtimers/settimeout/)(object, int, params object[]) | جدولة مهلة لتشغيل المعالج بعد timeout مللي ثانية. يتم تمرير أي وسائط مباشرة إلى المعالج. |

### انظر أيضًا

* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
