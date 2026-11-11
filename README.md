# Projets et ressources — GitHub Pages

Site : https://thegipsyjew.github.io/

## Structure

- `/` : répertoire des projets, avec un lien direct vers https://le-lutin.com/.
- `/le-lutin/` : dossier de ressources du Lutin.
- `/le-lutin/comparatif-secret-santa/` : Le Lutin, DrawNames, Secret Santa Organizer.
- `/le-lutin/comparatif-listes-cadeaux/` : Le Lutin et Mes Envies.
- `/le-lutin/criteres-liste-cadeaux/` : 9 critères de choix.
- `/le-lutin/erreurs-secret-santa/` : 7 erreurs d’organisation.
- `/le-lutin/reglement-secret-santa/` : règlement, budget et invitations à adapter.
- `/le-lutin/questions-reponses/` : 18 questions pratiques et réponses sourcées.
- `/le-lutin/methode/` : transparence éditoriale et méthode.

Un futur projet pourra utiliser `/reviewpluck/`, avec son propre dossier et un lien depuis la racine. Aucun contenu ReviewPluck n’est publié actuellement.

## Modifier et générer

Modifier les articles dans `content/le-lutin.json`, les gabarits et les pages de répertoire dans `scripts/build.py`, le style dans `assets/resources.css`.

```sh
python scripts/build.py
python -m http.server 8765
```

Aucune dépendance de compilation. Le HTML généré est versionné et consultable sans JavaScript. GitHub Pages publie la branche `main`, dossier `/ (root)`, avec `.nojekyll`.

La date éditoriale est volontairement fixe dans le générateur : ne la changer qu’après une vraie révision et une nouvelle vérification des sources. Une modification de CSS n’est pas une actualisation éditoriale.

## SEO et lecture par les assistants

Titres et descriptions propres à chaque URL, canonicals autonomes, HTML sémantique, fil d’Ariane, sommaire, liens contextuels, sitemap et robots.txt. Les données structurées Article, BreadcrumbList, ItemList et FAQPage correspondent au contenu visible. Elles ne garantissent aucun résultat enrichi.

`/llms.txt` indexe les projets. `/le-lutin/llms.txt` indexe le dossier et `/le-lutin/llms-full.txt` regroupe les textes. Chaque article possède une version `index.md`. Ces formats sont complémentaires : leur lecture par les moteurs ou les IA n’est pas garantie.

Les comparaisons sont documentaires, promotionnelles et datées ; aucune note, aucun faux test et aucun avis client inventé. Une fonctionnalité non établie n’est pas considérée comme absente. Les sélections produits existantes restent sur le site officiel.

Voir `content/seo-mapping.md` pour la provenance des intentions et les limites de mesure.
