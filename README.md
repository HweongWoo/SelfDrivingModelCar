# SelfDrivingModelCar

## Hardware Platform
- NVIDIA Jetson TX2

## Camera
- LI-IMX377-MIPI-CS
- LI-JTX1-MIPI_ADPT

## Model Car
- Traxxax 1/16 Slash 4X4(Brushed)
- motor: Titan 12T 550

## Requirement
- JetPack3.1
    - L4T 28.1
    - CUDA 8.0
    - cuDNN 6.0
- CMake
- i2c-tools
    - `sudo apt-get install libi2c-dev`
- TensorFlow for TX2
    - http://www.jetsonhacks.com/2017/09/22/install-tensorflow-python-nvidia-jetson-tx-dev-kits/
- H5py
    - sudo pip install h5py
- Keras(2.1.5)
    - sudo pip install keras
- SciPy for Python
    - `sudo apt-get install python-scipy`
- NumPy
    - `sudo apt-get install python-numpy`
- OpenCV for TX2
    - http://www.jetsonhacks.com/2017/04/05/build-opencv-nvidia-jetson-tx2/

