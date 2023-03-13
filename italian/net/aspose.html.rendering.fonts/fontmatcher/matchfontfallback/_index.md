---
title: FontMatcher.MatchFontFallback
second_title: Aspose.HTML per riferimento API .NET
description: FontMatcher metodo. Questo metodo viene chiamato se non viene trovato alcun carattere appropriato nelle cartelle di ricerca dei caratteri. Dovrebbe restituire un carattere true type basato sulfontMatchingProperties che può renderecharCode  Onullo se tale font non è disponibile.
type: docs
weight: 10
url: /it/net/aspose.html.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Questo metodo viene chiamato se non viene trovato alcun carattere appropriato nelle cartelle di ricerca dei caratteri. Dovrebbe restituire un carattere true type basato sul*fontMatchingProperties* che può rendere*charCode* , O`nullo` se tale font non è disponibile.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Proprietà del carattere corrispondente. |
| charCode | UInt32 | Codice del carattere che verrà reso utilizzando il font corrispondente. |

### Valore di ritorno

Un array di byte contenente i dati dei caratteri o`nullo`.

### Guarda anche

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* spazio dei nomi [Aspose.Html.Rendering.Fonts](../../fontmatcher/)
* assemblea [Aspose.HTML](../../../)


