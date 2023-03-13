---
title: Class FormEditor
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.Forms.FormEditor कक्ष. यह वर्ग संपदक क प्रतनधत्व करत हैHTMLFormElement यह .net डेवलपर्स के लए html रूपं क संपदत करने क एक आसन तरक बनत है
type: docs
weight: 2930
url: /hi/net/aspose.html.forms/formeditor/
---
## FormEditor class

यह वर्ग संपादक का प्रतिनिधित्व करता है[`HTMLFormElement`](../../aspose.html/htmlformelement/) यह .net डेवलपर्स के लिए html रूपों को संपादित करने का एक आसान तरीका बनाता है।

```csharp
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Action](../../aspose.html.forms/formeditor/action/) { get; set; } | सर्वर-साइड फॉर्म हैंडलर। HTML 4.01. में क्रिया विशेषता परिभाषा देखें |
| [Count](../../aspose.html.forms/formeditor/count/) { get; } | प्रपत्र में प्रपत्र नियंत्रणों की संख्या. |
| [Form](../../aspose.html.forms/formeditor/form/) { get; } | मूल[`HTMLFormElement`](../../aspose.html/htmlformelement/) के वर्तमान उदाहरण से संबंधित है`FormEditor` . |
| [Item](../../aspose.html.forms/formeditor/item/) { get; } | निर्दिष्ट इंडेक्स द्वारा तत्व लौटाता है। (2 indexers) |
| [Method](../../aspose.html.forms/formeditor/method/) { get; set; } | HTTP विधि [[आईईटीएफ आरएफसी 2616](http://www.ietf.org/rfc/rfc2616.txt) फॉर्म जमा करते थे। HTML 4.01. में विधि विशेषता परिभाषा देखें |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [Create](../../aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | एक नया बनाता है`FormEditor` पर आधारित[`HTMLFormElement`](../../aspose.html/htmlformelement/) . |
| static [Create](../../aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | एक नया बनाता है`FormEditor` पर आधारित[`HTMLFormElement`](../../aspose.html/htmlformelement/) से चुना गया[`Forms`](../../aspose.html/htmldocument/forms/) अनुक्रमणिका द्वारा संग्रह. |
| static [Create](../../aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, string) | एक नया बनाता है`FormEditor` पर आधारित[`HTMLFormElement`](../../aspose.html/htmlformelement/) दस्तावेज़ से id. द्वारा चयनित |
| static [CreateNew](../../aspose.html.forms/formeditor/createnew/)(HTMLDocument) | एक नया बनाता है[`HTMLFormElement`](../../aspose.html/htmlformelement/) और इसे इससे जोड़ा`FormEditor` .[`HTMLFormElement`](../../aspose.html/htmlformelement/) दस्तावेज़ स्थिति से अलग किए गए में बनाया गया है; इसे दस्तावेज़ में संलग्न करने के लिए, कृपया उचित स्थान का चयन करें और उसका उपयोग करें[`AppendChild`](../../aspose.html.dom/node/appendchild/) विधि. |
| [Add&lt;T&gt;](../../aspose.html.forms/formeditor/add/)(string) | एक नया बनाता है[`HTMLElement`](../../aspose.html/htmlelement/) और इसे फॉर्म के अंत में जोड़ता है। |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput)(string) | एक नया बनाता है[`InputElement`](../inputelement/) और इसे फॉर्म के अंत में जोड़ता है। |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput_1)(string, InputElementType) | एक नया बनाता है[`InputElement`](../inputelement/) और इसे फॉर्म के अंत में जोड़ता है। |
| [Dispose](../../aspose.html.forms/formeditor/dispose/)() | अप्रबंधित और प्रबंधित संसाधन जारी करता है। |
| [Fill](../../aspose.html.forms/formeditor/fill/)(Dictionary&lt;string, string&gt;) | यह विधि पूरे फॉर्म को निर्दिष्ट मानों से भरती है। |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement)(int) | निर्दिष्ट इंडेक्स द्वारा तत्व लौटाता है। |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement_1)(string) | तत्व को निर्दिष्ट नाम से लौटाता है। |
| [GetEnumerator](../../aspose.html.forms/formeditor/getenumerator/)() | गणनाकर्ता प्राप्त करता है। |

### यह सभी देखें

* class [FormElement](../formelement/)
* नाम स्थान [Aspose.Html.Forms](../../aspose.html.forms/)
* सभा [Aspose.HTML](../../)


