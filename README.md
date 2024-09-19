# Niveau_0 : API DE CITATIONS :

1. Le backend a été construit avec NodeJs, ExpressJS et se connecte bien à la base de données en MongoDB.
2. Il y a bien 3 endpoints différents: un GET pour lister toutes les citations présentes dans l'App, un POST pour ajouter une citation manuellement en fournissant la "citation" (le texte) et l'Auteur (j'ajouterias les sources par la suite de manière à avoir un champ facultatif).
3. L'Application possède bien 2 composants (écrans) en VueJS3 qui se mettent à jour à l'ajout ou suppression directement sans recharger la page. Par la suite je développerais le visuel, ainsi que l'utilisation de TailwindCSS pour mettre en forme et en disposition plus élaborée.
4. J'ai fourni la collection de ma base de données (avec 10 entrées) afin d'avoir un exemple concret et de pratiquer la connexion : la base de données est "dbtest" et la collection s'intitule : "citationsDB".

# Pour lancer ne pas oublier de faire npm install.

Pour lancer le frontend : npm run dev.
Pour le backend: node server.js.
Pour la base de données les informations sont au dessus. (créer la base "dbtest") et la collection à copier porte le nom "citationsDB".
J'ai fourni une capture d'écran afin de voir comment elle s'organise ou pour illustrer en vrai.

**_ N'hésitez pas à alimenter la base de données avec des citations d'Animes, de Séries, Films, Auteurs littéraires, ou toutes autres sources bien inspirantes. _**
