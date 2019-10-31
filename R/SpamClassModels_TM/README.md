<p align="center">
<img  src="http://arqmain.net/Researches/Researchs/HamSpamClassModels/R/TM/images/spam1.gif">
</p>

<hr>

# Data Science: Comparison of binary text classification models with pca and the caret R library 
 
This article is about an application of several supervised learning algorithms to the text classification problem, evaluating and selecting the best of them according to a precision measurement (accuracy score) and the caret R-project library.

The PCA transformation is applied to the original variables and the modeling is carried out with the components that retain an accumulated 80% of the original total variation. This allows a significant reduction of the variables (now PC ones) to be used in modeling and, therefore, a significant reduction in processing time.

The data wrangling and modeling are covered by using R base with various libraries but, preferably, tydiverse, tm, pander, dplyr, xlsx, doParallel,and caret. The visualization of the results is generated through ggplot2 or some of its extensions.

The specifics objectives are:
<b><i>
1) Perform the necessary data wrangling.<br>
2) Configure and run the models.<br>
3) Compare the performance of the models to classify the text data.<br>
4) Select the best model based on its accuracy score.<br>
5) Present the selected model and use it to make predictions.<br>
</i>
</b>

There are many fields where the binary text classification models idea can be addressed. The method and models applied in this project could be extrapolated to various situations and problems typical of human development in general, and scientific research in particular. Research Analysis in all its wide range of possibilities is especially benefited with the implementation and use of the ideas applied to this project, and for sure should have a high value in its daily development.

## TABLE OF CONTENTS   (  [  Link to project results ](http://arqmain.net/Researches/Researchs/HamSpamClassModels/R/TM/Ham_Spam_ClassModels_TM.html))

### WHAT IS IT ALL ABOUT?

### DATA SOURCE  AND  R PACKAGES
#### DATA SOURCE
#### R PACKAGES

### DATA READING AND DATA WRANGLING 
#### DATA READING
#### DATA WRANGLING

### MACHINE LEARNING MODELS
#### TRAIN AND TEST DATASETS
#### BUILD MODELS
#### SELECT BEST MODEL
#### MAKE PREDICTIONS

### DISCUSSION

<hr>

><i>Hector Alvaro Rojas<br>
>Data Science, Visualizations and Applied Statistics | October 27, 2019<br>
>Email: <arqmain2010@gmail.com> <br>
>Url: [http://www.arqmain.net]   |  GitHub: [https://github.com/arqmain]</i>
