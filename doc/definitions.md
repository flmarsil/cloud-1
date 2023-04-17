# Ansible 
Outil open source de gestion de configuration, d'automatisation de tâches et de déploiement d'applications. Il permet de déployer et de gérer des applications sur un grand nombre de serveurs de manière simultanée.

Voici les étapes pour comprendre comment Ansible fonctionne :

## Inventaire : 
Ansible utilise un inventaire pour identifier les serveurs sur lesquels il doit agir. L'inventaire est généralement stocké dans un fichier texte ou YAML.

## Playbooks : 
Les playbooks sont des fichiers YAML qui décrivent les étapes à suivre pour déployer une application ou effectuer une tâche sur un ou plusieurs serveurs. Ils sont composés de tâches qui doivent être exécutées sur les serveurs cibles.

## Modules : 
Ansible utilise des modules pour effectuer des actions sur les serveurs. Les modules sont des scripts ou des programmes qui sont exécutés sur les serveurs cibles. Ansible possède une grande bibliothèque de modules pour effectuer différentes actions.

## Connexion : 
Ansible se connecte aux serveurs cibles en utilisant SSH ou WinRM (Windows Remote Management). Cela permet à Ansible de se connecter à distance aux serveurs sans avoir besoin de logiciels supplémentaires sur les serveurs cibles.

## Exécution : 
Ansible exécute les tâches décrites dans les playbooks en utilisant les modules appropriés sur les serveurs cibles.

## Résultats : 
Ansible collecte les résultats des tâches exécutées sur les serveurs cibles et les stocke dans des fichiers de sortie. Cela permet de vérifier si les tâches ont été exécutées correctement ou non.

## En résumé :
Ansible utilise des playbooks pour décrire les actions à effectuer, des modules pour effectuer ces actions, et se connecte aux serveurs cibles pour exécuter les tâches et collecter les résultats.