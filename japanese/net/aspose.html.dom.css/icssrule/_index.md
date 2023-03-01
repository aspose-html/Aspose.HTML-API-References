---
title: Interface ICSSRule
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Css.ICSSRule インターフェース. CSSRule インターフェイスはあらゆるタイプの CSS ステートメントの抽象基本インターフェイスですこれには規則セットと  規則の両方が含まれますルールがパーサーによって認識されない場合でも実装は CSS スタイル シートで指定されたすべてのルールを保持することが期待されます認識されていないルールはICSSUnknownRuleインターフェイス.
type: docs
weight: 470
url: /ja/net/aspose.html.dom.css/icssrule/
---
## ICSSRule interface

CSSRule インターフェイスは、あらゆるタイプの CSS ステートメントの抽象基本インターフェイスです。これには、規則セットと @ 規則の両方が含まれます。ルールがパーサーによって認識されない場合でも、実装は CSS スタイル シートで指定されたすべてのルールを保持することが期待されます。認識されていないルールは、!:ICSSUnknownRuleインターフェイス.

```csharp
public interface ICSSRule
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssrule/csstext/) { get; set; } | ルールの解析可能なテキスト表現。これはルールの現在の状態を反映しており、初期値ではありません. |
| [ParentRule](../../aspose.html.dom.css/icssrule/parentrule/) { get; } | このルールが別のルール (@media ブロック内のスタイル ルールなど) 内に含まれている場合、これが含まれているルールです。このルールが他のルール内にネストされていない場合、null. が返されます。 |
| [ParentStyleSheet](../../aspose.html.dom.css/icssrule/parentstylesheet/) { get; } | このルールを含むスタイル シート。 |
| [Type](../../aspose.html.dom.css/icssrule/type/) { get; } | 上記で定義したルールのタイプ。バインディング固有のキャスト メソッドを使用して、CSSRule インターフェイスのインスタンスから、type. によって暗示された特定の派生インターフェイスにキャスト ダウンできることが期待されます。 |

### 関連項目

* 名前空間 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 組み立て [Aspose.HTML](../../)


