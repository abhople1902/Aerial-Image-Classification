# Aerial-Image-Classification
<hr>
A repository with code for altering the output of VGG19 architecture by concatenating each layer's output and then passing it into the FC layer.

## Model recreation
The model recreation file demonstrates the use of the concatenation technique to achieve an output that can be further passed to the FC layer.
### Well what is different?
The output through the complete architecture is based on the combined granularities of each layer. Still, here we are demonstrating how we can use the granular throughput of each layer to make a customized model. Many things could be done with it so feel free to extend your creativity and use this idea to innovate something more profound.

## Implementation notebook
This notebook has the model loaded and used to classify the Aerial Image Dataset (AID).

Maybe this is not a breakthrough code repository with some patentable idea but I hope it would be useful for exploring deep into the subject.
