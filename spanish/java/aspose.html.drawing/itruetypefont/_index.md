---
title: "Interfaz ITrueTypeFont"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "interfaz com.aspose.html.drawing.ITrueTypeFont. Declara métodos para trabajar con fuentes TrueType."
type: docs

url: /es/java/com.aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

Declara métodos para trabajar con fuentes TrueType.

```java
public interface ITrueTypeFont
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getDataSize](../../com.aspose.html.drawing/itruetypefont/datasize/) Devuelve el tamaño de los datos de la fuente en bytes |
| [getFamilyName](../../com.aspose.html.drawing/itruetypefont/familyname/) Obtiene el nombre de la familia de la fuente. |
| [getFullFontName](../../com.aspose.html.drawing/itruetypefont/fullfontname/) Esto debería ser una combinación de "FamilyName" y "SubFamilyName". Excepción: si la fuente es "Regular" según lo indicado en "SubFamilyName", entonces use solo el nombre de familia contenido en "FamilyName". Una excepción a la definición anterior del nombre completo de la fuente es para las cadenas de la plataforma Microsoft para fuentes CFF OpenType: en este caso, la cadena del nombre completo de la fuente debe ser idéntica al FontName PostScript en el índice de nombres CFF. |
| [getSubFamilyName](../../com.aspose.html.drawing/itruetypefont/subfamilyname/) El nombre de subfamilia de la fuente distingue la fuente en un grupo con el mismo nombre de familia de fuente. Se asume que aborda el estilo (cursiva, oblicua) y el peso (ligero, negrita, negro, etc.). Una fuente sin diferencias particulares en peso o estilo (p. ej., peso medio, no cursiva y bit 6 de fsSelection activado) debe tener la cadena "Regular" almacenada en esta posición. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getAscent](../../com.aspose.html.drawing/itruetypefont/getascent/)(float) | Devuelve la ascendente, en puntos. |
| [getData](../../com.aspose.html.drawing/itruetypefont/getdata/)() | Abre el flujo con los datos de la fuente. El llamador es responsable de liberar el flujo. |
| [getDescent](../../com.aspose.html.drawing/itruetypefont/getdescent/)(float) | Devuelve la descendente, en puntos. |

### Ver también

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
