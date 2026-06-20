---
title: "Node.Normalize"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة Node. تُضع جميع عقد Text في العمق الكامل للشجرة الفرعية تحت هذا Node بما في ذلك عقد السمات في صيغة طبيعية حيث يقتصر الفصل بين عقد Text على البنية فقط مثل العناصر والتعليقات وتعليمات المعالجة وأقسام CDATA وإشارات الكيان. أي لا توجد عقد Text متجاورة ولا عقد Text فارغة. يمكن استخدام ذلك لضمان أن عرض DOM للمستند هو نفسه كما لو تم حفظه وإعادة تحميله، وهو مفيد عندما تُستخدم عمليات مثل عمليات البحث XPointer التي تعتمد على بنية شجرة المستند المحددة. إذا كان معامل normalize-characters لكائن DOMConfiguration المرتبط بـ Node.ownerDocument صحيحًا، فإن هذه الطريقة ستقوم أيضًا بتطبيع أحرف عقد Text بالكامل."
type: docs

url: /ar/java/com.aspose.html.dom/node/normalize/
---
## Node.Normalize method

توضع جميع عقد [`Text`](../../text/) في العمق الكامل للشجرة الفرعية تحت هذا Node، بما في ذلك عقد السمات، في صيغة "طبيعية" حيث يقتصر الفصل بين عقد [`Text`](../../text/) على البنية فقط (مثل [`elements`](../../element/)، [`comments`](../../comment/)، [`processing instructions`](../../processinginstruction/)، [`CDATA sections`](../../cdatasection/)، و[`entity references`](../../entityreference/)). أي لا توجد عقد Text متجاورة ولا عقد Text فارغة. يمكن استخدام ذلك لضمان أن عرض DOM للمستند هو نفسه كما لو تم حفظه وإعادة تحميله، وهو مفيد عندما تُستخدم عمليات (مثل عمليات البحث XPointer [XPointer]) التي تعتمد على بنية شجرة المستند المحددة. إذا كان معامل "normalize-characters" لكائن [`DOMConfiguration`](../../../com.aspose.html/configuration/) المرتبط بـ [`Node.ownerDocument`](../ownerdocument/) صحيحًا، فإن هذه الطريقة ستقوم أيضًا بتطبيع أحرف عقد Text بالكامل.

```java
public void Normalize()
```

### انظر أيضًا

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
