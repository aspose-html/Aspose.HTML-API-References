---
title: "Clase License"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.License class. Proporciona métodos para licenciar el componente"
type: docs

url: /es/java/com.aspose.html/license/
---
## License class

Proporciona métodos para licenciar el componente.

```java
public class License
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [License](license/)() | Inicializa una nueva instancia de esta clase. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense)(Stream) | Licencia el componente. |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense_1)(String) | Licencia el componente. |

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

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
