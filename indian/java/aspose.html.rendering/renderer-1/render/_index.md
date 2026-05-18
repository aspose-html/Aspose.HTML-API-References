---
title: "Renderer-1.Render"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Renderer मेथड। निर्दिष्ट IDevice में TDocument को रेंडर करने की विधि को परिभाषित करता है"
type: docs

url: /hi/java/com.aspose.html.rendering/renderer-1/render/
---
## Render(IDevice, TSource) {#render_3}

निर्दिष्ट [`IDevice`](../../idevice/) में !:TDocument को रेंडर करने की विधि को परिभाषित करता है।

```java
public void Render(IDevice device, TSource source)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| डिवाइस | IDevice | आउटपुट डिवाइस। |
| डॉक्यूमेंट | TSource | दस्तावेज़। |

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, TimeSpan) {#render_5}

निर्दिष्ट [`IDevice`](../../idevice/) में !:TDocument को रेंडर करने की विधि को परिभाषित करता है। रेंडरिंग तब की जाएगी जब संसाधनों को लोड करने के लिए कोई नेटवर्क ऑपरेशन, सक्रिय टाइमर, एनीमेशन टास्क न हों या निर्दिष्ट टाइमआउट समाप्त हो गया हो।

```java
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| डिवाइस | IDevice | आउटपुट डिवाइस। |
| डॉक्यूमेंट | TSource | दस्तावेज़। |
| timeout | TimeSpan | एक TimeSpan जो प्रतीक्षा करने के मिलिसेकंड की संख्या दर्शाता है, या एक TimeSpan जो -1 मिलिसेकंड दर्शाता है जिससे अनिश्चितकाल तक प्रतीक्षा की जा सके। |

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, int) {#render_4}

निर्दिष्ट [`IDevice`](../../idevice/) में !:TDocument को रेंडर करने की विधि को परिभाषित करता है। रेंडरिंग तब की जाएगी जब संसाधनों को लोड करने के लिए कोई नेटवर्क ऑपरेशन, सक्रिय टाइमर, एनीमेशन टास्क न हों या निर्दिष्ट टाइमआउट समाप्त हो गया हो।

```java
public void Render(IDevice device, TSource source, int timeout)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| डिवाइस | IDevice | आउटपुट डिवाइस। |
| डॉक्यूमेंट | TSource | दस्तावेज़। |
| timeout | Int32 | एक मिलिसेकंड संख्या जो प्रतीक्षा करने के मिलिसेकंड की संख्या दर्शाती है, या -1 मिलिसेकंड जिससे अनिश्चितकाल तक प्रतीक्षा की जा सके। |

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, params TSource[]) {#render_6}

```java
public void Render(IDevice device, params TSource[] sources)
```

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, int, params TSource[]) {#render}

```java
public void Render(IDevice device, int timeout, params TSource[] sources)
```

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TimeSpan, params TSource[]) {#render_2}

```java
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params TSource[]) {#render_1}

```java
public abstract void Render(IDevice device, CancellationToken cancellationToken, 
    params TSource[] sources)
```

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
