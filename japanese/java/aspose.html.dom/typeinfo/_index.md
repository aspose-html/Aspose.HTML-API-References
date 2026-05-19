---
title: "TypeInfo クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.TypeInfo クラス。TypeInfo は、ドキュメントに関連付けられたスキーマで指定された Element または Attr ノードから参照される型を表します"
type: docs

url: /ja/java/com.aspose.html.dom/typeinfo/
---
## TypeInfo class

TypeInfo は、ドキュメントに関連付けられたスキーマで指定された、Element または Attr ノードから参照される型を表します。

```java
public class TypeInfo : DOMObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getTypeName](../../com.aspose.html.dom/typeinfo/typename/) 宣言された型の名前（関連付けられた要素または属性用）を取得します。型が不明な場合は null が返されます。 |
| [getTypeNamespace](../../com.aspose.html.dom/typeinfo/typepackage/) 型パッケージを取得します。関連付けられた要素または属性のために宣言された型のパッケージ、または要素に宣言がなくパッケージ情報が利用できない場合は null が返されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [isDerivedFrom](../../com.aspose.html.dom/typeinfo/isderivedfrom/)(String, String, ulong) | このメソッドは、参照型定義（このメソッドが呼び出されている TypeInfo）と、パラメータとして渡された他の型定義との間に派生関係があるかどうかを返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [DERIVATION_EXTENSION](../../com.aspose.html.dom/typeinfo/derivation_extension/) | ドキュメントのスキーマが XML スキーマ [XML Schema Part 1] の場合、この定数は拡張による派生を表します。 |
| const [DERIVATION_LIST](../../com.aspose.html.dom/typeinfo/derivation_list/) | ドキュメントのスキーマが XML スキーマ [XML Schema Part 1] の場合、この定数はリストを表します。 |
| const [DERIVATION_RESTRICTION](../../com.aspose.html.dom/typeinfo/derivation_restriction/) | ドキュメントのスキーマが XML スキーマ [XML Schema Part 1] の場合、この定数は、複合型が関与する場合は制限による派生、単純型が関与する場合は制限を表します。 |
| const [DERIVATION_UNION](../../com.aspose.html.dom/typeinfo/derivation_union/) | ドキュメントのスキーマが XML スキーマ [XML Schema Part 1] の場合、この定数は単純型が関与する場合の union を表します。 |

### 関連項目

* class [DOMObject](../domobject/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
