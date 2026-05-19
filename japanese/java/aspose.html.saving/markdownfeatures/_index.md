---
title: "MarkdownFeatures 列挙型"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.saving.MarkdownFeatures 列挙型。MarkdownFeatures フラグセットは、markdown に変換される要素を選択するために使用される以下のフラグの 0 個以上の集合です。"
type: docs

url: /ja/java/com.aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

`MarkdownFeatures` フラグセットは、markdown に変換される要素を選択するために使用される以下のフラグの 0 個以上の集合です。

```java
[Flags]
public enum MarkdownFeatures
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| InlineHTML | `1` | このフラグは HTML 要素のインライン化を有効にします。このフラグが設定されている場合、ブロックレベル要素（例: `div`）で `markdown` 属性の値が `inline` と等しいものが、結果の markdown に挿入されます。 |
| AutomaticParagraph | `2` | このフラグは `paragraph` 要素の変換を有効にします。そのような要素の内容は別々の行に配置され、markdown ハンドラがラップします。 |
| Header | `4` | このフラグは `header` 要素の変換を有効にします。 |
| Blockquote | `8` | このフラグは `blockquote` 要素の変換を有効にします。 |
| List | `10` | このフラグは `list` 要素の変換を有効にします。 |
| CodeBlock | `20` | このフラグはコードブロックの変換を有効にします。コードブロックは `pre` と `code` の 2 つの要素から構成され、そのような構造の内容は「そのまま」処理されます。 |
| HorizontalRule | `40` | このフラグは `horizontal rules` の変換を有効にします。 |
| Link | `80` | このフラグは `a` 要素の変換を有効にします。 |
| Emphasis | `100` | このフラグは `emphasis` 要素の変換を有効にします。 |
| InlineCode | `200` | このフラグは `code` 要素の変換を有効にします。 |
| Image | `400` | このフラグは `img` 要素の変換を有効にします。 |
| LineBreak | `800` | このフラグは `br` 要素の変換を有効にします。 |
| Video | `1000` | このフラグは `video` 要素の変換を有効にします。 |
| Table | `2000` | このフラグは `table` 要素の変換を有効にします。 |
| TaskList | `4000` | このフラグはタスクリストの変換を有効にします。タスクリストは `input` 要素で構成され、`list` 要素の最初の子であり、`type` 属性の値が `checkbox` と等しい必要があります。 |
| Strikethrough | `8000` | このフラグは `del` 要素の変換を有効にします。 |
| Strong | `10000` | このフラグは `strong` 要素の変換を有効にします。 |

### 関連項目

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
