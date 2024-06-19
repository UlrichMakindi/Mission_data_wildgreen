# WildGreen

Mission Data sur Deux Jours pour la Société Fictive WildGreen
L'objectif est de créer un tableau de bord pour suivre l'évolution des différentes variables.

Nous avons d'abord nettoyé et préparé la base de données qui nous a été fournie. Nous avons commencé par grouper les différents pays par continent afin d'obtenir une vision plus globale. Ensuite, nous avons affiné les différentes métriques qui nous avaient été fournies, soit par nettoyage, soit par création d'agrégations.

Nous avons ensuite pris l'initiative de créer un modèle de prévisions grâce à ExponentialSmoothing de statsmodels. Il est utilisé notamment pour l'analyse de séries temporelles et le lissage exponentiel.

Après le nettoyage, nous avons fusionné toutes nos bases de données afin de créer un tableau de bord à partir de PowerBi (consultable en PDF dans le dossier).

Ce tableau de bord se compose de deux vues principales, puis d'une analyse plus détaillée des données environnementales et démographiques.

Il dispose d'un filtre par continent, par pays et par date, ce qui permet d'avoir un effet d'entonnoir.

Plusieurs types de visualisations ont été utilisés, et les données géographiques pour la visualisation par cartes ont été ajoutées.


