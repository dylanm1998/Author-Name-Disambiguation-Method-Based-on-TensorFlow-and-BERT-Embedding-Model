# Author Name Disambiguation Method Based on TensorFlow and BERT Embedding Model


Experiment data:
https://drive.google.com/drive/folders/15qHCm_ca6zGd1L4KAuhH7OhHgAXokktX?usp=drive_link

During the model training process, since Tensorflow will give priority to the GPU, I encountered a CUDA error in my experimental environment. It may be a problem with the experimental environment. So code to disable the GPU was added at the beginning of the code. Please pay attention.


When choosing a BERT model, please use low dimensions during the debugging phase, otherwise the embedding process will last dozens or even hundreds of hours.
