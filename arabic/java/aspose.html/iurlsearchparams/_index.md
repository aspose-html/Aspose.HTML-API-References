---
title: "واجهة IUrlSearchParams"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "واجهة com.aspose.html.IUrlSearchParams. توفر طرقًا للعمل مع سلسلة استعلام URLs"
type: docs

url: /ar/java/com.aspose.html/iurlsearchparams/
---
## IUrlSearchParams interface

يوفر طرقًا للعمل مع سلسلة استعلام URLs.

```java
public interface IUrlSearchParams : IEnumerable<String[]>
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [append](../../com.aspose.html/iurlsearchparams/append/)(String, String) | يضيف زوج اسم-قيمة جديد يكون اسمه `name` وقيمته `value`. |
| [delete](../../com.aspose.html/iurlsearchparams/delete/)(String) | يزيل جميع أزواج الاسم-القيمة التي يكون اسمها `name`. |
| [get](../../com.aspose.html/iurlsearchparams/get/)(String) | يعيد قيمة أول زوج اسم-قيمة يكون اسمه `name`. |
| [getAll](../../com.aspose.html/iurlsearchparams/getall/)(String) | يعيد جميع القيم التي يكون اسمها `name`. |
| [has](../../com.aspose.html/iurlsearchparams/has/)(String) | يتحقق مما إذا كان هناك زوج اسم-قيمة اسمه `name` في القائمة. |
| [set](../../com.aspose.html/iurlsearchparams/set/)(String, String) | يضبط قيمة أول زوج اسم-قيمة يتم العثور عليه إلى القيمة المحددة ويزيل البقية. إذا لم يتم العثور على أي أزواج اسم-قيمة بالاسم المحدد، سيتم إضافة زوج جديد إلى القائمة. |
| [sort](../../com.aspose.html/iurlsearchparams/sort/)() | يرتب جميع أزواج الاسم-القيمة، إن وجدت، حسب أسمائها. |

### انظر أيضًا

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
