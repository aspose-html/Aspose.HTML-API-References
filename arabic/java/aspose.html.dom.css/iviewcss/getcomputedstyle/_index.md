---
title: "IViewCSS.GetComputedStyle"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة IViewCSS. طريقة IViewCSS.getComputedStyle تُعيد كائنًا يحتوي على قيم جميع خصائص CSS لعنصر بعد تطبيق أوراق الأنماط النشطة وحل أي حسابات أساسية قد تحتويها تلك القيم."
type: docs

url: /ar/java/com.aspose.html.dom.css/iviewcss/getcomputedstyle/
---
## GetComputedStyle(Element) {#getcomputedstyle}

طريقة IViewCSS.getComputedStyle() تُعيد كائنًا يحتوي على قيم جميع خصائص CSS لعنصر، بعد تطبيق أوراق الأنماط النشطة وحل أي حساب أساسي قد تحتويه تلك القيم.

يمكن الوصول إلى قيم خصائص CSS الفردية عبر واجهات برمجة التطبيقات (APIs) التي يوفرها الكائن، أو عبر الفهرسة باستخدام أسماء خصائص CSS.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| element | Element | الـ [`Element`](../../../com.aspose.html.dom/element/) الذي يُراد الحصول على النمط المحسوب له. لا يمكن أن تكون هذه المعلمة null. |

### قيمة الإرجاع

النمط المُعاد هو كائن [`CSSStyleDeclaration`](../../icssstyledeclaration/) حي، يتم تحديثه تلقائيًا عندما تتغير أنماط العنصر.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| TypeError | إذا كان الكائن المُمرَّر ليس عنصرًا أو أن pseudoElt ليس مُحدِّدًا صالحًا لعنصر زائف. |

## ملاحظات

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

المرجع

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### انظر أيضًا

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

---

## GetComputedStyle(Element, String) {#getcomputedstyle_1}

طريقة IViewCSS.getComputedStyle() تُعيد كائنًا يحتوي على قيم جميع خصائص CSS لعنصر، بعد تطبيق أوراق الأنماط النشطة وحل أي حساب أساسي قد تحتويه تلك القيم.

يمكن الوصول إلى قيم خصائص CSS الفردية عبر واجهات برمجة التطبيقات (APIs) التي يوفرها الكائن، أو عبر الفهرسة باستخدام أسماء خصائص CSS.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element, String pseudoElement)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| element | Element | الـ [`Element`](../../../com.aspose.html.dom/element/) الذي يُراد الحصول على النمط المحسوب له. لا يمكن أن تكون هذه المعلمة null. |
| pseudoElement | String | سلسلة نصية تحدد العنصر الزائف للمطابقة. تُهمل (أو تكون null) للعناصر الحقيقية. |

### قيمة الإرجاع

النمط المُعاد هو كائن [`CSSStyleDeclaration`](../../icssstyledeclaration/) حي، يتم تحديثه تلقائيًا عندما تتغير أنماط العنصر.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| TypeError | إذا كان الكائن المُمرَّر ليس عنصرًا أو أن pseudoElt ليس مُحدِّدًا صالحًا لعنصر زائف. |

## ملاحظات

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

المرجع

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### انظر أيضًا

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
