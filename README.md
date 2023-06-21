# Rice-Disease-Detection-With-ResNet-ans-Self_Attention
# Project Description
This project is solving the crisis of rice leaf diseases by building a classifier that can early classify rice leaf diseases for better treatment. The implementation is a merge between the implementation of two research papers. The first paper is Designing self attention-based ResNet architecture for rice leaf disease classification which adds two layers of self-attention in between the layers of a pre-trained ResNet-34 for better feature extraction. The second paper is Learn to pay attention which add three self-attention layers outside a pre-trained Vgg-16, and then adds the classification layers after thoso attention layers.

My implementation adds two self-attention layers (The second paper) outside a pre-trained ResNet-34 (The first paper). The model architecture is shown in the figure below.
![242939273-ddbe78ab-151d-408f-8b3b-f9c92ba96d30](https://github.com/omartt4/Rice-Disease-Detection-With-ResNet-ans-Self_Attention/assets/85070236/7273ae50-0262-48bb-873e-b9f482195ef2)

# Dataset
The training dataset was taking from this Zindi competition for rice disease classification.

The test dataset was taken from the sane website, but without labels. After training the model and predicting the test dataset outputs, the prediction were submitted to the competition to get a score.

# Research paper
In the main branch, I have submitted a research paper that was done for the proposed architecture. All of the methodology and results of the proposed solution can be found there.

