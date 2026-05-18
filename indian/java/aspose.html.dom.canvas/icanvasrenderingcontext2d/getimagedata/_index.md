---
title: "ICanvasRenderingContext2D.GetImageData"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "ICanvasRenderingContext2D मेथड। एक ImageData ऑब्जेक्ट लौटाता है जो कैनवास के उस क्षेत्र के अंतर्निहित पिक्सेल डेटा को दर्शाता है, जिसे वह आयत द्वारा निर्दिष्ट किया गया है जो sx, sy से शुरू होती है और जिसकी चौड़ाई sw और ऊँचाई sh है। यह मेथड कैनवास ट्रांसफ़ॉर्मेशन मैट्रिक्स से प्रभावित नहीं होता।"
type: docs

url: /hi/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/
---
## ICanvasRenderingContext2D.GetImageData method

एक ImageData ऑब्जेक्ट लौटाता है जो कैनवास के उस क्षेत्र के अंतर्निहित पिक्सेल डेटा को दर्शाता है, जिसे आयत द्वारा दर्शाया गया है जो (sx, sy) से शुरू होती है और जिसकी चौड़ाई sw और ऊँचाई sh है। यह मेथड कैनवास ट्रांसफ़ॉर्मेशन मैट्रिक्स से प्रभावित नहीं होता।

```java
public IImageData GetImageData(double sx, double sy, double sw, double sh)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| sx | Double | उस आयत के ऊपरी बाएँ कोने का x निर्देशांक जिससे ImageData निकाला जाएगा। |
| sy | Double | उस आयत के ऊपरी बाएँ कोने का y निर्देशांक जिससे ImageData निकाला जाएगा। |
| sw | Double | उस आयत की चौड़ाई जिससे ImageData निकाला जाएगा। |
| sh | Double | उस आयत की ऊँचाई जिससे ImageData निकाला जाएगा। |

### रिटर्न वैल्यू

कैनवास के दिए गए आयत के लिए छवि डेटा युक्त एक ImageData ऑब्जेक्ट।

### संबंधित देखें

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
