---
title: OutputStream.Read
second_title: Referencia de API de Aspose.HTML para .NET
description: OutputStream método. Lee una secuencia de bytes del flujo de salida empaquetado y avanza la posición dentro del flujo según el número de bytes leídos.
type: docs
weight: 100
url: /es/net/aspose.html.io/outputstream/read/
---
## OutputStream.Read method

Lee una secuencia de bytes del flujo de salida empaquetado y avanza la posición dentro del flujo según el número de bytes leídos.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| buffer | Byte[] | Una matriz de bytes. Cuando este método regresa, el búfer contiene la matriz de bytes especificada con los valores entre desplazamiento y (desplazamiento + recuento - 1) reemplazados por los bytes leídos del flujo de salida envuelto. |
| offset | Int32 | El desplazamiento de bytes de base cero en el búfer en el que comenzar a almacenar los datos read del flujo de salida empaquetado. |
| count | Int32 | El número máximo de bytes que se leerán del flujo de salida empaquetado. |

### Valor_devuelto

El número total de bytes leídos en el búfer. Puede ser menor que el número de bytes solicitados si esa cantidad de bytes no está disponible actualmente, o cero (0) si se alcanzó el final de la transmisión.

### Ver también

* class [OutputStream](../)
* espacio de nombres [Aspose.Html.IO](../../outputstream/)
* asamblea [Aspose.HTML](../../../)


