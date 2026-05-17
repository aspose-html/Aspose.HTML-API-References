---
title: "IWindow.Atob"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة IWindow. تأخذ بيانات الإدخال على شكل سلسلة Unicode تحتوي على بيانات ثنائية مشفرة بـ base64، تقوم بفك تشفيرها وتعيد سلسلة تتكون من أحرف في النطاق U0000 إلى U00FF، كل منها يمثل بايت ثنائي بقيم 0x00 إلى 0xFF على التوالي، وفقًا لتلك البيانات الثنائية."
type: docs

url: /ar/java/com.aspose.html.window/iwindow/atob/
---
## IWindow.Atob method

يأخذ بيانات الإدخال على شكل سلسلة Unicode تحتوي على بيانات ثنائية مُشفَّرة بـ base64، يفكّ شفرتها، ويُعيد سلسلة تتكون من أحرف في النطاق U+0000 إلى U+00FF، كل حرف يمثل بايتًا ثنائيًا بقيم 0x00 إلى 0xFF على التوالي، بما يتطابق مع تلك البيانات الثنائية.

```java
public String Atob(String data)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | String | سلسلة Unicode التي تحتوي على بيانات ثنائية مشفرة بـ base64 |

### قيمة الإرجاع

السلسلة التي تتكون من أحرف في النطاق U+0000 إلى U+00FF

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | يرمي استثناء DOMException "InvalidCharacterError" إذا لم تكن سلسلة الإدخال بيانات base64 صالحة. |

### انظر أيضًا

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
