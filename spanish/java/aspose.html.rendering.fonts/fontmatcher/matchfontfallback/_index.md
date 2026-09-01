---
title: "FontMatcher.MatchFontFallback"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método FontMatcher. Este método se llama si no se encuentra una fuente adecuada en las carpetas de búsqueda de fuentes. Debe devolver una fuente TrueType basada en fontMatchingProperties que pueda renderizar charCode o null si dicha fuente no está disponible"
type: docs

url: /es/java/com.aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Este método se llama si no se encuentra una fuente adecuada en las carpetas de búsqueda de fuentes. Debe devolver una fuente de tipo verdadero basada en *fontMatchingProperties* que pueda renderizar *charCode*, o `null` si dicha fuente no está disponible.

```java
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Propiedades de la fuente coincidente. |
| charCode | UInt32 | Código del carácter que se renderizará usando la fuente coincidente. |

### Valor devuelto

Una matriz de bytes que contiene los datos de las fuentes o `null`.

### Ver también

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* package [com.aspose.html.rendering.fonts](../../../com.aspose.html.rendering.fonts/)
* package [Aspose.HTML](../../../)
