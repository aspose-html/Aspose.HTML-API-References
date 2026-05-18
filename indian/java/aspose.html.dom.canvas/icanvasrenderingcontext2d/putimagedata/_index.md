---
title: "ICanvasRenderingContext2D.PutImageData"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "ICanvasRenderingContext2D मेथड। दिए गए ImageData ऑब्जेक्ट से डेटा को बिटमैप पर पेंट करता है। यदि एक डर्टी रेक्टेंगल प्रदान किया जाता है तो केवल उस रेक्टेंगल के पिक्सेल पेंट होते हैं। यह मेथड कैनवास ट्रांसफ़ॉर्मेशन मैट्रिक्स से प्रभावित नहीं होता।"
type: docs

url: /hi/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(IImageData, double, double) {#putimagedata}

दिए गए ImageData ऑब्जेक्ट से डेटा को बिटमैप पर पेंट करता है। यदि एक डर्टी आयत प्रदान की जाती है, तो केवल उस आयत के पिक्सेल पेंट होते हैं। यह मेथड कैनवास ट्रांसफ़ॉर्मेशन मैट्रिक्स से प्रभावित नहीं होता।

```java
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| imagedata | IImageData | एक ImageData ऑब्जेक्ट जिसमें पिक्सेल मानों की एरे होती है। |
| dx | Double | हॉरिज़ॉन्टल पोज़िशन (x-कोऑर्डिनेट) जहाँ इमेज डेटा को डेस्टिनेशन कैनवास में रखा जाना है। |
| dy | Double | वर्टिकल पोज़िशन (y-कोऑर्डिनेट) जहाँ इमेज डेटा को डेस्टिनेशन कैनवास में रखा जाना है। |

### संबंधित देखें

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## PutImageData(IImageData, double, double, double, double, double, double) {#putimagedata_1}

दिए गए ImageData ऑब्जेक्ट से डेटा को बिटमैप पर पेंट करता है। यदि एक डर्टी आयत प्रदान की जाती है, तो केवल उस आयत के पिक्सेल पेंट होते हैं। यह मेथड कैनवास ट्रांसफ़ॉर्मेशन मैट्रिक्स से प्रभावित नहीं होता।

```java
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| imagedata | IImageData | एक ImageData ऑब्जेक्ट जिसमें पिक्सेल मानों की एरे होती है। |
| dx | Double | हॉरिज़ॉन्टल पोज़िशन (x-कोऑर्डिनेट) जहाँ इमेज डेटा को डेस्टिनेशन कैनवास में रखा जाना है। |
| dy | Double | वर्टिकल पोज़िशन (y-कोऑर्डिनेट) जहाँ इमेज डेटा को डेस्टिनेशन कैनवास में रखा जाना है। |
| dirtyX | Double | हॉरिज़ॉन्टल पोज़िशन (x-कोऑर्डिनेट)। आपके Image डेटा के टॉप लेफ़्ट कोने का x कोऑर्डिनेट। डिफ़ॉल्ट 0। |
| dirtyY | Double | वर्टिकल पोज़िशन (y-कोऑर्डिनेट)। आपके Image डेटा के टॉप लेफ़्ट कोने का y कोऑर्डिनेट। डिफ़ॉल्ट 0। |
| dirtyWidth | Double | पेंट किए जाने वाले रेक्टेंगल की चौड़ाई। डिफ़ॉल्ट इमेज डेटा की चौड़ाई। |
| dirtyHeight | Double | पेंट किए जाने वाले रेक्टेंगल की ऊँचाई। डिफ़ॉल्ट इमेज डेटा की ऊँचाई। |

### संबंधित देखें

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
