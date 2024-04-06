# Hey there!

You were gifted a macro pad! 

> What the hell is a "macro pad"???

I'm glad you asked! A macro pad is a small keyboard that contains extra programmable keys. These pads are designed to work with your main keyboard, which you can then use to assign commands, keyboard shortcuts, and macros (hence the term macro pad).

A macro, on the other hand, is a recorded sequence of keyboard and mouse actions. This recording allows you to automate long, tedious tasks on your computer, thus saving you time and effort. So, after you assign a macro to a specific key on a macro pad, it will initiate once you press the set button.

While anyone can use a macro pad, who would actually need it? After all, the mouse and graphical user interface have allowed practically anyone to use computers and be adept at them. However, while graphical menus make it easy to use any app, it's still not as fast as keyboard shortcuts.

For example, it might take you three seconds to right-click on some text and select copy, but it will probably take you just one second to press CTRL + C. However, if you set a macro key just for copying, you no longer have to press two keys to copy anything. Instead, just tap the copy key, and you're good to go.

Another example is gaming: if you're playing an RPG or RTS game, some commands require you to click multiple on-screen buttons or press a combination of keys. But, say you assign a macro key for a complicated command that requires numerous clicks or keypresses; then you save time and gain the upper hand.

While you might think that saving half a second isn't worth the cost of buying and setting up a macro pad, if you're doing this action hundreds or even thousands of times in a day, you're saving a lot of time.

> Okay, but why did you give this to me?

This is why I love you, you question everything! 

I gifted this to you because I've been on a journey to learn PCB design, and CAD modeling. The bad boy you have in your hand is my "Hello, World" and represents my first win in this new and exciting realm - and, I wanted to share this win with you!


This particular 3x4 macro pad features: 

- BTLE with up to five profiles
- Two rotary encoders with push buttons
- A simple programmable web-interface
- Firmware through the _exceptionally_ powerful ZMK
- And endless customization possibilities!

## How do I use it?

### Charging
- Charge the macropad by plugging it in via USB-C and turn it on by pulling the tiny switch on the left towards you (away from the direction of the USB plug)

### Pairing
- Pair it via bluetooth by searching for "MacrowPAD"

### Programming

#### Initial setup - repo creation
This may seem tedious - but, I promise it's easy.
- Up at the top right of this repo, and click the green button that reads "Use this template"
- Select "Create new repository"
- Give your new repo a name

#### Initial setup - connecting it to a web base editor
- Go here: https://nickcoutsos.github.io/keymap-editor/
- Give the app access to your newly minted repo
- Go nuts editing/adding layers!

#### Programming you new layout
- Go to your layout repo
- Click on the "Actions" tab
- Go to your latest workflow run
- If it's finished - you'll see a file in assets named "firmware.zip"
- Plug in your MacrowPAD via USB
- Double click the little tiny button to the left of the USB-C port (alternatively, you can add a &bootloader button to your layour)
  This will put the pad into bootloader mode, which means what looks like a USB drive will show up on your computer.
- Unzip the firmware.zip file and drag the .uf2 file into the root of the macro pad's "USB drive"

The pad will then dismount, reboot, and boom. You are rocking your latest layout.


You can use it as is (with an admittedly basic keymap: https://github.com/vinniefranco/macrowbt-zmk-config/blob/main/config/macrowbt.keymap)
