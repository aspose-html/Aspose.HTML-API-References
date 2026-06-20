---
title: "ICanvasRenderingContext2D.FillText"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة ICanvasRenderingContext2D. ترسم وتملأ نصًا معينًا في الموضع xy المحدد."
type: docs

url: /ar/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/
---
## FillText(String, double, double) {#filltext}

يرسم (يملأ) نصًا معينًا عند الموضع (x,y) المحدد.

```java
public void FillText(String text, double x, double y)
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

## FillText(String, double, double, double) {#filltext_1}

يرسم (يملأ) نصًا معينًا عند الموضع (x,y) المحدد.

```java
public void FillText(String text, double x, double y, double maxWidth)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| text | String | النص المراد رسمه باستخدام الخط الحالي، وخصائص textAlign، textBaseline، واتجاه الكتابة. |
| x | Double | محور x للإحداثيات لنقطة بدء النص. |
| y | Double | محور y للإحداثيات لنقطة بدء النص. |
| maxWidth | Double | العرض الأقصى للرسم. إذا تم تحديده، وكان النص محسوبًا أنه أوسع من هذا العرض، يتم تعديل الخط لاستخدام خط أكثر تكثيفًا أفقيًا (إذا كان متاحًا أو إذا كان يمكن توليد خط مقروء بشكل معقول عن طريق تكبير الخط الحالي أفقيًا) أو يتم استخدام خط أصغر. |

### انظر أيضًا

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
