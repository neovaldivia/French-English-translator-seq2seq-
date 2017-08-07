# French-English-translator-seq2seq-
French to English translator

Machine translation project using LSTM-based se2seq

Modules:
Encoder and Decoder based on 

Required:
Conda
TF 1.0 Layers API
Python 3.5

Perfomance:
Train Accuracy:  0.937
Validation Accuracy:  0.940
Loss:  0.042

Sample:

Input
  Word Ids:      [73, 120, 175, 64, 162]
  English Words: ['he', 'saw', 'a', 'red', 'truck']

Prediction
  Word Ids:      [298, 343, 129, 254, 117, 47, 306, 341, 1]
  French Words: ['il', 'a', 'pas', 'un', 'lac', 'automobile', 'rouge', '.', '<EOS>']
