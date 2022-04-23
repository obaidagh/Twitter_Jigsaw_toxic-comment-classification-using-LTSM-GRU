
## `Project’s title:  Twitter Jigsaw toxic comment classification using LTSM GRUs` 

# ****Project Description:****
The project uses Keras Sequential library and Keras preprocessing for tokenization and padding, I also used ReduceLROnPlateau and EarlyStopping callback that monitors validation accuracy and validation loss respectively.
I used Glove50 Embeddings as a non trainable embdding layers.

## The project consist of 5 parts:
     1-Library Importing and config class
     2-Data importing and preperation
     3-Tokenization and padding
     4-Glove50 Embeddings vector
     5-Model Initialization and Compiling


The only difference between the LSTM and GRU model is that I used 1 bidirectional LSTM and 2 bidirectional GRU layers in the models.


## Model Architecture:
## Gru
![GRU model](/Toxic%20comment%20Gru/Gru%20model.png)
## LSTM

![LSTM model](/Toxic%20comment%20LSTM/LTSM%20model.png)

