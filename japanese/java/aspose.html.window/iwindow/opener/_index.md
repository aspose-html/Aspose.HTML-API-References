---
title: "IWindow.Opener"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IWindow プロパティ。Window オブジェクト上の opener IDL 属性は、取得時に現在のブラウジングコンテキストが作成された元のブラウジングコンテキスト（opener ブラウジングコンテキスト）が存在し、かつ利用可能で、かつ現在のブラウジングコンテキストがその opener を放棄していない場合、該当する WindowProxy オブジェクトを返す必要があります。そうでない場合は null を返します。設定時に新しい値が null の場合、現在のブラウジングコンテキストはその opener を放棄しなければなりません。新しい値がそれ以外の場合、ユーザーエージェントは Window オブジェクトの DefineOwnProperty 内部メソッドを呼び出し、プロパティ名 opener をプロパティキーとして渡し、プロパティ記述子 { Value: value, Writable: true, Enumerable: true, Configurable: true } を使用します。ここで value は新しい値です。"
type: docs

url: /ja/java/com.aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

Window オブジェクト上の opener IDL 属性は、取得時に現在のブラウジングコンテキストが作成された元のブラウジングコンテキスト（その opener ブラウジングコンテキスト）が存在し、かつ利用可能で、かつ現在のブラウジングコンテキストがその opener を放棄していない場合、該当する WindowProxy オブジェクトを返す必要があります。そうでない場合は null を返します。設定時に新しい値が null の場合、現在のブラウジングコンテキストはその opener を放棄しなければなりません。新しい値がそれ以外の場合、ユーザーエージェントは Window オブジェクトの [[DefineOwnProperty]] 内部メソッドを呼び出し、プロパティ名 "opener" をプロパティキーとして渡し、プロパティ記述子 { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } を使用します。ここで value は新しい値です。

```java
public IWindow Opener { get; }
```

### Property Value

openerです。

### 関連項目

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
