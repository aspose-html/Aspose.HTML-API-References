---
title: "XpsSaveOptions فئة"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "الفئة com.aspose.html.saving.XpsSaveOptions. فئة بيانات خيارات محددة توفر عددًا قليلًا من الخصائص لإدارة نتيجة التحويل. على سبيل المثال، PageSetup يحدد خصائص الصفحة. راجع مقالة الوثائق."
type: docs

url: /ar/java/com.aspose.html.saving/xpssaveoptions/
---
## XpsSaveOptions class

فئة بيانات الخيارات المحددة توفر عددًا قليلًا من الخصائص لإدارة نتيجة التحويل. على سبيل المثال [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) يحدد خصائص الصفحة. راجع الوثائق [مقال](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#save-options).

```java
public class XpsSaveOptions : XpsRenderingOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) يحصل على كائن [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) يُستخدم لتكوين معالجة خصائص css. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | يضبط أو يحصل على الدقة الأفقية للصور الداخلية (التي تُستخدم أثناء معالجة الفلاتر)، بوحدة البكسل لكل بوصة. بشكل افتراضي، هذه الخاصية هي 300 نقطة في البوصة. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) يحصل على كائن إعداد الصفحة يُستخدم لتكوين إخراج مجموعة الصفحات. |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | يضبط أو يحصل على الدقة العمودية للصور الداخلية (التي تُستخدم أثناء معالجة الفلاتر)، بوحدة البكسل لكل بوصة. بشكل افتراضي، هذه الخاصية هي 300 نقطة في البوصة. |

## ملاحظات

يمكنك العثور على أمثلة كاملة وملفات بيانات على [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## الأمثلة

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
	  String documentPath = Path.Combine(OutputDir, "save-options.html");
      String savePath = Path.Combine(OutputDir, "save-options-output.xps");

      // جهّز كود HTML واحفظه في ملف
      var code = "<h1> XpsSaveOptions Class</h1>\r\n" +
            "<p>Using XpsSaveOptions Class, you can programmatically apply a wide range of conversion parameters such as BackgroundColor, PageSetup, etc.</p>\r\n";

      File.WriteAllText(documentPath, code);

      // تهيئة مستند HTML من ملف html
      using var document = new HTMLDocument(documentPath);
       
      // اضبط حجم الصفحة، الهوامش، وغير لون الخلفية إلى AntiqueWhite
      var options = new XpsSaveOptions()
      {
        BackgroundColor = Color.AntiqueWhite
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(Length.FromInches(4.9f), Length.FromInches(3.5f)), new Margin(30, 20, 10, 10));

      // تحويل HTML إلى XPS
      Converter.ConvertHTML(document, options, savePath); 
```

### انظر أيضًا

* class [XpsRenderingOptions](../../com.aspose.html.rendering.xps/xpsrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
