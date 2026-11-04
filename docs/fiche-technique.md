# Fiche Technique : EKO LINK

## 1. Pages
Les pages prévues sont :
- Accueil : présentation de la plateforme et accès aux missions.
- Missions : consultation des missions disponibles possibilité de les filter.
- Détail d’une mission : informations et modalités d’inscription.
- Associations : permettre aux associations de publier une missions et d'avoir l'histoire de celles existantes.
- Connexion / inscription : permettre à l’utilisateur de s’identifier ou de créer un compte.
- Mon espace : historique des inscriptions, le suivi des heures, des niveaux et du nombre de missions effectuées.
- Assistant : un petit qustionnaire à réponse fermée afin de déterminer le type de mission qui convient le mieux à l'étudiant.


## 2. Composants
Les éléments réutilisables sont : 
- le menu de navigation
- le pied de page
- les cartes de mission
- les boutons
- les champs de formulaire
- le logo 


## 3. Gestion des contenus et des médias
- Textes : titres, descriptions des missions, consignes et informations des associations.
- Images : photos de missions, visuels de présentation, logos et illustrations.
- Informations de mission : nom, description, type, lieu, date, durée et nombre de places.
Mode de gestion : contenu écrit dans le code, fichiers Word, WordPress.


## 4. Gestion des états
Les états à gérer concernent la connexion, les formulaires, l’inscription à une mission,
la disponibilité des places et les retours d’erreur ou de confirmation.
- Connexion : connecté / non connecté
- Inscription à une mission : en cours, confirmée.
- Formulaires : champs remplis, champs manquants, validation et retour utilisateur.
- Disponibilité : nombre places encore disponibles.


## 5. Données dynamiques et API
Pour ce qui est de cette partie, rien n'est encore sûr ce sont juste des idées.
Les données susceptibles d’être dynamiques sont les cartes missions, leurs dates, leurs lieux,
leurs statuts et le nombre de places. 
Si aucune API n’existe encore, une évolution possible vers une API qui permetterait d'intéger une carte maps interactive au site afin d'y retrouver visuellement toutes les missions.


## 6. Fonctionnalité IA
Une fonctionnalité envisagée serait un coach perso.
L’étudiant répond à un formulaire de 4-8 questions fermées, l'ia lui propose ensuite deux types de missions qui lui correspond le plus ainsi que 4 missions (2 de chaque types si possible) qui existe déjà la page mission.