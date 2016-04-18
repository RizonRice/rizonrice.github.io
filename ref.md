---
layout: ref
title: "list o' resources"
description: 'Ricing resources for Linux, Mac and Windows'
---

[Pull requests](https://github.com/RizonRice/ref) for contributions are more than welcome.

# Table of contents
- [A quick summary](#how)
- [Window managers](#window-managers)
- [Tiling](#tiling)
- [Bars](#bars)
- [Program Launchers](#program-launchers)
- [Terminal emulators](#terminal-emulators)
- [Shells](#shells)
- [Color schemes](#color-schemes)
- [Wallpapers](#wallpapers)
- [Fonts](#fonts)
- [Firefox](#firefox)
- [Seamonkey](#seamonkey)
- [Image viewers](#image-viewers)
- [Audio](#audio)
- [Video](#video)
- [IRC](#irc)
- [System](#system-info)
- [Sharing it!](#sharing-it)

# How?

First of all; ricing won't be an easy task. I mean, sure you can copy the config
files from someone else and live with that. But that kind of ruins the fun of it all.

**You encounter a problem or error and don't know how to continue?**

#### Google it

This solves literally 90% of all the problems people ever have. I can't push
this enough. The problem you're encountering is most likely not unique. You're
probably not the first to struggle with it. By looking online you will nearly
always find your (or a similar) question that will help you get going again.

* [duckduckgo](https://duckduckgo/)
* [google](https://google.com/)

#### Manual

"How do I do x in y?", "Is it possible to do x with y?". "What does x do?".

These are all way to common questions, especially for people who are starting
with linux. 99% of the applications/binaries you're using have some kind of
manual through either `$ man NAME_OF_APPLICATION` or `$ NAME_OF_APPLICATION
--help`. This will very likely contain the solution one way or another.

If you still feel like you want a guide or something as a place to start,
you can go [here](http://linuxnewbieguide.org/) for Linux, and for ricing
on Windows 7, you can go [here](http://nanami-tan.info/).

# Window managers

A window manager (WM) is system software that controls the placement and
appearance of windows within a windowing system in a graphical user interface (GUI).
It can be part of a desktop environment (DE) or be used standalone.

#### Linux
- [X11](https://wiki.archlinux.org/index.php/Xorg)
  - [Openbox](https://wiki.archlinux.org/index.php/Openbox)
  - [Awesome](https://wiki.archlinux.org/index.php/Awesome)
    - [Awesome gaps](https://github.com/copycat-killer/lain)
  - [i3](https://wiki.archlinux.org/index.php/I3)
    - [i3 gaps](https://github.com/Airblader/i3)
  - [Qtile](http://www.qtile.org/)
  - [herbstluftwm](http://www.herbstluftwm.org/)
  - [howm](https://github.com/HarveyHunt/howm)
  - [bspwm](https://wiki.archlinux.org/index.php/Bspwm)
  - [dwm](https://wiki.archlinux.org/index.php/Dwm)
  - [xmonad](https://wiki.archlinux.org/index.php/Xmonad)
  - [FVWM](http://www.fvwm.org/)
- [Wayland](https://wiki.archlinux.org/index.php/Wayland)
  - [velox](https://github.com/michaelforney/velox)
  - [sway](https://github.com/SirCmpwn/sway)
  - [Orbment](https://github.com/Cloudef/orbment)

#### Windows
- [Blackbox](http://blackbox4windows.com/) - [bbZero mirror(no registration)](http://spoonm.org/share/bbzero/)
- [Windawesome](https://windawesome.codeplex.com)
- [bugn](https://code.google.com/p/bugn/wiki/bugn)
- [qt](https://github.com/Vibex/qt.pi)
- [Tilde++](https://github.com/ragesalmon/TildePlusPlus)

#### OSX
- [Spectacle](https://www.spectacleapp.com/)
- [Mjolnir](https://github.com/sdegutis/mjolnir)
- [KWM](https://github.com/koekeishiya/kwm)
- [Phoenix](https://github.com/kasper/phoenix)

# Tiling

The following applications are purely created for tiling. They bring nothing
else to the table. If you're looking for something more complete consider
looking at [window managers](#window-managers).

#### Linux
- [PyTyle](http://sourceforge.net/projects/pytyle/)
- [PyTyle2](https://code.google.com/p/pytyle/)
- [PyTyle3](https://github.com/BurntSushi/pytyle3)
- [The difference between PyTyles](https://bbs.archlinux.org/viewtopic.php?pid=1058199#p1058199).

#### Windows
- [WinSplit](http://download.cnet.com/WinSplit-Revolution/3000-2072_4-10971915.html)
- [Gridmove](http://jgpaiva.dcmembers.com/gridmove.html)

#### OSX
- [hs.tiling](https://github.com/dsanson/hs.tiling)

# Bars

Bars (aka panels) are used to display everything from current desktops to active windows to
system informaton. They have very similiar behaviour to the bar you would expect
on Windows and OSX.

#### Linux
- [Candybar](https://github.com/Lokaltog/candybar)
- [Dzen](https://wiki.archlinux.org/index.php/Dzen)
- [Lemonbar](https://github.com/LemonBoy/bar)
- [Tint](https://wiki.archlinux.org/index.php/Tint2)
- [n30f](https://github.com/sdhand/n30f)

#### Windows
*Placeholder*

#### OSX
- [bar](https://github.com/callahanrts/bar)

# Program Launchers

A launcher is a program displaying a dialog to search for an action, typically launch an application. Many are not limited to just this, and allow you to perform other operations such as open up files and folders on your computer.

#### Linux
- [bmenu](https://github.com/Cloudef/bemenu)
- [dmenu](http://tools.suckless.org/dmenu/)
  - [dmenu2](https://bitbucket.org/melek/dmenu2)
- [lighthouse](https://github.com/emgram769/lighthouse)
- [interrobang](https://github.com/TrilbyWhite/interrobang)
- [thinglaunch](http://git.r-36.net/thinglaunch/)
- [rofi](https://github.com/DaveDavenport/rofi)

#### OSX
- Finder (included with OS)

#### Windows
- Start Menu (included with OS)
- [Launchy](http://www.launchy.net/)

# Terminal emulators

A terminal emulator, terminal application, term, or tty for short, is a program
that emulates a video terminal within some other display architecture.
Though typically synonymous with a shell or text terminal, the term terminal
covers all remote terminals, including graphical interfaces. A terminal emulator
inside a graphical user interface is often called a terminal window.

#### Linux
- [termite](https://github.com/thestinger/termite)
- [urxvt](https://wiki.archlinux.org/index.php/Rxvt-unicode)
  - [urxvt-perls](https://github.com/muennich/urxvt-perls)
- [st](http://st.suckless.org/)
  - [st-patches](http://st.suckless.org/patches/)
- [Terminator](https://wiki.archlinux.org/index.php/Terminator)
- [xfce4-terminal](http://docs.xfce.org/apps/terminal/start)

#### Windows
- [Console](http://sourceforge.net/projects/console/)
- [Mintty](https://code.google.com/p/mintty/)
- [Conemu](https://conemu.github.io/)
- [Babun](https://babun.github.io/)

#### OSX
- [Iterm2](https://www.iterm2.com)

# Shells
- [Zsh](http://www.zsh.org/)
  - [Oh-My-Zsh](https://github.com/robbyrussell/oh-my-zsh)
  - [Prezto](https://github.com/sorin-ionescu/prezto)
- [Fish](http://fishshell.com/)
  - [Fisherman](http://fisherman.sh/)

# Color schemes
- http://terminal.sexy
- http://coolors.co
- http://paletton.com
- http://www.xcolors.net
- http://www.colourlovers.com
- http://www.materialpalette.com
- http://www.transparenttextures.com
- http://daylerees.github.io
- http://www.imagecolorpicker.com
- http://pltts.me
- http://dotshare.it/category/terms/colors

# Wallpapers
- http://alpha.wallhaven.cc
- http://simpledesktops.com
- http://subtlepatterns.com
- http://www.squidfingers.com/patterns
- https://unsplash.com
- https://nik.bot.nu/browse.html
- http://4walled.cc
- http://www.stripegenerator.com
- http://www.tartanmaker.com
- https://www.flickr.com
- https://deviantart.com
- http://gratisography.com

# Fonts

## Where to get fonts?
- http://www.dafont.com
- http://fontawesome.io
- http://ionicons.com
- https://github.com/chrissimpkins/codeface
- https://github.com/Tecate/bitmap-fonts
- https://github.com/brabadu/awesome-fonts

On Debian/Ubuntu you need to enable bitmap fonts first:

```bash
sudo rm /etc/fonts/conf.d/70-no-bitmaps.conf
sudo fc-cache -f -v
```

## Font rendering

#### Windows
- https://code.google.com/p/gdipp
- https://code.google.com/p/mactype - [installer](http://spoonm.org/share/mactype.exe)

#### Linux
- https://wiki.archlinux.org/index.php/Infinality
- https://aur.archlinux.org/packages/freetype2-ubuntu
- https://aur.archlinux.org/packages/fontconfig-ubuntu
- https://aur.archlinux.org/packages/cairo-ubuntu

#### OSX
*Do you even need it?*

# Firefox
- chrome://browser/content/browser.xul
- [Nightly](https://nightly.mozilla.org)
- [Stylish](https://addons.mozilla.org/en-US/firefox/addon/stylish)
- [LINC](http://www.logicalincrements.com/firefox/)
- [Twily's stuff](http://twily.info/firefox/stylish/)
- [TinyCSS](http://noha-ra.deviantart.com/art/Tinycss-476413072)

# Seamonkey
- chrome://navigator/content/navigator.xul
- [Incompatible addon converter](http://addonconverter.fotokraina.com/)

# Image viewers

#### Linux
- [sxiv](https://github.com/lucy/sxiv)
- [pqiv](https://github.com/phillipberndt/pqiv)
- [feh](http://feh.finalrewind.org/)
- [meh](http://www.johnhawthorn.com/meh/)

#### Windows
- [Honeyview](http://www.bandisoft.com/honeyview/)
- [stb](https://github.com/nothings/stb-imv/)

#### OSX
*Placeholder*

# Audio

#### Linux
- [mpd](http://www.musicpd.org)
  - [ncmpcpp](http://ncmpcpp.rybczak.net)
  - [cava](http://karlstav.github.io/cava)
  - [mpdviz](https://github.com/lucy/mpdviz)
  - [nausea](https://github.com/ViktorNova/nausea)
- [cmus](https://cmus.github.io/)

#### Windows
- [Aimp](http://www.aimp.ru)
- [Foobar](http://www.foobar2000.org)

#### OSX
- [Vox](http://coppertino.com/)

# Video

#### Linux
- [mpv](https://github.com/mpv-player/mpv)
- [mpvhq](https://github.com/haasn/mpvhq)

#### Windows
- [mpv](http://mpv.srsfckn.biz/)
- [mpvhq](https://github.com/haasn/mpvhq)
- [mpcbe](http://sourceforge.net/projects/mpcbe)
- [mpc-hc](https://mpc-hc.org)

#### OSX
- [mpv](https://github.com/mpv-player/mpv)
- [mpvhq](https://github.com/haasn/mpvhq)

# IRC
- [Hexchat](https://hexchat.github.io/)
- [Weechat](https://weechat.org/)
- [Irssi](http://www.irssi.org/)

# System info

#### Linux
- [Screenfetch](https://github.com/KittyKatt/screenFetch)
- [Archey](https://github.com/djmelik/archey)
- [Alsi](https://github.com/trizen/alsi)
- [Ufetch](https://github.com/jschx/ufetch)
- [Neofetch](https://github.com/dylanaraps/neofetch)

#### Windows
- [Cmdfetch](https://github.com/hal-ullr/cmdfetch)
- [Neofetch](https://github.com/dylanaraps/neofetch)

#### OSX
- [Screenfetch](https://github.com/KittyKatt/screenFetch)
- [osxinfo](https://github.com/yrmt/osxinfo)
- [Neofetch](https://github.com/dylanaraps/neofetch)

# Sharing it
- File hosts
  - https://mixtape.moe
  - https://catbox.moe
  - https://u.teknik.io
  - http://1339.cf
  - https://maxfile.ro
  - http://puush.me
  - https://transfer.sh
  - https://curl.io
  - https://madokami.com/
  - https://u.pste.pw
- Upload tools
  - [Moe](https://github.com/Imakethings/Moe)
  - [ShareX](https://getsharex.com/)
  - [gone](https://github.com/kori/gone)
  - [uguush](https://github.com/jschx/uguush)
  - [puush](http://puush.me/)
  - [cURL](https://curl.io/)
- Screenshot tools
  - [maim](https://github.com/naelstrof/maim)
  - [Import](http://www.imagemagick.org/script/import.php)
  - [scrot](http://freecode.com/projects/scrot)
  - (Windows only) Pressing the Print Screen key saves the screen to your clipboard. Then, paste in any image manipulation program.
  - (Windows 8.1+ only) Windows key + Print Screen (stored in your Pictures\Screenshots folder)
- Screen recording
  - [Screencast](http://twily.info/scripts/screencast#view) (Uses ffmpeg to record screen to webm)
- Pastebins
  - https://p.teknik.io
  - https://spit.mixtape.moe
  - http://ix.io
  - http://sprunge.us
  - https://ptpb.pw
  - https://pste.pw
