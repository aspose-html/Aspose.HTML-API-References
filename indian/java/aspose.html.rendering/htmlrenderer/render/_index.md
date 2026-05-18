---
title: "HtmlRenderer.Render"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "HtmlRenderer मेथड। कई HTMLDocuments को विशिष्ट IDevice में रेंडर करने के लिए मेथड परिभाषित करता है"
type: docs

url: /hi/java/com.aspose.html.rendering/htmlrenderer/render/
---
## Render(IDevice, TimeSpan, params HTMLDocument[]) {#render_6}

कई [`HTMLDocument`](../../../com.aspose.html/htmldocument/) को विशिष्ट [`IDevice`](../../idevice/) में रेंडर करने के लिए मेथड परिभाषित करता है।

```java
public void Render(IDevice device, TimeSpan timeout, params HTMLDocument[] sources)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| डिवाइस | IDevice | आउटपुट डिवाइस। |
| timeout | TimeSpan | एक TimeSpan जो प्रतीक्षा करने के मिलिसेकंड की संख्या दर्शाता है, या एक TimeSpan जो -1 मिलिसेकंड दर्शाता है जिससे अनिश्चितकाल तक प्रतीक्षा की जा सके। |
| स्रोत | HTMLDocument[] | रेंडर करने के लिए HTML दस्तावेज़। |

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params HTMLDocument[]) {#render_5}

कई [`HTMLDocument`](../../../com.aspose.html/htmldocument/) को विशिष्ट [`IDevice`](../../idevice/) में रेंडर करने के लिए एक मेथड परिभाषित करता है, ऑपरेशन को रद्द करने के अनुरोध के लिए कैंसलेशन टोकन का उपयोग करता है।

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params HTMLDocument[] sources)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| डिवाइस | IDevice | आउटपुट डिवाइस। |
| cancellationToken | CancellationToken | कार्य के पूर्ण होने की प्रतीक्षा करते समय निरीक्षण करने के लिए एक CancellationToken। |
| स्रोत | HTMLDocument[] | रेंडर करने के लिए HTML दस्तावेज़। |

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
