---
title: "ShadowRoot क्लास"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.ShadowRoot क्लास। ShadowRoot शैडो ट्री का रूट नोड है।"
type: docs

url: /hi/java/com.aspose.html.dom/shadowroot/
---
## ShadowRoot class

ShadowRoot शैडो ट्री का मूल नोड है।

```java
public class ShadowRoot : DocumentFragment
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node इंटरफ़ेस की केवल-पढ़ने योग्य baseURI प्रॉपर्टी वह पूर्ण बेस URL लौटाती है जो नोड को सम्मिलित दस्तावेज़ का है। |
| [getChildElementCount](../../com.aspose.html.dom/documentfragment/childelementcount/) वर्तमान में इस तत्व के बच्चों के रूप में मौजूद तत्व नोड्स की संख्या लौटाता है। यदि इस तत्व के पास nodeType 1 के कोई चाइल्ड नोड नहीं हैं तो 0। |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node इंटरफ़ेस की केवल-पढ़ने योग्य childNodes प्रॉपर्टी दिए गए तत्व के चाइल्ड नोड्स की एक लाइव [`NodeList`](../../com.aspose.html.collections/nodelist/) लौटाती है जहाँ पहला चाइल्ड नोड इंडेक्स 0 पर होता है। चाइल्ड नोड्स में तत्व, टेक्स्ट और टिप्पणी शामिल हैं। |
| [getChildren](../../com.aspose.html.dom/documentfragment/children/) वर्तमान तत्व के चाइल्ड एलिमेंट्स लौटाता है। |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) केवल-पढ़ने योग्य firstChild प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस नोड के ट्री में पहला चाइल्ड लौटाती है, या यदि नोड के कोई चाइल्ड नहीं हैं तो null। |
| [getFirstElementChild](../../com.aspose.html.dom/documentfragment/firstelementchild/) इस तत्व का पहला चाइल्ड एलिमेंट नोड लौटाता है। यदि इस तत्व के पास कोई चाइल्ड एलिमेंट नहीं हैं तो null। |
| [getHost](../../com.aspose.html.dom/shadowroot/host/) Host वह एलिमेंट है जो इस ShadowRoot को सम्मिलित करता है। |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) केवल-पढ़ने योग्य lastChild प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस नोड का अंतिम चाइल्ड लौटाती है। यदि इसका पैरेंट एक तत्व है, तो चाइल्ड आमतौर पर एक element नोड, एक टेक्स्ट नोड, या एक कमेंट नोड होता है। यदि कोई चाइल्ड तत्व नहीं हैं तो यह null लौटाता है। |
| [getLastElementChild](../../com.aspose.html.dom/documentfragment/lastelementchild/) इस तत्व का अंतिम चाइल्ड एलिमेंट नोड लौटाता है। यदि इस तत्व के पास कोई चाइल्ड एलिमेंट नहीं हैं तो null। |
| [getLocalName](../../com.aspose.html.dom/node/localname/) इस नोड के योग्य नाम का स्थानीय भाग लौटाता है। किसी भी प्रकार के नोड्स के लिए, जो [`ELEMENT_NODE`](../node/element_node/) और [`ATTRIBUTE_NODE`](../node/attribute_node/) नहीं हैं, और जो DOM Level 1 विधि जैसे [`Document.createElement()`](../document/createelement/) से बनाए गए हैं, यह हमेशा null होता है। |
| [getMode](../../com.aspose.html.dom/shadowroot/mode/) वह मोड जिसमें यह ShadowRoot कार्य करता है। |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI केवल-पढ़ने योग्य प्रॉपर्टी तत्व का पैकेज URI लौटाती है, या null यदि तत्व किसी पैकेज में नहीं है। |
| [getNextElementSibling](../../com.aspose.html.dom/documentfragment/nextelementsibling/) इस तत्व का अगला सिब्लिंग एलिमेंट नोड लौटाता है। यदि दस्तावेज़ ट्री में इस तत्व के बाद कोई एलिमेंट सिब्लिंग नोड नहीं है तो null। |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) केवल-पढ़ने योग्य nextSibling प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस का निर्दिष्ट नोड के बाद तुरंत आने वाला नोड उसके पैरेंट के [`childNodes`](../node/childnodes/) में लौटाती है, या यदि निर्दिष्ट नोड पैरेंट तत्व में अंतिम चाइल्ड है तो null लौटाती है। |
| [getNodeName](../../com.aspose.html.dom/documentfragment/nodename/) इस नोड का नाम, उसके प्रकार के आधार पर। |
| [getNodeType](../../com.aspose.html.dom/documentfragment/nodetype/) अधोस्तित वस्तु के प्रकार को दर्शाने वाला कोड। |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | वर्तमान नोड का मान लौटाने या सेट करने के लिए [`Node `](../node/) इंटरफ़ेस की nodeValue प्रॉपर्टी। |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) `Node` इंटरफ़ेस की केवल-पढ़ने योग्य ownerDocument प्रॉपर्टी नोड का शीर्ष-स्तरीय दस्तावेज़ ऑब्जेक्ट लौटाती है। |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) केवल-पढ़ने योग्य parentElement प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस का DOM नोड का पैरेंट [`Element`](../element/) लौटाती है, या यदि नोड का कोई पैरेंट नहीं है या उसका पैरेंट DOM Element नहीं है तो null। |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) `Node` इंटरफ़ेस की केवल-पढ़ने योग्य parentNode प्रॉपर्टी DOM वृक्ष में निर्दिष्ट नोड के पैरेंट को लौटाती है। |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix केवल-पढ़ने योग्य प्रॉपर्टी निर्दिष्ट एलिमेंट का पैकेज प्रीफ़िक्स लौटाती है, या यदि कोई प्रीफ़िक्स निर्दिष्ट नहीं है तो null। |
| [getPreviousElementSibling](../../com.aspose.html.dom/documentfragment/previouselementsibling/) इस तत्व का पूर्ववर्ती सिब्लिंग एलिमेंट नोड लौटाता है। यदि दस्तावेज़ ट्री में इस तत्व से पहले कोई एलिमेंट सिब्लिंग नोड नहीं है तो null। |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) केवल-पढ़ने योग्य previousSibling प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस का निर्दिष्ट नोड से पहले तुरंत आने वाला नोड उसके पैरेंट के [`childNodes`](../node/firstchild/) सूची में लौटाती है, या यदि निर्दिष्ट नोड सूची में पहला है तो null। |
| [textContent](../../com.aspose.html.dom/documentfragment/textcontent/) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new String is not empty or null, replaced by a single Text node containing the String this attribute is set to. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | addEventListener() मेथड [`EventTarget `](../eventtarget/) इंटरफ़ेस का एक फ़ंक्शन सेट करता है जो तब कॉल किया जाएगा जब निर्दिष्ट इवेंट लक्ष्य को दिया जाएगा। |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस एक फ़ंक्शन सेट करता है जो तब बुलाया जाएगा जब निर्दिष्ट इवेंट लक्ष्य को पहुँचाया जाता है। |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस एक फ़ंक्शन सेट करता है जो तब बुलाया जाएगा जब निर्दिष्ट इवेंट लक्ष्य को पहुँचाया जाता है। |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() मेथड Node इंटरफ़ेस का एक नोड को निर्दिष्ट पैरेंट नोड के बच्चों की सूची के अंत में जोड़ता है। यदि दिया गया चाइल्ड दस्तावेज़ में मौजूदा नोड का संदर्भ है, तो appendChild() उसे उसकी वर्तमान स्थिति से नई स्थिति में ले जाता है (किसी अन्य नोड में जोड़ने से पहले नोड को उसके पैरेंट नोड से हटाने की कोई आवश्यकता नहीं है)। |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode() मेथड Node इंटरफ़ेस का उस नोड की प्रतिलिपि लौटाता है जिस पर यह मेथड कॉल किया गया था। इसका पैरामीटर नियंत्रित करता है कि नोड में शामिल सबट्री भी क्लोन किया जाए या नहीं। |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode() मेथड Node इंटरफ़ेस का उस नोड की प्रतिलिपि लौटाता है जिस पर यह मेथड कॉल किया गया था। इसका पैरामीटर नियंत्रित करता है कि नोड में शामिल सबट्री भी क्लोन किया जाए या नहीं। |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | `EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) पर निर्दिष्ट इवेंट को डिस्पैच करता है, (सिंक्रोनस रूप से) प्रभावित EventListeners को उचित क्रम में बुलाता है। सामान्य इवेंट प्रोसेसिंग नियम (कैप्चरिंग और वैकल्पिक बबलिंग चरण सहित) मैन्युअल रूप से [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) के साथ डिस्पैच किए गए इवेंट्स पर भी लागू होते हैं। |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | अनमैनेज्ड संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से जुड़े एप्लिकेशन-परिभाषित कार्यों को निष्पादित करता है। |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को प्राप्त करने के लिए उपयोग किया जाता है। |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | `hasChildNodes()` मेथड Node इंटरफ़ेस का एक बूलियन मान लौटाता है जो दर्शाता है कि दिया गया [`Node`](../node/) के पास चाइल्ड नोड्स हैं या नहीं। |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() मेथड Node इंटरफ़ेस का एक नोड को रेफ़रेंस नोड से पहले निर्दिष्ट पैरेंट नोड के चाइल्ड के रूप में सम्मिलित करता है। |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() मेथड Node इंटरफ़ेस का एक पैकेज URI को तर्क के रूप में स्वीकार करता है। यह एक बूलियन मान लौटाता है जो true होता है यदि पैकेज दिए गए नोड पर डिफ़ॉल्ट पैकेज है और नहीं तो false। |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | `isEqualNode()` मेथड [`Node`](../node/) इंटरफ़ेस का दो नोड्स समान हैं या नहीं परीक्षण करता है। दो नोड्स समान होते हैं जब उनका प्रकार, परिभाषित विशेषताएँ (तत्वों के लिए, उनका ID, चाइल्ड की संख्या आदि), उनके गुण (attributes) मेल खाते हों, आदि। मिलान करने वाले डेटा बिंदुओं का विशिष्ट सेट नोड्स के प्रकार पर निर्भर करता है। |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode() मेथड Node इंटरफ़ेस का === सख्त समानता ऑपरेटर का एक लेगेसी उपनाम है। अर्थात, यह परीक्षण करता है कि दो नोड्स समान हैं या नहीं (दूसरे शब्दों में, क्या वे एक ही ऑब्जेक्ट को संदर्भित करते हैं)। |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI() मेथड Node इंटरफ़ेस का एक प्रीफ़िक्स को पैरामीटर के रूप में लेता है और यदि मिला तो दिए गए नोड पर उससे संबंधित पैकेज URI लौटाता है (और यदि नहीं मिला तो null)। |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix() मेथड Node इंटरफ़ेस का एक स्ट्रिंग लौटाता है जिसमें दिए गए पैकेज URI के लिए प्रीफ़िक्स शामिल होता है, यदि मौजूद हो, अन्यथा null। जब कई प्रीफ़िक्स संभव हों, तो पहला प्रीफ़िक्स लौटाया जाता है। |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | सभी [`Text`](../text/) नोड्स को इस Node के नीचे सब‑ट्री की पूरी गहराई में, गुण (attribute) नोड्स सहित, एक "सामान्य" रूप में रखता है जहाँ केवल संरचना (जैसे, [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), और [`entity references`](../entityreference/)) ही [`Text`](../text/) नोड्स को अलग करती है, अर्थात कोई सटे हुए Text नोड्स या खाली Text नोड्स नहीं होते। इसका उपयोग यह सुनिश्चित करने के लिए किया जा सकता है कि दस्तावेज़ का DOM दृश्य उसी तरह हो जैसा कि इसे सहेजा और पुनः लोड किया गया हो, और यह उन ऑपरेशनों (जैसे XPointer [XPointer] लुकअप) के लिए उपयोगी है जो किसी विशिष्ट दस्तावेज़ ट्री संरचना पर निर्भर होते हैं। यदि [`DOMConfiguration`](../../com.aspose.html/configuration/) ऑब्जेक्ट के "normalize-characters" पैरामीटर, जो [`Node.ownerDocument`](../node/ownerdocument/) से जुड़ा है, true है, तो यह मेथड Text नोड्स के अक्षरों को भी पूरी तरह सामान्य करेगा। |
| [querySelector](../../com.aspose.html.dom/documentfragment/queryselector/)(String) | दस्तावेज़ में पहला तत्व लौटाता है, जो चयनकर्ता से मेल खाता है। |
| [querySelectorAll](../../com.aspose.html.dom/documentfragment/queryselectorall/)(String) | दस्तावेज़ में सभी तत्वों की एक NodeList लौटाता है, जो चयनकर्ता से मेल खाते हैं। |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node इंटरफ़ेस की removeChild() विधि DOM से एक चाइल्ड नोड हटाती है और हटाए गए नोड को लौटाती है। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | यह विधि इवेंट लक्ष्य से इवेंट लिस्नर को हटाने की अनुमति देती है। यदि इवेंट प्रोसेस हो रहा हो तो इवेंट लिस्नर को हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। Event Listeners को हटाए जाने के बाद कभी भी बुलाया नहीं जा सकता। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | यह विधि इवेंट लक्ष्य से इवेंट लिस्नर को हटाने की अनुमति देती है। यदि इवेंट प्रोसेस हो रहा हो तो इवेंट लिस्नर को हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। Event Listeners को हटाए जाने के बाद कभी भी बुलाया नहीं जा सकता। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | यह विधि इवेंट लक्ष्य से इवेंट लिस्नर को हटाने की अनुमति देती है। यदि इवेंट प्रोसेस हो रहा हो तो इवेंट लिस्नर को हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। Event Listeners को हटाए जाने के बाद कभी भी बुलाया नहीं जा सकता। |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | चाइल्ड नोड oldChild को सूची में newChild से बदलता है और oldChild नोड लौटाता है। यदि newChild एक [`DocumentFragment`](../documentfragment/) ऑब्जेक्ट है, तो oldChild को सभी [`DocumentFragment`](../documentfragment/) चाइल्ड्स से बदल दिया जाता है, जो उसी क्रम में डाले जाते हैं। यदि newChild पहले से ही ट्री में है, तो उसे पहले हटाया जाता है। |
| [toString](../../com.aspose.html.dom/node/toString/)() | इस उदाहरण का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |

### संबंधित देखें

* class [DocumentFragment](../documentfragment/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
