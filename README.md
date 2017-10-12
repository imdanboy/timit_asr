# timit_asr
automatic speech recognition on timit dataset

**It is the implementation of the paper 'convolutional attention-based seq2seq neural network for end-to-end asr'**

## required library
- tensorflow-gpu verison 1.3 (https://www.tensorflow.org/)
- python_speech_features (https://github.com/jameslyons/python_speech_features)
- scikit-learn (http://scikit-learn.org/stable/)
- sox: convert TIMIT file format to 'wav' (http://sox.sourceforge.net/)

## reproducible research
- Windows 10, Intel i5-4690 CPU, 8GB RAM, GTX 1070
- It seems that current tf version (1.3) at the time of writing (2017-10-12) could not produce exact same results even if it start with same seed via 'tf.set_random_seed'. please refer to https://github.com/tensorflow/tensorflow/issues/2732 

## script
1) prepare_dataset - [nbviewer](http://nbviewer.jupyter.org/github/imdanboy/timit_asr/blob/master/prepare_dataset.ipynb)
2) train_model - [nbviewer](http://nbviewer.jupyter.org/github/imdanboy/timit_asr/blob/master/train_model.ipynb)
