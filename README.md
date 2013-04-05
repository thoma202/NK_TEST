# Test structure Git NK

## Branches

### Branche "master"

Branche permanente qui contiendra uniquement les versions stables

### Branche "fix"

Branche permanente qui contiendra uniquement les corrections de bugs "critiques". Chaque commit devra �tre merg� avec la branche master ainsi que la branche develop

### Branche "develop"

Branche permanente qui contiendra uniquement la version actuellement en d�veloppement et fonctionnelle. Quand la version en d�veloppement arrivera � maturit� elle devra �tre merg�e avec la master et tager avec le N� de version.

### Branche "features_?"

Branche temporaires qui contiendra uniquement l'implantation d'un nouveau module, d'une nouvelle fonctionnalit�.

Exemple de syntaxe :

* Pour le module News la branche s'appelera : features_news
* Pour l'ajout d'une fonction d'upload dans l'admin la branche s'appelera : features_admin_upload

Une fois qu'une branche feature_? est jug�e stable et termin�e elle devra �tre merg�e avec la develop et supprim�e

### Branche "bugs"

Branche permanente qui contiendra uniquement les corrections des bugs d�couverts sur la version en d�veloppement. Une fois un bug corrig�, la branche devra �tre merg�e avec la develop

**(En cours de r�daction)**