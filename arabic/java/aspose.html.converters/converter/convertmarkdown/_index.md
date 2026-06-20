---
title: "Converter.ConvertMarkdown"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة Converter. تحويل مصدر MD markdown المقدم عبر تدفق الإدخال إلى html. النتيجة هي HTMLDocument التي يمكن حفظها عبر مسار ملف الإخراج."
type: docs

url: /ar/java/com.aspose.html.converters/converter/convertmarkdown/
---
## ConvertMarkdown(Stream, String) {#convertmarkdown}

تحويل مصدر MD (markdown) المقدم عبر تدفق الإدخال إلى html. النتيجة هي [`HTMLDocument`](../../../com.aspose.html/htmldocument/) التي يمكن حفظها عبر مسار ملف الإخراج.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | تدفق بيانات الإدخال لتحويل MD (Markdown). |
| baseUri | String | عنوان URI الأساسي للمستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |

### قيمة الإرجاع

تم إنشاء [`HTMLDocument`](../../../com.aspose.html/htmldocument/) جديد كنتيجة للتحويل يمكن حفظه عبر مسار ملف الإخراج.

## ملاحظات

محول Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

خطوات التحويل

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

مصدر التحويل. اكتشاف ملف MD محلي موجود أو إنشاء تدفق بيانات الإدخال كمصدر للتحويل. نتيجة التحويل. يمكنك الحصول مباشرة على [`HTMLDocument`](../../../com.aspose.html/htmldocument/) أو تحديد مسار ملف الإخراج للنتيجة اعتمادًا على توقيع الطريقة. استخدم طريقة ConvertMarkdown() من فئة Converter لحفظ MD كنتيجة html. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. محول MD عبر الإنترنت

قد تكون مهتمًا أيضًا بأداة مجانية عبر الإنترنت [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) التي تحول MD إلى HTML بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ! يمكنك أيضًا الاطلاع على أدوات تحويل MD الأخرى عبر الإنترنت: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)، [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)، [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) والعثور على [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) المناسبة.

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.html");
       
      // فتح ملف المصدر كتيار
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // بدء عملية التحويل
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty);
         
        // حفظ نتيجة التحويل
        document.Save(resultPath);
      }





*InputFolder - user source folder path.



```

*OutputFolder - user output file path.

### انظر أيضًا

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration) {#convertmarkdown_1}

تحويل مصدر MD (markdown) المقدم عبر تدفق الإدخال إلى html. النتيجة هي [`HTMLDocument`](../../../com.aspose.html/htmldocument/) التي يمكن حفظها عبر مسار ملف الإخراج.

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri, 
    Configuration configuration)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | تدفق بيانات الإدخال لتحويل MD (Markdown). |
| baseUri | String | عنوان URI الأساسي للمستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |

### قيمة الإرجاع

تم إنشاء [`HTMLDocument`](../../../com.aspose.html/htmldocument/) جديد كنتيجة للتحويل يمكن حفظه عبر مسار ملف الإخراج.

## ملاحظات

محول Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

خطوات التحويل

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

مصدر التحويل. اكتشاف ملف MD محلي موجود أو إنشاء تدفق بيانات الإدخال كمصدر للتحويل. نتيجة التحويل. يمكنك الحصول مباشرة على [`HTMLDocument`](../../../com.aspose.html/htmldocument/) أو تحديد مسار ملف الإخراج للنتيجة اعتمادًا على توقيع الطريقة. استخدم طريقة ConvertMarkdown() من فئة Converter لحفظ MD كنتيجة html. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. محول MD عبر الإنترنت

قد تكون مهتمًا أيضًا بأداة مجانية عبر الإنترنت [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) التي تحول MD إلى HTML بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ! يمكنك أيضًا الاطلاع على أدوات تحويل MD الأخرى عبر الإنترنت: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)، [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)، [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) والعثور على [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) المناسبة.

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // فتح ملف المصدر كتيار
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // بدء عملية التحويل باستخدام التكوين الافتراضي
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration());

        // حفظ نتيجة التحويل
        document.Save(resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### انظر أيضًا

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, String) {#convertmarkdown_5}

تحويل مصدر MD (markdown) المقدم عبر تدفق الإدخال إلى html. النتيجة هي ملف html تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | تدفق بيانات الإدخال لتحويل MD (Markdown). |
| baseUri | String | عنوان URI الأساسي للمستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| outputPath | String | مسار ملف html الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

خطوات التحويل

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

مصدر التحويل. اكتشاف ملف MD محلي موجود أو إنشاء تدفق بيانات الإدخال كمصدر للتحويل. نتيجة التحويل. يمكنك الحصول مباشرة على [`HTMLDocument`](../../../com.aspose.html/htmldocument/) أو تحديد مسار ملف الإخراج للنتيجة اعتمادًا على توقيع الطريقة. استخدم طريقة ConvertMarkdown() من فئة Converter لحفظ MD كنتيجة html. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. محول MD عبر الإنترنت

قد تكون مهتمًا أيضًا بأداة مجانية عبر الإنترنت [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) التي تحول MD إلى HTML بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ! يمكنك أيضًا الاطلاع على أدوات تحويل MD الأخرى عبر الإنترنت: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)، [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)، [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) والعثور على [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) المناسبة.

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // فتح ملف المصدر كتيار
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // بدء عملية التحويل
        Converter.ConvertMarkdown(sourceStream, String.Empty, resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### انظر أيضًا

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration, String) {#convertmarkdown_4}

تحويل مصدر MD (markdown) المقدم عبر تدفق الإدخال إلى html. النتيجة هي ملف html تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertMarkdown(Stream stream, String baseUri, Configuration configuration, 
    String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| دفق | دفق | تدفق بيانات الإدخال لتحويل MD (Markdown). |
| baseUri | String | عنوان URI الأساسي للمستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| outputPath | String | مسار ملف html الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

خطوات التحويل

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

مصدر التحويل. اكتشاف ملف MD محلي موجود أو إنشاء تدفق بيانات الإدخال كمصدر للتحويل. نتيجة التحويل. يمكنك الحصول مباشرة على [`HTMLDocument`](../../../com.aspose.html/htmldocument/) أو تحديد مسار ملف الإخراج للنتيجة اعتمادًا على توقيع الطريقة. استخدم طريقة ConvertMarkdown() من فئة Converter لحفظ MD كنتيجة html. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. محول MD عبر الإنترنت

قد تكون مهتمًا أيضًا بأداة مجانية عبر الإنترنت [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) التي تحول MD إلى HTML بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ! يمكنك أيضًا الاطلاع على أدوات تحويل MD الأخرى عبر الإنترنت: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)، [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)، [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) والعثور على [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) المناسبة.

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // فتح ملف المصدر كتيار
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // بدء عملية التحويل باستخدام التكوين الافتراضي
        Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration(), resultPath);
      }
```

*InputFolder - user source folder path.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String) {#convertmarkdown_2}

تحويل مصدر MD (markdown) المقدم عبر مسار ملف كامل إلى html. النتيجة هي [`HTMLDocument`](../../../com.aspose.html/htmldocument/) التي يمكن حفظها عبر مسار ملف الإخراج.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف مصدر MD (Markdown) الكامل. |

### قيمة الإرجاع

تم إنشاء [`HTMLDocument`](../../../com.aspose.html/htmldocument/) جديد كنتيجة للتحويل يمكن حفظه عبر مسار ملف الإخراج.

## ملاحظات

محول Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

خطوات التحويل

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

مصدر التحويل. اكتشاف ملف MD محلي موجود أو إنشاء تدفق بيانات الإدخال كمصدر للتحويل. نتيجة التحويل. يمكنك الحصول مباشرة على [`HTMLDocument`](../../../com.aspose.html/htmldocument/) أو تحديد مسار ملف الإخراج للنتيجة اعتمادًا على توقيع الطريقة. استخدم طريقة ConvertMarkdown() من فئة Converter لحفظ MD كنتيجة html. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. محول MD عبر الإنترنت

قد تكون مهتمًا أيضًا بأداة مجانية عبر الإنترنت [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) التي تحول MD إلى HTML بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ! يمكنك أيضًا الاطلاع على أدوات تحويل MD الأخرى عبر الإنترنت: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)، [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)، [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) والعثور على [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) المناسبة.

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // بدء عملية التحويل
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath))
      {
        // حفظ نتيجة التحويل كملف محلي
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### انظر أيضًا

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration) {#convertmarkdown_3}

تحويل مصدر MD (markdown) المقدم عبر مسار ملف كامل إلى html. النتيجة هي [`HTMLDocument`](../../../com.aspose.html/htmldocument/) التي يمكن حفظها عبر مسار ملف الإخراج.

```java
public static HTMLDocument ConvertMarkdown(String sourcePath, Configuration configuration)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف مصدر MD (Markdown) الكامل. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |

### قيمة الإرجاع

تم إنشاء [`HTMLDocument`](../../../com.aspose.html/htmldocument/) جديد كنتيجة للتحويل يمكن حفظه عبر مسار ملف الإخراج.

## ملاحظات

محول Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

خطوات التحويل

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

مصدر التحويل. اكتشاف ملف MD محلي موجود أو إنشاء تدفق بيانات الإدخال كمصدر للتحويل. نتيجة التحويل. يمكنك الحصول مباشرة على [`HTMLDocument`](../../../com.aspose.html/htmldocument/) أو تحديد مسار ملف الإخراج للنتيجة اعتمادًا على توقيع الطريقة. استخدم طريقة ConvertMarkdown() من فئة Converter لحفظ MD كنتيجة html. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. محول MD عبر الإنترنت

قد تكون مهتمًا أيضًا بأداة مجانية عبر الإنترنت [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) التي تحول MD إلى HTML بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ! يمكنك أيضًا الاطلاع على أدوات تحويل MD الأخرى عبر الإنترنت: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)، [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)، [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) والعثور على [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) المناسبة.

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath, new Configuration()))
      {
        // حفظ نتيجة التحويل كملف محلي
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### انظر أيضًا

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, String) {#convertmarkdown_7}

تحويل مصدر MD (markdown) المقدم عبر مسار ملف كامل إلى html. النتيجة هي ملف html تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertMarkdown(String sourcePath, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف Markdown المصدر. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| outputPath | String | مسار ملف html الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

خطوات التحويل

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

مصدر التحويل. اكتشاف ملف MD محلي موجود أو إنشاء تدفق بيانات الإدخال كمصدر للتحويل. نتيجة التحويل. يمكنك الحصول مباشرة على [`HTMLDocument`](../../../com.aspose.html/htmldocument/) أو تحديد مسار ملف الإخراج للنتيجة اعتمادًا على توقيع الطريقة. استخدم طريقة ConvertMarkdown() من فئة Converter لحفظ MD كنتيجة html. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. محول MD عبر الإنترنت

قد تكون مهتمًا أيضًا بأداة مجانية عبر الإنترنت [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) التي تحول MD إلى HTML بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ! يمكنك أيضًا الاطلاع على أدوات تحويل MD الأخرى عبر الإنترنت: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)، [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)، [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) والعثور على [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) المناسبة.

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // بدء عملية التحويل
      Converter.ConvertMarkdown(sourcePath, resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration, String) {#convertmarkdown_6}

تحويل مصدر MD (markdown) المقدم عبر مسار ملف كامل إلى html. النتيجة هي ملف html تم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertMarkdown(String sourcePath, Configuration configuration, 
    String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | مسار ملف Markdown المصدر. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لضبط إعدادات البيئة للتطبيق. |
| outputPath | String | مسار ملف html الكامل كنتيجة تحويل الإخراج. |

## ملاحظات

محول Markdown

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

خطوات التحويل

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

مصدر التحويل. اكتشاف ملف MD محلي موجود أو إنشاء تدفق بيانات الإدخال كمصدر للتحويل. نتيجة التحويل. يمكنك الحصول مباشرة على [`HTMLDocument`](../../../com.aspose.html/htmldocument/) أو تحديد مسار ملف الإخراج للنتيجة اعتمادًا على توقيع الطريقة. استخدم طريقة ConvertMarkdown() من فئة Converter لحفظ MD كنتيجة html. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل اختياري. محول MD عبر الإنترنت

قد تكون مهتمًا أيضًا بأداة مجانية عبر الإنترنت [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) التي تحول MD إلى HTML بجودة عالية، وسهولة وسرعة. ما عليك سوى تحميل ملفاتك، تحويلها والحصول على النتائج في بضع ثوانٍ! يمكنك أيضًا الاطلاع على أدوات تحويل MD الأخرى عبر الإنترنت: [MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)، [MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)، [MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) والعثور على [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) المناسبة.

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // مسار ملف النتيجة للنموذج
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // بدء عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertMarkdown(sourcePath, new Configuration(), resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
