+++
title = "IJKL Navigation in Karabiner"
author = ["nixorg"]
date = 2018-07-31T13:13:00+03:00
tags = ["karabier", "keyboard", "macos", "macbook", "ergonomic"]
draft = false
+++

I'm macbook user and have programable keyboard where I use <kbd>Fn</kbd> + <kbd>I</kbd>,<kbd>J</kbd>,<kbd>K</kbd>,<kbd>L</kbd>
instead of arrow keys. This way is more ergonomic as you don't need to move
your hand if you need use arrows.
![](/images/karabiner_workflow_arrows.png)

<!--more-->

Sometimes I work without external keyboard and it's a pain if I type or proramming a lot and then I
need to move my hand to arrows.

Fortunetely Mac OS have amazing application which is called `Karabiner` where you able to remap any keys or key sequence (even <kbd>Fn</kbd> keys sequence).


## Instalation {#instalation}

-   Install [Karabiner Elements](https://pqrs.org/osx/karabiner)
-   Open the config [qwerty](karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/KreiDer/dotfiles/master/.config/karabiner/assets/complex_modifications/karabiner_qwerty.json) or [dvorak](karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/KreiDer/dotfiles/master/.config/karabiner/assets/complex_modifications/karabiner_dvorak.json) and select import
-   Go to Complex Modifications tab and Add corespondent rules

So here are my layout that makes <kbd>⌥</kbd> + <kbd>I</kbd>,<kbd>J</kbd>,<kbd>K</kbd>,<kbd>L</kbd> as arrows along with some usefull stuff:


## Word navigation {#word-navigation}

-   <kbd>⌥</kbd> + <kbd>u</kbd> to <kbd>⌥</kbd> + <kbd>←</kbd>
-   <kbd>⌥</kbd> + <kbd>o</kbd> to <kbd>⌥</kbd> + <kbd>→</kbd>
-   <kbd>⌥</kbd> + <kbd>⇧</kbd> + <kbd>u</kbd> to <kbd>⌥</kbd> + <kbd>⇧</kbd> + <kbd>←</kbd>
-   <kbd>⌥</kbd> + <kbd>⇧</kbd> + <kbd>o</kbd> to <kbd>⌥</kbd> + <kbd>⇧</kbd> + <kbd>→</kbd>


## Change ⌥ (or ⇧) + h/; to Home and End {#change--or--h-to-home-and-end}

-   <kbd>⌥</kbd> + <kbd>h</kbd> to <kbd>⌘</kbd> + <kbd>←</kbd>
-   <kbd>⌥</kbd> + <kbd>;</kbd> to <kbd>⌘</kbd> + <kbd>→</kbd>
-   <kbd>⌥</kbd> + <kbd>⇧</kbd> + <kbd>h</kbd> to <kbd>⌘</kbd> + <kbd>⇧</kbd> + <kbd>←</kbd>
-   <kbd>⌥</kbd> + <kbd>⇧</kbd> + <kbd>;</kbd> to <kbd>⌘</kbd> + <kbd>⇧</kbd> + <kbd>→</kbd>


## Change ⌥ (or ⇧) + i/j/k/l to Arrows {#change--or--i-j-k-l-to-arrows}

-   <kbd>⌥</kbd> + <kbd>⇧</kbd> + <kbd>j</kbd> to <kbd>⇧</kbd> + <kbd>←</kbd>
-   <kbd>⌥</kbd> + <kbd>⇧</kbd> + <kbd>l</kbd> to <kbd>⇧</kbd> + <kbd>→</kbd>
-   <kbd>⌥</kbd> + <kbd>⇧</kbd> + <kbd>i</kbd> to <kbd>⇧</kbd> + <kbd>↑</kbd>
-   <kbd>⌥</kbd> + <kbd>⇧</kbd> + <kbd>k</kbd> to <kbd>⇧</kbd> + <kbd>↓</kbd>
-   <kbd>⌥</kbd> + <kbd>j</kbd> to <kbd>←</kbd>
-   <kbd>⌥</kbd> + <kbd>k</kbd> to <kbd>↓</kbd>
-   <kbd>⌥</kbd> + <kbd>i</kbd> to <kbd>↑</kbd>
-   <kbd>⌥</kbd> + <kbd>l</kbd> to <kbd>→</kbd>


## Change Fn + to copy {#change-fn-to-copy}

-   <kbd>Fn</kbd> + <kbd>z</kbd> to <kbd>⌘</kbd> + <kbd>z</kbd>
-   <kbd>Fn</kbd> + <kbd>x</kbd> to <kbd>⌘</kbd> + <kbd>x</kbd>
-   <kbd>Fn</kbd> + <kbd>c</kbd> to <kbd>⌘</kbd> + <kbd>c</kbd>
-   <kbd>Fn</kbd> + <kbd>v</kbd> to <kbd>⌘</kbd> + <kbd>v</kbd>
-   <kbd>Fn</kbd> + <kbd>a</kbd> to <kbd>⌘</kbd> + <kbd>a</kbd>
-   <kbd>Fn</kbd> + <kbd>w</kbd> to <kbd>⌘</kbd> + <kbd>w</kbd>


## ⌥ + 0 to Ctrl + c (for iTerm) {#0-to-ctrl-c--for-iterm}

-   <kbd>⌥</kbd> + <kbd>0</kbd> to <kbd>⌃</kbd> + <kbd>i</kbd>

PS: Here are some topics that inspired me [ijkl](http://xahlee.info/kbd/vi%5Fhjkl%5Fvs%5Finverted%5Ft%5Fijkl%5Farrow%5Fkeys.html) and [ergoemacs](https://ergoemacs.github.io/)
