---
title: Metered Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Metered class. Provides methods to set metered key
type: docs
weight: 4030
url: /net/aspose.html/metered/
---
## Metered class

Provides methods to set metered key.

```csharp
public class Metered
```

## Constructors

| Name | Description |
| --- | --- |
| [Metered](metered/)() | Initializes a new instance of this class. |

## Methods

| Name | Description |
| --- | --- |
| [SetMeteredKey](../../aspose.html/metered/setmeteredkey/)(*string, string*) | Sets metered public and private key. If you purchase metered license, when start application, this API should be called, normally, this is enough. However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again. |
| static [GetConsumptionCredit](../../aspose.html/metered/getconsumptioncredit/)() | Gets consumption credit |
| static [GetConsumptionQuantity](../../aspose.html/metered/getconsumptionquantity/)() | Gets consumption file size |
| static [IsMeteredLicensed](../../aspose.html/metered/ismeteredlicensed/)() | Check whether metered is licensed |

## Examples

In this example, an attempt will be made to set metered public and private key

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

the component jar file:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### See Also

* namespace [Aspose.Html](../../aspose.html/)
* assembly [Aspose.HTML](../../)
