# NeuralBlock - NeuralNetPredictor
A neural network predictor algorithm for the AI minecraft mod "NeuralBlock".

This is part of a larger project that includes both a Minecraft mod to collect the data:
http://github.com/TheIcyStar/NeuralBlock

and a series of programs to downcast the data into a much more manageable 8 block types:
https://github.com/avc6361/NeuralBlock-Preprocess

This Colab file takes a premade CSV file input of downcasted data from Google Drive via gdown,
  and handles everything the whole way through both KNN and NN model running and analysis.

We use Pandas to handle data, TensorFlow Keras for the Neural Network, sklearn for K Nearest Neighbor, 
  and various other tools like Numpy and Matplotlib for analysis and data display.

- Joseph Cooper

Created in collaboration with:
- Alex Petrov
- Alex Chmeilowski
- Tyler Lawer
