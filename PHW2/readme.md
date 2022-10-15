# PHW 1

### Preprocessing

* Scaling by 유소연
  * Standard scaling
  * Minmax scaling
  * Robust scaling
* Encoding by 유소연
  * label
  * frequency
  * astype('category').cat.codes

* Outlier & Missing Value by 유소연
  * df.dropna()

 ### Model building

1. K-Means by 이민아
   * number of clusters : 5(2, 4, 6, 8, 10)
2. EM by 이민아
   * number of clusters : 5(2, 4, 6, 8, 10)
3. DBSCAN by 서정덕
   * data 'dataframe'
     * train data
   * combination 'list'
     * list of feature
   * eps 'float
     * eps
   * min samples 'float'
     * min samples
   * Return value
     * combination 'list'
       * list of feature
     * score 'float'
       * score of model

### Evaluation
* Evaluation by 유소연
  * Silhouette score
