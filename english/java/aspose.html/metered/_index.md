---
title: Metered Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Metered class. Provides methods to set metered key
type: docs
weight: 3850
url: /java/com.aspose.html/metered/
---
## Metered class

Provides methods to set metered key.

```java
public class Metered
```

## Constructors

| Name | Description |
| --- | --- |
| [Metered](metered/)() | Initializes a new instance of this class. |

## Methods

| Name | Description |
| --- | --- |
| [setMeteredKey](../../com.aspose.html/metered/setmeteredkey/)(String, String) | Sets metered public and private key. If you purchase metered license, when start application, this API should be called, normally, this is enough. However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again. |
| static [GetConsumptionCredit](../../com.aspose.html/metered/getconsumptioncredit/)() | Gets consumption credit |
| static [GetConsumptionQuantity](../../com.aspose.html/metered/getconsumptionquantity/)() | Gets consumption file size |

## Examples

In this example, an attempt will be made to set metered public and private key

```java
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

the component jar file:

```java
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### See Also

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
