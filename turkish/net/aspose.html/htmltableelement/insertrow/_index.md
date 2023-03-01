---
title: HTMLTableElement.InsertRow
second_title: Aspose.HTML for .NET API Referansı
description: HTMLTableElement yöntem. Tabloya yeni bir boş satır ekleyin. Yeni satır geçerli satırından hemen önce ve aynı bölüme eklenir.dizin tablodaki inci sıra. Eğerdizin 1 veya satır sayısına eşitse yeni satır eklenir. Ek olarak tablo boş olduğunda satır birTBODY oluşturulur ve tabloya eklenir. Bir tablo satırı ya göre boş olamazHTML 4.01 .
type: docs
weight: 220
url: /tr/net/aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

Tabloya yeni bir boş satır ekleyin. Yeni satır, geçerli satırından hemen önce ve aynı bölüme eklenir.`dizin` tablodaki inci sıra. Eğer`dizin` -1 veya satır sayısına eşitse, yeni satır eklenir. Ek olarak, tablo boş olduğunda satır bir`TBODY` oluşturulur ve tabloya eklenir. Bir tablo satırı ['ya göre boş olamaz[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224) ].

```csharp
public Node InsertRow(int index)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| index | Int32 | Yeni bir satırın ekleneceği satır numarası. Bu dizin , 0'dan başlar ve tablonun içerdiği tüm satırların mantıksal sırasına (belge sırasına değil) bağlıdır. |

### Geri dönüş değeri

Yeni oluşturulan satır.

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Belirtilen dizin satır sayısından büyükse veya dizin -1. @version DOM Düzey 2'den farklı bir negatif sayıysa yükselir. |

### Ayrıca bakınız

* class [Node](../../../aspose.html.dom/node/)
* class [HTMLTableElement](../)
* ad alanı [Aspose.Html](../../htmltableelement/)
* toplantı [Aspose.HTML](../../../)


