---
title: "Document क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.Document क्लास। Document पूरे HTML, XML या SVG दस्तावेज़ का प्रतिनिधित्व करता है। अवधारणात्मक रूप से यह दस्तावेज़ ट्री की जड़ है और दस्तावेज़ के डेटा तक प्राथमिक पहुँच प्रदान करता है।"
type: docs

url: /hi/java/com.aspose.html.dom/document/
---
## Document class

Document पूरे HTML, XML या SVG दस्तावेज़ का प्रतिनिधित्व करता है। अवधारणात्मक रूप से, यह दस्तावेज़ ट्री की जड़ है, और दस्तावेज़ के डेटा तक प्राथमिक पहुँच प्रदान करता है।

```java
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) इस नोड का पूर्ण बेस URI या यदि कार्यान्वयन पूर्ण URI प्राप्त नहीं कर सका तो Null। |
| [getCharacterSet](../../com.aspose.html.dom/document/characterset/) दस्तावेज़ की एन्कोडिंग प्राप्त करता है। |
| [getCharset](../../com.aspose.html.dom/document/charset/) दस्तावेज़ की एन्कोडिंग प्राप्त करता है। |
| [getChildElementCount](../../com.aspose.html.dom/document/childelementcount/) इस तत्व के बच्चों के रूप में मौजूद तत्व नोड्स की वर्तमान संख्या लौटाता है। यदि इस तत्व के पास nodeType 1 के कोई चाइल्ड नोड नहीं हैं तो 0। |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node इंटरफ़ेस की केवल-पढ़ने योग्य childNodes प्रॉपर्टी दिए गए तत्व के चाइल्ड नोड्स की एक लाइव [`NodeList`](../../com.aspose.html.collections/nodelist/) लौटाती है जहाँ पहला चाइल्ड नोड इंडेक्स 0 पर असाइन किया जाता है। चाइल्ड नोड्स में तत्व, टेक्स्ट और टिप्पणी शामिल हैं। |
| [getChildren](../../com.aspose.html.dom/document/children/) संतान तत्वों को लौटाता है। |
| [getContentType](../../com.aspose.html.dom/document/contenttype/) दस्तावेज़ की सामग्री प्रकार को प्राप्त करता है। |
| [getContext](../../com.aspose.html.dom/document/context/) वर्तमान ब्राउज़िंग संदर्भ को प्राप्त करता है। |
| [getDefaultView](../../com.aspose.html.dom/document/defaultview/) Document इंटरफ़ेस का defaultView IDL एट्रिब्यूट, प्राप्त करने पर, इस Document के ब्राउज़िंग संदर्भ के WindowProxy ऑब्जेक्ट को लौटाना चाहिए, यदि इस Document का संबंधित ब्राउज़िंग संदर्भ है, अन्यथा null लौटाता है। |
| [getDoctype](../../com.aspose.html.dom/document/doctype/) इस दस्तावेज़ से जुड़ी Document Type घोषणा। |
| [getDocumentElement](../../com.aspose.html.dom/document/documentelement/) यह एक सुविधा एट्रिब्यूट है जो दस्तावेज़ के एलिमेंट नोड तक सीधे पहुँच की अनुमति देता है। |
| [getDocumentURI](../../com.aspose.html.dom/document/documenturi/) दस्तावेज़ का स्थान या यदि अपरिभाषित हो या Document को DOMImplementation.createDocument द्वारा बनाया गया हो तो null। |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) केवल-पढ़ने योग्य firstChild प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस की नोड के वृक्ष में पहला चाइल्ड लौटाती है, या यदि नोड के कोई चाइल्ड नहीं हैं तो null लौटाती है। |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) इस एलिमेंट का पहला बच्चा एलिमेंट नोड लौटाता है। यदि इस एलिमेंट के कोई बच्चा एलिमेंट नहीं हैं तो null। |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) यह दस्तावेज़ संभालने वाला DOMImplementation ऑब्जेक्ट। |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) दस्तावेज़ की एन्कोडिंग प्राप्त करता है। |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) केवल-पढ़ने योग्य lastChild प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस की नोड का अंतिम चाइल्ड लौटाती है। यदि इसका पैरेंट एक तत्व है, तो चाइल्ड सामान्यतः एक element node, एक text node, या एक comment node होता है। यदि कोई चाइल्ड तत्व नहीं हैं तो यह null लौटाती है। |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) इस एलिमेंट का अंतिम बच्चा एलिमेंट नोड लौटाता है। यदि इस एलिमेंट के कोई बच्चा एलिमेंट नहीं हैं तो null। |
| [getLocalName](../../com.aspose.html.dom/node/localname/) इस नोड के योग्य नाम का स्थानीय भाग लौटाता है। उन नोड्स के लिए जो किसी भी प्रकार के हैं, सिवाय [`ELEMENT_NODE`](../node/element_node/) और [`ATTRIBUTE_NODE`](../node/attribute_node/) और उन नोड्स के लिए जो DOM लेवल 1 मेथड, जैसे [`Document.createElement()`](./createelement/), द्वारा बनाए गए हैं, यह हमेशा null रहता है। |
| [getLocation](../../com.aspose.html.dom/document/location/) दस्तावेज़ का स्थान। |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI केवल-पढ़ने योग्य प्रॉपर्टी तत्व का पैकेज URI लौटाती है, या यदि तत्व किसी पैकेज में नहीं है तो null। |
| [getNextElementSibling](../../com.aspose.html.dom/document/nextelementsibling/) इस एलिमेंट का अगला सिब्लिंग एलिमेंट नोड लौटाता है। यदि इस एलिमेंट के बाद दस्तावेज़ वृक्ष में कोई सिब्लिंग एलिमेंट नोड नहीं है तो null। |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) केवल-पढ़ने योग्य nextSibling प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस की निर्दिष्ट नोड के बाद तुरंत आने वाले नोड को उसके पैरेंट के [`childNodes`](../node/childnodes/) में लौटाती है, या यदि निर्दिष्ट नोड पैरेंट तत्व में अंतिम चाइल्ड है तो null लौटाती है। |
| [getNodeName](../../com.aspose.html.dom/document/nodename/) इस नोड का नाम, उसके प्रकार के आधार पर। |
| [getNodeType](../../com.aspose.html.dom/document/nodetype/) अधोस्तित ऑब्जेक्ट के प्रकार को दर्शाने वाला कोड। |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | `nodeValue` प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस की वर्तमान नोड का मान लौटाती या सेट करती है। |
| [getOrigin](../../com.aspose.html.dom/document/origin/) दस्तावेज़ की मूल उत्पत्ति प्राप्त करता है। |
| [getOwnerDocument](../../com.aspose.html.dom/document/ownerdocument/) स्वामी दस्तावेज़ प्राप्त करता है। |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) केवल-पढ़ने योग्य parentElement प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस की DOM नोड के पैरेंट [`Element`](../element/) को लौटाती है, या यदि नोड का कोई पैरेंट नहीं है या उसका पैरेंट DOM Element नहीं है तो null। |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Node इंटरफ़ेस की केवल-पढ़ने योग्य parentNode प्रॉपर्टी DOM वृक्ष में निर्दिष्ट नोड के पैरेंट को लौटाती है। |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix केवल-पढ़ने योग्य प्रॉपर्टी निर्दिष्ट तत्व का पैकेज प्रीफ़िक्स लौटाती है, या यदि कोई प्रीफ़िक्स निर्दिष्ट नहीं है तो null। |
| [getPreviousElementSibling](../../com.aspose.html.dom/document/previouselementsibling/) इस एलिमेंट का पिछला सिब्लिंग एलिमेंट नोड लौटाता है। यदि इस एलिमेंट से पहले दस्तावेज़ वृक्ष में कोई सिब्लिंग एलिमेंट नोड नहीं है तो null। |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) केवल-पढ़ने योग्य previousSibling प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस की निर्दिष्ट नोड से पहले तुरंत आने वाले नोड को उसके पैरेंट के [`childNodes`](../node/firstchild/) सूची में लौटाती है, या यदि निर्दिष्ट नोड सूची में पहला है तो null। |
| [getReadyState](../../com.aspose.html.dom/document/readystate/) दस्तावेज़ की तैयार स्थिति लौटाता है। जब दस्तावेज़ लोड हो रहा हो तो "loading", पार्सिंग समाप्त होने पर लेकिन उप-संसाधन अभी भी लोड हो रहे हों तो "interactive", और पूरी तरह लोड होने पर "complete"। |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) एक सूची जिसमें सभी स्टाइल शीट्स शामिल हैं जो स्पष्ट रूप से दस्तावेज़ में लिंक की गई हैं या एम्बेड की गई हैं। HTML दस्तावेज़ों के लिए, इसमें बाहरी स्टाइल शीट्स शामिल हैं, जो HTML LINK तत्व के माध्यम से जोड़ी गई हैं, और इनलाइन STYLE तत्व। |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | `textContent` प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस का नोड और उसके वंशजों की टेक्स्ट सामग्री को दर्शाती है। |
[getXmlStandalone]
[setXmlStandalone] An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
[getXmlVersion]
[setXmlVersion] An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | [`EventTarget `](../eventtarget/) इंटरफ़ेस की addEventListener() मेथड एक फ़ंक्शन सेट करती है जो जब भी निर्दिष्ट इवेंट लक्ष्य को पहुँचाया जाता है, कॉल किया जाएगा। |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस का यह सेट करता है कि एक फ़ंक्शन को कॉल किया जाए जब भी निर्दिष्ट इवेंट लक्ष्य तक पहुँचाया जाता है। |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस का यह सेट करता है कि एक फ़ंक्शन को कॉल किया जाए जब भी निर्दिष्ट इवेंट लक्ष्य तक पहुँचाया जाता है। |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() मेथड Node इंटरफ़ेस का यह निर्दिष्ट पैरेंट नोड के बच्चों की सूची के अंत में एक नोड जोड़ता है। यदि दिया गया चाइल्ड दस्तावेज़ में मौजूदा नोड का संदर्भ है, तो appendChild() उसे उसकी वर्तमान स्थिति से नई स्थिति में ले जाता है (नोड को किसी अन्य नोड में जोड़ने से पहले पैरेंट नोड से हटाने की कोई आवश्यकता नहीं है)। |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode() मेथड Node इंटरफ़ेस का यह उस नोड की एक प्रतिलिपि लौटाता है जिस पर यह मेथड बुलाया गया था। इसका पैरामीटर नियंत्रित करता है कि नोड में निहित सबट्री भी क्लोन किया जाए या नहीं। |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode() मेथड Node इंटरफ़ेस का यह उस नोड की एक प्रतिलिपि लौटाता है जिस पर यह मेथड बुलाया गया था। इसका पैरामीटर नियंत्रित करता है कि नोड में निहित सबट्री भी क्लोन किया जाए या नहीं। |
| [createAttribute](../../com.aspose.html.dom/document/createattribute/)(String) | `Document.createAttribute()` मेथड एक नया एट्रीब्यूट नोड बनाता है और उसे लौटाता है। बनाया गया ऑब्जेक्ट एक नोड है जो [`Attr`](../attr/) इंटरफ़ेस को लागू करता है। DOM यह निर्धारित नहीं करता कि इस प्रकार किसी विशेष तत्व में कौन से एट्रीब्यूट जोड़े जा सकते हैं। |
| [createAttributeNS](../../com.aspose.html.dom/document/createattributens/)(String, String) | Document.createAttribute() मेथड एक नया एट्रिब्यूट नोड बनाता है और उसे लौटाता है। बनाया गया ऑब्जेक्ट एक नोड बनाता है जो [Attr](T:com.aspose.html.dom.Attr) इंटरफ़ेस को लागू करता है। DOM यह निर्धारित नहीं करता कि किसी विशेष तत्व में किस प्रकार के एट्रिब्यूट जोड़े जा सकते हैं। |
| [createCDATASection](../../com.aspose.html.dom/document/createcdatasection/)(String) | एक [`CDATASection`](../cdatasection/) नोड बनाता है जिसकी मान निर्दिष्ट स्ट्रिंग होती है। |
| [createComment](../../com.aspose.html.dom/document/createcomment/)(String) | एक [`Comment`](../comment/) नोड बनाता है जो निर्दिष्ट स्ट्रिंग को लेता है। |
| [createDocumentFragment](../../com.aspose.html.dom/document/createdocumentfragment/)() | एक नया खाली [`DocumentFragment`](../documentfragment/) बनाता है जिसमें DOM नोड्स को जोड़कर एक ऑफ‑स्क्रीन DOM ट्री बनाया जा सकता है। |
| [createDocumentType](../../com.aspose.html.dom/document/createdocumenttype/)(String, String, String, String) | यह मेथड एक [`DocumentType`](../documenttype/) ऑब्जेक्ट लौटाता है जिसे दस्तावेज़ निर्माण के समय DOMImplementation.createDocument के साथ उपयोग किया जा सकता है या Node.insertBefore() या Node.replaceChild() जैसे मेथड्स के माध्यम से दस्तावेज़ में डाला जा सकता है। |
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | HTML दस्तावेज़ में, document.createElement() मेथड टैगनाम द्वारा निर्दिष्ट HTML तत्व बनाता है, या यदि टैगनाम पहचाना नहीं जाता तो एक [`HTMLUnknownElement`](../../com.aspose.html/htmlunknownelement/) बनाता है। |
| [createElementNS](../../com.aspose.html.dom/document/createelementns/)(String, String) | दिए गए योग्य नाम और पैकेज URI का उपयोग करके एक तत्व बनाता है। |
| [createEntityReference](../../com.aspose.html.dom/document/createentityreference/)(String) | एक EntityReference ऑब्जेक्ट बनाता है। अतिरिक्त रूप से, यदि संदर्भित एंटिटी ज्ञात है, तो EntityReference नोड की चाइल्ड सूची को संबंधित Entity नोड की समान बना दिया जाता है। |
| [createEvent](../../com.aspose.html.dom/document/createevent/)(String) | इम्प्लीमेंटेशन द्वारा समर्थित प्रकार का एक [`Event`](../../com.aspose.html.dom.events/event/) बनाता है। |
| [createExpression](../../com.aspose.html.dom/document/createexpression/)(String, IXPathNSResolver) | समाधान किए गए पैकेजों के साथ एक पार्स किया हुआ XPath अभिव्यक्ति बनाता है। यह तब उपयोगी होता है जब अभिव्यक्ति को एप्लिकेशन में पुनः उपयोग किया जाना हो क्योंकि यह अभिव्यक्ति स्ट्रिंग को अधिक कुशल आंतरिक रूप में संकलित करने और अभिव्यक्ति में मौजूद सभी पैकेज प्रीफ़िक्स को पहले से हल करने की सुविधा देता है। |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator)(Node) | निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया NodeIterator बनाएं। |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator_1)(Node, long) | निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया NodeIterator बनाएं। |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया NodeIterator बनाएं। |
| [createNSResolver](../../com.aspose.html.dom/document/creatensresolver/)(Node) | किसी भी DOM नोड को इस प्रकार अनुकूलित करता है कि पैकेजों को हल किया जा सके, जिससे XPath अभिव्यक्ति को दस्तावेज़ में नोड के संदर्भ के सापेक्ष आसानी से मूल्यांकन किया जा सके। यह एडेप्टर DOM Level 3 मेथड `lookupNamespaceURI` की तरह काम करता है, जो नोड की पदानुक्रम में उपलब्ध वर्तमान जानकारी का उपयोग करके दिए गए प्रीफ़िक्स से packageURI को हल करता है, तथा निहित xml प्रीफ़िक्स को भी सही ढंग से हल करता है। |
| [createProcessingInstruction](../../com.aspose.html.dom/document/createprocessinginstruction/)(String, String) | निर्दिष्ट नाम और डेटा स्ट्रिंग्स के साथ एक ProcessingInstruction नोड बनाता है। |
| [createTextNode](../../com.aspose.html.dom/document/createtextnode/)(String) | निर्दिष्ट स्ट्रिंग के साथ एक Text नोड बनाता है। |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker)(Node) | निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया TreeWalker बनाएं। |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker_1)(Node, long) | निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया TreeWalker बनाएं। |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया TreeWalker बनाएं। |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | निर्दिष्ट [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) पर एक इवेंट डिस्पैच करता है, (सिंक्रोनस रूप से) प्रभावित EventListeners को उचित क्रम में बुलाता है। सामान्य इवेंट प्रोसेसिंग नियम (कैप्चरिंग और वैकल्पिक बबलिंग चरण सहित) उन इवेंट्स पर भी लागू होते हैं जिन्हें मैन्युअली [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) से डिस्पैच किया जाता है। |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | ऐप्लिकेशन-परिभाषित कार्यों को निष्पादित करता है जो अनमैनेज्ड संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से संबंधित होते हैं। |
| [evaluate](../../com.aspose.html.dom/document/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | एक XPath अभिव्यक्ति स्ट्रिंग का मूल्यांकन करता है और यदि संभव हो तो निर्दिष्ट प्रकार का परिणाम लौटाता है। |
| [getElementById](../../com.aspose.html.dom/document/getelementbyid/)(String) | Document का मेथड getElementById() एक [`Element`](../element/) ऑब्जेक्ट लौटाता है जो उस तत्व को दर्शाता है जिसकी id प्रॉपर्टी निर्दिष्ट स्ट्रिंग से मेल खाती है। चूँकि तत्व IDs को निर्दिष्ट करने पर अद्वितीय होना आवश्यक है, यह किसी विशिष्ट तत्व तक शीघ्र पहुँच प्राप्त करने का उपयोगी तरीका है। |
| [getElementsByClassName](../../com.aspose.html.dom/document/getelementsbyclassname/)(String) | `Document` इंटरफ़ेस का getElementsByClassName मेथड सभी चाइल्ड तत्वों का एक एरे‑समान ऑब्जेक्ट लौटाता है जिनके पास सभी दिए गए क्लास नाम हैं। |
| [getElementsByTagName](../../com.aspose.html.dom/document/getelementsbytagname/)(String) | `Document` इंटरफ़ेस का getElementsByTagName मेथड दिए गए टैग नाम वाले तत्वों की एक [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) लौटाता है। |
| [getElementsByTagNameNS](../../com.aspose.html.dom/document/getelementsbytagnamens/)(String, String) | दिए गए पैकेज से संबंधित दिए गए टैग नाम वाले तत्वों की सूची लौटाता है। पूरी दस्तावेज़, जिसमें रूट नोड भी शामिल है, खोजी जाती है। |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Node इंटरफ़ेस की hasChildNodes() मेथड एक बूलियन मान लौटाती है जो दर्शाता है कि दिया गया [`Node`](../node/) के पास चाइल्ड नोड हैं या नहीं। |
| [importNode](../../com.aspose.html.dom/document/importnode/)(Node, bool) | एक अन्य दस्तावेज़ से नोड को इस दस्तावेज़ में आयात करता है, मूल दस्तावेज़ से स्रोत नोड को बदले या हटाए बिना; यह मेथड स्रोत नोड की एक नई कॉपी बनाता है। |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() मेथड Node इंटरफ़ेस का यह निर्दिष्ट पैरेंट नोड के एक रेफ़रेंस नोड से पहले एक नोड को बच्चे के रूप में डालता है। |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() मेथड Node इंटरफ़ेस का यह पैकेज URI को आर्ग्यूमेंट के रूप में लेता है। यह बूलियन मान लौटाता है जो सत्य (true) होता है यदि पैकेज दिए गए नोड पर डिफ़ॉल्ट पैकेज हो और अन्यथा असत्य (false)। |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | [`Node`](../node/) इंटरफ़ेस की isEqualNode() मेथड जांचती है कि दो नोड समान हैं या नहीं। दो नोड समान होते हैं जब उनका प्रकार समान हो, परिभाषित विशेषताएँ (तत्वों के लिए, उनका ID, चाइल्ड की संख्या आदि), उनके गुण मेल खाते हों, आदि। मिलान करने वाले डेटा बिंदुओं का विशिष्ट सेट नोड के प्रकार पर निर्भर करता है। |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode() मेथड Node इंटरफ़ेस का यह एक लेगेसी उपनाम है === सख्त समानता ऑपरेटर के लिए। यह परीक्षण करता है कि दो नोड्स एक ही हैं (अर्थात् वे एक ही ऑब्जेक्ट को रेफ़र करते हैं) या नहीं। |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI() मेथड Node इंटरफ़ेस का यह एक प्रीफ़िक्स को पैरामीटर के रूप में लेता है और यदि पाया जाता है तो दिए गए नोड पर उससे जुड़ा पैकेज URI लौटाता है (और न मिलने पर null)। |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix() मेथड Node इंटरफ़ेस का यह एक स्ट्रिंग लौटाता है जिसमें दिए गए पैकेज URI के लिए प्रीफ़िक्स होता है, यदि मौजूद हो, अन्यथा null। जब कई प्रीफ़िक्स संभव हों, तो पहला प्रीफ़िक्स लौटाया जाता है। |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate)(RequestMessage) | निर्दिष्ट अनुरोध ऑब्जेक्ट के आधार पर दस्तावेज़ लोड करता है, पूर्व सामग्री को प्रतिस्थापित करता है। |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_4)(String) | निर्दिष्ट यूनिफ़ॉर्म रिसोर्स लोकेटर (URL) पर दस्तावेज़ को वर्तमान उदाहरण में लोड करता है, पिछले सामग्री को बदलते हुए। |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_1)(Url) | निर्दिष्ट यूनिफ़ॉर्म रिसोर्स लोकेटर (URL) पर दस्तावेज़ को वर्तमान उदाहरण में लोड करता है, पिछले सामग्री को बदलते हुए। |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_3)(Stream, String) | निर्दिष्ट सामग्री से दस्तावेज़ को लोड करता है और सापेक्ष संसाधनों को हल करने के लिए baseUri का उपयोग करता है, पिछले सामग्री को बदलते हुए। दस्तावेज़ लोडिंग स्ट्रीम में वर्तमान स्थिति से शुरू होती है। |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_2)(Stream, Url) | निर्दिष्ट सामग्री से दस्तावेज़ को लोड करता है और सापेक्ष संसाधनों को हल करने के लिए baseUri का उपयोग करता है, पिछले सामग्री को बदलते हुए। दस्तावेज़ लोडिंग स्ट्रीम में वर्तमान स्थिति से शुरू होती है। |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_6)(String, String) | निर्दिष्ट सामग्री से दस्तावेज़ को लोड करता है और सापेक्ष संसाधनों को हल करने के लिए baseUri का उपयोग करता है, पिछले सामग्री को बदलते हुए। |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_5)(String, Url) | निर्दिष्ट सामग्री से दस्तावेज़ को लोड करता है और सापेक्ष संसाधनों को हल करने के लिए baseUri का उपयोग करता है, पिछले सामग्री को बदलते हुए। |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | इस Node के नीचे सब‑ट्री की पूरी गहराई में सभी [`Text`](../text/) नोड्स, गुण नोड्स सहित, को एक \"सामान्य\" रूप में बदलता है जहाँ केवल संरचना (जैसे, [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), और [`entity references`](../entityreference/)) ही [`Text`](../text/) नोड्स को अलग करती है, अर्थात् कोई आसन्न Text नोड या खाली Text नोड नहीं रहता। इसका उपयोग यह सुनिश्चित करने के लिए किया जा सकता है कि दस्तावेज़ का DOM दृश्य उसी तरह हो जैसे इसे सहेजा गया हो और पुनः लोड किया गया हो, और यह उन ऑपरेशनों (जैसे XPointer [XPointer] लुकअप) के लिए उपयोगी है जो विशेष दस्तावेज़ ट्री संरचना पर निर्भर होते हैं। यदि [`DOMConfiguration`](../../com.aspose.html/configuration/) ऑब्जेक्ट के \"normalize-characters\" पैरामीटर, जो [`Node.ownerDocument`](../node/ownerdocument/) से जुड़ा है, true है, तो यह मेथड Text नोड्स के अक्षरों को भी पूरी तरह सामान्य करेगा। |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | दस्तावेज़ में पहला Element लौटाता है, जो चयनकर्ता से मेल खाता है |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | दस्तावेज़ में सभी Elements की एक NodeList लौटाता है, जो चयनकर्ता से मेल खाते हैं |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node इंटरफ़ेस की removeChild() मेथड DOM से एक child node हटाती है और हटाए गए node को लौटाती है। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि कोई इवेंट लिस्नर इवेंट प्रोसेस हो रहा हो तो उसे हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। हटाए जाने के बाद इवेंट लिस्नर्स कभी भी कॉल नहीं किए जा सकते। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि कोई इवेंट लिस्नर इवेंट प्रोसेस हो रहा हो तो उसे हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। हटाए जाने के बाद इवेंट लिस्नर्स कभी भी कॉल नहीं किए जा सकते। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि कोई इवेंट लिस्नर इवेंट प्रोसेस हो रहा हो तो उसे हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। हटाए जाने के बाद इवेंट लिस्नर्स कभी भी कॉल नहीं किए जा सकते। |
| [renderTo](../../com.aspose.html.dom/document/renderto/)(IDevice) | यह मेथड वर्तमान दस्तावेज़ की सामग्री को एक निर्दिष्ट ग्राफ़िकल डिवाइस पर रेंडर करने के लिए उपयोग किया जाता है। |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | चाइल्ड नोड oldChild को newChild से बच्चों की सूची में बदलता है और oldChild नोड लौटाता है। यदि newChild एक [`DocumentFragment`](../documentfragment/) ऑब्जेक्ट है, तो oldChild को सभी [`DocumentFragment`](../documentfragment/) चाइल्ड्स से बदला जाता है, जो उसी क्रम में सम्मिलित होते हैं। यदि newChild पहले से ही ट्री में है, तो उसे पहले हटाया जाता है। |
| [toString](../../com.aspose.html.dom/node/toString/)() | इस उदाहरण का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |
| [write](../../com.aspose.html.dom/document/write/)(params String[]) | `open()` द्वारा खोले गए दस्तावेज़ स्ट्रीम में टेक्स्ट की एक स्ट्रिंग लिखें। ध्यान दें कि यह फ़ंक्शन ऐसा दस्तावेज़ उत्पन्न करेगा जो अनिवार्य रूप से DTD द्वारा नियंत्रित नहीं होता और इसलिए दस्तावेज़ के संदर्भ में एक अमान्य परिणाम दे सकता है। |
| [writeLn](../../com.aspose.html.dom/document/writeln/)(params String[]) | `open()` द्वारा खोले गए दस्तावेज़ स्ट्रीम में टेक्स्ट की एक स्ट्रिंग के बाद नई पंक्ति अक्षर लिखें। ध्यान दें कि यह फ़ंक्शन ऐसा दस्तावेज़ उत्पन्न करेगा जो अनिवार्य रूप से DTD द्वारा नियंत्रित नहीं होता और इसलिए दस्तावेज़ के संदर्भ में एक अमान्य परिणाम दे सकता है। |

## इवेंट्स

| नाम | विवरण |
| --- | --- |
| event [OnAbort](../../com.aspose.html.dom/document/onabort/) | OnAbort इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnBlur](../../com.aspose.html.dom/document/onblur/) | OnBlur इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnCancel](../../com.aspose.html.dom/document/oncancel/) | OnCancel इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnCanplay](../../com.aspose.html.dom/document/oncanplay/) | OnCanplay इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnCanPlayThrough](../../com.aspose.html.dom/document/oncanplaythrough/) | OnCanPlayThrough इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnChange](../../com.aspose.html.dom/document/onchange/) | OnChange इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnClick](../../com.aspose.html.dom/document/onclick/) | OnClick इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnCueChange](../../com.aspose.html.dom/document/oncuechange/) | OnCueChange इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnDblClick](../../com.aspose.html.dom/document/ondblclick/) | OnDblClick इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnDurationChange](../../com.aspose.html.dom/document/ondurationchange/) | OnDurationChange इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnEmptied](../../com.aspose.html.dom/document/onemptied/) | OnEmptied इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnEnded](../../com.aspose.html.dom/document/onended/) | OnEnded इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnError](../../com.aspose.html.dom/document/onerror/) | OnError इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnFocus](../../com.aspose.html.dom/document/onfocus/) | OnFocus इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnInput](../../com.aspose.html.dom/document/oninput/) | OnInput इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnInvalid](../../com.aspose.html.dom/document/oninvalid/) | OnInvalid इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnKeyDown](../../com.aspose.html.dom/document/onkeydown/) | OnKeyDown इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnKeyPress](../../com.aspose.html.dom/document/onkeypress/) | OnKeyPress इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnKeyUp](../../com.aspose.html.dom/document/onkeyup/) | OnKeyUp इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnLoad](../../com.aspose.html.dom/document/onload/) | OnLoad इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnLoadedData](../../com.aspose.html.dom/document/onloadeddata/) | OnLoadedData इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnLoadedMetadata](../../com.aspose.html.dom/document/onloadedmetadata/) | OnLoadedMetadata इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnLoadStart](../../com.aspose.html.dom/document/onloadstart/) | OnLoadStart इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnMouseDown](../../com.aspose.html.dom/document/onmousedown/) | OnMouseDown इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnMouseEnter](../../com.aspose.html.dom/document/onmouseenter/) | OnMouseEnter इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnMouseLeave](../../com.aspose.html.dom/document/onmouseleave/) | OnMouseLeave इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnMouseMove](../../com.aspose.html.dom/document/onmousemove/) | OnMouseMove इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnMouseOut](../../com.aspose.html.dom/document/onmouseout/) | OnMouseOut इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnMouseOver](../../com.aspose.html.dom/document/onmouseover/) | OnMouseOver इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnMouseUp](../../com.aspose.html.dom/document/onmouseup/) | OnMouseUp इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnMouseWheel](../../com.aspose.html.dom/document/onmousewheel/) | OnMouseWheel इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnPause](../../com.aspose.html.dom/document/onpause/) | OnPause इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnPlay](../../com.aspose.html.dom/document/onplay/) | OnPlay इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnPlaying](../../com.aspose.html.dom/document/onplaying/) | OnPlaying इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnProgress](../../com.aspose.html.dom/document/onprogress/) | OnProgress इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnRateChange](../../com.aspose.html.dom/document/onratechange/) | OnRateChange इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnReadyStateChange](../../com.aspose.html.dom/document/onreadystatechange/) | OnReadyStateChange इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnReset](../../com.aspose.html.dom/document/onreset/) | OnReset इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnResize](../../com.aspose.html.dom/document/onresize/) | OnResize इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnScroll](../../com.aspose.html.dom/document/onscroll/) | OnScroll इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnSeeked](../../com.aspose.html.dom/document/onseeked/) | OnSeeked इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnSeeking](../../com.aspose.html.dom/document/onseeking/) | OnSeeking इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnSelect](../../com.aspose.html.dom/document/onselect/) | OnSelect इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnShow](../../com.aspose.html.dom/document/onshow/) | OnShow इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnStalled](../../com.aspose.html.dom/document/onstalled/) | OnStalled इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnSubmit](../../com.aspose.html.dom/document/onsubmit/) | OnSubmit इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnSuspend](../../com.aspose.html.dom/document/onsuspend/) | OnSuspend इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnTimeUpdate](../../com.aspose.html.dom/document/ontimeupdate/) | OnTimeUpdate इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnToggle](../../com.aspose.html.dom/document/ontoggle/) | OnToggle इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnVolumeChange](../../com.aspose.html.dom/document/onvolumechange/) | OnVolumeChange इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnWaiting](../../com.aspose.html.dom/document/onwaiting/) | OnWaiting इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |

### संबंधित देखें

* class [Node](../node/)
* interface [IDocumentEvent](../../com.aspose.html.dom.events/idocumentevent/)
* interface [IDocumentStyle](../../com.aspose.html.dom.css/idocumentstyle/)
* interface [IDocumentTraversal](../../com.aspose.html.dom.traversal/idocumenttraversal/)
* interface [IGlobalEventHandlers](../iglobaleventhandlers/)
* interface [INonElementParentNode](../inonelementparentnode/)
* interface [IParentNode](../iparentnode/)
* interface [IXPathEvaluator](../../com.aspose.html.dom.xpath/ixpathevaluator/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
