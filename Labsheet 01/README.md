1. Introduction to OpenCv
* OpenCV - Open Source Computer Vision Library.
* It is an open source computer vision and machine learning software library.
* It is built to provide a common infrastructure for computer vision applications and to 
accelerate the use of machine perception in the commercial products.
* The library has more than 2500 optimized algorithms.
* These algorithms can be used to detect and recognize faces, identify objects, classify 
human actions in videos, track camera movements, track moving objects, extract 3D 
models of objects, etc.

2. Introduction to Python
* Python is an open-source programming language.
* It allows you to run applications and plugins from a wide variety of 3rd party sources (or 
even applications you develop yourself) on your server. 
* It is cross-platform, that you can run it on a number of different operating systems, 
including Windows VPS Server.

3. Introduction to Jupyter Notebook
* The Jupyter Notebook is an open-source web application.
* It allows you to create and share documents that contain live code, equations, 
visualizations and narrative text. 
* Uses include: data cleaning and transformation, numerical simulation, statistical 
modeling, data visualization, machine learning, and much more.

4. How to setup Jupyter Notebook

  - Step 1: Installing Python in Windows

The leading Python site is on https://www.python.org/, and the most up-to-date source 
distribution version for windows is python 3.9.1. It is recommended use a lower version than the 
latest version.

  - Step 2: Confirm that Python is installed

The simplest way to test for a Python installation on your Windows server is to open a command 
prompt. Once a command prompt window opens, type python and press Enter. If Python is 
installed correctly, you should see output similar to what is shown below.

  - Step 3: Installing Pip in Windows

Once you have confirmed that Python is installed correctly, we can proceed with installing Pip.
1. Download get-pip.py to a folder on your computer.
2. Open a command prompt and navigate to the folder containing the get-pip.py installer.
3. Run the following command:
`python get-pip.py`

  - Step 4: Verify Installation and Check the Pip Version

We can now verify that Pip was installed correctly by opening a command prompt and entering 
the following command.
`pip -V`

  - Step 5: Installing OpenCv library using pip command

After the installation of the Python and pip, we can directly install the OpenCV library and start 
using them. To install the library, we need to enter the given command in the terminal.
`pip install opencv-python`

  - Step 6: Installing matplotlib library using pip command

Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations 
in Python. To install the matplotlib, we need to enter the given command in the terminal.

`pip install matplotlib`

  - Step 7: Installing Jupyter notebook using pip command

To install Jupyter notebook using Python’s package manager, pip, we need to enter the given 
command in the terminal.
`python -m pip install jupyter`

  - Step 8: Run Jupyter notebook on Windows

To run the notebook, run the following command in the terminal.
`python -m notebook`

Exercise: Write a small program to:
1. To read and save the image from/in storage device.
2. To access pixel values of an image and modify them.
3. To access image properties.
4. To split and merge channels.
5. To resize/rotate image.
6. To draw circle/rectangle/lines.
7. To write text on image.
8. To covert color to grayscale/binary/negative image
