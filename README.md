# Projet Home Assistant avec ChatGPT

Ce projet vise à créer un Home Assistant connecté à ChatGPT, permettant aux utilisateurs d'interagir avec le système en utilisant une commande vocale ("Hey Flash"). Le Home Assistant pourra répondre à une variété de requêtes formulées par l'utilisateur en utilisant le traitement du langage naturel fourni par le modèle ChatGPT d'OpenAI.


## Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants :

- Raspberry Pi (de préférence Raspberry Pi 4 ou supérieur)
- Microphone USB ou un module microphone compatible avec Raspberry Pi
- Haut-parleur ou un module audio compatible avec Raspberry Pi
- Connexion Internet active
- Compte OpenAI pour accéder à l'API de ChatGPT
- Environnement Python avec les dépendances nécessaires (liste dans `requirements.txt`)

## TODO

- [x] Mise en place du modèle de Wake Up Word Recognition pour détecter la commande vocale "Hey Flash".
- [ ] Intégration du modèle de Voice Activity Detection pour identifier la fin de la requête de l'utilisateur.
- [ ] Ajout du modèle de Speech-to-text pour convertir les commandes vocales en texte.
- [ ] Intégration de l'API ChatGPT pour traiter les requêtes en texte et obtenir les réponses de ChatGPT.
- [ ] Mise en place du modèle Text-to-speech pour lire les réponses de ChatGPT à haute voix.
- [ ] Tests et débogage du système complet.
- [ ] Amélioration de la gestion des erreurs et des exceptions.
- [ ] Documentation complète du projet et mise à jour du README.
- [ ] Création d'un GIF animé ou d'une vidéo de démonstration pour le README.
