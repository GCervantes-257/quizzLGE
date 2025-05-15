Petite appli web pour réaliser des quizz en lien avec les niveaux d'arbitrage de la Fédération Française de Baseball et de Softball.

Initialement prévue pour servir au sein de la Commission Régionale d'Arbitrage de la Ligue Grand Est (CRA LGE), l'application à vocation à être accessible rapidement et simplement (aucune installation, aucun temps de chargement).

J'ai souhaité quelque chose de très simple et très réactif (un clic, ou deux avant d'arriver aux questions), qui s'adapte aux ordinateurs et surtout aux mobiles.

Une fois le niveau choisi, l'application sélectionne 10 questions aléatoires regroupées par niveaux officiels de la FFBS. L'utilisateur sait à tout moment quel diplôme il prépare ou révise.

Pour l'instant, le projet est en phase de test.

L'architecture repose sur :
- un index html (la page web)
- une base de données questions/réponses (formulaire google sheet publié au format .csv)
- un dossier contenant les illustrations (hébergement Postimages)

L'index est relativement prêt. Pour l'instant, est principalement complété le niveau AF1BS afin de réaliser des tests.

La base de données reste à travailler. Pour cette phase de test, elle a été en partie nourrie par chatgpt (à affiner donc). Je suis actuellement en train d'ajouter une colonne "theme" qui facilitera le travail de ceux qui vont l'abonder par la suite.
J'espère pouvoir monter une petite communauté à cet effet, et j'ai eu l'info qu'il y a des ressources sur la page FB de la CRA Grand Est.

Je vais également ajouter une thématique spéciale UC règles.

Je suis preneur des retours et je pense que je vais monter une petite communauté pour bosser ce projet (peut être même au niveau national).

L'objectif restera de pouvoir mettre à jour rapidement et simplement la base de données.

Suggestions de développement :

  Index :
  - [Fait] Ajouter un logo au-dessus du quizz (au-dessus du choix du quizz)
  - [Fait] Ajouter un encart expliquant brièvement le rôle de l'application et en particulier le public destinataire (en-dessous de la sélection du quizz pour éviter d'avoir à scroller quand on est un habitué ?)
  - Ajouter le module UC règles
  - Ajouter un lien vers les bulletins de la FFBS au sujet de l'arbitrage (en-dessous du choix du quizz)
  - Ajouter d'autres liens utiles
  - Références légales ? Liccence ? Réutilisation ?
  - Envisager d'intégrer des vidéos
    
  Base de données :
  - Achever de compléter la partie theme en fonction des classements utilisés par la FFBS
  - Vérifier la cohérence avec les questions
  - Développer davantage la section "Mécanique à deux" de l'AF1BS
  - Développer les questions relatives aux appels
  - Envisager d'intégrer des vidéos

  Postimages :
  - Récupérer ou fabriquer un modèle avec les positions théoriques des arbitres sur le terrain (plaque avec la zone d'observation éventuelle, mais surtout arbitre de base A, B, C et zone de travail)
