# FlipperZeroEuropeanPortals
A repository of portals I made for the **Evil Portal** app on the **Flipper Zero**. _For educational purposes only!_

It now consists of a few well-known internet providers "Hotspots" to emulate. (well at least they are well known where I live)

I will be working on more and am open for suggestions!

## **!! THERE ARE TWO VERSIONS FOR EACH PORTAL !!**
- One has a fake "Forgot credentials" button that will invite people to go to their provider's app if they forgot their creds.
- The other doesn't have this option.

## How to Use
If you do not know how to use this great app which is **Evil Portal**, watch Talking Sasquach's tutorial [here](https://youtu.be/zfd7wADSkD4).  
In a nutshell, after installing Evil Portal on your Flipper (can be done easily through flipc.org):

1. **Open QFlipper**
2. **Browse to SD Card > apps_data > evil_portal**
3. **Upload the two files you find for each portal** (index.html and ap.config.txt). _YOU ONLY UPLOAD THE FILES FROM THE ONE PORTAL YOU WANT TO USE AT THAT POINT IN TIME!_ Unfortunately, you have to do this every time you want to switch the portal you use.
4. **Start Portal in the Evil Portal app** using a WiFi dev board (official or not, doesn't matter)
5. The portal you will see by connecting to your access point will be the one for the provider you uploaded the files from!

### Customization
- If you want to change the Access Point's name, you can do it simply by editing the `ap.config.txt` file.
- You can also tweak the indexes a bit if you know some HTML (there is some JS on the "ForgotCredentials" files).

**Happy flippin'**
