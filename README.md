# Neural Style Transfer [Keras|Tensorflow v2]

In this repo I re-implement [A Neural Algorithm of Artistic Style](http://arxiv.org/pdf/1508.06576v2.pdf) from scratch entirly on Google Colab, using Imagenet pre-traing VGG19 network, with a lot of interesting gif demos of the reconstruction process from layers and the style transfer process.

<p align="center">
  <img src="https://github.com/mohammed-elkomy/neural-style-transfer-tensorflow/blob/master/gifs/x2.gif"  />
</p>

## How To Use
To run the code through colab you just need add my [drive folder](https://drive.google.com/drive/u/4/folders/1j6AmahNcJ3seM7Davwz2CuXCN87FQQjZ) for style transfer artifacts to your *google drive storage* since the code references content and style images from this folder, also saves generated images to it to generate videos and demos.

You may make your own directory structure on your drive and change the root_path referenced in the notebook, Also make sure of the **_root_path_**  in your drive when mounted to Colab.

<p align="center">
  <img src="https://github.com/mohammed-elkomy/neural-style-transfer-tensorflow/blob/master/gifs/style.jpg"  />
</p>

In summary you may need to 
1) Set the mounted path 
2) modify the layer of interset at **_Precomputing Source Style and Content Representation_**
3) Either Do Style Transfer or Image reconstruction from layer 

### Image Reconstruction using VGG19 features
Modify the layer of interest at **_Precomputing Source Style and Content Representation_** then run **_Recontstruction From Layer Experiment_**.

<p align="center">
  <img src="https://github.com/mohammed-elkomy/neural-style-transfer-tensorflow/blob/master/gifs/0.gif"  />
</p>

### Style Transfer Experiment
Modify the layer of interest at **_Precomputing Source Style and Content Representation_** then run **_Style Transfer  Experiment_**
You may also modify the losses and the weighting of content and style loss.

<p align="center">
  <img src="https://github.com/mohammed-elkomy/neural-style-transfer-tensorflow/blob/master/gifs/3.gif"  />
</p>

## Video to gif 
Converting high resolution videos into gifs isn't a simple task, I used gifski(https://gif.ski/) it's a great and efficient tool for producing high-quality gifs.

### For More Gif Demos
[Here](https://github.com/mohammed-elkomy/neural-style-transfer-tensorflow/tree/master/gifs)

## Reference Papers:
* [A Neural Algorithm of Artistic Style](http://arxiv.org/pdf/1508.06576v2.pdf)





