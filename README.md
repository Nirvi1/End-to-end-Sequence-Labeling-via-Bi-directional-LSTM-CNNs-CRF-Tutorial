# End-to-end-Sequence-Labeling-via-CNNs-CRF 

This repository is built upon this [**End-to-end-Sequence-Labeling-via-Bi-directional-LSTM-CNNs-CRF**] and my codebase replaces the LSTM-based word-level encoder with a CNN layer. 


## Setup details

### 1. Upload the entire **CE7455A2-G2004830** folder into google colab. 

CE7455A2-G2004830 should contain following -

####  A2_G2004830.ipynb is the jupyter notebook file that contains the source code.


### 3. Installation
The best way to install pytorch is via the [**pytorch webpage**](http://pytorch.org/)

####  PyTorch Installation command:
`conda install pytorch torchvision -c pytorch`

### 4. Open **A2_G2004830.ipynb** in Google Colab

#### **Important things to note**:
1. Code will automatically download the dataset, no need to download manually.
2. In the code cell with initialised parameters, edit `parameters['word_encoder_mode']` and `parameters['relu']` in order to choose your model
3. Uncomment out `parameters['reload']=False` in order to train the model you have chosen.  
