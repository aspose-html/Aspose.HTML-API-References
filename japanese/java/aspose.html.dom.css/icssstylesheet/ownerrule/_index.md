---
title: "ICSSStyleSheet.OwnerRule"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICSSStyleSheet プロパティ。読み取り専用の CSSStyleSheet プロパティ ownerRule は、スタイルシートをドキュメントにインポートした import at-rule に対応する CSSImportRule を返します。スタイルシートが import を使用してドキュメントにインポートされていない場合、返される値は null です。"
type: docs

url: /ja/java/com.aspose.html.dom.css/icssstylesheet/ownerrule/
---
## ICSSStyleSheet.OwnerRule property

読み取り専用の CSSStyleSheet プロパティ ownerRule は、スタイルシートをドキュメントにインポートした @import at-rule に対応する [`CSSImportRule`](../../icssimportrule/) を返します。スタイルシートが @import を使用してドキュメントにインポートされていない場合、返される値は null です。

```java
public ICSSRule OwnerRule { get; }
```

### Property Value

@import ルールに対応する CSSImportRule です。スタイルシートが @import を使用してドキュメントにインポートされていない場合、返される値は null です。

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参照

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-cssstylesheet-ownerrule](https://drafts.csswg.org/cssom/#dom-cssstylesheet-ownerrule) – The CSSOM definition.

### 関連項目

* interface [ICSSRule](../../icssrule/)
* interface [ICSSStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
