# ArbresDécision
exemple d'utilisation des arbres de décision sous Python. Les packages utilisés seront pandas, scikit-learn et ses sous-packages, notamment tree et model_selection.


Le jeu de données utilisé provient de l'UCI ML Repositry et contient des données calculées à partir d'images numérisées de masses mammaires.
Elles décrivent les caractéristiques des noyaux cellulaires présents dans chaque image (rayon, périmètre, texture etc..) La première colonne donne le résultat du diagnostic de chaque masse cellulaire : 'B' pour bénigne, 'M' pour maligne.
L'objectif est de construire un modèle sous la forme d'un arbre de décision, pour prédire si une masse cellulaire est bénigne ou maline, en fonction des caractéristiques calculées à partir de l'image de sa biopsie.
