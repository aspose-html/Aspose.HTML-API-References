---
title: "TypeInfo.IsDerivedFrom"
second_title: "Aspose.HTML for Java API リファレンス"
description: "TypeInfo メソッド。このメソッドは、呼び出し元の TypeInfo（参照型定義）とパラメータとして渡された他の型定義との間に派生関係があるかどうかを返します。"
type: docs

url: /ja/java/com.aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

このメソッドは、参照型定義（このメソッドが呼び出されている TypeInfo）と、パラメータとして渡された他の型定義との間に派生関係があるかどうかを返します。

```java
public bool IsDerivedFrom(String typeNamespaceArg, String typeNameArg, ulong derivationMethod)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| typeNamespaceArg | 文字列 | 他の型定義のパッケージ |
| typeNameArg | 文字列 | 他の型定義の名前。 |
| derivationMethod | UInt64 | このインターフェイスで提供される定数リストに記載された、2 つの型間に適用される派生の種類と条件。 |

### 戻り値

ドキュメントのスキーマが DTD であるか、スキーマが関連付けられていない場合、このメソッドは常に false を返します。ドキュメントのスキーマが XML Schema の場合、参照型定義が派生パラメータに従って他の型定義から派生しているときに true を返します。パラメータの値が 0（derivationMethod パラメータでビットが 1 に設定されていない）である場合、参照型定義から {base type definition}、{item type definition}、または {member type definitions} の任意の組み合わせを再帰的にたどって他の型定義に到達できれば true を返します。

### 関連項目

* class [TypeInfo](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
