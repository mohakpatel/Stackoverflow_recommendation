# Stackoverflow Question Tags Recommendation

In this project, I develope a natural language processing machine learning model to recommend tags to the quesitons asked on StackOverflow. 

Here are some examples of the tags predicted for the questions on StackOverflow:

1. Question: "Return data after ajax call success?"  
Recommended tags: 'ajax', 'javascript', 'jquery', 'php'

2. Question: "Bootstrap div exceeds its content on image gallery"  
Recommended tags: 'css', 'html', 'javascript', 'jquery', 'bootstrap'

3. Question: "Use .dll to store other .dlls or .libs?"  
Recommended tags: 'c#', 'c++'

I develop a deep leanring based convolutional multi-label sentence classificaiton model to recommend tags for the StackOverflow questions. 


## Files

* [Tag_recommendation_NLP_model.ipynb](https://github.com/mohakpatel/Stackoverflow_recommendation/blob/master/src/Tag_recommendation_NLP_model.ipynb): Data preprocessing, cleaning, model training and test results. 
* [model.py](https://github.com/mohakpatel/ImageCleaning/blob/master/src/model.py): Deep learning based convolutional multi-label sentence classification model implemented in Tensorflow. 


## Requirements

I used the following version of libraries in Python 3 for my model
* Tensorflow 1.12
* NLTK
* scikit-learn 0.19.2
* re
* gensim 3.6.0
* Pandas 0.23.4
* Numpy 1.15.1
* Scipy 1.1.0
* matplotlib 2.2.3
* time
* os