# Dvorak-multitap-keyboard-layout
## If you have a question send it to:
elsanussi.m@outlook.com


## Repository Status
This repository is abandoned. No new changes expected. See POSTSCRIPT.txt for explanation. I abandoned this for the standard Dvorak keyboard layout.

This repository is mostly now left as a historical example of creating keyboard layouts for Mac OS Catalina, and Windows 8 in the year 2020.

If you use this repository, I suggest you clone, or fork it so that you do not lose access.

## Health disclaimer
I make no claim that this keyboard is more ergonomic or better for anyone. Any health related questions should go to your local medical specialist in that field.

## About the license, and copyright
I honestly don't know what the copyright law is when you make derivative works of keyboard layouts that came with Mac OS, and Windows. I do not intend to find out. For that reason, and becuase I did not make this from scratch, I don't include a license or copyright. 

I believe it would be counterproductive if Apple, and Microsoft did not allow customers to modify keyboard layouts, and so I don't think it makes sense to worry about it. This is especially true for accessibility reasons.

However, if this violates copyright law, then I will take it down.

## Introduction
This is a keyboard layout I started using and modifying in 2020 after reading about other programmers  who wanted a more comfortable keyboard layout.

It is currently a very conservative modification of the Dvorak keyboard layout.

It is a derivative of the Dvorak Keyboard Layout with inspiration from the Workman Dead key layout.
- It works on MacOS Catalina.
- It works on Windows 8.

### On Windows
Use the file with the name 

## What I did:
I used the DVORAK keyboard layout that comes with my computer
- I added the deadkey layout from Workman on top, using the semicolon key as a dead key.

- Then I experimented for a while with the following ideas
  - a layer so that keys not above or below could be accessed more closely.
  - a layer so that keys on the opposite hand could be accessed by any hand near its usual position.
  - a layer to make move keys that are on the numbers row to the home row
  - a layer for single, double, and quadruple  tabs, spaces, or new lines
  - a layer for capital letters
  - a layer for accented characters 


Then I gave up on most of those layers, and stuck with only the extra layer from workman Dead layout, but with the modification that the Shift key doubles any characters on that layer.

Motivations:
 - I wanted a more comfortable way to type when I program, that could handle English and French.
  - For a while I thought it would be useful to be able to type with one hand in place.


What I learned:
It would be really useful to have a few extra keys on the keyboard. The concept of being able to type with one hand is hampered greatly because there are more keys on the right hand than the left, making a single mirrored keyboard layout impossible without leaving some keys out.


The following video is where I got the layer for programmers on the semicolon.
https://youtu.be/ek2Ld6Li8bM?t=377

He uses a different keyboard layout than Dvorak. I decided to go with Dvorak instead, but I liked the layer for programmers I found on the Worman Deadkey layout, so I combined it with Dvorak.

The idea behind my layout is that it is as close to Dvorak as possible so that if you end up on a computer where you can only use preinstalled layouts (not your own custom ones), you should be okay. 

## Note to developer
### How to change the version number of the file
Use a command similar to the following.
```
git mv "Dvorak Multitap v9.3.bundle" "Dvorak Multitap v9.4.bundle"
```
Then you may open the bundle and begin editing it.
This is so that we can see the changes easily in the source control management system.