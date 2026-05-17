---
title: "ISVGAnimatedPathData واجهة"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "com.aspose.html.dom.svg.paths.ISVGAnimatedPathData واجهة. تدعم واجهة SVGAnimatedPathData العناصر التي لديها سمة d التي تحتوي على بيانات مسار SVG وتدعم إمكانية تحريك تلك السمة"
type: docs

url: /ar/java/com.aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

واجهة SVGAnimatedPathData تدعم العناصر التي لديها سمة ‘d’ التي تحتوي على بيانات مسار SVG، وتدعم القدرة على تحريك تلك السمة.

```java
public interface ISVGAnimatedPathData
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getAnimatedPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) يوفر الوصول إلى المحتويات المتحركة الحالية لسمة ‘d’ في صيغة تتطابق واحدًا لواحد مع صياغة SVG. إذا كانت السمة أو الخاصية المحددة يتم تحريكها، فإنها تحتوي على القيمة المتحركة الحالية للسمة أو الخاصية، وكلا من الكائن نفسه ومحتوياته للقراءة فقط. إذا لم تكن السمة أو الخاصية المحددة يتم تحريكها حاليًا، فإنها تحتوي على نفس قيمة pathSegList. |
| [getPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) يوفر الوصول إلى المحتويات الأساسية (أي الثابتة) لسمة ‘d’ في صيغة تتطابق واحدًا لواحد مع صياغة SVG. وبالتالي، إذا كان لسمة ‘d’ أمر "moveto مطلق (M)" وأمر "arcto مطلق (A)"، فإن pathSegList سيحتوي على مدخلين: SVG_PATHSEG_MOVETO_ABS و SVG_PATHSEG_ARC_ABS. |

### انظر أيضًا

* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
