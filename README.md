# Keras-Char-LSTM

Implements simple character level name classification using Keras LSTM and Dense layers. Training is done using about 20K names across 18 languages. The names are clubbed into three categories : English, Russian, Other for simplicity. Using SGD as optimizer produces poor results, Adam performs better, Nadam even better. 
