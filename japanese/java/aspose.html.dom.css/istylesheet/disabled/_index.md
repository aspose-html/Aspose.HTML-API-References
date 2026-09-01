---
title: "IStyleSheet.Disabled"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IStyleSheet プロパティ。StyleSheet インターフェイスの disabled プロパティは、スタイルシートが文書への適用を防止されているかどうかを決定します。"
type: docs

url: /ja/java/com.aspose.html.dom.css/istylesheet/disabled/
---
## IStyleSheet.Disabled property

`[`StyleSheet`](../)` インターフェイスの disabled プロパティは、スタイルシートが文書への適用を防止されているかどうかを決定します。

スタイルシートは、このプロパティを true に手動で設定するか、非アクティブな代替スタイルシートである場合に無効化されることがあります。disabled == false でもスタイルシートが適用されることが保証されないことに注意してください（例えば、文書から削除されている可能性があります）。

この属性を変更すると、文書のスタイル解決が新たに行われる可能性があります。スタイルシートは、適切なメディア定義が存在し、かつ disabled 属性が false の場合にのみ適用されます。したがって、メディアが現在のユーザーエージェントに適用されない場合、disabled 属性は無視されます。

```java
public bool Disabled { get; set; }
```

### 戻り値

disabled属性は、取得時に、disabledフラグが設定されていればtrueを返し、そうでなければfalseを返す必要があります。設定時には、新しい値がtrueであればdisabledフラグを設定し、そうでなければdisabledフラグを解除する必要があります。

### Property Value

disabled属性は、取得時に、disabledフラグが設定されていればtrueを返し、そうでなければfalseを返す必要があります。設定時には、新しい値がtrueであればdisabledフラグを設定し、そうでなければdisabledフラグを解除する必要があります。

## 備考

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参照

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-disabled](https://drafts.csswg.org/cssom/#dom-stylesheet-disabled) – The CSSOM definition.

### 関連項目

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
