# Projet 5: Segmentez des clients d'un site e-commerce
## Présentation:
Je suis consultante pour Olist, une entreprise brésilienne qui propose une solution de vente sur les marketplaces en ligne.
Olist souhaite que je fournisse à ses équipes d'e-commerce une segmentation des clients qu’elles pourront utiliser
au quotidien pour leurs campagnes de communication.

Mon objectif est de comprendre les différents types d’utilisateurs grâce à leur comportement et à leurs données personnelles.

Je dois fournir à l’équipe marketing une description actionable de ma segmentation et de sa logique sous-jacente
pour une utilisation optimale, ainsi qu’une proposition de contrat de maintenance basée sur une analyse de la stabilité des segments au cours du temps.
## Mission:
Ma mission est d’aider les équipes d’Olist à comprendre les différents types d'utilisateurs. J'utiliserais donc des méthodes non supervisées pour regrouper des clients de profils similaires. Ces catégories pourront être utilisées par l’équipe Marketing pour mieux communiquer.

Je crée donc un notebook et démarre votre travail d’analyse exploratoire.
Après quelques premières analyses, je me rends compte qu’Olist ne m'a a pas fourni beaucoup de données ; j'enquête 
donc auprès de l’entreprise pour obtenir quelques informations complémentaires, et vérifier que j'ai bien compris la mission. 

Voici sa réponse: 
" Pour des raisons de confidentialité, nous ne pouvons pas vous fournir beaucoup de données à ce stade. Ensuite, en raison de ressources limitées, nous avons dû vous fournir l’ensemble des données, alors que seule une partie va vous intéresser. Nos dashboards internes nous indiquent en effet que seuls 3 % des clients du fichier de données partagé avec vous ont réalisé plusieurs commandes.
Nous sommes confiants sur le fait que les données à disposition suffiront pour réaliser un premier clustering. Cela a déjà été fait par d’autres prestataires par le passé, avec encore moins de données.
La segmentation proposée doit être exploitable et facile d’utilisation par notre équipe Marketing. Elle doit au minimum pouvoir différencier les bons et moins bons clients en termes de commandes et de satisfaction. Nous attendons bien sûr une segmentation sur l’ensemble des clients.
Dans un deuxième temps, une fois le modèle de segmentation choisi, nous souhaiterions  que vous nous fassiez une recommandation de fréquence à laquelle la segmentation doit être mise à jour pour rester pertinente, afin de pouvoir effectuer un devis de contrat de maintenance.
Pour information, le code fourni doit respecter la convention PEP8, pour être utilisable par Olist."
## Données:
Pour cette mission, Olist m'afournit une base de données anonymisée : https://www.kaggle.com/olistbr/brazilian-ecommerce comportant des informations sur l’historique de 
commandes, les produits achetés, les commentaires de satisfaction, et la localisation des clients depuis janvier 2017.
## Construction:
Dans ce dépôt, vous trouverez plusieurs fichiers:

- "exploration.ipynb" : notebook  comportant les analyses pré-exploratoires réalisées.
- "essais.ipynb" : notebook comportant les essais des différentes approches de modélisation.
- "simulation.ipynb" : notebook comportant la simulation pour déterminer la fréquence nécessaire de mise à jour du modèle de segmentation.

## Packages:
Différents packages Python ont été utilisés:

- pandas 1.4.4
- numpy 1.23.5
- seaborn 0.11.2
- matplotlib 3.5.2
- scikit-learn 1.0.2
- scipy 1.9.1


## Compétences:
- Adapter les hyperparamètres d'un algorithme non supervisé afin de l'améliorer
- Évaluer les performances d’un modèle d'apprentissage non supervisé
- Transformer les variables pertinentes d'un modèle d'apprentissage non supervisé
- Mettre en place le modèle d'apprentissage non supervisé adapté au problème métier
