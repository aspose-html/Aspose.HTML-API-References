---
title: "ICanvasRenderingContext2D.Clip"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "ICanvasRenderingContext2D मेथड। वर्तमान क्लिपिंग क्षेत्र और पाथ द्वारा वर्णित क्षेत्र के बीच इंटरसेक्शन की गणना करके एक नया क्लिपिंग क्षेत्र बनाता है, जिसमें नॉन-ज़ीरो विंडिंग नंबर नियम का उपयोग किया जाता है। खुले सबपाथ को क्लिपिंग क्षेत्र की गणना करते समय निहित रूप से बंद किया जाना चाहिए बिना वास्तविक सबपाथ को प्रभावित किए। नया क्लिपिंग क्षेत्र वर्तमान क्लिपिंग क्षेत्र को प्रतिस्थापित करता है।"
type: docs

url: /hi/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/
---
## Clip() {#clip}

नॉन-ज़ीरो विंडिंग नंबर नियम का उपयोग करके वर्तमान क्लिपिंग रीजन और पाथ द्वारा वर्णित क्षेत्र के इंटरसेक्शन की गणना करके एक नया क्लिपिंग रीजन बनाता है। क्लिपिंग रीजन की गणना करते समय खुले सबपाथ को अप्रत्यक्ष रूप से बंद किया जाना चाहिए, बिना वास्तविक सबपाथ को प्रभावित किए। नया क्लिपिंग रीजन वर्तमान क्लिपिंग रीजन को प्रतिस्थापित करता है।

```java
public void Clip()
```

### संबंधित देखें

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(CanvasFillRule) {#clip_1}

नॉन-ज़ीरो विंडिंग नंबर नियम का उपयोग करके वर्तमान क्लिपिंग रीजन और पाथ द्वारा वर्णित क्षेत्र के इंटरसेक्शन की गणना करके एक नया क्लिपिंग रीजन बनाता है। क्लिपिंग रीजन की गणना करते समय खुले सबपाथ को अप्रत्यक्ष रूप से बंद किया जाना चाहिए, बिना वास्तविक सबपाथ को प्रभावित किए। नया क्लिपिंग रीजन वर्तमान क्लिपिंग रीजन को प्रतिस्थापित करता है।

```java
public void Clip(CanvasFillRule fillRule)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| fillRule | CanvasFillRule | वह एल्गोरिद्म जिसके द्वारा यह निर्धारित किया जाता है कि कोई बिंदु पाथ के अंदर है या बाहर। |

### संबंधित देखें

* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Clip(Path2D, CanvasFillRule) {#clip_2}

नॉन-ज़ीरो विंडिंग नंबर नियम का उपयोग करके वर्तमान क्लिपिंग रीजन और पाथ द्वारा वर्णित क्षेत्र के इंटरसेक्शन की गणना करके एक नया क्लिपिंग रीजन बनाता है। क्लिपिंग रीजन की गणना करते समय खुले सबपाथ को अप्रत्यक्ष रूप से बंद किया जाना चाहिए, बिना वास्तविक सबपाथ को प्रभावित किए। नया क्लिपिंग रीजन वर्तमान क्लिपिंग रीजन को प्रतिस्थापित करता है।

```java
public void Clip(Path2D path, CanvasFillRule fillRule)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| पथ | Path2D | क्लिप करने के लिए एक Path2D पाथ। |
| fillRule | CanvasFillRule | वह एल्गोरिद्म जिससे निर्धारित किया जाता है कि बिंदु पथ के अंदर है या बाहर। |

### संबंधित देखें

* class [Path2D](../../path2d/)
* enum [CanvasFillRule](../../canvasfillrule/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
