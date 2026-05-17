---
title: "عدد PdfPermissions"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "عدد com.aspose.html.rendering.pdf.encryption.PdfPermissions. يمثل هذا العدد أذونات المستخدمين لملف PDF"
type: docs

url: /ar/java/com.aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

يمثل هذا التعداد أذونات المستخدم لملف PDF.

```java
[Flags]
public enum PdfPermissions
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| PrintDocument | `4` | (معالجات الأمان للإصدار 2) طباعة المستند. (معالجات الأمان للإصدار 3 أو أعلى) طباعة المستند (قد لا تكون بأعلى مستوى جودة، اعتمادًا على ما إذا كان تم تعيين PrintingQuality أيضًا). |
| ModifyContent | `8` | تعديل محتويات المستند عبر عمليات غير تلك التي يتحكم فيها ModifyTextAnnotations و FillForm و 11. |
| ExtractContent | `10` | (معالجات الأمان للإصدار 2) نسخ أو استخراج النصوص والرسومات من المستند بأي طريقة أخرى، بما في ذلك استخراج النصوص والرسومات (لدعم إمكانية الوصول للمستخدمين ذوي الإعاقات أو لأغراض أخرى). (معالجات الأمان للإصدار 3 أو أعلى) نسخ أو استخراج النصوص والرسومات من المستند عبر عمليات غير تلك التي يتحكم فيها ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | إضافة أو تعديل تعليقات النص، تعبئة حقول النماذج التفاعلية، وإذا كان ModifyContent مُحددًا أيضًا، إنشاء أو تعديل حقول النماذج التفاعلية (بما في ذلك حقول التوقيع). |
| FillForm | `100` | (معالجات الأمان للإصدار 3 أو أعلى) تعبئة حقول النماذج التفاعلية الموجودة (بما في ذلك حقول التوقيع)، حتى إذا كان ModifyTextAnnotations غير مفعّل. |
| ExtractContentWithDisabilities | `200` | (معالجات الأمان للإصدار 3 أو أعلى) استخراج النصوص والرسومات (لدعم إمكانية الوصول للمستخدمين ذوي الإعاقات أو لأغراض أخرى). |
| AssembleDocument | `400` | (معالجات الأمان للإصدار 3 أو أعلى) تجميع المستند (إدراج، تدوير، أو حذف صفحات وإنشاء إشارات مرجعية أو صور مصغرة)، حتى إذا كان ModifyContent غير مفعّل. |
| PrintingQuality | `800` | (معالجات الأمان للإصدار 3 أو أعلى) طباعة المستند إلى تمثيل يمكن من خلاله إنشاء نسخة رقمية دقيقة من محتوى PDF. عندما يكون هذا البت غير مفعّل (وبيت 3 مفعّل)، تكون الطباعة محدودة بتمثيل منخفض المستوى للمظهر قد يكون بجودة منخفضة. |

### انظر أيضًا

* package [com.aspose.html.rendering.pdf.encryption](../../com.aspose.html.rendering.pdf.encryption/)
* package [Aspose.HTML](../../)
