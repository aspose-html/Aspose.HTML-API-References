---
title: License.License
second_title: Referencia de API de Aspose.HTML para .NET
description: License constructor. Inicializa una nueva instancia de esta clase.
type: docs
weight: 10
url: /es/net/aspose.html/license/license/
---
## License constructor

Inicializa una nueva instancia de esta clase.

```csharp
public License()
```

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

* class [License](../)
* espacio de nombres [Aspose.Html](../../license/)
* asamblea [Aspose.HTML](../../../)


