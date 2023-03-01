---
title: Interface IStyleSheet
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Css.IStyleSheet インターフェース. StyleSheet インターフェイスはあらゆるタイプのスタイル シートの抽象ベース インターフェイスです構造化ドキュメントに関連付けられた単一のスタイル シートを表します
type: docs
weight: 590
url: /ja/net/aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

StyleSheet インターフェイスは、あらゆるタイプのスタイル シートの抽象ベース インターフェイスです。構造化ドキュメントに関連付けられた単一のスタイル シートを表します。

```csharp
public interface IStyleSheet
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Disabled](../../aspose.html.dom.css/istylesheet/disabled/) { get; set; } | スタイル シートがドキュメントに適用されている場合は false。そうでない場合は true。この属性を変更すると、ドキュメントのスタイルが新たに解決される場合があります。スタイルシートは、適切なメディア定義が存在し、disabled 属性が false の場合にのみ適用されます。そのため、メディアが現在のユーザー エージェントに適用されない場合、disabled 属性は無視されます. |
| [Href](../../aspose.html.dom.css/istylesheet/href/) { get; } | スタイル シートがリンクされたスタイル シートの場合、その属性の値はその場所です。インライン スタイル シートの場合、この属性の値は null です。 |
| [Media](../../aspose.html.dom.css/istylesheet/media/) { get; } | スタイル情報の対象メディア。 |
| [OwnerNode](../../aspose.html.dom.css/istylesheet/ownernode/) { get; } | このスタイル シートをドキュメントに関連付けるノード。 HTML の場合、これは対応する LINK または STYLE 要素である可能性があります。 XML の場合は、リンク処理命令の可能性があります。他のスタイル シートに含まれるスタイル シートの場合、この属性の値は null. です。 |
| [ParentStyleSheet](../../aspose.html.dom.css/istylesheet/parentstylesheet/) { get; } | スタイル シート インクルードの概念をサポートするスタイル シート言語の場合、この属性はインクルード スタイル シートを表します (存在する場合)。スタイル シートがトップレベルのスタイル シートである場合、またはスタイル シート言語が包含をサポートしていない場合、この属性の値は null. です。 |
| [Title](../../aspose.html.dom.css/istylesheet/title/) { get; } | アドバイザリのタイトル。 |
| [Type](../../aspose.html.dom.css/istylesheet/type/) { get; } | このスタイル シートのスタイル シート言語を指定します。スタイルシート言語はコンテンツタイプとして指定されます (例: "text/css"). |

### 関連項目

* 名前空間 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 組み立て [Aspose.HTML](../../)


