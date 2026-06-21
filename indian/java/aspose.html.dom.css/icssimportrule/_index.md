---
title: "ICSSImportRule इंटरफ़ेस"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.css.ICSSImportRule इंटरफ़ेस। The CSSImportRule इंटरफ़ेस एक CSS स्टाइल शीट के भीतर एक इम्पोर्ट नियम का प्रतिनिधित्व करता है। इम्पोर्ट नियम का उपयोग अन्य स्टाइल शीट्स से स्टाइल नियमों को आयात करने के लिए किया जाता है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/icssimportrule/
---
## ICSSImportRule interface

CSSImportRule इंटरफ़ेस CSS स्टाइल शीट के भीतर एक @import नियम का प्रतिनिधित्व करता है। @import नियम अन्य स्टाइल शीट्स से स्टाइल नियमों को आयात करने के लिए उपयोग किया जाता है।

```java
public interface ICSSImportRule : ICSSRule
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [getHref](../../com.aspose.html.dom.css/icssimportrule/href/) The CSSImportRule इंटरफ़ेस की read-only href प्रॉपर्टी @import at-rule द्वारा निर्दिष्ट URL लौटाती है। |
| [getMedia](../../com.aspose.html.dom.css/icssimportrule/media/) The CSSImportRule इंटरफ़ेस की read-only media प्रॉपर्टी एक MediaList ऑब्जेक्ट लौटाती है, जिसमें संबंधित स्टाइलशीट के media एट्रिब्यूट का मान होता है। |
| [getStyleSheet](../../com.aspose.html.dom.css/icssimportrule/stylesheet/) इस नियम द्वारा संदर्भित स्टाइल शीट, यदि लोड हो चुकी है। इस एट्रिब्यूट का मान null होता है यदि स्टाइल शीट अभी तक लोड नहीं हुई है या लोड नहीं होगी (उदा., यदि स्टाइल शीट किसी ऐसे मीडिया प्रकार के लिए है जो उपयोगकर्ता एजेंट द्वारा समर्थित नहीं है)। |

### संबंधित देखें

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
