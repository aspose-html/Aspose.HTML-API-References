---
title: "IDocumentCSS interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.css.IDocumentCSS interface. Deze interface vertegenwoordigt een document met een CSS‑weergave."
type: docs

url: /nl/java/com.aspose.html.dom.css/idocumentcss/
---
## IDocumentCSS interface

Deze interface vertegenwoordigt een document met een CSS-weergave.

De getOverrideStyle‑methode biedt een mechanisme waarmee een DOM‑auteur een onmiddellijke wijziging van de stijl van een element kan doorvoeren zonder de expliciet gekoppelde stylesheets van een document of de inline‑stijl van elementen in de stylesheets te wijzigen. Deze stylesheet komt na de auteurs‑stylesheet in het cascade‑algoritme en wordt een override‑stylesheet genoemd. De override‑stylesheet heeft voorrang boven auteurs‑stylesheets. Een "!important"‑declaratie heeft nog steeds voorrang boven een normale declaratie. Override‑, auteur‑ en gebruikers‑stylesheets kunnen allemaal "!important"‑declaraties bevatten. Gebruikers‑"!important"‑regels hebben voorrang boven zowel override‑ als auteur‑"!important"‑regels, en override‑"!important"‑regels hebben voorrang boven auteur‑"!important"‑regels.

De verwachting is dat een instantie van de DocumentCSS‑interface verkregen kan worden door bindingspecifieke cast‑methoden te gebruiken op een instantie van de Document‑interface.

Zie ook de [Document Object Model (DOM) Level 2 Style Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113).

```java
public interface IDocumentCSS : IDocumentStyle
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getOverrideStyle](../../com.aspose.html.dom.css/idocumentcss/getoverridestyle/)(Element, String) | Deze methode wordt gebruikt om de override‑stijl‑declaratie op te halen voor een opgegeven element en een opgegeven pseudo‑element. |

### Zie ook

* interface [IDocumentStyle](../idocumentstyle/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
