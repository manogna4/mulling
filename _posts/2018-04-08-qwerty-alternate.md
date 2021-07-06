---
title: qwerty alternate for ergo and ortho keyboards
tags: keyboard
category: nonfiction
---

In all my previous experiments with keyboards over the last two years (culminating with this [post](http://mull.in/2018/03/25/keyboard-improvement-3-layers/)) I did not tinker with the layout of the alphabet keys. In fact, early on itself, after giving Dvorak a very brief try, I swore I wouldn't - it took too long to learn, and at 50+ words per minute I was at a comfortable pace for the work I do. My pain points were elsewhere, and the layers I use solved that.

## My motivation

However, the situation changed when I got my first custom keyboard, which has a column staggered layout. While it made most typing much easier, a few keys actually got more difficult. Let us see why:

![00 row stag vs ortho.JPG](/assets/img/qwerty-alternate/00-row-stag-vs-ortho.jpg)

The above diagram shows the distances between the keys (in terms of key units) and the home positions in row staggered (normal qwerty layout) and an ortholinear layout. Ergo (column staggered) and ortho boards would have similar key distances.

In most row staggered keyboards, the top row is a quarter unit to the left of the home column, while the bottom row is a half unit to the left of the home column. This non uniformity of the stagger is a historical artefact and gives the top and bottom row different relative positions.

The distances are actual travel distances between keys calculated using [Gougu theorem](http://www.rediff.com/news/special/did-india-discover-pythogoras-theorem-a-top-mathematician-answers/20150109.htm) (or Pythagorus theorem, as some wrongly call it :-P ). Note that many analyses similar to the one I am attempting here, measure the key distances in terms of number of keys travelled - so 'T' would be considered to have a distance of 1, instead of the 1.25 that I have used here (for the row staggered layout). But, I chose actual distances, since they are crucial to my proposition.

Note that when you move from a row staggered to an ortho layout, the 'N' and 'T' positions change unfavourably. Together, they constitute about 16% ( T is around 9% and N is around 7% ) of all alphabet key presses, so this is a very significant compromise. For me, this was a significant enough to consider different layouts, and down that rabbit hole I went.

## Methodology

Many (and likely better skilled) people have attempted this before. So why do I propose an alternate alternate (repetition intentional) layout?

I eliminated completely new layouts because they took too long to learn, and I spend too long on my keyboards as it is. This eliminates layouts like Dvorak. I did give it another shot though, and will refer to that attempt at the end of this post.

Why I chose not to use qwerty-like layouts should become clearer (to those familiar with these layouts) as I describe my layout.

Before delving into the layout, let us first identify some guiding principles for designing a good layout.

### Key preferences

1.  The highest preference is for keys on home row (qwerty positons a s d f j k l ; ).
2.  The keys directly above the index, ring and middle finger are given the next preference. (qwerty positons w e r u i o)
3.  The keys directly below the index, ring and middle finger are given the next preference (qwerty positions x c v m , . )
4.  The keys that need the index to be moved up and in or just in will be given the next preference. (qwerty positions t g y h). Normally, the g and h positions are given a high preference since they are only 1u away. I assign it a low preference because to access these keys one has to rotate the wrist (to varying degrees depending on finger size) resulting in all fingers losing their home positions.
5.  The other keys i.e the keys that need the index to be moved down and in (qwerty positions b n); and the keys that need the pinky to be moved up or down will be given the least preference (qwerty positions q z p / ) .
6.  The middle finger is the strongest finger albeit not the most flexible. It shoud have a higher share of key presses.
7.  For the other fingers, Index > Ring >> Pinky
8.  Since the Index finger operates 2 columns of keys care should be taken so that it doesn't get over loaded with too many common keys.  For total frequency of keys pressed, we should have Middle > Index > Ring >> Pinky

### Character assignment

1.  Preferred positions are given to keys with higher frequency.
2.  Bigrams should be easy to type. They should either:
    1.  be on one row with an out-to-in finger roll
    2.  be on different hands
3.  do not seek to preserve z x c v positions. The editing functions (undo, cut, copy, paste) can be assigned to the same keys separately if needed.

### Guiding principles for ease of qwerty (or any) transition

1.  If a key has to be moved, same position > same finger > same hand > different hand. ( '>' means 'preferable to' )
2.  Preserve common bigram positions if possible.
3.  Qwerty transitions are designed step-wise, so that a user may does not experience a sudden drop in typing speed.
4.  Qwerty transitions steps are designed in decreasing order of impact so that a user may decide to stop at any step and still gain maximum benefit.

I believe #2 above is what differentiates my layout from other qwerty like ones.

## Transition steps

Before we actually begin changing qwerty, let us note a few problems with qwerty. They have been extensively documented elsewhere, so I shall not attempt to be exhaustive.

### Step 0: qwerty analysis

![00 QWER positions](/assets/img/qwerty-alternate/00-qwer-positions.jpg)

![00 qwer change](/assets/img/qwerty-alternate/00-qwer-change.jpg)

1.  The frequency of usage of each row is given in the middle of the first table. The frequency of usage of each side of the row is given at the outer peripheries of the same table.
2.  The top row lists the frequency of the fingers in green.
3.  The top row lists the frequency of each hand in peach.
4.  I have not considered any weightage for punctuation. While , and . weigh in at more than 1% (more than x j z q k), they are almost always followed by a space and that behaviour makes them very different from the alphabet keys. The same behaviour is seen for ; and / although their weighatages are much lower. For these reasons they have been given a 0 weightage here.
5.  Home keys are marked in light blue. Easy to hit keys ( #2 and #3 in key preferences) are marked in a darker blue and hard keys (#4 and #5 in key preferences) are marked in marked in yellow.
6.  The bottom table lists the home, easy and hard key frequency of each hand.

#### Observations

1.  Hard positions have a substantial weightage. T (second most common) and N ( 6th most common ) are located in hard positions. The theoretical limit for the hard positions i.e bottom 10 characters is around 4%. Instead it is at 29% so there is massive scope for improvement here.
2.  Home positions are underutilized. One would expect them to be occupied by the top 8 keys - instead two of those positions (J and K) are occupied by the bottom 5 alphabetic keys. The theoretical limit for the home positions is 58.3%. Instead it is at 27% so there is lot of scope for improvement here as well.
3.  Certain commonly used non alphabet keys like backspace and Enter don't feature here at all and can only be accessed by a sustantial stretch of the Pinky. Instead we have rarely used keys like ; and /.
4.  The right hand is over utilized at 59% even though most people are right handed. This is not terrible, since the right hand is also used to handle the mouse. But a lot of intense work is more efficient when one uses the keyboard exclusively so I would be more comfortable if this ratio were closer to 50%
5.  The distribution of the workload amongst the fingers is very suboptimal.
    1.  The index fingers are overloaded. Not only to they have to deal with double the number of keys as compared to other fingers, but they are also used the most often. This gives a hunt and peck feeling even to touch typists. Try typing hymn on a qwerty and you'll understand.
    2.  The right finger is used more often than the right middle finger.

We now move on to changing the qwerty layout.

### Step 1: T H transition

T, the second most common character is in a hard position, so we need to move it to a better place. The same applies to H.

These are the changes:

1.  T and K exchange positions getting T into a home position
2.  H and J exchange positions getting H into a home position
3.  Substitute 'Enter' for ';' and 'Backspace' for '/'. The special characters are moved to another layer as descibed in another [post](http://mull.in/2018/03/25/keyboard-improvement-3-layers/). I don't give them a weightage since usage can vary widely depending on the user and on context. We just try to give them places that are easy to access.

![01 th positions](/assets/img/qwerty-alternate/01-th-positions.jpg)

![01 th analysis](/assets/img/qwerty-alternate/01-th-analysis.jpg)

I have introduced a new table that shows the number of characters that have changed poisitions on the same finger (the easiest change), fingers on the same hand (more difficult) or different hands (the most difficult change). We will be monitoring this at every step from now on.

This is the most difficult step I am going to propose, but it also has the maximum impact.

#### Impact**

1.  We have exchanged 2 high value keys in home positions for very low value ones. Note the massive jump in home position frequency.
2.  Right and left hand distribution is nearly even now.
3.  The right middle finger has a much higher role to play - although it is still not the most used right finger.
4.  'T' changing hands is difficult to get used to. But, that is compensated (once you get used to it) by
    1.  ease of hitting 'T' - accessed by the strongest finger.
    2.  ease of hitting the most common english bigram - 'TH' - with arguably the easiest 2 finger roll on the board. 2.7% of all 2 letter combinations typed in English are 'th'.
5.  Enter is now hit using the same finger as before (pinky) but is now much easier to access. It also matches the positions I use in all other layers.

The below tables lists all the bigrams that have a weightage greater than 1% . We will be using this later as well.

<table style="height:66px;" width="678">

<tbody>

<tr>

<td width="38">TH</td>

<td width="38">HE</td>

<td width="38">IN</td>

<td width="38">ER</td>

<td width="38">AN</td>

<td width="38">RE</td>

<td width="38">ES</td>

<td width="38">ON</td>

<td width="38">ST</td>

</tr>

<tr>

<td>2.7%</td>

<td>2.3%</td>

<td>2.0%</td>

<td>1.8%</td>

<td>1.6%</td>

<td>1.4%</td>

<td>1.3%</td>

<td>1.3%</td>

<td>1.2%</td>

</tr>

</tbody>

</table>

<table width="304">

<tbody>

<tr>

<td width="38">NT</td>

<td width="38">EN</td>

<td width="38">AT</td>

<td width="38">ED</td>

<td width="38">ND</td>

<td width="38">TO</td>

<td width="38">OR</td>

<td width="38">EA</td>

</tr>

<tr>

<td>1.2%</td>

<td>1.1%</td>

<td>1.1%</td>

<td>1.1%</td>

<td>1.1%</td>

<td>1.1%</td>

<td>1.1%</td>

<td>1.0%</td>

</tr>

</tbody>

</table>

### Step 2: N transition

N, the 6th most common character is in a hard position so we need to move it.

N and U exchange positions getting N, into an easy position. The resuting NIO configuration on the top row is one of the most commonly suggested qwerty modification.

![02 n position](/assets/img/qwerty-alternate/02-n-position.jpg)

![02 n analysis](/assets/img/qwerty-alternate/02-n-analysis.jpg)

#### **Impact:**

1.  The hard positions now have no high value characters on them.
2.  Common bigrams ON  and IN now are easy 2 finger rolls

### Step 3: E R transition

E and D exchange positions; R and F exchange positons.

![03 er position](/assets/img/qwerty-alternate/03-er-position.jpg)

![03 er analysis](/assets/img/qwerty-alternate/03-er-analysis.jpg)

#### Impact:

1.  The home position frequency has improved. The most common alphabet, E is on the strongest finger (albeit on the left hand) in home position.
2.  ES bigram (#7) is easier to hit than before.
3.  E and R preserve their relative positions. This is important because ER and RE are ranked #3 and #5.

### Step 4: LIO Transition

Note that while H-T-L makes a pretty good home row configuration with a weightage of 18%, the N-I-O configuration located right above it has a higher weightage of 22%. So, we exchange positions of the 3 key configurations. Since T H and N are already at new positions, I call this the LIO step.

![04 lio position](/assets/img/qwerty-alternate/04-lio-position.jpg)

![04 lio analysis](/assets/img/qwerty-alternate/04-lio-analysis.jpg)

#### **Impact:**

1.  Home positions have more weightage
2.  While TH bigram is a little more difficult to hit than before, but ON and IN are a little easier and they more than make up for the loss.

Note that at this point while 13 keys have changed positions, only 2 have changed hands, and one of them (K) has a small weightage 0.8%. The other 11 changes actually use the same fingers as qwerty.

In other words, if you have managed to get through to step 1, you should be able to breeze through till step 4\. I'd recommend giving step 5 a shot before reverting to step 4 if it you find that too uncomfortable.

### Step 5: U P transition

U and ',' exchange positions. P and '.' exchange positions.

![05 up position](/assets/img/qwerty-alternate/05-up-position.jpg)

![05 up analysis](/assets/img/qwerty-alternate/05-up-analysis.jpg)

#### Impact:

1.  On the right side, the hard positions are pretty much as low as it can go without keys changing hands.

### Step 6: C G transition

We have spent most of time with the right side, and optimization of that is nearly complete, so let us take a look at the present configuration on the left side. The below table are a repeat of step 5

![05 up position](/assets/img/qwerty-alternate/05-up-position.jpg)

Note that G is the most common key in the 'hard' position and there are 2 characters W and X that are less common in easy positions. X is a very rarely used key.

Also note that C is an outlier in the bottom row. The others in this row are significantly rarer. In the section on Key preferences, we noted that the top row is preferable to the bottom row. So, we do the following:

1.  Move C to the top row in place of W
2.  Move W to the bottom row in place of X
3.  Move X to G
4.  Move G to C

![06 cg position](/assets/img/qwerty-alternate/06-cg-position.jpg)

![06 cg analysis](/assets/img/qwerty-alternate/06-cg-analysis2.jpg)

### Recommended Exit:

Step 6 forms a good exit point for this layout optimization.

Step 1, and in that, the movement of T is the only substantial change from qwerty. I expect most people to breeze through between steps 2 and 4, but with good reward, before encountering a litte bit of resistance at step 5 and 6.

Note that most of left side of the keyboard is nearly unchanged. until step 5\. At step 5, T has been moved out, and ER have exchanged positions with DF (but the latter will feel very natural once you have tried it).

Most of you will find the effort-reward ratio descreasing after this. You might also find some steps subjective to my use case. I am a professional data and business analyst, and an amatuer developer - so I spend most of my time in spreadsheets, sql IDEs and text editors meant for coding (like [Atom](https://atom.io/)).

If you are exiting at this point, I recommend you take a look at Step 9 that deals with the backspace key before you go.

### Step 7: B transition

Note that B has a higher frequency than V, which is right next to it. The numbers seem small in absolute terms, but once you see that B is 45% more common than V, it makes sense to switch the two characters.

![07 b position](/assets/img/qwerty-alternate/07-b-position.jpg)

![07 b analysis](/assets/img/qwerty-alternate/07-b-analysis.jpg)

### Step 8: V transition

In the section on key preferences, we noted that the presnt position of K and X are easier to approach than V. Since V has a higher frequency and X has a very low frequency, we:

1.  Move V to the top of that column
2.  move K to the middle of that column
3.  move X to the bottom of that column

![08 v position.JPG](/assets/img/qwerty-alternate/08-v-position.jpg)

![08 v analysis](/assets/img/qwerty-alternate/08-v-analysis.jpg)

Note that every key we are moving in this step has already moved before, so one can combine this with the previous step without much incremental effort.

### Step 9: better backspace and J-K proximity

Backspace is used too often for it to be relegated to the most difficult position to reach on the board, so we try to move it to a better place. In many places, especially in web apps, J and K are frequently used as keyboard shortcuts for down and up, so we try to keep them together as a pair. To achieve both, we:

1.  move backspace to where J is
2.  move J to where X is (right under K, so side change)
3.  move X to where Z is
4.  move Z to where ',' is (side change)
5.  move ',' to where backspace was

Step 4 and 5 exist because I chose to retain X on the same side of the board (albeit activated by a different finger) because it is used quite often as a variable in programming.

![09 jbs position](/assets/img/qwerty-alternate/09-jbs-position.jpg)

![09 jbs analysis](/assets/img/qwerty-alternate/09-jbs-analysis.jpg)

K-J now form a nice up-down pair like their functions, and backspace is in the positions it occupies on all my [layers](http://mull.in/2018/03/25/keyboard-improvement-3-layers/).

### Step 10: ',' transition

Sometimes, while editing spreadsheets, I find myself with my right hand on the mouse needing to hit comma. So, I move the comma to the left side in place of Q to enable this.

![10 comma position](/assets/img/qwerty-alternate/10-comma-position1.jpg)

![10 comma analysis.JPG](/assets/img/qwerty-alternate/10-comma-analysis2.jpg)

###  Step 11: VY exchange

The VE and EV bigrams constitute 43% of V bigram usage in English. With the present layout that is quite difficult to hit since striking V will take the middle finger off E for many people. Y bigrams favour the left side of the keyboard too, but not by much. So I chose to exchage their positions.

![11 vy position](/assets/img/qwerty-alternate/11-vy-position.jpg)

![11 vy analysis](/assets/img/qwerty-alternate/11-vy-analysis.jpg)

## Conclusion

The board looks very close to optimal now on all these factors:

1.  key preferences:  7 home keys (not counting Enter) contribute to 56% of the key hits, and the eight 'hard' positions (not counting the comma and full stop) contribute only 4.2% of the key hits.
2.  finger distribution: On both hands frequency of middle finger > index > ring > pinky
3.  bigrams: many common bigrams have become much easier than before.

But other alternate layouts have great optimizations too - some much better than mine. A primary motivation for this layout was ease of moving to it - both because it tries to preserve qwerty similarity, and because it proceeds from qwerty in a step wise manner.

Unfortunately I cannot measure the former. My orignal intention was to go through the transition step wise, but in deciding the steps, they got baked into my brain. I found myself automatically jumping ahead without any intention to do so. So I just switched straight to step 11.

I can provide an indicator to how easy it might be to shift to this layout eventually though. I was around 55 wpm before I switched - after 2 weeks with this new layout, I am arount 33 wpm, and managing 43+ when I am not tired.

I think most people would be able to switch faster. I tried a couple of very different layouts before this and they have muddled me up a bit. I find myself hitting a key character in the qwerty position, then in a position on one of the two other layouts I tried before hitting it correctly.

My progress over these three layouts also hints that switching to this layout should be easy.

![graph.jpg](/assets/img/qwerty-alternate/graph.jpg)

Layout3 is what I have described in this post. Layout1 was built from scratch, layout 2 was a qwerty like layout with an ASET configuration on the left side. Notice how quickly my speed starts moving up on layout3\. While I didn't try layout1 outside of typing tests, I have approximately the same amount of practice on layout3 as today as I did on layout2 when I switched to layout3\. I believe this is primarily because I chose to preserve the A-S-E-R configuration on the left side, while moving T over to the other side.

## The name

I like the name Alt-thern because it derives most of its benefit from alternate positions of T H E R N keys in the qwerty layout. I have an [amatuerish interest](http://mull.in/2017/06/10/en1glix/) in linguistics and I like how the l - t - th consonant cluster flirts with unpronouncability for most English speakers without actually going over the edge.

Also, this is not just an alternate layout, it is an altthernate layout. Get it? No?

I am also considering calling it the degrees layout. DEG and RES intersect at 90 degrees on the left side of the keyboard at the end of step 6 (which is the recommended exit point). Also, it varies from the qwerty layout in degrees.

For now though, I remain partial to Altthern.

In a subsequent post, I will describe why I chose not to go for some obvious strategies - such as putting T on the right pinky and getting even more keys on the home row.