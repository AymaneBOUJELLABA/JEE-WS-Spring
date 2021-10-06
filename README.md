# TP_GitLab

## M2 DOSI TP



### Un fichier .yml
un fichier .yml est écrit en language YAML, qui sert à enregistrer les informations ( serialization ) sous une
format lisible et structuré.


### le fichier gitlab-ci.yml
et un fichier qAML qui s'execute à chaque commit, qui permet de lancer un runner pour éxecuter une tâche 
spécifique

### un runner
est un agent qui travaille avec gitlab CI/CD permet de lancer les spécifier dans le fichier .yml

### stages of a runner

#### .pre   : étape avant l'étape de compilation ( initialisation )
#### build  : étape qui permet de compiler et executer tous les tâches necessaire pour creer l'application
#### test   : étape qui permet de tester les fonctionalité de l'application
#### deploy : étape qui permet de lancer les 
#### .Post

All jobs in build execute in parallel.
If all jobs in build succeed, the test jobs execute in parallel.
If all jobs in test succeed, the deploy jobs execute in parallel.
If all jobs in deploy succeed, the pipeline is marked as passed.


