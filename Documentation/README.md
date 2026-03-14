# Documentation - Assistant d'Arbitrage

## Vue d'ensemble
Système d'arbitrage composé de deux cartes Arduino Uno communicant par XBee.

### Carte 1 : Écran & Clavier
- **Processeur** : Arduino Uno
- **Composants** :
  - Écran TFT (affichage des résultats)
  - Clavier 4x4 (entrée utilisateur)
- **Responsabilités** :
  - Affichage de l'interface
  - Gestion des entrées utilisateur
  - Envoi des données via XBee

### Carte 2 : XBee
- **Processeur** : Arduino Uno
- **Composants** :
  - Module XBee (communication sans fil)
- **Responsabilités** :
  - Réception des données de la Carte 1
  - Traitement des données
  - Retour d'information

## Communication
- **Protocole** : XBee (à définir)
- **Vitesse baud** : 9600

## Notes de développement
À remplir au fur et à mesure du projet...
