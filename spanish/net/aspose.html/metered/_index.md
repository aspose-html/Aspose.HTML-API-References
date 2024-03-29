---
title: Class Metered
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Metered clase. Proporciona métodos para configurar la clave medida.
type: docs
weight: 3830
url: /es/net/aspose.html/metered/
---
## Metered class

Proporciona métodos para configurar la clave medida.

```csharp
public class Metered
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Metered](metered/)() | Inicializa una nueva instancia de esta clase. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SetMeteredKey](../../aspose.html/metered/setmeteredkey/)(string, string) | Establece la clave pública y privada medidas. Si compra una licencia medida, cuando inicie la aplicación, esta API debe llamarse, normalmente, esto es suficiente. Sin embargo, si siempre falla al cargar los datos de consumo y excede las 24 horas, la licencia se establecerá en estado de evaluación, para evitar tal caso, debe verificar regularmente el estado de la licencia, si es el estado de evaluación, llame a esta API nuevamente. |
| static [GetConsumptionCredit](../../aspose.html/metered/getconsumptioncredit/)() | Obtiene crédito de consumo |
| static [GetConsumptionQuantity](../../aspose.html/metered/getconsumptionquantity/)() | Obtiene el tamaño del archivo de consumo |

### Ejemplos

En este ejemplo, se intentará establecer una clave pública y privada medidas

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

el archivo jar del componente:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Ver también

* espacio de nombres [Aspose.Html](../../aspose.html/)
* asamblea [Aspose.HTML](../../)


