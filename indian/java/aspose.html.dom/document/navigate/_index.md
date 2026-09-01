---
title: "Document.Navigate"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "Document मेथड। निर्दिष्ट यूनिफ़ॉर्म रिसोर्स लोकेटर URL पर स्थित दस्तावेज़ को वर्तमान इंस्टेंस में लोड करता है और पूर्व सामग्री को प्रतिस्थापित करता है।"
type: docs

url: /hi/java/com.aspose.html.dom/document/navigate/
---
## Navigate(String) {#navigate_4}

निर्दिष्ट यूनिफॉर्म रिसोर्स लोकेटर (URL) पर दस्तावेज़ को वर्तमान इंस्टेंस में लोड करता है, पिछले सामग्री को बदलते हुए।

```java
public void Navigate(String address)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| पता | String | दस्तावेज़ का पता। इसे वर्तमान डायरेक्टरी पाथ के साथ मिलाकर एक पूर्ण URL बनाया जाएगा। |

### संबंधित देखें

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

निर्दिष्ट यूनिफॉर्म रिसोर्स लोकेटर (URL) पर दस्तावेज़ को वर्तमान इंस्टेंस में लोड करता है, पिछले सामग्री को बदलते हुए।

```java
public void Navigate(Url url)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| url | Url | दस्तावेज़ URL। |

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, String) {#navigate_6}

निर्दिष्ट सामग्री से दस्तावेज़ को लोड करता है और सापेक्ष संसाधनों को हल करने के लिए baseUri का उपयोग करता है, पिछले सामग्री को बदलते हुए।

```java
public void Navigate(String content, String baseUri)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| सामग्री | String | दस्तावेज़ की सामग्री। |
| baseUri | String | रिलेटिव रिसोर्सेज़ को रिज़ॉल्व करने के लिए बेस URI। इसे वर्तमान डायरेक्टरी पाथ के साथ मिलाकर एक एब्सोल्यूट URL बनाया जाएगा। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | `baseUri` है `null`। |

### संबंधित देखें

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, Url) {#navigate_5}

निर्दिष्ट सामग्री से दस्तावेज़ को लोड करता है और सापेक्ष संसाधनों को हल करने के लिए baseUri का उपयोग करता है, पिछले सामग्री को बदलते हुए।

```java
public void Navigate(String content, Url baseUri)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| सामग्री | String | दस्तावेज़ की सामग्री। |
| baseUri | Url | रिलेटिव रिसोर्सेज़ को रिज़ॉल्व करने के लिए बेस URI। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | `baseUri` है `null`। |

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, String) {#navigate_3}

निर्दिष्ट सामग्री से दस्तावेज़ को लोड करता है और सापेक्ष संसाधनों को हल करने के लिए baseUri का उपयोग करता है, पिछले सामग्री को बदलते हुए। दस्तावेज़ लोडिंग स्ट्रीम में वर्तमान स्थिति से शुरू होती है।

```java
public void Navigate(Stream content, String baseUri)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| सामग्री | स्ट्रीम | दस्तावेज़ की सामग्री। |
| baseUri | String | रिलेटिव रिसोर्सेज़ को रिज़ॉल्व करने के लिए बेस URI। इसे वर्तमान डायरेक्टरी पाथ के साथ मिलाकर एक एब्सोल्यूट URL बनाया जाएगा। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | `baseUri` है `null`। |

### संबंधित देखें

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

निर्दिष्ट सामग्री से दस्तावेज़ को लोड करता है और सापेक्ष संसाधनों को हल करने के लिए baseUri का उपयोग करता है, पिछले सामग्री को बदलते हुए। दस्तावेज़ लोडिंग स्ट्रीम में वर्तमान स्थिति से शुरू होती है।

```java
public void Navigate(Stream content, Url baseUri)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| सामग्री | स्ट्रीम | दस्तावेज़ की सामग्री। |
| baseUri | Url | रिलेटिव रिसोर्सेज़ को रिज़ॉल्व करने के लिए बेस URI। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | `baseUri` है `null`। |

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

निर्दिष्ट अनुरोध ऑब्जेक्ट के आधार पर दस्तावेज़ लोड करता है, पिछले सामग्री को प्रतिस्थापित करता है।

```java
public void Navigate(RequestMessage request)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| अनुरोध | RequestMessage | वह अनुरोध ऑब्जेक्ट जो दस्तावेज़ की सामग्री लोड करने के लिए उपयोग किया जाता है। |

### संबंधित देखें

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
