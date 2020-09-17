# Keras-Char-LSTM

Implements simple character level name classification using Keras LSTM and Dense layers. Training is done using about 20K names across 18 languages. The names are clubbed into three categories : English, Russian, Other for simplicity. Using SGD as optimizer produces poor results, Adam performs better, Nadam even better.

Also implements the same using pytorch, be careful of initializating the LSTM properly when using pytorch, unlike Keras, a proper initialization of the LSTM parameters is not automatically done for you. 
