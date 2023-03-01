---
title: Interface ICSSStyleSheet
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Css.ICSSStyleSheet इंटरफेस. CSSStyleSheet इंटरफ़ेस एक ठस इंटरफ़ेस है जसक उपयग CSS स्टइल शट क प्रतनधत्व करने के लए कय जत है अर्थत एक स्टइल शट जसक समग्र प्रकर text/css है
type: docs
weight: 510
url: /hi/net/aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

CSSStyleSheet इंटरफ़ेस एक ठोस इंटरफ़ेस है जिसका उपयोग CSS स्टाइल शीट का प्रतिनिधित्व करने के लिए किया जाता है, अर्थात, एक स्टाइल शीट जिसका सामग्री प्रकार "text/css" है।

```csharp
public interface ICSSStyleSheet : IStyleSheet
```

## गुण

| नाम | विवरण |
| --- | --- |
| [CSSRules](../../aspose.html.dom.css/icssstylesheet/cssrules/) { get; } | स्टाइल शीट में निहित सभी सीएसएस नियमों की सूची। इसमें नियम सेट और नियम-नियम दोनों शामिल हैं. |
| [OwnerRule](../../aspose.html.dom.css/icssstylesheet/ownerrule/) { get; } | यदि यह स्टाइल शीट @import नियम से आती है, तो OwnerRule विशेषता में CSSImportRule शामिल होगा। उस स्थिति में, StyleSheet इंटरफ़ेस में OwnerNode विशेषता शून्य होगी। यदि स्टाइल शीट किसी तत्व या प्रसंस्करण निर्देश से आती है, तो OwnerRule विशेषता शून्य होगी और OwnerNode विशेषता में Node. होगा |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [DeleteRule](../../aspose.html.dom.css/icssstylesheet/deleterule/)(int) | स्टाइल शीट से एक नियम को हटाने के लिए उपयोग किया जाता है। |
| [InsertRule](../../aspose.html.dom.css/icssstylesheet/insertrule/)(string, int) | स्टाइल शीट में एक नया नियम डालने के लिए प्रयुक्त होता है। नया नियम अब कैस्केड का हिस्सा बन गया है. |

### यह सभी देखें

* interface [IStyleSheet](../istylesheet/)
* नाम स्थान [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* सभा [Aspose.HTML](../../)


