---
title: "فئة ImageSaveOptions"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "الفئة com.aspose.html.saving.ImageSaveOptions. فئة بيانات الخيارات المحددة. توفر خصائص لإدارة نتيجة الصورة مثل الدقة، التنعيم، الجودة، الصيغة بالإضافة إلى إعدادات الصفحة وغيرها. يمكنك الحصول على مزيد من المعلومات في مقالة الوثائق."
type: docs

url: /ar/java/com.aspose.html.saving/imagesaveoptions/
---
## ImageSaveOptions class

فئة بيانات خيارات محددة. توفر خصائص لإدارة دقة نتيجة الصورة، جودة التنعيم، الصيغة بالإضافة إلى إعدادات الصفحة وغيرها. يمكنك الحصول على مزيد من المعلومات في الوثائق [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#save-options).

```java
public class ImageSaveOptions : ImageRenderingOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/#constructor)() | يقوم بتهيئة نسخة جديدة من الفئة `ImageSaveOptions`؛ سيتم استخدام Png كصيغة الصورة الافتراضية. |
| [ImageSaveOptions](imagesaveoptions/#constructor_1)(ImageFormat) | صيغة الصورة [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/) بناءً على التهيئة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../../com.aspose.html.rendering.image/compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) يحصل على كائن [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) يُستخدم لتكوين معالجة خصائص css. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | يضبط أو يحصل على الدقة الأفقية للصور الناتجة والداخلية (التي تُستخدم أثناء معالجة الفلاتر)، بوحدة بكسل لكل بوصة. بشكل افتراضي، هذه الخاصية 300 نقطة في البوصة. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) يحصل على كائن إعداد الصفحة يُستخدم لتكوين إخراج مجموعة الصفحات. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) يحصل على كائن [`TextOptions`](../../com.aspose.html.rendering.image/textoptions/) الذي يُستخدم لتكوين عرض النص. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | يضبط أو يحصل على الدقة العمودية للصور الناتجة والداخلية (التي تُستخدم أثناء معالجة الفلاتر)، بوحدة بكسل لكل بوصة. بشكل افتراضي، هذه الخاصية 300 نقطة في البوصة. |

## ملاحظات

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## الأمثلة

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
      // جهّز مسارًا إلى ملف HTML المصدر
      String documentPath = Path.Combine(DataDir, "nature.html");

      // جهّز مسارًا لحفظ الملف المحوَّل
      String savePath = Path.Combine(OutputDir, "nature-output-options.png");

      // تهيئة مستند HTML من الملف
      using var document = new HTMLDocument(documentPath);

      // تهيئة ImageSaveOptions
      var options = new ImageSaveOptions()
      {
        SmoothingMode = SmoothingMode.Default,
        HorizontalResolution = 100,
        VerticalResolution = 100,
        BackgroundColor = Color.Beige
      };

      // تحويل HTML إلى PNG
      Converter.ConvertHTML(document, options, savePath);
```

### انظر أيضًا

* class [ImageRenderingOptions](../../com.aspose.html.rendering.image/imagerenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
