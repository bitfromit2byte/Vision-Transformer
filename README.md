# Vision-Transformer
This notebook shows a personally made vision transformer modeled by authors of the paper 
'An image is worth 16x16 words: transformers for image recognition at scale'

Link to Paper: https://arxiv.org/abs/2010.11929 

The Vision Transformer made is trained on the CIFAR-10 dataset.
It can be observed that without the fancy training schedule and compute power used by 
researchers to process a much larger dataset, results produced aren't good.

I also show that a pretrained model can be used using transfer learning 
to classify a dataset and that by using frozen layers, classification can be improved drastically

I followed a break down of this model according to Daniel Bourke's paper replication presentation

Paper Replicating Presentation: https://www.learnpytorch.io/08_pytorch_paper_replicating/ 
