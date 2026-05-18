---
title: "Interface IWindow"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.window.IWindow. L'objet window représente une fenêtre contenant un document DOM"
type: docs

url: /fr/java/com.aspose.html.window/iwindow/
---
## IWindow interface

L'objet window représente une fenêtre contenant un document DOM.

```java
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getDocument](../../com.aspose.html.window/iwindow/document/) L'attribut document doit renvoyer le dernier objet Document de l'objet Window. |
| [getFrameElement](../../com.aspose.html.window/iwindow/frameelement/) L'objet frameElement d'un Document. |
| [getLocalStorage](../../com.aspose.html.window/iwindow/localstorage/) Renvoie un objet Storage qui vous permet d'enregistrer des paires clé/valeur dans l'agent utilisateur. |
| [getLocation](../../com.aspose.html.window/iwindow/location/) L'attribut location de l'interface Window doit renvoyer l'objet Location pour le Document de cet objet Window. |
[getName]
[setName] The name attribute of the Window object must, on getting, return the current name of the browsing context, and, on setting, set the name of the browsing context to the new value. |
| [getOpener](../../com.aspose.html.window/iwindow/opener/) L'attribut IDL opener sur l'objet Window, lors de la lecture, doit renvoyer l'objet WindowProxy du contexte de navigation à partir duquel le contexte de navigation actuel a été créé (son contexte de navigation d'ouverture), s'il existe, s'il est encore disponible, et si le contexte de navigation actuel n'a pas renoncé à son ouvreur ; sinon, il doit renvoyer null. Lors de l'écriture, si la nouvelle valeur est null, le contexte de navigation actuel doit renoncer à son ouvreur ; si la nouvelle valeur est autre, l'agent utilisateur doit appeler la méthode interne [[DefineOwnProperty]] de l'objet Window, en passant le nom de propriété "opener" comme clé de propriété, et le Property Descriptor { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } comme le descripteur de propriété, où value est la nouvelle valeur. |
| [getParent](../../com.aspose.html.window/iwindow/parent/) L'attribut IDL parent sur l'objet Window d'un Document dans un contexte de navigation b doit renvoyer l'objet WindowProxy du contexte de navigation parent, s'il existe (c.-à-d. si b est un contexte de navigation enfant), ou l'objet WindowProxy du contexte de navigation b lui‑même, sinon (c.-à-d. s'il s'agit d'un contexte de navigation de niveau supérieur ou d'un contexte imbriqué détaché). |
| [getSelf](../../com.aspose.html.window/iwindow/self/) Renvoie l'objet WindowProxy du contexte de navigation de l'objet Window. |
| [getTop](../../com.aspose.html.window/iwindow/top/) L'attribut IDL top sur l'objet Window d'un Document dans un contexte de navigation b doit renvoyer l'objet WindowProxy de son contexte de navigation de niveau supérieur (qui serait son propre objet WindowProxy s'il était lui‑même un contexte de navigation de niveau supérieur), s'il en possède un, ou son propre objet WindowProxy sinon (p. ex. s'il était un contexte imbriqué détaché). |
| [getWindow](../../com.aspose.html.window/iwindow/window/) Renvoie l'objet WindowProxy du contexte de navigation de l'objet Window. |

## Méthodes

| Nom | Description |
| --- | --- |
| [alert](../../com.aspose.html.window/iwindow/alert/)(String) | Affiche une alerte modale avec le message fourni et attend que l'utilisateur la ferme. |
| [atob](../../com.aspose.html.window/iwindow/atob/)(String) | Prend les données d'entrée, sous la forme d'une chaîne Unicode contenant des données binaires encodées en base64, les décode, et renvoie une chaîne composée de caractères dans la plage U+0000 à U+00FF, chaque caractère représentant un octet binaire avec des valeurs de 0x00 à 0xFF respectivement, correspondant à ces données binaires. |
| [btoa](../../com.aspose.html.window/iwindow/btoa/)(String) | Prend les données d'entrée, sous la forme d'une chaîne Unicode ne contenant que des caractères dans la plage U+0000 à U+00FF, chaque caractère représentant un octet binaire avec des valeurs de 0x00 à 0xFF respectivement, et les convertit en leur représentation base64, qu'elle renvoie. |
| [confirm](../../com.aspose.html.window/iwindow/confirm/)(String) | Affiche une boîte de dialogue modale OK/Annuler avec le message fourni, attend que l'utilisateur la ferme, et renvoie true si l'utilisateur clique sur OK et false s'il clique sur Annuler. |
| [matchMedia](../../com.aspose.html.window/iwindow/matchmedia/)(String) | Renvoie un nouvel objet MediaQueryList qui peut ensuite être utilisé pour déterminer si le document correspond à la chaîne de requête média, ainsi que pour surveiller le document afin de détecter quand il correspond (ou cesse de correspondre) à cette requête média. Voir la spécification du module CSSOM View : [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [prompt](../../com.aspose.html.window/iwindow/prompt/)(String, String) | Affiche une boîte de dialogue modale avec un champ texte et le message fourni, attend que l'utilisateur la ferme, et renvoie la valeur saisie par l'utilisateur. Si l'utilisateur annule la boîte de dialogue, elle renvoie null. Si le deuxième argument est présent, la valeur fournie est utilisée comme valeur par défaut. |

### Voir aussi

* interface [IDocumentView](../../com.aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../com.aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
