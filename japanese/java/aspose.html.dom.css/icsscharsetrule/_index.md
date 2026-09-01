---
title: "ICSSCharsetRule インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.css.ICSSCharsetRule インターフェイス。CSSCharsetRule インターフェイスは CSS スタイルシート内の charset ルールを表します。encoding 属性の値は DOM オブジェクト内のテキストデータのエンコーディングに影響せず、このエンコーディングは常に UTF-16 です。スタイルシートがロードされた後、encoding 属性の値は charset ルールで見つかった値になります。元のドキュメントに charset が存在しなかった場合、CSSCharsetRule は作成されません。encoding 属性の値は、スタイルシートのシリアライズ時に使用されるエンコーディングのヒントとしても使用されることがあります。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

CSSCharsetRule インターフェイスは、CSS スタイルシート内の @charset ルールを表します。encoding 属性の値は DOM オブジェクト内のテキストデータのエンコーディングには影響せず、エンコーディングは常に UTF-16 です。スタイルシートが読み込まれた後、encoding 属性の値は @charset ルールで見つかった値になります。元のドキュメントに @charset が存在しなかった場合、CSSCharsetRule は作成されません。encoding 属性の値は、スタイルシートのシリアライズ時に使用されるエンコーディングのヒントとしても使用されることがあります。

```java
public interface ICSSCharsetRule : ICSSRule
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
[getEncoding]
[setEncoding] The encoding information associated with the current stylesheet used in this @charset rule. |

### 関連項目

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
