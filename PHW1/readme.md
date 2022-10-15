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

1. Decision tree by 서정덕
   * criterion 'string'
     * Select('entropy' or 'gini')
   * X train 'dataframe'
     * Independent var for train
   * Y train 'dataframe'
     * Dependent var for train
   * X test 'dataframe'
     * Independent var for test
   * Y test 'dataframe'
     * Dependent var for test
2. Logistic regression by 이민아
   * X train 'dataframe'
     * Independent var for train
   * Y train 'dataframe'
     * Dependent var for train
   * X test 'dataframe'
     * Independent var for test
   * Y test 'dataframe'
     * Dependent var for test
3. Support vector machine by 이민아
   * criterion 'string'
     * Select('entropy' or 'gini')
   * X train 'dataframe'
     * Independent var for train
   * Y train 'dataframe'
     * Dependent var for train
   * X test 'dataframe'
     * Independent var for test
   * Y test 'dataframe'
     * Dependent var for test

### Evaluation

* Validation by 유소연
  * K-fold

* Evaluation by 유소연
  * Accuracy score
  * Precision score
