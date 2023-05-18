## Installation d'un environnement virtuel Python sur Linux ( Pipenv )
---
- Mise à jour Pip  
`pip install --upgrade pip`

- Installation de Pipenv  
`pip install pipenv`
---
---
## Option de Pipenv  
 - check  
  
    > Vérifie les vulnérabilités de sécurité de PyUp Safety et les marqueurs PEP 508 fournis dans Pipfile. PEP 508 fournis dans Pipfile.  
---
  - clean  

    > Désinstalle tous les paquets non spécifiés dans Pipfile.lock.
---
- graph  
  
    > Affiche les informations du graphe de dépendances actuellement installé.
---
- install  
  
    > Installe les paquets fournis et les ajoute au fichier Pipfile, ou (si aucun paquet n'est fourni), installe tous les paquets à partir du fichier Pipfile.
---
- lock  
  
    > Génère Pipfile.lock.
---
- open  

    > Affiche un module donné dans votre éditeur.
---
- requirements  

    > Génère un requirements.txt à partir de Pipfile.lock.
---
- run  

    > Lance une commande installée dans la virtualenv.
---
- scripts  

    > Liste les scripts dans la configuration de l'environnement actuel.
---
- shell 

    > Lance un shell dans l'environnement virtuel.
---
- sync 

    > Installe tous les paquets spécifiés dans Pipfile.lock.
---
- uninstall  

    > Désinstalle un paquet fourni et le supprime du Pipfile.
---
- update  

    > Exécute lock, puis sync.  
---
- upgrade  

    > Résout les paquets fournis et les ajoute au Pipfile, ou (si aucun paquets n'est fourni), fusionne les résultats dans Pipfile.lock
---
- verify  

    > Vérifie que le hachage dans Pipfile.lock est à jour.
---
- Savoir ou se situe le répertoire de son environnement  
    `pipenv --venv` ( Etre dans dans son projet pour éxécuter la commande )
---
---
## Créer un environnement virtuel  
1. Créer le dossier du projet  
`mkdir nom_du_projet`
2. Se rendre dans le dossier du projet  
`cd nom_du_projet`
3. Créer un dossier d'environnement ".venv"  
`mkdir .venv`
4. Installer l'environnement pipenv  
`pipenv install` 
5. Activer l'environnement du projet  
`pipenv shell`
---

