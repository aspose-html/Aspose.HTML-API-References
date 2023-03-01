---
title: Class TypeInfo
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.TypeInfo クラス. TypeInfo はドキュメントに関連付けられたスキーマで指定されたElement または Attr ノードから参照される型を表します
type: docs
weight: 2530
url: /ja/net/aspose.html.dom/typeinfo/
---
## TypeInfo class

TypeInfo は、ドキュメントに関連付けられたスキーマで指定された、Element または Attr ノードから参照される型を表します。

```csharp
public class TypeInfo : DOMObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [TypeName](../../aspose.html.dom/typeinfo/typename/) { get; } | 関連付けられた要素または属性に対して宣言された型の名前、または不明な場合は null。 |
| [TypeNamespace](../../aspose.html.dom/typeinfo/typenamespace/) { get; } | 型の名前空間を取得します。関連付けられた要素または属性に対して宣言された型の名前空間、または要素に宣言がない場合、または名前空間情報が利用できない場合は null です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType. |
| [IsDerivedFrom](../../aspose.html.dom/typeinfo/isderivedfrom/)(string, string, ulong) | このメソッドは、参照型定義 (メソッドが呼び出される TypeInfo など) と他の型定義 (パラメーターとして渡されるもの) の間に派生がある場合に戻ります。 |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [DERIVATION_EXTENSION](../../aspose.html.dom/typeinfo/derivation_extension/) | ドキュメントのスキーマが XML スキーマ [XML スキーマ パート 1] の場合、この定数は拡張による派生を表します。 |
| const [DERIVATION_LIST](../../aspose.html.dom/typeinfo/derivation_list/) | ドキュメントのスキーマが XML スキーマ [XML スキーマ パート 1] の場合、この定数はリストを表します。 |
| const [DERIVATION_RESTRICTION](../../aspose.html.dom/typeinfo/derivation_restriction/) | ドキュメントのスキーマが XML スキーマ [XML スキーマ パート 1] の場合、この定数は、複合型が含まれる場合は制限による派生を表し、単純型が含まれる場合は制限を表します。 |
| const [DERIVATION_UNION](../../aspose.html.dom/typeinfo/derivation_union/) | ドキュメントのスキーマが XML スキーマ [XML スキーマ パート 1] である場合、単純型が含まれている場合、この定数は共用体を表します。 |

### 関連項目

* class [DOMObject](../domobject/)
* 名前空間 [Aspose.Html.Dom](../../aspose.html.dom/)
* 組み立て [Aspose.HTML](../../)


