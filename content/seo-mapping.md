# Intention, provenance et répartition des contenus

Analyse du 11 novembre 2026, à partir du dossier fourni `christmas-wishlist/docs/seo-noel-2026`, audit du 13 octobre 2026, France/français. Aucun nouvel appel DataForSEO n’a été effectué. Les pages officielles des services ont été vérifiées le 11 novembre 2026.

## Repères quantitatifs

Source : `donnees/initial/mots-cles.csv`, `audit/strategie-editoriale.md` et les réponses DataForSEO sous-jacentes. Les moyennes sont les estimations du fournisseur, non des objectifs de trafic. Novembre/décembre correspondent à 2025. Ne pas additionner des variantes dont les audiences se recoupent.

| Requête | Moyenne mensuelle | Novembre 2025 | Décembre 2025 | Affectation |
|---|---:|---:|---:|---|
| application secret santa | 1 300 | 8 100 | 6 600 | comparatif-secret-santa |
| liste de noel en ligne | 590 | 3 600 | 1 600 | comparatif-listes-cadeaux et critères complémentaires |
| liste de noël partagée | 40 | 320 | 40 | guide officiel conservé, liens depuis les ressources |
| règles secret santa | 110 | 480 | 720 | règlement et modèles originaux |
| tirage au sort avec exclusion | 70 | 390 | 260 | section des erreurs et critère du comparatif |
| cadeau secret santa 10 euros | 1 600 | 6 600 | 12 100 | sélection existante sur le-lutin.com, lien contextuel |

La collecte contient 443 expressions distinctes dont 361 avec volume. Ce ne sont ni 443 intentions distinctes ni des questions effectivement observées dans les LLM. Les questions de la FAQ sont des formulations éditoriales issues des fonctions documentées. La couverture n’est pas exhaustive.

## Contenu complémentaire

Le sitemap de production a confirmé que les guides liste familiale, liste enfant, Secret Santa, bureau et la sélection à moins de 10 € sont déjà publiés. Ils ne sont pas recopiés sur GitHub Pages. Les nouvelles pages apportent des critères de décision, deux comparatifs nominatifs, une liste d’erreurs et des modèles. La FAQ regroupe les contraintes produit pour éviter une URL mince par question.

La racine du site héberge les projets avec un backlink direct vers le-lutin.com. Le dossier /le-lutin/ assure la navigation thématique. Les futures ressources d’autres projets doivent utiliser un autre préfixe et des liens réellement utiles à leurs lecteurs.

## Comparaisons et sources

- Le Lutin : https://le-lutin.com/
- DrawNames : https://www.drawnames.fr/secret-santa
- Secret Santa Organizer : https://www.secretsantaorganizer.com/fr (lecture web ; accès HTTP direct refusé 403 dans l’environnement)
- Mes Envies : https://www.mesenvies.fr/liste-noel.html

Les données des éditeurs sur leurs propres services sont distinguées de notre recommandation. Pas de test utilisateur complet, pas d’audit sécurité, pas de classement absolu. Ne pas reprendre le discours d’un concurrent sur un autre comme preuve.

## Mesure à prévoir

Search Console pour les impressions, clics et indexation du sous-domaine ; analyse séparée des clics sortants vers le site officiel si une mesure est ajoutée. Aucun analytics ni cookie ajouté ici. Évaluer la visibilité sur un ensemble stable de questions sans attribuer automatiquement une variation à ces pages.

Plusieurs URL du même sous-domaine ne créent pas plusieurs domaines référents. Aucune hausse de DR, indexation ou citation IA n’est garantie. Le sous-domaine github.io n’hérite pas automatiquement de l’autorité de github.com.
