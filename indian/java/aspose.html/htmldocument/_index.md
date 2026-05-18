---
title: "HTMLDocument क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.HTMLDocument क्लास। एक HTML दस्तावेज़ का प्रतिनिधित्व करता है। सभी टॉप-लेवल HTML ऑब्जेक्ट्स इस ऑब्जेक्ट में जोड़े जाते हैं। यह क्लास ब्राउज़र में हम जो देखते हैं, उसी रूप में HTML पेज को दर्शाता है। सभी फॉर्म, टेबल, स्क्रिप्ट आदि इस क्लास के इंटरफ़ेस के माध्यम से HTML पेज में जोड़े जाते हैं। HTMLDocument सबसे सामान्य Document इंटरफ़ेस की HTML कार्यान्वयन है और दोनों DOM - Document Object Model के मूल बिंदु हैं। ये अवधारणाएँ आधिकारिक वेब विकास आधार या मानकों के पूर्ण अनुरूप हैं। वेब विकास के उद्देश्यों के लिए आप सामान्यतः HTMLDocument को उस Document का उपनाम मान सकते हैं, जिस पर HTMLDocument आधारित है।"
type: docs

url: /hi/java/com.aspose.html/htmldocument/
---
## HTMLDocument class

एक HTML दस्तावेज़ का प्रतिनिधित्व करता है। सभी शीर्ष स्तर के HTML वस्तुएँ इस वस्तु में जोड़ी जाती हैं। यह क्लास ब्राउज़र में दिखाई देने वाले HTML पृष्ठ को दर्शाती है। सभी फ़ॉर्म, तालिकाएँ, स्क्रिप्ट आदि इस क्लास के इंटरफ़ेस के माध्यम से HTML पृष्ठ में जोड़े जाते हैं। [HTMLDocument](https://dom.spec.whatwg.org/#ref-for-dom-domimplementation-createhtmldocument) अधिकांश सामान्य [Document](https://dom.spec.whatwg.org/#document) इंटरफ़ेस का HTML कार्यान्वयन है और दोनों DOM (Document Object Model) के कोर या मूल बिंदु हैं। ये अवधारणाएँ आधिकारिक वेब विकास आधार या मानकों के पूर्ण अनुरूप हैं। वेब विकास के उद्देश्यों के लिए, आप सामान्यतः HTMLDocument को Document का उपनाम मान सकते हैं, जिस पर HTMLDocument आधारित है।

```java
public class HTMLDocument : Document, IDocumentCSS
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [HTMLDocument](htmldocument/#constructor)() | HTMLDocument कंस्ट्रक्टर एक नया HTML Document ऑब्जेक्ट बनाता है जो ब्राउज़र में लोड किया गया वेब पेज होता है और पेज की सामग्री में प्रवेश बिंदु के रूप में कार्य करता है। |
| [HTMLDocument](htmldocument/#constructor_1)(Configuration) | HTMLDocument कंस्ट्रक्टर एक नया HTML Document ऑब्जेक्ट बनाता है जो ब्राउज़र में लोड किया गया वेब पेज होता है और पेज की सामग्री में प्रवेश बिंदु के रूप में कार्य करता है। |
| [HTMLDocument](htmldocument/#constructor_2)(RequestMessage) | एक HTML दस्तावेज़ को [`RequestMessage`](../../com.aspose.html.net/requestmessage/) ऑब्जेक्ट से बनाता है। |
| [HTMLDocument](htmldocument/#constructor_10)(String) | HTML दस्तावेज़ को एक पते से लोड करता है। |
| [HTMLDocument](htmldocument/#constructor_4)(Url) | HTML दस्तावेज़ को एक URL से लोड करता है। |
| [HTMLDocument](htmldocument/#constructor_3)(RequestMessage, Configuration) | एक [RequestMessage](T:com.aspose.html.net.RequestMessage) ऑब्जेक्ट से HTML दस्तावेज़ बनाता है। |
| [HTMLDocument](htmldocument/#constructor_8)(Stream, String) | निर्दिष्ट base-uri के साथ एक [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) सामग्री से HTML दस्तावेज़ बनाता है, जिसका उपयोग सापेक्ष संसाधनों के पथ को हल करने के लिए किया जाता है। |
| [HTMLDocument](htmldocument/#constructor_6)(Stream, Url) | निर्दिष्ट base-uri के साथ एक [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) सामग्री से HTML दस्तावेज़ बनाता है, जिसका उपयोग सापेक्ष संसाधनों के पथ को हल करने के लिए किया जाता है। |
| [HTMLDocument](htmldocument/#constructor_11)(String, Configuration) | निर्दिष्ट पर्यावरण कॉन्फ़िगरेशन सेटिंग्स के साथ एक पते से HTML दस्तावेज़ लोड करता है। |
| [HTMLDocument](htmldocument/#constructor_14)(String, String) | निर्दिष्ट base-uri के साथ एक स्ट्रिंग सामग्री से HTML दस्तावेज़ बनाता है। |
| [HTMLDocument](htmldocument/#constructor_12)(String, Url) | निर्दिष्ट base-uri के साथ एक स्ट्रिंग सामग्री से HTML दस्तावेज़ बनाता है। |
| [HTMLDocument](htmldocument/#constructor_5)(Url, Configuration) | निर्दिष्ट पर्यावरण कॉन्फ़िगरेशन सेटिंग्स के साथ एक URL से HTML दस्तावेज़ लोड करता है। |
| [HTMLDocument](htmldocument/#constructor_9)(Stream, String, Configuration) | निर्दिष्ट base-uri और पर्यावरण कॉन्फ़िगरेशन सेटिंग्स के साथ एक [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) सामग्री से HTML दस्तावेज़ बनाता है। |
| [HTMLDocument](htmldocument/#constructor_7)(Stream, Url, Configuration) | निर्दिष्ट base-uri और पर्यावरण कॉन्फ़िगरेशन सेटिंग्स के साथ एक [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) सामग्री से HTML दस्तावेज़ बनाता है। |
| [HTMLDocument](htmldocument/#constructor_15)(String, String, Configuration) | निर्दिष्ट base-uri और पर्यावरण कॉन्फ़िगरेशन सेटिंग्स के साथ एक स्ट्रिंग सामग्री से HTML दस्तावेज़ बनाता है। |
| [HTMLDocument](htmldocument/#constructor_13)(String, Url, Configuration) | निर्दिष्ट base-uri और पर्यावरण कॉन्फ़िगरेशन सेटिंग्स के साथ एक स्ट्रिंग सामग्री से HTML दस्तावेज़ बनाता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [getAnchors](../../com.aspose.html/htmldocument/anchors/) एक दस्तावेज़ में सभी एंकर (`A`) तत्वों का संग्रह, जिनमें `name` एट्रिब्यूट का मान होता है। पिछली संगतता के कारण, लौटाए गए एंकर सेट में केवल वे एंकर शामिल होते हैं जो `name` एट्रिब्यूट के साथ बनाए गए हैं, न कि वे जो `id` एट्रिब्यूट के साथ बनाए गए हैं। ध्यान दें कि [[XHTML 1.0](http://www.w3.org/TR/2002/REC-xhtml1-20020801)] में, `name` एट्रिब्यूट (सेक्शन 4.10 देखें) का कोई अर्थ नहीं है और यह केवल लेगेसी यूज़र एजेंट्स के लिए मौजूद है: इसके बजाय `id` एट्रिब्यूट उपयोग किया जाता है। उपयोगकर्ताओं को [[DOM Level 2 Traversal](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)] द्वारा प्रदान किए गए इटरटर मेकैनिज़्म को प्राथमिकता देनी चाहिए। |
| [getApplets](../../com.aspose.html/htmldocument/applets/) एक दस्तावेज़ में सभी `OBJECT` तत्वों का संग्रह, जिसमें एप्लेट्स और `APPLET` (अप्रचलित) तत्व शामिल हैं। |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) इस नोड का पूर्ण बेस URI या यदि कार्यान्वयन पूर्ण URI प्राप्त नहीं कर सका तो Null। |
[getBody]
[setBody] The element that contains the content for the document. In documents with `BODY` contents, returns the `BODY`element. In frameset documents, this returns the outermost `FRAMESET` element. |
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
| [getDomain](../../com.aspose.html/htmldocument/domain/) उस सर्वर का डोमेन नाम जिसने दस्तावेज़ सर्व किया, या `null` यदि सर्वर को डोमेन नाम द्वारा पहचाना नहीं जा सकता। |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) [`Node`](../../com.aspose.html.dom/node/) इंटरफ़ेस की केवल-पढ़ने योग्य firstChild प्रॉपर्टी नोड के ट्री में पहला चाइल्ड लौटाती है, या यदि नोड के कोई बच्चे नहीं हैं तो null। |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) इस एलिमेंट का पहला बच्चा एलिमेंट नोड लौटाता है। यदि इस एलिमेंट के कोई बच्चा एलिमेंट नहीं हैं तो null। |
| [getForms](../../com.aspose.html/htmldocument/forms/) एक दस्तावेज़ के सभी फ़ॉर्म का संग्रह। |
| [getImages](../../com.aspose.html/htmldocument/images/) एक दस्तावेज़ में सभी `IMG` तत्वों का संग्रह। पिछली संगतता के लिए व्यवहार केवल `IMG` तत्वों तक सीमित है। [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)] के अनुसार, छवियों को शामिल करने के लिए लेखक `OBJECT` तत्व या `IMG` तत्व का उपयोग कर सकते हैं। इसलिए, इस एट्रिब्यूट का उपयोग करके दस्तावेज़ में छवियों को खोजने की बजाय HTML 4.01 के साथ `getElementsByTagName` या XHTML 1.0 के साथ `getElementsByTagNameNS` का उपयोग करने की सलाह दी जाती है। |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) यह दस्तावेज़ संभालने वाला DOMImplementation ऑब्जेक्ट। |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) दस्तावेज़ की एन्कोडिंग प्राप्त करता है। |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) [`Node`](../../com.aspose.html.dom/node/) इंटरफ़ेस की केवल-पढ़ने योग्य lastChild प्रॉपर्टी नोड का अंतिम चाइल्ड लौटाती है। यदि इसका पैरेंट एक तत्व है, तो चाइल्ड सामान्यतः एक एलिमेंट नोड, टेक्स्ट नोड, या टिप्पणी नोड होता है। यदि कोई चाइल्ड एलिमेंट नहीं हैं तो यह null लौटाता है। |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) इस एलिमेंट का अंतिम बच्चा एलिमेंट नोड लौटाता है। यदि इस एलिमेंट के कोई बच्चा एलिमेंट नहीं हैं तो null। |
| [getLinks](../../com.aspose.html/htmldocument/links/) एक दस्तावेज़ में सभी `AREA` तत्वों और एंकर (`A`) तत्वों का संग्रह, जिनमें `href` एट्रिब्यूट का मान होता है। |
| [getLocalName](../../com.aspose.html.dom/node/localname/) इस नोड के योग्य नाम का स्थानीय भाग लौटाता है। `ELEMENT_NODE` और `ATTRIBUTE_NODE` के अलावा किसी भी प्रकार के नोड के लिए, और DOM Level 1 विधि जैसे `Document.createElement()` से बनाए गए नोड के लिए, यह हमेशा null रहता है। |
| [getLocation](../../com.aspose.html.dom/document/location/) दस्तावेज़ का स्थान। |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI केवल-पढ़ने योग्य प्रॉपर्टी तत्व का पैकेज URI लौटाती है, या यदि तत्व किसी पैकेज में नहीं है तो null। |
| [getNextElementSibling](../../com.aspose.html.dom/document/nextelementsibling/) इस एलिमेंट का अगला सिब्लिंग एलिमेंट नोड लौटाता है। यदि इस एलिमेंट के बाद दस्तावेज़ वृक्ष में कोई सिब्लिंग एलिमेंट नोड नहीं है तो null। |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) [`Node`](../../com.aspose.html.dom/node/) इंटरफ़ेस की केवल-पढ़ने योग्य nextSibling प्रॉपर्टी निर्दिष्ट नोड के पैरेंट के [`childNodes`](../../com.aspose.html.dom/node/childnodes/) में तुरंत बाद वाला नोड लौटाती है, या यदि निर्दिष्ट नोड पैरेंट एलिमेंट में अंतिम चाइल्ड है तो null लौटाती है। |
| [getNodeName](../../com.aspose.html.dom/document/nodename/) इस नोड का नाम, उसके प्रकार के आधार पर। |
| [getNodeType](../../com.aspose.html.dom/document/nodetype/) अधोस्तित ऑब्जेक्ट के प्रकार को दर्शाने वाला कोड। |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | The nodeValue प्रॉपर्टी of the [`Node `](../../com.aspose.html.dom/node/)interface वर्तमान नोड का मान लौटाती या सेट करती है। |
| [getOrigin](../../com.aspose.html.dom/document/origin/) दस्तावेज़ की मूल उत्पत्ति प्राप्त करता है। |
| [getOwnerDocument](../../com.aspose.html.dom/document/ownerdocument/) स्वामी दस्तावेज़ प्राप्त करता है। |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) [`Node`](../../com.aspose.html.dom/node/) इंटरफ़ेस की केवल-पढ़ने योग्य parentElement प्रॉपर्टी DOM नोड का पैरेंट [`Element`](../../com.aspose.html.dom/element/) लौटाती है, या यदि नोड का कोई पैरेंट नहीं है या उसका पैरेंट DOM Element नहीं है तो null। |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Node इंटरफ़ेस की केवल-पढ़ने योग्य parentNode प्रॉपर्टी DOM वृक्ष में निर्दिष्ट नोड के पैरेंट को लौटाती है। |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix केवल-पढ़ने योग्य प्रॉपर्टी निर्दिष्ट तत्व का पैकेज प्रीफ़िक्स लौटाती है, या यदि कोई प्रीफ़िक्स निर्दिष्ट नहीं है तो null। |
| [getPreviousElementSibling](../../com.aspose.html.dom/document/previouselementsibling/) इस एलिमेंट का पिछला सिब्लिंग एलिमेंट नोड लौटाता है। यदि इस एलिमेंट से पहले दस्तावेज़ वृक्ष में कोई सिब्लिंग एलिमेंट नोड नहीं है तो null। |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) [`Node`](../../com.aspose.html.dom/node/) इंटरफ़ेस की केवल-पढ़ने योग्य previousSibling प्रॉपर्टी पैरेंट के [`childNodes`](../../com.aspose.html.dom/node/firstchild/) सूची में निर्दिष्ट नोड से तुरंत पहले वाला नोड लौटाती है, या यदि निर्दिष्ट नोड उस सूची में पहला है तो null। |
| [getReadyState](../../com.aspose.html.dom/document/readystate/) दस्तावेज़ की तैयार स्थिति लौटाता है। जब दस्तावेज़ लोड हो रहा हो तो "loading", पार्सिंग समाप्त होने पर लेकिन उप-संसाधन अभी भी लोड हो रहे हों तो "interactive", और पूरी तरह लोड होने पर "complete"। |
| [getReferrer](../../com.aspose.html/htmldocument/referrer/) उस पेज का URI [[IETF RFC 2396](http://www.ietf.org/rfc/rfc2396.txt)] लौटाता है जो इस पेज से लिंक किया गया था। यदि उपयोगकर्ता सीधे (लिंक के माध्यम से नहीं, बल्कि उदाहरण के तौर पर बुकमार्क द्वारा) पेज पर नेविगेट करता है तो मान एक खाली स्ट्रिंग होता है। |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) एक सूची जिसमें सभी स्टाइल शीट्स शामिल हैं जो स्पष्ट रूप से दस्तावेज़ में लिंक की गई हैं या एम्बेड की गई हैं। HTML दस्तावेज़ों के लिए, इसमें बाहरी स्टाइल शीट्स शामिल हैं, जो HTML LINK तत्व के माध्यम से जोड़ी गई हैं, और इनलाइन STYLE तत्व। |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | [`Node`](../../com.aspose.html.dom/node/) इंटरफ़ेस की textContent प्रॉपर्टी नोड और उसके वंशजों की टेक्स्ट सामग्री का प्रतिनिधित्व करती है। |
[getTitle]
[setTitle] The title of a document as specified by the `TITLE` element in the head of the document. |
[getXmlStandalone]
[setXmlStandalone] An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
[getXmlVersion]
[setXmlVersion] An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | The addEventListener() मेथड of the [`EventTarget `](../../com.aspose.html.dom/eventtarget/)interface एक फ़ंक्शन सेट करता है जो निर्दिष्ट इवेंट लक्ष्य पर पहुँचने पर कॉल किया जाएगा। |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस का यह सेट करता है कि एक फ़ंक्शन को कॉल किया जाए जब भी निर्दिष्ट इवेंट लक्ष्य तक पहुँचाया जाता है। |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() मेथड [EventTarget ](T:com.aspose.html.dom.EventTarget) इंटरफ़ेस का यह सेट करता है कि एक फ़ंक्शन को कॉल किया जाए जब भी निर्दिष्ट इवेंट लक्ष्य तक पहुँचाया जाता है। |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() मेथड Node इंटरफ़ेस का यह निर्दिष्ट पैरेंट नोड के बच्चों की सूची के अंत में एक नोड जोड़ता है। यदि दिया गया चाइल्ड दस्तावेज़ में मौजूदा नोड का संदर्भ है, तो appendChild() उसे उसकी वर्तमान स्थिति से नई स्थिति में ले जाता है (नोड को किसी अन्य नोड में जोड़ने से पहले पैरेंट नोड से हटाने की कोई आवश्यकता नहीं है)। |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode() मेथड Node इंटरफ़ेस का यह उस नोड की एक प्रतिलिपि लौटाता है जिस पर यह मेथड बुलाया गया था। इसका पैरामीटर नियंत्रित करता है कि नोड में निहित सबट्री भी क्लोन किया जाए या नहीं। |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode() मेथड Node इंटरफ़ेस का यह उस नोड की एक प्रतिलिपि लौटाता है जिस पर यह मेथड बुलाया गया था। इसका पैरामीटर नियंत्रित करता है कि नोड में निहित सबट्री भी क्लोन किया जाए या नहीं। |
| [createAttribute](../../com.aspose.html.dom/document/createattribute/)(String) | Document.createAttribute() मेथड एक नया एट्रिब्यूट नोड बनाता है और उसे लौटाता है। बनाया गया ऑब्जेक्ट एक नोड बनाता है जो [`Attr`](../../com.aspose.html.dom/attr/) इंटरफ़ेस को लागू करता है। DOM यह निर्धारित नहीं करता कि किसी विशेष तत्व में किस प्रकार के एट्रिब्यूट जोड़े जा सकते हैं। |
| [createAttributeNS](../../com.aspose.html.dom/document/createattributens/)(String, String) | Document.createAttribute() मेथड एक नया एट्रिब्यूट नोड बनाता है और उसे लौटाता है। बनाया गया ऑब्जेक्ट एक नोड बनाता है जो [Attr](T:com.aspose.html.dom.Attr) इंटरफ़ेस को लागू करता है। DOM यह निर्धारित नहीं करता कि किसी विशेष तत्व में किस प्रकार के एट्रिब्यूट जोड़े जा सकते हैं। |
| [createCDATASection](../../com.aspose.html.dom/document/createcdatasection/)(String) | `[`CDATASection`](../../com.aspose.html.dom/cdatasection/)` नोड बनाता है जिसकी वैल्यू निर्दिष्ट स्ट्रिंग होती है। |
| [createComment](../../com.aspose.html.dom/document/createcomment/)(String) | `[`Comment`](../../com.aspose.html.dom/comment/)` नोड बनाता है जो निर्दिष्ट स्ट्रिंग को लेता है। |
| [createDocumentFragment](../../com.aspose.html.dom/document/createdocumentfragment/)() | एक नया खाली [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) बनाता है जिसमें DOM नोड्स जोड़े जा सकते हैं ताकि ऑफ‑स्क्रीन DOM ट्री बनाया जा सके। |
| [createDocumentType](../../com.aspose.html.dom/document/createdocumenttype/)(String, String, String, String) | यह मेथड एक [`DocumentType`](../../com.aspose.html.dom/documenttype/) ऑब्जेक्ट लौटाता है जिसे दस्तावेज़ निर्माण के समय DOMImplementation.createDocument के साथ उपयोग किया जा सकता है या Node.insertBefore() या Node.replaceChild() जैसे मेथड्स के माध्यम से दस्तावेज़ में डाला जा सकता है। |
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | एक HTML दस्तावेज़ में, document.createElement() मेथड tagName द्वारा निर्दिष्ट HTML तत्व बनाता है, या यदि tagName पहचाना नहीं जाता है तो एक [`HTMLUnknownElement`](../htmlunknownelement/) बनाता है। |
| [createElementNS](../../com.aspose.html.dom/document/createelementns/)(String, String) | दिए गए योग्य नाम और पैकेज URI का उपयोग करके एक तत्व बनाता है। |
| [createEntityReference](../../com.aspose.html.dom/document/createentityreference/)(String) | एक EntityReference ऑब्जेक्ट बनाता है। अतिरिक्त रूप से, यदि संदर्भित एंटिटी ज्ञात है, तो EntityReference नोड की चाइल्ड सूची को संबंधित Entity नोड की समान बना दिया जाता है। |
| [createEvent](../../com.aspose.html.dom/document/createevent/)(String) | इम्प्लीमेंटेशन द्वारा समर्थित प्रकार का एक [`Event`](../../com.aspose.html.dom.events/event/) बनाता है। |
| [createExpression](../../com.aspose.html.dom/document/createexpression/)(String, IXPathNSResolver) | समाधान किए गए पैकेजों के साथ एक पार्स किया हुआ XPath अभिव्यक्ति बनाता है। यह तब उपयोगी होता है जब अभिव्यक्ति को एप्लिकेशन में पुनः उपयोग किया जाना हो क्योंकि यह अभिव्यक्ति स्ट्रिंग को अधिक कुशल आंतरिक रूप में संकलित करने और अभिव्यक्ति में मौजूद सभी पैकेज प्रीफ़िक्स को पहले से हल करने की सुविधा देता है। |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node) | निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया NodeIterator बनाएं। |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long) | निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया NodeIterator बनाएं। |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long, INodeFilter) | निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया NodeIterator बनाएं। |
| [createNSResolver](../../com.aspose.html.dom/document/creatensresolver/)(Node) | किसी भी DOM नोड को इस प्रकार अनुकूलित करता है कि पैकेजों को हल किया जा सके, जिससे XPath अभिव्यक्ति को दस्तावेज़ में नोड के संदर्भ के सापेक्ष आसानी से मूल्यांकन किया जा सके। यह एडेप्टर DOM Level 3 मेथड `lookupNamespaceURI` की तरह काम करता है, जो नोड की पदानुक्रम में उपलब्ध वर्तमान जानकारी का उपयोग करके दिए गए प्रीफ़िक्स से packageURI को हल करता है, तथा निहित xml प्रीफ़िक्स को भी सही ढंग से हल करता है। |
| [createProcessingInstruction](../../com.aspose.html.dom/document/createprocessinginstruction/)(String, String) | निर्दिष्ट नाम और डेटा स्ट्रिंग्स के साथ एक ProcessingInstruction नोड बनाता है। |
| [createTextNode](../../com.aspose.html.dom/document/createtextnode/)(String) | निर्दिष्ट स्ट्रिंग के साथ एक Text नोड बनाता है। |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node) | निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया TreeWalker बनाएं। |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long) | निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया TreeWalker बनाएं। |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long, INodeFilter) | निर्दिष्ट नोड पर मूलित उपवृक्ष के लिए एक नया TreeWalker बनाएं। |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | निर्दिष्ट [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) पर एक इवेंट डिस्पैच करता है, (सिंक्रोनस रूप से) प्रभावित EventListeners को उचित क्रम में बुलाता है। सामान्य इवेंट प्रोसेसिंग नियम (कैप्चरिंग और वैकल्पिक बबलिंग चरण सहित) उन इवेंट्स पर भी लागू होते हैं जिन्हें मैन्युअली [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) से डिस्पैच किया जाता है। |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | ऐप्लिकेशन-परिभाषित कार्यों को निष्पादित करता है जो अनमैनेज्ड संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से संबंधित होते हैं। |
| [evaluate](../../com.aspose.html.dom/document/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | एक XPath अभिव्यक्ति स्ट्रिंग का मूल्यांकन करता है और यदि संभव हो तो निर्दिष्ट प्रकार का परिणाम लौटाता है। |
| [getElementById](../../com.aspose.html.dom/document/getelementbyid/)(String) | Document मेथड getElementById() एक [`Element`](../../com.aspose.html.dom/element/) ऑब्जेक्ट लौटाता है जो उस तत्व का प्रतिनिधित्व करता है जिसकी id प्रॉपर्टी निर्दिष्ट स्ट्रिंग से मेल खाती है। चूँकि तत्व IDs को निर्दिष्ट करने पर अद्वितीय होना आवश्यक है, यह एक विशिष्ट तत्व तक तेज़ी से पहुँचने का उपयोगी तरीका है। |
| [getElementsByClassName](../../com.aspose.html.dom/document/getelementsbyclassname/)(String) | `Document` इंटरफ़ेस की getElementsByClassName मेथड सभी चाइल्ड तत्वों का एक एरे‑समान ऑब्जेक्ट लौटाती है जिनके पास दिए गए सभी क्लास नाम हैं। |
| [getElementsByTagName](../../com.aspose.html.dom/document/getelementsbytagname/)(String) | `Document` इंटरफ़ेस की getElementsByTagName मेथड दिए गए टैग नाम वाले तत्वों की एक [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) लौटाती है। |
| [getElementsByTagNameNS](../../com.aspose.html.dom/document/getelementsbytagnamens/)(String, String) | दिए गए पैकेज से संबंधित दिए गए टैग नाम वाले तत्वों की सूची लौटाता है। पूरी दस्तावेज़, जिसमें रूट नोड भी शामिल है, खोजी जाती है। |
| [getOverrideStyle](../../com.aspose.html/htmldocument/getoverridestyle/)(Element, String) | यह मेथड निर्दिष्ट तत्व और निर्दिष्ट प्यूडो-एलिमेंट के लिए ओवरराइड स्टाइल घोषणा को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | यह मेथड ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए उपयोग किया जाता है। |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | hasChildNodes() मेथड Node इंटरफ़ेस का यह बूलियन मान लौटाता है जो दर्शाता है कि दिया गया [`Node`](../../com.aspose.html.dom/node/) के पास चाइल्ड नोड्स हैं या नहीं। |
| [importNode](../../com.aspose.html.dom/document/importnode/)(Node, bool) | एक अन्य दस्तावेज़ से नोड को इस दस्तावेज़ में आयात करता है, मूल दस्तावेज़ से स्रोत नोड को बदले या हटाए बिना; यह मेथड स्रोत नोड की एक नई कॉपी बनाता है। |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() मेथड Node इंटरफ़ेस का यह निर्दिष्ट पैरेंट नोड के एक रेफ़रेंस नोड से पहले एक नोड को बच्चे के रूप में डालता है। |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() मेथड Node इंटरफ़ेस का यह पैकेज URI को आर्ग्यूमेंट के रूप में लेता है। यह बूलियन मान लौटाता है जो सत्य (true) होता है यदि पैकेज दिए गए नोड पर डिफ़ॉल्ट पैकेज हो और अन्यथा असत्य (false)। |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | isEqualNode() मेथड [`Node`](../../com.aspose.html.dom/node/) इंटरफ़ेस का यह परीक्षण करता है कि दो नोड्स समान हैं या नहीं। दो नोड्स समान होते हैं जब उनका प्रकार, परिभाषित विशेषताएँ (तत्वों के लिए, उनका ID, चाइल्ड की संख्या आदि), उनके एट्रिब्यूट मेल खाते हों, आदि। मिलान करने वाले डेटा पॉइंट्स का सेट नोड के प्रकार पर निर्भर करता है। |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode() मेथड Node इंटरफ़ेस का यह एक लेगेसी उपनाम है === सख्त समानता ऑपरेटर के लिए। यह परीक्षण करता है कि दो नोड्स एक ही हैं (अर्थात् वे एक ही ऑब्जेक्ट को रेफ़र करते हैं) या नहीं। |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI() मेथड Node इंटरफ़ेस का यह एक प्रीफ़िक्स को पैरामीटर के रूप में लेता है और यदि पाया जाता है तो दिए गए नोड पर उससे जुड़ा पैकेज URI लौटाता है (और न मिलने पर null)। |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix() मेथड Node इंटरफ़ेस का यह एक स्ट्रिंग लौटाता है जिसमें दिए गए पैकेज URI के लिए प्रीफ़िक्स होता है, यदि मौजूद हो, अन्यथा null। जब कई प्रीफ़िक्स संभव हों, तो पहला प्रीफ़िक्स लौटाया जाता है। |
| [navigate](../../com.aspose.html.dom/document/navigate/)(RequestMessage) | निर्दिष्ट अनुरोध ऑब्जेक्ट के आधार पर दस्तावेज़ लोड करता है, पूर्व सामग्री को प्रतिस्थापित करता है। |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String) | निर्दिष्ट यूनिफ़ॉर्म रिसोर्स लोकेटर (URL) पर दस्तावेज़ को वर्तमान उदाहरण में लोड करता है, पिछले सामग्री को बदलते हुए। |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Url) | निर्दिष्ट यूनिफ़ॉर्म रिसोर्स लोकेटर (URL) पर दस्तावेज़ को वर्तमान उदाहरण में लोड करता है, पिछले सामग्री को बदलते हुए। |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, String) | निर्दिष्ट सामग्री से दस्तावेज़ को लोड करता है और सापेक्ष संसाधनों को हल करने के लिए baseUri का उपयोग करता है, पिछले सामग्री को बदलते हुए। दस्तावेज़ लोडिंग स्ट्रीम में वर्तमान स्थिति से शुरू होती है। |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, Url) | निर्दिष्ट सामग्री से दस्तावेज़ को लोड करता है और सापेक्ष संसाधनों को हल करने के लिए baseUri का उपयोग करता है, पिछले सामग्री को बदलते हुए। दस्तावेज़ लोडिंग स्ट्रीम में वर्तमान स्थिति से शुरू होती है। |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, String) | निर्दिष्ट सामग्री से दस्तावेज़ को लोड करता है और सापेक्ष संसाधनों को हल करने के लिए baseUri का उपयोग करता है, पिछले सामग्री को बदलते हुए। |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, Url) | निर्दिष्ट सामग्री से दस्तावेज़ को लोड करता है और सापेक्ष संसाधनों को हल करने के लिए baseUri का उपयोग करता है, पिछले सामग्री को बदलते हुए। |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | इस नोड के नीचे उप-ट्री की पूरी गहराई में सभी [`Text`](../../com.aspose.html.dom/text/) नोड्स को, विशेषता नोड्स सहित, एक "सामान्य" रूप में रखता है जहाँ केवल संरचना (जैसे, [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), और [`entity references`](../../com.aspose.html.dom/entityreference/)) [`Text`](../../com.aspose.html.dom/text/) नोड्स को अलग करती है, अर्थात निकटस्थ Text नोड्स या खाली Text नोड्स नहीं होते। इसका उपयोग यह सुनिश्चित करने के लिए किया जा सकता है कि किसी दस्तावेज़ का DOM दृश्य उसी तरह हो जैसा कि इसे सहेजा गया हो और पुनः लोड किया गया हो, और यह उन संचालन के लिए उपयोगी है (जैसे XPointer [XPointer] लुकअप) जो किसी विशिष्ट दस्तावेज़ वृक्ष संरचना पर निर्भर होते हैं। यदि [`DOMConfiguration`](../configuration/) ऑब्जेक्ट के "normalize-characters" पैरामीटर, जो [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) से जुड़ा है, सत्य है, तो यह विधि Text नोड्स के अक्षरों को भी पूरी तरह सामान्य करेगी। |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | दस्तावेज़ में पहला Element लौटाता है, जो चयनकर्ता से मेल खाता है |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | दस्तावेज़ में सभी Elements की एक NodeList लौटाता है, जो चयनकर्ता से मेल खाते हैं |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node इंटरफ़ेस की removeChild() मेथड DOM से एक child node हटाती है और हटाए गए node को लौटाती है। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि कोई इवेंट लिस्नर इवेंट प्रोसेस हो रहा हो तो उसे हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। हटाए जाने के बाद इवेंट लिस्नर्स कभी भी कॉल नहीं किए जा सकते। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि कोई इवेंट लिस्नर इवेंट प्रोसेस हो रहा हो तो उसे हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। हटाए जाने के बाद इवेंट लिस्नर्स कभी भी कॉल नहीं किए जा सकते। |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | यह मेथड इवेंट टार्गेट से इवेंट लिस्नर्स को हटाने की अनुमति देता है। यदि कोई इवेंट लिस्नर इवेंट प्रोसेस हो रहा हो तो उसे हटाया जाता है, तो वह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं होगा। हटाए जाने के बाद इवेंट लिस्नर्स कभी भी कॉल नहीं किए जा सकते। |
| [renderTo](../../com.aspose.html/htmldocument/renderto/)(IDevice) | यह विधि वर्तमान दस्तावेज़ की सामग्री को निर्दिष्ट डिवाइस पर प्रिंट करने के लिए उपयोग की जाती है। |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | बच्चों की सूची में child node oldChild को newChild से बदलता है, और oldChild node को लौटाता है। यदि newChild एक [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) ऑब्जेक्ट है, तो oldChild को सभी [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) बच्चों से बदल दिया जाता है, जो समान क्रम में डाले जाते हैं। यदि newChild पहले से ही ट्री में है, तो उसे पहले हटाया जाता है। |
| [save](../../com.aspose.html/htmldocument/save/#save)(ResourceHandler) | दस्तावेज़ की सामग्री और संसाधनों को [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/) का उपयोग करके सहेजता है। |
| [save](../../com.aspose.html/htmldocument/save/#save_10)(String) | दस्तावेज़ को निर्दिष्ट पथ वाली स्थानीय फ़ाइल में सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधन एक सन्निहित फ़ोल्डर में सहेजे जाएंगे, जिसका नाम इस प्रकार निर्मित होगा: output_file_name + "_files"। |
| [save](../../com.aspose.html/htmldocument/save/#save_5)(Url) | दस्तावेज़ को निर्दिष्ट url द्वारा स्थानीय फ़ाइल में सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को एक सन्निहित फ़ोल्डर में सहेजा जाएगा, जिसका नाम output_file_name + "_files" के रूप में बनाया जाएगा। |
| [save](../../com.aspose.html/htmldocument/save/#save_1)(ResourceHandler, HTMLSaveFormat) | दस्तावेज़ की सामग्री और संसाधनों को [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/) का उपयोग करके सहेजता है। |
| [save](../../com.aspose.html/htmldocument/save/#save_2)(ResourceHandler, HTMLSaveOptions) | दस्तावेज़ की सामग्री और संसाधनों को [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/) का उपयोग करके सहेजता है। |
| [save](../../com.aspose.html/htmldocument/save/#save_3)(ResourceHandler, MarkdownSaveOptions) | दस्तावेज़ की सामग्री और संसाधनों को [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/) का उपयोग करके सहेजता है। |
| [save](../../com.aspose.html/htmldocument/save/#save_4)(ResourceHandler, MHTMLSaveOptions) | दस्तावेज़ की सामग्री और संसाधनों को [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/) का उपयोग करके सहेजता है। |
| [save](../../com.aspose.html/htmldocument/save/#save_11)(String, HTMLSaveFormat) | दस्तावेज़ को निर्दिष्ट path द्वारा स्थानीय फ़ाइल में सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को एक सन्निहित फ़ोल्डर में सहेजा जाएगा, जिसका नाम output_file_name + "_files" के रूप में बनाया जाएगा। |
| [save](../../com.aspose.html/htmldocument/save/#save_12)(String, HTMLSaveOptions) | दस्तावेज़ को निर्दिष्ट पथ वाली स्थानीय फ़ाइल में सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधन एक सन्निहित फ़ोल्डर में सहेजे जाएंगे, जिसका नाम इस प्रकार निर्मित होगा: output_file_name + "_files"। |
| [save](../../com.aspose.html/htmldocument/save/#save_13)(String, MarkdownSaveOptions) | दस्तावेज़ को निर्दिष्ट पथ वाली स्थानीय फ़ाइल में सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधन एक सन्निहित फ़ोल्डर में सहेजे जाएंगे, जिसका नाम इस प्रकार निर्मित होगा: output_file_name + "_files"। |
| [save](../../com.aspose.html/htmldocument/save/#save_14)(String, MHTMLSaveOptions) | दस्तावेज़ को निर्दिष्ट पथ वाली स्थानीय फ़ाइल में सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधन एक सन्निहित फ़ोल्डर में सहेजे जाएंगे, जिसका नाम इस प्रकार निर्मित होगा: output_file_name + "_files"। |
| [save](../../com.aspose.html/htmldocument/save/#save_6)(Url, HTMLSaveFormat) | दस्तावेज़ को निर्दिष्ट url द्वारा स्थानीय फ़ाइल में सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को एक सन्निहित फ़ोल्डर में सहेजा जाएगा, जिसका नाम output_file_name + "_files" के रूप में बनाया जाएगा। |
| [save](../../com.aspose.html/htmldocument/save/#save_7)(Url, HTMLSaveOptions) | दस्तावेज़ को निर्दिष्ट url द्वारा स्थानीय फ़ाइल में सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को एक सन्निहित फ़ोल्डर में सहेजा जाएगा, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files"। |
| [save](../../com.aspose.html/htmldocument/save/#save_8)(Url, MarkdownSaveOptions) | दस्तावेज़ को निर्दिष्ट url द्वारा स्थानीय फ़ाइल में सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को एक सन्निहित फ़ोल्डर में सहेजा जाएगा, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files"। |
| [save](../../com.aspose.html/htmldocument/save/#save_9)(Url, MHTMLSaveOptions) | दस्तावेज़ को निर्दिष्ट url द्वारा स्थानीय फ़ाइल में सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को एक सन्निहित फ़ोल्डर में सहेजा जाएगा, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files"। |
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

## टिप्पणियाँ

HTMLDocument, Document और DOM के बारे में अधिक जानकारी लोकप्रिय वेब विकास संसाधनों में प्राप्त की जा सकती है:

[General Document interface](https://developer.mozilla.org/en-US/docs/Web/API/Document).[Html specific HTMLDocument interface](https://developer.mozilla.org/en-US/docs/Web/API/HTMLDocument).[What is the HTML DOM](https://www.w3schools.com/js/js_htmldom.asp).

मानक संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## उदाहरण

```java
    // एक HTML दस्तावेज़ का एक उदाहरण बनाएं
	using (var document = new HTMLDocument())
      {
        // एक style तत्व बनाएं और सभी तत्वों जिनकी class-name 'gr' है, के लिए हरा रंग निर्धारित करें।
        var style = document.CreateElement("style");
        style.TextContent = ".gr { color: green }";

        // दस्तावेज़ के header तत्व को खोजें और style तत्व को header में जोड़ें
        var head = document.GetElementsByTagName("head").First();
        head.AppendChild(style);

        // class-name 'gr' के साथ एक पैराग्राफ तत्व बनाएं।
        var p = (HTMLParagraphElement)document.CreateElement("p");
        p.ClassName = "gr";

        // एक टेक्स्ट नोड बनाएं
        var text = document.CreateTextNode("Hello World!!");

        // टेक्स्ट नोड को पैराग्राफ में जोड़ें
        p.AppendChild(text);

        // पैराग्राफ को दस्तावेज़ के body तत्व में जोड़ें
        document.Body.AppendChild(p);

        // HTML दस्तावेज़ को फ़ाइल में सहेजें 
        document.Save(Path.Combine(OutputDir, "using-dom.html"));

        // PDF आउटपुट डिवाइस का एक उदाहरण बनाएं और दस्तावेज़ को इस डिवाइस में रेंडर करें
        using (var device = new PdfDevice(Path.Combine(OutputDir, "using-dom.pdf")))
        {
          // HTML को PDF में रेंडर करें
          document.RenderTo(device);
        }
      }       
```

### संबंधित देखें

* class [Document](../../com.aspose.html.dom/document/)
* interface [IDocumentCSS](../../com.aspose.html.dom.css/idocumentcss/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
