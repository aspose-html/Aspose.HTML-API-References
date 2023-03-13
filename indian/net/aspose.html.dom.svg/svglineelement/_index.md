---
title: Class SVGLineElement
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Svg.SVGLineElement कक्ष. SVGLineElement इंटरफ़ेस लइन तत्व से संबंधत है
type: docs
weight: 2130
url: /hi/net/aspose.html.dom.svg/svglineelement/
---
## SVGLineElement class

SVGLineElement इंटरफ़ेस 'लाइन' तत्व से संबंधित है।

```csharp
public class SVGLineElement : SVGGeometryElement
```

## गुण

| नाम | विवरण |
| --- | --- |
| override [Attributes](../../aspose.html.dom/element/attributes/) { get; } | एक NamedNodeMap जिसमें इस नोड की विशेषताएँ हैं (यदि यह एक तत्व है) या अशक्त अन्यथा। |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri/) { get; } | इस नोड का पूर्ण आधार यूआरआई या शून्य यदि कार्यान्वयन पूर्ण यूआरआई प्राप्त करने में सक्षम नहीं था। |
| [ChildElementCount](../../aspose.html.dom/element/childelementcount/) { get; } | तत्व नोड्स की वर्तमान संख्या लौटाता है जो इस तत्व के बच्चे हैं। 0 यदि इस तत्व का कोई चाइल्ड नोड नहीं है जो नोड टाइप 1. का है |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | एक नोडलिस्ट जिसमें इस नोड के सभी बच्चे शामिल हैं। यदि कोई बच्चे नहीं हैं, तो यह एक नोडलिस्ट है जिसमें कोई नोड नहीं है.. |
| [Children](../../aspose.html.dom/element/children/) { get; } | वर्तमान तत्व के बाल तत्व लौटाता है। |
| [ClassList](../../aspose.html.dom/element/classlist/) { get; } | एक लाइव DOMTokenList लौटाता है जिसमें "वर्ग" विशेषता को पार्स करने से प्राप्त टोकन शामिल हैं। |
| [ClassName](../../aspose.html.dom.svg/svgelement/classname/) { get; } | दिए गए तत्व पर विशेषता 'वर्ग' के अनुरूप है। |
| [ClassName](../../aspose.html.dom/element/classname/) { get; set; } | तत्व की वर्ग विशेषता। कई भाषाओं द्वारा प्रकट किए गए "वर्ग" कीवर्ड के विरोध के कारण इस एट्रिब्यूट का नाम ड्यू कर दिया गया है। देखें HTML 4.01. में वर्ग विशेषता परिभाषा |
| [FarthestViewportElement](../../aspose.html.dom.svg/svggraphicselement/farthestviewportelement/) { get; } | सबसे दूर का पूर्वज 'svg' तत्व। शून्य अगर वर्तमान तत्व सबसे बाहरी svg तत्व है. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | इस नोड का पहला चाइल्ड। यदि ऐसा कोई नोड नहीं है, तो यह शून्य वापस आ जाता है। |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild/) { get; } | इस तत्व का पहला बाल तत्व नोड लौटाता है। शून्य अगर इस तत्व में कोई बाल तत्व नहीं है। |
| [Id](../../aspose.html.dom.svg/svgelement/id/) { get; set; } | दिए गए तत्व पर 'आईडी' विशेषता का मान, या 'आईडी' मौजूद नहीं होने पर खाली स्ट्रिंग। |
| [InnerHTML](../../aspose.html.dom/element/innerhtml/) { get; set; } | HTML या XML का एक टुकड़ा देता है जो तत्व की सामग्री का प्रतिनिधित्व करता है। दिए गए स्ट्रिंग से पार्स किए गए नोड्स के साथ तत्व की सामग्री को बदलने के लिए सेट किया जा सकता है। |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | इस नोड का अंतिम बच्चा। यदि ऐसा कोई नोड नहीं है, तो यह शून्य वापस आ जाता है। |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild/) { get; } | इस तत्व का अंतिम बाल तत्व नोड लौटाता है। शून्य अगर इस तत्व में कोई बाल तत्व नहीं है। |
| override [LocalName](../../aspose.html.dom/element/localname/) { get; } | इस नोड के योग्य नाम का स्थानीय भाग लौटाता है। ELEMENT_NODE और ATTRIBUTE_NODE के अलावा किसी भी प्रकार के नोड्स और DOM स्तर 1 विधि के साथ बनाए गए नोड्स के लिए, जैसे कि Document.createElement (), यह हमेशा शून्य होता है। |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri/) { get; } | इस नोड का नामस्थान यूआरआई, या अनिर्दिष्ट होने पर शून्य। |
| [NearestViewportElement](../../aspose.html.dom.svg/svggraphicselement/nearestviewportelement/) { get; } | वह तत्व जिसने वर्तमान व्यूपोर्ट स्थापित किया। अक्सर, निकटतम पूर्वज 'svg' तत्व। शून्य अगर वर्तमान तत्व सबसे बाहरी svg तत्व है. |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling/) { get; } | इस तत्व का अगला सहोदर तत्व नोड लौटाता है। नल अगर इस तत्व में कोई तत्व सिबलिंग नोड नहीं है जो दस्तावेज़ ट्री में इसके बाद आता है। |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | इस नोड के तुरंत बाद का नोड। यदि ऐसा कोई नोड नहीं है, तो यह शून्य वापस आ जाता है। |
| override [NodeName](../../aspose.html.dom/element/nodename/) { get; } | इस नोड का नाम, इसके प्रकार पर निर्भर करता है। |
| override [NodeType](../../aspose.html.dom/element/nodetype/) { get; } | अंतर्निहित वस्तु के प्रकार का प्रतिनिधित्व करने वाला एक कोड। |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | इस नोड का मान, इसके प्रकार पर निर्भर करता है। |
| [OuterHTML](../../aspose.html.dom/element/outerhtml/) { get; set; } | HTML या XML का एक टुकड़ा देता है जो तत्व और उसकी सामग्री का प्रतिनिधित्व करता है। दिए गए स्ट्रिंग से पार्स किए गए नोड्स के साथ तत्व को बदलने के लिए सेट किया जा सकता है। |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument/) { get; } | इस नोड से जुड़ा दस्तावेज़ ऑब्जेक्ट। यह नए नोड बनाने के लिए उपयोग की जाने वाली दस्तावेज़ वस्तु भी है। जब यह नोड एक दस्तावेज़ या एक दस्तावेज़ प्रकार है जिसका अभी तक किसी दस्तावेज़ के साथ उपयोग नहीं किया गया है, तो यह शून्य है। |
| [OwnerSVGElement](../../aspose.html.dom.svg/svgelement/ownersvgelement/) { get; } | निकटतम पूर्वज 'svg' तत्व। नल अगर दिया गया तत्व सबसे बाहरी svg तत्व है। |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | माता-पिता को प्राप्त करता है[`Element`](../../aspose.html.dom/element/) इस नोड का. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | इस नोड का जनक। Attr, Document, DocumentFragment, Entity, और Notation को छोड़कर सभी नोड्स में माता-पिता हो सकते हैं। हालाँकि, यदि कोई नोड अभी बनाया गया है और अभी तक ट्री में नहीं जोड़ा गया है, या यदि इसे ट्री से हटा दिया गया है, तो यह शून्य है। |
| [PathLength](../../aspose.html.dom.svg/svggeometryelement/pathlength/) { get; } | दिए गए तत्व पर विशेषता पथ लंबाई के अनुरूप है। |
| override [Prefix](../../aspose.html.dom/element/prefix/) { get; } | इस नोड का नामस्थान उपसर्ग, या अनिर्दिष्ट होने पर अशक्त। जब इसे शून्य के रूप में परिभाषित किया जाता है, तो इसे सेट करने से कोई प्रभाव नहीं पड़ता |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling/) { get; } | इस तत्व के पिछले सहोदर तत्व नोड को लौटाता है। नल अगर इस तत्व में कोई तत्व सिबलिंग नोड नहीं है जो दस्तावेज़ ट्री में इससे पहले आता है। |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | इस नोड के ठीक पहले वाला नोड। यदि ऐसा कोई नोड नहीं है, तो यह शून्य वापस आ जाता है। |
| [RequiredExtensions](../../aspose.html.dom.svg/svggraphicselement/requiredextensions/) { get; } | दिए गए तत्व पर विशेषता 'आवश्यक एक्सटेंशन' के अनुरूप है। |
| [RequiredFeatures](../../aspose.html.dom.svg/svggraphicselement/requiredfeatures/) { get; } | दिए गए तत्व पर विशेषता 'आवश्यक सुविधाओं' के अनुरूप है। |
| [SchemaTypeInfo](../../aspose.html.dom/element/schematypeinfo/) { get; } | इस तत्व से जुड़ी प्रकार की जानकारी। |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot/) { get; } | इस तत्व पर संग्रहीत शैडोरूट लौटाता है या बंद होने पर अशक्त होता है। |
| [Style](../../aspose.html.dom.svg/svgelement/style/) { get; } | दिए गए तत्व पर विशेषता 'शैली' के अनुरूप है। यदि उपयोगकर्ता एजेंट सीएसएस के साथ स्टाइलिंग का समर्थन नहीं करता है, तो इस विशेषता में हमेशा शून्य का मान होना चाहिए। |
| [SystemLanguage](../../aspose.html.dom.svg/svggraphicselement/systemlanguage/) { get; } | दिए गए तत्व पर विशेषता 'systemLanguage' के अनुरूप है। |
| [TagName](../../aspose.html.dom/element/tagname/) { get; } | तत्व का नाम। |
| override [TextContent](../../aspose.html.dom/element/textcontent/) { get; set; } | यह विशेषता इस नोड और उसके वंश की पाठ्य सामग्री लौटाती है। जब इसे शून्य के रूप में परिभाषित किया जाता है, तो इसे सेट करने का कोई प्रभाव नहीं पड़ता है। सेट करने पर, इस नोड के किसी भी संभावित बच्चे को हटा दिया जा सकता है और, यदि यह नया स्ट्रिंग खाली या शून्य नहीं है, तो इस विशेषता को सेट करने वाले स्ट्रिंग वाले एकल टेक्स्ट नोड द्वारा प्रतिस्थापित किया जाता है। |
| [Transform](../../aspose.html.dom.svg/svggraphicselement/transform/) { get; } | दिए गए तत्व पर विशेषता 'रूपांतरण' के अनुरूप है। |
| [ViewportElement](../../aspose.html.dom.svg/svgelement/viewportelement/) { get; } | वह तत्व जिसने वर्तमान व्यूपोर्ट स्थापित किया। अक्सर, निकटतम पूर्वज 'svg' तत्व। नल अगर दिया गया तत्व सबसे बाहरी svg तत्व है। |
| [X1](../../aspose.html.dom.svg/svglineelement/x1/) { get; } | दिए गए 'लाइन' तत्व पर विशेषता 'X1' के अनुरूप है। |
| [X2](../../aspose.html.dom.svg/svglineelement/x2/) { get; } | दिए गए 'लाइन' तत्व पर विशेषता 'x2' के अनुरूप है। |
| [Y1](../../aspose.html.dom.svg/svglineelement/y1/) { get; } | दिए गए 'लाइन' तत्व पर विशेषता 'y1' के अनुरूप है। |
| [Y2](../../aspose.html.dom.svg/svglineelement/y2/) { get; } | दिए गए 'लाइन' तत्व पर विशेषता 'y2' के अनुरूप है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | यह विधि ईवेंट लक्ष्य पर ईवेंट श्रोताओं के पंजीकरण की अनुमति देती है। |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | यह विधि ईवेंट लक्ष्य पर ईवेंट श्रोताओं के पंजीकरण की अनुमति देती है। |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | यह विधि ईवेंट लक्ष्य पर ईवेंट श्रोताओं के पंजीकरण की अनुमति देती है। |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | इस नोड के चिल्ड्रन की सूची के अंत में नोड न्यूचाइल्ड जोड़ता है। यदि नया बच्चा पहले से ही पेड़ में है, तो इसे पहले हटा दिया जाता है। |
| [AttachShadow](../../aspose.html.dom/element/attachshadow/)(ShadowRootMode) | छाया जड़ बनाता है और इसे वर्तमान तत्व से जोड़ता है। |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | इस नोड का एक डुप्लिकेट लौटाता है, अर्थात, नोड्स के लिए एक सामान्य कॉपी कंस्ट्रक्टर के रूप में कार्य करता है। डुप्लिकेट नोड का कोई पैरेंट नहीं है (parentNode खाली है) और कोई उपयोगकर्ता डेटा नहीं है। |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | इस नोड का एक डुप्लिकेट लौटाता है, अर्थात, नोड्स के लिए एक सामान्य कॉपी कंस्ट्रक्टर के रूप में कार्य करता है। डुप्लिकेट नोड का कोई पैरेंट नहीं है (parentNode खाली है) और कोई उपयोगकर्ता डेटा नहीं है। |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | यह विधि इवेंट को कार्यान्वयन इवेंट मॉडल में भेजने की अनुमति देती है. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | अप्रबंधित संसाधनों को मुक्त करने, जारी करने या रीसेट करने से संबंधित एप्लिकेशन-परिभाषित कार्य करता है। |
| [GetAttribute](../../aspose.html.dom/element/getattribute/)(string) | नाम से एक विशेषता मान प्राप्त करता है। |
| [GetAttributeNode](../../aspose.html.dom/element/getattributenode/)(string) | नाम से एक विशेषता नोड पुनर्प्राप्त करता है। |
| [GetAttributeNodeNS](../../aspose.html.dom/element/getattributenodens/)(string, string) | स्थानीय नाम और नाम स्थान URI. द्वारा एक Attr नोड प्राप्त करता है |
| [GetAttributeNS](../../aspose.html.dom/element/getattributens/)(string, string) | स्थानीय नाम और नाम स्थान URI. द्वारा एक विशेषता मान प्राप्त करता है |
| [GetBBox](../../aspose.html.dom.svg/svggraphicselement/getbbox/)() | स्ट्रोकिंग, क्लिपिंग, मास्किंग और फिल्टर प्रभावों को छोड़कर, सभी निहित ग्राफिक्स तत्वों की ज्यामिति पर वर्तमान उपयोगकर्ता स्थान (यानी, 'ट्रांसफॉर्म' विशेषता के आवेदन के बाद, यदि कोई हो) में तंग बाउंडिंग बॉक्स लौटाता है)। ध्यान दें कि GetBBox को उस समय वास्तविक बाउंडिंग बॉक्स को वापस करना होगा जब विधि को कॉल किया गया था, भले ही तत्व अभी तक प्रस्तुत नहीं किया गया हो। |
| [GetCTM](../../aspose.html.dom.svg/svggraphicselement/getctm/)() | वर्तमान उपयोगकर्ता इकाइयों से रूपांतरण मैट्रिक्स लौटाता है (यानी, 'ट्रांसफॉर्म' विशेषता के आवेदन के बाद, यदि कोई हो) निकटतम व्यूपोर्ट एलिमेंट के लिए व्यूपोर्ट समन्वय प्रणाली में। |
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname/)(string) | एक लाइव नोडलिस्ट ऑब्जेक्ट लौटाता है जिसमें दस्तावेज़ में सभी तत्व होते हैं जिनमें तर्क में निर्दिष्ट सभी वर्ग होते हैं। http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname/)(string) | दस्तावेज़ क्रम में दिए गए टैग नाम के साथ सभी वंशज तत्वों की एक नोड सूची लौटाता है। |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens/)(string, string) | दस्तावेज़ क्रम में दिए गए स्थानीय नाम और नाम स्थान URI के साथ सभी वंशज तत्वों की एक नोड सूची लौटाता है। |
| [GetEquivalentPath](../../aspose.html.dom.svg/svggeometryelement/getequivalentpath/)() | का एक नया उदाहरण देता है[`SVGPathSegList`](../../aspose.html.dom.svg.paths/svgpathseglist/) जो दर्शाता है[`SVGGeometryElement`](../svggeometryelement/) पथ खंडों के रूप में. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | इस विधि का उपयोग ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए किया जाता हैType . |
| [GetPointAtLength](../../aspose.html.dom.svg/svggeometryelement/getpointatlength/)(float) | यूजर स्पेस में (x, y) कोऑर्डिनेट लौटाता है जो पथ के साथ दूरी इकाइयां हैं, उपयोगकर्ता एजेंट की दूरी-साथ-एक-पथ एल्गोरिथ्म का उपयोग करते हुए। |
| [GetScreenCTM](../../aspose.html.dom.svg/svggraphicselement/getscreenctm/)() | मूल उपयोगकर्ता एजेंट के "पिक्सेल" नोटिस पर वर्तमान उपयोगकर्ता इकाइयों (यानी, 'रूपांतरण' विशेषता के आवेदन के बाद, यदि कोई हो) से रूपांतरण मैट्रिक्स लौटाता है। प्रदर्शन उपकरणों के लिए, आदर्श रूप से यह एक भौतिक स्क्रीन पिक्सेल का प्रतिनिधित्व करता है। अन्य उपकरणों या परिवेशों के लिए जहां भौतिक पिक्सेल आकार ज्ञात नहीं हैं, तो इसके बजाय "पिक्सेल" की CSS2 परिभाषा के समान एक एल्गोरिथम का उपयोग किया जा सकता है। ध्यान दें कि यदि यह तत्व दस्तावेज़ पेड़ में नहीं लगाया गया है तो शून्य वापस आ गया है। इस विधि को अधिक उपयुक्त नाम getClientCTM दिया गया होगा, लेकिन getScreenCTM नाम ऐतिहासिक कारणों से रखा गया है। |
| [GetTotalLength](../../aspose.html.dom.svg/svggeometryelement/gettotallength/)() | वर्तमान उपयोगकर्ता समन्वय प्रणाली में दूरी के रूप में, उपयोगकर्ता एजेंट के डिस्टेंस-अलॉन्ग-ए-पाथ एल्गोरिथम का उपयोग करके पथ की कुल लंबाई के लिए उपयोगकर्ता एजेंट का परिकलित मान लौटाता है. |
| [HasAttribute](../../aspose.html.dom/element/hasattribute/)(string) | सही रिटर्न देता है जब किसी दिए गए नाम के साथ एक विशेषता इस तत्व पर निर्दिष्ट होती है या एक डिफ़ॉल्ट मान होता है, अन्यथा झूठा होता है। |
| [HasAttributeNS](../../aspose.html.dom/element/hasattributens/)(string, string) | सही होता है जब किसी दिए गए स्थानीय नाम और नामस्थान यूआरआई के साथ एक विशेषता इस तत्व पर निर्दिष्ट होती है या इसका डिफ़ॉल्ट मान होता है, अन्यथा झूठा होता है। |
| override [HasAttributes](../../aspose.html.dom/element/hasattributes/)() | रिटर्न करता है कि क्या इस नोड (यदि यह एक तत्व है) में कोई विशेषता है |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | लौटाता है कि क्या इस नोड के कोई बच्चे हैं। |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | मौजूदा चाइल्ड नोड चाइल्ड से पहले नोड डालें। यदि बच्चा शून्य है, तो बच्चों की सूची के अंत में नोड डालें। यदि बच्चा पहले से ही पेड़ में है, तो उसे पहले हटा दिया जाता है। |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | यह विधि जांचती है कि निर्दिष्ट नामस्थान यूआरआई डिफ़ॉल्ट नामस्थान है या नहीं। |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | परीक्षण करता है कि क्या दो नोड समान हैं। यह विधि नोड्स की समानता के लिए परीक्षण करती है, समरूपता के लिए नहीं (अर्थात, क्या दो नोड एक ही वस्तु के संदर्भ हैं) जिसे Node.isSameNode() के साथ परीक्षण किया जा सकता है। सभी नोड जो समान हैं, वे भी बराबर होंगे, हालांकि रिवर्स सत्य नहीं हो सकता है। |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | रिटर्न देता है कि क्या यह नोड दिए गए नोड के समान नोड है। यह विधि यह निर्धारित करने का एक तरीका प्रदान करती है कि कार्यान्वयन द्वारा लौटाए गए दो नोड संदर्भ एक ही वस्तु को संदर्भित करते हैं या नहीं। जब दो नोड संदर्भ एक ही वस्तु के संदर्भ होते हैं, भले ही एक प्रॉक्सी के माध्यम से, संदर्भों को पूरी तरह से एक दूसरे के स्थान पर उपयोग किया जा सकता है, जैसे कि सभी विशेषताओं में समान मान होते हैं और समान DOM विधि को किसी भी संदर्भ पर कॉल करने का हमेशा एक ही प्रभाव होता है। |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | इस नोड से शुरू करते हुए, दिए गए उपसर्ग से जुड़े नामस्थान यूआरआई को देखें। |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | इस नोड से शुरू करते हुए दिए गए नेमस्पेस यूआरआई से जुड़े उपसर्ग को देखें। इस विधि द्वारा डिफ़ॉल्ट नामस्थान घोषणाओं को अनदेखा किया जाता है। इस विधि द्वारा उपयोग किए गए एल्गोरिदम पर विवरण के लिए नामस्थान उपसर्ग लुकअप देखें। |
| [Normalize](../../aspose.html.dom/node/normalize/)() | सभी टेक्स्ट नोड्स को इस नोड के नीचे सब-ट्री की पूरी गहराई में रखता है, विशेषता नोड्स सहित, एक "सामान्य" रूप में जहां केवल संरचना (जैसे, तत्व, टिप्पणियां, प्रसंस्करण निर्देश, सीडीएटीए अनुभाग और इकाई संदर्भ) टेक्स्ट को अलग करती है। नोड्स, यानी, न तो सन्निकट टेक्स्ट नोड्स हैं और न ही खाली टेक्स्ट नोड्स। इसका उपयोग यह सुनिश्चित करने के लिए किया जा सकता है कि किसी दस्तावेज़ का DOM दृश्य वैसा ही है जैसे कि उसे सहेजा गया था और पुनः लोड किया गया था, और जब संचालन (जैसे XPointer [XPointer] लुकअप) जो किसी विशेष दस्तावेज़ ट्री संरचना पर निर्भर करता है, तब उपयोगी होता है इस्तेमाल किया गया। यदि Node.ownerDocument से जुड़ी DOMConfiguration ऑब्जेक्ट का पैरामीटर "सामान्यीकृत-अक्षर" सत्य है, तो यह विधि टेक्स्ट नोड्स के वर्णों को भी पूरी तरह से सामान्य कर देगी। |
| [QuerySelector](../../aspose.html.dom/element/queryselector/)(string) | दस्तावेज़ में पहला तत्व लौटाता है, जो चयनकर्ता से मेल खाता है |
| [QuerySelectorAll](../../aspose.html.dom/element/queryselectorall/)(string) | दस्तावेज़ में सभी तत्वों की एक नोड सूची देता है, जो चयनकर्ता से मेल खाता है |
| [Remove](../../aspose.html.dom/element/remove/)() | इस उदाहरण को निकालता है। |
| [RemoveAttribute](../../aspose.html.dom/element/removeattribute/)(string) | एक विशेषता को नाम से हटाता है। |
| [RemoveAttributeNode](../../aspose.html.dom/element/removeattributenode/)(Attr) | निर्दिष्ट विशेषता नोड को हटाता है। |
| [RemoveAttributeNS](../../aspose.html.dom/element/removeattributens/)(string, string) | स्थानीय नाम और नामस्थान यूआरआई द्वारा एक विशेषता को हटाता है। |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | ओल्डचाइल्ड द्वारा बच्चों की सूची से संकेतित चाइल्ड नोड को हटाता है, और इसे वापस करता है। |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | यह विधि ईवेंट श्रोताओं को ईवेंट लक्ष्य से हटाने की अनुमति देती है। यदि कोई[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) एक से हटा दिया जाता है[`EventTarget`](../../aspose.html.dom/eventtarget/) जबकि यह किसी घटना को संसाधित कर रहा है, यह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं किया जाएगा। इवेंट श्रोताओं को हटाए जाने के बाद कभी नहीं बुलाया जा सकता है। |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | यह विधि ईवेंट श्रोताओं को ईवेंट लक्ष्य से हटाने की अनुमति देती है। यदि कोई[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) एक से हटा दिया जाता है[`EventTarget`](../../aspose.html.dom/eventtarget/) जबकि यह किसी घटना को संसाधित कर रहा है, यह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं किया जाएगा। इवेंट श्रोताओं को हटाए जाने के बाद कभी नहीं बुलाया जा सकता है। |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | यह विधि ईवेंट श्रोताओं को ईवेंट लक्ष्य से हटाने की अनुमति देती है। यदि कोई[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) एक से हटा दिया जाता है[`EventTarget`](../../aspose.html.dom/eventtarget/) जबकि यह किसी घटना को संसाधित कर रहा है, यह वर्तमान क्रियाओं द्वारा ट्रिगर नहीं किया जाएगा। इवेंट श्रोताओं को हटाए जाने के बाद कभी नहीं बुलाया जा सकता है। |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | बच्चों की सूची में चाइल्ड नोड ओल्डचाइल्ड को न्यूचाइल्ड से बदल देता है, और ओल्डचाइल्ड नोड लौटाता है। यदि न्यूचाइल्ड एक डॉक्यूमेंटफ्रैगमेंट ऑब्जेक्ट है, तो ओल्डचाइल्ड को सभी डॉक्यूमेंटफ्रैगमेंट चिल्ड्रेन से बदल दिया जाता है, जो उसी क्रम में डाले जाते हैं। यदि नया बच्चा पहले से ही पेड़ में है, तो इसे पहले हटा दिया जाता है। |
| [SetAttribute](../../aspose.html.dom/element/setattribute/)(string, string) | एक नई विशेषता जोड़ता है। यदि उस नाम के साथ एक विशेषता पहले से ही तत्व में मौजूद है, तो इसका मान मान पैरामीटर के रूप में बदल दिया जाता है |
| [SetAttributeNode](../../aspose.html.dom/element/setattributenode/)(Attr) | एक नया विशेषता नोड जोड़ता है। यदि उस नाम के साथ एक विशेषता (नोडनाम) पहले से ही तत्व में मौजूद है, तो इसे नए से बदल दिया जाता है। |
| [SetAttributeNodeNS](../../aspose.html.dom/element/setattributenodens/)(Attr) | एक नई विशेषता जोड़ता है। यदि उस स्थानीय नाम और उस नामस्थान URI के साथ एक विशेषता पहले से ही तत्व में मौजूद है, तो इसे नए से बदल दिया जाता है। |
| [SetAttributeNS](../../aspose.html.dom/element/setattributens/)(string, string, string) | एक नई विशेषता जोड़ता है। यदि एक ही स्थानीय नाम और नामस्थान URI के साथ एक विशेषता पहले से ही तत्व पर मौजूद है, तो इसके उपसर्ग को योग्यनाम के उपसर्ग भाग के रूप में बदल दिया जाता है, और इसका मान मान पैरामीटर के रूप में बदल जाता है। |
| [SetIdAttribute](../../aspose.html.dom/element/setidattribute/)(string, bool) | यदि पैरामीटर isId सत्य है, तो यह विधि निर्दिष्ट विशेषता को उपयोगकर्ता-निर्धारित आईडी विशेषता घोषित करती है। |
| [SetIdAttributeNode](../../aspose.html.dom/element/setidattributenode/)(Attr, bool) | यदि पैरामीटर isId सत्य है, तो यह विधि निर्दिष्ट विशेषता को उपयोगकर्ता-निर्धारित आईडी विशेषता घोषित करती है। |
| [SetIdAttributeNS](../../aspose.html.dom/element/setidattributens/)(string, string, bool) | यदि पैरामीटर isId सत्य है, तो यह विधि निर्दिष्ट विशेषता को उपयोगकर्ता-निर्धारित आईडी विशेषता घोषित करती है। |
| override [ToString](../../aspose.html.dom/node/tostring/)() | रिटर्न एString जो इस उदाहरण का प्रतिनिधित्व करता है। |

### यह सभी देखें

* class [SVGGeometryElement](../svggeometryelement/)
* नाम स्थान [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg/)
* सभा [Aspose.HTML](../../)


