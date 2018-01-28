# Seal: Examining Member Education Numbers

## Preface
The numbers in here are JUST FOR MEMES and are very inaccurate. Please take up all complaints with SteveyRuggles. 

## Introduction
What follows in this illustrious, peer-reviewed document is a study of each member of the SEAL discord, and a ranking of smartness, calcuated using an approximation of their reading levels based on how well they write.

## Methods
First, a dump of all messages on the SEAL Discord was created using Kaede-Bot. This dump was created on 1/21/2018, so all messages after that were not taken into account (sorry ryrk).

This dump was parsed, and for each message a user sent, a Flesch-Kincaid grade level was calulated. Before a message is processed, the program removed all emojis (custom and unicode) and web links.

This is an approximation of what grade a person would need to be in to read the text.
The Flesch-Kincaid score is based on 2 factors: sentence length and average syllables per word. Syllables per word was calculated, in this case, using a varient of the algorithm used to determine
placement of hyphens in LaTeX documents when words must be split accross lines.

Once all a user's messages have been processed, the upper and lower 25% of that users scores are discarded, and the rest are averaged.
This hopefully accounts for various mispellings and made up words the user has written.

## Results
The full results can be found [here](../master/reading_level_resources/gradelevels.txt).

**Top 5:**

User | Grade Level 
---------|---------
Too_Much_Cheeze | 14.7 
COMCAST SUPREME | 13.1
Wolf | 11.9 
sT.Pain | 8.8
Wyvern | 8.4

**Bottom 9:**

User | Grade Level 
---------|---------
Xelfer the Boulder | -3.5 
arex | -3.5
Took | -3.5 
Snuggles | -3.5
chance | -3.5
Poxie | -3.5
StarEnd | -3.5
!Jake | -3.5
Abober | -3.5

## Analysis
The bottom 9 here are interesting because it is a 9 way tie for least educated SEALer. However, this -3.5 is the theoretical minimum the algorithm predicts, so it is not that suprising. We can just assume that these 9 are actually retarded.

The Top 5, however, are suprising. I would have expected a Danny or a Krenn up there, as their messages seem to be reasonable and well thought out.
Instead, we see the moving and eloquent single message from Too_Much_Cheeze, "hello everyone" bringing home the top spot. What a wonderful and heartfelt message to our community.

Plotting the Messages Sent vs the Grade Level of the sender, we see:

![nothing](../master/reading_level_resources/chart1.png "Chart 1")

Nothing really. The only real thing of interest is that taking a look at the person with the most messages, we see that quality, in fact, is not over quantity. That person, of course, is Potato Farmer.

*However*, if we look at only the users that have sent less than 5000 messages, we see:


![nothing](../master/reading_level_resources/chart2.png "Chart 2")

...still nothing.

## Conclusion
This whole thing was a major waste of time. I would like to try other metrics to determine intelect, but as of now, I have nothing good to present.

If one thing was to be learned from this experiment, it was that, in fact, **the average SEALer is *not* smarter than a fifth grader**.