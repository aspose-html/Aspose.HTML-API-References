---
title: EpubRenderer.Render
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: EpubRenderer तरक. एक से ज़्यद ईपब क रेंडर करने के तरके क परभषत करत हैStream वशष्ट मेंIDevice . संसधनं क लड करने सक्रय टइमर एनमेशन कर्यं य नर्दष्ट टइमआउट के लए कई नेटवर्क संचलन नहं हने के बद रेंडरंग कय जएग
type: docs
weight: 20
url: /hi/net/aspose.html.rendering/epubrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_9}

एक से ज़्यादा ईपब को रेंडर करने के तरीके को परिभाषित करता हैStream विशिष्ट में[`IDevice`](../../idevice/) . संसाधनों को लोड करने, सक्रिय टाइमर, एनीमेशन कार्यों या निर्दिष्ट टाइमआउट के लिए कोई नेटवर्क संचालन नहीं होने के बाद रेंडरिंग किया जाएगा।

```csharp
public override void Render(IDevice device, TimeSpan timeout, params Stream[] documents)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| device | IDevice | आउटपुट डिवाइस। |
| timeout | TimeSpan | एTimeSpan जो प्रतीक्षा करने के लिए मिलीसेकंड की संख्या का प्रतिनिधित्व करता है, या aTimeSpan जो अनिश्चित काल तक प्रतीक्षा करने के लिए -1 मिलीसेकंड का प्रतिनिधित्व करता है। |
| documents | Stream[] | प्रस्तुत करने के लिए दस्तावेज। |

### यह सभी देखें

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* नाम स्थान [Aspose.Html.Rendering](../../epubrenderer/)
* सभा [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

ईपब दस्तावेज़ को निर्दिष्ट में रेंडर करता है[`IDevice`](../../idevice/) .

```csharp
public void Render(IDevice device, Stream document, Configuration configuration)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| device | IDevice | युक्ति। |
| document | Stream | दस्तावेज़। |
| configuration | Configuration | विन्यास। |

### यह सभी देखें

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* नाम स्थान [Aspose.Html.Rendering](../../epubrenderer/)
* सभा [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

ईपब दस्तावेज़ को निर्दिष्ट में रेंडर करता है[`IDevice`](../../idevice/) . संसाधनों को लोड करने, सक्रिय टाइमर, एनीमेशन कार्यों या निर्दिष्ट टाइमआउट के लिए कोई नेटवर्क संचालन नहीं होने के बाद रेंडरिंग किया जाएगा।

```csharp
public void Render(IDevice device, Stream document, Configuration configuration, TimeSpan timeout)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| device | IDevice | युक्ति। |
| document | Stream | दस्तावेज़। |
| configuration | Configuration | विन्यास। |
| timeout | TimeSpan | एTimeSpan जो प्रतीक्षा करने के लिए मिलीसेकंड की संख्या का प्रतिनिधित्व करता है, या aTimeSpan जो अनिश्चित काल तक प्रतीक्षा करने के लिए -1 मिलीसेकंड का प्रतिनिधित्व करता है। |

### यह सभी देखें

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* नाम स्थान [Aspose.Html.Rendering](../../epubrenderer/)
* सभा [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

एकाधिक ईपब दस्तावेज़ों को निर्दिष्ट में रेंडर करता है[`IDevice`](../../idevice/) .

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| device | IDevice | युक्ति। |
| documents | IList`1 | IList प्रस्तुत करने के लिए दस्तावेजों की। |
| configuration | Configuration | विन्यास। |

### यह सभी देखें

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* नाम स्थान [Aspose.Html.Rendering](../../epubrenderer/)
* सभा [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

एकाधिक ईपब दस्तावेज़ों को निर्दिष्ट में रेंडर करता है[`IDevice`](../../idevice/) . संसाधनों को लोड करने, सक्रिय टाइमर, एनीमेशन कार्यों या निर्दिष्ट टाइमआउट के लिए कोई नेटवर्क संचालन नहीं होने के बाद रेंडरिंग किया जाएगा।

```csharp
public void Render(IDevice device, IList<Stream> documents, Configuration configuration, 
    TimeSpan timeout)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| device | IDevice | युक्ति। |
| documents | IList`1 | IList प्रस्तुत करने के लिए दस्तावेजों की। |
| configuration | Configuration | विन्यास। |
| timeout | TimeSpan | एTimeSpan जो प्रतीक्षा करने के लिए मिलीसेकंड की संख्या का प्रतिनिधित्व करता है, या aTimeSpan जो अनिश्चित काल तक प्रतीक्षा करने के लिए -1 मिलीसेकंड का प्रतिनिधित्व करता है। |

### यह सभी देखें

* interface [IDevice](../../idevice/)
* class [Configuration](../../../aspose.html/configuration/)
* class [EpubRenderer](../)
* नाम स्थान [Aspose.Html.Rendering](../../epubrenderer/)
* सभा [Aspose.HTML](../../../)


