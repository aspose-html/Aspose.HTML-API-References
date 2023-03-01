---
title: Enum MarkdownFeatures
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Saving.MarkdownFeatures 列挙. AMarkdownFeaturesフラグ セットは次のフラグの 0 個以上のセットでありmarkdown に変換される要素を選択するために使用されます
type: docs
weight: 4620
url: /ja/net/aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

A`MarkdownFeatures`フラグ セットは、次のフラグの 0 個以上のセットであり、markdown に変換される要素を選択するために使用されます。

```csharp
[Flags]
public enum MarkdownFeatures
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| InlineHTML | `1` | このフラグは、HTML 要素のインライン化を有効にします。このフラグがブロック レベルの要素 (`分周` ） だれの`マークダウン`属性値が等しい`列をなして`結果のmarkdown. に挿入されます |
| AutomaticParagraph | `2` | このフラグは、`段落`要素。そのような要素のコンテンツは別の行に配置されるため、マークダウン ハンドラーはそれをラップします. |
| Header | `4` | このフラグは、`ヘッダ` elements. |
| Blockquote | `8` | このフラグは、`ブロッククオート` elements. |
| List | `10` | このフラグは、`リスト` elements. |
| CodeBlock | `20` | このフラグは、コード ブロックの変換を有効にします。コードブロックは2つの要素で構成されています`前`と`コード`、そのような構築の内容は「そのまま」のプロセスです。 |
| HorizontalRule | `40` | このフラグは、`水平ルール`. |
| Link | `80` | このフラグは、`a` elements. |
| Emphasis | `100` | このフラグは、`強調` elements. |
| InlineCode | `200` | このフラグは、`コード` elements. |
| Image | `400` | このフラグは、`画像` elements. |
| LineBreak | `800` | このフラグは、`br` elements. |
| Video | `1000` | このフラグは、`ビデオ` elements. |
| Table | `2000` | このフラグは、`テーブル` elements. |
| TaskList | `4000` | このフラグは、タスク リストの変換を有効にします。タスクリストの構成`入力`の最初の子でなければならない要素`リスト`要素とその`タイプ`属性値は等しい必要があります`チェックボックス`. |
| Strikethrough | `8000` | このフラグは、`デル` elements. |
| Strong | `10000` | このフラグは、`強い` elements. |

### 関連項目

* 名前空間 [Aspose.Html.Saving](../../aspose.html.saving/)
* 組み立て [Aspose.HTML](../../)


