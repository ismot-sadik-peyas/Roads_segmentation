# Roads_segmentation
The aim of this project is road detection from satellite images using a variant of deep Convolutional Neural Networks which is known as U-Net. The output of the model is a segmentation mask which differentiates roads from other terrains.
# Dependencies
Keras with TensorFlow backend
Numpy
Matplotlib
OS
OpenCV
H5py

**Dataset**
per-pixel-classification technique is used, which means that a single pixel generates one feature vector, so an 1500x1500 image will generate 2250000 vectors, which is too large to be handled by a personal computer, that's why the 'convertToFeatureFiles.py' script generates only 200000 vectors per file. full dataset is collecled from https://www.cs.toronto.edu/~vmnih/data/ which provide Massachusetts Roads Dataset of salletile imagery.
