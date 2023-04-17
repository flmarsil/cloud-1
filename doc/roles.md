L'arborescence de base pour un rôle Ansible est la suivante :

```bash
roles/
   myrole/
      tasks/
         main.yml
      handlers/
         main.yml
      files/
         myfile.conf
      templates/
         mytemplate.conf.j2
      vars/
         main.yml
      defaults/
         main.yml
      meta/
         main.yml
```
`tasks/` : Ce dossier contient le ou les fichiers YAML qui contiennent les tâches à effectuer. Le fichier principal est main.yml.

`handlers/` : Ce dossier contient les handlers, qui sont des tâches qui sont déclenchées en réponse à des événements générés par d'autres tâches. Le fichier principal est main.yml.

`files/` : Ce dossier contient les fichiers à copier sur les hôtes cibles. Par exemple, des fichiers de configuration ou des scripts à exécuter. Ces fichiers peuvent être utilisés par les tâches du rôle.

`templates`/ : Ce dossier contient les fichiers de templates Jinja2 qui sont utilisés pour générer des fichiers de configuration. Les templates sont souvent utilisés pour générer des fichiers de configuration dynamiquement en fonction des variables définies pour le rôle.

`vars`/ : Ce dossier contient les fichiers YAML qui définissent les variables utilisées par le rôle.

`defaults`/ : Ce dossier contient les fichiers YAML qui définissent les valeurs par défaut pour les variables utilisées par le rôle.

`meta`/ : Ce dossier contient les fichiers YAML qui fournissent des informations sur le rôle, telles que le nom, la description et les dépendances.

Il est important de noter que tous ces dossiers sont facultatifs. Selon les besoins spécifiques du rôle, il peut être nécessaire d'utiliser certains d'entre eux et pas d'autres. De plus, il est possible de créer des dossiers supplémentaires pour inclure des fichiers spécifiques au rôle. Par exemple, si le rôle nécessite l'installation de packages supplémentaires, vous pouvez créer un dossier packages et y inclure les fichiers YAML nécessaires.