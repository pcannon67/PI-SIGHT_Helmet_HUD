# PI-SIGHT Helmet HUD

The PI-SIGHT Helmet HUD is a head-up display device mounted on the outside of a helmet that displays essential information directly in front of the user's eyes. Users can view necessary information or rear-view camera footage on the display without moving their head.

The device's most notable feature is its use of a Raspberry Pi, a compact general-purpose computer, and an interchangeable module system. This allows users to program or replace the software themselves with whatever they need. By connecting a Bluetooth headset or GPS module, the device can be used for a variety of purposes, including navigation, racing instrumentation, and aircraft instrumentation.


## function

 - Prism Display: You can check the necessary information without moving your head or holding a separate device through the 3000cd/m^2 display located in front of your eyes.
 - General-purpose system: Using the Raspberry Pi, a general-purpose Linux computer, you can easily develop and apply programs and sensors tailored to your purpose.
 - Interchangeable module system: Allows for easy replacement of programs and modules, allowing one device to be used for a variety of activities.
 - For more information on wireless remote control, rear camera, etc., please visit the [VUDEV website](https://sites.google.com/vudev.net/vudevnet/about-pi-sight) or download the [manual](https://github.com/younsj97/PI-SIGHT_Helmet_HUD/blob/main/PI-SIGHT%20%EC%82%AC%EC%9A%A9%EC%84%A4%EB%AA%85%EC%84%9C-1%20(%EB%94%94%EB%B0%94%EC%9D%B4%EC%8A%A4%20%EA%B8%B0%EB%B3%B8).pdf)


## Software

 1. [Openauto](https://github.com/younsj97/PI-SIGHT_SW_Openauto): You can use it as an Android Auto head unit by connecting it to an Android smartphone.
 2. [GPS Racer](https://github.com/younsj97/PI-SIGHT_SW_GPSRacer): It can be used as a self-lap timer or a Bluetooth GPS receiver that connects to a smartphone.
 3. [Rearview](https://github.com/younsj97/PI-SIGHT_SW_Rearview): Shows real-time rear camera video and automatically records during operation.
 - Anyone can create and use the programs and modules they need.


## How to make

 - Scheduled to be uploaded


## caution

 _PI-SIGHT has not been sufficiently tested in various environments. While you are free to create and use it, we are not responsible for any problems that may arise from doing so._
 - _PI-SIGHT is not dustproof or waterproof. Please do not let water get into it_
 - _If the tension adjustment bolt of the prism display is too loose, the display may move during use, which may be dangerous_


## Customizing

 - For wireless remote control firmware, please refer to [PI-SIGHT Remote Controller SW](https://github.com/younsj97/PI-SIGHT_SW_RemoteController)
 - For PCB circuit and module connector, please refer to the [circuit](https://github.com/younsj97/PI-SIGHT_Helmet_HUD/blob/main/Documents/Circuits.pdf)