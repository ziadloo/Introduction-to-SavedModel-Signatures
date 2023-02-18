# Introduction to SavedModel Signatures
Using SavedModel Signatures to include preprocessing and postprocessing graphs for your Keras models.

When trainging a model, the input features and the model's output are designed in way suitable for training. But that does not mean they are also suitable for serving. This is specially prominent when your training phase comes with a preprocessing and/or postprocessing step. Such steps are not saved into the model by default. In Keras (Tensorflow), SavedModel comes with a feature called Signatures which can be leveraged to save the processing and postprocessing alongside your model.

In this repo, you can find an example how to do so using [Palmer's Penguin dataset](https://github.com/allisonhorst/palmerpenguins)
