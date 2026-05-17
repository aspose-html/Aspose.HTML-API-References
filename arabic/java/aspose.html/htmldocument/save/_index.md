---
title: "HTMLDocument.Save"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة HTMLDocument. تحفظ المستند في ملف محلي محدد بواسطة url. جميع الموارد المستخدمة في هذا المستند سيتم حفظها في مجلد مجاور يُنشأ اسمه كـ output_file_name _files."
type: docs

url: /ar/java/com.aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

يحفظ المستند إلى ملف محلي محدد بواسطة URL. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، سيتم إنشاء اسمه كـ output_file_name + \"_files\".

```java
public void Save(Url url)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | محلي [`URL`](../../url/) إلى ملف الإخراج. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرفع إذا كان `url` المحدد ليس عنوان URL ملف محلي صالح. |

## ملاحظات

حفظ HTML

معظم المهام التي تحتاج إلى تنفيذها تتطلب حفظ مستند. بمجرد تحميل الملف الموجود أو إنشاء مستند HTML من الصفر، يمكنك حفظ التغييرات باستخدام إحدى طرق HTMLDocument.Save(). تسمح هذه الطرق بحفظ HTML إلى ملف محلي محدد بالمسار أو URL أو مساحة التخزين. راجع [التوثيق](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) لمعرفة المزيد حول الحفظ.

طريقة Save(Url)

من الضروري تحديد مسار Url كامل - 'outputFilePath' لحفظ مستند HTML. يُنشئ المُنشئ Url(url) مثلاً من الفئة [`Url`](../../url/) بالـ url المحدد. ثم يجب تمرير هذا المثيل إلى طريقة Save(Url). سيُحفظ المستند في الملف المحلي المحدد بالـ url. جميع الموارد المستخدمة في هذا المستند سيتم حفظها في مجلد مجاور يُنشأ اسمه كـ output_file_name + "_files".

الكود المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## الأمثلة

```java
import System;
import System.IO;
import Aspose.Html;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
        
	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(new Url(outputFilePath));
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### انظر أيضًا

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler) {#save}

يحفظ محتوى المستند والموارد باستخدام [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| resourceHandler | ResourceHandler | معالج الموارد [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |

### انظر أيضًا

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_10}

يحفظ المستند إلى ملف محلي يُحدَّد بالمسار. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، يُنشأ اسمه كالتالي: اسم_ملف_الإخراج + "_files".

```java
public void Save(String path)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | مسار نظام الملفات المحلي إلى ملف الإخراج. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرفع إذا كان `path` المحدد ليس مسار ملف محلي صالح. |

## ملاحظات

حفظ HTML

معظم المهام التي تحتاج إلى تنفيذها تتطلب حفظ مستند. بمجرد تحميل الملف الموجود أو إنشاء مستند HTML من الصفر، يمكنك حفظ التغييرات باستخدام إحدى طرق HTMLDocument.Save(). تسمح هذه الطرق بحفظ HTML إلى ملف محلي محدد بالمسار أو URL أو مساحة التخزين. راجع [التوثيق](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) لمعرفة المزيد حول الحفظ.

طريقة Save(String) تأخذ كمعامل مسار نظام ملفات محلي إلى ملف الإخراج وتُحفظ مستند HTML في الملف المحلي المحدد بالمسار. جميع الموارد المستخدمة في المستند سيتم حفظها في مجلد مجاور.

الكود المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## الأمثلة

```java
import System;
import System.IO;
import Aspose.Html;
...
 using (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (outputHtmlPath == null)
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(outputFilePath);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### انظر أيضًا

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveFormat) {#save_11}

يحفظ المستند إلى ملف محلي محدد بواسطة المسار. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، سيتم إنشاء اسمه كـ output_file_name + \"_files\".

```java
public void Save(String path, HTMLSaveFormat saveFormat)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | مسار الملف المحلي إلى ملف الإخراج. |
| saveFormat | HTMLSaveFormat | الصيغة التي يتم حفظ المستند بها. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرفع إذا كان `path` المحدد ليس مسار ملف محلي صالح. |

## ملاحظات

حفظ HTML

معظم المهام التي تحتاج إلى تنفيذها تتطلب حفظ مستند. بمجرد تحميل الملف الموجود أو إنشاء مستند HTML من الصفر، يمكنك حفظ التغييرات باستخدام إحدى طرق HTMLDocument.Save(). تسمح هذه الطرق بحفظ HTML إلى ملف محلي محدد بالمسار أو URL أو مساحة التخزين. راجع [التوثيق](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) لمعرفة المزيد حول الحفظ.

Save(String, HTMLSaveFormat) طريقة

طريقة Save(String, HTMLSaveFormat) تأخذ كمعلمات مسار نظام ملفات محلي لملف الإخراج و saveFormat. تحدد تعداد [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) التنسيق الذي يُحفظ به المستند، ويمكن أن يكون HTML أو MHTML أو MD. الطريقة تحفظ مستند HTML بالتنسيق المحدد إلى الملف المحلي المحدد بالمسار. جميع الموارد المستخدمة في المستند سيتم حفظها في مجلد مجاور.

الكود المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## الأمثلة

```java
# HTML input file content
<!DOCTYPE html>
<html lang="en"
   xmlns:xml="http://www.w3.org/XML/1998/package">
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="styles/main.css">
  <title>Title</title>
</head>
<body>
<div id="uniqueIdentifier">Container with ID - identifier</div>
<div class="custom-class">Customized by css class container</div>

<div>
  <p class="pStyle">First styled by pStyle class paragraph</p>
  <p class="pStyle">Second styled by pStyle class paragraph</p>
  <p class="pStyle">Third styled by pStyle class paragraph</p>
  <span class="pStyle">Span styled by pStyle</span>
</div>

<math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>...</mrow>
</math>

<div id="smart class">
  <p id="p1" class="ddd kkk">Paragraph styled by class name =ddd kkk=</p>
  <p id="p2" class="ddd fff">Paragraph styled by class name =ddd fff=</p>
  <p id="p3" class="kkk fff">Paragraph styled by class name =kkk fff=</p>
</div>

</body>
</html>

# C# code
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}
	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(outputFilePath, HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

# Content of result file

MIME-Version: 1.0

Content-Type: Multipart/related; boundary="boundary";type=Text/HTML

--boundary

Content-Type: text/html;

Content-Location: result.mhtml

&lt;!DOCTYPE html&gt;&lt;html lang="en" xmlns:xml="http://www.w3.org/XML/1998/package"&gt;&lt;head&gt;

&lt;meta charset="UTF-8"&gt;

&lt;link rel="stylesheet" href="main.css"&gt;

&lt;title&gt;العنوان&lt;/title&gt;

&lt;/head&gt;

&lt;body&gt;

&lt;div id="uniqueIdentifier"&gt;حاوية مع المعرف - identifier&lt;/div&gt;

&lt;div class="custom-class"&gt;مُخصص بواسطة حاوية فئة css&lt;/div&gt;

&lt;div&gt;

&lt;p class="pStyle"&gt;الفقرة الأولى مُنسقة بواسطة فئة pStyle&lt;/p&gt;

&lt;p class="pStyle"&gt;الفقرة الثانية مُنسقة بواسطة فئة pStyle&lt;/p&gt;

&lt;p class="pStyle"&gt;الفقرة الثالثة مُنسقة بواسطة فئة pStyle&lt;/p&gt;

&lt;span class="pStyle"&gt;العنصر Span مُنسق بواسطة pStyle&lt;/span&gt;

&lt;/div&gt;

&lt;math xmlns="http://www.w3.org/1998/Math/MathML"&gt;

&lt;mrow&gt;...&lt;/mrow&gt;

&lt;/math&gt;

&lt;div id="smart class"&gt;

&lt;p id="p1" class="ddd kkk"&gt;فقرة مُنسقة بواسطة اسم الفئة =ddd kkk=&lt;/p&gt;

&lt;p id="p2" class="ddd fff"&gt;فقرة مُنسقة بواسطة اسم الفئة =ddd fff=&lt;/p&gt;

&lt;p id="p3" class="kkk fff"&gt;فقرة مُنسقة بواسطة اسم الفئة =kkk fff=&lt;/p&gt;

&lt;/div&gt;

&lt;div&gt;مرحبًا من عنصر DIV&lt;/div&gt;&lt;/body&gt;&lt;/html&gt;

--boundary

نوع المحتوى: text/css;

موقع المحتوى: main.css

.custom-class { color: yellow; background-color: blueviolet; margin-top: 10pt; margin-right: 10pt; margin-bottom: 10pt; margin-left: 10pt; }.pStyle { font-

--boundary--

### انظر أيضًا

* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

يحفظ المستند إلى ملف محلي محدد بواسطة URL. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، سيتم إنشاء اسمه كـ output_file_name + \"_files\".

```java
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | عنوان URL المحلي لملف الإخراج. |
| saveFormat | HTMLSaveFormat | الصيغة التي يتم حفظ المستند بها. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرفع إذا كان `url` المحدد ليس عنوان URL ملف محلي صالح. |

## ملاحظات

حفظ HTML

معظم المهام التي تحتاج إلى تنفيذها تتطلب حفظ مستند. بمجرد تحميل الملف الموجود أو إنشاء مستند HTML من الصفر، يمكنك حفظ التغييرات باستخدام إحدى طرق HTMLDocument.Save(). تسمح هذه الطرق بحفظ HTML إلى ملف محلي محدد بالمسار أو URL أو مساحة التخزين. راجع [التوثيق](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) لمعرفة المزيد حول الحفظ.

Save(Url, HTMLSaveFormat) طريقة

من الضروري تحديد مسار Url كامل - 'outputFilePath' لحفظ مستند HTML. يقوم المُنشئ Url(url) بإنشاء نسخة من الفئة [`Url`](../../url/) بالعنوان المحدد. تحدد تعداد [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) الصيغة التي يُحفظ بها المستند، ويمكن أن تكون HTML أو MHTML أو صيغ MD. بعد ذلك يجب تمرير المعلمات إلى طريقة Save(url, saveFormat). سيتم حفظ المستند بالصِيغة المحددة إلى الملف المحلي المحدد بالعنوان.

الكود المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## الأمثلة

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(new Url(outputFilePath), HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### انظر أيضًا

* class [Url](../../url/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveFormat) {#save_1}

يحفظ محتوى المستند والموارد باستخدام [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveFormat saveFormat)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| resourceHandler | ResourceHandler | معالج الموارد [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveFormat | HTMLSaveFormat | الصيغة التي يتم حفظ المستند بها. |

### انظر أيضًا

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveOptions) {#save_12}

يحفظ المستند إلى ملف محلي يُحدَّد بالمسار. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، يُنشأ اسمه كالتالي: اسم_ملف_الإخراج + "_files".

```java
public void Save(String path, HTMLSaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار المحلي لملف الإخراج. |
| saveOptions | HTMLSaveOptions | كائن [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) مخصص لإدارة عملية معالجة الموارد. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرفع إذا كان `path` المحدد ليس مسار ملف محلي صالح. |

## ملاحظات

حفظ HTML

معظم المهام التي تحتاج إلى تنفيذها تتطلب حفظ مستند. بمجرد تحميل الملف الموجود أو إنشاء مستند HTML من الصفر، يمكنك حفظ التغييرات باستخدام إحدى طرق HTMLDocument.Save(). تسمح هذه الطرق بحفظ HTML إلى ملف محلي محدد بالمسار أو URL أو مساحة التخزين. راجع [التوثيق](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) لمعرفة المزيد حول الحفظ.

Save(String, HTMLSaveOptions) طريقة

طريقة Save(String, HTMLSaveOptions) تأخذ كمعلمات مسار نظام ملفات محلي إلى ملف الإخراج، نسخة من الفئة [HTMLSaveOptions](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) وتقوم بحفظ مستند HTML مع الموارد إلى الملف المحلي المحدد بالمسار. يقوم المُنشئ HTMLSaveOptions() بإنشاء نسخة من خيارات الحفظ التي تحتوي على خصائص [`ResourceHandlingOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) المستخدمة لتكوين معالجة الموارد. سيتم حفظ جميع الموارد المستخدمة في المستند في مجلد مجاور.

الكود المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## الأمثلة

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// تعريف نسخة من فئة الخيارات
	var options = new HTMLSaveOptions();
	// قيد معالجة الصفحات
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### انظر أيضًا

* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

يحفظ المستند إلى ملف محلي محدد بواسطة URL. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، سيتم إنشاء اسمه كالتالي: output_file_name + \"_files\".

```java
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | محلي [`URL`](../../url/) إلى ملف الإخراج. |
| saveOptions | HTMLSaveOptions | كائن [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) مخصص لإدارة عملية معالجة الموارد. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرفع إذا كان `url` المحدد ليس عنوان URL ملف محلي صالح. |

## ملاحظات

حفظ HTML

معظم المهام التي تحتاج إلى تنفيذها تتطلب حفظ مستند. بمجرد تحميل الملف الموجود أو إنشاء مستند HTML من الصفر، يمكنك حفظ التغييرات باستخدام إحدى طرق HTMLDocument.Save(). تسمح هذه الطرق بحفظ HTML إلى ملف محلي محدد بالمسار أو URL أو مساحة التخزين. راجع [التوثيق](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) لمعرفة المزيد حول الحفظ.

Save(Url, HTMLSaveOptions) طريقة

من الضروري تحديد مسار Url كامل لحفظ مستند HTML. يقوم المُنشئ Url(url) بإنشاء نسخة من الفئة [`Url`](../../url/) بالعنوان المحدد. يقوم المُنشئ HTMLSaveOptions() بإنشاء نسخة من الفئة [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) التي تحتوي على خصائص ResourceHandlingOptions المستخدمة لتكوين معالجة الموارد. طريقة Save(url, saveOptions) تأخذ المعلمات وتقوم بحفظ مستند HTML مع الموارد إلى الملف المحلي المحدد بالعنوان.

الكود المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## الأمثلة

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// تعريف نسخة من فئة الخيارات
	var options = new HTMLSaveOptions();
	// قيد معالجة الصفحات
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### انظر أيضًا

* class [Url](../../url/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveOptions) {#save_2}

يحفظ محتوى المستند والموارد باستخدام [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| resourceHandler | ResourceHandler | معالج الموارد [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | HTMLSaveOptions | خيارات حفظ HTML. |

### انظر أيضًا

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MarkdownSaveOptions) {#save_13}

يحفظ المستند إلى ملف محلي يُحدَّد بالمسار. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، يُنشأ اسمه كالتالي: اسم_ملف_الإخراج + "_files".

```java
public void Save(String path, MarkdownSaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار المحلي لملف الإخراج. |
| saveOptions | MarkdownSaveOptions | استخدام كائن [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [توثيق Aspose](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options). |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرفع إذا كان `path` المحدد ليس مسار ملف محلي صالح. |

## ملاحظات

حفظ HTML

معظم المهام التي تحتاج إلى تنفيذها تتطلب حفظ مستند. بمجرد تحميل الملف الموجود أو إنشاء مستند HTML من الصفر، يمكنك حفظ التغييرات باستخدام إحدى طرق HTMLDocument.Save(). تسمح هذه الطرق بحفظ HTML إلى ملف محلي محدد بالمسار أو URL أو مساحة التخزين. راجع [التوثيق](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) لمعرفة المزيد حول الحفظ.

Save(String, MarkdownSaveOptions) طريقة

من الضروري تحديد مسار نظام ملفات محلي إلى ملف الإخراج لحفظ المستند. يقوم المُنشئ MarkdownSaveOptions() بإنشاء نسخة من الفئة [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) التي تحتوي على مجموعة من الخصائص. على سبيل المثال، يمكنك ضبط نمط تنسيق markdown، واستخدام خيارات متوافقة مع GitLab Flavored Markdown المحددة مسبقًا وتكوين معالجة الموارد. طريقة Save(path, saveOptions) تأخذ مسار نظام الملفات المحلي إلى ملف الإخراج ونسخة الخيارات كمعلمات وتقوم بحفظ HTML كمستند Markdown مع الموارد إلى الملف المحلي المحدد بالمسار.

الكود المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## الأمثلة

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
     
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// تعريف نسخة من فئة الخيارات
	var options = new MarkdownSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### انظر أيضًا

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

يحفظ المستند إلى ملف محلي محدد بواسطة URL. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، سيتم إنشاء اسمه كالتالي: output_file_name + \"_files\".

```java
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | محلي [`URL`](../../url/) إلى ملف الإخراج. |
| saveOptions | MarkdownSaveOptions | استخدام كائن [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [التوثيق](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options). |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرفع إذا كان `url` المحدد ليس عنوان URL ملف محلي صالح. |

## ملاحظات

حفظ HTML

معظم المهام التي تحتاج إلى تنفيذها تتطلب حفظ مستند. بمجرد تحميل الملف الموجود أو إنشاء مستند HTML من الصفر، يمكنك حفظ التغييرات باستخدام إحدى طرق HTMLDocument.Save(). تسمح هذه الطرق بحفظ HTML إلى ملف محلي محدد بالمسار أو URL أو مساحة التخزين. راجع [التوثيق](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) لمعرفة المزيد حول الحفظ.

Save(Url, MarkdownSaveOptions) طريقة

من الضروري تحديد مسار Url كامل لحفظ المستند. يقوم المُنشئ Url(url) بإنشاء نسخة من الفئة [`Url`](../../url/) بالعنوان المحدد. يقوم المُنشئ MarkdownSaveOptions() بإنشاء نسخة من الفئة [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) التي تحتوي على مجموعة من الخصائص. على سبيل المثال، يمكنك ضبط نمط تنسيق Markdown، واستخدام خيارات متوافقة مع GitLab Flavored Markdown المحددة مسبقًا وتكوين معالجة الموارد. طريقة Save(url, saveOptions) تأخذ نسخة العنوان والخيارات كمعلمات وتقوم بحفظ المستند مع الموارد إلى الملف المحلي المحدد بالعنوان.

الكود المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## الأمثلة

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// تعريف نسخة من فئة الخيارات
	var options = new MarkdownSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### انظر أيضًا

* class [Url](../../url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MarkdownSaveOptions) {#save_3}

يحفظ محتوى المستند والموارد باستخدام [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, MarkdownSaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| resourceHandler | ResourceHandler | معالج الموارد [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MarkdownSaveOptions | خيارات حفظ Markdown. |

### انظر أيضًا

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MHTMLSaveOptions) {#save_14}

يحفظ المستند إلى ملف محلي يُحدَّد بالمسار. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، يُنشأ اسمه كالتالي: اسم_ملف_الإخراج + "_files".

```java
public void Save(String path, MHTMLSaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار المحلي لملف الإخراج. |
| saveOptions | MHTMLSaveOptions | استخدام كائن [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [التوثيق](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options). |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرفع إذا كان `path` المحدد ليس مسار ملف محلي صالح. |

## ملاحظات

حفظ HTML

معظم المهام التي تحتاج إلى تنفيذها تتطلب حفظ مستند. بمجرد تحميل الملف الموجود أو إنشاء مستند HTML من الصفر، يمكنك حفظ التغييرات باستخدام إحدى طرق HTMLDocument.Save(). تسمح هذه الطرق بحفظ HTML إلى ملف محلي محدد بالمسار أو URL أو مساحة التخزين. راجع [التوثيق](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) لمعرفة المزيد حول الحفظ.

طريقة Save(String, MHTMLSaveOptions)

من الضروري تحديد مسار نظام ملفات محلي إلى ملف الإخراج لحفظ المستند. يقوم المُنشئ MHTMLSaveOptions() بإنشاء نسخة من الفئة [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) التي تحتوي على الخاصية ResourceHandlingOptions والتي تُستخدم لتكوين معالجة الموارد. طريقة Save(path, saveOptions) تأخذ مسار نظام ملفات محلي إلى ملف الإخراج وكائن خيارات الحفظ كمعاملات وتقوم بحفظ HTML كمستند MHTML إلى الملف المحلي المحدد بالمسار.

الكود المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## الأمثلة

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// تعريف نسخة من فئة الخيارات
	var options = new MHTMLSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### انظر أيضًا

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

يحفظ المستند إلى ملف محلي محدد بواسطة URL. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، سيتم إنشاء اسمه كالتالي: output_file_name + \"_files\".

```java
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | عنوان URL المحلي لملف الإخراج. |
| saveOptions | MHTMLSaveOptions | استخدام كائن [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) يتيح لك ضبط عملية العرض. لمزيد من المعلومات راجع [التوثيق](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options). |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرفع إذا كان `url` المحدد ليس عنوان URL ملف محلي صالح. |

## ملاحظات

حفظ HTML

معظم المهام التي تحتاج إلى تنفيذها تتطلب حفظ مستند. بمجرد تحميل الملف الموجود أو إنشاء مستند HTML من الصفر، يمكنك حفظ التغييرات باستخدام إحدى طرق HTMLDocument.Save(). تسمح هذه الطرق بحفظ HTML إلى ملف محلي محدد بالمسار أو URL أو مساحة التخزين. راجع [التوثيق](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) لمعرفة المزيد حول الحفظ.

طريقة Save(Url, MHTMLSaveOptions)

من الضروري تحديد مسار Url كامل لحفظ المستند. يقوم المُنشئ Url(url) بإنشاء نسخة من الفئة [`Url`](../../url/) بالعنوان المحدد. يقوم المُنشئ MHTMLSaveOptions() بإنشاء نسخة من الفئة [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) التي تحتوي على الخاصية ResourceHandlingOptions والتي تُستخدم لتكوين معالجة الموارد. طريقة Save(url, saveOptions) تأخذ العنوان والخيارات كمعاملات وتقوم بحفظ HTML كمستند MHTML إلى الملف المحلي المحدد بالعنوان.

الكود المصدر

يمكنك تنزيل الأمثلة الكاملة وملفات البيانات من [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## الأمثلة

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// تعريف نسخة من فئة الخيارات
	var options = new MHTMLSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input file path.

*outputHtmlPath - user output folder path.

### انظر أيضًا

* class [Url](../../url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MHTMLSaveOptions) {#save_4}

يحفظ محتوى المستند والموارد باستخدام [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, MHTMLSaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| resourceHandler | ResourceHandler | معالج الموارد [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MHTMLSaveOptions | خيارات حفظ MHTML. |

### انظر أيضًا

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
