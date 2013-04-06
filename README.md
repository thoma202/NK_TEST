# Test structure Git NK

## Branches

### Branche "master"

Branche permanente qui contiendra uniquement les versions stables

### Branche "fix"

Branche permanente qui contiendra uniquement les corrections de bugs "critiques". Chaque commit devra être mergé avec la branche master ainsi que la branche develop

### Branche "develop"

Branche permanente qui contiendra uniquement la version actuellement en développement et fonctionnelle. Quand la version en d�veloppement arrivera � maturit� elle devra �tre merg�e avec la master et tager avec le N� de version.

### Branche "features_?"

Branche temporaires qui contiendra uniquement l'implantation d'un nouveau module, d'une nouvelle fonctionnalité.

Exemple de syntaxe :

* Pour le module News la branche s'appelera : features_news
* Pour l'ajout d'une fonction d'upload dans l'admin la branche s'appelera : features_admin_upload

Une fois qu'une branche feature_? est jugée stable et terminée elle devra être mergée avec la develop et supprimée

### Branche "bugs"

Branche permanente qui contiendra uniquement les corrections des bugs découverts sur la version en développement. Une fois un bug corrig�, la branche devra �tre merg�e avec la develop

**(En cours de rédaction)**
