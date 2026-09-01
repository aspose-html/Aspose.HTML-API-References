---
title: "Converter.ConvertSVG"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة Converter. تحويل مصدر SVG المقدم بواسطة SVGDocument. النتيجة هي بيانات إخراج تم إنشاؤها بواسطة تنفيذ واجهة ICreateStreamProvider"
type: docs

url: /ar/java/com.aspose.html.converters/converter/convertsvg/
---
## ConvertSVG(SVGDocument, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_6}

تحويل مصدر SVG المقدم بواسطة [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). النتيجة هي بيانات إخراج تم إنشاؤها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertSVG(SVGDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| document | SVGDocument | مصدر التحويل المقدم بواسطة [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | استخدام كائن [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

ارجع إلى [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) حيث ستجد معلومات حول كيفية تحويل SVG إلى XPS باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى XPS

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى XPS. لتحويل SVG إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو بعيد باستخدام [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم بواسطة مصدر String. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة XPS مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) يقوم بتحويل SVG إلى XPS بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك وتحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // إنشاء مستند SVG كمصدر للتحويل
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
			// بدء عملية التحويل باستخدام التكوين الافتراضي
			Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_22}

تحويل مصدر SVG المقدم بواسطة [`URL`](../../../com.aspose.html/url/). النتيجة هي بيانات إخراج تم إنشاؤها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | مستند مصدر SVG [`URL`](../../../com.aspose.html/url/) - يوفر تمثيلًا كائنًا لمعرف عالمي (URL). |
| options | XpsSaveOptions | استخدام كائن [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. |
| provider | ICreateStreamProvider | معروف (انظر [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) أو تنفيذ مخصص لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

ارجع إلى [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) حيث ستجد معلومات حول كيفية تحويل SVG إلى XPS باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى XPS

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى XPS. لتحويل SVG إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو بعيد باستخدام [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم بواسطة مصدر String. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة XPS مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) يقوم بتحويل SVG إلى XPS بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك وتحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // مسار ملف المصدر للنموذج
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل
      Converter.ConvertSVG(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_14}

تحويل مصدر SVG المقدم بواسطة [`URL`](../../../com.aspose.html/url/). النتيجة هي بيانات إخراج تم إنشاؤها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | مستند مصدر SVG [`URL`](../../../com.aspose.html/url/) - يوفر تمثيلًا كائنًا لمعرف عالمي (URL). |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | XpsSaveOptions | استخدام كائن [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | معروف (انظر [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) أو تنفيذ مخصص لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

ارجع إلى [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) حيث ستجد معلومات حول كيفية تحويل SVG إلى XPS باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى XPS

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى XPS. لتحويل SVG إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو بعيد باستخدام [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم بواسطة مصدر String. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة XPS مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) يقوم بتحويل SVG إلى XPS بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك وتحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // مسار ملف المصدر للنموذج
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_38}

تحويل مصدر SVG المقدم بواسطة مسار ملف كامل إلى XPS. النتيجة هي بيانات إخراج تم إنشاؤها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف كامل لمصدر SVG. |
| options | XpsSaveOptions | استخدام كائن [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

ارجع إلى [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) حيث ستجد معلومات حول كيفية تحويل SVG إلى XPS باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى XPS

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى XPS. لتحويل SVG إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو بعيد باستخدام [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم بواسطة مصدر String. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة XPS مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) يقوم بتحويل SVG إلى XPS بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك وتحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_30}

تحويل مصدر SVG المقدم بواسطة مسار ملف كامل إلى XPS. النتيجة هي بيانات إخراج تم إنشاؤها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف كامل لمصدر SVG. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | XpsSaveOptions | استخدام كائن [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

ارجع إلى [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) حيث ستجد معلومات حول كيفية تحويل SVG إلى XPS باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى XPS

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى XPS. لتحويل SVG إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو بعيد باستخدام [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم بواسطة مصدر String. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة XPS مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) يقوم بتحويل SVG إلى XPS بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك وتحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_54}

تحويل مصدر SVG المقدم عبر محتوى مضمن إلى XPS. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | سلسلة كنص SVG مضمن. |
| baseUri | String | عنوان URI الأساسي للمستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| options | XpsSaveOptions | استخدام كائن [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

ارجع إلى [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) حيث ستجد معلومات حول كيفية تحويل SVG إلى XPS باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى XPS

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى XPS. لتحويل SVG إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو بعيد باستخدام [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم بواسطة مصدر String. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة XPS مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) يقوم بتحويل SVG إلى XPS بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك وتحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### انظر أيضًا

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_46}

تحويل مصدر SVG المقدم عبر محتوى مضمن إلى XPS. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | سلسلة كنص SVG مضمن. |
| baseUri | String | عنوان URI الأساسي للمستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | XpsSaveOptions | استخدام كائن [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | معروف (انظر [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) أو تنفيذ مخصص لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

ارجع إلى [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) حيث ستجد معلومات حول كيفية تحويل SVG إلى XPS باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى XPS

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى XPS. لتحويل SVG إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو بعيد باستخدام [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم بواسطة مصدر String. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة XPS مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) يقوم بتحويل SVG إلى XPS بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك وتحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### انظر أيضًا

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, DocSaveOptions, String) {#convertsvg_1}

تحويل مصدر SVG المقدم عبر [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). النتيجة هي ملف docx تم إنشاؤه عبر مسار ملف الإخراج.

```java
public static void ConvertSVG(SVGDocument source, DocSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| source | SVGDocument | مصدر التحويل المقدم بواسطة [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | استخدام كائن [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | مسار ملف docx الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) حيث ستجد معلومات حول كيفية تحويل SVG إلى [DOCX](https://docs.fileformat.com/word-processing/docx/) باستخدام طرق ConvertSVG() في فئة Converter وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى DOCX

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى DOCX. لتحويل SVG إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) يقوم بتحويل SVG إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // إنشاء مستند SVG كمصدر للتحويل
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // بدء عملية التحويل باستخدام التكوين الافتراضي
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, String) {#convertsvg_17}

تحويل مصدر SVG المقدم عبر [`URL`](../../../com.aspose.html/url/). النتيجة هي ملف docx تم إنشاؤه عبر مسار ملف الإخراج.

```java
public static void ConvertSVG(Url url, DocSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | مستند مصدر SVG [`URL`](../../../com.aspose.html/url/) - يوفر تمثيلًا كائنًا لمعرف عالمي (URL). |
| options | DocSaveOptions | استخدام كائن [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | مسار ملف docx الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) حيث ستجد معلومات حول كيفية تحويل SVG إلى [DOCX](https://docs.fileformat.com/word-processing/docx/) باستخدام طرق ConvertSVG() في فئة Converter وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى DOCX

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى DOCX. لتحويل SVG إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) يقوم بتحويل SVG إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // إنشاء Url بناءً على مسار ملف الإدخال
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertSVG(sourceUrl, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, DocSaveOptions, String) {#convertsvg_9}

تحويل مصدر SVG المقدم عبر [`URL`](../../../com.aspose.html/url/). النتيجة هي ملف docx تم إنشاؤه عبر مسار ملف الإخراج.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | مستند مصدر SVG [`URL`](../../../com.aspose.html/url/) - يوفر تمثيلًا كائنًا لمعرف عالمي (URL). |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | DocSaveOptions | استخدام كائن [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | مسار ملف docx الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) حيث ستجد معلومات حول كيفية تحويل SVG إلى [DOCX](https://docs.fileformat.com/word-processing/docx/) باستخدام طرق ConvertSVG() في فئة Converter وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى DOCX

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى DOCX. لتحويل SVG إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) يقوم بتحويل SVG إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // إنشاء Url بناءً على مسار ملف الإدخال
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, String) {#convertsvg_33}

تحويل مصدر SVG المقدم بواسطة مسار ملف كامل إلى DOCX. النتيجة هي ملف DOCX تم تشكيله بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف كامل لمصدر SVG. |
| options | DocSaveOptions | استخدام كائن [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | مسار ملف docx الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) حيث ستجد معلومات حول كيفية تحويل SVG إلى [DOCX](https://docs.fileformat.com/word-processing/docx/) باستخدام طرق ConvertSVG() في فئة Converter وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى DOCX

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى DOCX. لتحويل SVG إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) يقوم بتحويل SVG إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertSVG(sourcePath, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### انظر أيضًا

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, DocSaveOptions, String) {#convertsvg_25}

تحويل مصدر SVG المقدم بواسطة مسار ملف كامل إلى DOCX. النتيجة هي ملف DOCX تم تشكيله بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف كامل لمصدر SVG. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | DocSaveOptions | استخدام كائن [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | مسار ملف docx الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) حيث ستجد معلومات حول كيفية تحويل SVG إلى [DOCX](https://docs.fileformat.com/word-processing/docx/) باستخدام طرق ConvertSVG() في فئة Converter وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى DOCX

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى DOCX. لتحويل SVG إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) يقوم بتحويل SVG إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, DocSaveOptions, String) {#convertsvg_49}

تحويل مصدر SVG المقدم عبر المحتوى المضمن. النتيجة هي ملف docx تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | سلسلة كنص SVG مضمن. |
| baseUri | String | عنوان URI الأساسي للمستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| options | DocSaveOptions | استخدام كائن [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | مسار ملف docx الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) حيث ستجد معلومات حول كيفية تحويل SVG إلى [DOCX](https://docs.fileformat.com/word-processing/docx/) باستخدام طرق ConvertSVG() في فئة Converter وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى DOCX

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى DOCX. لتحويل SVG إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) يقوم بتحويل SVG إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // نموذج محتوى SVG مضمن
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### انظر أيضًا

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, String) {#convertsvg_41}

تحويل مصدر SVG المقدم عبر المحتوى المضمن. النتيجة هي ملف docx تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | سلسلة كنص SVG مضمن. |
| baseUri | String | عنوان URI الأساسي للمستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | DocSaveOptions | استخدام كائن [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | مسار ملف docx الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) حيث ستجد معلومات حول كيفية تحويل SVG إلى [DOCX](https://docs.fileformat.com/word-processing/docx/) باستخدام طرق ConvertSVG() في فئة Converter وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى DOCX

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى DOCX. لتحويل SVG إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) يقوم بتحويل SVG إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // نموذج محتوى SVG مضمن
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### انظر أيضًا

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, DocSaveOptions, ICreateStreamProvider) {#convertsvg}

تحويل مصدر SVG المقدم بواسطة [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). النتيجة هي بيانات إخراج تم إنشاؤها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertSVG(SVGDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| document | SVGDocument | مصدر التحويل المقدم بواسطة [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | استخدام كائن [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | معروف (انظر [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) أو تنفيذ مخصص لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) حيث ستجد معلومات حول كيفية تحويل SVG إلى [DOCX](https://docs.fileformat.com/word-processing/docx/) باستخدام طرق ConvertSVG() في فئة Converter وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى DOCX

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى DOCX. لتحويل SVG إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) يقوم بتحويل SVG إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // إنشاء مستند SVG كمصدر للتحويل
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // بدء عملية التحويل باستخدام التكوين الافتراضي
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, ICreateStreamProvider) {#convertsvg_16}

تحويل مصدر SVG المقدم بواسطة [`URL`](../../../com.aspose.html/url/). النتيجة هي بيانات إخراج تم إنشاؤها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | مستند مصدر SVG [`URL`](../../../com.aspose.html/url/) - يوفر تمثيلًا كائنًا لمعرف عالمي (URL). |
| options | DocSaveOptions | استخدام كائن [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) حيث ستجد معلومات حول كيفية تحويل SVG إلى [DOCX](https://docs.fileformat.com/word-processing/docx/) باستخدام طرق ConvertSVG() في فئة Converter وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى DOCX

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى DOCX. لتحويل SVG إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) يقوم بتحويل SVG إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // إنشاء Url بناءً على مسار ملف الإدخال
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل
      Converter.ConvertSVG(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_8}

تحويل مصدر SVG المقدم عبر [`URL`](../../../com.aspose.html/url/). النتيجة هي ملف docx تم إنشاؤه عبر مسار ملف الإخراج.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | مستند مصدر SVG [`URL`](../../../com.aspose.html/url/) - يوفر تمثيلًا كائنًا لمعرف عالمي (URL). |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | DocSaveOptions | استخدام كائن [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | معروف (انظر [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) أو تنفيذ مخصص لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) حيث ستجد معلومات حول كيفية تحويل SVG إلى [DOCX](https://docs.fileformat.com/word-processing/docx/) باستخدام طرق ConvertSVG() في فئة Converter وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى DOCX

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى DOCX. لتحويل SVG إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) يقوم بتحويل SVG إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // إنشاء Url بناءً على مسار ملف الإدخال
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_32}

تحويل مصدر SVG المقدم عبر مسار ملف كامل إلى DOCX. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف كامل لمصدر SVG. |
| options | DocSaveOptions | استخدام كائن [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | معروف (انظر [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) أو تنفيذ مخصص لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) حيث ستجد معلومات حول كيفية تحويل SVG إلى [DOCX](https://docs.fileformat.com/word-processing/docx/) باستخدام طرق ConvertSVG() في فئة Converter وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى DOCX

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى DOCX. لتحويل SVG إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) يقوم بتحويل SVG إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_24}

تحويل مصدر SVG المقدم عبر مسار ملف كامل إلى DOCX. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف كامل لمصدر SVG. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | DocSaveOptions | استخدام كائن [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) حيث ستجد معلومات حول كيفية تحويل SVG إلى [DOCX](https://docs.fileformat.com/word-processing/docx/) باستخدام طرق ConvertSVG() في فئة Converter وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى DOCX

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى DOCX. لتحويل SVG إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) يقوم بتحويل SVG إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_48}

تحويل مصدر SVG المقدم عبر محتوى مضمن إلى DOCX. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | سلسلة كنص SVG مضمن. |
| baseUri | String | عنوان URI الأساسي للمستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| options | DocSaveOptions | استخدام كائن [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) حيث ستجد معلومات حول كيفية تحويل SVG إلى [DOCX](https://docs.fileformat.com/word-processing/docx/) باستخدام طرق ConvertSVG() في فئة Converter وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى DOCX

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى DOCX. لتحويل SVG إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) يقوم بتحويل SVG إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### انظر أيضًا

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_40}

تحويل مصدر SVG المقدم عبر محتوى مضمن إلى DOCX. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | سلسلة كنص SVG مضمن. |
| baseUri | String | عنوان URI الأساسي للمستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | DocSaveOptions | استخدام كائن [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) حيث ستجد معلومات حول كيفية تحويل SVG إلى [DOCX](https://docs.fileformat.com/word-processing/docx/) باستخدام طرق ConvertSVG() في فئة Converter وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى DOCX

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى DOCX. لتحويل SVG إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) يقوم بتحويل SVG إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### انظر أيضًا

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, String) {#convertsvg_5}

تحويل مصدر SVG المقدم عبر [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) إلى PDF. النتيجة هي ملف pdf تم إنشاؤه عبر مسار ملف الإخراج.

```java
public static void ConvertSVG(SVGDocument source, PdfSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| source | SVGDocument | مصدر التحويل المقدم بواسطة [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | استخدام كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | مسار ملف pdf الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) حيث ستجد معلومات حول كيفية تحويل SVG إلى PDF باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى PDF

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى PDF. لتحويل SVG إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة PDF مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) يقوم بتحويل SVG إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // إنشاء مستند SVG كمصدر للتحويل
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // بدء عملية التحويل باستخدام التكوين الافتراضي
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, String) {#convertsvg_21}

تحويل مصدر SVG المقدم عبر [`URL`](../../../com.aspose.html/url/). النتيجة هي ملف pdf تم إنشاؤه عبر مسار ملف الإخراج.

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | مستند مصدر SVG [`URL`](../../../com.aspose.html/url/) - يوفر تمثيلًا كائنًا لمعرف عالمي (URL). |
| options | PdfSaveOptions | استخدام كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | مسار ملف pdf الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) حيث ستجد معلومات حول كيفية تحويل SVG إلى PDF باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى PDF

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى PDF. لتحويل SVG إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة PDF مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) يقوم بتحويل SVG إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // إنشاء Url بناءً على مسار ملف الإدخال
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertSVG(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, PdfSaveOptions, String) {#convertsvg_13}

تحويل مصدر SVG المقدم عبر [`URL`](../../../com.aspose.html/url/). النتيجة هي ملف pdf تم إنشاؤه عبر مسار ملف الإخراج.

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | مستند مصدر SVG [`URL`](../../../com.aspose.html/url/) - يوفر تمثيلًا كائنًا لمعرف عالمي (URL). |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | PdfSaveOptions | استخدام كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | مسار ملف pdf الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) حيث ستجد معلومات حول كيفية تحويل SVG إلى PDF باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى PDF

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى PDF. لتحويل SVG إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة PDF مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) يقوم بتحويل SVG إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // إنشاء Url بناءً على مسار ملف الإدخال
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, PdfSaveOptions, String) {#convertsvg_37}

تحويل مصدر SVG المقدم بواسطة مسار ملف كامل إلى PDF. النتيجة هي ملف PDF تم تشكيله بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف كامل لمصدر SVG. |
| options | PdfSaveOptions | استخدام كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | مسار ملف pdf الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) حيث ستجد معلومات حول كيفية تحويل SVG إلى PDF باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى PDF

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى PDF. لتحويل SVG إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة PDF مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) يقوم بتحويل SVG إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, PdfSaveOptions, String) {#convertsvg_29}

تحويل مصدر SVG المقدم بواسطة مسار ملف كامل إلى PDF. النتيجة هي ملف PDF تم تشكيله بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف كامل لمصدر SVG. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | PdfSaveOptions | استخدام كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | مسار ملف pdf الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) حيث ستجد معلومات حول كيفية تحويل SVG إلى PDF باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى PDF

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى PDF. لتحويل SVG إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة PDF مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) يقوم بتحويل SVG إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, PdfSaveOptions, String) {#convertsvg_53}

تحويل مصدر SVG المقدم عبر المحتوى المضمن إلى PDF. النتيجة هي ملف pdf تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | سلسلة كنص SVG مضمن. |
| baseUri | String | عنوان URI الأساسي للمستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| options | PdfSaveOptions | استخدام كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | مسار ملف pdf الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) حيث ستجد معلومات حول كيفية تحويل SVG إلى PDF باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى PDF

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى PDF. لتحويل SVG إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة PDF مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) يقوم بتحويل SVG إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // نموذج محتوى SVG مضمن
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### انظر أيضًا

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, String) {#convertsvg_45}

تحويل مصدر SVG المقدم عبر المحتوى المضمن إلى PDF. النتيجة هي ملف pdf تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | سلسلة كنص SVG مضمن. |
| baseUri | String | عنوان URI الأساسي للمستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | PdfSaveOptions | استخدام كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | مسار ملف pdf الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) حيث ستجد معلومات حول كيفية تحويل SVG إلى PDF باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى PDF

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى PDF. لتحويل SVG إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة PDF مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) يقوم بتحويل SVG إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // نموذج محتوى SVG مضمن
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### انظر أيضًا

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_4}

تحويل مصدر SVG المقدم عبر [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) إلى PDF. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| document | SVGDocument | مصدر التحويل المقدم بواسطة [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | استخدام كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | معروف (انظر [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) أو تنفيذ مخصص لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) حيث ستجد معلومات حول كيفية تحويل SVG إلى PDF باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى PDF

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى PDF. لتحويل SVG إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة PDF مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) يقوم بتحويل SVG إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // إنشاء مستند SVG كمصدر للتحويل
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // بدء عملية التحويل باستخدام التكوين الافتراضي
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_20}

تحويل مصدر SVG المقدم بواسطة [`URL`](../../../com.aspose.html/url/). النتيجة هي بيانات إخراج تم إنشاؤها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | مستند مصدر SVG [`URL`](../../../com.aspose.html/url/) - يوفر تمثيلًا كائنًا لمعرف عالمي (URL). |
| options | PdfSaveOptions | استخدام كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | معروف (انظر [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) أو تنفيذ مخصص لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) حيث ستجد معلومات حول كيفية تحويل SVG إلى PDF باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى PDF

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى PDF. لتحويل SVG إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة PDF مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) يقوم بتحويل SVG إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // إنشاء Url بناءً على مسار ملف الإدخال
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل
      Converter.ConvertSVG(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_12}

تحويل مصدر SVG المقدم بواسطة [`URL`](../../../com.aspose.html/url/). النتيجة هي بيانات إخراج تم إنشاؤها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | مستند مصدر SVG [`URL`](../../../com.aspose.html/url/) - يوفر تمثيلًا كائنًا لمعرف عالمي (URL). |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | PdfSaveOptions | استخدام كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | معروف (انظر [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) أو تنفيذ مخصص لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) حيث ستجد معلومات حول كيفية تحويل SVG إلى PDF باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى PDF

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى PDF. لتحويل SVG إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة PDF مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) يقوم بتحويل SVG إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // إنشاء Url بناءً على مسار ملف الإدخال
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_36}

تحويل مصدر SVG المقدم عبر مسار ملف كامل إلى PDF. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف كامل لمصدر SVG. |
| options | PdfSaveOptions | استخدام كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) حيث ستجد معلومات حول كيفية تحويل SVG إلى PDF باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى PDF

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى PDF. لتحويل SVG إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة PDF مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) يقوم بتحويل SVG إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_28}

تحويل مصدر SVG المقدم عبر مسار ملف كامل إلى PDF. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف كامل لمصدر SVG. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | PdfSaveOptions | استخدام كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) حيث ستجد معلومات حول كيفية تحويل SVG إلى PDF باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى PDF

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى PDF. لتحويل SVG إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة PDF مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) يقوم بتحويل SVG إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_52}

تحويل مصدر SVG المقدم عبر محتوى مضمن إلى PDF. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | سلسلة كنص SVG مضمن. |
| baseUri | String | عنوان URI الأساسي للمستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| options | PdfSaveOptions | استخدام كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) حيث ستجد معلومات حول كيفية تحويل SVG إلى PDF باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى PDF

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى PDF. لتحويل SVG إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة PDF مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) يقوم بتحويل SVG إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### انظر أيضًا

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_44}

تحويل مصدر SVG المقدم عبر محتوى مضمن إلى PDF. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | سلسلة كنص SVG مضمن. |
| baseUri | String | عنوان URI الأساسي للمستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | PdfSaveOptions | استخدام كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية التصيير. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | معروف (انظر [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) أو تنفيذ مخصص لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) حيث ستجد معلومات حول كيفية تحويل SVG إلى PDF باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى PDF

تقدم فئة Converter عدة تحويلات خاصة بـ SVG إلى PDF. لتحويل SVG إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم عبر مصدر من نوع String. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة PDF مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) يقوم بتحويل SVG إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى رفع ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### انظر أيضًا

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, String) {#convertsvg_3}

تحويل مصدر SVG المقدم بواسطة [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). النتيجة هي ملف صورة يتم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(SVGDocument source, ImageSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| source | SVGDocument | مصدر التحويل المقدم بواسطة [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| outputPath | String | مسار ملف الصورة الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) حيث ستجد معلومات حول كيفية تحويل SVG إلى JPG باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). مقالات أخرى متعلقة بصيغ الصور الشائعة: [تحويل SVG إلى PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)، [تحويل SVG إلى BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)، [تحويل SVG إلى GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) و[تحويل SVG إلى TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

تحويل SVG إلى صورة

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى صورة في صيغ شائعة. لتحويل SVG إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم كسلسلة نصية. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. لاحظ أن صيغة الصورة الافتراضية هي PNG. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة صورة مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) يقوم بتحويل SVG إلى JPG بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

يمكن العثور على محولات صور شائعة أخرى لتنسيقات مختلفة هنا: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)، [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)، [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) و[SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions();

      // إنشاء مستند SVG كمصدر للتحويل
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // بدء عملية التحويل باستخدام التكوين الافتراضي
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, String) {#convertsvg_19}

تحويل مصدر SVG المقدم بواسطة [`URL`](../../../com.aspose.html/url/). النتيجة هي ملف صورة يتم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | مستند مصدر SVG [`URL`](../../../com.aspose.html/url/) - يوفر تمثيلًا كائنًا لمعرف عالمي (URL). |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| outputPath | String | مسار ملف الصورة الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) حيث ستجد معلومات حول كيفية تحويل SVG إلى JPG باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). مقالات أخرى متعلقة بصيغ الصور الشائعة: [تحويل SVG إلى PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)، [تحويل SVG إلى BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)، [تحويل SVG إلى GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) و[تحويل SVG إلى TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

تحويل SVG إلى صورة

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى صورة في صيغ شائعة. لتحويل SVG إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم كسلسلة نصية. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. لاحظ أن صيغة الصورة الافتراضية هي PNG. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة صورة مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) يقوم بتحويل SVG إلى JPG بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

يمكن العثور على محولات صور شائعة أخرى لتنسيقات مختلفة هنا: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)، [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)، [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) و[SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // إنشاء Url بناءً على مسار ملف الإدخال
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // بدء عملية التحويل
      Converter.ConvertSVG(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, ImageSaveOptions, String) {#convertsvg_11}

تحويل مصدر SVG المقدم بواسطة [`URL`](../../../com.aspose.html/url/). النتيجة هي ملف صورة يتم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | مستند مصدر SVG [`URL`](../../../com.aspose.html/url/) - يوفر تمثيلًا كائنًا لمعرف عالمي (URL). |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| outputPath | String | مسار ملف الصورة الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) حيث ستجد معلومات حول كيفية تحويل SVG إلى JPG باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). مقالات أخرى متعلقة بصيغ الصور الشائعة: [تحويل SVG إلى PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)، [تحويل SVG إلى BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)، [تحويل SVG إلى GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) و[تحويل SVG إلى TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

تحويل SVG إلى صورة

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى صورة في صيغ شائعة. لتحويل SVG إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم كسلسلة نصية. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. لاحظ أن صيغة الصورة الافتراضية هي PNG. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة صورة مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) يقوم بتحويل SVG إلى JPG بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

يمكن العثور على محولات صور شائعة أخرى لتنسيقات مختلفة هنا: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)، [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)، [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) و[SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // إنشاء Url بناءً على مسار ملف الإدخال
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, ImageSaveOptions, String) {#convertsvg_35}

تحويل مصدر SVG المقدم بواسطة مسار ملف كامل إلى صورة. النتيجة هي ملف صورة تم تشكيله بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف كامل لمصدر SVG. |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| outputPath | String | مسار ملف الصورة الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) حيث ستجد معلومات حول كيفية تحويل SVG إلى JPG باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). مقالات أخرى متعلقة بصيغ الصور الشائعة: [تحويل SVG إلى PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)، [تحويل SVG إلى BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)، [تحويل SVG إلى GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) و[تحويل SVG إلى TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

تحويل SVG إلى صورة

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى صورة في صيغ شائعة. لتحويل SVG إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم كسلسلة نصية. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. لاحظ أن صيغة الصورة الافتراضية هي PNG. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة صورة مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) يقوم بتحويل SVG إلى JPG بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

يمكن العثور على محولات صور شائعة أخرى لتنسيقات مختلفة هنا: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)، [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)، [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) و[SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // بدء عملية التحويل
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, ImageSaveOptions, String) {#convertsvg_27}

تحويل مصدر SVG المقدم بواسطة مسار ملف كامل إلى صورة. النتيجة هي ملف صورة تم تشكيله بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف كامل لمصدر SVG. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| outputPath | String | مسار ملف الصورة الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) حيث ستجد معلومات حول كيفية تحويل SVG إلى JPG باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). مقالات أخرى متعلقة بصيغ الصور الشائعة: [تحويل SVG إلى PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)، [تحويل SVG إلى BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)، [تحويل SVG إلى GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) و[تحويل SVG إلى TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

تحويل SVG إلى صورة

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى صورة في صيغ شائعة. لتحويل SVG إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم كسلسلة نصية. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. لاحظ أن صيغة الصورة الافتراضية هي PNG. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة صورة مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) يقوم بتحويل SVG إلى JPG بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

يمكن العثور على محولات صور شائعة أخرى لتنسيقات مختلفة هنا: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)، [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)، [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) و[SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, ImageSaveOptions, String) {#convertsvg_51}

تحويل مصدر SVG المقدم عبر المحتوى المضمن إلى صورة. النتيجة هي ملف صورة تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | سلسلة كنص SVG مضمن. |
| baseUri | String | عنوان URI الأساسي للمستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| outputPath | String | مسار ملف الصورة الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) حيث ستجد معلومات حول كيفية تحويل SVG إلى JPG باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). مقالات أخرى متعلقة بصيغ الصور الشائعة: [تحويل SVG إلى PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)، [تحويل SVG إلى BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)، [تحويل SVG إلى GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) و[تحويل SVG إلى TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

تحويل SVG إلى صورة

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى صورة في صيغ شائعة. لتحويل SVG إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم كسلسلة نصية. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. لاحظ أن صيغة الصورة الافتراضية هي PNG. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة صورة مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) يقوم بتحويل SVG إلى JPG بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

يمكن العثور على محولات صور شائعة أخرى لتنسيقات مختلفة هنا: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)، [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)، [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) و[SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // نموذج محتوى SVG مضمن
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### انظر أيضًا

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, String) {#convertsvg_43}

تحويل مصدر SVG المقدم عبر المحتوى المضمن إلى صورة. النتيجة هي ملف صورة تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | سلسلة كنص SVG مضمن. |
| baseUri | String | عنوان URI الأساسي للمستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| outputPath | String | مسار ملف الصورة الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) حيث ستجد معلومات حول كيفية تحويل SVG إلى JPG باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). مقالات أخرى متعلقة بصيغ الصور الشائعة: [تحويل SVG إلى PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)، [تحويل SVG إلى BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)، [تحويل SVG إلى GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) و[تحويل SVG إلى TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

تحويل SVG إلى صورة

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى صورة في صيغ شائعة. لتحويل SVG إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم كسلسلة نصية. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. لاحظ أن صيغة الصورة الافتراضية هي PNG. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة صورة مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) يقوم بتحويل SVG إلى JPG بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

يمكن العثور على محولات صور شائعة أخرى لتنسيقات مختلفة هنا: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)، [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)، [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) و[SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // نموذج محتوى SVG مضمن
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### انظر أيضًا

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_2}

تحويل مصدر SVG المقدم بواسطة [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). النتيجة هي بيانات إخراج تم إنشاؤها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertSVG(SVGDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| document | SVGDocument | مصدر التحويل المقدم بواسطة [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| provider | ICreateStreamProvider | معروف (انظر [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) أو تنفيذ مخصص لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) حيث ستجد معلومات حول كيفية تحويل SVG إلى JPG باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). مقالات أخرى متعلقة بصيغ الصور الشائعة: [تحويل SVG إلى PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)، [تحويل SVG إلى BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)، [تحويل SVG إلى GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) و[تحويل SVG إلى TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

تحويل SVG إلى صورة

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى صورة في صيغ شائعة. لتحويل SVG إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم كسلسلة نصية. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. لاحظ أن صيغة الصورة الافتراضية هي PNG. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة صورة مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) يقوم بتحويل SVG إلى JPG بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

يمكن العثور على محولات صور شائعة أخرى لتنسيقات مختلفة هنا: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)، [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)، [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) و[SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // إنشاء مستند SVG كمصدر للتحويل
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // بدء عملية التحويل
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_18}

تحويل مصدر SVG المقدم بواسطة [`URL`](../../../com.aspose.html/url/). النتيجة هي بيانات إخراج تم إنشاؤها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | مستند مصدر SVG [`URL`](../../../com.aspose.html/url/) - يوفر تمثيلًا كائنًا لمعرف عالمي (URL). |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) حيث ستجد معلومات حول كيفية تحويل SVG إلى JPG باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). مقالات أخرى متعلقة بصيغ الصور الشائعة: [تحويل SVG إلى PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)، [تحويل SVG إلى BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)، [تحويل SVG إلى GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) و[تحويل SVG إلى TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

تحويل SVG إلى صورة

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى صورة في صيغ شائعة. لتحويل SVG إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم كسلسلة نصية. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. لاحظ أن صيغة الصورة الافتراضية هي PNG. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة صورة مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) يقوم بتحويل SVG إلى JPG بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

يمكن العثور على محولات صور شائعة أخرى لتنسيقات مختلفة هنا: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)، [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)، [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) و[SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // إنشاء Url بناءً على مسار ملف الإدخال
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل
      Converter.ConvertSVG(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_10}

تحويل مصدر SVG المقدم بواسطة [`URL`](../../../com.aspose.html/url/). النتيجة هي بيانات إخراج تم إنشاؤها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | مستند مصدر SVG [`URL`](../../../com.aspose.html/url/) - يوفر تمثيلًا كائنًا لمعرف عالمي (URL). |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) حيث ستجد معلومات حول كيفية تحويل SVG إلى JPG باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). مقالات أخرى متعلقة بصيغ الصور الشائعة: [تحويل SVG إلى PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)، [تحويل SVG إلى BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)، [تحويل SVG إلى GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) و[تحويل SVG إلى TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

تحويل SVG إلى صورة

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى صورة في صيغ شائعة. لتحويل SVG إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم كسلسلة نصية. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. لاحظ أن صيغة الصورة الافتراضية هي PNG. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة صورة مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) يقوم بتحويل SVG إلى JPG بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

يمكن العثور على محولات صور شائعة أخرى لتنسيقات مختلفة هنا: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)، [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)، [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) و[SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // إنشاء Url بناءً على مسار ملف الإدخال
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_34}

تحويل مصدر SVG المقدم بواسطة مسار ملف كامل إلى صورة. النتيجة هي بيانات إخراج يتم إنشاؤها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف كامل لمصدر SVG. |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) حيث ستجد معلومات حول كيفية تحويل SVG إلى JPG باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). مقالات أخرى متعلقة بصيغ الصور الشائعة: [تحويل SVG إلى PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)، [تحويل SVG إلى BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)، [تحويل SVG إلى GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) و[تحويل SVG إلى TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

تحويل SVG إلى صورة

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى صورة في صيغ شائعة. لتحويل SVG إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم كسلسلة نصية. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. لاحظ أن صيغة الصورة الافتراضية هي PNG. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة صورة مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) يقوم بتحويل SVG إلى JPG بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

يمكن العثور على محولات صور شائعة أخرى لتنسيقات مختلفة هنا: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)، [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)، [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) و[SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_26}

تحويل مصدر SVG المقدم بواسطة مسار ملف كامل إلى صورة. النتيجة هي بيانات إخراج يتم إنشاؤها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف كامل لمصدر SVG. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| provider | ICreateStreamProvider | معروف (انظر [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) أو تنفيذ مخصص لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) حيث ستجد معلومات حول كيفية تحويل SVG إلى JPG باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). مقالات أخرى متعلقة بصيغ الصور الشائعة: [تحويل SVG إلى PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)، [تحويل SVG إلى BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)، [تحويل SVG إلى GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) و[تحويل SVG إلى TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

تحويل SVG إلى صورة

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى صورة في صيغ شائعة. لتحويل SVG إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم كسلسلة نصية. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. لاحظ أن صيغة الصورة الافتراضية هي PNG. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة صورة مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) يقوم بتحويل SVG إلى JPG بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

يمكن العثور على محولات صور شائعة أخرى لتنسيقات مختلفة هنا: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)، [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)، [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) و[SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_50}

تحويل مصدر SVG المقدم بواسطة محتوى مضمن إلى صورة. النتيجة هي بيانات إخراج يتم إنشاؤها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | سلسلة كنص SVG مضمن. |
| baseUri | String | عنوان URI الأساسي للمستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| provider | ICreateStreamProvider | معروف (انظر [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) أو تنفيذ مخصص لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) حيث ستجد معلومات حول كيفية تحويل SVG إلى JPG باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). مقالات أخرى متعلقة بصيغ الصور الشائعة: [تحويل SVG إلى PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)، [تحويل SVG إلى BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)، [تحويل SVG إلى GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) و[تحويل SVG إلى TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

تحويل SVG إلى صورة

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى صورة في صيغ شائعة. لتحويل SVG إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم كسلسلة نصية. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. لاحظ أن صيغة الصورة الافتراضية هي PNG. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة صورة مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) يقوم بتحويل SVG إلى JPG بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

يمكن العثور على محولات صور شائعة أخرى لتنسيقات مختلفة هنا: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)، [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)، [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) و[SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### انظر أيضًا

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_42}

تحويل مصدر SVG المقدم بواسطة محتوى مضمن إلى صورة. النتيجة هي بيانات إخراج يتم إنشاؤها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | سلسلة كنص SVG مضمن. |
| baseUri | String | عنوان URI الأساسي للمستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) حيث ستجد معلومات حول كيفية تحويل SVG إلى JPG باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). مقالات أخرى متعلقة بصيغ الصور الشائعة: [تحويل SVG إلى PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)، [تحويل SVG إلى BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)، [تحويل SVG إلى GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) و[تحويل SVG إلى TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

تحويل SVG إلى صورة

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى صورة في صيغ شائعة. لتحويل SVG إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم كسلسلة نصية. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. لاحظ أن صيغة الصورة الافتراضية هي PNG. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة صورة مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول SVG عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) يقوم بتحويل SVG إلى JPG بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

يمكن العثور على محولات صور شائعة أخرى لتنسيقات مختلفة هنا: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)، [SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)، [SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) و[SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### انظر أيضًا

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, XpsSaveOptions, String) {#convertsvg_7}

تحويل مصدر SVG المقدم بواسطة [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). النتيجة هي ملف xps يتم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(SVGDocument source, XpsSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| source | SVGDocument | مصدر التحويل المقدم بواسطة [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | استخدام كائن [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | المسار الكامل لملف xps كناتج التحويل. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

ارجع إلى [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) حيث ستجد معلومات حول كيفية تحويل SVG إلى XPS باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى XPS

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى XPS. لتحويل SVG إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو بعيد باستخدام [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم بواسطة مصدر String. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة XPS مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) يقوم بتحويل SVG إلى XPS بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك وتحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // إنشاء مستند SVG كمصدر للتحويل
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
		// بدء عملية التحويل باستخدام التكوين الافتراضي
		Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, String) {#convertsvg_23}

تحويل مصدر SVG المقدم بواسطة [`URL`](../../../com.aspose.html/url/). النتيجة هي ملف xps يتم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | مستند مصدر SVG [`URL`](../../../com.aspose.html/url/) - يوفر تمثيلًا كائنًا لمعرف عالمي (URL). |
| options | XpsSaveOptions | استخدام كائن [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | المسار الكامل لملف xps كناتج التحويل. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

ارجع إلى [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) حيث ستجد معلومات حول كيفية تحويل SVG إلى XPS باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى XPS

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى XPS. لتحويل SVG إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو بعيد باستخدام [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم بواسطة مصدر String. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة XPS مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) يقوم بتحويل SVG إلى XPS بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك وتحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // إنشاء Url بناءً على مسار ملف الإدخال     
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertSVG(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, XpsSaveOptions, String) {#convertsvg_15}

تحويل مصدر SVG المقدم بواسطة [`URL`](../../../com.aspose.html/url/). النتيجة هي ملف xps يتم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | مستند مصدر SVG [`URL`](../../../com.aspose.html/url/) - يوفر تمثيلًا كائنًا لمعرف عالمي (URL). |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | XpsSaveOptions | استخدام كائن [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | المسار الكامل لملف xps كناتج التحويل. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

ارجع إلى [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) حيث ستجد معلومات حول كيفية تحويل SVG إلى XPS باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى XPS

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى XPS. لتحويل SVG إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو بعيد باستخدام [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم بواسطة مصدر String. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة XPS مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) يقوم بتحويل SVG إلى XPS بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك وتحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // إنشاء Url بناءً على مسار ملف الإدخال
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, XpsSaveOptions, String) {#convertsvg_39}

تحويل مصدر SVG المقدم بواسطة مسار ملف كامل إلى XPS. النتيجة هي ملف XPS تم تشكيله بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف كامل لمصدر SVG. |
| options | XpsSaveOptions | استخدام كائن [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. |
| outputPath | String | المسار الكامل لملف xps كناتج التحويل. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

ارجع إلى [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) حيث ستجد معلومات حول كيفية تحويل SVG إلى XPS باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى XPS

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى XPS. لتحويل SVG إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو بعيد باستخدام [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم بواسطة مصدر String. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة XPS مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) يقوم بتحويل SVG إلى XPS بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك وتحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, String) {#convertsvg_31}

تحويل مصدر SVG المقدم بواسطة مسار ملف كامل إلى XPS. النتيجة هي ملف XPS تم تشكيله بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف كامل لمصدر SVG. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | XpsSaveOptions | استخدام كائن [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | المسار الكامل لملف xps كناتج التحويل. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

ارجع إلى [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) حيث ستجد معلومات حول كيفية تحويل SVG إلى XPS باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى XPS

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى XPS. لتحويل SVG إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو بعيد باستخدام [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم بواسطة مصدر String. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة XPS مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) يقوم بتحويل SVG إلى XPS بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك وتحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, XpsSaveOptions, String) {#convertsvg_55}

تحويل مصدر SVG المقدم عبر المحتوى المضمن إلى XPS. النتيجة هي ملف xps تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | سلسلة كنص SVG مضمن. |
| baseUri | String | عنوان URI الأساسي للمستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| options | XpsSaveOptions | استخدام كائن [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. |
| outputPath | String | المسار الكامل لملف xps كناتج التحويل. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

ارجع إلى [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) حيث ستجد معلومات حول كيفية تحويل SVG إلى XPS باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى XPS

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى XPS. لتحويل SVG إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو بعيد باستخدام [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم بواسطة مصدر String. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة XPS مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) يقوم بتحويل SVG إلى XPS بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك وتحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // نموذج محتوى SVG مضمن
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### انظر أيضًا

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, String) {#convertsvg_47}

تحويل مصدر SVG المقدم عبر المحتوى المضمن إلى XPS. النتيجة هي ملف xps تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | سلسلة كنص SVG مضمن. |
| baseUri | String | عنوان URI الأساسي للمستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | XpsSaveOptions | استخدام كائن [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | المسار الكامل لملف xps كناتج التحويل. |

## ملاحظات

محول SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

ارجع إلى [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) حيث ستجد معلومات حول كيفية تحويل SVG إلى XPS باستخدام طرق ConvertSVG() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل SVG إلى XPS

توفر فئة Converter تحويلات متعددة خاصة بـ SVG إلى XPS. لتحويل SVG إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف SVG محلي موجود أو بعيد باستخدام [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا تعريف [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) كمصدر للتحويل أو حتى استخدام محتوى SVG مضمن مقدم بواسطة مصدر String. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كذاكرة مؤقتة لبيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertSVG() في فئة Converter لحفظ SVG كنتيجة XPS مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول SVG عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) يقوم بتحويل SVG إلى XPS بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك وتحويلها والحصول على النتائج في بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // نموذج محتوى SVG مضمن
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### انظر أيضًا

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
