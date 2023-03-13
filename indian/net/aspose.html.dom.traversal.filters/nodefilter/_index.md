---
title: Class NodeFilter
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Traversal.Filters.NodeFilter कक्ष. फ़ल्टर ऐस वस्तुएं हैं ज जनते हैं क नड्स क फ़ल्टर आउट कैसे करन है
type: docs
weight: 2460
url: /hi/net/aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

फ़िल्टर ऐसी वस्तुएं हैं जो जानते हैं कि नोड्स को "फ़िल्टर आउट" कैसे करना है।

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## तरीकों

| नाम | विवरण |
| --- | --- |
| abstract [AcceptNode](../../aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | परीक्षण करें कि a TreeWalker या NodeIterator के तार्किक दृश्य में निर्दिष्ट नोड दृश्यमान है या नहीं। इस function को TreeWalker और NodeIterator के कार्यान्वयन द्वारा बुलाया जाएगा; इसे आम तौर पर सीधे उपयोगकर्ता कोड से नहीं कहा जाता है। (हालांकि आप ऐसा कर सकते हैं यदि आप अपने स्वयं के एप्लिकेशन तर्क को निर्देशित करने के लिए Same फ़िल्टर का उपयोग करना चाहते हैं।) |
| override [GetPlatformType](../../aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | इस विधि का उपयोग ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए किया जाता हैType . |

## खेत

| नाम | विवरण |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | नोड स्वीकार करें। _ NodeIterator या TreeWalker के लिए परिभाषित नेविगेशन विधियां इस नोड को लौटाएंगी। |
| const [FILTER_REJECT](../../aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | नोड को अस्वीकार करें। _ NodeIterator या TreeWalker के लिए परिभाषित नेविगेशन विधियां इस नोड को वापस नहीं करेंगी। ट्रीवॉकर के लिए, इस नोड के चिल्ड्रन को भी अस्वीकार कर दिया जाएगा। NodeIterators इसे FILTER_SKIP. के लिए पर्यायवाची मानते हैं |
| const [FILTER_SKIP](../../aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | इस एकल नोड को छोड़ दें। _ NodeIterator या TreeWalker के लिए परिभाषित नेविगेशन विधियां इस नोड को वापस नहीं करेंगी। NodeIterator और TreeWalker दोनों के लिए, इस नोड के चिल्ड्रन को अभी भी माना जाएगा। |
| const [SHOW_ALL](../../aspose.html.dom.traversal.filters/nodefilter/show_all/) | सभी नोड्स दिखाएं। |
| const [SHOW_ATTRIBUTE](../../aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | एटीआर नोड्स दिखाएं। यह तभी सार्थक है जब एक पुनरावर्तक या ट्री-वॉकर एक विशेषता नोड के साथ इसके रूट के रूप में बनाया जाए; इस मामले में, इसका मतलब है कि विशेषता नोड पुनरावृत्ति या ट्रैवर्सल की पहली स्थिति में दिखाई देगा। चूंकि एट्रिब्यूट्स कभी भी अन्य नोड्स के बच्चे नहीं होते हैं, वे दस्तावेज़ ट्री पर ट्रैवर्स करते समय प्रकट नहीं होते हैं। |
| const [SHOW_CDATA_SECTION](../../aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | CDATASection नोड्स दिखाएं। |
| const [SHOW_COMMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_comment/) | टिप्पणी नोड दिखाएं. |
| const [SHOW_DOCUMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document/) | दस्तावेज़ नोड दिखाएं. |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | दस्तावेज़फ़्रैगमेंट नोड दिखाएं. |
| const [SHOW_DOCUMENT_TYPE](../../aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | दस्तावेज़ प्रकार नोड्स दिखाएं। |
| const [SHOW_ELEMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_element/) | एलिमेंट नोड दिखाएं. |
| const [SHOW_ENTITY](../../aspose.html.dom.traversal.filters/nodefilter/show_entity/) | एंटिटी नोड दिखाएं। यह तभी सार्थक है जब एक इटरेटर या ट्री-वॉकर बना रहा हो, जिसके रूट के रूप में एक एंटिटी नोड हो; इस मामले में, इसका मतलब है कि Entity नोड ट्रैवर्सल की पहली स्थिति में दिखाई देगा। चूँकि संस्थाएँ दस्तावेज़ ट्री का हिस्सा नहीं हैं, वे दस्तावेज़ ट्री पर ट्रैवर्स करते समय दिखाई नहीं देते हैं। |
| const [SHOW_ENTITY_REFERENCE](../../aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | EntityReference नोड्स दिखाएं। |
| const [SHOW_NOTATION](../../aspose.html.dom.traversal.filters/nodefilter/show_notation/) | संकेतन नोड दिखाएं। यह तभी सार्थक है जब एक पुनरावर्तक या ट्री-वॉकर को इसके रूट के रूप में नोटेशन नोड के साथ बनाया जाए; इस मामले में, इसका मतलब है कि नोटेशन नोड ट्रैवर्सल की पहली स्थिति में दिखाई देगा। चूंकि अंकन दस्तावेज़ ट्री का हिस्सा नहीं हैं, वे दस्तावेज़ ट्री पर ट्रैवर्स करते समय प्रकट नहीं होते हैं। |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | प्रोसेसिंग इंस्ट्रक्शन नोड्स दिखाएं। |
| const [SHOW_TEXT](../../aspose.html.dom.traversal.filters/nodefilter/show_text/) | टेक्स्ट नोड दिखाएं. |

### यह सभी देखें

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [INodeFilter](../../aspose.html.dom.traversal/inodefilter/)
* नाम स्थान [Aspose.Html.Dom.Traversal.Filters](../../aspose.html.dom.traversal.filters/)
* सभा [Aspose.HTML](../../)


