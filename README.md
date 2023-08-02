# FlipperZeroEuropeanPortals
A repository of portals I made for the **Evil Portal** app on the **Flipper Zero**. _For educational purposes only!_

It consists of: 
- A few well-known **internet providers'** "Hotspots" to emulate. 

- **McDonald's** because they are everywhere

- Some **transportation companies**

- Other **big companies or hotels known to offer free hotspots**

I will be working on more and am *open for suggestions!* -> r/u/FlippieHacks


## **!! THERE ARE TWO VERSIONS FOR EACH PORTAL !!**
- One has a **fake** "*Forgot credentials*" button that will invite people to go to their provider's app if they forgot their creds. Makes it seem a bit more legit.
- The other doesn't have this option, simply
  
![Ibis Hotels WiFi](https://zupimages.net/up/23/31/mu13.png)


## How to Use
If you do not know how to use this great app which is **Evil Portal**, watch Talking Sasquach's tutorial [here](https://youtu.be/zfd7wADSkD4).  
In a nutshell, after installing Evil Portal on your Flipper (can be done easily through [flipc](https://flipc.org) or even on the official App Store):

1. **Open QFlipper**
2. **Browse to SD Card > apps_data > evil_portal**
3. **Upload the two files you find for each portal** (index.html and ap.config.txt). _YOU ONLY UPLOAD THE FILES FROM THE ONE PORTAL YOU WANT TO USE AT THAT POINT IN TIME!_ Unfortunately, you have to do this every time you want to switch the portal you use.
4. **Start Portal in the Evil Portal app** using a WiFi dev board (official or not, doesn't matter)
5. The portal you will see by connecting to your access point will be the one for the provider you uploaded the files from!

### Customization
- If you want to change the Access Point's name, you can do it simply by editing the `ap.config.txt` file. The text in there will be the AP name.
- You can also tweak the indexes a bit if you know some HTML. There is some Javascript on the "ForgotCredentials" files but nothing even a noob can't handle.

**Happy flippin'**

Some of the portals:

![Ryanair Portal](https://zupimages.net/up/23/31/2vxa.png)
![British Airways WiFi](https://zupimages.net/up/23/31/8jkp.png)
![Vodafone WiFi](https://zupimages.net/up/23/31/cgp5.png)
![Orange WiFi](https://zupimages.net/up/23/31/9jfm.png)
![Tesco WiFi](https://zupimages.net/up/23/31/8rde.png)
![Thalys Portal](https://zupimages.net/up/23/31/9mvw.png)
![McDonald's Portal](https://zupimages.net/up/23/31/ccjy.png)
![BT Portal](https://zupimages.net/up/23/31/fitm.png)
![Proximus WiFi](https://zupimages.net/up/23/31/w718.png)
