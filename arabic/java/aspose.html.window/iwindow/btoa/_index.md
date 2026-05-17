---
title: "IWindow.Btoa"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة IWindow. تأخذ بيانات الإدخال على شكل سلسلة Unicode تحتوي فقط على أحرف في النطاق U0000 إلى U00FF، كل منها يمثل بايت ثنائي بقيم 0x00 إلى 0xFF على التوالي، وتحولها إلى تمثيل base64 وتعيده"
type: docs

url: /ar/java/com.aspose.html.window/iwindow/btoa/
---
## IWindow.Btoa method

يأخذ بيانات الإدخال على شكل سلسلة Unicode تحتوي فقط على أحرف في النطاق U+0000 إلى U+00FF، كل حرف يمثل بايتًا ثنائيًا بقيم 0x00 إلى 0xFF على التوالي، ويحوّلها إلى تمثيل base64، ثم يُعيده.

```java
public String Btoa(String data)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | String | سلسلة Unicode التي تحتوي فقط على أحرف في النطاق U+0000 إلى U+00FF. |

### قيمة الإرجاع

سلسلة base64.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | يرمي استثناء DOMException "InvalidCharacterError" إذا احتوت سلسلة الإدخال على أي أحرف خارج النطاق. |

### انظر أيضًا

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
