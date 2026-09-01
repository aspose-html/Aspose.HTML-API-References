---
title: "فئة ImageRenderingOptions"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "فئة com.aspose.html.rendering.image.ImageRenderingOptions. تمثّل خيارات التصيير لـ ImageDevice. تُستخدم هذه الخيارات لتحديد صيغة الصورة الناتجة، الضغط، الدقة، إلخ"
type: docs

url: /ar/java/com.aspose.html.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

تمثّل خيارات التصيير لـ [`ImageDevice`](../imagedevice/). تُستخدم هذه الخيارات لتحديد صيغة الصورة الناتجة، الضغط، الدقة، إلخ.

```java
public class ImageRenderingOptions : RenderingOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | يُنشئ مثيلاً جديدًا لفئة `ImageRenderingOptions`؛ سيتم استخدام PNG كصيغة الصورة الافتراضية. |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(ImageFormat) | يُنشئ مثيلاً جديدًا لفئة `ImageRenderingOptions` باستخدام صيغة الصورة المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) يحصل على كائن [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) الذي يُستخدم لتكوين معالجة خصائص css. |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | يضبط أو يحصل على الدقة الأفقية للإخراج والداخلية (المستخدمة أثناء معالجة الفلاتر) للصور، بوحدة بكسل لكل بوصة. بشكل افتراضي، هذه الخاصية 300 نقطة في البوصة. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) يحصل على كائن إعداد الصفحة الذي يُستخدم لتكوين مجموعة الصفحات الناتجة. |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) يحصل على كائن [`TextOptions`](../textoptions/) يُستخدم لتكوين تصيير النص. |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | يضبط أو يحصل على الدقة العمودية للإخراج والداخلية (المستخدمة أثناء معالجة الفلاتر) للصور، بوحدة بكسل لكل بوصة. بشكل افتراضي، هذه الخاصية 300 نقطة في البوصة. |

### انظر أيضًا

* class [RenderingOptions](../../com.aspose.html.rendering/renderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
