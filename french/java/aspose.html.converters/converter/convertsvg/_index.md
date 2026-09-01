---
title: "Converter.ConvertSVG"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Converter. Convertissez la source SVG présentée par SVGDocument. Le résultat est des données de sortie formées par l'implémentation de l'interface ICreateStreamProvider"
type: docs

url: /fr/java/com.aspose.html.converters/converter/convertsvg/
---
## ConvertSVG(SVGDocument, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_6}

Convertissez la source SVG présentée par [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Le résultat est des données de sortie formées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | SVGDocument | Source de conversion présentée par [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Reportez-vous à [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) où vous trouverez des informations sur la façon de convertir SVG en XPS en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et sur la façon d'appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en XPS

La classe Converter propose plusieurs conversions spécifiques SVG vers XPS. Pour convertir SVG en XPS, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) gratuit en ligne qui convertit le SVG en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Formez le document SVG comme source de conversion
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
			// Initier le processus de conversion avec la configuration par défaut
			Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_22}

Convertissez la source SVG présentée par [`URL`](../../../com.aspose.html/url/). Le résultat est des données de sortie formées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | Document source SVG [`URL`](../../../com.aspose.html/url/) - fournit une représentation objet d'un identifiant universel (URL). |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Reportez-vous à [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) où vous trouverez des informations sur la façon de convertir SVG en XPS en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et sur la façon d'appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en XPS

La classe Converter propose plusieurs conversions spécifiques SVG vers XPS. Pour convertir SVG en XPS, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) gratuit en ligne qui convertit le SVG en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion
      Converter.ConvertSVG(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_14}

Convertissez la source SVG présentée par [`URL`](../../../com.aspose.html/url/). Le résultat est des données de sortie formées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | Document source SVG [`URL`](../../../com.aspose.html/url/) - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Reportez-vous à [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) où vous trouverez des informations sur la façon de convertir SVG en XPS en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et sur la façon d'appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en XPS

La classe Converter propose plusieurs conversions spécifiques SVG vers XPS. Pour convertir SVG en XPS, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) gratuit en ligne qui convertit le SVG en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_38}

Convertissez la source SVG présentée par le chemin complet du fichier en XPS. Le résultat est des données de sortie formées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source SVG. |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Reportez-vous à [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) où vous trouverez des informations sur la façon de convertir SVG en XPS en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et sur la façon d'appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en XPS

La classe Converter propose plusieurs conversions spécifiques SVG vers XPS. Pour convertir SVG en XPS, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) gratuit en ligne qui convertit le SVG en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion
      Converter.ConvertSVG(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_30}

Convertissez la source SVG présentée par le chemin complet du fichier en XPS. Le résultat est des données de sortie formées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source SVG. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Reportez-vous à [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) où vous trouverez des informations sur la façon de convertir SVG en XPS en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et sur la façon d'appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en XPS

La classe Converter propose plusieurs conversions spécifiques SVG vers XPS. Pour convertir SVG en XPS, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) gratuit en ligne qui convertit le SVG en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_54}

Convertissez la source SVG présentée par du contenu en ligne vers XPS. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu SVG en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Reportez-vous à [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) où vous trouverez des informations sur la façon de convertir SVG en XPS en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et sur la façon d'appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en XPS

La classe Converter propose plusieurs conversions spécifiques SVG vers XPS. Pour convertir SVG en XPS, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) gratuit en ligne qui convertit le SVG en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Voir aussi

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_46}

Convertissez la source SVG présentée par du contenu en ligne vers XPS. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu SVG en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Reportez-vous à [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) où vous trouverez des informations sur la façon de convertir SVG en XPS en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et sur la façon d'appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en XPS

La classe Converter propose plusieurs conversions spécifiques SVG vers XPS. Pour convertir SVG en XPS, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) gratuit en ligne qui convertit le SVG en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, DocSaveOptions, String) {#convertsvg_1}

Convertissez la source SVG présentée par [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Le résultat est un fichier docx créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(SVGDocument source, DocSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| source | SVGDocument | Source de conversion présentée par [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Chemin complet du fichier docx en tant que résultat de conversion de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) où vous trouverez des informations sur la façon de convertir SVG en [DOCX](https://docs.fileformat.com/word-processing/docx/) en utilisant les méthodes ConvertSVG() de la classe Converter et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en DOCX

La classe Converter propose plusieurs conversions spécifiques SVG vers DOCX. Pour convertir SVG en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers DOCX](https://products.aspose.app/svg/en/conversion/svg) gratuit en ligne qui convertit SVG en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Formez le document SVG comme source de conversion
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Initier le processus de conversion avec la configuration par défaut
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, String) {#convertsvg_17}

Convertissez la source SVG présentée par [`URL`](../../../com.aspose.html/url/). Le résultat est un fichier docx créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(Url url, DocSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | Document source SVG [`URL`](../../../com.aspose.html/url/) - fournit une représentation objet d'un identifiant universel (URL). |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Chemin complet du fichier docx en tant que résultat de conversion de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) où vous trouverez des informations sur la façon de convertir SVG en [DOCX](https://docs.fileformat.com/word-processing/docx/) en utilisant les méthodes ConvertSVG() de la classe Converter et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en DOCX

La classe Converter propose plusieurs conversions spécifiques SVG vers DOCX. Pour convertir SVG en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers DOCX](https://products.aspose.app/svg/en/conversion/svg) gratuit en ligne qui convertit SVG en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertSVG(sourceUrl, options, resultPath);





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

## ConvertSVG(Url, Configuration, DocSaveOptions, String) {#convertsvg_9}

Convertissez la source SVG présentée par [`URL`](../../../com.aspose.html/url/). Le résultat est un fichier docx créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | Document source SVG [`URL`](../../../com.aspose.html/url/) - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Chemin complet du fichier docx en tant que résultat de conversion de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) où vous trouverez des informations sur la façon de convertir SVG en [DOCX](https://docs.fileformat.com/word-processing/docx/) en utilisant les méthodes ConvertSVG() de la classe Converter et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en DOCX

La classe Converter propose plusieurs conversions spécifiques SVG vers DOCX. Pour convertir SVG en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers DOCX](https://products.aspose.app/svg/en/conversion/svg) gratuit en ligne qui convertit SVG en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, String) {#convertsvg_33}

Convertir la source SVG présentée par le chemin complet du fichier en DOCX. Le résultat est un fichier DOCX créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source SVG. |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Chemin complet du fichier docx en tant que résultat de conversion de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) où vous trouverez des informations sur la façon de convertir SVG en [DOCX](https://docs.fileformat.com/word-processing/docx/) en utilisant les méthodes ConvertSVG() de la classe Converter et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en DOCX

La classe Converter propose plusieurs conversions spécifiques SVG vers DOCX. Pour convertir SVG en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers DOCX](https://products.aspose.app/svg/en/conversion/svg) gratuit en ligne qui convertit SVG en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertSVG(sourcePath, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Voir aussi

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, DocSaveOptions, String) {#convertsvg_25}

Convertir la source SVG présentée par le chemin complet du fichier en DOCX. Le résultat est un fichier DOCX créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source SVG. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Chemin complet du fichier docx en tant que résultat de conversion de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) où vous trouverez des informations sur la façon de convertir SVG en [DOCX](https://docs.fileformat.com/word-processing/docx/) en utilisant les méthodes ConvertSVG() de la classe Converter et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en DOCX

La classe Converter propose plusieurs conversions spécifiques SVG vers DOCX. Pour convertir SVG en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers DOCX](https://products.aspose.app/svg/en/conversion/svg) gratuit en ligne qui convertit SVG en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, DocSaveOptions, String) {#convertsvg_49}

Convertir la source SVG présentée par du contenu en ligne. Le résultat est un fichier docx créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu SVG en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Chemin complet du fichier docx en tant que résultat de conversion de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) où vous trouverez des informations sur la façon de convertir SVG en [DOCX](https://docs.fileformat.com/word-processing/docx/) en utilisant les méthodes ConvertSVG() de la classe Converter et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en DOCX

La classe Converter propose plusieurs conversions spécifiques SVG vers DOCX. Pour convertir SVG en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers DOCX](https://products.aspose.app/svg/en/conversion/svg) gratuit en ligne qui convertit SVG en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulaire de contenu SVG en ligne
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Voir aussi

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, String) {#convertsvg_41}

Convertir la source SVG présentée par du contenu en ligne. Le résultat est un fichier docx créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu SVG en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| outputPath | String | Chemin complet du fichier docx en tant que résultat de conversion de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) où vous trouverez des informations sur la façon de convertir SVG en [DOCX](https://docs.fileformat.com/word-processing/docx/) en utilisant les méthodes ConvertSVG() de la classe Converter et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en DOCX

La classe Converter propose plusieurs conversions spécifiques SVG vers DOCX. Pour convertir SVG en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers DOCX](https://products.aspose.app/svg/en/conversion/svg) gratuit en ligne qui convertit SVG en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulaire de contenu SVG en ligne
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, DocSaveOptions, ICreateStreamProvider) {#convertsvg}

Convertissez la source SVG présentée par [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Le résultat est des données de sortie formées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | SVGDocument | Source de conversion présentée par [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) où vous trouverez des informations sur la façon de convertir SVG en [DOCX](https://docs.fileformat.com/word-processing/docx/) en utilisant les méthodes ConvertSVG() de la classe Converter et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en DOCX

La classe Converter propose plusieurs conversions spécifiques SVG vers DOCX. Pour convertir SVG en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers DOCX](https://products.aspose.app/svg/en/conversion/svg) gratuit en ligne qui convertit SVG en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Formez le document SVG comme source de conversion
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Initier le processus de conversion avec la configuration par défaut
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, ICreateStreamProvider) {#convertsvg_16}

Convertissez la source SVG présentée par [`URL`](../../../com.aspose.html/url/). Le résultat est des données de sortie formées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | Document source SVG [`URL`](../../../com.aspose.html/url/) - fournit une représentation objet d'un identifiant universel (URL). |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) où vous trouverez des informations sur la façon de convertir SVG en [DOCX](https://docs.fileformat.com/word-processing/docx/) en utilisant les méthodes ConvertSVG() de la classe Converter et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en DOCX

La classe Converter propose plusieurs conversions spécifiques SVG vers DOCX. Pour convertir SVG en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers DOCX](https://products.aspose.app/svg/en/conversion/svg) gratuit en ligne qui convertit SVG en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion
      Converter.ConvertSVG(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_8}

Convertissez la source SVG présentée par [`URL`](../../../com.aspose.html/url/). Le résultat est un fichier docx créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | Document source SVG [`URL`](../../../com.aspose.html/url/) - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) où vous trouverez des informations sur la façon de convertir SVG en [DOCX](https://docs.fileformat.com/word-processing/docx/) en utilisant les méthodes ConvertSVG() de la classe Converter et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en DOCX

La classe Converter propose plusieurs conversions spécifiques SVG vers DOCX. Pour convertir SVG en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers DOCX](https://products.aspose.app/svg/en/conversion/svg) gratuit en ligne qui convertit SVG en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_32}

Convertissez la source SVG présentée par le chemin complet du fichier vers DOCX. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source SVG. |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) où vous trouverez des informations sur la façon de convertir SVG en [DOCX](https://docs.fileformat.com/word-processing/docx/) en utilisant les méthodes ConvertSVG() de la classe Converter et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en DOCX

La classe Converter propose plusieurs conversions spécifiques SVG vers DOCX. Pour convertir SVG en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers DOCX](https://products.aspose.app/svg/en/conversion/svg) gratuit en ligne qui convertit SVG en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_24}

Convertissez la source SVG présentée par le chemin complet du fichier vers DOCX. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source SVG. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) où vous trouverez des informations sur la façon de convertir SVG en [DOCX](https://docs.fileformat.com/word-processing/docx/) en utilisant les méthodes ConvertSVG() de la classe Converter et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en DOCX

La classe Converter propose plusieurs conversions spécifiques SVG vers DOCX. Pour convertir SVG en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers DOCX](https://products.aspose.app/svg/en/conversion/svg) gratuit en ligne qui convertit SVG en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_48}

Convertissez la source SVG présentée par du contenu en ligne vers DOCX. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu SVG en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) où vous trouverez des informations sur la façon de convertir SVG en [DOCX](https://docs.fileformat.com/word-processing/docx/) en utilisant les méthodes ConvertSVG() de la classe Converter et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en DOCX

La classe Converter propose plusieurs conversions spécifiques SVG vers DOCX. Pour convertir SVG en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers DOCX](https://products.aspose.app/svg/en/conversion/svg) gratuit en ligne qui convertit SVG en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Voir aussi

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_40}

Convertissez la source SVG présentée par du contenu en ligne vers DOCX. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu SVG en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | DocSaveOptions | L'utilisation de l'objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) où vous trouverez des informations sur la façon de convertir SVG en [DOCX](https://docs.fileformat.com/word-processing/docx/) en utilisant les méthodes ConvertSVG() de la classe Converter et comment appliquer les paramètres [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en DOCX

La classe Converter propose plusieurs conversions spécifiques SVG vers DOCX. Pour convertir SVG en DOCX, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat DOCX avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers DOCX](https://products.aspose.app/svg/en/conversion/svg) gratuit en ligne qui convertit SVG en DOCX avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Définir l'objet DocSaveOptions par défaut
      var options = new DocSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, String) {#convertsvg_5}

Convertissez la source SVG présentée par [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) en PDF. Le résultat est un fichier pdf créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(SVGDocument source, PdfSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| source | SVGDocument | Source de conversion présentée par [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Chemin complet du fichier pdf en tant que résultat de conversion. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) où vous trouverez des informations sur la façon de convertir SVG en PDF en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en PDF

La classe Converter propose plusieurs conversions spécifiques SVG vers PDF. Pour convertir SVG en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) gratuit en ligne qui convertit SVG en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Formez le document SVG comme source de conversion
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Initier le processus de conversion avec la configuration par défaut
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, String) {#convertsvg_21}

Convertissez la source SVG présentée par [`URL`](../../../com.aspose.html/url/). Le résultat est un fichier pdf créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | Document source SVG [`URL`](../../../com.aspose.html/url/) - fournit une représentation objet d'un identifiant universel (URL). |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Chemin complet du fichier pdf en tant que résultat de conversion. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) où vous trouverez des informations sur la façon de convertir SVG en PDF en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en PDF

La classe Converter propose plusieurs conversions spécifiques SVG vers PDF. Pour convertir SVG en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) gratuit en ligne qui convertit SVG en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, PdfSaveOptions, String) {#convertsvg_13}

Convertissez la source SVG présentée par [`URL`](../../../com.aspose.html/url/). Le résultat est un fichier pdf créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | Document source SVG [`URL`](../../../com.aspose.html/url/) - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Chemin complet du fichier pdf en tant que résultat de conversion. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) où vous trouverez des informations sur la façon de convertir SVG en PDF en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en PDF

La classe Converter propose plusieurs conversions spécifiques SVG vers PDF. Pour convertir SVG en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) gratuit en ligne qui convertit SVG en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertSVG(String, PdfSaveOptions, String) {#convertsvg_37}

Convertir la source SVG présentée par le chemin complet du fichier en PDF. Le résultat est un fichier PDF créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source SVG. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Chemin complet du fichier pdf en tant que résultat de conversion. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) où vous trouverez des informations sur la façon de convertir SVG en PDF en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en PDF

La classe Converter propose plusieurs conversions spécifiques SVG vers PDF. Pour convertir SVG en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) gratuit en ligne qui convertit SVG en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, PdfSaveOptions, String) {#convertsvg_29}

Convertir la source SVG présentée par le chemin complet du fichier en PDF. Le résultat est un fichier PDF créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source SVG. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Chemin complet du fichier pdf en tant que résultat de conversion. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) où vous trouverez des informations sur la façon de convertir SVG en PDF en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en PDF

La classe Converter propose plusieurs conversions spécifiques SVG vers PDF. Pour convertir SVG en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) gratuit en ligne qui convertit SVG en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, PdfSaveOptions, String) {#convertsvg_53}

Convertir la source SVG présentée par du contenu en ligne en PDF. Le résultat est un fichier pdf créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu SVG en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Chemin complet du fichier pdf en tant que résultat de conversion. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) où vous trouverez des informations sur la façon de convertir SVG en PDF en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en PDF

La classe Converter propose plusieurs conversions spécifiques SVG vers PDF. Pour convertir SVG en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) gratuit en ligne qui convertit SVG en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulaire de contenu SVG en ligne
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Voir aussi

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, String) {#convertsvg_45}

Convertir la source SVG présentée par du contenu en ligne en PDF. Le résultat est un fichier pdf créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu SVG en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| outputPath | String | Chemin complet du fichier pdf en tant que résultat de conversion. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) où vous trouverez des informations sur la façon de convertir SVG en PDF en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en PDF

La classe Converter propose plusieurs conversions spécifiques SVG vers PDF. Pour convertir SVG en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) gratuit en ligne qui convertit SVG en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulaire de contenu SVG en ligne
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_4}

Convertissez la source SVG présentée par [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) en PDF. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | SVGDocument | Source de conversion présentée par [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) où vous trouverez des informations sur la façon de convertir SVG en PDF en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en PDF

La classe Converter propose plusieurs conversions spécifiques SVG vers PDF. Pour convertir SVG en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) gratuit en ligne qui convertit SVG en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Formez le document SVG comme source de conversion
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Initier le processus de conversion avec la configuration par défaut
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_20}

Convertissez la source SVG présentée par [`URL`](../../../com.aspose.html/url/). Le résultat est des données de sortie formées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | Document source SVG [`URL`](../../../com.aspose.html/url/) - fournit une représentation objet d'un identifiant universel (URL). |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) où vous trouverez des informations sur la façon de convertir SVG en PDF en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en PDF

La classe Converter propose plusieurs conversions spécifiques SVG vers PDF. Pour convertir SVG en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) gratuit en ligne qui convertit SVG en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_12}

Convertissez la source SVG présentée par [`URL`](../../../com.aspose.html/url/). Le résultat est des données de sortie formées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | Document source SVG [`URL`](../../../com.aspose.html/url/) - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) où vous trouverez des informations sur la façon de convertir SVG en PDF en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en PDF

La classe Converter propose plusieurs conversions spécifiques SVG vers PDF. Pour convertir SVG en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) gratuit en ligne qui convertit SVG en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_36}

Convertissez la source SVG présentée par le chemin complet du fichier en PDF. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source SVG. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) où vous trouverez des informations sur la façon de convertir SVG en PDF en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en PDF

La classe Converter propose plusieurs conversions spécifiques SVG vers PDF. Pour convertir SVG en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) gratuit en ligne qui convertit SVG en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_28}

Convertissez la source SVG présentée par le chemin complet du fichier en PDF. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source SVG. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) où vous trouverez des informations sur la façon de convertir SVG en PDF en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en PDF

La classe Converter propose plusieurs conversions spécifiques SVG vers PDF. Pour convertir SVG en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) gratuit en ligne qui convertit SVG en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_52}

Convertissez la source SVG présentée par du contenu en ligne en PDF. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu SVG en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) où vous trouverez des informations sur la façon de convertir SVG en PDF en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en PDF

La classe Converter propose plusieurs conversions spécifiques SVG vers PDF. Pour convertir SVG en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) gratuit en ligne qui convertit SVG en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Voir aussi

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_44}

Convertissez la source SVG présentée par du contenu en ligne en PDF. Le résultat est des données de sortie générées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu SVG en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | PdfSaveOptions | L'utilisation de l'objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez la [Documentation Aspose](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options). |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez-vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) où vous trouverez des informations sur la façon de convertir SVG en PDF en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en PDF

La classe Converter propose plusieurs conversions spécifiques SVG vers PDF. Pour convertir SVG en PDF, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne fourni par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode `ConvertSVG()` de la classe Converter pour enregistrer le SVG en résultat PDF avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers PDF](https://products.aspose.app/svg/en/conversion/svg-to-pdf) gratuit en ligne qui convertit SVG en PDF avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, convertir vos fichiers et obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Définir l'objet PdfSaveOptions par défaut
      var options = new PdfSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, String) {#convertsvg_3}

Convertir la source SVG présentée par [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Le résultat est un fichier image créé à partir du chemin de fichier de sortie.

```java
public static void ConvertSVG(SVGDocument source, ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| source | SVGDocument | Source de conversion présentée par [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez‑vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) où vous trouverez des informations sur la façon de convertir SVG en JPG en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Autres articles liés aux formats d’image populaires : [conversion SVG en PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversion SVG en BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversion SVG en GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) et [conversion SVG en TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG en image

La classe Converter propose plusieurs conversions spécifiques de SVG en image dans des formats populaires. Pour convertir SVG en image, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source de type String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Notez que le format d’image par défaut est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat d’image avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG en JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) gratuit en ligne qui convertit SVG en JPG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

D’autres convertisseurs d’image populaires pour différents formats peuvent être trouvés ici : [convertisseur SVG en PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [convertisseur SVG en BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [convertisseur SVG en GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) et [convertisseur SVG en TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions();

      // Formez le document SVG comme source de conversion
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Initier le processus de conversion avec la configuration par défaut
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, String) {#convertsvg_19}

Convertir la source SVG présentée par [`URL`](../../../com.aspose.html/url/). Le résultat est un fichier image créé à partir du chemin de fichier de sortie.

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | Document source SVG [`URL`](../../../com.aspose.html/url/) - fournit une représentation objet d'un identifiant universel (URL). |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez‑vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) où vous trouverez des informations sur la façon de convertir SVG en JPG en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Autres articles liés aux formats d’image populaires : [conversion SVG en PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversion SVG en BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversion SVG en GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) et [conversion SVG en TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG en image

La classe Converter propose plusieurs conversions spécifiques de SVG en image dans des formats populaires. Pour convertir SVG en image, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source de type String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Notez que le format d’image par défaut est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat d’image avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG en JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) gratuit en ligne qui convertit SVG en JPG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

D’autres convertisseurs d’image populaires pour différents formats peuvent être trouvés ici : [convertisseur SVG en PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [convertisseur SVG en BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [convertisseur SVG en GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) et [convertisseur SVG en TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Initier le processus de conversion
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, ImageSaveOptions, String) {#convertsvg_11}

Convertir la source SVG présentée par [`URL`](../../../com.aspose.html/url/). Le résultat est un fichier image créé à partir du chemin de fichier de sortie.

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | Document source SVG [`URL`](../../../com.aspose.html/url/) - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez‑vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) où vous trouverez des informations sur la façon de convertir SVG en JPG en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Autres articles liés aux formats d’image populaires : [conversion SVG en PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversion SVG en BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversion SVG en GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) et [conversion SVG en TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG en image

La classe Converter propose plusieurs conversions spécifiques de SVG en image dans des formats populaires. Pour convertir SVG en image, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source de type String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Notez que le format d’image par défaut est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat d’image avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG en JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) gratuit en ligne qui convertit SVG en JPG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

D’autres convertisseurs d’image populaires pour différents formats peuvent être trouvés ici : [convertisseur SVG en PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [convertisseur SVG en BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [convertisseur SVG en GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) et [convertisseur SVG en TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertSVG(String, ImageSaveOptions, String) {#convertsvg_35}

Convertir la source SVG présentée par le chemin complet du fichier en image. Le résultat est un fichier image créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source SVG. |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez‑vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) où vous trouverez des informations sur la façon de convertir SVG en JPG en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Autres articles liés aux formats d’image populaires : [conversion SVG en PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversion SVG en BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversion SVG en GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) et [conversion SVG en TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG en image

La classe Converter propose plusieurs conversions spécifiques de SVG en image dans des formats populaires. Pour convertir SVG en image, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source de type String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Notez que le format d’image par défaut est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat d’image avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG en JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) gratuit en ligne qui convertit SVG en JPG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

D’autres convertisseurs d’image populaires pour différents formats peuvent être trouvés ici : [convertisseur SVG en PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [convertisseur SVG en BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [convertisseur SVG en GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) et [convertisseur SVG en TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Initier le processus de conversion
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, ImageSaveOptions, String) {#convertsvg_27}

Convertir la source SVG présentée par le chemin complet du fichier en image. Le résultat est un fichier image créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source SVG. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez‑vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) où vous trouverez des informations sur la façon de convertir SVG en JPG en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Autres articles liés aux formats d’image populaires : [conversion SVG en PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversion SVG en BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversion SVG en GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) et [conversion SVG en TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG en image

La classe Converter propose plusieurs conversions spécifiques de SVG en image dans des formats populaires. Pour convertir SVG en image, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source de type String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Notez que le format d’image par défaut est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat d’image avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG en JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) gratuit en ligne qui convertit SVG en JPG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

D’autres convertisseurs d’image populaires pour différents formats peuvent être trouvés ici : [convertisseur SVG en PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [convertisseur SVG en BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [convertisseur SVG en GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) et [convertisseur SVG en TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, ImageSaveOptions, String) {#convertsvg_51}

Convertir la source SVG présentée par du contenu en ligne en image. Le résultat est un fichier image créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu SVG en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez‑vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) où vous trouverez des informations sur la façon de convertir SVG en JPG en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Autres articles liés aux formats d’image populaires : [conversion SVG en PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversion SVG en BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversion SVG en GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) et [conversion SVG en TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG en image

La classe Converter propose plusieurs conversions spécifiques de SVG en image dans des formats populaires. Pour convertir SVG en image, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source de type String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Notez que le format d’image par défaut est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat d’image avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG en JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) gratuit en ligne qui convertit SVG en JPG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

D’autres convertisseurs d’image populaires pour différents formats peuvent être trouvés ici : [convertisseur SVG en PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [convertisseur SVG en BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [convertisseur SVG en GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) et [convertisseur SVG en TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulaire de contenu SVG en ligne
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Voir aussi

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, String) {#convertsvg_43}

Convertir la source SVG présentée par du contenu en ligne en image. Le résultat est un fichier image créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu SVG en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| outputPath | String | Chemin complet du fichier image en tant que résultat de conversion. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez‑vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) où vous trouverez des informations sur la façon de convertir SVG en JPG en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Autres articles liés aux formats d’image populaires : [conversion SVG en PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversion SVG en BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversion SVG en GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) et [conversion SVG en TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG en image

La classe Converter propose plusieurs conversions spécifiques de SVG en image dans des formats populaires. Pour convertir SVG en image, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source de type String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Notez que le format d’image par défaut est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat d’image avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG en JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) gratuit en ligne qui convertit SVG en JPG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

D’autres convertisseurs d’image populaires pour différents formats peuvent être trouvés ici : [convertisseur SVG en PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [convertisseur SVG en BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [convertisseur SVG en GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) et [convertisseur SVG en TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Formulaire de contenu SVG en ligne
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_2}

Convertissez la source SVG présentée par [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Le résultat est des données de sortie formées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(SVGDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | SVGDocument | Source de conversion présentée par [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez‑vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) où vous trouverez des informations sur la façon de convertir SVG en JPG en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Autres articles liés aux formats d’image populaires : [conversion SVG en PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversion SVG en BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversion SVG en GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) et [conversion SVG en TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG en image

La classe Converter propose plusieurs conversions spécifiques de SVG en image dans des formats populaires. Pour convertir SVG en image, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source de type String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Notez que le format d’image par défaut est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat d’image avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG en JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) gratuit en ligne qui convertit SVG en JPG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

D’autres convertisseurs d’image populaires pour différents formats peuvent être trouvés ici : [convertisseur SVG en PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [convertisseur SVG en BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [convertisseur SVG en GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) et [convertisseur SVG en TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Formez le document SVG comme source de conversion
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // Initier le processus de conversion
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_18}

Convertissez la source SVG présentée par [`URL`](../../../com.aspose.html/url/). Le résultat est des données de sortie formées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | Document source SVG [`URL`](../../../com.aspose.html/url/) - fournit une représentation objet d'un identifiant universel (URL). |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez‑vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) où vous trouverez des informations sur la façon de convertir SVG en JPG en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Autres articles liés aux formats d’image populaires : [conversion SVG en PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversion SVG en BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversion SVG en GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) et [conversion SVG en TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG en image

La classe Converter propose plusieurs conversions spécifiques de SVG en image dans des formats populaires. Pour convertir SVG en image, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source de type String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Notez que le format d’image par défaut est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat d’image avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG en JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) gratuit en ligne qui convertit SVG en JPG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

D’autres convertisseurs d’image populaires pour différents formats peuvent être trouvés ici : [convertisseur SVG en PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [convertisseur SVG en BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [convertisseur SVG en GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) et [convertisseur SVG en TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_10}

Convertissez la source SVG présentée par [`URL`](../../../com.aspose.html/url/). Le résultat est des données de sortie formées par l'implémentation de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | Document source SVG [`URL`](../../../com.aspose.html/url/) - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez‑vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) où vous trouverez des informations sur la façon de convertir SVG en JPG en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Autres articles liés aux formats d’image populaires : [conversion SVG en PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversion SVG en BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversion SVG en GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) et [conversion SVG en TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG en image

La classe Converter propose plusieurs conversions spécifiques de SVG en image dans des formats populaires. Pour convertir SVG en image, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source de type String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Notez que le format d’image par défaut est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat d’image avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG en JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) gratuit en ligne qui convertit SVG en JPG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

D’autres convertisseurs d’image populaires pour différents formats peuvent être trouvés ici : [convertisseur SVG en PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [convertisseur SVG en BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [convertisseur SVG en GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) et [convertisseur SVG en TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

---

## ConvertSVG(String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_34}

Convertir la source SVG présentée par le chemin complet du fichier en image. Le résultat est des données de sortie générées par l’implémentation de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source SVG. |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez‑vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) où vous trouverez des informations sur la façon de convertir SVG en JPG en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Autres articles liés aux formats d’image populaires : [conversion SVG en PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversion SVG en BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversion SVG en GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) et [conversion SVG en TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG en image

La classe Converter propose plusieurs conversions spécifiques de SVG en image dans des formats populaires. Pour convertir SVG en image, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source de type String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Notez que le format d’image par défaut est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat d’image avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG en JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) gratuit en ligne qui convertit SVG en JPG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

D’autres convertisseurs d’image populaires pour différents formats peuvent être trouvés ici : [convertisseur SVG en PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [convertisseur SVG en BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [convertisseur SVG en GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) et [convertisseur SVG en TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions();

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_26}

Convertir la source SVG présentée par le chemin complet du fichier en image. Le résultat est des données de sortie générées par l’implémentation de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source SVG. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez‑vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) où vous trouverez des informations sur la façon de convertir SVG en JPG en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Autres articles liés aux formats d’image populaires : [conversion SVG en PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversion SVG en BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversion SVG en GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) et [conversion SVG en TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG en image

La classe Converter propose plusieurs conversions spécifiques de SVG en image dans des formats populaires. Pour convertir SVG en image, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source de type String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Notez que le format d’image par défaut est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat d’image avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG en JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) gratuit en ligne qui convertit SVG en JPG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

D’autres convertisseurs d’image populaires pour différents formats peuvent être trouvés ici : [convertisseur SVG en PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [convertisseur SVG en BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [convertisseur SVG en GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) et [convertisseur SVG en TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_50}

Convertir la source SVG présentée par du contenu en ligne en image. Le résultat est des données de sortie générées par l’implémentation de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu SVG en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Connu (voir [`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/)) ou implémentation personnalisée de l'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) . |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez‑vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) où vous trouverez des informations sur la façon de convertir SVG en JPG en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Autres articles liés aux formats d’image populaires : [conversion SVG en PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversion SVG en BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversion SVG en GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) et [conversion SVG en TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG en image

La classe Converter propose plusieurs conversions spécifiques de SVG en image dans des formats populaires. Pour convertir SVG en image, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source de type String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Notez que le format d’image par défaut est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat d’image avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG en JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) gratuit en ligne qui convertit SVG en JPG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

D’autres convertisseurs d’image populaires pour différents formats peuvent être trouvés ici : [convertisseur SVG en PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [convertisseur SVG en BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [convertisseur SVG en GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) et [convertisseur SVG en TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### Voir aussi

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_42}

Convertir la source SVG présentée par du contenu en ligne en image. Le résultat est des données de sortie générées par l’implémentation de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu SVG en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | ImageSaveOptions | L'utilisation de l'objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) vous permet d'ajuster le processus de rendu. Vous pouvez spécifier la [`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), les [`margins`](../../../com.aspose.html.drawing/page/margin/), le [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/), etc. |
| provider | ICreateStreamProvider | Implémentation de l'[`interface`](../../../com.aspose.html.io/icreatestreamprovider/), qui sera utilisée pour obtenir un flux de sortie. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

Reportez‑vous à l'[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) où vous trouverez des informations sur la façon de convertir SVG en JPG en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et comment appliquer les paramètres [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/). Autres articles liés aux formats d’image populaires : [conversion SVG en PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), [conversion SVG en BMP](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), [conversion SVG en GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) et [conversion SVG en TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/).

Convertir SVG en image

La classe Converter propose plusieurs conversions spécifiques de SVG en image dans des formats populaires. Pour convertir SVG en image, vous devez suivre l’un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir un [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source de type String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation connue ou personnalisée de l’interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) comme tampon de données de sortie. Créez un nouvel objet [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) avec des paramètres spécifiques ou par défaut. Notez que le format d’image par défaut est PNG. Vous pouvez également ajouter la [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d’option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat d’image avec trois paramètres ou plus selon le scénario de l’utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG en JPG](https://products.aspose.app/svg/en/conversion/svg-to-jpg) gratuit en ligne qui convertit SVG en JPG avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d’obtenir les résultats en quelques secondes !

D’autres convertisseurs d’image populaires pour différents formats peuvent être trouvés ici : [convertisseur SVG en PNG](https://products.aspose.app/svg/en/conversion/svg-to-png), [convertisseur SVG en BMP](https://products.aspose.app/svg/en/conversion/svg-to-bmp), [convertisseur SVG en GIF](https://products.aspose.app/svg/en/conversion/svg-to-gif) et [convertisseur SVG en TIFF](https://products.aspose.app/svg/en/conversion/svg-to-tiff).

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Utiliser l'une des implémentations de ICreateStreamProvider
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // Définir l’objet ImageSaveOptions par défaut
      var options = new ImageSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
```

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, XpsSaveOptions, String) {#convertsvg_7}

Convertir la source SVG présentée par [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). Le résultat est un fichier xps créé à partir du chemin de fichier de sortie.

```java
public static void ConvertSVG(SVGDocument source, XpsSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| source | SVGDocument | Source de conversion présentée par [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/). |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Chemin complet du fichier xps en tant que résultat de conversion. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Reportez-vous à [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) où vous trouverez des informations sur la façon de convertir SVG en XPS en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et sur la façon d'appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en XPS

La classe Converter propose plusieurs conversions spécifiques SVG vers XPS. Pour convertir SVG en XPS, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) gratuit en ligne qui convertit le SVG en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

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
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result");

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Formez le document SVG comme source de conversion
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
		// Initier le processus de conversion avec la configuration par défaut
		Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, String) {#convertsvg_23}

Convertir la source SVG présentée par [`URL`](../../../com.aspose.html/url/). Le résultat est un fichier xps créé à partir du chemin de fichier de sortie.

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | Document source SVG [`URL`](../../../com.aspose.html/url/) - fournit une représentation objet d'un identifiant universel (URL). |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Chemin complet du fichier xps en tant que résultat de conversion. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Reportez-vous à [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) où vous trouverez des informations sur la façon de convertir SVG en XPS en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et sur la façon d'appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en XPS

La classe Converter propose plusieurs conversions spécifiques SVG vers XPS. Pour convertir SVG en XPS, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) gratuit en ligne qui convertit le SVG en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // Créer une Url basée sur le chemin du fichier d’entrée
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, XpsSaveOptions, String) {#convertsvg_15}

Convertir la source SVG présentée par [`URL`](../../../com.aspose.html/url/). Le résultat est un fichier xps créé à partir du chemin de fichier de sortie.

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| url | Url | Document source SVG [`URL`](../../../com.aspose.html/url/) - fournit une représentation objet d'un identifiant universel (URL). |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Chemin complet du fichier xps en tant que résultat de conversion. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Reportez-vous à [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) où vous trouverez des informations sur la façon de convertir SVG en XPS en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et sur la façon d'appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en XPS

La classe Converter propose plusieurs conversions spécifiques SVG vers XPS. Pour convertir SVG en XPS, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) gratuit en ligne qui convertit le SVG en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

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
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### Voir aussi

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, XpsSaveOptions, String) {#convertsvg_39}

Convertir la source SVG présentée par le chemin complet du fichier en XPS. Le résultat est un fichier XPS créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source SVG. |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. |
| outputPath | String | Chemin complet du fichier xps en tant que résultat de conversion. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Reportez-vous à [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) où vous trouverez des informations sur la façon de convertir SVG en XPS en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et sur la façon d'appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en XPS

La classe Converter propose plusieurs conversions spécifiques SVG vers XPS. Pour convertir SVG en XPS, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) gratuit en ligne qui convertit le SVG en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### Voir aussi

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, String) {#convertsvg_31}

Convertir la source SVG présentée par le chemin complet du fichier en XPS. Le résultat est un fichier XPS créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourcePath | String | Chemin complet du fichier source SVG. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Chemin complet du fichier xps en tant que résultat de conversion. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Reportez-vous à [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) où vous trouverez des informations sur la façon de convertir SVG en XPS en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et sur la façon d'appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en XPS

La classe Converter propose plusieurs conversions spécifiques SVG vers XPS. Pour convertir SVG en XPS, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) gratuit en ligne qui convertit le SVG en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

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
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, XpsSaveOptions, String) {#convertsvg_55}

Convertir la source SVG présentée par du contenu en ligne en XPS. Le résultat est un fichier xps créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu SVG en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. |
| outputPath | String | Chemin complet du fichier xps en tant que résultat de conversion. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Reportez-vous à [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) où vous trouverez des informations sur la façon de convertir SVG en XPS en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et sur la façon d'appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en XPS

La classe Converter propose plusieurs conversions spécifiques SVG vers XPS. Pour convertir SVG en XPS, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) gratuit en ligne qui convertit le SVG en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulaire de contenu SVG en ligne
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Initier le processus de conversion
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### Voir aussi

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, String) {#convertsvg_47}

Convertir la source SVG présentée par du contenu en ligne en XPS. Le résultat est un fichier xps créé à partir du chemin du fichier de sortie.

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contenu | String | Chaîne en tant que contenu SVG en ligne. |
| baseUri | String | L'URI de base du document. Elle sera combinée avec le chemin du répertoire actuel pour former une URL absolue. |
| configuration | Configuration | La configuration de l'environnement. Représente l'objet de contexte [`configuration`](../../../com.aspose.html/configuration/) qui est utilisé pour configurer les paramètres d'environnement de l'application. |
| options | XpsSaveOptions | L'utilisation de l'objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) vous permet d'ajuster le processus de rendu. Pour plus d'informations, consultez [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options). |
| outputPath | String | Chemin complet du fichier xps en tant que résultat de conversion. |

## Remarques

Convertisseur SVG

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

Reportez-vous à [article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) où vous trouverez des informations sur la façon de convertir SVG en XPS en utilisant les méthodes ConvertSVG() de la classe [`Converter`](../) et sur la façon d'appliquer les paramètres [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) et [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/).

Convertir SVG en XPS

La classe Converter propose plusieurs conversions spécifiques SVG vers XPS. Pour convertir SVG en XPS, vous devez suivre l'un des scénarios simples composés de quelques étapes :

Source de conversion. Détectez un fichier SVG local existant ou une [`Url`](../../../com.aspose.html/url/) distante comme source de conversion. Vous pouvez également définir [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) comme source de conversion ou même utiliser du contenu SVG en ligne présenté par une source String. Résultat de la conversion. Définissez le chemin du fichier de sortie ou utilisez une implémentation d'interface [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) connue ou personnalisée comme tampon de données de sortie. Créez un nouvel objet [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) avec des paramètres spécifiques ou par défaut. Vous pouvez également ajouter [`configuration`](../../../com.aspose.html/configuration/) comme paramètre d'option. Utilisez la méthode ConvertSVG() de la classe Converter pour enregistrer le SVG en tant que résultat XPS avec trois paramètres ou plus selon le scénario de l'utilisateur. Convertisseur SVG en ligne

Aspose.HTML propose un [convertisseur SVG vers XPS](https://products.aspose.app/svg/en/conversion/svg-to-xps) gratuit en ligne qui convertit le SVG en XPS avec une haute qualité, de manière simple et rapide. Il suffit de télécharger, de convertir vos fichiers et d'obtenir les résultats en quelques secondes !

Code source

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net).

## Exemples

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // Formulaire de contenu SVG en ligne
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // Chemin du fichier résultat du formulaire
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // Définissez l'objet XpsSaveOptions par défaut
      var options = new XpsSaveOptions();

      // Initier le processus de conversion avec la configuration par défaut
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### Voir aussi

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
