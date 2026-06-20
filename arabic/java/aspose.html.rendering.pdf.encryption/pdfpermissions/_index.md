---
title: "PdfPermissions تعداد"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "com.aspose.html.rendering.pdf.encryption.PdfPermissions تعداد. هذا التعداد يمثل أذونات المستخدمين لملف PDF"
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
| PrintDocument | `4` | (معالجات الأمان للإصدار 2) طباعة المستند. (معالجات الأمان للإصدار 3 أو أعلى) طباعة المستند (ربما ليس بأعلى مستوى جودة، اعتمادًا على ما إذا كان تم تعيين PrintingQuality أيضًا). |
| ModifyContent | `8` | تعديل محتويات المستند عبر عمليات غير تلك التي يتحكم فيها ModifyTextAnnotations و FillForm و 11. |
| ExtractContent | `10` | معالجات الأمان للإصدار 2) نسخ أو استخراج النص والرسومات من المستند، بما في ذلك استخراج النص والرسومات (دعمًا لإمكانية الوصول للمستخدمين ذوي الإعاقات أو لأغراض أخرى). (معالجات الأمان للإصدار 3 أو أعلى) نسخ أو استخراج النص والرسومات من المستند عبر عمليات غير تلك التي يتحكم فيها ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | إضافة أو تعديل تعليقات نصية، ملء حقول النماذج التفاعلية، وإذا تم تعيين ModifyContent أيضًا، إنشاء أو تعديل حقول النماذج التفاعلية (بما في ذلك حقول التوقيع). |
| FillForm | `100` | (معالجات الأمان للإصدار 3 أو أعلى) ملء حقول النماذج التفاعلية الموجودة (بما في ذلك حقول التوقيع)، حتى إذا كان ModifyTextAnnotations غير مفعّل. |
| ExtractContentWithDisabilities | `200` | (معالجات الأمان للإصدار 3 أو أعلى) استخراج النص والرسومات (دعمًا لإمكانية الوصول للمستخدمين ذوي الإعاقات أو لأغراض أخرى). |
| AssembleDocument | `400` | (معالجات الأمان للإصدار 3 أو أعلى) تجميع المستند (إدراج، تدوير، أو حذف صفحات وإنشاء إشارات مرجعية أو صور مصغرة)، حتى إذا كان ModifyContent غير مفعّل. |
| PrintingQuality | `800` | (معالجات الأمان للإصدار 3 أو أعلى) طباعة المستند إلى تمثيل يمكن من خلاله إنشاء نسخة رقمية دقيقة من محتوى PDF. عندما يكون هذا البت غير مفعّل (والبت 3 مفعّل)، يقتصر الطباعة على تمثيل منخفض المستوى للمظهر، ربما بجودة منخفضة. |

### انظر أيضًا

* package [com.aspose.html.rendering.pdf.encryption](../../com.aspose.html.rendering.pdf.encryption/)
* package [Aspose.HTML](../../)
