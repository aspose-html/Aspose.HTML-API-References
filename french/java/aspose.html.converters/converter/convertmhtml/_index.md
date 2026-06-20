---
title: "Converter.ConvertMHTML"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Converter. Convertir la source MHTML présentée par le flux d’entrée. Le résultat est un fichier xps créé à partir du chemin de fichier de sortie."
type: docs

url: /fr/java/com.aspose.html.converters/converter/convertmhtml/
---
## ConvertMHTML(Stream, XpsSaveOptions, String) {#convertmhtml_31}

Convertir la source MHTML présentée par le [flux](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0). Le résultat est un fichier xps créé par le chemin du fichier de sortie.

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux de données mhtml (.mht) d’entrée. |
| options | XpsSaveOptions | L’utilisation de l’objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d’ajuster le processus de rendu. Pour plus d’informations, consultez la [documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Chemin complet du fichier xps en tant que résultat de conversion. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en [XPS](https://docs.fileformat.com/page-description-language/xps/) est souvent nécessaire pour tirer parti du format XPS pour des tâches spécifiques. Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper, créés par Microsoft.

Reportez‑vous à l’[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) où vous trouverez des informations sur la façon de convertir MHTML en XPS en utilisant les méthodes ConvertHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en XPS

La classe Converter propose quelques conversions spécifiques de MHTML en XPS. Pour convertir MHTML en XPS, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratuit en ligne qui convertit MHTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, String) {#convertmhtml_47}

Convertir la source MHTML présentée par le chemin complet du fichier en XPS. Le résultat est un fichier XPS créé à partir du chemin du fichier de sortie.

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source MHTML. |
| options | XpsSaveOptions | L’utilisation de l’objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d’ajuster le processus de rendu. Pour plus d’informations, consultez la [documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Chemin complet du fichier xps en tant que résultat de conversion. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en [XPS](https://docs.fileformat.com/page-description-language/xps/) est souvent nécessaire pour tirer parti du format XPS pour des tâches spécifiques. Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper, créés par Microsoft.

Reportez‑vous à l’[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) où vous trouverez des informations sur la façon de convertir MHTML en XPS en utilisant les méthodes ConvertHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en XPS

La classe Converter propose quelques conversions spécifiques de MHTML en XPS. Pour convertir MHTML en XPS, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratuit en ligne qui convertit MHTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Chemin du fichier source du formulaire
	var sourcePath = Path.Combine(InputFolder, "sample.mht");

	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Définissez l'objet XpsSaveOptions par défaut
	var options = new XpsSaveOptions();

	// Initier le processus de conversion
	Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, String) {#convertmhtml_15}

Convertir la source MHTML présentée par URL. Le résultat est un fichier XPS créé à partir du chemin du fichier de sortie.

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL du document source MHTML - fournit une représentation objet d'un identifiant universel (URL). |
| options | XpsSaveOptions | L’utilisation de l’objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d’ajuster le processus de rendu. Pour plus d’informations, consultez la [documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Chemin complet du fichier xps en tant que résultat de conversion. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en [XPS](https://docs.fileformat.com/page-description-language/xps/) est souvent nécessaire pour tirer parti du format XPS pour des tâches spécifiques. Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper, créés par Microsoft.

Reportez‑vous à l’[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) où vous trouverez des informations sur la façon de convertir MHTML en XPS en utilisant les méthodes ConvertHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en XPS

La classe Converter propose quelques conversions spécifiques de MHTML en XPS. Pour convertir MHTML en XPS, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratuit en ligne qui convertit MHTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// Chemin du fichier source du formulaire
	var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

	// Chemin du fichier résultat du formulaire
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// Définissez l'objet XpsSaveOptions par défaut
	var options = new XpsSaveOptions();

	// Initier le processus de conversion
	Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, String) {#convertmhtml_23}

Convertir la source MHTML présentée par le [flux](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) d'entrée. Le résultat est un fichier XPS créé à partir du chemin du fichier de sortie.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux de données source de conversion mhtml (.mht). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | L’utilisation de l’objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d’ajuster le processus de rendu. Pour plus d’informations, consultez la [documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Chemin complet du fichier xps en tant que résultat de conversion. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en [XPS](https://docs.fileformat.com/page-description-language/xps/) est souvent nécessaire pour tirer parti du format XPS pour des tâches spécifiques. Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper, créés par Microsoft.

Reportez‑vous à l’[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) où vous trouverez des informations sur la façon de convertir MHTML en XPS en utilisant les méthodes ConvertHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en XPS

La classe Converter propose quelques conversions spécifiques de MHTML en XPS. Pour convertir MHTML en XPS, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratuit en ligne qui convertit MHTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(File.OpenRead(sourcePath), new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, String) {#convertmhtml_39}

Convertir la source MHTML présentée par le chemin complet du fichier en XPS. Le résultat est un fichier XPS créé à partir du chemin du fichier de sortie.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source MHTML. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | L’utilisation de l’objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d’ajuster le processus de rendu. Pour plus d’informations, consultez la [documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Chemin complet du fichier xps en tant que résultat de conversion. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en [XPS](https://docs.fileformat.com/page-description-language/xps/) est souvent nécessaire pour tirer parti du format XPS pour des tâches spécifiques. Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper, créés par Microsoft.

Reportez‑vous à l’[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) où vous trouverez des informations sur la façon de convertir MHTML en XPS en utilisant les méthodes ConvertHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en XPS

La classe Converter propose quelques conversions spécifiques de MHTML en XPS. Pour convertir MHTML en XPS, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratuit en ligne qui convertit MHTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, XpsSaveOptions, String) {#convertmhtml_7}

Convertir la source MHTML présentée par URL. Le résultat est un fichier XPS créé à partir du chemin du fichier de sortie.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL du document source MHTML - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | L’utilisation de l’objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d’ajuster le processus de rendu. Pour plus d’informations, consultez la [documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| outputPath | String | Chemin complet du fichier xps en tant que résultat de conversion. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en [XPS](https://docs.fileformat.com/page-description-language/xps/) est souvent nécessaire pour tirer parti du format XPS pour des tâches spécifiques. Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper, créés par Microsoft.

Reportez‑vous à l’[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) où vous trouverez des informations sur la façon de convertir MHTML en XPS en utilisant les méthodes ConvertHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en XPS

La classe Converter propose quelques conversions spécifiques de MHTML en XPS. Pour convertir MHTML en XPS, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratuit en ligne qui convertit MHTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Chemin du fichier source du formulaire
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_30}

Convertir la source MHTML présentée par le flux d'entrée. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux de données source de conversion mhtml (.mht). |
| options | XpsSaveOptions | L’utilisation de l’objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d’ajuster le processus de rendu. Pour plus d’informations, consultez la [documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en [XPS](https://docs.fileformat.com/page-description-language/xps/) est souvent nécessaire pour tirer parti du format XPS pour des tâches spécifiques. Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper, créés par Microsoft.

Reportez‑vous à l’[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) où vous trouverez des informations sur la façon de convertir MHTML en XPS en utilisant les méthodes ConvertHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en XPS

La classe Converter propose quelques conversions spécifiques de MHTML en XPS. Pour convertir MHTML en XPS, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratuit en ligne qui convertit MHTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Voir aussi

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_46}

Convertir la source MHTML présentée par le chemin complet du fichier en XPS. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source MHTML. |
| options | XpsSaveOptions | L’utilisation de l’objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d’ajuster le processus de rendu. Pour plus d’informations, consultez la [documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Convertisseur MHTML

La conversion de MHTML en [XPS](https://docs.fileformat.com/page-description-language/xps/) est souvent nécessaire pour tirer parti du format XPS pour des tâches spécifiques. Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper, créés par Microsoft.

Reportez‑vous à l’[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) où vous trouverez des informations sur la façon de convertir MHTML en XPS en utilisant les méthodes ConvertHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en XPS

La classe Converter propose quelques conversions spécifiques de MHTML en XPS. Pour convertir MHTML en XPS, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratuit en ligne qui convertit MHTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion
      Converter.ConvertMHTML(sourcePath, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Voir aussi

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_14}

Convertir la source MHTML présentée par [`URL`](../../../com.aspose.html/url/). Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL du document source MHTML - fournit une représentation objet d'un identifiant universel (URL). |
| options | XpsSaveOptions | L’utilisation de l’objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d’ajuster le processus de rendu. Pour plus d’informations, consultez la [documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en [XPS](https://docs.fileformat.com/page-description-language/xps/) est souvent nécessaire pour tirer parti du format XPS pour des tâches spécifiques. Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper, créés par Microsoft.

Reportez‑vous à l’[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) où vous trouverez des informations sur la façon de convertir MHTML en XPS en utilisant les méthodes ConvertHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en XPS

La classe Converter propose quelques conversions spécifiques de MHTML en XPS. Pour convertir MHTML en XPS, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratuit en ligne qui convertit MHTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io; 
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Chemin du fichier source du formulaire
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion
      Converter.ConvertMHTML(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_22}

Convertir la source MHTML présentée par le flux d'entrée. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux de données source de conversion mhtml (.mht). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | L’utilisation de l’objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d’ajuster le processus de rendu. Pour plus d’informations, consultez la [documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en [XPS](https://docs.fileformat.com/page-description-language/xps/) est souvent nécessaire pour tirer parti du format XPS pour des tâches spécifiques. Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper, créés par Microsoft.

Reportez‑vous à l’[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) où vous trouverez des informations sur la façon de convertir MHTML en XPS en utilisant les méthodes ConvertHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en XPS

La classe Converter propose quelques conversions spécifiques de MHTML en XPS. Pour convertir MHTML en XPS, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratuit en ligne qui convertit MHTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_38}

Convertir la source MHTML présentée par le chemin complet du fichier en XPS. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source MHTML. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | L’utilisation de l’objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d’ajuster le processus de rendu. Pour plus d’informations, consultez la [documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Convertisseur MHTML

La conversion de MHTML en [XPS](https://docs.fileformat.com/page-description-language/xps/) est souvent nécessaire pour tirer parti du format XPS pour des tâches spécifiques. Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper, créés par Microsoft.

Reportez‑vous à l’[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) où vous trouverez des informations sur la façon de convertir MHTML en XPS en utilisant les méthodes ConvertHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en XPS

La classe Converter propose quelques conversions spécifiques de MHTML en XPS. Pour convertir MHTML en XPS, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratuit en ligne qui convertit MHTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_6}

Convertir la source MHTML présentée par l'URL. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL du document source MHTML - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | L’utilisation de l’objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d’ajuster le processus de rendu. Pour plus d’informations, consultez la [documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Convertisseur MHTML

La conversion de MHTML en [XPS](https://docs.fileformat.com/page-description-language/xps/) est souvent nécessaire pour tirer parti du format XPS pour des tâches spécifiques. Un fichier XPS représente des fichiers de mise en page basés sur les spécifications XML Paper, créés par Microsoft.

Reportez‑vous à l’[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) où vous trouverez des informations sur la façon de convertir MHTML en XPS en utilisant les méthodes ConvertHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en XPS

La classe Converter propose quelques conversions spécifiques de MHTML en XPS. Pour convertir MHTML en XPS, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en XPS](https://products.aspose.app/html/en/conversion/mhtml-to-xps) gratuit en ligne qui convertit MHTML en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Chemin du fichier source du formulaire
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, DocSaveOptions, String) {#convertmhtml_25}

Convertir la source MHTML présentée par le flux d'entrée. Le résultat est un fichier docx créé par le chemin du fichier de sortie.

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux de données d'entrée de conversion MHTML. |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Chemin complet du fichier docx en tant que résultat de conversion de sortie. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en DOCX est souvent nécessaire pour tirer parti du format [DOCX](https://docs.fileformat.com/word-processing/docx/) pour des tâches spécifiques. DOCX est un format bien connu pour les documents Microsoft Word. Il peut contenir une large gamme de données, y compris du texte, des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Ce format est populaire car il prend en charge des fonctionnalités de mise en forme complexes et offre aux utilisateurs une variété d'options pour créer tout type de document.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) où vous trouverez des informations sur la façon de convertir MHTML en DOCX en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en DOCX

La classe Converter propose quelques conversions spécifiques de MHTML vers DOCX. Pour convertir MHTML en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez ajouter également la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en ligne gratuit qui convertit le MHTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Voir aussi

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, String) {#convertmhtml_41}

Convertir la source MHTML présentée par le chemin complet du fichier en DOCX. Le résultat est un fichier docx créé par le chemin du fichier de sortie.

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin du fichier source MHTML. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Chemin complet du fichier docx en tant que résultat de conversion de sortie. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en DOCX est souvent nécessaire pour tirer parti du format [DOCX](https://docs.fileformat.com/word-processing/docx/) pour des tâches spécifiques. DOCX est un format bien connu pour les documents Microsoft Word. Il peut contenir une large gamme de données, y compris du texte, des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Ce format est populaire car il prend en charge des fonctionnalités de mise en forme complexes et offre aux utilisateurs une variété d'options pour créer tout type de document.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) où vous trouverez des informations sur la façon de convertir MHTML en DOCX en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en DOCX

La classe Converter propose quelques conversions spécifiques de MHTML vers DOCX. Pour convertir MHTML en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez ajouter également la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en ligne gratuit qui convertit le MHTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, String) {#convertmhtml_9}

Convertir la source MHTML présentée par URL. Le résultat est un fichier DOCX créé à partir du chemin du fichier de sortie.

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL du document source MHTML - fournit une représentation objet d'un identifiant universel (URL). |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Chemin complet du fichier docx en tant que résultat de conversion de sortie. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en DOCX est souvent nécessaire pour tirer parti du format [DOCX](https://docs.fileformat.com/word-processing/docx/) pour des tâches spécifiques. DOCX est un format bien connu pour les documents Microsoft Word. Il peut contenir une large gamme de données, y compris du texte, des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Ce format est populaire car il prend en charge des fonctionnalités de mise en forme complexes et offre aux utilisateurs une variété d'options pour créer tout type de document.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) où vous trouverez des informations sur la façon de convertir MHTML en DOCX en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en DOCX

La classe Converter propose quelques conversions spécifiques de MHTML vers DOCX. Pour convertir MHTML en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez ajouter également la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en ligne gratuit qui convertit le MHTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Créer une URL basée sur le chemin du fichier d'entrée
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertMHTML(sourceUrl, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, DocSaveOptions, String) {#convertmhtml_17}

Convertir la source MHTML présentée par le flux d'entrée. Le résultat est un fichier docx créé par le chemin du fichier de sortie.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux de données d'entrée de conversion MHTML. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Chemin complet du fichier docx en tant que résultat de conversion de sortie. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en DOCX est souvent nécessaire pour tirer parti du format [DOCX](https://docs.fileformat.com/word-processing/docx/) pour des tâches spécifiques. DOCX est un format bien connu pour les documents Microsoft Word. Il peut contenir une large gamme de données, y compris du texte, des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Ce format est populaire car il prend en charge des fonctionnalités de mise en forme complexes et offre aux utilisateurs une variété d'options pour créer tout type de document.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) où vous trouverez des informations sur la façon de convertir MHTML en DOCX en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en DOCX

La classe Converter propose quelques conversions spécifiques de MHTML vers DOCX. Pour convertir MHTML en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez ajouter également la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en ligne gratuit qui convertit le MHTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, DocSaveOptions, String) {#convertmhtml_33}

Convertir la source MHTML présentée par le chemin complet du fichier en DOCX. Le résultat est un fichier docx créé par le chemin du fichier de sortie.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source MHTML. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Chemin complet du fichier docx en tant que résultat de conversion de sortie. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en DOCX est souvent nécessaire pour tirer parti du format [DOCX](https://docs.fileformat.com/word-processing/docx/) pour des tâches spécifiques. DOCX est un format bien connu pour les documents Microsoft Word. Il peut contenir une large gamme de données, y compris du texte, des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Ce format est populaire car il prend en charge des fonctionnalités de mise en forme complexes et offre aux utilisateurs une variété d'options pour créer tout type de document.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) où vous trouverez des informations sur la façon de convertir MHTML en DOCX en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en DOCX

La classe Converter propose quelques conversions spécifiques de MHTML vers DOCX. Pour convertir MHTML en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez ajouter également la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en ligne gratuit qui convertit le MHTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, DocSaveOptions, String) {#convertmhtml_1}

Convertir la source MHTML présentée par [`URL`](../../../com.aspose.html/url/). Le résultat est un fichier docx généré à partir du chemin du fichier de sortie.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | Document source MHTML [`URL`](../../../com.aspose.html/url/) - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| outputPath | String | Chemin complet du fichier docx en tant que résultat de conversion de sortie. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en DOCX est souvent nécessaire pour tirer parti du format [DOCX](https://docs.fileformat.com/word-processing/docx/) pour des tâches spécifiques. DOCX est un format bien connu pour les documents Microsoft Word. Il peut contenir une large gamme de données, y compris du texte, des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Ce format est populaire car il prend en charge des fonctionnalités de mise en forme complexes et offre aux utilisateurs une variété d'options pour créer tout type de document.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) où vous trouverez des informations sur la façon de convertir MHTML en DOCX en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en DOCX

La classe Converter propose quelques conversions spécifiques de MHTML vers DOCX. Pour convertir MHTML en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez ajouter également la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en ligne gratuit qui convertit le MHTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Créer une URL basée sur le chemin du fichier d'entrée
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_24}

Convertir la source MHTML présentée par le flux d'entrée. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux de données d'entrée de conversion MHTML. |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en DOCX est souvent nécessaire pour tirer parti du format [DOCX](https://docs.fileformat.com/word-processing/docx/) pour des tâches spécifiques. DOCX est un format bien connu pour les documents Microsoft Word. Il peut contenir une large gamme de données, y compris du texte, des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Ce format est populaire car il prend en charge des fonctionnalités de mise en forme complexes et offre aux utilisateurs une variété d'options pour créer tout type de document.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) où vous trouverez des informations sur la façon de convertir MHTML en DOCX en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en DOCX

La classe Converter propose quelques conversions spécifiques de MHTML vers DOCX. Pour convertir MHTML en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez ajouter également la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en ligne gratuit qui convertit le MHTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_40}

Convertir la source MHTML présentée par le chemin complet du fichier en DOCX. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source MHTML. |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en DOCX est souvent nécessaire pour tirer parti du format [DOCX](https://docs.fileformat.com/word-processing/docx/) pour des tâches spécifiques. DOCX est un format bien connu pour les documents Microsoft Word. Il peut contenir une large gamme de données, y compris du texte, des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Ce format est populaire car il prend en charge des fonctionnalités de mise en forme complexes et offre aux utilisateurs une variété d'options pour créer tout type de document.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) où vous trouverez des informations sur la façon de convertir MHTML en DOCX en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en DOCX

La classe Converter propose quelques conversions spécifiques de MHTML vers DOCX. Pour convertir MHTML en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez ajouter également la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en ligne gratuit qui convertit le MHTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_8}

Convertir la source MHTML présentée par l'URL. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | Document source MHTML [`URL`](../../../com.aspose.html/url/) - fournit une représentation objet d'un identifiant universel (URL). |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Convertisseur MHTML

La conversion de MHTML en DOCX est souvent nécessaire pour tirer parti du format [DOCX](https://docs.fileformat.com/word-processing/docx/) pour des tâches spécifiques. DOCX est un format bien connu pour les documents Microsoft Word. Il peut contenir une large gamme de données, y compris du texte, des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Ce format est populaire car il prend en charge des fonctionnalités de mise en forme complexes et offre aux utilisateurs une variété d'options pour créer tout type de document.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) où vous trouverez des informations sur la façon de convertir MHTML en DOCX en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en DOCX

La classe Converter propose quelques conversions spécifiques de MHTML vers DOCX. Pour convertir MHTML en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez ajouter également la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en ligne gratuit qui convertit le MHTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Créer une URL basée sur le chemin du fichier d'entrée
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_16}

Convertir la source MHTML présentée par le flux d'entrée. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux de données d'entrée de conversion MHTML. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Convertisseur MHTML

La conversion de MHTML en DOCX est souvent nécessaire pour tirer parti du format [DOCX](https://docs.fileformat.com/word-processing/docx/) pour des tâches spécifiques. DOCX est un format bien connu pour les documents Microsoft Word. Il peut contenir une large gamme de données, y compris du texte, des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Ce format est populaire car il prend en charge des fonctionnalités de mise en forme complexes et offre aux utilisateurs une variété d'options pour créer tout type de document.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) où vous trouverez des informations sur la façon de convertir MHTML en DOCX en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en DOCX

La classe Converter propose quelques conversions spécifiques de MHTML vers DOCX. Pour convertir MHTML en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez ajouter également la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en ligne gratuit qui convertit le MHTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_32}

Convertir la source MHTML présentée par le chemin complet du fichier en DOCX. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source MHTML. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en DOCX est souvent nécessaire pour tirer parti du format [DOCX](https://docs.fileformat.com/word-processing/docx/) pour des tâches spécifiques. DOCX est un format bien connu pour les documents Microsoft Word. Il peut contenir une large gamme de données, y compris du texte, des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Ce format est populaire car il prend en charge des fonctionnalités de mise en forme complexes et offre aux utilisateurs une variété d'options pour créer tout type de document.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) où vous trouverez des informations sur la façon de convertir MHTML en DOCX en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en DOCX

La classe Converter propose quelques conversions spécifiques de MHTML vers DOCX. Pour convertir MHTML en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez ajouter également la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en ligne gratuit qui convertit le MHTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml}

Convertir la source MHTML présentée par [`URL`](../../../com.aspose.html/url/). Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | Document source MHTML [`URL`](../../../com.aspose.html/url/) - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en DOCX est souvent nécessaire pour tirer parti du format [DOCX](https://docs.fileformat.com/word-processing/docx/) pour des tâches spécifiques. DOCX est un format bien connu pour les documents Microsoft Word. Il peut contenir une large gamme de données, y compris du texte, des tableaux, des graphiques raster et vectoriels, des vidéos, des sons et des diagrammes. Ce format est populaire car il prend en charge des fonctionnalités de mise en forme complexes et offre aux utilisateurs une variété d'options pour créer tout type de document.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) où vous trouverez des informations sur la façon de convertir MHTML en DOCX en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en DOCX

La classe Converter propose quelques conversions spécifiques de MHTML vers DOCX. Pour convertir MHTML en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source de conversion. Résultat de conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez ajouter également la configuration comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en DOCX](https://products.aspose.app/html/en/conversion/mhtml-to-docx) en ligne gratuit qui convertit le MHTML en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Créer une URL basée sur le chemin du fichier d'entrée
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source folder path.

*OutputFolder - user output folder path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, String) {#convertmhtml_29}

Convertir la source MHTML présentée par le flux d'entrée. Le résultat est un fichier pdf créé par le chemin du fichier de sortie.

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux de données d'entrée de conversion MHTML. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Chemin complet du fichier pdf en tant que résultat de conversion. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en PDF est souvent nécessaire pour tirer parti du format [PDF](https://docs.fileformat.com/pdf/) pour des tâches spécifiques. Le PDF offre de nombreux avantages que les autres fichiers n'ont pas. Par exemple, de nombreux programmes et applications prennent en charge les documents PDF ; les fichiers PDF sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez configurer les paramètres de sécurité des fichiers PDF – désactiver l'impression, la modification, l'utilisation d'une signature électronique, etc.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), où vous trouverez des informations sur la façon de convertir MHTML en PDF en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en PDF

La classe Converter propose quelques conversions spécifiques de MHTML en PDF. Pour convertir MHTML en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une URL distante comme source de conversion. Vous pouvez également utiliser un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en ligne gratuit qui convertit le MHTML en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, String) {#convertmhtml_45}

Convertir la source MHTML présentée par le chemin complet du fichier en PDF. Le résultat est un fichier PDF créé à partir du chemin du fichier de sortie.

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source MHTML. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Chemin complet du fichier pdf en tant que résultat de conversion. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en PDF est souvent nécessaire pour tirer parti du format [PDF](https://docs.fileformat.com/pdf/) pour des tâches spécifiques. Le PDF offre de nombreux avantages que les autres fichiers n'ont pas. Par exemple, de nombreux programmes et applications prennent en charge les documents PDF ; les fichiers PDF sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez configurer les paramètres de sécurité des fichiers PDF – désactiver l'impression, la modification, l'utilisation d'une signature électronique, etc.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), où vous trouverez des informations sur la façon de convertir MHTML en PDF en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en PDF

La classe Converter propose quelques conversions spécifiques de MHTML en PDF. Pour convertir MHTML en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une URL distante comme source de conversion. Vous pouvez également utiliser un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en ligne gratuit qui convertit le MHTML en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, String) {#convertmhtml_13}

Convertir la source MHTML présentée par URL. Le résultat est un fichier PDF créé à partir du chemin du fichier de sortie.

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL du document source MHTML - fournit une représentation objet d'un identifiant universel (URL). |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Chemin complet du fichier pdf en tant que résultat de conversion. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en PDF est souvent nécessaire pour tirer parti du format [PDF](https://docs.fileformat.com/pdf/) pour des tâches spécifiques. Le PDF offre de nombreux avantages que les autres fichiers n'ont pas. Par exemple, de nombreux programmes et applications prennent en charge les documents PDF ; les fichiers PDF sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez configurer les paramètres de sécurité des fichiers PDF – désactiver l'impression, la modification, l'utilisation d'une signature électronique, etc.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), où vous trouverez des informations sur la façon de convertir MHTML en PDF en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en PDF

La classe Converter propose quelques conversions spécifiques de MHTML en PDF. Pour convertir MHTML en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une URL distante comme source de conversion. Vous pouvez également utiliser un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en ligne gratuit qui convertit le MHTML en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Créer une URL basée sur le chemin du fichier d'entrée
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, String) {#convertmhtml_21}

Convertir la source MHTML présentée par le flux d'entrée. Le résultat est un fichier pdf créé par le chemin du fichier de sortie.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux de données d'entrée de conversion MHTML. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Chemin complet du fichier pdf en tant que résultat de conversion. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en PDF est souvent nécessaire pour tirer parti du format [PDF](https://docs.fileformat.com/pdf/) pour des tâches spécifiques. Le PDF offre de nombreux avantages que les autres fichiers n'ont pas. Par exemple, de nombreux programmes et applications prennent en charge les documents PDF ; les fichiers PDF sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez configurer les paramètres de sécurité des fichiers PDF – désactiver l'impression, la modification, l'utilisation d'une signature électronique, etc.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), où vous trouverez des informations sur la façon de convertir MHTML en PDF en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en PDF

La classe Converter propose quelques conversions spécifiques de MHTML en PDF. Pour convertir MHTML en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une URL distante comme source de conversion. Vous pouvez également utiliser un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en ligne gratuit qui convertit le MHTML en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, PdfSaveOptions, String) {#convertmhtml_37}

Convertir la source MHTML présentée par le chemin complet du fichier en PDF. Le résultat est un fichier PDF créé à partir du chemin du fichier de sortie.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin du fichier source MHTML. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Chemin complet du fichier pdf en tant que résultat de conversion. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en PDF est souvent nécessaire pour tirer parti du format [PDF](https://docs.fileformat.com/pdf/) pour des tâches spécifiques. Le PDF offre de nombreux avantages que les autres fichiers n'ont pas. Par exemple, de nombreux programmes et applications prennent en charge les documents PDF ; les fichiers PDF sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez configurer les paramètres de sécurité des fichiers PDF – désactiver l'impression, la modification, l'utilisation d'une signature électronique, etc.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), où vous trouverez des informations sur la façon de convertir MHTML en PDF en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en PDF

La classe Converter propose quelques conversions spécifiques de MHTML en PDF. Pour convertir MHTML en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une URL distante comme source de conversion. Vous pouvez également utiliser un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en ligne gratuit qui convertit le MHTML en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, PdfSaveOptions, String) {#convertmhtml_5}

Convertir la source MHTML présentée par URL. Le résultat est un fichier PDF créé à partir du chemin du fichier de sortie.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL du document source MHTML - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| outputPath | String | Chemin complet du fichier pdf en tant que résultat de conversion. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en PDF est souvent nécessaire pour tirer parti du format [PDF](https://docs.fileformat.com/pdf/) pour des tâches spécifiques. Le PDF offre de nombreux avantages que les autres fichiers n'ont pas. Par exemple, de nombreux programmes et applications prennent en charge les documents PDF ; les fichiers PDF sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez configurer les paramètres de sécurité des fichiers PDF – désactiver l'impression, la modification, l'utilisation d'une signature électronique, etc.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), où vous trouverez des informations sur la façon de convertir MHTML en PDF en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en PDF

La classe Converter propose quelques conversions spécifiques de MHTML en PDF. Pour convertir MHTML en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une URL distante comme source de conversion. Vous pouvez également utiliser un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en ligne gratuit qui convertit le MHTML en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Créer une URL basée sur le chemin du fichier d'entrée
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_28}

Convertir la source MHTML présentée par le flux d'entrée. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux de données d'entrée de conversion MHTML. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Convertisseur MHTML

La conversion de MHTML en PDF est souvent nécessaire pour tirer parti du format [PDF](https://docs.fileformat.com/pdf/) pour des tâches spécifiques. Le PDF offre de nombreux avantages que les autres fichiers n'ont pas. Par exemple, de nombreux programmes et applications prennent en charge les documents PDF ; les fichiers PDF sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez configurer les paramètres de sécurité des fichiers PDF – désactiver l'impression, la modification, l'utilisation d'une signature électronique, etc.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), où vous trouverez des informations sur la façon de convertir MHTML en PDF en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en PDF

La classe Converter propose quelques conversions spécifiques de MHTML en PDF. Pour convertir MHTML en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une URL distante comme source de conversion. Vous pouvez également utiliser un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en ligne gratuit qui convertit le MHTML en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_44}

Convertissez la source MHTML présentée par le chemin complet du fichier en PDF. Le résultat est constitué de données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin du fichier source MHTML. Il sera combiné avec le chemin du répertoire actuel pour former une URL absolue. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en PDF est souvent nécessaire pour tirer parti du format [PDF](https://docs.fileformat.com/pdf/) pour des tâches spécifiques. Le PDF offre de nombreux avantages que les autres fichiers n'ont pas. Par exemple, de nombreux programmes et applications prennent en charge les documents PDF ; les fichiers PDF sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez configurer les paramètres de sécurité des fichiers PDF – désactiver l'impression, la modification, l'utilisation d'une signature électronique, etc.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), où vous trouverez des informations sur la façon de convertir MHTML en PDF en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en PDF

La classe Converter propose quelques conversions spécifiques de MHTML en PDF. Pour convertir MHTML en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une URL distante comme source de conversion. Vous pouvez également utiliser un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en ligne gratuit qui convertit le MHTML en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_12}

Convertir la source MHTML présentée par l'URL. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL du document source MHTML - fournit une représentation objet d'un identifiant universel (URL). |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en PDF est souvent nécessaire pour tirer parti du format [PDF](https://docs.fileformat.com/pdf/) pour des tâches spécifiques. Le PDF offre de nombreux avantages que les autres fichiers n'ont pas. Par exemple, de nombreux programmes et applications prennent en charge les documents PDF ; les fichiers PDF sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez configurer les paramètres de sécurité des fichiers PDF – désactiver l'impression, la modification, l'utilisation d'une signature électronique, etc.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), où vous trouverez des informations sur la façon de convertir MHTML en PDF en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en PDF

La classe Converter propose quelques conversions spécifiques de MHTML en PDF. Pour convertir MHTML en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une URL distante comme source de conversion. Vous pouvez également utiliser un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en ligne gratuit qui convertit le MHTML en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Créer une URL basée sur le chemin du fichier d'entrée
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_20}

Convertir la source MHTML présentée par le flux d'entrée. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux de données d'entrée de conversion MHTML. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en PDF est souvent nécessaire pour tirer parti du format [PDF](https://docs.fileformat.com/pdf/) pour des tâches spécifiques. Le PDF offre de nombreux avantages que les autres fichiers n'ont pas. Par exemple, de nombreux programmes et applications prennent en charge les documents PDF ; les fichiers PDF sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez configurer les paramètres de sécurité des fichiers PDF – désactiver l'impression, la modification, l'utilisation d'une signature électronique, etc.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), où vous trouverez des informations sur la façon de convertir MHTML en PDF en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en PDF

La classe Converter propose quelques conversions spécifiques de MHTML en PDF. Pour convertir MHTML en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une URL distante comme source de conversion. Vous pouvez également utiliser un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en ligne gratuit qui convertit le MHTML en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_36}

Convertissez la source MHTML présentée par le chemin complet du fichier en PDF. Le résultat est constitué de données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source MHTML. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en PDF est souvent nécessaire pour tirer parti du format [PDF](https://docs.fileformat.com/pdf/) pour des tâches spécifiques. Le PDF offre de nombreux avantages que les autres fichiers n'ont pas. Par exemple, de nombreux programmes et applications prennent en charge les documents PDF ; les fichiers PDF sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez configurer les paramètres de sécurité des fichiers PDF – désactiver l'impression, la modification, l'utilisation d'une signature électronique, etc.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), où vous trouverez des informations sur la façon de convertir MHTML en PDF en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en PDF

La classe Converter propose quelques conversions spécifiques de MHTML en PDF. Pour convertir MHTML en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une URL distante comme source de conversion. Vous pouvez également utiliser un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en ligne gratuit qui convertit le MHTML en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_4}

Convertir la source MHTML présentée par [`URL`](../../../com.aspose.html/url/). Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL du document source MHTML - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, voir la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur MHTML

La conversion de MHTML en PDF est souvent nécessaire pour tirer parti du format [PDF](https://docs.fileformat.com/pdf/) pour des tâches spécifiques. Le PDF offre de nombreux avantages que les autres fichiers n'ont pas. Par exemple, de nombreux programmes et applications prennent en charge les documents PDF ; les fichiers PDF sont optimisés pour l'impression et sont idéaux pour créer des copies physiques de vos documents ; vous pouvez configurer les paramètres de sécurité des fichiers PDF – désactiver l'impression, la modification, l'utilisation d'une signature électronique, etc.

Consultez l'[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), où vous trouverez des informations sur la façon de convertir MHTML en PDF en utilisant les méthodes ConvertMHTML() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en PDF

La classe Converter propose quelques conversions spécifiques de MHTML en PDF. Pour convertir MHTML en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une URL distante comme source de conversion. Vous pouvez également utiliser un [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en PDF](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) en ligne gratuit qui convertit le MHTML en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Créer une URL basée sur le chemin du fichier d'entrée
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, ImageSaveOptions, String) {#convertmhtml_27}

Convertir la source MHTML présentée par le flux d'entrée en image. Le résultat est un fichier image créé par le chemin du fichier de sortie.

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux de données d'entrée de conversion MHTML. |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Convertisseur MHTML

Les fichiers avec l'extension [MHTML](https://docs.fileformat.com/web/mhtml/) représentent un format d'archive de pages Web que plusieurs applications différentes peuvent créer. Ce format est appelé format d'archive car il enregistre le code HTML du Web et les ressources associées dans un seul fichier. Ces ressources comprennent tout ce qui est lié à la page Web, comme les images, les applets, les animations, les fichiers audio, etc. Les fichiers MHTML peuvent être ouverts dans diverses applications telles qu'Internet Explorer et Microsoft Word. Les spécifications réelles du format sont détaillées dans le [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Reportez-vous à l'article, où vous trouverez des informations sur la façon de convertir le MHTML en images dans différents formats en utilisant les méthodes ConvertMHTML() de la classe Converter et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en image

La classe Converter propose quelques conversions spécifiques de MHTML en images. Les formats pris en charge sont [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) et [TIFF](https://docs.fileformat.com/image/tiff/). Pour convertir le MHTML en image, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Le format d'image par défaut est PNG. Vous pouvez également ajouter la configuration comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en ligne gratuit qui convertit le MHTML en fichier JPEG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Initier le processus de conversion
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, String) {#convertmhtml_43}

Convertir la source MHTML présentée par le chemin complet du fichier. Le résultat est un fichier image créé par le chemin du fichier de sortie.

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source MHTML. |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Convertisseur MHTML

Les fichiers avec l'extension [MHTML](https://docs.fileformat.com/web/mhtml/) représentent un format d'archive de pages Web que plusieurs applications différentes peuvent créer. Ce format est appelé format d'archive car il enregistre le code HTML du Web et les ressources associées dans un seul fichier. Ces ressources comprennent tout ce qui est lié à la page Web, comme les images, les applets, les animations, les fichiers audio, etc. Les fichiers MHTML peuvent être ouverts dans diverses applications telles qu'Internet Explorer et Microsoft Word. Les spécifications réelles du format sont détaillées dans le [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Reportez-vous à l'article, où vous trouverez des informations sur la façon de convertir le MHTML en images dans différents formats en utilisant les méthodes ConvertMHTML() de la classe Converter et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en image

La classe Converter propose quelques conversions spécifiques de MHTML en images. Les formats pris en charge sont [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) et [TIFF](https://docs.fileformat.com/image/tiff/). Pour convertir le MHTML en image, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Le format d'image par défaut est PNG. Vous pouvez également ajouter la configuration comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en ligne gratuit qui convertit le MHTML en fichier JPEG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Initier le processus de conversion
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, String) {#convertmhtml_11}

Convertir la source MHTML présentée par URL. Le résultat est un fichier image créé à partir du chemin du fichier de sortie.

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL du document source MHTML - fournit une représentation objet d'un identifiant universel (URL). |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Convertisseur MHTML

Les fichiers avec l'extension [MHTML](https://docs.fileformat.com/web/mhtml/) représentent un format d'archive de pages Web que plusieurs applications différentes peuvent créer. Ce format est appelé format d'archive car il enregistre le code HTML du Web et les ressources associées dans un seul fichier. Ces ressources comprennent tout ce qui est lié à la page Web, comme les images, les applets, les animations, les fichiers audio, etc. Les fichiers MHTML peuvent être ouverts dans diverses applications telles qu'Internet Explorer et Microsoft Word. Les spécifications réelles du format sont détaillées dans le [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Reportez-vous à l'article, où vous trouverez des informations sur la façon de convertir le MHTML en images dans différents formats en utilisant les méthodes ConvertMHTML() de la classe Converter et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en image

La classe Converter propose quelques conversions spécifiques de MHTML en images. Les formats pris en charge sont [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) et [TIFF](https://docs.fileformat.com/image/tiff/). Pour convertir le MHTML en image, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Le format d'image par défaut est PNG. Vous pouvez également ajouter la configuration comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en ligne gratuit qui convertit le MHTML en fichier JPEG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Créer une URL basée sur le chemin du fichier d'entrée
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Initier le processus de conversion
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, String) {#convertmhtml_19}

Convertir la source MHTML présentée par le flux d'entrée en image. Le résultat est un fichier image créé par le chemin du fichier de sortie.

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux de données d'entrée de conversion MHTML. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Convertisseur MHTML

Les fichiers avec l'extension [MHTML](https://docs.fileformat.com/web/mhtml/) représentent un format d'archive de pages Web que plusieurs applications différentes peuvent créer. Ce format est appelé format d'archive car il enregistre le code HTML du Web et les ressources associées dans un seul fichier. Ces ressources comprennent tout ce qui est lié à la page Web, comme les images, les applets, les animations, les fichiers audio, etc. Les fichiers MHTML peuvent être ouverts dans diverses applications telles qu'Internet Explorer et Microsoft Word. Les spécifications réelles du format sont détaillées dans le [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Reportez-vous à l'article, où vous trouverez des informations sur la façon de convertir le MHTML en images dans différents formats en utilisant les méthodes ConvertMHTML() de la classe Converter et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en image

La classe Converter propose quelques conversions spécifiques de MHTML en images. Les formats pris en charge sont [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) et [TIFF](https://docs.fileformat.com/image/tiff/). Pour convertir le MHTML en image, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Le format d'image par défaut est PNG. Vous pouvez également ajouter la configuration comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en ligne gratuit qui convertit le MHTML en fichier JPEG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, ImageSaveOptions, String) {#convertmhtml_35}

Convertir la source MHTML présentée par le chemin complet du fichier. Le résultat est un fichier image créé par le chemin du fichier de sortie.

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source MHTML. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Convertisseur MHTML

Les fichiers avec l'extension [MHTML](https://docs.fileformat.com/web/mhtml/) représentent un format d'archive de pages Web que plusieurs applications différentes peuvent créer. Ce format est appelé format d'archive car il enregistre le code HTML du Web et les ressources associées dans un seul fichier. Ces ressources comprennent tout ce qui est lié à la page Web, comme les images, les applets, les animations, les fichiers audio, etc. Les fichiers MHTML peuvent être ouverts dans diverses applications telles qu'Internet Explorer et Microsoft Word. Les spécifications réelles du format sont détaillées dans le [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Reportez-vous à l'article, où vous trouverez des informations sur la façon de convertir le MHTML en images dans différents formats en utilisant les méthodes ConvertMHTML() de la classe Converter et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en image

La classe Converter propose quelques conversions spécifiques de MHTML en images. Les formats pris en charge sont [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) et [TIFF](https://docs.fileformat.com/image/tiff/). Pour convertir le MHTML en image, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Le format d'image par défaut est PNG. Vous pouvez également ajouter la configuration comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en ligne gratuit qui convertit le MHTML en fichier JPEG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, ImageSaveOptions, String) {#convertmhtml_3}

Convertir la source MHTML présentée par URL. Le résultat est un fichier image créé à partir du chemin du fichier de sortie.

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL du document source MHTML - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Convertisseur MHTML

Les fichiers avec l'extension [MHTML](https://docs.fileformat.com/web/mhtml/) représentent un format d'archive de pages Web que plusieurs applications différentes peuvent créer. Ce format est appelé format d'archive car il enregistre le code HTML du Web et les ressources associées dans un seul fichier. Ces ressources comprennent tout ce qui est lié à la page Web, comme les images, les applets, les animations, les fichiers audio, etc. Les fichiers MHTML peuvent être ouverts dans diverses applications telles qu'Internet Explorer et Microsoft Word. Les spécifications réelles du format sont détaillées dans le [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Reportez-vous à l'article, où vous trouverez des informations sur la façon de convertir le MHTML en images dans différents formats en utilisant les méthodes ConvertMHTML() de la classe Converter et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en image

La classe Converter propose quelques conversions spécifiques de MHTML en images. Les formats pris en charge sont [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) et [TIFF](https://docs.fileformat.com/image/tiff/). Pour convertir le MHTML en image, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Le format d'image par défaut est PNG. Vous pouvez également ajouter la configuration comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en ligne gratuit qui convertit le MHTML en fichier JPEG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Créer une URL basée sur le chemin du fichier d'entrée
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_26}

Convertir la source MHTML présentée par le flux d'entrée. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux de données d'entrée de conversion MHTML. |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur MHTML

Les fichiers avec l'extension [MHTML](https://docs.fileformat.com/web/mhtml/) représentent un format d'archive de pages Web que plusieurs applications différentes peuvent créer. Ce format est appelé format d'archive car il enregistre le code HTML du Web et les ressources associées dans un seul fichier. Ces ressources comprennent tout ce qui est lié à la page Web, comme les images, les applets, les animations, les fichiers audio, etc. Les fichiers MHTML peuvent être ouverts dans diverses applications telles qu'Internet Explorer et Microsoft Word. Les spécifications réelles du format sont détaillées dans le [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Reportez-vous à l'article, où vous trouverez des informations sur la façon de convertir le MHTML en images dans différents formats en utilisant les méthodes ConvertMHTML() de la classe Converter et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en image

La classe Converter propose quelques conversions spécifiques de MHTML en images. Les formats pris en charge sont [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) et [TIFF](https://docs.fileformat.com/image/tiff/). Pour convertir le MHTML en image, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Le format d'image par défaut est PNG. Vous pouvez également ajouter la configuration comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en ligne gratuit qui convertit le MHTML en fichier JPEG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_42}

Convertissez la source MHTML présentée par le chemin complet du fichier en image. Le résultat est constitué de données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source MHTML. |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Convertisseur MHTML

Les fichiers avec l'extension [MHTML](https://docs.fileformat.com/web/mhtml/) représentent un format d'archive de pages Web que plusieurs applications différentes peuvent créer. Ce format est appelé format d'archive car il enregistre le code HTML du Web et les ressources associées dans un seul fichier. Ces ressources comprennent tout ce qui est lié à la page Web, comme les images, les applets, les animations, les fichiers audio, etc. Les fichiers MHTML peuvent être ouverts dans diverses applications telles qu'Internet Explorer et Microsoft Word. Les spécifications réelles du format sont détaillées dans le [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Reportez-vous à l'article, où vous trouverez des informations sur la façon de convertir le MHTML en images dans différents formats en utilisant les méthodes ConvertMHTML() de la classe Converter et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en image

La classe Converter propose quelques conversions spécifiques de MHTML en images. Les formats pris en charge sont [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) et [TIFF](https://docs.fileformat.com/image/tiff/). Pour convertir le MHTML en image, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Le format d'image par défaut est PNG. Vous pouvez également ajouter la configuration comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en ligne gratuit qui convertit le MHTML en fichier JPEG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_10}

Convertir la source MHTML présentée par l'URL. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL du document source MHTML - fournit une représentation objet d'un identifiant universel (URL). |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Convertisseur MHTML

Les fichiers avec l'extension [MHTML](https://docs.fileformat.com/web/mhtml/) représentent un format d'archive de pages Web que plusieurs applications différentes peuvent créer. Ce format est appelé format d'archive car il enregistre le code HTML du Web et les ressources associées dans un seul fichier. Ces ressources comprennent tout ce qui est lié à la page Web, comme les images, les applets, les animations, les fichiers audio, etc. Les fichiers MHTML peuvent être ouverts dans diverses applications telles qu'Internet Explorer et Microsoft Word. Les spécifications réelles du format sont détaillées dans le [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Reportez-vous à l'article, où vous trouverez des informations sur la façon de convertir le MHTML en images dans différents formats en utilisant les méthodes ConvertMHTML() de la classe Converter et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en image

La classe Converter propose quelques conversions spécifiques de MHTML en images. Les formats pris en charge sont [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) et [TIFF](https://docs.fileformat.com/image/tiff/). Pour convertir le MHTML en image, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Le format d'image par défaut est PNG. Vous pouvez également ajouter la configuration comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en ligne gratuit qui convertit le MHTML en fichier JPEG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Créer une URL basée sur le chemin du fichier d'entrée
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_18}

Convertir la source MHTML présentée par le flux d'entrée. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Flux de données d'entrée de conversion MHTML. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur MHTML

Les fichiers avec l'extension [MHTML](https://docs.fileformat.com/web/mhtml/) représentent un format d'archive de pages Web que plusieurs applications différentes peuvent créer. Ce format est appelé format d'archive car il enregistre le code HTML du Web et les ressources associées dans un seul fichier. Ces ressources comprennent tout ce qui est lié à la page Web, comme les images, les applets, les animations, les fichiers audio, etc. Les fichiers MHTML peuvent être ouverts dans diverses applications telles qu'Internet Explorer et Microsoft Word. Les spécifications réelles du format sont détaillées dans le [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Reportez-vous à l'article, où vous trouverez des informations sur la façon de convertir le MHTML en images dans différents formats en utilisant les méthodes ConvertMHTML() de la classe Converter et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en image

La classe Converter propose quelques conversions spécifiques de MHTML en images. Les formats pris en charge sont [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) et [TIFF](https://docs.fileformat.com/image/tiff/). Pour convertir le MHTML en image, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Le format d'image par défaut est PNG. Vous pouvez également ajouter la configuration comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en ligne gratuit qui convertit le MHTML en fichier JPEG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_34}

Convertissez la source MHTML présentée par le chemin complet du fichier en image. Le résultat est constitué de données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source MHTML. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur MHTML

Les fichiers avec l'extension [MHTML](https://docs.fileformat.com/web/mhtml/) représentent un format d'archive de pages Web que plusieurs applications différentes peuvent créer. Ce format est appelé format d'archive car il enregistre le code HTML du Web et les ressources associées dans un seul fichier. Ces ressources comprennent tout ce qui est lié à la page Web, comme les images, les applets, les animations, les fichiers audio, etc. Les fichiers MHTML peuvent être ouverts dans diverses applications telles qu'Internet Explorer et Microsoft Word. Les spécifications réelles du format sont détaillées dans le [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Reportez-vous à l'article, où vous trouverez des informations sur la façon de convertir le MHTML en images dans différents formats en utilisant les méthodes ConvertMHTML() de la classe Converter et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en image

La classe Converter propose quelques conversions spécifiques de MHTML en images. Les formats pris en charge sont [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) et [TIFF](https://docs.fileformat.com/image/tiff/). Pour convertir le MHTML en image, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Le format d'image par défaut est PNG. Vous pouvez également ajouter la configuration comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en ligne gratuit qui convertit le MHTML en fichier JPEG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Chemin du fichier source du formulaire
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_2}

Convertir la source MHTML présentée par l'URL. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceUrl | Url | URL du document source MHTML - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur MHTML

Les fichiers avec l'extension [MHTML](https://docs.fileformat.com/web/mhtml/) représentent un format d'archive de pages Web que plusieurs applications différentes peuvent créer. Ce format est appelé format d'archive car il enregistre le code HTML du Web et les ressources associées dans un seul fichier. Ces ressources comprennent tout ce qui est lié à la page Web, comme les images, les applets, les animations, les fichiers audio, etc. Les fichiers MHTML peuvent être ouverts dans diverses applications telles qu'Internet Explorer et Microsoft Word. Les spécifications réelles du format sont détaillées dans le [RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557).

Reportez-vous à l'article, où vous trouverez des informations sur la façon de convertir le MHTML en images dans différents formats en utilisant les méthodes ConvertMHTML() de la classe Converter et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir MHTML en image

La classe Converter propose quelques conversions spécifiques de MHTML en images. Les formats pris en charge sont [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [GIF](https://docs.fileformat.com/image/gif/) et [TIFF](https://docs.fileformat.com/image/tiff/). Pour convertir le MHTML en image, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier MHTML (.mht) local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également utiliser un flux standard ou personnalisé comme source. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Le format d'image par défaut est PNG. Vous pouvez également ajouter la configuration comme paramètre d'option. Utilisez la méthode ConvertMHTML() de la classe Converter pour enregistrer le MHTML en résultat image avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur MHTML en ligne

Aspose.HTML propose un [convertisseur MHTML en JPEG](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) en ligne gratuit qui convertit le MHTML en fichier JPEG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Créer une URL basée sur le chemin du fichier d'entrée
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
