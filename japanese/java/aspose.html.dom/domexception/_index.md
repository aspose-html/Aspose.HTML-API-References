---
title: "DOMException クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.DOMException クラス。DOMException インターフェイスは、メソッド呼び出しや Web API のプロパティアクセスの結果として発生する例外と呼ばれる異常事象を表します。これは、Web API におけるエラー状態の記述方法そのものです。"
type: docs

url: /ja/java/com.aspose.html.dom/domexception/
---
## DOMException class

DOMException インターフェイスは、Web API のメソッド呼び出しやプロパティアクセスの結果として発生する異常事象（例外と呼ばれる）を表します。これは、Web API におけるエラー状態が記述される基本的な方法です。

```java
public class DOMException : PlatformException
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [DOMException](domexception/#constructor)(String) | `DOMException` クラスの新しいインスタンスを初期化します。 |
| [DOMException](domexception/#constructor_1)(String, String) | `DOMException` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getCode](../../com.aspose.html.dom/domexception/code/) エラーコード定数のいずれかを含む値、または一致するものがなければ 0 を返します。このフィールドは歴史的な理由で使用されます。 |
| [getMessage](../../com.aspose.html.dom/domexception/message/) 指定されたエラー名に関連付けられたメッセージまたは説明を表す文字列を返します。 |
| [getName](../../com.aspose.html.dom/domexception/name/) エラー名に関連付けられた文字列のうちの一つを含む文字列を返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [ABORT_ERR](../../com.aspose.html.dom/domexception/abort_err/) | 操作は中止されました。 |
| const [DATA_CLONE_ERR](../../com.aspose.html.dom/domexception/data_clone_err/) | オブジェクトはクローンできません。 |
| const [DOMSTRING_SIZE_ERR](../../com.aspose.html.dom/domexception/domString_size_err/) | 指定されたテキスト範囲が DOMString に収まらない場合。 |
| const [HIERARCHY_REQUEST_ERR](../../com.aspose.html.dom/domexception/hierarchy_request_err/) | ノードが所属すべきでない場所に挿入された場合。 |
| const [INDEX_SIZE_ERR](../../com.aspose.html.dom/domexception/index_size_err/) | インデックスまたはサイズが負の値、または許容範囲を超えている場合。 |
| const [INUSE_ATTRIBUTE_ERR](../../com.aspose.html.dom/domexception/inuse_attribute_err/) | 既に他の場所で使用されている属性を追加しようとした場合。 |
| const [INVALID_ACCESS_ERR](../../com.aspose.html.dom/domexception/invalid_access_err/) | 基礎オブジェクトがパラメータまたは操作をサポートしていない場合。 |
| const [INVALID_CHARACTER_ERR](../../com.aspose.html.dom/domexception/invalid_character_err/) | XML 名などで無効または不正な文字が指定された場合。 |
| const [INVALID_EXPRESSION_ERR](../../com.aspose.html.dom/domexception/invalid_expression_err/) | 式に構文エラーがある、または特定の XPathEvaluator の規則に従った合法的な式でない、あるいはこの実装がサポートしていない特殊な拡張関数や変数を含んでいる場合。 |
| const [INVALID_MODIFICATION_ERR](../../com.aspose.html.dom/domexception/invalid_modification_err/) | 基礎オブジェクトのタイプを変更しようとした場合。 |
| const [INVALID_NODE_TYPE_ERR](../../com.aspose.html.dom/domexception/invalid_node_type_err/) | 提供されたノードが正しくない、またはこの操作に対して不適切な先祖ノードを持っている場合。 |
| const [INVALID_STATE_ERR](../../com.aspose.html.dom/domexception/invalid_state_err/) | オブジェクトが使用できない、またはもはや使用できない状態で使用しようとした場合。 |
| const [NAMESPACE_ERR](../../com.aspose.html.dom/domexception/package_err/) | パッケージに関して不正な方法でオブジェクトを作成または変更しようとした場合。 |
| const [NETWORK_ERR](../../com.aspose.html.dom/domexception/network_err/) | ネットワークエラーが発生しました。 |
| const [NOT_FOUND_ERR](../../com.aspose.html.dom/domexception/not_found_err/) | ノードが存在しないコンテキストでノードを参照しようとした場合。 |
| const [NOT_SUPPORTED_ERR](../../com.aspose.html.dom/domexception/not_supported_err/) | 実装が要求されたオブジェクトまたは操作のタイプをサポートしていない場合。 |
| const [NO_DATA_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_data_allowed_err/) | データをサポートしないノードにデータが指定された場合。 |
| const [NO_MODIFICATION_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_modification_allowed_err/) | 変更が許可されていないオブジェクトを変更しようとした場合。 |
| const [QUOTA_EXCEEDED_ERR](../../com.aspose.html.dom/domexception/quota_exceeded_err/) | クォータが超過しました。 |
| const [SECURITY_ERR](../../com.aspose.html.dom/domexception/security_err/) | 操作が安全ではありません。 |
| const [SYNTAX_ERR](../../com.aspose.html.dom/domexception/syntax_err/) | 無効または不正な文字列が指定された場合。 |
| const [TIMEOUT_ERR](../../com.aspose.html.dom/domexception/timeout_err/) | 操作がタイムアウトしました。 |
| const [TYPE_ERR](../../com.aspose.html.dom/domexception/type_err/) | 式を指定された型で返すように変換できません。 |
| const [TYPE_MISMATCH_ERR](../../com.aspose.html.dom/domexception/type_mismatch_err/) | オブジェクトの型が、そのオブジェクトに関連付けられたパラメータの期待型と互換性がない場合。 |
| const [URL_MISMATCH_ERR](../../com.aspose.html.dom/domexception/url_mismatch_err/) | 指定されたURLが別のURLと一致しません。 |
| const [VALIDATION_ERR](../../com.aspose.html.dom/domexception/validation_err/) | insertBefore や removeChild のようなメソッド呼び出しが "partial validity" に関してノードを無効にする場合、この例外が発生し、操作は実行されません。このコードは [DOM Level 3 Validation] で使用されています。詳細はこの仕様を参照してください。 |
| const [WRONG_DOCUMENT_ERR](../../com.aspose.html.dom/domexception/wrong_document_err/) | ノードが作成元とは異なるドキュメントで使用された場合（そのドキュメントがサポートしていない場合）。 |

### 関連項目

* class [PlatformException](../../com.aspose.html/platformexception/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
