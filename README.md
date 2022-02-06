## GURJAS SINGH CHHABRA


### [Project (A): Exploratory Data Analysis Using Principal Component Analysis](https://github.com/gurjaschhabra2324/PORTFOLIO/blob/main/Expploratory%20Data%20Analysis%20Using%20Principal%20Component%20Analysis/PCA%20for%20EDA.ipynb)

Baisc data cleaning to deal with missing values using a KNN imputer with neighbours=5 followed by PCA. The idea is to trace the source of variance to the combination of variables using PCA loadings. And explore the combination of these variables with the intent of narrowing down the research. The following script is an excert from Jypter Notebook that generated the initial PCA output.  

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

Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```


```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/gurjaschhabra2324/PORTFOLIO/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
