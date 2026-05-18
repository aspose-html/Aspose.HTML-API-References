---
title: "Element क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.Element क्लास। Element इंटरफ़ेस HTML या XML दस्तावेज़ में एक तत्व को दर्शाता है।"
type: docs

url: /hi/java/com.aspose.html.dom/element/
---
## Element class

Element इंटरफ़ेस HTML या XML दस्तावेज़ में एक तत्व का प्रतिनिधित्व करता है।

```java
public class Element : Node, IChildNode, IParentNode
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Element](element/)(QualifiedName, Document) | `Element` क्लास का नया इंस्टेंस प्रारंभ करता है। इस कंस्ट्रक्टर को सीधे न बुलाएँ, बल्कि [`CreateElement`](../document/createelement/) या [`CreateElementNS`](../document/createelementns/) का उपयोग करें। |

## गुण

| नाम | विवरण |
| --- | --- |
| [getAttributes](../../com.aspose.html.dom/element/attributes/) एक NamedNodeMap जिसमें इस नोड के गुण होते हैं (यदि यह एक Element है) या अन्यथा null। |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node इंटरफ़ेस की केवल-पढ़ने योग्य baseURI प्रॉपर्टी दस्तावेज़ में नोड को सम्मिलित करने वाले दस्तावेज़ का पूर्ण बेस URL लौटाती है। |
| [getChildElementCount](../../com.aspose.html.dom/element/childelementcount/) इस तत्व के बच्चों के रूप में मौजूद तत्व नोड्स की वर्तमान संख्या लौटाता है। यदि इस तत्व के कोई बच्चे नहीं हैं जिनका nodeType 1 है तो 0। |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node इंटरफ़ेस की केवल-पढ़ने योग्य childNodes प्रॉपर्टी दिए गए तत्व के चाइल्ड नोड्स की एक लाइव [`NodeList`](../../com.aspose.html.collections/nodelist/) लौटाती है जहाँ पहला चाइल्ड नोड इंडेक्स 0 पर असाइन किया जाता है। चाइल्ड नोड्स में तत्व, टेक्स्ट और टिप्पणी शामिल हैं। |
| [getChildren](../../com.aspose.html.dom/element/children/) वर्तमान तत्व के चाइल्ड तत्वों को लौटाता है। |
| [getClassList](../../com.aspose.html.dom/element/classlist/) एक लाइव DOMTokenList लौटाता है जिसमें "class" एट्रिब्यूट को पार्स करने से प्राप्त टोकन होते हैं। |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) केवल-पढ़ने योग्य firstChild प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस की नोड के वृक्ष में पहला चाइल्ड लौटाती है, या यदि नोड के कोई चाइल्ड नहीं हैं तो null लौटाती है। |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) इस तत्व का पहला चाइल्ड एलिमेंट नोड लौटाता है। यदि इस तत्व के कोई चाइल्ड एलिमेंट नहीं हैं तो null। |
[getId]
[setId] The element's identifier. See the id attribute definition in HTML 4.01. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) केवल-पढ़ने योग्य lastChild प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस की नोड का अंतिम चाइल्ड लौटाती है। यदि इसका पैरेंट एक तत्व है, तो चाइल्ड सामान्यतः एक element node, एक text node, या एक comment node होता है। यदि कोई चाइल्ड तत्व नहीं हैं तो यह null लौटाती है। |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) इस तत्व का अंतिम चाइल्ड एलिमेंट नोड लौटाता है। यदि इस तत्व के पास कोई चाइल्ड एलिमेंट नहीं है तो null। |
| [getLocalName](../../com.aspose.html.dom/element/localname/) योग्य नाम के स्थानीय भाग को लौटाता है। ELEMENT_NODE और ATTRIBUTE_NODE के अलावा किसी भी प्रकार के नोड्स और DOM Level 1 विधि जैसे Document.createElement() से बनाए गए नोड्स के लिए यह हमेशा null होता है। |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) इस नोड का पैकेज URI, या यदि निर्दिष्ट नहीं है तो null। |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) इस तत्व का अगला सिब्लिंग एलिमेंट नोड लौटाता है। यदि इस तत्व के बाद दस्तावेज़ वृक्ष में कोई एलिमेंट सिब्लिंग नोड नहीं है तो null। |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) केवल-पढ़ने योग्य nextSibling प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस की निर्दिष्ट नोड के बाद तुरंत आने वाले नोड को उसके पैरेंट के [`childNodes`](../node/childnodes/) में लौटाती है, या यदि निर्दिष्ट नोड पैरेंट तत्व में अंतिम चाइल्ड है तो null लौटाती है। |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) इस नोड का नाम, उसके प्रकार पर निर्भर करता है। |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) अंतर्निहित ऑब्जेक्ट के प्रकार को दर्शाने वाला कोड। |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | `nodeValue` प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस की वर्तमान नोड का मान लौटाती या सेट करती है। |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Node इंटरफ़ेस की केवल-पढ़ने योग्य ownerDocument प्रॉपर्टी नोड का टॉप-लेवल डॉक्यूमेंट ऑब्जेक्ट लौटाती है। |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) [`Node`](../node/) इंटरफ़ेस की केवल-पढ़ने योग्य parentElement प्रॉपर्टी DOM नोड का पैरेंट `Element` लौटाती है, या null यदि नोड का कोई पैरेंट नहीं है, या उसका पैरेंट DOM Element नहीं है। |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Node इंटरफ़ेस की केवल-पढ़ने योग्य parentNode प्रॉपर्टी DOM वृक्ष में निर्दिष्ट नोड के पैरेंट को लौटाती है। |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) इस नोड का पैकेज प्रीफ़िक्स, या यदि निर्दिष्ट नहीं है तो null। जब इसे null पर सेट किया जाता है, तो इसका कोई प्रभाव नहीं पड़ता। |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) इस तत्व का पूर्ववर्ती सिब्लिंग एलिमेंट नोड लौटाता है। यदि दस्तावेज़ वृक्ष में इस तत्व से पहले कोई एलिमेंट सिब्लिंग नोड नहीं है तो null। |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) केवल-पढ़ने योग्य previousSibling प्रॉपर्टी [`Node`](../node/) इंटरफ़ेस की निर्दिष्ट नोड से पहले तुरंत आने वाले नोड को उसके पैरेंट के [`childNodes`](../node/firstchild/) सूची में लौटाती है, या यदि निर्दिष्ट नोड सूची में पहला है तो null। |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) इस एलिमेंट पर संग्रहीत shadowRoot लौटाता है या यदि यह बंद है तो null। |
| [getTagName](../../com.aspose.html.dom/element/tagname/) एलिमेंट का नाम। |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | यह एट्रिब्यूट इस नोड और उसके वंशजों की टेक्स्ट सामग्री लौटाता है। जब इसे null पर परिभाषित किया जाता है, तो इसे सेट करने का कोई प्रभाव नहीं पड़ता। सेट करने पर, इस नोड के सभी संभावित चाइल्ड हटाए जाते हैं और यदि नया स्ट्रिंग खाली या null नहीं है, तो इसे एकल Text नोड से प्रतिस्थापित किया जाता है जिसमें वह स्ट्रिंग होती है जिसे इस एट्रिब्यूट को सेट किया गया है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | [`EventTarget `](../eventtarget/) इंटरफ़ेस की addEventListener() मेथड एक फ़ंक्शन सेट करती है जो जब भी निर्दिष्ट इवेंट लक्ष्य को पहुँचाया जाता है, कॉल किया जाएगा। |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस का यह सेट करता है कि एक फ़ंक्शन को कॉल किया जाए जब भी निर्दिष्ट इवेंट लक्ष्य तक पहुँचाया जाता है। |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस का यह सेट करता है कि एक फ़ंक्शन को कॉल किया जाए जब भी निर्दिष्ट इवेंट लक्ष्य तक पहुँचाया जाता है। |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() मेथड Node इंटरफ़ेस का यह निर्दिष्ट पैरेंट नोड के बच्चों की सूची के अंत में एक नोड जोड़ता है। यदि दिया गया चाइल्ड दस्तावेज़ में मौजूदा नोड का संदर्भ है, तो appendChild() उसे उसकी वर्तमान स्थिति से नई स्थिति में ले जाता है (नोड को किसी अन्य नोड में जोड़ने से पहले पैरेंट नोड से हटाने की कोई आवश्यकता नहीं है)। |
| [attachShadow](../../com.aspose.html.dom/element/attachshadow/)(ShadowRootMode) | एक शैडो रूट बनाता है और उसे वर्तमान तत्व से जोड़ता है। |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode() मेथड Node इंटरफ़ेस का यह उस नोड की एक प्रतिलिपि लौटाता है जिस पर यह मेथड बुलाया गया था। इसका पैरामीटर नियंत्रित करता है कि नोड में निहित सबट्री भी क्लोन किया जाए या नहीं। |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode() मेथड Node इंटरफ़ेस का यह उस नोड की एक प्रतिलिपि लौटाता है जिस पर यह मेथड बुलाया गया था। इसका पैरामीटर नियंत्रित करता है कि नोड में निहित सबट्री भी क्लोन किया जाए या नहीं। |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | निर्दिष्ट [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) पर एक इवेंट डिस्पैच करता है, (सिंक्रोनस रूप से) प्रभावित EventListeners को उचित क्रम में बुलाता है। सामान्य इवेंट प्रोसेसिंग नियम (कैप्चरिंग और वैकल्पिक बबलिंग चरण सहित) उन इवेंट्स पर भी लागू होते हैं जिन्हें मैन्युअली [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) से डिस्पैच किया जाता है। |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | ऐप्लिकेशन-परिभाषित कार्यों को निष्पादित करता है जो अनमैनेज्ड संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से संबंधित होते हैं। |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | नाम द्वारा एक एट्रिब्यूट मान प्राप्त करता है। |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | तत्व के एट्रिब्यूट नामों को स्ट्रिंग्स की एक एरे के रूप में लौटाता है। यदि तत्व के पास कोई एट्रिब्यूट नहीं है तो यह एक खाली एरे लौटाता है। |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | नाम द्वारा एक एट्रिब्यूट नोड प्राप्त करता है। |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | स्थानीय नाम और पैकेज URI द्वारा एक Attr नोड प्राप्त करता है। |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | स्थानीय नाम और पैकेज URI द्वारा एक एट्रिब्यूट मान प्राप्त करता है। |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | एक [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) ऑब्जेक्ट लौटाता है जिसमें `element` के भीतर सभी वे तत्व शामिल होते हैं जिनके पास तर्क में निर्दिष्ट सभी क्लासें हैं। |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | एक [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) ऑब्जेक्ट लौटाता है जिसमें दिए गए टैग नाम वाले सभी `elements` दस्तावेज़ क्रम में होते हैं। |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | एक [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) ऑब्जेक्ट लौटाता है जिसमें दिए गए स्थानीय नाम और पैकेज URI स्ट्रिंग वाले सभी `elements` दस्तावेज़ क्रम में होते हैं। |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | सही (true) लौटाता है जब इस तत्व पर दिया गया नाम वाला एट्रिब्यूट निर्दिष्ट हो या उसका डिफ़ॉल्ट मान हो, अन्यथा गलत (false)। |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | सही (true) लौटाता है जब इस तत्व पर दिया गया स्थानीय नाम और पैकेज URI वाला एट्रिब्यूट निर्दिष्ट हो या उसका डिफ़ॉल्ट मान हो, अन्यथा गलत (false)। |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | यह दर्शाता है कि यह नोड (यदि यह एक तत्व है) के पास कोई एट्रिब्यूट हैं या नहीं। |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Node इंटरफ़ेस की hasChildNodes() मेथड एक बूलियन मान लौटाती है जो दर्शाता है कि दिया गया [`Node`](../node/) के पास चाइल्ड नोड हैं या नहीं। |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() मेथड Node इंटरफ़ेस का यह निर्दिष्ट पैरेंट नोड के एक रेफ़रेंस नोड से पहले एक नोड को बच्चे के रूप में डालता है। |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() मेथड Node इंटरफ़ेस का यह पैकेज URI को आर्ग्यूमेंट के रूप में लेता है। यह बूलियन मान लौटाता है जो सत्य (true) होता है यदि पैकेज दिए गए नोड पर डिफ़ॉल्ट पैकेज हो और अन्यथा असत्य (false)। |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | [`Node`](../node/) इंटरफ़ेस की isEqualNode() मेथड जांचती है कि दो नोड समान हैं या नहीं। दो नोड समान होते हैं जब उनका प्रकार समान हो, परिभाषित विशेषताएँ (तत्वों के लिए, उनका ID, चाइल्ड की संख्या आदि), उनके गुण मेल खाते हों, आदि। मिलान करने वाले डेटा बिंदुओं का विशिष्ट सेट नोड के प्रकार पर निर्भर करता है। |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode() मेथड Node इंटरफ़ेस का यह एक लेगेसी उपनाम है === सख्त समानता ऑपरेटर के लिए। यह परीक्षण करता है कि दो नोड्स एक ही हैं (अर्थात् वे एक ही ऑब्जेक्ट को रेफ़र करते हैं) या नहीं। |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI() मेथड Node इंटरफ़ेस का यह एक प्रीफ़िक्स को पैरामीटर के रूप में लेता है और यदि पाया जाता है तो दिए गए नोड पर उससे जुड़ा पैकेज URI लौटाता है (और न मिलने पर null)। |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix() मेथड Node इंटरफ़ेस का यह एक स्ट्रिंग लौटाता है जिसमें दिए गए पैकेज URI के लिए प्रीफ़िक्स होता है, यदि मौजूद हो, अन्यथा null। जब कई प्रीफ़िक्स संभव हों, तो पहला प्रीफ़िक्स लौटाया जाता है। |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | इस Node के नीचे स्थित सब‑ट्री की पूरी गहराई में सभी [`Text`](../text/) नोड्स को, एट्रिब्यूट नोड्स सहित, एक "सामान्य" रूप में रखता है जहाँ केवल संरचना (जैसे `elements`, [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), और [`entity references`](../entityreference/)) ही [`Text`](../text/) नोड्स को अलग करती है, अर्थात् न तो सटे हुए Text नोड्स होते हैं और न ही खाली Text नोड्स। इसका उपयोग यह सुनिश्चित करने के लिए किया जा सकता है कि दस्तावेज़ का DOM दृश्य उसी तरह हो जैसा कि इसे सहेजा और पुनः लोड किया गया हो, और यह उन ऑपरेशनों के लिए उपयोगी है (जैसे XPointer [XPointer] लुकअप) जो किसी विशेष दस्तावेज़ ट्री संरचना पर निर्भर होते हैं। यदि [`DOMConfiguration`](../../com.aspose.html/configuration/) ऑब्जेक्ट के "normalize-characters" पैरामीटर, जो [`Node.ownerDocument`](../node/ownerdocument/) से जुड़ा है, true है, तो यह मेथड Text नोड्स के अक्षरों को भी पूरी तरह से सामान्यीकृत करेगा। |
| [querySelector](../../com.aspose.html.dom/element/queryselector/)(String) | दस्तावेज़ में पहला Element लौटाता है, जो चयनकर्ता से मेल खाता है |
| [querySelectorAll](../../com.aspose.html.dom/element/queryselectorall/)(String) | दस्तावेज़ में सभी Elements की एक NodeList लौटाता है, जो चयनकर्ता से मेल खाते हैं |
| [remove](../../com.aspose.html.dom/element/remove/)() | इस instance को हटाता है। |
| [removeAttribute](../../com.aspose.html.dom/element/removeattribute/)(String) | नाम द्वारा एक attribute हटाता है। |
| [removeAttributeNode](../../com.aspose.html.dom/element/removeattributenode/)(Attr) | निर्दिष्ट attribute node को हटाता है। |
| [removeAttributeNS](../../com.aspose.html.dom/element/removeattributens/)(String, String) | स्थानीय नाम और package URI द्वारा एक attribute हटाता है। |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node इंटरफ़ेस की removeChild() मेथड DOM से एक child node हटाती है और हटाए गए node को लौटाती है। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि कोई इवेंट लिस्नर इवेंट प्रोसेस हो रहा हो तो उसे हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। हटाए जाने के बाद इवेंट लिस्नर्स कभी भी कॉल नहीं किए जा सकते। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि कोई इवेंट लिस्नर इवेंट प्रोसेस हो रहा हो तो उसे हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। हटाए जाने के बाद इवेंट लिस्नर्स कभी भी कॉल नहीं किए जा सकते। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि कोई इवेंट लिस्नर इवेंट प्रोसेस हो रहा हो तो उसे हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। हटाए जाने के बाद इवेंट लिस्नर्स कभी भी कॉल नहीं किए जा सकते। |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | चाइल्ड नोड oldChild को newChild से बच्चों की सूची में बदलता है और oldChild नोड लौटाता है। यदि newChild एक [`DocumentFragment`](../documentfragment/) ऑब्जेक्ट है, तो oldChild को सभी [`DocumentFragment`](../documentfragment/) चाइल्ड्स से बदला जाता है, जो उसी क्रम में सम्मिलित होते हैं। यदि newChild पहले से ही ट्री में है, तो उसे पहले हटाया जाता है। |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | एक नया attribute जोड़ता है। यदि उस नाम वाला attribute पहले से ही तत्व में मौजूद है, तो उसका मान value पैरामीटर के मान में बदल दिया जाता है। |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | एक नया attribute node जोड़ता है। यदि उस नाम (nodeName) वाला attribute पहले से ही तत्व में मौजूद है, तो उसे नए से बदल दिया जाता है। |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | एक नया attribute जोड़ता है। यदि उस स्थानीय नाम और package URI वाला attribute पहले से ही तत्व में मौजूद है, तो उसे नए से बदल दिया जाता है। |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | एक नया attribute जोड़ता है। यदि समान स्थानीय नाम और package URI वाला attribute पहले से ही तत्व पर मौजूद है, तो उसका prefix qualifiedName के prefix भाग में बदल दिया जाता है, और उसका मान value पैरामीटर के मान में बदल दिया जाता है। |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/#toggleattribute)(String) | यदि force नहीं दिया गया है, तो qualifiedName को "टॉगल" करता है, यदि वह मौजूद है तो उसे हटाता है और यदि नहीं है तो जोड़ता है। यदि force true है, तो qualifiedName जोड़ता है। यदि force false है, तो qualifiedName हटाता है। |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/#toggleattribute_1)(String, bool) | यदि force नहीं दिया गया है, तो qualifiedName को "टॉगल" करता है, यदि वह मौजूद है तो उसे हटाता है और यदि नहीं है तो जोड़ता है। यदि force true है, तो qualifiedName जोड़ता है। यदि force false है, तो qualifiedName हटाता है। |
| [toString](../../com.aspose.html.dom/node/toString/)() | इस उदाहरण का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |

### संबंधित देखें

* class [Node](../node/)
* interface [IChildNode](../ichildnode/)
* interface [IParentNode](../iparentnode/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
