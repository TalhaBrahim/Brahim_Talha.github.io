<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">

<div style="font-family: 'Roboto', sans-serif;">

# Portfolio de [Votre Nom]

Bienvenue sur mon portfolio ! Je suis [votre rôle, par exemple, Analyste de Données] et je suis passionné par l’utilisation des données pour résoudre des problèmes concrets. Vous trouverez ci-dessous ma formation, mes compétences et une présentation de mes projets, y compris des analyses de données interactives.

## À Propos de Moi
- **Nom** : [Votre Nom Complet]
- **Localisation** : [Votre Ville, Pays]
- **Email** : [votre.email@exemple.com]
- **LinkedIn** : [Votre URL LinkedIn]
- **GitHub** : [Votre URL GitHub]

## Formation
- **Diplôme** : [par exemple, Licence en Informatique]  
  **Établissement** : [par exemple, Université de [Ville]]  
  **Année de Diplômation** : [par exemple, 2023]  
  **Cours Pertinents** : [par exemple, Analyse de Données, Apprentissage Automatique, Statistiques]

- **Autres Certifications** :  
  - [par exemple, Certificat Professionnel en Analyse de Données Google, 2022]  
  - [par exemple, Python pour la Science des Données (Coursera), 2021]

## Compétences
- **Programmation** : Python (Pandas, NumPy, Plotly, Folium), SQL, [autres langages]  
- **Analyse de Données** : Nettoyage des Données, Analyse Exploratoire, Analyse Statistique  
- **Visualisation** : Plotly, Folium, Matplotlib, Seaborn  
- **Outils** : Jupyter Notebook, Git, GitHub, Excel, [autres outils]  
- **Domaines** : Analyse de la Santé, Analyse Géospatiale, [autres domaines]

## Projets

### Analyse de la Répartition des Hôpitaux au Maroc
- **Objectif** : Étudier la répartition géographique et administrative des hôpitaux au Maroc, en comparant les zones urbaines (Arrondissements) et rurales (Municipalités).  
- **Méthodologie** :  
  J’ai débuté en téléchargeant les données à partir de [data.gov.ma](https://data.gov.ma), précisément le fichier `repartition-des-hopitaux-par-region-et-province-2022.csv`. Cependant, les données ne répondaient pas entièrement à mes attentes. Initialement, le jeu de données contenait les colonnes suivantes : `Région`, `Délégation`, `Commune` (combinée avec NUM et Arrond.), `Établissement hospitalier`, `Catégorie`, `Liste des abréviations`. J’ai identifié et supprimé deux colonnes inutiles (`Délégation` et `Liste des abréviations`) pour simplifier l’analyse. Ensuite, j’ai mappé la colonne `Catégorie` (contenant des abréviations comme HR, HPr, CRO) avec une nouvelle colonne que j’ai créée, `Signification de la Catégorie`, pour donner un sens clair aux abréviations (par exemple, HR pour Hôpital Régional, HPr pour Hôpital de Proximité). J’ai également ajouté une nouvelle colonne, `Type Administratif`, pour classifier les communes en Arrondissements (urbains) ou Municipalités (rurales) en fonction de leurs noms. Pour la visualisation, j’ai géocodé les communes à l’aide de la bibliothèque `geopy` pour obtenir leurs coordonnées (latitude et longitude), en utilisant Nominatim et en mettant en place une limitation de taux pour respecter les politiques d’utilisation. J’ai ensuite créé une carte interactive avec Folium, où chaque hôpital est marqué avec des couleurs selon la région et des icônes (bâtiment pour urbain, maison pour rural). J’ai ajouté une légende pour clarifier les couleurs des régions et les types administratifs. Enfin, j’ai généré des graphiques interactifs avec Plotly, notamment un graphique à barres empilées pour comparer les types d’hôpitaux (Hôpital Régional, Hôpital de Proximité, etc.) dans les zones urbaines et rurales, ainsi que des tableaux pour résumer les données.  
- **Outils** : Python, Plotly, Folium, Pandas, Geopy  
- **Résultats Clés** :  
  - **Carte Interactive** : Visualisation des hôpitaux par région et type administratif.  
    [Voir l’Analyse Complète](hospital_analysis(3).html) *(Ouvrez dans un navigateur pour voir les éléments interactifs.)*  
    *(Note : Si les graphiques ou la carte ne s’affichent pas, voir les captures d’écran ci-dessous.)*  
    ![Carte des Hôpitaux](folium_map.png)  
  - **Comparaison Urbain vs. Rural** : Graphique à barres empilées des types d’hôpitaux.  
    ![Graphique Urbain vs. Rural](plotly_graph1.png)  
  - **Tableaux** : Résumés des hôpitaux par région et catégorie.  
- **Code Source** : [Notebook Jupyter](hospital_analysis.ipynb)  

### [Nom du Projet 2]
- **Objectif** : [Brève description du projet]  
- **Outils** : [Outils utilisés]  
- **Résultats Clés** :  
  - [Lien vers visualisation, fichier HTML ou capture d’écran]  
  - [Description des résultats]  
- **Code Source** : [Lien vers .ipynb ou fichier GitHub]  

### [Nom du Projet 3]
- **Objectif** : [Brève description]  
- **Outils** : [Outils utilisés]  
- **Résultats Clés** :  
  - [Lien vers visualisation, fichier HTML ou capture d’écran]  
  - [Description des résultats]  
- **Code Source** : [Lien vers .ipynb ou fichier GitHub]  

## Contact
Je serais ravi de discuter de mon travail ou d’opportunités potentielles ! Contactez-moi par email à [votre.email@exemple.com] ou sur [LinkedIn](votre-url-linkedin).

## Remerciements
- Merci à [collaborateurs, mentors, ou sources de données].  
- Hébergé sur GitHub Pages.

</div>
