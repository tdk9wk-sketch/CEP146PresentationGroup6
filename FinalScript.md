The Script For the Video -

Have You heard?

Heard what?

2 weeks ago the Droid Deck officially released

The what?

You don't know what the droid deck is?

Well, surely you know the issue with translating code between Windows and Android

*nodding no

Before the droid deck, programmers must manually rewrite their code for it to work on Android devices

The Droid Deck removes that step

That's not all, the droid deck is publicly available on GitHub as an open source project licensed under GPL-3.0, so anyone can report bugs, suggest changes, or study the code

How does it work?

I'm glad you asked

I didn't

Well, Droid Deck combines three important technologies, PRoot, Proton, and Fex

PRoot is like having a little Linux enviroment running inside your Android device. 

Then there's Proton, which provides the compatibility between Windows and Linux and is talored to gaming

And lastly, Fex fixes the issue of processor translation

It bridges the gap by translating the instructions from one to the other

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

*Video Cuts to the second part

*Title Screen "What does the Droid Deck really do?"

alright now seriously. if you didn't quite get what my friends just told you, then let me make a quick recap just for you.

1.Currently, the Droid Deck allows you to have steam's big picture mode experience on your android phone or a tablet,

as long as your device's chip is supported by the app, allowing you to play games from your stam library.

how? well... There are tree steps that allow this

step one, translate the steam client and windows version of a games from WindowsOS to Linux.

2.since windows and linux have very different architectures, a program written for windows will not run on linux and vise versa. this means we need to somehow translate windows version of a program to linux.

and this can actually be done with Proton, which captures requests from the game that are meant to be received by Windows,

translates the recived requests in a version that linux understands, and sends the translated requests to Linux, while your game doesn't even understand that it is running on a different system.

3.step two, your android device must be able to run Linux programs, which it actually cannot do by default.

even though androi is linux at its core, it is way to different from regular linux, and so we need to find a way to convert linux programs to android.

4.and that is what PRoot was built for. It creates a folder that is structurally identical to linux's root system, which tricks linux programs into thinking that they are running on normal linux,

because it is essantially what they are running on.

5.step tree, make linux version of the game to run on an ARM system.

Most Windows games are designed specifically for x86 based processors while Android phones and tablets primerely run on ARM.

they have different processor instructions and regesters which makes binaries incompatable between platforms.

6.however, fex solves this problem. it can translate our x86 program to ARM, finalizing the translation process.

7.Though, what this technology does sounds magical, there is a catch.

Because the algorhythm translates the application in real time, your device's game performance will be significantly lower, because some fraction of power is being used on the translation,

though the community is actively working on optimizing the algorhythms.

8.Another thing I got to mention: not every single game on steam runs perfectly through these translation layers.

while some games might have occasional bugs, such as input issues or aspect ratio quirks, other games might not even be launched at all,

due to anti-cheat incompatability in multiplayer games, or because a game relies on some proprietary Windows components that proton cannot substitute.

9.right now, only around 10-15% of steam games run well on Android devices via Droid Deck, and around 30% of them run, but with heavy stuttering and graphics glitches,

and while this number is not impressive, this is still something, and this something grows with every year. hopefully, one day,

you will be able to run most of pc games on your Android device without any issues, and the translation will barely affect the performance. I really can't wait to see what this project will become.

*Video Ends
