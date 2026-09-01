---
title: "FormEditor क्लास"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.forms.FormEditor क्लास। यह क्लास HTMLFormElement के ऊपर संपादक का प्रतिनिधित्व करती है जो .net डेवलपर्स के लिए HTML फ़ॉर्म को संपादित करने का आसान तरीका बनाती है।"
type: docs

url: /hi/java/com.aspose.html.forms/formeditor/
---
## FormEditor class

यह क्लास [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) के ऊपर संपादक का प्रतिनिधित्व करती है जो .net डेवलपर्स के लिए HTML फ़ॉर्म को संपादित करने का आसान तरीका बनाती है।

```java
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
| [getCount](../../com.aspose.html.forms/formeditor/count/) फ़ॉर्म में फ़ॉर्म नियंत्रणों की संख्या। |
| [getForm](../../com.aspose.html.forms/formeditor/form/) वर्तमान `FormEditor` उदाहरण से जुड़ा मूल [`HTMLFormElement`](../../com.aspose.html/htmlformelement/)। |
| [getItem](../../com.aspose.html.forms/formeditor/item/) निर्दिष्ट इंडेक्स द्वारा तत्व लौटाता है। (2 इंडेक्सर) |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | `FormEditor` को नई रूप में बनाता है जो [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) पर आधारित है। |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | `FormEditor` को नई रूप में बनाता है जो इंडेक्स द्वारा [`Forms`](../../com.aspose.html/htmldocument/forms/) संग्रह से चुने गए [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) पर आधारित है। |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, String) | `FormEditor` को नई रूप में बनाता है जो दस्तावेज़ से id द्वारा चुने गए [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) पर आधारित है। |
| static [CreateNew](../../com.aspose.html.forms/formeditor/createnew/)(HTMLDocument) | एक नया [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) बनाता है और उसे `FormEditor` से जोड़ता है। [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) दस्तावेज़ से अलग स्थिति में बनाया जाता है; इसे दस्तावेज़ से जोड़ने के लिए, कृपया उचित स्थान चुनें और [`AppendChild`](../../com.aspose.html.dom/node/appendchild/) विधि का उपयोग करें। |
| [Add&lt;T&gt;](../../com.aspose.html.forms/formeditor/add/)(String) | एक नया [`HTMLElement`](../../com.aspose.html/htmlelement/) बनाता है और उसे फ़ॉर्म के अंत में जोड़ता है। |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput)(String) | एक नया [`InputElement`](../inputelement/) बनाता है और उसे फ़ॉर्म के अंत में जोड़ता है। |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput_1)(String, InputElementType) | एक नया [`InputElement`](../inputelement/) बनाता है और उसे फ़ॉर्म के अंत में जोड़ता है। |
| [dispose](../../com.aspose.html.forms/formeditor/dispose/)() | अप्रबंधित और प्रबंधित संसाधनों को मुक्त करता है। |
| [fill](../../com.aspose.html.forms/formeditor/fill/)(Dictionary&lt;String, String&gt;) |  |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement)(int) | निर्दिष्ट इंडेक्स द्वारा तत्व लौटाता है। |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement_1)(String) | निर्दिष्ट नाम द्वारा तत्व लौटाता है। |
| [getEnumerator](../../com.aspose.html.forms/formeditor/getenumerator/)() | एन्यूमरेटर प्राप्त करता है। |

### संबंधित देखें

* class [FormElement](../formelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
