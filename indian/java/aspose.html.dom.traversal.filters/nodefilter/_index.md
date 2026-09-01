---
title: "NodeFilter क्लास"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.traversal.filters.NodeFilter क्लास। फ़िल्टर ऐसे ऑब्जेक्ट होते हैं जो नोड्स को फ़िल्टर करना जानते हैं"
type: docs

url: /hi/java/com.aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

फ़िल्टर ऐसे ऑब्जेक्ट्स हैं जो नोड्स को "फ़िल्टर आउट" करना जानते हैं।

```java
public abstract class NodeFilter : DOMObject, INodeFilter
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| abstract [AcceptNode](../../com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | जाँचें कि क्या निर्दिष्ट नोड TreeWalker या NodeIterator के तर्कसंगत दृश्य में दृश्यमान है। यह फ़ंक्शन TreeWalker और NodeIterator के कार्यान्वयन द्वारा बुलाया जाएगा; यह सामान्यतः उपयोगकर्ता कोड से सीधे नहीं बुलाया जाता। (हालाँकि यदि आप अपने स्वयं के एप्लिकेशन लॉजिक को मार्गदर्शन करने के लिए वही फ़िल्टर उपयोग करना चाहते हैं तो आप ऐसा कर सकते हैं।) |
| [getPlatformType](../../com.aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट टाइप प्राप्त करने के लिए उपयोग किया जाता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [FILTER_ACCEPT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | नोड को स्वीकार करें। NodeIterator या TreeWalker के लिए परिभाषित नेविगेशन मेथड्स इस नोड को लौटाएंगे। |
| const [FILTER_REJECT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | नोड को अस्वीकार करें। NodeIterator या TreeWalker के लिए परिभाषित नेविगेशन मेथड्स इस नोड को नहीं लौटाएंगे। TreeWalker के लिए, इस नोड के बच्चे भी अस्वीकार किए जाएंगे। NodeIterators इसे FILTER_SKIP का समानार्थक मानते हैं। |
| const [FILTER_SKIP](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | इस एकल नोड को स्किप करें। NodeIterator या TreeWalker के लिए परिभाषित नेविगेशन मेथड्स इस नोड को नहीं लौटाएंगे। NodeIterator और TreeWalker दोनों के लिए, इस नोड के बच्चे अभी भी विचार किए जाएंगे। |
| const [SHOW_ALL](../../com.aspose.html.dom.traversal.filters/nodefilter/show_all/) | सभी नोड्स दिखाएँ। |
| const [SHOW_ATTRIBUTE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | Attr नोड्स दिखाएँ। यह केवल तब अर्थपूर्ण है जब आप एक एट्रिब्यूट नोड को रूट के रूप में लेकर इटररेटर या ट्री-वॉकर बना रहे हों; इस स्थिति में, इसका मतलब है कि एट्रिब्यूट नोड इटररेशन या ट्रैवर्सल की पहली स्थिति में दिखाई देगा। चूँकि एट्रिब्यूट कभी भी अन्य नोड्स के बच्चे नहीं होते, वे दस्तावेज़ ट्री पर ट्रैवर्स करते समय दिखाई नहीं देते। |
| const [SHOW_CDATA_SECTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | CDATASection नोड्स दिखाएँ। |
| const [SHOW_COMMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_comment/) | कमेंट नोड्स दिखाएँ। |
| const [SHOW_DOCUMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document/) | डॉक्यूमेंट नोड्स दिखाएँ। |
| const [SHOW_DOCUMENT_FRAGMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | DocumentFragment नोड्स दिखाएँ। |
| const [SHOW_DOCUMENT_TYPE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | DocumentType नोड्स दिखाएँ। |
| const [SHOW_ELEMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_element/) | एलिमेंट नोड्स दिखाएँ। |
| const [SHOW_ENTITY](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity/) | Entity नोड्स दिखाएँ। यह केवल तब अर्थपूर्ण है जब आप एक Entity नोड को रूट के रूप में लेकर इटररेटर या ट्री-वॉकर बना रहे हों; इस स्थिति में, इसका मतलब है कि Entity नोड ट्रैवर्सल की पहली स्थिति में दिखाई देगा। चूँकि एंटिटीज़ दस्तावेज़ ट्री का हिस्सा नहीं हैं, वे दस्तावेज़ ट्री पर ट्रैवर्स करते समय दिखाई नहीं देते। |
| const [SHOW_ENTITY_REFERENCE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | EntityReference नोड दिखाएँ। |
| const [SHOW_NOTATION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_notation/) | Notation नोड दिखाएँ। यह केवल तब अर्थपूर्ण है जब आप एक iterator या tree-walker को Notation नोड को मूल (root) के रूप में बनाते हैं; इस स्थिति में, इसका मतलब है कि Notation नोड यात्रा (traversal) की पहली स्थिति में दिखाई देगा। चूँकि notations दस्तावेज़ वृक्ष (document tree) का हिस्सा नहीं हैं, वे दस्तावेज़ वृक्ष पर यात्रा करते समय दिखाई नहीं देते। |
| const [SHOW_PROCESSING_INSTRUCTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | ProcessingInstruction नोड दिखाएँ। |
| const [SHOW_TEXT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_text/) | Text नोड दिखाएँ। |

### संबंधित देखें

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [INodeFilter](../../com.aspose.html.dom.traversal/inodefilter/)
* package [com.aspose.html.dom.traversal.filters](../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../)
