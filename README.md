<img src="https://github.com/axiom2018/AG-News-Classification/blob/main/ag_news%20banner.png"/>


## Description
<p align="left"> 
  A multi-classification NLP project with multiple neural networks used for comparison. Link to dataset is <a href="https://www.kaggle.com/datasets/amananandrai/ag-news-classification-dataset">here</a>.
  The code is <b><i>HEAVILY</i></b> commented with great detail in every section to ensure reader understands as much of the code as possible. I revisted the ag_news dataset a long while after, when I 
  learned more about NLP. So there's 2 notebook to see and I describe them in detail. The first one mentioned is the most recent one.

  <h3>AG News 3/31/2024 UPDATED Project</h3>
  This notebook uses not 1, not 2, but 3 (technically) models on the dataset. Technically because Optuna, the hyperparameter tuning library found here <a href="https://optuna.readthedocs.io/en/stable/">here</a>.
  This project explores in depth how the <b>BASICS</b> of lstms, rnns, and combining lstms with embedding bag models, can all work. Below is the project breakdown:

  1) Exploratory Data Analysis
  2) Preprocessing
     - Using Regex, & PyTorch 
  3) Splitting
  4) Tokenization
  5) Building the vocabulary
  6) Padding
  7) Changing labels
  8) Dataset & Dataloaders
  9) <b>Understanding Embedding & LSTM section</b>
      - Section dedicated to understanding the lstm mathematics, process and steps in depth
  10) Custom Validation & Training functions
      - PyTorch Embedding bag layers require offset vectors. However, nn.LSTM & nn.RNN do not yet the train/validation functions supports all 3 now with a bit a tweaking.
  11) Variables for ALL models
    
  <b><i>Now for the models!</i></b>
  1) Lstm
     - Lstm input test. Like section 9 above, this helps to understand the math, process and steps of the input into the ltm
  4) Rnn
     - Rnn input test. For same reason above.
  5) Building data for lstm & embedding bag layer
     - Embedding bag layers use Offset Vectors. Explained in much more detail in the project
  6) Lstm & embedding bag model
     - Lstm & embedding bag input test.
  7) Graphing results of all 3
  9) Predictions/Evaluation
  10) Optuna
      - Creating smaller portion of data for the various types of models to be created <b><i>DURING</i></b> hyperparameter tuning
      - Saving the best model & optimizer during tuning
  11) <b><i>Testing</i></b> Optuna
  12) <b><i>BIG</i></b> Difference between Rnn model Optuna created vs Original Rnn
        

  <h3>AG News 2/9/2024 Project</h3>
  In this notebook there are two neural network models, with specific layers, used to tackle this dataset: 

  - Embedding
  - Embedding Bag

  Both approaches explained very well and results documented with matplotlib. Project sections are broken down into:
  1) Exploratory Data Analysis
     - Exploring word usage
     - Stop words
  2) Tokenization
  3) Vocab
  4) Batches
  5) Model Building
  6) Get model training ready
     - Creating testing function
     - Training model
  7) Model evaluation
  8) Embedding model comparison
     - Embedding model building
     - Embedding model training function
     - Data loaders and test function
     - Embedding model training
  9) Model evaluation comparison

NLP is my passion and I'm always working at it. Hope this project can help someone out there understand a thing or two about NLP.
</p>
