---
title: HTMLTableSectionElement.InsertRow
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: HTMLTableSectionElement तरक. इस खंड में एक पंक्त डलें नई पंक्त वर्तमन से पहले तुरंत डल गई हैअनुक्रमणक इस खंड में वं पंक्त अगर अनुक्रमणक इस सेक्शन में 1 य पंक्तयं क संख्य के बरबर है नई पंक्त जड़ गई है
type: docs
weight: 70
url: /hi/net/aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

इस खंड में एक पंक्ति डालें। नई पंक्ति वर्तमान से पहले तुरंत डाली गई है`अनुक्रमणिका` इस खंड में वीं पंक्ति। अगर `अनुक्रमणिका` इस सेक्शन में -1 या पंक्तियों की संख्या के बराबर है, नई पंक्ति जोड़ी गई है।

```csharp
public HTMLElement InsertRow(int index)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | Int32 | वह पंक्ति संख्या जहां नई पंक्ति सम्मिलित करनी है. यह इंडेक्स 0 से शुरू होता है और केवल इस सेक्शन में निहित पंक्तियों के सापेक्ष है, तालिका में सभी पंक्तियों के लिए नहीं। |

### प्रतिलाभ की मात्रा

नव निर्मित पंक्ति।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: यदि निर्दिष्ट अनुक्रमणिका पंक्तियों की संख्या से अधिक है, यदि अनुक्रमणिका -1. @version DOM स्तर 2 के अलावा कोई ऋणात्मक संख्या है, तो उठाया जाता है |

### यह सभी देखें

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* नाम स्थान [Aspose.Html](../../htmltablesectionelement/)
* सभा [Aspose.HTML](../../../)


