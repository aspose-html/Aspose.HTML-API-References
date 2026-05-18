---
title: "Node क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.Node क्लास। Node इंटरफ़ेस पूरे Document Object Model के लिए मुख्य डेटा टाइप है। यह दस्तावेज़ वृक्ष में एकल नोड का प्रतिनिधित्व करता है। जबकि Node इंटरफ़ेस को लागू करने वाले सभी वस्तुएँ बच्चों को संभालने के लिए मेथड्स प्रदान करती हैं, सभी वस्तुओं के पास बच्चे नहीं हो सकते। उदाहरण के लिए Text नोड्स के पास बच्चे नहीं हो सकते और ऐसे नोड्स में बच्चे जोड़ने से DOMException उत्पन्न होता है।"
type: docs

url: /hi/java/com.aspose.html.dom/node/
---
## Node class

Node इंटरफ़ेस पूरे Document Object Model के लिए मुख्य डेटा प्रकार है। यह दस्तावेज़ वृक्ष में एकल नोड का प्रतिनिधित्व करता है। जबकि सभी ऑब्जेक्ट जो Node इंटरफ़ेस को लागू करते हैं, बच्चों को संभालने के लिए मेथड्स उजागर करते हैं, सभी ऑब्जेक्ट जिनमें Node इंटरफ़ेस लागू है, उनके पास बच्चे नहीं हो सकते। उदाहरण के लिए, [`Text`](../text/) नोड्स के पास बच्चे नहीं हो सकते, और ऐसे नोड्स में बच्चों को जोड़ने से एक [`DOMException`](../domexception/) उत्पन्न होता है।

Attributes [`nodeName`](./nodename/), [`nodeValue`](./nodevalue/) और attributes को नोड जानकारी तक पहुँचने के लिए एक तंत्र के रूप में शामिल किया गया है, बिना विशिष्ट व्युत्पन्न इंटरफ़ेस में कास्ट किए। उन मामलों में जहाँ किसी विशिष्ट [`nodeType`](./nodetype/) के लिए इन attributes का स्पष्ट मैपिंग नहीं है (जैसे, [`Element`](../element/) के लिए nodeValue या [`Comment`](../comment/) के लिए attributes), यह null लौटाता है। ध्यान दें कि विशेषीकृत इंटरफ़ेस अतिरिक्त और अधिक सुविधाजनक तंत्र प्रदान कर सकते हैं ताकि संबंधित जानकारी को प्राप्त और सेट किया जा सके।

```java
public abstract class Node : EventTarget, IXPathNSResolver
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node इंटरफ़ेस की केवल-पढ़ने योग्य baseURI प्रॉपर्टी दस्तावेज़ में नोड को सम्मिलित करने वाले दस्तावेज़ का पूर्ण बेस URL लौटाती है। |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node इंटरफ़ेस की केवल-पढ़ने योग्य childNodes प्रॉपर्टी दिए गए तत्व के चाइल्ड नोड्स की एक लाइव [`NodeList`](../../com.aspose.html.collections/nodelist/) लौटाती है जहाँ पहला चाइल्ड नोड इंडेक्स 0 पर असाइन किया जाता है। चाइल्ड नोड्स में तत्व, टेक्स्ट और टिप्पणी शामिल हैं। |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) `Node` इंटरफ़ेस की read-only firstChild प्रॉपर्टी नोड के वृक्ष में पहला बच्चा लौटाती है, या यदि नोड के पास कोई बच्चा नहीं है तो null लौटाती है। |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) `Node` इंटरफ़ेस की read-only lastChild प्रॉपर्टी नोड का अंतिम बच्चा लौटाती है। यदि इसका पैरेंट एक element है, तो बच्चा सामान्यतः एक element node, एक text node, या एक comment node होता है। यदि कोई child elements नहीं हैं तो यह null लौटाती है। |
| [getLocalName](../../com.aspose.html.dom/node/localname/) यह नोड के योग्य नाम का स्थानीय भाग लौटाता है। किसी भी प्रकार के नोड के लिए जो [`ELEMENT_NODE`](./element_node/) और [`ATTRIBUTE_NODE`](./attribute_node/) के अलावा है और जो DOM Level 1 मेथड, जैसे [`Document.createElement()`](../document/createelement/) से बनाया गया है, यह हमेशा null होता है। |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI केवल-पढ़ने योग्य प्रॉपर्टी तत्व का पैकेज URI लौटाती है, या यदि तत्व किसी पैकेज में नहीं है तो null। |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) `Node` इंटरफ़ेस की read-only nextSibling प्रॉपर्टी निर्दिष्ट नोड के तुरंत बाद वाले नोड को उसके पैरेंट के [`childNodes`](./childnodes/) में लौटाती है, या यदि निर्दिष्ट नोड पैरेंट element में अंतिम बच्चा है तो null लौटाती है। |
| abstract [getNodeName](../../com.aspose.html.dom/node/nodename/) Node की read-only nodeName प्रॉपर्टी वर्तमान नोड का नाम एक String के रूप में लौटाती है। |
| abstract [getNodeType](../../com.aspose.html.dom/node/nodetype/) यह अंतर्निहित ऑब्जेक्ट के प्रकार को दर्शाने वाला कोड है। |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | `Node `इंटरफ़ेस की nodeValue प्रॉपर्टी वर्तमान नोड का मान लौटाती या सेट करती है। |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Node इंटरफ़ेस की केवल-पढ़ने योग्य ownerDocument प्रॉपर्टी नोड का टॉप-लेवल डॉक्यूमेंट ऑब्जेक्ट लौटाती है। |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) `Node` इंटरफ़ेस की read-only parentElement प्रॉपर्टी DOM नोड के पैरेंट [`Element`](../element/) को लौटाती है, या यदि नोड का कोई पैरेंट नहीं है या उसका पैरेंट DOM Element नहीं है तो null लौटाती है। |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Node इंटरफ़ेस की केवल-पढ़ने योग्य parentNode प्रॉपर्टी DOM वृक्ष में निर्दिष्ट नोड के पैरेंट को लौटाती है। |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix केवल-पढ़ने योग्य प्रॉपर्टी निर्दिष्ट तत्व का पैकेज प्रीफ़िक्स लौटाती है, या यदि कोई प्रीफ़िक्स निर्दिष्ट नहीं है तो null। |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) `Node` इंटरफ़ेस की read-only previousSibling प्रॉपर्टी निर्दिष्ट नोड के तुरंत पहले वाले नोड को उसके पैरेंट के [`childNodes`](./firstchild/) सूची में लौटाती है, या यदि निर्दिष्ट नोड उस सूची में पहला है तो null लौटाती है। |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | `Node` इंटरफ़ेस की textContent प्रॉपर्टी नोड और उसके वंशजों की पाठ सामग्री का प्रतिनिधित्व करती है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | [`EventTarget `](../eventtarget/) इंटरफ़ेस की addEventListener() मेथड एक फ़ंक्शन सेट करती है जो जब भी निर्दिष्ट इवेंट लक्ष्य को पहुँचाया जाता है, कॉल किया जाएगा। |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस का यह सेट करता है कि एक फ़ंक्शन को कॉल किया जाए जब भी निर्दिष्ट इवेंट लक्ष्य तक पहुँचाया जाता है। |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस का यह सेट करता है कि एक फ़ंक्शन को कॉल किया जाए जब भी निर्दिष्ट इवेंट लक्ष्य तक पहुँचाया जाता है। |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() मेथड Node इंटरफ़ेस का यह निर्दिष्ट पैरेंट नोड के बच्चों की सूची के अंत में एक नोड जोड़ता है। यदि दिया गया चाइल्ड दस्तावेज़ में मौजूदा नोड का संदर्भ है, तो appendChild() उसे उसकी वर्तमान स्थिति से नई स्थिति में ले जाता है (नोड को किसी अन्य नोड में जोड़ने से पहले पैरेंट नोड से हटाने की कोई आवश्यकता नहीं है)। |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode)() | cloneNode() मेथड Node इंटरफ़ेस का यह उस नोड की एक प्रतिलिपि लौटाता है जिस पर यह मेथड बुलाया गया था। इसका पैरामीटर नियंत्रित करता है कि नोड में निहित सबट्री भी क्लोन किया जाए या नहीं। |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode_1)(bool) | cloneNode() मेथड Node इंटरफ़ेस का यह उस नोड की एक प्रतिलिपि लौटाता है जिस पर यह मेथड बुलाया गया था। इसका पैरामीटर नियंत्रित करता है कि नोड में निहित सबट्री भी क्लोन किया जाए या नहीं। |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | निर्दिष्ट [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) पर एक इवेंट डिस्पैच करता है, (सिंक्रोनस रूप से) प्रभावित EventListeners को उचित क्रम में बुलाता है। सामान्य इवेंट प्रोसेसिंग नियम (कैप्चरिंग और वैकल्पिक बबलिंग चरण सहित) उन इवेंट्स पर भी लागू होते हैं जिन्हें मैन्युअली [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) से डिस्पैच किया जाता है। |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | ऐप्लिकेशन-परिभाषित कार्यों को निष्पादित करता है जो अनमैनेज्ड संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से संबंधित होते हैं। |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Node इंटरफ़ेस की hasChildNodes() मेथड एक बूलियन मान लौटाती है जो दर्शाता है कि दिया गया `Node` के पास बच्चे हैं या नहीं। |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() मेथड Node इंटरफ़ेस का यह निर्दिष्ट पैरेंट नोड के एक रेफ़रेंस नोड से पहले एक नोड को बच्चे के रूप में डालता है। |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() मेथड Node इंटरफ़ेस का यह पैकेज URI को आर्ग्यूमेंट के रूप में लेता है। यह बूलियन मान लौटाता है जो सत्य (true) होता है यदि पैकेज दिए गए नोड पर डिफ़ॉल्ट पैकेज हो और अन्यथा असत्य (false)। |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | `Node` इंटरफ़ेस की isEqualNode() मेथड परीक्षण करती है कि दो नोड समान हैं या नहीं। दो नोड समान होते हैं जब उनका प्रकार, परिभाषित विशेषताएँ (elements के लिए, उनका ID, बच्चों की संख्या आदि), उनके attributes मेल खाते हों, आदि। उन डेटा बिंदुओं का विशिष्ट सेट जो मेल खाना आवश्यक है, नोड के प्रकारों पर निर्भर करता है। |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode() मेथड Node इंटरफ़ेस का यह एक लेगेसी उपनाम है === सख्त समानता ऑपरेटर के लिए। यह परीक्षण करता है कि दो नोड्स एक ही हैं (अर्थात् वे एक ही ऑब्जेक्ट को रेफ़र करते हैं) या नहीं। |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI() मेथड Node इंटरफ़ेस का यह एक प्रीफ़िक्स को पैरामीटर के रूप में लेता है और यदि पाया जाता है तो दिए गए नोड पर उससे जुड़ा पैकेज URI लौटाता है (और न मिलने पर null)। |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix() मेथड Node इंटरफ़ेस का यह एक स्ट्रिंग लौटाता है जिसमें दिए गए पैकेज URI के लिए प्रीफ़िक्स होता है, यदि मौजूद हो, अन्यथा null। जब कई प्रीफ़िक्स संभव हों, तो पहला प्रीफ़िक्स लौटाया जाता है। |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | सभी [`Text`](../text/) नोड्स को इस Node के नीचे की उप-वृक्ष की पूरी गहराई में, attribute नोड्स सहित, एक \"normal\" रूप में रखता है जहाँ केवल संरचना (जैसे, [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), और [`entity references`](../entityreference/)) ही [`Text`](../text/) नोड्स को अलग करती है, अर्थात् न तो आसन्न Text नोड्स होते हैं और न ही खाली Text नोड्स। यह उपयोगी है ताकि दस्तावेज़ का DOM दृश्य उसी तरह हो जैसा कि इसे सहेजा और पुनः लोड किया गया हो, और यह उन ऑपरेशनों (जैसे XPointer [XPointer] लुकअप) के लिए उपयोगी है जो किसी विशिष्ट दस्तावेज़ वृक्ष संरचना पर निर्भर होते हैं। यदि [`DOMConfiguration`](../../com.aspose.html/configuration/) ऑब्जेक्ट के \"normalize-characters\" पैरामीटर, जो [`Node.ownerDocument`](./ownerdocument/) से जुड़ा है, true है, तो यह मेथड Text नोड्स के अक्षरों को भी पूरी तरह से सामान्यीकृत करेगा। |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node इंटरफ़ेस की removeChild() मेथड DOM से एक child node हटाती है और हटाए गए node को लौटाती है। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि कोई इवेंट लिस्नर इवेंट प्रोसेस हो रहा हो तो उसे हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। हटाए जाने के बाद इवेंट लिस्नर्स कभी भी कॉल नहीं किए जा सकते। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि कोई इवेंट लिस्नर इवेंट प्रोसेस हो रहा हो तो उसे हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। हटाए जाने के बाद इवेंट लिस्नर्स कभी भी कॉल नहीं किए जा सकते। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि कोई इवेंट लिस्नर इवेंट प्रोसेस हो रहा हो तो उसे हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। हटाए जाने के बाद इवेंट लिस्नर्स कभी भी कॉल नहीं किए जा सकते। |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | चाइल्ड नोड oldChild को newChild से बच्चों की सूची में बदलता है और oldChild नोड लौटाता है। यदि newChild एक [`DocumentFragment`](../documentfragment/) ऑब्जेक्ट है, तो oldChild को सभी [`DocumentFragment`](../documentfragment/) चाइल्ड्स से बदला जाता है, जो उसी क्रम में सम्मिलित होते हैं। यदि newChild पहले से ही ट्री में है, तो उसे पहले हटाया जाता है। |
| [toString](../../com.aspose.html.dom/node/toString/)() | इस उदाहरण का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [ATTRIBUTE_NODE](../../com.aspose.html.dom/node/attribute_node/) | एक [`Attribute`](../attr/) का एक [`Element`](../element/)। |
| const [CDATA_SECTION_NODE](../../com.aspose.html.dom/node/cdata_section_node/) | एक [`CDATASection`](../cdatasection/), जैसे &lt;!CDATA[[ … ]]&gt;। |
| const [COMMENT_NODE](../../com.aspose.html.dom/node/comment_node/) | एक [`Comment`](../comment/) नोड, जैसे &lt;!-- … --&gt;। |
| const [DOCUMENT_FRAGMENT_NODE](../../com.aspose.html.dom/node/document_fragment_node/) | एक [`DocumentFragment`](../documentfragment/) नोड। |
| const [DOCUMENT_NODE](../../com.aspose.html.dom/node/document_node/) | एक [`Document`](../document/) नोड। |
| const [DOCUMENT_TYPE_NODE](../../com.aspose.html.dom/node/document_type_node/) | एक [`DocumentType`](../documenttype/) नोड, जैसे &lt;!DOCTYPE html&gt;। |
| const [ELEMENT_NODE](../../com.aspose.html.dom/node/element_node/) | एक [`Element`](../element/) नोड जैसे &lt;p&gt; या &lt;div&gt;। |
| const [ENTITY_NODE](../../com.aspose.html.dom/node/entity_node/) | एक [`Entity`](../entity/) नोड। |
| const [ENTITY_REFERENCE_NODE](../../com.aspose.html.dom/node/entity_reference_node/) | एक [`EntityReference`](../entityreference/) नोड। |
| const [NOTATION_NODE](../../com.aspose.html.dom/node/notation_node/) | एक [`Notation`](../notation/) नोड। |
| const [PROCESSING_INSTRUCTION_NODE](../../com.aspose.html.dom/node/processing_instruction_node/) | एक [`ProcessingInstruction`](../processinginstruction/) XML दस्तावेज़ का, जैसे &lt;?xml-stylesheet … ?&gt;. |
| const [TEXT_NODE](../../com.aspose.html.dom/node/text_node/) | वास्तविक [`Text`](../text/) जो एक [`Element`](../element/) या [`Attr`](../attr/) के अंदर है। |

## टिप्पणियाँ

संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # interface-node](https://dom.spec.whatwg.org/#interface-node).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### संबंधित देखें

* class [EventTarget](../eventtarget/)
* interface [IXPathNSResolver](../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
