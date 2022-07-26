# TwisteRPi-Imager
RPi-Imager with Twister OS inside alongside all other OSes. 

### ***NOTE: DEPRECATED***

All credits go to the [RPi-Imager team](https://github.com/raspberry/rpi-imager) for making the imager.  

This page hosts the patch files & json files required to add Twister OS in TwisteRPi-Imager alongside other OSes present in RPi-Imager.

   - This patch persists over RPi-Imager updates and works well over the updates as it does not modify your default RPi-Imager.
   - In case you need the original RPi-Imager (RPi-Imager with original configuration) it is readily available.
   - It does work well with added TwisterOS until it is added to official RPi-Imager.

The TwisteRPi-Imager works by utilising the [Custom Repo](https://github.com/raspberrypi/rpi-imager#custom-repository) feature of RPi-Imager and some json files available on this page.

TwisteRPi-Imager is completely unofficial & unsupported by RPi-Imager team.
In case you have any issues running this patch create a new issue [here](https://github.com/Jai-JAP/TwisteRpi-Imager/issues).
    
### This patch does not modify the default configuration of RPi-Imager.

## To install TwisteRPi-Imager follow the below steps.  
   ***[Note] Only the latest version of RPi-Imager is supported. The .json files maybe incompatible with older versions. If your system has an older version installed consider updating it to the latest.***

Install Manually  
 - *Prerequisites* : `rpi-imager`
```
sudo wget -qO- https://raw.githubusercontent.com/Jai-JAP/TwisteRPi-Imager/main/install_rpi-imager.sh | bash
sudo wget https://raw.githubusercontent.com/Jai-JAP/TwisteRPi-Imager/main/TwisteRPi-Imager.desktop -O /usr/share/applications/TwisteRPi-Imager.desktop
sudo wget https://raw.githubusercontent.com/Jai-JAP/TwisteRPi-Imager/main/twisterpi-imager.svg -O /usr/share/icons/twisterpi-imager.svg
sudo wget https://raw.githubusercontent.com/Jai-JAP/TwisteRPi-Imager/main/twisterpi-imager -O /usr/local/bin/twisterpi-imager
sudo chmod +x /usr/local/bin/twisterpi-imager /usr/share/applications/TwisteRPi-Imager.desktop
```
or

Directly [download](https://github.com/Jai-JAP/TwisteRPi-Imager/raw/master/TwisteRPi-Imager_1.0.0_all.deb) and install [.deb file](https://github.com/Jai-JAP/TwisteRPi-Imager/blob/master/TwisteRPi-Imager_1.0.0_all.deb)
```
wget https://github.com/Jai-JAP/TwisteRPi-Imager/raw/master/TwisteRPi-Imager_1.0.0_all.deb -O TwisteRPi-Imager.deb
sudo apt install ./TwisteRPi-Imager.deb
sudo rm ./TwisteRPi-Imager.deb
```

## To uninstall TwisteRPi-Imager follow the below steps.

If installed manually
```
sudo rm /usr/share/applications/TwisteRPi-Imager.desktop
sudo rm /usr/local/bin/twisterpi-imager
sudo rm /usr/share/icons/twisterpi-imager.svg
```

or

If installed using .deb file
```
sudo apt purge twisterpi-imager
```
    
If you want to uninstall rpi-imager
```
sudo apt purge rpi-imager
```
## Usage

To use **TwisteRPi-Imager**  run `twisterpi-imager` in terminal or use the menu entry **TwisteRPi-Imager**. 

To use **RPi-Imager**  with its original configuration run `rpi-imager` in terminal or usr the menu entry **Imager**.

## Screenshots
![TwisteRPi-Imager](https://user-images.githubusercontent.com/78354625/114858460-1c330f00-9e07-11eb-9fd6-84f92d13cdda.png)
![Operating System](https://user-images.githubusercontent.com/78354625/114858514-2ce38500-9e07-11eb-9d2a-49214f34454b.png)
![Other General Purpose OS](https://user-images.githubusercontent.com/78354625/114858529-31a83900-9e07-11eb-80d1-046932510aea.png)
![Twister OS](https://user-images.githubusercontent.com/78354625/114858540-35d45680-9e07-11eb-9d7e-ab8f0ab56d9a.png)


