---
title: IXPathEvaluator.CreateNSResolver
second_title: Aspose.HTML for .NET API Referansı
description: IXPathEvaluator yöntem. Herhangi bir DOM düğümünü ad alanlarını çözecek şekilde uyarlar böylece bir XPath ifadesi belgede göründüğü düğümün bağlamına göre kolayca değerlendirilebilir. Bu bağdaştırıcı DOM Düzey 3 yöntemi gibi çalışır aramaNamespaceURI namespaceURI öğesini belirli bir önekten çözümlemede düğümlerde düğümün hiyerarşisinde lookupNamespaceURI çağrıldığında mevcut olan geçerli bilgileri kullanarak aynı zamanda örtük xml önekini doğru bir şekilde çözerek.
type: docs
weight: 20
url: /tr/net/aspose.html.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

Herhangi bir DOM düğümünü ad alanlarını çözecek şekilde uyarlar, böylece bir XPath ifadesi belgede göründüğü düğümün bağlamına göre kolayca değerlendirilebilir. Bu bağdaştırıcı, DOM Düzey 3 yöntemi gibi çalışır `aramaNamespaceURI` namespaceURI öğesini belirli bir önekten çözümlemede düğümlerde, düğümün hiyerarşisinde lookupNamespaceURI çağrıldığında mevcut olan geçerli bilgileri kullanarak, aynı zamanda örtük xml önekini doğru bir şekilde çözerek.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| nodeResolver | Node | Ad alanı çözümlemesi için bağlam olarak kullanılacak düğüm. |

### Geri dönüş değeri

[`IXPathNSResolver`](../../ixpathnsresolver/) bu, belirli bir düğüm için kapsamdaki defines ile ilgili olarak ad alanlarını çözer.

### Ayrıca bakınız

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathEvaluator](../)
* ad alanı [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* toplantı [Aspose.HTML](../../../)


