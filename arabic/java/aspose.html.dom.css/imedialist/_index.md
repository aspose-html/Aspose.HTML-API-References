---
title: "واجهة IMediaList"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "com.aspose.html.dom.css.IMediaList interface. توفر واجهة MediaList تجريدًا لمجموعة مرتبة من الوسائط دون تعريف أو تقييد كيفية تنفيذ هذه المجموعة. القائمة الفارغة هي نفسها القائمة التي تحتوي على جميع الوسائط."
type: docs

url: /ar/java/com.aspose.html.dom.css/imedialist/
---
## IMediaList interface

واجهة MediaList توفر تجريدًا لمجموعة مرتبة من الوسائط، دون تعريف أو تقييد طريقة تنفيذ هذه المجموعة. القائمة الفارغة هي نفسها القائمة التي تحتوي على الوسيط "all".

انظر أيضًا إلى [CSS Object Model (CSSOM) # ](https://www.w3.org/TR/cssom-1/#the-medialist-interface)[MediaList](https://www.w3.org/TR/cssom-1/#the-medialist-interface).

```java
public interface IMediaList : IEnumerable<String>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/imedialist/item/) يجب أن تُعيد طريقة item(index) تسلسلًا لاستعلام الوسائط في مجموعة استعلامات الوسائط المحددة بالفهارس، أو null إذا كان الفهرس أكبر من أو يساوي عدد استعلامات الوسائط في المجموعة. |
| [getLength](../../com.aspose.html.dom.css/imedialist/length/) يجب أن تُعيد خاصية الطول عدد استعلامات الوسائط في مجموعة استعلامات الوسائط. النطاق الصالح للوسائط هو من 0 إلى length-1 شاملًا. |
| [getMediaText](../../com.aspose.html.dom.css/imedialist/mediatext/) أداة تحويل (Stringifier) تُعيد DOMString تمثل MediaList كنص، وتسمح أيضًا بتعيين MediaList جديد. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [appendMedium](../../com.aspose.html.dom.css/imedialist/appendmedium/)(String) | يضيف الوسيط newMedium إلى نهاية القائمة. إذا كان newMedium مستخدمًا بالفعل، يتم إزالته أولاً. |
| [deleteMedium](../../com.aspose.html.dom.css/imedialist/deletemedium/)(String) | يحذف الوسيط المشار إليه بـ oldMedium من القائمة. |

## ملاحظات

ملاحظة: MediaList هي قائمة حية؛ تحديث القائمة باستخدام الخصائص أو الأساليب المذكورة أدناه سيؤثر فورًا على سلوك المستند.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

المرجع

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # medialist](https://drafts.csswg.org/cssom/#medialist) – The CSSOM definition.

## أمثلة

سيسجل التالي في وحدة التحكم تمثيلًا نصيًا لـ MediaList الخاص بأول ورقة أنماط مطبقة على المستند الحالي.

```java
var stylesheets = document.StyleSheets;
var stylesheet = stylesheets[0];
Console.Write(stylesheet.Media.MediaText);
```

### انظر أيضًا

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
