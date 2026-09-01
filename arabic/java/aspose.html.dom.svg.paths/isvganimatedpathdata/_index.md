---
title: "ISVGAnimatedPathData الواجهة"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "com.aspose.html.dom.svg.paths.ISVGAnimatedPathData الواجهة. تدعم الواجهة SVGAnimatedPathData العناصر التي تحتوي على سمة d التي تحمل بيانات مسار SVG وتدعم إمكانية تحريك تلك السمة"
type: docs

url: /ar/java/com.aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

تدعم الواجهة SVGAnimatedPathData العناصر التي لديها السمة ‘d’ التي تحتوي على بيانات مسار SVG، وتدعم إمكانية تحريك تلك السمة.

```java
public interface ISVGAnimatedPathData
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getAnimatedPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) يوفر الوصول إلى المحتويات المتحركة الحالية لسمة ‘d’ في صيغة تتطابق واحدًا لواحد مع صياغة SVG. إذا كانت السمة أو الخاصية المحددة قيد التحريك، فإنه يحتوي على القيمة المتحركة الحالية للسمة أو الخاصية، وكلا من الكائن نفسه ومحتوياته للقراءة فقط. إذا لم تكن السمة أو الخاصية المحددة قيد التحريك حاليًا، فإنه يحتوي على نفس القيمة كما في pathSegList. |
| [getPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) يوفر الوصول إلى المحتويات الأساسية (أي الثابتة) لسمة ‘d’ في صيغة تتطابق واحدًا لواحد مع صياغة SVG. وبالتالي، إذا كانت سمة ‘d’ تحتوي على أمر \"moveto مطلق (M)\" وأمر \"arcto مطلق (A)\", فإن pathSegList سيحتوي على مدخلين: SVG_PATHSEG_MOVETO_ABS و SVG_PATHSEG_ARC_ABS. |

### انظر أيضًا

* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
