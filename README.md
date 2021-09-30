# Target1-Hackathon

Goal: 

To identify the plant category (grass, broadleaf, clover) and to detect the plant size (small, medium, or large). For the plant identification you should use the RGB inference camera, create the pipeline with the camera for using a semantic segmentation model we will provide you (for bonus points you could use your own model). For the plant size you should use the depth camera integrated also with the RGB inference camera.

We are expecting to see into a visualization tool, the detection and the size of the plant in real time.

Resources:
TensorFlow Model (.pb format) (Tensorflow==1.15)
RPi 4(8GB) - 128GB (MicroSD Card) with accesories
1 OAK-D camera with accesories

Warning: Power cable (USB-3.5mm) just use the computer port (different that RPis port) or one 5V-2A adaptor

1. Verify OAK-D camera kiy:
    - RPi
    - MicroSD Card 128 GB
    - Cable HDMI-MicroHDMI
    - ...

2. Verify connection...
  - screen
  - register hotspot or wifi signal to the same wifi network your computer is connected.
  - ipconfig ....
  - get the RPi IP address

3. Download libraries you should use to control and use the OAK-D camera
  - [https://docs.luxonis.com/en/latest/pages/tutorials/first_steps/](https://docs.luxonis.com/en/latest/pages/tutorials/first_steps/)

4. Install the camera in the tripod and connect it to your RPi.

5. Calibrate the camera and test the demo python script.
   - [https://docs.luxonis.com/en/latest/pages/calibration/](https://docs.luxonis.com/en/latest/pages/calibration/)

6. Happy hacking!!!

