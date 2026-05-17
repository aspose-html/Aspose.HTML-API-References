---
title: "واجهة IStorage"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "واجهة com.aspose.html.dom.IStorage. تُوفر هذه الواجهة في واجهة برمجة تطبيقات Web Storage إمكانية الوصول إلى جلسة أو تخزين محلي لنطاق معين. راجع مواصفة Web Storage https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs

url: /ar/java/com.aspose.html.dom/istorage/
---
## IStorage interface

توفر هذه الواجهة من واجهة برمجة تطبيقات Web Storage إمكانية الوصول إلى جلسة أو تخزين محلي لنطاق معين. راجع مواصفات Web Storage: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```java
public interface IStorage
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getLength](../../com.aspose.html.dom/istorage/length/) يُرجع عدد أزواج المفتاح/القيمة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [clear](../../com.aspose.html.dom/istorage/clear/)() | يزيل جميع أزواج المفتاح/القيمة، إذا وجدت أي منها. |
| [getItem](../../com.aspose.html.dom/istorage/getitem/)(String) | يعيد القيمة الحالية المرتبطة بالمفتاح المعطى، أو null إذا لم يكن المفتاح المعطى موجودًا. |
| [key](../../com.aspose.html.dom/istorage/key/)(long) | يعيد اسم المفتاح رقم n، أو null إذا كان n أكبر من أو يساوي عدد أزواج المفتاح/القيمة. |
| [removeItem](../../com.aspose.html.dom/istorage/removeitem/)(String) | يزيل زوج المفتاح/القيمة بالمفتاح المعطى، إذا كان هناك زوج مفتاح/قيمة بالمفتاح المعطى. |
| [setItem](../../com.aspose.html.dom/istorage/setitem/)(String, String) | يضبط قيمة الزوج المحدد بالمفتاح إلى value، مع إنشاء زوج مفتاح/قيمة جديد إذا لم يكن هناك أي زوج للمفتاح مسبقًا. |

### انظر أيضًا

* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
