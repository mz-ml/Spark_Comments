## User Comments on Pet Videos

#### Project Goals 

1. To predict pet owners based on video comments
3. To identify important topics among all estimated pet owners
4. To identify popular video creators among all estimated pet owners

#### Outline

- Data Exploration and Preprocessing 
  - Load and Explore Data
  - Label Data (manually)
  - Create Pipeline
    - Tokenizer
    - Remover
    - Word2Vec *(for owner prediction)*
    - Stemmer + TF-IDF *(for topic identification)*
  - Split Dataset

- Cat/Dog Owners Prediction [PySpark.ml]
  - Model Training and Selection on Training Set 
   - **Logistic Regression**
   - **Gradient-Boosted Trees**
  - Prediction on Testing Set

- Estimated Classification of Cat/Dog Owners
  - Estimated Cat/Dog Owners = # of labeled owners + # predicted unlabeled owners

- Important Topics Identification [PySpark.ml]
  - Latent Dirichlet Allocation
  
- Popular Creatiors Identification [PySpark.sql]


#### PDF Preview

https://htmlpreview.github.io/?https://github.com/mingzhao1103/Spark_Comments/blob/main/comments.html
