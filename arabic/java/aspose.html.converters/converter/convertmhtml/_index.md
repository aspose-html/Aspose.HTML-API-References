---
title: "Converter.ConvertMHTML"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة Converter. تحويل مصدر MHTML المقدم بواسطة تدفق الإدخال. النتيجة هي ملف xps يتم إنشاؤه بواسطة مسار ملف الإخراج"
type: docs

url: /ar/java/com.aspose.html.converters/converter/convertmhtml/
---
## ConvertMHTML(Stream, XpsSaveOptions, String) {#convertmhtml_31}

تحويل مصدر MHTML المقدم عبر [تدفق](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). النتيجة هي ملف xps تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | تدفق بيانات mhtml (.mht) الإدخال. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [وثائق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | المسار الكامل لملف xps كناتج التحويل. |

## ملاحظات

محول MHTML

غالبًا ما تكون عملية تحويل MHTML إلى [XPS](https://docs.fileformat.com/page-description-language/xps/) مطلوبة للاستفادة من تنسيق XPS في مهام محددة. يمثل ملف XPS ملفات تخطيط الصفحات التي تعتمد على مواصفات XML Paper، التي أنشأتها Microsoft.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى XPS باستخدام طرق ConvertHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى XPS

توفر فئة Converter عددًا قليلًا من التحويلات الخاصة بـ MHTML إلى XPS. لتحويل MHTML إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة XPS مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) يقوم بتحويل MHTML إلى XPS بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, String) {#convertmhtml_47}

تحويل مصدر MHTML المقدم بواسطة مسار ملف كامل إلى XPS. النتيجة هي ملف XPS تم تشكيله بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف المصدر الكامل لـ MHTML. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [وثائق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | المسار الكامل لملف xps كناتج التحويل. |

## ملاحظات

محول MHTML

غالبًا ما تكون عملية تحويل MHTML إلى [XPS](https://docs.fileformat.com/page-description-language/xps/) مطلوبة للاستفادة من تنسيق XPS في مهام محددة. يمثل ملف XPS ملفات تخطيط الصفحات التي تعتمد على مواصفات XML Paper، التي أنشأتها Microsoft.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى XPS باستخدام طرق ConvertHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى XPS

توفر فئة Converter عددًا قليلًا من التحويلات الخاصة بـ MHTML إلى XPS. لتحويل MHTML إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة XPS مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) يقوم بتحويل MHTML إلى XPS بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// مسار ملف المصدر للنموذج
	var sourcePath = Path.Combine(InputFolder, "sample.mht");

	// مسار ملف النتيجة للنموذج
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// حدد كائن XpsSaveOptions الافتراضي
	var options = new XpsSaveOptions();

	// بدء عملية التحويل
	Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, String) {#convertmhtml_15}

تحويل مصدر MHTML المقدم عبر URL. النتيجة هي ملف XPS تم تشكيله بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceUrl | Url | عنوان URL لمستند مصدر MHTML - يوفر تمثيلًا كائنًا لمعرّف عالمي (URL). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [وثائق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | المسار الكامل لملف xps كناتج التحويل. |

## ملاحظات

محول MHTML

غالبًا ما تكون عملية تحويل MHTML إلى [XPS](https://docs.fileformat.com/page-description-language/xps/) مطلوبة للاستفادة من تنسيق XPS في مهام محددة. يمثل ملف XPS ملفات تخطيط الصفحات التي تعتمد على مواصفات XML Paper، التي أنشأتها Microsoft.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى XPS باستخدام طرق ConvertHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى XPS

توفر فئة Converter عددًا قليلًا من التحويلات الخاصة بـ MHTML إلى XPS. لتحويل MHTML إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة XPS مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) يقوم بتحويل MHTML إلى XPS بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// مسار ملف المصدر للنموذج
	var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

	// مسار ملف النتيجة للنموذج
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// حدد كائن XpsSaveOptions الافتراضي
	var options = new XpsSaveOptions();

	// بدء عملية التحويل
	Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, String) {#convertmhtml_23}

تحويل مصدر MHTML المقدم بواسطة إدخال [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0). النتيجة هي ملف XPS تم تشكيله بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | تدفق بيانات مصدر التحويل mhtml (.mht). |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [وثائق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | المسار الكامل لملف xps كناتج التحويل. |

## ملاحظات

محول MHTML

غالبًا ما تكون عملية تحويل MHTML إلى [XPS](https://docs.fileformat.com/page-description-language/xps/) مطلوبة للاستفادة من تنسيق XPS في مهام محددة. يمثل ملف XPS ملفات تخطيط الصفحات التي تعتمد على مواصفات XML Paper، التي أنشأتها Microsoft.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى XPS باستخدام طرق ConvertHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى XPS

توفر فئة Converter عددًا قليلًا من التحويلات الخاصة بـ MHTML إلى XPS. لتحويل MHTML إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة XPS مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) يقوم بتحويل MHTML إلى XPS بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(File.OpenRead(sourcePath), new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### انظر أيضًا

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, String) {#convertmhtml_39}

تحويل مصدر MHTML المقدم بواسطة مسار ملف كامل إلى XPS. النتيجة هي ملف XPS تم تشكيله بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف المصدر الكامل لـ MHTML. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [وثائق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | المسار الكامل لملف xps كناتج التحويل. |

## ملاحظات

محول MHTML

غالبًا ما تكون عملية تحويل MHTML إلى [XPS](https://docs.fileformat.com/page-description-language/xps/) مطلوبة للاستفادة من تنسيق XPS في مهام محددة. يمثل ملف XPS ملفات تخطيط الصفحات التي تعتمد على مواصفات XML Paper، التي أنشأتها Microsoft.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى XPS باستخدام طرق ConvertHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى XPS

توفر فئة Converter عددًا قليلًا من التحويلات الخاصة بـ MHTML إلى XPS. لتحويل MHTML إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة XPS مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) يقوم بتحويل MHTML إلى XPS بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // مسار ملف المصدر للنموذج
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, XpsSaveOptions, String) {#convertmhtml_7}

تحويل مصدر MHTML المقدم عبر URL. النتيجة هي ملف XPS تم تشكيله بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceUrl | Url | عنوان URL لمستند مصدر MHTML - يوفر تمثيلًا كائنًا لمعرّف عالمي (URL). |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [وثائق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | المسار الكامل لملف xps كناتج التحويل. |

## ملاحظات

محول MHTML

غالبًا ما تكون عملية تحويل MHTML إلى [XPS](https://docs.fileformat.com/page-description-language/xps/) مطلوبة للاستفادة من تنسيق XPS في مهام محددة. يمثل ملف XPS ملفات تخطيط الصفحات التي تعتمد على مواصفات XML Paper، التي أنشأتها Microsoft.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى XPS باستخدام طرق ConvertHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى XPS

توفر فئة Converter عددًا قليلًا من التحويلات الخاصة بـ MHTML إلى XPS. لتحويل MHTML إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة XPS مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) يقوم بتحويل MHTML إلى XPS بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

الكود المصدري

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## أمثلة

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // مسار ملف المصدر للنموذج
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_30}

تحويل مصدر MHTML المقدم عبر تدفق الإدخال. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | تدفق بيانات مصدر التحويل mhtml (.mht). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [وثائق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول MHTML

غالبًا ما تكون عملية تحويل MHTML إلى [XPS](https://docs.fileformat.com/page-description-language/xps/) مطلوبة للاستفادة من تنسيق XPS في مهام محددة. يمثل ملف XPS ملفات تخطيط الصفحات التي تعتمد على مواصفات XML Paper، التي أنشأتها Microsoft.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى XPS باستخدام طرق ConvertHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى XPS

توفر فئة Converter عددًا قليلًا من التحويلات الخاصة بـ MHTML إلى XPS. لتحويل MHTML إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة XPS مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) يقوم بتحويل MHTML إلى XPS بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### انظر أيضًا

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_46}

تحويل مصدر MHTML المقدم عبر مسار ملف كامل إلى XPS. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف المصدر الكامل لـ MHTML. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [وثائق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | معروف (انظر [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) أو تنفيذ مخصص لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## ملاحظات

محول MHTML

غالبًا ما تكون عملية تحويل MHTML إلى [XPS](https://docs.fileformat.com/page-description-language/xps/) مطلوبة للاستفادة من تنسيق XPS في مهام محددة. يمثل ملف XPS ملفات تخطيط الصفحات التي تعتمد على مواصفات XML Paper، التي أنشأتها Microsoft.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى XPS باستخدام طرق ConvertHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى XPS

توفر فئة Converter عددًا قليلًا من التحويلات الخاصة بـ MHTML إلى XPS. لتحويل MHTML إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة XPS مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) يقوم بتحويل MHTML إلى XPS بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل
      Converter.ConvertMHTML(sourcePath, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### انظر أيضًا

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_14}

تحويل مصدر MHTML المقدم عبر [`URL`](../../../com.aspose.html/url/). النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceUrl | Url | عنوان URL لمستند مصدر MHTML - يوفر تمثيلًا كائنًا لمعرّف عالمي (URL). |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [وثائق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول MHTML

غالبًا ما تكون عملية تحويل MHTML إلى [XPS](https://docs.fileformat.com/page-description-language/xps/) مطلوبة للاستفادة من تنسيق XPS في مهام محددة. يمثل ملف XPS ملفات تخطيط الصفحات التي تعتمد على مواصفات XML Paper، التي أنشأتها Microsoft.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى XPS باستخدام طرق ConvertHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى XPS

توفر فئة Converter عددًا قليلًا من التحويلات الخاصة بـ MHTML إلى XPS. لتحويل MHTML إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة XPS مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) يقوم بتحويل MHTML إلى XPS بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل
      Converter.ConvertMHTML(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_22}

تحويل مصدر MHTML المقدم عبر تدفق الإدخال. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | تدفق بيانات مصدر التحويل mhtml (.mht). |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [وثائق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول MHTML

غالبًا ما تكون عملية تحويل MHTML إلى [XPS](https://docs.fileformat.com/page-description-language/xps/) مطلوبة للاستفادة من تنسيق XPS في مهام محددة. يمثل ملف XPS ملفات تخطيط الصفحات التي تعتمد على مواصفات XML Paper، التي أنشأتها Microsoft.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى XPS باستخدام طرق ConvertHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى XPS

توفر فئة Converter عددًا قليلًا من التحويلات الخاصة بـ MHTML إلى XPS. لتحويل MHTML إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة XPS مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) يقوم بتحويل MHTML إلى XPS بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertMHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_38}

تحويل مصدر MHTML المقدم عبر مسار ملف كامل إلى XPS. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف المصدر الكامل لـ MHTML. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [وثائق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | معروف (انظر [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) أو تنفيذ مخصص لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## ملاحظات

محول MHTML

غالبًا ما تكون عملية تحويل MHTML إلى [XPS](https://docs.fileformat.com/page-description-language/xps/) مطلوبة للاستفادة من تنسيق XPS في مهام محددة. يمثل ملف XPS ملفات تخطيط الصفحات التي تعتمد على مواصفات XML Paper، التي أنشأتها Microsoft.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى XPS باستخدام طرق ConvertHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى XPS

توفر فئة Converter عددًا قليلًا من التحويلات الخاصة بـ MHTML إلى XPS. لتحويل MHTML إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة XPS مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) يقوم بتحويل MHTML إلى XPS بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_6}

تحويل مصدر MHTML المقدم عبر URL. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceUrl | Url | عنوان URL لمستند مصدر MHTML - يوفر تمثيلًا كائنًا لمعرّف عالمي (URL). |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [وثائق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | معروف (انظر [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) أو تنفيذ مخصص لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## ملاحظات

محول MHTML

غالبًا ما تكون عملية تحويل MHTML إلى [XPS](https://docs.fileformat.com/page-description-language/xps/) مطلوبة للاستفادة من تنسيق XPS في مهام محددة. يمثل ملف XPS ملفات تخطيط الصفحات التي تعتمد على مواصفات XML Paper، التي أنشأتها Microsoft.

ارجع إلى [المقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى XPS باستخدام طرق ConvertHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى XPS

توفر فئة Converter عددًا قليلًا من التحويلات الخاصة بـ MHTML إلى XPS. لتحويل MHTML إلى XPS، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو مصدر بعيد [`Url`](../../../com.aspose.html/url/) كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم تنفيذًا معروفًا أو مخصصًا لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) كقائمة بيانات الإخراج. أنشئ كائنًا جديدًا من [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة XPS مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) يقوم بتحويل MHTML إلى XPS بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج خلال بضع ثوانٍ!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // حدد كائن XpsSaveOptions الافتراضي
      var options = new XpsSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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

## ConvertMHTML(Stream, DocSaveOptions, String) {#convertmhtml_25}

تحويل مصدر MHTML المقدم عبر تدفق الإدخال. النتيجة هي ملف docx تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | تدفق بيانات الإدخال لتحويل MHTML. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | مسار ملف docx الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى DOCX مطلوبًا للاستفادة من تنسيق [DOCX](https://docs.fileformat.com/word-processing/docx/) لمهام محددة. يُعد DOCX تنسيقًا معروفًا لمستندات Microsoft Word. يمكنه احتواء مجموعة واسعة من البيانات، بما في ذلك النصوص والجداول والرسومات النقطية والمتجهة والفيديو والأصوات والرسوم البيانية. يُفضَّل هذا التنسيق لأنه يدعم ميزات تنسيق معقدة ويقدم للمستخدمين مجموعة متنوعة من الخيارات لكتابة أي نوع من المستندات.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى DOCX باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى DOCX

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى DOCX. لتحويل MHTML إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروف أو المخصص كذاكرة مؤقتة للبيانات. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) يقوم بتحويل MHTML إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### انظر أيضًا

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, String) {#convertmhtml_41}

تحويل مصدر MHTML المقدم عبر مسار ملف كامل إلى DOCX. النتيجة هي ملف docx تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف مصدر MHTML. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | مسار ملف docx الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى DOCX مطلوبًا للاستفادة من تنسيق [DOCX](https://docs.fileformat.com/word-processing/docx/) لمهام محددة. يُعد DOCX تنسيقًا معروفًا لمستندات Microsoft Word. يمكنه احتواء مجموعة واسعة من البيانات، بما في ذلك النصوص والجداول والرسومات النقطية والمتجهة والفيديو والأصوات والرسوم البيانية. يُفضَّل هذا التنسيق لأنه يدعم ميزات تنسيق معقدة ويقدم للمستخدمين مجموعة متنوعة من الخيارات لكتابة أي نوع من المستندات.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى DOCX باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى DOCX

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى DOCX. لتحويل MHTML إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروف أو المخصص كذاكرة مؤقتة للبيانات. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) يقوم بتحويل MHTML إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, String) {#convertmhtml_9}

تحويل مصدر MHTML المقدم عبر URL. النتيجة هي ملف DOCX تم تشكيله بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceUrl | Url | عنوان URL لمستند مصدر MHTML - يوفر تمثيلًا كائنًا لمعرّف عالمي (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | مسار ملف docx الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى DOCX مطلوبًا للاستفادة من تنسيق [DOCX](https://docs.fileformat.com/word-processing/docx/) لمهام محددة. يُعد DOCX تنسيقًا معروفًا لمستندات Microsoft Word. يمكنه احتواء مجموعة واسعة من البيانات، بما في ذلك النصوص والجداول والرسومات النقطية والمتجهة والفيديو والأصوات والرسوم البيانية. يُفضَّل هذا التنسيق لأنه يدعم ميزات تنسيق معقدة ويقدم للمستخدمين مجموعة متنوعة من الخيارات لكتابة أي نوع من المستندات.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى DOCX باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى DOCX

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى DOCX. لتحويل MHTML إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروف أو المخصص كذاكرة مؤقتة للبيانات. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) يقوم بتحويل MHTML إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertMHTML(sourceUrl, options, resultPath);





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

## ConvertMHTML(Stream, Configuration, DocSaveOptions, String) {#convertmhtml_17}

تحويل مصدر MHTML المقدم عبر تدفق الإدخال. النتيجة هي ملف docx تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | تدفق بيانات الإدخال لتحويل MHTML. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | مسار ملف docx الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى DOCX مطلوبًا للاستفادة من تنسيق [DOCX](https://docs.fileformat.com/word-processing/docx/) لمهام محددة. يُعد DOCX تنسيقًا معروفًا لمستندات Microsoft Word. يمكنه احتواء مجموعة واسعة من البيانات، بما في ذلك النصوص والجداول والرسومات النقطية والمتجهة والفيديو والأصوات والرسوم البيانية. يُفضَّل هذا التنسيق لأنه يدعم ميزات تنسيق معقدة ويقدم للمستخدمين مجموعة متنوعة من الخيارات لكتابة أي نوع من المستندات.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى DOCX باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى DOCX

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى DOCX. لتحويل MHTML إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروف أو المخصص كذاكرة مؤقتة للبيانات. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) يقوم بتحويل MHTML إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, DocSaveOptions, String) {#convertmhtml_33}

تحويل مصدر MHTML المقدم عبر مسار ملف كامل إلى DOCX. النتيجة هي ملف docx تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف المصدر الكامل لـ MHTML. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | مسار ملف docx الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى DOCX مطلوبًا للاستفادة من تنسيق [DOCX](https://docs.fileformat.com/word-processing/docx/) لمهام محددة. يُعد DOCX تنسيقًا معروفًا لمستندات Microsoft Word. يمكنه احتواء مجموعة واسعة من البيانات، بما في ذلك النصوص والجداول والرسومات النقطية والمتجهة والفيديو والأصوات والرسوم البيانية. يُفضَّل هذا التنسيق لأنه يدعم ميزات تنسيق معقدة ويقدم للمستخدمين مجموعة متنوعة من الخيارات لكتابة أي نوع من المستندات.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى DOCX باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى DOCX

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى DOCX. لتحويل MHTML إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروف أو المخصص كذاكرة مؤقتة للبيانات. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) يقوم بتحويل MHTML إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, DocSaveOptions, String) {#convertmhtml_1}

تحويل مصدر MHTML المقدم عبر [`URL`](../../../com.aspose.html/url/). النتيجة هي ملف docx تم تشكيله بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceUrl | Url | مستند مصدر MHTML [`URL`](../../../com.aspose.html/url/) - يوفر تمثيلًا كائنًا لمعرّف عالمي (URL). |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | مسار ملف docx الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى DOCX مطلوبًا للاستفادة من تنسيق [DOCX](https://docs.fileformat.com/word-processing/docx/) لمهام محددة. يُعد DOCX تنسيقًا معروفًا لمستندات Microsoft Word. يمكنه احتواء مجموعة واسعة من البيانات، بما في ذلك النصوص والجداول والرسومات النقطية والمتجهة والفيديو والأصوات والرسوم البيانية. يُفضَّل هذا التنسيق لأنه يدعم ميزات تنسيق معقدة ويقدم للمستخدمين مجموعة متنوعة من الخيارات لكتابة أي نوع من المستندات.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى DOCX باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى DOCX

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى DOCX. لتحويل MHTML إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروف أو المخصص كذاكرة مؤقتة للبيانات. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) يقوم بتحويل MHTML إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_24}

تحويل مصدر MHTML المقدم عبر تدفق الإدخال. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | تدفق بيانات الإدخال لتحويل MHTML. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى DOCX مطلوبًا للاستفادة من تنسيق [DOCX](https://docs.fileformat.com/word-processing/docx/) لمهام محددة. يُعد DOCX تنسيقًا معروفًا لمستندات Microsoft Word. يمكنه احتواء مجموعة واسعة من البيانات، بما في ذلك النصوص والجداول والرسومات النقطية والمتجهة والفيديو والأصوات والرسوم البيانية. يُفضَّل هذا التنسيق لأنه يدعم ميزات تنسيق معقدة ويقدم للمستخدمين مجموعة متنوعة من الخيارات لكتابة أي نوع من المستندات.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى DOCX باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى DOCX

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى DOCX. لتحويل MHTML إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروف أو المخصص كذاكرة مؤقتة للبيانات. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) يقوم بتحويل MHTML إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_40}

تحويل مصدر MHTML المقدم عبر مسار ملف كامل إلى DOCX. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف المصدر الكامل لـ MHTML. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى DOCX مطلوبًا للاستفادة من تنسيق [DOCX](https://docs.fileformat.com/word-processing/docx/) لمهام محددة. يُعد DOCX تنسيقًا معروفًا لمستندات Microsoft Word. يمكنه احتواء مجموعة واسعة من البيانات، بما في ذلك النصوص والجداول والرسومات النقطية والمتجهة والفيديو والأصوات والرسوم البيانية. يُفضَّل هذا التنسيق لأنه يدعم ميزات تنسيق معقدة ويقدم للمستخدمين مجموعة متنوعة من الخيارات لكتابة أي نوع من المستندات.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى DOCX باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى DOCX

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى DOCX. لتحويل MHTML إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروف أو المخصص كذاكرة مؤقتة للبيانات. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) يقوم بتحويل MHTML إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_8}

تحويل مصدر MHTML المقدم عبر URL. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceUrl | Url | مستند مصدر MHTML [`URL`](../../../com.aspose.html/url/) - يوفر تمثيلًا كائنًا لمعرّف عالمي (URL). |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | معروف (انظر [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) أو تنفيذ مخصص لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى DOCX مطلوبًا للاستفادة من تنسيق [DOCX](https://docs.fileformat.com/word-processing/docx/) لمهام محددة. يُعد DOCX تنسيقًا معروفًا لمستندات Microsoft Word. يمكنه احتواء مجموعة واسعة من البيانات، بما في ذلك النصوص والجداول والرسومات النقطية والمتجهة والفيديو والأصوات والرسوم البيانية. يُفضَّل هذا التنسيق لأنه يدعم ميزات تنسيق معقدة ويقدم للمستخدمين مجموعة متنوعة من الخيارات لكتابة أي نوع من المستندات.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى DOCX باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى DOCX

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى DOCX. لتحويل MHTML إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروف أو المخصص كذاكرة مؤقتة للبيانات. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) يقوم بتحويل MHTML إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_16}

تحويل مصدر MHTML المقدم عبر تدفق الإدخال. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | تدفق بيانات الإدخال لتحويل MHTML. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | معروف (انظر [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) أو تنفيذ مخصص لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى DOCX مطلوبًا للاستفادة من تنسيق [DOCX](https://docs.fileformat.com/word-processing/docx/) لمهام محددة. يُعد DOCX تنسيقًا معروفًا لمستندات Microsoft Word. يمكنه احتواء مجموعة واسعة من البيانات، بما في ذلك النصوص والجداول والرسومات النقطية والمتجهة والفيديو والأصوات والرسوم البيانية. يُفضَّل هذا التنسيق لأنه يدعم ميزات تنسيق معقدة ويقدم للمستخدمين مجموعة متنوعة من الخيارات لكتابة أي نوع من المستندات.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى DOCX باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى DOCX

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى DOCX. لتحويل MHTML إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروف أو المخصص كذاكرة مؤقتة للبيانات. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) يقوم بتحويل MHTML إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_32}

تحويل مصدر MHTML المقدم عبر مسار ملف كامل إلى DOCX. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف المصدر الكامل لـ MHTML. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى DOCX مطلوبًا للاستفادة من تنسيق [DOCX](https://docs.fileformat.com/word-processing/docx/) لمهام محددة. يُعد DOCX تنسيقًا معروفًا لمستندات Microsoft Word. يمكنه احتواء مجموعة واسعة من البيانات، بما في ذلك النصوص والجداول والرسومات النقطية والمتجهة والفيديو والأصوات والرسوم البيانية. يُفضَّل هذا التنسيق لأنه يدعم ميزات تنسيق معقدة ويقدم للمستخدمين مجموعة متنوعة من الخيارات لكتابة أي نوع من المستندات.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى DOCX باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى DOCX

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى DOCX. لتحويل MHTML إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروف أو المخصص كذاكرة مؤقتة للبيانات. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة configuration كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) يقوم بتحويل MHTML إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml}

تحويل مصدر MHTML المقدم عبر [`URL`](../../../com.aspose.html/url/). النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceUrl | Url | مستند مصدر MHTML [`URL`](../../../com.aspose.html/url/) - يوفر تمثيلًا كائنًا لمعرّف عالمي (URL). |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى DOCX مطلوبًا للاستفادة من تنسيق [DOCX](https://docs.fileformat.com/word-processing/docx/) لمهام محددة. يُعد DOCX تنسيقًا معروفًا لمستندات Microsoft Word. يمكنه احتواء مجموعة واسعة من البيانات، بما في ذلك النصوص والجداول والرسومات النقطية والمتجهة والفيديو والأصوات والرسوم البيانية. يُفضَّل هذا التنسيق لأنه يدعم ميزات تنسيق معقدة ويقدم للمستخدمين مجموعة متنوعة من الخيارات لكتابة أي نوع من المستندات.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى DOCX باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى DOCX

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى DOCX. لتحويل MHTML إلى DOCX، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر للتحويل. نتيجة التحويل. حدد مسار ملف الإخراج للنتيجة أو استخدم تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروف أو المخصص كذاكرة مؤقتة للبيانات. أنشئ كائنًا جديدًا من [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة configuration كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة DOCX مع ثلاثة معلمات أو أكثر حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

توفر Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) يقوم بتحويل MHTML إلى DOCX بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تحديد كائن DocSaveOptions الافتراضي
      var options = new DocSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source folder path.

*OutputFolder - user output folder path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, String) {#convertmhtml_29}

تحويل مصدر MHTML المقدم عبر تدفق الإدخال. النتيجة هي ملف pdf تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | تدفق بيانات الإدخال لتحويل MHTML. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | مسار ملف pdf الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى PDF مطلوبًا للاستفادة من تنسيق [PDF](https://docs.fileformat.com/pdf/) لمهام محددة. يتميز PDF بالعديد من الفوائد التي لا تتوفر في الملفات الأخرى. على سبيل المثال، تدعم العديد من البرامج والتطبيقات مستندات PDF؛ تُحَسَّن ملفات PDF للطباعة، وهي مثالية لإنشاء نسخ ورقية من مستنداتك؛ يمكنك ضبط إعدادات الأمان لملفات PDF - تعطيل الطباعة، التحرير، استخدام التوقيع الإلكتروني، إلخ.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى PDF باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى PDF

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى PDF. لتحويل MHTML إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو عنوان Url بعيد كمصدر للتحويل. يمكنك أيضًا استخدام [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة PDF مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) يقوم بتحويل MHTML إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, String) {#convertmhtml_45}

تحويل مصدر MHTML المقدم بواسطة مسار ملف كامل إلى PDF. النتيجة هي ملف PDF تم تشكيله بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف المصدر الكامل لـ MHTML. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | مسار ملف pdf الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى PDF مطلوبًا للاستفادة من تنسيق [PDF](https://docs.fileformat.com/pdf/) لمهام محددة. يتميز PDF بالعديد من الفوائد التي لا تتوفر في الملفات الأخرى. على سبيل المثال، تدعم العديد من البرامج والتطبيقات مستندات PDF؛ تُحَسَّن ملفات PDF للطباعة، وهي مثالية لإنشاء نسخ ورقية من مستنداتك؛ يمكنك ضبط إعدادات الأمان لملفات PDF - تعطيل الطباعة، التحرير، استخدام التوقيع الإلكتروني، إلخ.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى PDF باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى PDF

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى PDF. لتحويل MHTML إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو عنوان Url بعيد كمصدر للتحويل. يمكنك أيضًا استخدام [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة PDF مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) يقوم بتحويل MHTML إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, String) {#convertmhtml_13}

تحويل مصدر MHTML المقدم عبر URL. النتيجة هي ملف PDF تم تشكيله بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceUrl | Url | عنوان URL لمستند مصدر MHTML - يوفر تمثيلًا كائنًا لمعرّف عالمي (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | مسار ملف pdf الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى PDF مطلوبًا للاستفادة من تنسيق [PDF](https://docs.fileformat.com/pdf/) لمهام محددة. يتميز PDF بالعديد من الفوائد التي لا تتوفر في الملفات الأخرى. على سبيل المثال، تدعم العديد من البرامج والتطبيقات مستندات PDF؛ تُحَسَّن ملفات PDF للطباعة، وهي مثالية لإنشاء نسخ ورقية من مستنداتك؛ يمكنك ضبط إعدادات الأمان لملفات PDF - تعطيل الطباعة، التحرير، استخدام التوقيع الإلكتروني، إلخ.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى PDF باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى PDF

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى PDF. لتحويل MHTML إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو عنوان Url بعيد كمصدر للتحويل. يمكنك أيضًا استخدام [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة PDF مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) يقوم بتحويل MHTML إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, String) {#convertmhtml_21}

تحويل مصدر MHTML المقدم عبر تدفق الإدخال. النتيجة هي ملف pdf تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | تدفق بيانات الإدخال لتحويل MHTML. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | مسار ملف pdf الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى PDF مطلوبًا للاستفادة من تنسيق [PDF](https://docs.fileformat.com/pdf/) لمهام محددة. يتميز PDF بالعديد من الفوائد التي لا تتوفر في الملفات الأخرى. على سبيل المثال، تدعم العديد من البرامج والتطبيقات مستندات PDF؛ تُحَسَّن ملفات PDF للطباعة، وهي مثالية لإنشاء نسخ ورقية من مستنداتك؛ يمكنك ضبط إعدادات الأمان لملفات PDF - تعطيل الطباعة، التحرير، استخدام التوقيع الإلكتروني، إلخ.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى PDF باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى PDF

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى PDF. لتحويل MHTML إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو عنوان Url بعيد كمصدر للتحويل. يمكنك أيضًا استخدام [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة PDF مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) يقوم بتحويل MHTML إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, PdfSaveOptions, String) {#convertmhtml_37}

تحويل مصدر MHTML المقدم بواسطة مسار ملف كامل إلى PDF. النتيجة هي ملف PDF تم تشكيله بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف مصدر MHTML. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | مسار ملف pdf الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى PDF مطلوبًا للاستفادة من تنسيق [PDF](https://docs.fileformat.com/pdf/) لمهام محددة. يتميز PDF بالعديد من الفوائد التي لا تتوفر في الملفات الأخرى. على سبيل المثال، تدعم العديد من البرامج والتطبيقات مستندات PDF؛ تُحَسَّن ملفات PDF للطباعة، وهي مثالية لإنشاء نسخ ورقية من مستنداتك؛ يمكنك ضبط إعدادات الأمان لملفات PDF - تعطيل الطباعة، التحرير، استخدام التوقيع الإلكتروني، إلخ.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى PDF باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى PDF

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى PDF. لتحويل MHTML إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو عنوان Url بعيد كمصدر للتحويل. يمكنك أيضًا استخدام [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة PDF مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) يقوم بتحويل MHTML إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, PdfSaveOptions, String) {#convertmhtml_5}

تحويل مصدر MHTML المقدم عبر URL. النتيجة هي ملف PDF تم تشكيله بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceUrl | Url | عنوان URL لمستند مصدر MHTML - يوفر تمثيلًا كائنًا لمعرّف عالمي (URL). |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | مسار ملف pdf الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى PDF مطلوبًا للاستفادة من تنسيق [PDF](https://docs.fileformat.com/pdf/) لمهام محددة. يتميز PDF بالعديد من الفوائد التي لا تتوفر في الملفات الأخرى. على سبيل المثال، تدعم العديد من البرامج والتطبيقات مستندات PDF؛ تُحَسَّن ملفات PDF للطباعة، وهي مثالية لإنشاء نسخ ورقية من مستنداتك؛ يمكنك ضبط إعدادات الأمان لملفات PDF - تعطيل الطباعة، التحرير، استخدام التوقيع الإلكتروني، إلخ.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى PDF باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى PDF

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى PDF. لتحويل MHTML إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو عنوان Url بعيد كمصدر للتحويل. يمكنك أيضًا استخدام [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة PDF مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) يقوم بتحويل MHTML إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_28}

تحويل مصدر MHTML المقدم عبر تدفق الإدخال. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | تدفق بيانات الإدخال لتحويل MHTML. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | معروف (انظر [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) أو تنفيذ مخصص لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى PDF مطلوبًا للاستفادة من تنسيق [PDF](https://docs.fileformat.com/pdf/) لمهام محددة. يتميز PDF بالعديد من الفوائد التي لا تتوفر في الملفات الأخرى. على سبيل المثال، تدعم العديد من البرامج والتطبيقات مستندات PDF؛ تُحَسَّن ملفات PDF للطباعة، وهي مثالية لإنشاء نسخ ورقية من مستنداتك؛ يمكنك ضبط إعدادات الأمان لملفات PDF - تعطيل الطباعة، التحرير، استخدام التوقيع الإلكتروني، إلخ.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى PDF باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى PDF

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى PDF. لتحويل MHTML إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو عنوان Url بعيد كمصدر للتحويل. يمكنك أيضًا استخدام [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة PDF مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) يقوم بتحويل MHTML إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_44}

تحويل مصدر MHTML المقدم بمسار ملف كامل إلى PDF. النتيجة هي بيانات الإخراج التي تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف مصدر MHTML. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى PDF مطلوبًا للاستفادة من تنسيق [PDF](https://docs.fileformat.com/pdf/) لمهام محددة. يتميز PDF بالعديد من الفوائد التي لا تتوفر في الملفات الأخرى. على سبيل المثال، تدعم العديد من البرامج والتطبيقات مستندات PDF؛ تُحَسَّن ملفات PDF للطباعة، وهي مثالية لإنشاء نسخ ورقية من مستنداتك؛ يمكنك ضبط إعدادات الأمان لملفات PDF - تعطيل الطباعة، التحرير، استخدام التوقيع الإلكتروني، إلخ.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى PDF باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى PDF

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى PDF. لتحويل MHTML إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو عنوان Url بعيد كمصدر للتحويل. يمكنك أيضًا استخدام [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة PDF مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) يقوم بتحويل MHTML إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_12}

تحويل مصدر MHTML المقدم عبر URL. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceUrl | Url | عنوان URL لمستند مصدر MHTML - يوفر تمثيلًا كائنًا لمعرّف عالمي (URL). |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى PDF مطلوبًا للاستفادة من تنسيق [PDF](https://docs.fileformat.com/pdf/) لمهام محددة. يتميز PDF بالعديد من الفوائد التي لا تتوفر في الملفات الأخرى. على سبيل المثال، تدعم العديد من البرامج والتطبيقات مستندات PDF؛ تُحَسَّن ملفات PDF للطباعة، وهي مثالية لإنشاء نسخ ورقية من مستنداتك؛ يمكنك ضبط إعدادات الأمان لملفات PDF - تعطيل الطباعة، التحرير، استخدام التوقيع الإلكتروني، إلخ.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى PDF باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى PDF

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى PDF. لتحويل MHTML إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو عنوان Url بعيد كمصدر للتحويل. يمكنك أيضًا استخدام [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة PDF مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) يقوم بتحويل MHTML إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل
      Converter.ConvertMHTML(sourceUrl, options, sp);
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

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_20}

تحويل مصدر MHTML المقدم عبر تدفق الإدخال. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | تدفق بيانات الإدخال لتحويل MHTML. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى PDF مطلوبًا للاستفادة من تنسيق [PDF](https://docs.fileformat.com/pdf/) لمهام محددة. يتميز PDF بالعديد من الفوائد التي لا تتوفر في الملفات الأخرى. على سبيل المثال، تدعم العديد من البرامج والتطبيقات مستندات PDF؛ تُحَسَّن ملفات PDF للطباعة، وهي مثالية لإنشاء نسخ ورقية من مستنداتك؛ يمكنك ضبط إعدادات الأمان لملفات PDF - تعطيل الطباعة، التحرير، استخدام التوقيع الإلكتروني، إلخ.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى PDF باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى PDF

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى PDF. لتحويل MHTML إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو عنوان Url بعيد كمصدر للتحويل. يمكنك أيضًا استخدام [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة PDF مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) يقوم بتحويل MHTML إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_36}

تحويل مصدر MHTML المقدم بمسار ملف كامل إلى PDF. النتيجة هي بيانات الإخراج التي تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف المصدر الكامل لـ MHTML. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى PDF مطلوبًا للاستفادة من تنسيق [PDF](https://docs.fileformat.com/pdf/) لمهام محددة. يتميز PDF بالعديد من الفوائد التي لا تتوفر في الملفات الأخرى. على سبيل المثال، تدعم العديد من البرامج والتطبيقات مستندات PDF؛ تُحَسَّن ملفات PDF للطباعة، وهي مثالية لإنشاء نسخ ورقية من مستنداتك؛ يمكنك ضبط إعدادات الأمان لملفات PDF - تعطيل الطباعة، التحرير، استخدام التوقيع الإلكتروني، إلخ.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى PDF باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى PDF

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى PDF. لتحويل MHTML إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو عنوان Url بعيد كمصدر للتحويل. يمكنك أيضًا استخدام [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة PDF مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) يقوم بتحويل MHTML إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_4}

تحويل مصدر MHTML المقدم عبر [`URL`](../../../com.aspose.html/url/). النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceUrl | Url | عنوان URL لمستند مصدر MHTML - يوفر تمثيلًا كائنًا لمعرّف عالمي (URL). |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول MHTML

غالبًا ما يكون تحويل MHTML إلى PDF مطلوبًا للاستفادة من تنسيق [PDF](https://docs.fileformat.com/pdf/) لمهام محددة. يتميز PDF بالعديد من الفوائد التي لا تتوفر في الملفات الأخرى. على سبيل المثال، تدعم العديد من البرامج والتطبيقات مستندات PDF؛ تُحَسَّن ملفات PDF للطباعة، وهي مثالية لإنشاء نسخ ورقية من مستنداتك؛ يمكنك ضبط إعدادات الأمان لملفات PDF - تعطيل الطباعة، التحرير، استخدام التوقيع الإلكتروني، إلخ.

ارجع إلى [مقال](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) حيث ستجد معلومات حول كيفية تحويل MHTML إلى PDF باستخدام طرق ConvertMHTML() في فئة [`Converter`](../) وكيفية تطبيق معلمات [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى PDF

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى PDF. لتحويل MHTML إلى PDF، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو عنوان Url بعيد كمصدر للتحويل. يمكنك أيضًا استخدام [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) بإعدادات محددة أو افتراضية. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة PDF مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) يقوم بتحويل MHTML إلى PDF بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تحديد كائن PdfSaveOptions الافتراضي
      var options = new PdfSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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

## ConvertMHTML(Stream, ImageSaveOptions, String) {#convertmhtml_27}

تحويل مصدر MHTML المقدم عبر تدفق الإدخال إلى صورة. النتيجة هي ملف صورة تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | تدفق بيانات الإدخال لتحويل MHTML. |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| outputPath | String | مسار ملف الصورة الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول MHTML

الملفات ذات الامتداد [MHTML](https://docs.fileformat.com/web/mhtml/) تمثل تنسيق أرشيف صفحة ويب يمكن للعديد من التطبيقات المختلفة إنشاؤه. يُعرف هذا التنسيق بتنسيق الأرشيف لأنه يحفظ كود HTML للويب والموارد المرتبطة به في ملف واحد. تشمل هذه الموارد أي شيء مرتبط بصفحة الويب مثل الصور، التطبيقات الصغيرة، الرسوم المتحركة، ملفات الصوت وما إلى ذلك. يمكن فتح ملفات MHTML في مجموعة متنوعة من التطبيقات مثل Internet Explorer وMicrosoft Word. المواصفات الفعلية للتنسيق موضحة بالتفصيل في [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

ارجع إلى المقالة حيث ستجد معلومات حول كيفية تحويل MHTML إلى صور بصيغ مختلفة باستخدام طرق ConvertMHTML() في فئة Converter وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى صورة

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى صور. الصيغ المدعومة هي [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) و[TIFF](https://docs.fileformat.com/image/tiff/). لتحويل MHTML إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. الصيغة الافتراضية للصورة هي PNG. يمكنك أيضًا إضافة configuration كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة صورة مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) يقوم بتحويل MHTML إلى ملف jpeg بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // بدء عملية التحويل
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, String) {#convertmhtml_43}

تحويل مصدر MHTML المقدم عبر مسار ملف كامل. النتيجة هي ملف صورة تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف المصدر الكامل لـ MHTML. |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| outputPath | String | مسار ملف الصورة الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول MHTML

الملفات ذات الامتداد [MHTML](https://docs.fileformat.com/web/mhtml/) تمثل تنسيق أرشيف صفحة ويب يمكن للعديد من التطبيقات المختلفة إنشاؤه. يُعرف هذا التنسيق بتنسيق الأرشيف لأنه يحفظ كود HTML للويب والموارد المرتبطة به في ملف واحد. تشمل هذه الموارد أي شيء مرتبط بصفحة الويب مثل الصور، التطبيقات الصغيرة، الرسوم المتحركة، ملفات الصوت وما إلى ذلك. يمكن فتح ملفات MHTML في مجموعة متنوعة من التطبيقات مثل Internet Explorer وMicrosoft Word. المواصفات الفعلية للتنسيق موضحة بالتفصيل في [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

ارجع إلى المقالة حيث ستجد معلومات حول كيفية تحويل MHTML إلى صور بصيغ مختلفة باستخدام طرق ConvertMHTML() في فئة Converter وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى صورة

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى صور. الصيغ المدعومة هي [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) و[TIFF](https://docs.fileformat.com/image/tiff/). لتحويل MHTML إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. الصيغة الافتراضية للصورة هي PNG. يمكنك أيضًا إضافة configuration كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة صورة مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) يقوم بتحويل MHTML إلى ملف jpeg بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // بدء عملية التحويل
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, String) {#convertmhtml_11}

تحويل مصدر MHTML المقدم عبر URL. النتيجة هي ملف صورة تم تشكيله بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceUrl | Url | عنوان URL لمستند مصدر MHTML - يوفر تمثيلًا كائنًا لمعرّف عالمي (URL). |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| outputPath | String | مسار ملف الصورة الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول MHTML

الملفات ذات الامتداد [MHTML](https://docs.fileformat.com/web/mhtml/) تمثل تنسيق أرشيف صفحة ويب يمكن للعديد من التطبيقات المختلفة إنشاؤه. يُعرف هذا التنسيق بتنسيق الأرشيف لأنه يحفظ كود HTML للويب والموارد المرتبطة به في ملف واحد. تشمل هذه الموارد أي شيء مرتبط بصفحة الويب مثل الصور، التطبيقات الصغيرة، الرسوم المتحركة، ملفات الصوت وما إلى ذلك. يمكن فتح ملفات MHTML في مجموعة متنوعة من التطبيقات مثل Internet Explorer وMicrosoft Word. المواصفات الفعلية للتنسيق موضحة بالتفصيل في [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

ارجع إلى المقالة حيث ستجد معلومات حول كيفية تحويل MHTML إلى صور بصيغ مختلفة باستخدام طرق ConvertMHTML() في فئة Converter وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى صورة

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى صور. الصيغ المدعومة هي [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) و[TIFF](https://docs.fileformat.com/image/tiff/). لتحويل MHTML إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. الصيغة الافتراضية للصورة هي PNG. يمكنك أيضًا إضافة configuration كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة صورة مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) يقوم بتحويل MHTML إلى ملف jpeg بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // بدء عملية التحويل
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
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

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, String) {#convertmhtml_19}

تحويل مصدر MHTML المقدم عبر تدفق الإدخال إلى صورة. النتيجة هي ملف صورة تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | تدفق بيانات الإدخال لتحويل MHTML. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| outputPath | String | مسار ملف الصورة الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول MHTML

الملفات ذات الامتداد [MHTML](https://docs.fileformat.com/web/mhtml/) تمثل تنسيق أرشيف صفحة ويب يمكن للعديد من التطبيقات المختلفة إنشاؤه. يُعرف هذا التنسيق بتنسيق الأرشيف لأنه يحفظ كود HTML للويب والموارد المرتبطة به في ملف واحد. تشمل هذه الموارد أي شيء مرتبط بصفحة الويب مثل الصور، التطبيقات الصغيرة، الرسوم المتحركة، ملفات الصوت وما إلى ذلك. يمكن فتح ملفات MHTML في مجموعة متنوعة من التطبيقات مثل Internet Explorer وMicrosoft Word. المواصفات الفعلية للتنسيق موضحة بالتفصيل في [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

ارجع إلى المقالة حيث ستجد معلومات حول كيفية تحويل MHTML إلى صور بصيغ مختلفة باستخدام طرق ConvertMHTML() في فئة Converter وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى صورة

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى صور. الصيغ المدعومة هي [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) و[TIFF](https://docs.fileformat.com/image/tiff/). لتحويل MHTML إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. الصيغة الافتراضية للصورة هي PNG. يمكنك أيضًا إضافة configuration كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة صورة مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) يقوم بتحويل MHTML إلى ملف jpeg بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
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

## ConvertMHTML(String, Configuration, ImageSaveOptions, String) {#convertmhtml_35}

تحويل مصدر MHTML المقدم عبر مسار ملف كامل. النتيجة هي ملف صورة تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف المصدر الكامل لـ MHTML. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| outputPath | String | مسار ملف الصورة الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول MHTML

الملفات ذات الامتداد [MHTML](https://docs.fileformat.com/web/mhtml/) تمثل تنسيق أرشيف صفحة ويب يمكن للعديد من التطبيقات المختلفة إنشاؤه. يُعرف هذا التنسيق بتنسيق الأرشيف لأنه يحفظ كود HTML للويب والموارد المرتبطة به في ملف واحد. تشمل هذه الموارد أي شيء مرتبط بصفحة الويب مثل الصور، التطبيقات الصغيرة، الرسوم المتحركة، ملفات الصوت وما إلى ذلك. يمكن فتح ملفات MHTML في مجموعة متنوعة من التطبيقات مثل Internet Explorer وMicrosoft Word. المواصفات الفعلية للتنسيق موضحة بالتفصيل في [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

ارجع إلى المقالة حيث ستجد معلومات حول كيفية تحويل MHTML إلى صور بصيغ مختلفة باستخدام طرق ConvertMHTML() في فئة Converter وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى صورة

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى صور. الصيغ المدعومة هي [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) و[TIFF](https://docs.fileformat.com/image/tiff/). لتحويل MHTML إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. الصيغة الافتراضية للصورة هي PNG. يمكنك أيضًا إضافة configuration كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة صورة مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) يقوم بتحويل MHTML إلى ملف jpeg بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertMHTML(Url, Configuration, ImageSaveOptions, String) {#convertmhtml_3}

تحويل مصدر MHTML المقدم عبر URL. النتيجة هي ملف صورة تم تشكيله بواسطة مسار ملف الإخراج.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceUrl | Url | عنوان URL لمستند مصدر MHTML - يوفر تمثيلًا كائنًا لمعرّف عالمي (URL). |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| outputPath | String | مسار ملف الصورة الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول MHTML

الملفات ذات الامتداد [MHTML](https://docs.fileformat.com/web/mhtml/) تمثل تنسيق أرشيف صفحة ويب يمكن للعديد من التطبيقات المختلفة إنشاؤه. يُعرف هذا التنسيق بتنسيق الأرشيف لأنه يحفظ كود HTML للويب والموارد المرتبطة به في ملف واحد. تشمل هذه الموارد أي شيء مرتبط بصفحة الويب مثل الصور، التطبيقات الصغيرة، الرسوم المتحركة، ملفات الصوت وما إلى ذلك. يمكن فتح ملفات MHTML في مجموعة متنوعة من التطبيقات مثل Internet Explorer وMicrosoft Word. المواصفات الفعلية للتنسيق موضحة بالتفصيل في [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

ارجع إلى المقالة حيث ستجد معلومات حول كيفية تحويل MHTML إلى صور بصيغ مختلفة باستخدام طرق ConvertMHTML() في فئة Converter وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى صورة

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى صور. الصيغ المدعومة هي [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) و[TIFF](https://docs.fileformat.com/image/tiff/). لتحويل MHTML إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. الصيغة الافتراضية للصورة هي PNG. يمكنك أيضًا إضافة configuration كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة صورة مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) يقوم بتحويل MHTML إلى ملف jpeg بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions();

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertMHTML(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_26}

تحويل مصدر MHTML المقدم عبر تدفق الإدخال. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | تدفق بيانات الإدخال لتحويل MHTML. |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول MHTML

الملفات ذات الامتداد [MHTML](https://docs.fileformat.com/web/mhtml/) تمثل تنسيق أرشيف صفحة ويب يمكن للعديد من التطبيقات المختلفة إنشاؤه. يُعرف هذا التنسيق بتنسيق الأرشيف لأنه يحفظ كود HTML للويب والموارد المرتبطة به في ملف واحد. تشمل هذه الموارد أي شيء مرتبط بصفحة الويب مثل الصور، التطبيقات الصغيرة، الرسوم المتحركة، ملفات الصوت وما إلى ذلك. يمكن فتح ملفات MHTML في مجموعة متنوعة من التطبيقات مثل Internet Explorer وMicrosoft Word. المواصفات الفعلية للتنسيق موضحة بالتفصيل في [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

ارجع إلى المقالة حيث ستجد معلومات حول كيفية تحويل MHTML إلى صور بصيغ مختلفة باستخدام طرق ConvertMHTML() في فئة Converter وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى صورة

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى صور. الصيغ المدعومة هي [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) و[TIFF](https://docs.fileformat.com/image/tiff/). لتحويل MHTML إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. الصيغة الافتراضية للصورة هي PNG. يمكنك أيضًا إضافة configuration كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة صورة مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) يقوم بتحويل MHTML إلى ملف jpeg بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
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

## ConvertMHTML(String, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_42}

تحويل مصدر MHTML المقدم بمسار ملف كامل إلى صورة. النتيجة هي بيانات الإخراج التي تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف المصدر الكامل لـ MHTML. |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| provider | ICreateStreamProvider | معروف (انظر [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) أو تنفيذ مخصص لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## ملاحظات

محول MHTML

الملفات ذات الامتداد [MHTML](https://docs.fileformat.com/web/mhtml/) تمثل تنسيق أرشيف صفحة ويب يمكن للعديد من التطبيقات المختلفة إنشاؤه. يُعرف هذا التنسيق بتنسيق الأرشيف لأنه يحفظ كود HTML للويب والموارد المرتبطة به في ملف واحد. تشمل هذه الموارد أي شيء مرتبط بصفحة الويب مثل الصور، التطبيقات الصغيرة، الرسوم المتحركة، ملفات الصوت وما إلى ذلك. يمكن فتح ملفات MHTML في مجموعة متنوعة من التطبيقات مثل Internet Explorer وMicrosoft Word. المواصفات الفعلية للتنسيق موضحة بالتفصيل في [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

ارجع إلى المقالة حيث ستجد معلومات حول كيفية تحويل MHTML إلى صور بصيغ مختلفة باستخدام طرق ConvertMHTML() في فئة Converter وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى صورة

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى صور. الصيغ المدعومة هي [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) و[TIFF](https://docs.fileformat.com/image/tiff/). لتحويل MHTML إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. الصيغة الافتراضية للصورة هي PNG. يمكنك أيضًا إضافة configuration كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة صورة مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) يقوم بتحويل MHTML إلى ملف jpeg بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل
      Converter.ConvertMHTML(sourcePath, options, sp);
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

## ConvertMHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_10}

تحويل مصدر MHTML المقدم عبر URL. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceUrl | Url | عنوان URL لمستند مصدر MHTML - يوفر تمثيلًا كائنًا لمعرّف عالمي (URL). |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| provider | ICreateStreamProvider | معروف (انظر [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) أو تنفيذ مخصص لواجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). |

## ملاحظات

محول MHTML

الملفات ذات الامتداد [MHTML](https://docs.fileformat.com/web/mhtml/) تمثل تنسيق أرشيف صفحة ويب يمكن للعديد من التطبيقات المختلفة إنشاؤه. يُعرف هذا التنسيق بتنسيق الأرشيف لأنه يحفظ كود HTML للويب والموارد المرتبطة به في ملف واحد. تشمل هذه الموارد أي شيء مرتبط بصفحة الويب مثل الصور، التطبيقات الصغيرة، الرسوم المتحركة، ملفات الصوت وما إلى ذلك. يمكن فتح ملفات MHTML في مجموعة متنوعة من التطبيقات مثل Internet Explorer وMicrosoft Word. المواصفات الفعلية للتنسيق موضحة بالتفصيل في [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

ارجع إلى المقالة حيث ستجد معلومات حول كيفية تحويل MHTML إلى صور بصيغ مختلفة باستخدام طرق ConvertMHTML() في فئة Converter وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى صورة

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى صور. الصيغ المدعومة هي [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) و[TIFF](https://docs.fileformat.com/image/tiff/). لتحويل MHTML إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. الصيغة الافتراضية للصورة هي PNG. يمكنك أيضًا إضافة configuration كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة صورة مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) يقوم بتحويل MHTML إلى ملف jpeg بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل
      Converter.ConvertMHTML(sourceUrl, options, sp);
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

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_18}

تحويل مصدر MHTML المقدم عبر تدفق الإدخال. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | تدفق بيانات الإدخال لتحويل MHTML. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول MHTML

الملفات ذات الامتداد [MHTML](https://docs.fileformat.com/web/mhtml/) تمثل تنسيق أرشيف صفحة ويب يمكن للعديد من التطبيقات المختلفة إنشاؤه. يُعرف هذا التنسيق بتنسيق الأرشيف لأنه يحفظ كود HTML للويب والموارد المرتبطة به في ملف واحد. تشمل هذه الموارد أي شيء مرتبط بصفحة الويب مثل الصور، التطبيقات الصغيرة، الرسوم المتحركة، ملفات الصوت وما إلى ذلك. يمكن فتح ملفات MHTML في مجموعة متنوعة من التطبيقات مثل Internet Explorer وMicrosoft Word. المواصفات الفعلية للتنسيق موضحة بالتفصيل في [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

ارجع إلى المقالة حيث ستجد معلومات حول كيفية تحويل MHTML إلى صور بصيغ مختلفة باستخدام طرق ConvertMHTML() في فئة Converter وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى صورة

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى صور. الصيغ المدعومة هي [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) و[TIFF](https://docs.fileformat.com/image/tiff/). لتحويل MHTML إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. الصيغة الافتراضية للصورة هي PNG. يمكنك أيضًا إضافة configuration كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة صورة مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) يقوم بتحويل MHTML إلى ملف jpeg بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions();

      // بدء عملية التحويل
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
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

## ConvertMHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_34}

تحويل مصدر MHTML المقدم بمسار ملف كامل إلى صورة. النتيجة هي بيانات الإخراج التي تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف المصدر الكامل لـ MHTML. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| provider | ICreateStreamProvider | تنفيذ الـ [` interface`](../../../com.aspose.html.io/icreatestreamprovider/) الذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول MHTML

الملفات ذات الامتداد [MHTML](https://docs.fileformat.com/web/mhtml/) تمثل تنسيق أرشيف صفحة ويب يمكن للعديد من التطبيقات المختلفة إنشاؤه. يُعرف هذا التنسيق بتنسيق الأرشيف لأنه يحفظ كود HTML للويب والموارد المرتبطة به في ملف واحد. تشمل هذه الموارد أي شيء مرتبط بصفحة الويب مثل الصور، التطبيقات الصغيرة، الرسوم المتحركة، ملفات الصوت وما إلى ذلك. يمكن فتح ملفات MHTML في مجموعة متنوعة من التطبيقات مثل Internet Explorer وMicrosoft Word. المواصفات الفعلية للتنسيق موضحة بالتفصيل في [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

ارجع إلى المقالة حيث ستجد معلومات حول كيفية تحويل MHTML إلى صور بصيغ مختلفة باستخدام طرق ConvertMHTML() في فئة Converter وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى صورة

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى صور. الصيغ المدعومة هي [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) و[TIFF](https://docs.fileformat.com/image/tiff/). لتحويل MHTML إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. الصيغة الافتراضية للصورة هي PNG. يمكنك أيضًا إضافة configuration كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة صورة مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) يقوم بتحويل MHTML إلى ملف jpeg بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions();

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
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

## ConvertMHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_2}

تحويل مصدر MHTML المقدم عبر URL. النتيجة هي بيانات إخراج تم تشكيلها بواسطة تنفيذ واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) .

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceUrl | Url | عنوان URL لمستند مصدر MHTML - يوفر تمثيلًا كائنًا لمعرّف عالمي (URL). |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| options | ImageSaveOptions | استخدام كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) يتيح لك ضبط عملية التصيير. يمكنك تحديد [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)، [`margins`](../../../com.aspose.html.drawing/page/margin/)، [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)، إلخ. |
| provider | ICreateStreamProvider | تنفيذ الـ[`interface`](../../../com.aspose.html.io/icreatestreamprovider/)، والذي سيُستخدم للحصول على تدفق إخراج. |

## ملاحظات

محول MHTML

الملفات ذات الامتداد [MHTML](https://docs.fileformat.com/web/mhtml/) تمثل تنسيق أرشيف صفحة ويب يمكن للعديد من التطبيقات المختلفة إنشاؤه. يُعرف هذا التنسيق بتنسيق الأرشيف لأنه يحفظ كود HTML للويب والموارد المرتبطة به في ملف واحد. تشمل هذه الموارد أي شيء مرتبط بصفحة الويب مثل الصور، التطبيقات الصغيرة، الرسوم المتحركة، ملفات الصوت وما إلى ذلك. يمكن فتح ملفات MHTML في مجموعة متنوعة من التطبيقات مثل Internet Explorer وMicrosoft Word. المواصفات الفعلية للتنسيق موضحة بالتفصيل في [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

ارجع إلى المقالة حيث ستجد معلومات حول كيفية تحويل MHTML إلى صور بصيغ مختلفة باستخدام طرق ConvertMHTML() في فئة Converter وكيفية تطبيق معلمات [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) و[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

تحويل MHTML إلى صورة

تقدم فئة Converter بعض التحويلات الخاصة بـ MHTML إلى صور. الصيغ المدعومة هي [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) و[TIFF](https://docs.fileformat.com/image/tiff/). لتحويل MHTML إلى صورة، يجب عليك اتباع أحد السيناريوهات البسيطة التي تتكون من بضع خطوات:

مصدر التحويل. اكتشف ملف MHTML (.mht) محلي موجود أو [`Url`](../../../com.aspose.html/url/) بعيد كمصدر للتحويل. يمكنك أيضًا استخدام تدفق قياسي أو مخصص كمصدر. نتيجة التحويل. حدد مسار ملف الإخراج أو استخدم واجهة [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) المعروفة أو المخصصة كمنطقة تخزين بيانات الإخراج. أنشئ كائن [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) بإعدادات محددة أو افتراضية. الصيغة الافتراضية للصورة هي PNG. يمكنك أيضًا إضافة configuration كمعامل خيار. استخدم طريقة ConvertMHTML() في فئة Converter لحفظ MHTML كنتيجة صورة مع ثلاثة أو أكثر من المعاملات حسب سيناريو المستخدم. محول MHTML عبر الإنترنت

تقدم Aspose.HTML محولًا مجانيًا عبر الإنترنت لـ [MHTML إلى JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) يقوم بتحويل MHTML إلى ملف jpeg بجودة عالية، بسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ!

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result");

      // تعريف كائن ImageSaveOptions الافتراضي
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // استخدام أحد تنفيذات ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
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
