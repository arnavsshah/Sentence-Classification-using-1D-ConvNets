# Sentence-Classification-using-1D-ConvNets
Implementation of 1D Convolutional Neural Network for Sentence Classification based on the paper by [Yoon Kim(2014)]

[Yoon Kim(2014)]: <https://www.aclweb.org/anthology/D14-1181.pdf>

## Datasets
- Large Movie Review Dataset (https://ai.stanford.edu/~amaas/data/sentiment/)
- TREC (http://cogcomp.cs.illinois.edu/Data/QA/QC/)

## Hyperparameters(KimNet)
- Glove vecotrs with 100-dimensional embedding vectors
- Drouput rate set to 0.5
- Batch size set to 50 and trained for 6 epochs
- Kernel size for Convolutions - {3, 4, 5} with filter size as 100

## KimNet Architechure 
![KimNet architecture](assets/kim_architecture.png)

![Kim model summary](assets/kim_model_plot.png)

## ShallowNet Architecture
![Shallow model summary](assets/shallow_model_plot.png)