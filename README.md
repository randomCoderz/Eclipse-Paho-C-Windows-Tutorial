# Eclipse-Paho-Cpp-Windows-Tutorial
Tutorial on Eclipse Paho C++ wrapper
Tested on Visual Studios 2017

## Purpose
This tutorial may come in handy to anyone who needs to install the Eclipse Paho C++ wrapper on Windows. The official ReadMe for the C++ wrapper was slightly vague for Windows so I thought my experience in setting it up might help somebody. This may also help those who need help setting up Paho C as well, since the C++ wrapper is dependent on the Paho C library. 

## Software
1. Visual Studios 2017
2. [CMAKE](https://cmake.org/)
3. [Paho C](https://github.com/eclipse/paho.mqtt.c)
4. [Paho C++](https://github.com/eclipse/paho.mqtt.cpp)

## Paho C
1. Download Paho C
2. Unzip the files in a location of your choice (Documents, Downloads, ect.)
3. Inside Paho.mqtt.c-master you will see another Paho.mqtt.c-master
  * Remove the internal Paho.mqtt.c-master from the folder and place it somewhere else temporarily
  * You can discard the empty Paho.mqtt.c-master and place back your folder to initial location
4. Open CMAKE
5. Under "Where is the source code located": browse source to your Paho.mqtt.c-master folder
  * Ex: /Desktop/test/paho.mqtt.c-master/
6. Under "Where to build the binaries" add a "/build
  * Ex: /Desktop/test/paho.mqtt.c-master/build
7. Hit Configure
  * After, under the "Red highlighted text" click on samples
8. Hit Generate
