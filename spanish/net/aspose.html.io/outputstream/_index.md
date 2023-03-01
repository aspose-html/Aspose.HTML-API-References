---
title: Class OutputStream
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.IO.OutputStream clase. Un flujo sustituto envuelve el flujo de salida real y controla el acceso a él. OutputStream contiene datos de URI que describen la ubicación del flujo de salida.
type: docs
weight: 3750
url: /es/net/aspose.html.io/outputstream/
---
## OutputStream class

Un flujo sustituto envuelve el flujo de salida real y controla el acceso a él. `OutputStream` contiene datos de URI que describen la ubicación del flujo de salida.

```csharp
public class OutputStream : Stream
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [OutputStream](outputstream/)(Stream, string) | Inicializa una nueva instancia del`OutputStream` clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [CanRead](../../aspose.html.io/outputstream/canread/) { get; } | Obtiene un valor que indica si el flujo de salida envuelto admite la lectura. |
| override [CanSeek](../../aspose.html.io/outputstream/canseek/) { get; } | Obtiene un valor que indica si el flujo de salida envuelto admite la búsqueda. |
| override [CanWrite](../../aspose.html.io/outputstream/canwrite/) { get; } | Obtiene un valor que indica si el flujo de salida envuelto admite escritura. |
| override [Length](../../aspose.html.io/outputstream/length/) { get; } | Obtiene la longitud en bytes del flujo de salida envuelto. |
| override [Position](../../aspose.html.io/outputstream/position/) { get; set; } | Obtiene o establece la posición dentro del flujo de salida envuelto. |
| [Uri](../../aspose.html.io/outputstream/uri/) { get; } | Obtiene la URI de la ubicación de transmisión. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Close](../../aspose.html.io/outputstream/close/)() | Cierra el flujo de salida envuelto y el flujo actual. |
| override [Flush](../../aspose.html.io/outputstream/flush/)() | Borra todos los búferes para el flujo de salida empaquetado y hace que los datos almacenados en el búfer se escriban en el dispositivo subyacente. |
| override [Read](../../aspose.html.io/outputstream/read/)(byte[], int, int) | Lee una secuencia de bytes del flujo de salida empaquetado y avanza la posición dentro del flujo según el número de bytes leídos. |
| override [Seek](../../aspose.html.io/outputstream/seek/)(long, SeekOrigin) | Establece la posición dentro del flujo de salida envuelto. |
| override [SetLength](../../aspose.html.io/outputstream/setlength/)(long) | Establece la longitud del flujo de salida envuelto. |
| override [Write](../../aspose.html.io/outputstream/write/)(byte[], int, int) | Escribe una secuencia de bytes en el flujo de salida envuelto y avanza la posición actual dentro de este flujo por el número de bytes escritos. |

### Ver también

* espacio de nombres [Aspose.Html.IO](../../aspose.html.io/)
* asamblea [Aspose.HTML](../../)


