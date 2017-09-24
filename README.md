This is the AISTARVISION MIPI Adapter,V2.0! It's updated from V1.0,with the goal of two CSI2 port support.Still,it's only for 96boards CE Edition.Our goal is to make Dragonboard support multiple CMOS image sensors,include SOC sensor and raw bayer sensor.

Sensor sample drivers available in Debian 16.09 for Dragonboard410C.

https://github.com/Kevin-WSCU/Debian-169.git

Android sensor driver coming soon

Support list(Default on Debian):

1)OV5645:2592*1944@15fps,1920*1080@30fps,1280*960@30fps

2)OV5640:2592*1944@15fps,1920*1080@30fps,1280*960@30fps

3)OV7251:640*480@100fps

4)MT9V024 with Toshiba MIPI Bridge:752*480@60fps

5)IMX185:1080p@60fps

6)AP0202+AR0230:1080p@30fps,WDR

7)OV13850 supported by Android

8)OV8865 supported by Android


MIPI Adapter further update:V2.1,ETA,by the end of August

1) Flexibility
2) Mechinical(mounting hole)
  
  


![img_1920](https://cloud.githubusercontent.com/assets/22780075/25014460/b3ec0d7c-202c-11e7-958e-fe873ddf64c9.JPG)

a)Build and Flash

For Linaro 16.09 release,refer to https://builds.96boards.org/releases/dragonboard410c/linaro/debian/16.09        Note that,the original Linaro 16.09 release removed camera nodes from device tree.To add camera support,use the updated apq8016-sbc.dtsi in this GitHub：Pre-built/Debian-16.09/ to replace the original one,then build.

If you use Linaro 16.06 release,then don't need do anything else,the default build would support our camera.Linaro 16.06 release:https://builds.96boards.org/releases/dragonboard410c/linaro/debian/16.06/

b)Get the hardware,please go to our Ebay store for more details(Camera adapter and all kinds of sensor boards available)
http://www.ebay.com/itm/96Boards-MIPI-Adapter-/252900099832?ssPageName=STRK:MESE:IT

1>Single camera support
One OV5645/OV5640 auto focus module
![img_1948](https://cloud.githubusercontent.com/assets/22780075/24592272/728c99a8-17c8-11e7-880a-757cf84d0f45.jpg)

2>Dual camera support

Two OV5645/OV5640 supported by AISTARVISION MIPI Adapter V2.0
![img_1966](https://cloud.githubusercontent.com/assets/22780075/24592212/ca0ae0e6-17c7-11e7-9c82-a632147f91d1.jpg)
![img_2600](https://user-images.githubusercontent.com/22780075/29755167-8176956a-8b48-11e7-97b3-897652bd19ed.JPG)

3>Camera boards

a)OV5645/OV5640 camera board
![img_2603](https://user-images.githubusercontent.com/22780075/29755205-53cf2e82-8b49-11e7-94a3-ab23203a82e1.JPG)

b)OV7251 camera board



