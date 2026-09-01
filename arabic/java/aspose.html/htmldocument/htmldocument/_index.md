---
title: "HTMLDocument"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "منشئ HTMLDocument. يقوم منشئ HTMLDocument بإنشاء كائن مستند HTML جديد وهو صفحة ويب تم تحميلها في المتصفح وتعمل كنقطة دخول إلى محتوى الصفحات."
type: docs

url: /ar/java/com.aspose.html/htmldocument/htmldocument/
---
## HTMLDocument() {#constructor}

يقوم مُنشئ HTMLDocument بإنشاء كائن مستند HTML جديد يكون صفحة ويب محمَّلة في المتصفح وتعمل كنقطة دخول إلى محتوى الصفحة.

```java
public HTMLDocument()
```

## ملاحظات

ملاحظة: يتم إنشاء المستند بقيمة افتراضية للخاصية base-url تساوي 'about:blank'.

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## أمثلة

بمجرد إنشاء كائن المستند، يمكن ملؤه لاحقًا بعناصر HTML. يوضح مقتطف الشيفرة التالي استخدام منشئ HTMLDocument() الافتراضي لإنشاء مستند HTML فارغ وحفظه إلى ملف.

```java
import (var document = new HTMLDocument())
{
	// اعمل مع المستند هنا
	...	
	
	// احفظ المستند إلى ملف
	document.Save("document.html");
}
```

### انظر أيضًا

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Configuration) {#constructor_1}

يقوم مُنشئ HTMLDocument بإنشاء كائن مستند HTML جديد يكون صفحة ويب محمَّلة في المتصفح وتعمل كنقطة دخول إلى محتوى الصفحة.

```java
public HTMLDocument(Configuration configuration)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| التكوين | التكوين | تكوين البيئة مثل سياسة السكريبتات، ورقة الأنماط المخصصة للمستخدم، إلخ. |

## ملاحظات

ملاحظة: يتم إنشاء المستند بقيمة افتراضية للخاصية base-url تساوي 'about:blank'.

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## أمثلة

المثال التالي يوضح كيفية استخدام كائن التكوين لتعطيل السكريبتات:

```java
// جهّز كود HTML واحفظه في ملف
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// إنشاء نسخة من Configuration
import (var configuration = new Configuration())
{
	// وضع علامة 'scripts' كموارد غير موثوق
	configuration.Security |= Sandbox.Scripts;

	// تهيئة مستند HTML باستخدام التكوين المحدد
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// تحويل HTML إلى PDF
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### انظر أيضًا

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url) {#constructor_4}

يقوم بتحميل مستند HTML من عنوان URL.

ملاحظة: في حال تمرير URL غير صحيح لا يمكن الوصول إليه في الوقت الحالي، تقوم المكتبة برمي [`DOMException`](../../../com.aspose.html.dom/domexception/) مع رمز متخصص ‘NetworkError’ لإبلاغك بأنه لا يمكن العثور على المورد المحدد.

```java
public HTMLDocument(Url url)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | عنوان URL لمستند HTML لفتحه. |

## ملاحظات

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## أمثلة

حمّل مستندًا من صفحة الويب 'https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html':

```java
import (var document = new HTMLDocument("https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html"))
{
	// اكتب محتوى المستند إلى تدفق الإخراج
	Console.WriteLine(document.DocumentElement.OuterHTML);
}
```

### انظر أيضًا

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url, Configuration) {#constructor_5}

يقوم بتحميل مستند HTML من عنوان URL مع إعدادات تكوين البيئة المحددة.

ملاحظة: في حال تمرير URL غير صحيح لا يمكن الوصول إليه في الوقت الحالي، تقوم المكتبة برمي [DOMException](T:com.aspose.html.dom.DOMException) مع رمز متخصص ‘NetworkError’ لإبلاغك بأنه لا يمكن العثور على المورد المحدد.

```java
public HTMLDocument(Url url, Configuration configuration)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | عنوان URL لمستند HTML لفتحه. |
| التكوين | التكوين | تكوين البيئة مثل سياسة السكريبتات، ورقة الأنماط المخصصة للمستخدم، إلخ. |

## ملاحظات

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## أمثلة

```java
The following example demonstrates how to use the configuration object to disable scripts:

// جهّز كود HTML واحفظه في ملف
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// إنشاء نسخة من Configuration
import (var configuration = new Configuration())
{
	// وضع علامة 'scripts' كموارد غير موثوق
	configuration.Security |= Sandbox.Scripts;

	// تهيئة مستند HTML باستخدام التكوين المحدد
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// تحويل HTML إلى PDF
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### انظر أيضًا

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String) {#constructor_10}

يقوم بتحميل مستند HTML من عنوان.

ملاحظة: في حال تمرير URL غير صحيح لا يمكن الوصول إليه في الوقت الحالي، تقوم المكتبة برمي [`DOMException`](../../../com.aspose.html.dom/domexception/) مع رمز متخصص ‘NetworkError’ لإبلاغك بأنه لا يمكن العثور على المورد المحدد.

```java
public HTMLDocument(String address)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العنوان | String | عنوان مستند HTML لفتحه. |

## ملاحظات

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## أمثلة

تهيئة مستند HTML من عنوان.

```java
import (var document = new HTMLDocument("./my-folder/document.html")))
{
	...
}
```

### انظر أيضًا

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Configuration) {#constructor_11}

يقوم بتحميل مستند HTML من عنوان مع إعدادات تكوين البيئة المحددة.

ملاحظة: في حال تمرير URL غير صحيح لا يمكن الوصول إليه في الوقت الحالي، تقوم المكتبة برمي [`DOMException`](../../../com.aspose.html.dom/domexception/) مع رمز متخصص ‘NetworkError’ لإبلاغك بأنه لا يمكن العثور على المورد المحدد.

```java
public HTMLDocument(String address, Configuration configuration)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العنوان | String | عنوان مستند HTML لفتحه. |
| التكوين | التكوين | تكوين البيئة مثل سياسة السكريبتات، ورقة الأنماط المخصصة للمستخدم، إلخ. |

## ملاحظات

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## أمثلة

```java
// إنشاء نسخة من Configuration
import (var configuration = new Configuration())
{
	// وضع علامة 'scripts' كموارد غير موثوق
	configuration.Security |= Sandbox.Scripts;
	
	using (var document = new HTMLDocument("./my-folder/document.html", configuration)))
	{
		...
	}
}
```

### انظر أيضًا

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String) {#constructor_14}

ينشئ مستند HTML من محتوى سلسلة (String) مع base-uri محدد.

```java
public HTMLDocument(String content, String baseUri)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | محتوى الـ String لتحميل المستند به. |
| baseUri | String | عنوان URI الأساسي للمستند. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يرمي استثناءً إذا كان معامل base-uri فارغًا (null). |

## ملاحظات

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## أمثلة

```java
// تحضير كود HTML
var html_code = "<p>Hello World!</p>";

// تهيئة مستند من المتغير String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### انظر أيضًا

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String, Configuration) {#constructor_15}

ينشئ مستند HTML من محتوى سلسلة (String) مع base-uri محدد وإعدادات تكوين البيئة.

```java
public HTMLDocument(String content, String baseUri, Configuration configuration)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | محتوى الـ String لتحميل المستند به. |
| baseUri | String | عنوان URI الأساسي للمستند. |
| التكوين | التكوين | تكوين البيئة مثل سياسة السكريبتات، ورقة الأنماط المخصصة للمستخدم، إلخ. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يرمي استثناءً إذا كان معامل base-uri فارغًا (null). |

## ملاحظات

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## أمثلة

```java
// تحضير كود HTML
var html_code = "<p>Hello World!</p>";

// تهيئة مستند من المتغير String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### انظر أيضًا

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url) {#constructor_12}

ينشئ مستند HTML من محتوى سلسلة (String) مع base-uri محدد.

```java
public HTMLDocument(String content, Url baseUri)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | محتوى الـ String لتحميل المستند به. |
| baseUri | Url | عنوان URI الأساسي للمستند. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يرمي استثناءً إذا كان معامل base-uri فارغًا (null). |

## ملاحظات

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## أمثلة

```java
// تحضير كود HTML
var html_code = "<p>Hello World!</p>";

// تهيئة مستند من المتغير String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### انظر أيضًا

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url, Configuration) {#constructor_13}

ينشئ مستند HTML من محتوى سلسلة (String) مع base-uri محدد وإعدادات تكوين البيئة.

```java
public HTMLDocument(String content, Url baseUri, Configuration configuration)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | محتوى الـ String لتحميل المستند به. |
| baseUri | Url | عنوان URI الأساسي للمستند. |
| التكوين | التكوين | تكوين البيئة مثل سياسة السكريبتات، ورقة الأنماط المخصصة للمستخدم، إلخ. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يرمي استثناءً إذا كان معامل base-uri فارغًا (null). |

## ملاحظات

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## أمثلة

```java
// تحضير كود HTML
var html_code = "<p>Hello World!</p>";

// تهيئة مستند من المتغير String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### انظر أيضًا

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String) {#constructor_8}

ينشئ مستند HTML من محتوى [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) مع base-uri محدد يُستخدم لحل مسار الموارد النسبية.

```java
public HTMLDocument(Stream content, String baseUri)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| content | Stream | محتوى الـ [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) لتحميل المستند به. |
| baseUri | String | عنوان URI الأساسي للمستند. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يرمي استثناءً إذا كان معامل base-uri فارغًا (null). |

## ملاحظات

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## أمثلة

```java
// إنشاء كائن تدفق ذاكرة
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// اكتب كود HTML إلى كائن الذاكرة
	sw.Write("<p>Hello World! I love HTML!</p>");

	// من المهم ضبط الموضع إلى البداية لأن HTMLDocument يبدأ القراءة بالضبط من الموضع الحالي داخل الدفق
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// تهيئة مستند من المتغير String
	using (var document = new HTMLDocument(mem, "."))
	{
		// احفظ المستند على القرص
		document.Save("load-from-stream.html");
	}
}
```

### انظر أيضًا

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String, Configuration) {#constructor_9}

ينشئ مستند HTML من محتوى [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) مع base-uri محدد وإعدادات تكوين البيئة.

```java
public HTMLDocument(Stream content, String baseUri, Configuration configuration)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| content | Stream | محتوى الـ [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) لتحميل المستند به. |
| baseUri | String | عنوان URI الأساسي للمستند. |
| التكوين | التكوين | تكوين البيئة مثل سياسة السكريبتات، ورقة الأنماط المخصصة للمستخدم، إلخ. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يرمي استثناءً إذا كان معامل base-uri فارغًا (null). |

## ملاحظات

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## أمثلة

```java
// إنشاء كائن تدفق ذاكرة
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// اكتب كود HTML إلى كائن الذاكرة
	sw.Write("<p>Hello World! I love HTML!</p>");

	// من المهم ضبط الموضع إلى البداية لأن HTMLDocument يبدأ القراءة بالضبط من الموضع الحالي داخل الدفق
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// تهيئة مستند من المتغير String
	using (var document = new HTMLDocument(mem, "."))
	{
		// احفظ المستند على القرص
		document.Save("load-from-stream.html");
	}
}
```

### انظر أيضًا

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url) {#constructor_6}

ينشئ مستند HTML من محتوى [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) مع base-uri محدد يُستخدم لحل مسار الموارد النسبية.

```java
public HTMLDocument(Stream content, Url baseUri)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| content | Stream | محتوى الـ [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) لتحميل المستند به. |
| baseUri | Url | عنوان URI الأساسي للمستند. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يرمي استثناءً إذا كان معامل base-uri فارغًا (null). |

## ملاحظات

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## أمثلة

```java
// إنشاء كائن تدفق ذاكرة
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// اكتب كود HTML إلى كائن الذاكرة
	sw.Write("<p>Hello World! I love HTML!</p>");

	// من المهم ضبط الموضع إلى البداية لأن HTMLDocument يبدأ القراءة بالضبط من الموضع الحالي داخل الدفق
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// تهيئة مستند من المتغير String
	using (var document = new HTMLDocument(mem, "."))
	{
		// احفظ المستند على القرص
		document.Save("load-from-stream.html");
	}
}
```

### انظر أيضًا

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url, Configuration) {#constructor_7}

ينشئ مستند HTML من محتوى [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) مع base-uri محدد وإعدادات تكوين البيئة.

```java
public HTMLDocument(Stream content, Url baseUri, Configuration configuration)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| content | Stream | محتوى الـ [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) لتحميل المستند به. |
| baseUri | Url | عنوان URI الأساسي للمستند. |
| التكوين | التكوين | تكوين البيئة مثل سياسة السكريبتات، ورقة الأنماط المخصصة للمستخدم، إلخ. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يرمي استثناءً إذا كان معامل base-uri فارغًا (null). |

## ملاحظات

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## أمثلة

```java
// إنشاء كائن تدفق ذاكرة
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// اكتب كود HTML إلى كائن الذاكرة
	sw.Write("<p>Hello World! I love HTML!</p>");

	// من المهم ضبط الموضع إلى البداية لأن HTMLDocument يبدأ القراءة بالضبط من الموضع الحالي داخل الدفق
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// تهيئة مستند من المتغير String
	using (var document = new HTMLDocument(mem, "."))
	{
		// احفظ المستند على القرص
		document.Save("load-from-stream.html");
	}
}
```

### انظر أيضًا

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage) {#constructor_2}

ينشئ مستند HTML من كائن [`RequestMessage`](../../../com.aspose.html.net/requestmessage/).

```java
public HTMLDocument(RequestMessage request)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| request | RequestMessage | رسالة الطلب التي تحتوي على [`body`](../../../com.aspose.html.net/requestmessage/content/) مع محتوى المستند. |

## ملاحظات

بحسب التعريف، معالج الرسائل هو فئة تستقبل طلب ويب وتعيد استجابة ويب. بعبارة أخرى، يُستخدم معالج الرسائل لمعالجة طلب خدمة ويب أثناء الإدخال و/أو لمعالجة الاستجابة أثناء الإخراج.

يرجى زيارة [موقع الوثائق](https://docs.aspose.com/html/net/message-handlers/) لرؤية المزيد من السيناريوهات حول كيفية استخدام هذا المُنشئ.

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### انظر أيضًا

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage, Configuration) {#constructor_3}

ينشئ مستند HTML من كائن [RequestMessage](T:com.aspose.html.net.RequestMessage).

```java
public HTMLDocument(RequestMessage request, Configuration configuration)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| request | RequestMessage | رسالة الطلب التي تحتوي على [body](P:com.aspose.html.net.RequestMessage.Content) مع محتوى المستند. |
| التكوين | التكوين | تكوين البيئة مثل سياسة السكريبتات، ورقة الأنماط المخصصة للمستخدم، إلخ. |

## ملاحظات

بحسب التعريف، معالج الرسائل هو فئة تستقبل طلب ويب وتعيد استجابة ويب. بعبارة أخرى، يُستخدم معالج الرسائل لمعالجة طلب خدمة ويب أثناء الإدخال و/أو لمعالجة الاستجابة أثناء الإخراج.

يرجى زيارة [موقع الوثائق](https://docs.aspose.com/html/net/message-handlers/) لرؤية المزيد من السيناريوهات حول كيفية استخدام هذا المُنشئ.

المرجع:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### انظر أيضًا

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
