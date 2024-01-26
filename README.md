# Projet Ansible Mastodon 

Membre du groupe : 
- Ahamadou Yaya GBANE
- Soumaila COULIBALY
- Serigne Saliou SECK


## Usage

```
ansible-playbook mastodon-main.yml
```
Comment l'utiliser : 

- Etape 1 : Mettre en place un environmment (machines) avec    acces ssh sans mot de pass
                

- Etape 2 : déploiement "principal" : 
                  ansible-playbook mastodon-main.yml

## Notes

Dans ce projet vous avez plusieurs roles

- common : Pour mettre en place 
- postgresql : Pour la configuration de POSTGRESQL
- yarn-nodejs : YARN et NODEJS 
- ruby : Pour Installation de Ruby
- mastodon
- proxy : Pour Configuration de nginx



## Difficultés rencontrés 

- Lors de la création d'un utilisateur postgres dans le role postgresql ; Utilisateur non privilégié

- Ruby : non Idempotents

- connexion refusée lors des telechargement de fichier en ligne 