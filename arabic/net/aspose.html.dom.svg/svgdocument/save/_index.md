---
title: SVGDocument.Save
second_title: Aspose.HTML لمرجع .NET API
description: SVGDocument طريقة. يحفظ المستند في الملف المحلي المحدد بواسطةعنوان url سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور  والذي سيتم إنشاء اسمه على النحو التالي output_file_name  _files .
type: docs
weight: 90
url: /ar/net/aspose.html.dom.svg/svgdocument/save/
---
## Save(Url) {#save_3}

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

* class [Url](../../../aspose.html/url/)
* class [SVGDocument](../)
* مساحة الاسم [Aspose.Html.Dom.Svg](../../svgdocument/)
* المجسم [Aspose.HTML](../../../)

---

## Save(string) {#save_6}

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

* class [SVGDocument](../)
* مساحة الاسم [Aspose.Html.Dom.Svg](../../svgdocument/)
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
* class [SVGDocument](../)
* مساحة الاسم [Aspose.Html.Dom.Svg](../../svgdocument/)
* المجسم [Aspose.HTML](../../../)

---

## Save(string, SVGSaveFormat) {#save_7}

يحفظ المستند في الملف المحلي المحدد بواسطة`طريق` سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور ، والذي سيتم إنشاء اسمه على النحو التالي: output_file_name + "_files" .

```csharp
public void Save(string path, SVGSaveFormat saveFormat)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | المسار المحلي لملف الإخراج. |
| saveFormat | SVGSaveFormat | التنسيق الذي يتم حفظ المستند به. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | أثار إذا كان المحدد`طريق` ليس مسار ملف محلي صالحًا. |

### أنظر أيضا

* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* مساحة الاسم [Aspose.Html.Dom.Svg](../../svgdocument/)
* المجسم [Aspose.HTML](../../../)

---

## Save(IOutputStorage, SVGSaveFormat) {#save_1}

يحفظ محتوى الوثيقة والموارد في تخزين المخرجات.

```csharp
public void Save(IOutputStorage outputStorage, SVGSaveFormat saveFormat)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStorage | IOutputStorage | تخزين الإخراج[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveFormat | SVGSaveFormat | التنسيق الذي يتم حفظ المستند به. |

### أنظر أيضا

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* مساحة الاسم [Aspose.Html.Dom.Svg](../../svgdocument/)
* المجسم [Aspose.HTML](../../../)

---

## Save(string, SVGSaveOptions) {#save_8}

يحفظ المستند في الملف المحلي المحدد بواسطة`طريق` سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور ، والذي سيتم إنشاء اسمه على النحو التالي: output_file_name + "_files" .

```csharp
public void Save(string path, SVGSaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | المسار المحلي لملف الإخراج. |
| saveOptions | SVGSaveOptions | خيارات حفظ SVG. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | أثار إذا كان المحدد`طريق` ليس مسار ملف محلي صالحًا. |

### أنظر أيضا

* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* مساحة الاسم [Aspose.Html.Dom.Svg](../../svgdocument/)
* المجسم [Aspose.HTML](../../../)

---

## Save(IOutputStorage, SVGSaveOptions) {#save_2}

يحفظ محتوى الوثيقة والموارد في تخزين المخرجات.

```csharp
public void Save(IOutputStorage outputStorage, SVGSaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputStorage | IOutputStorage | تخزين الإخراج[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveOptions | SVGSaveOptions | خيارات حفظ SVG. |

### أنظر أيضا

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* مساحة الاسم [Aspose.Html.Dom.Svg](../../svgdocument/)
* المجسم [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveFormat) {#save_4}

يحفظ المستند في الملف المحلي المحدد بواسطة`عنوان url` سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور ، والذي سيتم إنشاء اسمه على النحو التالي: output_file_name + "_files" .

```csharp
public void Save(Url url, SVGSaveFormat saveFormat)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| url | Url | URL المحلي لملف الإخراج. |
| saveFormat | SVGSaveFormat | التنسيق الذي يتم حفظ المستند به. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | أثار إذا كان المحدد`عنوان url` ليس عنوان URL صالحًا للملف المحلي. |

### أنظر أيضا

* class [Url](../../../aspose.html/url/)
* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* مساحة الاسم [Aspose.Html.Dom.Svg](../../svgdocument/)
* المجسم [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveOptions) {#save_5}

يحفظ المستند في الملف المحلي المحدد بواسطة`عنوان url` سيتم حفظ جميع الموارد المستخدمة في هذا المستند في إلى المجلد المجاور ، والذي سيتم إنشاء اسمه على النحو التالي: output_file_name + "_files" .

```csharp
public void Save(Url url, SVGSaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| url | Url | URL المحلي لملف الإخراج. |
| saveOptions | SVGSaveOptions | خيارات حفظ SVG. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | أثار إذا كان المحدد`عنوان url` ليس عنوان URL صالحًا للملف المحلي. |

### أنظر أيضا

* class [Url](../../../aspose.html/url/)
* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* مساحة الاسم [Aspose.Html.Dom.Svg](../../svgdocument/)
* المجسم [Aspose.HTML](../../../)


