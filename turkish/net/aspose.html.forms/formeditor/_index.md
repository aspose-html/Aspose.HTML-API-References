---
title: Class FormEditor
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Forms.FormEditor sınıf. Bu sınıf düzenleyiciyi temsil eder.HTMLFormElement bu .net geliştiricilerinin html formlarını düzenlemesi için daha kolay bir yol oluşturur.
type: docs
weight: 2930
url: /tr/net/aspose.html.forms/formeditor/
---
## FormEditor class

Bu sınıf, düzenleyiciyi temsil eder.[`HTMLFormElement`](../../aspose.html/htmlformelement/) bu, .net geliştiricilerinin html formlarını düzenlemesi için daha kolay bir yol oluşturur.

```csharp
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Action](../../aspose.html.forms/formeditor/action/) { get; set; } | Sunucu tarafı form işleyici. HTML 4.01. 'deki eylem özniteliği tanımına bakın |
| [Count](../../aspose.html.forms/formeditor/count/) { get; } | Formdaki form kontrollerinin sayısı. |
| [Form](../../aspose.html.forms/formeditor/form/) { get; } | orijinal[`HTMLFormElement`](../../aspose.html/htmlformelement/) şu anki örneğiyle ilişkili`FormEditor` . |
| [Item](../../aspose.html.forms/formeditor/item/) { get; } | Öğeyi belirtilen dizine göre döndürür. (2 indexers) |
| [Method](../../aspose.html.forms/formeditor/method/) { get; set; } | HTTP yöntemi [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt) formu göndermek için kullanılır. HTML 4.01. 'deki yöntem özniteliği tanımına bakın |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [Create](../../aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | Yeni bir tane oluşturur`FormEditor` dayalı[`HTMLFormElement`](../../aspose.html/htmlformelement/) . |
| static [Create](../../aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | Yeni bir tane oluşturur`FormEditor` dayalı[`HTMLFormElement`](../../aspose.html/htmlformelement/) arasından seçilen[`Forms`](../../aspose.html/htmldocument/forms/) index. ile toplama |
| static [Create](../../aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, string) | Yeni bir tane oluşturur`FormEditor` dayalı[`HTMLFormElement`](../../aspose.html/htmlformelement/) id. tarafından belgeden seçildi |
| static [CreateNew](../../aspose.html.forms/formeditor/createnew/)(HTMLDocument) | Yeni bir tane oluşturur[`HTMLFormElement`](../../aspose.html/htmlformelement/) ve bununla ilişkilendirdi`FormEditor` .[`HTMLFormElement`](../../aspose.html/htmlformelement/) belge durumundan kopuk olarak oluşturulur; belgeye eklemek için lütfen uygun yeri seçin ve kullanın[`AppendChild`](../../aspose.html.dom/node/appendchild/) yöntem. |
| [Add&lt;T&gt;](../../aspose.html.forms/formeditor/add/)(string) | Yeni bir tane oluşturur[`HTMLElement`](../../aspose.html/htmlelement/) ve formun sonuna ekler. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput)(string) | Yeni bir tane oluşturur[`InputElement`](../inputelement/) ve formun sonuna ekler. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput_1)(string, InputElementType) | Yeni bir tane oluşturur[`InputElement`](../inputelement/) ve formun sonuna ekler. |
| [Dispose](../../aspose.html.forms/formeditor/dispose/)() | Yönetilmeyen ve yönetilen kaynakları serbest bırakır. |
| [Fill](../../aspose.html.forms/formeditor/fill/)(Dictionary&lt;string, string&gt;) | Bu yöntem, tüm formu belirtilen değerlerle doldurur. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement)(int) | Öğeyi belirtilen dizine göre döndürür. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement_1)(string) | Öğeyi belirtilen ada göre döndürür. |
| [GetEnumerator](../../aspose.html.forms/formeditor/getenumerator/)() | Numaralandırıcıyı alır. |

### Ayrıca bakınız

* class [FormElement](../formelement/)
* ad alanı [Aspose.Html.Forms](../../aspose.html.forms/)
* toplantı [Aspose.HTML](../../)


