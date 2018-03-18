# 

## How to debug android app over wifi 

#### Remember: Your devices have to connected on the same wifi 

* Step 1: On Android Studio, choose File -> Setting -> Plugins -> Browse Responsitories..

  Search `Wifi adb ultimate` and Install it, after that Restart the IDE

Notice: Now you have to enable USB Debugging  on your phone (Settings -> Additional Settings - Developer Settings or Setting -> Developer Settings).

* Step 2: Connect your phone to PC over USB cable and press `Refresh` image button on Wifi Adb Ultimate tab (On the right of the IDE), then press `Connect` image button which right of the target device, after that you can unplug the USB cable and Run 'app' over wifi. 

  From now on, you would no longer need an USB cable. You can quickly copy the IP address of your device and parse it to this plugin (Ex: 192.168.1.108, you can find it on your Wifi details), then press `Connect` image button, and now you can Run or Debug over wifi.

% Step 3: Enjoy it! :)
