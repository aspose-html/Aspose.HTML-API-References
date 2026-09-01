---
title: "فئة DocSaveOptions"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "الفئة com.aspose.html.saving.DocSaveOptions. فئة بيانات خيارات محددة. من خلال تعيين الخصائص يمكنك إدارة خصائص العرض مثل الدقة وحجم الصفحة ولون الخلفية بالإضافة إلى خيارات خاصة بالمستند مثل تضمين الخطوط. لمزيد من المعلومات راجع مقالة الوثائق"
type: docs

url: /ar/java/com.aspose.html.saving/docsaveoptions/
---
## DocSaveOptions class

فئة بيانات خيارات محددة. من خلال تعيين الخصائص يمكنك إدارة خصائص العرض مثل الدقة، حجم الصفحة، لون الخلفية بالإضافة إلى خيارات المستند المحددة مثل تضمين الخطوط. لمزيد من المعلومات راجع الوثائق [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#save-options).

```java
public class DocSaveOptions : DocRenderingOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) يحصل على كائن [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) الذي يُستخدم لتكوين معالجة خصائص css. |
[getDocumentFormat]
[setDocumentFormat] Gets or sets the file format of the output document. The default value is DOCX. |
[getFontEmbeddingRule]
[setFontEmbeddingRule] Gets or sets the font embedding rule. The default value is None. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | يضبط أو يحصل على الدقة الأفقية للصور الداخلية (التي تُستخدم أثناء معالجة الفلاتر)، بوحدة البكسل لكل بوصة. بشكل افتراضي، هذه الخاصية هي 300 نقطة في البوصة. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) يحصل على كائن إعداد الصفحة الذي يُستخدم لتكوين مجموعة الصفحات الناتجة. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | يضبط أو يحصل على الدقة الرأسية للصور الداخلية (التي تُستخدم أثناء معالجة الفلاتر)، بوحدة البكسل لكل بوصة. بشكل افتراضي، هذه الخاصية هي 300 نقطة في البوصة. |

## ملاحظات

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.saving;
import System;
...
 // جهّز مسارًا إلى ملف HTML المصدر
      String documentPath = Path.Combine(DataDir, "canvas.html");

      // جهّز مسار لحفظ الملف المحوّل
      String savePath = Path.Combine(OutputDir, "canvas-output-options.docx");

      // ابدأ مستند HTML من الملف
      using var document = new HTMLDocument(documentPath);

      // ابدأ DocSaveOptions. اضبط حجم الصفحة 600x400 بكسل والهوامش
      var options = new DocSaveOptions();
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 400), new Margin(10, 10, 10, 10));

      // تحويل HTML إلى DOCX
      Converter.ConvertHTML(document, options, savePath);
```

*OutputDir - custom output folder path.

### انظر أيضًا

* class [DocRenderingOptions](../../com.aspose.html.rendering.doc/docrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
