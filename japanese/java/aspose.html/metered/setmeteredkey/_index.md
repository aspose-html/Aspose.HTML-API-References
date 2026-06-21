---
title: "Metered.SetMeteredKey"
second_title: "Aspose.HTML for Java API リファレンス"
description: "メータリングメソッド。メータリングされた公開鍵と秘密鍵を設定します。アプリケーション起動時にメータリングライセンスを購入した場合、この API は通常通り呼び出すだけで十分です。ただし、消費データのアップロードが常に失敗し、24 時間を超えるとライセンスは評価版ステータスに設定されます。そのようなケースを回避するために、ライセンスステータスを定期的に確認し、評価版ステータスであればこの API を再度呼び出してください。"
type: docs

url: /ja/java/com.aspose.html/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

メーター制の公開キーとプライベートキーを設定します。メーター制ライセンスを購入した場合、アプリケーション起動時にこの API を呼び出す必要があり、通常はこれだけで十分です。ただし、使用量データのアップロードが常に失敗し 24 時間を超えると、ライセンスは評価ステータスに設定されます。そのような事態を回避するため、ライセンスステータスを定期的に確認し、評価ステータスである場合は再度この API を呼び出す必要があります。

```java
public void SetMeteredKey(String publicKey, String privateKey)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| publicKey | 文字列 | 公開鍵 |
| privateKey | 文字列 | 秘密鍵 |

### 関連項目

* class [Metered](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
