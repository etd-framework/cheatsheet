# Cheatsheet pour les bonnes pratiques chez ETD !

## Labels

Création automatique des labels sur un repo : [create_labels.sh](https://gist.githubusercontent.com/jbanety/b8077dfe87ee3c5aa9bd1735baceef8f/raw/create_labels.sh)

Thème         | Labels        | Description
------------- | ------------- | -------------
Plateforme    | ![](http://github-labels.etd-solutions.com/?text=framework&bg=BFD4F2&color=282C33) ![](http://github-labels.etd-solutions.com/?text=app&bg=BFD4F2&color=282C33) | Si le repo couvre plusieurs parties, on affiche où les issues "vivent" (ex: framework etd, app)
Problèmes     | ![](http://github-labels.etd-solutions.com/?text=bug&bg=EE3F46&color=fff) ![](http://github-labels.etd-solutions.com/?text=sécurité&bg=EE3F46&color=fff&1) ![](http://github-labels.etd-solutions.com/?text=prod&bg=EE3F46&color=fff) | Issues qui font que le produit est dégradé. Haute priorité, d'autant plus si c'est présent en production.
Ennuyeux      | ![](http://github-labels.etd-solutions.com/?text=corvée&bg=FEF2C0&color=333026&1) ![](http://github-labels.etd-solutions.com/?text=contenu&bg=FEF2C0&color=333026) | Remplir un site, réorganiser la structure des dossiers et autre tâche nécessaire (mais moins impactante).
Expérience    | ![](http://github-labels.etd-solutions.com/?text=design&bg=FFC274&color=372918) ![](http://github-labels.etd-solutions.com/?text=ux&bg=FFC274&color=372918) | Affecte la compréhension de l'utilisateur ou l'utilisation générale de l'appli. Cela peut être à la fois des changements ou des bugs UX.
Environnement | ![](http://github-labels.etd-solutions.com/?text=staging&bg=FAD8C7&color=332C28) ![](http://github-labels.etd-solutions.com/?text=tests&bg=FAD8C7&color=332C28) | Environnement serveur. Avec une bonne assurance qualité (QA), on identifira les bugs pendant les déploiement en tests et en staging.
Feedback      | ![](http://github-labels.etd-solutions.com/?text=discussion&bg=CC317C&color=fff) ![](http://github-labels.etd-solutions.com/?text=question&bg=CC317C&color=fff) ![](http://github-labels.etd-solutions.com/?text=besoin aide&bg=CC317C&color=fff) | A besoin de plus de discussion pour comprendre les étapes d'action. La plupart des nouveautés démarre ici.
Améliorations      | ![](http://github-labels.etd-solutions.com/?text=amélioration&bg=5EBEFF&color=132736) ![](http://github-labels.etd-solutions.com/?text=optimisation&bg=5EBEFF&color=132736) | Itérations sur des fonctionnalités ou infrastructure déjà existantes. Généralement ce la améliore la rapidité ou la qualité des résultats. Par ex: ajouter un champ "Propriétaire" dans un model "Calendrier" existant.
Ajouts      | ![](http://github-labels.etd-solutions.com/?text=fonction&bg=91CA55&color=243315) | Nouvelles fonctionnalités. Nouvelles pages, workflows, ...
