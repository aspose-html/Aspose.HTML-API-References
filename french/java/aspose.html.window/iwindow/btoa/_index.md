---
title: "IWindow.Btoa"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode IWindow. Prend les données d'entrée sous la forme d'une chaîne Unicode contenant uniquement des caractères dans la plage U0000 à U00FF, chaque caractère représentant un octet binaire avec des valeurs 0x00 à 0xFF respectivement, et les convertit en leur représentation base64 qu'elle renvoie."
type: docs

url: /fr/java/com.aspose.html.window/iwindow/btoa/
---
## IWindow.Btoa method

Prend les données d'entrée, sous forme d'une chaîne Unicode ne contenant que des caractères dans la plage U+0000 à U+00FF, chaque caractère représentant un octet binaire avec des valeurs de 0x00 à 0xFF respectivement, et les convertit en leur représentation base64, qu'elle renvoie.

```java
public String Btoa(String data)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| données | String | La chaîne Unicode contenant uniquement des caractères dans la plage U+0000 à U+00FF. |

### Valeur de retour

La chaîne base64.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Lance une exception DOMException "InvalidCharacterError" si la chaîne d'entrée contient des caractères hors de la plage. |

### Voir aussi

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
