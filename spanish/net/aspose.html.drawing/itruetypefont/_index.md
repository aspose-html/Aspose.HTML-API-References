---
title: Interface ITrueTypeFont
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Drawing.ITrueTypeFont interfaz. Declara métodos para trabajar con fuentes TrueType.
type: docs
weight: 2760
url: /es/net/aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

Declara métodos para trabajar con fuentes TrueType.

```csharp
public interface ITrueTypeFont
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DataSize](../../aspose.html.drawing/itruetypefont/datasize/) { get; } | Devuelve el tamaño de los datos de fuente en bytes |
| [FamilyName](../../aspose.html.drawing/itruetypefont/familyname/) { get; } | Obtener el nombre de la familia de fuentes. |
| [FullFontName](../../aspose.html.drawing/itruetypefont/fullfontname/) { get; } | Debe ser una combinación de "FamilyName" y "SubFamilyName". Excepción: si la fuente es "Regular" como se indica en "SubFamilyName", use solo el nombre de familia contenido en "FamilyName". Una excepción a la definición anterior de nombre de fuente completo es para las cadenas de la plataforma Microsoft para fuentes CFF OpenType: en este caso, la cadena de nombre de fuente completo debe ser idéntica a PostScript FontName en CFF Name INDEX. |
| [SubFamilyName](../../aspose.html.drawing/itruetypefont/subfamilyname/) { get; } | El nombre de la subfamilia de fuentes distingue la fuente en un grupo con el mismo nombre de familia de fuentes. Se supone que se refiere al estilo (cursiva, oblicua) y al peso (claro, negrita, negro, etc.). Una fuente sin diferencias particulares en peso o estilo (por ejemplo, peso medio, no cursiva y fsSelection bit 6 establecido) debe tener la cadena "Regular" almacenada en esta posición. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetAscent](../../aspose.html.drawing/itruetypefont/getascent/)(float) | Devuelve el ascenso, en puntos. |
| [GetData](../../aspose.html.drawing/itruetypefont/getdata/)() | Abre la transmisión con los datos de la fuente. La persona que llama es responsable de desechar la transmisión. |
| [GetDescent](../../aspose.html.drawing/itruetypefont/getdescent/)(float) | Devuelve la bajada, en puntos. |

### Ver también

* espacio de nombres [Aspose.Html.Drawing](../../aspose.html.drawing/)
* asamblea [Aspose.HTML](../../)


