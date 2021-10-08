# Target1-Hackathon

## Goal: 

To identify the plant category (grass, broadleaf, clover) and to detect the plant size (small, medium, or large). For the plant identification you should use the RGB inference camera, create the pipeline with the camera for using a semantic segmentation model we will provide you (for bonus points you could use your own model). For the plant size you should use the depth camera integrated also with the RGB inference camera.

A complete visualization tool would identify the plant category and size in real time.

## Resources:
TensorFlow Model (.pb format) (Tensorflow==1.15)
RPi 4(8GB) - 128GB (MicroSD Card) with accesories (Adaptor+MicroHDMI+switch)
1 OAK-D camera with accesories (Adaptor+USBC-3-cable)
1 Tripod

![](https://lh5.googleusercontent.com/WtM-Kst0wuQMg5hsTHavC5QDaKrxGhIhloG0uFUXzlnPzDLU-qPBP8yCbhBKBzLzAXNYk5wyr--1_pC0aPOGhTyyitEJkM78LOdwoLqFILBSrd4T6dFdYNzS6OEMAHZwSOJtV9k3=s0)

Warning: 

- The OAK-D camera should be connected to the RPi USB3 ports with the USB-3 cable you could find into the camera box.

![](https://lh4.googleusercontent.com/69kh1PBybX8urfH3Pl2YH6-4P1_2rjf8ncJpBz47B11QEMhVbpwJ-sqK9j3JVLlzko440sku5QYOvrFmVChF-eoVeaNF5gBYcZhHyiQQCzhhCCP6yh29XX2qpMOKtROBaHXKlhw8=s0)

- Power cable (USB-3.5mm) just use the computer port (different that RPis port) or one 5V-2A adaptor.
- Please do not use cables other than those provided.
- Ethernet port is used to connect the Machine Motion Driver, you should connect this when you test your deployment with the BenchBot.

1. The RPis are already registered on the **ncsu** WiFi Network, you could see the Static IP address for each kit on the canakit box.

2. If you are note able to connect please contact one of your mentors and check the connectivity using monitor, keyboard and mouse.

3. The depthai library is preinstalled in the RPi and the cameras are precalibrated, you are able to run the demo file **/home/pi/depthai/depthai_demo.py**

4. Please follow the instructions and documentation of [Luxonis' webpage](https://docs.luxonis.com/en/latest/pages/tutorials/first_steps/) to understand better the camera uses.

5. Happy hacking!!!



