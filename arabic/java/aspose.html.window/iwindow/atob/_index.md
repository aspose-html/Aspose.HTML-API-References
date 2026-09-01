---
title: "IWindow.Atob"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة IWindow. تأخذ بيانات الإدخال على شكل Unicode String يحتوي على بيانات ثنائية مشفرة بـ base64، تقوم بفك تشفيرها وتعيد سلسلة تتكون من أحرف في النطاق U0000 إلى U00FF، كل منها يمثل بايت ثنائي بقيم 0x00 إلى 0xFF على التوالي، وفقًا لتلك البيانات الثنائية."
type: docs

url: /ar/java/com.aspose.html.window/iwindow/atob/
---
## IWindow.Atob method

يأخذ بيانات الإدخال على شكل سلسلة Unicode تحتوي على بيانات ثنائية مشفرة بقاعدة 64، يفك تشفيرها، ويعيد سلسلة تتكون من أحرف في النطاق U+0000 إلى U+00FF، كل حرف يمثل بايتًا ثنائيًا بقيمة 0x00 إلى 0xFF على التوالي، مطابقة لتلك البيانات الثنائية.

```java
public String Atob(String data)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| بيانات | String | سلسلة Unicode التي تحتوي على بيانات ثنائية مشفرة بـ base64 |

### قيمة الإرجاع

السلسلة التي تتكون من أحرف في النطاق U+0000 إلى U+00FF

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | ترمي استثناء DOMException من نوع "InvalidCharacterError" إذا لم تكن سلسلة الإدخال بيانات base64 صالحة. |

### انظر أيضًا

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
