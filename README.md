# EF UE L316 - Diversification des langages

URL du dépôt [https://github.com/filkat34/ef316](https://github.com/filkat34/ef316)

## Partie 1 : Questions

### Question 1

Une application _Symfony_ suit une architecture SSR (Server Side Rendering) ce qui veut dire que le rendu des templates TWIG se fait dans le backend. Plus précisément :

1. L'utilisateur déclenche une requête au backend (GET, POST, DELETE, PUT, etc)

2. La requête arrive dans le backend et est gérée par le contrôleur correspondant à l'URL

3. La logique pour le traitement demandé par l'utilisateur est exécutée par le contrôleur côté serveur et les requêtes en base de données passent souvent par l'ORM doctrine intallé par défaut dans un projet _Symfony_

4. Le cotrôleur fait appel au moteur de template TWIG pour rendre le résultat de la requête côté front end.*

### Question 2

Le cache de Symfony comme tout cache sert à stocker des données appelées à être réutilisées : cela permet d'améliorer les performances pour éviter leur réexécution mais peut parfois poser des problèmes en développement ; c'est pour cela qu'il est recommandé de vider le cache à chaque changement majeur dans un projet afin de ne pas réutiliser des données obsolètes.