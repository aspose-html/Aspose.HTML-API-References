---
title: "HTMLImageElement क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.HTMLImageElement क्लास। एम्बेडेड इमेज। HTML 4.01 में IMG तत्व परिभाषा देखें।"
type: docs

url: /hi/java/com.aspose.html/htmlimageelement/
---
## HTMLImageElement class

एंबेडेड इमेज। देखें IMG तत्व की परिभाषा HTML 4.01 में।

साथ ही देखें [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109)।

```java
public class HTMLImageElement : HTMLElement
```

## गुण

| नाम | विवरण |
| --- | --- |
[getAlign]
[setAlign] Aligns this object (vertically or horizontally) with respect to its surrounding text. See the align attribute definition in HTML 4.01. This attribute is deprecated in HTML 4.01. |
[getAlt]
[setAlt] Alternate text for user agents not rendering the normal content of this element. See the alt attribute definition in HTML 4.01. |
| [getAttributes](../../com.aspose.html.dom/element/attributes/) एक NamedNodeMap जिसमें इस नोड के गुण होते हैं (यदि यह एक Element है) या अन्यथा null। |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node इंटरफ़ेस की केवल-पढ़ने योग्य baseURI प्रॉपर्टी दस्तावेज़ में नोड को सम्मिलित करने वाले दस्तावेज़ का पूर्ण बेस URL लौटाती है। |
[getBorder]
[setBorder] Width of border around image. See the border attribute definition in HTML 4.01. This attribute is deprecated in HTML 4.01. Note that the type of this attribute was `DOMString` in DOM Level 1 HTML [[DOM Level 1](http://www.w3.org/TR/1998/REC-DOM-Level-1-19981001)] . |
| [getChildElementCount](../../com.aspose.html.dom/element/childelementcount/) इस तत्व के बच्चों के रूप में मौजूद तत्व नोड्स की वर्तमान संख्या लौटाता है। यदि इस तत्व के कोई बच्चे नहीं हैं जिनका nodeType 1 है तो 0। |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node इंटरफ़ेस की केवल-पढ़ने योग्य childNodes प्रॉपर्टी दिए गए तत्व के चाइल्ड नोड्स की एक लाइव [`NodeList`](../../com.aspose.html.collections/nodelist/) लौटाती है जहाँ पहला चाइल्ड नोड इंडेक्स 0 पर असाइन किया जाता है। चाइल्ड नोड्स में तत्व, टेक्स्ट और टिप्पणी शामिल हैं। |
| [getChildren](../../com.aspose.html.dom/element/children/) वर्तमान तत्व के चाइल्ड तत्वों को लौटाता है। |
| [getClassList](../../com.aspose.html.dom/element/classlist/) एक लाइव DOMTokenList लौटाता है जिसमें "class" एट्रिब्यूट को पार्स करने से प्राप्त टोकन होते हैं। |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
[getDir]
[setDir] Specifies the base direction of directionally neutral text and the directionality of tables. See the dir attribute definition in HTML 4.01. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) [`Node`](../../com.aspose.html.dom/node/) इंटरफ़ेस की केवल-पढ़ने योग्य firstChild प्रॉपर्टी नोड के ट्री में पहला चाइल्ड लौटाती है, या यदि नोड के कोई बच्चे नहीं हैं तो null। |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) इस तत्व का पहला चाइल्ड एलिमेंट नोड लौटाता है। यदि इस तत्व के कोई चाइल्ड एलिमेंट नहीं हैं तो null। |
[getHeight]
[setHeight] Height of the image in pixels. See the height attribute definition in HTML 4.01. Note that the type of this attribute was `DOMString` in DOM Level 1 HTML [[DOM Level 1](http://www.w3.org/TR/1998/REC-DOM-Level-1-19981001)]. @version DOM Level 2 |
[getHspace]
[setHspace] Horizontal space to the left and right of this image in pixels. See the hspace attribute definition in HTML 4.01. This attribute is deprecated in HTML 4.01. Note that the type of this attribute was `DOMString` in DOM Level 1 HTML [[DOM Level 1](http://www.w3.org/TR/1998/REC-DOM-Level-1-19981001)]. @version DOM Level 2 |
[getId]
[setId] The element's identifier. See the id attribute definition in HTML 4.01. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
[getIsMap]
[setIsMap] Use server-side image map. See the ismap attribute definition in HTML 4.01. |
[getLang]
[setLang] Language code defined in RFC 1766. See the lang attribute definition in HTML 4.01. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) [`Node`](../../com.aspose.html.dom/node/) इंटरफ़ेस की केवल-पढ़ने योग्य lastChild प्रॉपर्टी नोड का अंतिम चाइल्ड लौटाती है। यदि इसका पैरेंट एक तत्व है, तो चाइल्ड सामान्यतः एक एलिमेंट नोड, टेक्स्ट नोड, या टिप्पणी नोड होता है। यदि कोई चाइल्ड एलिमेंट नहीं हैं तो यह null लौटाता है। |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) इस तत्व का अंतिम चाइल्ड एलिमेंट नोड लौटाता है। यदि इस तत्व के पास कोई चाइल्ड एलिमेंट नहीं है तो null। |
| [getLocalName](../../com.aspose.html.dom/element/localname/) योग्य नाम के स्थानीय भाग को लौटाता है। ELEMENT_NODE और ATTRIBUTE_NODE के अलावा किसी भी प्रकार के नोड्स और DOM Level 1 विधि जैसे Document.createElement() से बनाए गए नोड्स के लिए यह हमेशा null होता है। |
[getLongDesc]
[setLongDesc] URI [[IETF RFC 2396](http://www.ietf.org/rfc/rfc2396.txt)] designating a long description of this image or frame. See the longdesc attribute definition in HTML 4.01. |
[getName]
[setName] The name of the element (for backwards compatibility). |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) इस नोड का पैकेज URI, या यदि निर्दिष्ट नहीं है तो null। |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) इस तत्व का अगला सिब्लिंग एलिमेंट नोड लौटाता है। यदि इस तत्व के बाद दस्तावेज़ वृक्ष में कोई एलिमेंट सिब्लिंग नोड नहीं है तो null। |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) [`Node`](../../com.aspose.html.dom/node/) इंटरफ़ेस की केवल-पढ़ने योग्य nextSibling प्रॉपर्टी निर्दिष्ट नोड के पैरेंट के [`childNodes`](../../com.aspose.html.dom/node/childnodes/) में तुरंत बाद वाला नोड लौटाती है, या यदि निर्दिष्ट नोड पैरेंट एलिमेंट में अंतिम चाइल्ड है तो null लौटाती है। |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) इस नोड का नाम, उसके प्रकार पर निर्भर करता है। |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) अंतर्निहित ऑब्जेक्ट के प्रकार को दर्शाने वाला कोड। |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | The nodeValue प्रॉपर्टी of the [`Node `](../../com.aspose.html.dom/node/)interface वर्तमान नोड का मान लौटाती या सेट करती है। |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Node इंटरफ़ेस की केवल-पढ़ने योग्य ownerDocument प्रॉपर्टी नोड का टॉप-लेवल डॉक्यूमेंट ऑब्जेक्ट लौटाती है। |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) [`Node`](../../com.aspose.html.dom/node/) इंटरफ़ेस की केवल-पढ़ने योग्य parentElement प्रॉपर्टी DOM नोड का पैरेंट [`Element`](../../com.aspose.html.dom/element/) लौटाती है, या यदि नोड का कोई पैरेंट नहीं है या उसका पैरेंट DOM Element नहीं है तो null। |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Node इंटरफ़ेस की केवल-पढ़ने योग्य parentNode प्रॉपर्टी DOM वृक्ष में निर्दिष्ट नोड के पैरेंट को लौटाती है। |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) इस नोड का पैकेज प्रीफ़िक्स, या यदि निर्दिष्ट नहीं है तो null। जब इसे null पर सेट किया जाता है, तो इसका कोई प्रभाव नहीं पड़ता। |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) इस तत्व का पूर्ववर्ती सिब्लिंग एलिमेंट नोड लौटाता है। यदि दस्तावेज़ वृक्ष में इस तत्व से पहले कोई एलिमेंट सिब्लिंग नोड नहीं है तो null। |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) [`Node`](../../com.aspose.html.dom/node/) इंटरफ़ेस की केवल-पढ़ने योग्य previousSibling प्रॉपर्टी पैरेंट के [`childNodes`](../../com.aspose.html.dom/node/firstchild/) सूची में निर्दिष्ट नोड से तुरंत पहले वाला नोड लौटाती है, या यदि निर्दिष्ट नोड उस सूची में पहला है तो null। |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) इस एलिमेंट पर संग्रहीत shadowRoot लौटाता है या यदि यह बंद है तो null। |
[getSrc]
[setSrc] URI [[IETF RFC 2396](http://www.ietf.org/rfc/rfc2396.txt)] designating the source of this image. See the src attribute definition in HTML 4.01. |
| [getStyle](../../com.aspose.html/htmlelement/style/) एक शैली गुण का प्रतिनिधित्व करता है जो लेखक को सीधे विशिष्ट तत्व पर शैली जानकारी लागू करने की अनुमति देता है। |
| [getTagName](../../com.aspose.html.dom/element/tagname/) एलिमेंट का नाम। |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | यह एट्रिब्यूट इस नोड और उसके वंशजों की टेक्स्ट सामग्री लौटाता है। जब इसे null पर परिभाषित किया जाता है, तो इसे सेट करने का कोई प्रभाव नहीं पड़ता। सेट करने पर, इस नोड के सभी संभावित चाइल्ड हटाए जाते हैं और यदि नया स्ट्रिंग खाली या null नहीं है, तो इसे एकल Text नोड से प्रतिस्थापित किया जाता है जिसमें वह स्ट्रिंग होती है जिसे इस एट्रिब्यूट को सेट किया गया है। |
[getTitle]
[setTitle] The element's advisory title. See the title attribute definition in HTML 4.01. |
[getUseMap]
[setUseMap] Use client-side image map. See the usemap attribute definition in HTML 4.01. |
[getVspace]
[setVspace] Vertical space above and below this image in pixels. See the vspace attribute definition in HTML 4.01. This attribute is deprecated in HTML 4.01. Note that the type of this attribute was "DOMString" in DOM Level 1 HTML [[DOM Level 1](http://www.w3.org/TR/1998/REC-DOM-Level-1-19981001)]. @version DOM Level 2 |
[getWidth]
[setWidth] The width of the image in pixels. See the width attribute definition in HTML 4.01. Note that the type of this attribute was `DOMString` in DOM Level 1 HTML [[DOM Level 1](http://www.w3.org/TR/1998/REC-DOM-Level-1-19981001)]. @version DOM Level 2 |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | The addEventListener() मेथड of the [`EventTarget `](../../com.aspose.html.dom/eventtarget/)interface एक फ़ंक्शन सेट करता है जो निर्दिष्ट इवेंट लक्ष्य पर पहुँचने पर कॉल किया जाएगा। |
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
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | एक [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) ऑब्जेक्ट लौटाता है जिसमें सभी तत्व शामिल होते हैं जो [`element`](../../com.aspose.html.dom/element/) के भीतर निर्दिष्ट सभी क्लासेज़ को धारण करते हैं। |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | एक [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) ऑब्जेक्ट लौटाता है जिसमें सभी [`elements`](../../com.aspose.html.dom/element/) दिए गए टैग नाम के साथ, दस्तावेज़ क्रम में होते हैं। |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | एक [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) ऑब्जेक्ट लौटाता है जिसमें सभी [`elements`](../../com.aspose.html.dom/element/) दिए गए स्थानीय नाम और पैकेज URI स्ट्रिंग के साथ, दस्तावेज़ क्रम में होते हैं। |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | सही (true) लौटाता है जब इस तत्व पर दिया गया नाम वाला एट्रिब्यूट निर्दिष्ट हो या उसका डिफ़ॉल्ट मान हो, अन्यथा गलत (false)। |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | सही (true) लौटाता है जब इस तत्व पर दिया गया स्थानीय नाम और पैकेज URI वाला एट्रिब्यूट निर्दिष्ट हो या उसका डिफ़ॉल्ट मान हो, अन्यथा गलत (false)। |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | यह दर्शाता है कि यह नोड (यदि यह एक तत्व है) के पास कोई एट्रिब्यूट हैं या नहीं। |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | hasChildNodes() मेथड Node इंटरफ़ेस का यह बूलियन मान लौटाता है जो दर्शाता है कि दिया गया [`Node`](../../com.aspose.html.dom/node/) के पास चाइल्ड नोड्स हैं या नहीं। |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() मेथड Node इंटरफ़ेस का यह निर्दिष्ट पैरेंट नोड के एक रेफ़रेंस नोड से पहले एक नोड को बच्चे के रूप में डालता है। |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() मेथड Node इंटरफ़ेस का यह पैकेज URI को आर्ग्यूमेंट के रूप में लेता है। यह बूलियन मान लौटाता है जो सत्य (true) होता है यदि पैकेज दिए गए नोड पर डिफ़ॉल्ट पैकेज हो और अन्यथा असत्य (false)। |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | isEqualNode() मेथड [`Node`](../../com.aspose.html.dom/node/) इंटरफ़ेस का यह परीक्षण करता है कि दो नोड्स समान हैं या नहीं। दो नोड्स समान होते हैं जब उनका प्रकार, परिभाषित विशेषताएँ (तत्वों के लिए, उनका ID, चाइल्ड की संख्या आदि), उनके एट्रिब्यूट मेल खाते हों, आदि। मिलान करने वाले डेटा पॉइंट्स का सेट नोड के प्रकार पर निर्भर करता है। |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode() मेथड Node इंटरफ़ेस का यह एक लेगेसी उपनाम है === सख्त समानता ऑपरेटर के लिए। यह परीक्षण करता है कि दो नोड्स एक ही हैं (अर्थात् वे एक ही ऑब्जेक्ट को रेफ़र करते हैं) या नहीं। |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI() मेथड Node इंटरफ़ेस का यह एक प्रीफ़िक्स को पैरामीटर के रूप में लेता है और यदि पाया जाता है तो दिए गए नोड पर उससे जुड़ा पैकेज URI लौटाता है (और न मिलने पर null)। |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix() मेथड Node इंटरफ़ेस का यह एक स्ट्रिंग लौटाता है जिसमें दिए गए पैकेज URI के लिए प्रीफ़िक्स होता है, यदि मौजूद हो, अन्यथा null। जब कई प्रीफ़िक्स संभव हों, तो पहला प्रीफ़िक्स लौटाया जाता है। |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | इस नोड के नीचे उप-ट्री की पूरी गहराई में सभी [`Text`](../../com.aspose.html.dom/text/) नोड्स को, विशेषता नोड्स सहित, एक "सामान्य" रूप में रखता है जहाँ केवल संरचना (जैसे, [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), और [`entity references`](../../com.aspose.html.dom/entityreference/)) [`Text`](../../com.aspose.html.dom/text/) नोड्स को अलग करती है, अर्थात निकटस्थ Text नोड्स या खाली Text नोड्स नहीं होते। इसका उपयोग यह सुनिश्चित करने के लिए किया जा सकता है कि किसी दस्तावेज़ का DOM दृश्य उसी तरह हो जैसा कि इसे सहेजा गया हो और पुनः लोड किया गया हो, और यह उन संचालन के लिए उपयोगी है (जैसे XPointer [XPointer] लुकअप) जो किसी विशिष्ट दस्तावेज़ वृक्ष संरचना पर निर्भर होते हैं। यदि [`DOMConfiguration`](../configuration/) ऑब्जेक्ट के "normalize-characters" पैरामीटर, जो [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) से जुड़ा है, सत्य है, तो यह विधि Text नोड्स के अक्षरों को भी पूरी तरह सामान्य करेगी। |
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
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | बच्चों की सूची में child node oldChild को newChild से बदलता है, और oldChild node को लौटाता है। यदि newChild एक [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) ऑब्जेक्ट है, तो oldChild को सभी [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) बच्चों से बदल दिया जाता है, जो समान क्रम में डाले जाते हैं। यदि newChild पहले से ही ट्री में है, तो उसे पहले हटाया जाता है। |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | एक नया attribute जोड़ता है। यदि उस नाम वाला attribute पहले से ही तत्व में मौजूद है, तो उसका मान value पैरामीटर के मान में बदल दिया जाता है। |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | एक नया attribute node जोड़ता है। यदि उस नाम (nodeName) वाला attribute पहले से ही तत्व में मौजूद है, तो उसे नए से बदल दिया जाता है। |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | एक नया attribute जोड़ता है। यदि उस स्थानीय नाम और package URI वाला attribute पहले से ही तत्व में मौजूद है, तो उसे नए से बदल दिया जाता है। |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | एक नया attribute जोड़ता है। यदि समान स्थानीय नाम और package URI वाला attribute पहले से ही तत्व पर मौजूद है, तो उसका prefix qualifiedName के prefix भाग में बदल दिया जाता है, और उसका मान value पैरामीटर के मान में बदल दिया जाता है। |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String) | यदि force नहीं दिया गया है, तो qualifiedName को "टॉगल" करता है, यदि वह मौजूद है तो उसे हटाता है और यदि नहीं है तो जोड़ता है। यदि force true है, तो qualifiedName जोड़ता है। यदि force false है, तो qualifiedName हटाता है। |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String, bool) | यदि force नहीं दिया गया है, तो qualifiedName को "टॉगल" करता है, यदि वह मौजूद है तो उसे हटाता है और यदि नहीं है तो जोड़ता है। यदि force true है, तो qualifiedName जोड़ता है। यदि force false है, तो qualifiedName हटाता है। |
| [toString](../../com.aspose.html.dom/node/toString/)() | इस उदाहरण का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |

## इवेंट्स

| नाम | विवरण |
| --- | --- |
| event [OnAbort](../../com.aspose.html/htmlelement/onabort/) | OnAbort इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnBlur](../../com.aspose.html/htmlelement/onblur/) | OnBlur इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnCancel](../../com.aspose.html/htmlelement/oncancel/) | OnCancel इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnCanplay](../../com.aspose.html/htmlelement/oncanplay/) | OnCanplay इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnCanPlayThrough](../../com.aspose.html/htmlelement/oncanplaythrough/) | OnCanPlayThrough इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnChange](../../com.aspose.html/htmlelement/onchange/) | OnChange इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnClick](../../com.aspose.html/htmlelement/onclick/) | OnClick इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnCueChange](../../com.aspose.html/htmlelement/oncuechange/) | OnCueChange इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnDblClick](../../com.aspose.html/htmlelement/ondblclick/) | OnDblClick इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnDurationChange](../../com.aspose.html/htmlelement/ondurationchange/) | OnDurationChange इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnEmptied](../../com.aspose.html/htmlelement/onemptied/) | OnEmptied इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnEnded](../../com.aspose.html/htmlelement/onended/) | OnEnded इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnError](../../com.aspose.html/htmlelement/onerror/) | OnError इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnFocus](../../com.aspose.html/htmlelement/onfocus/) | OnFocus इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnInput](../../com.aspose.html/htmlelement/oninput/) | OnInput इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnInvalid](../../com.aspose.html/htmlelement/oninvalid/) | OnInvalid इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnKeyDown](../../com.aspose.html/htmlelement/onkeydown/) | OnKeyDown इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnKeyPress](../../com.aspose.html/htmlelement/onkeypress/) | OnKeyPress इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnKeyUp](../../com.aspose.html/htmlelement/onkeyup/) | OnKeyUp इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnLoad](../../com.aspose.html/htmlelement/onload/) | OnLoad इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnLoadedData](../../com.aspose.html/htmlelement/onloadeddata/) | OnLoadedData इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnLoadedMetadata](../../com.aspose.html/htmlelement/onloadedmetadata/) | OnLoadedMetadata इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnLoadStart](../../com.aspose.html/htmlelement/onloadstart/) | OnLoadStart इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnMouseDown](../../com.aspose.html/htmlelement/onmousedown/) | OnMouseDown इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnMouseEnter](../../com.aspose.html/htmlelement/onmouseenter/) | OnMouseEnter इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnMouseLeave](../../com.aspose.html/htmlelement/onmouseleave/) | OnMouseLeave इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnMouseMove](../../com.aspose.html/htmlelement/onmousemove/) | OnMouseMove इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnMouseOut](../../com.aspose.html/htmlelement/onmouseout/) | OnMouseOut इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnMouseOver](../../com.aspose.html/htmlelement/onmouseover/) | OnMouseOver इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnMouseUp](../../com.aspose.html/htmlelement/onmouseup/) | OnMouseUp इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnMouseWheel](../../com.aspose.html/htmlelement/onmousewheel/) | OnMouseWheel इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnPause](../../com.aspose.html/htmlelement/onpause/) | OnPause इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnPlay](../../com.aspose.html/htmlelement/onplay/) | OnPlay इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnPlaying](../../com.aspose.html/htmlelement/onplaying/) | OnPlaying इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnProgress](../../com.aspose.html/htmlelement/onprogress/) | OnProgress इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnRateChange](../../com.aspose.html/htmlelement/onratechange/) | OnRateChange इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnReset](../../com.aspose.html/htmlelement/onreset/) | OnReset इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnResize](../../com.aspose.html/htmlelement/onresize/) | OnResize इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnScroll](../../com.aspose.html/htmlelement/onscroll/) | OnScroll इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnSeeked](../../com.aspose.html/htmlelement/onseeked/) | OnSeeked इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnSeeking](../../com.aspose.html/htmlelement/onseeking/) | OnSeeking इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnSelect](../../com.aspose.html/htmlelement/onselect/) | OnSelect इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnShow](../../com.aspose.html/htmlelement/onshow/) | OnShow इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnStalled](../../com.aspose.html/htmlelement/onstalled/) | OnStalled इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnSubmit](../../com.aspose.html/htmlelement/onsubmit/) | OnSubmit इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnSuspend](../../com.aspose.html/htmlelement/onsuspend/) | OnSuspend इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnTimeUpdate](../../com.aspose.html/htmlelement/ontimeupdate/) | OnTimeUpdate इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnToggle](../../com.aspose.html/htmlelement/ontoggle/) | OnToggle इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnVolumeChange](../../com.aspose.html/htmlelement/onvolumechange/) | OnVolumeChange इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |
| event [OnWaiting](../../com.aspose.html/htmlelement/onwaiting/) | OnWaiting इवेंट के लिए इवेंट हैंडलर को प्राप्त करता है या सेट करता है। |

### संबंधित देखें

* class [HTMLElement](../htmlelement/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
