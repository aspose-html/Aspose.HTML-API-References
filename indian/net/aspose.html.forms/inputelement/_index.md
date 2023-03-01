---
title: Class InputElement
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Forms.InputElement कक्ष. InputElement एक रैपर क प्रतनधत्व करत है ज HTMLInputElement. से संबद्ध है
type: docs
weight: 2980
url: /hi/net/aspose.html.forms/inputelement/
---
## InputElement class

InputElement एक रैपर का प्रतिनिधित्व करता है जो HTMLInputElement. से संबद्ध है

```csharp
public class InputElement : FormElement<HTMLInputElement>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [ElementType](../../aspose.html.forms/formelement/elementtype/) { get; } | तत्व का प्रकार प्राप्त करता है। |
| [HtmlElement](../../aspose.html.forms/formelement-1/htmlelement/) { get; } |  |
| override [Id](../../aspose.html.forms/inputelement/id/) { get; set; } | इनपुट तत्व की आईडी विशेषता का प्रतिनिधित्व करता है। |
| [List](../../aspose.html.forms/inputelement/list/) { get; } | विकल्पों की सूची का प्रतिनिधित्व करता है |
| override [Name](../../aspose.html.forms/inputelement/name/) { get; set; } | इनपुट तत्व के नाम विशेषता का प्रतिनिधित्व करते हैं। |
| [Type](../../aspose.html.forms/inputelement/type/) { get; set; } | प्रपत्र नियंत्रण का प्रकार. |
| override [Value](../../aspose.html.forms/inputelement/value/) { get; set; } | इनपुट तत्व के स्ट्रिंग मान का प्रतिनिधित्व करता है जिसे सीधे 'मान' विशेषता में मैप किया जाता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [AddFile](../../aspose.html.forms/inputelement/addfile/)(string) | यह विधि फाइलों को इसमें जोड़ती है[`Files`](../../aspose.html/htmlinputelement/files/) संग्रह जो अगले वेब अनुरोध के दौरान भेजा जाएगा. |
| [GetCheckboxValue](../../aspose.html.forms/inputelement/getcheckboxvalue/)() | चेकबॉक्स प्रकार . के साथ इनपुट तत्व के लिए चेकनेस स्थिति देता है |
| [GetColorValue](../../aspose.html.forms/inputelement/getcolorvalue/)() | इस विधि का उपयोग रंग के रूप में मान प्राप्त करने के लिए किया जाता है। यह विधि मान्य है यदि केवल इनपुट तत्व का प्रकार "रंग" है |
| [GetDateTimeLocalValue](../../aspose.html.forms/inputelement/getdatetimelocalvalue/)() | इस विधि का उपयोग मूल्य के रूप में प्राप्त करने के लिए किया जाता हैDateTime वस्तु वस्तु। यह विधि मान्य है यदि केवल इनपुट तत्व का प्रकार "डेटाटाइम-लोकल" है |
| [GetDateValue](../../aspose.html.forms/inputelement/getdatevalue/)() | इस विधि का उपयोग मूल्य के रूप में प्राप्त करने के लिए किया जाता हैDateTime वस्तु। यह विधि मान्य है यदि केवल इनपुट तत्व का प्रकार "दिनांक" है |
| [GetEmailValue](../../aspose.html.forms/inputelement/getemailvalue/)() | इस विधि का उपयोग ईमेल स्ट्रिंग ऑब्जेक्ट के रूप में मान प्राप्त करने के लिए किया जाता है। यह विधि मान्य है यदि केवल इनपुट तत्व का प्रकार "ईमेल" है |
| [GetMonthValue](../../aspose.html.forms/inputelement/getmonthvalue/)() | इस विधि का उपयोग मूल्य के रूप में प्राप्त करने के लिए किया जाता हैDateTime वस्तु। यह विधि मान्य है यदि केवल इनपुट तत्व का प्रकार "महीना" है |
| [GetNumberValue](../../aspose.html.forms/inputelement/getnumbervalue/)() | इस विधि का उपयोग संख्या के रूप में मान प्राप्त करने के लिए किया जाता है। यह विधि मान्य है यदि केवल इनपुट तत्व का प्रकार "संख्या" है |
| [GetPasswordValue](../../aspose.html.forms/inputelement/getpasswordvalue/)() | इस विधि का उपयोग पासवर्ड स्ट्रिंग ऑब्जेक्ट के रूप में मान प्राप्त करने के लिए किया जाता है। यह विधि मान्य है यदि केवल इनपुट तत्व का प्रकार "पासवर्ड" है |
| [GetRadioValue](../../aspose.html.forms/inputelement/getradiovalue/)() | रेडियो प्रकार के साथ इनपुट तत्व के लिए जाँच स्थिति देता है। |
| [GetTimeValue](../../aspose.html.forms/inputelement/gettimevalue/)() | इस विधि का उपयोग मूल्य के रूप में प्राप्त करने के लिए किया जाता हैTimeSpan वस्तु। यह विधि मान्य है यदि केवल इनपुट तत्व का प्रकार "समय" है |
| [GetUrlValue](../../aspose.html.forms/inputelement/geturlvalue/)() | इस विधि का उपयोग मान प्राप्त करने के लिए किया जाता है[`Url`](../../aspose.html/url/) वस्तु। यह विधि मान्य है यदि केवल इनपुट तत्व का प्रकार "url" है |
| [GetWeekValue](../../aspose.html.forms/inputelement/getweekvalue/)() | इस विधि का उपयोग सप्ताह स्ट्रिंग के रूप में मान प्राप्त करने के लिए किया जाता है। यह विधि मान्य है यदि केवल इनपुट तत्व का प्रकार "सप्ताह" है |
| [SetCheckboxValue](../../aspose.html.forms/inputelement/setcheckboxvalue/)(bool) | चेकबॉक्स प्रकार के साथ इनपुट तत्व के लिए चेकनेस स्थिति सेट करता है। |
| [SetColorValue](../../aspose.html.forms/inputelement/setcolorvalue/)(Color) | इस विधि का उपयोग रंग को इनपुट तत्व के मान के रूप में सेट करने के लिए किया जाता है। यह विधि मान्य है यदि केवल इनपुट तत्व का प्रकार "रंग" है |
| [SetDateTimeLocalValue](../../aspose.html.forms/inputelement/setdatetimelocalvalue/)(DateTime) | इस विधि का प्रयोग सेट करने के लिए किया जाता हैDateTimeवस्तु इनपुट तत्व के लिए एक मूल्य के रूप में। यह विधि मान्य है यदि केवल इनपुट तत्व का प्रकार "डेटाटाइम-लोकल" है |
| [SetDateValue](../../aspose.html.forms/inputelement/setdatevalue/)(DateTime) | इस विधि का प्रयोग सेट करने के लिए किया जाता हैDateTime वस्तु इनपुट तत्व के लिए एक मूल्य के रूप में। यह विधि मान्य है यदि केवल इनपुट तत्व का प्रकार "तारीख" है |
| [SetEmailValue](../../aspose.html.forms/inputelement/setemailvalue/)(string) | इस विधि का उपयोग ईमेल स्ट्रिंग को इनपुट तत्व के मान के रूप में सेट करने के लिए किया जाता है। यह विधि मान्य है यदि केवल इनपुट तत्व का प्रकार "ईमेल" है |
| [SetMonthValue](../../aspose.html.forms/inputelement/setmonthvalue/)(DateTime) | इस विधि का प्रयोग सेट करने के लिए किया जाता हैDateTimeवस्तु इनपुट तत्व के लिए एक मूल्य के रूप में। यह विधि मान्य है यदि केवल इनपुट तत्व का प्रकार "माह" है |
| [SetNumberValue](../../aspose.html.forms/inputelement/setnumbervalue/)(float) | इस विधि का उपयोग संख्या को इनपुट तत्व के मान के रूप में सेट करने के लिए किया जाता है। यह विधि मान्य है यदि केवल इनपुट तत्व का प्रकार "संख्या" है |
| [SetPasswordValue](../../aspose.html.forms/inputelement/setpasswordvalue/)(string) | इस विधि का उपयोग पासवर्ड स्ट्रिंग को इनपुट तत्व के मान के रूप में सेट करने के लिए किया जाता है। यह विधि मान्य है यदि केवल इनपुट तत्व का प्रकार "पासवर्ड" है |
| [SetRadioValue](../../aspose.html.forms/inputelement/setradiovalue/)(bool) | रेडियो प्रकार के साथ इनपुट तत्व के लिए जाँच स्थिति सेट करता है। |
| [SetTimeValue](../../aspose.html.forms/inputelement/settimevalue/)(TimeSpan) | इस विधि का प्रयोग सेट करने के लिए किया जाता हैTimeSpan वस्तु इनपुट तत्व के लिए एक मूल्य के रूप में। यह विधि मान्य है यदि केवल इनपुट तत्व का प्रकार "समय" है |
| [SetUrlValue](../../aspose.html.forms/inputelement/seturlvalue/)(Url) | इस विधि का प्रयोग सेट करने के लिए किया जाता है[`Url`](../../aspose.html/url/) वस्तु इनपुट तत्व के लिए एक मूल्य के रूप में। यह विधि मान्य है यदि केवल इनपुट तत्व का प्रकार "url" है |
| [SetWeekValue](../../aspose.html.forms/inputelement/setweekvalue/)(string) | इस विधि का उपयोग 'सप्ताह' स्ट्रिंग को इनपुट तत्व के मान के रूप में सेट करने के लिए किया जाता है। यह विधि मान्य है यदि केवल इनपुट तत्व का प्रकार "सप्ताह" है |

### यह सभी देखें

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLInputElement](../../aspose.html/htmlinputelement/)
* नाम स्थान [Aspose.Html.Forms](../../aspose.html.forms/)
* सभा [Aspose.HTML](../../)


