---
title: Class Location
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Window.Location クラス. Location オブジェクトはDocument のブラウジング コンテキストのアクティブなドキュメントのアドレスの表現を提供し履歴オブジェクトのエントリを追加または置換することによってブラウジング コンテキストのセッション履歴の現在のエントリを変更できるようにします
type: docs
weight: 5880
url: /ja/net/aspose.html.window/location/
---
## Location class

Location オブジェクトは、Document のブラウジング コンテキストのアクティブなドキュメントのアドレスの表現を提供し、履歴オブジェクトのエントリを追加または置換することによって、ブラウジング コンテキストのセッション履歴の現在のエントリを変更できるようにします。

```csharp
public sealed class Location : Url
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Hash](../../aspose.html/url/hash/) { get; set; } | 指定された URL ハッシュ セグメントの文字列表現を取得または設定します。 |
| [Host](../../aspose.html/url/host/) { get; set; } | 指定された URL ホストの文字列表現を取得または設定します。 |
| [Hostname](../../aspose.html/url/hostname/) { get; set; } | 指定された URL ホスト名の文字列表現を取得または設定します。 |
| [Href](../../aspose.html/url/href/) { get; set; } | 指定された URL インスタンスのシリアル化された表現を取得または設定します。 |
| [Origin](../../aspose.html/url/origin/) { get; } | 指定された URL オリジンの文字列表現を取得します。 |
| [Password](../../aspose.html/url/password/) { get; set; } | 指定された URL パスワードの文字列表現を取得または設定します。 |
| [Pathname](../../aspose.html/url/pathname/) { get; set; } | 指定された URL パスの文字列表現を取得または設定します。 |
| [Port](../../aspose.html/url/port/) { get; set; } | 指定された URL ポートの文字列表現を取得または設定します。 |
| [Protocol](../../aspose.html/url/protocol/) { get; set; } | 指定された URL スキーマの文字列表現を取得または設定します。 |
| [Search](../../aspose.html/url/search/) { get; set; } | 指定された URL 検索セグメントの文字列表現を取得または設定します。 |
| [SearchParams](../../aspose.html/url/searchparams/) { get; } | 関連を取得します[`IUrlSearchParams`](../../aspose.html/iurlsearchparams/)object. |
| [Username](../../aspose.html/url/username/) { get; set; } | 指定された URL ユーザー名の文字列表現を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Assign](../../aspose.html.window/location/assign/)(string) | 指定されたページに移動します。 |
| override [Equals](../../aspose.html/url/equals/)(object) | 指定されたObject 、このインスタンスと等しい. |
| override [GetHashCode](../../aspose.html/url/gethashcode/)() | このインスタンスのハッシュ コードを返します。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType. |
| [Reload](../../aspose.html.window/location/reload/)() | 現在のページをリロードします。 |
| [Replace](../../aspose.html.window/location/replace/)(string) | セッション履歴から現在のページを削除し、指定されたページに移動します。 |
| [ToJson](../../aspose.html/url/tojson/)() | を返しますStringこのインスタンスを表す. |
| override [ToString](../../aspose.html/url/tostring/)() | を返しますStringこのインスタンスを表す. |

### 関連項目

* class [Url](../../aspose.html/url/)
* 名前空間 [Aspose.Html.Window](../../aspose.html.window/)
* 組み立て [Aspose.HTML](../../)


