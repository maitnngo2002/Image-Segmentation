# Image-Segmentation

To run the file on Google Colab or any IDE, you must first install the Tensorflow Examples module with:

`!pip install git+https://github.com/tensorflow/examples.git`

I train and test this image segmentation model using the **Oxford-IIIT Pets dataset** (can be downloaded from Tensorflow Dataset)

The image segmentation model is a kind of encoder-decoder structure in which the encoder will **downsample** the input and output a tensor containing information about the objects, its shape and size. Then the decoder will take these information to produce segmentation maps (which is called **upsample**).


