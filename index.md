This is the demo page for the paper [Neural Loop Combiner: Neural Network Models for Assessing the Compatibility of Loops](https://arxiv.org/abs/2008.02011)

## Abstract
Music producers who use loops may have access to thousands in loop libraries, but finding ones that are compatible is a time-consuming process; we hope to reduce this burden with automation. State-of-the-art systems for estimating compatibility, such as AutoMashUpper, are mostly rule-based and could be improved on with machine learning. To train a model, we need a large set of loops with ground truth compatibility values. No such dataset exists, so we extract loops from existing music to obtain positive examples of compatible loops, and propose and compare various strategies for choosing negative examples. For reproducibility, we curate data from the Free Music Archive. Using this data, we investigate two types of model architectures for estimating the compatibility of loops: one based on a Siamese network, and the other a pure convolutional neural network (CNN). We conducted a user study in which participants rated the quality of the combinations suggested by each model, and found the CNN to outperform the Siamese network. Both model-based approaches outperformed the rule-based one. We have opened source the code for building the models and the dataset.

### [Interactive Demo Website](https://paulyuchen.com/mashup-ml-client/)

### Demo audio

1. Query loop (`Query`)
2. Loop combination made by human based on Query loop (`Original`)
3. Generated loop combination based on Query loop by `AutoMashupper`
4. Generated loop combination based on Query loop by `CNN+reverse`

|   |Query|Original|AutoMashUpper|CNN+Reverse|
|1.|<audio src="result/Q1/src.wav" controls="" preload=""></audio>|<audio src="result/Q1/ori.wav" controls="" preload=""></audio>|<audio src="result/Q1/atp.wav" controls="" preload=""></audio>|<audio src="result/Q1/cnn.wav" controls="" preload=""></audio>|
|2.|<audio src="result/Q2/src.wav" controls="" preload=""></audio>|<audio src="result/Q2/ori.wav" controls="" preload=""></audio>|<audio src="result/Q2/atp.wav" controls="" preload=""></audio>|<audio src="result/Q2/cnn.wav" controls="" preload=""></audio>|
|3.|<audio src="result/Q3/src.wav" controls="" preload=""></audio>|<audio src="result/Q3/ori.wav" controls="" preload=""></audio>|<audio src="result/Q3/atp.wav" controls="" preload=""></audio>|<audio src="result/Q3/cnn.wav" controls="" preload=""></audio>|
|4.|<audio src="result/Q4/src.wav" controls="" preload=""></audio>|<audio src="result/Q4/ori.wav" controls="" preload=""></audio>|<audio src="result/Q4/atp.wav" controls="" preload=""></audio>|<audio src="result/Q4/cnn.wav" controls="" preload=""></audio>|
|5.|<audio src="result/Q5/src.wav" controls="" preload=""></audio>|<audio src="result/Q5/ori.wav" controls="" preload=""></audio>|<audio src="result/Q5/atp.wav" controls="" preload=""></audio>|<audio src="result/Q5/cnn.wav" controls="" preload=""></audio>|
|6.|<audio src="result/Q6/src.wav" controls="" preload=""></audio>|<audio src="result/Q6/ori.wav" controls="" preload=""></audio>|<audio src="result/Q6/atp.wav" controls="" preload=""></audio>|<audio src="result/Q6/cnn.wav" controls="" preload=""></audio>|

### Demo Video

<iframe width="560" height="315" src="https://www.youtube.com/embed/NfYeEZ6h0fc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

ps: [Slide](https://www.slideshare.net/secret/Ls1MW17LWmukyK)


### Contact 
Bo-Yu Chen bernie40916@gmail.com
