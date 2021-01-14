[:arrow_left: Retour vers le portfolio](https://github.com/ThibaultLanthiez/Portfolio)

<img src="https://github.com/ThibaultLanthiez/Detection-fraude-carte-bancaire/blob/main/image-carte.PNG" width="140%" and height="120%"/>

# Detection de fraude à la carte bancaire

L'objectif est de détecter si un transfert d'argent est une fraude ou non.

Pour cela, j'ai téléchargé sur la plateforme Kaggle un jeu de données d'environ 300 000 transactions bancaires.

Puis, avec python j'ai pu analyser les données et les préparer pour les entrer dans le modèle. 

Ensuite, j'ai utilisé des techniques d'apprentissage non-supervisé. Avec l'algorithme isolation forest présent dans la bibliothèque Scikit-Learn, j'ai pu déterminer quelles transactions étaient très différentes de ce qui se fait habituellement. Ces dernières sont donc surement des fraudes. 

Étant donné que le jeu de données était labellisé, la qualité des algorithmes de détection d'anomalies a donc pu être étudiée.

# Code

Voici le code du projet : [notebook](https://github.com/ThibaultLanthiez/Detection-fraude-carte-bancaire/blob/main/Projet_10_D%C3%A9tection_d'anomalies_Credit_Card_Fraud_Detection.ipynb)
