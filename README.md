# IntroductionToMachineLearning
A Culmination Of An Independent Study In Machine Learning


During my Senior year at Wheaton College, MA, I conducted an independent study in Machine Learning with Mark LeBlanc, Wheaton College's Computer Science Department Chair. During this course, we dove into a large survey of Machine Learning techniques, and developed a codebase for future students to experiment with and learn from.

This repo is split into 3 main sections:
  1) Decision Tree
  2) Support Vector Machine (SVM)
  3) KMeans
  4) _DBSCAN -- CURRENTLY BEING POLISHED_


For each of these ML approaches, I created models for two datasets:
  1) Poe Dataset
  2) Iris Dataset

The Poe Dataset contains 86 texts, 16 of which are known to have been written by the author Edgar Allen Poe, 69 of which being written by authors of the same time period (Melville, Badcock, etc), and 1 text that is believed to have been written by Poe. To us, the objective is to discern whether or not this "UNKNOWN" text is indeed written by Poe or if it is not written by Poe. The features are words that appear in all 86 texts, and the values for each of these features is the relative abundance of these words in each text (i.e. a value of .0187 for "been" means that of all the words in the text, 1.87% of the words are "been"). All values in the dataset are of the form '.XXXX'.

See related work:
  https://github.com/WheatonCS/aGoodMystery A Good Mystery by WheatonCS/Mark LeBlanc

The Iris dataset contains 150 instances of 3 seperate species of Iris (Iris-virginica, Iris-setosa, and Iris-versicolor). Each instance has 4 attributes recorded, which are the sample's sepal-length, sepal-width, petal-length, and petal-width (for more information about sepals and petals, check out this website for some additional background info: https://davesgarden.com/guides/articles/view/3152). Each of the values in the dataset is a float of the form 'X.X' with one digit after and one digit before the period.

## Technologies, Tools, and Languages Used:
* Python
  - sci-kit learn
  - pandas
  - numpy
  - matplotlib
  - Regular Expressions (regex - "re" library)
* Jupyter Notebook

## Steps to run:

1) Install Jupyter Notebook https://jupyter.org/install
2) git clone the repo
3) play around with notebooks, learn, and have fun
