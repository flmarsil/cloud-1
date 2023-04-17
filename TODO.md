# Installer un site WordPress simple sur une instance

- Le déploiement de votre application doit être entièrement automatisé (Ansible) ✅

- Le site doit redémarrer automatiquement si le serveur est redémarré ✅

- Deployer le site sur un deuxieme serveur et verifier que le site est identique ✅

- Possibilité de relancer les containers séparement par service ✅

- En cas de redémarrage toutes les données du site sont persistantes ✅

- Il est possible de déployer votre site sur plusieurs serveurs en parallèle. ✅

- Le script doit pouvoir fonctionner de manière automatisée avec pour seule hypothèse
un OS de type ubuntu 20.04 LTS de l'instance cible faisant tourner un daemon SSH et
avec Python installé. ✅

- Vos applications seront exécutées dans des conteneurs séparés qui peuvent communiquer entre eux ✅

- L'accès public à votre serveur doit être limité et sécurisé (par exemple, il n'est pas
possible de se connecter directement à votre base de données depuis Internet) ✅

- Les services seront les différents composants d'un WordPress à installer par vous-même. (Phpmyadmin, MySQL ...etc) ✅

- Vous devez avoir un docker-compose.yml. ✅

- Vous devrez vous assurer que votre base de données SQL fonctionne avec WordPress et PHPMyAdmin. ✅

- Votre serveur doit être capable, lorsque cela est possible, d'utiliser TLS. ✅

- Vous devrez vous assurer que, selon l'URL demandée, votre serveur redirige vers le bon site. ✅

