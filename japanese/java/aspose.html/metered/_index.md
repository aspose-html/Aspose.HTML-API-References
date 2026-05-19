---
title: "Metered クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.Metered クラス。メータ付きキーを設定するメソッドを提供します。"
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
| [setMeteredKey](../../com.aspose.html/metered/setmeteredkey/)(String, String) | メータ付きの公開キーとプライベートキーを設定します。メータ付きライセンスを購入した場合、アプリケーション起動時にこの API を呼び出す必要があり、通常はこれだけで十分です。ただし、使用量データのアップロードが常に失敗し 24 時間を超えると、ライセンスは評価版ステータスに設定されます。そのような事態を防ぐため、ライセンスステータスを定期的に確認し、評価版ステータスである場合は再度この API を呼び出してください。 |
| static [GetConsumptionCredit](../../com.aspose.html/metered/getconsumptioncredit/)() | 使用量クレジットを取得します |
| static [GetConsumptionQuantity](../../com.aspose.html/metered/getconsumptionquantity/)() | 使用量ファイルサイズを取得します |
| static [IsMeteredLicensed](../../com.aspose.html/metered/ismeteredlicensed/)() | メーターがライセンスされているか確認する |

## 例

この例では、メーターの公開鍵と秘密鍵を設定しようとします

```java
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

コンポーネントの JAR ファイル:

```java
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### 関連項目

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
