# Portal-button-
## How to build it 
#### steps to 3d print 
the building part is pretty easy. First print the pieces, I kept all the setting the same as the base setting is Bambu lab except I enabled the supports. I included to different types of files for the printed piece, one colored version if you have ams and one un-colored one that you can just paint for you you don't have ams. If you are using ams it will require black, gray, white, and red filament, but I highly suggest to print the top of the button separate from the base. 
#### steps to put it together 
1. solder 6-ish inch lengths of wire to the bottom of the button where the little metal pieces come out (the wire is only so long to make it easy to solder) 
2. put the button through the hole in the top of the base, then pull the wires out of the side
3. connect or solder one wire to pin 5 and one wire to pin 3 of your Raspberry pi pico, it doesn't matter which is which. (see picture bellow)
4. stick the pico into the box and push it so the micro USB of the pico is sticking out the little hole on the side of the box, gule it if you want.
5. close the box up and upload the code to your computer.
<img width="425" height="405" alt="71a5ZhvpvpL _AC_SX425_" src="https://github.com/user-attachments/assets/6a488c9e-5506-475d-8209-d043c2c89e18" />

## How to set this up on your computer 
The portal button not only requires you to put the code into the raspberry pi pico, but you also have to set it up right on your desktop. First of all, you will need steam, you can set it up to any steam game, but its a button from portal, so it would be weird if you set it to open a game other than portal or portal 2. first log into steam and go to the game that you would like to set it up to open and press the "Manage" button and then press "add to desktop" from the list of options, this will make a desktop shortcut for the game that you want to open. Next, right clip the new shortcut on your desktop and press "Properties". Next go to the short cut tab and click on the Shortcut key field. Then set the short cut to Control+Shift+P+L, and lastly press apply and ok. Basically, what this did was make it so when you press the buttons, control, shift, P, and L, the game will launch, and the code in the physical button is coded to press that series of buttons when it is pressed. 
