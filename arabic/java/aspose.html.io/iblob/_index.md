---
title: "IBlob واجهة"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "واجهة com.aspose.html.io.IBlob. كائن Blob يشير إلى تسلسل بايتات وله سمة size التي هي إجمالي عدد البايتات في تسلسل البايتات وسمة type التي هي String مشفر بـ ASCII بأحرف صغيرة تمثل نوع الوسائط لتسلسل البايتات."
type: docs

url: /ar/java/com.aspose.html.io/iblob/
---
## IBlob interface

كائن Blob يشير إلى تسلسل بايتات، وله خاصية size التي تمثل إجمالي عدد البايتات في تسلسل البايتات، وخاصية type التي هي سلسلة مشفرة بـ ASCII بأحرف صغيرة تمثل نوع الوسائط لتسلسل البايتات.

```java
public interface IBlob
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getSize](../../com.aspose.html.io/iblob/size/) تُعيد حجم تسلسل البايتات بعدد البايتات. عند الاستدعاء، يجب على وكلاء المستخدم المتوافقين إرجاع إجمالي عدد البايتات التي يمكن قراءتها بواسطة كائن FileReader أو FileReaderSync، أو 0 إذا لم يحتوي Blob على بايتات للقراءة. |
| [getType](../../com.aspose.html.io/iblob/type/) String مشفر بـ ASCII بأحرف صغيرة يمثل نوع وسائط Blob. عند الاستدعاء، يجب على وكلاء المستخدم إرجاع نوع Blob كـ String مشفر بـ ASCII بأحرف صغيرة، بحيث عند تحويله إلى تسلسل بايتات يكون نوع MIME قابلًا للتحليل، أو String فارغ – 0 بايت – إذا تعذر تحديد النوع. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [slice](../../com.aspose.html.io/iblob/slice/)(ulong, ulong, String) | تُعيد كائن Blob جديد يحتوي على بايتات تتراوح من المعامل الاختياري start حتى ما قبل المعامل الاختياري end، ومع سمة type التي تكون قيمة المعامل الاختياري contentType. |

### انظر أيضًا

* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)
