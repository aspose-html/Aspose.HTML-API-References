---
title: "IStyleSheet.ParentStyleSheet"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "خاصية IStyleSheet. للغات أوراق الأنماط التي تدعم مفهوم تضمين أوراق الأنماط تمثّل هذه الخاصية ورقة الأنماط المضمنة إذا وجدت. إذا كانت ورقة الأنماط ورقة أنماط عليا أو إذا كانت لغة ورقة الأنماط لا تدعم التضمين فإن قيمة هذه الخاصية تكون null."
type: docs

url: /ar/java/com.aspose.html.dom.css/istylesheet/parentstylesheet/
---
## IStyleSheet.ParentStyleSheet property

للغات أوراق الأنماط التي تدعم مفهوم تضمين أوراق الأنماط، تمثّل هذه الخاصية ورقة الأنماط المضمنة، إذا وجدت. إذا كانت ورقة الأنماط ورقة أنماط عليا، أو إذا كانت لغة ورقة الأنماط لا تدعم التضمين، تكون قيمة هذه الخاصية null.

```java
public IStyleSheet ParentStyleSheet { get; }
```

### Property Value

يجب أن تُعيد خاصية parentStyleSheet ورقة الأنماط [`CSS style sheet`](../../icssstylesheet/) الأصلية.

## ملاحظات

تُعيد هذه الخاصية null إذا كانت ورقة الأنماط الحالية ورقة أنماط عليا أو إذا لم يكن تضمين أوراق الأنماط مدعومًا.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

المرجع

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-parentstylesheet](https://drafts.csswg.org/cssom/#dom-stylesheet-parentstylesheet) – The CSSOM definition.

### انظر أيضًا

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
