---
title: "ICanvasRenderingContext2D.StrokeText"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة ICanvasRenderingContext2D. ترسم حدودًا لنص معين في الموضع x y المحدد."
type: docs

url: /ar/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/
---
## StrokeText(String, double, double) {#stroketext}

يرسم (يرسم حدود) نصًا معينًا عند الموضع (x, y) المحدد.

```java
public void StrokeText(String text, double x, double y)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| text | String | النص المراد رسمه باستخدام الخط الحالي، وخصائص textAlign، textBaseline، واتجاه الكتابة. |
| x | Double | محور x للإحداثيات لنقطة بدء النص. |
| y | Double | محور y للإحداثيات لنقطة بدء النص. |

### انظر أيضًا

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## StrokeText(String, double, double, double?) {#stroketext_1}

يرسم (يرسم حدود) نصًا معينًا عند الموضع (x, y) المحدد.

```java
public void StrokeText(String text, double x, double y, double? maxWidth)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| text | String | النص المراد رسمه باستخدام الخط الحالي، وخصائص textAlign، textBaseline، واتجاه الكتابة. |
| x | Double | محور x للإحداثيات لنقطة بدء النص. |
| y | Double | محور y للإحداثيات لنقطة بدء النص. |
| maxWidth | Nullable`1 | العرض الأقصى للرسم. إذا تم تحديده، وكان النص محسوبًا أنه أوسع من هذا العرض، يتم تعديل الخط لاستخدام خط أكثر تكثيفًا أفقيًا (إذا كان متاحًا أو إذا كان يمكن توليد خط مقروء بشكل معقول عن طريق تكبير الخط الحالي أفقيًا) أو يتم استخدام خط أصغر. |

### انظر أيضًا

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
