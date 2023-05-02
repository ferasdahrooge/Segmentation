# Segmentation

### Introduction

- Semantic segmentation is the process of assigning a class label to each pixel in an image. In other words, it is a classification task done on a pixel-by-pixel basis. This is particularily useful in separating certain elements from the background.

- Some practical applications for this technology include:

  - - self-driving technology
  - - medical imaging
  - - augmented reality

- Typical semantic segmentation architectures follow an encoder-decoder pattern, where the encoders compress the information into lower-dimensional representations, and the decoders project this information back to the original image dimensions. This tutorial will begin by using a pre-trained model from the PyTorch library, followed by training a semantic segmentation model using the segmentation-models-pytorch library.

* IDE : Google Colab
