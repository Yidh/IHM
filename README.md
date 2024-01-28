# ProjectHotel

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.0.8.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help.

## techno utiliséé

[nodejs] - (https://nodejs.org/en)
[ng neat effect ] -(https://ngneat.github.io/elf/) 
[date-fns]-(https://date-fns.org/)
[material]- (https://material.angular.io/)
[angular] -(https://angular.dev/)
Angular CLI: 17.0.8
Node: 20.10.0
Package Manager: npm 10.3.0
OS: win32 x64


## lancement

     Utilisez la commande pour installer les dépendences :

   ```bash
   npm install
   ```
   

## quelques explications:
# Utilisation des Auth Guards et Interceptors dans le projet Angular

Ce projet utilise des Auth Guards et des Interceptors fournis par Angular pour implémenter des fonctionnalités de sécurité et d'interception HTTP.

## Auth Guards

Les Auth Guards sont des classes utilisées pour contrôler l'accès aux routes dans une application Angular. Ils sont souvent utilisés pour protéger les routes qui nécessitent une authentification utilisateur.

Dans ce projet, les Auth Guards sont utilisés pour :

- Restreindre l'accès à certaines routes aux utilisateurs authentifiés.
- Rediriger les utilisateurs non authentifiés vers la page de connexion lorsqu'ils tentent d'accéder à des routes protégées.

Les Auth Guards peuvent être configurés dans le fichier de configuration des routes (`app-routing.module.ts`) en associant un Auth Guard spécifique à une route.

## Interceptors

Les Interceptors sont des services Angular utilisés pour intercepter les requêtes HTTP sortantes et entrantes. Ils permettent de modifier les requêtes avant leur envoi au serveur et les réponses avant qu'elles ne soient traitées par l'application.

Dans ce projet, les Interceptors sont utilisés pour :

- Ajouter des en-têtes d'authentification aux requêtes sortantes pour authentifier les utilisateurs auprès du serveur.
- Gérer les erreurs de connexion, telles que les jetons expirés ou les autorisations insuffisantes.

Les Interceptors sont configurés dans le module `AppModule` en fournissant une liste d'intercepteurs à l'aide de la méthode `HTTP_INTERCEPTORS`.




# Utilisation de @ngneat/effects dans Angular

Ce projet utilise `@ngneat/effects`, une bibliothèque qui fournit une manière élégante de gérer les effets secondaires dans les applications Angular utilisant NgRx.

## @ngneat/effects

`@ngneat/effects` permet de gérer les effets secondaires dans les applications Angular en fournissant une structure pour isoler les effets secondaires des composants et des réducteurs. Les effets secondaires comprennent les appels HTTP, les interactions avec le stockage local, la navigation, etc.

Dans ce projet, `@ngneat/effects` est utilisé pour :

- Gérer les appels HTTP pour récupérer et sauvegarder des données depuis et vers un serveur.
- Gérer les actions de navigation et effectuer des redirections conditionnelles en fonction de l'état de l'application.
- Gérer les interactions avec le stockage local, telles que l'écriture et la lecture des données dans le stockage local du navigateur.

`@ngneat/effects` permet de séparer les préoccupations liées aux effets secondaires de la logique de l'application principale, ce qui rend le code plus modulaire, testable et maintenable.

Pour configurer les effets dans une application Angular, vous devez :

1. Définir une classe d'effets qui implémente l'interface `Effect`.
2. Définir les effets à l'aide de de fonction spécifiques (`Effect`, `@ctions`, etc.).
3. Injecter les services nécessaires dans les effets et les manipuler en réponse aux actions.

Pour plus d'informations sur la configuration et l'utilisation de `@ngneat/effects`, veuillez consulter la documentation officielle : [NgRx Effects](https://ngneat.github.io/elf/).


# Utilisation de Angular Material

Ce projet utilise Angular Material, une bibliothèque UI pour Angular qui fournit un ensemble complet de composants d'interface utilisateur et de directives prêtes à l'emploi.

## Angular Material

Angular Material est une bibliothèque de composants UI conçue pour les applications Angular. Elle offre une collection de composants prêts à l'emploi pour créer des interfaces utilisateur modernes et réactives.

Dans ce projet, Angular Material est utilisé pour :

- Créer une interface utilisateur conviviale et esthétique.
- Utiliser des composants prêts à l'emploi tels que les boutons, les champs de formulaire, les dialogues, les cartes, etc.
- Assurer la cohérence du design et des interactions utilisateur dans toute l'application.

Pour plus d'informations sur Angular Material et la manière de l'intégrer à votre projet Angular, veuillez consulter la documentation officielle : [Angular Material](https://material.angular.io/).
