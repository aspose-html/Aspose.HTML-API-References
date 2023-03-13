---
title: Class HTMLDocument
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.HTMLDocument कक्ष. एकHTMLDocument HTML पदनुक्रम क मूल है और संपूर्ण समग्र क रखत है पदनुक्रम तक पहुँच प्रदन करने के अलव यह दस्तवेज़ से जनकर के कुछ सेटं तक पहुँचने के लए कुछ सुवधजनक तरके भ प्रदन करत है
type: docs
weight: 3190
url: /hi/net/aspose.html/htmldocument/
---
## HTMLDocument class

एक`HTMLDocument` HTML पदानुक्रम का मूल है और संपूर्ण सामग्री को रखता है। पदानुक्रम तक पहुँच प्रदान करने के अलावा, यह दस्तावेज़ से जानकारी के कुछ सेटों तक पहुँचने के लिए कुछ सुविधाजनक तरीके भी प्रदान करता है।

निम्नलिखित गुणों को इसके लिए संगत गुणों के पक्ष में बहिष्कृत कर दिया गया है`शरीर` element. डोम स्तर 2 में, विधि`getElementById` से विरासत में मिला है`दस्तावेज़` इंटरफ़ेस जहां इसे स्थानांतरित किया गया था.

यह भी देखें[दस्तावेज़ वस्तु मॉडल (DOM) स्तर 2 HTML विशिष्टता](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109) .

```csharp
public class HTMLDocument : Document, IDocumentCSS
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [HTMLDocument](htmldocument/#constructor)() | का एक नया उदाहरण प्रारंभ करता है`HTMLDocument` वर्ग. |
| [HTMLDocument](htmldocument/#constructor_1)(Configuration) | का एक नया उदाहरण प्रारंभ करता है`HTMLDocument` वर्ग. |
| [HTMLDocument](htmldocument/#constructor_2)(RequestMessage) | का एक नया उदाहरण प्रारंभ करता है`HTMLDocument` कक्षा। कंस्ट्रक्टर समकालिक रूप से काम करता है, यह सभी बाहरी संसाधनों (छवियों, स्क्रिप्ट, आदि) के लोड होने की प्रतीक्षा करता है। दस्तावेज़ को एसिंक्रोनस रूप से लोड करने के लिए विधि का उपयोग करें[`Navigate`](../../aspose.html.dom/document/navigate/) या इसके ओवरलोड्स. या आप उपयुक्त फ़्लैग्स सेट करके कुछ बाहरी संसाधनों को लोड करना अक्षम कर सकते हैं[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_10)(string) | का एक नया उदाहरण प्रारंभ करता है`HTMLDocument` कक्षा। कंस्ट्रक्टर समकालिक रूप से काम करता है, यह सभी बाहरी संसाधनों (छवियों, स्क्रिप्ट, आदि) के लोड होने की प्रतीक्षा करता है। दस्तावेज़ को एसिंक्रोनस रूप से लोड करने के लिए विधि का उपयोग करें[`Navigate`](../../aspose.html.dom/document/navigate/) या इसके ओवरलोड्स. या आप उपयुक्त फ़्लैग्स सेट करके कुछ बाहरी संसाधनों को लोड करना अक्षम कर सकते हैं[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_4)(Url) | का एक नया उदाहरण प्रारंभ करता है`HTMLDocument` कक्षा। कंस्ट्रक्टर समकालिक रूप से काम करता है, यह सभी बाहरी संसाधनों (छवियों, स्क्रिप्ट, आदि) के लोड होने की प्रतीक्षा करता है। दस्तावेज़ को एसिंक्रोनस रूप से लोड करने के लिए विधि का उपयोग करें[`Navigate`](../../aspose.html.dom/document/navigate/) या इसके ओवरलोड्स. या आप उपयुक्त फ़्लैग्स सेट करके कुछ बाहरी संसाधनों को लोड करना अक्षम कर सकते हैं[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_3)(RequestMessage, Configuration) | का एक नया उदाहरण प्रारंभ करता है`HTMLDocument` कक्षा। कंस्ट्रक्टर समकालिक रूप से काम करता है, यह सभी बाहरी संसाधनों (छवियों, स्क्रिप्ट, आदि) के लोड होने की प्रतीक्षा करता है। दस्तावेज़ को एसिंक्रोनस रूप से लोड करने के लिए विधि का उपयोग करें[`Navigate`](../../aspose.html.dom/document/navigate/) या इसके ओवरलोड्स. या आप उपयुक्त फ़्लैग्स सेट करके कुछ बाहरी संसाधनों को लोड करना अक्षम कर सकते हैं[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_8)(Stream, string) | का एक नया उदाहरण प्रारंभ करता है`HTMLDocument` कक्षा। कंस्ट्रक्टर समकालिक रूप से काम करता है, यह सभी बाहरी संसाधनों (छवियों, स्क्रिप्ट, आदि) के लोड होने की प्रतीक्षा करता है। दस्तावेज़ को एसिंक्रोनस रूप से लोड करने के लिए विधि का उपयोग करें[`Navigate`](../../aspose.html.dom/document/navigate/) या इसके ओवरलोड्स. या आप उपयुक्त फ़्लैग्स सेट करके कुछ बाहरी संसाधनों को लोड करना अक्षम कर सकते हैं[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . दस्तावेज़ लोड करना स्ट्रीम में वर्तमान स्थिति से शुरू होता है। |
| [HTMLDocument](htmldocument/#constructor_6)(Stream, Url) | का एक नया उदाहरण प्रारंभ करता है`HTMLDocument` कक्षा। कंस्ट्रक्टर समकालिक रूप से काम करता है, यह सभी बाहरी संसाधनों (छवियों, स्क्रिप्ट, आदि) के लोड होने की प्रतीक्षा करता है। दस्तावेज़ को एसिंक्रोनस रूप से लोड करने के लिए विधि का उपयोग करें[`Navigate`](../../aspose.html.dom/document/navigate/) या इसके ओवरलोड्स. या आप उपयुक्त फ़्लैग्स सेट करके कुछ बाहरी संसाधनों को लोड करना अक्षम कर सकते हैं[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . दस्तावेज़ लोड करना स्ट्रीम में वर्तमान स्थिति से शुरू होता है। |
| [HTMLDocument](htmldocument/#constructor_11)(string, Configuration) | का एक नया उदाहरण प्रारंभ करता है`HTMLDocument` कक्षा। कंस्ट्रक्टर समकालिक रूप से काम करता है, यह सभी बाहरी संसाधनों (छवियों, स्क्रिप्ट, आदि) के लोड होने की प्रतीक्षा करता है। दस्तावेज़ को एसिंक्रोनस रूप से लोड करने के लिए विधि का उपयोग करें[`Navigate`](../../aspose.html.dom/document/navigate/) या इसके ओवरलोड्स. या आप उपयुक्त फ़्लैग्स सेट करके कुछ बाहरी संसाधनों को लोड करना अक्षम कर सकते हैं[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_14)(string, string) | का एक नया उदाहरण प्रारंभ करता है`HTMLDocument` कक्षा। कंस्ट्रक्टर समकालिक रूप से काम करता है, यह सभी बाहरी संसाधनों (छवियों, स्क्रिप्ट, आदि) के लोड होने की प्रतीक्षा करता है। दस्तावेज़ को एसिंक्रोनस रूप से लोड करने के लिए विधि का उपयोग करें[`Navigate`](../../aspose.html.dom/document/navigate/) या इसके ओवरलोड्स. या आप उपयुक्त फ़्लैग्स सेट करके कुछ बाहरी संसाधनों को लोड करना अक्षम कर सकते हैं[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_12)(string, Url) | का एक नया उदाहरण प्रारंभ करता है`HTMLDocument` कक्षा। कंस्ट्रक्टर समकालिक रूप से काम करता है, यह सभी बाहरी संसाधनों (छवियों, स्क्रिप्ट, आदि) के लोड होने की प्रतीक्षा करता है। दस्तावेज़ को एसिंक्रोनस रूप से लोड करने के लिए विधि का उपयोग करें[`Navigate`](../../aspose.html.dom/document/navigate/) या इसके ओवरलोड्स. या आप उपयुक्त फ़्लैग्स सेट करके कुछ बाहरी संसाधनों को लोड करना अक्षम कर सकते हैं[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_5)(Url, Configuration) | का एक नया उदाहरण प्रारंभ करता है`HTMLDocument` कक्षा। कंस्ट्रक्टर समकालिक रूप से काम करता है, यह सभी बाहरी संसाधनों (छवियों, स्क्रिप्ट, आदि) के लोड होने की प्रतीक्षा करता है। दस्तावेज़ को एसिंक्रोनस रूप से लोड करने के लिए विधि का उपयोग करें[`Navigate`](../../aspose.html.dom/document/navigate/) या इसके ओवरलोड्स. या आप उपयुक्त फ़्लैग्स सेट करके कुछ बाहरी संसाधनों को लोड करना अक्षम कर सकते हैं[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_9)(Stream, string, Configuration) | का एक नया उदाहरण प्रारंभ करता है`HTMLDocument` कक्षा। कंस्ट्रक्टर समकालिक रूप से काम करता है, यह सभी बाहरी संसाधनों (छवियों, स्क्रिप्ट, आदि) के लोड होने की प्रतीक्षा करता है। दस्तावेज़ को एसिंक्रोनस रूप से लोड करने के लिए विधि का उपयोग करें[`Navigate`](../../aspose.html.dom/document/navigate/) या इसके ओवरलोड्स. या आप उपयुक्त फ़्लैग्स सेट करके कुछ बाहरी संसाधनों को लोड करना अक्षम कर सकते हैं[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . दस्तावेज़ लोड करना स्ट्रीम में वर्तमान स्थिति से शुरू होता है। |
| [HTMLDocument](htmldocument/#constructor_7)(Stream, Url, Configuration) | का एक नया उदाहरण प्रारंभ करता है`HTMLDocument` कक्षा। कंस्ट्रक्टर समकालिक रूप से काम करता है, यह सभी बाहरी संसाधनों (छवियों, स्क्रिप्ट, आदि) के लोड होने की प्रतीक्षा करता है। दस्तावेज़ को एसिंक्रोनस रूप से लोड करने के लिए विधि का उपयोग करें[`Navigate`](../../aspose.html.dom/document/navigate/) या इसके ओवरलोड्स. या आप उपयुक्त फ़्लैग्स सेट करके कुछ बाहरी संसाधनों को लोड करना अक्षम कर सकते हैं[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . दस्तावेज़ लोड करना स्ट्रीम में वर्तमान स्थिति से शुरू होता है। |
| [HTMLDocument](htmldocument/#constructor_15)(string, string, Configuration) | का एक नया उदाहरण प्रारंभ करता है`HTMLDocument` कक्षा। कंस्ट्रक्टर समकालिक रूप से काम करता है, यह सभी बाहरी संसाधनों (छवियों, स्क्रिप्ट, आदि) के लोड होने की प्रतीक्षा करता है। दस्तावेज़ को एसिंक्रोनस रूप से लोड करने के लिए विधि का उपयोग करें[`Navigate`](../../aspose.html.dom/document/navigate/) या इसके ओवरलोड्स. या आप उपयुक्त फ़्लैग्स सेट करके कुछ बाहरी संसाधनों को लोड करना अक्षम कर सकते हैं[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |
| [HTMLDocument](htmldocument/#constructor_13)(string, Url, Configuration) | का एक नया उदाहरण प्रारंभ करता है`HTMLDocument` कक्षा। कंस्ट्रक्टर समकालिक रूप से काम करता है, यह सभी बाहरी संसाधनों (छवियों, स्क्रिप्ट, आदि) के लोड होने की प्रतीक्षा करता है। दस्तावेज़ को एसिंक्रोनस रूप से लोड करने के लिए विधि का उपयोग करें[`Navigate`](../../aspose.html.dom/document/navigate/) या इसके ओवरलोड्स. या आप उपयुक्त फ़्लैग्स सेट करके कुछ बाहरी संसाधनों को लोड करना अक्षम कर सकते हैं[`Security`](../../aspose.html.dom/ibrowsingcontext/security/) . |

## गुण

| नाम | विवरण |
| --- | --- |
| [Anchors](../../aspose.html/htmldocument/anchors/) { get; } | सभी एंकर का संग्रह (`ए` ) दस्तावेज़ में तत्व के मान के साथ`नाम`गुण। _ पिछड़े संगतता के कारणों के लिए, एंकरों के लौटाए गए सेट में केवल होते हैं जो एंकरों के साथ बनाए जाते हैं`नाम` विशेषता, न कि के साथ बनाई गई`पहचान` गुण। ध्यान दें कि में [[एक्सएचटीएमएल 1.0](http://www.w3.org/TR/2002/REC-xhtml1-20020801) ], `नाम` विशेषता (धारा 4.10 देखें) का कोई शब्दार्थ नहीं है और केवल विरासती उपयोगकर्ता एजेंटों के लिए मौजूद है:`पहचान` इसके बजाय विशेषता का उपयोग किया जाता है। उपयोगकर्ताओं को [द्वारा प्रदान किए गए इटरेटर तंत्र को प्राथमिकता देनी चाहिए][डोम लेवल 2 ट्रैवर्सल](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113) ] बजाय। |
| [Applets](../../aspose.html/htmldocument/applets/) { get; } | सभी का संग्रह`वस्तु` तत्व जिनमें एप्लेट और शामिल हैं`एप्लेट` (पदावनत) एक दस्तावेज़ में तत्व। |
| virtual [Attributes](../../aspose.html.dom/node/attributes/) { get; } | एक NamedNodeMap जिसमें इस नोड की विशेषताएँ हैं (यदि यह एक तत्व है) या अशक्त अन्यथा। |
| override [BaseURI](../../aspose.html.dom/document/baseuri/) { get; } | इस नोड का पूर्ण आधार यूआरआई या शून्य यदि कार्यान्वयन पूर्ण यूआरआई प्राप्त करने में सक्षम नहीं था। |
| [Body](../../aspose.html/htmldocument/body/) { get; set; } | वह तत्व जिसमें दस्तावेज़ की सामग्री है। दस्तावेजों में के साथ`शरीर` सामग्री, लौटाता है`शरीर` तत्व। फ़्रेमसेट दस्तावेज़ों में, यह सबसे बाहरी लौटाता है`फ़्रेमसेट` तत्व। |
| [CharacterSet](../../aspose.html.dom/document/characterset/) { get; } | दस्तावेज़ की एन्कोडिंग प्राप्त करता है. |
| [Charset](../../aspose.html.dom/document/charset/) { get; } | दस्तावेज़ की एन्कोडिंग प्राप्त करता है. |
| [ChildElementCount](../../aspose.html.dom/document/childelementcount/) { get; } | तत्व नोड्स की वर्तमान संख्या लौटाता है जो इस तत्व के बच्चे हैं। 0 यदि इस तत्व का कोई चाइल्ड नोड नहीं है जो नोड टाइप 1. का है |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | एक नोडलिस्ट जिसमें इस नोड के सभी बच्चे शामिल हैं। यदि कोई बच्चे नहीं हैं, तो यह एक नोडलिस्ट है जिसमें कोई नोड नहीं है.. |
| [Children](../../aspose.html.dom/document/children/) { get; } | बाल तत्व लौटाता है। |
| [ContentType](../../aspose.html.dom/document/contenttype/) { get; } | दस्तावेज़ सामग्री प्रकार प्राप्त करता है। |
| [Context](../../aspose.html.dom/document/context/) { get; } | वर्तमान ब्राउज़िंग प्रसंग प्राप्त करता है. |
| [DefaultView](../../aspose.html.dom/document/defaultview/) { get; } | दस्तावेज़ इंटरफ़ेस की डिफ़ॉल्ट दृश्य आईडीएल विशेषता, प्राप्त करने पर, को इस दस्तावेज़ के ब्राउज़िंग संदर्भ की विंडोप्रॉक्सी ऑब्जेक्ट, को वापस करना होगा, यदि इस दस्तावेज़ में एक संबंधित ब्राउज़िंग संदर्भ है, या शून्य अन्यथा। |
| [Doctype](../../aspose.html.dom/document/doctype/) { get; } | इस दस्तावेज़ से संबद्ध दस्तावेज़ प्रकार घोषणा. |
| [DocumentElement](../../aspose.html.dom/document/documentelement/) { get; } | यह एक सुविधा विशेषता है जो चाइल्ड नोड तक सीधे पहुंच की अनुमति देता है जो दस्तावेज़ का दस्तावेज़ तत्व है। |
| [DocumentURI](../../aspose.html.dom/document/documenturi/) { get; } | दस्तावेज़ का स्थान या अपरिभाषित होने पर शून्य या यदि दस्तावेज़ को DOMImplementation.createDocument. का उपयोग करके बनाया गया था |
| [Domain](../../aspose.html/htmldocument/domain/) { get; } | दस्तावेज़ प्रस्तुत करने वाले सर्वर का डोमेन नाम, या `व्यर्थ` यदि सर्वर को डोमेन नाम से पहचाना नहीं जा सकता है। |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | इस नोड का पहला चाइल्ड। यदि ऐसा कोई नोड नहीं है, तो यह शून्य वापस आ जाता है। |
| [FirstElementChild](../../aspose.html.dom/document/firstelementchild/) { get; } | इस तत्व का पहला बाल तत्व नोड लौटाता है। शून्य अगर इस तत्व में कोई बाल तत्व नहीं है। |
| [Forms](../../aspose.html/htmldocument/forms/) { get; } | दस्तावेज़ के सभी रूपों का संग्रह। |
| [Images](../../aspose.html/htmldocument/images/) { get; } | सभी का संग्रह`आईएमजी` दस्तावेज़ में तत्व। _ व्यवहार तक सीमित है`आईएमजी` पिछड़े संगतता के लिए तत्व। जैसा सुझाव दिया [[एचटीएमएल 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)], छवियों को शामिल करने के लिए, लेखक का उपयोग कर सकते हैं`वस्तु` तत्व या`आईएमजी` तत्व। इसलिए, यह अनुशंसा की जाती है कि दस्तावेज़ में छवियों को खोजने के लिए इस विशेषता का उपयोग न करें लेकिन`getElementsByTagName` HTML 4.01 या के साथ`getElementsByTagNameNS` एक्सएचटीएमएल 1.0. के साथ |
| [Implementation](../../aspose.html.dom/document/implementation/) { get; } | DOMIइम्प्लीमेंटेशन ऑब्जेक्ट जो इस दस्तावेज़ को हैंडल करता है. |
| [InputEncoding](../../aspose.html.dom/document/inputencoding/) { get; } | दस्तावेज़ की एन्कोडिंग प्राप्त करता है. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | इस नोड का अंतिम बच्चा। यदि ऐसा कोई नोड नहीं है, तो यह शून्य वापस आ जाता है। |
| [LastElementChild](../../aspose.html.dom/document/lastelementchild/) { get; } | इस तत्व का अंतिम बाल तत्व नोड लौटाता है। शून्य अगर इस तत्व में कोई बाल तत्व नहीं है। |
| [Links](../../aspose.html/htmldocument/links/) { get; } | सभी का संग्रह`क्षेत्र` तत्व और एंकर ( `ए` ) के मान वाले दस्तावेज़ में तत्व`href` गुण। |
| virtual [LocalName](../../aspose.html.dom/node/localname/) { get; } | इस नोड के योग्य नाम का स्थानीय भाग लौटाता है। ELEMENT_NODE और ATTRIBUTE_NODE के अलावा किसी भी प्रकार के नोड्स और DOM स्तर 1 विधि के साथ बनाए गए नोड्स के लिए, जैसे कि Document.createElement (), यह हमेशा शून्य होता है। |
| [Location](../../aspose.html.dom/document/location/) { get; } | दस्तावेज़ का स्थान। |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri/) { get; } | इस नोड का नामस्थान यूआरआई, या अनिर्दिष्ट होने पर शून्य। |
| [NextElementSibling](../../aspose.html.dom/document/nextelementsibling/) { get; } | इस तत्व का अगला सहोदर तत्व नोड लौटाता है। नल अगर इस तत्व में कोई तत्व सिबलिंग नोड नहीं है जो दस्तावेज़ ट्री में इसके बाद आता है। |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | इस नोड के तुरंत बाद का नोड। यदि ऐसा कोई नोड नहीं है, तो यह शून्य वापस आ जाता है। |
| override [NodeName](../../aspose.html.dom/document/nodename/) { get; } | इस नोड का नाम, इसके प्रकार पर निर्भर करता है। |
| override [NodeType](../../aspose.html.dom/document/nodetype/) { get; } | अंतर्निहित वस्तु के प्रकार का प्रतिनिधित्व करने वाला एक कोड। |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | इस नोड का मान, इसके प्रकार पर निर्भर करता है। |
| [Origin](../../aspose.html.dom/document/origin/) { get; } | दस्तावेज़ की उत्पत्ति प्राप्त करता है। |
| override [OwnerDocument](../../aspose.html.dom/document/ownerdocument/) { get; } | स्वामी दस्तावेज़ प्राप्त करता है. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | माता-पिता को प्राप्त करता है[`Element`](../../aspose.html.dom/element/) इस नोड का. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | इस नोड का जनक। Attr, Document, DocumentFragment, Entity, और Notation को छोड़कर सभी नोड्स में माता-पिता हो सकते हैं। हालाँकि, यदि कोई नोड अभी बनाया गया है और अभी तक ट्री में नहीं जोड़ा गया है, या यदि इसे ट्री से हटा दिया गया है, तो यह शून्य है। |
| virtual [Prefix](../../aspose.html.dom/node/prefix/) { get; set; } | इस नोड का नामस्थान उपसर्ग, या अनिर्दिष्ट होने पर अशक्त। जब इसे शून्य के रूप में परिभाषित किया जाता है, तो इसे सेट करने से कोई प्रभाव नहीं पड़ता |
| [PreviousElementSibling](../../aspose.html.dom/document/previouselementsibling/) { get; } | इस तत्व के पिछले सहोदर तत्व नोड को लौटाता है। नल अगर इस तत्व में कोई तत्व सिबलिंग नोड नहीं है जो दस्तावेज़ ट्री में इससे पहले आता है। |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | इस नोड के ठीक पहले वाला नोड। यदि ऐसा कोई नोड नहीं है, तो यह शून्य वापस आ जाता है। |
| [ReadyState](../../aspose.html.dom/document/readystate/) { get; } | दस्तावेज़ की तैयारी लौटाता है। दस्तावेज़ लोड होने के दौरान "लोडिंग", पार्सिंग समाप्त होने के बाद "इंटरैक्टिव" लेकिन फिर भी उप-संसाधनों को लोड करना, और लोड होने के बाद "पूर्ण"। |
| [Referrer](../../aspose.html/htmldocument/referrer/) { get; } | यूआरआई लौटाता है [[आईईटीएफ आरएफसी 2396](http://www.ietf.org/rfc/rfc2396.txt) उस पृष्ठ का जो इस पृष्ठ से जुड़ा हुआ है। मान एक रिक्त स्ट्रिंग है यदि उपयोगकर्ता सीधे पृष्ठ पर नेविगेट करता है ( लिंक के माध्यम से नहीं, बल्कि, उदाहरण के लिए, बुकमार्क के माध्यम से)। |
| [StrictErrorChecking](../../aspose.html.dom/document/stricterrorchecking/) { get; set; } | एट्रिब्यूट निर्दिष्ट करता है कि त्रुटि जांच लागू की गई है या नहीं। जब गलत पर सेट किया जाता है, तो कार्यान्वयन सामान्य रूप से DOM संचालन पर परिभाषित हर संभव त्रुटि मामले का परीक्षण नहीं करने के लिए स्वतंत्र है, और DOM संचालन पर कोई DOMException नहीं बढ़ाता है या Document.normalizeDocument() का उपयोग करते समय त्रुटियों की रिपोर्ट नहीं करता है। त्रुटि के मामले में, व्यवहार अपरिभाषित है। यह विशेषता डिफ़ॉल्ट रूप से सत्य है। |
| [StyleSheets](../../aspose.html.dom/document/stylesheets/) { get; } | एक सूची जिसमें एक दस्तावेज़ में स्पष्ट रूप से लिंक या एम्बेडेड सभी स्टाइल शीट शामिल हैं। HTML दस्तावेज़ों के लिए, इसमें HTML LINK तत्व के माध्यम से शामिल बाहरी स्टाइल शीट और इनलाइन STYLE तत्व शामिल हैं. |
| virtual [TextContent](../../aspose.html.dom/node/textcontent/) { get; set; } | यह विशेषता इस नोड और उसके वंश की पाठ्य सामग्री लौटाती है। जब इसे शून्य के रूप में परिभाषित किया जाता है, तो इसे सेट करने का कोई प्रभाव नहीं पड़ता है। सेट करने पर, इस नोड के किसी भी संभावित बच्चे को हटा दिया जा सकता है और, यदि यह नया स्ट्रिंग खाली या शून्य नहीं है, तो इस विशेषता को सेट करने वाले स्ट्रिंग वाले एकल टेक्स्ट नोड द्वारा प्रतिस्थापित किया जाता है। |
| [Title](../../aspose.html/htmldocument/title/) { get; set; } | द्वारा निर्दिष्ट दस्तावेज़ का शीर्षक`शीर्षक` दस्तावेज़ के शीर्ष में तत्व । |
| [XmlStandalone](../../aspose.html.dom/document/xmlstandalone/) { get; set; } | एक्सएमएल घोषणा के हिस्से के रूप में निर्दिष्ट एक विशेषता, कि यह दस्तावेज़ स्टैंडअलोन है या नहीं। अनिर्दिष्ट होने पर यह असत्य है। |
| [XmlVersion](../../aspose.html.dom/document/xmlversion/) { get; set; } | एक्सएमएल घोषणा के भाग के रूप में निर्दिष्ट एक विशेषता, इस दस्तावेज़ की संस्करण संख्या। यदि कोई घोषणा नहीं है और यदि यह दस्तावेज़ "XML" सुविधा का समर्थन करता है, तो मान "1.0" है। यदि यह दस्तावेज़ "XML" सुविधा का समर्थन नहीं करता है, तो मान हमेशा शून्य होता है. |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | यह विधि ईवेंट लक्ष्य पर ईवेंट श्रोताओं के पंजीकरण की अनुमति देती है। |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | यह विधि ईवेंट लक्ष्य पर ईवेंट श्रोताओं के पंजीकरण की अनुमति देती है। |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | यह विधि ईवेंट लक्ष्य पर ईवेंट श्रोताओं के पंजीकरण की अनुमति देती है। |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | इस नोड के चिल्ड्रन की सूची के अंत में नोड न्यूचाइल्ड जोड़ता है। यदि नया बच्चा पहले से ही पेड़ में है, तो इसे पहले हटा दिया जाता है। |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | इस नोड का एक डुप्लिकेट लौटाता है, अर्थात, नोड्स के लिए एक सामान्य कॉपी कंस्ट्रक्टर के रूप में कार्य करता है। डुप्लिकेट नोड का कोई पैरेंट नहीं है (parentNode खाली है) और कोई उपयोगकर्ता डेटा नहीं है। |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | इस नोड का एक डुप्लिकेट लौटाता है, अर्थात, नोड्स के लिए एक सामान्य कॉपी कंस्ट्रक्टर के रूप में कार्य करता है। डुप्लिकेट नोड का कोई पैरेंट नहीं है (parentNode खाली है) और कोई उपयोगकर्ता डेटा नहीं है। |
| [CreateAttribute](../../aspose.html.dom/document/createattribute/)(string) | दिए गए नाम का एक Attr बनाता है। |
| [CreateAttributeNS](../../aspose.html.dom/document/createattributens/)(string, string) | दिए गए योग्य नाम और नाम स्थान URI. की विशेषता बनाता है |
| [CreateCDATASection](../../aspose.html.dom/document/createcdatasection/)(string) | एक CDATASection नोड बनाता है जिसका मान निर्दिष्ट स्ट्रिंग है। |
| [CreateComment](../../aspose.html.dom/document/createcomment/)(string) | निर्दिष्ट स्ट्रिंग दिए जाने पर एक टिप्पणी नोड बनाता है। |
| [CreateDocumentFragment](../../aspose.html.dom/document/createdocumentfragment/)() | एक खाली डॉक्यूमेंट फ्रैगमेंट ऑब्जेक्ट बनाता है। |
| [CreateDocumentType](../../aspose.html.dom/document/createdocumenttype/)(string, string, string, string) | एक दस्तावेज़ प्रकार नोड बनाता है। |
| [CreateElement](../../aspose.html.dom/document/createelement/)(string) | निर्दिष्ट प्रकार का एक तत्व बनाता है। ध्यान दें कि लौटाया गया उदाहरण एलिमेंट इंटरफ़ेस को लागू करता है, इसलिए विशेषताओं को सीधे लौटाई गई वस्तु पर निर्दिष्ट किया जा सकता है। |
| [CreateElementNS](../../aspose.html.dom/document/createelementns/)(string, string) | दिए गए योग्य नाम और नामस्थान URI. का एक तत्व बनाता है |
| [CreateEntityReference](../../aspose.html.dom/document/createentityreference/)(string) | EntityReference ऑब्जेक्ट बनाता है। इसके अलावा, यदि संदर्भित इकाई ज्ञात है, तो EntityReference नोड की चाइल्ड सूची को संबंधित इकाई नोड के समान बनाया जाता है। |
| [CreateEvent](../../aspose.html.dom/document/createevent/)(string) | एक बनाता है[`Event`](../../aspose.html.dom.events/event/) कार्यान्वयन द्वारा समर्थित एक प्रकार का। |
| [CreateExpression](../../aspose.html.dom/document/createexpression/)(string, IXPathNSResolver) | पार्स किए गए XPath व्यंजक को हल किए गए नामस्थानों के साथ बनाता है. यह उपयोगी है जब किसी एप्लिकेशन में एक अभिव्यक्ति का पुन: उपयोग किया जाएगा क्योंकि यह अभिव्यक्ति स्ट्रिंग को एक अधिक कुशल आंतरिक रूप में संकलित करने के लिए को संभव बनाता है और अभिव्यक्ति के भीतर होने वाले सभी नामस्थान उपसर्गों को पूर्व-समाधान करता है। |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node) | निर्दिष्ट नोड पर रूट किए गए सबट्री पर एक नया नोडइटरेटर बनाएं। |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node, long) | निर्दिष्ट नोड पर रूट किए गए सबट्री पर एक नया नोडइटरेटर बनाएं। |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/)(Node, long, INodeFilter) | निर्दिष्ट नोड पर रूट किए गए सबट्री पर एक नया नोडइटरेटर बनाएं। |
| [CreateNSResolver](../../aspose.html.dom/document/creatensresolver/)(Node) | नामस्थानों को हल करने के लिए किसी भी DOM नोड को अनुकूलित करता है ताकि XPath एक्सप्रेशन का आसानी से मूल्यांकन किया जा सके उस नोड के संदर्भ के सापेक्ष जहां वह दस्तावेज़ में दिखाई दिया था। यह एडॉप्टर DOM लेवल 3 विधि की तरह काम करता है`lookupNamespaceURI` नोड के पदानुक्रम में time lookupNamespaceURI पर उपलब्ध वर्तमान जानकारी का उपयोग करके दिए गए उपसर्ग से namespaceURI को हल करने में नोड्स पर, अंतर्निहित xml उपसर्ग को भी सही ढंग से हल करना। |
| [CreateProcessingInstruction](../../aspose.html.dom/document/createprocessinginstruction/)(string, string) | निर्दिष्ट नाम और डेटा स्ट्रिंग्स दिए जाने पर एक प्रोसेसिंग इंस्ट्रक्शन नोड बनाता है। |
| [CreateTextNode](../../aspose.html.dom/document/createtextnode/)(string) | निर्दिष्ट स्ट्रिंग दिए जाने पर एक टेक्स्ट नोड बनाता है। |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node) | निर्दिष्ट नोड पर रूट किए गए सबट्री पर एक नया ट्रीवॉकर बनाएं। |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node, long) | निर्दिष्ट नोड पर रूट किए गए सबट्री पर एक नया ट्रीवॉकर बनाएं। |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/)(Node, long, INodeFilter) | निर्दिष्ट नोड पर रूट किए गए सबट्री पर एक नया ट्रीवॉकर बनाएं। |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | यह विधि इवेंट को कार्यान्वयन इवेंट मॉडल में भेजने की अनुमति देती है. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | अप्रबंधित संसाधनों को मुक्त करने, जारी करने या रीसेट करने से संबंधित एप्लिकेशन-परिभाषित कार्य करता है। |
| [Evaluate](../../aspose.html.dom/document/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | एक XPath अभिव्यक्ति स्ट्रिंग का मूल्यांकन करता है और यदि संभव हो तो निर्दिष्ट प्रकार का परिणाम देता है। |
| [GetElementById](../../aspose.html.dom/document/getelementbyid/)(string) | उस तत्व को लौटाता है जिसमें दिए गए मान के साथ एक आईडी विशेषता होती है। यदि ऐसा कोई तत्व मौजूद नहीं है, तो यह शून्य हो जाता है। यदि एक से अधिक तत्वों में उस मान के साथ एक आईडी विशेषता है, तो जो लौटाया जाता है वह अनिर्धारित होता है। |
| [GetElementsByClassName](../../aspose.html.dom/document/getelementsbyclassname/)(string) | एक लाइव नोडलिस्ट ऑब्जेक्ट लौटाता है जिसमें दस्तावेज़ में सभी तत्व होते हैं जिनमें तर्क में निर्दिष्ट सभी वर्ग होते हैं। http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/document/getelementsbytagname/)(string) | दिए गए टैग नाम के साथ दस्तावेज़ क्रम में सभी तत्वों की एक नोडलिस्ट लौटाता है और दस्तावेज़ में समाहित है। |
| [GetElementsByTagNameNS](../../aspose.html.dom/document/getelementsbytagnamens/)(string, string) | दस्तावेज़ क्रम में दिए गए स्थानीय नाम और नामस्थान URI वाले सभी तत्वों की एक नोड सूची लौटाता है। |
| [GetOverrideStyle](../../aspose.html/htmldocument/getoverridestyle/)(Element, string) | इस विधि का उपयोग निर्दिष्ट तत्व और निर्दिष्ट छद्म तत्व के लिए ओवरराइड शैली घोषणा को पुनर्प्राप्त करने के लिए किया जाता है। |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | इस विधि का उपयोग ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए किया जाता हैType . |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes/)() | रिटर्न करता है कि क्या इस नोड (यदि यह एक तत्व है) में कोई विशेषता है |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | लौटाता है कि क्या इस नोड के कोई बच्चे हैं। |
| [ImportNode](../../aspose.html.dom/document/importnode/)(Node, bool) | मूल दस्तावेज़ से स्रोत नोड को बदले या हटाए बिना, किसी अन्य दस्तावेज़ से इस दस्तावेज़ में एक नोड आयात करता है; यह विधि स्रोत नोड की एक नई प्रति बनाती है। |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | मौजूदा चाइल्ड नोड चाइल्ड से पहले नोड डालें। यदि बच्चा शून्य है, तो बच्चों की सूची के अंत में नोड डालें। यदि बच्चा पहले से ही पेड़ में है, तो उसे पहले हटा दिया जाता है। |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | यह विधि जांचती है कि निर्दिष्ट नामस्थान यूआरआई डिफ़ॉल्ट नामस्थान है या नहीं। |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | परीक्षण करता है कि क्या दो नोड समान हैं। यह विधि नोड्स की समानता के लिए परीक्षण करती है, समरूपता के लिए नहीं (अर्थात, क्या दो नोड एक ही वस्तु के संदर्भ हैं) जिसे Node.isSameNode() के साथ परीक्षण किया जा सकता है। सभी नोड जो समान हैं, वे भी बराबर होंगे, हालांकि रिवर्स सत्य नहीं हो सकता है। |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | रिटर्न देता है कि क्या यह नोड दिए गए नोड के समान नोड है। यह विधि यह निर्धारित करने का एक तरीका प्रदान करती है कि कार्यान्वयन द्वारा लौटाए गए दो नोड संदर्भ एक ही वस्तु को संदर्भित करते हैं या नहीं। जब दो नोड संदर्भ एक ही वस्तु के संदर्भ होते हैं, भले ही एक प्रॉक्सी के माध्यम से, संदर्भों को पूरी तरह से एक दूसरे के स्थान पर उपयोग किया जा सकता है, जैसे कि सभी विशेषताओं में समान मान होते हैं और समान DOM विधि को किसी भी संदर्भ पर कॉल करने का हमेशा एक ही प्रभाव होता है। |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | इस नोड से शुरू करते हुए, दिए गए उपसर्ग से जुड़े नामस्थान यूआरआई को देखें। |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | इस नोड से शुरू करते हुए दिए गए नेमस्पेस यूआरआई से जुड़े उपसर्ग को देखें। इस विधि द्वारा डिफ़ॉल्ट नामस्थान घोषणाओं को अनदेखा किया जाता है। इस विधि द्वारा उपयोग किए गए एल्गोरिदम पर विवरण के लिए नामस्थान उपसर्ग लुकअप देखें। |
| [Navigate](../../aspose.html.dom/document/navigate/)(RequestMessage) | निर्दिष्ट अनुरोध वस्तु के आधार पर दस्तावेज़ को लोड करता है, पिछली सामग्री को प्रतिस्थापित करता है। |
| [Navigate](../../aspose.html.dom/document/navigate/)(string) | निर्दिष्ट यूनिफ़ॉर्म रिसोर्स लोकेटर (URL) पर दस्तावेज़ को वर्तमान उदाहरण में लोड करता है, पिछली सामग्री को प्रतिस्थापित करता है। |
| [Navigate](../../aspose.html.dom/document/navigate/)(Url) | निर्दिष्ट यूनिफ़ॉर्म रिसोर्स लोकेटर (URL) पर दस्तावेज़ को वर्तमान उदाहरण में लोड करता है, पिछली सामग्री को प्रतिस्थापित करता है। |
| [Navigate](../../aspose.html.dom/document/navigate/)(Stream, string) | दस्तावेज़ को निर्दिष्ट सामग्री से लोड करता है और संबंधित संसाधनों को हल करने के लिए बेसयूरी का उपयोग करता है, पिछली सामग्री को प्रतिस्थापित करता है। दस्तावेज़ लोडिंग स्ट्रीम में वर्तमान स्थिति से शुरू होती है। |
| [Navigate](../../aspose.html.dom/document/navigate/)(Stream, Url) | दस्तावेज़ को निर्दिष्ट सामग्री से लोड करता है और संबंधित संसाधनों को हल करने के लिए बेसयूरी का उपयोग करता है, पिछली सामग्री को प्रतिस्थापित करता है। दस्तावेज़ लोडिंग स्ट्रीम में वर्तमान स्थिति से शुरू होती है। |
| [Navigate](../../aspose.html.dom/document/navigate/)(string, string) | निर्दिष्ट सामग्री से दस्तावेज़ लोड करता है और संबंधित संसाधनों को हल करने के लिए बेसयूरी का उपयोग करता है, पिछली सामग्री को प्रतिस्थापित करता है। |
| [Navigate](../../aspose.html.dom/document/navigate/)(string, Url) | निर्दिष्ट सामग्री से दस्तावेज़ लोड करता है और संबंधित संसाधनों को हल करने के लिए बेसयूरी का उपयोग करता है, पिछली सामग्री को प्रतिस्थापित करता है। |
| [Normalize](../../aspose.html.dom/node/normalize/)() | सभी टेक्स्ट नोड्स को इस नोड के नीचे सब-ट्री की पूरी गहराई में रखता है, विशेषता नोड्स सहित, एक "सामान्य" रूप में जहां केवल संरचना (जैसे, तत्व, टिप्पणियां, प्रसंस्करण निर्देश, सीडीएटीए अनुभाग और इकाई संदर्भ) टेक्स्ट को अलग करती है। नोड्स, यानी, न तो सन्निकट टेक्स्ट नोड्स हैं और न ही खाली टेक्स्ट नोड्स। इसका उपयोग यह सुनिश्चित करने के लिए किया जा सकता है कि किसी दस्तावेज़ का DOM दृश्य वैसा ही है जैसे कि उसे सहेजा गया था और पुनः लोड किया गया था, और जब संचालन (जैसे XPointer [XPointer] लुकअप) जो किसी विशेष दस्तावेज़ ट्री संरचना पर निर्भर करता है, तब उपयोगी होता है इस्तेमाल किया गया। यदि Node.ownerDocument से जुड़ी DOMConfiguration ऑब्जेक्ट का पैरामीटर "सामान्यीकृत-अक्षर" सत्य है, तो यह विधि टेक्स्ट नोड्स के वर्णों को भी पूरी तरह से सामान्य कर देगी। |
| [QuerySelector](../../aspose.html.dom/document/queryselector/)(string) | दस्तावेज़ में पहला तत्व लौटाता है, जो चयनकर्ता से मेल खाता है |
| [QuerySelectorAll](../../aspose.html.dom/document/queryselectorall/)(string) | दस्तावेज़ में सभी तत्वों की एक नोड सूची देता है, जो चयनकर्ता से मेल खाता है |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | ओल्डचाइल्ड द्वारा बच्चों की सूची से संकेतित चाइल्ड नोड को हटाता है, और इसे वापस करता है। |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | यह विधि ईवेंट श्रोताओं को ईवेंट लक्ष्य से हटाने की अनुमति देती है। यदि कोई[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) एक से हटा दिया जाता है[`EventTarget`](../../aspose.html.dom/eventtarget/) जबकि यह किसी घटना को संसाधित कर रहा है, यह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं किया जाएगा। इवेंट श्रोताओं को हटाए जाने के बाद कभी नहीं बुलाया जा सकता है। |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | यह विधि ईवेंट श्रोताओं को ईवेंट लक्ष्य से हटाने की अनुमति देती है। यदि कोई[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) एक से हटा दिया जाता है[`EventTarget`](../../aspose.html.dom/eventtarget/) जबकि यह किसी घटना को संसाधित कर रहा है, यह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं किया जाएगा। इवेंट श्रोताओं को हटाए जाने के बाद कभी नहीं बुलाया जा सकता है। |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | यह विधि ईवेंट श्रोताओं को ईवेंट लक्ष्य से हटाने की अनुमति देती है। यदि कोई[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) एक से हटा दिया जाता है[`EventTarget`](../../aspose.html.dom/eventtarget/) जबकि यह किसी घटना को संसाधित कर रहा है, यह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं किया जाएगा। इवेंट श्रोताओं को हटाए जाने के बाद कभी नहीं बुलाया जा सकता है। |
| override [RenderTo](../../aspose.html/htmldocument/renderto/)(IDevice) | इस विधि का उपयोग वर्तमान दस्तावेज़ की सामग्री को निर्दिष्ट डिवाइस पर प्रिंट करने के लिए किया जाता है। |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | बच्चों की सूची में चाइल्ड नोड ओल्डचाइल्ड को न्यूचाइल्ड से बदल देता है, और ओल्डचाइल्ड नोड लौटाता है। यदि न्यूचाइल्ड एक डॉक्यूमेंटफ्रैगमेंट ऑब्जेक्ट है, तो ओल्डचाइल्ड को सभी डॉक्यूमेंटफ्रैगमेंट चिल्ड्रेन से बदल दिया जाता है, जो उसी क्रम में डाले जाते हैं। यदि नया बच्चा पहले से ही पेड़ में है, तो इसे पहले हटा दिया जाता है। |
| [Save](../../aspose.html/htmldocument/save/#save)(IOutputStorage) | दस्तावेज़ सामग्री और संसाधनों को आउटपुट स्टोरेज में सहेजता है। |
| [Save](../../aspose.html/htmldocument/save/#save_10)(string) | द्वारा निर्दिष्ट स्थानीय फ़ाइल में दस्तावेज़ सहेजता है`पथ` इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को में आसन्न फ़ोल्डर में सहेजा जाएगा, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_5)(Url) | द्वारा निर्दिष्ट स्थानीय फ़ाइल में दस्तावेज़ सहेजता है`यूआरएल` इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को में आसन्न फ़ोल्डर में सहेजा जाएगा, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_1)(IOutputStorage, HTMLSaveFormat) | दस्तावेज़ सामग्री और संसाधनों को आउटपुट स्टोरेज में सहेजता है। |
| [Save](../../aspose.html/htmldocument/save/#save_2)(IOutputStorage, HTMLSaveOptions) | दस्तावेज़ सामग्री और संसाधनों को आउटपुट स्टोरेज में सहेजता है। |
| [Save](../../aspose.html/htmldocument/save/#save_3)(IOutputStorage, MarkdownSaveOptions) | दस्तावेज़ सामग्री और संसाधनों को आउटपुट स्टोरेज में सहेजता है। |
| [Save](../../aspose.html/htmldocument/save/#save_4)(IOutputStorage, MHTMLSaveOptions) | दस्तावेज़ सामग्री और संसाधनों को आउटपुट स्टोरेज में सहेजता है। |
| [Save](../../aspose.html/htmldocument/save/#save_11)(string, HTMLSaveFormat) | द्वारा निर्दिष्ट स्थानीय फ़ाइल में दस्तावेज़ सहेजता है`पथ` इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को में आसन्न फ़ोल्डर में सहेजा जाएगा, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_12)(string, HTMLSaveOptions) | द्वारा निर्दिष्ट स्थानीय फ़ाइल में दस्तावेज़ सहेजता है`पथ` इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को में आसन्न फ़ोल्डर में सहेजा जाएगा, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_13)(string, MarkdownSaveOptions) | द्वारा निर्दिष्ट स्थानीय फ़ाइल में दस्तावेज़ सहेजता है`पथ` इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को में आसन्न फ़ोल्डर में सहेजा जाएगा, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_14)(string, MHTMLSaveOptions) | द्वारा निर्दिष्ट स्थानीय फ़ाइल में दस्तावेज़ सहेजता है`पथ` इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को में आसन्न फ़ोल्डर में सहेजा जाएगा, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_6)(Url, HTMLSaveFormat) | द्वारा निर्दिष्ट स्थानीय फ़ाइल में दस्तावेज़ सहेजता है`यूआरएल` इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को में आसन्न फ़ोल्डर में सहेजा जाएगा, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_7)(Url, HTMLSaveOptions) | द्वारा निर्दिष्ट स्थानीय फ़ाइल में दस्तावेज़ सहेजता है`यूआरएल` इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को में आसन्न फ़ोल्डर में सहेजा जाएगा, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_8)(Url, MarkdownSaveOptions) | द्वारा निर्दिष्ट स्थानीय फ़ाइल में दस्तावेज़ सहेजता है`यूआरएल` इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को में आसन्न फ़ोल्डर में सहेजा जाएगा, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files". |
| [Save](../../aspose.html/htmldocument/save/#save_9)(Url, MHTMLSaveOptions) | द्वारा निर्दिष्ट स्थानीय फ़ाइल में दस्तावेज़ सहेजता है`यूआरएल` इस दस्तावेज़ में उपयोग किए गए सभी संसाधनों को में आसन्न फ़ोल्डर में सहेजा जाएगा, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files". |
| override [ToString](../../aspose.html.dom/node/tostring/)() | रिटर्न एString जो इस उदाहरण का प्रतिनिधित्व करता है। |
| [Write](../../aspose.html.dom/document/write/)(params string[]) | open() द्वारा खोले गए दस्तावेज़ स्ट्रीम में टेक्स्ट की एक स्ट्रिंग लिखें। ध्यान दें कि फ़ंक्शन एक दस्तावेज़ उत्पन्न करेगा जो आवश्यक रूप से डीटीडी द्वारा संचालित नहीं है और इसलिए हो सकता है दस्तावेज़ के संदर्भ में एक अमान्य परिणाम उत्पन्न करता है। |
| [WriteLn](../../aspose.html.dom/document/writeln/)(params string[]) | खुले() द्वारा खोले गए दस्तावेज़ स्ट्रीम में टेक्स्ट की एक स्ट्रिंग लिखें जिसके बाद एक न्यूलाइन वर्ण हो। ध्यान दें कि फ़ंक्शन will एक दस्तावेज़ तैयार करेगा जो आवश्यक रूप से DTD द्वारा संचालित नहीं है और इसलिए दस्तावेज़ के संदर्भ में एक अमान्य परिणाम उत्पन्न कर सकता है |

## आयोजन

| नाम | विवरण |
| --- | --- |
| event [OnAbort](../../aspose.html.dom/document/onabort/) | ऑनएबॉर्ट इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnBlur](../../aspose.html.dom/document/onblur/) | ऑनब्लर इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnCancel](../../aspose.html.dom/document/oncancel/) | OnCancel ईवेंट के लिए ईवेंट हैंडलर प्राप्त करता है या सेट करता है. |
| event [OnCanplay](../../aspose.html.dom/document/oncanplay/) | ऑनकैनप्ले इवेंट के लिए इवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnCanPlayThrough](../../aspose.html.dom/document/oncanplaythrough/) | ऑनकैनप्लेथ्रू इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnChange](../../aspose.html.dom/document/onchange/) | ऑन चेंज इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnClick](../../aspose.html.dom/document/onclick/) | ऑनक्लिक ईवेंट के लिए ईवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnCueChange](../../aspose.html.dom/document/oncuechange/) | ऑनक्यू चेंज इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnDblClick](../../aspose.html.dom/document/ondblclick/) | ऑनडब्लिक इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnDurationChange](../../aspose.html.dom/document/ondurationchange/) | ऑन ड्यूरेशन चेंज इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnEmptied](../../aspose.html.dom/document/onemptied/) | OnEmptied इवेंट के लिए इवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnEnded](../../aspose.html.dom/document/onended/) | ऑनएंडेड इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnError](../../aspose.html.dom/document/onerror/) | ऑनरर इवेंट के लिए इवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnFocus](../../aspose.html.dom/document/onfocus/) | ऑनफोकस इवेंट के लिए इवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnInput](../../aspose.html.dom/document/oninput/) | ऑनइनपुट ईवेंट के लिए ईवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnInvalid](../../aspose.html.dom/document/oninvalid/) | ऑन-इनवैलिड इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnKeyDown](../../aspose.html.dom/document/onkeydown/) | ऑनकेडाउन इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnKeyPress](../../aspose.html.dom/document/onkeypress/) | ऑनकीप्रेस ईवेंट के लिए ईवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnKeyUp](../../aspose.html.dom/document/onkeyup/) | ऑनकीअप इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnLoad](../../aspose.html.dom/document/onload/) | ऑनलोड ईवेंट के लिए ईवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnLoadedData](../../aspose.html.dom/document/onloadeddata/) | ऑनलोडेडडेटा ईवेंट के लिए ईवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnLoadedMetadata](../../aspose.html.dom/document/onloadedmetadata/) | ऑनलोडेड मेटाडेटा ईवेंट के लिए ईवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnLoadStart](../../aspose.html.dom/document/onloadstart/) | ऑनलोडस्टार्ट ईवेंट के लिए ईवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnMouseDown](../../aspose.html.dom/document/onmousedown/) | ऑनमाउसडाउन ईवेंट के लिए ईवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnMouseEnter](../../aspose.html.dom/document/onmouseenter/) | ऑनमाउस एंटर इवेंट के लिए इवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnMouseLeave](../../aspose.html.dom/document/onmouseleave/) | ऑनमाउसलीव इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnMouseMove](../../aspose.html.dom/document/onmousemove/) | ऑनमाउसमोव इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnMouseOut](../../aspose.html.dom/document/onmouseout/) | ऑनमाउसऑउट इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnMouseOver](../../aspose.html.dom/document/onmouseover/) | ऑनमाउसओवर ईवेंट के लिए इवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnMouseUp](../../aspose.html.dom/document/onmouseup/) | ऑनमाउसअप इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnMouseWheel](../../aspose.html.dom/document/onmousewheel/) | ऑनमाउसव्हील इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnPause](../../aspose.html.dom/document/onpause/) | ऑनपॉज इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnPlay](../../aspose.html.dom/document/onplay/) | ऑनप्ले इवेंट के लिए इवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnPlaying](../../aspose.html.dom/document/onplaying/) | ऑनप्लेइंग इवेंट के लिए इवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnProgress](../../aspose.html.dom/document/onprogress/) | ऑनप्रोग्रेस इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnRateChange](../../aspose.html.dom/document/onratechange/) | ऑनरेट चेंज इवेंट के लिए इवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnReadyStateChange](../../aspose.html.dom/document/onreadystatechange/) | ऑनरेडीस्टेट चेंज इवेंट के लिए इवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnReset](../../aspose.html.dom/document/onreset/) | ऑनरीसेट ईवेंट के लिए इवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnResize](../../aspose.html.dom/document/onresize/) | OnResize ईवेंट के लिए इवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnScroll](../../aspose.html.dom/document/onscroll/) | ऑनस्क्रॉल इवेंट के लिए इवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnSeeked](../../aspose.html.dom/document/onseeked/) | ऑनसीकेड इवेंट के लिए इवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnSeeking](../../aspose.html.dom/document/onseeking/) | ऑनसीकिंग इवेंट के लिए इवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnSelect](../../aspose.html.dom/document/onselect/) | ऑनसेलेक्ट इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnShow](../../aspose.html.dom/document/onshow/) | ऑनशो इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnStalled](../../aspose.html.dom/document/onstalled/) | ऑनस्टाल्ड इवेंट के लिए इवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnSubmit](../../aspose.html.dom/document/onsubmit/) | ऑनसबमिट इवेंट के लिए इवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnSuspend](../../aspose.html.dom/document/onsuspend/) | ऑनसस्पेंड इवेंट के लिए इवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnTimeUpdate](../../aspose.html.dom/document/ontimeupdate/) | ऑनटाइमअपडेट इवेंट के लिए इवेंट हैंडलर प्राप्त करता है या सेट करता है। |
| event [OnToggle](../../aspose.html.dom/document/ontoggle/) | ऑनटॉगल ईवेंट के लिए ईवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnVolumeChange](../../aspose.html.dom/document/onvolumechange/) | ऑनवॉल्यूम चेंज इवेंट के लिए इवेंट हैंडलर प्राप्त या सेट करता है। |
| event [OnWaiting](../../aspose.html.dom/document/onwaiting/) | ऑनवेटिंग इवेंट के लिए इवेंट हैंडलर प्राप्त या सेट करता है। |

### यह सभी देखें

* class [Document](../../aspose.html.dom/document/)
* interface [IDocumentCSS](../../aspose.html.dom.css/idocumentcss/)
* नाम स्थान [Aspose.Html](../../aspose.html/)
* सभा [Aspose.HTML](../../)


