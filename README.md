# Birthday Card
Birthday greeting card using Arduino UNO, TFT LCD touch screen 2.4" Shield and SD Card from the tiktok https://vt.tiktok.com/ZSdJf91JV/. 

Arduino UNO is programmed with Arduino IDE and uses 3 libraries, namely Adafruit BusIO, Adafruit GFX and Adafruit TFTLCD.

## Components and Tools
1. Arduino Uno and USB Connector
2. TFT LCD touch screen 2.4" Shield (240x360)
3. SD Card
4. SD Card Reader

## Tutorial
1. Connect the TFT LCD touch screen 2.4" Shield to Arduino Uno and connect Arduino Uno to computer using the USB connecter.
2. Open Arduino IDE, make a new sketchbook and paste the code above. 
3. Go to Tools > Manage Libraries and search for Adafruit BusIO, and then click install.
4. Repeat the step and install two other libraries, Adafruit GFX and Adafruit TFTLCD.
5. Customize the code anything you like by using the functions in the **loop()** function.
6. Click Verify and Upload.

## Picture print using SD Card tutorial
1. Connect SD Card with the SD Card reader.
2. Upload the picture you want to print by copy the picture to SD Card with **.bmp** format (Max Resolution: 240 x 360 pixel).
3. Don't forget the picture file name in the SD Card.
4. Use the function **bmpDraw("Image file name", x position, y position)** to print the picture in the LCD
> Example we want to print a picture with file name person.bmp in the x position 10 pixel from the left and 
> y position 50 pixel from the top, the code should be **bmpDraw("person.bmp", 10, 50);**
5. Put it in the code and upload.
