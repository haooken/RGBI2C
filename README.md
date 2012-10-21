Title: RGBI2C Module v2

Author: Dan Ternes (haooken)

Description: This circuit relies on an ATTiny flashed with the CYZ_RGB firmware (http://code.google.com/p/codalyze/wiki/CyzRgb). When the appropriate commands are sent via I2C, this module can be used to control one or several RGB LEDs.

Control of the channels is achieved by varying the PWM signals to the three N-channel power MOSFETs (STP16NF06: http://www.digikey.com/product-detail/en/STP16NF06L/497-2765-5-ND/603790). They are rated to support up to 60V at 16A.