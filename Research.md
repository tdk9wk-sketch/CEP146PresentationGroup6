# Research For CEP146 Presentation -

Aidan Research ˬ



Wen Research ˬ
## What is Droid Deck
- Droid deck is an application translation layer using Proot, Proton, and Fex to bring games made for AMD64 Windows to ARM64 Android devices [4]
- Droid deck is a community driven application licenced as GPL 3.0 [1]

## What is Proton
- Proton is a translation layer built off Wine that brings Win32 functionality to Linux [2]

## What is FEX
- Fex is a ARM64 to AMD64 translation layer [5]
- Forwards calls to the host system library [5]

## What is Proot
- proot is a sandbox enviroment for another file system that does not require root [3]

## What does Droid Deck do
- Brings the Linux Desktop to Android [1]
- uses the LXQT desktop enviroment [1]
- Brings systemd, glibc, gamescope/wlroots to Android [4]
- Bridges Linux daemons such as PulseAudio [4]
- Translates touchscreen inputs into uinput events [4]
- Translates to native gpu drivers [4]

1. https://droiddeck.app/
1. https://www.pcworld.com/article/394895/what-is-valve-proton-steam-deck-games-software-explained.html
1. https://wiki.archlinux.org/title/PRoot
1. https://en.linuxadictos.com/Droiddeck-lets-you-run-Steam-and-PC-games-directly-on-Android.html#:~:text=From%20there%2C%20you%20can%20run%20desktop%20applications,game.%20Installation%20without%20root%20and%20open%20source.
1. https://fex-emu.com/

Ali Research ˬ

# SteamOS On Android?!?!

In this research we will tell you about the recently released Android application, the Droid Deck,
which allows you to have SteamOS experience on your Android device, including all the Steam features,
and most importantly, it allows you to play most of pc games on your phone or tablet!

## About Droid Deck:

The Droid deck is an open sourse community project that is meant to bring the SteamOS experience to
Android devices and run pc games on them. For that, the applications uses Proton and Fex translation
layers in order to translate the Steam client and games you want to play, so that Android could
understand and execute them.

## The Translation Process:

In order to run Steam games on Android, first we need to translate the Steam client and the games from
WindowsOS to Linux, becasue these operating systems have different architectures, and then translate
then to ARM, because at this stage the Linux versions of the applications we want to translate are still
meant to be run on a x86 based hardware, where as Android devices are ARM based. The resulting programs
will provide the exact same experience as if you ran them on a normal Windows pc.

However, because of the double translation level, your device's performance in games will be significantly
lowered, because some fraction of power is being used for the translation, though the comunity is activly
working on optimizing the algorhythms.
