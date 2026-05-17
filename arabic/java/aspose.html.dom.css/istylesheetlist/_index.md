---
title: "واجهة IStyleSheetList"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "واجهة com.aspose.html.dom.css.IStyleSheetList. تمثل واجهة StyleSheetList قائمة من كائنات CSSStyleSheet. يمكن إرجاع نسخة من هذا الكائن عبر Document.styleSheets"
type: docs

url: /ar/java/com.aspose.html.dom.css/istylesheetlist/
---
## IStyleSheetList interface

واجهة StyleSheetList تمثل قائمة من كائنات [`CSSStyleSheet`](../icssstylesheet/). يمكن إرجاع نسخة من هذا الكائن عبر [`Document.styleSheets`](../../com.aspose.html.dom/document/stylesheets/).

مؤشرات الخصائص المدعومة للكائن هي الأرقام في النطاق من الصفر إلى واحد أقل من عدد أوراق الأنماط CSS الممثلة في المجموعة. إذا لم توجد مثل هذه الأوراق، فلا توجد مؤشرات خصائص مدعومة.

```java
public interface IStyleSheetList : IEnumerable<ICSSStyleSheet>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/istylesheetlist/item/) يجب أن تُعيد طريقة item(index) العنصر رقم index من [`CSS style sheet`](../icssstylesheet/) في المجموعة. إذا لم يكن هناك كائن رقم index في المجموعة، يجب أن تُعيد الطريقة null. |
| [getLength](../../com.aspose.html.dom.css/istylesheetlist/length/) يجب أن تُعيد سمة length عدد أوراق الأنماط CSS الممثلة في المجموعة. النطاق الصالح لمؤشرات أوراق الأنماط الفرعية هو من 0 إلى length-1 شاملًا. |

## ملاحظات

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

المرجع

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # stylesheetlist](https://drafts.csswg.org/cssom/#stylesheetlist) – The CSSOM definition.

### انظر أيضًا

* interface [ICSSStyleSheet](../icssstylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
