---
title: "MhtmlRenderer.Render"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "MhtmlRenderer मेथड। कई MHTML दस्तावेज़ों को निर्दिष्ट IDevice में रेंडर करता है। रेंडरिंग तब की जाएगी जब संसाधनों को लोड करने के लिए कोई नेटवर्क ऑपरेशन, सक्रिय टाइमर, एनीमेशन टास्क न हों या निर्दिष्ट टाइमआउट समाप्त हो गया हो।"
type: docs

url: /hi/java/com.aspose.html.rendering/mhtmlrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

कई MHTML दस्तावेज़ों को निर्दिष्ट [`IDevice`](../../idevice/) में रेंडर करता है। रेंडरिंग तब की जाएगी जब संसाधनों को लोड करने के लिए कोई नेटवर्क ऑपरेशन, सक्रिय टाइमर, एनीमेशन टास्क न हों या निर्दिष्ट टाइमआउट समाप्त हो गया हो।

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| डिवाइस | IDevice | डिवाइस। |
| timeout | TimeSpan | एक TimeSpan जो प्रतीक्षा करने के मिलिसेकंड की संख्या दर्शाता है, या एक TimeSpan जो -1 मिलिसेकंड दर्शाता है जिससे अनिश्चितकाल तक प्रतीक्षा की जा सके। |
| दस्तावेज़ | Stream[] | रेंडर करने के लिए दस्तावेज़। |

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

कई MHTML दस्तावेज़ों को एक विशिष्ट [`IDevice`](../../idevice/) में रेंडर करने के लिए एक विधि परिभाषित करता है, ऑपरेशन को रद्द करने के लिए एक कैंसलेशन टोकन का उपयोग करता है।

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| डिवाइस | IDevice | आउटपुट डिवाइस। |
| cancellationToken | CancellationToken | कार्य के पूर्ण होने की प्रतीक्षा करते समय निरीक्षण करने के लिए एक CancellationToken। |
| स्रोत | Stream[] | रेंडर करने के लिए MHTML दस्तावेज़। |

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

निर्दिष्ट [`IDevice`](../../idevice/) में MHTML दस्तावेज़ को रेंडर करता है।

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
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

निर्दिष्ट [`IDevice`](../../idevice/) में MHTML दस्तावेज़ को रेंडर करता है। रेंडरिंग तब की जाएगी जब संसाधनों को लोड करने के लिए कोई नेटवर्क ऑपरेशन, सक्रिय टाइमर, एनीमेशन कार्य नहीं रहे और निर्दिष्ट टाइमआउट समाप्त हो गया हो।

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
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

निर्दिष्ट [`IDevice`](../../idevice/) में कई MHTML दस्तावेज़ों को रेंडर करता है।

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
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

कई MHTML दस्तावेज़ों को निर्दिष्ट [`IDevice`](../../idevice/) में रेंडर करता है। रेंडरिंग तब की जाएगी जब संसाधनों को लोड करने के लिए कोई नेटवर्क ऑपरेशन, सक्रिय टाइमर, एनीमेशन टास्क न हों या निर्दिष्ट टाइमआउट समाप्त हो गया हो।

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
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
