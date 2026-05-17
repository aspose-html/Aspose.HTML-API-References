---
title: "Node.Normalize"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة Node. تُضع جميع عقد `Text` في العمق الكامل للشجرة الفرعية تحت هذا الـNode بما في ذلك عقد السمات في صيغة طبيعية حيث يفرق فقط البنية مثل العناصر والتعليقات وتعليمات المعالجة وأقسام CDATA وإشارات الكيانات بين عقد `Text`، أي لا توجد عقد `Text` متجاورة ولا عقد `Text` فارغة. يمكن استخدام ذلك لضمان أن عرض DOM للمستند هو نفسه كما لو تم حفظه وإعادة تحميله، وهو مفيد عندما تُستخدم عمليات مثل عمليات البحث XPointer التي تعتمد على بنية شجرة المستند المحددة. إذا كان معامل `normalize-characters` لكائن `DOMConfiguration` المرتبط بـ`Node.ownerDocument` صحيحًا، فإن هذه الطريقة ستقوم أيضًا بتطبيع أحرف عقد `Text` بالكامل."
type: docs

url: /ar/java/com.aspose.html.dom/node/normalize/
---
## Node.Normalize method

تضع جميع عقد [`Text`](../../text/) في العمق الكامل للشجرة الفرعية تحت هذا الـNode، بما في ذلك عقد السمات، في صيغة "طبيعية" حيث تفصل فقط البنية (مثل [`elements`](../../element/)، [`comments`](../../comment/)، [`processing instructions`](../../processinginstruction/)، [`CDATA sections`](../../cdatasection/)، و[`entity references`](../../entityreference/)) بين عقد [`Text`](../../text/)، أي لا توجد عقد `Text` متجاورة ولا عقد `Text` فارغة. يمكن استخدام ذلك لضمان أن عرض DOM للمستند هو نفسه كما لو تم حفظه وإعادة تحميله، وهو مفيد عندما تُستخدم عمليات (مثل عمليات البحث XPointer [XPointer]) التي تعتمد على بنية شجرة المستند المحددة. إذا كان معامل "normalize-characters" لكائن [`DOMConfiguration`](../../../com.aspose.html/configuration/) المرتبط بـ[`Node.ownerDocument`](../ownerdocument/) صحيحًا، فإن هذه الطريقة ستقوم أيضًا بتطبيع أحرف عقد `Text` بالكامل.

```java
public void Normalize()
```

### انظر أيضًا

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
