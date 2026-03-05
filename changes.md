This commit is barebones vanilla, only added keymap layout.
`a840b1eeff0d019ad8f8ddb63adfbbdf7e829b63`;

CURRENT KNOWN ISSUE(s):
        ~~- OLED wont power sometimes. If plugged into the right side(no OLED) the OLED will then work.
        (This might be a hardware issue on my end? OLED will power up if USB is plugged in "just right")
        - There could be more issues, but so far just the OLED is an issue~~
        04 MAR 2026
        - Custom firmware isn't displaying anything on the OLED, OLED CONFIRMED WORKING WITH OTHER FIRMWARE. Something in the code is bugged? Maybe it's since I'm using a SSD1306?


 
01 MAR 2026

    I think everything works now? OLED is still wonky.

~~I have to fix my own board first to test the firmware any further. As far as I can see the LEDs work, the OLED just sometimes wont come on? (I have  to test further if it's a hardware issue on my end)
    One of the custom widgets is working, the nyan cat one.~~ 
    I want to test the other widgets. (Or just opt to only use the ZMK widgets.)

Most of this code was just copied in the structure of PandaKB's firmware. I have 0 experience with this, I read some of the zmk docs, and watched a few youtube videos going in. Then desperately asked ChatGPT for help whenever there were errors in the actions page.  This is my 3rd attempt at this ~~, for now, until I fix my hardware I cannot test the firmware any further.~~


~~If anyone wants to give it a look in the mean time
(I'm bad at managing projects once I set them down, especially ones I have to teach myself a new skill for, I probably wont get back to this for a little. Until I gain a "better" grasp on ZMK.) 
you are more than free to edit and use this firmware how you wish. In my endeavors to build this I never saw any ZMK firmware  that integrated RGB so I just did it myself.~~


I'm sure tweety has one but I wanted to undertake this challenge since I never "programmed" anything before.
(given 'most' of the important parts of the firmware was already written all I did was copy and paste codes from other repos and try to find the appropriate places to put them. You will see from all my commits that I didnt want to risk changing too much at once.)

 I hope this can serve someone well, this took me a month to "understand" to even get the RGB programmed. 
 (and I use this VERY loosely since I still dont really understand what I did or why it worked. and I fear any one minor change can ruin the rest of the code.) 
