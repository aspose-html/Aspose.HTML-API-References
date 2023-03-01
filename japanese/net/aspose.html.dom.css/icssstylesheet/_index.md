---
title: Interface ICSSStyleSheet
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Css.ICSSStyleSheet インターフェース. CSSStyleSheet インターフェイスはCSS スタイル シートつまりコンテンツ タイプがtext/cssのスタイル シートを表すために使用される具体的なインターフェイスです
type: docs
weight: 510
url: /ja/net/aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

CSSStyleSheet インターフェイスは、CSS スタイル シート、つまりコンテンツ タイプが「text/css」のスタイル シートを表すために使用される具体的なインターフェイスです。

```csharp
public interface ICSSStyleSheet : IStyleSheet
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CSSRules](../../aspose.html.dom.css/icssstylesheet/cssrules/) { get; } | スタイルシートに含まれるすべての CSS ルールのリスト。これには、ルール セットと @-rules. の両方が含まれます。 |
| [OwnerRule](../../aspose.html.dom.css/icssstylesheet/ownerrule/) { get; } | このスタイル シートが @import ルールに由来する場合、ownerRule 属性には CSSImportRule が含まれます。その場合、StyleSheet インターフェイスの ownerNode 属性は null になります。スタイル シートが要素または処理命令に由来する場合、ownerRule 属性は null になり、ownerNode 属性には Node. が含まれます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [DeleteRule](../../aspose.html.dom.css/icssstylesheet/deleterule/)(int) | スタイルシートからルールを削除するために使用されます. |
| [InsertRule](../../aspose.html.dom.css/icssstylesheet/insertrule/)(string, int) | スタイルシートに新しいルールを挿入するために使用されます。新しいルールがカスケードの一部になります。 |

### 関連項目

* interface [IStyleSheet](../istylesheet/)
* 名前空間 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 組み立て [Aspose.HTML](../../)


