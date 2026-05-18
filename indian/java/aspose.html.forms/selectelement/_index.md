---
title: "SelectElement क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.forms.SelectElement क्लास। SelectElement एक रैपर का प्रतिनिधित्व करता है जो HTMLSelectElement से जुड़ा होता है।"
type: docs

url: /hi/java/com.aspose.html.forms/selectelement/
---
## SelectElement class

SelectElement एक रैपर को दर्शाता है जो HTMLSelectElement से जुड़ा होता है।

```java
public class SelectElement : FormElement<HTMLSelectElement>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [getElementType](../../com.aspose.html.forms/formelement/elementtype/) एलेमेंट का प्रकार प्राप्त करता है। |
| [getHtmlElement](../../com.aspose.html.forms/formelement-1/htmlelement/) |
| [id](../../com.aspose.html.forms/selectelement/id/) { get; set; } | इनपुट तत्व के Id विशेषता का प्रतिनिधित्व करता है। |
[getMultiple]
[setMultiple] If true, multiple `OPTION` elements may be selected in this `SELECT`. See the multiple attribute definition in HTML 4.01. |
| [name](../../com.aspose.html.forms/selectelement/name/) { get; set; } | इनपुट तत्व के name विशेषता का प्रतिनिधित्व करता है। |
| [getOptions](../../com.aspose.html.forms/selectelement/options/) विकल्पों की सूची लौटाता है |
| [getSelectedOptions](../../com.aspose.html.forms/selectelement/selectedoptions/) चयनित विकल्पों की सूची लौटाता है |
| [getType](../../com.aspose.html.forms/selectelement/type/) इस फ़ॉर्म नियंत्रण का प्रकार। जब multiple विशेषता `true` हो तो यह स्ट्रिंग "select-multiple" है और जब `false` हो तो स्ट्रिंग "select-one" है। |
| [value](../../com.aspose.html.forms/selectelement/value/) { get; set; } | प्राप्त करने पर, यदि कोई हो तो विकल्पों की सूची में वृक्ष क्रम में पहले विकल्प तत्व का मान लौटाना चाहिए, जिसकी चयनित स्थिति `true` सेट हो। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems)(params int[]) | यह विधि उनके अनुक्रमणिकाओं द्वारा कई विकल्पों का चयन करने की अनुमति देती है। |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems_1)(params String[]) | यह विधि उनके मानों द्वारा कई विकल्पों का चयन करने की अनुमति देती है। |

### संबंधित देखें

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLSelectElement](../../com.aspose.html/htmlselectelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
