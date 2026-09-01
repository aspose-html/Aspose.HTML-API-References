---
title: "IWindow.Opener"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IWindow プロパティ。Window オブジェクト上の opener IDL 属性を取得すると、現在の閲覧コンテキストが作成された元の閲覧コンテキスト（opener 閲覧コンテキスト）が存在し、かつ利用可能で、かつ現在の閲覧コンテキストがその opener を放棄していない場合は、その WindowProxy オブジェクトを返します。そうでなければ null を返します。設定時に新しい値が null の場合、現在の閲覧コンテキストはその opener を放棄しなければなりません。新しい値がそれ以外の場合、ユーザーエージェントは Window オブジェクトの [[DefineOwnProperty]] 内部メソッドを呼び出し、プロパティ名 \"opener\" をプロパティキーとして、プロパティ記述子 { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } を渡し、value は新しい値となります。"
type: docs

url: /ja/java/com.aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

opener IDL 属性は、Window オブジェクトに対して、取得時に現在の閲覧コンテキストが作成された元の閲覧コンテキスト（その opener 閲覧コンテキスト）が存在し、利用可能で、かつ現在の閲覧コンテキストがその opener を放棄していない場合にその WindowProxy オブジェクトを返します。そうでなければ null を返します。設定時に新しい値が null の場合、現在の閲覧コンテキストは opener を放棄しなければなりません。新しい値がそれ以外の場合、ユーザーエージェントは Window オブジェクトの [[DefineOwnProperty]] 内部メソッドを呼び出し、プロパティ名 "opener" をプロパティキーとして、プロパティ記述子 { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } を渡し、value は新しい値です。

```java
public IWindow Opener { get; }
```

### Property Value

オープナーです。

### 関連項目

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
