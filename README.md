![](Logo.png)

# MobileMouse

The project is still in its development phase so be sure to stay tuned for more future improvements.

## 1. Getting Started

These instructions will get you a copy of the project up and running on your local machine and mobile device for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### 2. Prerequisites

For now the project requires the server side computer and the mobile device to be connected to the same local address, for better and smoother connection you should let the #portnumber (default 5000) throught the firewall.

## 3. Project structure
* [MobileMouseClient] folder consists of the Android Studio project (Java) which implements the client side of the project and the mouse movement logic. 
* [MobileMouseServer] folder consists of all the Python files used for the implementation of the server. It also has a MobileHotspot.py file which is only working on Linux.
* [MobileMouse.apk] ready android .apk application for mobile phone installation.
* [MobileMouseServer.exe] ready script to run the local machine server.

### 4. Installing

For usage of the app and the server, you just need to run MobileMouseServer.exe on your computer, if you want the script to automatically open firewall ports you should run it as administrator. Furthermore you should install the MobileMouse.apk that is also located in the project structure tree.


## 5. MobileMouse.apk usage

The home page lets you input your IP addres which is given by the server .py script, so you have to run that first. You can also input your sensitivity choice below that. The application has two main ways to controll the mouse movement, one is a simple touchpad with buttons and a scroller, the other is a AirMouse which lets you control the mouse movement with the tilt of your phone. The last app page is only to show some simple statistics. Further instructions can be found in ![INSTRUCTIONS.md](https://github.com/kolan51/MobileMouse/INSTRUCTIONS.md) file.

## 5. Built With

* [Python]
* [Java]
* [Gradle]

## Versioning

Now only the initial 1.0.0 version is available, we will inform you of any further commits and changes.

## Authors

* **Jasa Frelih Crv** - *Initial idea and further work, project leader* 

* **Tilen Mocnik** - *server part* 

* **Jan Debenjak** - *touchpad part* 

* **Erika Maglica** - *all around coding and graphical design* 

