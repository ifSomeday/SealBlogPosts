# Perusal into Emoji Numbers: an Investigation in SEAL

by Will

## Introduction

This post was inspired by an offhand comment by Spence Dotes a couple weeks ago, where he postulated that the most commonly used emoji in SEAL was :blobwave:.

![The original hypothesis](/emoji_count_resources/spence_dotes_guess.png)

I finally got bored enough to see if this was actually the case


## The Data

All the messages in the SEAL discord were parsed, with the exception of those in the *shadow council*. Messages were parsed for unicode and custom emojis,
from both the mesasge content itself, and the reactions. In the raw data, available in `/emoji_count_resources`, *most* emoji have been translated into descriptive
text (I.E. `:smiling_face_with_open_mouth:`). Some emoji, such as the the letter emoji, were not translated due to library limitations.

**Total messages processed:** 298833

*messages were processed 11/16/2017*

Content type | Emoji Count
--------|--------
Unicode in message body | 14848
Custom in message body | 12549
Total in message body | 27397
Unicode in reactions | 6302
Custom in reactions | 7403
Total in reactions | 13705
**Grand total** | 41102

## Analysis

For a league whose mission statement includes "Be a part of the memes / bE a PaRt Of tHE mEMeS", only having an average of 0.09 emoji in the body of each message sent seems like a failure.

### Message Body

**Top 5 Emoji in Message Body:**

Emoji| Count
--------|-------
snake | 1572
fire | 1459
thinking face | 1199
middle finger | 616
clapping hands | 552

Already Spence Dote's prediction is not looking good. :blobwave: is not even in the top 5 emojis used in message bodies. Here fierysnake wins out.
The appearance of :thinking_face: is not suprising either, seeing as there are large numbers of Goons in the SEAL discord. Also of note is the fact that there
are over 900 emojis that have been used less than 10 times, with over 400 only being used once

### Reactions

**Top 5 Emoji in Reactions:**

Emoji| Count
--------|-------
monkaS | 1147
yea | 769
speech balloon | 687
panda face | 580
clapping hands | 294

Spence Dote's predicition is officially blown out of the water at this point. :blob_wave: does not show up at all in either top 5. I am suprised that
monkaS wins out for most common reactions; I would have thought :middle_finger: would be on top. Note 2 seperate :middle_fingers: show up on this ranking,
with one in 6th with 284 uses and one in 10th with 194 uses. Combining these two seperate emojis results in a total use of 478 times, which would put 
it in 5th place, beating out :clapping_hands:. I was not sure if I should leave speech balloon in here because it is essentially a bot command,
but after much internal debate I decided it should stay. By this, of course, I mean that I was just lazy.

### Totals

**Top 5 Total Emoji:**

Emoji| Count
--------|-------
snake | 1612
fire | 1564
monkaS | 1449
thinking face | 1289
panda face | 1097

These results closely mirror the top rankings from the individual categories, nothing really new and interesting here. However, in an effort to spice things
up, I attempted to add an unlabeled pie chart with a second pie chart exploding out of its asshole.

![Pie Chart](/emoji_count_resources/game_changing_chart.png)

## Wrap up

Spence Dotes was left. People need to use more emojis. Maybe someday I will redo this and compare results over time, but that requires actually dealing 
with time frames and that is not something I enjoy doing

