![Seuil d'intervention des acariens _page-0001](https://github.com/user-attachments/assets/b11660af-3182-470f-b021-90499fd1873e)# Seuil-d-intervention-contre-les-acariens
Il s'agit d'une application développée sur AppSheet à partir de feuilles de calcul codées en JavaScript. Cette application a pour objectif de faciliter la prise de décision concernant les interventions contre les acariens. 
Etapes : 

  Échantillonnage
    Nombre d’arbres : minimum 5 arbres (maximum 20 arbres si nécessaire).
    Nombre de feuilles analysées : 15 feuilles par arbre.
    
Cas 1 : Présence de prédateurs
Pourcentage de feuilles infestées < 35 % :
Décision : Traitement retardé.

Pourcentage de feuilles infestées entre 35 % et 53 % :
Décision : Inspecter un arbre supplémentaire (jusqu’à un maximum de 20 arbres).

Pourcentage de feuilles infestées > 53 % :
Décision : Traitement immédiat.

Cas 2 : Absence de prédateurs
Pourcentage de feuilles infestées < 15 % :
Décision : Traitement retardé.

Pourcentage de feuilles infestées entre 15 % et 32 % :
Décision : Inspecter un arbre supplémentaire (jusqu’à un maximum de 20 arbres).

Pourcentage de feuilles infestées > 32 % :
Décision : Traitement immédiat.
