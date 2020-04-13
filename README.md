# Topic-Modelling-on-Research-papers-using-LDA

# DOCUMENTATION

# Dataset:
Data is manually collected from https://www.mdpi.com/
 train_txt : Folder containing twenty text document 5 of each domain
agriculture, animals, electronics & logistics respectively.
 test_txt.txt: Text file have a research from logistics domain.

# ALGORITHM:
1. Import the required libraries and read the data from the folder
(train_txt).
2. Perform pre-processing.
 Tokenization.
 Stemming.
 Lemmatization.
 Removing stop-words.
3. Feature engineering by converting text document into matrix count.
4. Training the model using LDA Topic Modelling.
5. Describing the weight for each topic.
6. Two-way table showing weight of each terms in a particular topic with
respect to each document.
7. Dominant topic for each document.
8. Testing the model with the text data (test_txt.txt).
9. Result.
10. Visualization.

# Packages used:
1. numpy
2. pandas
3. nltk
4. sklearn
5. glob
6. pyLDAvis
7. dill

# Conclusion
The trained LDA model is tested with the new research paper which is from the
logistics domain, predict the dominant Topic No as 2 with the topics score as
63.30 and another dominant Topic No as 11 with the topic score as 25.40.
Topics 2 belong to research paper No 19 which is of logistics domain, Whereas
Topics 11 belong to research paper No 15 which is of electronics domain.
As per the prediction new research paper has highest topic score for Topic 2
(logistic domain) which is same as our actual tested paper.

# Reference:
 https://www.mdpi.com/ (Data)
 http://chdoig.github.io/pytexas2015-topic-modeling/#/3/4
 https://towardsdatascience.com/topic-modeling-and-latent-dirichletallocation-in-python-9bf156893c24
