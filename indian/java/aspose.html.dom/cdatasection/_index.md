---
title: "CDATASection वर्ग"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.dom.CDATASection वर्ग। CDATA सेक्शन का उपयोग उन टेक्स्ट ब्लॉकों को एस्केप करने के लिए किया जाता है जिनमें ऐसे अक्षर होते हैं जिन्हें अन्यथा मार्कअप माना जाता है।"
type: docs

url: /hi/java/com.aspose.html.dom/cdatasection/
---
## CDATASection class

CDATA सेक्शन का उपयोग उन टेक्स्ट ब्लॉकों को एस्केप करने के लिए किया जाता है जिनमें ऐसे अक्षर होते हैं जिन्हें अन्यथा मार्कअप माना जाता।

```java
public class CDATASection : Text
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node इंटरफ़ेस की केवल-पढ़ने योग्य baseURI प्रॉपर्टी वह पूर्ण बेस URL लौटाती है जो नोड को सम्मिलित दस्तावेज़ का है। |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node इंटरफ़ेस की केवल-पढ़ने योग्य childNodes प्रॉपर्टी दिए गए तत्व के चाइल्ड नोड्स की एक लाइव [`NodeList`](../../com.aspose.html.collections/nodelist/) लौटाती है जहाँ पहला चाइल्ड नोड इंडेक्स 0 पर होता है। चाइल्ड नोड्स में तत्व, टेक्स्ट और टिप्पणी शामिल हैं। |
| [data](../../com.aspose.html.dom/characterdata/data/) { get; set; } | इस इंटरफ़ेस को लागू करने वाले नोड का वर्ण डेटा। |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) केवल-पढ़ने योग्य firstChild प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस नोड के ट्री में पहला चाइल्ड लौटाती है, या यदि नोड के कोई चाइल्ड नहीं हैं तो null। |
| [getIsElementContentWhitespace](../../com.aspose.html.dom/text/iselementcontentwhitespace/) यह लौटाता है कि क्या यह टेक्स्ट नोड तत्व सामग्री व्हाइटस्पेस रखता है, जिसे अक्सर अनुचित रूप से "अवहेलनीय व्हाइटस्पेस" कहा जाता है। |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) केवल-पढ़ने योग्य lastChild प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस नोड का अंतिम चाइल्ड लौटाती है। यदि इसका पैरेंट एक तत्व है, तो चाइल्ड आमतौर पर एक element नोड, एक टेक्स्ट नोड, या एक कमेंट नोड होता है। यदि कोई चाइल्ड तत्व नहीं हैं तो यह null लौटाता है। |
| [getLength](../../com.aspose.html.dom/characterdata/length/) डेटा और नीचे के subStringData मेथड के माध्यम से उपलब्ध 16-बिट इकाइयों की संख्या। यह शून्य भी हो सकता है, अर्थात् CharacterData नोड्स खाली हो सकते हैं। |
| [getLocalName](../../com.aspose.html.dom/node/localname/) इस नोड के योग्य नाम का स्थानीय भाग लौटाता है। किसी भी प्रकार के नोड्स के लिए, जो [`ELEMENT_NODE`](../node/element_node/) और [`ATTRIBUTE_NODE`](../node/attribute_node/) नहीं हैं, और जो DOM Level 1 विधि जैसे [`Document.createElement()`](../document/createelement/) से बनाए गए हैं, यह हमेशा null होता है। |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI केवल-पढ़ने योग्य प्रॉपर्टी तत्व का पैकेज URI लौटाती है, या null यदि तत्व किसी पैकेज में नहीं है। |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) केवल-पढ़ने योग्य nextSibling प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस का निर्दिष्ट नोड के बाद तुरंत आने वाला नोड उसके पैरेंट के [`childNodes`](../node/childnodes/) में लौटाती है, या यदि निर्दिष्ट नोड पैरेंट तत्व में अंतिम चाइल्ड है तो null लौटाती है। |
| [getNodeName](../../com.aspose.html.dom/cdatasection/nodename/) इस नोड का नाम, उसके प्रकार पर निर्भर करता है। |
| [getNodeType](../../com.aspose.html.dom/cdatasection/nodetype/) अधोस्त वस्तु के प्रकार को दर्शाने वाला कोड। |
| [nodeValue](../../com.aspose.html.dom/text/nodevalue/) { get; set; } | इस नोड का मान, उसके प्रकार पर निर्भर करता है। |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) `Node` इंटरफ़ेस की केवल-पढ़ने योग्य ownerDocument प्रॉपर्टी नोड का शीर्ष-स्तरीय दस्तावेज़ ऑब्जेक्ट लौटाती है। |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) केवल-पढ़ने योग्य parentElement प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस का DOM नोड का पैरेंट [`Element`](../element/) लौटाती है, या यदि नोड का कोई पैरेंट नहीं है या उसका पैरेंट DOM Element नहीं है तो null। |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) `Node` इंटरफ़ेस की केवल-पढ़ने योग्य parentNode प्रॉपर्टी DOM वृक्ष में निर्दिष्ट नोड के पैरेंट को लौटाती है। |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix केवल-पढ़ने योग्य प्रॉपर्टी निर्दिष्ट एलिमेंट का पैकेज प्रीफ़िक्स लौटाती है, या यदि कोई प्रीफ़िक्स निर्दिष्ट नहीं है तो null। |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) केवल-पढ़ने योग्य previousSibling प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस का निर्दिष्ट नोड से पहले तुरंत आने वाला नोड उसके पैरेंट के [`childNodes`](../node/firstchild/) सूची में लौटाती है, या यदि निर्दिष्ट नोड सूची में पहला है तो null। |
| [textContent](../../com.aspose.html.dom/text/textcontent/) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new String is not empty or null, replaced by a single Text node containing the String this attribute is set to. |
| [getWholeText](../../com.aspose.html.dom/text/wholetext/) इस नोड के तर्कसंगत रूप से सटे हुए Text नोड्स का सभी पाठ, दस्तावेज़ क्रम में संयोजित करके लौटाता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | addEventListener() मेथड [`EventTarget `](../eventtarget/) इंटरफ़ेस का एक फ़ंक्शन सेट करता है जो तब कॉल किया जाएगा जब निर्दिष्ट इवेंट लक्ष्य को दिया जाएगा। |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस एक फ़ंक्शन सेट करता है जो तब बुलाया जाएगा जब निर्दिष्ट इवेंट लक्ष्य को पहुँचाया जाता है। |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस एक फ़ंक्शन सेट करता है जो तब बुलाया जाएगा जब निर्दिष्ट इवेंट लक्ष्य को पहुँचाया जाता है। |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() मेथड Node इंटरफ़ेस का एक नोड को निर्दिष्ट पैरेंट नोड के बच्चों की सूची के अंत में जोड़ता है। यदि दिया गया चाइल्ड दस्तावेज़ में मौजूदा नोड का संदर्भ है, तो appendChild() उसे उसकी वर्तमान स्थिति से नई स्थिति में ले जाता है (किसी अन्य नोड में जोड़ने से पहले नोड को उसके पैरेंट नोड से हटाने की कोई आवश्यकता नहीं है)। |
| [appendData](../../com.aspose.html.dom/characterdata/appenddata/)(String) | नोड के वर्ण डेटा के अंत में स्ट्रिंग जोड़ें। |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode() मेथड Node इंटरफ़ेस का उस नोड की प्रतिलिपि लौटाता है जिस पर यह मेथड कॉल किया गया था। इसका पैरामीटर नियंत्रित करता है कि नोड में शामिल सबट्री भी क्लोन किया जाए या नहीं। |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode() मेथड Node इंटरफ़ेस का उस नोड की प्रतिलिपि लौटाता है जिस पर यह मेथड कॉल किया गया था। इसका पैरामीटर नियंत्रित करता है कि नोड में शामिल सबट्री भी क्लोन किया जाए या नहीं। |
| [deleteData](../../com.aspose.html.dom/characterdata/deletedata/)(int, int) | नोड से 16-बिट इकाइयों की एक रेंज हटाएँ। |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | `EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) पर निर्दिष्ट इवेंट को डिस्पैच करता है, (सिंक्रोनस रूप से) प्रभावित EventListeners को उचित क्रम में बुलाता है। सामान्य इवेंट प्रोसेसिंग नियम (कैप्चरिंग और वैकल्पिक बबलिंग चरण सहित) मैन्युअल रूप से [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) के साथ डिस्पैच किए गए इवेंट्स पर भी लागू होते हैं। |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | अनमैनेज्ड संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से जुड़े एप्लिकेशन-परिभाषित कार्यों को निष्पादित करता है। |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को प्राप्त करने के लिए उपयोग किया जाता है। |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | `hasChildNodes()` मेथड Node इंटरफ़ेस का एक बूलियन मान लौटाता है जो दर्शाता है कि दिया गया [`Node`](../node/) के पास चाइल्ड नोड्स हैं या नहीं। |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() मेथड Node इंटरफ़ेस का एक नोड को रेफ़रेंस नोड से पहले निर्दिष्ट पैरेंट नोड के चाइल्ड के रूप में सम्मिलित करता है। |
| [insertData](../../com.aspose.html.dom/characterdata/insertdata/)(int, String) | निर्दिष्ट 16-बिट इकाई ऑफसेट पर स्ट्रिंग डालें। |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() मेथड Node इंटरफ़ेस का एक पैकेज URI को तर्क के रूप में स्वीकार करता है। यह एक बूलियन मान लौटाता है जो true होता है यदि पैकेज दिए गए नोड पर डिफ़ॉल्ट पैकेज है और नहीं तो false। |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | `isEqualNode()` मेथड [`Node`](../node/) इंटरफ़ेस का दो नोड्स समान हैं या नहीं परीक्षण करता है। दो नोड्स समान होते हैं जब उनका प्रकार, परिभाषित विशेषताएँ (तत्वों के लिए, उनका ID, चाइल्ड की संख्या आदि), उनके गुण (attributes) मेल खाते हों, आदि। मिलान करने वाले डेटा बिंदुओं का विशिष्ट सेट नोड्स के प्रकार पर निर्भर करता है। |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode() मेथड Node इंटरफ़ेस का === सख्त समानता ऑपरेटर का एक लेगेसी उपनाम है। अर्थात, यह परीक्षण करता है कि दो नोड्स समान हैं या नहीं (दूसरे शब्दों में, क्या वे एक ही ऑब्जेक्ट को संदर्भित करते हैं)। |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI() मेथड Node इंटरफ़ेस का एक प्रीफ़िक्स को पैरामीटर के रूप में लेता है और यदि मिला तो दिए गए नोड पर उससे संबंधित पैकेज URI लौटाता है (और यदि नहीं मिला तो null)। |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix() मेथड Node इंटरफ़ेस का एक स्ट्रिंग लौटाता है जिसमें दिए गए पैकेज URI के लिए प्रीफ़िक्स शामिल होता है, यदि मौजूद हो, अन्यथा null। जब कई प्रीफ़िक्स संभव हों, तो पहला प्रीफ़िक्स लौटाया जाता है। |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | सभी [`Text`](../text/) नोड्स को इस नोड के नीचे स्थित उप‑वृक्ष की पूरी गहराई में, एट्रिब्यूट नोड्स सहित, एक "सामान्य" रूप में रखता है जहाँ केवल संरचना (जैसे, [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), `CDATA sections`, और [`entity references`](../entityreference/)) [`Text`](../text/) नोड्स को अलग करती है, अर्थात् न तो सन्निकट Text नोड्स होते हैं और न ही खाली Text नोड्स। यह उपयोग किया जा सकता है ताकि किसी दस्तावेज़ का DOM दृश्य उसी तरह हो जैसा कि वह सहेजा गया हो और पुनः लोड किया गया हो, और यह तब उपयोगी होता है जब ऐसी क्रियाएँ (जैसे XPointer [XPointer] लुकअप) जो किसी विशिष्ट दस्तावेज़ वृक्ष संरचना पर निर्भर करती हैं, उपयोग में लाई जानी हों। यदि [`DOMConfiguration`](../../com.aspose.html/configuration/) ऑब्जेक्ट के "normalize-characters" पैरामीटर का मान true है, जो [`Node.ownerDocument`](../node/ownerdocument/) से जुड़ा है, तो यह मेथड Text नोड्स के अक्षरों को भी पूरी तरह सामान्यीकृत कर देगा। |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node इंटरफ़ेस की removeChild() विधि DOM से एक चाइल्ड नोड हटाती है और हटाए गए नोड को लौटाती है। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | यह विधि इवेंट लक्ष्य से इवेंट लिस्नर को हटाने की अनुमति देती है। यदि इवेंट प्रोसेस हो रहा हो तो इवेंट लिस्नर को हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। Event Listeners को हटाए जाने के बाद कभी भी बुलाया नहीं जा सकता। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | यह विधि इवेंट लक्ष्य से इवेंट लिस्नर को हटाने की अनुमति देती है। यदि इवेंट प्रोसेस हो रहा हो तो इवेंट लिस्नर को हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। Event Listeners को हटाए जाने के बाद कभी भी बुलाया नहीं जा सकता। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | यह विधि इवेंट लक्ष्य से इवेंट लिस्नर को हटाने की अनुमति देती है। यदि इवेंट प्रोसेस हो रहा हो तो इवेंट लिस्नर को हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। Event Listeners को हटाए जाने के बाद कभी भी बुलाया नहीं जा सकता। |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | चाइल्ड नोड oldChild को सूची में newChild से बदलता है और oldChild नोड लौटाता है। यदि newChild एक [`DocumentFragment`](../documentfragment/) ऑब्जेक्ट है, तो oldChild को सभी [`DocumentFragment`](../documentfragment/) चाइल्ड्स से बदल दिया जाता है, जो उसी क्रम में डाले जाते हैं। यदि newChild पहले से ही ट्री में है, तो उसे पहले हटाया जाता है। |
| [replaceData](../../com.aspose.html.dom/characterdata/replacedata/)(int, int, String) | निर्दिष्ट 16-बिट इकाई ऑफसेट से शुरू होने वाले अक्षरों को निर्दिष्ट स्ट्रिंग से बदलें। |
| [replaceWholeText](../../com.aspose.html.dom/text/replacewholetext/)(String) | वर्तमान नोड और सभी तर्कसंगत‑सन्निकट टेक्स्ट नोड्स के टेक्स्ट को निर्दिष्ट टेक्स्ट से बदल देता है। सभी तर्कसंगत‑सन्निकट टेक्स्ट नोड्स हटा दिए जाते हैं, जिसमें वर्तमान नोड भी शामिल है, जब तक कि वह प्रतिस्थापन टेक्स्ट का प्राप्तकर्ता न हो। |
| [splitText](../../com.aspose.html.dom/text/splittext/)(int) | निर्दिष्ट ऑफ़सेट पर इस नोड को दो नोड्स में विभाजित करता है, दोनों को पेड़ में भाई‑बहन के रूप में रखता है। |
| [subStringData](../../com.aspose.html.dom/characterdata/subStringdata/)(int, int) | नोड से डेटा की एक रेंज निकालता है। |
| [toString](../../com.aspose.html.dom/characterdata/toString/)() | इस उदाहरण का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |

### संबंधित देखें

* class [Text](../text/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
