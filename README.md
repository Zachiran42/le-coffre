# Le Coffre

[Télécharger l’APK](https://github.com/Zachiran42/le-coffre/releases/latest/download/le-coffre-0.1.0.apk) · [Versions](https://github.com/Zachiran42/le-coffre/releases) · [Page du jeu](https://zachiran42.github.io/le-coffre/)

Prototype Android8+, natif et universel, sans publicité ni permission, hors ligne. Licence MIT.

Huit choix, trois objets proposés à chaque fois. Sélectionne un objet, tourne-le et choisis son ancrage sur la grille4×4, puis POSER. Chaque forme a sa valeur. Tous les trois objets d’une même collection : bonus40. PASSER consomme un choix sans point, utile si les objets ne rentrent plus.

La tentative est enregistrée après chaque coup validé ; la pause et le record sont locaux. APK de développement, aucun téléphone physique testé.

## Compiler
Copier le modèle .toolchain.example.json en .toolchain.json avec JDK21, AndroidSDK36 et BuildTools36. Définir MINIGAMES_KEYSTORE_PASSWORD dans l’environnement et fournir une clé externe à scripts/build.ps1 -KeyStore ... -KeyAlias ... . Ne jamais publier les clés.

## Dans Cercle

Dans « Ajouter depuis GitHub », coller `https://github.com/Zachiran42/le-coffre`. La dernière Release contient un seul APK, signé, universel et sans permission Internet.

## Compilation

Copier `.toolchain.example.json` vers `.toolchain.json`, renseigner JDK21, Android SDK36 et Build Tools, puis définir `MINIGAMES_KEYSTORE_PASSWORD` dans l’environnement. Utiliser `scripts/build.ps1 -KeyStore C:/cles/jeu.keystore -KeyAlias votre-alias`. Garder les clés hors du dépôt.
