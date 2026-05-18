---
title: "InputElement वर्ग"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.forms.InputElement वर्ग। InputElement एक रैपर का प्रतिनिधित्व करता है जो HTMLInputElement से जुड़ा होता है।"
type: docs

url: /hi/java/com.aspose.html.forms/inputelement/
---
## InputElement class

InputElement एक रैपर को दर्शाता है जो HTMLInputElement से जुड़ा होता है।

```java
public class InputElement : FormElement<HTMLInputElement>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getElementType](../../com.aspose.html.forms/formelement/elementtype/) एलेमेंट का प्रकार प्राप्त करता है। |
| [getHtmlElement](../../com.aspose.html.forms/formelement-1/htmlelement/) |
| [id](../../com.aspose.html.forms/inputelement/id/) { get; set; } | इनपुट तत्व के Id विशेषता का प्रतिनिधित्व करता है। |
| [getList](../../com.aspose.html.forms/inputelement/list/) विकल्पों की सूची का प्रतिनिधित्व करता है |
| [name](../../com.aspose.html.forms/inputelement/name/) { get; set; } | इनपुट तत्व के name विशेषता का प्रतिनिधित्व करता है। |
[getType]
[setType] Type of the form control. |
| [value](../../com.aspose.html.forms/inputelement/value/) { get; set; } | इनपुट तत्व के स्ट्रिंग मान का प्रतिनिधित्व करता है जो सीधे 'value' एट्रिब्यूट से मैप किया गया है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addFile](../../com.aspose.html.forms/inputelement/addfile/)(String) | यह मेथड फ़ाइलों को [`Files`](../../com.aspose.html/htmlinputelement/files/) संग्रह में जोड़ता है जो अगले वेब अनुरोध के दौरान भेजी जाएँगी। |
| [getCheckboxValue](../../com.aspose.html.forms/inputelement/getcheckboxvalue/)() | Checkbox प्रकार वाले इनपुट तत्व की चयनित स्थिति लौटाता है। |
| [getColorValue](../../com.aspose.html.forms/inputelement/getcolorvalue/)() | यह मेथड मान को रंग के रूप में प्राप्त करने के लिए उपयोग किया जाता है। यह मेथड तभी मान्य है जब इनपुट तत्व का प्रकार केवल "color" हो। |
| [getDateTimeLocalValue](../../com.aspose.html.forms/inputelement/getdatetimelocalvalue/)() | यह मेथड मान को DateTime ऑब्जेक्ट के रूप में प्राप्त करने के लिए उपयोग किया जाता है। यह मेथड तभी मान्य है जब इनपुट तत्व का प्रकार केवल "datetime-local" हो। |
| [getDateValue](../../com.aspose.html.forms/inputelement/getdatevalue/)() | यह मेथड मान को DateTime ऑब्जेक्ट के रूप में प्राप्त करने के लिए उपयोग किया जाता है। यह मेथड तभी मान्य है जब इनपुट तत्व का प्रकार केवल "date" हो। |
| [getEmailValue](../../com.aspose.html.forms/inputelement/getemailvalue/)() | यह मेथड मान को ईमेल स्ट्रिंग ऑब्जेक्ट के रूप में प्राप्त करने के लिए उपयोग किया जाता है। यह मेथड तभी मान्य है जब इनपुट तत्व का प्रकार केवल "email" हो। |
| [getMonthValue](../../com.aspose.html.forms/inputelement/getmonthvalue/)() | यह मेथड मान को DateTime ऑब्जेक्ट के रूप में प्राप्त करने के लिए उपयोग किया जाता है। यह मेथड तभी मान्य है जब इनपुट तत्व का प्रकार केवल "month" हो। |
| [getNumberValue](../../com.aspose.html.forms/inputelement/getnumbervalue/)() | यह मेथड मान को संख्या के रूप में प्राप्त करने के लिए उपयोग किया जाता है। यह मेथड तभी मान्य है जब इनपुट तत्व का प्रकार केवल "number" हो। |
| [getPasswordValue](../../com.aspose.html.forms/inputelement/getpasswordvalue/)() | यह मेथड मान को पासवर्ड स्ट्रिंग ऑब्जेक्ट के रूप में प्राप्त करने के लिए उपयोग किया जाता है। यह मेथड तभी मान्य है जब इनपुट तत्व का प्रकार केवल "password" हो। |
| [getRadioValue](../../com.aspose.html.forms/inputelement/getradiovalue/)() | Radio प्रकार वाले इनपुट तत्व की चयनित स्थिति लौटाता है। |
| [getTimeValue](../../com.aspose.html.forms/inputelement/gettimevalue/)() | यह मेथड मान को TimeSpan ऑब्जेक्ट के रूप में प्राप्त करने के लिए उपयोग किया जाता है। यह मेथड तभी मान्य है जब इनपुट तत्व का प्रकार केवल "time" हो। |
| [getUrlValue](../../com.aspose.html.forms/inputelement/geturlvalue/)() | यह मेथड मान को [`Url`](../../com.aspose.html/url/) ऑब्जेक्ट के रूप में प्राप्त करने के लिए उपयोग किया जाता है। यह मेथड तभी मान्य है जब इनपुट तत्व का प्रकार केवल "url" हो। |
| [getWeekValue](../../com.aspose.html.forms/inputelement/getweekvalue/)() | यह मेथड मान को सप्ताह स्ट्रिंग के रूप में प्राप्त करने के लिए उपयोग किया जाता है। यह मेथड तभी मान्य है जब इनपुट तत्व का प्रकार केवल "week" हो। |
| [setCheckboxValue](../../com.aspose.html.forms/inputelement/setcheckboxvalue/)(bool) | Checkbox प्रकार वाले इनपुट तत्व की चयनित स्थिति सेट करता है। |
| [setColorValue](../../com.aspose.html.forms/inputelement/setcolorvalue/)(Color) | यह मेथड इनपुट तत्व के लिए रंग को मान के रूप में सेट करने के लिए उपयोग किया जाता है। यह मेथड तभी मान्य है जब इनपुट तत्व का प्रकार "color" हो। |
| [setDateTimeLocalValue](../../com.aspose.html.forms/inputelement/setdatetimelocalvalue/)(DateTime) | यह मेथड इनपुट तत्व के लिए DateTime ऑब्जेक्ट को मान के रूप में सेट करने के लिए उपयोग किया जाता है। यह मेथड तभी मान्य है जब इनपुट तत्व का प्रकार "datetime-local" हो। |
| [setDateValue](../../com.aspose.html.forms/inputelement/setdatevalue/)(DateTime) | यह मेथड इनपुट तत्व के लिए DateTime ऑब्जेक्ट को मान के रूप में सेट करने के लिए उपयोग किया जाता है। यह मेथड तभी मान्य है जब इनपुट तत्व का प्रकार "date" हो। |
| [setEmailValue](../../com.aspose.html.forms/inputelement/setemailvalue/)(String) | यह मेथड इनपुट तत्व के लिए ईमेल स्ट्रिंग को मान के रूप में सेट करने के लिए उपयोग किया जाता है। यह मेथड तभी मान्य है जब इनपुट तत्व का प्रकार "email" हो। |
| [setMonthValue](../../com.aspose.html.forms/inputelement/setmonthvalue/)(DateTime) | यह मेथड इनपुट तत्व के लिए DateTime ऑब्जेक्ट को मान के रूप में सेट करने के लिए उपयोग किया जाता है। यह मेथड तभी मान्य है जब इनपुट तत्व का प्रकार "month" हो। |
| [setNumberValue](../../com.aspose.html.forms/inputelement/setnumbervalue/)(float) | यह मेथड इनपुट तत्व के लिए संख्या को मान के रूप में सेट करने के लिए उपयोग किया जाता है। यह मेथड तभी मान्य है जब इनपुट तत्व का प्रकार "number" हो। |
| [setPasswordValue](../../com.aspose.html.forms/inputelement/setpasswordvalue/)(String) | यह मेथड इनपुट तत्व के लिए पासवर्ड स्ट्रिंग को मान के रूप में सेट करने के लिए उपयोग किया जाता है। यह मेथड तभी मान्य है जब इनपुट तत्व का प्रकार "password" हो। |
| [setRadioValue](../../com.aspose.html.forms/inputelement/setradiovalue/)(bool) | Radio प्रकार वाले इनपुट तत्व की चयनित स्थिति सेट करता है। |
| [setTimeValue](../../com.aspose.html.forms/inputelement/settimevalue/)(TimeSpan) | यह मेथड इनपुट तत्व के लिए TimeSpan ऑब्जेक्ट को मान के रूप में सेट करने के लिए उपयोग किया जाता है। यह मेथड तभी मान्य है जब इनपुट तत्व का प्रकार "time" हो। |
| [setUrlValue](../../com.aspose.html.forms/inputelement/seturlvalue/)(Url) | यह विधि इनपुट तत्व के लिए मान के रूप में [`Url`](../../com.aspose.html/url/) ऑब्जेक्ट सेट करने के लिए उपयोग की जाती है। यह विधि तभी मान्य है जब इनपुट तत्व का प्रकार केवल "url" हो। |
| [setWeekValue](../../com.aspose.html.forms/inputelement/setweekvalue/)(String) | यह विधि इनपुट तत्व के लिए मान के रूप में 'week' स्ट्रिंग सेट करने के लिए उपयोग की जाती है। यह विधि तभी मान्य है जब इनपुट तत्व का प्रकार केवल "week" हो। |

### संबंधित देखें

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLInputElement](../../com.aspose.html/htmlinputelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
