---
title: "ICanvasRenderingContext2D.PutImageData"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة ICanvasRenderingContext2D. ترسم البيانات من كائن ImageData المعطى على الـ bitmap. إذا تم توفير مستطيل غير نظيف، يتم رسم البكسلات فقط من ذلك المستطيل. هذه الطريقة لا تتأثر بمصفوفة تحويل الـ canvas."
type: docs

url: /ar/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(IImageData, double, double) {#putimagedata}

يرسم البيانات من كائن ImageData المعطى على الصورة النقطية. إذا تم توفير مستطيل متسخ، يتم رسم البكسلات الموجودة فقط في ذلك المستطيل. لا تتأثر هذه الطريقة بمصفوفة تحويل القماش.

```java
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| imagedata | IImageData | كائن ImageData يحتوي على مصفوفة قيم البكسل. |
| dx | Double | الموضع الأفقي (الإحداثي x) الذي يتم وضع بيانات الصورة فيه على الـ canvas الهدف. |
| dy | Double | الموضع العمودي (الإحداثي y) الذي يتم وضع بيانات الصورة فيه على الـ canvas الهدف. |

### انظر أيضًا

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## PutImageData(IImageData, double, double, double, double, double, double) {#putimagedata_1}

يرسم البيانات من كائن ImageData المعطى على الصورة النقطية. إذا تم توفير مستطيل متسخ، يتم رسم البكسلات الموجودة فقط في ذلك المستطيل. لا تتأثر هذه الطريقة بمصفوفة تحويل القماش.

```java
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| imagedata | IImageData | كائن ImageData يحتوي على مصفوفة قيم البكسل. |
| dx | Double | الموضع الأفقي (الإحداثي x) الذي يتم وضع بيانات الصورة فيه على الـ canvas الهدف. |
| dy | Double | الموضع العمودي (الإحداثي y) الذي يتم وضع بيانات الصورة فيه على الـ canvas الهدف. |
| dirtyX | Double | الموضع الأفقي (الإحداثي x). إحداثي x للزاوية العلوية اليسرى لبيانات Image الخاصة بك. الافتراضي 0. |
| dirtyY | Double | الموضع العمودي (الإحداثي y). إحداثي y للزاوية العلوية اليسرى لبيانات Image الخاصة بك. الافتراضي 0. |
| dirtyWidth | Double | عرض المستطيل الذي سيتم رسمه. الافتراضي عرض بيانات الصورة. |
| dirtyHeight | Double | ارتفاع المستطيل الذي سيتم رسمه. الافتراضي ارتفاع بيانات الصورة. |

### انظر أيضًا

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
