---
layout: post
title:  "Setting up Rasperry Pi Device"
categories: [ Data Engineering ]
image: assets/images/setting_up_rasperry_pi/rasperry_pi_image.jpg
---
Recently I bought a Raspberry Pi to try Data Engineering work for IoT. For now, assume IoT as a sensor device that can measure the paraments. For example, place an IoT device inside/outside of the home to measure the temperature and transmit that data.

I ordered the Raspberry Pi through [The Pi Hut][https://thepihut.com/products/raspberry-pi-5], 8 GB. 

The power cable and the micro SD card are required in addition.  The micro USB to HDMI cable is required to connect the Pi to the monitor. Mouse and Keyboards are required, either wired or wireless. The device has got 4 USB slots.  These are the hardware required. 

Coming to the software, the device doesn't come with a pre-installed OS, like the Windows OS in the laptop. 

The micro SD card is the hard disk of the Pi device. Raperry Pi OS is the operating system for the device and this should be installed in the SD card before inserting it in to the device slot.

## Installing the Rasperry Pi OS in the SD card. 

<li>Insert the memory card in the laptop (Windows/MAC/Linux)</li>
<li>Install the Raspberry Pi Imager from the link: [https://www.raspberrypi.com/software/][https://www.raspberrypi.com/software/] </li>
<li>Once installed, run the Imager, the below image will pop up. </li>

![walking]({{ site.baseurl }}/assets/images/setting_up_rasperry_pi/0.png)

<li>Chose the device, OS and the storage  </li>

![walking]({{ site.baseurl }}/assets/images/setting_up_rasperry_pi/1.png)

<li> An option to customise will pop up in the next window. Click EDIT SETTINGS </li>

![walking]({{ site.baseurl }}/assets/images/setting_up_rasperry_pi/2.png)

![walking]({{ site.baseurl }}/assets/images/setting_up_rasperry_pi/3.png)

<li> Setup the username and password and configure the WIFI, so that you don't need to configure this later in the device </li>

<li> Save and press yes next </li>

<li> This will start writing the OS in the memory card  </li>

![walking]({{ site.baseurl }}/assets/images/setting_up_rasperry_pi/4.png)

Once installed, it is ready to go. 

Connect the power cable and monitor, insert the memory card and monitor. After a few minutes, the home screen will appear.

![walking]({{ site.baseurl }}/assets/images/setting_up_rasperry_pi/5.png)
<!-- 
Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk]. -->

[The Pi Hut]: https://thepihut.com/products/raspberry-pi-5
[https://www.raspberrypi.com/software/]: https://www.raspberrypi.com/software/


<!-- 
[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/ -->