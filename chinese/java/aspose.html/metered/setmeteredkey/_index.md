---
title: "Metered.SetMeteredKey"
second_title: "Aspose.HTML for Java API 参考"
description: "计量方法。设置计量的公钥和私钥。如果在启动应用程序时购买计量许可证，应正常调用此 API，这已足够。然而，如果始终无法上传消费数据且超过 24 小时，许可证将被设置为评估状态，为避免此情况，应定期检查许可证状态；如果是评估状态，请再次调用此 API。"
type: docs

url: /zh/java/com.aspose.html/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

设置计量的公钥和私钥。如果您购买了计量许可证，在启动应用程序时应调用此 API，通常这已足够。然而，如果始终未能上传使用数据且超过 24 小时，许可证将被设为评估状态。为避免这种情况，您应定期检查许可证状态，如果处于评估状态，请再次调用此 API。

```java
public void SetMeteredKey(String publicKey, String privateKey)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| publicKey | String | 公钥 |
| privateKey | String | 私钥 |

### 另请参阅

* class [Metered](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
