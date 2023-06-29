# BULMA VEILLE TECHNOLOGIQUE #

![bulma](bulma.png.png)
## Introduction : ##

Bulma est un framework CSS open source qui offre une approche moderne et flexible pour la création de mises en page responsives. Il est devenu très populaire en raison de sa simplicité, de sa légèreté et de sa facilité d'utilisation.


## Pourquoi BULMA ? ##

- 100 % réactif conçu pour être mobile d'abord

- Modulaire obligeant uniquement les développeurs à importer uniquement ce qui est nécessaire

- Construction moderne avec Flexbox

- Personnalisation complète en définissant des variables SASS avant l'importation

- Aucun JavaScript requis - CSS s'intégrant uniquement dans n'importe quel environnement JS

- Gratuit avec une grande communauté open source. Disponible sur GitHub


## Bulma VS Bootstrap ##

1. Complexité : Bulma se distingue par sa simplicité. Il n'impose pas de styles prédéfinis et offre une grande flexibilité pour personnaliser les composants. En revanche, Bootstrap propose un ensemble complet de styles prédéfinis, ce qui peut être pratique pour les développeurs qui souhaitent une solution prête à l'emploi sans avoir à personnaliser chaque détail.

2. Taille du fichier : Bulma est plus légère que Bootstrap en termes de taille de fichier. Bulma utilise une approche modulaire où vous pouvez importer uniquement les composants nécessaires, ce qui permet de réduire la taille finale du code CSS. Bootstrap, en revanche, inclut un ensemble complet de styles et de fonctionnalités, ce qui se traduit par des fichiers plus volumineux.

3. Personnalisation : Bulma offre une plus grande liberté de personnalisation. Vous pouvez facilement modifier les variables Sass pour personnaliser les couleurs, les polices et d'autres aspects du framework. Bootstrap propose également des options de personnalisation, mais elles peuvent être plus limitées par rapport à Bulma.

4. Communauté et écosystème : Bootstrap a une communauté et un écosystème très développés. Il existe de nombreux thèmes, extensions, plugins et ressources disponibles pour Bootstrap, ce qui facilite la mise en place rapide de projets. Bien que Bulma ait également une communauté active, l'écosystème et le nombre de ressources supplémentaires disponibles peuvent être moins vastes que pour Bootstrap.

Vous retrouverez toutes ses infos sur le site : https://bulma.io/alternative-to-bootstrap/

La décision entre Bulma et Bootstrap dépendra de vos besoins spécifiques. Si vous recherchez une solution légère, flexible et hautement personnalisable, Bulma peut être un bon choix. En revanche, si vous avez besoin d'un framework plus complet avec des styles prédéfinis et un écosystème établi, Bootstrap peut être plus adapté à vos besoins.

### Voici un exemple simple de code HTML utilisant Bulma : ###

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bulma@0.9.3/css/bulma.min.css">
  <title>Exemple avec Bulma</title>
</head>
<body>
  <section class="section">
    <div class="container">
      <h1 class="title">Titre de la page</h1>
      <p class="subtitle">Sous-titre de la page</p>
      <div class="columns">
        <div class="column">
          <div class="notification is-primary">
            <p class="title is-4">Colonne 1</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          </div>
        </div>
        <div class="column">
          <div class="notification is-info">
            <p class="title is-4">Colonne 2</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</body>
</html>
```

### Voici un exemple similaire en utilisant Bootstrap : ###

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css">
  <title>Exemple avec Bootstrap</title>
</head>
<body>
  <section class="section">
    <div class="container">
      <h1 class="display-4">Titre de la page</h1>
      <p class="lead">Sous-titre de la page</p>
      <div class="row">
        <div class="col-md-6">
          <div class="alert alert-primary" role="alert">
            <h4 class="alert-heading">Colonne 1</h4>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          </div>
        </div>
        <div class="col-md-6">
          <div class="alert alert-info" role="alert">
            <h4 class="alert-heading">Colonne 2</h4>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</body>
</html>
```



