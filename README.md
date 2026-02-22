# EF UE L316 - Diversification des langages

## Partie 1 : Questions

## Partie 2 : Web app _Symfony_

### Mise en place de l'environnement de développement

- Boilerplate Symfony WebApp

```bash
symfony new ef316 --webapp
```

- Installation du bundle _EasyAdmin_

```bash
composer require easycorp/easyadmin-bundle
```

- Mise en place d'un contrôleur et d'un template pour la page d'accueil

```bash
php bin/console make:controller HomeController
```
