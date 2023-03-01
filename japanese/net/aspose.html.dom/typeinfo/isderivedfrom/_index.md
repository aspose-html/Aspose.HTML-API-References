---
title: TypeInfo.IsDerivedFrom
second_title: Aspose.HTML for .NET API リファレンス
description: TypeInfo 方法. このメソッドは参照型定義 メソッドが呼び出される TypeInfo など と他の型定義 パラメーターとして渡されるもの の間に派生がある場合に戻ります
type: docs
weight: 30
url: /ja/net/aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

このメソッドは、参照型定義 (メソッドが呼び出される TypeInfo など) と他の型定義 (パラメーターとして渡されるもの) の間に派生がある場合に戻ります。

```csharp
public bool IsDerivedFrom(string typeNamespaceArg, string typeNameArg, ulong derivationMethod)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| typeNamespaceArg | String | 他の型定義の名前空間 |
| typeNameArg | String | 他の型定義の名前。 |
| derivationMethod | UInt64 | このインターフェイスで提供される定数のリストで説明されているように、2 つの型の間に適用される派生の型と条件。 |

### 戻り値

ドキュメントのスキーマが DTD であるか、ドキュメントにスキーマが関連付けられていない場合、このメソッドは常に false を返します。ドキュメントのスキーマが XML スキーマの場合、derivation パラメーターに従って参照型定義が他の型定義から派生している場合、メソッドは true になります。パラメーターの値が 0 の場合 (derivationMethod パラメーターのビットが 1 に設定されていない場合)、{base type definition}、{item type definition} の任意の組み合わせを再帰することによって他のタイプ定義に到達できる場合、メソッドは true を返します。 、または参照型定義からの {メンバー型定義}.

### 関連項目

* class [TypeInfo](../)
* 名前空間 [Aspose.Html.Dom](../../typeinfo/)
* 組み立て [Aspose.HTML](../../../)


