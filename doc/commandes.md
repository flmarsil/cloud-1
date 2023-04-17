```bash
# create ssh key
ssh-keygen -o -a 100 -t ed25519 

# add key on remote server
ssh-copy-id root@212.227.13.69

# add agent to easyier connection
eval `ssh-agent`
ssh-add

# test configuration works
mysql -u flmarsil -p wordpress_db -h 212.227.13.69

docker exec -it mariadb mysql -u flmarsil -p wordpress_db
```

```bash
# vérifier les hosts
ansible-inventory -i 00_inventory.yml --list

# chiffrer le contenu d'un fichier
ansible-vault .env

# dechiffrer le contenu d'un fichier
ansible-vault decrypt .env

# changer le mot de passe du vault ansible
ansible-vault rekey
```