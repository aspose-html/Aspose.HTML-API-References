---
title: "com.aspose.html.dom"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom Document Object Model पैकेज API प्रदान करता है जो किसी भी HTML, XML या SVG दस्तावेज़ का प्रतिनिधित्व करता है और उसके साथ इंटरैक्ट करता है। DOM ब्राउज़र में लोड किया गया एक दस्तावेज़ मॉडल है और दस्तावेज़ को नोड ट्री के रूप में दर्शाता है जहाँ प्रत्येक नोड दस्तावेज़ का एक भाग दर्शाता है, जैसे कि एक एलिमेंट, टेक्स्ट, स्ट्रिंग या टिप्पणी।"
type: docs

url: /hi/java/com.aspose.html.dom/
---
यह **com.aspose.html.dom (Document Object Model)** पैकेज API प्रदान करता है जो किसी भी HTML, XML या SVG दस्तावेज़ का प्रतिनिधित्व और इंटरैक्शन करता है। DOM ब्राउज़र में लोड किया गया एक दस्तावेज़ मॉडल है जो दस्तावेज़ को नोड ट्री के रूप में दर्शाता है, जहाँ प्रत्येक नोड दस्तावेज़ के किसी भाग (जैसे एलिमेंट, टेक्स्ट स्ट्रिंग, या टिप्पणी) का प्रतिनिधित्व करता है।

## क्लासेज़

| क्लास | विवरण |
| --- | --- |
| [Attr](./attr/) | Attr इंटरफ़ेस एक Element ऑब्जेक्ट में एट्रिब्यूट का प्रतिनिधित्व करता है। सामान्यतः एट्रिब्यूट के अनुमत मान दस्तावेज़ से जुड़े स्कीमा में परिभाषित होते हैं। |
| [CDATASection](./cdatasection/) | CDATA सेक्शन का उपयोग उन टेक्स्ट ब्लॉकों को एस्केप करने के लिए किया जाता है जिनमें ऐसे अक्षर होते हैं जिन्हें अन्यथा मार्कअप माना जाता। |
| [CharacterData](./characterdata/) | CharacterData, Node को DOM में कैरेक्टर डेटा तक पहुँचने के लिए एट्रिब्यूट्स और मेथड्स के सेट के साथ विस्तारित करता है। |
| [Comment](./comment/) | CharacterData से विरासत में मिलता है और टिप्पणी की सामग्री का प्रतिनिधित्व करता है, अर्थात् शुरूआती '' के बीच के सभी अक्षर। |
| [Document](./document/) | Document पूरे HTML, XML या SVG दस्तावेज़ का प्रतिनिधित्व करता है। अवधारणात्मक रूप से, यह दस्तावेज़ ट्री की जड़ है, और दस्तावेज़ के डेटा तक प्राथमिक पहुँच प्रदान करता है। |
| [DocumentFragment](./documentfragment/) | DocumentFragment एक "हल्का" या "न्यूनतम" Document ऑब्जेक्ट है। यह बहुत सामान्य है कि आप दस्तावेज़ के ट्री का एक भाग निकालना या नया फ्रैगमेंट बनाना चाहें। |
| [DocumentType](./documenttype/) | DocumentType दस्तावेज़ के लिए परिभाषित इकाइयों की सूची के लिए एक इंटरफ़ेस प्रदान करता है। |
| [DOMException](./domexception/) | DOMException इंटरफ़ेस एक असामान्य घटना (जिसे एक्सेप्शन कहा जाता है) का प्रतिनिधित्व करता है जो वेब API की किसी मेथड को कॉल करने या प्रॉपर्टी तक पहुँचने के परिणामस्वरूप होती है। यह मूलतः वेब APIs में त्रुटि स्थितियों का वर्णन करने का तरीका है। |
| [DOMObject](./domobject/) | DOMObject प्रकार पूरे Document Object Model के लिए एक बेस ऑब्जेक्ट का प्रतिनिधित्व करने के लिए उपयोग किया जाता है। Java और ECMAScript के लिए, DOMObject को Object प्रकार से बंधा हुआ है। |
| [Element](./element/) | Element इंटरफ़ेस HTML या XML दस्तावेज़ में एक एलिमेंट का प्रतिनिधित्व करता है। |
| [Entity](./entity/) | XML दस्तावेज़ में एक ज्ञात इकाई को दर्शाता है, चाहे वह पार्स्ड हो या अनपार्स्ड। |
| [EntityReference](./entityreference/) | EntityReference नोड्स का उपयोग पेड़ में एक इकाई संदर्भ को दर्शाने के लिए किया जा सकता है। |
| [EventTarget](./eventtarget/) | EventTarget इंटरफ़ेस उन वस्तुओं द्वारा लागू किया जाता है जो घटनाएँ प्राप्त कर सकती हैं और उनके लिए श्रोताओं (listeners) रख सकती हैं। दूसरे शब्दों में, घटनाओं का कोई भी लक्ष्य इस इंटरफ़ेस से जुड़े तीन विधियों (methods) को लागू करता है। |
| [Node](./node/) | Node इंटरफ़ेस पूरे Document Object Model के लिए मुख्य डेटा प्रकार है। यह दस्तावेज़ पेड़ में एकल नोड को दर्शाता है। जबकि Node इंटरफ़ेस को लागू करने वाले सभी वस्तुएँ बच्चों (children) को संभालने के लिए विधियाँ प्रदान करती हैं, सभी वस्तुओं के पास बच्चे नहीं हो सकते। उदाहरण के लिए, [`Text`](../com.aspose.html.dom/text/) नोड्स के पास बच्चे नहीं हो सकते, और ऐसे नोड्स में बच्चे जोड़ने से एक [`DOMException`](../com.aspose.html.dom/domexception/) उत्पन्न होता है। |
| [Notation](./notation/) | DTD में घोषित एक नोटेशन को दर्शाता है। |
| [ProcessingInstruction](./processinginstruction/) | ProcessingInstruction एक \"processing instruction\" को दर्शाता है, जो XML में दस्तावेज़ के पाठ में प्रोसेसर-विशिष्ट जानकारी रखने का तरीका है। |
| [QualifiedName](./qualifiedname/) | एक HTML योग्य नाम (qualified name) को दर्शाता है। |
| [ShadowRoot](./shadowroot/) | ShadowRoot शैडो ट्री का मूल नोड है। |
| [Text](./text/) | Text इंटरफ़ेस CharacterData से विरासत में मिलता है और एक Element या Attr की पाठ्य सामग्री (XML में इसे character data कहा जाता है) को दर्शाता है। |
| [TypeInfo](./typeinfo/) | TypeInfo वह प्रकार दर्शाता है जो Element या Attr नोड्स से संदर्भित है, जो दस्तावेज़ से जुड़े स्कीमा में निर्दिष्ट है। |
## इंटरफ़ेस

| इंटरफ़ेस | विवरण |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | ब्राउज़िंग कॉन्टेक्स्ट वह वातावरण है जिसमें [`Document`](../com.aspose.html.dom/document/) वस्तुएँ उपयोगकर्ता को प्रस्तुत की जाती हैं। |
| [IChildNode](./ichildnode/) | Defines [`IChildNode`](../com.aspose.html.dom/ichildnode/) इंटरफ़ेस जिसे उन [`Node`](../com.aspose.html.dom/node/) द्वारा लागू किया जाना चाहिए जिनके पास पैरेंट हो सकता है। |
| [IDOMImplementation](./idomimplementation/) | DOMImplementation इंटरफ़ेस कई विधियाँ प्रदान करता है जो दस्तावेज़ ऑब्जेक्ट मॉडल की किसी विशिष्ट इंस्टेंस से स्वतंत्र संचालन करने के लिए उपयोगी हैं। |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | एक इंटरफ़ेस को दर्शाता है जिसे सभी तत्वों द्वारा विरासत में लेना आवश्यक है जो सिस्टम इवेंट हैंडलिंग का समर्थन करते हैं। |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | [`IChildNode`](../com.aspose.html.dom/ichildnode/) को परिभाषित करता है जो [`DOCUMENT_TYPE_NODE`](../com.aspose.html.dom/node/document_type_node/) नहीं हैं। |
| [INonElementParentNode](./inonelementparentnode/) | [`IParentNode`](../com.aspose.html.dom/iparentnode/) को परिभाषित करता है जो Element प्रकार नहीं हैं। |
| [IParentNode](./iparentnode/) | [`IParentNode`](../com.aspose.html.dom/iparentnode/) इंटरफ़ेस को परिभाषित करता है जिसे कोई भी संभावित पैरेंट लागू करता है। |
| [IStorage](./istorage/) | Web Storage API का यह इंटरफ़ेस किसी विशेष डोमेन के सत्र (session) या स्थानीय (local) स्टोरेज तक पहुँच प्रदान करता है। Web Storage विनिर्देशन देखें: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage) |
## एन्यूमरेशन

| एन्यूमरेशन | विवरण |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | ShadowRoot जिन मोडों में काम कर सकता है। |
