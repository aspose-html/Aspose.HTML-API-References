---
title: "واجهة ICSSRuleList"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "واجهة com.aspose.html.dom.css.ICSSRuleList. تمثل CSSRuleList مجموعة مرتبة من كائنات CSSRule للقراءة فقط."
type: docs

url: /ar/java/com.aspose.html.dom.css/icssrulelist/
---
## ICSSRuleList interface

تمثل CSSRuleList مجموعة مرتبة من كائنات [`CSSRule`](../icssrule/) للقراءة فقط.

بينما كائن CSSRuleList للقراءة فقط ولا يمكن تعديله مباشرة، يُعتبر كائنًا حيًا، حيث يمكن أن يتغير المحتوى مع مرور الوقت.

لتعديل القواعد الأساسية التي تُرجعها كائنات [`CSSRule`](../icssrule/)، استخدم CSSStyleSheet.insertRule() و CSSStyleSheet.deleteRule()، وهما طريقتان في [`CSSStyleSheet`](../icssstylesheet/).

```java
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssrulelist/item/) يُستخدم لاسترجاع قاعدة CSS بواسطة الطريقة item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList). الترتيب في هذه المجموعة يمثل ترتيب القواعد في ورقة أنماط CSS. إذا كان الفهرس أكبر من أو يساوي عدد القواعد في القائمة، فإنها تُعيد null. |
| [getLength](../../com.aspose.html.dom.css/icssrulelist/length/) خاصية الطول في واجهة `CSSRuleList` تُعيد عدد كائنات [`CSSRule`](../icssrule/) في القائمة. |

### انظر أيضًا

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
