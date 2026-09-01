---
title: "SVGGraphicsElement.GetScreenCTM"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode SVGGraphicsElement. Retourne la matrice de transformation à partir des unités utilisateur actuelles, c’est‑à‑dire après l’application de l’attribut transform le cas échéant, vers la notice du pixel de l’agent utilisateur parent. Pour les dispositifs d’affichage, cela représente idéalement un pixel d’écran physique. Pour d’autres dispositifs ou environnements où la taille physique du pixel n’est pas connue, un algorithme similaire à la définition CSS2 d’un pixel peut être utilisé. Notez que null est renvoyé si cet élément n’est pas intégré à l’arbre du document. Cette méthode aurait pu être nommée plus justement getClientCTM, mais le nom getScreenCTM est conservé pour des raisons historiques."
type: docs

url: /fr/java/com.aspose.html.dom.svg/svggraphicselement/getscreenctm/
---
## SVGGraphicsElement.GetScreenCTM method

Renvoie la matrice de transformation des unités utilisateur actuelles (c’est‑à‑dire après l'application de l'attribut ‘transform’, le cas échéant) vers la notion de "pixel" de l'agent utilisateur parent. Pour les dispositifs d'affichage, cela représente idéalement un pixel physique d'écran. Pour d'autres dispositifs ou environnements où la taille physique des pixels n'est pas connue, un algorithme similaire à la définition CSS2 d'un "pixel" peut être utilisé à la place. Notez que null est renvoyé si cet élément n'est pas intégré à l'arbre du document. Cette méthode aurait pu être plus correctement nommée getClientCTM, mais le nom getScreenCTM est conservé pour des raisons historiques.

```java
public SVGMatrix GetScreenCTM()
```

### Valeur de retour

Un objet SVGMatrix qui définit la matrice de transformation donnée.

### Voir aussi

* class [SVGMatrix](../../../com.aspose.html.dom.svg.datatypes/svgmatrix/)
* class [SVGGraphicsElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
