---
title: "ICSSImportRule インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.css.ICSSImportRule インターフェイス。CSSImportRule インターフェイスは CSS スタイルシート内のインポート規則を表します。インポート規則は他のスタイルシートからスタイル規則をインポートするために使用されます。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icssimportrule/
---
## ICSSImportRule interface

CSSImportRule インターフェイスは CSS スタイルシート内の @import ルールを表します。@import ルールは他のスタイルシートからスタイルルールをインポートするために使用されます。

```java
public interface ICSSImportRule : ICSSRule
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getHref](../../com.aspose.html.dom.css/icssimportrule/href/) CSSImportRule インターフェイスの読み取り専用 href プロパティは、@import at-rule で指定された URL を返します。 |
| [getMedia](../../com.aspose.html.dom.css/icssimportrule/media/) CSSImportRule インターフェイスの読み取り専用 media プロパティは、関連付けられたスタイルシートの media 属性の値を含む MediaList オブジェクトを返します。 |
| [getStyleSheet](../../com.aspose.html.dom.css/icssimportrule/stylesheet/) この規則が参照するスタイルシートです。ロードされている場合に返されます。スタイルシートがまだロードされていない、またはロードされない場合（例: ユーザーエージェントがサポートしないメディアタイプのスタイルシートの場合）は、この属性の値は null です。 |

### 関連項目

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
