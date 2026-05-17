---
title: "فئة HTMLSaveOptions"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "com.aspose.html.saving.HTMLSaveOptions فئة. تمثل خيارات حفظ HTML. من خلال تعيين خصائص محددة يمكنك إدارة معالجة الموارد مثل أقصى عمق معالجة وما إلى ذلك. لمزيد من المعلومات راجع مقالة الوثائق"
type: docs

url: /ar/java/com.aspose.html.saving/htmlsaveoptions/
---
## HTMLSaveOptions class

يمثل خيارات حفظ HTML. من خلال تعيين خصائص محددة يمكنك إدارة معالجة الموارد مثل أقصى عمق للمعالجة وما إلى ذلك. لمزيد من المعلومات راجع الوثائق في [article](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
public class HTMLSaveOptions : SaveOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [HTMLSaveOptions](htmlsaveoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
[getDocumentType]
[setDocumentType] Gets or sets the output document type. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) يحصل على كائن [`ResourceHandlingOptions`](../resourcehandlingoptions/) يُستخدم لتكوين معالجة الموارد. |
[getSerializeInputValue]
[setSerializeInputValue] This option controls whether to serialize the value of the [`HTMLInputElement`](../../com.aspose.html/htmlinputelement/)'s or the [`HTMLTextAreaElement`](../../com.aspose.html/htmltextareaelement/)'s "value" property into the "value" attribute. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [AUTO](../../com.aspose.html.saving/htmlsaveoptions/auto/) | سيتم اختيار نوع مستند الإخراج تلقائيًا. |
| const [HTML](../../com.aspose.html.saving/htmlsaveoptions/html/) | سيتم حفظ المستند كـ HTML. |
| const [XHTML](../../com.aspose.html.saving/htmlsaveoptions/xhtml/) | سيتم حفظ المستند كـ XHTML. |

## ملاحظات

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## الأمثلة

```java
import Aspose.Html;
import com.aspose.html.dom.svg;
import com.aspose.html.saving;
import System;
...
     // جهّز مسار إخراج لمستند HTML 
      String documentPath = Path.Combine(OutputDir, "save-with-linked-file.html");

      // جهّز ملف HTML بسيط مع مستند مرتبط
      File.WriteAllText(documentPath, "<p>Hello World!</p>" +
                      "<a href='linked.html'>linked file</a>");

      // جهّز ملف HTML مرتبط بسيط
      File.WriteAllText(Path.Combine(OutputDir, "linked.html"), "<p>Hello linked file!</p>");

      // حمّل "save-with-linked-file.html" في الذاكرة
      using (var document = new HTMLDocument(documentPath))
      {
        // أنشئ مثيلًا لخيارات الحفظ
        var options = new HTMLSaveOptions();

        // السطر التالي بالقيمة '0' يقطع جميع ملفات HTML المرتبطة الأخرى أثناء حفظ هذه النسخة
        // إذا قمت بإزالة هذا السطر أو غيرت القيمة إلى '1'، سيتم حفظ ملف 'linked.html' أيضًا في مجلد الإخراج
        options.ResourceHandlingOptions.MaxHandlingDepth = 1;

        // احفظ المستند باستخدام خيارات الحفظ
        document.Save(Path.Combine(OutputDir, "save-with-linked-file_out.html"), options);
      }
```

*OutputDir - user output folder.

### انظر أيضًا

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
