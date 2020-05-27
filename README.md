# My repo of Jupyter Notebooks from Google Colab

- [keras_2_onnx.ipynb](./keras_2_onnx.ipynb): this example converts a keras' efficient model into onnx format;
- [TensorFlow_Keras_EfficientNet_onnx.ipynb](./TensorFlow_Keras_EfficientNet_onnx.ipynb): this is the keras2onnx example with few adaptations. It loads an existing HDF5 file, does some inference, saves the ONNX, loads the onnx files, and does the inference on the same previous image;
- [MNIST_onnx_runtime.ipynb](./MNIST_onnx_runtime.ipynb): learning how to perform ONNX inference with MNIST dataset and a hand-crafted CNN based on lenet;
- [MNIST_keras2onnx.ipynb](./MNIST_keras2onnx.ipynb): a full process of creating the CNN model for MNIST in keras, its evaluation, a conversion to ONNX. Then the ONNX file is loaded to compare it's prediction against keras;
- [TensorFlow_Keras_MNIST.ipynb](./TensorFlow_Keras_MNIST.ipynb): this is an example notebook contributed to [keras2onnx](https://github.com/onnx/keras-onnx) conversion tool;
