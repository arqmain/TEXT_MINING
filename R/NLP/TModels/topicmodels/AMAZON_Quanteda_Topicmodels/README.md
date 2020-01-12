<p align="center">
<img  src="http://arqmain.net/Researches/Researchs/TMining/R/NLP/TModels/AMAZON_Quanteda_Topicmodels/visualizations/TEXTMining2.png">
</p>

<hr>

# Data Science: Some useful Text Mining results by using Quanteda and Topicsmodels R libraries 
 
This article is about an application of Text Mining to the  Amazon Reviews, getting useful results  by using Quanteda and Topicsmodels R libraries. 

Quanteda and Topicsmodels are R libraries that provide us with a lot of support and very practical options to be used when we need to perform Text Mining. With these two libraries, you can develop classical text mining, sentiment analysis, and topic modeling quickly and easily. If you also add Tidytext and TM to these two, you will get a very powerful set of tools to perform high-quality text mining that will allow you to cover the most common and frequent everyday problems in this field.

The data wrangling and data processing are covered with various libraries but, preferably, dplyr, tydiverse, lubridate, tidytext, reshape2, quanteda, topicmodels, and stm. The visualization of the results is generated through gridExtra, viridis, ggplot2 or some of its extensions.

The specifics objectives are:
<b><i>
1) Perform Corpus Wrangling, Managements and Visualizations Results.
2) Configure and run some topics model.
3) Obtain some interest results from the model and get visualizations accordingly.<br>
</i>
</b>

Specifics methods of text mining have been applied to develop this article. Using quanteda allows us to easily perform frequent text mining processing tasks that appear to be easy both to apply and to get useful results. That is one of the more important characteristics of quanteda, which makes it position itself as one of the most efficient packages for text mining in the r project environment.

Although the concepts and statistical theory that underlie some methods used here are not addressed in this project, an overview of the concepts and their direct scope in this project is given. However, adequate links are provided that would allow the reader to access the statistical foundations of these methods in case it so requires.

Anyway, I strongly recommend applying Alfred, Lord Tennyson's famous quote in this context. This is: "It is always better to have tried to learn more statistics and lost in the attempt than never to have tried to learn statistics at all".

## TABLE OF CONTENTS   (  [  Link to project results ](http://arqmain.net/Researches/Researchs/TMining/R/NLP/TModels/AMAZON_Quanteda_Topicmodels/AMAZON_TMining_Quanteda_Topicmodels_LDA.html))


### WHAT IS IT ALL ABOUT?

### DATA SOURCE  AND  R PACKAGES
#### DATA SOURCE
#### R PACKAGES

### FEATURE ENGINEERING AND FINAL DATASET
#### CREATION OF NEW VARIABLES
#### FINAL DATASET

### THE DATA 

### THE CORPUS
#### GETTING THE CORPUS
#### GETTING SOME CORPUS STATS
#### VISUALIZING CORPUS STATS TOKENS
#### VISUALIZING, TYPES, TOKENS, AND SENTENCES
#### VISUALIZING TYPE-TOKEN RATIO (TTR)
#### VISUALIZING CORPUS COMPONENTS DISTRIBUTION

### SOME CORPUS DATA MANAGEMENT RESULTS
#### RESHAPING CORPUS
##### RESHAPING to "sentences"
##### RESHAPING to "paragraphs"
#### USING GROUPED CORPUS
##### GETTING THE GROUPED CORPUS
##### VISUALIZING GROUPED CORPUS
#### EXPLORING CORPUS TEXTS
##### UNIGRAMS:
##### MULTI-WORD ESPRESSIONS
###### Bigrams:
###### Trigrams:
#### WORKING WITH DICTIONARIES
##### SIMPLE DICTIONARY
##### SIMPLE DICTIONARY RESULTS IN PERCENTAGE
##### SIMPLE DICTIONARY RESULTS VISUALIZATION

### SOME ADVANCED OPERATIONS
#### WORD AND DOCUMENT SIMILARITIES
##### WORD OR TERM SIMILARITIES
##### DOCUMENTS (REVIEWS) SIMILARITIES
#### TARGETED DICTIONARY ANALYSIS
##### THROUGH THE PAGES
##### THROUGH THE YEARS
#### RELATIVE FREQUENCY ANALYSIS (KEYNESS)
#### LEXICAL DIVERSITY
#### SIMILARITY BETWEN DOCUMENTS
#### CORRESPONDENCE ANALYSIS (CA)
#### TOPIC MODELS
##### LDA: Latent Dirichlet Allocation 
##### STM: Structural Topic Model 
##### LSA: Latent Semantic Analysis

### DISCUSSION

<br>
<hr>

><i>Hector Alvaro Rojas<br>
>Data Science, Visualizations and Applied Statistics | January 11, 2020<br>
>Email: <arqmain2010@gmail.com> <br>
>Url: [http://www.arqmain.net]   |  GitHub: [https://github.com/arqmain]</i>
