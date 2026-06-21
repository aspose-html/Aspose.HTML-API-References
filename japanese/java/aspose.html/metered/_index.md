---
title: "Metered クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.Metered クラス。メーターキーを設定するメソッドを提供します。"
type: docs

url: /ja/java/com.aspose.html/metered/
---
## Metered class

メーターキーを設定するためのメソッドを提供します。

```java
public class Metered
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Metered](metered/)() | このクラスの新しいインスタンスを初期化します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [setMeteredKey](../../com.aspose.html/metered/setmeteredkey/)(String, String) | メーター制の公開キーとプライベートキーを設定します。メーター制ライセンスを購入した場合、アプリケーション起動時にこの API を呼び出す必要があり、通常はこれだけで十分です。ただし、使用量データのアップロードが常に失敗し 24 時間を超えると、ライセンスは評価ステータスに設定されます。そのような事態を回避するため、ライセンスステータスを定期的に確認し、評価ステータスである場合は再度この API を呼び出す必要があります。 |
| static [GetConsumptionCredit](../../com.aspose.html/metered/getconsumptioncredit/)() | 使用量クレジットを取得します |
| static [GetConsumptionQuantity](../../com.aspose.html/metered/getconsumptionquantity/)() | 使用量ファイルサイズを取得します |
| static [IsMeteredLicensed](../../com.aspose.html/metered/ismeteredlicensed/)() | メーターがライセンスされているか確認してください |

## サンプル

この例では、メーターの公開鍵と秘密鍵を設定しようとします

```java
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

コンポーネントの jar ファイル:

```java
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### 関連項目

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
