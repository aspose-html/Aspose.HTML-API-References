---
title: "PdfPermissions Enum"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.rendering.pdf.encryption.PdfPermissions enum. Este enum representa los permisos de los usuarios para un pdf"
type: docs

url: /es/java/com.aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

Esta enumeración representa los permisos del usuario para un PDF.

```java
[Flags]
public enum PdfPermissions
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| PrintDocument | `4` | (Manejadores de seguridad de la revisión 2) Imprimir el documento. (Manejadores de seguridad de la revisión 3 o superior) Imprimir el documento (posiblemente no en el nivel de calidad más alto, dependiendo de si PrintingQuality también está configurado). |
| ModifyContent | `8` | Modificar el contenido del documento mediante operaciones distintas a las controladas por ModifyTextAnnotations, FillForm y 11. |
| ExtractContent | `10` | (Manejadores de seguridad de la revisión 2) Copiar o extraer de otro modo texto y gráficos del documento, incluyendo la extracción de texto y gráficos (para apoyar la accesibilidad a usuarios con discapacidades o para otros propósitos). (Manejadores de seguridad de la revisión 3 o superior) Copiar o extraer de otro modo texto y gráficos del documento mediante operaciones distintas a las controladas por ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Agregar o modificar anotaciones de texto, rellenar campos de formulario interactivo y, si ModifyContent también está establecido, crear o modificar campos de formulario interactivo (incluidos los campos de firma). |
| FillForm | `100` | (Manejadores de seguridad de la revisión 3 o superior) Rellenar campos de formulario interactivo existentes (incluidos los campos de firma), incluso si ModifyTextAnnotations está desactivado. |
| ExtractContentWithDisabilities | `200` | (Manejadores de seguridad de la revisión 3 o superior) Extraer texto y gráficos (para apoyar la accesibilidad a usuarios con discapacidades o para otros propósitos). |
| AssembleDocument | `400` | (Manejadores de seguridad de la revisión 3 o superior) Ensamblar el documento (insertar, rotar o eliminar páginas y crear marcadores o miniaturas), incluso si ModifyContent está desactivado. |
| PrintingQuality | `800` | (Manejadores de seguridad de la revisión 3 o superior) Imprimir el documento a una representación a partir de la cual se pueda generar una copia digital fiel del contenido PDF. Cuando este bit está desactivado (y el bit 3 está activado), la impresión se limita a una representación de bajo nivel de la apariencia, posiblemente de calidad degradada. |

### Ver también

* package [com.aspose.html.rendering.pdf.encryption](../../com.aspose.html.rendering.pdf.encryption/)
* package [Aspose.HTML](../../)
