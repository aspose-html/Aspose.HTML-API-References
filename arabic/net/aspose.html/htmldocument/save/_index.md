---
title: HTMLDocument.Save
second_title: Aspose.HTML لمرجع .NET API
description: HTMLDocument طريقة. يحفظ المستند في الملف المحلي المحدد بواسطةعنوان url سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور  والذي سيتم إنشاء اسمه على النحو التالي output_file_name  _files .
type: docs
weight: 130
url: /ar/net/aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

يحفظ المستند في الملف المحلي المحدد بواسطة`عنوان url` سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور ، والذي سيتم إنشاء اسمه على النحو التالي: output_file_name + "_files" .

```csharp
public void Save(Url url)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| url | Url | URL المحلي لملف الإخراج. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | أثار إذا كان المحدد`عنوان url` ليس عنوان URL صالحًا للملف المحلي. |

### أنظر أيضا

* class [Url](../../url/)
* class [HTMLDocument](../)
* مساحة الاسم [Aspose.Html](../../htmldocument/)
* المجسم [Aspose.HTML](../../../)

---

## Save(IOutputStorage) {#save}

يحفظ محتوى الوثيقة والموارد في تخزين المخرجات.

```csharp
public void Save(IOutputStorage outputStorage)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStorage | IOutputStorage | تخزين الإخراج[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |

### أنظر أيضا

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [HTMLDocument](../)
* مساحة الاسم [Aspose.Html](../../htmldocument/)
* المجسم [Aspose.HTML](../../../)

---

## Save(string) {#save_10}

يحفظ المستند في الملف المحلي المحدد بواسطة`طريق` سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور ، والذي سيتم إنشاء اسمه على النحو التالي: output_file_name + "_files" .

```csharp
public void Save(string path)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | المسار المحلي لملف الإخراج. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | أثار إذا كان المحدد`طريق` ليس مسار ملف محلي صالحًا. |

### أنظر أيضا

* class [HTMLDocument](../)
* مساحة الاسم [Aspose.Html](../../htmldocument/)
* المجسم [Aspose.HTML](../../../)

---

## Save(string, HTMLSaveFormat) {#save_11}

يحفظ المستند في الملف المحلي المحدد بواسطة`طريق` سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور ، والذي سيتم إنشاء اسمه على النحو التالي: output_file_name + "_files" .

```csharp
public void Save(string path, HTMLSaveFormat saveFormat)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | المسار المحلي لملف الإخراج. |
| saveFormat | HTMLSaveFormat | التنسيق الذي يتم حفظ المستند به. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | أثار إذا كان المحدد`طريق` ليس مسار ملف محلي صالحًا. |

### أنظر أيضا

* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* مساحة الاسم [Aspose.Html](../../htmldocument/)
* المجسم [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

يحفظ المستند في الملف المحلي المحدد بواسطة`عنوان url` سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور ، والذي سيتم إنشاء اسمه على النحو التالي: output_file_name + "_files" .

```csharp
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| url | Url | URL المحلي لملف الإخراج. |
| saveFormat | HTMLSaveFormat | التنسيق الذي يتم حفظ المستند به. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | أثار إذا كان المحدد`عنوان url` ليس عنوان URL صالحًا للملف المحلي. |

### أنظر أيضا

* class [Url](../../url/)
* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* مساحة الاسم [Aspose.Html](../../htmldocument/)
* المجسم [Aspose.HTML](../../../)

---

## Save(IOutputStorage, HTMLSaveFormat) {#save_1}

يحفظ محتوى الوثيقة والموارد في تخزين المخرجات.

```csharp
public void Save(IOutputStorage outputStorage, HTMLSaveFormat saveFormat)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStorage | IOutputStorage | تخزين الإخراج[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveFormat | HTMLSaveFormat | التنسيق الذي يتم حفظ المستند به. |

### أنظر أيضا

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* مساحة الاسم [Aspose.Html](../../htmldocument/)
* المجسم [Aspose.HTML](../../../)

---

## Save(string, HTMLSaveOptions) {#save_12}

يحفظ المستند في الملف المحلي المحدد بواسطة`طريق` سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور ، والذي سيتم إنشاء اسمه على النحو التالي: output_file_name + "_files" .

```csharp
public void Save(string path, HTMLSaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | المسار المحلي لملف الإخراج. |
| saveOptions | HTMLSaveOptions | خيارات حفظ HTML. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | أثار إذا كان المحدد`طريق` ليس مسار ملف محلي صالحًا. |

### أنظر أيضا

* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* مساحة الاسم [Aspose.Html](../../htmldocument/)
* المجسم [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

يحفظ المستند في الملف المحلي المحدد بواسطة`عنوان url` سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور ، والذي سيتم إنشاء اسمه على النحو التالي: output_file_name + "_files" .

```csharp
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| url | Url | URL المحلي لملف الإخراج. |
| saveOptions | HTMLSaveOptions | خيارات حفظ HTML. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | أثار إذا كان المحدد`عنوان url` ليس عنوان URL صالحًا للملف المحلي. |

### أنظر أيضا

* class [Url](../../url/)
* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* مساحة الاسم [Aspose.Html](../../htmldocument/)
* المجسم [Aspose.HTML](../../../)

---

## Save(IOutputStorage, HTMLSaveOptions) {#save_2}

يحفظ محتوى الوثيقة والموارد في تخزين المخرجات.

```csharp
public void Save(IOutputStorage outputStorage, HTMLSaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStorage | IOutputStorage | تخزين الإخراج[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveOptions | HTMLSaveOptions | خيارات حفظ HTML. |

### أنظر أيضا

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* مساحة الاسم [Aspose.Html](../../htmldocument/)
* المجسم [Aspose.HTML](../../../)

---

## Save(string, MarkdownSaveOptions) {#save_13}

يحفظ المستند في الملف المحلي المحدد بواسطة`طريق` سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور ، والذي سيتم إنشاء اسمه على النحو التالي: output_file_name + "_files" .

```csharp
public void Save(string path, MarkdownSaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | المسار المحلي لملف الإخراج. |
| saveOptions | MarkdownSaveOptions | Markdown حفظ الخيارات. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | أثار إذا كان المحدد`طريق` ليس مسار ملف محلي صالحًا. |

### أنظر أيضا

* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* مساحة الاسم [Aspose.Html](../../htmldocument/)
* المجسم [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

يحفظ المستند في الملف المحلي المحدد بواسطة`عنوان url` سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور ، والذي سيتم إنشاء اسمه على النحو التالي: output_file_name + "_files" .

```csharp
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| url | Url | URL المحلي لملف الإخراج. |
| saveOptions | MarkdownSaveOptions | Markdown حفظ الخيارات. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | أثار إذا كان المحدد`عنوان url` ليس عنوان URL صالحًا للملف المحلي. |

### أنظر أيضا

* class [Url](../../url/)
* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* مساحة الاسم [Aspose.Html](../../htmldocument/)
* المجسم [Aspose.HTML](../../../)

---

## Save(IOutputStorage, MarkdownSaveOptions) {#save_3}

يحفظ محتوى الوثيقة والموارد في تخزين المخرجات.

```csharp
public void Save(IOutputStorage outputStorage, MarkdownSaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStorage | IOutputStorage | تخزين الإخراج[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveOptions | MarkdownSaveOptions | Markdown حفظ الخيارات. |

### أنظر أيضا

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* مساحة الاسم [Aspose.Html](../../htmldocument/)
* المجسم [Aspose.HTML](../../../)

---

## Save(string, MHTMLSaveOptions) {#save_14}

يحفظ المستند في الملف المحلي المحدد بواسطة`طريق` سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور ، والذي سيتم إنشاء اسمه على النحو التالي: output_file_name + "_files" .

```csharp
public void Save(string path, MHTMLSaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | المسار المحلي لملف الإخراج. |
| saveOptions | MHTMLSaveOptions | خيارات حفظ MHTML. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | أثار إذا كان المحدد`طريق` ليس مسار ملف محلي صالحًا. |

### أنظر أيضا

* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* مساحة الاسم [Aspose.Html](../../htmldocument/)
* المجسم [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

يحفظ المستند في الملف المحلي المحدد بواسطة`عنوان url` سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور ، والذي سيتم إنشاء اسمه على النحو التالي: output_file_name + "_files" .

```csharp
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| url | Url | URL المحلي لملف الإخراج. |
| saveOptions | MHTMLSaveOptions | خيارات حفظ MHTML. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | أثار إذا كان المحدد`عنوان url` ليس عنوان URL صالحًا للملف المحلي. |

### أنظر أيضا

* class [Url](../../url/)
* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* مساحة الاسم [Aspose.Html](../../htmldocument/)
* المجسم [Aspose.HTML](../../../)

---

## Save(IOutputStorage, MHTMLSaveOptions) {#save_4}

يحفظ محتوى الوثيقة والموارد في تخزين المخرجات.

```csharp
public void Save(IOutputStorage outputStorage, MHTMLSaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStorage | IOutputStorage | تخزين الإخراج[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveOptions | MHTMLSaveOptions | خيارات حفظ MHTML. |

### أنظر أيضا

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* مساحة الاسم [Aspose.Html](../../htmldocument/)
* المجسم [Aspose.HTML](../../../)


