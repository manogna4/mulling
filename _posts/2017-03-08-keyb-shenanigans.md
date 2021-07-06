---
title: 'keyboard shenanigans'
tags: keyboard
category: nonfiction
---

About a year ago, I wrote a [post](/_posts/2016-01-26-saner-keyboard.md) describing what I thought would be the perfect keyboard.

My opinion has changed since then based on my experience of using a similar layout. I propose a different one that can be used on commercially available keyboards.

This is still not my perfect keyboard - I would prefer an orthonormal one, but procuring them is very expensive and will most often mean compromising on wirelessness(??) and size. Instead, I show how most compact keyboards available nowadays can be remapped to what I think is way more efficient. I've also included the software that can be used to do this on Windows.

Basic Principles:

1. *Minimize use of the pinkies*: Most keyboards make heavy use of them for modifiers, Enter, Tab, BackSpace.
2. *Commonly used keys should be close to home row*: The Cursor keys, Enter, BackSpace and Delete are too far from the home row on most keyboards.
3. *Modifiers should be easily accessible*: In windows keyboards only the Alt key is easily accessible by the thumb. This is worse for full size keyboards where the spacebar can be gigantic. An ideal keyboard would have a smaller spacebar and more keys that are accessible by the thumb, but such keyboards are very rare.
4. *Doc Nav keys should not be buried under combos*: Doc Nav keys are Home/End, Page Up/Down. Most compact keyboards use Function and Cursor key combinations to expose them. They are used often, and since combinations of the doc-nav keys with other modifiers are used in tab navigation and excel (Ctrl + PageUp for example), cumbersome 3 key combos become necessary.

My new layout addresses all these concerns. Broadly speaking, this is the strategy:

1. **Easy Enter key.** Remap the ; key to the enter key. 'Enter' becomes one of the home keys. Semi colon is rarely used anyway.
2. **Claim the right side of the keyboard as the doc nav cluster.** Look at the red area in the image below. This approximates to the doc nav cluster on full size keyboards. Remap the special character keys ( [ ] \ ' ) at the right side of the keyboard to doc nav keys. Also expose the Apps key through a Ctrl+/ combo - most keyboards use Fn+RCtrl for this but they are located at opposite ends of the keyboard.
3. **Make better use of the Home area through layers.** Home area is the region surrounding (i,j,k,l) - this is marked in blue in the below pic. Depending on the modifier this region could be used as a Doc Nav cluster or a Numpad.
4. **Replace the number keys on the top of the keyboard with Modifiers.** These keys are far more easily accessible than the usual location for modifiers (except for Alt, which can be accessed easily with the thumb). This makes it very easy to hit modifier combinations as well. (Try hitting Ctrl+Alt+Shift+Up on a normal keyboard). Notice that the number keys (and their corresponding special characters) will lost and will have to be exposed in some other way.
    1. **Ctrl** is the most common modifier and will be positioned at the most accessible number keys - 2 and 0. These 2 Ctrl keys have slightly different functions. More on this later. The ring fingers can be extended upward to hit these keys. (Respite for the pinkies!!)
    2. **Shift** will be positioned at the key locations of 3 and 9. These 2 Shift keys have slightly different functions as well. More on this later. The middle fingers can be used for them. (More respite for the pinkies).
    3. **Alt** is very accessible at it's usual location. However, for reasons explained in the section titled "modified modifiers" a modified Alt (modified modifier??) key will replace the 1 key.
    4. **Curs** (Cursor) modifiers expose cursor keys in the Home area. When the Curs modifiers are in effect the home area gets transformed as shown (the green legends) in the below pic. ijkl become the cursor keys; and other commonly used keys such as BS, Del, Tab, Esc, Page Up/Down, Home/End and Appkey become accessible without moving the right wrist. 4 and 6 key will be used for this with slightly different functions. The 4 key works like a normal modifier (eg shift). The Home area becomes transformed to the cursor cluster only when this key is held down. The 6 key works like a toggle (like Caps Lock).
    5. **Num** modifier exposes the standard NumPad (and then some) in the home region.
    6. **SP1 and SP2** (Special Characters) - expose special characters like !@$ which have been rendered directly inaccessible by the modifications made so far. The 8 key is used for SP1 which exposes most of the special characters on the left half of the keyboard. The mapping of the keys to the special characters can be difficult to remember. So I have used the top row (qwerty) to mimic the row above it. SP1+q = ! and SP2+w=@ and so on up to y. The other characters mappings will have to be remembered, but they get easy in time. The 7 key is used for SP2 combos that expose more special characters.
5. Modified Modifiers - the Alt, Ctrl and Shift modifiers that replace 1,2,3 keys have an added function. They also effectively trigger the non-toggle Curs modifier (ie the 4 key). So, holding down the 2 key and pressing the i key will behave as if one is holding down the Ctrl key and hitting the Up cursor key.
6. Caps Lock on steroids. The normal location is very accessible but the feature is rarely used, so this key can be co-opted for other purposes. The key is remapped to the Esc key (the usual placement of which is very inconvenient) but CapsLock key combos can be used for other functions like Alt+Tab, Ctrl+Tab. The `/~ key is used as the Caps Lock instead.

- - -

![key clusters](/assets/img/keyb-shenanigans/key-clusters.jpg)

Blue - Home Area. Red - Doc Nav Cluster. Orange - Modified Modifiers

- - -

I implemented the above using the excellent AutoHotKey. I have been using this new layout for just a couple of days (I typed the post using it), but I see myself working faster already. My hands ache a little adjusting to some new movements but I should get used to it in time. The same thing happened a year ago when I came up with the previous layout.

So, why didn't the layout described in my previous blogpost work? In that I had created a toggleable layer that changed all the alphabet keys to modifiers (like ctrl, alt), cursor keys, doc nav keys and commonly keyboard combos. It worked great in most cases, but broke down completely when a weird combination (like Alt E S V - paste special in excel) was required. Many programs expose shortcuts through the alt key combinations now. This is very convenient in normal layout but impossible when all the alphabet keys are replaced. I found myself frequently toggling in and out of this mode.

There are definitely limitations with the layout I have suggested here. Some keyboard combinations use numbers, and since I have hidden the numbers behind a layer, those combinations become very difficult. I have been mostly typing text since I started using this layout and it's been working great so far. I also hold down the Caps Lock key to modify n,h,i,j,k,l into del, bs, up, left, down, right.

I'll share the program that remaps the keyboard as described above with anyone interested. It should work on any keyboard on windows.

- - -

![logitech normal](/assets/img/keyb-shenanigans/logitech-normal.jpg)

Logitech K810 - my keyboard, unmodified

- - -

![logitech japan](/assets/img/keyb-shenanigans/logitech-japan.png)

The Japanese version with extra thumb keys. Anyone coming to India from Japan?