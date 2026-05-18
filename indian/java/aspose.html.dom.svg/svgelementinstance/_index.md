---
title: "SVGElementInstance क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.dom.svg.SVGElementInstance क्लास। प्रत्येक use-element शैडो ट्री का मूल ऑब्जेक्ट SVGUseElementShadowRoot इंटरफ़ेस को लागू करता है। यह इंटरफ़ेस वर्तमान में ShadowRoot इंटरफ़ेस और DocumentOrShadowRoot मिक्सिन के लिए परिभाषित गुणों और विधियों में कोई विस्तार नहीं परिभाषित करता है। हालांकि इस नोड पर आधारित ट्री लेखक स्क्रिप्ट्स के दृष्टिकोण से पूरी तरह पढ़ने‑के‑लिए‑केवल है।"
type: docs

url: /hi/java/com.aspose.html.dom.svg/svgelementinstance/
---
## SVGElementInstance class

प्रत्येक use‑element शैडो ट्री का मूल ऑब्जेक्ट SVGUseElementShadowRoot इंटरफ़ेस को लागू करता है। यह इंटरफ़ेस वर्तमान में ShadowRoot इंटरफ़ेस और DocumentOrShadowRoot मिक्सिन के लिए परिभाषित गुणों और विधियों में कोई विस्तार परिभाषित नहीं करता है। हालांकि, इस नोड पर आधारित ट्री लेखक स्क्रिप्ट्स के दृष्टिकोण से पूरी तरह पढ़ने‑के‑लिए‑सिर्फ़ है।

```java
public class SVGElementInstance : ShadowRoot
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node इंटरफ़ेस की केवल-पढ़ने योग्य baseURI प्रॉपर्टी दस्तावेज़ में नोड को सम्मिलित करने वाले दस्तावेज़ का पूर्ण बेस URL लौटाती है। |
| [getChildElementCount](../../com.aspose.html.dom/documentfragment/childelementcount/) वर्तमान में इस एलिमेंट के बच्चों के रूप में मौजूद एलिमेंट नोड्स की संख्या लौटाता है। यदि इस एलिमेंट के कोई nodeType 1 वाले चाइल्ड नोड नहीं हैं तो 0। |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node इंटरफ़ेस की केवल-पढ़ने योग्य childNodes प्रॉपर्टी दिए गए तत्व के चाइल्ड नोड्स की एक लाइव [`NodeList`](../../com.aspose.html.collections/nodelist/) लौटाती है जहाँ पहला चाइल्ड नोड इंडेक्स 0 पर असाइन किया जाता है। चाइल्ड नोड्स में तत्व, टेक्स्ट और टिप्पणी शामिल हैं। |
| [getChildren](../../com.aspose.html.dom/documentfragment/children/) वर्तमान एलिमेंट के चाइल्ड एलिमेंट्स लौटाता है। |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) [`Node`](../../com.aspose.html.dom/node/) इंटरफ़ेस की केवल-पढ़ने योग्य firstChild प्रॉपर्टी नोड के ट्री में पहला चाइल्ड लौटाती है, या यदि नोड के कोई बच्चे नहीं हैं तो null। |
| [getFirstElementChild](../../com.aspose.html.dom/documentfragment/firstelementchild/) इस एलिमेंट का पहला चाइल्ड एलिमेंट नोड लौटाता है। यदि इस एलिमेंट के कोई चाइल्ड एलिमेंट नहीं हैं तो null। |
| [getHost](../../com.aspose.html.dom/shadowroot/host/) Host वह एलिमेंट है जो इस ShadowRoot को समाहित करता है। |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) [`Node`](../../com.aspose.html.dom/node/) इंटरफ़ेस की केवल-पढ़ने योग्य lastChild प्रॉपर्टी नोड का अंतिम चाइल्ड लौटाती है। यदि इसका पैरेंट एक तत्व है, तो चाइल्ड सामान्यतः एक एलिमेंट नोड, टेक्स्ट नोड, या टिप्पणी नोड होता है। यदि कोई चाइल्ड एलिमेंट नहीं हैं तो यह null लौटाता है। |
| [getLastElementChild](../../com.aspose.html.dom/documentfragment/lastelementchild/) इस एलिमेंट का अंतिम चाइल्ड एलिमेंट नोड लौटाता है। यदि इस एलिमेंट के कोई चाइल्ड एलिमेंट नहीं हैं तो null। |
| [getLocalName](../../com.aspose.html.dom/node/localname/) इस नोड के योग्य नाम का स्थानीय भाग लौटाता है। `ELEMENT_NODE` और `ATTRIBUTE_NODE` के अलावा किसी भी प्रकार के नोड के लिए, और DOM Level 1 विधि जैसे `Document.createElement()` से बनाए गए नोड के लिए, यह हमेशा null रहता है। |
| [getMode](../../com.aspose.html.dom/shadowroot/mode/) वह मोड जिसमें यह ShadowRoot कार्य करता है। |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI केवल-पढ़ने योग्य प्रॉपर्टी तत्व का पैकेज URI लौटाती है, या यदि तत्व किसी पैकेज में नहीं है तो null। |
| [getNextElementSibling](../../com.aspose.html.dom/documentfragment/nextelementsibling/) इस एलिमेंट का अगला सिब्लिंग एलिमेंट नोड लौटाता है। यदि इस एलिमेंट के बाद दस्तावेज़ ट्री में कोई सिब्लिंग एलिमेंट नोड नहीं है तो null। |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) [`Node`](../../com.aspose.html.dom/node/) इंटरफ़ेस की केवल-पढ़ने योग्य nextSibling प्रॉपर्टी निर्दिष्ट नोड के पैरेंट के [`childNodes`](../../com.aspose.html.dom/node/childnodes/) में तुरंत बाद वाला नोड लौटाती है, या यदि निर्दिष्ट नोड पैरेंट एलिमेंट में अंतिम चाइल्ड है तो null लौटाती है। |
| [getNodeName](../../com.aspose.html.dom/documentfragment/nodename/) इस नोड का नाम, उसके प्रकार के आधार पर। |
| [getNodeType](../../com.aspose.html.dom/documentfragment/nodetype/) अधोस्तित ऑब्जेक्ट के प्रकार को दर्शाने वाला कोड। |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | The nodeValue प्रॉपर्टी of the [`Node `](../../com.aspose.html.dom/node/)interface वर्तमान नोड का मान लौटाती या सेट करती है। |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Node इंटरफ़ेस की केवल-पढ़ने योग्य ownerDocument प्रॉपर्टी नोड का टॉप-लेवल डॉक्यूमेंट ऑब्जेक्ट लौटाती है। |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) [`Node`](../../com.aspose.html.dom/node/) इंटरफ़ेस की केवल-पढ़ने योग्य parentElement प्रॉपर्टी DOM नोड का पैरेंट [`Element`](../../com.aspose.html.dom/element/) लौटाती है, या यदि नोड का कोई पैरेंट नहीं है या उसका पैरेंट DOM Element नहीं है तो null। |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Node इंटरफ़ेस की केवल-पढ़ने योग्य parentNode प्रॉपर्टी DOM वृक्ष में निर्दिष्ट नोड के पैरेंट को लौटाती है। |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix केवल-पढ़ने योग्य प्रॉपर्टी निर्दिष्ट तत्व का पैकेज प्रीफ़िक्स लौटाती है, या यदि कोई प्रीफ़िक्स निर्दिष्ट नहीं है तो null। |
| [getPreviousElementSibling](../../com.aspose.html.dom/documentfragment/previouselementsibling/) इस एलिमेंट का पूर्ववर्ती सिब्लिंग एलिमेंट नोड लौटाता है। यदि इस एलिमेंट से पहले दस्तावेज़ ट्री में कोई सिब्लिंग एलिमेंट नोड नहीं है तो null। |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) [`Node`](../../com.aspose.html.dom/node/) इंटरफ़ेस की केवल-पढ़ने योग्य previousSibling प्रॉपर्टी पैरेंट के [`childNodes`](../../com.aspose.html.dom/node/firstchild/) सूची में निर्दिष्ट नोड से तुरंत पहले वाला नोड लौटाती है, या यदि निर्दिष्ट नोड उस सूची में पहला है तो null। |
| [textContent](../../com.aspose.html.dom/documentfragment/textcontent/) { get; set; } | यह एट्रिब्यूट इस नोड और उसके वंशजों की टेक्स्ट सामग्री लौटाता है। जब इसे null पर परिभाषित किया जाता है, तो इसे सेट करने का कोई प्रभाव नहीं पड़ता। सेट करने पर, इस नोड के सभी संभावित चाइल्ड हटाए जाते हैं और यदि नया स्ट्रिंग खाली या null नहीं है, तो इसे एकल Text नोड से प्रतिस्थापित किया जाता है जिसमें वह स्ट्रिंग होती है जिसे इस एट्रिब्यूट को सेट किया गया है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | The addEventListener() मेथड of the [`EventTarget `](../../com.aspose.html.dom/eventtarget/)interface एक फ़ंक्शन सेट करता है जो निर्दिष्ट इवेंट लक्ष्य पर पहुँचने पर कॉल किया जाएगा। |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस का यह सेट करता है कि एक फ़ंक्शन को कॉल किया जाए जब भी निर्दिष्ट इवेंट लक्ष्य तक पहुँचाया जाता है। |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस का यह सेट करता है कि एक फ़ंक्शन को कॉल किया जाए जब भी निर्दिष्ट इवेंट लक्ष्य तक पहुँचाया जाता है। |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() मेथड Node इंटरफ़ेस का यह निर्दिष्ट पैरेंट नोड के बच्चों की सूची के अंत में एक नोड जोड़ता है। यदि दिया गया चाइल्ड दस्तावेज़ में मौजूदा नोड का संदर्भ है, तो appendChild() उसे उसकी वर्तमान स्थिति से नई स्थिति में ले जाता है (नोड को किसी अन्य नोड में जोड़ने से पहले पैरेंट नोड से हटाने की कोई आवश्यकता नहीं है)। |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode() मेथड Node इंटरफ़ेस का यह उस नोड की एक प्रतिलिपि लौटाता है जिस पर यह मेथड बुलाया गया था। इसका पैरामीटर नियंत्रित करता है कि नोड में निहित सबट्री भी क्लोन किया जाए या नहीं। |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode() मेथड Node इंटरफ़ेस का यह उस नोड की एक प्रतिलिपि लौटाता है जिस पर यह मेथड बुलाया गया था। इसका पैरामीटर नियंत्रित करता है कि नोड में निहित सबट्री भी क्लोन किया जाए या नहीं। |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | निर्दिष्ट [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) पर एक इवेंट डिस्पैच करता है, (सिंक्रोनस रूप से) प्रभावित EventListeners को उचित क्रम में बुलाता है। सामान्य इवेंट प्रोसेसिंग नियम (कैप्चरिंग और वैकल्पिक बबलिंग चरण सहित) उन इवेंट्स पर भी लागू होते हैं जिन्हें मैन्युअली [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) से डिस्पैच किया जाता है। |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | ऐप्लिकेशन-परिभाषित कार्यों को निष्पादित करता है जो अनमैनेज्ड संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से संबंधित होते हैं। |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | hasChildNodes() मेथड Node इंटरफ़ेस का यह बूलियन मान लौटाता है जो दर्शाता है कि दिया गया [`Node`](../../com.aspose.html.dom/node/) के पास चाइल्ड नोड्स हैं या नहीं। |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() मेथड Node इंटरफ़ेस का यह निर्दिष्ट पैरेंट नोड के एक रेफ़रेंस नोड से पहले एक नोड को बच्चे के रूप में डालता है। |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() मेथड Node इंटरफ़ेस का यह पैकेज URI को आर्ग्यूमेंट के रूप में लेता है। यह बूलियन मान लौटाता है जो सत्य (true) होता है यदि पैकेज दिए गए नोड पर डिफ़ॉल्ट पैकेज हो और अन्यथा असत्य (false)। |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | isEqualNode() मेथड [`Node`](../../com.aspose.html.dom/node/) इंटरफ़ेस का यह परीक्षण करता है कि दो नोड्स समान हैं या नहीं। दो नोड्स समान होते हैं जब उनका प्रकार, परिभाषित विशेषताएँ (तत्वों के लिए, उनका ID, चाइल्ड की संख्या आदि), उनके एट्रिब्यूट मेल खाते हों, आदि। मिलान करने वाले डेटा पॉइंट्स का सेट नोड के प्रकार पर निर्भर करता है। |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode() मेथड Node इंटरफ़ेस का यह एक लेगेसी उपनाम है === सख्त समानता ऑपरेटर के लिए। यह परीक्षण करता है कि दो नोड्स एक ही हैं (अर्थात् वे एक ही ऑब्जेक्ट को रेफ़र करते हैं) या नहीं। |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI() मेथड Node इंटरफ़ेस का यह एक प्रीफ़िक्स को पैरामीटर के रूप में लेता है और यदि पाया जाता है तो दिए गए नोड पर उससे जुड़ा पैकेज URI लौटाता है (और न मिलने पर null)। |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix() मेथड Node इंटरफ़ेस का यह एक स्ट्रिंग लौटाता है जिसमें दिए गए पैकेज URI के लिए प्रीफ़िक्स होता है, यदि मौजूद हो, अन्यथा null। जब कई प्रीफ़िक्स संभव हों, तो पहला प्रीफ़िक्स लौटाया जाता है। |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | सभी [`Text`](../../com.aspose.html.dom/text/) नोड्स को इस नोड के नीचे की पूरी सब-ट्री की गहराई में, एट्रिब्यूट नोड्स सहित, एक "सामान्य" रूप में रखता है जहाँ केवल संरचना (जैसे [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), और [`entity references`](../../com.aspose.html.dom/entityreference/)) `Text` नोड्स को अलग करती है, अर्थात् न तो सटे हुए Text नोड्स होते हैं और न ही खाली Text नोड्स। यह सुनिश्चित करने के लिए उपयोगी है कि दस्तावेज़ का DOM दृश्य उसी तरह हो जैसे वह सहेजा गया हो और पुनः लोड किया गया हो, और उन ऑपरेशनों (जैसे XPointer लुकअप) के लिए उपयोगी है जो विशिष्ट दस्तावेज़ ट्री संरचना पर निर्भर होते हैं। यदि [`DOMConfiguration`](../../com.aspose.html/configuration/) ऑब्जेक्ट के `Node.ownerDocument` से जुड़े "normalize-characters" पैरामीटर सत्य है, तो यह मेथड Text नोड्स के अक्षरों को भी पूरी तरह से सामान्यीकृत करेगा। |
| [querySelector](../../com.aspose.html.dom/documentfragment/queryselector/)(String) | दस्तावेज़ में पहला Element लौटाता है, जो चयनकर्ता से मेल खाता है |
| [querySelectorAll](../../com.aspose.html.dom/documentfragment/queryselectorall/)(String) | दस्तावेज़ में सभी Elements की एक NodeList लौटाता है, जो चयनकर्ता से मेल खाते हैं |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node इंटरफ़ेस की removeChild() मेथड DOM से एक child node हटाती है और हटाए गए node को लौटाती है। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि कोई इवेंट लिस्नर इवेंट प्रोसेस हो रहा हो तो उसे हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। हटाए जाने के बाद इवेंट लिस्नर्स कभी भी कॉल नहीं किए जा सकते। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि कोई इवेंट लिस्नर इवेंट प्रोसेस हो रहा हो तो उसे हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। हटाए जाने के बाद इवेंट लिस्नर्स कभी भी कॉल नहीं किए जा सकते। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि कोई इवेंट लिस्नर इवेंट प्रोसेस हो रहा हो तो उसे हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। हटाए जाने के बाद इवेंट लिस्नर्स कभी भी कॉल नहीं किए जा सकते। |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | बच्चों की सूची में child node oldChild को newChild से बदलता है, और oldChild node को लौटाता है। यदि newChild एक [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) ऑब्जेक्ट है, तो oldChild को सभी [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) बच्चों से बदल दिया जाता है, जो समान क्रम में डाले जाते हैं। यदि newChild पहले से ही ट्री में है, तो उसे पहले हटाया जाता है। |
| [toString](../../com.aspose.html.dom/node/toString/)() | इस उदाहरण का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |

### संबंधित देखें

* class [ShadowRoot](../../com.aspose.html.dom/shadowroot/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
