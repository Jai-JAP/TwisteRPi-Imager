# TwisteRPi-Imager
RPi-Imager with Twister OS inside alongside all other OSes. 

All credits go to the [RPi-Imager team](https://github.com/raspberry/rpi-imager) for making the imager.  

This page hosts the patch files & json files required to add Twister OS in TwisteRPi-Imager alongside other OSes present in RPi-Imager.
    
## This patch does not modify the default configuration of RPi-Imager.

## To install this version of RPi-Imager (TwisteRPi-Imager) follow the below steps.   
```
sudo wget https://raw.githubusercontent.com/Jai-JAP/TwisteRPi-Imager/main/TwisteRPi-Imager.desktop -O /usr/share/applications/TwisteRPi-Imager.desktop
sudo wget https://raw.githubusercontent.com/Jai-JAP/TwisteRPi-Imager/main/twisterpi-imager.svg -O /usr/share/icons/twisterpi-imager.svg
sudo wget https://raw.githubusercontent.com/Jai-JAP/TwisteRPi-Imager/main/twisterpi-imager -O /usr/local/bin/twisterpi-imager
sudo chmod +x /usr/local/bin/twisterpi-imager
```

To use **TwisteRPi-Imager**  run `twisterpi-imager` in terminal or use the menu entry **TwisteRPi-Imager**. 

To use **RPi-Imager**  with its original configuration run `rpi-imager` in terminal or usr the menu entry **Imager**.

## Screenshots
![TwisteRPi-Imager](https://user-images.githubusercontent.com/78354625/114858460-1c330f00-9e07-11eb-9fd6-84f92d13cdda.png)
![Operating System](https://user-images.githubusercontent.com/78354625/114858514-2ce38500-9e07-11eb-9d2a-49214f34454b.png)
![Other General Purpose OS](https://user-images.githubusercontent.com/78354625/114858529-31a83900-9e07-11eb-80d1-046932510aea.png)
![Twister OS](https://user-images.githubusercontent.com/78354625/114858540-35d45680-9e07-11eb-9d7e-ab8f0ab56d9a.png)

