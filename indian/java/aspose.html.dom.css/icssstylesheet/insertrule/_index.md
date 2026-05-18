---
title: "ICSSStyleSheet.InsertRule"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "ICSSStyleSheet विधि। CSSStyleSheet.insertRule विधि वर्तमान शैली पत्रक में कुछ प्रतिबंधों के साथ एक नया CSS नियम सम्मिलित करती है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/icssstylesheet/insertrule/
---
## ICSSStyleSheet.InsertRule method

CSSStyleSheet.insertRule() मेथड वर्तमान स्टाइलशीट में एक नया CSS नियम सम्मिलित करता है, कुछ प्रतिबंधों के साथ।

नोट: यद्यपि insertRule() केवल [`CSSStyleSheet`](../) की एक विधि है, यह वास्तव में नियम को CSSStyleSheet.cssRules में सम्मिलित करता है — इसका आंतरिक [`CSSRuleList`](../../icssrulelist/)।

```java
public long InsertRule(String rule, int index)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| नियम | String | एक स्ट्रिंग जिसमें सम्मिलित किए जाने वाला नियम होता है। सम्मिलित नियम में क्या होना चाहिए, यह उसके प्रकार पर निर्भर करता है: |
| index | Int32 | एक सकारात्मक पूर्णांक जो stylesheet.cssRules.length से कम या बराबर हो, नया सम्मिलित नियम की CSSStyleSheet.cssRules में स्थिति दर्शाता है। डिफ़ॉल्ट 0 है। |

### रिटर्न वैल्यू

नए सम्मिलित नियम का इंडेक्स शैली पत्रक की नियम-सूची में।

## टिप्पणियाँ

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

संदर्भ

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-cssstylesheet-insertrule](https://drafts.csswg.org/cssom/#dom-cssstylesheet-insertrule) – The CSSOM definition.

### संबंधित देखें

* interface [ICSSStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
