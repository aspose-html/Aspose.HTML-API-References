---
title: "License.SetLicense"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método License. Licencia el componente"
type: docs

url: /es/java/com.aspose.html/license/setlicense/
---
## SetLicense(String) {#setlicense_1}

Licencia el componente.

```java
public void SetLicense(String licenseName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| licenseName | Cadena | Puede ser un nombre de archivo completo o corto o el nombre de un recurso incrustado. Use una cadena vacía para cambiar al modo de evaluación. |

## Observaciones

Intenta encontrar la licencia en las siguientes ubicaciones:

1. Ruta explícita.

2. La carpeta que contiene el ensamblado del componente Aspose.

3. La carpeta que contiene el ensamblado que llama el cliente.

4. La carpeta que contiene el ensamblado de entrada (inicio).

5. Un recurso incrustado en el ensamblado que llama el cliente.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Ruta explícita.

2. Un recurso incrustado en el ensamblado que llama el cliente.

2. La carpeta que contiene el archivo JAR del componente Aspose.

3. La carpeta que contiene el archivo JAR que llama el cliente.

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

---

## SetLicense(Stream) {#setlicense}

Licencia el componente.

```java
public void SetLicense(Stream stream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Stream | Un flujo que contiene la licencia. |

## Observaciones

Utilice este método para cargar una licencia desde un flujo.

## Ejemplos

```java
[C#]

License license = new License();
license.SetLicense(myStream);
```

### Ver también

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
