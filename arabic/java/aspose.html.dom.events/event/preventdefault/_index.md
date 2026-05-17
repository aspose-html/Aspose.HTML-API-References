---
title: "Event.PreventDefault"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة الحدث. إذا كان الحدث قابلًا للإلغاء تُستخدم طريقة PreventDefault للدلالة على أن الحدث سيُلغى مما يعني أن أي إجراء افتراضي عادةً ما تتخذّه التنفيذ نتيجةً للحدث لن يحدث."
type: docs

url: /ar/java/com.aspose.html.dom.events/event/preventdefault/
---
## Event.PreventDefault method

إذا كان الحدث قابلًا للإلغاء، تُستخدم طريقة `PreventDefault` للدلالة على أن الحدث سيُلغى، مما يعني أن أي إجراء افتراضي عادةً ما تتخذّه التنفيذ نتيجةً للحدث لن يحدث.

```java
public void PreventDefault()
```

## ملاحظات

إذا تم استدعاء طريقة `PreventDefault` خلال أي مرحلة من تدفق الحدث، يُلغى الحدث. أي إجراء افتراضي مرتبط بالحدث لن يحدث. استدعاء هذه الطريقة لحدث غير قابل للإلغاء لا يؤثر. بمجرد استدعاء `PreventDefault` ستظل سارية طوال ما تبقى من انتشار الحدث. يمكن استخدام هذه الطريقة خلال أي مرحلة من تدفق الحدث.

### انظر أيضًا

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
