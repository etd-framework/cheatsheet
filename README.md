# Cheatsheet pour les bonnes pratiques chez ETD !




## Préparation automatique

Script PHP : [prepare_repo](https://github.etd-solutions.com/prepare_repo.php)
- Labels
- Templates Issues / PR

## Pipelines

Nom         | Description
----------- | -----------
New Issues  | Toutes les nouvelles issues créées arrivent ici. On doit les envoyer dans un autre pipeline dès que possible.
Icebox      | Les issues que l'on se garde pour plus tard : des idées, des choses que l'on ne fera pas tout de suite, ...
Backlog     | On ne travaille pas sur ces issues pour l'instant, mais on agit quand même sur elles. Si elles n'ont pas de `milestone` elles font parties du `Product Backlog` sinon du `Sprint Backlog`.
To Do       | Alimenté par les issues **bien définies**. Ce pipeline est le focus courant de l'équipe. Ces issues iront dans le pipeline `In Progress`, on les **classe** par priorité et on assigne les "garants" de la bonne réalisation.
In Progress | Ce pipeline répond à la question : "Sur quoi sommes-nous en train de travailler ?". Idéalement, chaque membre de l'équipe doit travailler sur une seule chose en même temps.
Done        | Les issues sont prêtes pour être mise en production ou staging.
Closed      | Ce sont les issues terminées.

## Labels

Thème         | Labels        | Description
------------- | ------------- | -------------
Plateforme    | ![](http://github.etd-solutions.com/label.php?text=framework&bg=BFD4F2&color=282C33) ![](http://github.etd-solutions.com/label.php?text=app&bg=BFD4F2&color=282C33) ![](http://github.etd-solutions.com/label.php?text=site&bg=BFD4F2&color=282C33) | Si le repo couvre plusieurs parties, on affiche où les issues "vivent" (ex: framework etd, app)
Problèmes     | ![](http://github.etd-solutions.com/label.php?text=bug&bg=EE3F46&color=fff) ![](http://github.etd-solutions.com/label.php?text=sécurité&bg=EE3F46&color=fff&1) ![](http://github.etd-solutions.com/label.php?text=prod&bg=EE3F46&color=fff) | Issues qui font que le produit est dégradé. Haute priorité, d'autant plus si c'est présent en production.
Ennuyeux      | ![](http://github.etd-solutions.com/label.php?text=corvée&bg=FEF2C0&color=333026&1) ![](http://github.etd-solutions.com/label.php?text=contenu&bg=FEF2C0&color=333026) | Remplir un site, réorganiser la structure des dossiers et autre tâche nécessaire (mais moins impactante).
Expérience    | ![](http://github.etd-solutions.com/label.php?text=design&bg=FFC274&color=372918) ![](http://github.etd-solutions.com/label.php?text=ux&bg=FFC274&color=372918) | Affecte la compréhension de l'utilisateur ou l'utilisation générale de l'appli. Cela peut être à la fois des changements ou des bugs UX.
Environnement | ![](http://github.etd-solutions.com/label.php?text=staging&bg=FAD8C7&color=332C28) ![](http://github.etd-solutions.com/label.php?text=tests&bg=FAD8C7&color=332C28) | Environnement serveur. Avec une bonne assurance qualité (QA), on identifira les bugs pendant les déploiement en tests et en staging.
Feedback      | ![](http://github.etd-solutions.com/label.php?text=discussion&bg=CC317C&color=fff) ![](http://github.etd-solutions.com/label.php?text=question&bg=CC317C&color=fff) ![](http://github.etd-solutions.com/label.php?text=besoin aide&bg=CC317C&color=fff) | A besoin de plus de discussion pour comprendre les étapes d'action. La plupart des nouveautés démarre ici.
Améliorations      | ![](http://github.etd-solutions.com/label.php?text=amélioration&bg=5EBEFF&color=132736) ![](http://github.etd-solutions.com/label.php?text=optimisation&bg=5EBEFF&color=132736) | Itérations sur des fonctionnalités ou infrastructure déjà existantes. Généralement ce la améliore la rapidité ou la qualité des résultats. Par ex: ajouter un champ "Propriétaire" dans un model "Calendrier" existant.
Ajouts      | ![](http://github.etd-solutions.com/label.php?text=fonction&bg=91CA55&color=243315) | Nouvelles fonctionnalités. Nouvelles pages, workflows, ...
En attente  | ![](http://github.etd-solutions.com/label.php?text=en cours&bg=FBCA04&color=332900) ![](http://github.etd-solutions.com/label.php?text=a surveiller&bg=FBCA04&color=332900) | Travail en cours, mais a besoin de quelques éléments avant. Une fonctionnalité qui a besoin d'une mise à jour d'une dépendency ou un bug qui nécessite plus de données.
Inactive  | ![](http://github.etd-solutions.com/label.php?text=invalide&bg=D2DAE1&color=2F3133) ![](http://github.etd-solutions.com/label.php?text=wontfix&bg=D2DAE1&color=2F3133) ![](http://github.etd-solutions.com/label.php?text=doublon&bg=D2DAE1&color=2F3133) ![](http://github.etd-solutions.com/label.php?text=en attente&bg=D2DAE1&color=2F3133) | Pas d'action requise ou possible. L'issue est soit corrigée, mieux définies dans une autre issue ou seulement en dehors du scope du projet.
Quick Fixes! | ![](http://github.etd-solutions.com/label.php?text=boum&bg=FFFF00&color=333300) ![](http://github.etd-solutions.com/label.php?text=45min&bg=FFFF00&color=333300) | Les issues qui peuvent être traitées rapidement !

## Templates Issues / PR

```md
## User Story

## Critères d'acceptation

- [ ] 
- [ ] 

## Définition de "Done"
