---
title: "Clase Metered"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.Metered. Proporciona métodos para establecer la clave medida"
type: docs

url: /es/java/com.aspose.html/metered/
---
## Metered class

Proporciona métodos para establecer la clave medida.

```java
public class Metered
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Metered](metered/)() | Inicializa una nueva instancia de esta clase. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [setMeteredKey](../../com.aspose.html/metered/setmeteredkey/)(String, String) | Establece la clave pública y privada medida. Si adquiere una licencia medida, al iniciar la aplicación, debe llamarse a esta API; normalmente, eso es suficiente. Sin embargo, si siempre falla la carga de datos de consumo y supera las 24 horas, la licencia se establecerá en estado de evaluación; para evitar este caso, debe comprobar regularmente el estado de la licencia y, si está en estado de evaluación, llamar a esta API nuevamente. |
| static [GetConsumptionCredit](../../com.aspose.html/metered/getconsumptioncredit/)() | Obtiene el crédito de consumo |
| static [GetConsumptionQuantity](../../com.aspose.html/metered/getconsumptionquantity/)() | Obtiene el tamaño del archivo de consumo |
| static [IsMeteredLicensed](../../com.aspose.html/metered/ismeteredlicensed/)() | Verifique si metered está licenciado |

## Ejemplos

En este ejemplo, se intentará establecer la clave pública y privada de metered

```java
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

el archivo jar del componente:

```java
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Ver también

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
