---

layout: post
author: manohar
title:  Change Log Cat colors in Android Studio
description: Make log cat look cooler
categories: [ Android, Android-Studio, Log ]
image: https://i.imgur.com/kYV3SiA.jpg
featured: true
hidden: false

---

---

layout: post
author: manohar
title:  Stop Using Post/PostDelayed in Your Android Views
description: Prevent avoidable crashes
categories: [ Android, Handler, Lifecycle ]
image: https://i.imgur.com/kYV3SiA.jpg
featured: true
hidden: false

---


You can make your Logcat look way more cooler and easier to read by changing the colors .

Steps to change Android Studio Logcat:



Go to

File → Settings → Editor → ColorScheme → Android Logcat

![Setting](https://i.imgur.com/j9Btln1.png)


Select the Log whose color you want to change

Suppose if  you want to change Info to green color

Select Info , uncheck Use inherited attributes

Select on foreground and change it to green

> Note : When you are picking color pull the right side slider to top to see colors


Similarly select remaining types of logs and change its colors

The Colors which I  use

<pre>
Assert :        #FF6B68    (Default)
Debug :       #91570A
Error:           #BB0000
Info:             #0D9724
Verbose:      #BBBBBB    (Default)
Warning :     #E8B74D      
</pre>

My Logcat

![My logcat](https://i.imgur.com/iNimEiL.png)


Just play with all the colors for Foreground,Background , Error stripe mark and Effects ( try all the type of effects in the dropdown) . Use the colors which best suites for your theme.
