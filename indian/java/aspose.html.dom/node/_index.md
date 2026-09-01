---
title: "Node क्लास"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.Node क्लास। Node इंटरफ़ेस पूरे Document Object Model के लिए मुख्य डेटा टाइप है। यह दस्तावेज़ ट्री में एकल नोड का प्रतिनिधित्व करता है। जबकि Node इंटरफ़ेस को लागू करने वाले सभी ऑब्जेक्ट बच्चों को संभालने के लिए मेथड्स प्रदान करते हैं, सभी ऑब्जेक्ट्स के पास बच्चे नहीं हो सकते। उदाहरण के लिए Text नोड्स के पास बच्चे नहीं हो सकते और ऐसे नोड्स में बच्चे जोड़ने से DOMException उत्पन्न होता है।"
type: docs

url: /hi/java/com.aspose.html.dom/node/
---
## Node class

Node इंटरफ़ेस पूरे Document Object Model के लिए प्राथमिक डेटा प्रकार है। यह दस्तावेज़ वृक्ष में एक एकल नोड का प्रतिनिधित्व करता है। जबकि Node इंटरफ़ेस को लागू करने वाले सभी वस्तुएँ बच्चों को संभालने के लिए विधियाँ प्रदान करती हैं, सभी वस्तुओं के पास बच्चे नहीं हो सकते। उदाहरण के लिए, [`Text`](../text/) नोड्स के पास बच्चे नहीं हो सकते, और ऐसे नोड्स में बच्चे जोड़ने से एक [`DOMException`](../domexception/) उत्पन्न होती है।

Attributes [`nodeName`](./nodename/), [`nodeValue`](./nodevalue/) को नोड जानकारी तक पहुँचने के लिए एक तंत्र के रूप में शामिल किया गया है, बिना विशिष्ट व्युत्पन्न इंटरफ़ेस में कास्ट किए। उन मामलों में जहाँ किसी विशेष [`nodeType`](./nodetype/) के लिए इन attributes का स्पष्ट मानचित्रण नहीं है (उदाहरण के लिए, एक [`Element`](../element/) के लिए nodeValue या एक [`Comment`](../comment/) के लिए attributes), यह null लौटाता है। ध्यान दें कि विशेषीकृत इंटरफ़ेस में संबंधित जानकारी को प्राप्त करने और सेट करने के लिए अतिरिक्त और अधिक सुविधाजनक तंत्र हो सकते हैं।

```java
public abstract class Node : EventTarget, IXPathNSResolver
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node इंटरफ़ेस की केवल-पढ़ने योग्य baseURI प्रॉपर्टी वह पूर्ण बेस URL लौटाती है जो नोड को सम्मिलित दस्तावेज़ का है। |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node इंटरफ़ेस की केवल-पढ़ने योग्य childNodes प्रॉपर्टी दिए गए तत्व के चाइल्ड नोड्स की एक लाइव [`NodeList`](../../com.aspose.html.collections/nodelist/) लौटाती है जहाँ पहला चाइल्ड नोड इंडेक्स 0 पर होता है। चाइल्ड नोड्स में तत्व, टेक्स्ट और टिप्पणी शामिल हैं। |
| [getFirstChild] `Node` इंटरफ़ेस की केवल-पढ़ने योग्य firstChild प्रॉपर्टी वृक्ष में नोड का पहला बच्चा लौटाती है, या यदि नोड के पास कोई बच्चा नहीं है तो null लौटाती है। |
| [getLastChild] `Node` इंटरफ़ेस की केवल-पढ़ने योग्य lastChild प्रॉपर्टी नोड का अंतिम बच्चा लौटाती है। यदि इसका पैरेंट एक तत्व है, तो बच्चा आमतौर पर एक element node, एक text node, या एक comment node होता है। यदि कोई बच्चा तत्व नहीं है तो यह null लौटाती है। |
| [getLocalName] इस नोड के योग्य नाम का स्थानीय भाग लौटाता है। किसी भी प्रकार के नोड्स के लिए, सिवाय [`ELEMENT_NODE`](./element_node/) और [`ATTRIBUTE_NODE`](./attribute_node/) के, और DOM Level 1 विधि जैसे [`Document.createElement()`](../document/createelement/) से निर्मित नोड्स के लिए, यह हमेशा null रहता है। |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI केवल-पढ़ने योग्य प्रॉपर्टी तत्व का पैकेज URI लौटाती है, या null यदि तत्व किसी पैकेज में नहीं है। |
| [getNextSibling] `Node` इंटरफ़ेस की केवल-पढ़ने योग्य nextSibling प्रॉपर्टी निर्दिष्ट नोड के बाद तुरंत आने वाले नोड को उसके पैरेंट के [`childNodes`](./childnodes/) में लौटाती है, या यदि निर्दिष्ट नोड पैरेंट तत्व में अंतिम बच्चा है तो null लौटाती है। |
| abstract [getNodeName] Node की केवल-पढ़ने योग्य nodeName प्रॉपर्टी वर्तमान नोड का नाम स्ट्रिंग के रूप में लौटाती है। |
| abstract [getNodeType] अंतर्निहित वस्तु के प्रकार को दर्शाने वाला कोड। |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | `Node` इंटरफ़ेस की nodeValue प्रॉपर्टी वर्तमान नोड का मान लौटाती या सेट करती है। |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) `Node` इंटरफ़ेस की केवल-पढ़ने योग्य ownerDocument प्रॉपर्टी नोड का शीर्ष-स्तरीय दस्तावेज़ ऑब्जेक्ट लौटाती है। |
| [getParentElement] `Node` इंटरफ़ेस की केवल-पढ़ने योग्य parentElement प्रॉपर्टी DOM नोड के पैरेंट [`Element`](../element/) को लौटाती है, या यदि नोड का कोई पैरेंट नहीं है या उसका पैरेंट DOM Element नहीं है तो null लौटाती है। |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) `Node` इंटरफ़ेस की केवल-पढ़ने योग्य parentNode प्रॉपर्टी DOM वृक्ष में निर्दिष्ट नोड के पैरेंट को लौटाती है। |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix केवल-पढ़ने योग्य प्रॉपर्टी निर्दिष्ट एलिमेंट का पैकेज प्रीफ़िक्स लौटाती है, या यदि कोई प्रीफ़िक्स निर्दिष्ट नहीं है तो null। |
| [getPreviousSibling] `Node` इंटरफ़ेस की केवल-पढ़ने योग्य previousSibling प्रॉपर्टी उसके पैरेंट के [`childNodes`](./firstchild/) सूची में निर्दिष्ट नोड से तुरंत पहले वाले नोड को लौटाती है, या यदि निर्दिष्ट नोड सूची में पहला है तो null लौटाती है। |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | `Node` इंटरफ़ेस की textContent प्रॉपर्टी नोड और उसके वंशजों की पाठ सामग्री को दर्शाती है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | addEventListener() मेथड [`EventTarget `](../eventtarget/) इंटरफ़ेस का एक फ़ंक्शन सेट करता है जो तब कॉल किया जाएगा जब निर्दिष्ट इवेंट लक्ष्य को दिया जाएगा। |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस एक फ़ंक्शन सेट करता है जो तब बुलाया जाएगा जब निर्दिष्ट इवेंट लक्ष्य को पहुँचाया जाता है। |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस एक फ़ंक्शन सेट करता है जो तब बुलाया जाएगा जब निर्दिष्ट इवेंट लक्ष्य को पहुँचाया जाता है। |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() मेथड Node इंटरफ़ेस का एक नोड को निर्दिष्ट पैरेंट नोड के बच्चों की सूची के अंत में जोड़ता है। यदि दिया गया चाइल्ड दस्तावेज़ में मौजूदा नोड का संदर्भ है, तो appendChild() उसे उसकी वर्तमान स्थिति से नई स्थिति में ले जाता है (किसी अन्य नोड में जोड़ने से पहले नोड को उसके पैरेंट नोड से हटाने की कोई आवश्यकता नहीं है)। |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode)() | cloneNode() मेथड Node इंटरफ़ेस का उस नोड की प्रतिलिपि लौटाता है जिस पर यह मेथड कॉल किया गया था। इसका पैरामीटर नियंत्रित करता है कि नोड में शामिल सबट्री भी क्लोन किया जाए या नहीं। |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode_1)(bool) | cloneNode() मेथड Node इंटरफ़ेस का उस नोड की प्रतिलिपि लौटाता है जिस पर यह मेथड कॉल किया गया था। इसका पैरामीटर नियंत्रित करता है कि नोड में शामिल सबट्री भी क्लोन किया जाए या नहीं। |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | `EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) पर निर्दिष्ट इवेंट को डिस्पैच करता है, (सिंक्रोनस रूप से) प्रभावित EventListeners को उचित क्रम में बुलाता है। सामान्य इवेंट प्रोसेसिंग नियम (कैप्चरिंग और वैकल्पिक बबलिंग चरण सहित) मैन्युअल रूप से [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) के साथ डिस्पैच किए गए इवेंट्स पर भी लागू होते हैं। |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | अनमैनेज्ड संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से जुड़े एप्लिकेशन-परिभाषित कार्यों को निष्पादित करता है। |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को प्राप्त करने के लिए उपयोग किया जाता है। |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Node इंटरफ़ेस की hasChildNodes() विधि एक बूलियन मान लौटाती है जो दर्शाता है कि दिया गया `Node` के पास बच्चा नोड्स हैं या नहीं। |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() मेथड Node इंटरफ़ेस का एक नोड को रेफ़रेंस नोड से पहले निर्दिष्ट पैरेंट नोड के चाइल्ड के रूप में सम्मिलित करता है। |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() मेथड Node इंटरफ़ेस का एक पैकेज URI को तर्क के रूप में स्वीकार करता है। यह एक बूलियन मान लौटाता है जो true होता है यदि पैकेज दिए गए नोड पर डिफ़ॉल्ट पैकेज है और नहीं तो false। |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | `Node` इंटरफ़ेस की isEqualNode() विधि जाँचती है कि दो नोड्स समान हैं या नहीं। दो नोड्स समान होते हैं जब उनका प्रकार, परिभाषित विशेषताएँ (तत्वों के लिए, यह उनका ID, बच्चों की संख्या, आदि) समान हों, उनके attributes मेल खाते हों, आदि। मिलनी वाली विशिष्ट डेटा बिंदुओं का सेट नोड्स के प्रकार पर निर्भर करता है। |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode() मेथड Node इंटरफ़ेस का === सख्त समानता ऑपरेटर का एक लेगेसी उपनाम है। अर्थात, यह परीक्षण करता है कि दो नोड्स समान हैं या नहीं (दूसरे शब्दों में, क्या वे एक ही ऑब्जेक्ट को संदर्भित करते हैं)। |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI() मेथड Node इंटरफ़ेस का एक प्रीफ़िक्स को पैरामीटर के रूप में लेता है और यदि मिला तो दिए गए नोड पर उससे संबंधित पैकेज URI लौटाता है (और यदि नहीं मिला तो null)। |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix() मेथड Node इंटरफ़ेस का एक स्ट्रिंग लौटाता है जिसमें दिए गए पैकेज URI के लिए प्रीफ़िक्स शामिल होता है, यदि मौजूद हो, अन्यथा null। जब कई प्रीफ़िक्स संभव हों, तो पहला प्रीफ़िक्स लौटाया जाता है। |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | इस Node के नीचे उप-ट्री की पूरी गहराई में सभी [`Text`](../text/) नोड्स, साथ ही attribute नोड्स, को एक "सामान्य" रूप में रखता है जहाँ केवल संरचना (जैसे, [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), और [`entity references`](../entityreference/)) ही [`Text`](../text/) नोड्स को अलग करती है, अर्थात् कोई सटे हुए Text नोड्स या खाली Text नोड्स नहीं होते। यह सुनिश्चित करने के लिए उपयोग किया जा सकता है कि दस्तावेज़ का DOM दृश्य उसी तरह हो जैसा कि इसे सहेजा और पुनः लोड किया गया हो, और यह उन ऑपरेशनों (जैसे XPointer [XPointer] लुकअप) के लिए उपयोगी है जो किसी विशेष दस्तावेज़ वृक्ष संरचना पर निर्भर होते हैं। यदि [`DOMConfiguration`](../../com.aspose.html/configuration/) ऑब्जेक्ट के पैरामीटर "normalize-characters" जो [`Node.ownerDocument`](./ownerdocument/) से जुड़ा है, true है, तो यह विधि Text नोड्स के अक्षरों को भी पूरी तरह सामान्य करेगी। |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node इंटरफ़ेस की removeChild() विधि DOM से एक चाइल्ड नोड हटाती है और हटाए गए नोड को लौटाती है। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | यह विधि इवेंट लक्ष्य से इवेंट लिस्नर को हटाने की अनुमति देती है। यदि इवेंट प्रोसेस हो रहा हो तो इवेंट लिस्नर को हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। Event Listeners को हटाए जाने के बाद कभी भी बुलाया नहीं जा सकता। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | यह विधि इवेंट लक्ष्य से इवेंट लिस्नर को हटाने की अनुमति देती है। यदि इवेंट प्रोसेस हो रहा हो तो इवेंट लिस्नर को हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। Event Listeners को हटाए जाने के बाद कभी भी बुलाया नहीं जा सकता। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | यह विधि इवेंट लक्ष्य से इवेंट लिस्नर को हटाने की अनुमति देती है। यदि इवेंट प्रोसेस हो रहा हो तो इवेंट लिस्नर को हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। Event Listeners को हटाए जाने के बाद कभी भी बुलाया नहीं जा सकता। |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | चाइल्ड नोड oldChild को सूची में newChild से बदलता है और oldChild नोड लौटाता है। यदि newChild एक [`DocumentFragment`](../documentfragment/) ऑब्जेक्ट है, तो oldChild को सभी [`DocumentFragment`](../documentfragment/) चाइल्ड्स से बदल दिया जाता है, जो उसी क्रम में डाले जाते हैं। यदि newChild पहले से ही ट्री में है, तो उसे पहले हटाया जाता है। |
| [toString](../../com.aspose.html.dom/node/toString/)() | इस उदाहरण का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [ATTRIBUTE_NODE](../../com.aspose.html.dom/node/attribute_node/) | एक [`Element`](../element/) का [`Attribute`](../attr/)। |
| const [CDATA_SECTION_NODE](../../com.aspose.html.dom/node/cdata_section_node/) | एक [`CDATASection`](../cdatasection/), जैसे &lt;!CDATA[[ … ]]&gt;। |
| const [COMMENT_NODE](../../com.aspose.html.dom/node/comment_node/) | एक [`Comment`](../comment/) नोड, जैसे &lt;!-- … --&gt;। |
| const [DOCUMENT_FRAGMENT_NODE](../../com.aspose.html.dom/node/document_fragment_node/) | एक [`DocumentFragment`](../documentfragment/) नोड। |
| const [DOCUMENT_NODE](../../com.aspose.html.dom/node/document_node/) | एक [`Document`](../document/) नोड। |
| const [DOCUMENT_TYPE_NODE](../../com.aspose.html.dom/node/document_type_node/) | एक [`DocumentType`](../documenttype/) नोड, जैसे &lt;!DOCTYPE html&gt;। |
| const [ELEMENT_NODE](../../com.aspose.html.dom/node/element_node/) | एक [`Element`](../element/) नोड जैसे &lt;p&gt; या &lt;div&gt;। |
| const [ENTITY_NODE](../../com.aspose.html.dom/node/entity_node/) | एक [`Entity`](../entity/) नोड। |
| const [ENTITY_REFERENCE_NODE](../../com.aspose.html.dom/node/entity_reference_node/) | एक [`EntityReference`](../entityreference/) नोड। |
| const [NOTATION_NODE](../../com.aspose.html.dom/node/notation_node/) | एक [`Notation`](../notation/) नोड |
| const [PROCESSING_INSTRUCTION_NODE](../../com.aspose.html.dom/node/processing_instruction_node/) | एक [`ProcessingInstruction`](../processinginstruction/) XML दस्तावेज़ का, जैसे &lt;?xml-stylesheet … ?&gt;। |
| const [TEXT_NODE](../../com.aspose.html.dom/node/text_node/) | वास्तविक [`Text`](../text/) एक [`Element`](../element/) या [`Attr`](../attr/) के अंदर। |

## Remarks

संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # interface-node](https://dom.spec.whatwg.org/#interface-node).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### संबंधित देखें

* class [EventTarget](../eventtarget/)
* interface [IXPathNSResolver](../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
