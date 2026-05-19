---
title: "FontMatcher.MatchFontFallback"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo FontMatcher. Questo metodo viene chiamato se non è stato trovato alcun font appropriato nelle cartelle di ricerca dei font. Dovrebbe restituire un font TrueType basato su fontMatchingProperties che può renderizzare charCode o null se tale font non è disponibile"
type: docs

url: /it/java/com.aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Questo metodo viene chiamato se non viene trovato alcun font appropriato nelle cartelle di ricerca dei font. Deve restituire un font TrueType basato su *fontMatchingProperties* che può renderizzare *charCode*, oppure `null` se tale font non è disponibile.

```java
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Proprietà del font corrispondente. |
| charCode | UInt32 | Codice del carattere che verrà renderizzato usando il font corrispondente. |

### Valore di ritorno

Un array di byte contenente i dati dei font o `null`.

### Vedi anche

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* package [com.aspose.html.rendering.fonts](../../../com.aspose.html.rendering.fonts/)
* package [Aspose.HTML](../../../)
