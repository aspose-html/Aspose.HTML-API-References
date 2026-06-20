---
title: "واجهة IBlob"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "واجهة com.aspose.html.io.IBlob. يشير كائن Blob إلى تسلسل بايتات وله سمة size تمثل إجمالي عدد البايتات في التسلسل وسمة type هي سلسلة String مشفرة بـ ASCII بحروف صغيرة تمثل نوع الوسائط لتسلسل البايتات"
type: docs

url: /ar/java/com.aspose.html.io/iblob/
---
## IBlob interface

كائن Blob يشير إلى تسلسل بايتات، وله خاصية size التي تمثل إجمالي عدد البايتات في التسلسل، وخاصية type التي هي سلسلة (String) مشفرة بترميز ASCII بحروف صغيرة تمثل نوع الوسائط للتسلسل.

```java
public interface IBlob
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getSize](../../com.aspose.html.io/iblob/size/) يُعيد حجم تسلسل البايتات بعدد البايتات. عند الحصول، يجب على وكلاء المستخدم المتوافقين إرجاع إجمالي عدد البايتات التي يمكن قراءتها بواسطة كائن FileReader أو FileReaderSync، أو 0 إذا لم يحتوي Blob على بايتات للقراءة. |
| [getType](../../com.aspose.html.io/iblob/type/) السلسلة المشفرة بـ ASCII بحروف صغيرة التي تمثل نوع وسائط Blob. عند الحصول، يجب على وكلاء المستخدم إرجاع نوع Blob كسلسلة String مشفرة بـ ASCII بحروف صغيرة، بحيث عند تحويلها إلى تسلسل بايتات تكون نوع MIME قابل للتحليل، أو السلسلة الفارغة – 0 بايت – إذا تعذر تحديد النوع. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [slice](../../com.aspose.html.io/iblob/slice/)(ulong, ulong, String) | يُعيد كائن Blob جديد مع بايتات تتراوح من المعامل الاختياري start حتى قبل المعامل الاختياري end، ومع سمة type التي هي قيمة المعامل الاختياري contentType. |

### انظر أيضًا

* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)
