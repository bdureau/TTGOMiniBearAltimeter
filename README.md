# TTGOMiniBearAltimeter
This is a smaller version of the TTGO altimeter using the [LILYGO T-QT Pro](https://www.lilygo.cc/products/t-qt-pro?srsltid=AfmBOopF1SZ4JgGggyEN98mcQudv0hQCX8_p8glDDWhrxQgzO5AKA-nX) board

The altimeter looks like this

<img src="/photos/TTGOMiniBearAltimeterBoard1.jpg" width="25%"><img src="/photos/ttgo-t-qt-mini-altimeter.jpg" width="35%">
# Building the code

You will need to download the Arduino ide from the [Arduino web site](https://www.arduino.cc/). 
Make sure that you install ESP32 support
The project depend on the following libraries
  - TFT
  - Adafruit ADXL345
  - Adafruit unified
  - Button2
  - uiwidgets
  
Compile with the following options:

<img src="/photos/LILYGo-T-QT.png" width="35%">

Prior to compiling go to the TFT_eSPI and open up the file User_Setup_Select.h

Comment out the following line

//#include <User_Setup.h> 

and uncomment the following line

#include <User_Setups/Setup211_LilyGo_T_QT_Pro_S3.h>

# Contributing

If you want to contribute to the project just fork my project or send me some code. 

Report any issue or bug that you have

Suggestions and enhancement are welcome

The code is free for you to download and you do not need to buy anything from me. However it cost money to try out new boards, you need to buy them and fly them so if you want to financially help me you can donate via paypal

| Paypal | 
| ------ |
| [![](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/paypalme/bearaltimeter) | 

# Disclaimer

I am not responsible for any damage that could happen. The code is provided as it is
