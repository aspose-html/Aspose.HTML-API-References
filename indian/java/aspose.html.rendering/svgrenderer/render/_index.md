---
title: "SvgRenderer.Render"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "SvgRenderer method. कई SVGDocuments को विशिष्ट IDevice में रेंडर करने के लिए विधि को परिभाषित करता है। रेंडरिंग तब की जाएगी जब संसाधनों को लोड करने के लिए कोई नेटवर्क ऑपरेशन, सक्रिय टाइमर, एनीमेशन टास्क न हों या निर्दिष्ट टाइमआउट समाप्त हो गया हो।"
type: docs

url: /hi/java/com.aspose.html.rendering/svgrenderer/render/
---
## Render(IDevice, TimeSpan, params SVGDocument[]) {#render_6}

कई [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s को विशिष्ट [`IDevice`](../../idevice/) में रेंडर करने के लिए विधि को परिभाषित करता है। रेंडरिंग तब की जाएगी जब संसाधनों को लोड करने के लिए कोई नेटवर्क ऑपरेशन, सक्रिय टाइमर, एनीमेशन टास्क न हों या निर्दिष्ट टाइमआउट समाप्त हो गया हो।

```java
public void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| device | IDevice | आउटपुट डिवाइस। |
| timeout | TimeSpan | एक TimeSpan जो प्रतीक्षा करने के लिए मिलीसेकंड की संख्या दर्शाता है, या एक TimeSpan जो -1 मिलीसेकंड दर्शाता है अनिश्चितकाल तक प्रतीक्षा करने के लिए। |
| दस्तावेज़ | SVGDocument[] | रेंडर करने के लिए दस्तावेज़। |

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params SVGDocument[]) {#render_5}

कई [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)s को विशिष्ट [`IDevice`](../../idevice/) में रेंडर करने के लिए एक विधि को परिभाषित करता है, ऑपरेशन को रद्द करने के अनुरोध के लिए एक कैंसलेशन टोकन का उपयोग करते हुए।

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| device | IDevice | आउटपुट डिवाइस। |
| cancellationToken | CancellationToken | कार्य के पूर्ण होने की प्रतीक्षा करते समय निरीक्षण करने के लिए एक कैंसलेशन टोकन। |
| स्रोत | SVGDocument[] | रेंडर करने के लिए SVG दस्तावेज़। |

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
