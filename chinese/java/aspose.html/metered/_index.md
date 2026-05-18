---
title: "Metered 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.Metered 类。提供设置计量密钥的方法。"
type: docs

url: /zh/java/com.aspose.html/metered/
---
## Metered class

提供设置计量密钥的方法。

```java
public class Metered
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Metered](metered/)() | 初始化此类的一个新实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [setMeteredKey](../../com.aspose.html/metered/setmeteredkey/)(String, String) | 设置计量的公钥和私钥。如果您购买了计量许可证，在启动应用程序时应调用此 API，通常这已足够。然而，如果始终未能上传使用数据且超过 24 小时，许可证将被设为评估状态。为避免这种情况，您应定期检查许可证状态，如果处于评估状态，请再次调用此 API。 |
| static [GetConsumptionCredit](../../com.aspose.html/metered/getconsumptioncredit/)() | 获取消耗额度 |
| static [GetConsumptionQuantity](../../com.aspose.html/metered/getconsumptionquantity/)() | 获取消耗文件大小 |
| static [IsMeteredLicensed](../../com.aspose.html/metered/ismeteredlicensed/)() | 检查计量是否已授权 |

## 示例

在此示例中，将尝试设置计量的公钥和私钥

```java
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

组件 jar 文件：

```java
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### 另请参阅

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
