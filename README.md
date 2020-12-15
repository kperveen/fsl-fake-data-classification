# fsl-fake-data-classification
Classify a given content as either fake or fact using Few-Shot-Learning and Baseline BERT and compare the performance of both approaches for fake data classification using limited labeled dataset. 

## Implementation

### BERT

The models for BERT were created using pytorch.

- Train the model on 90:10 train:test ratio and evaluate it
- Train the model on 50:50 train:rest ratio and evaluate it
- Train the model on 10:90 train:test ratio and evaluate it

### Few-shot learning

The few shot learning model used was Reptile which works by training the model on K-samples, the sample size used for this project was 20. The model was trained on sparse-categorical cross-entropy loss using stochatic gradient descent. 

