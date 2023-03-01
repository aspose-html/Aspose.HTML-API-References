---
title: Class DOMException
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.DOMException sınıf. DOMException arabirimi bir yöntemi çağırmanın veya bir web API özelliğine erişmenin sonucu olarak meydana gelen istisna adı verilen anormal bir olayı temsil eder. Bu temel olarak web APIlerinde hata koşullarının nasıl açıklandığıdır.
type: docs
weight: 640
url: /tr/net/aspose.html.dom/domexception/
---
## DOMException class

DOMException arabirimi, bir yöntemi çağırmanın veya bir web API özelliğine erişmenin sonucu olarak meydana gelen (istisna adı verilen) anormal bir olayı temsil eder. Bu, temel olarak web API'lerinde hata koşullarının nasıl açıklandığıdır.

```csharp
public class DOMException : PlatformException
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [DOMException](domexception/#constructor)(string) | Yeni bir örneğini başlatır.`DOMException` sınıf. |
| [DOMException](domexception/#constructor_1)(string, string) | Yeni bir örneğini başlatır.`DOMException` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Code](../../aspose.html.dom/domexception/code/) { get; } | Hata kodu sabitlerinden birini içeren bir değer veya hiçbiri eşleşmezse 0 döndürür. Bu alan tarihsel nedenlerle kullanılmaktadır. |
| override [Message](../../aspose.html.dom/domexception/message/) { get; } | Verilen hata adıyla ilişkili bir mesajı veya açıklamayı temsil eden bir dize döndürür. |
| [Name](../../aspose.html.dom/domexception/name/) { get; } | Bir hata adıyla ilişkili dizilerden birini içeren bir dizi döndürür. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [ABORT_ERR](../../aspose.html.dom/domexception/abort_err/) | İşlem durduruldu. |
| const [DATA_CLONE_ERR](../../aspose.html.dom/domexception/data_clone_err/) | Nesne klonlanamaz. |
| const [DOMSTRING_SIZE_ERR](../../aspose.html.dom/domexception/domstring_size_err/) | Belirtilen metin aralığı bir DOMString. dosyasına sığmazsa |
| const [HIERARCHY_REQUEST_ERR](../../aspose.html.dom/domexception/hierarchy_request_err/) | Herhangi bir Düğüm, ait olmadığı bir yere eklenirse. |
| const [INDEX_SIZE_ERR](../../aspose.html.dom/domexception/index_size_err/) | Dizin veya boyut negatifse veya izin verilen değerden büyükse. |
| const [INUSE_ATTRIBUTE_ERR](../../aspose.html.dom/domexception/inuse_attribute_err/) | Halihazırda başka bir yerde kullanımda olan bir özellik eklenmeye çalışılırsa. |
| const [INVALID_ACCESS_ERR](../../aspose.html.dom/domexception/invalid_access_err/) | Alttaki nesne tarafından bir parametre veya işlem desteklenmiyorsa. |
| const [INVALID_CHARACTER_ERR](../../aspose.html.dom/domexception/invalid_character_err/) | XML adında olduğu gibi geçersiz veya geçersiz bir karakter belirtilirse. |
| const [INVALID_EXPRESSION_ERR](../../aspose.html.dom/domexception/invalid_expression_err/) | İfadede bir sözdizimi hatası var veya belirli XPathEvaluator kurallarına göre yasal bir ifade değil veya özel uzantı işlevleri veya bu uygulama tarafından desteklenmeyen değişkenler içeriyor. |
| const [INVALID_MODIFICATION_ERR](../../aspose.html.dom/domexception/invalid_modification_err/) | Altta yatan nesnenin türü değiştirilmeye çalışılırsa. |
| const [INVALID_NODE_TYPE_ERR](../../aspose.html.dom/domexception/invalid_node_type_err/) | Sağlanan düğüm yanlış veya bu işlem için yanlış bir ataya sahip. |
| const [INVALID_STATE_ERR](../../aspose.html.dom/domexception/invalid_state_err/) | Kullanılmayan veya artık kullanılmayan bir nesneyi kullanma girişiminde bulunulursa. |
| const [NAMESPACE_ERR](../../aspose.html.dom/domexception/namespace_err/) | Ad alanları açısından yanlış bir şekilde bir nesne oluşturulmaya veya değiştirilmeye çalışılırsa. |
| const [NETWORK_ERR](../../aspose.html.dom/domexception/network_err/) | Bir ağ hatası oluştu. |
| const [NOT_FOUND_ERR](../../aspose.html.dom/domexception/not_found_err/) | Bir Düğüme, var olmadığı bir bağlamda başvurulmaya çalışılırsa. |
| const [NOT_SUPPORTED_ERR](../../aspose.html.dom/domexception/not_supported_err/) | Uygulama, istenen nesne veya işlem türünü desteklemiyorsa. |
| const [NO_DATA_ALLOWED_ERR](../../aspose.html.dom/domexception/no_data_allowed_err/) | Verileri desteklemeyen bir Düğüm için veri belirtilirse. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../aspose.html.dom/domexception/no_modification_allowed_err/) | Değişikliklere izin verilmeyen bir nesnede değişiklik yapılmaya çalışılırsa. |
| const [QUOTA_EXCEEDED_ERR](../../aspose.html.dom/domexception/quota_exceeded_err/) | Kota aşıldı. |
| const [SECURITY_ERR](../../aspose.html.dom/domexception/security_err/) | İşlem güvenli değil. |
| const [SYNTAX_ERR](../../aspose.html.dom/domexception/syntax_err/) | Geçersiz veya geçersiz bir dize belirtilirse. |
| const [TIMEOUT_ERR](../../aspose.html.dom/domexception/timeout_err/) | İşlem zaman aşımına uğradı. |
| const [TYPE_ERR](../../aspose.html.dom/domexception/type_err/) | İfade, belirtilen türü döndürmek için dönüştürülemez. |
| const [TYPE_MISMATCH_ERR](../../aspose.html.dom/domexception/type_mismatch_err/) | Bir nesnenin türü, nesneyle ilişkili beklenen parametre türüyle uyumsuzsa. |
| const [URL_MISMATCH_ERR](../../aspose.html.dom/domexception/url_mismatch_err/) | Verilen URL başka bir URL ile eşleşmiyor. |
| const [VALIDATION_ERR](../../aspose.html.dom/domexception/validation_err/) | InsertBefore veya removeChild gibi bir metoda yapılan çağrı Düğümü "kısmi geçerlilik" açısından geçersiz kılacaksa, bu istisna ortaya çıkar ve işlem yapılmaz. Bu kod, [DOM Düzey 3 Doğrulama]'da kullanılır. Daha fazla bilgi için bu spesifikasyona bakın. |
| const [WRONG_DOCUMENT_ERR](../../aspose.html.dom/domexception/wrong_document_err/) | Bir Düğüm, onu oluşturandan farklı bir belgede kullanılıyorsa (bu onu desteklemez). |

### Ayrıca bakınız

* class [PlatformException](../../aspose.html/platformexception/)
* ad alanı [Aspose.Html.Dom](../../aspose.html.dom/)
* toplantı [Aspose.HTML](../../)


