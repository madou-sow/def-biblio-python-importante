# Definition de quelques bibliothèques importantes en python

## Definition Scikit-learn

Scikit-learn est une bibliothèque libre Python destinée à l'apprentissage automatique. Elle est développée par de nombreux contributeurs notamment dans le monde académique par des instituts français d'enseignement supérieur et de recherche comme Inria.

Elle propose dans son framework de nombreuses bibliothèques d’algorithmes à implémenter, clé en main. Ces bibliothèques sont à disposition notamment des data scientists.

Elle comprend notamment des fonctions pour estimer des forêts aléatoires, des régressions logistiques, des algorithmes de classification, et les machines à vecteurs de support. Elle est conçue pour s'harmoniser avec d'autres bibliothèques libres Python, notamment NumPy et SciPy.

Alternative de skearn : mllib, weka, torch

## Définition Numpy

NumPy est une bibliothèque pour le langage de programmation Python, destinée à manipuler des matrices ou tableaux multidimensionnels ainsi que des fonctions mathématiques opérant sur ces tableaux.

Plus précisément, cette bibliothèque logicielle libre et open source fournit de multiples fonctions permettant notamment de créer directement un tableau depuis un fichier ou au contraire de sauvegarder un tableau dans un fichier, et manipuler des vecteurs, matrices et polynômes.

NumPy est la base de SciPy, regroupement de bibliothèques Python autour du calcul scientifique

Alternative de numpy : scipy (sympy), pytorch, pandas, R, panda, matlab, tensorflow, anaconda

## Définiton Scipy

SciPy est un projet visant à unifier et fédérer un ensemble de bibliothèques Python à usage scientifique. Scipy utilise les tableaux et matrices du module NumPy.

Cette distribution de modules est destinée à être utilisée avec le langage interprété Python afin de créer un environnement de travail scientifique très similaire à celui offert par Scilab, GNU Octave, Matlab voire R.

Il contient par exemple des modules pour l'optimisation, l'algèbre linéaire, les statistiques, le traitement du signal ou encore le traitement d'images.

Il offre également des possibilités avancées de visualisation grâce au module matplotlib.

## Définition Matplotlib

matplotlib est une bibliothèque Python capable de produire des graphes de qualité. matplotlib peut être utilisé dans des scripts Python, le shell Python et IPython, le notebook Jupyter, des serveurs d’application web et dans quatre outils d’interface graphique. Elle peut être combinée avec les bibliothèques python de calcul scientifique NumPy et SciPy. Elle fournit également une API orientée objet, permettant d'intégrer des graphiques dans des applications, utilisant des outils d'interface graphique polyvalents tels que Tkinter, wxPython, Qt ou GTK.

Alternative de matplotlib: seaborn, plotly, bokeh, altair, pygal, pandas

## Quelle est la relation entre NumPy, SciPy, Pandas et Scikit-learn et quand dois-je utiliser chacun d'eux ?

NumPy est une bibliothèque pour des calculs de tableaux efficaces, calquée sur Matlab. Les tableaux diffèrent des listes Python simples dans la manière dont ils sont stockés et gérés. Les éléments du tableau restent ensemble en mémoire, de sorte qu'ils soient rapidement accessibles. NumPy prend également en charge la sous-indexation rapide, par exemple, a[0, :, 2] vous donne tous les éléments du tableau dont le premier index est 0 et le troisième index est 2.

De plus, NumPy fournit des fonctions mathématiques vectorisées. Lorsque, par exemple, vous appelez numpy.sin(a), la fonction sinus est appliquée sur chaque élément du tableau a. Cela se fait à l'aide de code C compilé, il fonctionne donc beaucoup plus rapidement qu'une boucle Python for, encore plus rapidement que les compréhensions de liste.

SciPy fournit un large menu de bibliothèques pour le calcul scientifique, telles que l'intégration, l'interpolation, le traitement du signal, l'algèbre linéaire, les statistiques, etc. Il est construit sur l'infrastructure de Numpy.

Nous devrons également mentionner la bibliothèque matplotlib pour la représentation graphique et la visualisation. Il est également construit sur Numpy et conçu pour bien fonctionner avec Numpy. Ces trois bibliothèques Python sont bien établies à des fins scientifiques.

La bibliothèque Pandas est idéale pour analyser les données tabulaires. Vous pouvez l'utiliser pour l'analyse exploratoire des données, les statistiques, la visualisation.

Scikit-learn est une collection d'algorithmes avancés d'apprentissage automatique pour Python. Il est également basé sur Numpy et SciPy.

Alors, quand utilisez-vous chacun ?

    Si vous voulez comprendre les données dont vous disposez, utilisez Pandas.
    Si vous souhaitez utiliser ces données pour entraîner un algorithme d'apprentissage automatique, utilisez scikit-learn.
    Si vous faites d'autres calculs scientifiques ou techniques, utilisez SciPy.
    Si vous souhaitez tracer des données, utilisez matplotlib.
    Tous ces éléments utilisent Numpy, vous devrez donc configurer vos structures de données à l'aide de Numpy.

## Quelle est une bonne alternative à scikit-learn ?

La réponse serait dans le cadre de Python, scikit-learn est le package le plus complet pour l'apprentissage automatique de haut niveau et polyvalent. Il n'y a pas d'alternative qui vient dans un seul paquet. Alors que scikit-learn n'est exceptionnellement bon à rien, il peut faire beaucoup de choses à la fois. Il est possible de remplacer des parties de Scikit-Learn par des packages tels que NLTK, Gensim, SciPy et Matplotlib et d'en tirer un kilométrage énorme. travail bien meilleur que Scikit-Learn. Sortant de la zone de confort Pytonic, il y a MATLAB qui fait presque tout et plus encore Scikit-Learn. Octave est une version gratuite de MATLAB, R a de bons packages à usage général pour l'apprentissage automatique et en tant que langage de calcul scientifique, R est plutôt soigné. SPSS, bien qu'il reste dans la zone de confort Pytonic, offre certaines des capacités de Scikit-Learn mais se concentre davantage sur les statistiques basées sur la fréquence. Au final, Scikit-Learn est la meilleure bibliothèque générale d'apprentissage automatique pour Python, et des alternatives se trouvent généralement dans des environnements non python.

P.S - Scikit-Learn est très pauvre en réseaux de neurones, mais il peut être utilisé à des fins éducatives.
