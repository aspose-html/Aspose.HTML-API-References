---
title: "IMediaList インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.css.IMediaList インターフェイス。MediaList インターフェイスは、実装方法や制約を定義せずに、順序付けられたメディアのコレクションを抽象化します。空のリストは、すべてのメディアを含むリストと同等です。"
type: docs

url: /ja/java/com.aspose.html.dom.css/imedialist/
---
## IMediaList interface

MediaList インターフェイスは、実装方法を定義または制約せずに、メディアの順序付けられたコレクションの抽象化を提供します。空のリストは、メディア \"all\" を含むリストと同等です。

以下も参照してください: [CSS Object Model (CSSOM) # ](https://www.w3.org/TR/cssom-1/#the-medialist-interface)[MediaList](https://www.w3.org/TR/cssom-1/#the-medialist-interface)。

```java
public interface IMediaList : IEnumerable<String>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/imedialist/item/) item(index) メソッドは、指定されたインデックスのメディアクエリのシリアライズ結果を返す必要があります。インデックスがコレクション内のメディアクエリ数以上の場合は null を返します。 |
| [getLength](../../com.aspose.html.dom.css/imedialist/length/) length 属性は、メディアクエリコレクション内のメディアクエリ数を返す必要があります。有効なメディアの範囲は 0 から length-1 まで（両端含む）です。 |
| [getMediaText](../../com.aspose.html.dom.css/imedialist/mediatext/) MediaList をテキストとして表す DOMString を返す Stringifier であり、新しい MediaList を設定することも可能です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [appendMedium](../../com.aspose.html.dom.css/imedialist/appendmedium/)(String) | newMedium メディアをリストの末尾に追加します。newMedium が既に使用されている場合は、まず削除されます。 |
| [deleteMedium](../../com.aspose.html.dom.css/imedialist/deletemedium/)(String) | oldMedium が示すメディアをリストから削除します。 |

## 備考

注: MediaList はライブリストです。以下に示すプロパティやメソッドを使用してリストを更新すると、ドキュメントの動作が即座に反映されます。

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参照

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # medialist](https://drafts.csswg.org/cssom/#medialist) – The CSSOM definition.

## サンプル

以下のコードは、現在のドキュメントに適用された最初のスタイルシートの MediaList のテキスト表現をコンソールに出力します。

```java
var stylesheets = document.StyleSheets;
var stylesheet = stylesheets[0];
Console.Write(stylesheet.Media.MediaText);
```

### 関連項目

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
