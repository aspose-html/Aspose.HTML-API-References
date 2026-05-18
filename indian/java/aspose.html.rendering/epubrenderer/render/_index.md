---
title: "EpubRenderer.Render"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "EpubRenderer मेथड। कई EPub Streams को विशिष्ट IDevice में रेंडर करने के लिए मेथड को परिभाषित करता है। रेंडरिंग तब की जाएगी जब कोई नेटवर्क ऑपरेशन, संसाधन, सक्रिय टाइमर, एनीमेशन टास्क नहीं हों या निर्दिष्ट टाइमआउट समाप्त हो गया हो।"
type: docs

url: /hi/java/com.aspose.html.rendering/epubrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

कई EPub Streams को विशिष्ट [`IDevice`](../../idevice/) में रेंडर करने के लिए मेथड को परिभाषित करता है। रेंडरिंग तब की जाएगी जब कोई नेटवर्क ऑपरेशन, संसाधन, सक्रिय टाइमर, एनीमेशन टास्क नहीं हों या निर्दिष्ट टाइमआउट समाप्त हो गया हो।

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| डिवाइस | IDevice | आउटपुट डिवाइस। |
| timeout | TimeSpan | एक TimeSpan जो प्रतीक्षा करने के मिलिसेकंड की संख्या दर्शाता है, या एक TimeSpan जो -1 मिलिसेकंड दर्शाता है जिससे अनिश्चितकाल तक प्रतीक्षा की जा सके। |
| दस्तावेज़ | Stream[] | रेंडर करने के लिए दस्तावेज़। |

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

कई EPub दस्तावेज़ों को विशिष्ट [`IDevice`](../../idevice/) में रेंडर करने के लिए एक मेथड को परिभाषित करता है, जिसमें ऑपरेशन को रद्द करने के लिए एक कैंसलेशन टोकन का उपयोग किया जाता है।

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| डिवाइस | IDevice | आउटपुट डिवाइस। |
| cancellationToken | CancellationToken | कार्य के पूर्ण होने की प्रतीक्षा करते समय निरीक्षण करने के लिए एक CancellationToken। |
| स्रोत | Stream[] | रेंडर करने के लिए EPub दस्तावेज़। |

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

निर्दिष्ट [`IDevice`](../../idevice/) में EPub दस्तावेज़ को रेंडर करता है।

```java
public void Render(IDevice device, Stream source, Configuration configuration)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| डिवाइस | IDevice | डिवाइस। |
| डॉक्यूमेंट | स्ट्रीम | दस्तावेज़। |
| कॉन्फ़िगरेशन | कॉन्फ़िगरेशन | कॉन्फ़िगरेशन। |

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

निर्दिष्ट [`IDevice`](../../idevice/) में EPub दस्तावेज़ को रेंडर करता है। रेंडरिंग तब की जाएगी जब कोई नेटवर्क ऑपरेशन, संसाधन, सक्रिय टाइमर, एनीमेशन टास्क नहीं हों या निर्दिष्ट टाइमआउट समाप्त हो गया हो।

```java
public void Render(IDevice device, Stream source, Configuration configuration, TimeSpan timeout)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| डिवाइस | IDevice | डिवाइस। |
| डॉक्यूमेंट | स्ट्रीम | दस्तावेज़। |
| कॉन्फ़िगरेशन | कॉन्फ़िगरेशन | कॉन्फ़िगरेशन। |
| timeout | TimeSpan | एक TimeSpan जो प्रतीक्षा करने के मिलिसेकंड की संख्या दर्शाता है, या एक TimeSpan जो -1 मिलिसेकंड दर्शाता है जिससे अनिश्चितकाल तक प्रतीक्षा की जा सके। |

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

निर्दिष्ट [`IDevice`](../../idevice/) में कई EPub दस्तावेज़ों को रेंडर करता है।

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| डिवाइस | IDevice | डिवाइस। |
| दस्तावेज़ | IList`1 | रेंडर करने के लिए दस्तावेज़ों की IList। |
| कॉन्फ़िगरेशन | कॉन्फ़िगरेशन | कॉन्फ़िगरेशन। |

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

निर्दिष्ट [`IDevice`](../../idevice/) में कई EPub दस्तावेज़ों को रेंडर करता है। रेंडरिंग तब की जाएगी जब कोई नेटवर्क ऑपरेशन, संसाधन, सक्रिय टाइमर, एनीमेशन टास्क नहीं हों या निर्दिष्ट टाइमआउट समाप्त हो गया हो।

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration, 
    TimeSpan timeout)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| डिवाइस | IDevice | डिवाइस। |
| दस्तावेज़ | IList`1 | रेंडर करने के लिए दस्तावेज़ों की IList। |
| कॉन्फ़िगरेशन | कॉन्फ़िगरेशन | कॉन्फ़िगरेशन। |
| timeout | TimeSpan | एक TimeSpan जो प्रतीक्षा करने के मिलिसेकंड की संख्या दर्शाता है, या एक TimeSpan जो -1 मिलिसेकंड दर्शाता है जिससे अनिश्चितकाल तक प्रतीक्षा की जा सके। |

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
