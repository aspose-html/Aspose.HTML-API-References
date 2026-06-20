---
title: "فئة PdfSaveOptions"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "الفئة com.aspose.html.saving.PdfSaveOptions. فئة بيانات محددة توفر عددًا قليلًا من الخصائص لإدارة نتيجة التحويل. على سبيل المثال، PageSetup يحدد خصائص الصفحة. راجع مقالة الوثائق"
type: docs

url: /ar/java/com.aspose.html.saving/pdfsaveoptions/
---
## PdfSaveOptions class

فئة بيانات محددة توفر عددًا قليلًا من الخصائص لإدارة نتيجة التحويل. على سبيل المثال [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) يحدد خصائص الصفحة. راجع وثائق [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions).

```java
public class PdfSaveOptions : PdfRenderingOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) يحصل على كائن [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) الذي يُستخدم لتكوين معالجة خصائص css. |
| [getDocumentInfo](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/documentinfo/) يحتوي على معلومات حول وثيقة PDF الناتجة. |
[getEncryption]
[setEncryption] Gets or sets a encryption details. If not set, then no encryption will be performed. |
[getFormFieldBehaviour]
[setFormFieldBehaviour] Specifies the behavior of form fields in the output PDF document. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | يضبط أو يحصل على الدقة الأفقية للصور الداخلية (التي تُستخدم أثناء معالجة الفلاتر)، بوحدة البكسل لكل بوصة. بشكل افتراضي، هذه الخاصية هي 300 نقطة في البوصة. |
[getIsTaggedPdf]
[setIsTaggedPdf] Creates a tag structure if `true`. |
[getJpegQuality]
[setJpegQuality] Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) يحصل على كائن إعداد الصفحة الذي يُستخدم لتكوين مجموعة الصفحات الناتجة. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | يضبط أو يحصل على الدقة الرأسية للصور الداخلية (التي تُستخدم أثناء معالجة الفلاتر)، بوحدة البكسل لكل بوصة. بشكل افتراضي، هذه الخاصية هي 300 نقطة في البوصة. |

## ملاحظات

يمكنك العثور على أمثلة كاملة وملفات بيانات على [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
 	 // جهّز مسارًا إلى ملف HTML المصدر
      String documentPath = Path.Combine(DataDir, "drawing.html");

      // جهّز مسار لحفظ الملف المحوّل
      String savePath = Path.Combine(OutputDir, "drawing-options.pdf");

      // ابدأ مستند HTML من الملف
      using var document = new HTMLDocument(documentPath);

      // تهيئة PdfSaveOptions. ضبط حجم الصفحة 600x300 بكسل، الهوامش، 
      // الدقة وتغيير لون الخلفية إلى AliceBlue 
      var options = new PdfSaveOptions()
      {         
        HorizontalResolution = 200,
        VerticalResolution = 200,
        BackgroundColor = Color.AliceBlue,
        JpegQuality = 100
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 300), new Margin(20, 10, 10, 10));      

      // تحويل HTML إلى PDF
      Converter.ConvertHTML(document, options, savePath);
```

### انظر أيضًا

* class [PdfRenderingOptions](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
