---
title: "Renderer-1.Render"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "Renderer विधि। TDocument को निर्दिष्ट IDevice में रेंडर करने के लिए विधि को परिभाषित करता है"
type: docs

url: /hi/java/com.aspose.html.rendering/renderer-1/render/
---
## Render(IDevice, TSource) {#render_3}

निर्दिष्ट [`IDevice`](../../idevice/) में !:TDocument को रेंडर करने के लिए विधि को परिभाषित करता है।

```java
public void Render(IDevice device, TSource source)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| device | IDevice | आउटपुट डिवाइस। |
| दस्तावेज़ | TSource | दस्तावेज़। |

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, TimeSpan) {#render_5}

निर्दिष्ट [`IDevice`](../../idevice/) में !:TDocument को रेंडर करने के लिए विधि को परिभाषित करता है। रेंडरिंग तब की जाएगी जब संसाधनों को लोड करने के लिए कोई नेटवर्क ऑपरेशन, सक्रिय टाइमर, एनीमेशन कार्य नहीं रहे, या निर्दिष्ट टाइमआउट समाप्त हो गया हो।

```java
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| device | IDevice | आउटपुट डिवाइस। |
| दस्तावेज़ | TSource | दस्तावेज़। |
| timeout | TimeSpan | एक TimeSpan जो प्रतीक्षा करने के लिए मिलीसेकंड की संख्या दर्शाता है, या एक TimeSpan जो -1 मिलीसेकंड दर्शाता है अनिश्चितकाल तक प्रतीक्षा करने के लिए। |

### संबंधित देखें

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, int) {#render_4}

निर्दिष्ट [`IDevice`](../../idevice/) में !:TDocument को रेंडर करने के लिए विधि को परिभाषित करता है। रेंडरिंग तब की जाएगी जब संसाधनों को लोड करने के लिए कोई नेटवर्क ऑपरेशन, सक्रिय टाइमर, एनीमेशन कार्य नहीं रहे, या निर्दिष्ट टाइमआउट समाप्त हो गया हो।

```java
public void Render(IDevice device, TSource source, int timeout)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| device | IDevice | आउटपुट डिवाइस। |
| दस्तावेज़ | TSource | दस्तावेज़। |
| timeout | Int32 | एक संख्या मिलीसेकंड जो प्रतीक्षा करने के लिए मिलीसेकंड की संख्या दर्शाती है, या -1 मिलीसेकंड अनिश्चितकाल तक प्रतीक्षा करने के लिए। |

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
