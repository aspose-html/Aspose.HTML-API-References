---
title: Class DOMException
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.DOMException クラス. DOMException インターフェイスはWeb API のメソッドの呼び出しまたはプロパティへのアクセスの結果として発生する異常なイベント 例外と呼ばれます を表しますこれは基本的にWeb API でエラー状態を記述する方法です
type: docs
weight: 640
url: /ja/net/aspose.html.dom/domexception/
---
## DOMException class

DOMException インターフェイスは、Web API のメソッドの呼び出しまたはプロパティへのアクセスの結果として発生する異常なイベント (例外と呼ばれます) を表します。これは基本的に、Web API でエラー状態を記述する方法です。

```csharp
public class DOMException : PlatformException
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [DOMException](domexception/#constructor)(string) | の新しいインスタンスを初期化します`DOMException` class. |
| [DOMException](domexception/#constructor_1)(string, string) | の新しいインスタンスを初期化します`DOMException` class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Code](../../aspose.html.dom/domexception/code/) { get; } | エラー コード定数の 1 つを含む値を返します。一致するものがない場合は 0 を返します。このフィールドは歴史的な理由から使用されます. |
| override [Message](../../aspose.html.dom/domexception/message/) { get; } | 指定されたエラー名に関連付けられたメッセージまたは説明を表す文字列を返します。 |
| [Name](../../aspose.html.dom/domexception/name/) { get; } | エラー名に関連付けられた文字列の 1 つを含む文字列を返します。 |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [ABORT_ERR](../../aspose.html.dom/domexception/abort_err/) | 操作は中止されました. |
| const [DATA_CLONE_ERR](../../aspose.html.dom/domexception/data_clone_err/) | オブジェクトのクローンを作成できません。 |
| const [DOMSTRING_SIZE_ERR](../../aspose.html.dom/domexception/domstring_size_err/) | 指定された範囲のテキストが DOMString に収まらない場合. |
| const [HIERARCHY_REQUEST_ERR](../../aspose.html.dom/domexception/hierarchy_request_err/) | ノードが属していない場所に挿入された場合. |
| const [INDEX_SIZE_ERR](../../aspose.html.dom/domexception/index_size_err/) | インデックスまたはサイズが負の場合、または許容値より大きい場合. |
| const [INUSE_ATTRIBUTE_ERR](../../aspose.html.dom/domexception/inuse_attribute_err/) | 他の場所で既に使用されている属性を追加しようとした場合. |
| const [INVALID_ACCESS_ERR](../../aspose.html.dom/domexception/invalid_access_err/) | パラメータまたは操作が基になるオブジェクトでサポートされていない場合. |
| const [INVALID_CHARACTER_ERR](../../aspose.html.dom/domexception/invalid_character_err/) | XML 名などで無効または不正な文字が指定された場合。 |
| const [INVALID_EXPRESSION_ERR](../../aspose.html.dom/domexception/invalid_expression_err/) | 式に構文エラーがあるか、特定の XPathEvaluator の規則に従って有効な式ではないか、この実装でサポートされていない特殊な拡張関数または変数が含まれています. |
| const [INVALID_MODIFICATION_ERR](../../aspose.html.dom/domexception/invalid_modification_err/) | 基になるオブジェクトの型を変更しようとした場合. |
| const [INVALID_NODE_TYPE_ERR](../../aspose.html.dom/domexception/invalid_node_type_err/) | 指定されたノードが正しくないか、この操作の祖先が正しくありません。 |
| const [INVALID_STATE_ERR](../../aspose.html.dom/domexception/invalid_state_err/) | 使用できない、または使用できなくなったオブジェクトを使用しようとした場合. |
| const [NAMESPACE_ERR](../../aspose.html.dom/domexception/namespace_err/) | 名前空間に関して正しくない方法でオブジェクトを作成または変更しようとした場合. |
| const [NETWORK_ERR](../../aspose.html.dom/domexception/network_err/) | ネットワーク エラーが発生しました。 |
| const [NOT_FOUND_ERR](../../aspose.html.dom/domexception/not_found_err/) | ノードが存在しないコンテキストでノードを参照しようとした場合. |
| const [NOT_SUPPORTED_ERR](../../aspose.html.dom/domexception/not_supported_err/) | 実装が要求されたタイプのオブジェクトまたは操作をサポートしていない場合. |
| const [NO_DATA_ALLOWED_ERR](../../aspose.html.dom/domexception/no_data_allowed_err/) | データがサポートされていないノードにデータが指定されている場合. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../aspose.html.dom/domexception/no_modification_allowed_err/) | 変更が許可されていないオブジェクトを変更しようとした場合. |
| const [QUOTA_EXCEEDED_ERR](../../aspose.html.dom/domexception/quota_exceeded_err/) | クォータを超えました。 |
| const [SECURITY_ERR](../../aspose.html.dom/domexception/security_err/) | 操作は安全ではありません. |
| const [SYNTAX_ERR](../../aspose.html.dom/domexception/syntax_err/) | 無効または不正な文字列が指定された場合. |
| const [TIMEOUT_ERR](../../aspose.html.dom/domexception/timeout_err/) | 操作がタイムアウトしました。 |
| const [TYPE_ERR](../../aspose.html.dom/domexception/type_err/) | 指定された型を返すように式を変換できません。 |
| const [TYPE_MISMATCH_ERR](../../aspose.html.dom/domexception/type_mismatch_err/) | オブジェクトの型が、オブジェクトに関連付けられているパラメーターの予想される型と互換性がない場合。 |
| const [URL_MISMATCH_ERR](../../aspose.html.dom/domexception/url_mismatch_err/) | 指定された URL は別の URL と一致しません。 |
| const [VALIDATION_ERR](../../aspose.html.dom/domexception/validation_err/) | insertBefore や removeChild などのメソッドを呼び出すと、Node が「部分的な有効性」に関して無効になる場合、この例外が発生し、操作は実行されません。このコードは [DOM Level 3 Validation] で使用されます。詳細については、この仕様を参照してください。 |
| const [WRONG_DOCUMENT_ERR](../../aspose.html.dom/domexception/wrong_document_err/) | Node が、それを作成したドキュメントとは異なるドキュメントで使用されている場合 (それはそれをサポートしていません). |

### 関連項目

* class [PlatformException](../../aspose.html/platformexception/)
* 名前空間 [Aspose.Html.Dom](../../aspose.html.dom/)
* 組み立て [Aspose.HTML](../../)


