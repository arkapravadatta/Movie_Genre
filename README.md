--Word Embeddings and Text Classification--

Overview:
This project focuses on training a simple feedforward neural network for text classification while simultaneously generating trained word embedding vectors. The dataset is processed and transformed into vectorized representations to build an effective classification model. The project also includes visualization of word embeddings and similarity calculations.


Dataset:

The dataset can be accessed from the following link:
https://drive.google.com/uc?id=10Ka12eC8icg0kiQGL2YUGeUctxD-BeuY


Project Components:

Part 1: Text Data Preparation :

• Read and Clean Data: The dataset is read, and preprocessing techniques such as lowercasing and exploratory data analysis (EDA) are applied.
• Tokenization, Encoding, and Vectorization: The text data is tokenized, encoded, and converted into numerical vector representations.
• Feature Extraction: Features and labels are extracted for model training.

Part 2: Model Training :
A simple feedforward neural network is built using Keras with the following architecture:

• Embedding Layer: Shape (,10)
• Three Dense Layers: 100 neurons each, with ReLU activation functions
• Output Layer: A dense layer with an appropriate activation function
• Training: The model is compiled and trained for 50 epochs or until an accuracy of at least 75% is achieved.

Part 3: Word Embeddings & Predictions
 • Extracting Word Embedding Vector 
 • The trained word embeddings are extracted from the model.

Visualization of Word Embeddings
• PCA is used to reduce dimensionality, and a scatter plot is generated to visualize the embeddings.

Prediction of Class 
Given descriptions:

“A young man who survives a disaster at sea is hurtled into an epic journey of adventure and discovery.”
“Mountain guides Rob Hall and Scott Fischer combine their expedition teams for a final ascent to the summit of Mount Everest. With little warning, a storm strikes the mountain and the climbers must now battle to survive.”

The trained model predicts the class of each description.

Cosine Similarity Calculation:
Cosine similarity is computed for word pairs
