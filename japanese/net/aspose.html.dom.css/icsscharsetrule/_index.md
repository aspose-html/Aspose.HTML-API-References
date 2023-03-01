---
title: Interface ICSSCharsetRule
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Css.ICSSCharsetRule インターフェース. CSSCharsetRule インターフェイスはCSS スタイル シートの charset ルールを表します encoding 属性の値はDOM オブジェクト内のテキスト データのエンコーディングには影響しませんこのエンコーディングは常に UTF16 ですスタイルシートが読み込まれるとencoding 属性の値は charset ルールで見つかった値になります元のドキュメントに charset がなかった場合CSSCharsetRule は作成されません encoding 属性の値はスタイル シートのシリアル化で使用されるエンコーディングのヒントとしても使用できます
type: docs
weight: 380
url: /ja/net/aspose.html.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

CSSCharsetRule インターフェイスは、CSS スタイル シートの @charset ルールを表します。 encoding 属性の値は、DOM オブジェクト内のテキスト データのエンコーディングには影響しません。このエンコーディングは常に UTF-16 です。スタイルシートが読み込まれると、encoding 属性の値は @charset ルールで見つかった値になります。元のドキュメントに @charset がなかった場合、CSSCharsetRule は作成されません。 encoding 属性の値は、スタイル シートのシリアル化で使用されるエンコーディングのヒントとしても使用できます。

```csharp
public interface ICSSCharsetRule : ICSSRule
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Encoding](../../aspose.html.dom.css/icsscharsetrule/encoding/) { get; set; } | この @charset ルールで使用されるエンコード情報。 |

### 関連項目

* interface [ICSSRule](../icssrule/)
* 名前空間 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 組み立て [Aspose.HTML](../../)


