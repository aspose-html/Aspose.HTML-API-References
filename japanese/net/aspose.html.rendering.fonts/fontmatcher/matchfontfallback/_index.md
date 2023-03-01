---
title: FontMatcher.MatchFontFallback
second_title: Aspose.HTML for .NET API リファレンス
description: FontMatcher 方法. このメソッドは適切なフォントがフォント ルックアップ フォルダーに見つからない場合に呼び出されますfontMatchingPropertiesレンダリングできるcharCode またヌルそのようなフォントが利用できない場合.
type: docs
weight: 10
url: /ja/net/aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

このメソッドは、適切なフォントがフォント ルックアップ フォルダーに見つからない場合に呼び出されます。*fontMatchingProperties*レンダリングできる*charCode*、 また`ヌル`そのようなフォントが利用できない場合.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | 一致したフォントのプロパティ。 |
| charCode | UInt32 | 一致したフォントを使用してレンダリングされる文字のコード。 |

### 戻り値

フォントデータを含むバイト配列または`ヌル`.

### 関連項目

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* 名前空間 [Aspose.Html.Rendering.Fonts](../../fontmatcher/)
* 組み立て [Aspose.HTML](../../../)


