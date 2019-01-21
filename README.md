# Neural_Machine_Translator_seq2seq
Neural Machine Translator (NMT) for translating from english to hindi text. Used Pytorch framework with seq2seq architecture having Attention functionality .<br/>
The Jupyter Notebook given in this repository is self explanatory and well documented.

![](https://cdn-images-1.medium.com/max/1600/1*75Jb0q3sX1GDYmJSfl-gOw.gif)

# Dependencies
Pytorch == 0.3.0<br/>
Numpy == 1.14.2

[This](https://medium.com/@umerfarooq_26378/neural-machine-translation-with-code-68c425044bbd) blog explains NMT really well !

# Dataset
There are various sources from where you can download the eng-hind.txt parallel corpus : -<br/>
1. [IIT-Bombay Dataset](http://www.cfilt.iitb.ac.in/iitb_parallel/iitb_corpus_download/)<br/>
2. [HindEnCorp 0.5](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0023-625F-0)<br/>
3. [Indian parallel Corpora](https://github.com/joshua-decoder/indian-parallel-corpora)<br/>

The dataset file should be a tab seperated file having text in the following way - <br/>
I am cold.  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; मुझे ठंड लग रही है। <br/>
My name is yash &nbsp;&nbsp;  मेरा नाम यश है <br/>
.          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   .<br/>
.        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;     .<br/>

The jupyter notebook given here is for educational purpose, and if you wish to see some good results then I would highly recommend you to git clone one of the following repositories -<br/>

1.[Stanford NMT](https://nlp.stanford.edu/projects/nmt/) [Matlab] <br/>
2.[tf-seq2seq](https://github.com/google/seq2seq) [TensorFlow] <br/>
3.[Nemantus](https://github.com/rsennrich/nematus) [Theano] <br/>
4.[OpenNMT](https://github.com/OpenNMT/OpenNMT) [Torch with Lua Language]---> Highly recommended, incorporates all the functionalities <br/>
5.[OpenNMT-py](https://github.com/OpenNMT/OpenNMT-py) [PyTorch]<br/>

# Papers
A Statistical Approach to Machine Translation, 1990.<br/>
Review Article: Example-based Machine Translation, 1999.<br/>
Learning Phrase Representations using RNN Encoder-Decoder for Statistical Machine Translation, 2014.<br/>
Neural Machine Translation by Jointly Learning to Align and Translate, 2014.<br/>
Google’s Neural Machine Translation System: Bridging the Gap between Human and Machine Translation, 2016.<br/>
Sequence to sequence learning with neural networks, 2014.<br/>
Recurrent Continuous Translation Models, 2013.<br/>
Continuous space translation models for phrase-based statistical machine translation, 2013.<br/>

# Acknowledgements
A big Thank you to the whole team of [Messy Fractals](https://messyfractals.wordpress.com/), especially [Dhanya P](https://www.linkedin.com/in/dhanyap/?originalSubdomain=in) and [Arvind Sivdas](https://www.linkedin.com/in/arvindsivdas/?originalSubdomain=in) for letting me work under them, for this project . <br/>

# References
The credits for this code go to the user [spro](https://github.com/spro/practical-pytorch/blob/master/seq2seq-translation/seq2seq-translation.ipynb). I have merely made some changes in it for dealing with Hindi text.
