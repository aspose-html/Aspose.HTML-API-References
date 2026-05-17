---
title: "ICanvasRenderingContext2D.PutImageData"
second_title: "مرجع API لـ Aspose.HTML for Java"
description: "طريقة ICanvasRenderingContext2D. ترسم البيانات من كائن ImageData المعطى على صورة البت. إذا تم توفير مستطيل غير نظيف، يتم رسم البكسلات فقط من ذلك المستطيل. هذه الطريقة لا تتأثر بمصفوفة تحويل الكانفاس."
type: docs

url: /ar/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(IImageData, double, double) {#putimagedata}

يرسم البيانات من كائن ImageData المحدد على الخريطة النقطية. إذا تم توفير مستطيل متسخ، يتم رسم البكسلات فقط من ذلك المستطيل. لا تتأثر هذه الطريقة بمصفوفة تحويل اللوحة.

```java
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| imagedata | IImageData | كائن ImageData يحتوي على مصفوفة قيم البكسل. |
| dx | Double | الموضع الأفقي (الإحداثي x) الذي يتم وضع بيانات الصورة فيه على كانفاس الوجهة. |
| dy | Double | الموضع العمودي (الإحداثي y) الذي يتم وضع بيانات الصورة فيه على كانفاس الوجهة. |

### انظر أيضًا

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## PutImageData(IImageData, double, double, double, double, double, double) {#putimagedata_1}

يرسم البيانات من كائن ImageData المحدد على الخريطة النقطية. إذا تم توفير مستطيل متسخ، يتم رسم البكسلات فقط من ذلك المستطيل. لا تتأثر هذه الطريقة بمصفوفة تحويل اللوحة.

```java
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| imagedata | IImageData | كائن ImageData يحتوي على مصفوفة قيم البكسل. |
| dx | Double | الموضع الأفقي (الإحداثي x) الذي يتم وضع بيانات الصورة فيه على كانفاس الوجهة. |
| dy | Double | الموضع العمودي (الإحداثي y) الذي يتم وضع بيانات الصورة فيه على كانفاس الوجهة. |
| dirtyX | Double | الموضع الأفقي (الإحداثي x). إحداثي x للزاوية العلوية اليسرى لبيانات الصورة الخاصة بك. الافتراضي 0. |
| dirtyY | Double | الموضع العمودي (الإحداثي y). إحداثي y للزاوية العلوية اليسرى لبيانات الصورة الخاصة بك. الافتراضي 0. |
| dirtyWidth | Double | عرض المستطيل الذي سيتم رسمه. الافتراضي عرض بيانات الصورة. |
| dirtyHeight | Double | ارتفاع المستطيل الذي سيتم رسمه. الافتراضي ارتفاع بيانات الصورة. |

### انظر أيضًا

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
