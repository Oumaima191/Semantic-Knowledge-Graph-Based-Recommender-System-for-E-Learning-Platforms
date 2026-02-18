# Semantic-Knowledge-Graph-Based-Recommender-System-for-E-Learning-Platforms# Semantic-Knowledge-Graph-Based-Recommender-System-for-E-Learning-Platforms

**📂 Contenu du dossier**

**semantic_recommender_elearning.ipynb** : Notebook Jupyter contenant :

****Construction du graphe RDF/OWL

****Requêtes SPARQL pour la recommandation

****Implémentation du modèle ML (TF-IDF + similarité cosinus)

****Comparaison des résultats

****articleIEEE.docx**** : Article scientifique au format IEEE

******README.md**** : Description du projet

**⚙️ Prérequis**

**Python 3.x

**Jupyter Notebook

**Bibliothèques Python :

    ****rdflib
    
    ****scikit-learn
    
    ****numpy
    
Installation des dépendances :

  **pip install rdflib scikit-learn numpy matplotlib**

▶️ Étapes d’exécution

1.Ouvrir Jupyter Notebook :

2.jupyter notebook:

  **jupyter notebook**
  
3.Ouvrir le fichier semantic_recommender_elearning.ipynb.

4.Exécuter les cellules dans l’ordre :

**Cellule 1** : Import des bibliothèques

**Cellule 2** : Construction du graphe RDF

**Cellule 3** : Ajout des triplets (cours, concepts, utilisateurs)

**Cellule 4** : Requête SPARQL (recommandation sémantique)

**Cellule 5** : Implémentation du modèle ML

**Cellule 6** : Comparaison des résultats

**🧪 Tests effectués**
**Test 1 : Recommandation sémantique**

****Entrée**** : User1 aime Course1

****Résultat**** : Recommandation de cours liés aux sous-concepts du concept principal

****Observation**** : Exploitation correcte de la hiérarchie conceptuelle

**Test 2 : Modèle ML (TF-IDF)**

****Entrée**** : Course1 comme référence

****Résultat**** : Recommandations basées sur similarité textuelle

****Observation**** : Pas d’exploitation des relations hiérarchiques


****📊 Résultats obtenus****

L’approche sémantique permet :

****d’exploiter les relations ontologiques

****d’inférer des recommandations via la hiérarchie des concepts

****d’offrir une meilleure explicabilité

Le modèle ML :

****détecte les similarités lexicales

****ne capture pas les relations sémantiques implicites

****fonctionne comme une approche statistique classique

**🎯 Contribution**

****Intégration du raisonnement sémantique dans la recommandation

****Comparaison expérimentale avec un modèle ML classique

****Analyse de l’explicabilité des recommandations

**🚀 Perspectives**

****Extension à des données réelles

****Intégration d’un modèle hybride (graphe + ML)

****Évaluation quantitative (Precision, Recall, F1-score)






  
