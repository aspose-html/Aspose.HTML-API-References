---
title: "IStyleSheet.Disabled"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "IStyleSheet प्रॉपर्टी। StyleSheet इंटरफ़ेस की disabled प्रॉपर्टी निर्धारित करती है कि स्टाइल शीट को दस्तावेज़ पर लागू होने से रोका गया है या नहीं।"
type: docs

url: /hi/java/com.aspose.html.dom.css/istylesheet/disabled/
---
## IStyleSheet.Disabled property

`[`StyleSheet`](../)` इंटरफ़ेस की disabled प्रॉपर्टी निर्धारित करती है कि स्टाइल शीट को दस्तावेज़ पर लागू होने से रोका गया है या नहीं।

एक स्टाइल शीट को इस प्रॉपर्टी को true सेट करके या यदि यह एक निष्क्रिय वैकल्पिक स्टाइल शीट है, तो disabled किया जा सकता है। ध्यान दें कि disabled == false होने से यह गारंटी नहीं देता कि स्टाइल शीट लागू हुई है (उदाहरण के लिए इसे दस्तावेज़ से हटाया भी जा सकता है)।

इस एट्रिब्यूट को बदलने से दस्तावेज़ के लिए नई स्टाइल रेज़ॉल्यूशन हो सकती है। एक स्टाइल शीट तभी लागू होती है जब उपयुक्त माध्यम परिभाषा मौजूद हो और disabled एट्रिब्यूट false हो। इसलिए, यदि मीडिया वर्तमान यूज़र एजेंट पर लागू नहीं होता, तो disabled एट्रिब्यूट को नजरअंदाज किया जाता है।

```java
public bool Disabled { get; set; }
```

### रिटर्न वैल्यू

यह disabled attribute, प्राप्त करने पर, true लौटाना चाहिए यदि disabled फ़्लैग सेट है, अन्यथा false। सेट करने पर, यह disabled attribute disabled फ़्लैग को सेट करना चाहिए यदि नया मान true है, अन्यथा disabled फ़्लैग को अनसेट करना चाहिए।

### Property Value

यह disabled attribute, प्राप्त करने पर, true लौटाना चाहिए यदि disabled फ़्लैग सेट है, अन्यथा false। सेट करने पर, यह disabled attribute disabled फ़्लैग को सेट करना चाहिए यदि नया मान true है, अन्यथा disabled फ़्लैग को अनसेट करना चाहिए।

## टिप्पणियाँ

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

संदर्भ

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-disabled](https://drafts.csswg.org/cssom/#dom-stylesheet-disabled) – The CSSOM definition.

### संबंधित देखें

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
