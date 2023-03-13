---
title: Interface ICSSImportRule
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Css.ICSSImportRule इंटरफेस. CSSImportRule इंटरफ़ेस CSS स्टइल शट के भतर एक import नयम क प्रतनधत्व करत है Import नयम क उपयग अन्य स्टइल शट्स से शैल नयमं क आयत करने के लए कय जत है
type: docs
weight: 410
url: /hi/net/aspose.html.dom.css/icssimportrule/
---
## ICSSImportRule interface

CSSImportRule इंटरफ़ेस CSS स्टाइल शीट के भीतर एक @import नियम का प्रतिनिधित्व करता है। @Import नियम का उपयोग अन्य स्टाइल शीट्स से शैली नियमों को आयात करने के लिए किया जाता है।

```csharp
public interface ICSSImportRule : ICSSRule
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Href](../../aspose.html.dom.css/icssimportrule/href/) { get; } | आयात की जाने वाली स्टाइल शीट का स्थान। एट्रिब्यूट में URI. के आस-पास "url(...)" स्पेसिफ़ायर नहीं होगा |
| [Media](../../aspose.html.dom.css/icssimportrule/media/) { get; } | मीडिया प्रकारों की एक सूची जिसके लिए इस स्टाइल शीट का उपयोग किया जा सकता है। |
| [StyleSheet](../../aspose.html.dom.css/icssimportrule/stylesheet/) { get; } | इस नियम द्वारा संदर्भित स्टाइल शीट, यदि इसे लोड किया गया है। यदि स्टाइल शीट अभी तक लोड नहीं हुई है या इसे लोड नहीं किया जाएगा तो इस एट्रिब्यूट का मान शून्य है (उदाहरण के लिए यदि स्टाइल शीट मीडिया प्रकार के लिए है जो उपयोगकर्ता एजेंट द्वारा समर्थित नहीं है)। |

### यह सभी देखें

* interface [ICSSRule](../icssrule/)
* नाम स्थान [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* सभा [Aspose.HTML](../../)


