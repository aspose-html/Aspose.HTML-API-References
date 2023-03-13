---
title: FontMatcher.MatchFontFallback
second_title: Referencia de API de Aspose.HTML para .NET
description: FontMatcher método. Se llama a este método si no se encuentra una fuente adecuada en las carpetas de búsqueda de fuentes. Debería devolver una fuente de tipo verdadero según elfontMatchingProperties que puede representarcharCode  onulo si dicha fuente no está disponible.
type: docs
weight: 10
url: /es/net/aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Se llama a este método si no se encuentra una fuente adecuada en las carpetas de búsqueda de fuentes. Debería devolver una fuente de tipo verdadero según el*fontMatchingProperties* que puede representar*charCode* , o`nulo` si dicha fuente no está disponible.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Propiedades de la fuente coincidente. |
| charCode | UInt32 | Código del carácter que se representará utilizando la fuente coincidente. |

### Valor_devuelto

Una matriz de bytes que contiene los datos de las fuentes o`nulo`.

### Ver también

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* espacio de nombres [Aspose.Html.Rendering.Fonts](../../fontmatcher/)
* asamblea [Aspose.HTML](../../../)


