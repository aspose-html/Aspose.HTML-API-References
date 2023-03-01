---
title: Class SVGSVGElement
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Dom.Svg.SVGSVGElement कक्ष. एक मुख्य इंटरफ़ेस परभष SVGSVGElement इंटरफ़ेस है ज इंटरफ़ेस है ज svg तत्व से संबंधत है इस इंटरफ़ेस में वभन्न ववध समन्य रूप से उपयग क जने वल उपयगत वधयँ हैं जैसे क मैट्रक्स संचलन और दृश्य रेंडरंग डवइस पर रेड्र के समय क नयंत्रत करने क क्षमत
type: docs
weight: 2260
url: /hi/net/aspose.html.dom.svg/svgsvgelement/
---
## SVGSVGElement class

एक मुख्य इंटरफ़ेस परिभाषा SVGSVGElement इंटरफ़ेस है, जो इंटरफ़ेस है जो 'svg' तत्व से संबंधित है। इस इंटरफ़ेस में विभिन्न विविध सामान्य रूप से उपयोग की जाने वाली उपयोगिता विधियाँ हैं, जैसे कि मैट्रिक्स संचालन और दृश्य रेंडरिंग डिवाइस पर रेड्रा के समय को नियंत्रित करने की क्षमता।

```csharp
public class SVGSVGElement : SVGGraphicsElement, IDocumentEvent, ISVGFitToViewBox, ISVGZoomAndPan
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
| [CurrentScale](../../aspose.html.dom.svg/svgsvgelement/currentscale/) { get; set; } | सबसे बाहरी svg तत्व पर, यह विशेषता उपयोगकर्ता के आवर्धन और पैनिंग संचालन को ध्यान में रखते हुए प्रारंभिक दृश्य के सापेक्ष वर्तमान स्केल कारक को इंगित करती है, जैसा कि आवर्धन और पैनिंग के तहत वर्णित है। DOM विशेषताएँ करंटस्केल और करंटट्रांसलेट 2x3 मैट्रिक्स [abcdef] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y] के बराबर हैं। यदि "आवर्धन" सक्षम है (यानी, ज़ूमएंडपैन = "बढ़ाना"), तो प्रभाव ऐसा होता है जैसे एसवीजी दस्तावेज़ खंड पर बाहरीतम स्तर पर एक अतिरिक्त परिवर्तन रखा गया हो (यानी, सबसे बाहरी एसवीजी तत्व के बाहर)। जब एक्सेस किया गया एक 'svg' तत्व जो सबसे बाहरी svg तत्व नहीं है, यह अपरिभाषित है कि इस विशेषता का क्या व्यवहार है। |
| [CurrentTranslate](../../aspose.html.dom.svg/svgsvgelement/currenttranslate/) { get; } | सबसे बाहरी svg तत्व पर, संबंधित अनुवाद कारक जो उपयोगकर्ता "आवर्धन" को ध्यान में रखता है। जब किसी 'svg' तत्व पर पहुँचा जाता है जो सबसे बाहरी svg तत्व नहीं है, तो यह अपरिभाषित है कि इस विशेषता का क्या व्यवहार है। |
| [FarthestViewportElement](../../aspose.html.dom.svg/svggraphicselement/farthestviewportelement/) { get; } | सबसे दूर का पूर्वज 'svg' तत्व। शून्य अगर वर्तमान तत्व सबसे बाहरी svg तत्व है. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | इस नोड का पहला चाइल्ड। यदि ऐसा कोई नोड नहीं है, तो यह शून्य वापस आ जाता है। |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild/) { get; } | इस तत्व का पहला बाल तत्व नोड लौटाता है। शून्य अगर इस तत्व में कोई बाल तत्व नहीं है। |
| [Height](../../aspose.html.dom.svg/svgsvgelement/height/) { get; } | दिए गए 'svg' तत्व पर विशेषता 'ऊंचाई' के अनुरूप है। |
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
| override [Prefix](../../aspose.html.dom/element/prefix/) { get; } | इस नोड का नामस्थान उपसर्ग, या अनिर्दिष्ट होने पर अशक्त। जब इसे शून्य के रूप में परिभाषित किया जाता है, तो इसे सेट करने से कोई प्रभाव नहीं पड़ता |
| [PreserveAspectRatio](../../aspose.html.dom.svg/svgsvgelement/preserveaspectratio/) { get; } | दिए गए तत्व पर विशेषता 'preserveAspectRatio' के अनुरूप है। |
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
| [ViewBox](../../aspose.html.dom.svg/svgsvgelement/viewbox/) { get; } | दिए गए तत्व पर विशेषता 'व्यूबॉक्स' के अनुरूप है। |
| [ViewportElement](../../aspose.html.dom.svg/svgelement/viewportelement/) { get; } | वह तत्व जिसने वर्तमान व्यूपोर्ट स्थापित किया। अक्सर, निकटतम पूर्वज 'svg' तत्व। नल अगर दिया गया तत्व सबसे बाहरी svg तत्व है। |
| [Width](../../aspose.html.dom.svg/svgsvgelement/width/) { get; } | दिए गए 'svg' तत्व पर विशेषता 'चौड़ाई' के अनुरूप है। |
| [X](../../aspose.html.dom.svg/svgsvgelement/x/) { get; } | दिए गए 'svg' तत्व पर विशेषता 'x' के अनुरूप है। |
| [Y](../../aspose.html.dom.svg/svgsvgelement/y/) { get; } | दिए गए 'svg' तत्व पर विशेषता 'y' के अनुरूप है। |
| [ZoomAndPan](../../aspose.html.dom.svg/svgsvgelement/zoomandpan/) { get; set; } | दिए गए तत्व पर विशेषता 'zoomAndPan' के अनुरूप है। मान इस इंटरफ़ेस पर परिभाषित SVG_ZOOMANDPAN_* स्थिरांकों में से एक होना चाहिए। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | यह विधि ईवेंट लक्ष्य पर ईवेंट श्रोताओं के पंजीकरण की अनुमति देती है। |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | यह विधि ईवेंट लक्ष्य पर ईवेंट श्रोताओं के पंजीकरण की अनुमति देती है। |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | यह विधि ईवेंट लक्ष्य पर ईवेंट श्रोताओं के पंजीकरण की अनुमति देती है। |
| [AnimationsPaused](../../aspose.html.dom.svg/svgsvgelement/animationspaused/)() | सही रिटर्न देता है यदि यह एसवीजी दस्तावेज़ खंड रुकी हुई स्थिति में है। |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | इस नोड के चिल्ड्रन की सूची के अंत में नोड न्यूचाइल्ड जोड़ता है। यदि नया बच्चा पहले से ही पेड़ में है, तो इसे पहले हटा दिया जाता है। |
| [AttachShadow](../../aspose.html.dom/element/attachshadow/)(ShadowRootMode) | छाया जड़ बनाता है और इसे वर्तमान तत्व से जोड़ता है। |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | इस नोड का एक डुप्लिकेट लौटाता है, अर्थात, नोड्स के लिए एक सामान्य कॉपी कंस्ट्रक्टर के रूप में कार्य करता है। डुप्लिकेट नोड का कोई पैरेंट नहीं है (parentNode खाली है) और कोई उपयोगकर्ता डेटा नहीं है। |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | इस नोड का एक डुप्लिकेट लौटाता है, अर्थात, नोड्स के लिए एक सामान्य कॉपी कंस्ट्रक्टर के रूप में कार्य करता है। डुप्लिकेट नोड का कोई पैरेंट नहीं है (parentNode खाली है) और कोई उपयोगकर्ता डेटा नहीं है। |
| [CreateEvent](../../aspose.html.dom.svg/svgsvgelement/createevent/)(string) | एक बनाता है[`Event`](../../aspose.html.dom.events/event/) कार्यान्वयन द्वारा समर्थित एक प्रकार का। |
| [CreateSVGAngle](../../aspose.html.dom.svg/svgsvgelement/createsvgangle/)() | किसी दस्तावेज़ ट्री के बाहर एक SVGAngle ऑब्जेक्ट बनाता है। ऑब्जेक्ट को 0 डिग्री (यूनिट रहित) के मान से प्रारंभ किया गया है। |
| [CreateSVGLength](../../aspose.html.dom.svg/svgsvgelement/createsvglength/)() | किसी दस्तावेज़ ट्री के बाहर एक SVGLength ऑब्जेक्ट बनाता है। ऑब्जेक्ट को 0 उपयोगकर्ता इकाइयों के मान से प्रारंभ किया गया है। |
| [CreateSVGMatrix](../../aspose.html.dom.svg/svgsvgelement/createsvgmatrix/)() | किसी दस्तावेज़ ट्री के बाहर एक SVGMatrix ऑब्जेक्ट बनाता है। ऑब्जेक्ट को आइडेंटिटी मैट्रिक्स से इनिशियलाइज़ किया गया है। |
| [CreateSVGNumber](../../aspose.html.dom.svg/svgsvgelement/createsvgnumber/)() | किसी दस्तावेज़ ट्री के बाहर एक SVGNumber ऑब्जेक्ट बनाता है। ऑब्जेक्ट को शून्य के मान से प्रारंभ किया गया है। |
| [CreateSVGPoint](../../aspose.html.dom.svg/svgsvgelement/createsvgpoint/)() | किसी दस्तावेज़ ट्री के बाहर एक SVGPoint ऑब्जेक्ट बनाता है। ऑब्जेक्ट को उपयोगकर्ता समन्वय प्रणाली में बिंदु (0,0) पर प्रारंभ किया गया है। |
| [CreateSVGRect](../../aspose.html.dom.svg/svgsvgelement/createsvgrect/)() | किसी दस्तावेज़ ट्री के बाहर एक SVGRect ऑब्जेक्ट बनाता है। ऑब्जेक्ट को इनिशियलाइज़ किया जाता है जैसे कि सभी मान 0 उपयोगकर्ता इकाइयों पर सेट होते हैं। |
| [CreateSVGTransform](../../aspose.html.dom.svg/svgsvgelement/createsvgtransform/)() | किसी दस्तावेज़ ट्री के बाहर एक SVGTransform ऑब्जेक्ट बनाता है। ऑब्जेक्ट को पहचान मैट्रिक्स ट्रांसफ़ॉर्म (SVG_TRANSFORM_MATRIX) के लिए प्रारंभ किया गया है। |
| [CreateSVGTransformFromMatrix](../../aspose.html.dom.svg/svgsvgelement/createsvgtransformfrommatrix/)(SVGMatrix) | किसी दस्तावेज़ ट्री के बाहर एक SVGTransform ऑब्जेक्ट बनाता है। ऑब्जेक्ट को दिए गए मैट्रिक्स ट्रांसफ़ॉर्म (यानी, SVG_TRANSFORM_MATRIX) के लिए आरंभीकृत किया गया है। पैरामीटर मैट्रिक्स से मानों की प्रतिलिपि बनाई जाती है, मैट्रिक्स पैरामीटर को SVGTransform::matrix. के रूप में नहीं अपनाया जाता है |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | यह विधि इवेंट को कार्यान्वयन इवेंट मॉडल में भेजने की अनुमति देती है. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | अप्रबंधित संसाधनों को मुक्त करने, जारी करने या रीसेट करने से संबंधित एप्लिकेशन-परिभाषित कार्य करता है। |
| [GetAttribute](../../aspose.html.dom/element/getattribute/)(string) | नाम से एक विशेषता मान प्राप्त करता है। |
| [GetAttributeNode](../../aspose.html.dom/element/getattributenode/)(string) | नाम से एक विशेषता नोड पुनर्प्राप्त करता है। |
| [GetAttributeNodeNS](../../aspose.html.dom/element/getattributenodens/)(string, string) | स्थानीय नाम और नाम स्थान URI. द्वारा एक Attr नोड प्राप्त करता है |
| [GetAttributeNS](../../aspose.html.dom/element/getattributens/)(string, string) | स्थानीय नाम और नाम स्थान URI. द्वारा एक विशेषता मान प्राप्त करता है |
| [GetBBox](../../aspose.html.dom.svg/svggraphicselement/getbbox/)() | स्ट्रोकिंग, क्लिपिंग, मास्किंग और फिल्टर प्रभावों को छोड़कर, सभी निहित ग्राफिक्स तत्वों की ज्यामिति पर वर्तमान उपयोगकर्ता स्थान (यानी, 'ट्रांसफॉर्म' विशेषता के आवेदन के बाद, यदि कोई हो) में तंग बाउंडिंग बॉक्स लौटाता है)। ध्यान दें कि GetBBox को उस समय वास्तविक बाउंडिंग बॉक्स को वापस करना होगा जब विधि को कॉल किया गया था, भले ही तत्व अभी तक प्रस्तुत नहीं किया गया हो। |
| [GetCTM](../../aspose.html.dom.svg/svggraphicselement/getctm/)() | वर्तमान उपयोगकर्ता इकाइयों से रूपांतरण मैट्रिक्स लौटाता है (यानी, 'ट्रांसफॉर्म' विशेषता के आवेदन के बाद, यदि कोई हो) निकटतम व्यूपोर्ट एलिमेंट के लिए व्यूपोर्ट समन्वय प्रणाली में। |
| [GetCurrentTime](../../aspose.html.dom.svg/svgsvgelement/getcurrenttime/)() | वर्तमान एसवीजी दस्तावेज़ खंड के प्रारंभ समय के सापेक्ष वर्तमान समय सेकंड में देता है। यदि दस्तावेज़ समयरेखा शुरू होने से पहले getCurrentTime को कॉल किया जाता है (उदाहरण के लिए, दस्तावेज़ के SVGLoad ईवेंट भेजे जाने से पहले 'स्क्रिप्ट' तत्व में चलने वाली स्क्रिप्ट द्वारा), तो 0 वापस आ जाता है। |
| [GetElementById](../../aspose.html.dom.svg/svgsvgelement/getelementbyid/)(string) | इस एसवीजी दस्तावेज़ खंड को खोजता है (यानी, खोज दस्तावेज़ ट्री के सबसेट तक सीमित है) एक तत्व के लिए जिसकी आईडी एलीमेंटआईडी द्वारा दी गई है। यदि कोई तत्व पाया जाता है, तो वह तत्व वापस आ जाता है। यदि ऐसा कोई तत्व मौजूद नहीं है, तो शून्य वापस आ जाता है। यदि एक से अधिक तत्वों में यह आईडी है तो व्यवहार परिभाषित नहीं है। |
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname/)(string) | एक लाइव नोडलिस्ट ऑब्जेक्ट लौटाता है जिसमें दस्तावेज़ में सभी तत्व होते हैं जिनमें तर्क में निर्दिष्ट सभी वर्ग होते हैं। http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname/)(string) | दस्तावेज़ क्रम में दिए गए टैग नाम के साथ सभी वंशज तत्वों की एक नोड सूची लौटाता है। |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens/)(string, string) | दस्तावेज़ क्रम में दिए गए स्थानीय नाम और नाम स्थान URI के साथ सभी वंशज तत्वों की एक नोड सूची लौटाता है। |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | इस विधि का उपयोग ECMAScript ऑब्जेक्ट को पुनः प्राप्त करने के लिए किया जाता हैType . |
| [GetScreenCTM](../../aspose.html.dom.svg/svggraphicselement/getscreenctm/)() | मूल उपयोगकर्ता एजेंट के "पिक्सेल" नोटिस पर वर्तमान उपयोगकर्ता इकाइयों (यानी, 'रूपांतरण' विशेषता के आवेदन के बाद, यदि कोई हो) से रूपांतरण मैट्रिक्स लौटाता है। प्रदर्शन उपकरणों के लिए, आदर्श रूप से यह एक भौतिक स्क्रीन पिक्सेल का प्रतिनिधित्व करता है। अन्य उपकरणों या परिवेशों के लिए जहां भौतिक पिक्सेल आकार ज्ञात नहीं हैं, तो इसके बजाय "पिक्सेल" की CSS2 परिभाषा के समान एक एल्गोरिथम का उपयोग किया जा सकता है। ध्यान दें कि यदि यह तत्व दस्तावेज़ पेड़ में नहीं लगाया गया है तो शून्य वापस आ गया है। इस विधि को अधिक उपयुक्त नाम getClientCTM दिया गया होगा, लेकिन getScreenCTM नाम ऐतिहासिक कारणों से रखा गया है। |
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
| [PauseAnimations](../../aspose.html.dom.svg/svgsvgelement/pauseanimations/)() | वर्तमान में चल रहे सभी एनिमेशन को निलंबित करता है (यानी, रोकता है) जो इस 'एसवीजी' तत्व के अनुरूप एसवीजी दस्तावेज़ खंड के भीतर परिभाषित हैं, इस दस्तावेज़ खंड से संबंधित एनीमेशन घड़ी को तब तक स्थिर रहने का कारण बनता है जब तक कि यह अप्रकाशित न हो। |
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
| [SetCurrentTime](../../aspose.html.dom.svg/svgsvgelement/setcurrenttime/)(float) | इस एसवीजी दस्तावेज़ खंड के लिए घड़ी समायोजित करता है, एक नया वर्तमान समय स्थापित करता है। यदि दस्तावेज़ समयरेखा शुरू होने से पहले setCurrentTime को कॉल किया जाता है (उदाहरण के लिए, दस्तावेज़ के SVGLoad ईवेंट को भेजने से पहले 'स्क्रिप्ट' तत्व में चलने वाली स्क्रिप्ट द्वारा), तो विधि के अंतिम आह्वान में सेकंड का मान वह समय देता है जब दस्तावेज़ एक बार दस्तावेज़ की समयावधि शुरू हो जाने के बाद इसकी तलाश की जाएगी. |
| [SetIdAttribute](../../aspose.html.dom/element/setidattribute/)(string, bool) | यदि पैरामीटर isId सत्य है, तो यह विधि निर्दिष्ट विशेषता को उपयोगकर्ता-निर्धारित आईडी विशेषता घोषित करती है। |
| [SetIdAttributeNode](../../aspose.html.dom/element/setidattributenode/)(Attr, bool) | यदि पैरामीटर isId सत्य है, तो यह विधि निर्दिष्ट विशेषता को उपयोगकर्ता-निर्धारित आईडी विशेषता घोषित करती है। |
| [SetIdAttributeNS](../../aspose.html.dom/element/setidattributens/)(string, string, bool) | यदि पैरामीटर isId सत्य है, तो यह विधि निर्दिष्ट विशेषता को उपयोगकर्ता-निर्धारित आईडी विशेषता घोषित करती है। |
| override [ToString](../../aspose.html.dom/node/tostring/)() | रिटर्न एString जो इस उदाहरण का प्रतिनिधित्व करता है। |
| [UnpauseAnimations](../../aspose.html.dom.svg/svgsvgelement/unpauseanimations/)() | वर्तमान में चल रहे एनिमेशन को अनसस्पेंड करता है (यानी, अनपॉज़ करता है) जो एसवीजी दस्तावेज़ खंड के भीतर परिभाषित हैं, जिससे एनीमेशन घड़ी उस समय से जारी रहती है जब इसे निलंबित किया गया था। |

### यह सभी देखें

* class [SVGGraphicsElement](../svggraphicselement/)
* interface [ISVGFitToViewBox](../isvgfittoviewbox/)
* interface [IDocumentEvent](../../aspose.html.dom.events/idocumentevent/)
* interface [IViewCSS](../../aspose.html.dom.css/iviewcss/)
* interface [IDocumentCSS](../../aspose.html.dom.css/idocumentcss/)
* interface [ISVGZoomAndPan](../isvgzoomandpan/)
* नाम स्थान [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg/)
* सभा [Aspose.HTML](../../)


