+++
title = "Ride of Pok3r"
author = ["nixorg"]
date = 2018-07-27T15:38:00+03:00
tags = ["keyboard", "pok3r", "poker"]
draft = false
+++

This guide for how to programm an ergonomic layout with Pok3r keyboard
[![](/images/ride_of_pok3r-keyboard-layout.png)](/images/ride_of_pok3r-keyboard-layout.png)

<!--more-->

Here we are going to remap the default pok3r keys to more suitable places and it will be much more ergonomic and handy in work I promise.

If you are interesting in details how to setup this keyboard please see
[user manual](http://www.vortexgear.tw/db/upload/webdata4/6vortex%5F20166523361966663.pdf) and [reddit wiki](https://www.reddit.com/r/MechanicalKeyboards/wiki/pok3r)

Some people prefer to have `hjkl` in opposite of my `ijkl` and I understand them as they are VIM users but I'm emacs user and use emacs on daily basis.
I was inspired by [Xah Lee](http://xahlee.info/) with a lot of efficient articles you can read it [here](http://ergoemacs.org/)


## Main features: {#main-features}

-   Move <kbd>Fn</kbd> to  <kbd>L\_Ctrl</kbd> place
-   <kbd>Capslock</kbd> as <kbd>Esc</kbd> as I often use escape key so capslock is the best place for it
-   <kbd>Fn</kbd> + <kbd>z</kbd>,<kbd>x</kbd>,<kbd>c</kbd>,<kbd>v</kbd> as regular copy, cut, past operations (it will provide us do copy and paste with only left hand)
-   <kbd>Fn</kbd> + <kbd>u</kbd> and <kbd>o</kbd> for word navigation


## Remap <kbd>Fn</kbd> key to <kbd>L\_Ctrl</kbd> {#remap}

-   Unplug keyboard from usb
-   Switch DIP switch 4 to ON
-   Plug keyboard then press <kbd>Fn</kbd> -> <kbd>L\_Ctrl</kbd> -> <kbd>Pn</kbd> -> <kbd>Pn</kbd> again (to leave it in its original location)
-   Switch DIP 4 back to OFF

[![](/images/ride_of_pok3r-palm_pressing_control_key_from_youngstabber.jpg)](/images/ride_of_pok3r-palm_pressing_control_key_from_youngstabber.jpg)
So from now you able to press <kbd>Fn</kbd> by your palm as on image below to avoid RSI and issues with your pinky.


## Enter to programming mode {#enter-to-programming-mode}

-   Switch to any layer for example <kbd>Fn</kbd> + <kbd>,</kbd>
-   Press <kbd>Fn</kbd> + <kbd>R\_Ctrl</kbd> to enter programming (Don't forget that <kbd>Fn</kbd> aleady on left side)
-   To map something you need to press key that you want to remap then result key and <kbd>Pn</kbd> key in end of each sequence:
    -   <kbd>L\_Win</kbd> -> <kbd>L\_Alt</kbd> -> <kbd>Pn</kbd>
    -   <kbd>L\_Alt</kbd> -> <kbd>L\_Win</kbd> -> <kbd>Pn</kbd>
    -   <kbd>R\_Alt</kbd> -> <kbd>L\_Win</kbd> -> <kbd>Pn</kbd>
    -   <kbd>CapsLock</kbd> -> <kbd>Escape</kbd> -> <kbd>Pn</kbd>
    -   <kbd>Escape</kbd> -> <kbd>Fn</kbd> + <kbd>Escape</kbd> -> <kbd>Pn</kbd>
    -   <kbd>Fn</kbd> + <kbd>z</kbd> -> <kbd>L\_Win</kbd> + <kbd>z</kbd> -> <kbd>Pn</kbd>
    -   <kbd>Fn</kbd> + <kbd>x</kbd> -> <kbd>L\_Win</kbd> + <kbd>x</kbd> -> <kbd>Pn</kbd>
    -   <kbd>Fn</kbd> + <kbd>c</kbd> -> <kbd>L\_Win</kbd> + <kbd>c</kbd> -> <kbd>Pn</kbd>
    -   <kbd>Fn</kbd> + <kbd>v</kbd> -> <kbd>L\_Win</kbd> + <kbd>v</kbd> -> <kbd>Pn</kbd>
    -   <kbd>Fn</kbd> + <kbd>w</kbd> -> <kbd>L\_Win</kbd> + <kbd>w</kbd> -> <kbd>Pn</kbd>
    -   <kbd>Fn</kbd> + <kbd>a</kbd> -> <kbd>L\_Win</kbd> + <kbd>a</kbd> -> <kbd>Pn</kbd>
    -   <kbd>Fn</kbd> + <kbd>;</kbd> -> <kbd>Fn</kbd> + <kbd>n</kbd> -> <kbd>Pn</kbd>
    -   <kbd>Fn</kbd> + <kbd>u</kbd> -> <kbd>L\_Alt</kbd> + <kbd>Left</kbd> -> <kbd>Pn</kbd>
    -   <kbd>Fn</kbd> + <kbd>o</kbd> -> <kbd>L\_Alt</kbd> + <kbd>Right</kbd> -> <kbd>Pn</kbd>
    -   <kbd>Fn</kbd> + <kbd>9</kbd> -> <kbd>Fn</kbd> + <kbd>u</kbd> -> <kbd>Pn</kbd>
    -   <kbd>Fn</kbd> + <kbd>0</kbd> -> <kbd>Fn</kbd> + <kbd>o</kbd> -> <kbd>Pn</kbd>

-   Press <kbd>Fn</kbd> + <kbd>R\_Ctrl</kbd> to exit


## Here are compleated list of keys: {#here-are-compleated-list-of-keys}

| Key from        | Key to         |
|-----------------|----------------|
| L\_Ctrl         | Fn             |
| L\_Win          | Option         |
| L\_Alt          | Cmd            |
| R\_Alt          | Cmd            |
| CapsLock        | Escape         |
| Escape          | \`             |
| Shift + Espcape | ~              |
| fn + z          | Cmd + z        |
| fn + x          | Cmd + x        |
| fn + c          | Cmd + c        |
| fn + v          | Cmd + v        |
| fn + w          | Cmd + w        |
| fn + a          | Cmd + a        |
| fn + h          | Home           |
| fn + :          | End            |
| fn + u          | Option + Left  |
| fn + o          | Option + Right |
| fn + 9          | PgUp           |
| fn + 0          | PgDown         |
