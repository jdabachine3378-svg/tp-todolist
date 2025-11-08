## Projet: 📝 To-Do List Interactive (TP React)
author: Jamila Dabachine
project_type: React SPA (Single Page Application)
university: ENS Marrakech
module: Technologies Web / React JS
date: 2025-11

# description: |
  Ce projet a été réalisé dans le cadre du TP React.
  Il permet de consolider les notions fondamentales de React :
  - Création de composants fonctionnels
  - Gestion du state avec useState
  - Gestion des événements utilisateurs
  - Intégration de styles et ressources
  - Navigation (extension possible avec React Router)

# objectives:
  - Ajouter des tâches
  - Cocher et décocher les tâches terminées
  - Supprimer des tâches
  - (Optionnel) Modifier une tâche existante
  - (Optionnel) Appliquer un style Bootstrap ou Tailwind CSS

# structure:
  src/
    components/
      - TodoForm.js
      - TodoItem.js
      - TodoList.js
    App.js
    index.js
    App.css
    <img width="466" height="695" alt="image" src="https://github.com/user-attachments/assets/a4b7d8eb-9e9e-4cba-897f-084afd9ecab6" />


## installation:
  steps:
    - Installer Node.js et npm
    - Créer le projet : `npx create-react-app tp-todolist`
    - Se déplacer dans le dossier : `cd tp-todolist`
    - Lancer le serveur : `npm start`

# dependencies:
  - react: ^18.x
  - react-dom: ^18.x
  - bootstrap: (optionnel)
  - tailwindcss: (optionnel)

# usage:
  commands:
    - Démarrer le projet : `npm start`
    - Compiler pour la production : `npm run build`

# main_components:
  # - TodoForm:
      role: Formulaire d’ajout de nouvelles tâches.
      hooks: useState
  # - TodoList:
      role: Liste affichant toutes les tâches.
      props: taches, changerEtat, supprimerTache
 # - TodoItem:
      role: Élément individuel avec cases à cocher et suppression.
      features: checked binding, textDecoration conditionnelle
  # - App:
      role: Composant racine gérant l’état global des tâches.
<img width="1755" height="848" alt="image" src="https://github.com/user-attachments/assets/aad2dc7f-12f5-4b85-90aa-6c3cfbdc7517" />


# functions:
  # ajouterTache:
    description: Ajoute une tâche dans la liste.
    params: texte
 #  changerEtat:
    description: Inverse le statut "terminée" d'une tâche.
    params: id
#  supprimerTache:
    description: Supprime une tâche selon son identifiant.
    params: id



# screenshots:
  - todoform.png
  - todolist.png
  - app-interface.png

# remarks: |
  Ce projet forme la base pour la compréhension de React et de ses hooks.
  Il illustre le fonctionnement du rendu dynamique et des états contrôlés.
  Vous disposez maintenant d’une structure prête pour aller plus loin avec :
  - React Router
  - useEffect
  - gestion API (fetch/axios)

# credits:
  - Étudiante: Jamila Dabachine
  - Encadrant: M. Lachgar
  - Établissement: ENS Marrakech

version: 1.0
license: MIT
