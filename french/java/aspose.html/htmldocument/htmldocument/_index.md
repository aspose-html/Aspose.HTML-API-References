---
title: "HTMLDocument"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Constructeur HTMLDocument. Le constructeur HTMLDocument crée un nouvel objet HTML Document qui est une page web chargée dans le navigateur et sert de point d’entrée au contenu des pages."
type: docs

url: /fr/java/com.aspose.html/htmldocument/htmldocument/
---
## HTMLDocument() {#constructor}

Le constructeur HTMLDocument crée un nouvel objet Document HTML qui est une page web chargée dans le navigateur et sert de point d’entrée au contenu de la page.

```java
public HTMLDocument()
```

## Remarques

Remarque : Le document est créé avec une valeur par défaut pour la propriété base-url égale à 'about:blank'.

Référence :

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exemples

Une fois l’objet document créé, il peut être rempli ultérieurement avec des éléments HTML. Le fragment de code suivant montre l’utilisation du constructeur par défaut HTMLDocument() pour créer un document HTML vide et l’enregistrer dans un fichier.

```java
import (var document = new HTMLDocument())
{
	// Travaillez avec le document ici
	...	
	
	// Enregistrez le document dans un fichier
	document.Save("document.html");
}
```

### Voir aussi

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Configuration) {#constructor_1}

Le constructeur HTMLDocument crée un nouvel objet Document HTML qui est une page web chargée dans le navigateur et sert de point d’entrée au contenu de la page.

```java
public HTMLDocument(Configuration configuration)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| configuration | Configuration | La configuration de l’environnement telle que la politique des scripts, la feuille de style utilisateur personnalisée, etc. |

## Remarques

Remarque : Le document est créé avec une valeur par défaut pour la propriété base-url égale à 'about:blank'.

Référence :

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exemples

L’exemple suivant montre comment utiliser l’objet de configuration pour désactiver les scripts :

```java
// Préparez le code HTML et enregistrez-le dans un fichier
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Créer une instance de Configuration
import (var configuration = new Configuration())
{
	// Marquer 'scripts' comme une ressource non fiable
	configuration.Security |= Sandbox.Scripts;

	// Initialiser un document HTML avec la configuration spécifiée
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// Convertir HTML en PDF
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### Voir aussi

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url) {#constructor_4}

Charge le document HTML depuis une URL.

Remarque : Si vous fournissez une URL incorrecte qui ne peut pas être atteinte pour le moment, la bibliothèque lève l’[`DOMException`](../../../com.aspose.html.dom/domexception/) avec le code spécialisé ‘NetworkError’ pour vous informer que la ressource sélectionnée est introuvable.

```java
public HTMLDocument(Url url)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | L’URL du document HTML à ouvrir. |

## Remarques

Référence :

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exemples

Chargez un document depuis la page web 'https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html' :

```java
import (var document = new HTMLDocument("https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html"))
{
	// Écrivez le contenu du document dans le flux de sortie
	Console.WriteLine(document.DocumentElement.OuterHTML);
}
```

### Voir aussi

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url, Configuration) {#constructor_5}

Charge le document HTML depuis une URL avec les paramètres de configuration d’environnement spécifiés.

Remarque : Si vous fournissez une URL incorrecte qui ne peut pas être atteinte pour le moment, la bibliothèque lève le [DOMException](T:com.aspose.html.dom.DOMException) avec le code spécialisé ‘NetworkError’ pour vous informer que la ressource sélectionnée est introuvable.

```java
public HTMLDocument(Url url, Configuration configuration)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | L’URL du document HTML à ouvrir. |
| configuration | Configuration | La configuration de l’environnement telle que la politique des scripts, la feuille de style utilisateur personnalisée, etc. |

## Remarques

Référence :

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exemples

```java
The following example demonstrates how to use the configuration object to disable scripts:

// Préparez le code HTML et enregistrez-le dans un fichier
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Créer une instance de Configuration
import (var configuration = new Configuration())
{
	// Marquer 'scripts' comme une ressource non fiable
	configuration.Security |= Sandbox.Scripts;

	// Initialiser un document HTML avec la configuration spécifiée
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// Convertir HTML en PDF
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### Voir aussi

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String) {#constructor_10}

Charge le document HTML depuis une adresse.

Remarque : Si vous fournissez une URL incorrecte qui ne peut pas être atteinte pour le moment, la bibliothèque lève l’[`DOMException`](../../../com.aspose.html.dom/domexception/) avec le code spécialisé ‘NetworkError’ pour vous informer que la ressource sélectionnée est introuvable.

```java
public HTMLDocument(String address)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| adresse | String | L’adresse du document HTML à ouvrir. |

## Remarques

Référence :

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exemples

Initialisez un document HTML à partir d’une adresse.

```java
import (var document = new HTMLDocument("./my-folder/document.html")))
{
	...
}
```

### Voir aussi

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Configuration) {#constructor_11}

Charge le document HTML depuis une adresse avec les paramètres de configuration d’environnement spécifiés.

Remarque : Si vous fournissez une URL incorrecte qui ne peut pas être atteinte pour le moment, la bibliothèque lève l’[`DOMException`](../../../com.aspose.html.dom/domexception/) avec le code spécialisé ‘NetworkError’ pour vous informer que la ressource sélectionnée est introuvable.

```java
public HTMLDocument(String address, Configuration configuration)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| adresse | String | L’adresse du document HTML à ouvrir. |
| configuration | Configuration | La configuration de l’environnement telle que la politique des scripts, la feuille de style utilisateur personnalisée, etc. |

## Remarques

Référence :

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exemples

```java
// Créer une instance de Configuration
import (var configuration = new Configuration())
{
	// Marquer 'scripts' comme une ressource non fiable
	configuration.Security |= Sandbox.Scripts;
	
	using (var document = new HTMLDocument("./my-folder/document.html", configuration)))
	{
		...
	}
}
```

### Voir aussi

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String) {#constructor_14}

Crée un document HTML à partir d’un contenu String avec l’URI de base spécifiée.

```java
public HTMLDocument(String content, String baseUri)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Le contenu String avec lequel charger le document. |
| baseUri | String | L'URI de base du document. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lance une exception si le paramètre base-uri est nul. |

## Remarques

Référence :

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exemples

```java
// Préparer le code HTML
var html_code = "<p>Hello World!</p>";

// Initialiser un document à partir de la variable String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Voir aussi

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String, Configuration) {#constructor_15}

Crée un document HTML à partir d’un contenu String avec l’URI de base et les paramètres de configuration d’environnement spécifiés.

```java
public HTMLDocument(String content, String baseUri, Configuration configuration)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Le contenu String avec lequel charger le document. |
| baseUri | String | L'URI de base du document. |
| configuration | Configuration | La configuration de l’environnement telle que la politique des scripts, la feuille de style utilisateur personnalisée, etc. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lance une exception si le paramètre base-uri est nul. |

## Remarques

Référence :

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exemples

```java
// Préparer le code HTML
var html_code = "<p>Hello World!</p>";

// Initialiser un document à partir de la variable String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Voir aussi

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url) {#constructor_12}

Crée un document HTML à partir d’un contenu String avec l’URI de base spécifiée.

```java
public HTMLDocument(String content, Url baseUri)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Le contenu String avec lequel charger le document. |
| baseUri | Url | L'URI de base du document. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lance une exception si le paramètre base-uri est nul. |

## Remarques

Référence :

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exemples

```java
// Préparer le code HTML
var html_code = "<p>Hello World!</p>";

// Initialiser un document à partir de la variable String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Voir aussi

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url, Configuration) {#constructor_13}

Crée un document HTML à partir d’un contenu String avec l’URI de base et les paramètres de configuration d’environnement spécifiés.

```java
public HTMLDocument(String content, Url baseUri, Configuration configuration)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Le contenu String avec lequel charger le document. |
| baseUri | Url | L'URI de base du document. |
| configuration | Configuration | La configuration de l’environnement telle que la politique des scripts, la feuille de style utilisateur personnalisée, etc. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lance une exception si le paramètre base-uri est nul. |

## Remarques

Référence :

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exemples

```java
// Préparer le code HTML
var html_code = "<p>Hello World!</p>";

// Initialiser un document à partir de la variable String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Voir aussi

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String) {#constructor_8}

Crée un document HTML à partir d’un contenu [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) avec l’URI de base spécifiée, utilisée pour résoudre le chemin des ressources relatives.

```java
public HTMLDocument(Stream content, String baseUri)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| content | Stream | Le contenu du [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) avec lequel charger le document. |
| baseUri | String | L'URI de base du document. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lance une exception si le paramètre base-uri est nul. |

## Remarques

Référence :

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exemples

```java
// Créez un objet de flux mémoire
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Écrivez le code HTML dans l’objet mémoire
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Il est important de placer la position au début puisque HTMLDocument commence la lecture exactement à partir de la position actuelle dans le flux.
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Initialiser un document à partir de la variable String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Enregistrez le document sur un disque
		document.Save("load-from-stream.html");
	}
}
```

### Voir aussi

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String, Configuration) {#constructor_9}

Crée un document HTML à partir d’un contenu [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) avec l’URI de base et les paramètres de configuration d’environnement spécifiés.

```java
public HTMLDocument(Stream content, String baseUri, Configuration configuration)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| content | Stream | Le contenu du [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) avec lequel charger le document. |
| baseUri | String | L'URI de base du document. |
| configuration | Configuration | La configuration de l’environnement telle que la politique des scripts, la feuille de style utilisateur personnalisée, etc. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lance une exception si le paramètre base-uri est nul. |

## Remarques

Référence :

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exemples

```java
// Créez un objet de flux mémoire
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Écrivez le code HTML dans l’objet mémoire
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Il est important de placer la position au début puisque HTMLDocument commence la lecture exactement à partir de la position actuelle dans le flux.
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Initialiser un document à partir de la variable String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Enregistrez le document sur un disque
		document.Save("load-from-stream.html");
	}
}
```

### Voir aussi

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url) {#constructor_6}

Crée un document HTML à partir d’un contenu [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) avec l’URI de base spécifiée, utilisée pour résoudre le chemin des ressources relatives.

```java
public HTMLDocument(Stream content, Url baseUri)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| content | Stream | Le contenu du [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) avec lequel charger le document. |
| baseUri | Url | L'URI de base du document. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lance une exception si le paramètre base-uri est nul. |

## Remarques

Référence :

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exemples

```java
// Créez un objet de flux mémoire
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Écrivez le code HTML dans l’objet mémoire
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Il est important de placer la position au début puisque HTMLDocument commence la lecture exactement à partir de la position actuelle dans le flux.
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Initialiser un document à partir de la variable String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Enregistrez le document sur un disque
		document.Save("load-from-stream.html");
	}
}
```

### Voir aussi

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url, Configuration) {#constructor_7}

Crée un document HTML à partir d’un contenu [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) avec l’URI de base et les paramètres de configuration d’environnement spécifiés.

```java
public HTMLDocument(Stream content, Url baseUri, Configuration configuration)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| content | Stream | Le contenu du [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) avec lequel charger le document. |
| baseUri | Url | L'URI de base du document. |
| configuration | Configuration | La configuration de l’environnement telle que la politique des scripts, la feuille de style utilisateur personnalisée, etc. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lance une exception si le paramètre base-uri est nul. |

## Remarques

Référence :

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Exemples

```java
// Créez un objet de flux mémoire
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Écrivez le code HTML dans l’objet mémoire
	sw.Write("<p>Hello World! I love HTML!</p>");

	// Il est important de placer la position au début puisque HTMLDocument commence la lecture exactement à partir de la position actuelle dans le flux.
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Initialiser un document à partir de la variable String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Enregistrez le document sur un disque
		document.Save("load-from-stream.html");
	}
}
```

### Voir aussi

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage) {#constructor_2}

Crée un document HTML à partir de l'objet [`RequestMessage`](../../../com.aspose.html.net/requestmessage/).

```java
public HTMLDocument(RequestMessage request)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| request | RequestMessage | Le message de requête qui contient un [`body`](../../../com.aspose.html.net/requestmessage/content/) avec le contenu du document. |

## Remarques

Par définition, un gestionnaire de messages est une classe qui reçoit une requête Web et renvoie une réponse Web. En d'autres termes, un gestionnaire de messages est utilisé pour traiter une requête de service Web lors de l'entrée et/ou pour traiter la réponse lors de la sortie.

Veuillez visiter notre [site de documentation](https://docs.aspose.com/html/net/message-handlers/) pour voir plus de scénarios d'utilisation de ce constructeur.

Référence :

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Voir aussi

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage, Configuration) {#constructor_3}

Crée un document HTML à partir d’un objet [RequestMessage](T:com.aspose.html.net.RequestMessage).

```java
public HTMLDocument(RequestMessage request, Configuration configuration)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| request | RequestMessage | Le message de requête qui contient un [body](P:com.aspose.html.net.RequestMessage.Content) avec le contenu du document. |
| configuration | Configuration | La configuration de l’environnement telle que la politique des scripts, la feuille de style utilisateur personnalisée, etc. |

## Remarques

Par définition, un gestionnaire de messages est une classe qui reçoit une requête Web et renvoie une réponse Web. En d'autres termes, un gestionnaire de messages est utilisé pour traiter une requête de service Web lors de l'entrée et/ou pour traiter la réponse lors de la sortie.

Veuillez visiter notre [site de documentation](https://docs.aspose.com/html/net/message-handlers/) pour voir plus de scénarios d'utilisation de ce constructeur.

Référence :

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Voir aussi

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
