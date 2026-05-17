---
title: "Converter.ConvertTemplate"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة Converter. دمج مصدر القالب المقدم عبر HTMLDocument مع بيانات القالب XML JSON. النتيجة هي ملف html يتم إنشاؤه عبر مسار ملف الإخراج."
type: docs

url: /ar/java/com.aspose.html.converters/converter/converttemplate/
---
## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions, String) {#converttemplate_7}

دمج مصدر القالب المقدم عبر [`HTMLDocument`](../../../com.aspose.html/htmldocument/) مع بيانات القالب (XML, JSON). النتيجة هي ملف html يتم إنشاؤه عبر مسار ملف الإخراج.

```java
public static void ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| template | HTMLDocument | دمج هيكل المصدر المقدم عبر [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| البيانات | TemplateData | بيانات القالب للدمج - الاستبدال (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) كائن مثيل. يُستخدم لتحديد ما إذا كانت أسماء القالب وعناصر البيانات متطابقة، بغض النظر عن حالة الأحرف أم لا (الخيارات). |
| outputPath | String | المسار الكامل لملف html كنتيجة للتحويل. |

## ملاحظات

دمج القالب

فكرة دمج القوالب هي إنشاء مستند HTML بناءً على قالب HTML وتعبئته من مصدر بيانات. توفر Aspose.HTML بنية التعبيرات المضمنة للعمل مع القوالب وأنواع مصادر البيانات المختلفة، مثل XML و JSON. راجع [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) حيث يمكنك العثور على مزيد من المعلومات حول دمج القوالب واستخدام طريقة ConvertTemplate().

خطوات التحويل (الدمج)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

مصدر القالب. حدد مصدر قالب HTML عن طريق ملف، [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) كائن مثيل أو حتى عبر محتوى مضمن. نتيجة التحويل. يمكنك الحصول مباشرةً على HTMLDocument الناتج أو تحديد مسار ملف الإخراج للنتيجة حسب توقيع الطريقة. أنشئ مثيلًا لـ [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). استخدم طريقة ConvertTemplate() من فئة Converter لدمج القالب مع البيانات. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. شفرة المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## الأمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف مصدر هيكل HTML
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // مسار ملف بيانات قالب XML (JSON)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");
      
      // حدد مثيل كائن TemplateData
      var templateData = new TemplateData(templateDataPath);

      // مسار ملف النتيجة
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // حدد كائن TemplateLoadOptions الافتراضي
      var options = new TemplateLoadOptions();

      // استخدم مستند HTML كمصدر للتحويل
      var document = new HTMLDocument(sourcePath, new Configuration());

      // ابدأ عملية التحويل
      Converter.ConvertTemplate(document, templateData, options, resultPath);

      // مسح الموارد
      document.Dispose();





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### انظر أيضًا

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions, String) {#converttemplate_9}

دمج مصدر HTML للقالب المقدم عبر [`URL`](../../../com.aspose.html/url/) مع بيانات القالب (XML, JSON). النتيجة هي ملف HTML يتم إنشاؤه وفقًا لمسار ملف الإخراج.

```java
public static void ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options, 
    String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | دمج هيكل مصدر HTML المقدم عبر [`URL`](../../../com.aspose.html/url/). |
| البيانات | TemplateData | بيانات القالب للدمج - الاستبدال (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) كائن مثيل. يُستخدم لتحديد ما إذا كانت أسماء القالب وعناصر البيانات متطابقة، بغض النظر عن حالة الأحرف أم لا (الخيارات). |
| outputPath | String | المسار الكامل لملف html كنتيجة للتحويل. |

## ملاحظات

دمج القالب

فكرة دمج القوالب هي إنشاء مستند HTML بناءً على قالب HTML وتعبئته من مصدر بيانات. توفر Aspose.HTML بنية التعبيرات المضمنة للعمل مع القوالب وأنواع مصادر البيانات المختلفة، مثل XML و JSON. راجع [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) حيث يمكنك العثور على مزيد من المعلومات حول دمج القوالب واستخدام طريقة ConvertTemplate().

خطوات التحويل (الدمج)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

مصدر القالب. حدد مصدر قالب HTML عن طريق ملف، [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) كائن مثيل أو حتى عبر محتوى مضمن. نتيجة التحويل. يمكنك الحصول مباشرةً على HTMLDocument الناتج أو تحديد مسار ملف الإخراج للنتيجة حسب توقيع الطريقة. أنشئ مثيلًا لـ [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). استخدم طريقة ConvertTemplate() من فئة Converter لدمج القالب مع البيانات. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. شفرة المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## الأمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // عنوان URL لمصدر هيكل HTML
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // مسار ملف بيانات قالب XML (JSON)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // حدد مثيل كائن TemplateData
      var templateData = new TemplateData(templateDataPath);

      // مسار ملف النتيجة
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // حدد كائن TemplateLoadOptions الافتراضي
      var options = new TemplateLoadOptions();

      // ابدأ عملية التحويل
      Converter.ConvertTemplate(sourceUrl, templateData, options, resultPath);





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_8}

دمج مصدر HTML للقالب المقدم عبر [`URL`](../../../com.aspose.html/url/) مع بيانات القالب (XML, JSON). النتيجة هي ملف HTML يتم إنشاؤه وفقًا لمسار ملف الإخراج.

```java
public static void ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | دمج هيكل مصدر HTML المقدم عبر [`URL`](../../../com.aspose.html/url/). |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لإعداد إعدادات البيئة للتطبيق. |
| البيانات | TemplateData | بيانات القالب للدمج - الاستبدال (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) كائن مثيل. يُستخدم لتحديد ما إذا كانت أسماء القالب وعناصر البيانات متطابقة، بغض النظر عن حالة الأحرف أم لا (الخيارات). |
| outputPath | String | المسار الكامل لملف html كنتيجة للتحويل. |

## ملاحظات

دمج القالب

فكرة دمج القوالب هي إنشاء مستند HTML بناءً على قالب HTML وتعبئته من مصدر بيانات. توفر Aspose.HTML بنية التعبيرات المضمنة للعمل مع القوالب وأنواع مصادر البيانات المختلفة، مثل XML و JSON. راجع [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) حيث يمكنك العثور على مزيد من المعلومات حول دمج القوالب واستخدام طريقة ConvertTemplate().

خطوات التحويل (الدمج)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

مصدر القالب. حدد مصدر قالب HTML عن طريق ملف، [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) كائن مثيل أو حتى عبر محتوى مضمن. نتيجة التحويل. يمكنك الحصول مباشرةً على HTMLDocument الناتج أو تحديد مسار ملف الإخراج للنتيجة حسب توقيع الطريقة. أنشئ مثيلًا لـ [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). استخدم طريقة ConvertTemplate() من فئة Converter لدمج القالب مع البيانات. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. شفرة المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## الأمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // عنوان URL لمصدر هيكل HTML
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // مسار ملف بيانات قالب XML (JSON)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // حدد مثيل كائن TemplateData
      var templateData = new TemplateData(templateDataPath);

      // مسار ملف النتيجة
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // حدد كائن TemplateLoadOptions الافتراضي
      var options = new TemplateLoadOptions();

      // ابدأ عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions, String) {#converttemplate_11}

دمج مصدر HTML للقالب المقدم عبر مسار ملف كامل مع بيانات القالب (XML, JSON). النتيجة هي ملف html يتم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | دمج هيكل مصدر HTML المقدم عبر مسار ملف كامل. |
| البيانات | TemplateData | بيانات القالب للدمج - الاستبدال (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) كائن مثيل. يُستخدم لتحديد ما إذا كانت أسماء القالب وعناصر البيانات متطابقة، بغض النظر عن حالة الأحرف أم لا (الخيارات). |
| outputPath | String | المسار الكامل لملف html كنتيجة للتحويل. |

## ملاحظات

دمج القالب

فكرة دمج القوالب هي إنشاء مستند HTML بناءً على قالب HTML وتعبئته من مصدر بيانات. توفر Aspose.HTML بنية التعبيرات المضمنة للعمل مع القوالب وأنواع مصادر البيانات المختلفة، مثل XML و JSON. راجع [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) حيث يمكنك العثور على مزيد من المعلومات حول دمج القوالب واستخدام طريقة ConvertTemplate().

خطوات التحويل (الدمج)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

مصدر القالب. حدد مصدر قالب HTML عن طريق ملف، [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) كائن مثيل أو حتى عبر محتوى مضمن. نتيجة التحويل. يمكنك الحصول مباشرةً على HTMLDocument الناتج أو تحديد مسار ملف الإخراج للنتيجة حسب توقيع الطريقة. أنشئ مثيلًا لـ [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). استخدم طريقة ConvertTemplate() من فئة Converter لدمج القالب مع البيانات. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. شفرة المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## الأمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف مصدر هيكل HTML
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // مسار ملف بيانات قالب XML (JSON)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // حدد مثيل كائن TemplateData
      var templateData = new TemplateData(templateDataPath);

      // مسار ملف النتيجة
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // حدد كائن TemplateLoadOptions الافتراضي
      var options = new TemplateLoadOptions();

      // ابدأ عملية التحويل
      Converter.ConvertTemplate(sourcePath, templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### انظر أيضًا

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_10}

دمج مصدر HTML للقالب المقدم عبر مسار ملف كامل مع بيانات القالب (XML, JSON). النتيجة هي ملف html يتم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | دمج هيكل مصدر HTML المقدم عبر مسار ملف كامل. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لإعداد إعدادات البيئة للتطبيق. |
| البيانات | TemplateData | بيانات القالب للدمج - الاستبدال (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) كائن مثيل. يُستخدم لتحديد ما إذا كانت أسماء القالب وعناصر البيانات متطابقة، بغض النظر عن حالة الأحرف أم لا (الخيارات). |
| outputPath | String | المسار الكامل لملف html كنتيجة للتحويل. |

## ملاحظات

دمج القالب

فكرة دمج القوالب هي إنشاء مستند HTML بناءً على قالب HTML وتعبئته من مصدر بيانات. توفر Aspose.HTML بنية التعبيرات المضمنة للعمل مع القوالب وأنواع مصادر البيانات المختلفة، مثل XML و JSON. راجع [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) حيث يمكنك العثور على مزيد من المعلومات حول دمج القوالب واستخدام طريقة ConvertTemplate().

خطوات التحويل (الدمج)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

مصدر القالب. حدد مصدر قالب HTML عن طريق ملف، [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) كائن مثيل أو حتى عبر محتوى مضمن. نتيجة التحويل. يمكنك الحصول مباشرةً على HTMLDocument الناتج أو تحديد مسار ملف الإخراج للنتيجة حسب توقيع الطريقة. أنشئ مثيلًا لـ [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). استخدم طريقة ConvertTemplate() من فئة Converter لدمج القالب مع البيانات. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. شفرة المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## الأمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف مصدر هيكل HTML
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // مسار ملف بيانات قالب XML (JSON)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // حدد مثيل كائن TemplateData
      var templateData = new TemplateData(templateDataPath);

      // مسار ملف النتيجة
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // حدد كائن TemplateLoadOptions الافتراضي
      var options = new TemplateLoadOptions();

      // ابدأ عملية التحويل باستخدام التكوين الافتراضي
      Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### انظر أيضًا

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions, String) {#converttemplate_13}

دمج مصدر HTML للقالب المقدم عبر المحتوى المضمن مع بيانات القالب (XML, JSON). النتيجة هي ملف html يتم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | دمج هيكل مصدر HTML المقدم عبر محتوى سلسلة مضمن. |
| baseUrl | String | معرف URI الأساسي لقالب HTML. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| البيانات | TemplateData | بيانات القالب للدمج - الاستبدال (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) كائن مثيل. يُستخدم لتحديد ما إذا كانت أسماء القالب وعناصر البيانات متطابقة، بغض النظر عن حالة الأحرف أم لا (الخيارات). |
| outputPath | String | المسار الكامل لملف html كنتيجة للتحويل. |

## ملاحظات

دمج القالب

فكرة دمج القوالب هي إنشاء مستند HTML بناءً على قالب HTML وتعبئته من مصدر بيانات. توفر Aspose.HTML بنية التعبيرات المضمنة للعمل مع القوالب وأنواع مصادر البيانات المختلفة، مثل XML و JSON. راجع [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) حيث يمكنك العثور على مزيد من المعلومات حول دمج القوالب واستخدام طريقة ConvertTemplate().

خطوات التحويل (الدمج)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

مصدر القالب. حدد مصدر قالب HTML عن طريق ملف، [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) كائن مثيل أو حتى عبر محتوى مضمن. نتيجة التحويل. يمكنك الحصول مباشرةً على HTMLDocument الناتج أو تحديد مسار ملف الإخراج للنتيجة حسب توقيع الطريقة. أنشئ مثيلًا لـ [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). استخدم طريقة ConvertTemplate() من فئة Converter لدمج القالب مع البيانات. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. شفرة المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## الأمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	  // استخدم محتوى المصدر المضمن كقالب
      String templateContent =
        "<html>" + 
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";
       
      // مسار ملف بيانات قالب XML (JSON)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // حدد مثيل كائن TemplateData
      var templateData = new TemplateData(templateDataPath);

      // استخدم الإخراج كنتيجة للدمج
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // حدد كائن TemplateLoadOptions الافتراضي
      var options = new TemplateLoadOptions();
	  
      // ابدأ عملية التحويل
      Converter.ConvertTemplate(templateContent, String.Empty, templateData, options, resultFilePath);

*TemplateFolder - user template data folder.
*OutputFolder - user output file path.

Below is sample data file to merge with source

<?xml version="1.0" encoding="utf-8" ?>
<Data>
	<Person>
	<Title>Title 1</Title>
	<Name>John</Name>
	<Surname>Smith</Surname>
	<Address>
		<Number>200</Number>
		<Street>Austin rd.</Street>
		<City>Dallas</City>
	</Address>
	</Person>
	<Person>
	<Title>Title 2</Title>
	<Name>Mike</Name>
	<Surname>Milbert</Surname>
	<Address>
		<Number>126</Number>
		<Street>First Avenue</Street>
		<City>Chicago</City>
	</Address>
	</Person>
</Data>
```

### انظر أيضًا

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_12}

دمج مصدر HTML للقالب المقدم عبر المحتوى المضمن مع بيانات القالب (XML, JSON). النتيجة هي ملف html يتم إنشاؤه بواسطة مسار ملف الإخراج.

```java
public static void ConvertTemplate(String content, String baseUrl, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | دمج هيكل مصدر HTML المقدم عبر محتوى سلسلة مضمن. |
| baseUrl | String | معرف URI الأساسي لقالب HTML. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لإعداد إعدادات البيئة للتطبيق. |
| البيانات | TemplateData | بيانات القالب للدمج - الاستبدال (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) كائن مثيل. يُستخدم لتحديد ما إذا كانت أسماء القالب وعناصر البيانات متطابقة، بغض النظر عن حالة الأحرف أم لا (الخيارات). |
| outputPath | String | المسار الكامل لملف html كنتيجة للتحويل. |

## ملاحظات

دمج القالب

فكرة دمج القوالب هي إنشاء مستند HTML بناءً على قالب HTML وتعبئته من مصدر بيانات. توفر Aspose.HTML بنية التعبيرات المضمنة للعمل مع القوالب وأنواع مصادر البيانات المختلفة، مثل XML و JSON. راجع [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) حيث يمكنك العثور على مزيد من المعلومات حول دمج القوالب واستخدام طريقة ConvertTemplate().

خطوات التحويل (الدمج)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

مصدر القالب. حدد مصدر قالب HTML عن طريق ملف، [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) كائن مثيل أو حتى عبر محتوى مضمن. نتيجة التحويل. يمكنك الحصول مباشرةً على HTMLDocument الناتج أو تحديد مسار ملف الإخراج للنتيجة حسب توقيع الطريقة. أنشئ مثيلًا لـ [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). استخدم طريقة ConvertTemplate() من فئة Converter لدمج القالب مع البيانات. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. شفرة المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## الأمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
   // استخدم محتوى المصدر المضمن كقالب
   String templateContent =
    "<html>" + 
    "<body>" +
    "<div data_merge=\"{{#foreach Person}}\">" +
    "<p>{{Title}}</p>" +
    "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
    "<p>Address:</p>" +
    "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
    "</div>" +
    "</body></html>";
    
   // مسار ملف بيانات قالب XML (JSON)
   var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

   // حدد مثيل كائن TemplateData
   var templateData = new TemplateData(templateDataPath);

   // استخدم الإخراج كنتيجة للدمج
   var resultFilePath = Path.Combine(OutputFolder, "result.html");

   // حدد مثيل كائن configuration
   var configuration = new Configuration();

   // حدد كائن TemplateLoadOptions الافتراضي
   var options = new TemplateLoadOptions();

   // ابدأ عملية التحويل باستخدام التكوين الافتراضي
   Converter.ConvertTemplate(templateContent, String.Empty,
        configuration, templateData, options, resultFilePath);
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

فيما يلي ملف البيانات للدمج مع المصدر كقالب

```java
<?xml version="1.0" encoding="utf-8" ?>
<Data>
	<Person>
	<Title>Title 1</Title>
	<Name>John</Name>
	<Surname>Smith</Surname>
	<Address>
		<Number>200</Number>
		<Street>Austin rd.</Street>
		<City>Dallas</City>
	</Address>
	</Person>
	<Person>
	<Title>Title 2</Title>
	<Name>Mike</Name>
	<Surname>Milbert</Surname>
	<Address>
		<Number>126</Number>
		<Street>First Avenue</Street>
		<City>Chicago</City>
	</Address>
	</Person>
</Data>
```

### انظر أيضًا

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions) {#converttemplate}

دمج مصدر القالب المقدم بواسطة [`HTMLDocument`](../../../com.aspose.html/htmldocument/) مع بيانات القالب (XML, JSON). النتيجة هي HTMLDocument جديد يمكن حفظه كملف.

```java
public static HTMLDocument ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| template | HTMLDocument | دمج هيكل المصدر المقدم عبر [`HTMLDocument`](../../../com.aspose.html/htmldocument/). |
| البيانات | TemplateData | بيانات القالب للدمج - الاستبدال (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) كائن مثيل. يُستخدم لتحديد ما إذا كانت أسماء القالب وعناصر البيانات متطابقة، بغض النظر عن حالة الأحرف أم لا (الخيارات). |

### قيمة الإرجاع

تم إنشاء [`HTMLDocument`](../../../com.aspose.html/htmldocument/) جديد كنتيجة للتحويل يمكن حفظه عبر مسار ملف الإخراج.

## ملاحظات

دمج القالب

فكرة دمج القوالب هي إنشاء مستند HTML بناءً على قالب HTML وتعبئته من مصدر بيانات. توفر Aspose.HTML بنية التعبيرات المضمنة للعمل مع القوالب وأنواع مصادر البيانات المختلفة، مثل XML و JSON. راجع [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) حيث يمكنك العثور على مزيد من المعلومات حول دمج القوالب واستخدام طريقة ConvertTemplate().

خطوات التحويل (الدمج)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

مصدر القالب. حدد مصدر قالب HTML عن طريق ملف، [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) كائن مثيل أو حتى عبر محتوى مضمن. نتيجة التحويل. يمكنك الحصول مباشرةً على HTMLDocument الناتج أو تحديد مسار ملف الإخراج للنتيجة حسب توقيع الطريقة. أنشئ مثيلًا لـ [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). استخدم طريقة ConvertTemplate() من فئة Converter لدمج القالب مع البيانات. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. شفرة المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## الأمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف مصدر هيكل HTML
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // مسار ملف بيانات قالب XML (JSON)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // حدد مثيل كائن TemplateData
      var templateData = new TemplateData(templateDataPath);

      // مسار ملف النتيجة
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // حدد كائن TemplateLoadOptions الافتراضي
      var options = new TemplateLoadOptions();
      
      // استخدم مستند HTML كمصدر للتحويل
      using (var template = new HTMLDocument(sourcePath, new Configuration()))
      {
        // ابدأ عملية التحويل
        var document = Converter.ConvertTemplate(template, templateData, options);
         
        // حفظ النتيجة مع الموارد المرتبطة
        document.Save(new Url(resultPath));
      }





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### انظر أيضًا

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions) {#converttemplate_2}

دمج مصدر HTML القالب المقدم بواسطة [`URL`](../../../com.aspose.html/url/) مع بيانات القالب (XML, JSON). النتيجة هي [`HTMLDocument`](../../../com.aspose.html/htmldocument/) جديد يمكن حفظه كملف.

```java
public static HTMLDocument ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | دمج هيكل مصدر HTML المقدم عبر [`URL`](../../../com.aspose.html/url/). |
| البيانات | TemplateData | بيانات القالب للدمج - الاستبدال (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) كائن مثيل. يُستخدم لتحديد ما إذا كانت أسماء القالب وعناصر البيانات متطابقة، بغض النظر عن حالة الأحرف أم لا (الخيارات). |

### قيمة الإرجاع

تم إنشاء [`HTMLDocument`](../../../com.aspose.html/htmldocument/) جديد كنتيجة للتحويل يمكن حفظه عبر مسار ملف الإخراج.

## ملاحظات

دمج القالب

فكرة دمج القوالب هي إنشاء مستند HTML بناءً على قالب HTML وتعبئته من مصدر بيانات. توفر Aspose.HTML بنية التعبيرات المضمنة للعمل مع القوالب وأنواع مصادر البيانات المختلفة، مثل XML و JSON. راجع [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) حيث يمكنك العثور على مزيد من المعلومات حول دمج القوالب واستخدام طريقة ConvertTemplate().

خطوات التحويل (الدمج)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

مصدر القالب. حدد مصدر قالب HTML عن طريق ملف، [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) كائن مثيل أو حتى عبر محتوى مضمن. نتيجة التحويل. يمكنك الحصول مباشرةً على HTMLDocument الناتج أو تحديد مسار ملف الإخراج للنتيجة حسب توقيع الطريقة. أنشئ مثيلًا لـ [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). استخدم طريقة ConvertTemplate() من فئة Converter لدمج القالب مع البيانات. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. شفرة المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## الأمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // إنشاء عنوان URL لملف مصدر HTML الهيكلي
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // مسار ملف بيانات قالب XML (JSON)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // حدد مثيل كائن TemplateData
      var templateData = new TemplateData(templateDataPath);

      // مسار ملف النتيجة
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // حدد كائن TemplateLoadOptions الافتراضي
      var options = new TemplateLoadOptions();

      // ابدأ عملية التحويل
      using (var document = Converter.ConvertTemplate(sourceUrl, templateData, options))
      {
        // حفظ النتيجة مع الموارد المرتبطة
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### انظر أيضًا

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_1}

دمج مصدر HTML القالب المقدم بواسطة [`URL`](../../../com.aspose.html/url/) مع بيانات القالب (XML, JSON). النتيجة هي [`HTMLDocument`](../../../com.aspose.html/htmldocument/) جديد يمكن حفظه كملف.

```java
public static HTMLDocument ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | دمج هيكل مصدر HTML المقدم عبر [`URL`](../../../com.aspose.html/url/). |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لإعداد إعدادات البيئة للتطبيق. |
| البيانات | TemplateData | بيانات القالب للدمج - الاستبدال (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) كائن مثيل. يُستخدم لتحديد ما إذا كانت أسماء القالب وعناصر البيانات متطابقة، بغض النظر عن حالة الأحرف أم لا (الخيارات). |

### قيمة الإرجاع

تم إنشاء [`HTMLDocument`](../../../com.aspose.html/htmldocument/) جديد كنتيجة للتحويل يمكن حفظه عبر مسار ملف الإخراج.

## ملاحظات

دمج القالب

فكرة دمج القوالب هي إنشاء مستند HTML بناءً على قالب HTML وتعبئته من مصدر بيانات. توفر Aspose.HTML بنية التعبيرات المضمنة للعمل مع القوالب وأنواع مصادر البيانات المختلفة، مثل XML و JSON. راجع [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) حيث يمكنك العثور على مزيد من المعلومات حول دمج القوالب واستخدام طريقة ConvertTemplate().

خطوات التحويل (الدمج)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

مصدر القالب. حدد مصدر قالب HTML عن طريق ملف، [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) كائن مثيل أو حتى عبر محتوى مضمن. نتيجة التحويل. يمكنك الحصول مباشرةً على HTMLDocument الناتج أو تحديد مسار ملف الإخراج للنتيجة حسب توقيع الطريقة. أنشئ مثيلًا لـ [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). استخدم طريقة ConvertTemplate() من فئة Converter لدمج القالب مع البيانات. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. شفرة المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## الأمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // إنشاء عنوان URL لملف مصدر HTML الهيكلي
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // مسار ملف بيانات قالب XML (JSON)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // حدد مثيل كائن TemplateData
      var templateData = new TemplateData(templateDataPath);

      // مسار ملف النتيجة
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // حدد كائن TemplateLoadOptions الافتراضي
      var options = new TemplateLoadOptions();

      // ابدأ عملية التحويل باستخدام التكوين الافتراضي
      using (var document = Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options))
      {
        // حفظ النتيجة مع الموارد المرتبطة
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### انظر أيضًا

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions) {#converttemplate_4}

دمج مصدر HTML القالب المقدم بواسطة مسار ملف كامل مع بيانات القالب (XML, JSON). النتيجة هي [`HTMLDocument`](../../../com.aspose.html/htmldocument/) جديد يمكن حفظه كملف.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | دمج هيكل مصدر HTML المقدم عبر مسار ملف كامل. |
| البيانات | TemplateData | بيانات القالب للدمج - الاستبدال (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) كائن مثيل. يُستخدم لتحديد ما إذا كانت أسماء القالب وعناصر البيانات متطابقة، بغض النظر عن حالة الأحرف أم لا (الخيارات). |

### قيمة الإرجاع

تم إنشاء [`HTMLDocument`](../../../com.aspose.html/htmldocument/) جديد كنتيجة للتحويل يمكن حفظه عبر مسار ملف الإخراج.

## ملاحظات

دمج القالب

فكرة دمج القوالب هي إنشاء مستند HTML بناءً على قالب HTML وتعبئته من مصدر بيانات. توفر Aspose.HTML بنية التعبيرات المضمنة للعمل مع القوالب وأنواع مصادر البيانات المختلفة، مثل XML و JSON. راجع [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) حيث يمكنك العثور على مزيد من المعلومات حول دمج القوالب واستخدام طريقة ConvertTemplate().

خطوات التحويل (الدمج)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

مصدر القالب. حدد مصدر قالب HTML عن طريق ملف، [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) كائن مثيل أو حتى عبر محتوى مضمن. نتيجة التحويل. يمكنك الحصول مباشرةً على HTMLDocument الناتج أو تحديد مسار ملف الإخراج للنتيجة حسب توقيع الطريقة. أنشئ مثيلًا لـ [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). استخدم طريقة ConvertTemplate() من فئة Converter لدمج القالب مع البيانات. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. شفرة المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## الأمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف مصدر هيكل HTML
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // مسار ملف بيانات قالب XML (JSON)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // حدد مثيل كائن TemplateData
      var templateData = new TemplateData(templateDataPath);

      // مسار ملف النتيجة
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // حدد كائن TemplateLoadOptions الافتراضي
      var options = new TemplateLoadOptions();

      // ابدأ عملية التحويل
      using (var document = Converter.ConvertTemplate(sourcePath, templateData, options))
      {
        // حفظ النتيجة مع الموارد المرتبطة
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### انظر أيضًا

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_3}

دمج مصدر HTML القالب المقدم بواسطة مسار ملف كامل مع بيانات القالب (XML, JSON). النتيجة هي [`HTMLDocument`](../../../com.aspose.html/htmldocument/) جديد يمكن حفظه كملف.

```java
public static HTMLDocument ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | دمج هيكل مصدر HTML المقدم عبر مسار ملف كامل. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لإعداد إعدادات البيئة للتطبيق. |
| البيانات | TemplateData | بيانات القالب للدمج - الاستبدال (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) كائن مثيل. يُستخدم لتحديد ما إذا كانت أسماء القالب وعناصر البيانات متطابقة، بغض النظر عن حالة الأحرف أم لا (الخيارات). |

### قيمة الإرجاع

تم إنشاء [`HTMLDocument`](../../../com.aspose.html/htmldocument/) جديد كنتيجة للتحويل يمكن حفظه عبر مسار ملف الإخراج.

## ملاحظات

دمج القالب

فكرة دمج القوالب هي إنشاء مستند HTML بناءً على قالب HTML وتعبئته من مصدر بيانات. توفر Aspose.HTML بنية التعبيرات المضمنة للعمل مع القوالب وأنواع مصادر البيانات المختلفة، مثل XML و JSON. راجع [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) حيث يمكنك العثور على مزيد من المعلومات حول دمج القوالب واستخدام طريقة ConvertTemplate().

خطوات التحويل (الدمج)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

مصدر القالب. حدد مصدر قالب HTML عن طريق ملف، [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) كائن مثيل أو حتى عبر محتوى مضمن. نتيجة التحويل. يمكنك الحصول مباشرةً على HTMLDocument الناتج أو تحديد مسار ملف الإخراج للنتيجة حسب توقيع الطريقة. أنشئ مثيلًا لـ [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). استخدم طريقة ConvertTemplate() من فئة Converter لدمج القالب مع البيانات. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. شفرة المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## الأمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // مسار ملف مصدر هيكل HTML
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // مسار ملف بيانات قالب XML (JSON)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // حدد مثيل كائن TemplateData
      var templateData = new TemplateData(templateDataPath);

      // مسار ملف النتيجة
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // حدد كائن TemplateLoadOptions الافتراضي
      var options = new TemplateLoadOptions();

      // ابدأ عملية التحويل باستخدام التكوين الافتراضي
      using (var document = Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options))
      {
        // حفظ النتيجة مع الموارد المرتبطة
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### انظر أيضًا

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions) {#converttemplate_6}

دمج مصدر HTML القالب المقدم بواسطة محتوى مضمن مع بيانات القالب (XML, JSON). النتيجة هي [`HTMLDocument`](../../../com.aspose.html/htmldocument/) جديد يمكن حفظه كملف.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | دمج هيكل مصدر HTML المقدم عبر محتوى سلسلة مضمن. |
| baseUrl | String | معرف URI الأساسي لقالب HTML. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| البيانات | TemplateData | بيانات القالب للدمج - الاستبدال (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) كائن مثيل. يُستخدم لتحديد ما إذا كانت أسماء القالب وعناصر البيانات متطابقة، بغض النظر عن حالة الأحرف أم لا (الخيارات). |

### قيمة الإرجاع

تم إنشاء [`HTMLDocument`](../../../com.aspose.html/htmldocument/) جديد كنتيجة للتحويل يمكن حفظه عبر مسار ملف الإخراج.

## ملاحظات

دمج القالب

فكرة دمج القوالب هي إنشاء مستند HTML بناءً على قالب HTML وتعبئته من مصدر بيانات. توفر Aspose.HTML بنية التعبيرات المضمنة للعمل مع القوالب وأنواع مصادر البيانات المختلفة، مثل XML و JSON. راجع [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) حيث يمكنك العثور على مزيد من المعلومات حول دمج القوالب واستخدام طريقة ConvertTemplate().

خطوات التحويل (الدمج)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

مصدر القالب. حدد مصدر قالب HTML عن طريق ملف، [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) كائن مثيل أو حتى عبر محتوى مضمن. نتيجة التحويل. يمكنك الحصول مباشرةً على HTMLDocument الناتج أو تحديد مسار ملف الإخراج للنتيجة حسب توقيع الطريقة. أنشئ مثيلًا لـ [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). استخدم طريقة ConvertTemplate() من فئة Converter لدمج القالب مع البيانات. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. شفرة المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## الأمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // استخدم محتوى المصدر المضمن كقالب
      String templateContent =
        "<html>" +
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";

      // مسار ملف بيانات قالب XML (JSON)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // حدد مثيل كائن TemplateData
      var templateData = new TemplateData(templateDataPath);

      // استخدم الإخراج كنتيجة للدمج
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // حدد كائن TemplateLoadOptions الافتراضي
      var options = new TemplateLoadOptions();

      // بدء عملية التحويل وحفظ النتيجة
      using (var document = Converter.ConvertTemplate(
        templateContent, String.Empty,
        templateData,
        options))
      {
        document.Save(new Url(resultFilePath));
      }
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### انظر أيضًا

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_5}

دمج مصدر HTML القالب المقدم بواسطة محتوى مضمن مع بيانات القالب (XML, JSON). النتيجة هي [`HTMLDocument`](../../../com.aspose.html/htmldocument/) جديد يمكن حفظه كملف.

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, 
    Configuration configuration, TemplateData data, TemplateLoadOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | دمج هيكل مصدر HTML المقدم عبر محتوى سلسلة مضمن. |
| baseUrl | String | معرف URI الأساسي لقالب HTML. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| configuration | Configuration | تكوين البيئة. يمثل كائن السياق [`configuration`](../../../com.aspose.html/configuration/) الذي يُستخدم لإعداد إعدادات البيئة للتطبيق. |
| البيانات | TemplateData | بيانات القالب للدمج - الاستبدال (XML, JSON). |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) كائن مثيل. يُستخدم لتحديد ما إذا كانت أسماء القالب وعناصر البيانات متطابقة، بغض النظر عن حالة الأحرف أم لا (الخيارات). |

### قيمة الإرجاع

تم إنشاء [`HTMLDocument`](../../../com.aspose.html/htmldocument/) جديد كنتيجة للتحويل يمكن حفظه عبر مسار ملف الإخراج.

## ملاحظات

دمج القالب

فكرة دمج القوالب هي إنشاء مستند HTML بناءً على قالب HTML وتعبئته من مصدر بيانات. توفر Aspose.HTML بنية التعبيرات المضمنة للعمل مع القوالب وأنواع مصادر البيانات المختلفة، مثل XML و JSON. راجع [article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) حيث يمكنك العثور على مزيد من المعلومات حول دمج القوالب واستخدام طريقة ConvertTemplate().

خطوات التحويل (الدمج)

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

مصدر القالب. حدد مصدر قالب HTML عن طريق ملف، [`URL`](../../../com.aspose.html/url/), [`HTMLDocument`](../../../com.aspose.html/htmldocument/) كائن مثيل أو حتى عبر محتوى مضمن. نتيجة التحويل. يمكنك الحصول مباشرةً على HTMLDocument الناتج أو تحديد مسار ملف الإخراج للنتيجة حسب توقيع الطريقة. أنشئ مثيلًا لـ [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/). استخدم طريقة ConvertTemplate() من فئة Converter لدمج القالب مع البيانات. يمكنك أيضًا إضافة [`configuration`](../../../com.aspose.html/configuration/) كمعامل خيار. شفرة المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## الأمثلة

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // استخدم محتوى المصدر المضمن كقالب
      String templateContent =
        "<html>" + 
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";
       
      // مسار ملف بيانات قالب XML (JSON)
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // حدد مثيل كائن TemplateData
      var templateData = new TemplateData(templateDataPath);

      // استخدم الإخراج كنتيجة للدمج
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // حدد مثيل كائن configuration
      var configuration = new Configuration();

      // حدد كائن TemplateLoadOptions الافتراضي
      var options = new TemplateLoadOptions();

      // بدء عملية التحويل وحفظ النتيجة
      using (var document = Converter.ConvertTemplate(
        templateContent, String.Empty,
        configuration,
        templateData,
        options))
      {
        document.Save(new Url(resultFilePath));
      }
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### انظر أيضًا

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
