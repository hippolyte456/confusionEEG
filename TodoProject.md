A faire pour le projet:

--> tester si on peut retrouver à quel individu appartient tel enregistrement

--> faire attention aux facteurs confondants 'vidéosID' et 'sujetsID' (quand on a des facteurs confondants, on peut rajouter des réseaux bayesiens ? on prédit y a partir de X, sachant l'état de la variable confondante)

--> les pretraitements à tester:
    - prendre en compte / et les différentes manières de prendre les channels en compte  
    - redéfinir les features (nb de pics, moyenne du signal, variance du signal,.......,)
    - propres aux séries temporelles (binning, mapping)

--> tester différents modèles:
    SVM
    NaiveBayes 
    NN, CNN


IMPORTANT POUR LES PROCHAINES FOIS, PENSER À FAIRE LA RANDOMISATION DES LE DEBUT CAR :

COMME ÇA ON PEUT SÉPARER LES VARIABLES X ET Y 
PENDANT LES PRETRAITEMENTS (ET EVENTUELLEMENT LES REMETTRE EN TUPLE POUR PYTORCH ENSUITE [ou autre approche ou le training est itératif])

DE LA MEME MANIÈRE, IL EST PLUS SIMPLE DE FAIRE LA DIVISION EN TRAIN VAL TEST À LA FIN DES PRETRAITEMENTS ???


LE FAIT DE FAIRE PLUSIEURS TRAINING A PARTIR DE PARAMÈTRES INITIAUX DIFFÉRENTS, 
ÇA SE FAIT AVANT, EN COURS, OU APRES LA SELECTION DU MODÈLE ????