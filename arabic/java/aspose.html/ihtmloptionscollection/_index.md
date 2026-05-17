---
title: "واجهة IHTMLOptionsCollection"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "واجهة com.aspose.html.IHTMLOptionsCollection. HTMLOptionsCollection هي قائمة من العقد تمثل عنصر خيار HTML. يمكن الوصول إلى عقدة فردية إما عبر الفهرس الترتيبي أو عبر اسم العقدة أو سمات المعرف. يُفترض أن المجموعات في DOM HTML حية، مما يعني أنها تُحدَّث تلقائيًا عندما يتغير المستند الأساسي."
type: docs

url: /ar/java/com.aspose.html/ihtmloptionscollection/
---
## IHTMLOptionsCollection interface

تُعد `HTMLOptionsCollection` قائمة من العقد التي تمثل عنصر خيار HTML. يمكن الوصول إلى عقدة فردية إما عبر الفهرس الترتيبي أو عبر سمات العقدة `name` أو `id`. يُفترض أن المجموعات في DOM HTML حية، مما يعني أنها تُحدَّث تلقائيًا عندما يتغيّر المستند الأساسي.

انظر أيضاً إلى [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109). @since DOM Level 2

```java
public interface IHTMLOptionsCollection : IEnumerable<Element>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getItem](../../com.aspose.html/ihtmloptionscollection/item/) يُرجع العنصر رقم الفهرس في المجموعة. إذا كان الفهرس أكبر من أو يساوي عدد العقد في القائمة، فإن هذا يُرجع null. (مؤشرين) |
| [getLength](../../com.aspose.html/ihtmloptionscollection/length/) عدد العقد في القائمة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [namedItem](../../com.aspose.html/ihtmloptionscollection/nameditem/)(String) | الطريقة تُرجع العنصر رقم الفهرس في المجموعة. http://www.w3.org/TR/DOM-Level-2-HTML/html.html#HTMLOptionsCollection-namedItem |

### انظر أيضًا

* class [Element](../../com.aspose.html.dom/element/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
