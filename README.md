# Automatic-Math-Word-Problem

We have worked on following parts of the projects:

1. How to preprocess and tokenize the text datasets. 
2. How to create datasets so that we can directly feed it to different types of models.
3. We have tried different types of pre-built models of tensorflow in which we are getting various accuracy.  
a) Seq2Seq model that uses encoder, decoder and and attention model. Tensorflow source
b) Same Seq2seq model with some modifications such that adding bidirectional GRU layer and dropout layer in encoder and LSTM layer in decoder. Tensorflow source
c) Next we tried for transformer model and got some efficient accuracy with single equation problems i.e., 68% (best accuracy as compared to above two). Tensorflow source
5. We check our models by two methods i.e., accuracy and Corpus Bleu score.
All above methods we tried is for single equation problem. And, this single equation datasets we have generated from a github repo. 
6. While for double equations problem we run Dolphin datasets on a GitHub model. 
Now, we want to process our work as follows: either we should improve our model for single equation datasets or we should study more for double equations datasets as we haven't get more idea for this by running one github repo. 
