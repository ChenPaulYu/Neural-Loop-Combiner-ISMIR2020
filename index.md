This is the demo page for the paper [Neural Loop Combiner: Neural Network Models for Assessing the Compatibility of Loops](https://arxiv.org/abs/2008.02011)

## Abstract
Music producers who use loops may have access to thousands in loop libraries, but finding ones that are compatible is a time-consuming process; we hope to reduce this burden with automation. State-of-the-art systems for estimating compatibility, such as AutoMashUpper, are mostly rule-based and could be improved on with machine learning. To train a model, we need a large set of loops with ground truth compatibility values. No such dataset exists, so we extract loops from existing music to obtain positive examples of compatible loops, and propose and compare various strategies for choosing negative examples. For reproducibility, we curate data from the Free Music Archive. Using this data, we investigate two types of model architectures for estimating the compatibility of loops: one based on a Siamese network, and the other a pure convolutional neural network (CNN). We conducted a user study in which participants rated the quality of the combinations suggested by each model, and found the CNN to outperform the Siamese network. Both model-based approaches outperformed the rule-based one. We have opened source the code for building the models and the dataset.

### Demo audio
Audio in the same row share identical first 4 bars prompt. ***No grooving*** and ***Hard grooving***  model are asked to generate 16-bar continuations based on the prompt input.

|   |Query loop|Original|AutoMashupper|CNN+reverse|
|1.|<audio src="result/Q1/src.wav" controls="" preload=""></audio>|<audio src="result/Q1/ori.wav" controls="" preload=""></audio>|<audio src="result/Q1/atp.wav" controls="" preload=""></audio>|<audio src="result/Q1/cnn.wav" controls="" preload=""></audio>|
|2.|<audio src="result/Q2/src.wav" controls="" preload=""></audio>|<audio src="result/Q2/ori.wav" controls="" preload=""></audio>|<audio src="result/Q2/atp.wav" controls="" preload=""></audio>|<audio src="result/Q2/cnn.wav" controls="" preload=""></audio>|
|3.|<audio src="result/Q3/src.wav" controls="" preload=""></audio>|<audio src="result/Q3/ori.wav" controls="" preload=""></audio>|<audio src="result/Q3/atp.wav" controls="" preload=""></audio>|<audio src="result/Q3/cnn.wav" controls="" preload=""></audio>|
|4.|<audio src="result/Q4/src.wav" controls="" preload=""></audio>|<audio src="result/Q4/ori.wav" controls="" preload=""></audio>|<audio src="result/Q4/atp.wav" controls="" preload=""></audio>|<audio src="result/Q4/cnn.wav" controls="" preload=""></audio>|
|5.|<audio src="result/Q5/src.wav" controls="" preload=""></audio>|<audio src="result/Q5/ori.wav" controls="" preload=""></audio>|<audio src="result/Q5/atp.wav" controls="" preload=""></audio>|<audio src="result/Q5/cnn.wav" controls="" preload=""></audio>|
|6.|<audio src="result/Q6/src.wav" controls="" preload=""></audio>|<audio src="result/Q6/ori.wav" controls="" preload=""></audio>|<audio src="result/Q6/atp.wav" controls="" preload=""></audio>|<audio src="result/Q6/cnn.wav" controls="" preload=""></audio>|

### Demo Video
This video recording is a guitarist from our team playing a generated tab which is generated from scratch.
<iframe width="800" height="500" src="https://www.youtube.com/embed/yccH6kvinq0">
</iframe>

### Contact 
Bo-Yu Chen bernie40916@gmail.com
