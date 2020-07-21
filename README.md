# YoloV4-ncnn-Raspberry-Pi-64-bit
![output image]( https://qengineering.eu/images/Mumbai_YoloV4.jpg )

## YoloV4 with the ncnn framework.
The frame rate is about 3 FPS (RPi overclocked to 1950 MHz)<br/>
Paper: https://arxiv.org/pdf/2004.10934.pdf <br/>
Size: 550x550 <br/><br/>
Special made for a bare Raspberry Pi see https://qengineering.eu/deep-learning-examples-on-raspberry-32-64-os.html <br/>
## Dependencies.
To run the application, you have to:
- A raspberry Pi 4 with a 64-bit operating system. It can be the Raspberry 64-bit OS, or Ubuntu 18.04 / 20.04. (https://qengineering.eu/install-raspberry-64-os.html) <br/>
- The Tencent ncnn framework installed. (https://qengineering.eu/install-ncnn-on-raspberry-pi-4.html) <br/>
- OpenCV 64 bit installed. (https://qengineering.eu/install-opencv-4.3-on-raspberry-64-os.html) <br/>
- Code::Blocks installed.
## Running the app.
To extract and run the network in Code::Blocks <br/>
$ mkdir *MyDir* <br/>
$ cd *MyDir* <br/>
$ wget https://github.com/Qengineering/YoloV4-ncnn-Raspberry-Pi-64-bit/archive/master.zip <br/>
$ unzip -j master.zip <br/>
Remove master.zip and README.md as they are no longer needed. <br/> 
$ rm master.zip <br/>
$ rm README.md <br/> <br/>
Your *MyDir* folder must now look like this: <br/> 
dog.jpg <br/>
mumbai.jpg <br/>
YoloV4.cpb <br/>
yoloV4.cpp <br/>
yolov4-tiny-opt.bin <br/>
yol0v4-tiny-opt.param <br/>
yolov4.bin (download this file from [Gdrive](https://drive.google.com/file/d/1vu3GGOEWh-jmedM-cvoqzhGzaZaOQB9k) )<br/>
yolov4.param <br/><br/>
Many thanks to [nihui](https://github.com/nihui/) again!