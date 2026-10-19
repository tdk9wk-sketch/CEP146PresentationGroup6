# SteamOS On Android?!?!

In this research we will tell you about the recently released Android application, the Droid Deck, which allows you to have SteamOS experience on your Android device, including all the Steam features, and most importantly, it allows you to play most of pc games on your Android phone or tablet!

## About Droid Deck:

The Droid deck is an open source community project that is meant to bring the SteamOS experience to Android devices and run pc games on them. For that, the applications uses Proton and Fex translation layers in order to translate the Steam client and games you want to play, so that Android could understand and execute them.

## The Translation Process:

In order to run Steam games on Android, first we need to translate the Steam client and the games from WindowsOS to Linux, because these operating systems have different architectures, and then translate them to ARM, because at this stage the Linux versions of the applications we want to translate are still meant to be run on a x86 based hardware, where as Android devices are ARM based. The resulting programs will provide the exact same experience as if you ran them on a normal Windows pc.

## The Caveat

Though, what this technology can do sounds absolutely amazing, there is a catch. Because the algorhythm translates the application in real time, your device's game performance will be significantly lower, because some fraction of power is being used on the translation, though the community is actively working on optimizing the algorhythms.

Another thing I got to mention: not every single game on steam runs perfectly through these translation layers. While some games might have occasional bugs, such as input issues or aspect ratio quirks, other games might not even be launched at all, due to anti-cheat incompatability in multiplayer games, or because a game relies on some proprietary Windows components that proton cannot substitute.

right now, only around 10-15% of steam games run well on Android devices, and around 30% run, but with heavy stuttering and graphics glitches, and while this number is not impressive, this is still something, and this something grows with every year. hopefully, one day you will be able to run most of pc games on your Android device without any issues, and the translation will barely affect the performance.

==========================

Have You heard?

Heard what?

2 weeks ago the Droid Deck officially released

The what?

You don't know what the droid deck is?

Well, surely you know the issue with translating code between Windows and Android

*nodding no

Before the droid deck, programmers must manually rewrite their code for it to work on Android devices

The Droid Deck removes that step

That's not all, the droid deck is publicly available on GitHub as an open source project licensed under GPL-3.0, so anyone can report bugs, suggest changes, study the code, or add your own changes

How does it work?

I'm glad you asked

I didn't

Well, Droid Deck combines three important technologies, PRoot, Proton, and Fex

PRoot is like having a little Linux enviroment running inside your Android device. It provides you the environment that Linux programs expect without requiring you to replace Android itself or root your system.

Then there's Proton, which provides the compatibility between Windows Win32API and Linux and it's talored to gaming

Proton is built to capture requests to Win32 and it sends the request to the Linux equivalent and provides a windows file structure so games don't even realize they're running on a different system. It is also supported by Valve, the biggest PC games vendor.

And lastly, Fex fixes the issue of processor translation

Most Windows PC games are designed for x86-64 processors while many Android devices use ARM64 Processors, these have different processor instructions and regesters which makes binaries incompatable between platforms.

Fex bridges the gap by translating the instructions from one to the other.

For example ARM disallows direct memory requests. In the case that a program tries to manipulate memory instead of setting and loading, Fex would translate the program so that it does.

When these three work together, suddenly you have a game built for a different archetecture and operating system working on a smartphone

Cool

I've got class in ten minutes, can I go

Just think about what this means for programmers

And he's still talking

You don't have to rewrite your code for every device

If the code is translating in real time, does that not mean that it would be very slow?

I mean, right now it doesnt work perfectly

And I guess its not the fastest for running games with

But imagine

Majority of your computer games will be able to run on your phone thanks to the droid deck

Wait, where are you going?

I told you, I got class

Hold on, isn't it amazing though

I guess, but I don't play games on my phone either way

Wait, there's still so much to talk about! You have your entire Steam library on the go without spending money on a Steam Deck.

Hold on!

*Door shuts

*Video Ends
