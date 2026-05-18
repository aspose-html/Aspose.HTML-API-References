---
title: "SvgRenderer.Render"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "SvgRenderer मेथड। कई SVGDocuments को विशिष्ट IDevice में रेंडर करने के लिए मेथड को परिभाषित करता है। रेंडरिंग तब की जाएगी जब संसाधनों को लोड करने के लिए कोई नेटवर्क ऑपरेशन, सक्रिय टाइमर, एनीमेशन टास्क नहीं हों या निर्दिष्ट टाइमआउट समाप्त हो चुका हो।"
type: docs

url: /hi/java/com.aspose.html.rendering/svgrenderer/render/
---
## Render(IDevice, TimeSpan, params SVGDocument[]) {#render_6}

कई [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को विशिष्ट [`IDevice`](../../idevice/) में रेंडर करने के लिए मेथड को परिभाषित करता है। रेंडरिंग तब की जाएगी जब संसाधनों को लोड करने के लिए कोई नेटवर्क ऑपरेशन, सक्रिय टाइमर, एनीमेशन टास्क नहीं हों या निर्दिष्ट टाइमआउट समाप्त हो चुका हो।

```java
public void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| डिवाइस | IDevice | आउटपुट डिवाइस। |
| timeout | TimeSpan | एक TimeSpan जो प्रतीक्षा करने के मिलिसेकंड की संख्या दर्शाता है, या एक TimeSpan जो -1 मिलिसेकंड दर्शाता है जिससे अनिश्चितकाल तक प्रतीक्षा की जा सके। |
| दस्तावेज़ | SVGDocument[] | रेंडर करने के लिए दस्तावेज़। |

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params SVGDocument[]) {#render_5}

कई [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) को विशिष्ट [`IDevice`](../../idevice/) में रेंडर करने के लिए एक मेथड को परिभाषित करता है, ऑपरेशन को रद्द करने के लिए कैंसलेशन टोकन का उपयोग करते हुए।

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| डिवाइस | IDevice | आउटपुट डिवाइस। |
| cancellationToken | CancellationToken | टास्क के पूरा होने की प्रतीक्षा करते समय देखे जाने वाला कैंसलेशन टोकन। |
| स्रोत | SVGDocument[] | रेंडर करने के लिए SVG दस्तावेज़। |

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
