---
license: mit
---

<h1 align=center>Comment Toxicity Classification</h1>
This model helps to predict the is a comment/sentence is hateful on various parameters such as toxicity, severe toxicity, obscene, threat, insult and racism.


### Test the model here :  <a href="https://huggingface.co/spaces/pvcodes/comment_toxicity_classifier">pvcodes/comment_toxicity_classifier</a>


<br>

## Working of the Model

 - #### Loading of Data

    The data is fetched from <a href='assets/jigsaw_toxic_challenge/train.csv/train.csv'>csv</a> file, which consist of the comment and attributes such as toxicity, severe toxicity, obscene, threat, insult and racism.

- ####  Preprocessing the comments

    Then the data is tokenized using the `TextVectorization` method of `keras` in and embeded

 - #### Creating of <emp>Deep NLP Model</emp> 
    
    For this model we used `Keras sequential API` with a number of `LSTM` layers (because they are particulary good while working with sequences)

- #### 

- The dataset used to train the model is from <a href=https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge>Toxic Comment Classification Challenge</a> from <a href=https://www.kaggle.com>Kaggle</a>.




##### Note: The compiled data model is available here: <a href='assets/toxicity.h5'>here</a>.

<samp>
  <p align="center">
    ════ ⋆★⋆ ════<br>
    From <a href="https://github.com/pvcodes/pvcodes">pvcodes</a>
  </p>
</samp>
