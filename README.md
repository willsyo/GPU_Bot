Fixed some things from Nvidia3080_BB_bot by alexxsalazar, also adapted to buy other GPU's from Best Buy in addition to 3080 and a few others. It now supports all listed GPU's. Should also work with PS5.
Also, made installation and usage a little more accesible.

## Requirements
**You need 2 things for this bot to work**
1. A virtual credit card. You can get one from privacy.com.
2. Web cookie after valid sensor data has been sent by the browser

### What cookie?

[Here is a picture of what the cookie values will look like](https://imgs.developpaper.com/imgs/2561717502-cccff2c795e46080_articlex.png).
1. Go to Best Buy website to establish valid session and browse around for a few seconds.
2. Right click on webpage, click "Inspect".
3. Click "Console" at the top of the menu that pops up.
4. Type **document.cookie** and copy the entire output.
5. Paste the output in data/sensor_data_cookie.txt
6. Ctrl+F for the character sequence **_abck** and make sure that the value contains **~0~**. If it contains **~1~** change the 1 to a 0.

### Why do I need a virtual credit card?

A virtual credit card allows you to bypass Best Buy 3dsecure check, but you can also use your own card if you wish. Do at your own risk as it may be flagged or banned by Best Buy.

### Installation and usage

1. Follow all the steps in this tutorial to install python 3.8: https://python.tutorials24x7.com/blog/how-to-install-python-3-8-on-windows
2. You will probably need to restart computer.
3. Run 'installer.exe'
4. Run 'GPU_Bot.exe' to open application

I'll skip GUI instructions, but if you need them, look up BirdBot on Github. 
It should be pretty self explanatory.

Don't be a scalper. Only use this app for 1 card.

### Credits
**Credit to alexxsalazar for adapting bot from BirdBot repo created by Nate Wong and contributors. Both are MIT license projects.**
