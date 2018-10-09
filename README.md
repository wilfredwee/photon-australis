# 🐺 Photon Australis
Bringing sexy curves back to Firefox Photon.

![alt text](assets/images/screen-1.png "Photon Australis Dark Main Window")
<br />
<br />
<br />
![alt text](assets/images/screen-2.png "Photon Australis Dark Top Bar")
<br />
<br />
<br />
![alt text](assets/images/default-theme.png "Photon Australis Default Theme")

## Why?
Because all you sexy Firefox users deserve something sexier than ugly, blocky square. (Who wants to be square, right?)

## 😍 How do I get this sexy thing? 😍
Since Firefox 57+, the only way to customize your browser UI is through `userChrome.css`. Learn more [here](http://kb.mozillazine.org/index.php?title=UserChrome.css&printable=yes).

Rough instructions:
1. Go to your Firefox browser, type `about:profiles` in your url bar.
1. Under the profile that is in use (The message is something like `This is the profile in use and it cannot be deleted.`), click `Open Folder` on the `Root Directory` row.
1. If that folder does not have a `chrome` folder, create a folder, name it `chrome`.
1. In the `chrome` folder, create a file named `userChrome.css`
1. Determine what Firefox theme you are using:
    1. Click the icon with 3 lines on the top right corner to open the context Menu.
    1. Select `Customize`.
    1. At the bottom left of your screen, select `Themes`.
    1. Choose or determine which theme you want to use, they can either be `Dark`, `Default`, or `Light`.
1. Copy and paste the code that matches your Firefox theme. [Dark](./userChrome-dark.css), [Default](./userChrome-default.css), [Light](./userChrome-light.css)
<br/>**WARNING:** Newer versions of Firefox with Mojave or Windows 10 Dark Mode will cause Firefox to use the `Dark` theme by default. In this case, you should use the [userChrome-dark.css](./userChrome-dark.css) theme.
1. Restart Firefox and enjoy some sexy curves :D

## 😞 Something is broken 😞
Fret not! Please create an [issue](https://github.com/wilfredwee/photon-australis/issues/new) and I'll see what I can do.