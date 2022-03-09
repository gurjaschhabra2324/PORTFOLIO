# GURJAS SINGH CHHABRA

## Introduction:

<iframe width="300" height="250" src="https://www.youtube.com/embed/ZpKArwTGT2c" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Summary:
[Project (A): Exploratory Data Analysis Using Principal Component Analysis](https://github.com/gurjaschhabra2324/PORTFOLIO/blob/main/Expploratory%20Data%20Analysis%20Using%20Principal%20Component%20Analysis/PCA%20for%20EDA.ipynb)

[Project (B): Business Analysis Case Study](https://github.com/gurjaschhabra2324/PORTFOLIO/tree/main/Documentation%20and%20Business%20Analysis)

[Project (C): Performance of ML Models (RAPID MINER)](https://github.com/gurjaschhabra2324/PORTFOLIO/blob/main/ML%20RAPIDMINER/Machine%20Learning.pdf)

[Project (D): Miscellaneous Data Scritps for cleaning data and Hypothesis Testing](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2Fgurjaschhabra2324%2FPORTFOLIO%2Fmain%2FExcel%2520and%2520Python%2FStochastic%2520Decision%2520Modelling.pptx&wdOrigin=BROWSELINK)

_________________________________________________________________________________________________________________________________________________________



### [Project (A): EDA Using PCA](https://github.com/gurjaschhabra2324/PORTFOLIO/blob/main/Expploratory%20Data%20Analysis%20Using%20Principal%20Component%20Analysis/PCA%20for%20EDA.ipynb)

Baisc data cleaning to deal with missing values using a KNN imputer with neighbours=5 followed by PCA. The idea is to trace the source of variance to the combination of variables using PCA loadings. And explore the combination of variables causing maximum variance with the intent of looking for narratives and narrowing down the research. 

The following script is an excert from the Jypter Notebook that generated the initial PCA output.  

```markdown
n_components = len(pca.explained_variance_ratio_)
explained_variance = pca.explained_variance_ratio_
cum_explained_variance = np.cumsum(explained_variance)
idx = np.arange(n_components)+1
df_explained_variance = pd.DataFrame([explained_variance, cum_explained_variance], 
                                     index=['explained variance', 'cumulative'], 
                                     columns=idx).T
```
HEAT MAP: Variance (Using Colour) of orignal variables(Y axis) across Top four Principal components (X axis:1,2,3,4)

![](/images/015.JPG)


### [Project (B): Business Analysis Case Study](https://github.com/gurjaschhabra2324/PORTFOLIO/tree/main/Documentation%20and%20Business%20Analysis)
-[Process Decomposition](https://github.com/gurjaschhabra2324/PORTFOLIO/blob/main/Documentation%20and%20Business%20Analysis/(A.)%20PROCESS%20BREAKDOWN.pdf)

-[Stakeholder Analysis](https://github.com/gurjaschhabra2324/PORTFOLIO/blob/main/Documentation%20and%20Business%20Analysis/(B.)STAKEHOLDER%20ANALYSIS.pdf)

-[Problem Analysis](https://github.com/gurjaschhabra2324/PORTFOLIO/blob/main/Documentation%20and%20Business%20Analysis/(C.)OPTIMIZATION.pdf)

An indepth discussion and analysis of the AS-IS process, stakeholder analysis (on divisional level) and operational level inefficiencies (with possible solutions). The sensitive information of the organization has been redacted (an industry leader in the RCM industry based in U.S.A). The objective here was to study the status quo to reengineer the RCM process.

### [Project (C): Food&Beverage Industry Consultancy using Zomato Dataset](https://github.com/gurjaschhabra2324/PORTFOLIO/blob/main/ML%20RAPIDMINER/Machine%20Learning.pdf)

-Data exploration, machine learning and solution reccomendation using RapidMiner. Developed classification models to suggest restaurants what should be there customer satisfaction strategy going forward. 

-Segmentation Analysis of restaurants using clustering and NLP.

-Anamoly Detection
-Comparision of model performance using CV   
-Comparision of ML algorithms based on performance
-Model Deployment and running models on unseen data

![](https://github.com/gurjaschhabra2324/PORTFOLIO/blob/main/images/spider%20graph.jpg)
![](https://github.com/gurjaschhabra2324/PORTFOLIO/blob/main/images/words%20freq.jpg)


### [Project (D): Miscellaneous Data Scripts for cleaning data and Hypothesis Testing](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2Fgurjaschhabra2324%2FPORTFOLIO%2Fmain%2FExcel%2520and%2520Python%2FStochastic%2520Decision%2520Modelling.pptx&wdOrigin=BROWSELINK)

A combination of Data wrangling using python and hypothesis testing using excel on different Datasets. To exhibit understanding of foundational skills in data analysis.
