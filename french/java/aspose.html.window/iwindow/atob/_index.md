---
title: "IWindow.Atob"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode IWindow. Prend les données d'entrée sous la forme d'une chaîne Unicode contenant des données binaires encodées en base64, les décode et renvoie une chaîne composée de caractères dans la plage U0000 à U00FF, chaque caractère représentant un octet binaire avec des valeurs 0x00 à 0xFF respectivement correspondant à ces données binaires."
type: docs

url: /fr/java/com.aspose.html.window/iwindow/atob/
---
## IWindow.Atob method

Prend les données d'entrée, sous la forme d'une chaîne Unicode contenant des données binaires encodées en base64, les décode, et renvoie une chaîne composée de caractères dans la plage U+0000 à U+00FF, chaque caractère représentant un octet binaire avec des valeurs de 0x00 à 0xFF respectivement, correspondant à ces données binaires.

```java
public String Atob(String data)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| données | String | La chaîne Unicode contenant des données binaires encodées en base64 |

### Valeur de retour

La chaîne composée de caractères dans la plage U+0000 à U+00FF

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Lance une exception DOMException "InvalidCharacterError" si la chaîne d'entrée n'est pas des données base64 valides. |

### Voir aussi

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
