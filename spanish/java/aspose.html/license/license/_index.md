---
title: "Licencia"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Constructor de License. Inicializa una nueva instancia de esta clase"
type: docs

url: /es/java/com.aspose.html/license/license/
---
## License constructor

Inicializa una nueva instancia de esta clase.

```java
public License()
```

## Ejemplos

En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la carpeta que contiene el ensamblado que llama, en la carpeta del ensamblado de entrada y luego en los recursos incrustados del ensamblado que llama.

```java
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

el archivo jar del componente:

```java
License license = new License();
license.setLicense("MyLicense.lic");
```

### Ver también

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
