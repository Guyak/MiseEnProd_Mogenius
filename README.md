# Mise en ligne d'appli avec Mogenius
# Programme HTML simple basé sur template NginX

## TODO
**Ouvrir le lien** : https://miseenprod-mog-prod-td-applicloud-v0sf5k.mo4.mogenius.io/
La page index.html s'affiche bien

## Git repository
**Lien du repository comprenant le code source** : https://github.com/Guyak/Mogenius_MiseEnProd

## Difficultés rencontrées
### Tentative de connexion à une API
Premièrement tenté de me connecter à l'API créée pour le cours de FullStack

* Mise en place de variables d'environnement dans application.yaml, et renseignement sur Mogenius
![Sreenshot YAML](./images/yaml.PNG)
![Sreenshot Mogenius](./images/Mogenius_EV.PNG)

* Création de second service avec un template MySQL

* ***Problème rencontré*** => Le serveur distant créé par la base de donnée n'est pas accessible via MySQL malgré plusieurs modifications et tests

*Problème de host qui n'accepte pas de connection à distance*
