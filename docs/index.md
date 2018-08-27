# RICOH THETA V Wireless Live Streaming Guide

There are two parts to this guide:

1. Configuring THETA V prior to streaming event
2. Using THETA V to broadcast a streaming event

## Quickstart Summary

### Configuration Summary

1. Locate Wireless Live Streaming Plug-in in the THETA Store
1. Connect THETA V to computer with USB cable
1. Install Plug-in into THETA V using THETA Desktop Application
1. Set Wireless Live Streaming plug-in to launch
1. Reboot camera
1. Configure THETA V to connect to Internet using a Wi-Fi router or mobile phone hotspot
1. Configure YouTube Live 360° Event with web browser
1. Put THETA V into Plug-in mode
1. Save YouTube Live Events server URL and stream key into THETA V

## Usage Summary

1. Connect THETA V to Wi-Fi router or mobile phone hotspot
1. Start broadcast
1. Optional: verify broadcast is working properly

## Step-by-Step Configuration Guide

### Locate Plug-in in THETA Store

Go to [https://pluginstore.theta360.com/](https://pluginstore.theta360.com/)

![store](img/store.png)

Find the Wireless Live Streaming plug-in.

### Connect your THETA V to your computer

Connect the camera to your computer with a USB cable.

![connect](img/connect.png)

You must have the Ricoh Desktop Application installed on your 
computer.  If you do not have the desktop application installed,
download it from 
[https://theta360.com/en/support/download/](https://theta360.com/en/support/download/)

![desktop app](img/desktop-app.png)

### Install

Click on the Install button.

![install](img/install.png)

### Set Wireless Live Streaming Plug-in to Launch

With your camera and the computer still connected with a USB cable, 
set the active Plug-in with the Desktop App. Under the file menu, select 
*Plug-in management...*.

![plug-in manager](img/plug-in-manager.png)

Check the radio button for 
*Wireless Live Streaming*.

![select plug-in](img/select-plug-in.png)

### Reboot camera

To be safe, reboot the camera. A reboot may not be needed in some cases, but
if you have time, hold the power key down for 8 seconds. Once the camera
has turned off, press the power button again. 

Be careful not to do a short press of the power button, 
which places the camera into sleep mode and will not reboot the camera.


### Configure THETA V to Connect to Internet

The objective of this step is to configure your
THETA V to connect to the Internet using Client Mode Wi-Fi.
In Client Mode, the Wi-Fi LED on the front of the camera is solid
green.

If you have already configured your camera with Client Mode, you can 
skip this step.

Continue on if you do not have a green LED as shown in the picture below.

![Client Mode](img/green-led.png)

There is a more detailed guide for Client Mode configure [here](https://community.theta360.guide/t/theta-v-client-mode-configuration-guide/2565?u=codetricity).

Most routers have a mode called, "WPS", which stands for Wi-Fi Protected Setup. This will 
enable you to connect your THETA V directly to your router with a few button presses. 

#### WPS Setup

Hold your THETA V and press the Wi-Fi, Mode, and Shutter buttons down.

![WPS Camera](img/camera-wps.png)

On your Wi-Fi router, press the WPS button, usually on the back of the router.

![WPS Router](img/wps-button.png)

The THETA V should now be configured for Client Mode. In the future, you can place the THETA V into 
Client Mode by pressing the Wi-Fi button on the side of the camera.

#### Find IP Address

You will need the IP address of your camera to save the YouTube settings to your camera.
The easiset way to get the IP address of your THETA V is to use the Ricoh mobile application.
For this step, you need to connect your mobile phone to the camera with Client Mode (green LED).

From the screen where you can see your camera images, go to the Settings gear in the upper right
corner. Go to Camera Settings -> Camera versions -> IP Address.

![mobile camera](img/mobile-camera.jpg)

![camera settings](img/camera-settings.jpg)

![mobile ip](img/mobile-ip.png)

If you can't connect your mobile app to your camera with client mode, there is a separate article shows
a number of other [ways to get the IP address of your camera](http://theta360.guide/blog/plugin/2018/08/01/find-theta-ip-address.html).

#### Manual Setup

If you do not have access to WPS on your router or you are connecting 
the camera to your mobile hotspot, please look at [this]((https://community.theta360.guide/t/theta-v-client-mode-configuration-guide/2565?u=codetricity)) configuration
guide for information on manual configuration.

### Configure YouTube Live Event

With any web browser, configure YouTube Live Event. You must be logged into the
YouTube account that you plan to use for live streaming.

Go to YouTube Creator Studio.

![Creator Studio](img/creator-studio.png)

In the left-hand pane, select LIVE STREAMING -> Events.

![Live Event](img/live-event.png)

With the pane for *Live Event* selected, click on the button for 
*New live event* that is located in the upper right of your window.

![New Live Event](img/new-live-event.png)

Click on the Advanced settings tab.

![Advanced Settings](img/advanced-settings.png)

Check the box for *This live stream is 360°*.

![360 stream](img/360-event.png)

Select *Reusable stream key*.

![stream key](img/stream-key.png)

Create a new stream.

![new stream](img/new-stream.png)

You will need the Stream Name and the Primary Server URL for the next step.

![server info](img/server-info.png)

### Put THETA V into Plug-in Mode

Press the lower mode button on the side for longer than two seconds.

The LED above the shutter button should be solid white.

The Wi-Fi LED should be solid green.

![plug-in mode](img/plugin-mode.png)

### Save YouTube Settings to Camera

You need to use a web browser to connect to the camera at:

http://your-camera-ip:8888

For example, my camera was assigned an IP address of 192.168.2.100.

I can access my camera's configuration at:

http://192.168.2.100:8888

![streaming server](img/streaming-server.png)

Copy and paste the YouTube server and stream key into the boxes on the camera 
configuration tool.

![plug-in config](img/plug-in-config.png)

Congratualtions! You've finished the configuration of the 
Wireless Live Streaming plug-in.

To start the stream, press the shutter button of the camera.

### Testing

#### Camera Configuration Tool

In the camera configuration tool, you will see a 
red dot with the words, *Streaming*, next to it.

![streaming button](img/streaming-button.png)

You will also see a button that says, *Stop streaming*.

![stream working](img/stream-working.png)

#### YouTube Control Room

Preview.

![YouTube Control Room](img/youtube-control-room.png)

With the event live.

![YouTube Site](img/youtube-site.png)

View from YouTube.

![View on YouTube](img/youtube-view.png)

View from other browsers on Internet.

![public view](img/public-view.png)

## Additional Information

* [Plug-in User Guide](http://theta360.guide/plugin-user-guide/)
* [Plug-in Developer Guide](http://theta360.guide/plugin/)
