---
title: "ICSSStyleSheet インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.css.ICSSStyleSheet インターフェイス。CSSStyleSheet インターフェイスは単一の CSS スタイルシートを表し、スタイルシートに含まれるルールの一覧を検査および変更できます。親である IStyleSheet からプロパティとメソッドを継承します。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

CSSStyleSheet インターフェイスは単一の CSS スタイルシートを表し、スタイルシートに含まれるルールの一覧を検査および変更できます。親である [`IStyleSheet`](../istylesheet/) からプロパティとメソッドを継承します。

スタイルシートは、スタイルシート内の各ルールを表す [`ICSSRule`](../icssrule/) オブジェクトのコレクションで構成されます。これらのルールは [`ICSSRuleList`](../icssrulelist/) に格納されており、スタイルシートの cssRules プロパティから取得できます。

例として、あるルールは [`ICSSStyleRule`](../icssstylerule/) オブジェクトで、次のようなスタイルを含むことがあります

```java
h1, h2 {   font-size: 16pt; }
```

別のルールは、@import や @media などの at-rule である場合があります。

```java
public interface ICSSStyleSheet : IStyleSheet
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icssstylesheet/cssrules/) 読み取り専用の CSSStyleSheet プロパティ cssRules は、スタイルシートを構成するすべての CSS ルールのリアルタイムで最新のリストを提供するライブ [`CSSRuleList`](../icssrulelist/) を返します。リストの各項目は単一のルールを定義する [`CSSRule`](../icssrule/) です。 |
| [getOwnerRule](../../com.aspose.html.dom.css/icssstylesheet/ownerrule/) 読み取り専用の CSSStyleSheet プロパティ ownerRule は、スタイルシートをドキュメントにインポートした @import at-rule に対応する [`CSSImportRule`](../icssimportrule/) を返します。@import を使用してスタイルシートがドキュメントにインポートされていない場合、返される値は null です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [deleteRule](../../com.aspose.html.dom.css/icssstylesheet/deleterule/)(int) | `CSSStyleSheet` のメソッド deleteRule() は、スタイルシートオブジェクトからルールを削除します。 |
| [insertRule](../../com.aspose.html.dom.css/icssstylesheet/insertrule/)(String, int) | CSSStyleSheet.insertRule() メソッドは、いくつかの制限付きで新しい CSS ルールを現在のスタイルシートに挿入します。 |

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参照

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstylesheet](https://drafts.csswg.org/cssom/#cssstylesheet) – The CSSOM definition.

### 関連項目

* interface [IStyleSheet](../istylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
