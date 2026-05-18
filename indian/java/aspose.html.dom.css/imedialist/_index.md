---
title: "IMediaList इंटरफ़ेस"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.css.IMediaList इंटरफ़ेस। MediaList इंटरफ़ेस मीडिया की क्रमबद्ध संग्रह का अभिप्रेत प्रदान करता है बिना यह परिभाषित या प्रतिबंधित किए कि यह संग्रह कैसे लागू किया गया है। एक खाली सूची वही है जो सभी माध्यमों को शामिल करती है।"
type: docs

url: /hi/java/com.aspose.html.dom.css/imedialist/
---
## IMediaList interface

MediaList इंटरफ़ेस मीडिया के क्रमबद्ध संग्रह का अभिप्राय प्रदान करता है, बिना यह परिभाषित या प्रतिबंधित किए कि यह संग्रह कैसे लागू किया गया है। एक खाली सूची वही है जो \"all\" माध्यम को शामिल करती है।

साथ ही देखें [CSS Object Model (CSSOM) # ](https://www.w3.org/TR/cssom-1/#the-medialist-interface)[MediaList](https://www.w3.org/TR/cssom-1/#the-medialist-interface)।

```java
public interface IMediaList : IEnumerable<String>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/imedialist/item/) item(index) मेथड को इंडेक्स द्वारा निर्दिष्ट मीडिया क्वेरी संग्रह की सीरियलाइज़ेशन लौटानी चाहिए, या यदि इंडेक्स मीडिया क्वेरी संग्रह की संख्या से बड़ा या बराबर है तो null लौटाना चाहिए। |
| [getLength](../../com.aspose.html.dom.css/imedialist/length/) length एट्रिब्यूट को मीडिया क्वेरी संग्रह में मीडिया क्वेरी की संख्या लौटानी चाहिए। मान्य मीडिया की सीमा 0 से length-1 तक, दोनों सहित है। |
| [getMediaText](../../com.aspose.html.dom.css/imedialist/mediatext/) एक Stringifier जो MediaList को टेक्स्ट के रूप में दर्शाने वाला DOMString लौटाता है, और आपको नया MediaList सेट करने की भी अनुमति देता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [appendMedium](../../com.aspose.html.dom.css/imedialist/appendmedium/)(String) | नया माध्यम newMedium को सूची के अंत में जोड़ता है। यदि newMedium पहले से उपयोग में है, तो इसे पहले हटाया जाता है। |
| [deleteMedium](../../com.aspose.html.dom.css/imedialist/deletemedium/)(String) | oldMedium द्वारा संकेतित माध्यम को सूची से हटाता है। |

## टिप्पणियाँ

ध्यान दें: MediaList एक लाइव सूची है; नीचे सूचीबद्ध प्रॉपर्टी या मेथड का उपयोग करके सूची को अपडेट करने से दस्तावेज़ के व्यवहार में तुरंत परिवर्तन होगा।

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

संदर्भ

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # medialist](https://drafts.csswg.org/cssom/#medialist) – The CSSOM definition.

## उदाहरण

निम्नलिखित वर्तमान दस्तावेज़ पर लागू पहली शैलीपत्र की MediaList का पाठ्य प्रतिनिधित्व कंसोल में लॉग करेगा।

```java
var stylesheets = document.StyleSheets;
var stylesheet = stylesheets[0];
Console.Write(stylesheet.Media.MediaText);
```

### संबंधित देखें

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
