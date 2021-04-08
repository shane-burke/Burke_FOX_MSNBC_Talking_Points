## Shane Burke
## Classifying Fox News and MSNBC Talking Points

## Background
Political polarization has been on the rise in the U.S. in recent years. It has impacted our elections and political movements. 

One reason for differing political opinions and priorities might be the news you watch. Millions of Americans tune into channels like Fox, with a right slant, and MSNBC, with a left slant every day. The two cover the same news, though the scripts are drastically different. In the same night, they might cover entirely different news events and sound off on separate hot topics. Even when covering the same event, the language used can differ drastically. This all sets the agenda for what its viewers should watch. 

These viewers are also attracted to these channels because they confirm existing opinions, but the feedback loop can bring them further from the center, and sometimes, from truth.

## The project
I pulled 200 pages of transcripts from each of MSNBC and Fox’s evening news shows across the month of March. This amounted to about 12 hour-long shows from each channel. I split the text by line and cleaned it with RegEx. Then I ran a classifier to see which words were most common for each channel’s coverage.

## Findings
Fox News shows are more likely to speak about the border, Andrew Cuomo, masks, China, and immigration. This checks out — these are the talking points you’ll hear their viewers espousing.

MSNBC shows are more likely to speak about infrastructure, justice, Matt Gaetz, and Georgia. 

Through my classifier and findings, it shows that Fox News lines are more likely to identify. It doesn’t often predict an MSNBC line to be Fox, but can’t always tell on some of Fox’s more generic lines.
