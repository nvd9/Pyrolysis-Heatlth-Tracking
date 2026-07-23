# Pyrolysis-Heatlth-Tracking
LSTM-Autoencoder / Transformer Model


The **LSTM_A_normaldata** file is used for **clear-standard-most healty** dataset. It includes some EDA techniques: 
1) Feature Engineering
2) StandardScaler
3) ISO-Forest algorithm (use for finding threshold of normal data)
4) One-Class SVM algorithm (also use for find threshold of normal data)
5) LSTM-Autoencoder

**Note:** All parameters and workflows are based on assumptions and needed to change based on unique dataset. 



The **LSTM_A_newdata** file is used after getting threshold, values, validation from running LSTM_A_normaldata file.
All parameters and pipeline order could be change based on different dataset 



The **Transformer-normaldata** file is still on trial testing process, this includes: 
You can modify the architecture and parameter for utilizing and haveing best performance out of it. 


**Note:** This is the final stage to start, after we have extracted features from rawdata only, this means, any dataset that people receive from sensors must go through a well-structured **Data Analysis Stage** first. 
