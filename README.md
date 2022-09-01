## User Comments on Pet Videos

#### Project Goals 

1. To predict pet owners based on video comments *[PySpark.ml]*
3. To identify important topics among all estimated pet owners *[PySpark.ml]*
4. To identify popular video creators among all estimated pet owners *[PySpark.sql]*

#### Outline

- Data Exploration and Preprocessing 
  - Load and Explore Data
  - *Label Data*
  - Create Pipeline
    - Tokenizer
    - Remover
    - Word2Vec  ~ *owner prediction*
    - Stemmer+TFIDF  ~ *topic identification*
  - Split Dataset

- Cat/Dog Owners Prediction 
  - Model Training and Selection on Training Set 
    - **Logistic Regression**
    - **Gradient-Boosted Trees**
  - Prediction on Testing Set

- Estimated Classification of Cat/Dog Owners
  - $Estimated \space Owners = labeled \space owners + predicted \space unlabeled \space owners$

- Important Topics Identification
  - Latent Dirichlet Allocation
  
- Popular Creatiors Identification


#### PDF Preview

https://htmlpreview.github.io/?https://github.com/mingzhao1103/Spark_Comments/blob/main/comments.html
