---
title: Document.Navigate
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Document तरक. नर्दष्ट यूनफ़र्म रसर्स लकेटर URL पर दस्तवेज़ क वर्तमन उदहरण में लड करत है पछल समग्र क प्रतस्थपत करत है
type: docs
weight: 1010
url: /hi/net/aspose.html.dom/document/navigate/
---
## Navigate(string) {#navigate_4}

निर्दिष्ट यूनिफ़ॉर्म रिसोर्स लोकेटर (URL) पर दस्तावेज़ को वर्तमान उदाहरण में लोड करता है, पिछली सामग्री को प्रतिस्थापित करता है।

```csharp
public void Navigate(string address)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| address | String | दस्तावेज़ का पता। एक निरपेक्ष URL बनाने के लिए इसे वर्तमान निर्देशिका पथ के साथ जोड़ा जाएगा। |

### यह सभी देखें

* class [Document](../)
* नाम स्थान [Aspose.Html.Dom](../../document/)
* सभा [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

निर्दिष्ट यूनिफ़ॉर्म रिसोर्स लोकेटर (URL) पर दस्तावेज़ को वर्तमान उदाहरण में लोड करता है, पिछली सामग्री को प्रतिस्थापित करता है।

```csharp
public void Navigate(Url url)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| url | Url | दस्तावेज़ URL। |

### यह सभी देखें

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* नाम स्थान [Aspose.Html.Dom](../../document/)
* सभा [Aspose.HTML](../../../)

---

## Navigate(string, string) {#navigate_6}

निर्दिष्ट सामग्री से दस्तावेज़ लोड करता है और संबंधित संसाधनों को हल करने के लिए बेसयूरी का उपयोग करता है, पिछली सामग्री को प्रतिस्थापित करता है।

```csharp
public void Navigate(string content, string baseUri)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| content | String | दस्तावेज़ सामग्री। |
| baseUri | String | सापेक्ष संसाधनों को हल करने के लिए आधार यूआरआई। एक निरपेक्ष URL बनाने के लिए इसे वर्तमान निर्देशिका पथ के साथ जोड़ा जाएगा। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | `baseUri` है`व्यर्थ`. |

### यह सभी देखें

* class [Document](../)
* नाम स्थान [Aspose.Html.Dom](../../document/)
* सभा [Aspose.HTML](../../../)

---

## Navigate(string, Url) {#navigate_5}

निर्दिष्ट सामग्री से दस्तावेज़ लोड करता है और संबंधित संसाधनों को हल करने के लिए बेसयूरी का उपयोग करता है, पिछली सामग्री को प्रतिस्थापित करता है।

```csharp
public void Navigate(string content, Url baseUri)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| content | String | दस्तावेज़ सामग्री। |
| baseUri | Url | सापेक्ष संसाधनों को हल करने के लिए आधार यूआरआई। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | `baseUri` है`व्यर्थ`. |

### यह सभी देखें

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* नाम स्थान [Aspose.Html.Dom](../../document/)
* सभा [Aspose.HTML](../../../)

---

## Navigate(Stream, string) {#navigate_3}

दस्तावेज़ को निर्दिष्ट सामग्री से लोड करता है और संबंधित संसाधनों को हल करने के लिए बेसयूरी का उपयोग करता है, पिछली सामग्री को प्रतिस्थापित करता है। दस्तावेज़ लोडिंग स्ट्रीम में वर्तमान स्थिति से शुरू होती है।

```csharp
public void Navigate(Stream content, string baseUri)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| content | Stream | दस्तावेज़ सामग्री। |
| baseUri | String | सापेक्ष संसाधनों को हल करने के लिए आधार यूआरआई। एक निरपेक्ष URL बनाने के लिए इसे वर्तमान निर्देशिका पथ के साथ जोड़ा जाएगा। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | `baseUri` है`व्यर्थ`. |

### यह सभी देखें

* class [Document](../)
* नाम स्थान [Aspose.Html.Dom](../../document/)
* सभा [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

दस्तावेज़ को निर्दिष्ट सामग्री से लोड करता है और संबंधित संसाधनों को हल करने के लिए बेसयूरी का उपयोग करता है, पिछली सामग्री को प्रतिस्थापित करता है। दस्तावेज़ लोडिंग स्ट्रीम में वर्तमान स्थिति से शुरू होती है।

```csharp
public void Navigate(Stream content, Url baseUri)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| content | Stream | दस्तावेज़ सामग्री। |
| baseUri | Url | सापेक्ष संसाधनों को हल करने के लिए आधार यूआरआई। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | `baseUri` है`व्यर्थ`. |

### यह सभी देखें

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* नाम स्थान [Aspose.Html.Dom](../../document/)
* सभा [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

निर्दिष्ट अनुरोध वस्तु के आधार पर दस्तावेज़ को लोड करता है, पिछली सामग्री को प्रतिस्थापित करता है।

```csharp
public void Navigate(RequestMessage request)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| request | RequestMessage | दस्तावेज़ सामग्री लोड करने के लिए उपयोग की जाने वाली अनुरोध वस्तु। |

### यह सभी देखें

* class [RequestMessage](../../../aspose.html.net/requestmessage/)
* class [Document](../)
* नाम स्थान [Aspose.Html.Dom](../../document/)
* सभा [Aspose.HTML](../../../)


