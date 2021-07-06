---
title: 'a saner keyboard?'
tags: keyboard
category: nonfiction
---

I love spending hours saving seconds.

So, every time I move jobs or even just learn a new tool, I find myself obsessing over keyboard shortcuts. That eventually results in obsessing over the keyboard itself. So, when I started spending nearly all my time learning web programming a few months ago, keyboard layouts received more of my attention than coding itself.

Now, if you repeat the task enough number of times, it does make sense to spend time becoming more efficient. Probably no one could have illustrated this better than xkcd (who else) at https://xkcd.com/1205/

But that’s not why I do it. It can start as an itch I love to scratch – but right now my keyboard obsession has gone to the level of a mosquito that buzzes in my ears and doesn’t let me sleep. So, in an attempt to move on, I thought I’d just design my perfect keyboard, see if I can order a custom made one somewhere, and either way, get on with the rest of life.

It might surprise many to know that the current keyboard design might have been carefully designed to be inefficient. Computers inherited this design from mechanical typewriters and in those days of mechanical type bars, if nearby keys were hit in quick succession the mechanism would get jammed.

[More information on early keyboard design decisions here](http://www.smithsonianmag.com/arts-culture/fact-of-fiction-the-legend-of-the-qwerty-keyboard-49863249/?no-isthttp://www.smithsonianmag.com/arts-culture/fact-of-fiction-the-legend-of-the-qwerty-keyboard-49863249/?no-ist)

So, ‘j’, which is 0.15% of common usage is the easiest key to type for right handed typists ( it’s right under your favorite forefinger), whereas ‘t’, the most commonly used consonant in English that constitutes 9.05% of common usage requires a stretch of the left index finger.

The mechanism also drove the decision to have a staggered arrangement of keys. Worse, for reasons I haven’t been able to find out yet, the keys aren’t even evenly staggered.

To top that, some of the more reachable places that are used by barely used have modifier keys like the CAPS LOCK, which may have been necessary for early mechanical typists, but consume precious real estate now.

I set about putting some of the above right, and the above keyboard is what I came up with.

Major design concepts:

1. Use non staggered rows so that the keys are easy to find
2. Use modifier keys to have multiple uses for one key. Pressing a suitable positioned key combination is easier, faster and more accurate than moving a hand.

Design concepts in detail:

1. Every key has to be of the same width. I think It is easier for the muscle memory to remember one size than several variations. Modern keyboards can have as many as 5 different sized keys. Large keys exist on other keyboards so that they are easier to hit. This might be true for those doing a hunt-and-peck but looking at the wear marks on my present keyboard I guess touch typists hit large keys in the same spot every time. So, having larger keys just causes confusion and consumes precious real estate. The only exception in my design is the space bar which occupies double the space of the normal key, but that is because I want it accessible to both the thumbs.
2. There are 6 columns of keys per hand. The 4 fingers sit on the home row, and the index and little finger move just one key width horizontally for the hand to access the entire home row.
3. The keys are arranged in 6 non staggered rows. This enables typists to move across the keyboard just by feel, muscle memory isn’t needed to find the keys (but will eventually develop anyway). The function row can be done away with for non programmers (but a few layered functions will have to be reassigned).
4. I have introduced 3 kinds of modifier keys. Modifier keys are those keys used to modify how other keys work – such as the Ctrl or Shift key. The keys I have introduced are ULT(ra), NUM(ber) and MET(a). All these keys toggle a layer when pressed. So, they work like a traditional CAPS key and not like the shift key. However, if held down for a while (timings to be decided), they function like the shift key and toggle off when released. All three keys should have a light on it like many CAPS keys have.
    1. ULT activates the blue layer which is primarily used for cursor movement, document and application navigation and for some special characters that are usually accessed using the shift layer on a conventional keyboard but can’t here since I have reduced the number of keys.
    2. NUM activates the yellow layer which provides the function of a conventional number pad to the right hand and cursor and document navigation keys to the left hand.
    3. MET is used to activate user defined macros. I have currently not assigned any functions to this key, but I am sure any programmer can think of many ways of using it. Alternately, it can be used as a right-click or app switch key.
5. Do away with the CAPS and DEL key. The CAPS function can be accessed with a key combo like SHF+ULT and the DEL function can be accessed using SHF+BKS. The SUP(er) key is the windows key. Other OSes may refer to it differently.
6. The CTRL keys are moved towards the center of the bottom row (instead of the corners of the bottom row like a traditional windows layout) so that they are accessible using the thumbs. The undo, cut, copy, paste shortcuts become much more accessible to the left hand in this configuration. This actually resembles Apple’s OS-X layout where the command key is used to access many (Windows) Ctrl functions.
7. The entire keyboard can be accessed by only moving the fingers and not changing the position of the hand. This enables the typist to work faster by saving the seconds spend in moving the right hand from the alphabet key cluster to the cursor key cluster and the number pad. The typist needs to move one hand off the home position only to use the mouse. Many advanced typists learn to navigate using mostly the keyboard anyway, so this problem goes away with time.
8. I have made sure all important functions traditionally on the right side of the keyboard (such as return, backspace, cursor and document navigation) can be easily accessed using the left hand only, for the convenience of those who use the mouse with their right hand. A similar configuration can also be done for the left handed mouse users.
9. This keyboard is much smaller than the traditional layout. It extends from the caps lock key to the semi colon key of a traditional keyboard. With laptops getting thinner and smaller the space freed up by this configuration can be used for other stuff like a bigger battery. A lot of the keyboard lies below the surface, so this could mean a lot of additional volume.
10. I have stuck to the QWERTY layout. There exist better alphabetic layouts like COLEMARK and DVORAK, but I am already used to the QWERTY. All the other design decisions I have made can be used in conjunction with any these alternate layout as well.

Everything I have described above should be programmed at the keyboard firmware level. It isn’t difficult to set up layers and modified functions as described above using software like the excellent AutoHotKey for windows. But, many programmers use multiple computers and at times multiple operating systems on one computer, and setting up the above behavior on all systems can be tedious, and in some cases (like multiple virtual machines, maybe) impossible.

I would love to get feedback on the layout. After searching for months, I have finally found a company [http://www.access-is.com/pdf/AKC090_Programmable_Keyboard.pdf](access-is pdf) that non only custom makes non-staggered keyboards but provides a programmable interface as well. I would like to iron the kinks out of my design before placing an order.

I think I might have to settle for a 15 by 6 key configuration instead of the 12 x 6 configuration I have designed. So, I’d love suggestions on what to do with the extra 3 by 6 matrix of keys. I will utilize the right (12 by 6 keys) side of the larger keyboard for what I have designed above, and will have a 3 by 6 grid of keys to the left. (This is so that I have easy access to the mouse with my right hand).

I am definitely not to first person to think along these lines. In the search for the perfect keyboard over the past few months, I have come across companies that sell keyboards of various designs and even exotic ones have been proposed on geeky forums in the inner lanes of the internet, but haven’t seen the light of day. With the advent of 3D printing, even there’s even a small but active market for custom key caps. Describing some of these as non-traditional would be a gross understatement.

Sources:

I spent hours looking through threads such as [geekhack](https://geekhack.org/index.php?topic=49702.0) and [reddit](https://www.reddit.com/r/MechanicalKeyboards/).

- - -

![my design](/assets/img/keyb-saner/keyboard-mano.jpg)

My Design. I used the tool at keyboard-layout-editor.com

- - -

![my design](/assets/img/keyb-saner/various-sizes.jpg)

Keyboards come in all sizes. From the top: Full size, TKL (Ten key less) layout, 60% layout, 40% layout. [Source](i.imgur.com/4saapo8.jpg)

- - -

![my design](/assets/img/keyb-saner/truly-ergonomic-keyboard.jpg)

A non staggered layout from trulyergonomic.com. I liked that the rows weren't staggered. The staggered columns are interesting - the allow the fingers to rest more naturally. But I don't like the double sized modifier keys, the relatively inaccessible cursor and document navigation keys and the very inaccessible function keys.


- - -

![my design](/assets/img/keyb-saner/kinesis-advantage.jpg)

Kinesis advantage from kinesis-ergo.com. This literally adds another dimension to the trulyergonomic concept.

- - -

![my design](/assets/img/keyb-saner/textblade-2.jpg)

QWERTY text entry stripped to its bare essentials. From coolthings.com/textblade. I would love to give this a try, but it costs 100$

- - -

![my design](/assets/img/keyb-saner/mario-keycap.jpg)

Some people like this on their keys! From shapeways