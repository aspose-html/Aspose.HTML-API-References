---
title: Class License
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.License clase. Proporciona métodos para licenciar el componente.
type: docs
weight: 3810
url: /es/net/aspose.html/license/
---
## License class

Proporciona métodos para licenciar el componente.

```csharp
public class License
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [License](license/)() | Inicializa una nueva instancia de esta clase. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SetLicense](../../aspose.html/license/setlicense/#setlicense)(Stream) | Licencia el componente. |
| [SetLicense](../../aspose.html/license/setlicense/#setlicense_1)(string) | Licencia el componente. |

### Ejemplos

En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene  el componente, en la carpeta que contiene el ensamblado que llama, en la carpeta del ensamblado de entrada y luego en los recursos incrustados del ensamblado que llama.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

el archivo jar del componente:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Ver también

* espacio de nombres [Aspose.Html](../../aspose.html/)
* asamblea [Aspose.HTML](../../)


