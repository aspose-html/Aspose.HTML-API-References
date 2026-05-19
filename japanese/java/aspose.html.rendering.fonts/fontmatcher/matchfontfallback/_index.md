---
title: "FontMatcher.MatchFontFallback"
second_title: "Aspose.HTML for Java API リファレンス"
description: "FontMatcher メソッド。このメソッドはフォント検索フォルダーで適切なフォントが見つからない場合に呼び出されます。fontMatchingProperties に基づいて charCode をレンダリングできる TrueType フォントを返すか、利用できない場合は null を返す必要があります。"
type: docs

url: /ja/java/com.aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

このメソッドはフォント検索フォルダーで適切なフォントが見つからない場合に呼び出されます。*fontMatchingProperties* に基づいて *charCode* をレンダリングできる真のタイプのフォントを返す必要があり、利用できない場合は `null` を返します。

```java
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | 一致したフォントのプロパティ。 |
| charCode | UInt32 | 一致したフォントでレンダリングされる文字のコード。 |

### 戻り値

フォントデータを含むバイト配列、または `null`。

### 関連項目

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* package [com.aspose.html.rendering.fonts](../../../com.aspose.html.rendering.fonts/)
* package [Aspose.HTML](../../../)
