# My first computer vision project

This is an instance of video tracking or the process of locating a moving object (or multiple objects) over time using a camera.
If you are holding a an object in hand, please do make  movements with it near the camera so that the object gets detected.
I have taken help from various online blogs and youtube channels.
To reproduce this code,  please fork and clone this repo to get started!

## Dependancies

We require openCV for this.
The major dependancies are mentioned [here](https://docs.opencv.org/3.4.1/d2/de6/tutorial_py_setup_in_ubuntu.html)
Enter the following commands into your terminal:

### If you do not have conda installed

```
sudo apt-get install python-opencv
```

#### Required build dependencies

```
#We need CMake to configure the installation, GCC for compilation, Python-devel and Numpy for building Python bindings etc.
sudo apt-get install cmake
sudo apt-get install python-devel numpy
sudo apt-get install gcc gcc-c++
#Next we need GTK support for GUI features, Camera support (libv4l), Media Support (ffmpeg, gstreamer) etc.
sudo apt-get install gtk2-devel
sudo apt-get install libv4l-devel
sudo apt-get install ffmpeg-devel
sudo apt-get install gstreamer-plugins-base-devel
```

### Using conda

```
conda install opencv
```

#### Required build dependencies in conda

```
conda install -c anaconda cmake
conda install -c anaconda numpy-devel
sudo apt-get install gcc
sudo apt-get install g++
conda install -c anaconda gtk2-devel-cos6-x86_64
#conda install -c groakat ffmpeg-dev
#conda install -c danielballan ffmpeg
conda install -c conda-forge gstreamer 
conda install -c anaconda pkgconfig
conda remove opencv
conda update conda
conda install --channel menpo opencv
```

## Download latest openCV

```
git clone https://github.com/opencv/opencv.git
mkdir build
cd build
cmake ../
 ```

## Run your project:)

 Use python 2 as python 3 does not support xrange function.
 Your dependancies may be installed with ```Python 3.6.5 :: Anaconda, Inc.``` , but still run with python 2. It does not matter.

 ```
 python2 project.py
 ```
