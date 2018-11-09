# Super Lan Play Android Client

This small tutorial is based on an already rooted Android device. 

In my case I used the Kingroot tool. You can use whatever you want. Remember kingroot contains spam. So you will see ads in your tablet.

You have to download the app Termux from google play.

https://play.google.com/store/apps/details?id=com.termux

This app provides a Terminal with linux support to install packages. I developed by myself an installer script which will do all the tasks for you automatically. This installer just need to be run 'ONCE'.

To do this, run Termux as shown in the video below just touching the Termux icon in your android device.

When the app starts write next commands:

```
wget goo.gl/gEZ2ky
```

```
chmod 755 gEZ2ky 
```

```
./gEZ2ky
```

And that's all. When the procedure finishes you're ready to go.

Keep the Termux app running as any other app and run your Chrome app.

Go to Super Lan Play url, which is at: http://lanboard.retrogamer.tech

Do the steps as usual to authenticate and authorize. When you see, you have to run your client, then back to Termux app again and run one of the next command depending on the platform you want to play.

So for Nintendo Switch run:
```
./switch
```

And for PS4 run:
```
./ps4
```

When you do that you will receive a screen with all of your network interfaces supported in your android device. Even you won't see anything when you touch the keyboard on the screen, try to touch the number corresponding to your connection, which usually is the wlan0 device. In my case, it was the first. So I type number 1 and I touch ENTER key. That should be enough. The client will run and you're ready to back again to the Chrome and refresh the page. In that moment you should be connected and ready to play with your Switch or with your PS4 depending on your choice.

The app will be running and even you kill termux it won't die. So you will have to reboot to kill it.

Now you can run Termux again, and just type the ./switch or ./ps4 command. You don't need to do any extra step. Just run one of those commands, and then select the number of your network interface.

VIDEO

https://youtu.be/rCxpaKPVcHc

# CREDITS

The lan-play app is developed by imspace and its own github is located at:
https://github.com/spacemeowx2/switch-lan-play

