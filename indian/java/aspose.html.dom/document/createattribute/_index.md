---
title: "Document.CreateAttribute"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "Document मेथड। Document.createAttribute मेथड एक नया एट्रिब्यूट नोड बनाता है और उसे लौटाता है। यह ऑब्जेक्ट Attr इंटरफ़ेस को लागू करने वाला नोड बनाता है। DOM यह निर्धारित नहीं करता कि इस प्रकार किसी विशेष एलिमेंट में कौन‑से एट्रिब्यूट जोड़े जा सकते हैं।"
type: docs

url: /hi/java/com.aspose.html.dom/document/createattribute/
---
## Document.CreateAttribute method

The Document.createAttribute() मेथड एक नया एट्रिब्यूट नोड बनाता है, और उसे लौटाता है। यह ऑब्जेक्ट [`Attr`](../../attr/) इंटरफ़ेस को लागू करने वाला नोड बनाता है। DOM यह निर्धारित नहीं करता कि इस प्रकार किसी विशेष एलिमेंट में कौन‑से एट्रिब्यूट जोड़े जा सकते हैं।

```java
public Attr CreateAttribute(String localName)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| localName | String | name एक स्ट्रिंग है जिसमें एट्रिब्यूट का नाम होता है। |

### रिटर्न वैल्यू

एक [`Attr`](../../attr/) नोड।

## उदाहरण

```java
var element = document.GetElementById("div");
var attr = document.CreateAttribute("my_attr");
attr.Value = "my_value";
element.SetAttributeNode(attr);
```

### संबंधित देखें

* class [Attr](../../attr/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
