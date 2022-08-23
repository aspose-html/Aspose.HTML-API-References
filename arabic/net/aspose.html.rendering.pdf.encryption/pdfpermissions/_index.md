---
title: PdfPermissions
second_title: Aspose.HTML لمرجع .NET API
description: هذا التعداد يمثل أذونات المستخدم لقوات الدفاع الشعبي.
type: docs
weight: 4410
url: /ar/net/aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

هذا التعداد يمثل أذونات المستخدم لقوات الدفاع الشعبي.

```csharp
[Flags]
public enum PdfPermissions
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| PrintDocument | `4` | (معالجات الأمان للمراجعة 2) قم بطباعة المستند. (معالجات الأمان للمراجعة 3 أو أكبر) اطبع المستند (ربما ليس بأعلى مستوى من الجودة ، اعتمادًا على ما إذا تم تعيين جودة الطباعة أيضًا) . |
| ModifyContent | `8` | تعديل محتويات المستند بعمليات غير تلك التي يتحكم فيها ModifyTextAnnotations و FillForm و 11. |
| ExtractContent | `10` | معالجات الأمان للمراجعة 2) نسخ أو استخراج النص والرسومات بطريقة أخرى من المستند ، بما في ذلك استخراج النص والرسومات (لدعم إمكانية الوصول للمستخدمين ذوي الاحتياجات الخاصة أو لأغراض أخرى) . (معالجات الأمان للمراجعة 3 أو أكبر) نسخ أو استخرج النص والرسومات بطريقة أخرى من المستند من خلال عمليات أخرى غير تلك التي يتحكم فيها ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | قم بإضافة أو تعديل التعليقات التوضيحية النصية ، واملأ حقول النموذج التفاعلية ، وإذا تم أيضًا تعيين ModifyContent ، فقم بإنشاء أو تعديل حقول النموذج التفاعلية (بما في ذلك حقول التوقيع) . |
| FillForm | `100` | (معالجات الأمان للمراجعة 3 أو أكبر) املأ حقول النموذج التفاعلية الحالية (بما في ذلك حقول التوقيع) ، حتى إذا كان ModifyTextAnnotations واضحًا. |
| ExtractContentWithDisabilities | `200` | (معالجات الأمان للمراجعة 3 أو أكبر) استخراج النص والرسومات (لدعم إمكانية الوصول للمستخدمين ذوي الاحتياجات الخاصة أو لأغراض أخرى) . |
| AssembleDocument | `400` | (معالجات الأمان للمراجعة 3 أو أكبر) قم بتجميع المستند (قم بإدراج الصفحات أو تدويرها أو حذفها وإنشاء إشارات مرجعية أو صور مصغرة) ، حتى إذا كان تعديل المحتوى واضحًا. |
| PrintingQuality | `800` | (معالجات الأمان للمراجعة 3 أو أكبر) اطبع المستند إلى تمثيل يمكن من خلاله إنشاء نسخة رقمية موثوقة من محتوى PDF . عندما يكون هذا البت واضحًا (ويتم تعيين البت 3) ، تقتصر الطباعة على قيمة منخفضة - تمثيل بمستوى المظهر ، ربما بجودة متدهورة. |

### أنظر أيضا

* مساحة الاسم [Aspose.Html.Rendering.Pdf.Encryption](../../aspose.html.rendering.pdf.encryption)
* المجسم [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->