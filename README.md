# INFINITE-e-textile-workshop-
The following steps show how to install Arduino IDE and some useful libraries. Having these installed on your PC allows you to use INFINITE e-textile toolkit to create interactive projects. Please install before the e-textile workshop. 
> Ask Mei on Friday if you have problem 

## Download Arduino IDE and Adafruit Feather M0 environment
> You can follow Adafruit Feather M0 tutorail on [Arduino IDE Setup](https://learn.adafruit.com/adafruit-feather-m0-basic-proto/setup) then [Using with Arduino IDE](https://learn.adafruit.com/adafruit-feather-m0-basic-proto/using-with-arduino-ide), or see the following steps in short

### Step 1

Download and install the Arduino IDE from https://www.arduino.cc/en/Main/Software

### Step 2

Start the Arduino IDE, and in the menu bar click **Arduino** > **Preference**

Copy and paste the follow URL into **Additional Boards Manager URLs**, then click **OK**

*https://adafruit.github.io/arduino-board-index/package_adafruit_index.json*

### Step 3

Click **Tools** > **Board:**>**Board Manager...**， on the search bar on top search *Arduino SAMD Boards*, click **Install** 

### Step 4

Same as Step 3, on the search bar on top search *Adafruit SAMD*, click **Install** 

### Step 5

Quite and reopen Arduino IDE, click **Tools** > **Boards:** > **Adafruit Feather M0**

*Now your Arduino IDE is ready for Feather M0 board*

## Install library for movement and heating functions

To get started with the movement and heating functions, you need to download and install the library for the motor driver, [click here to download](https://github.com/sparkfun/SparkFun_TB6612FNG_Arduino_Library/archive/master.zip). Once downloaded, unzip the folder. Then you will need to find where your Arduino IDE foler is located, and move the unzipped folder to **Arduino** -> **Libraries**, for example, my Arduino folder is located here:

<p align="center">
  <img src="https://github.com/Mei2020/INFINITE-e-textile-workshop-/blob/main/pics/motor_step1.JPG">
  </p>

## Install library for MP3 player 

To get started with the audio function, you need to install its library into the Arduino IDE, first, open Arduino menu **Tools** -> **Manage Libraries** 
<p align="center">
<img src="https://github.com/Mei2020/INFINITE-e-textile-workshop-/blob/main/pics/MP3_step1.png">
</p> 

then, on the top right of the **Library Manager** window, search for **Adafruit_VS1053**, click **install**

<p align="center">
<img src="https://github.com/Mei2020/INFINITE-e-textile-workshop-/blob/main/pics/MP3_step2.png">
</p>

