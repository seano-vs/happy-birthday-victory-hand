![happy birthday ya fool](images/hbd.gif)

# HAPPY BIRTHDAY ✌️!!!!

Kayla and I (mostly Kayla) have prepared for you a kit to build a cool piece of artwork. Now you can solder and hammer your way to your own unique form of artistic expression! Let's make some art so cool that one older art teacher you had would have his brain wrinkled at the thought!

So the general idea for this is:

- LEDs go in the box
- LEDs connect to the arduino
- String art goes on top of it

We've got some sample code here that will get you off your feet, and some pics with vague suggestions on where to place the LEDs. 

## The LEDs!

You'll need to solder the strips and connect them to your Arduino. That's right, we didn't do _shit_ for you. You can earn your own damned birthday present. This picture shows you what you already probably know, but just look at how good that soldering job is, eh? Try and be at least a tenth as good as that 😏.

![damn we can solder eh](images/1.jpg)

Next, use the adhesive to attach them however the hell you want in the box but make sure the wires are coming out the back through the hole YOUR DEAR, DEAR, SELFLESS FRIENDS SO GRACIOUSLY CUT FOR YOU. But we suggest attaching first, and programming later. That way ya get to see how it'd look in real time 😊

![cable in da hole](images/2.jpg)

Maybe tape them in a circle around the box? Or whatever. Who cares, this is a github repo, not a cop.

![helicopter helicopter](images/3.jpg)

## The ARDIUNIO!

Microcontroller: Arduino Nano (I fucked up and accidentally got a 3.3V one but it seems to still work with my test kit so I think it'll be okkkkkkayyyy lol) 

Link to Tutorial/Overview: 

https://docs.arduino.cc/hardware/nano

Install the Arduino IDE: 

https://www.arduino.cc/en/software#future-version-of-the-arduino-ide 

If you have a Windows OS (of course you do Microsoft) then you will have to download the driver from here

https://www.wch.cn/download/CH341SER_EXE.html

It looks super sketch but this is the instructable that lead me to it and it worked for me. 

https://www.instructables.com/Arduino-Nano-USB-Not-Recognizing-Fix/

You can also program it at our place if you don't wanna put this sketch driver on your comp lol. 

Install FastLED Library: 

    Open Arduino software and then go to "Tools" --> "Manage Libraries"
    Type in the search bar "fastled"  and then click "Install"

![so faast](images/fastled.png)

Once you have the Arduino IDE installed and the driver to access the nano installed, you can program it. To do this you'll want to do the following: 

- Plug in the Arduino 
- Open the IDE and click on "Tools" --> "Board" --> select Arduino Nano from the drop down
- Select the Port that the microcontroller is hooked up to "Tools" --> "Port" --> "COM9" 
- - (yours will be a diff number but whatever port appears/disappears as you plug and unplug the arduino is the one to choose) 
- Open one of the examples that downloaded with the library by going to "File" --> "Examples" -->  "FastLED" --> Choose one :D...
- - Cyclon is a good starter one
- In the code you'll want to make sure you select/set the right pin number.
- - i.e. the one that you hook the data pin of the LEDs up to. 
- - You have to choose a PWM pin --> pulse width modulated signal pin which can send the square wave needed to run the LED strip. 
- - Pin 2 is one of these pins but you can also check the documentation in the link above to see which other pins work. 
- The second thing you need to set in the code is the number of LEDs I had 134 in ours so you can try this to start and modify (or you could count haha). 

![lol screenshot of text](images/fastledcode.png)


Then you'll be set to download the code!  

The two buttons are the check mark button (compiles the code) and the right arrow button (compiles then downloads the code). You can just use the right arrow button cause it'll compile then download...but if you use the check mark button it will not download the code; it'll just check if it can compile it. 
- The ColorPalette example is also super dope :D 
- You might also check out the FastLED Library documentation on GitHub: 
- - https://github.com/FastLED/FastLED/wiki/Basic-usage

## Solder the Arduino!



## The NAILS

Kayla literally told me just now "make sure you put in there that when she hammers the nails she has to make sure the nails don't move." So, when you nail them make sure they don't move. Got it? Great.

Here is a picture of one of the many ways Kayla experimented with this. Idk if she suggests this method but whatever

![nail the outside not the inside whoah who just said that](images/4.jpg)

Once it's nailed properly, tie it up!

## String it UP

There's a LOT of inspiration you can take for string art. Like, take a look at some of these fuckers:

https://youtu.be/28c3dlF54yE

https://youtu.be/5gbwxqFnWek

https://youtu.be/sfXcEXDesHM

Or, you could just take the search term "string nail art circle" and search yourself. It's not rocket science. BUT, if you fuck this up and it looks bad we'll forever judge your for your ineptitude. 

## Put it somewhere

Now that's done, put it somewhere! If you're proud of it, put it somewhere others can see it! If you aren't pretend like you are forever working on your unfinished masterpiece and hide it somewhere in shame. Follow your own artistic process!

We hope you had as much fun making this as Kayla did. And, of course, as I did helping Kayla. Here's a picture of us having fun together but our faces are censored since this is a public git repo 🥰

![beautiful fucking humans god damn](images/luvurfriends.jpg)
