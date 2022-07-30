---

layout: post
author: manohar
title:  Wireless Debugging Android-Studio
description: Connect android device to android studio with out any cables
categories: [ Android, Android-Studio, Debugging ]
image: https://i.imgur.com/qfo6g8I.jpg
featured: true
hidden: false

---

##### **Wirelessly connect Android device to Android studio (No cable required)**



Open Android studio and click on the devices list beside run button .

![](https://i.imgur.com/S0VjAi4.jpg)

In the drop down select Pair Devices using Wi-Fi option

It will open following dialog

![](https://i.imgur.com/GTZFjp9.jpg)


On Android phone open [Developer options](https://developer.android.com/studio/debug/dev-options "developer options") , and enable wireless debugging 

![](https://i.imgur.com/7l19V6U.jpg)


A dialog will popup asking wether to enable the wireless debugging on current network, Check on the Always allow on this network and click allow

![](https://i.imgur.com/6vm3ChV.jpg)

Next Open the wireless debugging option and click on Pair device with QR code

![](https://i.imgur.com/x28XIpy.jpg)

A Qr code Scanner will popup , use this scanner to scan the QR code displayed in android studio.

![](https://i.imgur.com/0Mi6Dwu.jpg)

Once scan is succeded the device will get connected to the android studio.

![](https://i.imgur.com/XOBsOPH.jpg)

you can close the dialog in android studio .

**Notes:-** Android version 11+ required, If QR is not working then you can use pair with pairing code option.


