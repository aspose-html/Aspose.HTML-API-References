---
title: "SVGDocument.Save"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة SVGDocument. تحفظ المستند إلى ملف محلي محدد بواسطة url. جميع الموارد المستخدمة في هذا المستند سيتم حفظها في مجلد مجاور يُنشأ اسمه كـ output_file_name _files"
type: docs

url: /ar/java/com.aspose.html.dom.svg/svgdocument/save/
---
## Save(Url) {#save_3}

يحفظ المستند إلى ملف محلي محدد بالعنوان `url`. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، يُنشأ اسمه كالتالي: اسم_ملف_الإخراج + \"_files\".

```java
public void Save(Url url)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | عنوان URL المحلي لملف الإخراج. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يتم رفع الاستثناء إذا كان `url` المحدد ليس عنوان URL ملف محلي صالح. |

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_6}

يحفظ المستند إلى ملف محلي محدد بالمسار `path`. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، يُنشأ اسمه كالتالي: اسم_ملف_الإخراج + \"_files\".

```java
public void Save(String path)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار المحلي لملف الإخراج. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يتم رفع الاستثناء إذا كان `path` المحدد ليس مسار ملف محلي صالح. |

### انظر أيضًا

* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
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
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String, SVGSaveFormat) {#save_7}

يحفظ المستند إلى ملف محلي محدد بالمسار `path`. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، يُنشأ اسمه كالتالي: اسم_ملف_الإخراج + \"_files\".

```java
public void Save(String path, SVGSaveFormat saveFormat)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار المحلي لملف الإخراج. |
| saveFormat | SVGSaveFormat | الصيغة التي يُحفظ بها المستند. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يتم رفع الاستثناء إذا كان `path` المحدد ليس مسار ملف محلي صالح. |

### انظر أيضًا

* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, SVGSaveFormat) {#save_1}

يحفظ محتوى المستند والموارد باستخدام [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, SVGSaveFormat saveFormat)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| resourceHandler | ResourceHandler | معالج الموارد [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveFormat | SVGSaveFormat | الصيغة التي يُحفظ بها المستند. |

### انظر أيضًا

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String, SVGSaveOptions) {#save_8}

يحفظ المستند إلى ملف محلي محدد بالمسار `path`. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، يُنشأ اسمه كالتالي: اسم_ملف_الإخراج + \"_files\".

```java
public void Save(String path, SVGSaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار المحلي لملف الإخراج. |
| saveOptions | SVGSaveOptions | خيارات حفظ SVG. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يتم رفع الاستثناء إذا كان `path` المحدد ليس مسار ملف محلي صالح. |

### انظر أيضًا

* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, SVGSaveOptions) {#save_2}

يحفظ محتوى المستند والموارد باستخدام [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, SVGSaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| resourceHandler | ResourceHandler | معالج الموارد [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | SVGSaveOptions | خيارات حفظ SVG. |

### انظر أيضًا

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveFormat) {#save_4}

يحفظ المستند إلى ملف محلي محدد بالعنوان `url`. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، يُنشأ اسمه كالتالي: اسم_ملف_الإخراج + \"_files\".

```java
public void Save(Url url, SVGSaveFormat saveFormat)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | عنوان URL المحلي لملف الإخراج. |
| saveFormat | SVGSaveFormat | الصيغة التي يُحفظ بها المستند. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يتم رفع الاستثناء إذا كان `url` المحدد ليس عنوان URL ملف محلي صالح. |

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveOptions) {#save_5}

يحفظ المستند إلى ملف محلي محدد بالعنوان `url`. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، يُنشأ اسمه كالتالي: اسم_ملف_الإخراج + \"_files\".

```java
public void Save(Url url, SVGSaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | عنوان URL المحلي لملف الإخراج. |
| saveOptions | SVGSaveOptions | خيارات حفظ SVG. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يتم رفع الاستثناء إذا كان `url` المحدد ليس عنوان URL ملف محلي صالح. |

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
